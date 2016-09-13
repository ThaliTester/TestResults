#### Test 83627337ae40023_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-13 22:55:00.082  1586  1586 I [SystemUI]Clock: called onTimeUpdated()
09-13 22:55:00.091  1586  1586 I LgeClockWidgetControlView: called onTimeUpdated()
09-13 22:55:00.091  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
09-13 22:55:00.093  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
09-13 22:55:00.095  1586  1586 D KeyguardUpdateMonitor: handleTimeUpdate
,09-13 22:55:09.056  6789  6789 D AndroidRuntime: 
09-13 22:55:09.056  6789  6789 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-13 22:55:09.063  6789  6789 D AndroidRuntime: CheckJNI is OFF
09-13 22:55:09.264  6789  6789 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-13 22:55:09.275  1035  1597 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 22:55:09.291  1926  2521 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-13 22:55:09.297  1035  1597 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-13 22:55:09.299  1035  1597 D ActivityManager: setTaskToReturnTo : TaskRecord{254a5e46 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-13 22:55:09.299  1035  1597 D ActivityManager: setTaskToReturnTo : TaskRecord{254a5e46 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-13 22:55:09.301  1035  1597 D WindowStateEx: AppWindowTokenEx init.. 
09-13 22:55:09.302   338   351 E GBMv2   : DFP En is all cleared set to be enabled
09-13 22:55:09.329  1035  1597 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6804 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-13 22:55:09.330  6789  6789 D AndroidRuntime: Shutting down VM
09-13 22:55:09.383  1926  1941 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-13 22:55:09.383  1926  1941 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1ed89e7d co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-13 22:55:09.384  1926  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-13 22:55:09.384  1926  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3433c172 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
,09-13 22:55:09.474  6804  6804 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-13 22:55:09.582  6804  6804 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-13 22:55:09.593  6804  6804 I LibraryLoader: Loading: webviewchromium
09-13 22:55:09.596  6804  6804 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 5863-5867)
,09-13 22:55:09.597  6804  6804 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 22:55:09.615  6804  6804 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {14363a33}
,09-13 22:55:09.617  6804  6804 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 22:55:09.617  6804  6804 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 22:55:09.633  6804  6804 I BrowserStartupController: Initializing chromium process, renderers=0
,09-13 22:55:09.634  6804  6804 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 22:55:09.651  6804  6804 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-13 22:55:09.652  6804  6804 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=33 off=46780 len=2953
,09-13 22:55:09.652  6804  6804 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:34 off:229536 len:643667
09-13 22:55:09.659   320  1365 V AudioPolicyService: registerClient() client 0xb558a720, uid 10118
09-13 22:55:09.664  1035  1117 D BluetoothManagerService: Message: 20
09-13 22:55:09.664  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a698a0:true
,09-13 22:55:09.671  6804  6804 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 22:55:09.671  6804  6804 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 22:55:09.671  6804  6804 I Adreno-EGL: Build Date: 12/12/14 금
09-13 22:55:09.671  6804  6804 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 22:55:09.671  6804  6804 I Adreno-EGL: Remote Branch: 
09-13 22:55:09.671  6804  6804 I Adreno-EGL: Local Patches: 
09-13 22:55:09.671  6804  6804 I Adreno-EGL: Reconstruct Branch: 
09-13 22:55:09.764  6804  6844 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-13 22:55:09.769  6804  6804 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-13 22:55:09.788  6804  6804 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 22:55:09.795  6804  6804 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-13 22:55:09.798  6804  6804 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-13 22:55:09.801  6804  6804 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-13 22:55:09.801  6804  6804 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,09-13 22:55:09.815  6804  6804 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
09-13 22:55:09.821  6804  6804 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 22:55:09.821  6804  6804 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 22:55:09.857  6804  6860 D OpenGLRenderer: Render dirty regions requested: true
09-13 22:55:09.857  6804  6860 I OpenGLRenderer: Initialized EGL, version 1.4
09-13 22:55:09.863  6804  6860 D OpenGLRenderer: Enabling debug mode 0
09-13 22:55:09.871  6804  6804 D Atlas   : Validating map...
,09-13 22:55:09.877  1035  1971 D SplitWindow: check instance of lgWin Window{2e94b7da u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-13 22:55:09.882  1035  1113 W ActivityManager: Activity pause timeout for ActivityRecord{3987a807 u0 com.test.thalitest/.MainActivity t6}
,09-13 22:55:09.943  6804  6858 D LgDataFeature: LgDataFeature() Constructor: none
09-13 22:55:09.943  6804  6858 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 22:55:09.981  1035  1118 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +599ms (total +678ms)
09-13 22:55:09.981  6804  6804 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2656829e time:166252
09-13 22:55:09.982  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3987a807 u0 com.test.thalitest/.MainActivity t6} time:166253
,09-13 22:55:10.172  6804  6804 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 22:55:10.240  6804  6858 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-13 22:55:10.240  6804  6858 I chromium: 
,09-13 22:55:10.366  6804  6870 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435056640
,09-13 22:55:10.379  6804  6870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 22:55:10.379  6804  6870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 22:55:10.379  6804  6870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 22:55:10.379  6804  6870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 22:55:10.379  6804  6870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-13 22:55:10.380  6804  6870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e336502 added. We now have 1 listener(s)
,09-13 22:55:10.386  1035  1925 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 22:55:10.389  6804  6870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-13 22:55:10.392  6804  6870 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 22:55:10.394  6804  6870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 22:55:10.395  6804  6870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 22:55:10.403  6804  6804 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-13 22:55:10.403  6804  6804 I chromium: 
09-13 22:55:10.410  6804  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 22:55:10.410  6804  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 22:55:10.410  6804  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 22:55:10.410  6804  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-13 22:55:10.410  6804  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 22:55:10.410  6804  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 22:55:10.410  6804  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 22:55:10.410  6804  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 22:55:10.410  6804  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 22:55:10.410  6804  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 22:55:10.410  6804  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 22:55:10.410  6804  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 22:55:10.410  6804  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 22:55:10.410  6804  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 22:55:10.411  6804  6870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21820a49 added. We now have 1 listener(s)
09-13 22:55:10.411  6804  6870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 22:55:10.416  1035  1528 D WifiService: New client listening to asynchronous messages
,09-13 22:55:10.420  6804  6870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 22:55:10.420  6804  6870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-13 22:55:10.421  6804  6870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 22:55:10.421  6804  6870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 22:55:10.421  6804  6870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-13 22:55:10.425  6804  6870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 22:55:10.427  1035  2016 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 22:55:10.428  6804  6870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-13 22:55:10.437  6804  6870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-13 22:55:10.438  6804  6870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 22:55:10.438  6804  6870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:10.438  6804  6870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:10.438  6804  6870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:10.438  6804  6870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:10.438  6804  6870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:10.438  6804  6870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:55:10.438  6804  6870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 22:55:10.438  6804  6870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 22:55:10.438  6804  6870 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 22:55:10.442  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:10.445  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:10.445  6804  6870 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 22:55:10.492  6804  6804 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 22:55:10.541   338   353 E GBMv2   : DFP En is all cleared set to be enabled
09-13 22:55:10.541   338   353 E GBMv2   : Set value is all cleared set the max
09-13 22:55:10.541   338   353 I GBMv2   : DFP Enabled. Ignore VFP set
,09-13 22:55:11.462  6804  6873 W jxcore-log: Initializing JXcore engine
09-13 22:55:11.462  6804  6873 W jxcore-log: JXcore engine is ready
,09-13 22:55:11.536  6873  6873 W Thread-806: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7595]" dev="sockfs" ino=7595 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-13 22:55:11.536  6873  6873 W Thread-806: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3271 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-13 22:55:11.536  6873  6873 W Thread-806: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10241]" dev="sockfs" ino=10241 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-13 22:55:11.536  6873  6873 W Thread-806: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-13 22:55:11.536  6873  6873 W Thread-806: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[32981]" dev="sockfs" ino=32981 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,09-13 22:55:11.567  6804  6873 W jxcore-log: Starting JXcore engine
,09-13 22:55:11.718  6804  6873 W jxcore-log: Platform android
09-13 22:55:11.718  6804  6873 W jxcore-log: 
09-13 22:55:11.718  6804  6873 W jxcore-log: Process ARCH arm
09-13 22:55:11.718  6804  6873 W jxcore-log: 
,09-13 22:55:12.104  6804  6873 I jxcore-log: JXcore Cordova bridge is ready!
09-13 22:55:12.104  6804  6873 I jxcore-log: 
,09-13 22:55:12.104  6804  6873 W jxcore-log: JXcore engine is started
,09-13 22:55:12.114  6804  6870 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-13 22:55:12.120  6804  6804 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 22:55:25.240  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 22:55:25.240  6804  6873 I jxcore-log: 
,09-13 22:55:25.243  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 22:55:25.243  6804  6873 I jxcore-log: 
09-13 22:55:25.248  6804  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 22:55:25.248  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:25.248  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:25.248  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:25.248  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:25.248  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:25.248  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:55:25.248  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 22:55:25.250  6804  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:25.252  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 22:55:25.252  6804  6873 I jxcore-log: 
,09-13 22:55:25.254  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 22:55:25.254  6804  6873 I jxcore-log: 
,09-13 22:55:25.753  6804  6873 I jxcore-log: Unit Test app is loaded
09-13 22:55:25.753  6804  6873 I jxcore-log: 
,09-13 22:55:25.762  6804  6804 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-13 22:55:25.771  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:55:25.771  6804  6873 I jxcore-log: 
09-13 22:55:25.784  6804  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 22:55:25.785  6804  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@209675ee added. We now have 2 listener(s)
,09-13 22:55:25.785  1035  1979 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 22:55:25.787  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 22:55:25.787  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 22:55:25.787  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 22:55:25.787  6804  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 22:55:25.787  6804  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c12ea8f added. We now have 2 listener(s)
09-13 22:55:25.787  6804  6873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 22:55:25.787  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 22:55:25.789  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 22:55:25.791  6804  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 22:55:25.791  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:25.791  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:25.791  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:25.791  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:25.791  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:25.791  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:55:25.791  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 22:55:25.793  6804  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:25.793  6804  6873 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 22:55:25.794  6804  6873 D ExecuteNativeTests: Running unit tests
09-13 22:55:25.794  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:25.795  6804  6873 D BluetoothAdapter: enable(): BT is already enabled..!
,09-13 22:55:25.797  1035  1560 D WifiServiceImplEx: setWifiEnabled: true pid=6804, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 22:55:25.798  1035  1560 D WifiService: setWifiEnabled: true pid=6804, uid=10118
09-13 22:55:25.798  1035  1560 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 22:55:25.798  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:25.800  6804  6873 I System.out: Running UT
09-13 22:55:35.960  6804  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 22:55:35.960  6804  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd6cd95 added. We now have 3 listener(s)
,09-13 22:55:35.963  1035  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 22:55:35.966  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 22:55:35.966  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 22:55:35.966  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 22:55:35.966  6804  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 22:55:35.966  6804  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571eaa added. We now have 3 listener(s)
09-13 22:55:35.966  6804  6873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 22:55:35.967  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 22:55:35.970  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 22:55:35.974  6804  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 22:55:35.974  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:35.974  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:35.974  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:35.974  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:35.974  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:35.974  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:55:35.974  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 22:55:35.978  6804  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:35.978  6804  6873 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 22:55:35.980  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:35.981  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:35.988  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 22:55:35.993  6804  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 22:55:35.993  6804  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 22:55:35.993  6804  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 22:55:35.997  6804  6873 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-13 22:55:35.998  6804  6873 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 22:55:35.998  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 22:55:35.998  6804  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 22:55:35.998  6804  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 22:55:35.998  6804  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 22:55:36.000  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:55:36.000  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.000  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 22:55:36.000  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 22:55:36.000  6804  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd6cd95 removed from the list
09-13 22:55:36.001  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:55:36.001  6804  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571eaa removed from the list
09-13 22:55:36.001  6804  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:55:36.001  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 22:55:36.009  6804  6873 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-13 22:55:36.010  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:55:36.010  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.010  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.010  6804  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd6cd95 not in the list
09-13 22:55:36.010  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:55:36.010  6804  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571eaa not in the list
09-13 22:55:36.011  6804  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:55:36.011  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.011  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.017  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 22:55:36.017  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 22:55:36.017  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 22:55:36.017  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 22:55:36.017  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 22:55:36.017  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 22:55:36.017  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 22:55:36.017  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 22:55:36.017  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 22:55:36.018  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 22:55:36.018  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 22:55:36.018  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 22:55:36.018  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 22:55:36.018  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 22:55:36.018  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 22:55:36.018  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 22:55:36.018  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 22:55:36.018  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 22:55:36.018  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 22:55:36.018  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 22:55:36.018  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 22:55:36.018  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 22:55:36.018  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 22:55:36.018  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 22:55:36.018  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 22:55:36.018  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 22:55:36.018  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 22:55:36.018  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 22:55:36.018  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 22:55:36.018  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 22:55:36.018  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 22:55:36.020  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:55:36.020  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.020  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.020  6804  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd6cd95 not in the list
09-13 22:55:36.020  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:55:36.020  6804  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571eaa not in the list
09-13 22:55:36.020  6804  6873 D io.jxcore.node.ConnectivityMonitor: stop,
09-13 22:55:36.020  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.020  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.021  6804  6873 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-13 22:55:36.031  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 22:55:36.034  6804  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 22:55:36.034  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:36.034  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:36.034  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:36.034  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:36.034  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:36.034  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:55:36.034  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 22:55:36.037  6804  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:36.037  6804  6873 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 22:55:36.039  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:36.041  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:36.042  6804  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 22:55:36.042  6804  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 22:55:36.042  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 22:55:36.042  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 22:55:36.042  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 22:55:36.047  6804  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 22:55:36.049  1035  1766 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 22:55:36.056  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 22:55:36.063  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 22:55:36.067  6804  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-13 22:55:36.069  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 22:55:36.069  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 22:55:36.072  6804  6873 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 22:55:36.073  6804  6873 I io.jxcore.node.ConnectionHelper: start: OK
09-13 22:55:36.075  6804  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-13 22:55:36.075  6804  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 22:55:36.075  6804  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 22:55:36.079  6804  6873 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 22:55:36.079  6804  6873 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-13 22:55:36.079  6804  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 22:55:36.079  6804  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 22:55:36.079  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 22:55:36.079  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 22:55:36.079  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 22:55:36.085  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 22:55:36.085  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 22:55:36.086  6804  6873 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-13 22:55:36.088  6804  6873 I io.jxcore.node.ConnectionHelper: start: OK
09-13 22:55:36.089  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:55:36.090  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.090  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 22:55:36.090  6804  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd6cd95 not in the list
09-13 22:55:36.090  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:55:36.090  6804  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571eaa not in the list
09-13 22:55:36.090  6804  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:55:36.090  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.092  6804  6873 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 22:55:36.094  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 22:55:36.097  6804  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 22:55:36.097  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:36.097  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:36.097  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:36.097  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:36.097  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:36.097  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:55:36.097  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 22:55:36.098  6804  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:36.099  6804  6873 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 22:55:36.103  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:36.105  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:36.105  6804  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 22:55:36.105  6804  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 22:55:36.105  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 22:55:36.105  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 22:55:36.105  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 22:55:36.113  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 22:55:36.115  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 22:55:36.117  6804  6873 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 22:55:36.117  6804  6873 I io.jxcore.node.ConnectionHelper: start: OK
09-13 22:55:36.118  6804  6873 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-13 22:55:36.118  6804  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 22:55:36.118  6804  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 22:55:36.120  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:55:36.120  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.121  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 22:55:36.121  6804  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd6cd95 not in the list
09-13 22:55:36.121  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:55:36.121  6804  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571eaa not in the list
09-13 22:55:36.121  6804  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:55:36.121  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.122  6804  6873 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-13 22:55:36.123  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:55:36.123  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.123  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.123  6804  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd6cd95 not in the list
09-13 22:55:36.123  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:55:36.123  6804  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571eaa not in the list
09-13 22:55:36.123  6804  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:55:36.123  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.123  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.124  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 22:55:36.124  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:55:36.124  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.124  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.124  6804  6873 E org.thaliproject.p2p.btconnectorlib.C,onnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd6cd95 not in the list
09-13 22:55:36.125  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:55:36.125  6804  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571eaa not in the list
09-13 22:55:36.125  6804  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:55:36.125  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.125  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.125  6804  6873 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-13 22:55:36.126  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:55:36.126  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.126  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.126  6804  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd6cd95 not in the list
09-13 22:55:36.126  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:55:36.126  6804  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571eaa not in the list
09-13 22:55:36.126  6804  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:55:36.126  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.126  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.127  6804  6873 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 22:55:36.127  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:55:36.127  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.127  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.127  6804  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd6cd95 not in the list
09-13 22:55:36.127  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:55:36.127  6804  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571eaa not in the list
09-13 22:55:36.127  6804  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:55:36.127  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.127  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.128  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 22:55:36.139  6804  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 22:55:36.139  6804  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 22:55:36.139  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 22:55:36.139  6804  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 22:55:36.139  6804  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 22:55:36.139  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 22:55:36.139  6804  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 22:55:36.140  6804  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 22:55:36.140  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:55:36.140  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.140  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.140  6804  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd6cd95 not in the list
09-13 22:55:36.140  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:55:36.140  6804  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571eaa not in the list
09-13 22:55:36.140  6804  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:55:36.140  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.140  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.142  6804  6873 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 22:55:36.142  6804  6873 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 22:55:36.142  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 22:55:36.146  6804  6873 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 22:55:36.149  6804  6873 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 22:55:36.151  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 22:55:36.151  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 22:55:36.151  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 22:55:36.151  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 22:55:36.151  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 22:55:36.151  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 22:55:36.152  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 22:55:36.152  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 22:55:36.152  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 22:55:36.152  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 22:55:36.152  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 22:55:36.152  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 22:55:36.152  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 22:55:36.152  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 22:55:36.152  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 22:55:36.152  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 22:55:36.153  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 22:55:36.153  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 22:55:36.153  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 22:55:36.153  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 22:55:36.153  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 22:55:36.153  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 22:55:36.153  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 22:55:36.153  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 22:55:36.153  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 22:55:36.153  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 22:55:36.153  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 22:55:36.153  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 22:55:36.153  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 22:55:36.153  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 22:55:36.153  6804  6873 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 22:55:36.154  6804  6873 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 22:55:36.155  6804  6873 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 22:55:36.157  6804  6873 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 22:55:36.157  6804  6873 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 22:55:36.158  6804  6873 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 22:55:36.158  6804  6873 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 22:55:36.158  6804  6873 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 22:55:36.158  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-13 22:55:36.162  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 22:55:36.164  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 22:55:36.164  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 22:55:36.164  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 22:55:36.165  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 22:55:36.165  6804  6873 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 22:55:36.165  6804  6873 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 22:55:36.165  6804  6873 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 22:55:36.165  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:55:36.165  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.165  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.166  6804  6914 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 904)
09-13 22:55:36.169  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 22:55:36.169  6804  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd6cd95 not in the list
09-13 22:55:36.169  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:55:36.169  6804  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571eaa not in the list
09-13 22:55:36.169  6804  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:55:36.170  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.170  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.171  6804  6873 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 22:55:36.171  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:55:36.171  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.171  6804  6915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 904
09-13 22:55:36.171  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.171  6804  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd6cd95 not in the list
09-13 22:55:36.171  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:55:36.171  6804  6915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 904)
09-13 22:55:36.171  6804  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571eaa not in the list
09-13 22:55:36.171  6804  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:55:36.171  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.171  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.171  6804  6915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 904)
09-13 22:55:36.172  6804  6873 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 22:55:36.173  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:55:36.173  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.173  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.173  6804  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd6cd95 not in the list
09-13 22:55:36.173  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:55:36.173  6804  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571eaa not in the list
09-13 22:55:36.173  6804  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:55:36.173  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.173  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.174  6804  6873 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 22:55:36.174  6804  6873 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 22:55:36.174  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 22:55:36.175  6804  6873 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 22:55:36.175  6804  6873 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 22:55:36.175  6804  6873 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 22:55:36.175  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 22:55:36.175  6804  6873 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 22:55:36.175  6804  6873 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 22:55:36.175  6804  6873 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 22:55:36.175  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 22:55:36.175  6804  6873 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 22:55:36.175  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:55:36.175  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.175  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.176  6804  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd6cd95 not in the list
09-13 22:55:36.176  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:55:36.176  6804  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571eaa not in the list
09-13 22:55:36.176  6804  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:55:36.176  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.176  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.178  6804  6873 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 22:55:36.179  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 22:55:36.183  6804  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 22:55:36.183  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:36.183  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:36.183  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:36.183  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:36.183  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:36.183  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:55:36.183  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 22:55:36.190  6804  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:36.190  6804  6873 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 22:55:36.192  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:36.194  6804  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 22:55:36.194  6804  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 22:55:36.194  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 22:55:36.194  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 22:55:36.194  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 22:55:36.194  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:36.199  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 22:55:36.202  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 22:55:36.203  6804  6873 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 22:55:36.203  6804  6873 I io.jxcore.node.ConnectionHelper: start: OK
09-13 22:55:36.203  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:55:36.203  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.203  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 22:55:36.203  6804  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd6cd95 not in the list
09-13 22:55:36.203  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:55:36.203  6804  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571eaa not in the list
09-13 22:55:36.203  6804  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:55:36.204  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.211  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:55:36.211  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.211  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.211  6804  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd6cd95 not in the list
09-13 22:55:36.211  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:55:36.211  6804  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571eaa not in the list
09-13 22:55:36.211  6804  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:55:36.211  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.211  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.213  6804  6873 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 22:55:36.214  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 22:55:36.218  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 22:55:36.219  6804  6873 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 22:55:36.219  6804  6873 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 22:55:36.219  6804  6804 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 22:55:36.220  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 22:55:36.220  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 22:55:36.221  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:55:36.221  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 22:55:36.221  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 22:55:36.221  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 22:55:36.221  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.221  6804  6873 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 22:55:36.221  6804  6804 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 22:55:36.222  6804  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd6cd95 not in the list
09-13 22:55:36.222  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:55:36.222  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 22:55:36.222  6804  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 22:55:36.222  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 22:55:36.223  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 22:55:36.224  6804  6917 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 22:55:36.224  6804  6917 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 22:55:36.226  6804  6873 D BluetoothLeScanner: could not find callback wrapper
09-13 22:55:36.227  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 22:55:36.227  6804  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 22:55:36.227  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.227  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.230  6804  6873 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 22:55:36.231  6804  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 22:55:36.231  6804  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 22:55:36.231  6804  6804 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 22:55:36.231  6804  6804 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 22:55:36.231  6804  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571eaa not in the list
09-13 22:55:36.231  6804  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:55:36.231  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.blueto,oth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.231  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.233  6804  6873 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-13 22:55:36.233  6804  6873 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 22:55:36.233  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 22:55:36.235  6804  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 22:55:36.235  6804  6873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 22:55:36.235  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:55:36.235  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.235  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.235  6804  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd6cd95 not in the list
09-13 22:55:36.236  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:55:36.236  6804  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571eaa not in the list
09-13 22:55:36.236  6804  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:55:36.236  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.236  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.238  1035  1971 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 22:55:36.239  1035  1979 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 22:55:36.242  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 22:55:36.246  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:55:36.246  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.246  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.247  6804  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd6cd95 not in the list
09-13 22:55:36.247  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:55:36.247  6804  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571eaa not in the list
09-13 22:55:36.247  6804  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:55:36.247  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.247  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.249  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:55:36.249  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.249  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.249  6804  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cd6cd95 not in the list
09-13 22:55:36.249  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:55:36.249  6804  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571eaa not in the list
09-13 22:55:36.249  6804  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:55:36.249  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:36.249  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:36.252  6804  6873 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 22:55:36.252  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 22:55:36.252  6804  6873 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 22:55:36.252  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 22:55:36.252  6804  6873 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 22:55:36.252  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 22:55:36.255  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 22:55:36.255  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-13 22:55:36.256  6804  6873 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-13 22:55:36.256  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 22:55:36.256  6804  6873 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-13 22:55:36.256  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 22:55:36.256  6804  6873 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-13 22:55:36.256  6804  6873 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 22:55:36.257  6804  6873 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 22:55:36.257  6804  6873 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-13 22:55:36.258  6804  6873 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 22:55:36.258  6804  6873 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 22:55:36.258  6804  6873 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-13 22:55:36.259  6804  6873 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-13 22:55:36.260  6804  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 22:55:36.260  6804  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d544c50 added. We now have 3 listener(s)
09-13 22:55:36.261  1035  1767 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 22:55:36.263  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 22:55:36.263  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 22:55:36.263  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 22:55:36.264  6804  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 22:55:36.264  6804  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2050e49 added. We now have 3 listener(s)
09-13 22:55:36.264  6804  6873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 22:55:36.264  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 22:55:36.267  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 22:55:36.279  6804  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 22:55:36.279  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:36.279  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:36.279  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:36.279  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:36.279  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:36.279  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:55:36.279  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 22:55:36.281  6804  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:36.281  6804  6873 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 22:55:36.283  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:36.284  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:36.285  6804  6873 D BluetoothAdapter: enable(): BT is already enabled..!
09-13 22:55:36.286  1035  1971 D WifiServiceImplEx: setWifiEnabled: true pid=6804, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 22:55:36.286  1035  1971 D WifiService: setWifiEnabled: true pid=6804, uid=10118
09-13 22:55:36.286  1035  1971 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 22:55:36.296  1035  1560 D WifiServiceImplEx: setWifiEnabled: false pid=6804, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-13 22:55:36.296  1035  1560 D WifiService: setWifiEnabled: false pid=6804, uid=10118
09-13 22:55:36.296  1035  1560 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 22:55:36.307  6804  6914 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-13 22:55:36.307  6804  6914 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 904)
,09-13 22:55:36.313  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 22:55:36.313  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 22:55:36.314  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-13 22:55:36.315  1035  1522 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-13 22:55:36.315  1035  1522 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-13 22:55:36.315  1035  1522 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-13 22:55:36.316  1035  1522 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-13 22:55:36.316  1035  1522 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-13 22:55:36.317  1035  1522 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-13 22:55:36.317  1035  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 22:55:36.317  1035  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 22:55:36.319  1035  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 22:55:36.319  1035  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-13 22:55:36.326  1035  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 22:55:36.326  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 22:55:36.327  1035  1519 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:36.327  1035  1519 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:36.327  2675  2675 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 22:55:36.328  1035  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 22:55:36.328  1035  1522 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 22:55:36.328  1035  1522 D WifiNative-wlan0: SET ps 1: returned true
09-13 22:55:36.329  1035  2809 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:36.329   315   879 D CommandListener: Clearing all IP addresses on wlan0
09-13 22:55:36.354  1035  1924 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,09-13 22:55:36.356  1035  2808 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:36.356  1035  2808 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:36.356  1035  2808 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-13 22:55:36.357  1035  2808 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:36.357  1035  2808 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-13 22:55:36.374   315  6921 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-13 22:55:36.375  1035  2808 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-13 22:55:36.377  1035  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 22:55:36.377  1035  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
09-13 22:55:36.384  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-13 22:55:36.384  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:36.384  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:36.384  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 22:55:36.384  1035  1115 D DSQN    : Dns fail occured do internet check.
09-13 22:55:36.385  1035  1035 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
09-13 22:55:36.385  1035  1035 D DSQN    : try Internet connection check
09-13 22:55:36.388  1926  1926 V WfdStateTracker: handleWifiStateChangedEvent: 0
,09-13 22:55:36.392  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:36.392  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 22:55:36.393  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:36.403  1035  1519 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:36.403  1035  1519 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:36.404  1035  1519 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2032be09
09-13 22:55:36.404  1035  1519 D LGWifiP2pService: P2pDisablingState
09-13 22:55:36.404  1035  1519 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:36.404  1035  1519 D LGWifiP2pService: p2p socket connection lost
09-13 22:55:36.404  1035  1519 D LGWifiP2pService: P2pDisabledState
,09-13 22:55:36.414  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-13 22:55:36.415  1035  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:36.415  1035  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:36.416  1035  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:36.416  1035  1522 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 22:55:36.416  1035  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:36.417  1035  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:36.417  1035  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:36.418  1035  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-13 22:55:36.423  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:36.423  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 22:55:36.425  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:36.426  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:36.426  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 22:55:36.426  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
09-13 22:55:36.427  1035  1540 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:36.427  1035  1035 D RttService: SCAN_AVAILABLE : 1
09-13 22:55:36.427  1035  1541 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 22:55:36.429  1035  1519 D LGWifiP2pService: P2pDisabledState{ when=-11ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:36.429  1035  1519 D LGWifiP2pService: DefaultState{ when=-11ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:36.430  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 22:55:36.430  1926  1926 D WfdsService: WifiP2pState is changed : false
09-13 22:55:36.430  1926  2306 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-13 22:55:36.430  1926  2306 D WfdsService: Set the WFDS Monitor: false
09-13 22:55:36.429  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 22:55:36.431  1926  2306 D WfdsMonitor: WFDS Monitor is stopped
09-13 22:55:36.431  1926  2742 D CtrlSupplicant: Received on exit socket, terminate
09-13 22:55:36.431  1926  2306 D WfdsService: STATE : WfdsDisabledState - enter
09-13 22:55:36.431  1926  2742 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-13 22:55:36.431  1926  2742 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-13 22:55:36.431  1926  2742 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-13 22:55:36.431  1926  2306 W WfdsService: DefaultState - msg [9445378] is not handled
09-13 22:55:36.431  1926  2308 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-13 22:55:36.432  2675  2675 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 22:55:36.432  1035  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 22:55:36.432  1035  1522 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 22:55:36.432  1035  1522 D WifiNative-wlan0: SET ps 1: returned true
,09-13 22:55:36.440  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:36.447  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 22:55:36.460   315   879 D CommandListener: Clearing all IP addresses on wlan0
,09-13 22:55:36.461   315  6939 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-13 22:55:36.461  1035  1529 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-13 22:55:36.461  1035  6929 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
09-13 22:55:36.462  1035  6923 D DSQN    : ThreadInternetCheck internet check NOK 
09-13 22:55:36.462  1035  1529 D DSQN    : disableDataServiceNotify
09-13 22:55:36.462  1035  1529 D DSQN    : stop dsqn bin
09-13 22:55:36.463  1035  1115 D DSQN    : Dns timeout INTERNET_CHECK already in progress ignore!
09-13 22:55:36.464  1035  6923 D DSQN    : L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
09-13 22:55:36.464  1035  6923 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
09-13 22:55:36.469  1035  1529 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-13 22:55:36.469  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:36.469  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 22:55:36.470  1035  1529 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 22:55:36.471  1035  1529 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-13 22:55:36.471  1035  1529 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-13 22:55:36.471  1035  1529 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-13 22:55:36.472  1035  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 22:55:36.472  1035  2808 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:36.472  1035  2808 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:36.472  1035  2808 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-13 22:55:36.473  1586  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-13 22:55:36.501  1035  1998 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6940 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-13 22:55:36.504  1035  1522 D WifiNative-p2p0: doBoolean: TERMINATE
09-13 22:55:36.505  1035  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:36.505  1035  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 22:55:36.505  1035  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 22:55:36.505  1035  1529 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:36.506  1035  1529 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:36.506  1035  1529 D NetworkManagementService: Removing idletimer
09-13 22:55:36.506  1836  1836 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:36.506  1035  1529 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:36.506  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 22:55:36.508  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-13 22:55:36.509  1035  1522 D WifiNative-p2p0: TERMINATE: returned true
09-13 22:55:36.509  1035  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 22:55:36.509  1035  1522 E WifiStateMachine: useWiFiOffloading() : false
09-13 22:55:36.509  1035  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 22:55:36.510  1035  1529 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-13 22:55:36.510  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:36.510  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:36.510  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 22:55:36.510  1035  1518 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,09-13 22:55:36.511  1035  1518 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 22:55:36.512  1035  1522 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:36.512  1035  1522 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 22:55:36.513  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-13 22:55:36.513  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 22:55:36.515  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 22:55:36.515  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 22:55:36.515  1035  1035 D WifiDataContinuityService: L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
,09-13 22:55:36.520  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:36.521  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-13 22:55:36.529  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:36.529  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:36.529  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:36.529  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 22:55:36.529  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:36.529  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:55:36.529  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:55:36.529  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 22:55:36.533  6804  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 22:55:36.534  1926  2521 D WifiServiceExtension: isInternetCheckAvailable return false
09-13 22:55:36.534  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 22:55:36.536  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 22:55:36.536  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 22:55:36.536  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 22:55:36.536  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 22:55:36.536  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 22:55:36.537  1035  2809 D DhcpStateMachine: StoppedState
09-13 22:55:36.537  1035  2809 D DhcpStateMachine: StoppedState{ when=-104ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:36.538  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:36.538  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:36.538  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:36.538  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 22:55:36.538  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:36.538  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:55:36.538  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:55:36.538  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 22:55:36.539  6804  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 22:55:36.541  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
,09-13 22:55:36.542  1035  1522 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
,09-13 22:55:36.543  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:36.543  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:36.543  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:36.543  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 22:55:36.543  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:36.543  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:55:36.543  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:55:36.543  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 22:55:36.543  1035  1522 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-13 22:55:36.544  6804  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 22:55:36.544  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 22:55:36.544  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-13 22:55:36.588  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 22:55:36.589  6940  6940 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 22:55:36.589  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 22:55:36.590  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:36.593  6940  6940 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 22:55:36.593  6940  6940 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 22:55:36.594  2675  2675 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-13 22:55:36.595  2675  2675 I wpa_supplicant: monitor socket send errors count : 1
09-13 22:55:36.595  2675  2675 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1926-2\x00 that cannot receive messages
09-13 22:55:36.596  1035  2736 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-13 22:55:36.596  1035  2736 D WifiMonitor: Dropping event because (p2p0) is stopped
09-13 22:55:36.635  2675  2675 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 22:55:36.636  1035  1924 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6962 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-13 22:55:36.636  1035  1924 I ActivityManager: Killing 6214:com.android.providers.calendar/u0a14 (adj 15): empty #17
09-13 22:55:36.637  1035  1117 D Tethering: InitialState.processMessage what=4
09-13 22:55:36.637  2675  2675 W wpa_supplicant: USIM:  scard_deinit function
09-13 22:55:36.638  1035  2736 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-13 22:55:36.638  1035  2736 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 22:55:36.638  1035  2736 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 22:55:36.639  1035  2736 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-13 22:55:36.639  1035  2736 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,09-13 22:55:36.639  1035  2736 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 22:55:36.639  1035  1522 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=192895
09-13 22:55:36.640  1035  1522 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=192896
09-13 22:55:36.640  1035  1522 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=192896  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 22:55:36.641  1035  1522 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=192897  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 22:55:36.723  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-13 22:55:36.724  1035  1051 W libprocessgroup: failed to open /acct/uid_10014/pid_6214/cgroup.procs: No such file or directory
09-13 22:55:36.732  6804  6804 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-13 22:55:36.733  1035  1522 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-13 22:55:36.734  1035  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-13 22:55:36.751  2675  2675 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-13 22:55:36.752  1035  2736 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-13 22:55:36.752  1035  2736 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-13 22:55:36.753  1035  2736 D WifiMonitor: Disconnecting from the supplicant, no more events
,09-13 22:55:36.756  1035  1522 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
09-13 22:55:36.776  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-13 22:55:36.777  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:36.778  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:36.779  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:36.783  6962  6962 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 22:55:36.783  6962  6962 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-13 22:55:36.784  6962  6962 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 22:55:36.784  6962  6962 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-13 22:55:36.786  6962  6962 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 22:55:36.786  6962  6962 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-13 22:55:36.817  6804  6918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:55:36.824  1035  1924 D WifiServiceImplEx: setWifiEnabled: true pid=6804, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 22:55:36.825  1035  1924 D WifiService: setWifiEnabled: true pid=6804, uid=10118
09-13 22:55:36.825  1035  1924 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 22:55:36.850  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 22:55:36.851  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 22:55:36.851  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-13 22:55:36.860  1926  1926 D WfdsService: Supplicant Connection state is changed : false
09-13 22:55:36.860  1035  1522 D WifiOffDelayIfNotUsed: stopMonitoring
09-13 22:55:36.861  1035  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 22:55:36.861  1035  1522 E WifiStateMachine: useWiFiOffloading() : false
09-13 22:55:36.861  1035  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-13 22:55:36.861  1926  2306 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,09-13 22:55:36.861  1926  2306 D WfdsService: Set the WFDS Monitor: false
09-13 22:55:36.861  1926  2306 D WfdsMonitor: WFDS Monitor is stopped
09-13 22:55:36.864  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-13 22:55:36.865  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 22:55:36.866  1035  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-13 22:55:36.866  1035  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-13 22:55:36.866  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:36.867  2491  2491 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:36.868  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:36.871  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:36.872  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:36.943  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 22:55:36.985  6962  6962 D LgDataFeature: LgDataFeature() Constructor: none
09-13 22:55:36.985  6962  6962 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 22:55:36.998  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:37.064  1035  1522 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,09-13 22:55:37.064  1035  1522 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-13 22:55:37.072  1035  1522 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-13 22:55:37.073  1035  1522 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 22:55:37.073  1035  1522 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-13 22:55:37.073  1035  1522 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 22:55:37.073  1035  1522 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-13 22:55:37.073  1035  1522 E WifiHW  : unknown target_country: EU , set to default
09-13 22:55:37.073  1035  1522 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-13 22:55:37.073  1035  1522 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-13 22:55:37.073  1035  1522 I WifiUtil: gEnableBmps=1
,09-13 22:55:37.078  1035  2034 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6986 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-13 22:55:37.081  1035  2034 I ActivityManager: Killing 6283:com.android.defcontainer/u0a4 (adj 15): empty #17
09-13 22:55:37.130  1035  1051 W libprocessgroup: failed to open /acct/uid_10004/pid_6283/cgroup.procs: No such file or directory
,09-13 22:55:37.162  6986  6986 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-13 22:55:37.189  6986  6986 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-13 22:55:37.228  6986  6986 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-13 22:55:37.228  6986  6986 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-13 22:55:37.229  6986  6986 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-13 22:55:37.229  6986  6986 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
,09-13 22:55:37.229  6986  6986 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,09-13 22:55:37.232  6986  6986 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-13 22:55:37.238  6986  6986 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-13 22:55:37.246  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 22:55:37.251  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 22:55:37.270  6986  6986 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-13 22:55:37.277  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 22:55:37.281  6940  6940 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 22:55:37.281  6940  6940 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 22:55:37.281  6940  6940 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 22:55:37.283  6986  6986 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-13 22:55:37.287  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 22:55:37.289  6986  6986 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-13 22:55:37.296  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:37.305  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 22:55:37.305  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 22:55:37.308  6986  6986 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 22:55:37.311  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 22:55:37.316  6940  6940 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 22:55:37.316  6940  6940 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 22:55:37.317  6940  6940 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 22:55:37.323  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 22:55:37.332  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:37.343  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 22:55:37.344  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 22:55:37.347  6986  6986 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-13 22:55:37.428  1035  1943 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7006 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-13 22:55:37.431  1035  1560 D WifiServiceImplEx: setWifiEnabled: true pid=6804, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 22:55:37.432  1035  1560 D WifiService: setWifiEnabled: true pid=6804, uid=10118
09-13 22:55:37.432  1035  1560 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 22:55:37.433  1035  1528 D WifiController: Mismatch in the state 1
,09-13 22:55:37.508  1035  1035 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
,09-13 22:55:37.538  6940  6940 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 22:55:37.548  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-13 22:55:37.565  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:37.576  7006  7026 W FormManager: Network not available. Please check & try again.
,09-13 22:55:37.584  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 22:55:37.584  6962  6962 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 22:55:37.585  6962  6962 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 22:55:37.585  6962  6962 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 22:55:37.585  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 22:55:37.587  7006  7032 V FormManager: Network unavailable.
09-13 22:55:37.590  7006  7032 V FormManager: Network unavailable.
,09-13 22:55:37.596  6962  6962 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 22:55:37.596  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 22:55:37.596  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 22:55:37.596  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 22:55:37.596  6962  6962 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 22:55:37.597  6962  6962 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 22:55:37.600  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 22:55:37.601  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 22:55:37.603  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 22:55:37.605  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 22:55:37.612  6940  6940 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-13 22:55:37.613  6940  6940 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 22:55:37.613  6940  6940 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 22:55:37.616  4747  7036 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 22:55:37.616  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 22:55:37.618  4747  7036 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-13 22:55:37.619  4747  7035 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 22:55:37.624  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:37.631  7006  7039 V FormManager: Network unavailable.
,09-13 22:55:37.635  7006  7038 W FormManager: Network not available. Please check & try again.
09-13 22:55:37.641  7006  7039 V FormManager: Network unavailable.
09-13 22:55:37.647  1035  1766 I ActivityManager: Killing 6450:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,09-13 22:55:37.677  1035  1943 W libprocessgroup: failed to open /acct/uid_10008/pid_6450/cgroup.procs: No such file or directory
,09-13 22:55:37.687  6986  6986 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-13 22:55:37.689  6986  6986 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,09-13 22:55:37.689  6986  6986 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-13 22:55:37.731  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-13 22:55:37.737  1035  1117 D Tethering: InitialState.processMessage what=4
,09-13 22:55:37.740  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 22:55:37.745  6986  6986 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 22:55:37.745  6986  6986 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 22:55:37.749   315   879 D SoftapController: Softap fwReload - Ok
09-13 22:55:37.751  1035  1522 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (667ms)
09-13 22:55:37.755  6986  6986 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-13 22:55:37.757   315   879 D CommandListener: Setting iface cfg
09-13 22:55:37.757   315   879 D CommandListener: Trying to bring down wlan0
09-13 22:55:37.758   315   879 D CommandListener: Clearing all IP addresses on wlan0
09-13 22:55:37.759  6986  6986 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-13 22:55:37.759  6986  6986 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-13 22:55:37.759  6986  6986 V SoundPool: doLoad: loading sample sampleID=1
09-13 22:55:37.759  6986  6986 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-13 22:55:37.761  1035  1522 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,09-13 22:55:37.764  1035  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 22:55:37.764  1035  1522 E WifiStateMachine: useWiFiOffloading() : false
09-13 22:55:37.764  1035  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 22:55:37.766  6711  6711 D UEI.SmartControl: QS Service created
09-13 22:55:37.769  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-13 22:55:37.756  7050  7050 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 22:55:37.756  7050  7050 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 22:55:37.771  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-13 22:55:37.773  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:37.774  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:37.776  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:37.776  1035  1522 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-13 22:55:37.776  1035  1522 D WifiMonitor: connecting to supplicant
09-13 22:55:37.779  6986  6986 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-13 22:55:37.779  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:37.781  6986  7049 V SoundPool: Start decode
09-13 22:55:37.781  6986  7049 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-13 22:55:37.782  6986  6986 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 22:55:37.782   320  1366 V MediaPlayerService: decode(22, 10857164, 17813)
09-13 22:55:37.782   320  1366 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-13 22:55:37.782   320  1366 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-13 22:55:37.782   320  1366 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-13 22:55:37.782   320  1366 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-13 22:55:37.782   320  1366 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-13 22:55:37.782   320  1366 V MediaPlayerService: player type = 3
09-13 22:55:37.782   320  1366 V AwesomePlayer: AwesomePlayer create()
09-13 22:55:37.783   320  1366 V AwesomePlayer: reset_l() 
09-13 22:55:37.783   320  1366 V AwesomePlayer: cancelPlayerEvents
09-13 22:55:37.783   320  1366 V AwesomePlayer: setAudioSink() 
09-13 22:55:37.783   320  1366 V AwesomePlayer: reset_l() 
09-13 22:55:37.783   320  1366 V AudioCache: notify(0xb5474680, 8, 0, 0)
09-13 22:55:37.783   320  1366 V AudioCache: ignored
09-13 22:55:37.783   320  1366 V AwesomePlayer: cancelPlayerEvents
09-13 22:55:37.783   320  1366 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
09-13 22:55:37.783   320  1366 V AwesomePlayer: setDataSource_l dataSource
09-13 22:55:37.783   320  1366 V LGParserOSAL: SniffLGParser start
09-13 22:55:37.783   320  1366 V LGParserOSAL: MainType:5, SubType=0
09-13 22:55:37.783   320  1366 V LGParserOSAL: #### check Mime : application/ogg
09-13 22:55:37.783   320  1366 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-13 22:55:37.783   320  1366 E MediaExtractor: Use LGExtractor :application/ogg 
,09-13 22:55:37.797  7050  7050 I wpa_supplicant: Successfully initialized wpa_supplicant
09-13 22:55:37.800  6986  6986 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-13 22:55:37.813  6986  6986 V LGMDMManager: Create singleton instance
,09-13 22:55:37.833   320  1366 V LGParserOSAL: supported mime: application/ogg
09-13 22:55:37.833   320  1366 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-13 22:55:37.833   320  1366 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-13 22:55:37.833   320  1366 V AwesomePlayer: mBitrate = -1 bits/sec
09-13 22:55:37.833   320  1366 V AwesomePlayer: AudioTrack Setting
09-13 22:55:37.833   320  1366 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-13 22:55:37.833   320  1366 V AwesomePlayer: setAudioSource() 
09-13 22:55:37.833   320  1366 V MediaPlayerService: prepare
09-13 22:55:37.833   320  1366 V AwesomePlayer: prepareAsync_l() 
09-13 22:55:37.834   320  1366 V MediaPlayerService: wait for prepare
09-13 22:55:37.834   320  7051 V AwesomePlayer: onPrepareAsyncEvent() 
09-13 22:55:37.834   320  7051 V AwesomePlayer: initAudioDecoder() 
09-13 22:55:37.834   320  7051 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-13 22:55:37.834   320  7051 V AudioSystem: isOffloadSupported()
09-13 22:55:37.834   320  7051 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-13 22:55:37.834   320  7051 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-13 22:55:37.834   320  7051 I AudioFlinger: isAudioPlaybackHookOn() false
09-13 22:55:37.834   320  7051 V AwesomePlayer: getUseOffload() = 0 
09-13 22:55:37.834   320  7051 V OMXCodec: OMXCodec::Create
09-13 22:55:37.834   320  7051 V OMXCodec: findMatchingCodecs()
09-13 22:55:37.834   320  7051 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-13 22:55:37.834   320  7051 V OMXCodec: matchingCodecs.size()=1
09-13 22:55:37.834   320  7051 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-13 22:55:37.836   320  7051 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-13 22:55:37.836   320  7051 V LGCodecAdapter: LG Codec Adapter start
09-13 22:55:37.836   320  7051 V OMXCodec: OMXCodec Createtor
09-13 22:55:37.836   320  7051 V OMXCodec: setComponentRole
09-13 22:55:37.836   320  7051 V OMXCodec: configureCodec protected=0
09-13 22:55:37.836   320  7051 V LGCodecAdapter: called getLGCodecSpecificData
,09-13 22:55:37.836   320  7051 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-13 22:55:37.836   320  7051 V LGCodecOSAL: Called LGconfigureCodecMETA
09-13 22:55:37.836   320  7051 V LGCodecOSAL: Called LGconfigureCodecMSG
09-13 22:55:37.836   320  7051 V LGCodecOSAL: Not support LGCodec
09-13 22:55:37.836   320  7051 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-13 22:55:37.836   320  7051 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-13 22:55:37.836   320  7051 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-13 22:55:37.836   320  7051 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-13 22:55:37.836   320  7051 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-13 22:55:37.836   320  7051 V AudioSystem: isOffloadSupported()
09-13 22:55:37.836   320  7051 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-13 22:55:37.836   320  7051 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-13 22:55:37.836   320  7051 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-13 22:55:37.836   320  7051 V OMXCodec: init()
09-13 22:55:37.836   320  7051 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-13 22:55:37.836   320  7051 V OMXCodec: allocateBuffers
09-13 22:55:37.836   320  7051 V OMXCodec: allocateBuffersOnPort portIndex=0
09-13 22:55:37.836   320  7051 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-13 22:55:37.836   320  7051 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
09-13 22:55:37.836   320  7051 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
09-13 22:55:37.836   320  7051 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
09-13 22:55:37.837   320  7051 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
09-13 22:55:37.837   320  7051 V OMXCodec: allocateBuffersOnPort portIndex=1
09-13 22:55:37.837   320  7051 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-13 22:55:37.837   320  7051 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
09-13 22:55:37.837   320  7051 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
09-13 22:55:37.837   320  7051 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
09-13 22:55:37.837   320  7051 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd5b0 on output port
09-13 22:55:37.837   320  7051 V OMXCodec: init() mAsyncCompletion wait!!! 
09-13 22:55:37.837   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-13 22:55:37.837   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-13 22:55:37.837   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-13 22:55:37.837   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-13 22:55:37.837   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-13 22:55:37.837   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-13 22:55:37.840  6711  6711 I UEI.SmartControl: Service initServices...
09-13 22:55:37.841  6711  6711 D UEI.SmartControl: QS start get config
09-13 22:55:37.844  7050  7050 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-13 22:55:37.844  7050  7050 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-13 22:55:37.845   320  7051 V OMXCodec: init() mAsyncCompletion wait free! 
09-13 22:55:37.845   320  7051 V ,AwesomePlayer: finishAsyncPrepare_l() 
09-13 22:55:37.845   320  7051 V AudioCache: notify(0xb5474680, 5, 0, 0)
09-13 22:55:37.845   320  7051 V AudioCache: ignored
09-13 22:55:37.845   320  7051 V AudioCache: notify(0xb5474680, 1, 0, 0)
09-13 22:55:37.845   320  7051 V AudioCache: prepared
09-13 22:55:37.845   320  1366 V AudioCache: wait - success
09-13 22:55:37.845   320  1366 V MediaPlayerService: start
09-13 22:55:37.845   320  1366 V AwesomePlayer: play_l() 
09-13 22:55:37.845   320  1366 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-13 22:55:37.845   320  1366 V AwesomePlayer: createAudioPlayer_l
09-13 22:55:37.845   320  1366 V AwesomePlayer: seekAudioIfNecessary_l() 
09-13 22:55:37.845   320  1366 V AwesomePlayer: startAudioPlayer_l() 
09-13 22:55:37.846   320  1366 D AudioPlayer: start of Playback, useOffload 0
09-13 22:55:37.846   320  1366 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-13 22:55:37.846   320  1366 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
,09-13 22:55:37.849   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-13 22:55:37.849   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-13 22:55:37.849   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-13 22:55:37.849   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-13 22:55:37.850   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-13 22:55:37.850   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-13 22:55:37.850   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
09-13 22:55:37.850   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 22:55:37.850   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
09-13 22:55:37.850   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 22:55:37.850   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
09-13 22:55:37.850   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 22:55:37.850   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044791728
09-13 22:55:37.850   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 22:55:37.851   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-13 22:55:37.851   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-13 22:55:37.851   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-13 22:55:37.851   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-13 22:55:37.851   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-13 22:55:37.851   320  7053 V OMXCodec: allocateBuffersOnPort portIndex=1
09-13 22:55:37.851   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-13 22:55:37.851   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
09-13 22:55:37.851   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
09-13 22:55:37.851   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
09-13 22:55:37.851   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd8d0 on output port
09-13 22:55:37.852   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-13 22:55:37.852   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-13 22:55:37.853   320  1366 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-13 22:55:37.853   320  1366 V AudioCache: notify(0xb5474680, 6, 0, 0)
09-13 22:55:37.853   320  1366 V AudioCache: ignored
09-13 22:55:37.854   320  1366 V MediaPlayerService: wait for playback complete
09-13 22:55:37.854   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.854   320  7054 V AudioCache: memcpy(0xaf004000, 0xb16f8000, 4096)
09-13 22:55:37.855   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.855   320  7054 V AudioCache: memcpy(0xaf005000, 0xb16f8000, 4096)
09-13 22:55:37.856   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.856   320  7054 V AudioCache: memcpy(0xaf006000, 0xb16f8000, 4096)
09-13 22:55:37.856   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.856   320  7054 V AudioCache: memcpy(0xaf007000, 0xb16f8000, 4096)
09-13 22:55:37.857   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.857   320  7054 V AudioCache: memcpy(0xaf008000, 0xb16f8000, 4096)
,09-13 22:55:37.858   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.858   320  7054 V AudioCache: memcpy(0xaf009000, 0xb16f8000, 4096)
09-13 22:55:37.860   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.860   320  7054 V AudioCache: memcpy(0xaf00a000, 0xb16f8000, 4096)
09-13 22:55:37.860   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.860   320  7054 V AudioCache: memcpy(0xaf00b000, 0xb16f8000, 4096)
09-13 22:55:37.861   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.861   320  7054 V AudioCache: memcpy(0xaf00c000, 0xb16f8000, 4096)
09-13 22:55:37.862   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.862   320  7054 V AudioCache: memcpy(0xaf00d000, 0xb16f8000, 4096)
09-13 22:55:37.863   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.863   320  7054 V AudioCache: memcpy(0xaf00e000, 0xb16f8000, 4096)
09-13 22:55:37.863   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.863   320  7054 V AudioCache: memcpy(0xaf00f000, 0xb16f8000, 4096)
09-13 22:55:37.864   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.864   320  7054 V AudioCache: memcpy(0xaf010000, 0xb16f8000, 4096)
09-13 22:55:37.864   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.864   320  7054 V AudioCache: memcpy(0xaf011000, 0xb16f8000, 4096)
09-13 22:55:37.865   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.865   320  7054 V AudioCache: memcpy(0xaf012000, 0xb16f8000, 4096)
09-13 22:55:37.866   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.866   320  7054 V AudioCache: memcpy(0xaf013000, 0xb16f8000, 4096)
09-13 22:55:37.866   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.866   320  7054 V AudioCache: memcpy(0xaf014000, 0xb16f8000, 4096)
09-13 22:55:37.867   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.867   320  7054 V AudioCache: memcpy(0xaf015000, 0xb16f8000, 4096)
09-13 22:55:37.867   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.867   320  7054 V AudioCache: memcpy(0xaf016000, 0xb16f8000, 4096)
09-13 22:55:37.868   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.868   320  7054 V AudioCache: memcpy(0xaf017000, 0xb16f8000, 4096)
09-13 22:55:37.869   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.869   320  7054 V AudioCache: memcpy(0xaf018000, 0xb16f8000, 4096)
09-13 22:55:37.870   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.870   320  7054 V AudioCache: memcpy(0xaf019000, 0xb16f8000, 4096)
09-13 22:55:37.870   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.870   320  7054 V AudioCache: memcpy(0xaf01a000, 0xb16f8000, 4096)
09-13 22:55:37.871   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.871   320  7054 V AudioCache: memcpy(0xaf01b000, 0xb16f8000, 4096)
09-13 22:55:37.873   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.873   320  7054 V AudioCache: memcpy(0xaf01c000, 0xb16f8000, 4096)
09-13 22:55:37.873   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.873   320  7054 V AudioCache: memcpy(0xaf01d000, 0xb16f8000, 4096)
09-13 22:55:37.874   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.874   320  7054 V AudioCache: memcpy(0xaf01e000, 0xb16f8000, 4096)
09-13 22:55:37.875   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.875   320  7054 V AudioCache: memcpy(0xaf01f000, 0xb16f8000, 4096)
09-13 22:55:37.875   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.875   320  7054 V AudioCache: memcpy(0xaf020000, 0xb16f8000, 4096)
09-13 22:55:37.876   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.876   320  7054 V AudioCache: memcpy(0xaf021000, 0xb16f8000, 4096)
09-13 22:55:37.877   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.877   320  7054 V AudioCache: memcpy(0xaf022000, 0xb16f8000, 4096)
09-13 22:55:37.877   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.877   320  7054 V AudioCache: mem,cpy(0xaf023000, 0xb16f8000, 4096)
09-13 22:55:37.878   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.878   320  7054 V AudioCache: memcpy(0xaf024000, 0xb16f8000, 4096)
09-13 22:55:37.878   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.878   320  7054 V AudioCache: memcpy(0xaf025000, 0xb16f8000, 4096)
09-13 22:55:37.879   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.879   320  7054 V AudioCache: memcpy(0xaf026000, 0xb16f8000, 4096)
09-13 22:55:37.880   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.880   320  7054 V AudioCache: memcpy(0xaf027000, 0xb16f8000, 4096)
09-13 22:55:37.880   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.880   320  7054 V AudioCache: memcpy(0xaf028000, 0xb16f8000, 4096)
,09-13 22:55:37.881   320  7054 V AudioCache: write(0xb16f8000, 4096)
,09-13 22:55:37.881   320  7054 V AudioCache: memcpy(0xaf029000, 0xb16f8000, 4096)
09-13 22:55:37.882   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.882   320  7054 V AudioCache: memcpy(0xaf02a000, 0xb16f8000, 4096)
09-13 22:55:37.882   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.882   320  7054 V AudioCache: memcpy(0xaf02b000, 0xb16f8000, 4096)
09-13 22:55:37.884   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.884   320  7054 V AudioCache: memcpy(0xaf02c000, 0xb16f8000, 4096)
09-13 22:55:37.884   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.884   320  7054 V AudioCache: memcpy(0xaf02d000, 0xb16f8000, 4096)
09-13 22:55:37.885   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.885   320  7054 V AudioCache: memcpy(0xaf02e000, 0xb16f8000, 4096)
09-13 22:55:37.886   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.886   320  7054 V AudioCache: memcpy(0xaf02f000, 0xb16f8000, 4096)
09-13 22:55:37.887   320  7054 V AudioCache: write(0xb16f8000, 4096)
,09-13 22:55:37.887   320  7054 V AudioCache: memcpy(0xaf030000, 0xb16f8000, 4096)
09-13 22:55:37.887   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.887   320  7054 V AudioCache: memcpy(0xaf031000, 0xb16f8000, 4096)
09-13 22:55:37.888   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.888   320  7054 V AudioCache: memcpy(0xaf032000, 0xb16f8000, 4096)
,09-13 22:55:37.889   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.889   320  7054 V AudioCache: memcpy(0xaf033000, 0xb16f8000, 4096)
09-13 22:55:37.889  6986  6986 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-13 22:55:37.890  6986  6986 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-13 22:55:37.890   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.890   320  7054 V AudioCache: memcpy(0xaf034000, 0xb16f8000, 4096)
09-13 22:55:37.890   320  7054 V AudioCache: write(0xb16f8000, 4096)
09-13 22:55:37.890   320  7054 V AudioCache: memcpy(0xaf035000, 0xb16f8000, 4096)
09-13 22:55:37.890   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-13 22:55:37.891   320  7054 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-13 22:55:37.891   320  7054 V AwesomePlayer: postAudioEOS() 
09-13 22:55:37.891   320  7054 V AudioCache: write(0xb16f8000, 280)
09-13 22:55:37.891   320  7054 V AudioCache: memcpy(0xaf036000, 0xb16f8000, 280)
09-13 22:55:37.891  6986  6986 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5604
09-13 22:55:37.892   320  7051 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-13 22:55:37.892   320  7051 V AwesomePlayer: onStreamDone
09-13 22:55:37.892   320  7051 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-13 22:55:37.892   320  7051 V AudioCache: notify(0xb5474680, 2, 0, 0)
09-13 22:55:37.892   320  7051 V AudioCache: playback complete
09-13 22:55:37.892   320  7051 V AwesomePlayer: pause_l() 
09-13 22:55:37.892   320  7051 V AudioCache: notify(0xb5474680, 7, 0, 0)
09-13 22:55:37.892   320  7051 V AudioCache: ignored
09-13 22:55:37.892   320  7051 V AwesomePlayer: cancelPlayerEvents
09-13 22:55:37.892   320  1366 V AudioCache: wait - success
09-13 22:55:37.892   320  1366 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-13 22:55:37.892   320  7051 D AudioPlayer: Pause Playback at 1068125
09-13 22:55:37.893   320  1366 V AwesomePlayer: reset_l() 
09-13 22:55:37.893   320  1366 V AudioCache: notify(0xb5474680, 8, 0, 0)
09-13 22:55:37.893   320  1366 V AudioCache: ignored
09-13 22:55:37.893   320  1366 V AwesomePlayer: cancelPlayerEvents
09-13 22:55:37.893   320  1366 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-13 22:55:37.893   320  1366 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-13 22:55:37.893   320  1366 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-13 22:55:37.893   320  1366 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-13 22:55:37.893   320  1366 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-13 22:55:37.893   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-13 22:55:37.893   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-13 22:55:37.893   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-13 22:55:37.893   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
09-13 22:55:37.894   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-13 22:55:37.894   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
09-13 22:55:37.894   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-13 22:55:37.894   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
09-13 22:55:37.894   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-13 22:55:37.894  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 22:55:37.894  6962  6962 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 22:55:37.894   320  705,3 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
09-13 22:55:37.894   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-13 22:55:37.894  6962  6962 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 22:55:37.894  6962  6962 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 22:55:37.894   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-13 22:55:37.894   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bd8d0 on port 1
09-13 22:55:37.894   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-13 22:55:37.894   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
09-13 22:55:37.894   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-13 22:55:37.894   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
09-13 22:55:37.894   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-13 22:55:37.894   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
09-13 22:55:37.894   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 22:55:37.894   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-13 22:55:37.894  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 22:55:37.894   320  1366 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-13 22:55:37.894   320  1366 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-13 22:55:37.895  6962  6962 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 22:55:37.895  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 22:55:37.895  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 22:55:37.895  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 22:55:37.895  6962  6962 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 22:55:37.895  6962  6962 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 22:55:37.895   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-13 22:55:37.895   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-13 22:55:37.895   320  7053 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-13 22:55:37.895   320  1366 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-13 22:55:37.895   320  1366 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-13 22:55:37.895   320  1366 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-13 22:55:37.897   320  1366 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
,09-13 22:55:37.897   320  1366 D AudioPlayer: AudioPlayer releasing audio source
09-13 22:55:37.897   320  1366 D AudioPlayer: AudioPlayer done releasing audio source
09-13 22:55:37.897   320  1366 V AwesomePlayer: reset_l() 
09-13 22:55:37.897   320  1366 V AwesomePlayer: cancelPlayerEvents
09-13 22:55:37.898   320  1366 V AwesomePlayer: ~AwesomePlayer call
09-13 22:55:37.898   320  1366 V AwesomePlayer: reset_l() 
09-13 22:55:37.898   320  1366 V AwesomePlayer: cancelPlayerEvents
09-13 22:55:37.898  6986  7049 V SoundPool: close(31)
09-13 22:55:37.898  6986  7049 V SoundPool: pointer = 0x9fe8c000, size = 205080, sampleRate = 48000, numChannels = 2
09-13 22:55:37.903  6940  6940 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 22:55:37.904  7050  7050 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-13 22:55:37.905  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 22:55:37.908  7006  7056 W FormManager: Network not available. Please check & try again.
,09-13 22:55:37.911  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:37.912  7006  7057 V FormManager: Network unavailable.
09-13 22:55:37.920  7006  7057 V FormManager: Network unavailable.
,09-13 22:55:37.934  1035  1925 D WifiServiceImplEx: setWifiEnabled: true pid=6804, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 22:55:37.934  1035  1925 D WifiService: setWifiEnabled: true pid=6804, uid=10118
09-13 22:55:37.934  1035  1925 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 22:55:37.958  7050  7050 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-13 22:55:37.971  7050  7050 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,09-13 22:55:37.972  1035  1522 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-13 22:55:37.973  1035  1522 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-13 22:55:37.973  1035  1522 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-13 22:55:37.973  1035  1522 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-13 22:55:37.974  1035  1522 E WifiStateMachine:  SupplicantStartingState CMD_START_SUPPLICANT 0 0
09-13 22:55:37.974  1035  7058 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-13 22:55:37.974  1035  7058 D WifiMonitor: Dropping event because (p2p0) is stopped
09-13 22:55:37.974  1035  1522 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-13 22:55:37.975  1035  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 22:55:37.975  1035  1522 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-13 22:55:37.975  1035  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 22:55:37.976  1035  1522 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-13 22:55:37.976  1035  1522 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-13 22:55:37.977  1035  1522 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-13 22:55:37.977  1035  1522 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-13 22:55:37.977  1035  1522 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-13 22:55:37.978  1035  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 22:55:37.978  1035  1522 E WifiStateMachine: useWiFiOffloading() : false
09-13 22:55:37.978  1035  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 22:55:37.978  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:37.978  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:37.978  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:37.978  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:37.978  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 22:55:37.979  1035  1522 D WifiNative-wlan0: doBoolean: SET update_config 1
09-13 22:55:37.980  1035  7058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-13 22:55:37.980  7050  7050 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-13 22:55:37.980  1035  7058 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-13 22:55:37.980  1035  1522 D WifiNative-wlan0: SET update_config 1: returned true
09-13 22:55:37.981  1035  1522 D WifiConfigStore: Loading config and enabling all networks 
09-13 22:55:37.981  1035  1522 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-13 22:55:37.981  1926  1926 D WfdService: Waiting for WifiP2p enabling
09-13 22:55:37.981  1035  1522 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-13 22:55:37.982  1035  7058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-13 22:55:37.982  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:37.982  1035  7058 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-13 22:55:37.982  1035  7058 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-13 22:55:37.982  1035  7058 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-13 22:55:37.988  1035  1522 E WifiConfigS,tore: readNetworkVariablesFromSupplicantFile key=psk
,09-13 22:55:37.989  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-13 22:55:37.990  1035  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-13 22:55:37.999  1035  1522 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-13 22:55:37.999  1035  1522 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-13 22:55:38.000  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:38.000  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:38.000  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:38.000  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:38.000  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:38.000  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:55:38.000  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:55:38.000  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 22:55:38.000  1035  1522 D WifiStateMachine: enableVerboseLogging : level 2
09-13 22:55:38.000  1035  1522 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-13 22:55:38.001  1035  1522 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-13 22:55:38.001  1035  1522 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-13 22:55:38.001  1035  1522 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-13 22:55:38.001  1035  1522 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-13 22:55:38.002  1035  1522 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-13 22:55:38.002  1035  1522 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-13 22:55:38.002  1035  1522 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-13 22:55:38.002  1035  1522 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
,09-13 22:55:38.002  1035  1522 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-13 22:55:38.003  1035  1522 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-13 22:55:38.003  6804  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
09-13 22:55:38.003  1035  1522 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-13 22:55:38.003  1035  1522 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-13 22:55:38.003  1035  1522 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,09-13 22:55:38.006  6940  6940 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 22:55:38.007  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:38.007  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:38.007  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:38.007  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:38.007  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:38.007  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:55:38.007  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:55:38.007  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 22:55:38.009  6804  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 22:55:38.011  1035  1522 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 22:55:38.011  1035  1522 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-13 22:55:38.012  1035  1522 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-13 22:55:38.012  1035  1522 D WifiNative-HAL: Setting external_sim to 1
09-13 22:55:38.012  1926  1926 D WfdsService: Supplicant Connection state is changed : true
09-13 22:55:38.012  1035  1522 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-13 22:55:38.012  1926  2306 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-13 22:55:38.012  1926  2306 D WfdsService: Set the WFDS Monitor: true
09-13 22:55:38.012  1926  2306 D WfdsMonitor: WfdsMonitorThread create
09-13 22:55:38.013  1035  1522 D WifiNative-wlan0: SET external_sim 1: returned true
09-13 22:55:38.013  1035  1522 I WifiNative-HAL: startHal
09-13 22:55:38.013  1926  2306 D WfdsMonitor: WFDS Monitor is created and started
09-13 22:55:38.013  1926  2306 D WfdsService: WiFi: Supplicant connection re-established
09-13 22:55:38.013  1035  1522 D wifi    : setting scan oui 0x953a6520
09-13 22:55:38.013  1035  1522 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 22:55:38.013  1035  1522 I WifiNative-HAL: startHal
09-13 22:55:38.013  1035  1522 D wifi    : setting scan oui 0x953a6520
09-13 22:55:38.013  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:38.013  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:38.013  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:38.013  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:38.013  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:38.013  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:55:38.013  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:55:38.013  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 22:55:38.013  1035  1522 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-13 22:55:38.014  1035  1522 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-13 22:55:38.014  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-13 22:55:38.014  7050  7050 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-13 22:55:38.014  1035  1522 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-13 22:55:38.015  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 22:55:38.015  7050  7050 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 22:55:38.015  1926  7060 E CtrlSupplicant: Access OK "@andro,id:wpa_wlan0"
09-13 22:55:38.015  6804  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 22:55:38.015  1035  1522 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 22:55:38.015  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-13 22:55:38.015  7050  7050 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-13 22:55:38.016  1035  1522 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-13 22:55:38.016  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 22:55:38.016  7050  7050 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 22:55:38.016  1926  7060 E CtrlSupplicant: Succeed to open control connection
09-13 22:55:38.016  1926  7060 E CtrlSupplicant: Succeed to open monitor connection
09-13 22:55:38.016  1035  1522 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
,09-13 22:55:38.016  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 22:55:38.017  7050  7050 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 22:55:38.017  1926  7060 D WfdsMonitor: Supplicant connection established
09-13 22:55:38.017  1926  2306 D WfdsService: Connected to the supplicant for wfds
09-13 22:55:38.017  1035  1522 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 22:55:38.017  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-13 22:55:38.017  7050  7050 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-13 22:55:38.017  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 22:55:38.018  1035  1522 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-13 22:55:38.018  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 22:55:38.018  7050  7050 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 22:55:38.018  1035  1522 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 22:55:38.019  1035  1522 E WifiNative: : [194,274,580 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-13 22:55:38.019  1035  1522 D WifiNative-wlan0: doBoolean: RECONNECT
09-13 22:55:38.020  1035  1522 D WifiNative-wlan0: RECONNECT: returned true
09-13 22:55:38.020  1035  1522 D WifiNative-wlan0: doString: [STATUS]
09-13 22:55:38.020  1035  7058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-13 22:55:38.020  1035  7058 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-13 22:55:38.021  1035  1522 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 22:55:38.021  1035  1522 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 22:55:38.021  1035  1522 D WifiNative-wlan0: SET ps 1: returned true
09-13 22:55:38.021  1035  1519 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.023  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
09-13 22:55:38.023  1035  1035 D RttService: SCAN_AVAILABLE : 3
09-13 22:55:38.023  1035  1540 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.023  1035  1540 I WifiNative-HAL: startHal
09-13 22:55:38.023  1035  1541 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.023  1035  1522 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-13 22:55:38.023  1035  1540 D wifi    : getting scan capabilities on interface[1] = 0x953a6520
09-13 22:55:38.023  1035  1540 D wifi    : failed to get capabilities : -3
09-13 22:55:38.023  1035  1540 E WifiScanningService: could not get scan capabilities
09-13 22:55:38.023  1035  1522 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-13 22:55:38.024  1035  1522 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-13 22:55:38.024   315   879 D CommandListener: Setting iface cfg
09-13 22:55:38.024   315   879 D CommandListener: Trying to bring up p2p0
09-13 22:55:38.024  1035  1522 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-13 22:55:38.024  1035  1519 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-13 22:55:38.024  1035  1519 D LGWifiP2pService: P2pEnablingState
09-13 22:55:38.025  1035  1522 E WifiStateMachine:  DisconnectedState CMD_START_SUPPLICANT 0 0
09-13 22:55:38.025  1035  1519 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.025  1035  1519 D LGWifiP2pService: P2p socket connection successful
09-13 22:55:38.025  1035  1519 D LGWifiP2pService: P2pEnabledState
09-13 22:55:,38.025  1035  1522 E WifiStateMachine:  ConnectModeState CMD_START_SUPPLICANT 0 0
09-13 22:55:38.025  1035  1519 D LGWifiP2pService: sending p2p connection changed broadcast
09-13 22:55:38.025  1035  1522 E WifiStateMachine:  DriverStartedState CMD_START_SUPPLICANT 0 0
09-13 22:55:38.025  1035  1519 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-13 22:55:38.026  1035  1522 E WifiStateMachine:  SupplicantStartedState CMD_START_SUPPLICANT 0 0
09-13 22:55:38.026  1035  1522 E WifiStateMachine:  DefaultState CMD_START_SUPPLICANT 0 0
09-13 22:55:38.027  1035  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=194283  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 22:55:38.027  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-13 22:55:38.027  1926  1926 D WfdsService: WifiP2pState is changed : true
09-13 22:55:38.028  1926  1926 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-13 22:55:38.028  1926  1926 D WfdsService: isConnected: false
09-13 22:55:38.028  1926  2306 D WfdsService: Receive the WFDS_ENABLE Method
09-13 22:55:38.028  1926  2306 D WfdsService: Set the WFDS Monitor: true
09-13 22:55:38.028  1926  2306 D WfdsService: Connected to the supplicant for wfds
09-13 22:55:38.028  1926  2306 D WfdsJNI : doCommand: WFDS_SET TRUE
09-13 22:55:38.029  7050  7050 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-13 22:55:38.029  1926  2306 D WfdsService: selectPreferredScanChannel [36]
09-13 22:55:38.029  1926  2306 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-13 22:55:38.029  1035  1519 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-13 22:55:38.029  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:38.029  1035  1519 D WifiNative-p2p0: doBoolean: SET device_name G3
09-13 22:55:38.029  1035  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=194285  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 22:55:38.030  1035  1522 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-13 22:55:38.030  1035  1522 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-13 22:55:38.031  1035  1519 D WifiNative-p2p0: SET device_name G3: returned true
09-13 22:55:38.031  1035  1519 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-13 22:55:38.031  1035  1519 D LGWifiP2pService: before postfix = G3
09-13 22:55:38.031  1035  1522 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-13 22:55:38.031  1035  1519 D WifiServerServiceExt: postfix byte check : 2
09-13 22:55:38.031  1035  1519 D LGWifiP2pService: after postfix = G3
09-13 22:55:38.031  1035  1522 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-13 22:55:38.031  1035  1519 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
,09-13 22:55:38.031  7050  7050 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-13 22:55:38.032  1035  1522 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-13 22:55:38.032  1035  1522 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-13 22:55:38.032  1035  1522 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-13 22:55:38.032  1035  1522 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-13 22:55:38.033  7050  7050 E wpa_supplicant: disconnect_rssi_lvl: -100
,09-13 22:55:38.035  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:38.035  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 22:55:38.037  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:38.037  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:38.038  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:38.038  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 22:55:38.038  1035  1519 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-13 22:55:38.038  1035  1519 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-13 22:55:38.039  1035  1522 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-13 22:55:38.039  1035  1519 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-13 22:55:38.039  1035  1519 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-13 22:55:38.039  1035  1522 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-13 22:55:38.040  1035  1522 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-13 22:55:38.040  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-13 22:55:38.040  1035  1519 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-13 22:55:38.040  1035  1519 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-13 22:55:38.041  1035  1519 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-13 22:55:38.041  1035  1519 D WifiNative-HAL: p2pGetDeviceAddress
09-13 22:55:38.041  1035  1519 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-13 22:55:38.042  7050  7050 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 22:55:38.042  7050  7050 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 22:55:38.043  7050  7050 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 22:55:38.043  7050  7050 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:38.044  7050  7050 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:38.044  1035  1522 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-13 22:55:38.044  1926  7060 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 22:55:38.045  1926  7060 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 22:55:38.045  1035  7058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 22:55:38.045  1035  7058 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 22:55:38.045  1035  7058 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 22:55:38.045  1035  1522 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-13 22:55:38.045  1035  7058 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 22:55:38.045  1035  7058 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 22:55:38.045  1035  7058 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:38.045  1035  7058 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:38.045  1035  7058 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER typ,e=WORLD
09-13 22:55:38.045  1035  1522 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
,09-13 22:55:38.045  1035  7058 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 22:55:38.045  1035  7058 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:38.045  1035  7058 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:38.045  1035  7058 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:38.046  1035  1522 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-13 22:55:38.046  1035  1519 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-13 22:55:38.046  1035  1519 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-13 22:55:38.046  1035  1519 D WifiNative-p2p0: P2P_FLUSH: returned true
09-13 22:55:38.046  1035  1519 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-13 22:55:38.047  1035  1519 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-13 22:55:38.047  1035  1519 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-13 22:55:38.047  1035  1519 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-13 22:55:38.047  1035  1519 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-13 22:55:38.049  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-13 22:55:38.051  1926  1926 I WfdStateTracker: handleP2pThisDeviceChanged
09-13 22:55:38.051  1926  1926 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-13 22:55:38.051  1926  1926 D WfdsService: Update P2p Interface State: 3
09-13 22:55:38.053  7006  7061 W FormManager: Network not available. Please check & try again.
09-13 22:55:38.061  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 22:55:38.062  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 22:55:38.063  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 22:55:38.065  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 22:55:38.065  7006  7062 V FormManager: Network unavailable.
09-13 22:55:38.070  1035  1519 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-13 22:55:38.070  1035  1519 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-13 22:55:38.071  1035  1519 D LGWifiP2pService: InactiveState
09-13 22:55:38.071  1035  1519 D LGWifiP2pService: InactiveState{ when=-26ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.071  1035  1519 D LGWifiP2pService: P2pEnabledState{ when=-26ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.071  1035  1519 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-13 22:55:38.071  7050  7050 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 22:55:38.071  7006  7062 V FormManager: Network unavailable.
09-13 22:55:38.072  5608  5608 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-13 22:55:38.072  7050  7050 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 22:55:38.073  7050  7050 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 22:55:38.073  7050  7050 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:38.073  7050  7050 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:38.074  1035  1519 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-13 22:55:38.074  1035  1519 D LGWifiP2pService: InactiveState{ when=-27ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.074  1035  1519 D LGWifiP2pService: P2pEnabledState{ when=-27ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.074  1035  1519 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.074  1035  1519 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.074  1035  1519 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.075  1926  7060 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 22:55:38.075  1926  7060 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 22:55:38.075  1035  1519 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.075  1926  7060 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 22:55:38.075  1035  1519 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.075  1035  1519 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.075  1035  7058 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 22:55:38.075  1035  7058 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 22:55:38.075  1035  1519 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.075  1035  1519 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.075  1035  7058 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE i,nit=USER type=COUNTRY alpha2=CZ
09-13 22:55:38.075  1035  7058 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 22:55:38.075  1035  1519 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.075  1035  7058 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 22:55:38.075  1035  7058 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:38.075  1035  1519 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.075  1035  7058 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:38.075  1035  1519 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.075  1035  7058 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:38.075  1035  1519 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.075  1035  7058 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 22:55:38.075  1035  7058 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:38.075  7050  7050 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-13 22:55:38.075  1035  1035 E WifiServerServiceExt: No p2p device connected
09-13 22:55:38.076  7050  7050 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 22:55:38.076  1926  2306 W WfdsService: DefaultState - msg [9441285] is not handled
09-13 22:55:38.076  1035  1522 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-13 22:55:38.076  1035  1522 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
,09-13 22:55:38.077  1035  1522 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-13 22:55:38.077  1035  1522 D WifiNative-wlan0: doBoolean: SCAN
09-13 22:55:38.075  1035  7058 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:38.077  1035  7058 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:38.077  1035  7058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-13 22:55:38.077  1035  7058 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 22:55:38.077  1035  7058 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 22:55:38.077  1035  7058 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 22:55:38.078  1035  1522 D WifiNative-wlan0: SCAN: returned false
09-13 22:55:38.078  1035  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=194334  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 22:55:38.079  1035  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=194335  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 22:55:38.080  1035  1522 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 22:55:38.081  1035  1522 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 22:55:38.082  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:38.082  5608  5608 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-13 22:55:38.082  1035  1522 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 22:55:38.082  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 22:55:38.082  1035  1522 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 22:55:38.083  1035  1522 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 22:55:38.084  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:38.084  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:38.084  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:38.084  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 22:55:38.084  5608  5608 V [BNRBootReceiver]: Boot Receiver Return
09-13 22:55:38.085  4747  7063 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 22:55:38.088  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 22:55:38.090  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 22:55:38.090  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
,09-13 22:55:38.096  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 22:55:38.096  4747  7064 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 22:55:38.096  4747  7064 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 22:55:38.101  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:38.106  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 22:55:38.106  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 22:55:38.107  6986  6986 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-13 22:55:38.110  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 22:55:38.114  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 22:55:38.118  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:38.123  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 22:55:38.123  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 22:55:38.124  6986  6986 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 22:55:38.248  6711  6711 I UEI.SmartControl: Supports setup maps: true
09-13 22:55:38.250  6711  6711 D UEI.SmartControl: QS start statue = true Error code = 0
09-13 22:55:38.250  6711  6711 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-13 22:55:38.250  6711  6711 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-13 22:55:38.250  6711  6711 I UEI.SmartControl: ### init IR Blaster...
,09-13 22:55:38.253  6711  6711 D serial_port: Configuring serial port
,09-13 22:55:38.254  6711  6711 E UEI.SmartControl: UEIBLaster setting for 616
09-13 22:55:38.254  6711  6711 I UEI.SmartControl: Setting serial record hearder size = 2
09-13 22:55:38.254  6711  6711 I UEI.SmartControl: configuring settings for MAXQ616
09-13 22:55:38.254  6711  6711 I UEI.SmartControl: Get version...
09-13 22:55:38.272  6711  7065 D UEI.SmartControl: serial port data available: 21
,09-13 22:55:38.299  6711  6711 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-13 22:55:38.299  6711  6711 I UEI.SmartControl: IR Blaster version: 256702256704300002
,09-13 22:55:38.299  6711  6711 I UEI.SmartControl: QS saving settings...
09-13 22:55:38.302  6711  6711 D UEI.SmartControl: IR Blaster version: 25672567
,09-13 22:55:38.319  6711  7065 D UEI.SmartControl: serial port data available: 4
,09-13 22:55:38.351  6711  7068 I UEI.SmartControl: Device manager: loading config....
,09-13 22:55:38.353  6711  7068 D UEI.SmartControl: ----------- loading internal config...
09-13 22:55:38.354  6711  6711 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-13 22:55:38.358  6711  6711 E UEI.SmartControl: Services init done
09-13 22:55:38.359  6711  6711 D UEI.SmartControl: QS Service init finished
09-13 22:55:38.361  6711  6711 D UEI.SmartControl: QS Service version name: 2.1.91
09-13 22:55:38.361  6711  6711 D UEI.SmartControl: QS Service version code: 201091
09-13 22:55:38.361  6711  6711 D UEI.SmartControl: Service requested: Control
09-13 22:55:38.363  6711  7068 E UEI.SmartControl: Loading SETTINGS...
09-13 22:55:38.367  6711  6711 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-13 22:55:38.370  6711  6711 D UEI.SmartControl: Internal service binding...
09-13 22:55:38.371  6986  6986 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-13 22:55:38.373  6711  6727 I UEI.SmartControl: ------ IControl API: 11
09-13 22:55:38.373  6711  6727 D UEI.SmartControl: File observer start...
09-13 22:55:38.374  6711  6727 E UEI.SmartControl: IR Port is disabled: false
09-13 22:55:38.374  6711  6727 D UEI.SmartControl: Starting file observer...
09-13 22:55:38.376  6711  6727 I UEI.SmartControl: Registering callback...
09-13 22:55:38.377  6711  7068 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-13 22:55:38.379  6711  6726 I UEI.SmartControl: ------ IControl API: 19
09-13 22:55:38.381  6711  6726 I UEI.SmartControl: Registering Services Ready callback...
09-13 22:55:38.390  6711  7067 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-13 22:55:38.390  6711  7067 D UEI.SmartControl: -----service ready thread exits
09-13 22:55:38.391  6986  7001 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-13 22:55:38.392  6986  7047 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-13 22:55:38.392  6986  7047 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-13 22:55:38.393  6986  6986 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-13 22:55:38.394  6986  6986 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-13 22:55:38.394  6711  6727 I UEI.SmartControl: ------ IControl API: 8
,09-13 22:55:38.398  6986  6986 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-13 22:55:38.399  6986  6986 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-13 22:55:38.400  6986  6986 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-13 22:55:38.401  6986  6986 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-13 22:55:38.402  6986  6986 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-13 22:55:38.403  6986  6986 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-13 22:55:38.406  6986  6986 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-13 22:55:38.410  6986  6986 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-13 22:55:38.412  6986  6986 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,09-13 22:55:38.414  6986  6986 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 22:55:38.414  6986  6986 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-13 22:55:38.417  6986  6986 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,09-13 22:55:38.419  6986  6986 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-13 22:55:38.421  6986  6986 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-13 22:55:38.424  6986  6986 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473800138423]
,09-13 22:55:38.427  6986  6986 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-13 22:55:38.433  1035  1051 I ActivityManager: Killing 5997:com.lge.appbox.client/u0a11 (adj 15): empty #17
09-13 22:55:38.439  6804  6980 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:55:38.460  6986  7070 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-13 22:55:38.492  1035  2016 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 22:55:38.493  1035  2016 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1adb52c1 mBinding = false
,09-13 22:55:38.493  1035  1050 W libprocessgroup: failed to open /acct/uid_10011/pid_5997/cgroup.procs: No such file or directory
,09-13 22:55:38.500  6986  6986 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-13 22:55:38.503  6986  6986 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 22:55:38.505  6986  6986 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-13 22:55:38.505  6986  6986 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-13 22:55:38.507  6986  6986 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,09-13 22:55:38.509  6986  6986 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-13 22:55:38.511  6986  6986 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-13 22:55:38.519  1035  1117 D BluetoothManagerService: Message: 2
09-13 22:55:38.519  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 22:55:38.520  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 22:55:38.520  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,09-13 22:55:38.523  1035  1117 D BluetoothManagerService: Sending off request.
09-13 22:55:38.525  4287  6901 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-13 22:55:38.526  4287  4363 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-13 22:55:38.526  4287  4363 D BluetoothAdapterProperties: Setting state to 13
09-13 22:55:38.526  4287  4363 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 22:55:38.528  4287  4363 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 22:55:38.528  1035  1117 D BluetoothManagerService: Message: 60
09-13 22:55:38.528  4287  4363 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-13 22:55:38.529  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-13 22:55:38.529  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-13 22:55:38.533  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 22:55:38.535  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-13 22:55:38.536  4287  4287 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:38.537  4287  4287 D BluetoothMapService: STATE_TURNING_OFF
09-13 22:55:38.537  4287  4287 V BluetoothMapService: Handler(): got msg=4
09-13 22:55:38.537  4287  4287 D BluetoothMapService: MAP Service closeService in
09-13 22:55:38.538  4287  4287 D BluetoothMapMasInstance: MAP Service shutdown
09-13 22:55:38.539  4287  4629 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-13 22:55:38.539  4287  4629 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 22:55:38.539  4287  4629 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-13 22:55:38.539  4287  4629 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-13 22:55:38.539  4287  4629 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-13 22:55:38.539  4287  4629 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-13 22:55:38.539  4287  4629 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-13 22:55:38.539  4287  4629 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-13 22:55:38.542  4287  4287 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 22:55:38.542  4287  4287 V BluetoothMapService: MAP Service closeService out
09-13 22:55:38.542  4287  4287 V BtOppService: Receiver DISABLED_ACTION 
09-13 22:55:38.543  4287  4287 I BtOppRfcommListener: stopping Accept Thread
09-13 22:55:38.543  4287  4287 V BtOppRfcommListener: close mBtServerSocket
09-13 22:55:38.543  4287  4673 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 22:55:38.544  4287  4673 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 22:55:38.545  4287  4287 V BtOppRfcommListener: waiting for thread to terminate
09-13 22:55:38.546  4287  4287 V BtOppRfcommListener: done waiting for thread to terminate
09-13 22:55:38.548  6804  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 22:55:38.549  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:38.549  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:38.549  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:38.549  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:38.549  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 22:55:38.549  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:55:38.549  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:55:38.549  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 22:55:38.549  4287  4287 V BtOppService: onDestroy
,09-13 22:55:38.554  4287  4366 D BluetoothAdapterProperties: Scan Mode:20
09-13 22:55:38.555  4287  4363 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-13 22:55:38.555  4287  4684 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 22:55:38.555  4287  4504 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-13 22:55:38.555  4287  4630 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 22:55:38.556  4287  4363 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 22:55:38.556  4287  4692 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 22:55:38.556  4287  4504 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-13 22:55:38.561  4287  4287 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-13 22:55:38.562  4287  4504 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 22:55:38.562  4287  4504 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 22:55:38.562  4287  4504 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 22:55:38.562  4287  4504 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 22:55:38.562  4287  4504 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 22:55:38.562  4287  4504 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 22:55:38.562  4287  4504 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 22:55:38.562  4287  4504 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 22:55:38.562  4287  4504 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 22:55:38.562  4287  4504 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-13 22:55:38.562  4287  4504 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-13 22:55:38.562  4287  4504 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 22:55:38.563  6804  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 22:55:38.563  6804  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 22:55:38.565  6962  6962 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 22:55:38.566  6804  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 22:55:38.566  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:38.566  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:38.566  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:38.566  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:38.566  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 22:55:38.566  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:55:38.566  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:55:38.566  6804  6804 V io.jxcore.node.Connectivity,Monitor:     - active network type is Wi-Fi: false
09-13 22:55:38.567  6804  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 22:55:38.567  6804  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 22:55:38.569  6804  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 22:55:38.569  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:38.569  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:38.569  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:38.569  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:38.569  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 22:55:38.569  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:55:38.569  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:55:38.569  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 22:55:38.570  6804  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 22:55:38.570  6804  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 22:55:38.571  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:38.579  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:55:38.581  4287  4287 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 22:55:38.581  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:38.581  4287  4287 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:38.582  6986  6986 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
09-13 22:55:38.583  4287  4287 V BluetoothPbapReceiver: ***********state = 13
09-13 22:55:38.591  4287  4287 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-13 22:55:38.591  1035  1117 D BluetoothManagerService: Message: 20
09-13 22:55:38.591  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d186654:true
,09-13 22:55:38.612  1035  7058 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-13 22:55:38.612  1035  7058 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,09-13 22:55:38.613  7050  7050 E wpa_supplicant: USIM:  scard_init function
,09-13 22:55:38.614  7050  7050 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-13 22:55:38.614  1035  7058 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-13 22:55:38.614  1035  7058 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
09-13 22:55:38.614  1035  7058 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-13 22:55:38.615  1035  1522 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-13 22:55:38.615  1035  7058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-13 22:55:38.615  1035  7058 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-13 22:55:38.616  1035  1522 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-13 22:55:38.616  1035  1522 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-13 22:55:38.616  1035  1522 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-13 22:55:38.616  1035  1522 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-13 22:55:38.638  1035  1971 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7073 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-13 22:55:38.641  1035  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=194897  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-13 22:55:38.641  4287  4287 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,09-13 22:55:38.641  4287  4287 V BluetoothPbapService: state: 13
09-13 22:55:38.641  4287  4287 V BluetoothPbapService: Pbap Service closeService in
09-13 22:55:38.642  1035  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=194898  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-13 22:55:38.643  4287  4287 V BluetoothPbapService: successfully stopped pbap service
09-13 22:55:38.643  4287  4287 V BluetoothPbapService: Pbap Service closeService out
09-13 22:55:38.643  4287  4287 V BluetoothPbapService: Pbap Service onDestroy
09-13 22:55:38.643  4287  4287 V BluetoothPbapService: Pbap Service closeService in
09-13 22:55:38.643  4287  4287 V BluetoothPbapService: Pbap Service closeService out
09-13 22:55:38.643  4287  4287 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-13 22:55:38.644  2182  2182 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 22:55:38.645  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:38.645  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 22:55:38.646  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:38.646  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:38.646  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 22:55:38.646  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 22:55:38.646  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-13 22:55:38.646  1035  1117 D BluetoothManagerService: Message: 30
09-13 22:55:38.650  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 22:55:38.652  1035  1117 D BluetoothManagerService: Message: 30
,09-13 22:55:38.655  6962  6962 D LocalBluetoothProfileManager: Adding local MAP profile
09-13 22:55:38.657  6962  6962 D BluetoothMap: Create BluetoothMap proxy object
09-13 22:55:38.658  1035  1117 D BluetoothManagerService: Message: 30
09-13 22:55:38.661  1035  1117 D BluetoothManagerService: Message: 30
09-13 22:55:38.663  6962  6962 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-13 22:55:38.664  6962  6962 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,09-13 22:55:38.682  6962  6962 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,09-13 22:55:38.685  6962  6962 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-13 22:55:38.691  6962  6962 D DockEventReceiver: finishStartingService: stopping service
09-13 22:55:38.691  6962  6962 D BluetoothInputDevice: Proxy object connected
09-13 22:55:38.692  6962  6962 D HidProfile: Bluetooth service connected
09-13 22:55:38.692  6962  6962 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 22:55:38.693  6962  6962 D PanProfile: Bluetooth service connected
09-13 22:55:38.693  6962  6962 D BluetoothMap: Proxy object connected
09-13 22:55:38.693  6962  6962 D MapProfile: Bluetooth service connected
09-13 22:55:38.693  6962  6962 D BluetoothMap: getConnectedDevices()
09-13 22:55:38.694  6962  6962 D BluetoothMap: Bluetooth is Not enabled
,09-13 22:55:38.694  6962  6962 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-13 22:55:38.723  7050  7050 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 22:55:38.725  1035  7058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-13 22:55:38.725  1035  7058 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-13 22:55:38.725  1035  7058 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-13 22:55:38.725  1035  7058 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-13 22:55:38.725  1035  7058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 22:55:38.725  1035  7058 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 22:55:38.726  1035  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=194982  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 22:55:38.726  1035  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=194982  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 22:55:38.727  1035  1522 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=194983
09-13 22:55:38.727  1035  1522 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=194983
09-13 22:55:38.727  1035  1522 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=194983
09-13 22:55:38.727  1035  1522 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=194983
09-13 22:55:38.728  1035  1522 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=194984
09-13 22:55:38.728  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-13 22:55:38.728  1035  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=194984  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-13 22:55:38.731  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:38.731  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 22:55:38.732  7050  7050 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 22:55:38.732  1035  7058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 22:55:38.732  7050  7050 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 22:55:38.732  1035  7058 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 22:55:38.732  1035  7058 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-13 22:55:38.732  1035  7058 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 22:55:38.732  1035  7058 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 22:55:38.732  1035  7058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-13 22:55:38.732  1035  7058 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 22:55:38.732  1035  7058 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 22:55:38.732  1035  7058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE i,d=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 22:55:38.732  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:38.733  1035  7058 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 22:55:38.733  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:38.733  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:38.733  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 22:55:38.734  7073  7073 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-13 22:55:38.734  7073  7073 W LG Account v2.2: No ProfileInfo entries
09-13 22:55:38.734  7073  7073 I LG Account v2.2: isEnabled: false
09-13 22:55:38.734  7073  7073 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-13 22:55:38.734  7073  7073 I Feature : [Lifetracker]Country: EU
09-13 22:55:38.734  7073  7073 I Feature : [Lifetracker]Operator: OPEN
09-13 22:55:38.734  7073  7073 I Feature : [Lifetracker]Ranking support: false
09-13 22:55:38.734  7073  7073 I Feature : [Lifetracker]Comfort support: false
09-13 22:55:38.734  7073  7073 I Feature : [Lifetracker]Accessory: true
,09-13 22:55:38.734  7073  7073 I Feature : [Lifetracker]Health device: true
09-13 22:55:38.735  7073  7073 I Feature : [Lifetracker]Extra Pedometer: false
09-13 22:55:38.735  7073  7073 I Feature : [Lifetracker]Blood glucose device: false
09-13 22:55:38.735  7073  7073 I Feature : [Lifetracker]Device Number: 3
09-13 22:55:38.743  1035  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=194999  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-13 22:55:38.744  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:38.744  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:38.744  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-13 22:55:38.745  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 22:55:38.745  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-13 22:55:38.745  1035  1522 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-13 22:55:38.746  1035  1522 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-13 22:55:38.746  1035  1522 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 22:55:38.746  1035  1522 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 22:55:38.747  1035  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 22:55:38.747  1035  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=195003  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 22:55:38.748  1035  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=195004  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,09-13 22:55:38.748  1035  1522 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=195004
09-13 22:55:38.749  1035  1522 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=195005
09-13 22:55:38.749  1035  1522 D WifiNative-wlan0: doString: [STATUS]
09-13 22:55:38.750  1035  7058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 22:55:38.750  1035  7058 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 22:55:38.750  1035  1522 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 22:55:38.750  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-13 22:55:38.752  1035  1522 I WifiServiceExtension: setVHTCapabilityType  : false
09-13 22:55:38.754  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:38.754  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 22:55:38.754  6962  6962 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-13 22:55:38.755  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:38.755  6962  6962 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-13 22:55:38.760  6962  6962 D BluetoothPermissionRequest: onReceive
,09-13 22:55:38.760  1035  1522 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-13 22:55:38.760  1035  1522 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-13 22:55:38.763  6962  6962 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-13 22:55:38.765  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:38.765  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:38.766  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 22:55:38.767  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:38.767  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:38.767  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 22:55:38.769  1035  1888 I ActivityManager: Killing 6018:com.android.contacts/u0a19 (adj 15): empty #17
09-13 22:55:38.771  6962  6962 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-13 22:55:38.775  1035  1522 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-13 22:55:38.775  1035  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 22:55:38.775  1035  1529 D ConnectivityService: Got NetworkAgent Messenger
09-13 22:55:38.775  1035  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 22:55:38.775  1035  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-13 22:55:38.775  1035  1529 D ConnectivityService: NetworkAgent connected
09-13 22:55:38.775  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:38.776  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 22:55:38.776  1035  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 22:55:38.776  1035  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 22:55:38.777  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:38.779  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:38.779  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 22:55:38.780  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:38.780  1035  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 22:55:38.780  1035  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 22:55:38.780  1035  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 22:55:38.781  1035  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 22:55:38.781  1035  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 22:55:38.784  1035  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-13 22:55:38.786   315   879 D CommandListener: Setting iface cfg
,09-13 22:55:38.799  4287  4287 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-13 22:55:38.799  4287  4287 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,09-13 22:55:38.799  1035  1943 W libprocessgroup: failed to open /acct/uid_10019/pid_6018/cgroup.procs: No such file or directory
09-13 22:55:38.800  4287  4287 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-13 22:55:38.805  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 22:55:38.806  1035  1522 E WifiStateMachine: Start Dhcp Watchdog 2
09-13 22:55:38.806  1035  7100 D DhcpStateMachine: StoppedState
09-13 22:55:38.806  1035  7100 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.806  1035  7100 D DhcpStateMachine: WaitBeforeStartState
09-13 22:55:38.806  1035  1522 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=195062  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 22:55:38.807  1035  1522 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=195062  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 22:55:38.807  1035  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=195063  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 22:55:38.810  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 22:55:38.810  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-13 22:55:38.810  4287  4287 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:38.810  1035  1522 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=195066  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 22:55:38.811  4287  4287 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 22:55:38.812  1035  1522 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=195068  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 22:55:38.812  4287  4287 V BluetoothFtpService: Ftp Service onStartCommand
09-13 22:55:38.812  4287  4287 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,09-13 22:55:38.812  4287  4287 V BluetoothFtpService: Ftp Service closeService
09-13 22:55:38.812  4287  4287 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-13 22:55:38.813  1035  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=195069  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 22:55:38.814  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 22:55:38.814  1035  1522 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:148783] from screen [on:0 period:626356286] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 22:55:38.815  1035  1522 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:626356287] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 22:55:38.816  1035  1522 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-13 22:55:38.816  4287  4287 V BluetoothFtpService: successfully stopped ftp service
09-13 22:55:38.817  4287  4287 V BluetoothFtpService: Ftp Service onDestroy
09-13 22:55:38.817  4287  4287 V BluetoothFtpService: Ftp Service closeService
09-13 22:55:38.819  4287  4287 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 22:55:38.819  4287  4287 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 22:55:38.819  4287  4287 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 22:55:38.820  4287  4287 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:38.820  4287  4287 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-13 22:55:38.820  4287  4287 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 22:55:38.821  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:38.822  4287  4287 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:38.822  4287  4287 V BluetoothSapService: state: 13
09-13 22:55:38.822  4287  4287 V BluetoothSapService: Stopping SAP server process
09-13 22:55:38.824  4287  4287 V BluetoothSapService: Sap Service closeSapService in
09-13 22:55:38.824  4287  4287 V BluetoothSapService: Close listen Socket : 
09-13 22:55:38.825  4287  4287 V BluetoothSapService: Close rfcomm Socket : 
09-13 22:55:38.825  4287  4287 V BluetoothSapService: Close sapd  Socket : 
09-13 22:55:38.825  1035  1529 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-13 22:55:38.826  1035  1522 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:38.827  1035  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:38.827  1035  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,09-13 22:55:38.828  1035  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:38.828  1035  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:38.829  1035  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:38.830  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:38.831  1035  1522 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=135,0,0
09-13 22:55:38.831  1035  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-13 22:55:38.831  1035  1522 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=135,0,0
09-13 22:55:38.832  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-13 22:55:38.832  7050  7050 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-13 22:55:38.833  1035  1522 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-13 22:55:38.833  1035  1522 D WifiNative-wlan0: doBoolean: SET ps 0
09-13 22:55:38.834  1035  1522 D WifiNative-wlan0: SET ps 0: returned true
09-13 22:55:38.834  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-13 22:55:38.834  7050  7050 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-13 22:55:38.835  1035  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-13 22:55:38.835  1035  1522 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-13 22:55:38.835  1035  1522 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 22:55:38.835  1035  1519 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3a940513 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.835  1035  1519 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3a940513 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.835  1035  1522 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 22:55:38.836  1035  7100 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.836  1035  7100 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-13 22:55:38.837   315   879 D CommandListener: Setting iface cfg
09-13 22:55:38.837   315   879 D CommandListener: Trying to bring up wlan0
09-13 22:55:38.838  1035  1522 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
,09-13 22:55:38.882  1035  1888 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7101 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-13 22:55:38.883  4287  4287 V BluetoothSapService: Sap Service closeSapService out
09-13 22:55:38.883  4287  4287 V BluetoothSapService: Sap Service onDestroy
09-13 22:55:38.883  4287  4287 V BluetoothSapService: Sap Service closeSapService in
09-13 22:55:38.883  4287  4287 V BluetoothSapService: Close listen Socket : 
09-13 22:55:38.883  4287  4287 V BluetoothSapService: Close rfcomm Socket : 
09-13 22:55:38.883  4287  4287 V BluetoothSapService: Close sapd  Socket : 
09-13 22:55:38.883  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 22:55:38.884  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 22:55:38.884  4287  4287 V BluetoothSapService: Sap Service closeSapService out
09-13 22:55:38.885  1035  1522 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:38.886  1035  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:38.886  1035  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:38.887  1035  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:38.887  1035  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:38.887  1035  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:38.888  1035  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-13 22:55:38.889  1035  1522 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-13 22:55:38.889  1035  1522 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-13 22:55:38.890  1035  1519 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.890  1035  1519 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.890  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 22:55:38.890  7050  7050 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 22:55:38.892  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 22:55:38.892  1035  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 22:55:38.893  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-13 22:55:38.893  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 22:55:38.893  7050  7050 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-13 22:55:38.893  1035  1522 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-13 22:55:38.893  1035  1522 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 22:55:38.893  6986  6986 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 22:55:38.896  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 22:55:38.897  6962  6962 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 22:55:38.897  6962  6962 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 22:55:38.897  6962  6962 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 22:55:38.897  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 22:55:38.898  6962  6962 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 22:55:38.898  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-13 22:55:38.898  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 22:55:38.898  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 22:55:38.898  6962  6962 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 22:55:38.898  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-13 22:55:38.899  6962  6962 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 22:55:38.903  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 22:55:38.909  1035  1522 D WifiNative-wlan0: SET ps 1: returned true
,09-13 22:55:38.909  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 22:55:38.910  1035  1522 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 22:55:38.910  1035  1522 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 22:55:38.911  1035  1522 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-13 22:55:38.912  1035  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-13 22:55:38.913  1035  1529 D ConnectivityService: ignoring duplicate network state non-change
09-13 22:55:38.917  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:38.917  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 22:55:38.917  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:38.917  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:38.917  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 22:55:38.920  1035  1522 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-13 22:55:38.921  1035  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-13 22:55:38.921  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 22:55:38.922  1035  1529 D ConnectivityService: Adding iface wlan0 to network 101
09-13 22:55:38.929  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:38.929  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:38.929  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 22:55:38.932  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-13 22:55:38.935  1926  1926 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-13 22:55:38.936  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:38.936  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:38.936  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,09-13 22:55:38.938  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-13 22:55:38.949  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:38.950  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 22:55:38.952  1035  1529 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-13 22:55:38.952  1035  1529 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-13 22:55:38.953  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 22:55:38.954  1035  1529 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-13 22:55:38.955   315   879 E Netd    : netlink response contains error (File exists)
09-13 22:55:38.956  1035  1529 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-13 22:55:38.956  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:38.956  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 22:55:38.956  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 22:55:38.957  1035  1529 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-13 22:55:38.957  1035  1529 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-13 22:55:38.957  1035  1529 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-13 22:55:38.958  1035  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 22:55:38.958  1035  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-13 22:55:38.958  1035  1529 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-13 22:55:38.958  1035  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-13 22:55:38.958  1035  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 22:55:38.958  1035  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 22:55:38.959  1035  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 22:55:38.959  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:38.959  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 22:55:38.959  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:38.960  1035  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:38.960  1035  7099 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.960  1035  7099 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-13 22:55:38.960  1035  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-13 22:55:38.960  1035  1529 D ConnectivityService: currentScore = 0, newScore = 20
09-13 22:55:38.960  1035  1529 D ConnectivityService:    accepting network in place of null
09-13 22:55:38.960  1035  7099 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:38.961  1035  1529 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:38.961  1035  7099 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-13 22:55:38.963   315  7121 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-13 22:55:38.964  1035  1522 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:38.965  1035  1522 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 22:55:38.965  1836  1836 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:38.966  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Spec,ifier: <-1>]
,09-13 22:55:38.967  1035  1529 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-13 22:55:38.967  1035  1529 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-13 22:55:38.967  1035  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 22:55:38.971  1035  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:38.971  1035  1529 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-13 22:55:38.971  1035  1529 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-13 22:55:38.972  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-13 22:55:38.972  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:38.972  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 22:55:38.972  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 22:55:38.972  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 22:55:38.972  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 22:55:38.972  1035  1529 D ConnectivityService: validation of new default Network = false
09-13 22:55:38.972  1035  1529 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-13 22:55:38.972  1035  1529 D DSQN    : enableDataServiceNotify 
09-13 22:55:38.972  1035  1529 D DSQN    : start dsqn bin
09-13 22:55:38.973  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 22:55:38.976  7122  7122 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 22:55:38.976  7122  7122 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 22:55:38.979  1035  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-13 22:55:38.979  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:38.979  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 22:55:38.981  1035  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 22:55:38.982  1586  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 22:55:38.984  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:38.986  1035  1518 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-13 22:55:38.995  7122  7122 E DSQN    : DSQN ssw
,09-13 22:55:39.002  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 22:55:39.003  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 22:55:39.003  6986  6986 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 22:55:39.005  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 22:55:39.006  7101  7101 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 22:55:39.016  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 22:55:39.017   315  7121 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-13 22:55:39.023  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 22:55:39.024  6804  7071 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 22:55:39.024  6804  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:39.024  6804  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:39.024  6804  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:39.024  6804  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:39.024  6804  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 22:55:39.024  6804  7071 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:39.024  6804  7071 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:55:39.024  6804  7071 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 22:55:39.024  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:39.024  6804  7071 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 22:55:39.024  6804  7071 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:39.024  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:39.025  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:39.030  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 22:55:39.030  1035  1767 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 22:55:39.030  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 22:55:39.030  1035  1767 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@1adb52c1 mBinding = false
09-13 22:55:39.030  6986  6986 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 22:55:39.033  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 22:55:39.037  1035  7100 D DhcpStateMachine: DHCPV4 request on wlan0
09-13 22:55:39.038  1035  7100 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-13 22:55:39.038  1035  7100 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-13 22:55:39.038  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 22:55:39.036  7127  7127 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 22:55:39.036  7127  7127 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 22:55:39.042  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 22:55:39.042  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 22:55:39.042  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-13 22:55:39.043  1035  1117 D BluetoothManagerService: Message: 1
09-13 22:55:39.043  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1adb52c1
,09-13 22:55:39.045  4287  6901 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-13 22:55:39.045  1035  1117 E BluetoothManagerService: IBluetooth.enable() returned false
09-13 22:55:39.047  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:39.048  7127  7127 I dhcpcd  : version 5.5.6 starting
09-13 22:55:39.049  7127  7127 E dhcpcd  : get_duid: m
09-13 22:55:39.049  7127  7127 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-13 22:55:39.049  7127  7127 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-13 22:55:39.051   315  7121 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-13 22:55:39.053  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 22:55:39.053  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 22:55:39.054  6986  6986 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 22:55:39.058  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 22:55:39.064  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 22:55:39.070  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:39.076   315   878 D LGDataListener: argv[0]=dsqncommand
09-13 22:55:39.076  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 22:55:39.076   315   878 D LGDataListener: argv[1]=wlan0
09-13 22:55:39.076   315   878 D LGDataListener: argv[2]=1
09-13 22:55:39.076   315   878 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-13 22:55:39.076  1035  1115 D DSQN    : DSQM DsqnNotification wlan0  1
09-13 22:55:39.076  1035  1115 D DSQN    : start to monitor internet connection
09-13 22:55:39.076  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 22:55:39.077  6986  6986 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 22:55:39.084  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 22:55:39.095  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 22:55:39.101  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:39.102  7127  7127 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-13 22:55:39.102  1035  7099 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 20:55:39 GMT], X-Android-Received-Millis=[1473800139102], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473800139074]}
09-13 22:55:39.102  7127  7127 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-13 22:55:39.102  7127  7127 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-13 22:55:39.102  1035  7099 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-13 22:55:39.102  1035  7099 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-13 22:55:39.102  7127  7127 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-13 22:55:39.102  7127  7127 D dhcpcd  : wlan0: sending REQUEST (xid 0x1806a53f), next in 3.05 seconds
09-13 22:55:39.103  1035  1529 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-13 22:55:39.103  1035  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-13 22:55:39.103  1035  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 22:55:39.103  1035  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 22:55:39.103  1035  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 22:55:39.103  1035  1529 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-13 22:55:39.103  1035  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-13 22:55:39.103  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:39.103  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 22:55:39.104  1035  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 22:55:39.104  1035  1529 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:39.104  1586  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 22:55:39.104  1035  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-13 22:55:39.104  1035  1522 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:39.104  1035  1522 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 22:55:39.105  1836  1836 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:39.105  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 22:55:39.109  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 22:55:39.109  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 22:55:39.114  6986  6986 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 22:55:39.120  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 22:55:39.129  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 22:55:39.132  7127  7127 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-13 22:55:39.136  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:39.144  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 22:55:39.145  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 22:55:39.146  6986  6986 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 22:55:39.149  7127  7127 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-13 22:55:39.149  7127  7127 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-13 22:55:39.149  7127  7127 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-13 22:55:39.149  7127  7127 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-13 22:55:39.150  7127  7127 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-13 22:55:39.150  7127  7127 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-13 22:55:39.150  7127  7127 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-13 22:55:39.150  7127  7127 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-13 22:55:39.152  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 22:55:39.153  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 22:55:39.155  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:39.157  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:39.161  6940  6940 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-13 22:55:39.171  6940  6940 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-13 22:55:39.176  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 22:55:39.184  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:39.193  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 22:55:39.193  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 22:55:39.195  6986  6986 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 22:55:39.196  6986  6986 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 22:55:39.196  6986  6986 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 22:55:39.202  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 22:55:39.210  6940  6940 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-13 22:55:39.212  6940  6940 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 22:55:39.217  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 22:55:39.226  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:39.233  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 22:55:39.233  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 22:55:39.234  6986  6986 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 22:55:39.235  6986  6986 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 22:55:39.236  6986  6986 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 22:55:39.238  1035  1767 I ActivityManager: Killing 6502:com.lge.email/u0a23 (adj 15): empty #17
09-13 22:55:39.313  1035  1051 W libprocessgroup: failed to open /acct/uid_10023/pid_6502/cgroup.procs: No such file or directory
,09-13 22:55:39.440  1035  7100 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-13 22:55:39.441  1035  7100 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,09-13 22:55:39.442  1035  7100 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 22:55:39.442  1035  7100 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-13 22:55:39.442  1035  7100 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-13 22:55:39.442  1035  7100 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 22:55:39.442  1035  7100 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-13 22:55:39.442  1035  7100 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-13 22:55:39.443  1035  7100 D DhcpStateMachine: RunningState
09-13 22:55:39.506  1035  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:39.510  1035  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 22:55:39.515  1035  1117 D Tethering: MasterInitialState.processMessage what=3
09-13 22:55:39.519  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:39.522  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:39.528  1035  1117 D Tethering: MasterInitialState.processMessage what=3
09-13 22:55:39.528  6804  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 22:55:39.529  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:39.529  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:39.529  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:39.529  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:39.529  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 22:55:39.529  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:39.529  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:55:39.529  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 22:55:39.530  6804  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 22:55:39.530  6804  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:39.535  6804  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 22:55:39.535  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:39.535  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:39.535  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:39.535  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:39.535  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 22:55:39.535  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:39.535  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:55:39.535  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 22:55:39.536  6804  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 22:55:39.536  6804  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:39.539  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:39.541  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-13 22:55:39.545  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:39.546  1035  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 22:55:39.546  1035  1998 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@1adb52c1 mBinding = false
09-13 22:55:39.546  1035  1117 D BluetoothManagerService: Message: 1
09-13 22:55:39.546  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1adb52c1
09-13 22:55:39.547  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:39.549  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:39.550  4287  6901 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-13 22:55:39.550  5790  5790 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-13 22:55:39.550  1035  1117 E BluetoothManagerService: IBluetooth.enable() returned false
09-13 22:55:39.550  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-13 22:55:39.554  6408  6937 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-13 22:55:39.563  5790  5790 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-13 22:55:39.563  4287  4366 D bt_hci_bdroid: cleanup
09-13 22:55:39.563  4287  4506 I bt_lpm  : LPM is already off!!!
09-13 22:55:39.563  4287  4605 I bt_userial_mct: exiting userial_read_thread
09-13 22:55:39.563  4287  4605 D bt_userial_mct: Leaving userial_evt_read_thread()
09-13 22:55:39.564  4287  4366 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-13 22:55:39.564  4287  4504 W bt-btif : ag scb idx 1 not allocated
09-13 22:55:39.564  4287  4504 E bt-btif : BTA AG is already disabled, ignoring ...
09-13 22:55:39.564  4287  4504 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 22:55:39.564  4287  4506 I bt_vendor: hw_epilog_process
09-13 22:55:39.564  4287  4504 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 22:55:39.564  4287  4504 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 22:55:39.564  4287  4504 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 22:55:39.564  4287  4504 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 22:55:39.564  4287  4504 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 22:55:39.564  4287  4504 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 22:55:39.564  4287  4504 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 22:55:39.564  4287  4504 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 22:55:39.564  4287  4504 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 22:55:39.564  4287  4504 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 22:55:39.564  4287  4504 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 22:55:39.564  4287  4504 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 22:55:39.564  4287  4504 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 22:55:39.564  4287  4504 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 22:55:39.564  4287  4504 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 22:55:39.564  4287  4366 D bt_hci_bdroid: cleanup Finalizing cleanup
09-13 22:55:39.564  4287  4504 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 22:55:39.564  4287  4366 D bt_userial_mct: userial_close
09-13 22:55:39.564  4287  4504 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 22:55:39.564  4287  4366 E bt_userial_mct: pthread_join() FAILED result:3
09-13 22:55:39.564  4287  4366 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-13 22:55:39.564  4287  4504 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,09-13 22:55:39.583  2182  2182 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 22:55:39.589   315  7166 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 22:55:39.590   315  7166 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-13 22:55:39.622   315  7166 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,09-13 22:55:39.639  1035  1051 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7172 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-13 22:55:39.699  4287  4366 D bt_hci_bdroid: set_power 0
09-13 22:55:39.699  4287  4366 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-13 22:55:39.699  4287  4366 I bt_vendor: bluetooth satus is on
09-13 22:55:39.699  4287  4366 I bt_vendor: bt-vendor : resetting BT status
09-13 22:55:39.699  4287  4366 I bt_vendor: Starting hciattach daemon
09-13 22:55:39.699  4287  4366 I bt_vendor: try to set false
09-13 22:55:39.700  4287  4366 I bt_vendor: Starting hciattach daemon
09-13 22:55:39.700  4287  4366 I bt_vendor: try to set false
09-13 22:55:39.700  4287  4366 I bt_vendor: cleanup
09-13 22:55:39.701  4287  4504 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-13 22:55:39.701  4287  4366 I GKI_LINUX: GKI_exit_task 0 done
09-13 22:55:39.701  4287  4366 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-13 22:55:39.702  4287  4363 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-13 22:55:39.704  4287  4287 D HeadsetService: Received stop request...Stopping profile...
09-13 22:55:39.704  4287  4287 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 22:55:39.704  4287  4287 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 22:55:39.705  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:39.705  4287  4422 D HeadsetStateMachine: Exit Disconnected: -1
09-13 22:55:39.706  1035  1035 D BluetoothHeadset: Proxy object disconnected
09-13 22:55:39.706  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-13 22:55:39.707  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-13 22:55:39.707  4287  4287 D A2dpService: Received stop request...Stopping profile...
09-13 22:55:39.707  4287  4471 D A2dpStateMachine: Exit Disconnected: -1
09-13 22:55:39.708  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-13 22:55:39.709  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-13 22:55:39.709  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-13 22:55:39.709  4287  4287 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-13 22:55:39.709  4287  4287 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 22:55:39.709  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:39.711  1035  1035 D BluetoothA2dp: Proxy object disconnected
09-13 22:55:39.711  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-13 22:55:39.712  4287  4363 D BluetoothAdapterState: Stopping profile services that were post enabled
09-13 22:55:39.712  4287  4287 D HidService: Received stop request...Stopping profile...
09-13 22:55:39.712  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:39.713  4287  4287 D HealthService: Received stop request...Stopping profile...
09-13 22:55:39.713  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:39.714  6962  6962 D BluetoothInputDevice: Proxy object disconnected
09-13 22:55:39.714  6962  6962 D HidProfile: Bluetooth service disconnected
09-13 22:55:39.714  4287  4287 D HeadsetStateMachine: Unbinding service...
09-13 22:55:39.715  4287  4287 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 22:55:39.715  4287  4287 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 22:55:39.715  4287  4287 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 22:55:39.715  4287  4287 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 22:55:39.715  4287  4287 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 22:55:39.715  4287  4287 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 22:55:39.715  4287  4287 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 22:55:39.716  4287  4287 D PanService: Received stop request...Stopping profile...
09-13 22:55:39.717  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:39.717  6962  6962 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 22:55:39.717  6962  6962 D PanProfile: Bluetooth service disconnected
09-13 22:55:39.718  4287  4287 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 22:55:39.718  4287  4287 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 22:55:39.718  4287  4287 D BtGatt.GattService: stop()
09-13 22:55:39.719  4287  4287 D BtGatt.AdvertiseManager: advertise clients cleared
09-13 22:55:39.719  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17,4481f0
09-13 22:55:39.720  4287  4287 I BluetoothA2dpServiceJni: cleanupNative
09-13 22:55:39.720  4287  4472 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-13 22:55:39.720  4287  4287 I GKI_LINUX: GKI_exit_task 2 done
09-13 22:55:39.720  4287  4287 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-13 22:55:39.721  4287  4287 D BluetoothMapService: Received stop request...Stopping profile...
09-13 22:55:39.721  4287  4287 D BluetoothMapService: stop()
09-13 22:55:39.722  4287  4287 D BluetoothMapEmailAppObserver: deinitObservers()
09-13 22:55:39.722  4287  4287 D BluetoothMapEmailAppObserver: removeReceiver()
09-13 22:55:39.722  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:39.722  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:39.723  4287  4287 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 22:55:39.723  6962  6962 D BluetoothMap: Proxy object disconnected
09-13 22:55:39.723  6962  6962 D MapProfile: Bluetooth service disconnected
09-13 22:55:39.723  4287  4287 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-13 22:55:39.724  4287  4287 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 22:55:39.724  4287  4287 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 22:55:39.725  4287  4287 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 22:55:39.725  4287  4287 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 22:55:39.725  4287  4287 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 22:55:39.726  4287  4287 V BluetoothMapService: Handler(): got msg=4
09-13 22:55:39.726  4287  4287 D BluetoothMapService: MAP Service closeService in
09-13 22:55:39.726  4287  4287 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 22:55:39.726  4287  4287 V BluetoothMapService: MAP Service closeService out
09-13 22:55:39.726  4287  4287 D BluetoothMapService: cleanup()
,09-13 22:55:39.726  4287  4287 D BluetoothMapService: MAP Service closeService in
09-13 22:55:39.726  4287  4287 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 22:55:39.726  4287  4287 V BluetoothMapService: MAP Service closeService out
09-13 22:55:39.727  4287  4363 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-13 22:55:39.727  4287  4363 D BluetoothAdapterProperties: Setting state to 10
09-13 22:55:39.727  4287  4363 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-13 22:55:39.727  1035  1117 D BluetoothManagerService: Message: 60
09-13 22:55:39.728  4287  4363 I BluetoothAdapterState: Entering OffState
09-13 22:55:39.728  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-13 22:55:39.728  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-13 22:55:39.728  6962  6979 D BluetoothMap: onBluetoothStateChange: up=false
09-13 22:55:39.728  1836  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 22:55:39.729  6962  6977 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 22:55:39.729  6962  6979 D BluetoothPan: onBluetoothStateChange on: false
09-13 22:55:39.730  1836  4424 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 22:55:39.730  6962  6977 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 22:55:39.731  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 22:55:39.731  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 22:55:39.731  1836  4418 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 22:55:39.731  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-13 22:55:39.734  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:39.735  6962  6962 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-13 22:55:39.735  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 22:55:39.735  6962  6962 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-13 22:55:39.735  6962  6962 D LGBluetoothEventManager: [BTUI] clear device connection state
,09-13 22:55:39.736  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:39.737  1926  2120 D LGBluetoothAPIService: Message: 2
09-13 22:55:39.738  1926  2120 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@f2649c3 mBinding = false
09-13 22:55:39.738  1926  2120 D LGBluetoothAPIService: Sending unbind request.
09-13 22:55:39.738  4287  4287 D LGBluetoothAPIServer: [BTUI] onUnbind()
09-13 22:55:39.738  4287  4287 D LGBluetoothAPIServer: [BTUI] cleanup() done
09-13 22:55:39.740  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:39.740  4287  4287 D LGBluetoothAPIServer: [BTUI] onDestroy()
09-13 22:55:39.741  6962  6962 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 22:55:39.743  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:39.746  7172  7172 I AppUp4:AppBoxCP: onCreate
,09-13 22:55:39.747  7172  7172 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
09-13 22:55:39.747  6962  6962 D DockEventReceiver: finishStartingService: stopping service
09-13 22:55:39.749  4287  4287 V BluetoothPbapReceiver: PbapReceiver onReceive 
,09-13 22:55:39.749  4287  4287 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:39.749  4287  4287 V BluetoothPbapReceiver: ***********state = 10
09-13 22:55:39.753  2182  2182 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 22:55:39.755  7172  7172 I AppUp4:DB:  setFingerPrint start
09-13 22:55:39.755  7172  7172 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-13 22:55:39.762  7172  7172 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-13 22:55:39.762  7172  7172 I AppUp4:DB:  SDK version = 21
,09-13 22:55:39.762  7172  7172 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-13 22:55:39.764  6962  6962 D BluetoothPermissionRequest: onReceive
09-13 22:55:39.765  7172  7172 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-13 22:55:39.766  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 22:55:39.766  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:39.767  6962  6962 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 22:55:39.767  6962  6962 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-13 22:55:39.767  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 22:55:39.768  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 22:55:39.769  6962  6962 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 22:55:39.775  7172  7172 I AppUp4:CustModeStarterReceiver: onReceive
,09-13 22:55:39.776  4287  4287 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:39.778  4287  4287 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 22:55:39.778  4287  4287 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 22:55:39.778  4287  4287 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 22:55:39.778  4287  4287 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:39.778  4287  4287 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-13 22:55:39.784  7101  7101 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-13 22:55:39.804  7172  7172 D LgDataFeature: LgDataFeature() Constructor: none
09-13 22:55:39.804  7172  7172 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 22:55:39.811  7172  7172 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@14363a33
09-13 22:55:39.811  7172  7172 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 22:55:39.811  7172  7172 D AppUp4:CustFacade: isPhone : true
09-13 22:55:39.812  7172  7172 D AppUp4:CustModeStarterReceiver: begin check event
09-13 22:55:39.812  7172  7172 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-13 22:55:39.812  7172  7172 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-13 22:55:39.813  7172  7192 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-13 22:55:39.813  7172  7192 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-13 22:55:39.813  7172  7192 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-13 22:55:39.818  1035  1050 I ActivityManager: Killing 6040:com.android.gallery3d/u0a27 (adj 15): empty #17
,09-13 22:55:39.902  2182  7190 D GCM     : Connected
09-13 22:55:39.903  1035  1925 W libprocessgroup: failed to open /acct/uid_10027/pid_6040/cgroup.procs: No such file or directory
09-13 22:55:39.906  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:39.907  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 22:55:39.914  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 22:55:39.920  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 22:55:39.929  3389  3389 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:39.931  4747  7195 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 22:55:39.934  3389  3389 V DownloadManager: DownloadService onCreate
09-13 22:55:39.934  4747  7195 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,09-13 22:55:39.937  2182  7190 D GCM     : Message class com.google.e.a.a.q
09-13 22:55:39.940  4747  7196 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:39.940  4747  7196 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 22:55:39.942  3389  7197 I DownloadManager: in removeSpuriousFiles
09-13 22:55:39.943  3389  7197 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-13 22:55:39.944  3389  7197 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@23960c14 on behalf of 3389
09-13 22:55:39.944  3389  7197 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-13 22:55:39.944  3389  7197 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-13 22:55:39.945  3389  7197 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-13 22:55:39.945  3389  7197 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-13 22:55:39.945  3389  7197 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-13 22:55:39.945  3389  7197 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
,09-13 22:55:39.945  3389  7197 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-13 22:55:39.945  3389  7197 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-13 22:55:39.945  3389  7197 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-13 22:55:39.945  3389  7197 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-13 22:55:39.945  3389  7197 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-13 22:55:39.946  3389  7197 I DownloadManager: in trimDatabase
09-13 22:55:39.947  3389  7197 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-13 22:55:39.947  3389  7197 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@a096cbd on behalf of 3389
09-13 22:55:39.980  1035  1529 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-13 22:55:39.984  1035  1051 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7201 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
09-13 22:55:39.989  3389  3389 V DownloadManager: DownloadService onStartCommand
09-13 22:55:39.991  3389  7198 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-13 22:55:39.992  4747  7195 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-13 22:55:39.994  3389  7198 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3d1d580 on behalf of 3389
,09-13 22:55:39.999  4747  4747 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-13 22:55:39.999  4747  4747 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-13 22:55:39.999  4747  4747 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-13 22:55:40.002  4747  4747 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-13 22:55:40.005   359   359 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 436us total 20.026ms
09-13 22:55:40.006  4747  4747 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-13 22:55:40.008  3389  7198 V DownloadManager: processing inserted download 1
09-13 22:55:40.011  3389  7198 V DownloadManager: processing inserted download 4
,09-13 22:55:40.012  3389  7198 V DownloadManager: processing inserted download 7
,09-13 22:55:40.014  3389  7198 V DownloadManager: processing inserted download 8
09-13 22:55:40.015  3389  7198 V DownloadManager: processing inserted download 9
09-13 22:55:40.016  3389  7198 V DownloadManager: processing inserted download 10
09-13 22:55:40.017  3389  7198 V DownloadManager: processing inserted download 11
09-13 22:55:40.019  3389  7198 V DownloadManager: processing inserted download 12
09-13 22:55:40.021  3389  7198 V DownloadManager: processing inserted download 13
09-13 22:55:40.022  3389  7198 V DownloadManager: processing inserted download 14
09-13 22:55:40.023  3389  7198 V DownloadManager: processing inserted download 16
,09-13 22:55:40.026   359   359 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 409us total 20.318ms
09-13 22:55:40.026  3389  3389 V DownloadManager: DownloadService onDestroy
,09-13 22:55:40.045   359   359 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 405us total 18.762ms
,09-13 22:55:40.047  1035  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 22:55:40.047  1035  1924 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@1adb52c1 mBinding = false
09-13 22:55:40.048  1035  1117 D BluetoothManagerService: Message: 1
09-13 22:55:40.048  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1adb52c1
09-13 22:55:40.050  4287  4363 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-13 22:55:40.050  4287  4363 D BluetoothAdapterProperties: Setting state to 11
09-13 22:55:40.050  4287  4363 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-13 22:55:40.050  1035  1117 D BluetoothManagerService: Message: 60
09-13 22:55:40.050  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-13 22:55:40.050  4287  4363 D BluetoothBondStateMachine: make
09-13 22:55:40.050  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-13 22:55:40.051  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:40.052  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 22:55:40.053  4287  4363 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:40.053  4287  4363 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-13 22:55:40.053  4287  4363 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:40.053  4287  4363 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-13 22:55:40.053  4287  4363 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-13 22:55:40.053  4287  7218 I BluetoothBondStateMachine: StableState(): Entering Off State
09-13 22:55:40.054  6962  6962 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-13 22:55:40.055  4287  4363 E BluetoothAdapterService: File transfer profiles supported!!
09-13 22:55:40.056  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:40.058  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:40.059  4287  4287 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 22:55:40.059  4287  4287 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:40.059  4287  4287 V BluetoothPbapReceiver: ***********state = 11
,09-13 22:55:40.063  4287  4363 E BluetoothAdapterService: File transfer profiles supported!!
09-13 22:55:40.063  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:40.064  2182  2182 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 22:55:40.064  7201  7201 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 22:55:40.065  7201  7201 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 22:55:40.066  7201  7201 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 22:55:40.066  7201  7201 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-13 22:55:40.067  4287  4287 D HeadsetService: Received start request. Starting profile...
09-13 22:55:40.067  4287  4287 D HeadsetStateMachine: make
09-13 22:55:40.076  4287  4363 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 22:55:40.078  4287  4287 D HeadsetStateMachine: max_hf_connections = 1
09-13 22:55:40.079  4287  4287 I bluedroid-qcom: get_profile_interface handsfree
09-13 22:55:40.079  4287  4287 E LGBluetoothDtmfAdapter: LGBluetoothDtmfLocalPlay is not null
09-13 22:55:40.079  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:40.079  4287  7219 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-13 22:55:40.079  4287  7219 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 22:55:40.079  4287  7219 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 22:55:40.079  4287  7219 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-13 22:55:40.080   320  2128 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 4287
09-13 22:55:40.081   320  2128 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-13 22:55:40.081   320  2128 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-13 22:55:40.081   320  2128 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-13 22:55:40.081   320  2128 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-13 22:55:40.081   320  2128 V voice   : voice_set_parameters: exit with code(0)
09-13 22:55:40.081   320  2128 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-13 22:55:40.081   320  2128 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-13 22:55:40.081   320  2128 V msm8974_platform: platform_set_parameters: exit with code(0)
09-13 22:55:40.081   320  2128 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-13 22:55:40.081   320  2128 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-13 22:55:40.081   320  2128 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-13 22:55:40.082  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:40.083  4287  4287 D A2dpService: Received start request. Starting profile...
09-13 22:55:40.083  4287  4287 V Avrcp   : make
09-13 22:55:40.083  4287  4287 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-13 22:55:40.083  4287  4287 I bluedroid-qcom: get_profile_interface avrcp
09-13 22:55:40.084  4287  4363 E BluetoothAdapterService: File transfer profiles supported!!
09-13 22:55:40.087  6962  6962 D BluetoothPermissionRequest: onReceive
09-13 22:55:40.089  4287  4287 V AudioManager: registerRemoteController: size of Media player list: 0
,09-13 22:55:40.090  4287  4363 E BluetoothAdapterService: File transfer profiles supported!!
09-13 22:55:40.092  6962  6962 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 22:55:40.101  4287  4363 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 22:55:40.107  4287  4363 E BluetoothAdapterService: File transfer profiles supported!!
09-13 22:55:40.110  4287  4363 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-13 22:55:40.152  7201  7201 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-13 22:55:40.177  1035  1971 I art     : Explicit concurrent mark sweep GC freed 123753(5MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 1.407ms total 87.134ms
,09-13 22:55:40.179  4287  4287 E AudioManager: No RCC entry present to update
09-13 22:55:40.180  4287  4287 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-13 22:55:40.180  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-13 22:55:40.180  4287  4287 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-13 22:55:40.184  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-13 22:55:40.190  1035  1522 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 22:55:40.190  1035  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 22:55:40.190  1035  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 22:55:40.190  1035  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 22:55:40.190  1035  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 22:55:40.191  1035  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 22:55:40.191  1035  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
09-13 22:55:40.191  1035  1529 D ConnectivityService: identical MTU - not setting
09-13 22:55:40.191  1035  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 22:55:40.191  1035  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-13 22:55:40.191  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:40.191  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-13 22:55:40.192  1035  1529 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 22:55:40.193  1586  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-13 22:55:40.195  7201  7201 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
09-13 22:55:40.239  7201  7201 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-13 22:55:40.270  7201  7201 D LgDataFeature: LgDataFeature() Constructor: none
09-13 22:55:40.270  7201  7201 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 22:55:40.285  1035  1888 V SIM_STK : Menu title from STK is T-Mobile
09-13 22:55:40.286  1035  1888 V SIM_STK : Menu title from STK is T-Mobile
,09-13 22:55:40.364  7201  7201 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-13 22:55:40.390  3275  3275 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 22:55:40.390  3275  3275 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,09-13 22:55:40.391  3275  3275 I LgeMiscReceiver: networkInfo.isConnected() = false
09-13 22:55:40.402  7201  7201 I HubEmail: JNI_OnLoad()
09-13 22:55:40.402  7201  7201 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,09-13 22:55:40.402  7201  7201 I HubEmail: registerNatives()
09-13 22:55:40.402  7201  7201 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-13 22:55:40.402  7201  7201 I HubEmail: registerNativeMethods()
09-13 22:55:40.402  7201  7201 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-13 22:55:40.403  7201  7201 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,09-13 22:55:40.419   315  7233 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 22:55:40.419   315  7233 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,09-13 22:55:40.427  1035  2016 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7234 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
09-13 22:55:40.428  1035  1051 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-13 22:55:40.428  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-13 22:55:40.428  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-13 22:55:40.428  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-13 22:55:40.428  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-13 22:55:40.428  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-13 22:55:40.428  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 22:55:40.428  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-13 22:55:40.429  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-13 22:55:40.429  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-13 22:55:40.429  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 22:55:40.429  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-13 22:55:40.429  4287  4287 D A2dpStateMachine: make
09-13 22:55:40.430  4287  4287 I bluedroid-qcom: get_profile_interface a2dp
09-13 22:55:40.430  4287  7244 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-13 22:55:40.431  4287  4287 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-13 22:55:40.431  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:40.431  4287  7243 D A2dpStateMachine: Enter Disconnected: -2
09-13 22:55:40.431  4287  4287 D HeadsetStateMachine: Proxy object connected
09-13 22:55:40.431  4287  4287 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-13 22:55:40.431  4287  4287 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-13 22:55:40.432  7201  7231 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:40.433  4287  4287 D HidService: Received start request. Starting profile...
09-13 22:55:40.433  4287  4287 I bluedroid-qcom: get_profile_interface hidhost
09-13 22:55:40.433  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:40.435  4287  4287 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 22:55:40.435  4287  7219 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-13 22:55:40.435  4287  7219 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 22:55:40.435  4287  7219 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-13 22:55:40.435  4287  4287 D HealthService: Received start request. Starting profile...
09-13 22:55:40.436  4287  4287 I bluedroid-qcom: get_profile_interface health
,09-13 22:55:40.436  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:40.437  4287  4287 D PanService: Received start request. Starting profile...
09-13 22:55:40.437  4287  4287 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 22:55:40.437  4287  4287 I bluedroid-qcom: get_profile_interface pan
09-13 22:55:40.438  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:40.438  4287  4287 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 22:55:40.439  4287  4287 D BtGatt.GattService: Received start request. Starting profile...
09-13 22:55:40.439  4287  4287 D BtGatt.GattService: start()
09-13 22:55:40.439  4287  4287 D BtGatt.AdvertiseManager: advertise manager created
09-13 22:55:40.444  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:40.445  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
,09-13 22:55:40.445  4287  4287 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-13 22:55:40.445  4287  4287 V BluetoothMapService: BluetoothMapBinder()
09-13 22:55:40.445  4287  4287 D BluetoothMapService: Received start request. Starting profile...
09-13 22:55:40.445  4287  4287 D BluetoothMapService: start()
09-13 22:55:40.446  4287  4287 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-13 22:55:40.446  4287  4287 D BluetoothMapEmailAppObserver: createReceiver()
09-13 22:55:40.447  4287  4287 D BluetoothMapEmailAppObserver: initObservers()
09-13 22:55:40.447  4287  4287 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-13 22:55:40.447  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
,09-13 22:55:40.449  4287  4287 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 22:55:40.451  4287  4287 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 22:55:40.452  4287  4287 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 22:55:40.454  4287  4287 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:40.455  4287  4287 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 22:55:40.455  4287  4287 V PanService: [BTUI] SIM Extra State :ABSENT
09-13 22:55:40.457  4287  4287 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-13 22:55:40.457  4287  4287 V BluetoothMapService: Handler(): got msg=1
09-13 22:55:40.457  4287  4363 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-13 22:55:40.457  4287  4363 I bluedroid-qcom: enable
09-13 22:55:40.457  4287  4287 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 22:55:40.457  4287  4287 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 22:55:40.457  4287  4287 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 22:55:40.458  4287  7258 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-13 22:55:40.458  4287  7258 I bt-btu  : btu_task pending for preload complete event
09-13 22:55:40.458  4287  4363 I bt_hci_bdroid: init
,09-13 22:55:40.458   315  7233 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
09-13 22:55:40.458  4287  4363 I bt_vendor: bt-vendor : init
09-13 22:55:40.458  4287  4363 I bt_vendor: bt-vendor : get_bt_soc_type
09-13 22:55:40.458  4287  4363 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-13 22:55:40.458  4287  4363 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-13 22:55:40.458  4287  4363 D bt_userial_mct: userial_init
,09-13 22:55:40.458  4287  4287 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:40.459  4287  4287 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,09-13 22:55:40.459  4287  4363 D bt_hci_bdroid: set_power 1
09-13 22:55:40.459  4287  4363 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-13 22:55:40.459  4287  4363 I bt_vendor: Starting hciattach daemon
09-13 22:55:40.456  7261  7261 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 22:55:40.459  4287  4363 I bt_vendor: try to set true
09-13 22:55:40.456  7261  7261 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 22:55:40.477  7262  7262 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-13 22:55:40.511  7006  7230 V FormManager: There are no updated forms. The schedule will be deleted.
,09-13 22:55:40.512  7006  7230 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
,09-13 22:55:40.528  1035  1971 I ActivityManager: Killing 6575:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,09-13 22:55:40.535  7234  7234 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 22:55:40.535  7234  7234 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 22:55:40.537  7234  7234 D PhoneMonitor: Register our PhoneStateListener
09-13 22:55:40.540  7268  7268 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
09-13 22:55:40.550  7269  7269 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-13 22:55:40.567  7271  7271 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-13 22:55:40.577  7272  7272 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-13 22:55:40.590  7273  7273 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-13 22:55:40.600  1035  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 22:55:40.601  1035  1889 W libprocessgroup: failed to open /acct/uid_10061/pid_6575/cgroup.procs: No such file or directory
,09-13 22:55:40.601  1035  1943 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@1adb52c1 mBinding = false
,09-13 22:55:40.602  1035  1117 D BluetoothManagerService: Message: 1
,09-13 22:55:40.602  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1adb52c1
,09-13 22:55:40.602  7274  7274 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-13 22:55:40.607  4287  4306 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
,09-13 22:55:40.607  1035  1117 E BluetoothManagerService: IBluetooth.enable() returned false
,09-13 22:55:40.616  7234  7234 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-13 22:55:40.619  7234  7234 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-13 22:55:40.621  7276  7276 I libmdmdetect: ESOC framework not supported
09-13 22:55:40.621  7276  7276 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
09-13 22:55:40.626  7276  7276 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,09-13 22:55:40.626  7276  7276 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-13 22:55:40.626  7276  7276 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-13 22:55:40.626  7276  7276 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-13 22:55:40.626  7276  7276 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-13 22:55:40.627  7276  7276 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-13 22:55:40.627  7276  7276 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,09-13 22:55:40.633  7234  7234 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,09-13 22:55:40.636  7234  7234 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-13 22:55:40.636  7234  7234 D TelephonyAutoProfiling: [parse] Load xml
09-13 22:55:40.639  7234  7234 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,09-13 22:55:40.639  7234  7234 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-13 22:55:40.639  7234  7234 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-13 22:55:40.639  7234  7234 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-13 22:55:40.640  7234  7234 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
,09-13 22:55:40.640  7234  7234 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-13 22:55:40.640  7234  7234 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-13 22:55:40.640  7234  7234 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-13 22:55:40.640  7234  7234 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-13 22:55:40.640  7234  7234 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-13 22:55:40.640  7234  7234 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-13 22:55:40.640  7234  7234 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-13 22:55:40.640  7234  7234 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-13 22:55:40.640  7234  7234 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-13 22:55:40.641  7234  7234 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-13 22:55:40.641  7234  7234 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-13 22:55:40.641  7234  7234 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,09-13 22:55:40.648  7234  7234 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-13 22:55:40.659  7276  7278 E QC-QMI  : qmi_client [7276] 14: failed to locate client data
,09-13 22:55:40.661   476   476 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-13 22:55:40.661   476   476 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
09-13 22:55:40.680  1035  1998 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7280 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 22:55:40.683  1035  1998 I ActivityManager: Killing 6622:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
09-13 22:55:40.757  7300  7300 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-13 22:55:40.775  1035  1924 W libprocessgroup: failed to open /acct/uid_10080/pid_6622/cgroup.procs: No such file or directory
,09-13 22:55:40.780  7301  7301 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-13 22:55:40.807  1801  7303 I CheckinService: active receiver: enabled
09-13 22:55:40.810  4287  4363 I bt_vendor: bluetooth satus is on
09-13 22:55:40.810  4287  4363 D bt_hci_bdroid: preload
09-13 22:55:40.811  4287  7260 D bt_userial_mct: userial_open(port:0)
09-13 22:55:40.811  4287  7260 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-13 22:55:40.811  4287  7260 I bt_vendor: Done intiailizing UART
09-13 22:55:40.811  4287  7260 I bt_vendor: Done intiailizing UART
09-13 22:55:40.811  4287  7260 I bt_userial_mct: CMD=82, EVT=82, ACL_Out=83, ACL_In=83
09-13 22:55:40.812  4287  7260 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-13 22:55:40.812  4287  7304 D bt_userial_mct: Entering userial_read_thread()
09-13 22:55:40.812  4287  7258 I bt-btu  : btu_task received preload complete event
09-13 22:55:40.812  4287  7258 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-13 22:55:40.812  4287  7258 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-13 22:55:40.812  4287  7258 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,09-13 22:55:40.823  4287  7258 I         : BTE_InitTraceLevels -- TRC_HCI
09-13 22:55:40.823  4287  7258 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 22:55:40.823  4287  7258 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 22:55:40.823  4287  7258 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 22:55:40.823  4287  7258 I         : BTE_InitTraceLevels -- TRC_AVRC
09-13 22:55:40.823  4287  7258 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 22:55:40.823  4287  7258 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 22:55:40.823  4287  7258 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 22:55:40.823  4287  7258 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-13 22:55:40.823  4287  7258 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 22:55:40.824  4287  7258 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 22:55:40.824  4287  7258 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 22:55:40.824  4287  7258 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 22:55:40.824  4287  7258 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 22:55:40.824  4287  7258 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 22:55:40.824  4287  7258 I         : BTE_InitTraceLevels -- TRC_BTIF
09-13 22:55:40.825  1801  7303 I CheckinService: Preparing to send checkin request
09-13 22:55:40.825  1801  7303 I EventLogService: Accumulating logs since 1473799986781
09-13 22:55:40.864  1801  7303 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-13 22:55:40.892  4287  7258 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-13 22:55:40.892  4287  7258 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01a2061 
09-13 22:55:40.892  4287  7258 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01a2061 
,09-13 22:55:40.914  4287  4366 E bt-btif : Calling BTA_HhEnable
09-13 22:55:40.914  4287  4366 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,09-13 22:55:40.915  4287  4366 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-13 22:55:40.915  4287  7258 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-13 22:55:40.915  4287  7258 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-13 22:55:40.915  4287  7258 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-13 22:55:40.915  4287  7258 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-13 22:55:40.915  4287  7258 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-13 22:55:40.916  4287  4366 D BluetoothAdapterProperties: Name is: G3
,09-13 22:55:40.916  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,09-13 22:55:40.916  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
09-13 22:55:40.917  4287  4366 D BluetoothAdapterProperties: Scan Mode:20
09-13 22:55:40.917  4287  4366 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 22:55:40.917  4287  4366 D bt_hci_bdroid: postload
09-13 22:55:40.917  4287  7258 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-13 22:55:40.917  4287  4366 D bte_conf: Device ID record 1 : primary
09-13 22:55:40.917  4287  4366 D bte_conf:   vendorId            = 00c4
09-13 22:55:40.917  4287  4366 D bte_conf:   vendorIdSource      = 0001
09-13 22:55:40.917  4287  4366 D bte_conf:   product             = 13a1
09-13 22:55:40.917  4287  4366 D bte_conf:   version             = 1000
,09-13 22:55:40.917  4287  7260 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 22:55:40.916  7313  7313 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 22:55:40.917  4287  4366 D bte_conf:   clientExecutableURL = 
09-13 22:55:40.916  7313  7313 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 22:55:40.917  4287  4366 D bte_conf:   serviceDescription  = 
09-13 22:55:40.917  4287  4366 D bte_conf:   documentationURL    = 
09-13 22:55:40.917  4287  4366 D bte_conf: bte_load_did_conf no section named DID2.
09-13 22:55:40.919  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:40.920  4287  7260 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 22:55:40.920  4287  4366 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-13 22:55:40.921  4287  4363 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-13 22:55:40.921  4287  4363 D BluetoothAdapterProperties: ScanMode =  20
09-13 22:55:40.921  4287  4363 D BluetoothAdapterProperties: State =  11
09-13 22:55:40.921  4287  4363 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-13 22:55:40.921  4287  4363 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-13 22:55:40.921  4287  4363 D BluetoothAdapterProperties: Setting state to 12
09-13 22:55:40.921  4287  4363 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 22:55:40.921  1035  1117 D BluetoothManagerService: Message: 60
09-13 22:55:40.921  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-13 22:55:40.921  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-13 22:55:40.922  4287  4363 I BluetoothAdapterState: Entering On State
09-13 22:55:40.922  4287  4366 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 22:55:40.922  4287  4363 D LGBluetoothServiceAdapter: [BTUI] OnState
09-13 22:55:40.922  4287  4363 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-13 22:55:40.922  4287  4363 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-13 22:55:40.923  4287  4363 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-13 22:55:40.924  6962  6977 D BluetoothMap: onBluetoothStateChange: up=true
09-13 22:55:40.925  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:40.925  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:40.925  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:40.925  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:40.925  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:40.925  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:40.925  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:55:40.925  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 22:55:40.930  4287  7260 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 22:55:40.930  1836  2384 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 22:55:40.930  4287  7260 D bt_hci_bdroid: Used up Tx Cmd credits
,09-13 22:55:40.937  4287  7260 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 22:55:40.938  4287  7304 E bt_mct  : hci lib postload completed
09-13 22:55:40.941  6804  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:40.945  1836  1836 D BluetoothHeadset: Proxy object connected
09-13 22:55:40.947  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:40.947  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:40.947  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:40.947  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:40.947  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:40.947  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:40.947  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:55:40.947  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 22:55:40.949  6804  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:40.949  6962  6977 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 22:55:40.951  4287  7258 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 22:55:40.951  4287  7258 W bt-smp  : Plain text(LSB ~ MSB) = 56 15 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 22:55:40.951  4287  7258 W bt-smp  : Encrypted text(LSB ~ MSB) = 7e 4a 37 fa 72 b9 9c 54 d1 7d af 70 80 03 4a 27 
09-13 22:55:40.951  4287  7258 W bt-btm  : Stopping oneshot timer
09-13 22:55:40.951  6962  6979 D BluetoothPan: onBluetoothStateChange on: true
09-13 22:55:40.951  6962  6979 D BluetoothPan: onBluetoothStateChange call bindService
09-13 22:55:40.954  4287  4366 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 22:55:40.954  4287  4366 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-13 22:55:40.956  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 22:55:40.957  1836  1836 D BluetoothHeadset: Proxy object connected
09-13 22:55:40.958  6962  6977 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 22:55:40.959  6962  6962 D BluetoothMap: Proxy object connected
09-13 22:55:40.959  6962  6962 D MapProfile: Bluetooth service connected
09-13 22:55:40.959  6962  6962 D BluetoothMap: getConnectedDevices()
09-13 22:55:40.963  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 22:55:40.964  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 22:55:40.964  1035  1035 D BluetoothHeadset: Proxy object connected
09-13 22:55:40.964  1836  4424 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 22:55:40.970  1035  1035 D BluetoothA2dp: Proxy object connected
09-13 22:55:40.970  4287  7258 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 22:55:40.970  4287  7258 W bt-smp  : Plain text(LSB ~ MSB) = 82 96 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 22:55:40.970  4287  7258 W bt-smp  : Encrypted text(LSB ~ MSB) = 91 f5 ba f9 bc 37 9e 4f e7 52 32 32 ce d3 8f 13 
09-13 22:55:40.970  4287  7258 W bt-btm  : Stopping oneshot timer
09-13 22:55:40.971  1836  1836 D BluetoothHeadset: Proxy object connected
09-13 22:55:40.972  4287  4363 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-13 22:55:40.972  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-13 22:55:40.972  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-13 22:55:40.977  4287  4306 V BluetoothMapService: getConnectedDevices()
09-13 22:55:40.977  7320  7320 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-13 22:55:40.979  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:40.980  1926  2120 D LGBluetoothAPIService: Message: 1
09-13 22:55:40.980  1926  2120 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,09-13 22:55:40.980  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 22:55:40.981  6804  6804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-13 22:55:40.983  1926  2120 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-13 22:55:40.985  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:40.985  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:40.985  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:40.985  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:40.985  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:40.985  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:40.985  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:55:40.985  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 22:55:40.987  4287  4287 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:40.987  4287  4287 D BluetoothMapService: STATE_ON
09-13 22:55:40.987  4287  4287 D LGBluetoothAPIServer: [BTUI] onCreate()
09-13 22:55:40.988  4287  4287 D LGBluetoothAPIServer: [BTUI] onBind()
09-13 22:55:40.988  6804  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:40.989  6962  6962 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 22:55:40.989  6962  6962 D PanProfile: Bluetooth service connected
09-13 22:55:40.990  1926  1926 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,09-13 22:55:40.990  1926  2120 D LGBluetoothAPIService: Message: 100
09-13 22:55:40.990  1926  2120 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-13 22:55:40.990  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:40.991  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:40.991  4287  4287 V BluetoothPbapService: Pbap Service onCreate
09-13 22:55:40.991  4287  4287 V BluetoothPbapService: Starting PBAP service
09-13 22:55:40.991  4287  7258 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 22:55:40.991  4287  7258 W bt-smp  : Plain text(LSB ~ MSB) = bb 46 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 22:55:40.991  4287  7258 W bt-smp  : Encrypted text(LSB ~ MSB) = e8 9f 75 5f df 9e 13 33 c6 48 ac b5 ca 60 76 1d 
09-13 22:55:40.991  4287  7258 W bt-btm  : Stopping oneshot timer
,09-13 22:55:40.992  4287  4287 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-13 22:55:40.992  4287  4287 V BluetoothPbapService: Pbap Service onBind
09-13 22:55:40.992  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:40.992  6962  6962 D BluetoothInputDevice: Proxy object connected
09-13 22:55:40.992  6962  6962 D HidProfile: Bluetooth service connected
09-13 22:55:40.993  4287  4287 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:40.993  4287  4287 V BluetoothPbapService: state: 12
09-13 22:55:40.993  4287  4287 V BluetoothMapService: Handler(): got msg=1
09-13 22:55:40.993  4287  4287 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-13 22:55:40.994  4287  4287 V BluetoothPbapService: Handler(): got msg=1
09-13 22:55:40.994  4287  4287 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-13 22:55:40.994  4287  7323 D BluetoothMapMasInstance: MAS initSocket()
09-13 22:55:40.995  4287  7323 D BluetoothMapMasInstance:   masId = 00
09-13 22:55:40.995  4287  7323 D BluetoothMapMasInstance:   msgTypes = 0e
09-13 22:55:40.995  4287  7323 D BluetoothMapMasInstance:   masName = SMS/MMS
09-13 22:55:40.995  4287  7323 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-13 22:55:40.995  1035  1979 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 22:55:40.995  4287  7324 V BluetoothPbapService: Pbap Service initSocket
09-13 22:55:40.995  6962  6962 D LocalBluetoothProfileManager: Adding local A2DP profile
09-13 22:55:40.997  1035  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 22:55:40.997  1035  1117 D BluetoothManagerService: Message: 30
09-13 22:55:40.998  4287  7324 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 22:55:40.999  4287  7323 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 22:55:40.999  4287  7324 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=87 mFd=82
09-13 22:55:40.999  4287  7324 V BluetoothPbapService: Succeed to create listening socket 
09-13 22:55:40.999  4287  7324 V BluetoothPbapService: Accepting socket connection...
09-13 22:55:41.000  4287  7258 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 22:55:41.000  4287  7258 W bt-smp  : Plain text(LSB ~ MSB) = 6b a0 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 22:55:41.000  4287  7258 W bt-smp  : Encrypted text(LSB ~ MSB) = db b1 6b fe 41 b9 25 8c 20 a5 3e 2e 1b d4 25 e6 
09-13 22:55:41.000  4287  7258 W bt-btm  : Stopping oneshot timer
09-13 22:55:41.000  4287  7323 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=89 mFd=87
09-13 22:55:41.000  4287  7323 V BluetoothMapMasInstance: Succeed to create listening socket 
09-13 22:55:41.000  4287  7323 D BluetoothMapMasInstance: Accepting socket connection...
09-13 22:55:41.001  4287  4366 D BluetoothAdapterProperties: Scan Mode:21
09-13 22:55:41.001  4287  4366 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-13 22:55:41.003  6962  6962 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-13 22:55:41.003  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:55:41.004  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:41.005  1035  1117 D BluetoothManagerService: Message: 30
09-13 22:55:41.006  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:41.008  4287  7258 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 22:55:41.008  4287  7258 W bt-smp  : Plain text(LSB ~ MSB) = 63 6b 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 22:55:41.008  4287  7258 W bt-smp  : Encrypted text(LSB ~ MSB) = 41 29 bc b9 36 01 12 fb 14 2d 01 41 5f 7d 38 89 
09-13 22:55:41.008  4287  7258 W bt-btm  : Stopping oneshot timer
09-13 22:55:41.009  6962  6962 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-13 22:55:41.011  6962  6962 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 22:55:41.043  1035  1050 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7325 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,09-13 22:55:41.080  1035  2016 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7342 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-13 22:55:41.082  6962  6962 D BluetoothPbap: Proxy object connected
09-13 22:55:41.082  6962  6962 D PbapServerProfile: Bluetooth service connected
09-13 22:55:41.082  6962  6962 D BluetoothA2dp: Proxy object connected
09-13 22:55:41.083  6962  6962 D A2dpProfile: Bluetooth service connected
09-13 22:55:41.089  4287  4287 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 22:55:41.089  4287  4287 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:41.089  4287  4287 V BluetoothPbapReceiver: ***********state = 12
09-13 22:55:41.090  6962  6962 D BluetoothHeadset: Proxy object connected
09-13 22:55:41.092  2182  2182 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 22:55:41.092  6962  6962 D HeadsetProfile: Bluetooth service connected
09-13 22:55:41.092  2182  2182 D c       : Getting all permits...
09-13 22:55:41.092  2182  2182 D a       : Opening database...
09-13 22:55:41.095  2182  2182 D a       : Opening database auth.proximity.permit_store...
09-13 22:55:41.096  6962  6962 D DockEventReceiver: finishStartingService: stopping service
09-13 22:55:41.096  2182  2182 D a       : Closing database...
,09-13 22:55:41.103  6804  7126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:41.104  6804  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:55:41.104  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 22:55:41.115  6962  6962 D BluetoothPermissionRequest: onReceive
09-13 22:55:41.115  1035  1767 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 22:55:41.115  1035  1767 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1adb52c1 mBinding = false
09-13 22:55:41.117  6962  6962 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 22:55:41.118  6962  6962 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 22:55:41.120  1035  1889 I ActivityManager: Killing 6647:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-13 22:55:41.127  1035  1117 D BluetoothManagerService: Message: 2
09-13 22:55:41.128  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 22:55:41.128  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 22:55:41.128  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,09-13 22:55:41.128  1035  1117 D BluetoothManagerService: Sending off request.
09-13 22:55:41.128  4287  7321 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-13 22:55:41.129  4287  4363 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-13 22:55:41.129  4287  4363 D BluetoothAdapterProperties: Setting state to 13
09-13 22:55:41.129  4287  4363 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 22:55:41.129  4287  4363 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 22:55:41.129  4287  4363 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-13 22:55:41.129  1035  1117 D BluetoothManagerService: Message: 60
09-13 22:55:41.129  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-13 22:55:41.129  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-13 22:55:41.132  7342  7342 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-13 22:55:41.132  7342  7342 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-13 22:55:41.149  7342  7342 I MultiDex: VM with version 2.1.0 has multidex support
09-13 22:55:41.149  7342  7342 I MultiDex: install
09-13 22:55:41.149  7342  7342 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-13 22:55:41.170  4287  4287 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,09-13 22:55:41.171  4287  4287 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-13 22:55:41.173  1035  1979 W libprocessgroup: failed to open /acct/uid_10097/pid_6647/cgroup.procs: No such file or directory
09-13 22:55:41.173  4287  4366 D BluetoothAdapterProperties: Scan Mode:20
09-13 22:55:41.173  4287  4363 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-13 22:55:41.173  4287  7324 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 22:55:41.173  4287  4363 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 22:55:41.173  4287  7258 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-13 22:55:41.173  4287  7258 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-13 22:55:41.174  4287  7323 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-13 22:55:41.174  4287  7323 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 22:55:41.174  4287  7323 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-13 22:55:41.174  4287  7323 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-13 22:55:41.174  4287  7323 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-13 22:55:41.174  4287  7323 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-13 22:55:41.174  4287  7323 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-13 22:55:41.174  4287  7323 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-13 22:55:41.175  4287  7258 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 22:55:41.175  4287  7258 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 22:55:41.175  4287  7258 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 22:55:41.175  4287  7258 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 22:55:41.175  4287  7258 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 22:55:41.175  4287  7258 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 22:55:41.175  4287  7258 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 22:55:41.175  4287  7258 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 22:55:41.175  4287  7258 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 22:55:41.175  4287  7258 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-13 22:55:41.175  4287  7258 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-13 22:55:41.176  4287  7258 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 22:55:41.180  4287  4287 V BtOppService: onCreate
09-13 22:55:41.180  4287  4287 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-13 22:55:41.183  6804  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 22:55:41.183  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:41.183  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:41.183  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:41.183  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:41.183  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 22:55:41.183  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:41.183  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:55:41.183  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 22:55:41.183  4287  4287 V BluetoothOppNotification: send message
09-13 22:55:41.185  6804  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 22:55:41.185  6804  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:41.187  4287  7363 V BtOppService: Deleted complete outbound shares, number =  0
09-13 22:55:41.189  4287  7363 V BtOppService: Deleted complete inbound failed shares, number = 0
09-13 22:55:41.189  4287  7363 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-13 22:55:41.189  6804  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 22:55:41.189  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:41.189  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:41.189  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:41.189  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:41.189  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 22:55:41.189  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:41.189  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:55:41.189  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 22:55:41.190  4287  7363 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@132c026c on behalf of 
09-13 22:55:41.190  6804  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 22:55:41.190  6804  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:41.204  1035  1889 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7364 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 22:55:41.205  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 22:55:41.206  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:41.208  4287  4287 D BluetoothOppPreference: Dumping Names:  
09-13 22:55:41.209  4287  4287 D BluetoothOppPreference: {}
09-13 22:55:41.209  4287  4287 D BluetoothOppPreference: Dumping Channels:  
09-13 22:55:41.209  4287  4287 D BluetoothOppPreference: {}
09-13 22:55:41.209  4287  4287 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
09-13 22:55:41.209  1035  1889 I ActivityManager: Killing 6682:com.lge.eula/1000 (adj 15): empty #17
09-13 22:55:41.209  4287  4287 V BtOppService: onStartCommand
09-13 22:55:41.210  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:41.211  4287  4287 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
09-13 22:55:41.212  4287  4287 V BluetoothOppNotification: previous thread is not finished yet
09-13 22:55:41.212  4287  4287 V BtOppService: ContentObserver received notification
09-13 22:55:41.212  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:41.212  4287  4287 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
09-13 22:55:41.212  4287  4287 V BtOppService: ContentObserver received notification
09-13 22:55:41.212  4287  4287 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
09-13 22:55:41.212  4287  4287 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:41.212  6962  6962 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
09-13 22:55:41.212  4287  4287 D BluetoothMapService: STATE_TURNING_OFF
09-13 22:55:41.212  4287  4287 V BluetoothMapService: Handler(): got msg=4
09-13 22:55:41.212  4287  4287 D BluetoothMapService: MAP Service closeService in
09-13 22:55:41.212  4287  4287 D BluetoothMapMasInstance: MAP Service shutdown
09-13 22:55:41.212  4287  4287 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 22:55:41.212  4287  4287 V BluetoothMapService: MAP Service closeService out
09-13 22:55:41.252  1035  1767 W libprocessgroup: failed to open /acct/uid_1000/pid_6682/cgroup.procs: No such file or directory
,09-13 22:55:41.257  4287  4287 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:41.257  4287  4287 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 22:55:41.257  7342  7342 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-13 22:55:41.258  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:41.259  4287  4287 V BluetoothFtpService: Ftp Service onCreate
09-13 22:55:41.259  4287  4287 I BluetoothFtpService: Ftp Service onCreate
09-13 22:55:41.259  4287  4287 V BluetoothFtpService: Ftp Service onStartCommand
09-13 22:55:41.259  4287  4287 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:41.259  4287  4287 V BluetoothFtpService: Starting Listening on sockets
09-13 22:55:41.259  4287  4287 V BluetoothFtpService: Handler(): got msg=1
09-13 22:55:41.259  4287  4287 V BluetoothFtpService: Ftp Service closeService
09-13 22:55:41.261  4287  4287 V BluetoothFtpService: successfully stopped ftp service
09-13 22:55:41.261  4287  4287 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 22:55:41.261  4287  4287 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 22:55:41.261  4287  4287 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 22:55:41.261  4287  4287 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:41.261  4287  4287 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-13 22:55:41.261  4287  4287 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 22:55:41.265  4287  4287 V BluetoothFtpService: Ftp Service onDestroy
09-13 22:55:41.265  4287  4287 V BluetoothFtpService: Ftp Service closeService
,09-13 22:55:41.272  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:41.272  4287  4287 V BluetoothSapService: Sap Service onCreate
09-13 22:55:41.275  4287  4287 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:41.275  4287  4287 V BluetoothSapService: state: 12
09-13 22:55:41.275  4287  4287 V BluetoothSapService: Starting SAP server process
09-13 22:55:41.266  7381  7381 W sapd    : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 22:55:41.266  7381  7381 W sapd    : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 22:55:41.284  7364  7364 I art     : Almond Protected OAT
09-13 22:55:41.286  6962  6962 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 22:55:41.289  7381  7381 V BT_SAP  : Event pipe created
09-13 22:55:41.289  7381  7381 V BT_SAP  : create_server_socket qcom.sap.server
09-13 22:55:41.289  7381  7381 V BT_SAP  : created socket fd 6
09-13 22:55:41.291  4287  4287 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 22:55:41.291  4287  4287 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,09-13 22:55:41.291  4287  4287 V BluetoothPbapReceiver: ***********state = 13
09-13 22:55:41.292  6962  6962 D DockEventReceiver: finishStartingService: stopping service
09-13 22:55:41.296  4287  4287 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-13 22:55:41.296  4287  4287 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:41.296  4287  4287 V BluetoothPbapService: state: 13
09-13 22:55:41.296  4287  4287 V BluetoothPbapService: Pbap Service closeService in
09-13 22:55:41.298  4287  4287 V BluetoothPbapService: successfully stopped pbap service
09-13 22:55:41.298  4287  4287 V BluetoothPbapService: Pbap Service closeService out
09-13 22:55:41.298  2182  2182 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 22:55:41.299  4287  4287 V BluetoothPbapService: Pbap Service onDestroy
09-13 22:55:41.299  4287  4287 V BluetoothPbapService: Pbap Service closeService in
09-13 22:55:41.299  4287  4287 V BluetoothPbapService: Pbap Service closeService out
09-13 22:55:41.299  4287  4287 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-13 22:55:41.299  6962  6962 D BluetoothPbap: Proxy object disconnected
09-13 22:55:41.299  6962  6962 D PbapServerProfile: Bluetooth service disconnected
09-13 22:55:41.306  6962  6962 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-13 22:55:41.311  6962  6962 D BluetoothPermissionRequest: onReceive
09-13 22:55:41.312  6962  6962 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-13 22:55:41.315  6962  6962 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 22:55:41.318  4287  4287 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-13 22:55:41.318  4287  4287 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,09-13 22:55:41.318  4287  4287 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-13 22:55:41.321  4287  4287 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:41.321  4287  4287 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 22:55:41.323  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:41.323  4287  4287 V BluetoothFtpService: Ftp Service onCreate
09-13 22:55:41.323  4287  4287 I BluetoothFtpService: Ftp Service onCreate
09-13 22:55:41.323  4287  4287 V BluetoothFtpService: Ftp Service onStartCommand
09-13 22:55:41.323  4287  4287 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:41.324  4287  4287 V BluetoothFtpService: Ftp Service closeService
09-13 22:55:41.324  4287  4287 V BluetoothFtpService: successfully stopped ftp service
09-13 22:55:41.324  4287  4287 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 22:55:41.324  4287  4287 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 22:55:41.324  4287  4287 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 22:55:41.324  4287  4287 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:41.324  4287  4287 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-13 22:55:41.324  4287  4287 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 22:55:41.325  4287  4287 V BluetoothFtpService: Ftp Service onDestroy
09-13 22:55:41.325  4287  4287 V BluetoothFtpService: Ftp Service closeService
09-13 22:55:41.328  4287  4287 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:41.328  4287  4287 V BluetoothSapService: state: 13
09-13 22:55:41.328  4287  4287 V BluetoothSapService: Stopping SAP server process
09-13 22:55:41.328  4287  4287 V BluetoothSapService: Sap Service closeSapService in
09-13 22:55:41.328  4287  4287 V BluetoothSapService: Close listen Socket : 
09-13 22:55:41.328  4287  4287 V BluetoothSapService: Close rfcomm Socket : 
09-13 22:55:41.328  4287  4287 V BluetoothSapService: Close sapd  Socket : 
09-13 22:55:41.330  4287  4287 V BluetoothSapService: Sap Service closeSapService out
09-13 22:55:41.330  4287  4287 V BluetoothSapService: Sap Service onDestroy
09-13 22:55:41.330  4287  4287 V BluetoothSapService: Sap Service closeSapService in
09-13 22:55:41.330  4287  4287 V BluetoothSapService: Close listen Socket : 
09-13 22:55:41.330  4287  4287 V BluetoothSapService: Close rfcomm Socket : 
09-13 22:55:41.330  4287  4287 V BluetoothSapService: Close sapd  Socket : 
09-13 22:55:41.330  4287  4287 V BluetoothSapService: Sap Service closeSapService out
,09-13 22:55:41.342  7364  7364 D WeatherApplication: removeAccount
09-13 22:55:41.343  7364  7364 D WeatherApplication: Account.length = 0
09-13 22:55:41.343  7364  7364 E WeatherApplication: OPERATOR:OPEN
,09-13 22:55:41.348  7364  7364 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:55:41
09-13 22:55:41.350  7364  7364 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 22:55:41.351  7364  7364 D Weather.Utils: 2 : All the weather widget is gone.
09-13 22:55:41.352  7364  7364 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 22:55:41.354  7364  7364 D WeatherAncestor: connectivity changed - connection : true
09-13 22:55:41.354  7364  7364 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-13 22:55:41.362  7364  7364 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 22:55:41.362  7364  7364 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 22:55:41.362  7364  7364 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,09-13 22:55:41.383  7364  7364 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 22:55:41.384  7364  7364 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:55:41
,09-13 22:55:41.407  1035  1519 D LGWifiP2pService: InactiveState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 22:55:41.407  1035  1519 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:41.407  1035  1519 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:41.417  1035  1597 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7385 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 22:55:41.418  1035  1597 I ActivityManager: Killing 2109:com.lge.music/u0a34 (adj 15): empty #17
09-13 22:55:41.433   320  1365 V AudioFlinger: 2109 died, releasing its sessions
09-13 22:55:41.433   320  1365 V AudioFlinger:  pid 1836 @ 0
09-13 22:55:41.433   320  1365 V AudioFlinger:  pid 3275 @ 1
09-13 22:55:41.433   320  1365 V AudioFlinger:  pid 3275 @ 2
,09-13 22:55:41.511  1035  1522 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-13 22:55:41.512  1035  1522 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 22:55:41.512  1035  1522 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 22:55:41.512  1035  1522 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 22:55:41.513  1035  1522 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 22:55:41.513  1035  1522 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-13 22:55:41.514  1035  1998 W libprocessgroup: failed to open /acct/uid_10034/pid_2109/cgroup.procs: No such file or directory
09-13 22:55:41.544  7342  7359 D LgDataFeature: LgDataFeature() Constructor: none
09-13 22:55:41.544  7342  7359 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 22:55:41.600   277   360 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 22:55:41.600   277   360 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-13 22:55:41.601   277   360 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 22:55:41.601  7385  7405 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-13 22:55:41.603   277   360 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 22:55:41.603   277   360 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-13 22:55:41.603   277   360 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 22:55:41.603  7385  7405 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,09-13 22:55:41.607  7402  7402 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
09-13 22:55:41.618   277   360 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 22:55:41.618   277   360 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-13 22:55:41.618   277   360 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 22:55:41.619  7385  7408 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-13 22:55:41.629   277   360 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 22:55:41.629   277   360 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-13 22:55:41.629   277   360 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 22:55:41.630  7385  7408 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-13 22:55:41.631  6804  7360 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 22:55:41.631  6804  7360 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:41.631  6804  7360 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:41.631  6804  7360 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:41.631  6804  7360 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:41.631  6804  7360 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 22:55:41.631  6804  7360 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:41.631  6804  7360 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:55:41.631  6804  7360 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 22:55:41.633  6804  7360 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 22:55:41.633  6804  7360 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:41.638  6804  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:41.641  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 22:55:41.641  1035  1050 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@1adb52c1 mBinding = false
,09-13 22:55:41.652  1035  1117 D BluetoothManagerService: Message: 1
09-13 22:55:41.652  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1adb52c1
09-13 22:55:41.652  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 22:55:41.652  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 22:55:41.652  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-13 22:55:41.655  4287  7322 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-13 22:55:41.656  1035  1117 E BluetoothManagerService: IBluetooth.enable() returned false
,09-13 22:55:41.670  7402  7402 I dex2oat : dex2oat took 63.179ms (threads: 4)
,09-13 22:55:41.686  7342  7359 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 22:55:41.686  7342  7359 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 22:55:41.686  7342  7359 I Adreno-EGL: Build Date: 12/12/14 금
09-13 22:55:41.686  7342  7359 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 22:55:41.686  7342  7359 I Adreno-EGL: Remote Branch: 
09-13 22:55:41.686  7342  7359 I Adreno-EGL: Local Patches: 
09-13 22:55:41.686  7342  7359 I Adreno-EGL: Reconstruct Branch: 
,09-13 22:55:41.801  7385  7385 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-13 22:55:41.807  7385  7385 I LibraryLoader: Loading: webviewchromium
09-13 22:55:41.809  7385  7385 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 8078-8080)
09-13 22:55:41.809  7385  7385 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 22:55:41.813  7385  7385 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a42aaa}
09-13 22:55:41.814  7385  7385 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 22:55:41.814  7385  7385 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 22:55:41.820  7385  7385 I BrowserStartupController: Initializing chromium process, renderers=0
09-13 22:55:41.821  7385  7385 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 22:55:41.825  1035  1522 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2437 sc=60 link=72 tx=67.5, 0.0, 0.0  rx=72.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:626359297] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 22:55:41.826  1035  1522 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2437 sc=60 link=72 tx=67.5, 0.0, 0.0  rx=72.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:626359298] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 22:55:41.826  1035  1522 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-13 22:55:41.832   320   320 V AudioPolicyService: registerClient() client 0xb558ade0, uid 10093
09-13 22:55:41.833  7385  7436 W AudioManagerAndroid: Requires BLUETOOTH permission
09-13 22:55:41.833  7385  7385 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-13 22:55:41.834  7385  7385 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-13 22:55:41.835  7385  7385 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-13 22:55:41.843  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 22:55:41.850  7385  7385 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 22:55:41.850  7385  7385 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 22:55:41.850  7385  7385 I Adreno-EGL: Build Date: 12/12/14 금
09-13 22:55:41.850  7385  7385 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 22:55:41.850  7385  7385 I Adreno-EGL: Remote Branch: 
09-13 22:55:41.850  7385  7385 I Adreno-EGL: Local Patches: 
09-13 22:55:41.850  7385  7385 I Adreno-EGL: Reconstruct Branch: 
09-13 22:55:41.927  7385  7385 I NSApplication: Starting up...
,09-13 22:55:41.933  1035  1524 V WifiInternetCheck: Single check msg out of sync, ignoring.
,09-13 22:55:41.973  1035  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 22:55:41.994  1035  2034 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7449 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-13 22:55:41.997  1035  2034 I ActivityManager: Killing 6530:com.android.vending/u0a44 (adj 15): empty #17
,09-13 22:55:42.021  7342  7359 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 22:55:42.021  7342  7359 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 22:55:42.021  7342  7359 I Adreno-EGL: Build Date: 12/12/14 금
09-13 22:55:42.021  7342  7359 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 22:55:42.021  7342  7359 I Adreno-EGL: Remote Branch: 
09-13 22:55:42.021  7342  7359 I Adreno-EGL: Local Patches: 
09-13 22:55:42.021  7342  7359 I Adreno-EGL: Reconstruct Branch: 
,09-13 22:55:42.072  7342  7359 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 22:55:42.072  7342  7359 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 22:55:42.072  7342  7359 I Adreno-EGL: Build Date: 12/12/14 금
09-13 22:55:42.072  7342  7359 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 22:55:42.072  7342  7359 I Adreno-EGL: Remote Branch: 
09-13 22:55:42.072  7342  7359 I Adreno-EGL: Local Patches: 
09-13 22:55:42.072  7342  7359 I Adreno-EGL: Reconstruct Branch: 
,09-13 22:55:42.127  1035  1051 W libprocessgroup: failed to open /acct/uid_10044/pid_6530/cgroup.procs: No such file or directory,
,09-13 22:55:42.152  1035  1117 D Tethering: MasterInitialState.processMessage what=3
09-13 22:55:42.152  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-13 22:55:42.160  1035  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 22:55:42.160  1035  1888 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@1adb52c1 mBinding = false
09-13 22:55:42.160  1035  1117 D BluetoothManagerService: Message: 1
09-13 22:55:42.160  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1adb52c1
09-13 22:55:42.163  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:42.163  4287  7321 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-13 22:55:42.163  1035  1117 E BluetoothManagerService: IBluetooth.enable() returned false
09-13 22:55:42.166  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:42.166  5790  5790 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-13 22:55:42.167  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-13 22:55:42.177  4287  4366 D bt_hci_bdroid: cleanup
09-13 22:55:42.177  4287  7258 W bt-btif : ag scb idx 1 not allocated
09-13 22:55:42.177  4287  7258 E bt-btif : BTA AG is already disabled, ignoring ...
09-13 22:55:42.177  4287  7258 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 22:55:42.177  4287  7258 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 22:55:42.177  4287  7258 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 22:55:42.177  4287  7260 I bt_lpm  : LPM is already off!!!
09-13 22:55:42.178  4287  7258 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 22:55:42.178  4287  7304 I bt_userial_mct: exiting userial_read_thread
09-13 22:55:42.178  4287  7304 D bt_userial_mct: Leaving userial_evt_read_thread()
09-13 22:55:42.178  4287  7258 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 22:55:42.178  4287  7258 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 22:55:42.178  4287  7258 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 22:55:42.178  4287  7258 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 22:55:42.178  4287  7258 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 22:55:42.178  4287  4366 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-13 22:55:42.178  4287  7258 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 22:55:42.178  4287  7260 I bt_vendor: hw_epilog_process
09-13 22:55:42.178  4287  7258 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 22:55:42.178  4287  7258 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 22:55:42.178  4287  7258 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 22:55:42.178  4287  7258 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 22:55:42.178  4287  7258 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 22:55:42.178  4287  7258 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 22:55:42.178  4287  4366 D bt_hci_bdroid: cleanup Finalizing cleanup
09-13 22:55:42.178  4287  4366 D bt_userial_mct: userial_close
09-13 22:55:42.178  4287  7258 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 22:55:42.178  4287  7258 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 22:55:42.178  4287  4366 E bt_userial_mct: pthread_join() FAILED result:3
09-13 22:55:42.178  4287  4366 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-13 22:55:42.178  4287  7258 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 22:55:42.187  7449  7449 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 22:55:42.196   315  7468 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 22:55:42.197   315  7468 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
09-13 22:55:42.213  4287  4287 V BluetoothOppNotification: previous thread is not finished yet
,09-13 22:55:42.276   315  7468 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,09-13 22:55:42.299  4287  4366 D bt_hci_bdroid: set_power 0
09-13 22:55:42.299  4287  4366 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-13 22:55:42.299  4287  4366 I bt_vendor: bluetooth satus is on
09-13 22:55:42.299  4287  4366 I bt_vendor: bt-vendor : resetting BT status
09-13 22:55:42.299  4287  4366 I bt_vendor: Starting hciattach daemon
09-13 22:55:42.299  4287  4366 I bt_vendor: try to set false
09-13 22:55:42.300  4287  4366 I bt_vendor: Starting hciattach daemon
09-13 22:55:42.300  4287  4366 I bt_vendor: try to set false
,09-13 22:55:42.300  4287  4366 I bt_vendor: cleanup
09-13 22:55:42.301  4287  7258 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-13 22:55:42.301  4287  4366 I GKI_LINUX: GKI_exit_task 0 done
09-13 22:55:42.301  4287  4366 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-13 22:55:42.303  4287  4363 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-13 22:55:42.305  4287  4287 D HeadsetService: Received stop request...Stopping profile...
09-13 22:55:42.306  4287  4287 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 22:55:42.306  4287  7219 D HeadsetStateMachine: Exit Disconnected: -1
09-13 22:55:42.306  4287  4287 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 22:55:42.306  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:42.309  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-13 22:55:42.309  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-13 22:55:42.309  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-13 22:55:42.311  1035  1035 D BluetoothHeadset: Proxy object disconnected
09-13 22:55:42.311  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-13 22:55:42.312  4287  4287 D A2dpService: Received stop request...Stopping profile...
,09-13 22:55:42.312  4287  7243 D A2dpStateMachine: Exit Disconnected: -1
09-13 22:55:42.313  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-13 22:55:42.315  4287  4363 D BluetoothAdapterState: Stopping profile services that were post enabled
09-13 22:55:42.315  4287  4287 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-13 22:55:42.315  4287  4287 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 22:55:42.315  6962  6962 D BluetoothHeadset: Proxy object disconnected
09-13 22:55:42.316  6962  6962 D HeadsetProfile: Bluetooth service disconnected
09-13 22:55:42.316  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:42.317  1035  1035 D BluetoothA2dp: Proxy object disconnected
09-13 22:55:42.317  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-13 22:55:42.318  4287  4287 D HidService: Received stop request...Stopping profile...
09-13 22:55:42.318  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:42.319  6962  6962 D BluetoothA2dp: Proxy object disconnected
09-13 22:55:42.319  6962  6962 D A2dpProfile: Bluetooth service disconnected
09-13 22:55:42.319  4287  4287 D HeadsetStateMachine: Unbinding service...
09-13 22:55:42.320  6962  6962 D BluetoothInputDevice: Proxy object disconnected
09-13 22:55:42.320  6962  6962 D HidProfile: Bluetooth service disconnected
09-13 22:55:42.320  4287  4287 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 22:55:42.320  4287  4287 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 22:55:42.320  4287  4287 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 22:55:42.320  4287  4287 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 22:55:42.320  4287  4287 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 22:55:42.320  4287  4287 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 22:55:42.320  4287  4287 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 22:55:42.321  4287  4287 D HealthService: Received stop request...Stopping profile...
09-13 22:55:42.321  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:42.322  4287  4287 D PanService: Received stop request...Stopping profile...
09-13 22:55:42.322  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:42.323  6962  6962 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 22:55:42.323  6962  6962 D PanProfile: Bluetooth service disconnected
09-13 22:55:42.323  4287  4287 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 22:55:42.323  4287  4287 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 22:55:42.323  4287  4287 D BtGatt.GattService: stop()
09-13 22:55:42.324  4287  4287 D BtGatt.AdvertiseManager: advertise clients cleared
09-13 22:55:42.324  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:42.325  4287  4287 D BluetoothMapService: Received stop request...Stopping profile...
09-13 22:55:42.325  4287  4287 D BluetoothMapService: stop()
09-13 22:55:42.326  4287  4287 D BluetoothMapEmailAppObserver: deinitObservers()
09-13 22:55:42.326  4287  4287 D BluetoothMapEmailAppObserver: removeReceiver()
09-13 22:55:42.326  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:42.328  4287  4287 I BluetoothA2dpServiceJni: cleanupNative
09-13 22:55:42.328  4287  7244 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-13 22:55:42.329  4287  4287 I GKI_LINUX: GKI_exit_task 2 done
,09-13 22:55:42.329  4287  4287 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-13 22:55:42.329  4287  4287 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 22:55:42.329  4287  4287 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 22:55:42.329  4287  4287 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 22:55:42.330  4287  4287 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 22:55:42.330  4287  4287 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 22:55:42.330  4287  4287 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 22:55:42.330  4287  4287 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 22:55:42.330  6962  6962 D BluetoothMap: Proxy object disconnected
09-13 22:55:42.330  6962  6962 D MapProfile: Bluetooth service disconnected
09-13 22:55:42.333  4287  4287 V BluetoothMapService: Handler(): got msg=4
09-13 22:55:42.333  4287  4287 D BluetoothMapService: MAP Service closeService in
09-13 22:55:42.333  4287  4287 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 22:55:42.333  4287  4287 V BluetoothMapService: MAP Service closeService out
09-13 22:55:42.333  4287  4363 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-13 22:55:42.333  4287  4363 D BluetoothAdapterProperties: Setting state to 10
09-13 22:55:42.333  4287  4363 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-13 22:55:42.333  4287  4287 D BluetoothMapService: cleanup()
09-13 22:55:42.333  4287  4287 D BluetoothMapService: MAP Service closeService in
09-13 22:55:42.333  4287  4287 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 22:55:42.333  4287  4287 V BluetoothMapService: MAP Service closeService out
09-13 22:55:42.334  1035  1117 D BluetoothManagerService: Message: 60
09-13 22:55:42.334  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-13 22:55:42.334  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-13 22:55:42.335  4287  4363 I BluetoothAdapterState: Entering OffState
09-13 22:55:42.335  6962  6977 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 22:55:42.335  6962  6979 D BluetoothMap: onBluetoothStateChange: up=false
09-13 22:55:42.336  1836  2384 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 22:55:42.336  6962  7318 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 22:55:42.337  6962  6977 D BluetoothPan: onBluetoothStateChange on: false
09-13 22:55:42.337  1836  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 22:55:42.338  6962  6979 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 22:55:42.338  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 22:55:42.338  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 22:55:42.338  6962  7318 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 22:55:42.340  1836  4418 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 22:55:42.341  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-13 22:55:42.344  6962  6962 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-13 22:55:42.344  6962  6962 D LGBluetoothEventManager: [BTUI] clear device connection state
09-13 22:55:42.345  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:42.345  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 22:55:42.346  1926  2120 D LGBluetoothAPIService: Message: 2
09-13 22:55:42.346  1926  2120 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2d990240 mBinding = false
09-13 22:55:42.346  1926  2120 D LGBluetoothAPIService: Sending unbind request.
09-13 22:55:42.348  6962  6962 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 22:55:42.349  4287  4287 D LGBluetoothAPIServer: [BTUI] onUnbind()
09-13 22:55:42.349  4287  4287 D LGBluetoothAPIServer: [BTUI] cleanup() done
09-13 22:55:42.349  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:42.349  4287  4287 D LGBluetoothAPIServer: [BTUI] onDestroy()
09-13 22:55:42.351  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:42.353  4287  4287 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 22:55:42.353  4287  4287 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:42.353  4287  4287 V BluetoothPbapReceiver: ***********state = 10
09-13 22:55:42.353  6962  6962 D DockEventReceiver: finishStartingService: stopping service
,09-13 22:55:42.359  2182  2182 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 22:55:42.369  6962  6962 D BluetoothPermissionRequest: onReceive
09-13 22:55:42.371  6962  6962 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 22:55:42.371  6962  6962 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-13 22:55:42.373  6962  6962 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 22:55:42.380  4287  4287 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:42.382  4287  4287 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 22:55:42.382  4287  4287 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 22:55:42.382  4287  4287 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 22:55:42.382  4287  4287 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:42.382  4287  4287 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,09-13 22:55:42.387  7101  7101 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-13 22:55:42.410  1801  7303 I CheckinTask: Sending checkin request (7940 bytes)
,09-13 22:55:42.468  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-13 22:55:42.471  6408  6937 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 22:55:42.489  2182  2182 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 22:55:42.499  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 22:55:42.499  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:42.500  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 22:55:42.500  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 22:55:42.502  7172  7172 I AppUp4:CustModeStarterReceiver: onReceive
,09-13 22:55:42.508  7172  7172 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@14363a33
09-13 22:55:42.508  7172  7172 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 22:55:42.508  7172  7172 D AppUp4:CustFacade: isPhone : true
09-13 22:55:42.509  7172  7172 D AppUp4:CustModeStarterReceiver: begin check event
09-13 22:55:42.509  7172  7172 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 22:55:42.516  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:42.517  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-13 22:55:42.519  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 22:55:42.521  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 22:55:42.524  3389  3389 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:42.526  3389  3389 V DownloadManager: DownloadService onCreate
09-13 22:55:42.527  4747  7477 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 22:55:42.528  3389  7478 I DownloadManager: in removeSpuriousFiles
09-13 22:55:42.529  4747  7477 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,09-13 22:55:42.534  4747  7480 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:42.534  4747  7480 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 22:55:42.534  3389  7478 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-13 22:55:42.538  3389  7478 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3a5ba7fe on behalf of 3389
09-13 22:55:42.544  3389  7478 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-13 22:55:42.545  3389  7478 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-13 22:55:42.545  3389  7478 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-13 22:55:42.545  3389  7478 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-13 22:55:42.545  3389  7478 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-13 22:55:42.545  3389  7478 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-13 22:55:42.545  3389  7478 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-13 22:55:42.545  3389  7478 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-13 22:55:42.545  3389  7478 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-13 22:55:42.545  3275  3275 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 22:55:42.545  3275  3275 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:42.545  3275  3275 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-13 22:55:42.548  4747  7477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-13 22:55:42.548  7234  7234 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 22:55:42.548  3389  7478 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
,09-13 22:55:42.548  3389  7478 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-13 22:55:42.549  3389  7478 I DownloadManager: in trimDatabase
09-13 22:55:42.549  3389  7478 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-13 22:55:42.550  3389  7478 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@32aa1b5f on behalf of 3389
09-13 22:55:42.550  7234  7234 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 22:55:42.550  4747  4747 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-13 22:55:42.553  4747  4747 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
,09-13 22:55:42.553  4747  4747 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-13 22:55:42.555  4747  4747 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-13 22:55:42.557  4747  4747 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-13 22:55:42.558  7364  7364 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:55:42
09-13 22:55:42.558  3389  3389 V DownloadManager: DownloadService onStartCommand
09-13 22:55:42.559  3389  7479 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,09-13 22:55:42.560  7201  7481 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:42.561  7364  7364 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 22:55:42.561  7364  7364 D Weather.Utils: 2 : All the weather widget is gone.
09-13 22:55:42.562  7364  7364 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 22:55:42.562  7364  7364 D WeatherAncestor: connectivity changed - connection : true
09-13 22:55:42.562  7364  7364 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3762a369
09-13 22:55:42.562  7364  7364 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 22:55:42.562  7364  7364 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 22:55:42.562  7364  7364 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 22:55:42.562  7364  7364 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 22:55:42.563  7364  7364 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:55:42
09-13 22:55:42.563  3389  7479 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2c6460a on behalf of 3389
09-13 22:55:42.564  3389  7479 V DownloadManager: processing inserted download 1
09-13 22:55:42.565  3389  7479 V DownloadManager: processing inserted download 4
09-13 22:55:42.567  3389  7479 V DownloadManager: processing inserted download 7
09-13 22:55:42.568  3389  7479 V DownloadManager: processing inserted download 8
09-13 22:55:42.568  3389  7479 V DownloadManager: processing inserted download 9
09-13 22:55:42.571  3389  7479 V DownloadManager: processing inserted download 10
09-13 22:55:42.571  3389  7479 V DownloadManager: processing inserted download 11
,09-13 22:55:42.572  3389  7479 V DownloadManager: processing inserted download 12
09-13 22:55:42.573  3389  7479 V DownloadManager: processing inserted download 13
09-13 22:55:42.573  3389  7479 V DownloadManager: processing inserted download 14
09-13 22:55:42.574  3389  7479 V DownloadManager: processing inserted download 16
09-13 22:55:42.577  3389  3389 V DownloadManager: DownloadService onDestroy
,09-13 22:55:42.592  2182  2182 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-13 22:55:42.599  2182  2182 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-13 22:55:42.599  2182  2182 D c       : Getting all permits...
09-13 22:55:42.599  2182  2182 D a       : Opening database...
09-13 22:55:42.603  2182  2182 D a       : Opening database auth.proximity.permit_store...
09-13 22:55:42.603  2182  2182 D a       : Closing database...
09-13 22:55:42.610  7006  7486 V FormManager: There are no updated forms. The schedule will be deleted.
09-13 22:55:42.611  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-13 22:55:42.613  6408  6937 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-13 22:55:42.615  7006  7486 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-13 22:55:42.627  2182  2182 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:42.632  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 22:55:42.633  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:42.633  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 22:55:42.633  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 22:55:42.634  7172  7172 I AppUp4:CustModeStarterReceiver: onReceive
09-13 22:55:42.636  7172  7172 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@14363a33
09-13 22:55:42.636  7172  7172 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 22:55:42.636  7172  7172 D AppUp4:CustFacade: isPhone : true
09-13 22:55:42.636  7172  7172 D AppUp4:CustModeStarterReceiver: begin check event
09-13 22:55:42.636  7172  7172 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,09-13 22:55:42.638  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:42.638  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 22:55:42.640  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 22:55:42.641  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 22:55:42.645  3389  3389 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:42.646  3389  3389 V DownloadManager: DownloadService onCreate
09-13 22:55:42.649  4747  7494 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 22:55:42.650  3389  7495 I DownloadManager: in removeSpuriousFiles
,09-13 22:55:42.651  4747  7497 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:42.651  4747  7497 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 22:55:42.651  3389  7495 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-13 22:55:42.654  4747  7494 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-13 22:55:42.657  3389  7495 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2b8504f1 on behalf of 3389
09-13 22:55:42.657  3389  7495 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-13 22:55:42.657  3389  7495 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-13 22:55:42.657  3389  7495 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-13 22:55:42.657  3389  7495 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-13 22:55:42.657  3389  7495 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-13 22:55:42.657  3389  7495 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-13 22:55:42.657  3389  7495 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-13 22:55:42.657  3389  7495 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-13 22:55:42.657  3389  7495 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-13 22:55:42.657  3389  7495 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-13 22:55:42.657  3389  7495 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-13 22:55:42.658  3389  3389 V DownloadManager: DownloadService onStartCommand
09-13 22:55:42.658  3389  7496 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-13 22:55:42.660  3389  7495 I DownloadManager: in trimDatabase
09-13 22:55:42.661  3389  7495 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-13 22:55:42.661  4747  7494 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-13 22:55:42.664  1035  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 22:55:42.664  1035  1998 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@1adb52c1 mBinding = false
09-13 22:55:42.664  1035  1117 D BluetoothManagerService: Message: 1
09-13 22:55:42.664  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1adb52c1
09-13 22:55:42.664  4747  4747 E LG,DMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,09-13 22:55:42.665  4747  4747 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-13 22:55:42.665  4747  4747 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-13 22:55:42.666  4287  4363 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-13 22:55:42.666  4287  4363 D BluetoothAdapterProperties: Setting state to 11
09-13 22:55:42.666  4287  4363 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-13 22:55:42.666  4287  4363 D BluetoothBondStateMachine: make
09-13 22:55:42.666  3389  7495 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@34e61757 on behalf of 3389
09-13 22:55:42.666  1035  1117 D BluetoothManagerService: Message: 60
09-13 22:55:42.666  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-13 22:55:42.666  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-13 22:55:42.667  4287  7501 I BluetoothBondStateMachine: StableState(): Entering Off State
09-13 22:55:42.667  4287  4363 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:42.667  4287  4363 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-13 22:55:42.667  4287  4363 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:42.667  4287  4363 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-13 22:55:42.667  4287  4363 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-13 22:55:42.668  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:42.669  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 22:55:42.670  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:42.671  6962  6962 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-13 22:55:42.672  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:42.672  4287  4363 E BluetoothAdapterService: File transfer profiles supported!!
09-13 22:55:42.674  4287  4287 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 22:55:42.674  4287  4287 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:42.674  4287  4287 V BluetoothPbapReceiver: ***********state = 11
09-13 22:55:42.676  7201  7499 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 22:55:42.679  4287  4363 E BluetoothAdapterService: File transfer profiles supported!!
09-13 22:55:42.680  4287  4287 D HeadsetService: Received start request. Starting profile...
09-13 22:55:42.680  4287  4287 D HeadsetStateMachine: make
09-13 22:55:42.683  2182  2182 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 22:55:42.683  4287  4287 D HeadsetStateMachine: max_hf_connections = 1
09-13 22:55:42.683  4287  4287 I bluedroid-qcom: get_profile_interface handsfree
09-13 22:55:42.683  4287  4287 E LGBluetoothDtmfAdapter: LGBluetoothDtmfLocalPlay is not null
09-13 22:55:42.683  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:42.683  4747  4747 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-13 22:55:42.683  4287  7504 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-13 22:55:42.683  4287  7504 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 22:55:42.683  4287  7504 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 22:55:42.683  4287  7504 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-13 22:55:42.684   320  2128 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 4287
09-13 22:55:42.685  3389  7496 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@55ea244 on behalf of 3389
09-13 22:55:42.686  3389  7496 V DownloadManager: processing inserted download 1
09-13 22:55:42.686  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:42.686  4287  4287 D HeadsetStateMachine: Proxy object connected
09-13 22:55:42.686  4287  4287 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-13 22:55:42.686  4287  4287 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-13 22:55:42.687  3389  7496 V DownloadManager: processing inserted download 4
,09-13 22:55:42.688  3389  7496 V DownloadManager: processing inserted download 7
09-13 22:55:42.688  3389  7496 V DownloadManager: processing inserted download 8
09-13 22:55:42.689  3389  7496 V DownloadManager: processing inserted download 9
09-13 22:55:42.690  3389  7496 V DownloadManager: processing inserted download 10
09-13 22:55:42.691   320  2128 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-13 22:55:42.691   320  2128 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-13 22:55:42.691   320  2128 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
,09-13 22:55:42.691   320  2128 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-13 22:55:42.691   320  2128 V voice   : voice_set_parameters: exit with code(0)
09-13 22:55:42.691   320  2128 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-13 22:55:42.691   320  2128 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-13 22:55:42.691   320  2128 V msm8974_platform: platform_set_parameters: exit with code(0)
09-13 22:55:42.692   320  2128 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-13 22:55:42.692   320  2128 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-13 22:55:42.692   320  2128 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-13 22:55:42.692  4287  7504 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-13 22:55:42.692  4287  7504 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 22:55:42.692  4287  7504 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-13 22:55:42.693  4747  4747 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-13 22:55:42.696  4287  4287 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 22:55:42.697  1801  7303 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
09-13 22:55:42.699  3389  7496 V DownloadManager: processing inserted download 11
09-13 22:55:42.700  3389  7496 V DownloadManager: processing inserted download 12
09-13 22:55:42.702  4287  4363 E BluetoothAdapterService: File transfer profiles supported!!
09-13 22:55:42.702  3389  7496 V DownloadManager: processing inserted download 13
,09-13 22:55:42.703  4287  4287 D A2dpService: Received start request. Starting profile...
09-13 22:55:42.703  4287  4287 V Avrcp   : make
09-13 22:55:42.703  4287  4287 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-13 22:55:42.703  4287  4287 I bluedroid-qcom: get_profile_interface avrcp
09-13 22:55:42.704  3275  3275 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 22:55:42.704  3275  3275 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:42.705  3275  3275 I LgeMiscReceiver: networkInfo.isConnected() = true
09-13 22:55:42.705  3275  3275 D PhoneState: setPdpRejectCasuse : false
09-13 22:55:42.706  3389  7496 V DownloadManager: processing inserted download 14
09-13 22:55:42.709  4287  4363 E BluetoothAdapterService: File transfer profiles supported!!
09-13 22:55:42.709  3389  7496 V DownloadManager: processing inserted download 16
09-13 22:55:42.709  4287  4287 V AudioManager: registerRemoteController: size of Media player list: 0
,09-13 22:55:42.711  4287  4287 E AudioManager: No RCC entry present to update
09-13 22:55:42.711  4287  4287 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-13 22:55:42.711  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-13 22:55:42.711  4287  4287 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-13 22:55:42.711  6962  6962 D BluetoothPermissionRequest: onReceive
09-13 22:55:42.712  1035  1889 I art     : Explicit concurrent mark sweep GC freed 33854(1710KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.788ms total 107.667ms
09-13 22:55:42.713  7234  7234 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 22:55:42.714  7234  7234 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-13 22:55:42.716  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-13 22:55:42.721  4287  4363 E BluetoothAdapterService: File transfer profiles supported!!
09-13 22:55:42.759  6962  6962 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-13 22:55:42.764  4287  4363 E BluetoothAdapterService: File transfer profiles supported!!
09-13 22:55:42.766  3389  3389 V DownloadManager: DownloadService onDestroy
09-13 22:55:42.767  1801  7303 I CheckinService: active receiver: disabled
09-13 22:55:42.770  4287  4363 E BluetoothAdapterService: File transfer profiles supported!!
09-13 22:55:42.825  1035  1889 V SIM_STK : Menu title from STK is T-Mobile
09-13 22:55:42.825  1035  1889 V SIM_STK : Menu title from STK is T-Mobile
,09-13 22:55:42.833  4287  4363 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-13 22:55:42.839  7364  7364 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:55:42
,09-13 22:55:42.842  7364  7364 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 22:55:42.842  7364  7364 D Weather.Utils: 2 : All the weather widget is gone.
09-13 22:55:42.842  7364  7364 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 22:55:42.842  7364  7364 D WeatherAncestor: connectivity changed - connection : true
09-13 22:55:42.842  7364  7364 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3762a369
09-13 22:55:42.843  7364  7364 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 22:55:42.843  7364  7364 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 22:55:42.843  7364  7364 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 22:55:42.843  7364  7364 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 22:55:42.843  7364  7364 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:55:42
09-13 22:55:42.848  7006  7503 V FormManager: There are no updated forms. The schedule will be deleted.
09-13 22:55:42.850  7006  7503 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-13 22:55:42.860  1801  7508 I CheckinService: active receiver: disabled
,09-13 22:55:42.870  2182  2182 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
09-13 22:55:42.877  2182  2182 I GCM     : GCM config loaded
,09-13 22:55:42.888  7234  7234 V SetupWizard: Connected to Gservices successfully
09-13 22:55:42.889  1035  1943 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-13 22:55:42.890  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-13 22:55:42.890  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-13 22:55:42.890  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-13 22:55:42.890  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-13 22:55:42.890  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-13 22:55:42.890  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 22:55:42.890  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-13 22:55:42.890  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-13 22:55:42.890  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-13 22:55:42.890  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 22:55:42.890  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-13 22:55:42.890  4287  4287 D A2dpStateMachine: make
09-13 22:55:42.891  4287  4287 I bluedroid-qcom: get_profile_interface a2dp
09-13 22:55:42.891  4287  7512 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-13 22:55:42.892  1035  1389 D PowerManagerServiceEx: acquireWakeLockInternal: lock=688639854, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
09-13 22:55:42.893  4287  4287 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-13 22:55:42.893  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:42.894  4287  4287 D HidService: Received start request. Starting profile...
09-13 22:55:42.894  4287  4287 I bluedroid-qcom: get_profile_interface hidhost
09-13 22:55:42.894  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:42.894  6986  6986 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
09-13 22:55:42.894  6986  6986 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:5604
09-13 22:55:42.894  4287  7511 D A2dpStateMachine: Enter Disconnected: -2
09-13 22:55:42.895  4287  4287 D HealthService: Received start request. Starting profile...
09-13 22:55:42.895  4287  4287 I bluedroid-qcom: get_profile_interface health
09-13 22:55:42.896  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:42.896  4287  4287 D PanService: Received start request. Starting profile...
09-13 22:55:42.896  4287  4287 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 22:55:42.896  4287  4287 I bluedroid-qcom: get_profile_interface pan
09-13 22:55:42.898  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:42.898  4287  4287 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 22:55:42.898  4287  4287 D BtGatt.GattService: Received start request. Starting profile...
09-13 22:55:42.898  4287  4287 D BtGatt.GattService: start()
09-13 22:55:42.898  4287  4287 D BtGatt.AdvertiseManager: advertise manager created
09-13 22:55:42.901  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:42.901  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:42.901  4287  4287 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-13 22:55:42.901  4287  4287 V BluetoothMapService: BluetoothMapBinder()
09-13 22:55:42.901  4287  4287 D BluetoothMap,Service: Received start request. Starting profile...
09-13 22:55:42.901  4287  4287 D BluetoothMapService: start()
09-13 22:55:42.903  4287  4287 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-13 22:55:42.903  4287  4287 D BluetoothMapEmailAppObserver: createReceiver()
,09-13 22:55:42.903  4287  4287 D BluetoothMapEmailAppObserver: initObservers()
09-13 22:55:42.903  4287  4287 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-13 22:55:42.903  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:42.905  4287  4287 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 22:55:42.907  4287  4287 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 22:55:42.908  4287  4287 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-13 22:55:42.910  4287  4287 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 22:55:42.910  4287  4287 V PanService: [BTUI] SIM Extra State :ABSENT
09-13 22:55:42.912  4287  4287 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-13 22:55:42.913  4287  4287 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-13 22:55:42.913  4287  4287 V BluetoothMapService: Handler(): got msg=1
09-13 22:55:42.913  4287  4363 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-13 22:55:42.913  4287  4363 I bluedroid-qcom: enable
09-13 22:55:42.914  4287  4363 I bt_hci_bdroid: init
09-13 22:55:42.914  4287  7518 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-13 22:55:42.914  4287  4363 I bt_vendor: bt-vendor : init
09-13 22:55:42.914  4287  4363 I bt_vendor: bt-vendor : get_bt_soc_type
09-13 22:55:42.914  4287  4363 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-13 22:55:42.914  4287  4363 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-13 22:55:42.914  4287  4363 D bt_userial_mct: userial_init
09-13 22:55:42.914  4287  7518 I bt-btu  : btu_task pending for preload complete event
09-13 22:55:42.915  4287  4363 D bt_hci_bdroid: set_power 1
09-13 22:55:42.915  4287  4363 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-13 22:55:42.915  4287  4363 I bt_vendor: Starting hciattach daemon
09-13 22:55:42.915  4287  4363 I bt_vendor: try to set true
09-13 22:55:42.915  4287  4287 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 22:55:42.915  4287  4287 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 22:55:42.915  4287  4287 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 22:55:42.915  4287  4287 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:42.915  4287  4287 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-13 22:55:42.906  7521  7521 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 22:55:42.906  7521  7521 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 22:55:42.937  7522  7522 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-13 22:55:42.964  2660  2660 D [Concierge]Service: onStartCommand(). Type : 9
,09-13 22:55:42.977  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=688639854 [*alarm*], flags=0x0
,09-13 22:55:42.996  7528  7528 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-13 22:55:43.006  7529  7529 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-13 22:55:43.036  7531  7531 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-13 22:55:43.054  7532  7532 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-13 22:55:43.082  7533  7533 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-13 22:55:43.101  7534  7534 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-13 22:55:43.133  7536  7536 I libmdmdetect: ESOC framework not supported
09-13 22:55:43.134  7536  7536 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-13 22:55:43.140  7536  7536 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-13 22:55:43.140  7536  7536 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-13 22:55:43.140  7536  7536 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-13 22:55:43.140  7536  7536 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-13 22:55:43.140  7536  7536 D bthci_qcomm_common: [BTUI]     LE: Class 2
,09-13 22:55:43.140  7536  7536 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-13 22:55:43.140  7536  7536 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-13 22:55:43.146   315  7538 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 22:55:43.147   315  7538 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
09-13 22:55:43.167  1035  2016 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 22:55:43.167  1035  2016 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@1adb52c1 mBinding = false
09-13 22:55:43.168  1035  1117 D BluetoothManagerService: Message: 1
,09-13 22:55:43.168  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1adb52c1
,09-13 22:55:43.174  4287  4305 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-13 22:55:43.174  7536  7537 E QC-QMI  : qmi_client [7536] 15: failed to locate client data
09-13 22:55:43.174  1035  1117 E BluetoothManagerService: IBluetooth.enable() returned false
09-13 22:55:43.174   476   476 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-13 22:55:43.174   476   476 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
09-13 22:55:43.180   315  7538 D libc-netbsd: res_queryN name = www.google.com succeed
09-13 22:55:43.187   315  7540 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 22:55:43.188   315  7540 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-13 22:55:43.188   315  7540 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-13 22:55:43.214  4287  4287 V BluetoothOppNotification: previous thread is not finished yet
,09-13 22:55:43.234  7541  7541 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-13 22:55:43.238  1035  1525 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,09-13 22:55:43.261  7542  7542 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-13 22:55:43.317  4287  4363 I bt_vendor: bluetooth satus is on
09-13 22:55:43.317  4287  4363 D bt_hci_bdroid: preload
09-13 22:55:43.317  4287  7520 D bt_userial_mct: userial_open(port:0)
09-13 22:55:43.317  4287  7520 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-13 22:55:43.318  4287  7520 I bt_vendor: Done intiailizing UART
09-13 22:55:43.319  4287  7520 I bt_vendor: Done intiailizing UART
09-13 22:55:43.319  4287  7520 I bt_userial_mct: CMD=94, EVT=94, ACL_Out=95, ACL_In=95
09-13 22:55:43.320  4287  7520 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-13 22:55:43.320  4287  7547 D bt_userial_mct: Entering userial_read_thread()
09-13 22:55:43.321  4287  7518 I bt-btu  : btu_task received preload complete event
09-13 22:55:43.321  4287  7518 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-13 22:55:43.321  4287  7518 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-13 22:55:43.321  4287  7518 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-13 22:55:43.330  4287  7518 I         : BTE_InitTraceLevels -- TRC_HCI
09-13 22:55:43.330  4287  7518 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 22:55:43.330  4287  7518 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 22:55:43.330  4287  7518 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 22:55:43.330  4287  7518 I         : BTE_InitTraceLevels -- TRC_AVRC
09-13 22:55:43.330  4287  7518 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 22:55:43.330  4287  7518 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 22:55:43.330  4287  7518 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 22:55:43.330  4287  7518 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-13 22:55:43.330  4287  7518 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 22:55:43.330  4287  7518 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 22:55:43.330  4287  7518 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 22:55:43.330  4287  7518 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 22:55:43.330  4287  7518 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 22:55:43.330  4287  7518 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 22:55:43.330  4287  7518 I         : BTE_InitTraceLevels -- TRC_BTIF
09-13 22:55:43.355  6711  7069 D UEI.SmartControl: Internal timer expired: 4
09-13 22:55:43.355  6711  7069 D UEI.SmartControl: unbind internal service
,09-13 22:55:43.378  4287  7518 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,09-13 22:55:43.379  4287  7518 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01a2061 
09-13 22:55:43.379  4287  7518 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01a2061 
,09-13 22:55:43.387  6711  7066 D serial_port: close(fd = 24)
,09-13 22:55:43.391  4287  4366 E bt-btif : Calling BTA_HhEnable
09-13 22:55:43.391  4287  4366 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-13 22:55:43.391  4287  7518 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-13 22:55:43.391  4287  7518 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-13 22:55:43.391  4287  7518 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-13 22:55:43.391  4287  4366 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-13 22:55:43.392  4287  7518 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-13 22:55:43.392  4287  7518 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-13 22:55:43.396  4287  4366 D BluetoothAdapterProperties: Name is: G3
,09-13 22:55:43.399  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-13 22:55:43.401  4287  7518 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 22:55:43.401  4287  7518 W bt-smp  : Plain text(LSB ~ MSB) = 95 e9 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 22:55:43.401  4287  7518 W bt-smp  : Encrypted text(LSB ~ MSB) = 94 fb e6 f5 15 2b c2 fc e1 89 7b 76 71 25 8f a9 
09-13 22:55:43.401  4287  7518 W bt-btm  : Stopping oneshot timer
09-13 22:55:43.403  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
09-13 22:55:43.407  4287  4366 D BluetoothAdapterProperties: Scan Mode:20
09-13 22:55:43.407  4287  4366 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 22:55:43.407  4287  4366 D bt_hci_bdroid: postload
09-13 22:55:43.408  4287  7520 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 22:55:43.408  4287  7518 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-13 22:55:43.409  4287  7547 E bt_mct  : hci lib postload completed
09-13 22:55:43.411  4287  4366 D bte_conf: Device ID record 1 : primary
09-13 22:55:43.411  4287  4366 D bte_conf:   vendorId            = 00c4
09-13 22:55:43.411  4287  4366 D bte_conf:   vendorIdSource      = 0001
09-13 22:55:43.411  4287  4366 D bte_conf:   product             = 13a1
09-13 22:55:43.411  4287  4366 D bte_conf:   version             = 1000
09-13 22:55:43.411  4287  4366 D bte_conf:   clientExecutableURL = 
09-13 22:55:43.411  4287  4366 D bte_conf:   serviceDescription  = 
09-13 22:55:43.411  4287  4366 D bte_conf:   documentationURL    = 
09-13 22:55:43.411  4287  4366 D bte_conf: bte_load_did_conf no section named DID2.
,09-13 22:55:43.416  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:43.416  4287  4366 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-13 22:55:43.416  4287  4363 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-13 22:55:43.417  4287  4363 D BluetoothAdapterProperties: ScanMode =  20
09-13 22:55:43.417  4287  4363 D BluetoothAdapterProperties: State =  11
09-13 22:55:43.417  4287  4363 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-13 22:55:43.417  4287  4363 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-13 22:55:43.417  4287  4363 D BluetoothAdapterProperties: Setting state to 12
09-13 22:55:43.417  4287  4363 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 22:55:43.417  4287  4366 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 22:55:43.418  4287  4363 I BluetoothAdapterState: Entering On State
09-13 22:55:43.419  1035  1117 D BluetoothManagerService: Message: 60
09-13 22:55:43.419  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-13 22:55:43.419  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
09-13 22:55:43.420  4287  4363 D LGBluetoothServiceAdapter: [BTUI] OnState
09-13 22:55:43.420  4287  4363 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-13 22:55:43.420  4287  4363 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-13 22:55:43.416  7552  7552 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 22:55:43.416  7552  7552 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 22:55:43.435  4287  4363 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,09-13 22:55:43.438  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:43.438  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:43.438  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:43.438  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:43.438  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:43.438  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:43.438  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:55:43.438  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 22:55:43.442  6804  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:43.442  6962  7318 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 22:55:43.450  6962  7318 D BluetoothMap: onBluetoothStateChange: up=true
09-13 22:55:43.450  6711  7066 I UEI.SmartControl: Serial port is closed.
,09-13 22:55:43.461  1836  1852 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 22:55:43.466  6962  6962 D BluetoothHeadset: Proxy object connected
09-13 22:55:43.466  6962  6962 D HeadsetProfile: Bluetooth service connected
,09-13 22:55:43.470  4287  4363 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-13 22:55:43.476  4287  4366 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 22:55:43.476  4287  4366 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-13 22:55:43.476  6962  6979 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 22:55:43.477  1836  1836 D BluetoothHeadset: Proxy object connected
09-13 22:55:43.481  6962  6977 D BluetoothPan: onBluetoothStateChange on: true
09-13 22:55:43.481  6962  6977 D BluetoothPan: onBluetoothStateChange call bindService
,09-13 22:55:43.488  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 22:55:43.492  1836  1836 D BluetoothHeadset: Proxy object connected
09-13 22:55:43.493  6962  6979 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 22:55:43.496  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 22:55:43.496  7563  7563 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-13 22:55:43.496  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 22:55:43.498  1035  1035 D BluetoothHeadset: Proxy object connected
09-13 22:55:43.499  6962  6962 D BluetoothMap: Proxy object connected
09-13 22:55:43.499  6962  6962 D MapProfile: Bluetooth service connected
09-13 22:55:43.499  6962  6962 D BluetoothMap: getConnectedDevices()
09-13 22:55:43.500  6962  7318 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 22:55:43.500  1035  1035 D BluetoothA2dp: Proxy object connected
09-13 22:55:43.501  4287  6901 V BluetoothMapService: getConnectedDevices()
09-13 22:55:43.502  1836  1852 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 22:55:43.503  6962  6962 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 22:55:43.503  6962  6962 D PanProfile: Bluetooth service connected
09-13 22:55:43.503  1836  1836 D BluetoothHeadset: Proxy object connected
09-13 22:55:43.504  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-13 22:55:43.504  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-13 22:55:43.506  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:43.506  1926  2120 D LGBluetoothAPIService: Message: 1
09-13 22:55:43.507  1926  2120 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,09-13 22:55:43.510  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 22:55:43.518  6962  6962 D BluetoothInputDevice: Proxy object connected
09-13 22:55:43.518  6962  6962 D HidProfile: Bluetooth service connected
09-13 22:55:43.520  1926  2120 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-13 22:55:43.522  4287  4287 V BtOppService: Receiver BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,09-13 22:55:43.522  4287  4287 V BtOppService: start RfcommListener
09-13 22:55:43.522  4287  4287 V BtOppService: RfcommListener started
09-13 22:55:43.522  4287  4287 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:43.522  4287  4287 D BluetoothMapService: STATE_ON
09-13 22:55:43.522  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:43.522  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:43.522  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:43.522  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:43.522  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:43.522  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:43.522  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:55:43.522  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 22:55:43.522  4287  4287 D LGBluetoothAPIServer: [BTUI] onCreate()
09-13 22:55:43.523  6962  6962 D BluetoothA2dp: Proxy object connected
09-13 22:55:43.523  6962  6962 D A2dpProfile: Bluetooth service connected
09-13 22:55:43.524  4287  7569 V BtOppRfcommListener: Starting RFCOMM listener....
,09-13 22:55:43.525  1035  1979 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 22:55:43.525  4287  4287 V BluetoothMapService: Handler(): got msg=1
09-13 22:55:43.525  4287  4287 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-13 22:55:43.526  4287  4287 D LGBluetoothAPIServer: [BTUI] onBind()
09-13 22:55:43.527  4287  7570 D BluetoothMapMasInstance: MAS initSocket()
09-13 22:55:43.527  4287  7570 D BluetoothMapMasInstance:   masId = 00
09-13 22:55:43.527  4287  7570 D BluetoothMapMasInstance:   msgTypes = 0e
09-13 22:55:43.527  4287  7570 D BluetoothMapMasInstance:   masName = SMS/MMS
09-13 22:55:43.527  4287  7570 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-13 22:55:43.527  1926  1926 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-13 22:55:43.527  1926  2120 D LGBluetoothAPIService: Message: 100
09-13 22:55:43.527  1926  2120 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-13 22:55:43.527  6804  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:43.528  1035  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 22:55:43.528  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:43.528  4287  4287 V BluetoothPbapService: Pbap Service onCreate
09-13 22:55:43.528  4287  4287 V BluetoothPbapService: Starting PBAP service
09-13 22:55:43.531  4287  7570 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 22:55:43.531  4287  4287 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-13 22:55:43.532  4287  4287 V BluetoothPbapService: Handler(): got msg=1
09-13 22:55:43.533  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:43.533  4287  7569 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 22:55:43.533  4287  4287 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-13 22:55:43.534  4287  7570 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=99 mFd=89
09-13 22:55:43.534  4287  7570 V BluetoothMapMasInstance: Succeed to create listening socket 
09-13 22:55:43.534  4287  7570 D BluetoothMapMasInstance: Accepting socket connection...
09-13 22:55:43.534  4287  4287 V BluetoothPbapService: Pbap Service onBind
09-13 22:55:43.535  4287  4366 D BluetoothAdapterProperties: Scan Mode:21
09-13 22:55:43.535  4287  4366 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-13 22:55:43.535  4287  7569 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=101 mFd=99
,09-13 22:55:43.537  4287  7569 V BtOppRfcommListener: Started RFCOMM listener....
09-13 22:55:43.538  4287  7569 I BtOppRfcommListener: Accept thread started.
09-13 22:55:43.538  4287  7569 V BtOppRfcommListener: Accepting connection...
09-13 22:55:43.538  4287  4287 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:43.538  4287  4287 V BluetoothPbapService: state: 12
09-13 22:55:43.539  4287  7571 V BluetoothPbapService: Pbap Service initSocket
09-13 22:55:43.542  1035  1979 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 22:55:43.543  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:43.545  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:43.545  4287  7571 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 22:55:43.546  4287  7571 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=103 mFd=101
09-13 22:55:43.546  4287  7571 V BluetoothPbapService: Succeed to create listening socket 
09-13 22:55:43.546  4287  7571 V BluetoothPbapService: Accepting socket connection...
09-13 22:55:43.547  6962  6962 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,09-13 22:55:43.549  6962  6962 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 22:55:43.551  6962  6962 D BluetoothPbap: Proxy object connected
09-13 22:55:43.551  6962  6962 D PbapServerProfile: Bluetooth service connected
09-13 22:55:43.553  4287  4287 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 22:55:43.553  4287  4287 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:43.553  4287  4287 V BluetoothPbapReceiver: ***********state = 12
09-13 22:55:43.554  6962  6962 D DockEventReceiver: finishStartingService: stopping service
09-13 22:55:43.558  2182  2182 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 22:55:43.559  2182  2182 D c       : Getting all permits...
09-13 22:55:43.559  2182  2182 D a       : Opening database...
,09-13 22:55:43.563  2182  2182 D a       : Opening database auth.proximity.permit_store...
09-13 22:55:43.563  2182  2182 D a       : Closing database...
09-13 22:55:43.575  6962  6962 D BluetoothPermissionRequest: onReceive
,09-13 22:55:43.577  6962  6962 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 22:55:43.579  6962  6962 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 22:55:43.582  4287  4287 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-13 22:55:43.584  4287  4287 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-13 22:55:43.586  4287  4287 V BtOppService: onStartCommand
,09-13 22:55:43.589  4287  4287 V BtOppService: Starting RfcommListener
09-13 22:55:43.592  4287  4287 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:43.592  4287  7574 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-13 22:55:43.592  4287  4287 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 22:55:43.592  4287  7574 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-13 22:55:43.594  4287  7574 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31610c0b on behalf of 
09-13 22:55:43.594  4287  4287 V BtOppService: start RfcommListener
09-13 22:55:43.594  4287  4287 V BtOppService: RfcommListener started
09-13 22:55:43.595  4287  7574 V BluetoothOppNotification: update too frequent, put in queue
09-13 22:55:43.595  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:43.595  4287  4287 V BluetoothFtpService: Ftp Service onCreate
09-13 22:55:43.595  4287  4287 I BluetoothFtpService: Ftp Service onCreate
09-13 22:55:43.595  4287  4287 V BluetoothFtpService: Ftp Service onStartCommand
09-13 22:55:43.595  4287  4287 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:43.595  4287  4287 V BluetoothFtpService: Starting Listening on sockets
09-13 22:55:43.596  4287  4287 V BluetoothFtpService: Handler(): got msg=1
09-13 22:55:43.596  4287  4287 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-13 22:55:43.596  4287  7574 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-13 22:55:43.596  4287  4287 V BluetoothFtpService: Ftp Service initSocket
09-13 22:55:43.596  1035  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 22:55:43.597  4287  4287 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 22:55:43.598  4287  4287 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=105 mFd=103
,09-13 22:55:43.598  4287  4287 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-13 22:55:43.599  4287  4287 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 22:55:43.599  4287  4287 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 22:55:43.599  4287  4287 V BluetoothSapReceiver: SapReceiver onReceive 
,09-13 22:55:43.599  4287  4287 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:43.599  4287  4287 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-13 22:55:43.599  4287  4287 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 22:55:43.600  4287  7575 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-13 22:55:43.602  4287  4287 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@174481f0
09-13 22:55:43.602  4287  4287 V BluetoothSapService: Sap Service onCreate
09-13 22:55:43.608  4287  4287 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 22:55:43.608  4287  4287 V BluetoothSapService: state: 12
09-13 22:55:43.608  4287  4287 V BluetoothSapService: Starting SAP server process
09-13 22:55:43.609  4287  4287 V BluetoothSapService: SAP Service startRfcommListenerThread
09-13 22:55:43.606  7576  7576 W sapd    : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 22:55:43.611  4287  7577 V BluetoothSapService: Sap Service initRfcommSocket
09-13 22:55:43.613  1035  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 22:55:43.606  7576  7576 W sapd    : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file,
09-13 22:55:43.615  4287  7577 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 22:55:43.617  4287  7577 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=107 mFd=105
09-13 22:55:43.617  4287  7577 V BluetoothSapService: Succeed to create listening socket 
,09-13 22:55:43.617  4287  7577 V BluetoothSapService: Accepting socket connection...
09-13 22:55:43.625  7576  7576 V BT_SAP  : Event pipe created
09-13 22:55:43.625  7576  7576 V BT_SAP  : create_server_socket qcom.sap.server
09-13 22:55:43.625  7576  7576 V BT_SAP  : created socket fd 6
,09-13 22:55:43.683  6804  7415 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:43.683  6804  7415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:43.683  6804  7415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:43.683  6804  7415 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:43.683  6804  7415 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:43.683  6804  7415 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:43.683  6804  7415 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:55:43.683  6804  7415 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 22:55:43.690  6804  7415 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:43.694  6804  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:43.699  1035  1998 D WifiServiceImplEx: setWifiEnabled: false pid=6804, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-13 22:55:43.699  1035  1998 D WifiService: setWifiEnabled: false pid=6804, uid=10118
09-13 22:55:43.699  1035  1998 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 22:55:43.718  1035  1522 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-13 22:55:43.719  1035  1522 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-13 22:55:43.719  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 22:55:43.719  1035  1522 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-13 22:55:43.720  1035  1522 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-13 22:55:43.720  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 22:55:43.720  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-13 22:55:43.720  1035  1522 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-13 22:55:43.720  1035  1522 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-13 22:55:43.721  1035  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 22:55:43.721  1035  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 22:55:43.721  1035  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 22:55:43.721  1035  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 22:55:43.724  1035  1888 D WifiServiceImplEx: setWifiEnabled: false pid=6804, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 22:55:43.725  1035  1888 D WifiService: setWifiEnabled: false pid=6804, uid=10118
09-13 22:55:43.725  1035  1888 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 22:55:43.727  1035  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 22:55:43.727  1035  1519 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:43.728  1035  1519 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:43.728  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 22:55:43.728  7050  7050 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 22:55:43.728  1035  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 22:55:43.728  1035  1522 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 22:55:43.729  1035  1522 D WifiNative-wlan0: SET ps 1: returned true
09-13 22:55:43.729  1035  7100 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:43.729   315   879 D CommandListener: Clearing all IP addresses on wlan0
,09-13 22:55:43.761  1035  1979 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
,09-13 22:55:43.762  1035  7099 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:43.762  1035  7099 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:43.762  1035  7099 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-13 22:55:43.762  1035  7099 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:43.762  1035  7099 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-13 22:55:43.765   315  7580 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-13 22:55:43.766  1035  7099 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-13 22:55:43.766  1035  1115 D DSQN    : Dns fail occured do internet check.
09-13 22:55:43.767  1035  1035 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
09-13 22:55:43.767  1035  1035 D DSQN    : try Internet connection check
09-13 22:55:43.772  1035  7582 D DSQN    : ThreadTCPConnectionCheck connect try to216.58.214.238
09-13 22:55:43.773  1035  7582 D DSQN    : ThreadTCPConnectionCheck conn fail internet is not possible
09-13 22:55:43.774  1035  7581 D DSQN    : ThreadInternetCheck internet check NOK 
09-13 22:55:43.774  1035  7581 D DSQN    : L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
09-13 22:55:43.774  1035  7581 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
09-13 22:55:43.776  1035  1035 D WifiDataContinuityService: L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
09-13 22:55:43.776  1926  1941 D WifiServiceExtension: isInternetCheckAvailable return false
,09-13 22:55:43.779  1035  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 22:55:43.779  1035  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
09-13 22:55:43.783  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-13 22:55:43.786  1926  1926 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-13 22:55:43.790  1035  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:43.790  1035  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:43.790  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:43.790  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 22:55:43.791  1035  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:43.791  1035  1519 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:43.791  1035  1519 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:43.791  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:43.791  1035  1519 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2032be09
09-13 22:55:43.791  1035  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:43.791  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:43.792  1035  1519 D LGWifiP2pService: P2pDisablingState
09-13 22:55:43.792  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 22:55:43.792  1035  1519 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:43.792  1035  1519 D LGWifiP2pService: p2p socket connection lost
09-13 22:55:43.792  1035  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:43.792  1035  1519 D LGWifiP2pService: P2pDisabledState
09-13 22:55:43.792  1035  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:43.792  1035  1522 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 22:55:43.793  1035  1522 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-13 22:55:43.793  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 22:55:43.794  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:43.797  7050  7050 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 22:55:43.798  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-13 22:55:43.798  1035  1519 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:43.798  1035  1519 D LGWifiP2pService: DefaultState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 22:55:43.801  1035  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 22:55:43.801  1035  1522 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 22:55:43.802  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 22:55:43.802  1035  1522 D WifiNative-wlan0: SET ps 1: returned true
09-13 22:55:43.805  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:43.805  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:43.805  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 22:55:43.805  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
09-13 22:55:43.805  1035  1035 D RttService: SCAN_AVAILABLE : 1
09-13 22:55:43.805  1035  1541 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:43.806  1035  1540 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:43.806  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 22:55:43.806  1926  1926 D WfdsService: WifiP2pState is changed : false
09-13 22:55:43.807  1926  2306 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-13 22:55:43.808  1926  2306 D WfdsService: Set the WFDS Monitor: false
09-13 22:55:43.810  1926  7060 D CtrlSupplicant: Received on exit socket, terminate
09-13 22:55:43.810  1926  2306 D WfdsMonitor: WFDS Monitor is stopped
09-13 22:55:43.810  1926  7060 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-13 22:55:43.810  1926  7060 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-13 22:55:43.810  1926  2306 D WfdsService: STATE : WfdsDisabledState - enter
09-13 22:55:43.810  1926  7060 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
,09-13 22:55:43.814  1926  2306 W WfdsService: DefaultState - msg [9445378] is not handled
09-13 22:55:43.814  1926  2308 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-13 22:55:43.815  6940  6940 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 22:55:43.815  6940  6940 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 22:55:43.815  6940  6940 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 22:55:43.818  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 22:55:43.819  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:43.819  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 22:55:43.820  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 22:55:43.833  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:43.836   315   879 D CommandListener: Clearing all IP addresses on wlan0
09-13 22:55:43.836  1035  1529 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-13 22:55:43.836  1035  1529 D DSQN    : disableDataServiceNotify
,09-13 22:55:43.836  1035  1529 D DSQN    : stop dsqn bin
09-13 22:55:43.840  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 22:55:43.840  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 22:55:43.841  1035  1529 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-13 22:55:43.841  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:43.841  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 22:55:43.842  1035  1529 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 22:55:43.842  1035  1529 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-13 22:55:43.842  1035  1529 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-13 22:55:43.842  1035  1529 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-13 22:55:43.842  1035  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 22:55:43.842  1035  7099 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:43.842  1035  7099 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:43.843  1035  7099 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-13 22:55:43.843  1586  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,09-13 22:55:43.844  1035  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:43.844  1035  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 22:55:43.845  6986  6986 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 22:55:43.845  1035  1522 D WifiNative-p2p0: doBoolean: TERMINATE
09-13 22:55:43.845  1035  1522 D WifiNative-p2p0: TERMINATE: returned true
09-13 22:55:43.845  1035  1518 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 22:55:43.845  1035  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 22:55:43.845  1035  1522 E WifiStateMachine: useWiFiOffloading() : false
09-13 22:55:43.845  1035  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 22:55:43.845  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 22:55:43.846  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 22:55:43.846  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 22:55:43.846  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 22:55:43.847  1035  1035 D WifiHS20: hidePasspointNotification off =false
09-13 22:55:43.848  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:43.849  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:43.849  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 22:55:43.851  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 22:55:43.852  1035  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:43.852  1035  1529 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:43.852  1035  1529 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:43.852  1035  1529 D NetworkManagementService: Removing idletimer
09-13 22:55:43.852  1035  1529 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:43.852  1035  1529 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-13 22:55:43.853  1836  1836 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:43.853  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 22:55:43.853  1035  1522 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:43.853  1035  1522 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 22:55:43.854  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 22:55:43.854  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 22:55:43.854  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 u,navailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 22:55:43.854  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 22:55:43.855  1035  1518 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 22:55:43.856  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
,09-13 22:55:43.859  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:43.859  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:43.859  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:43.859  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 22:55:43.859  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:43.859  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:55:43.859  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:55:43.859  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 22:55:43.861  6804  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 22:55:43.861  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-13 22:55:43.862  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 22:55:43.862  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-13 22:55:43.863  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:43.863  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:43.863  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:43.863  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 22:55:43.863  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:43.863  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:55:43.863  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:55:43.863  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 22:55:43.865  6804  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 22:55:43.867  6940  6940 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 22:55:43.867  6940  6940 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 22:55:43.867  6940  6940 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 22:55:43.870  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 22:55:43.876  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 22:55:43.883  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 22:55:43.884  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 22:55:43.885  6986  6986 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 22:55:43.887  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 22:55:43.890  6940  6940 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 22:55:43.890  6940  6940 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 22:55:43.890  6940  6940 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 22:55:43.894  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 22:55:43.899  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:43.905  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 22:55:43.905  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 22:55:43.906  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 22:55:43.907  6986  6986 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-13 22:55:43.907  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:43.908  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:43.908  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-13 22:55:43.908  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 22:55:43.910  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:43.911  7050  7050 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-13 22:55:43.911  7050  7050 I wpa_supplicant: monitor socket send errors count : 1
09-13 22:55:43.911  7050  7050 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1926-4\x00 that cannot receive messages
09-13 22:55:43.913  1035  7058 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-13 22:55:43.913  1035  7058 D WifiMonitor: Dropping event because (p2p0) is stopped
09-13 22:55:43.914  6940  6940 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 22:55:43.917  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-13 22:55:43.927  7006  7588 W FormManager: Network not available. Please check & try again.
09-13 22:55:43.929  7006  7589 V FormManager: Network unavailable.
,09-13 22:55:43.932  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:43.941  7006  7589 V FormManager: Network unavailable.
,09-13 22:55:43.945  7050  7050 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-13 22:55:43.946  7050  7050 W wpa_supplicant: USIM:  scard_deinit function
09-13 22:55:43.947  1035  7058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-13 22:55:43.947  1035  7058 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 22:55:43.947  1035  7058 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 22:55:43.947  1035  7058 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-13 22:55:43.947  1035  7058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 22:55:43.947  1035  7058 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 22:55:43.948  1035  1522 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=200204
09-13 22:55:43.948  1035  1117 D Tethering: InitialState.processMessage what=4
09-13 22:55:43.949  1035  7100 D DhcpStateMachine: StoppedState
09-13 22:55:43.949  1035  7100 D DhcpStateMachine: StoppedState{ when=-147ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:43.949  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 22:55:43.950  1035  1522 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=200206
09-13 22:55:43.951  1035  1522 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=200206  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 22:55:43.952  1035  1522 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=200208  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 22:55:43.952  1035  1522 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-13 22:55:43.952  1035  1522 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-13 22:55:43.953  1035  1522 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-13 22:55:43.953  1035  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-13 22:55:43.956  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 22:55:43.956  6962  6962 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 22:55:43.957  6962  6962 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 22:55:43.957  6962  6962 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 22:55:43.957  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 22:55:43.957  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 22:55:43.958  6962  6962 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 22:55:43.958  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 22:55:43.958  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 22:55:43.958  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 22:55:43.958  6962  6962 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 22:55:43.958  6962  6962 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 22:55:43.958  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:43.959  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:43.960  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:44.011  7050  7050 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-13 22:55:44.012  1035  7058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
,09-13 22:55:44.012  1035  7058 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
,09-13 22:55:44.012  1035  7058 D WifiMonitor: Disconnecting from the supplicant, no more events
09-13 22:55:44.012  1035  1522 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
09-13 22:55:44.116  1926  1926 D WfdsService: Supplicant Connection state is changed : false
09-13 22:55:44.117  1926  2306 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-13 22:55:44.118  1926  2306 D WfdsService: Set the WFDS Monitor: false
09-13 22:55:44.118  1926  2306 D WfdsMonitor: WFDS Monitor is stopped
,09-13 22:55:44.122  1035  1522 D WifiOffDelayIfNotUsed: stopMonitoring
09-13 22:55:44.123  1035  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 22:55:44.123  1035  1522 E WifiStateMachine: useWiFiOffloading() : false
09-13 22:55:44.123  1035  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 22:55:44.125  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 22:55:44.126  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 22:55:44.127  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:44.129  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 22:55:44.131  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-13 22:55:44.132  1035  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-13 22:55:44.132  1035  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-13 22:55:44.134  2491  2491 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:44.135  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 22:55:44.135  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:55:44.139  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:44.142  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 22:55:44.153  4747  7590 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-13 22:55:44.157  4747  7591 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 22:55:44.158  4747  7591 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 22:55:44.160  6940  6940 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-13 22:55:44.160  6940  6940 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 22:55:44.160  6940  6940 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 22:55:44.167  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-13 22:55:44.173  7006  7593 W FormManager: Network not available. Please check & try again.
,09-13 22:55:44.174  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:44.180  7006  7594 V FormManager: Network unavailable.
,09-13 22:55:44.184  7006  7594 V FormManager: Network unavailable.
09-13 22:55:44.216  4287  4287 V BluetoothOppNotification: new notify threadi!
,09-13 22:55:44.216  4287  4287 V BluetoothOppNotification: send delay message
09-13 22:55:44.218  4287  7595 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-13 22:55:44.220  4287  7595 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9188d94 on behalf of 
,09-13 22:55:44.221  4287  7595 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-13 22:55:44.223  4287  7595 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-13 22:55:44.224  4287  7595 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f0f903d on behalf of 
09-13 22:55:44.225  4287  7595 V BluetoothOppNotification: outbound: succ-0  fail-0
09-13 22:55:44.228  4287  7595 V BluetoothOppNotification: outbound notification was removed.
09-13 22:55:44.229  4287  7595 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-13 22:55:44.232  4287  7595 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13c13032 on behalf of 
09-13 22:55:44.233  4287  7595 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-13 22:55:44.236  4287  7595 V BluetoothOppNotification: inbound notification was removed.
09-13 22:55:44.236  6804  7579 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:44.236  6804  7579 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:44.236  6804  7579 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:44.236  6804  7579 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 22:55:44.236  6804  7579 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:44.236  6804  7579 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:55:44.236  6804  7579 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:55:44.236  6804  7579 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 22:55:44.236  4287  7595 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-13 22:55:44.240  4287  7595 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e9cf183 on behalf of 
09-13 22:55:44.241  6804  7579 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 22:55:44.245  6804  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:44.246  1035  2016 D WifiServiceImplEx: setWifiEnabled: true pid=6804, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 22:55:44.247  1035  2016 D WifiService: setWifiEnabled: true pid=6804, uid=10118
09-13 22:55:44.247  1035  2016 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 22:55:44.263  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 22:55:44.264  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 22:55:44.264  1035  1035 D Ulp_jni : JNI:system_update. Event-4
09-13 22:55:44.271  1035  1766 D WifiServiceImplEx: setWifiEnabled: true pid=6804, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-13 22:55:44.272  1035  1766 D WifiService: setWifiEnabled: true pid=6804, uid=10118
09-13 22:55:44.272  1035  1766 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 22:55:44.274  1035  1528 D WifiController: Mismatch in the state 1
09-13 22:55:44.327  1035  1522 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,09-13 22:55:44.328  1035  1522 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-13 22:55:44.331  1035  1522 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-13 22:55:44.331  1035  1522 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 22:55:44.332  1035  1522 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-13 22:55:44.332  1035  1522 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 22:55:44.332  1035  1522 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-13 22:55:44.332  1035  1522 E WifiHW  : unknown target_country: EU , set to default
09-13 22:55:44.332  1035  1522 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-13 22:55:44.332  1035  1522 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-13 22:55:44.332  1035  1522 I WifiUtil: gEnableBmps=1
09-13 22:55:44.780  1035  1998 D WifiServiceImplEx: setWifiEnabled: true pid=6804, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 22:55:44.781  1035  1998 D WifiService: setWifiEnabled: true pid=6804, uid=10118
09-13 22:55:44.781  1035  1998 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 22:55:44.793  1035  1528 D WifiController: Mismatch in the state 1
09-13 22:55:44.989   315   879 D SoftapController: Softap fwReload - Ok
,09-13 22:55:44.996  1035  1522 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (655ms)
09-13 22:55:45.009   315   879 D CommandListener: Setting iface cfg
09-13 22:55:45.009   315   879 D CommandListener: Trying to bring down wlan0
,09-13 22:55:45.033  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-13 22:55:45.033   315   879 D CommandListener: Clearing all IP addresses on wlan0
09-13 22:55:45.035  1035  1522 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-13 22:55:45.046  7614  7614 W wpa_supplicant: type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 22:55:45.046  7614  7614 W wpa_supplicant: type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 22:55:45.069  1035  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 22:55:45.069  1035  1522 E WifiStateMachine: useWiFiOffloading() : false
09-13 22:55:45.069  1035  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-13 22:55:45.081  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-13 22:55:45.100  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 22:55:45.103  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-13 22:55:45.109  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:45.111  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:45.125  1035  1522 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-13 22:55:45.125  1035  1522 D WifiMonitor: connecting to supplicant
,09-13 22:55:45.128  7614  7614 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-13 22:55:45.145  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 22:55:45.145  6962  6962 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 22:55:45.145  6962  6962 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 22:55:45.145  6962  6962 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 22:55:45.149  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 22:55:45.151  6962  6962 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 22:55:45.151  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-13 22:55:45.151  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 22:55:45.151  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 22:55:45.152  6962  6962 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 22:55:45.152  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-13 22:55:45.152  6962  6962 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-13 22:55:45.173  7614  7614 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-13 22:55:45.173  7614  7614 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-13 22:55:45.176  6940  6940 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 22:55:45.177  1035  1117 D Tethering: InitialState.processMessage what=4
09-13 22:55:45.181  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 22:55:45.182  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-13 22:55:45.188  7006  7633 W FormManager: Network not available. Please check & try again.
09-13 22:55:45.191  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:45.194  7006  7634 V FormManager: Network unavailable.
09-13 22:55:45.198  7006  7634 V FormManager: Network unavailable.
,09-13 22:55:45.208  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 22:55:45.208  6962  6962 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 22:55:45.208  6962  6962 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 22:55:45.208  6962  6962 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 22:55:45.209  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 22:55:45.210  6962  6962 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 22:55:45.210  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 22:55:45.210  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 22:55:45.210  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 22:55:45.210  6962  6962 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 22:55:45.210  6962  6962 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-13 22:55:45.276  7614  7614 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-13 22:55:45.292  7614  7614 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-13 22:55:45.296  1035  1560 D WifiServiceImplEx: setWifiEnabled: true pid=6804, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 22:55:45.297  1035  1560 D WifiService: setWifiEnabled: true pid=6804, uid=10118
,09-13 22:55:45.297  1035  1560 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 22:55:45.299  7614  7614 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-13 22:55:45.300  1035  1522 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,09-13 22:55:45.301  1035  1522 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-13 22:55:45.303  1035  1522 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-13 22:55:45.304  1035  1522 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-13 22:55:45.305  1035  7635 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-13 22:55:45.305  1035  7635 D WifiMonitor: Dropping event because (p2p0) is stopped
09-13 22:55:45.305  1035  1522 E WifiStateMachine:  SupplicantStartingState CMD_START_SUPPLICANT 0 0
09-13 22:55:45.306  1035  1522 E WifiStateMachine:  SupplicantStartingState CMD_START_SUPPLICANT 0 0
09-13 22:55:45.308  1035  1522 E WifiStateMachine:  SupplicantStartingState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3466] from screen [on:0 period:626362780] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 22:55:45.310  1035  1522 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:626362782] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 22:55:45.312  1035  1522 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-13 22:55:45.313  1035  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-13 22:55:45.314  1035  1522 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,09-13 22:55:45.315  1035  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 22:55:45.316  1035  1522 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-13 22:55:45.317  1035  1522 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-13 22:55:45.317  1035  1522 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-13 22:55:45.318  1035  1522 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-13 22:55:45.318  1035  1522 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-13 22:55:45.319  1035  1522 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 22:55:45.319  1035  1522 E WifiStateMachine: useWiFiOffloading() : false
09-13 22:55:45.319  1035  1522 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 22:55:45.319  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:45.319  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:45.320  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:45.320  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:45.320  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 22:55:45.321  7614  7614 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-13 22:55:45.321  1035  7635 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-13 22:55:45.321  1035  7635 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-13 22:55:45.322  1035  7635 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-13 22:55:45.322  1035  7635 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-13 22:55:45.322  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:45.322  1035  7635 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-13 22:55:45.322  1035  7635 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-13 22:55:45.325  1926  1926 D WfdService: Waiting for WifiP2p enabling
,09-13 22:55:45.328  1035  1522 D WifiNative-wlan0: doBoolean: SET update_config 1
09-13 22:55:45.328  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-13 22:55:45.329  1035  1522 D WifiNative-wlan0: SET update_config 1: returned true
09-13 22:55:45.329  1035  1522 D WifiConfigStore: Loading config and enabling all networks 
09-13 22:55:45.329  1035  1522 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-13 22:55:45.329  1035  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-13 22:55:45.329  1035  1522 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-13 22:55:45.331  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:45.331  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:45.331  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:45.331  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:45.331  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:45.331  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:55:45.331  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:55:45.331  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 22:55:45.334  6804  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 22:55:45.340  1035  1522 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-13 22:55:45.341  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:45.341  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:45.341  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:45.341  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:45.341  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:45.341  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:55:45.341  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:55:45.341  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 22:55:45.345  6804  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 22:55:45.347  6940  6940 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 22:55:45.349  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-13 22:55:45.356  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:45.357  1035  1522 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-13 22:55:45.357  1035  1522 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-13 22:55:45.359  7006  7638 W FormManager: Network not available. Please check & try again.
09-13 22:55:45.360  1035  1522 D WifiStateMachine: enableVerboseLogging : level 2
09-13 22:55:45.360  1035  1522 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-13 22:55:45.360  1035  1522 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-13 22:55:45.360  1035  1522 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-13 22:55:45.361  1035  1522 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-13 22:55:45.361  1035  1522 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-13 22:55:45.361  1035  1522 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-13 22:55:45.361  1035  1522 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-13 22:55:45.362  1035  1522 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-13 22:55:45.362  1035  1522 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-13 22:55:45.362  1035  1522 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-13 22:55:45.362  1035  1522 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
,09-13 22:55:45.363  1035  1522 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-13 22:55:45.363  1035  1522 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-13 22:55:45.363  1035  1522 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-13 22:55:45.364  1035  1522 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 22:55:45.364  1035  1522 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-13 22:55:45.365  1035  1522 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-13 22:55:45.365  1035  1522 D WifiNative-HAL: Setting external_sim to 1
09-13 22:55:45.365  1926  1926 D WfdsService: Supplicant Connection state is changed : true
09-13 22:55:45.365  1035  1522 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-13 22:55:45.365  1926  2306 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-13 22:55:45.365  1926  2306 D WfdsService: Set the WFDS Monitor: true
09-13 22:55:45.365  1926  2306 D WfdsMonitor: WfdsMonitorThread create
09-13 22:55:45.365  1926  2306 D WfdsMonitor: WFDS Monitor is created and started
09-13 22:55:45.365  1926  2306 D WfdsService: WiFi: Supplicant connection re-established
09-13 22:55:45.365  1035  1522 D WifiNative-wlan0: SET external_sim 1: returned true
09-13 22:55:45.365  1035  1522 I WifiNative-HAL: startHal
09-13 22:55:45.366  1035  1522 D wifi    : setting scan oui 0x953a6520
09-13 22:55:45.366  1035  1522 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 22:55:45.366  1035  1522 I WifiNative-HAL: startHal
09-13 22:55:45.366  1035  1522 D wifi    : setting scan oui 0x953a6520
09-13 22:55:45.366  1926  7640 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-13 22:55:45.366  1035  1522 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-13 22:55:45.366  1926  7640 E CtrlSupplicant: Succeed to open control connection
09-13 22:55:45.367  1926  7640 E CtrlSupplicant: Succeed to open monitor connection
09-13 22:55:45.367  1035  1522 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-13 22:55:45.367  1926  7640 D WfdsMonitor: Supplicant connection established
09-13 22:55:45.367  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-13 22:55:45.367  1926  2306 D WfdsService: Connected to the supplicant for wfds
09-13 22:55:45.367  7614  7614 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-13 22:55:45.368  1035  1522 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-13 22:55:45.368  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 22:55:45.368  7614  7614 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,09-13 22:55:45.368  1035  1522 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 22:55:45.368  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-13 22:55:45.368  7614  7614 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-13 22:55:45.369  1035  1522 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-13 22:55:45.369  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 22:55:45.369  7614  7614 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 22:55:45.369  1035  1522 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
,09-13 22:55:45.369  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 22:55:45.369  7614  7614 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,09-13 22:55:45.373  1035  1522 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 22:55:45.373  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-13 22:55:45.373  7614  7614 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-13 22:55:45.373  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 22:55:45.374  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 22:55:45.374  7006  7639 V FormManager: Network unavailable.
09-13 22:55:45.376  7006  7639 V FormManager: Network unavailable.
09-13 22:55:45.376  1035  1522 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-13 22:55:45.376  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 22:55:45.376  7614  7614 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 22:55:45.376  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 22:55:45.376  1035  1522 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 22:55:45.377  1035  1522 E WifiNative: : [201,632,967 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-13 22:55:45.377  1035  1522 D WifiNative-wlan0: doBoolean: RECONNECT
,09-13 22:55:45.378  1035  1522 D WifiNative-wlan0: RECONNECT: returned true
09-13 22:55:45.378  1035  1522 D WifiNative-wlan0: doString: [STATUS]
09-13 22:55:45.378  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 22:55:45.378  1035  7635 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-13 22:55:45.378  1035  7635 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-13 22:55:45.379  1035  1522 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 22:55:45.379  1035  1522 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 22:55:45.379  1035  1522 D WifiNative-wlan0: SET ps 1: returned true
09-13 22:55:45.380  1035  1519 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:45.381   315   879 D CommandListener: Setting iface cfg
09-13 22:55:45.381   315   879 D CommandListener: Trying to bring up p2p0
09-13 22:55:45.381  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
09-13 22:55:45.381  1035  1519 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-13 22:55:45.382  1035  1519 D LGWifiP2pService: P2pEnablingState
09-13 22:55:45.382  1035  1035 D RttService: SCAN_AVAILABLE : 3
09-13 22:55:45.382  1035  1522 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-13 22:55:45.382  1035  1519 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:45.382  1035  1519 D LGWifiP2pService: P2p socket connection successful
09-13 22:55:45.382  1035  1519 D LGWifiP2pService: P2pEnabledState
09-13 22:55:45.382  1035  1541 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:45.382  1035  1540 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:45.382  1035  1540 I WifiNative-HAL: startHal
09-13 22:55:45.382  1035  1540 D wifi    : getting scan capabilities on interface[1] = 0x953a6520
09-13 22:55:45.382  1035  1540 D wifi    : failed to get capabilities : -3
09-13 22:55:45.382  1035  1540 E WifiScanningService: could not get scan capabilities
09-13 22:55:45.382  1035  1519 D LGWifiP2pService: sending p2p connection changed broadcast
09-13 22:55:45.382  1035  1522 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-13 22:55:45.382  1035  1522 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-13 22:55:45.383  1035  1522 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-13 22:55:45.383  1035  1522 E WifiStateMachine:  DisconnectedState CMD_START_SUPPLICANT 0 0
09-13 22:55:45.383  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-13 22:55:45.384  1926  1926 D WfdsService: WifiP2pState is changed : true
09-13 22:55:45.384  1035  1519 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-13 22:55:45.384  1926  2306 D WfdsService: Receive the WFDS_ENABLE Method
09-13 22:55:45.384  1926  2306 D WfdsService: Set the WFDS Monitor: true
09-13 22:55:45.384  1926  2306 D WfdsService: Connected to the supplicant for wfds
09-13 22:55:45.384  1926  2306 D WfdsJNI : doCommand: WFDS_SET TRUE
09-13 22:55:45.384  7614  7614 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-13 22:55:45.385  1035  1519 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-13 22:55:45.385  1035  1519 D WifiNative-p2p0: doBoolean: SET device_name G3
09-13 22:55:45.385  1035  1519 D WifiNative-p2p0: SET device_name G3: returned true
09-13 22:55:45.385  1035  1519 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-13 22:55:45.385  1035  1519 D LGWifiP2pService: before postfix = G3
09-13 22:55:45.385  1035  1519 D WifiServerServiceExt: postfix byte check : 2
09-13 22:55:45.385  1035  1519 D LGWifiP2pService: after postfix = G3
09-13 22:55:45.385  1035  1519 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-13 22:55:45.386  1926  1926 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
,09-13 22:55:45.387  1926  1926 D WfdsService: isConnected: false
09-13 22:55:45.387  1926  2306 D WfdsService: selectPreferredScanChannel [36]
09-13 22:55:45.387  1926  2306 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-13 22:55:45.387  1035  1519 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-13 22:55:45.387  1035  1519 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-13 22:55:45.384  1035  1522 E WifiStateMachine:  ConnectModeState CMD_START_SUPPLICANT 0 0
09-13 22:55:45.388  1035  1522 E WifiStateMachine:  DriverStartedState CMD_START_SUPPLICANT 0 0
09-13 22:55:45.388  1035  1522 E WifiStateMachine:  SupplicantStartedState CMD_START_SUPPLICANT 0 0
09-13 22:55:45.389  1035  1522 E WifiStateMachine:  DefaultState CMD_START_SUPPLICANT 0 0
09-13 22:55:45.389  1035  1522 E WifiStateMachine:  DisconnectedState CMD_START_SUPPLICANT 0 0
09-13 22:55:45.390  1035  1522 E WifiStateMachine:  ConnectModeState CMD_START_SUPPLICANT 0 0
09-13 22:55:45.390  1035  1522 E WifiStateMachine:  DriverStartedState CMD_START_SUPPLICANT 0 0
09-13 22:55:45.390  5608  5608 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-13 22:55:45.390  5608  5608 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-13 22:55:45.390  5608  5608 V [BNRBootReceiver]: Boot Receiver Return
09-13 22:55:45.391  1035  1522 E WifiStateMachine:  SupplicantStartedState CMD_START_SUPPLICANT 0 0
09-13 22:55:45.391  1035  1519 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-13 22:55:45.391  1035  1519 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-13 22:55:45.392  1035  1519 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-13 22:55:45.392  1035  1519 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-13 22:55:45.392  1035  1519 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-13 22:55:45.392  1035  1519 D WifiNative-HAL: p2pGetDeviceAddress
09-13 22:55:45.392  1035  1519 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-13 22:55:45.393  1035  1522 E WifiStateMachine:  DefaultState CMD_START_SUPPLICANT 0 0
09-13 22:55:45.393  1035  1519 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-13 22:55:45.393  1035  1519 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-13 22:55:45.394  1035  1519 D WifiNative-p2p0: P2P_FLUSH: returned true
09-13 22:55:45.394  1035  1519 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-13 22:55:45.394  1035  1519 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-13 22:55:45.394  1035  1519 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-13 22:55:45.394  1035  1519 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-13 22:55:45.395  1035  1519 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-13 22:55:45.395  1926  1926 I WfdStateTracker: handleP2pThisDeviceChanged
09-13 22:55:45.395  1926  1926 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-13 22:55:45.395  1926  1926 D WfdsService: Update P2p Interface State: 3
09-13 22:55:45.396  4747  7641 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 22:55:45.396  1035  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=201652  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 22:55:45.397  1035  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=201653  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 22:55:45.397  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:45.397  1035  1522 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-13 22:55:45.397  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 22:55:45.398  1035  1522 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-13 22:55:45.398  1035  1522 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-13 22:55:45.398  1035  1522 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-13 22:55:45.398  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:45.399  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:45.399  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,09-13 22:55:45.400  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:45.401  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 22:55:45.404  4747  7642 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 22:55:45.404  4747  7642 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 22:55:45.409  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 22:55:45.414  7614  7614 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-13 22:55:45.415  1035  1522 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-13 22:55:45.415  1035  1522 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-13 22:55:45.416  1035  1522 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-13 22:55:45.416  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 22:55:45.416  1035  1522 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-13 22:55:45.416  7614  7614 E wpa_supplicant: disconnect_rssi_lvl: -100
09-13 22:55:45.416  1035  1519 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-13 22:55:45.416  1035  1519 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-13 22:55:45.417  1035  1522 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-13 22:55:45.417  1035  1522 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-13 22:55:45.418  1035  1522 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-13 22:55:45.418  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-13 22:55:45.418  7614  7614 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 22:55:45.418  1035  1519 D LGWifiP2pService: InactiveState
09-13 22:55:45.418  1035  1519 D LGWifiP2pService: InactiveState{ when=-24ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:45.419  1035  1519 D LGWifiP2pService: P2pEnabledState{ when=-25ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:45.419  1035  1519 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-13 22:55:45.419  7614  7614 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 22:55:45.420  7614  7614 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 22:55:45.420  7614  7614 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:45.421  7614  7614 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:45.421  1926  7640 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 22:55:45.421  1926  7640 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 22:55:45.421  1035  1522 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-13 22:55:45.422  1035  1522 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-13 22:55:45.422  1035  1522 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-13 22:55:45.419  1035  7635 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 22:55:45.423  1035  7635 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 22:55:45.423  1035  7635 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 22:55:45.423  1035  7635 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 22:55:45.423  1035  7635 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 22:55:45.423  1035  1522 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-13 22:55:45.423  1035  7635 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:45.423  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-13 22:55:45.423  1035  7635 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:45.423  1035  7635 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:45.423  7614  7614 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-13 22:55:45.423  7614  7614 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 22:55:45.424  1035  7635 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 22:55:45.424  1035  7635 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:45.424  1035  1522 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-13 22:55:45.424  1035  7635 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:45.424  1035  7635 E WifiMonitor: handleEvent unknown: 14  CTRL-EV,ENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:45.424  1035  1522 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-13 22:55:45.424  1035  7635 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-13 22:55:45.424  1035  7635 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 22:55:45.424  1035  7635 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 22:55:45.424  1035  7635 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 22:55:45.425  1035  1522 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-13 22:55:45.425  1035  1522 D WifiNative-wlan0: doBoolean: SCAN
09-13 22:55:45.425  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 22:55:45.425  7614  7614 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 22:55:45.426  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 22:55:45.426  7614  7614 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,09-13 22:55:45.426  7614  7614 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 22:55:45.427  7614  7614 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:45.427  6986  6986 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 22:55:45.427  1035  1519 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-13 22:55:45.427  1035  1519 D LGWifiP2pService: InactiveState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:45.427  1035  1519 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:45.427  7614  7614 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:45.427  1035  1519 D LGWifiP2pService: DefaultState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:45.427  1035  1519 D LGWifiP2pService: InactiveState{ when=-9ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:45.427  1035  1519 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:45.427  1035  1519 D LGWifiP2pService: DefaultState{ when=-9ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:45.428  1035  1519 D LGWifiP2pService: InactiveState{ when=-6ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:45.428  1035  1519 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:45.428  1035  1519 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:45.428  1035  1519 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:45.428  1035  1519 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:45.428  1035  1519 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:45.428  1035  1519 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:45.428  1035  1519 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:45.428  1035  1035 E WifiServerServiceExt: No p2p device connected
09-13 22:55:45.429  1926  7640 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 22:55:45.429  1926  2306 W WfdsService: DefaultState - msg [9441285] is not handled
09-13 22:55:45.429  1926  7640 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 22:55:45.429  1926  7640 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 22:55:45.429  1035  7635 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 22:55:45.429  1035  7635 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 22:55:45.429  1035  7635 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 22:55:45.429  1035  7635 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 22:55:45.429  1035  7635 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 22:55:45.429  1035  7635 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:45.429  1035  1522 D WifiNative-wlan0: SCAN: returned false
09-13 22:55:45.429  1035  7635 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type,=WORLD
09-13 22:55:45.429  1035  7635 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:45.430  1035  7635 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 22:55:45.430  1035  7635 E WifiMonitor: WifiMonitor:p2p0 cnt=54 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:45.430  1035  7635 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:45.430  1035  7635 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 22:55:45.430  1035  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=201686  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 22:55:45.432  1035  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=201688  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 22:55:45.432  1035  1522 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 22:55:45.433  1035  1522 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 22:55:45.433  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:45.433  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 22:55:45.433  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:45.433  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:45.434  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 22:55:45.434  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:45.435  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 22:55:45.435  1035  1522 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 22:55:45.436  1035  1522 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 22:55:45.436  1035  1522 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 22:55:45.436  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 22:55:45.436  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
09-13 22:55:45.440  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 22:55:45.441  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
,09-13 22:55:45.444  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 22:55:45.449  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:45.454  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 22:55:45.454  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 22:55:45.455  6986  6986 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 22:55:45.807  6804  7597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:45.807  6804  7597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:45.807  6804  7597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:45.807  6804  7597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:45.807  6804  7597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:45.807  6804  7597 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 22:55:45.807  6804  7597 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 22:55:45.807  6804  7597 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 22:55:45.811  6804  7597 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 22:55:45.813  6804  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:45.815  6804  6873 D BluetoothAdapter: enable(): BT is already enabled..!
09-13 22:55:45.816  1035  1943 D WifiServiceImplEx: setWifiEnabled: true pid=6804, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 22:55:45.816  1035  1943 D WifiService: setWifiEnabled: true pid=6804, uid=10118
09-13 22:55:45.816  1035  1943 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 22:55:45.830  6804  7652 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-13 22:55:45.830  6804  7652 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 22:55:45.963  7614  7614 E wpa_supplicant: USIM:  scard_init function
09-13 22:55:45.963  7614  7614 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-13 22:55:45.970  1035  7635 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-13 22:55:45.970  1035  7635 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-13 22:55:45.970  1035  7635 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-13 22:55:45.970  1035  7635 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: WPS-AP-AVAILABLE 
09-13 22:55:45.970  1035  7635 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-13 22:55:45.970  1035  7635 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-13 22:55:45.970  1035  7635 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-13 22:55:45.971  1035  1522 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-13 22:55:45.972  1035  1522 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-13 22:55:45.972  1035  1522 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-13 22:55:45.972  1035  1522 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-13 22:55:45.973  1035  1522 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-13 22:55:45.996  1035  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=202252  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-13 22:55:46.005  1035  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=202261  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-13 22:55:46.008  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:46.008  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:46.008  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 22:55:46.009  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:46.009  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 22:55:46.013  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 22:55:46.016  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 22:55:46.016  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-13 22:55:46.020  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-13 22:55:46.031  6962  6962 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-13 22:55:46.040  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 22:55:46.050  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 22:55:46.060  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:46.067  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 22:55:46.068  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 22:55:46.068  6986  6986 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 22:55:46.088  7614  7614 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 22:55:46.095  1035  7635 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-13 22:55:46.095  1035  7635 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-13 22:55:46.095  1035  7635 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-13 22:55:46.095  1035  7635 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-13 22:55:46.095  1035  7635 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 22:55:46.095  1035  7635 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 22:55:46.099  7614  7614 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 22:55:46.099  7614  7614 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 22:55:46.101  1035  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=202357  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,09-13 22:55:46.106  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-13 22:55:46.113  1035  7635 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 22:55:46.113  1035  7635 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 22:55:46.114  1035  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=202370  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 22:55:46.115  1035  1522 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=202371
09-13 22:55:46.115  1035  1522 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=202371
09-13 22:55:46.116  1035  1522 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=202372
09-13 22:55:46.116  1035  1522 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=202372
09-13 22:55:46.116  1035  1522 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=202373
09-13 22:55:46.117  1035  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=202373  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-13 22:55:46.125  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:46.125  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 22:55:46.127  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:46.129  1035  7635 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-13 22:55:46.129  1035  7635 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 22:55:46.130  1035  7635 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 22:55:46.130  1035  7635 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-13 22:55:46.130  1035  7635 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 22:55:46.130  1035  7635 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 22:55:46.130  1035  7635 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 22:55:46.130  1035  7635 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-13 22:55:46.140  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:46.140  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:46.140  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 22:55:46.146  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:46.146  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:46.146  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-13 22:55:46.148  1035  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=202404  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-13 22:55:46.154  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:46.154  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 22:55:46.156  1035  1522 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-13 22:55:46.157  1035  1522 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-13 22:55:46.157  1035  1522 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 22:55:46.158  1035  1522 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 22:55:46.158  1035  1522 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 22:55:46.160  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:46.177  1035  1522 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=202414  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 22:55:46.178  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 22:55:46.178  6962  6962 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 22:55:46.178  6962  6962 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 22:55:46.178  6962  6962 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-13 22:55:46.181  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 22:55:46.183  1035  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=202438  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 22:55:46.183  6962  6962 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 22:55:46.184  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-13 22:55:46.184  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 22:55:46.184  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 22:55:46.184  6962  6962 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 22:55:46.184  6962  6962 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-13 22:55:46.184  6962  6962 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 22:55:46.185  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 22:55:46.185  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-13 22:55:46.190  1035  1522 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=202446
09-13 22:55:46.191  1035  1522 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=202447
09-13 22:55:46.192  1035  1522 D WifiNative-wlan0: doString: [STATUS]
,09-13 22:55:46.193  1035  7635 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 22:55:46.193  1035  7635 E WifiMonitor: WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 22:55:46.194  1035  1522 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 22:55:46.196  1035  1522 I WifiServiceExtension: setVHTCapabilityType  : false
09-13 22:55:46.199  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 22:55:46.206  1035  1522 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-13 22:55:46.206  1035  1522 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-13 22:55:46.212  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:46.212  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:46.212  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 22:55:46.213  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:46.213  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 22:55:46.214  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:46.222  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:46.222  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:46.222  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-13 22:55:46.225  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 22:55:46.233  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:46.235  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:46.235  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 22:55:46.235  1035  1522 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-13 22:55:46.235  1035  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 22:55:46.235  1035  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 22:55:46.236  1035  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 22:55:46.236  1035  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-13 22:55:46.238  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:46.238  1035  1529 D ConnectivityService: Got NetworkAgent Messenger
09-13 22:55:46.239  1035  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-13 22:55:46.239  1035  1529 D ConnectivityService: NetworkAgent connected
09-13 22:55:46.240  1035  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 22:55:46.240  1035  1522 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 22:55:46.240  1035  1522 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 22:55:46.240  1035  1522 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 22:55:46.240  1035  1522 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 22:55:46.244  1035  1522 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 22:55:46.246   315   879 D CommandListener: Setting iface cfg
09-13 22:55:46.248  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 22:55:46.248  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 22:55:46.249  6986  6986 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 22:55:46.252  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 22:55:46.253  1035  1522 E WifiStateMachine: Start Dhcp Watchdog 3
09-13 22:55:46.254  1035  1522 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=202510  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 22:55:46.255  1035  1522 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=202510  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 22:55:46.255  1035  7673 D DhcpStateMachine: StoppedState
09-13 22:55:46.255  1035  7673 D DhcpStateMachine: StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:46.255  1035  7673 D DhcpStateMachine: WaitBeforeStartState
09-13 22:55:46.255  1035  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=202511  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 22:55:46.260  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 22:55:46.260  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-13 22:55:46.264  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 22:55:46.264  1035  1522 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=202520  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 22:55:46.265  1035  1522 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=202521  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 22:55:46.265  1035  1522 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=202521  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-13 22:55:46.267  1035  1522 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:955] from screen [on:0 period:626363738] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 22:55:46.267  1035  1522 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:626363739] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-13 22:55:46.268  1035  1522 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-13 22:55:46.269  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 22:55:46.269  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-13 22:55:46.271  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:46.273  1035  1529 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-13 22:55:46.274  1035  1522 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:46.274  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:46.274  1035  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:46.274  1035  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:46.275  1035  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:46.275  1035  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:46.276  1035  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 22:55:46.276  1035  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-13 22:55:46.276  1035  1522 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=183,0,0
09-13 22:55:46.277  1035  1522 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=183,0,0
09-13 22:55:46.277  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-13 22:55:46.277  7614  7614 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-13 22:55:46.278  1035  1522 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-13 22:55:46.278  1035  1522 D WifiNative-wlan0: doBoolean: SET ps 0
09-13 22:55:46.278  1035  1522 D WifiNative-wlan0: SET ps 0: returned true
09-13 22:55:46.278  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-13 22:55:46.278  7614  7614 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-13 22:55:46.279  1035  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-13 22:55:46.279  1035  1522 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-13 22:55:46.279  1035  1522 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 22:55:46.279  1035  1522 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 22:55:46.280   315   879 D CommandListener: Setting iface cfg
09-13 22:55:46.281   315   879 D CommandListener: Trying to bring up wlan0
09-13 22:55:46.281  1035  1522 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
,09-13 22:55:46.283  1035  1519 D LGWifiP2pService: InactiveState{ when=-4ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@15f706d6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:46.283  1035  1519 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@15f706d6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:46.283  1035  7673 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:46.283  1035  7673 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-13 22:55:46.284  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 22:55:46.285  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 22:55:46.285  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 22:55:46.285  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 22:55:46.285  1035  1522 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
09-13 22:55:46.285  6986  6986 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 22:55:46.286  1035  1522 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
09-13 22:55:46.287  1035  1519 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:46.287  1035  1519 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:46.287  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 22:55:46.287  7614  7614 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 22:55:46.288  1035  1522 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 22:55:46.288  1035  1522 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-13 22:55:46.288  7614  7614 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-13 22:55:46.288  1035  1522 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-13 22:55:46.288  1035  1522 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 22:55:46.289  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 22:55:46.297  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 22:55:46.302  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:46.305  1035  1522 D WifiNative-wlan0: SET ps 1: returned true
09-13 22:55:46.306  1035  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-13 22:55:46.306  1035  1522 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 22:55:46.306  1035  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 22:55:46.307  1035  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 22:55:46.307  1035  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 22:55:46.308  1035  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 22:55:46.308  1035  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 22:55:46.308  1035  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,09-13 22:55:46.312  1035  1522 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 22:55:46.312  1035  1522 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 22:55:46.312  1035  1522 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-13 22:55:46.313  1035  1529 D ConnectivityService: ignoring duplicate network state non-change
09-13 22:55:46.313  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 22:55:46.315  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 22:55:46.315  6986  6986 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 22:55:46.317  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:46.317  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 22:55:46.317  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:46.317  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:46.317  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 22:55:46.318  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:46.319  1035  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-13 22:55:46.320  1035  1529 D ConnectivityService: Adding iface wlan0 to network 102
,09-13 22:55:46.323  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:46.323  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:46.323  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 22:55:46.327  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 22:55:46.328  1035  1522 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-13 22:55:46.329  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-13 22:55:46.333  1926  1926 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-13 22:55:46.333  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:46.333  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:46.333  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 22:55:46.337  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-13 22:55:46.339  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:46.339  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 22:55:46.340  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:46.342  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:46.343  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 22:55:46.343  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:46.343  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:46.343  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 22:55:46.343  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 22:55:46.344  1035  1529 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-13 22:55:46.344  1035  1529 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-13 22:55:46.346  6804  7652 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-13 22:55:46.346  6804  7652 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 22:55:46.347  1035  1529 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-13 22:55:46.347  6804  7652 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 22:55:46.347  6804  7652 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 22:55:46.347   315   879 E Netd    : netlink response contains error (File exists)
09-13 22:55:46.348  6804  7675 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-13 22:55:46.348  6804  7675 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 22:55:46.348  6804  7675 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 22:55:46.348  1035  1529 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-13 22:55:46.349  1035  1529 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-13 22:55:46.349  1035  1529 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-13 22:55:46.349  1035  1529 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-13 22:55:46.349  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:46.349  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 22:55:46.350  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:46.351  6804  7675 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 22:55:46.351  6804  7679 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 964, name: OutgoingSocketThread/Sender)
09-13 22:55:46.351  6804  7652 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-13 22:55:46.351  6804  7675 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 22:55:46.354  1035  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 22:55:46.355  1035  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-13 22:55:46.355  1035  1529 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-13 22:55:46.355  1035  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-13 22:55:46.355  1035  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 22:55:46.355  1035  7670 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:46.355  1035  7670 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-13 22:55:46.355  1035  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 22:55:46.355  1035  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 22:55:46.355  1035  7670 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:46.355  1035  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:46.355  1035  7670 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-13 22:55:46.355  1035  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-13 22:55:46.355  6804  7680 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 966, name: IncomingSocketThread/Sender)
09-13 22:55:46.355  1035  1529 D ConnectivityService: currentScore = 0, newScore = 20
09-13 22:55:46.355  1035  1529 D ConnectivityService:    accepting network in place of null
09-13 22:55:46.355  1035  1529 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:46.356  1836  1836 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:46.356  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 22:55:46.357  1035  1522 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:46.357  1035  1522 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 22:55:46.357  1035  1529 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-13 22:55:46.357  1035  1529 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-13 22:55:46.357  1035  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 22:55:46.358   315  7684 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-13 22:55:46.359  6804  7681 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 965, name: OutgoingSocketThread/Receiver)
09-13 22:55:46.360  6804  7681 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 965, thread name: OutgoingSocketThread/Receiver)
09-13 22:55:46.360  6804  7681 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 22:55:46.360  6804  7681 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 965, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-13 22:55:46.362  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 22:55:46.362  1035  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:46.362  1035  1529 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-13 22:55:46.363  6804  7682 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 967, name: IncomingSocketThread/Receiver)
09-13 22:55:46.364  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-13 22:55:46.364  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 22:55:46.364  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 22:55:46.364  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 22:55:46.366  1035  1529 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-13 22:55:46.368  6804  7682 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 967, thread name: IncomingSocketThread/Receiver)
09-13 22:55:46.368  6804  7682 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 22:55:46.368  6804  7682 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 967, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-13 22:55:46.369  1035  1529 D ConnectivityService: validation of new default Network = false
09-13 22:55:46.369  1035  1529 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-13 22:55:46.369  1035  1529 D DSQN    : enableDataServiceNotify 
09-13 22:55:46.369  1035  1529 D DSQN    : start dsqn bin
,09-13 22:55:46.375  1035  1518 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-13 22:55:46.376  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:46.376  1035  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-13 22:55:46.376  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:46.376  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 22:55:46.377  1035  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 22:55:46.366  7685  7685 W dsqn    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 22:55:46.366  7685  7685 W dsqn    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 22:55:46.378  1586  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 22:55:46.386  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 22:55:46.387  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 22:55:46.387  6986  6986 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 22:55:46.389  7685  7685 E DSQN    : DSQN ssw
09-13 22:55:46.393  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 22:55:46.400  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 22:55:46.406  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:46.408   315  7684 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-13 22:55:46.411  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 22:55:46.412  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 22:55:46.412  6986  6986 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 22:55:46.415  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 22:55:46.416  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:46.416  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 22:55:46.416  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:46.423  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 22:55:46.430  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:46.436  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 22:55:46.437  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 22:55:46.438  6986  6986 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 22:55:46.441   315  7684 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-13 22:55:46.442  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 22:55:46.447  6940  6940 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-13 22:55:46.448  6940  6940 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-13 22:55:46.451  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 22:55:46.456  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:46.464  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 22:55:46.464  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 22:55:46.466  6986  6986 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 22:55:46.466  6986  6986 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 22:55:46.467  6986  6986 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 22:55:46.467   315   878 D LGDataListener: argv[0]=dsqncommand
09-13 22:55:46.467   315   878 D LGDataListener: argv[1]=wlan0
09-13 22:55:46.467   315   878 D LGDataListener: argv[2]=1
09-13 22:55:46.467   315   878 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-13 22:55:46.467  1035  1115 D DSQN    : DSQM DsqnNotification wlan0  1
09-13 22:55:46.467  1035  1115 D DSQN    : start to monitor internet connection
09-13 22:55:46.476  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 22:55:46.483  6940  6940 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-13 22:55:46.486  6940  6940 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-13 22:55:46.487  1035  7673 D DhcpStateMachine: DHCPV4 request on wlan0
09-13 22:55:46.490  1035  7673 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-13 22:55:46.490  1035  7673 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-13 22:55:46.492  1035  7670 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 20:55:46 GMT], X-Android-Received-Millis=[1473800146491], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473800146465]}
09-13 22:55:46.492  1035  7670 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-13 22:55:46.492  1035  7670 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-13 22:55:46.492  1035  1529 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-13 22:55:46.493  1035  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-13 22:55:46.493  1035  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 22:55:46.493  6962  6962 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 22:55:46.493  1035  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 22:55:46.493  1035  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 22:55:46.493  1035  1529 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-13 22:55:46.493  1035  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-13 22:55:46.493  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:46.493  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 22:55:46.494  1035  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 22:55:46.494  1035  1529 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:46.494  1586  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 22:55:46.496  1836  1836 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:46.497  1035  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-13 22:55:46.497  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 22:55:46.486  7691  7691 W dhcpcd  : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 22:55:46.497  1035  1522 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:46.486  7691  7691 W dhcpcd  : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=8455 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 22:55:46.504  6962  6962 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 22:55:46.508  7691  7691 I dhcpcd  : version 5.5.6 starting
09-13 22:55:46.511  7691  7691 E dhcpcd  : get_duid: m
09-13 22:55:46.511  7691  7691 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-13 22:55:46.511  7691  7691 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,09-13 22:55:46.513  6986  6986 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 22:55:46.513  6986  6986 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 22:55:46.514  6986  6986 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 22:55:46.515  6986  6986 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 22:55:46.516  6986  6986 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 22:55:46.535  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 22:55:46.536  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 22:55:46.537  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 22:55:46.588  7691  7691 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,09-13 22:55:46.588  7691  7691 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,09-13 22:55:46.588  7691  7691 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,09-13 22:55:46.589  7691  7691 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-13 22:55:46.589  7691  7691 D dhcpcd  : wlan0: sending REQUEST (xid 0x1b8c3b7f), next in 4.17 seconds
09-13 22:55:46.639  7385  7409 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-13 22:55:46.648  7691  7691 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-13 22:55:46.650  7691  7691 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
,09-13 22:55:46.650  7691  7691 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,09-13 22:55:46.651  7691  7691 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-13 22:55:46.651  7691  7691 D dhcpcd  : wlan0: adding default route via 192.168.1.1,
,09-13 22:55:46.651  7691  7691 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease',
,09-13 22:55:46.652  7691  7691 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1,
09-13 22:55:46.653  7691  7691 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2,
,09-13 22:55:46.653  7691  7691 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-13 22:55:46.844  1035  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 22:55:46.846  6804  6873 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-13 22:55:46.851  6804  6873 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-13 22:55:46.854  6804  6873 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@181cbbdd Bundle[{}]
09-13 22:55:46.855  6804  6873 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 22:55:46.855  6804  6873 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-13 22:55:46.856  6804  6873 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-13 22:55:46.856  6804  6873 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 22:55:46.857  6804  6873 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-13 22:55:46.858  6804  6873 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-13 22:55:46.859  1035  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:46.862  1035  1117 D Tethering: MasterInitialState.processMessage what=3
09-13 22:55:46.862  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:46.863  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-13 22:55:46.874  6804  7715 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-13 22:55:46.874  6804  7715 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-13 22:55:46.878  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-13 22:55:46.880  6408  6937 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 22:55:46.882  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-13 22:55:46.883  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:46.885  1035  1117 D Tethering: MasterInitialState.processMessage what=3
09-13 22:55:46.885  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:46.885  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:46.885  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:46.885  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:46.885  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:46.885  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:46.885  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:55:46.885  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 22:55:46.893  6804  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:46.901  5790  5790 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-13 22:55:46.906  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 22:55:46.906  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:46.906  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:46.906  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:46.906  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:46.906  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:46.906  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:55:46.906  6804  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 22:55:46.908  6804  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:46.911  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:46.913  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:46.917  5790  5790 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-13 22:55:46.929  2182  2182 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 22:55:46.938   315  7728 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 22:55:46.939   315  7728 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-13 22:55:46.940  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 22:55:46.940  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:46.941  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 22:55:46.941  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 22:55:46.943  7172  7172 I AppUp4:CustModeStarterReceiver: onReceive
,09-13 22:55:46.947  7172  7172 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@14363a33
09-13 22:55:46.947  7172  7172 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 22:55:46.947  7172  7172 D AppUp4:CustFacade: isPhone : true
09-13 22:55:46.948  7172  7172 D AppUp4:CustModeStarterReceiver: begin check event
09-13 22:55:46.948  7172  7172 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 22:55:46.952  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:46.952  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 22:55:46.955  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 22:55:46.958  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 22:55:46.962  3389  3389 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:46.967  3389  3389 V DownloadManager: DownloadService onCreate
09-13 22:55:46.967  4747  7733 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-13 22:55:46.970  3389  7735 I DownloadManager: in removeSpuriousFiles
09-13 22:55:46.971   315  7728 D libc-netbsd: res_queryN name = mtalk.google.com succeed
09-13 22:55:46.972  4747  7733 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-13 22:55:46.974  3389  7735 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-13 22:55:46.975  3389  7735 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2c518c62 on behalf of 3389
09-13 22:55:46.976  3389  7735 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-13 22:55:46.976  3389  7735 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-13 22:55:46.976  3389  7735 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-13 22:55:46.976  3389  7735 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-13 22:55:46.976  3389  7735 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-13 22:55:46.976  3389  7735 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-13 22:55:46.976  3389  7735 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-13 22:55:46.976  3389  7735 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-13 22:55:46.976  3389  7735 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-13 22:55:46.976  3389  7735 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-13 22:55:46.977  3389  7735 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-13 22:55:46.977  4747  7734 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:46.977  4747  7734 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 22:55:46.978  3389  7735 I DownloadManager: in trimDatabase
09-13 22:55:46.978  3389  7735 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-13 22:55:46.979  3389  7735 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@29c59eb0 on behalf of 3389
,09-13 22:55:46.982  4747  7733 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-13 22:55:46.983  3389  3389 V DownloadManager: DownloadService onStartCommand
09-13 22:55:46.986  4747  4747 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-13 22:55:46.987  4747  4747 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-13 22:55:46.987  4747  4747 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-13 22:55:46.989  4747  4747 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-13 22:55:46.991  3389  7736 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-13 22:55:46.992  7201  7739 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 22:55:46.992  4747  4747 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
,09-13 22:55:46.995  3389  7736 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@22c00cae on behalf of 3389
09-13 22:55:46.995  3275  3275 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 22:55:46.995  3275  3275 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:46.996  3275  3275 I LgeMiscReceiver: networkInfo.isConnected() = false
09-13 22:55:46.997  3389  7736 V DownloadManager: processing inserted download 1
09-13 22:55:46.998  7234  7234 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 22:55:46.999  3389  7736 V DownloadManager: processing inserted download 4
09-13 22:55:46.999  7234  7234 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 22:55:47.000  3389  7736 V DownloadManager: processing inserted download 7
09-13 22:55:47.001  3389  7736 V DownloadManager: processing inserted download 8
09-13 22:55:47.002  3389  7736 V DownloadManager: processing inserted download 9
09-13 22:55:47.003  3389  7736 V DownloadManager: processing inserted download 10
09-13 22:55:47.004  3389  7736 V DownloadManager: processing inserted download 11
09-13 22:55:47.004  3389  7736 V DownloadManager: processing inserted download 12
,09-13 22:55:47.006  7364  7364 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:55:47
09-13 22:55:47.007  3389  7736 V DownloadManager: processing inserted download 13
09-13 22:55:47.007  7364  7364 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 22:55:47.008  7364  7364 D Weather.Utils: 2 : All the weather widget is gone.
09-13 22:55:47.008  7364  7364 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 22:55:47.008  7364  7364 D WeatherAncestor: connectivity changed - connection : true
09-13 22:55:47.008  7364  7364 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3762a369
09-13 22:55:47.008  3389  7736 V DownloadManager: processing inserted download 14
09-13 22:55:47.009  7364  7364 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 22:55:47.009  7364  7364 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 22:55:47.009  7364  7364 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 22:55:47.009  7364  7364 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 22:55:47.009  7364  7364 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:55:47
09-13 22:55:47.009  3389  7736 V DownloadManager: processing inserted download 16
09-13 22:55:47.013  3389  3389 V DownloadManager: DownloadService onDestroy
09-13 22:55:47.021   315  7745 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 22:55:47.022   315  7745 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,09-13 22:55:47.043  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-13 22:55:47.044  6408  6937 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 22:55:47.056  2182  2182 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 22:55:47.062   315  7745 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
09-13 22:55:47.063  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,09-13 22:55:47.063  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,09-13 22:55:47.063  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 22:55:47.063  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 22:55:47.065  7172  7172 I AppUp4:CustModeStarterReceiver: onReceive
09-13 22:55:47.071  7172  7172 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@14363a33
,09-13 22:55:47.073  7172  7172 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 22:55:47.073  7172  7172 D AppUp4:CustFacade: isPhone : true
09-13 22:55:47.073  7172  7172 D AppUp4:CustModeStarterReceiver: begin check event
09-13 22:55:47.073  7172  7172 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 22:55:47.077  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:47.078  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 22:55:47.082  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 22:55:47.085  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 22:55:47.093  3389  3389 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:47.097  4747  7748 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:47.097  4747  7748 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 22:55:47.098  1035  7673 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-13 22:55:47.099  3389  3389 V DownloadManager: DownloadService onCreate
09-13 22:55:47.099  1035  7673 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-13 22:55:47.100  1035  7673 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 22:55:47.100  1035  7673 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-13 22:55:47.100  1035  7673 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-13 22:55:47.100  1035  7673 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 22:55:47.100  1035  7673 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-13 22:55:47.100  1035  7673 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-13 22:55:47.101  1035  7673 D DhcpStateMachine: RunningState
09-13 22:55:47.102  4747  7747 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 22:55:47.105  4747  7747 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-13 22:55:47.106  3389  7749 I DownloadManager: in removeSpuriousFiles
09-13 22:55:47.107  3389  7749 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-13 22:55:47.111  3389  7749 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3e5df5dc on behalf of 3389
09-13 22:55:47.112  3389  7749 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-13 22:55:47.112  3389  7749 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-13 22:55:47.112  3389  7749 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-13 22:55:47.112  3389  7749 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-13 22:55:47.112  3389  7749 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-13 22:55:47.112  3389  7749 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-13 22:55:47.113  3389  7749 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-13 22:55:47.113  3389  7749 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-13 22:55:47.113  3389  7749 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-13 22:55:47.113  3389  7749 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-13 22:55:47.113  3389  7749 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-13 22:55:47.114  3389  7749 I DownloadManager: in trimDatabase
09-13 22:55:47.114  3389  7749 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,09-13 22:55:47.116  3389  7749 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3312e6e5 on behalf of 3389
09-13 22:55:47.122  3389  3389 V DownloadManager: DownloadService onStartCommand
09-13 22:55:47.125  4747  7747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-13 22:55:47.126  3389  7750 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,09-13 22:55:47.129  3389  7750 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@22c293c8 on behalf of 3389
09-13 22:55:47.133  4747  4747 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-13 22:55:47.133  3389  7750 V DownloadManager: processing inserted download 1
09-13 22:55:47.133  4747  4747 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-13 22:55:47.133  4747  4747 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-13 22:55:47.134  3389  7750 V DownloadManager: processing inserted download 4
09-13 22:55:47.137  4747  4747 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-13 22:55:47.139  7201  7753 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 22:55:47.139  3389  7750 V DownloadManager: processing inserted download 7
09-13 22:55:47.141  4747  4747 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-13 22:55:47.144  3389  7750 V DownloadManager: processing inserted download 8
09-13 22:55:47.146  3389  7750 V DownloadManager: processing inserted download 9
09-13 22:55:47.149  3389  7750 V DownloadManager: processing inserted download 10
09-13 22:55:47.149  3275  3275 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 22:55:47.149  3275  3275 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:47.149  3275  3275 I LgeMiscReceiver: networkInfo.isConnected() = false
09-13 22:55:47.152  3389  7750 V DownloadManager: processing inserted download 11
09-13 22:55:47.153  7234  7234 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 22:55:47.153  7234  7234 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-13 22:55:47.154  3389  7750 V DownloadManager: processing inserted download 12
09-13 22:55:47.157  3389  7750 V DownloadManager: processing inserted download 13
09-13 22:55:47.159  3389  7750 V DownloadManager: processing inserted download 14
09-13 22:55:47.162  3389  7750 V DownloadManager: processing inserted download 16
09-13 22:55:47.163  7364  7364 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:55:47
09-13 22:55:47.165  7364  7364 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 22:55:47.165  7364  7364 D Weather.Utils: 2 : All the weather widget is gone.
09-13 22:55:47.165  7364  7364 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,09-13 22:55:47.165  7364  7364 D WeatherAncestor: connectivity changed - connection : true
09-13 22:55:47.165  7364  7364 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3762a369
,09-13 22:55:47.166  7364  7364 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,09-13 22:55:47.166  7364  7364 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,09-13 22:55:47.167  7364  7364 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 22:55:47.167  7364  7364 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 22:55:47.167  7364  7364 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:55:47
09-13 22:55:47.172  3389  3389 V DownloadManager: DownloadService onDestroy
09-13 22:55:47.378  1035  1529 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-13 22:55:47.390  6804  7755 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-13 22:55:47.390  6804  7755 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 22:55:47.390  6804  7755 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 22:55:47.391  6804  7755 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 22:55:47.393  6804  7715 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-13 22:55:47.393  6804  7715 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 22:55:47.393  6804  7755 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 22:55:47.395  6804  7715 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 22:55:47.397  6804  7758 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 978, name: IncomingSocketThread/Sender)
,09-13 22:55:47.399  6804  7715 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 22:55:47.404  6804  7759 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 979, name: IncomingSocketThread/Receiver)
09-13 22:55:47.404  6804  7715 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-13 22:55:47.408  6804  7759 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 979, thread name: IncomingSocketThread/Receiver)
,09-13 22:55:47.408  6804  7759 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 22:55:47.408  6804  7759 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 979, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-13 22:55:47.412  1035  1522 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 22:55:47.414  1035  1522 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 22:55:47.414  6804  7760 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 980, name: OutgoingSocketThread/Sender)
09-13 22:55:47.415  1035  1522 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 22:55:47.417  1035  1522 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 22:55:47.418  1035  1522 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 22:55:47.419  6804  7761 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 981, name: OutgoingSocketThread/Receiver)
09-13 22:55:47.420  6804  7761 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 981, thread name: OutgoingSocketThread/Receiver)
09-13 22:55:47.420  1035  1522 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 22:55:47.420  6804  7761 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 22:55:47.420  6804  7761 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 981, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-13 22:55:47.421  1035  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-13 22:55:47.421  1035  1529 D ConnectivityService: identical MTU - not setting
09-13 22:55:47.422  1035  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 22:55:47.422  1035  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-13 22:55:47.422  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 22:55:47.422  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 22:55:47.424  1035  1529 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 22:55:47.426  1586  2053 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-13 22:55:47.475  1035  1766 I ActivityManager: Killing 7073:com.lge.lifetracker/u0a37 (adj 15): empty #17
,09-13 22:55:47.538  1035  1597 W libprocessgroup: failed to open /acct/uid_10037/pid_7073/cgroup.procs: No such file or directory
,09-13 22:55:47.644  2182  7751 D GCM     : Connected
,09-13 22:55:47.690  2182  7751 D GCM     : Message class com.google.e.a.a.q
,09-13 22:55:47.903  6804  6873 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 990)
09-13 22:55:47.904  6804  6873 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-13 22:55:47.904  6804  6873 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 991)
,09-13 22:55:47.910  6804  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 22:55:47.910  6804  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb8dc6f added. We now have 4 listener(s)
09-13 22:55:47.911  1035  1767 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 22:55:47.914  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 22:55:47.914  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 22:55:47.914  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 22:55:47.914  6804  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 22:55:47.914  6804  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b9dd7c added. We now have 4 listener(s)
09-13 22:55:47.914  6804  6873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 22:55:47.915  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 22:55:47.921  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 22:55:47.928  6804  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 22:55:47.928  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 22:55:47.928  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 22:55:47.928  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 22:55:47.928  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 22:55:47.928  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:47.928  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 22:55:47.928  6804  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 22:55:47.930  6804  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 22:55:47.930  6804  6873 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 22:55:47.932  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:47.934  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:55:47.939  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:55:47.939  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:47.939  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 22:55:47.939  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 22:55:47.940  6804  6873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb8dc6f removed from the list
09-13 22:55:47.940  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:55:47.940  6804  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b9dd7c removed from the list
09-13 22:55:47.940  6804  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:55:47.940  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:47.943  6804  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 22:55:47.943  6804  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 22:55:47.943  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 22:55:47.943  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 22:55:47.943  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 22:55:47.947  6804  6873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 22:55:47.949  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 22:55:47.954  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 22:55:47.956  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 22:55:47.957  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 22:55:47.958  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 22:55:47.961  6804  6873 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 22:55:48.118  7006  7742 V FormManager: There are no updated forms. The schedule will be deleted.
,09-13 22:55:48.127  7006  7742 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-13 22:55:48.202  7006  7772 V FormManager: There are no updated forms. The schedule will be deleted.
,09-13 22:55:48.207  7006  7772 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-13 22:55:48.230  1035  1971 I ActivityManager: Killing 7101:com.lge.settings.easy/1000 (adj 15): empty #17
,09-13 22:55:48.262  1035  1889 W libprocessgroup: failed to open /acct/uid_1000/pid_7101/cgroup.procs: No such file or directory
,09-13 22:55:48.795  1035  1519 D LGWifiP2pService: InactiveState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:48.795  1035  1519 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-13 22:55:48.795  1035  1519 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 22:55:48.847  1035  1522 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-13 22:55:48.855  1035  1522 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-13 22:55:48.856  1035  1522 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 2 0
09-13 22:55:48.857  1035  1522 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 2 0
09-13 22:55:48.858  1035  1522 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 2 0
09-13 22:55:48.861  1035  1522 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-13 22:55:49.276  1035  1522 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=91.5, 0.0, 0.0  rx=90.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:626366747] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-13 22:55:49.290  1035  1522 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=91.5, 0.0, 0.0  rx=90.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:626366750] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 22:55:49.290  1035  1522 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-13 22:55:49.304  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 22:55:49.333  1035  1524 V WifiInternetCheck: Single check msg out of sync, ignoring.
,09-13 22:55:49.364  1035  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 22:55:49.378  1035  1117 D Tethering: MasterInitialState.processMessage what=3
09-13 22:55:49.395  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 22:55:49.402  6804  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 22:55:49.405  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:49.407  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-13 22:55:49.408  6408  6937 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-13 22:55:49.422  5790  5790 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-13 22:55:49.442  2182  2182 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 22:55:49.456  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 22:55:49.456  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:49.456  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 22:55:49.456  7172  7172 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-13 22:55:49.461  7172  7172 I AppUp4:CustModeStarterReceiver: onReceive
09-13 22:55:49.464  7172  7172 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@14363a33
09-13 22:55:49.464  7172  7172 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 22:55:49.464  7172  7172 D AppUp4:CustFacade: isPhone : true
09-13 22:55:49.465  7172  7172 D AppUp4:CustModeStarterReceiver: begin check event
09-13 22:55:49.465  7172  7172 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 22:55:49.470  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:49.470  4747  4747 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 22:55:49.471  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-13 22:55:49.477  4747  4747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 22:55:49.482  3389  3389 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:49.491  3389  3389 V DownloadManager: DownloadService onCreate
,09-13 22:55:49.509  3389  7773 I DownloadManager: in removeSpuriousFiles
09-13 22:55:49.510  3389  7773 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,09-13 22:55:49.522  7201  7776 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 22:55:49.527  3389  7773 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@37210386 on behalf of 3389
09-13 22:55:49.527  3389  7773 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-13 22:55:49.527  3389  7773 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-13 22:55:49.527  3389  7773 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-13 22:55:49.527  3389  7773 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-13 22:55:49.528  3389  7773 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-13 22:55:49.528  3389  7773 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-13 22:55:49.528  3389  7773 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-13 22:55:49.528  3389  7773 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-13 22:55:49.528  3389  7773 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-13 22:55:49.528  3389  7773 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-13 22:55:49.528  3389  7773 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-13 22:55:49.530  4747  7777 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 22:55:49.551  3389  7773 I DownloadManager: in trimDatabase
,09-13 22:55:49.555  3389  7773 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-13 22:55:49.557  3389  7773 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@7c58447 on behalf of 3389
09-13 22:55:49.561  4747  7777 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-13 22:55:49.563  3275  3275 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 22:55:49.563  3275  3275 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:49.564  3275  3275 I LgeMiscReceiver: networkInfo.isConnected() = true
09-13 22:55:49.564  3275  3275 D PhoneState: setPdpRejectCasuse : false
09-13 22:55:49.568  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 22:55:49.569  4747  7779 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 22:55:49.569  4747  7779 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-13 22:55:49.571  7234  7234 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 22:55:49.571  7234  7234 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 22:55:49.573  3389  3389 V DownloadManager: DownloadService onStartCommand
09-13 22:55:49.573  3389  7774 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-13 22:55:49.575  3389  7774 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@979d212 on behalf of 3389
09-13 22:55:49.581  4747  7777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-13 22:55:49.582  3389  7774 V DownloadManager: processing inserted download 1
09-13 22:55:49.585  7364  7364 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:55:49
,09-13 22:55:49.587  3389  7774 V DownloadManager: processing inserted download 4
09-13 22:55:49.587  7364  7364 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 22:55:49.587  7364  7364 D Weather.Utils: 2 : All the weather widget is gone.
09-13 22:55:49.588  7364  7364 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 22:55:49.588  7364  7364 D WeatherAncestor: connectivity changed - connection : true
09-13 22:55:49.588  7364  7364 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3762a369
09-13 22:55:49.588  3389  7774 V DownloadManager: processing inserted download 7
09-13 22:55:49.589  7364  7364 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 22:55:49.589  7364  7364 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 22:55:49.589  7364  7364 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 22:55:49.589  7364  7364 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 22:55:49.589  7364  7364 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 22:55:49
09-13 22:55:49.590  4747  4747 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-13 22:55:49.590  4747  4747 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-13 22:55:49.591  4747  4747 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-13 22:55:49.593  4747  4747 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-13 22:55:49.598  4747  4747 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
,09-13 22:55:49.601  3389  7774 V DownloadManager: processing inserted download 8
09-13 22:55:49.602  3389  7774 V DownloadManager: processing inserted download 9
09-13 22:55:49.604  3389  7774 V DownloadManager: processing inserted download 10
09-13 22:55:49.605  3389  7774 V DownloadManager: processing inserted download 11
09-13 22:55:49.606  3389  7774 V DownloadManager: processing inserted download 12
09-13 22:55:49.607  3389  7774 V DownloadManager: processing inserted download 13
09-13 22:55:49.608  3389  7774 V DownloadManager: processing inserted download 14
09-13 22:55:49.610  3389  7774 V DownloadManager: processing inserted download 16
,09-13 22:55:49.616  3389  3389 V DownloadManager: DownloadService onDestroy
09-13 22:55:49.619  7006  7781 V FormManager: There are no updated forms. The schedule will be deleted.
09-13 22:55:49.621  7006  7781 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
,09-13 22:55:50.552   315  7808 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-13 22:55:50.561   315  7808 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
09-13 22:55:50.610   315  7808 D libc-netbsd: res_queryN name = www.google.com succeed
,09-13 22:55:50.621   315  7810 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-13 22:55:50.622   315  7810 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-13 22:55:50.622   315  7810 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-13 22:55:50.672  1035  1525 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,09-13 22:55:50.900  1586  1586 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-13 22:55:50.930  1035  1443 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 22:55:50.969  6804  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 22:55:50.969  6804  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 22:55:50.991  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:55:50.991  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:50.991  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:50.991  6804  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb8dc6f not in the list
09-13 22:55:50.991  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:55:50.991  6804  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b9dd7c not in the list
09-13 22:55:50.991  6804  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:55:50.991  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:50.991  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:50.992  6804  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 22:55:50.993  6804  6873 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-13 22:55:50.993  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-13 22:55:51.001  6804  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 22:55:51.001  6804  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 22:55:51.001  6804  6873 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 22:55:51.001  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 22:55:51.027  1035  1035 D administrator: Handling package changes for user 0
,09-13 22:55:51.039  1035  1113 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7812 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-13 22:55:51.040  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-13 22:55:51.080  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 22:55:51.080  6804  6873 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 22:55:51.080  6804  6873 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 22:55:51.081  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 22:55:51.081  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 22:55:51.081  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 22:55:51.081  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 22:55:51.084  6804  6804 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 22:55:51.094  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 22:55:51.094  1586  1586 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,09-13 22:55:51.096  1586  1586 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-13 22:55:51.098  6804  7836 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 22:55:51.100  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 22:55:51.101  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 22:55:51.101  4287  7322 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=109 mFd=107
09-13 22:55:51.101  6804  7836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 22:55:51.103  6804  6873 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 22:55:51.103  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:55:51.103  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 22:55:51.103  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 22:55:51.103  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 22:55:51.103  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:51.103  6804  6873 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 22:55:51.103  6804  7836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 22:55:51.103  6804  7836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 22:55:51.103  6804  7836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 22:55:51.103  6804  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb8dc6f not in the list
09-13 22:55:51.103  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:55:51.103  6804  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b9dd7c not in the list
09-13 22:55:51.103  6804  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:55:51.103  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:51.103  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:51.104  6804  6804 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 22:55:51.104  6804  6804 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 22:55:51.104  6804  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 22:55:51.104  6804  6873 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 22:55:51.104  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 22:55:51.104  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 22:55:51.104  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.wif,i.WifiDirectManager: bind: Binding a new listener
,09-13 22:55:51.113  6804  6873 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 22:55:51.114  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:51.115  6804  6873 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 22:55:51.131  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-13 22:55:51.143  7812  7812 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-13 22:55:51.182  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,09-13 22:55:51.182  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-13 22:55:51.226  1035  1112 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 22:55:51.230  1035  1112 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-13 22:55:51.237  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-13 22:55:51.237  7812  7812 D LgDataFeature: LgDataFeature() Constructor: none
09-13 22:55:51.238  7812  7812 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 22:55:51.238  2491  2491 V GmsNetworkLocationProvi: DISABLE
09-13 22:55:51.266  1035  1112 D LocationProviderProxy: applying state to connected service
,09-13 22:55:51.270  2491  2491 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-13 22:55:51.394  7812  7859 I Babel   : MmsConfig: mnc/mcc: 0/0
09-13 22:55:51.395  7812  7859 I Babel   : MmsConfig.loadMmsSettings
,09-13 22:55:51.407  7812  7859 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,09-13 22:55:51.407  7812  7859 I Babel   : MmsConfig.loadFromDatabase
,09-13 22:55:51.427  7812  7859 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-13 22:55:51.427  7812  7859 I Babel   : MmsConfig.loadFromResources
09-13 22:55:51.430  7812  7859 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-13 22:55:51.430  7812  7859 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,09-13 22:55:51.455  7812  7812 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 22:55:51.481  7812  7857 W AudioCapabilities: Unsupported mime audio/evrc
09-13 22:55:51.486  7812  7857 W AudioCapabilities: Unsupported mime audio/qcelp
09-13 22:55:51.490  7812  7857 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 22:55:51.495  1801  7861 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-13 22:55:51.496  1801  7861 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
09-13 22:55:51.500  7172  7172 I AppUp4:CustModeStarterReceiver: onReceive
09-13 22:55:51.507  1801  5185 I Icing   : updateResources: need to parse e{com.google.android.gms}
,09-13 22:55:51.509  7172  7172 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@14363a33
09-13 22:55:51.509  7172  7172 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 22:55:51.509  7172  7172 D AppUp4:CustFacade: isPhone : true
09-13 22:55:51.509  7172  7172 D AppUp4:CustModeStarterReceiver: begin check event
09-13 22:55:51.509  7172  7172 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-13 22:55:51.514  7812  7857 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-13 22:55:51.515  7812  7857 W AudioCapabilities: Unsupported mime audio/qcelp
09-13 22:55:51.516  7812  7857 W AudioCapabilities: Unsupported mime audio/evrc
,09-13 22:55:51.545  7812  7857 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-13 22:55:51.549  1035  1766 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7864 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-13 22:55:51.551  7812  7857 W VideoCapabilities: Unsupported mime video/divx
09-13 22:55:51.553  1035  1888 I ActivityManager: Killing 5608:com.lge.bnr/1000 (adj 15): empty #17
09-13 22:55:51.555  7812  7857 W VideoCapabilities: Unsupported mime video/divx311
09-13 22:55:51.565  7812  7857 W VideoCapabilities: Unsupported mime video/divx4
,09-13 22:55:51.572  7812  7857 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-13 22:55:51.586  7812  7857 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-13 22:55:51.590  7812  7857 W AudioCapabilities: Unsupported mime audio/eac3
,09-13 22:55:51.591  7812  7857 W AudioCapabilities: Unsupported mime audio/ac3
09-13 22:55:51.592  7812  7857 W AudioCapabilities: Unsupported mime audio/g726
09-13 22:55:51.592  7812  7857 W AudioCapabilities: Unsupported mime audio/wma-voice
09-13 22:55:51.593  7812  7857 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-13 22:55:51.594  7812  7857 W AudioCapabilities: Unsupported mime audio/adpcm
09-13 22:55:51.595  7812  7857 W VideoCapabilities: Unsupported mime video/theora
09-13 22:55:51.596  7812  7857 W VideoCapabilities: Unsupported mime video/mjpg
09-13 22:55:51.629  1035  1560 W libprocessgroup: failed to open /acct/uid_1000/pid_5608/cgroup.procs: No such file or directory
,09-13 22:55:51.661  7864  7864 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 22:55:51.662  7864  7864 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 22:55:51.662  7864  7864 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-13 22:55:51.664  7864  7864 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-13 22:55:51.665  7864  7864 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-13 22:55:51.751  7864  7864 I SystemConfig: BUILD Country: EU
09-13 22:55:51.751  7864  7864 I SystemConfig: BUILD Operator: OPEN
,09-13 22:55:51.799  1035  1050 I ActivityManager: Killing 6940:com.lge.sync/1000 (adj 15): empty #17
,09-13 22:55:51.948  1035  1979 W libprocessgroup: failed to open /acct/uid_1000/pid_6940/cgroup.procs: No such file or directory
,09-13 22:55:51.965  7864  7882 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-13 22:55:51.965  7864  7882 I SystemConfig: existFile = false
09-13 22:55:51.966  7864  7882 I SystemConfig: canReadFile = false
09-13 22:55:51.966  7864  7882 I SystemConfig: systemFeature RCS result false
09-13 22:55:51.966  7864  7882 D SystemConfig: refreshRcsSupport() :false
,09-13 22:55:52.041  1035  1050 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7887 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-13 22:55:52.119  7887  7887 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 22:55:52.120  7887  7887 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 22:55:52.121  7887  7887 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-13 22:55:52.122  7887  7887 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-13 22:55:52.240  7887  7887 I AppConfig: Total System Memory = 2995761152
,09-13 22:55:52.260  7887  7887 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-13 22:55:52.314  1035  1522 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=60.2, 0.0, 0.0  rx=56.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:626369786] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 22:55:52.317  1035  1522 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=60.2, 0.0, 0.0  rx=56.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:626369788] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 22:55:52.317  1035  1522 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-13 22:55:52.343  1035  1924 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7906 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 22:55:52.345  1035  1924 I ActivityManager: Killing 6711:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
09-13 22:55:52.368   359   359 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 492us total 25.547ms
,09-13 22:55:52.376  6986  6986 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-13 22:55:52.377  6986  6986 W System.err: android.os.DeadObjectException
09-13 22:55:52.377  6986  6986 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 22:55:52.377  6986  6986 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 22:55:52.377  6986  6986 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-13 22:55:52.377  6986  6986 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
,09-13 22:55:52.377  6986  6986 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-13 22:55:52.377  6986  6986 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-13 22:55:52.377  6986  6986 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 22:55:52.377  6986  6986 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 22:55:52.377  6986  6986 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 22:55:52.377  6986  6986 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 22:55:52.377  6986  6986 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 22:55:52.377  6986  6986 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 22:55:52.377  6986  6986 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 22:55:52.377  6986  6986 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 22:55:52.378  6986  6986 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-13 22:55:52.378  6986  6986 W System.err: android.os.DeadObjectException
09-13 22:55:52.379  6986  6986 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 22:55:52.379  6986  6986 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 22:55:52.379  6986  6986 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-13 22:55:52.379  6986  6986 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-13 22:55:52.379  6986  6986 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-13 22:55:52.379  6986  6986 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-13 22:55:52.379  6986  6986 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 22:55:52.379  6986  6986 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 22:55:52.379  6986  6986 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 22:55:52.379  6986  6986 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 22:55:52.379  6986  6986 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 22:55:52.379  6986  6986 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 22:55:52.379  6986  6986 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 22:55:52.379  6986  6986 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 22:55:52.380  6986  6986 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-13 22:55:52.380  6986  6986 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,09-13 22:55:52.392   359   359 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 495us total 22.806ms
,09-13 22:55:52.414   359   359 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 447us total 20.881ms
,09-13 22:55:52.559  1035  1889 I art     : Explicit concurrent mark sweep GC freed 145021(6MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.308ms total 164.370ms
,09-13 22:55:52.573  1035  2016 W libprocessgroup: failed to open /acct/uid_1000/pid_6711/cgroup.procs: No such file or directory
09-13 22:55:52.574  1035  2016 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-13 22:55:52.594  6986  6986 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-13 22:55:52.595  6986  6986 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,09-13 22:55:52.660  1035  2034 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7924 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-13 22:55:52.661  6986  6986 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-13 22:55:52.733  7924  7924 D UEI.SmartControl: Quickset Services start...
,09-13 22:55:52.735  7924  7924 I UEI.SmartControl: Manufacture = LGE
,09-13 22:55:52.735  7924  7924 D UEI.SmartControl: Id = LGNevo
09-13 22:55:52.736  7924  7924 D UEI.SmartControl: File observer start...
09-13 22:55:52.737  7924  7924 E UEI.SmartControl: IR Port is disabled: false
09-13 22:55:52.737  7924  7924 D UEI.SmartControl: Starting file observer...
09-13 22:55:52.738  7924  7924 D UEI.SmartControl: Extracting JNI libs...
09-13 22:55:52.738  7924  7924 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-13 22:55:52.791  7906  7906 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-13 22:55:52.842  7924  7924 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-13 22:55:52.843  7924  7924 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-13 22:55:52.843  7924  7924 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-13 22:55:52.879  7906  7906 D LgDataFeature: LgDataFeature() Constructor: none
09-13 22:55:52.879  7906  7906 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 22:55:52.882  7924  7924 I UEI.SmartControl: --- Selecting new region: 6
,09-13 22:55:52.885  7924  7924 I UEI.SmartControl: Model = LG-D855
09-13 22:55:52.887  7924  7924 D UEI.SmartControl: QS Service created
,09-13 22:55:52.905  7924  7924 I UEI.SmartControl: Service initServices...
,09-13 22:55:52.910  7924  7924 D UEI.SmartControl: QS start get config
09-13 22:55:52.934  7906  7906 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-13 22:55:52.957  7906  7906 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-13 22:55:52.959  7906  7906 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-13 22:55:52.959  7924  7924 D UEI.SmartControl: Loading JNI Libs...
09-13 22:55:52.976  7906  7906 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-13 22:55:52.977  7906  7906 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-13 22:55:53.006  1035  1766 I ActivityManager: Killing 6962:com.android.settings/1000 (adj 15): empty #17
,09-13 22:55:53.086  1035  1971 W libprocessgroup: failed to open /acct/uid_1000/pid_6962/cgroup.procs: No such file or directory
,09-13 22:55:53.095  3389  3412 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-13 22:55:53.098  3389  3412 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@129613e0 on behalf of 7906
09-13 22:55:53.109  5013  7961 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-13 22:55:53.141  1035  1597 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7962 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-13 22:55:53.158  7906  7906 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-13 22:55:53.179  7906  7906 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-13 22:55:53.224  7962  7962 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-13 22:55:53.246  7924  7924 I UEI.SmartControl: Supports setup maps: true
,09-13 22:55:53.248  7962  7962 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-13 22:55:53.248  7962  7962 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-13 22:55:53.248  7962  7962 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-13 22:55:53.248  7962  7962 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-13 22:55:53.248  7962  7962 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-13 22:55:53.248  7962  7962 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
09-13 22:55:53.260  7924  7924 D UEI.SmartControl: QS start statue = true Error code = 0
09-13 22:55:53.261  7924  7924 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-13 22:55:53.261  7924  7924 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-13 22:55:53.261  7924  7924 I UEI.SmartControl: ### init IR Blaster...
,09-13 22:55:53.268  7924  7924 D serial_port: Configuring serial port
09-13 22:55:53.269  1035  1998 I ActivityManager: Killing 6986:com.lge.qremote/u0a112 (adj 15): empty #17
09-13 22:55:53.272  7924  7924 E UEI.SmartControl: UEIBLaster setting for 616
09-13 22:55:53.272  7924  7924 I UEI.SmartControl: Setting serial record hearder size = 2
,09-13 22:55:53.273  7924  7924 I UEI.SmartControl: configuring settings for MAXQ616
09-13 22:55:53.273  7924  7924 I UEI.SmartControl: Get version...
,09-13 22:55:53.289  7924  7989 D UEI.SmartControl: serial port data available: 21
,09-13 22:55:53.300  1035  2016 W libprocessgroup: failed to open /acct/uid_10112/pid_6986/cgroup.procs: No such file or directory
09-13 22:55:53.319  7924  7924 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-13 22:55:53.319  7924  7924 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-13 22:55:53.319  7924  7924 I UEI.SmartControl: QS saving settings...
09-13 22:55:53.320  7924  7924 D UEI.SmartControl: IR Blaster version: 25672567
,09-13 22:55:53.336  7924  7989 D UEI.SmartControl: serial port data available: 4
,09-13 22:55:53.374  7924  7992 I UEI.SmartControl: Device manager: loading config....
09-13 22:55:53.375  7924  7992 D UEI.SmartControl: ----------- loading internal config...
09-13 22:55:53.376  7924  7924 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-13 22:55:53.381  7924  7924 E UEI.SmartControl: Services init done
09-13 22:55:53.382  7924  7924 D UEI.SmartControl: QS Service init finished
09-13 22:55:53.384  7924  7924 D UEI.SmartControl: QS Service version name: 2.1.91
09-13 22:55:53.384  7924  7924 D UEI.SmartControl: QS Service version code: 201091
09-13 22:55:53.385  7924  7924 D UEI.SmartControl: Service requested: Control
,09-13 22:55:53.390  7924  7924 D UEI.SmartControl: Request IControl service: devices are loaded...
09-13 22:55:53.391  7924  7992 E UEI.SmartControl: Loading SETTINGS...
09-13 22:55:53.392  7924  7924 D UEI.SmartControl: Service.onUnbind: IControl
09-13 22:55:53.393  7924  7924 D UEI.SmartControl: Service.onDestroy
09-13 22:55:53.393  7924  7924 D UEI.SmartControl: Lock is in USE false
09-13 22:55:53.393  7924  7924 D UEI.SmartControl: unbind internal service
,09-13 22:55:53.397  7924  7924 D serial_port: close(fd = 25)
,09-13 22:55:53.401  7924  7924 I UEI.SmartControl: Serial port is closed.
09-13 22:55:53.401  7924  7924 I UEI.SmartControl: Serial port is closed.
09-13 22:55:53.401  7924  7924 D UEI.SmartControl: Blaster closed
09-13 22:55:53.402  7924  7992 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-13 22:55:53.402  7924  7924 D UEI.SmartControl: Shut down QS...
09-13 22:55:53.402  7924  7924 D UEI.SmartControl: Stopping QS lib
09-13 22:55:53.402  7924  7924 D UEI.SmartControl: QS lib stop result = true
09-13 22:55:53.402  7924  7924 D UEI.SmartControl: Stopped QS lib
09-13 22:55:53.402  7924  7924 D UEI.SmartControl: Stopped file observer...
09-13 22:55:53.403  7924  7924 D UEI.SmartControl: QS shutdown complete
09-13 22:55:53.403  7924  7924 D UEI.SmartControl: QS Service created
09-13 22:55:53.412  7924  7991 I UEI.SmartControl: Notify AllClients services are ready: 11
09-13 22:55:53.412  7924  7991 D UEI.SmartControl: -----service ready thread exits
09-13 22:55:53.413  1035  1971 V SIM_STK : Menu title from STK is T-Mobile
,09-13 22:55:53.425  7924  7924 I UEI.SmartControl: Service initServices...
,09-13 22:55:53.425  7924  7924 D UEI.SmartControl: QS start get config
,09-13 22:55:53.433  5013  7961 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 324 ms] updated apps [took 324 ms] 
09-13 22:55:53.894  7924  7924 I UEI.SmartControl: Supports setup maps: true
09-13 22:55:53.898  7924  7924 D UEI.SmartControl: QS start statue = true Error code = 0
09-13 22:55:53.898  7924  7924 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-13 22:55:53.898  7924  7924 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-13 22:55:53.898  7924  7924 I UEI.SmartControl: ### init IR Blaster...
,09-13 22:55:53.903  7924  7924 D serial_port: Configuring serial port
,09-13 22:55:53.904  7924  7924 E UEI.SmartControl: UEIBLaster setting for 616
09-13 22:55:53.904  7924  7924 I UEI.SmartControl: Setting serial record hearder size = 2
09-13 22:55:53.904  7924  7924 I UEI.SmartControl: configuring settings for MAXQ616
09-13 22:55:53.904  7924  7924 I UEI.SmartControl: Get version...
09-13 22:55:53.920  7924  8001 D UEI.SmartControl: serial port data available: 21
,09-13 22:55:53.946  7924  7924 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-13 22:55:53.946  7924  7924 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-13 22:55:53.946  7924  7924 I UEI.SmartControl: QS saving settings...
09-13 22:55:53.947  7924  7924 D UEI.SmartControl: IR Blaster version: 25672567
,09-13 22:55:53.964  7924  8001 D UEI.SmartControl: serial port data available: 4
,09-13 22:55:53.996  7924  8004 I UEI.SmartControl: Device manager: loading config....
,09-13 22:55:53.998  7924  7924 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-13 22:55:54.007  7924  7924 E UEI.SmartControl: Services init done
09-13 22:55:54.008  7924  7924 D UEI.SmartControl: QS Service init finished
09-13 22:55:54.010  7924  8004 D UEI.SmartControl: ----------- loading internal config...
09-13 22:55:54.011  7924  7924 D UEI.SmartControl: QS Service version name: 2.1.91
09-13 22:55:54.011  7924  7924 D UEI.SmartControl: QS Service version code: 201091
09-13 22:55:54.011  7924  7924 D UEI.SmartControl: Service requested: Control
09-13 22:55:54.017  7924  7924 D UEI.SmartControl: Request IControl service: devices are loaded...
09-13 22:55:54.020  1035  1979 I ActivityManager: Killing 7342:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,09-13 22:55:54.021  7924  8004 E UEI.SmartControl: Loading SETTINGS...
09-13 22:55:54.026  7924  8004 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-13 22:55:54.034  7924  8003 I UEI.SmartControl: Notify AllClients services are ready: 0
09-13 22:55:54.034  7924  8003 D UEI.SmartControl: -----service ready thread exits
,09-13 22:55:54.116  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 22:55:54.116  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 22:55:54.116  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:54.116  6804  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb8dc6f not in the list
,09-13 22:55:54.116  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:55:54.116  6804  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b9dd7c not in the list
09-13 22:55:54.116  6804  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:55:54.116  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:54.116  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:54.118  6804  6873 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 22:55:54.118  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:54.118  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:54.118  6804  6873 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb8dc6f not in the list
09-13 22:55:54.118  6804  6873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 22:55:54.118  6804  6873 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b9dd7c not in the list
09-13 22:55:54.118  6804  6873 D io.jxcore.node.ConnectivityMonitor: stop
09-13 22:55:54.118  6804  6873 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 22:55:54.118  6804  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 22:55:54.120  6804  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-13 22:55:54.121  6804  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 22:55:54.121  6804  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-13 22:55:54.121  6804  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 22:55:54.122  6804  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 22:55:54.122  6804  6873 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 22:55:54.141  6804  8012 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1010, name: My test thread name)
,09-13 22:55:54.150  1035  1766 W libprocessgroup: failed to open /acct/uid_10005/pid_7342/cgroup.procs: No such file or directory,
,09-13 22:55:54.152  7924  7924 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@1c10468f that was originally bound here,
09-13 22:55:54.152  7924  7924 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@1c10468f that was originally bound here
09-13 22:55:54.152  7924  7924 E ActivityThread: 	,at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
09-13 22:55:54.152  7924  7924 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
,09-13 22:55:54.152  7924  7924 E ActivityThread: 	,at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
09-13 22:55:54.152  7924  7924 E ActivityThread: 	,at android.app.ContextImpl.bindService(ContextImpl.java:1822)
09-13 22:55:54.152  7924  7924 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538),
09-13 22:55:54.152  7924  7924 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
09-13 22:55:54.152  7924  7924 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
09-13 22:55:54.152  7924  7924 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
09-13 22:55:54.152  7924  7924 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
09-13 22:55:54.152  7924  7924 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
,09-13 22:55:54.152  7924  7924 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
09-13 22:55:54.152  7924  7924 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 22:55:54.152  7924  7924 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
09-13 22:55:54.152  7924  7924 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 22:55:54.152  7924  7924 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 22:55:54.152  7924  7924 E ActivityThread: 	,at java.lang.reflect.Method.invoke(Method.java:372)
09-13 22:55:54.152  7924  7924 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 22:55:54.152  7924  7924 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 22:55:54.153  7924  7924 D UEI.SmartControl: Internal service binding...
09-13 22:55:54.393  7924  7994 D UEI.SmartControl: Internal timer expired: 2
,09-13 22:55:55.338  1035  1522 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=35.1, 0.0, 0.0  rx=31.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:626372810] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-13 22:55:55.342  1035  1522 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=35.1, 0.0, 0.0  rx=31.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:626372814] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 22:55:55.342  1035  1522 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-13 22:55:56.139  6804  6873 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 1010
09-13 22:55:56.139  6804  6873 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 1010, name: My test thread name)
,09-13 22:55:56.155  6804  8019 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1011, name: My test thread name)
09-13 22:55:56.155  6804  8019 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1011, thread name: My test thread name)
09-13 22:55:56.155  6804  8019 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1011, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-13 22:55:56.160  6804  6873 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 22:55:56.170  6804  8020 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1015, name: My test thread name)
09-13 22:55:56.170  6804  8020 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 1015, thread name: My test thread name): Test exception.
09-13 22:55:56.170  6804  8020 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1015, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-13 22:55:56.176  6804  6873 I jxcore-log: Total number of executed tests:  82
09-13 22:55:56.176  6804  6873 I jxcore-log: 
09-13 22:55:56.176  6804  6873 I jxcore-log: Number of passed tests:  82
09-13 22:55:56.176  6804  6873 I jxcore-log: 
09-13 22:55:56.177  6804  6873 I jxcore-log: Number of failed tests:  0
09-13 22:55:56.177  6804  6873 I jxcore-log: 
09-13 22:55:56.177  6804  6873 I jxcore-log: Number of ignored tests:  0
09-13 22:55:56.177  6804  6873 I jxcore-log: 
09-13 22:55:56.177  6804  6873 I jxcore-log: Total duration:  20219
09-13 22:55:56.177  6804  6873 I jxcore-log: 
09-13 22:55:56.179  6804  8012 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1010, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
09-13 22:55:56.181  6804  6873 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 22:55:56.181  6804  6873 I jxcore-log: 
09-13 22:55:56.182  6804  6873 I jxcore-log: My device name is: LGE-LG-D855
09-13 22:55:56.182  6804  6873 I jxcore-log: 
09-13 22:55:56.192  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:55:56.192  6804  6873 I jxcore-log: 
09-13 22:55:56.194  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:55:56.194  6804  6873 I jxcore-log: 
09-13 22:55:56.195  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:55:56.195  6804  6873 I jxcore-log: 
09-13 22:55:56.196  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:55:56.196  6804  6873 I jxcore-log: 
09-13 22:55:56.197  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:55:56.197  6804  6873 I jxcore-log: 
,09-13 22:55:56.211  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:55:56.211  6804  6873 I jxcore-log: 
09-13 22:55:56.213  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 22:55:56.213  6804  6873 I jxcore-log: 
09-13 22:55:56.214  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 22:55:56.214  6804  6873 I jxcore-log: 
09-13 22:55:56.215  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 22:55:56.215  6804  6873 I jxcore-log: 
09-13 22:55:56.216  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 22:55:56.216  6804  6873 I jxcore-log: 
09-13 22:55:56.217  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 22:55:56.217  6804  6873 I jxcore-log: 
09-13 22:55:56.218  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 22:55:56.218  6804  6873 I jxcore-log: 
,09-13 22:55:56.233  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 22:55:56.233  6804  6873 I jxcore-log: 
09-13 22:55:56.234  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 22:55:56.234  6804  6873 I jxcore-log: 
09-13 22:55:56.235  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 22:55:56.235  6804  6873 I jxcore-log: 
09-13 22:55:56.236  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 22:55:56.236  6804  6873 I jxcore-log: 
09-13 22:55:56.237  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:55:56.237  6804  6873 I jxcore-log: 
09-13 22:55:56.237  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:55:56.237  6804  6873 I jxcore-log: 
09-13 22:55:56.238  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:55:56.238  6804  6873 I jxcore-log: 
,09-13 22:55:56.242  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:55:56.242  6804  6873 I jxcore-log: 
09-13 22:55:56.243  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:55:56.243  6804  6873 I jxcore-log: 
09-13 22:55:56.244  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:55:56.244  6804  6873 I jxcore-log: 
09-13 22:55:56.245  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:55:56.245  6804  6873 I jxcore-log: 
09-13 22:55:56.246  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:55:56.246  6804  6873 I jxcore-log: 
09-13 22:55:56.246  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:55:56.246  6804  6873 I jxcore-log: 
09-13 22:55:56.247  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:55:56.247  6804  6873 I jxcore-log: 
09-13 22:55:56.248  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:55:56.248  6804  6873 I jxcore-log: 
09-13 22:55:56.250  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:55:56.250  6804  6873 I jxcore-log: 
09-13 22:55:56.251  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 22:55:56.251  6804  6873 I jxcore-log: 
09-13 22:55:56.251  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 22:55:56.251  6804  6873 I jxcore-log: 
09-13 22:55:56.252  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 22:55:56.252  6804  6873 I jxcore-log: 
09-13 22:55:56.253  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 22:55:56.253  6804  6873 I jxcore-log: 
09-13 22:55:56.254  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 22:55:56.254  6804  6873 I jxcore-log: 
09-13 22:55:56.255  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 22:55:56.255  6804  6873 I jxcore-log: 
09-13 22:55:56.255  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:55:56.255  6804  6873 I jxcore-log: 
09-13 22:55:56.256  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on",,"cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:55:56.256  6804  6873 I jxcore-log: 
09-13 22:55:56.257  6804  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 22:55:56.257  6804  6873 I jxcore-log: 
09-13 22:55:56.501  8021  8021 D AndroidRuntime: 
09-13 22:55:56.501  8021  8021 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-13 22:55:56.504  8021  8021 D AndroidRuntime: CheckJNI is OFF
,09-13 22:55:56.678  8021  8021 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-13 22:55:56.687  1035  1113 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-13 22:55:56.687  1035  1113 I ActivityManager: Killing 6804:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
09-13 22:55:56.738  1035  1971 I WindowState: WIN DEATH: Window{2e94b7da u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 22:55:56.739  1035  1528 D WifiService: Client connection lost with reason: 4
09-13 22:55:56.746  1035  1971 D InputDispatcher: Window went away: Window{2e94b7da u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 22:55:56.925  1035  1113 I ActivityManager:   Force finishing activity ActivityRecord{3987a807 u0 com.test.thalitest/.MainActivity t6}
,09-13 22:55:56.959   338   351 E GBMv2   : DFP En is all cleared set to be enabled
09-13 22:55:56.968  1035  1979 W ActivityManager: Spurious death for ProcessRecord{9e06f9 6804:com.test.thalitest/u0a118}, curProc for 6804: null
,09-13 22:55:56.977  1035  1123 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,09-13 22:55:56.982  1035  1123 I ActivityManager:   Force finishing activity ActivityRecord{3987a807 u0 com.test.thalitest/.MainActivity t6 f}
09-13 22:55:56.982  1035  1123 W ActivityManager: Duplicate finish request for ActivityRecord{3987a807 u0 com.test.thalitest/.MainActivity t6 f}
,09-13 22:55:57.018  2017  2017 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,09-13 22:55:57.021  1926  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-13 22:55:57.022  1926  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1b19bf1f co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-13 22:55:57.023  2017  2017 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-13 22:55:57.024  1926  2521 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-13 22:55:57.024  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-13 22:55:57.024  1926  2521 D SplitWindowPolicy: topRunningActivity=ActivityInfo{132c026c co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-13 22:55:57.025  2017  2129 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-13 22:55:57.030  1586  1586 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,09-13 22:55:57.042  1980  1980 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-13 22:55:57.043  2491  2596 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-13 22:55:57.045  3784  3784 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-13 22:55:57.052  4287  4287 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-13 22:55:57.052  5013  5013 I art     : Explicit concurrent mark sweep GC freed 8208(470KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 596us total 57.998ms
09-13 22:55:57.052  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-13 22:55:57.055  4913  4913 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-13 22:55:57.055  4913  4913 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-13 22:55:57.055  4913  4913 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-13 22:55:57.055  4913  4913 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-13 22:55:57.055  4913  4913 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 22:55:57.055  4913  4913 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 22:55:57.055  4913  4913 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 22:55:57.055  4913  4913 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 22:55:57.055  4913  4913 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 22:55:57.055  4913  4913 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 22:55:57.055  4913  4913 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 22:55:57.055  4913  4913 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 22:55:57.071  1035  1443 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 22:55:57.141  1035  1035 D administrator: Handling package changes for user 0
,09-13 22:55:57.144  6408  6408 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-13 22:55:57.153  1035  1943 V SIM_STK : Menu title from STK is T-Mobile
,09-13 22:55:57.161  1890  1890 D ActionManagerService: notifyUserLog: 1000003
09-13 22:55:57.161  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-13 22:55:57.162  3784  4903 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-13 22:55:57.167  2017  2017 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-13 22:55:57.168  1586  1586 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-13 22:55:57.168  2017  2017 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,09-13 22:55:57.169  1801  1801 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-13 22:55:57.182  1586  1586 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-13 22:55:57.182  1586  1586 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,09-13 22:55:57.188  2017  2017 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,09-13 22:55:57.214  1854  1854 D SplitUIManager: split_name #11 / not available #0
09-13 22:55:57.214  1035  1112 W InputMethodInfo: Duplicated subtype definition found: , voice
09-13 22:55:57.214  1854  1854 D SplitUIService: removed split : 
,09-13 22:55:57.221  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-13 22:55:57.222  1890  1890 D ActionManagerService: notifyUserLog: 1000004
09-13 22:55:57.223  1586  1647 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-13 22:55:57.223  1586  1647 D KeyguardModel: createShortcutInfo...
09-13 22:55:57.223  2182  2182 I ConfigService: onCreate
09-13 22:55:57.224  3784  4903 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-13 22:55:57.224  3784  3800 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 22:55:57.225  2182  2182 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-13 22:55:57.227  1801  1801 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-13 22:55:57.239  1035  1888 V SIM_STK : Menu title from STK is T-Mobile
09-13 22:55:57.239  1035  1888 V SIM_STK : Menu title from STK is T-Mobile
,09-13 22:55:57.246  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-13 22:55:57.246  2017  2017 I GBoardWebViewUtils: , create_time: 1430832262123
09-13 22:55:57.246  2017  2017 I GBoardWebViewUtils: , expire_time: 0
09-13 22:55:57.246  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-13 22:55:57.246  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-13 22:55:57.246  2017  2017 I GBoardWebViewUtils: , display: false
09-13 22:55:57.246  2017  2017 I GBoardWebViewUtils: , animation: false }
09-13 22:55:57.246  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-13 22:55:57.246  2017  2017 I GBoardWebViewUtils: , create_time: 1430832262287
09-13 22:55:57.246  2017  2017 I GBoardWebViewUtils: , expire_time: 0
09-13 22:55:57.246  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-13 22:55:57.246  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-13 22:55:57.246  2017  2017 I GBoardWebViewUtils: , display: false
09-13 22:55:57.246  2017  2017 I GBoardWebViewUtils: , animation: false }
09-13 22:55:57.246  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1473420112499
09-13 22:55:57.246  2017  2017 I GBoardWebViewUtils: , create_time: 1473420113195
09-13 22:55:57.246  2017  2017 I GBoardWebViewUtils: , expire_time: 0
09-13 22:55:57.246  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-13 22:55:57.246  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-13 22:55:57.246  2017  2017 I GBoardWebViewUtils: , display: false
09-13 22:55:57.246  2017  2017 I GBoardWebViewUtils: , animation: false }
09-13 22:55:57.247  1586  1647 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-13 22:55:57.247  1586  1647 D KeyguardModel: createShortcutInfo...
09-13 22:55:57.261  2182  2182 I ConfigService: onBind returning update interface
09-13 22:55:57.262  2182  2182 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-13 22:55:57.262  2182  2182 I ConfigService: onBind returning config service
09-13 22:55:57.265  1586  1647 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-13 22:55:57.266  1586  1647 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 22:55:57.266  1586  1647 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-13 22:55:57.267  1586  1647 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-13 22:55:57.268  1586  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 22:55:57.268  1586  1647 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,09-13 22:55:57.279  2017  8079 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-13 22:55:57.286  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-13 22:55:57.287  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-13 22:55:57.291  1586  1647 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-13 22:55:57.291  1586  1647 D KeyguardModel: createShortcutInfo...
09-13 22:55:57.295  1586  1647 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-13 22:55:57.295  1586  1647 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 22:55:57.297  1035  1971 V SIM_STK : Menu title from STK is T-Mobile
09-13 22:55:57.299  1586  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 22:55:57.299  1586  1647 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-13 22:55:57.303  1586  1647 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-13 22:55:57.303  1586  1647 D KeyguardModel: createShortcutInfo...
09-13 22:55:57.303  2182  2182 I ConfigService: onDestroy
09-13 22:55:57.308  1586  1647 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 22:55:57.308  1586  1647 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 22:55:57.308  1586  1647 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-13 22:55:57.308  1586  1647 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-13 22:55:57.308  1035  1051 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-13 22:55:57.309  1586  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 22:55:57.309  1586  1647 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,09-13 22:55:57.310  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-13 22:55:57.310  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-13 22:55:57.310  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-13 22:55:57.310  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-13 22:55:57.310  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-13 22:55:57.310  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 22:55:57.310  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-13 22:55:57.310  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-13 22:55:57.310  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-13 22:55:57.310  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 22:55:57.310  4287  4287 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-13 22:55:57.311  1586  1647 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-13 22:55:57.311  1586  1647 D KeyguardModel: createShortcutInfo...
09-13 22:55:57.312  1801  8081 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-13 22:55:57.315  1586  1586 D KeyguardModel: handleShortcutListChanged...
09-13 22:55:57.315  1586  1586 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-13 22:55:57.316  1854  1854 D SplitUIManager: split_name #11 / not available #0
09-13 22:55:57.316  1854  1854 I SplitUIService: split app #11
09-13 22:55:57.320  1586  1647 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-13 22:55:57.320  1586  1647 D KeyguardModel: createShortcutInfo...
09-13 22:55:57.322  1586  1647 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-13 22:55:57.322  1586  1647 D KeyguardModel: createShortcutInfo...
09-13 22:55:57.323  1586  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 22:55:57.323  1586  1647 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-13 22:55:57.324  1586  1647 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-13 22:55:57.324  1586  1647 D KeyguardModel: createShortcutInfo...
09-13 22:55:57.327  1586  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 22:55:57.327  1586  1647 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-13 22:55:57.328  1586  1647 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-13 22:55:57.328  1586  1647 D KeyguardModel: createShortcutInfo...
09-13 22:55:57.329  1586  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 22:55:57.330  1586  1647 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,09-13 22:55:57.331  1586  1647 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-13 22:55:57.331  1586  1647 D KeyguardModel: createShortcutInfo...
09-13 22:55:57.352  2017  2017 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,09-13 22:55:57.365  5831  8086 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
09-13 22:55:57.365  2182  2209 I art     : Explicit concurrent mark sweep GC freed 8823(546KB) AllocSpace objects, 4(64KB) LOS objects, 52% free, 29MB/61MB, paused 792us total 31.391ms
09-13 22:55:57.366  1586  1586 D KeyguardModel: handleShortcutListChanged...
09-13 22:55:57.366  1586  1586 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-13 22:55:57.368  1801  8088 I PeopleContactsSync: CP2 sync disabled
,09-13 22:55:57.375  1801  5185 I Icing   : doRemovePackageData com.test.thalitest
09-13 22:55:57.380  1801  8087 W GmsApplication: Using Auth Proxy for data requests.
09-13 22:55:57.385  1801  8087 W GmsApplication: Using Auth Proxy for data requests.
,09-13 22:55:57.409  7172  7172 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,09-13 22:55:57.419  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-13 22:55:57.419  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-13 22:55:57.419  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-13 22:55:57.421  1035  1562 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-13 22:55:57.425  7201  7201 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
09-13 22:55:57.426  2349  8092 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-13 22:55:57.433  1980  1980 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-13 22:55:57.433  1980  1980 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
09-13 22:55:57.434  1980  1980 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
09-13 22:55:57.437  6408  6408 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,09-13 22:55:57.452   329   423 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-13 22:55:57.453  3233  8094 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,09-13 22:55:57.472  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,09-13 22:55:57.474  1035  1767 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=8095 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-13 22:55:57.477  1035  1123 I art     : Explicit concurrent mark sweep GC freed 32293(2036KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.879ms total 282.516ms
09-13 22:55:57.478  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 22:55:57.480  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-13 22:55:57.481  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-13 22:55:57.482  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-13 22:55:57.484  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-13 22:55:57.496  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2e81b421 u0 com.lge.launcher2/.Launcher t5} time:213767
,09-13 22:55:57.504  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-13 22:55:57.504  2017  2265 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-13 22:55:57.504  2017  2265 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-13 22:55:57.504  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-13 22:55:57.519  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-13 22:55:57.520  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-13 22:55:57.520  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-13 22:55:57.528  2017  2017 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-13 22:55:57.529  2660  2660 D [Concierge]Service: onStartCommand(). Type : 8
09-13 22:55:57.529  2660  2660 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-13 22:55:57.530  2660  2660 D [Concierge]Service: Update widget ID : 11
09-13 22:55:57.534  2017  2017 D [Concierge]WidgetView: change position of spinner
09-13 22:55:57.535  2017  2017 I [Concierge]WidgetView: initWebView(). Time : 1473800157535
09-13 22:55:57.536  2660  2660 D [Concierge]Service: onStartCommand(). Type : 0
09-13 22:55:57.557  2017  2017 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 156199418
09-13 22:55:57.558  2017  2017 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-13 22:55:57.558  2017  2017 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-13 22:55:57.561  2017  2017 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@dcd7696
09-13 22:55:57.561  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-13 22:55:57.563  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,09-13 22:55:57.563  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 22:55:57.568  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-13 22:55:57.568  2017  2017 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-13 22:55:57.569  2017  2017 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-13 22:55:57.569  2017  2017 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473799972003, New one : 1473800157535
09-13 22:55:57.569  2017  2017 D [Concierge]WidgetView: Unregister all receivers
09-13 22:55:57.569  2017  2017 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-13 22:55:57.570  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 22:55:57.571  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-13 22:55:57.572  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-13 22:55:57.573  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-13 22:55:57.574  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-13 22:55:57.575  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,09-13 22:55:57.576  8095  8095 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-13 22:55:57.576  8095  8095 W LG Account v2.2: No ProfileInfo entries
09-13 22:55:57.576  8095  8095 I LG Account v2.2: isEnabled: false
09-13 22:55:57.576  8095  8095 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-13 22:55:57.577  8095  8095 I Feature : [Lifetracker]Country: EU
09-13 22:55:57.577  8095  8095 I Feature : [Lifetracker]Operator: OPEN
09-13 22:55:57.577  8095  8095 I Feature : [Lifetracker]Ranking support: false
09-13 22:55:57.577  8095  8095 I Feature : [Lifetracker]Comfort support: false
09-13 22:55:57.577  8095  8095 I Feature : [Lifetracker]Accessory: true
09-13 22:55:57.577  8095  8095 I Feature : [Lifetracker]Health device: true
09-13 22:55:57.577  8095  8095 I Feature : [Lifetracker]Extra Pedometer: false
09-13 22:55:57.577  8095  8095 I Feature : [Lifetracker]Blood glucose device: false
09-13 22:55:57.577  8095  8095 I Feature : [Lifetracker]Device Number: 3
09-13 22:55:57.577  8095  8095 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
09-13 22:55:57.579  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 22:55:57.579  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 22:55:57.582  8021  8021 D AndroidRuntime: Shutting down VM
09-13 22:55:57.613  1035  1597 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8117 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-13 22:55:57.613  1035  1597 I ActivityManager: Killing 7006:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-13 22:55:57.629  2017  2017 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-13 22:55:57.637  2017  2017 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-13 22:55:57.637  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-13 22:55:57.639  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-13 22:55:57.651  1035  1112 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 22:55:57.655  1035  1112 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,09-13 22:55:57.658  2017  2017 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@32cc1de3 time:213929
09-13 22:55:57.700  1035  1767 W libprocessgroup: failed to open /acct/uid_10026/pid_7006/cgroup.procs: No such file or directory
,09-13 22:55:57.709  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-13 22:55:57.715  7924  7935 E UEI.SmartControl: file observer is disposed!
,09-13 22:55:57.721  8117  8117 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 22:55:57.721  8117  8117 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-13 22:55:57.721  8117  8117 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 22:55:57.721  8117  8117 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-13 22:55:57.722  8117  8117 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 22:55:57.723  8117  8117 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-13 22:55:57.793  2017  2017 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
09-13 22:55:57.794  8117  8117 D PackageIntentReceiver: Not supported Hotkey customization function 
,09-13 22:55:57.800  8117  8117 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
09-13 22:55:57.800  8117  8117 D HideNavigationAppsReceiver: replacing : false
09-13 22:55:57.815  1035  1123 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8134 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-13 22:55:57.818  8117  8117 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
09-13 22:55:57.819  8117  8117 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
09-13 22:55:57.819  8117  8117 D ButtonCombinationReceiver: replacing : false
09-13 22:55:57.827  1035  1924 I ActivityManager: Killing 7234:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-13 22:55:57.843  2017  2914 I GBoardtInterface: onReloaded()
,09-13 22:55:57.846  2017  2017 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
,09-13 22:55:57.907  1035  1766 W libprocessgroup: failed to open /acct/uid_10046/pid_7234/cgroup.procs: No such file or directory
09-13 22:55:57.910  3784  3800 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 22:55:57.912  3784  3799 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 22:55:57.912  5013  8155 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-13 22:55:57.943  1035  1998 V SIM_STK : Menu title from STK is T-Mobile
,09-13 22:55:57.951  1035  1943 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8158 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 22:55:57.953  1035  1925 I ActivityManager: Killing 7280:com.android.chrome/u0a57 (adj 15): empty #17
09-13 22:55:57.954  5013  8155 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,--------- beginning of crash
09-13 22:55:57.958  5013  8155 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
09-13 22:55:57.958  5013  8155 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 5013
09-13 22:55:57.958  5013  8155 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 22:55:57.958  5013  8155 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-13 22:55:57.958  5013  8155 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
09-13 22:55:57.958  5013  8155 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-13 22:55:57.958  5013  8155 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-13 22:55:57.958  5013  8155 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-13 22:55:57.958  5013  8155 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
09-13 22:55:57.958  5013  8155 E AndroidRuntime: 	at csx.d(PG:186)
09-13 22:55:57.958  5013  8155 E AndroidRuntime: 	at cun.g(PG:594)
09-13 22:55:57.958  5013  8155 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
09-13 22:55:57.958  5013  8155 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
09-13 22:55:57.958  5013  8155 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1349)
09-13 22:55:57.958  5013  8155 E AndroidRuntime: 	at cuw.Tg(PG:368)
09-13 22:55:57.958  5013  8155 E AndroidRuntime: 	at cuy.ub(PG:301)
09-13 22:55:57.958  5013  8155 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
09-13 22:55:57.958  5013  8155 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
09-13 22:55:57.958  5013  8155 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-13 22:55:57.958  5013  8155 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 22:55:57.958  5013  8155 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
09-13 22:55:57.958  5013  8155 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 22:55:57.990  1035  1888 W libprocessgroup: failed to open /acct/uid_10057/pid_7280/cgroup.procs: No such file or directory
09-13 22:55:58.001  1890  1890 D ActionManagerService: notifyUserLog: 1000001
,09-13 22:55:58.003  5013  8155 I Process : Sending signal. PID: 5013 SIG: 9
09-13 22:55:58.004  3784  4903 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-13 22:55:58.004  3784  4903 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED

```
