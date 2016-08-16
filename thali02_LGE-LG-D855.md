#### Test 80761374ecfdb04_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-16 16:40:00.049  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
08-16 16:40:00.058  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
08-16 16:40:00.059  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
08-16 16:40:00.061  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
08-16 16:40:00.063  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
,08-16 16:40:44.323  7030  7030 D AndroidRuntime: 
08-16 16:40:44.323  7030  7030 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 16:40:44.328  7030  7030 D AndroidRuntime: CheckJNI is OFF
08-16 16:40:44.454  7030  7030 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 16:40:44.458  1035  1913 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 16:40:44.469  1959  1976 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-16 16:40:44.472  1035  1913 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-16 16:40:44.473  1035  1913 D ActivityManager: setTaskToReturnTo : TaskRecord{170417e4 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 16:40:44.473  1035  1913 D ActivityManager: setTaskToReturnTo : TaskRecord{170417e4 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 16:40:44.474  1035  1913 D WindowStateEx: AppWindowTokenEx init.. 
08-16 16:40:44.475   350   360 E GBMv2   : DFP En is all cleared set to be enabled
08-16 16:40:44.509  1035  1913 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7049 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-16 16:40:44.511  7030  7030 D AndroidRuntime: Shutting down VM
08-16 16:40:44.573  1959  2343 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-16 16:40:44.574  1959  2343 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3092a670 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 16:40:44.575  1959  1977 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-16 16:40:44.579  1959  1977 D SplitWindowPolicy: topRunningActivity=ActivityInfo{7c72de9 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
,08-16 16:40:44.629  7049  7049 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-16 16:40:44.739  7049  7049 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 16:40:44.747  7049  7049 I LibraryLoader: Loading: webviewchromium
,08-16 16:40:44.751  7049  7049 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 6791-6795)
08-16 16:40:44.751  7049  7049 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 16:40:44.777  7049  7049 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3a103220}
08-16 16:40:44.778  7049  7049 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 16:40:44.779  7049  7049 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 16:40:44.787  7049  7049 I BrowserStartupController: Initializing chromium process, renderers=0
08-16 16:40:44.789  7049  7049 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 16:40:44.803  7049  7049 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-16 16:40:44.804  7049  7049 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,08-16 16:40:44.805  7049  7049 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-16 16:40:44.810   326  4290 V AudioPolicyService: registerClient() client 0xb557c140, uid 10118
08-16 16:40:44.817  1035  1117 D BluetoothManagerService: Message: 20
08-16 16:40:44.817  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3d28d54e:true
,08-16 16:40:44.827  7049  7049 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 16:40:44.827  7049  7049 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 16:40:44.827  7049  7049 I Adreno-EGL: Build Date: 12/12/14 금
08-16 16:40:44.827  7049  7049 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 16:40:44.827  7049  7049 I Adreno-EGL: Remote Branch: 
08-16 16:40:44.827  7049  7049 I Adreno-EGL: Local Patches: 
08-16 16:40:44.827  7049  7049 I Adreno-EGL: Reconstruct Branch: 
08-16 16:40:44.920  7049  7092 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-16 16:40:44.926  7049  7049 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-16 16:40:44.942  7049  7049 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 16:40:44.947  7049  7049 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-16 16:40:44.950  7049  7049 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-16 16:40:44.953  7049  7049 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-16 16:40:44.953  7049  7049 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-16 16:40:44.965  7049  7049 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-16 16:40:44.972  7049  7049 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 16:40:44.972  7049  7049 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 16:40:45.002  7049  7107 D OpenGLRenderer: Render dirty regions requested: true
08-16 16:40:45.003  7049  7107 I OpenGLRenderer: Initialized EGL, version 1.4
08-16 16:40:45.008  7049  7107 D OpenGLRenderer: Enabling debug mode 0
08-16 16:40:45.020  7049  7049 D Atlas   : Validating map...
,08-16 16:40:45.024  1035  1982 D SplitWindow: check instance of lgWin Window{2b782a98 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 16:40:45.086  7049  7105 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 16:40:45.086  7049  7105 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 16:40:45.193  1035  1118 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +620ms (total +716ms)
08-16 16:40:45.193  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2a5dd44d u0 com.test.thalitest/.MainActivity t6} time:317238
,08-16 16:40:45.198  7049  7049 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@6bd1f6f time:317243
08-16 16:40:45.306  7049  7049 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-16 16:40:45.306  7049  7049 I chromium: 
,08-16 16:40:45.322  7049  7049 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 16:40:45.385  7049  7105 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-16 16:40:45.385  7049  7105 I chromium: 
,08-16 16:40:45.511  7049  7121 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435032064
,08-16 16:40:45.526  7049  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 16:40:45.526  7049  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 16:40:45.526  7049  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 16:40:45.526  7049  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 16:40:45.526  7049  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-16 16:40:45.526  7049  7121 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24e19903 added. We now have 1 listener(s)
,08-16 16:40:45.531  1035  2077 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 16:40:45.534  7049  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-16 16:40:45.538  7049  7121 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 16:40:45.541  7049  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 16:40:45.542  7049  7121 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 16:40:45.556  7049  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 16:40:45.556  7049  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 16:40:45.556  7049  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 16:40:45.556  7049  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-16 16:40:45.556  7049  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 16:40:45.556  7049  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 16:40:45.556  7049  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 16:40:45.556  7049  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 16:40:45.556  7049  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 16:40:45.556  7049  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 16:40:45.556  7049  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 16:40:45.556  7049  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 16:40:45.556  7049  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 16:40:45.556  7049  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-16 16:40:45.556  7049  7121 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d5a8afe added. We now have 1 listener(s)
08-16 16:40:45.556  7049  7121 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 16:40:45.561  1035  1530 D WifiService: New client listening to asynchronous messages
08-16 16:40:45.564  7049  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 16:40:45.564  7049  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-16 16:40:45.566  7049  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 16:40:45.566  7049  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 16:40:45.566  7049  7121 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-16 16:40:45.569  7049  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 16:40:45.570  1035  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 16:40:45.572  7049  7121 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-16 16:40:45.581  7049  7121 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 16:40:45.581  7049  7121 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 16:40:45.581  7049  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:40:45.581  7049  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:40:45.581  7049  7121 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:40:45.581  7049  7121 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:40:45.581  7049  7121 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:40:45.581  7049  7121 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:40:45.581  7049  7121 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 16:40:45.581  7049  7121 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 16:40:45.581  7049  7121 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 16:40:45.582  7049  7121 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 16:40:45.583  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:40:45.585  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:40:45.620  7049  7049 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 16:40:45.745   350   362 E GBMv2   : DFP En is all cleared set to be enabled
08-16 16:40:45.746   350   362 E GBMv2   : Set value is all cleared set the max
08-16 16:40:45.746   350   362 I GBMv2   : DFP Enabled. Ignore VFP set
,08-16 16:40:46.299  7049  7124 W jxcore-log: Initializing JXcore engine
,08-16 16:40:46.299  7049  7124 W jxcore-log: JXcore engine is ready
08-16 16:40:46.325  7124  7124 W Thread-832: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[10737]" dev="sockfs" ino=10737 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-16 16:40:46.325  7124  7124 W Thread-832: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-16 16:40:46.325  7124  7124 W Thread-832: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9575]" dev="sockfs" ino=9575 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-16 16:40:46.325  7124  7124 W Thread-832: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-16 16:40:46.325  7124  7124 W Thread-832: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[33556]" dev="sockfs" ino=33556 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-16 16:40:46.354  7049  7124 W jxcore-log: Starting JXcore engine
,08-16 16:40:46.434  7049  7124 W jxcore-log: Platform android
08-16 16:40:46.434  7049  7124 W jxcore-log: 
08-16 16:40:46.434  7049  7124 W jxcore-log: Process ARCH arm
08-16 16:40:46.434  7049  7124 W jxcore-log: 
,08-16 16:40:46.663  7049  7124 I jxcore-log: JXcore Cordova bridge is ready!
08-16 16:40:46.663  7049  7124 I jxcore-log: 
08-16 16:40:46.664  7049  7124 W jxcore-log: JXcore engine is started
,08-16 16:40:46.677  7049  7121 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 16:40:46.680  7049  7049 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 16:41:00.055  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-16 16:41:00.055  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
08-16 16:41:00.055  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-16 16:41:00.056  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,08-16 16:41:00.058  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
08-16 16:41:00.058  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
08-16 16:41:00.059  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
08-16 16:41:00.059  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
08-16 16:41:02.566  1035  3463 I LocationManagerService: remove 101c5511
08-16 16:41:02.567  1035  3463 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-16 16:41:02.567  1035  3463 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-16 16:41:02.568  1035  3463 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-16 16:41:02.569  1035  3463 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,08-16 16:41:02.570  1035  3463 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
08-16 16:41:02.576  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 16:41:02.576  7049  7124 I jxcore-log: 
08-16 16:41:02.579  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 16:41:02.579  7049  7124 I jxcore-log: 
08-16 16:41:02.583  7049  7124 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 16:41:02.583  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:02.583  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:02.583  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:41:02.583  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:41:02.583  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:41:02.583  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:41:02.583  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 16:41:02.586  7049  7124 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 16:41:02.588  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 16:41:02.588  7049  7124 I jxcore-log: 
08-16 16:41:02.590  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 16:41:02.590  7049  7124 I jxcore-log: 
,08-16 16:41:02.923  7049  7124 I jxcore-log: Running unit tests
08-16 16:41:02.923  7049  7124 I jxcore-log: 
,08-16 16:41:02.925  7049  7124 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 16:41:02.925  7049  7124 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a2c1c5 added. We now have 2 listener(s)
08-16 16:41:02.926  1035  2053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 16:41:02.928  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 16:41:02.928  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 16:41:02.928  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 16:41:02.928  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 16:41:02.929  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14b4b71a added. We now have 2 listener(s)
08-16 16:41:02.929  7049  7124 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 16:41:02.929  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 16:41:02.934  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 16:41:02.939  7049  7124 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 16:41:02.939  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:02.939  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:02.939  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:41:02.939  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:41:02.939  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:41:02.939  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:41:02.939  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 16:41:02.943  7049  7124 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 16:41:02.944  7049  7124 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 16:41:02.945  7049  7124 D ExecuteNativeTests: Running unit tests
08-16 16:41:02.948  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:02.950  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:03.031  7049  7124 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 16:41:03.031  7049  7124 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32b99758 added. We now have 3 listener(s)
08-16 16:41:03.031  1035  2077 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 16:41:03.033  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 16:41:03.033  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 16:41:03.034  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 16:41:03.034  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 16:41:03.034  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 added. We now have 3 listener(s)
08-16 16:41:03.034  7049  7124 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 16:41:03.034  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 16:41:03.037  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 16:41:03.040  7049  7124 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 16:41:03.040  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:03.040  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:03.040  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:41:03.040  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:41:03.040  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:41:03.040  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:41:03.040  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 16:41:03.041  7049  7124 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 16:41:03.041  7049  7124 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 16:41:03.043  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:03.045  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:03.046  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 16:41:03.048  7049  7124 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 16:41:03.048  7049  7124 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 16:41:03.048  7049  7124 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 16:41:03.052  7049  7124 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-16 16:41:03.052  7049  7124 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 16:41:03.052  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 16:41:03.053  7049  7124 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 16:41:03.053  7049  7124 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 16:41:03.053  7049  7124 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 16:41:03.053  7049  7124 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:41:03.054  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:41:03.054  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:41:03.054  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:41:03.054  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:03.054  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 16:41:03.054  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 16:41:03.054  7049  7124 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32b99758 removed from the list
08-16 16:41:03.054  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:03.054  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 removed from the list
08-16 16:41:03.054  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:41:03.054  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:03.055  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:03.055  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:03.056  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:41:03.056  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 16:41:03.056  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:03.056  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:03.057  7049  7124 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-16 16:41:03.058  7049  7124 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:41:03.058  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:41:03.058  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:41:03.058  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:41:03.058  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:03.058  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:03.058  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32b99758 not in the list
08-16 16:41:03.058  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:03.058  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:03.058  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:41:03.058  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:03.058  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:03.058  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:03.058  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:03.059  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:41:03.059  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:41:03.059  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:03.059  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:03.068  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 16:41:03.068  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 16:41:03.069  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 16:41:03.069  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 16:41:03.069  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 16:41:03.069  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 16:41:03.069  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoing,Connections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 16:41:03.069  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 16:41:03.069  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 16:41:03.069  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 16:41:03.069  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 16:41:03.070  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 16:41:03.070  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 16:41:03.070  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 16:41:03.070  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 16:41:03.070  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 16:41:03.070  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 16:41:03.070  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 16:41:03.070  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 16:41:03.071  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 16:41:03.071  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 16:41:03.071  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 16:41:03.071  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 16:41:03.071  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 16:41:03.071  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 16:41:03.071  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 16:41:03.071  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 16:41:03.072  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 16:41:03.072  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 16:41:03.072  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 16:41:03.072  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 16:41:03.072  7049  7124 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:41:03.072  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop ,everything
08-16 16:41:03.072  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:41:03.072  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:41:03.073  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:03.073  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:03.073  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32b99758 not in the list
08-16 16:41:03.073  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:03.073  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:03.073  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:41:03.073  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:03.073  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:03.073  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:03.073  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:03.075  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:41:03.075  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:41:03.075  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:03.075  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:03.077  7049  7124 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 16:41:03.080  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 16:41:03.084  7049  7124 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 16:41:03.084  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:03.084  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:03.084  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:41:03.084  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:41:03.084  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:41:03.084  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:41:03.084  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 16:41:03.085  7049  7124 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 16:41:03.085  7049  7124 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 16:41:03.086  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 16:41:03.086  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 16:41:03.086  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 16:41:03.086  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 16:41:03.086  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:03.087  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 16:41:03.090  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 16:41:03.091  1035  2077 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 16:41:03.092  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:03.097  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 16:41:03.101  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 16:41:03.102  7049  7124 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
,08-16 16:41:03.105  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 16:41:03.105  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 16:41:03.106  7049  7124 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 16:41:03.106  7049  7124 I io.jxcore.node.ConnectionHelper: start: OK
08-16 16:41:08.118  7049  7124 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:41:08.118  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:41:08.118  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 16:41:08.127  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:41:08.127  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:08.127  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 16:41:08.128  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32b99758 not in the list
08-16 16:41:08.128  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:08.128  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:08.128  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:41:08.128  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:13.129  7049  7124 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 16:41:13.143  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 16:41:13.150  7049  7124 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 16:41:13.150  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:13.150  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:13.150  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:41:13.150  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:41:13.150  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:41:13.150  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:41:13.150  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 16:41:13.153  7049  7124 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 16:41:13.154  7049  7124 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 16:41:13.156  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:13.157  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:13.158  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 16:41:13.158  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 16:41:13.158  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 16:41:13.158  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 16:41:13.159  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 16:41:13.164  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 16:41:13.166  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 16:41:13.168  7049  7124 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 16:41:13.168  7049  7124 I io.jxcore.node.ConnectionHelper: start: OK
08-16 16:41:13.170  7049  7124 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:41:13.170  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:41:13.170  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:41:13.171  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:41:13.172  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:13.172  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 16:41:13.172  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32b99758 not in the list
08-16 16:41:13.172  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:13.172  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:13.172  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:41:13.172  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:13.173  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:13.173  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:13.173  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:41:13.174  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:41:13.176  7049  7124 D BluetoothLeScanner: could not find callback wrapper
08-16 16:41:13.176  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 16:41:13.176  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:13.176  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:13.177  7049  7124 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 16:41:13.183  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 16:41:13.187  7049  7124 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 16:41:13.187  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:13.187  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:13.187  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:41:13.187  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:41:13.187  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:41:13.187  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:41:13.187  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 16:41:13.189  7049  7124 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 16:41:13.189  7049  7124 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 16:41:13.193  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:13.194  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:13.195  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 16:41:13.196  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 16:41:13.196  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 16:41:13.196  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 16:41:13.196  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 16:41:13.201  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 16:41:13.203  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 16:41:13.205  7049  7124 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 16:41:13.205  7049  7124 I io.jxcore.node.ConnectionHelper: start: OK
08-16 16:41:18.206  7049  7124 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:41:18.206  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:41:18.206  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 16:41:18.824  1035  1407 D PowerManagerServiceEx: acquireWakeLockInternal: lock=506009113, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,08-16 16:41:18.889  2613  2613 D [Concierge]Service: onStartCommand(). Type : 9
,08-16 16:41:18.924  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=506009113 [*alarm*], flags=0x0
,08-16 16:41:23.218  7049  7124 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:41:23.218  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:41:23.218  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 16:41:23.224  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:41:23.224  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.224  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 16:41:23.227  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32b99758 not in the list
08-16 16:41:23.227  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:23.227  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:23.227  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:41:23.227  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.228  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.228  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.229  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:41:23.229  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:41:23.230  7049  7124 D BluetoothLeScanner: could not find callback wrapper
08-16 16:41:23.230  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 16:41:23.230  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:23.230  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:23.231  7049  7124 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 16:41:23.231  7049  7124 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:41:23.232  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:41:23.232  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:41:23.232  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:41:23.232  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.232  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.232  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32b99758 not in the list
08-16 16:41:23.232  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:23.232  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:23.232  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:41:23.232  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.233  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Blueto,othManager: release: 2 listener(s) left
08-16 16:41:23.233  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.233  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:41:23.238  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:41:23.238  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:41:23.255  7049  7124 D BluetoothLeScanner: could not find callback wrapper
08-16 16:41:23.255  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 16:41:23.255  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:23.255  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:23.257  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 16:41:23.257  7049  7124 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:41:23.257  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:41:23.258  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 16:41:23.261  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:41:23.261  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.261  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.261  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32b99758 not in the list
08-16 16:41:23.261  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:23.261  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:23.261  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:41:23.261  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.261  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.261  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.261  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.266  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:41:23.266  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:41:23.267  7049  7124 D BluetoothLeScanner: could not find callback wrapper
08-16 16:41:23.267  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 16:41:23.267  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:23.267  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:23.268  7049  7124 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-16 16:41:23.268  7049  7124 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:41:23.269  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:41:23.269  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:41:23.269  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:41:23.269  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.269  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.269  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32b99758 not in the list
08-16 16:41:23.269  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:23.270  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:23.270  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:41:23.270  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The give,n listener does not exist in the list - probably already removed
08-16 16:41:23.270  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.270  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.270  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.276  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:41:23.276  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 16:41:23.280  7049  7124 D BluetoothLeScanner: could not find callback wrapper
08-16 16:41:23.280  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 16:41:23.280  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:23.280  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:23.282  7049  7124 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 16:41:23.282  7049  7124 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:41:23.282  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:41:23.283  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:41:23.283  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:41:23.283  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.283  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.284  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32b99758 not in the list
08-16 16:41:23.284  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:23.284  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:23.284  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:41:23.284  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.284  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.284  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.284  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.286  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:41:23.286  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:41:23.286  7049  7124 D BluetoothLeScanner: could not find callback wrapper
08-16 16:41:23.286  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 16:41:23.286  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:23.286  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:23.287  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 16:41:23.297  7049  7124 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 16:41:23.297  7049  7124 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 16:41:23.297  7049  7124 I org.thaliproject.p2p.btconn,ectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-16 16:41:23.303  7049  7124 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 16:41:23.303  7049  7124 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 16:41:23.303  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 16:41:23.304  7049  7124 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 16:41:23.304  7049  7124 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 16:41:23.304  7049  7124 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:41:23.304  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:41:23.304  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:41:23.305  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:41:23.305  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.305  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.305  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32b99758 not in the list
08-16 16:41:23.305  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:23.305  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:23.305  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:41:23.305  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.305  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.306  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.306  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.308  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:41:23.308  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:41:23.308  7049  7124 D BluetoothLeScanner: could not find callback wrapper
08-16 16:41:23.308  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 16:41:23.308  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:23.308  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:23.312  7049  7124 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-16 16:41:23.316  7049  7124 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 16:41:23.316  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 16:41:23.324  7049  7124 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 16:41:23.324  7049  7124 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 16:41:23.324  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 16:41:23.324  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 16:41:23.324  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 16:41:23.324  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 16:41:23.324  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 16:41:23.324  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 16:41:23.324  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 16:41:23.324  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 16:41:23.324  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 16:41:23.324  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 16:41:23.324  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 16:41:23.325  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 16:41:23.325  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 16:41:23.325  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 16:41:23.325  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 16:41:23.328  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 16:41:23.328  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 16:41:23.328  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 16:41:23.328  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 16:41:23.328  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 16:41:23.328  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 16:41:23.329  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 16:41:23.329  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:22,10:2210]
08-16 16:41:23.329  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 16:41:23.329  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 16:41:23.329  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 16:41:23.329  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 16:41:23.329  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 16:41:23.329  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 16:41:23.329  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 16:41:23.329  7049  7124 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 16:41:23.329  7049  7124 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 16:41:23.329  7049  7124 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-16 16:41:23.330  7049  7124 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 16:41:23.330  7049  7124 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 16:41:23.330  7049  7124 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 16:41:23.330  7049  7124 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 16:41:23.330  7049  7124 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 16:41:23.330  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-16 16:41:23.338  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 16:41:23.339  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 16:41:23.340  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 16:41:23.340  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 16:41:23.341  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 16:41:23.341  7049  7124 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 16:41:23.341  7049  7124 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 16:41:23.341  7049  7124 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 16:41:23.341  7049  7124 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:41:23.341  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:41:23.341  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:41:23.344  7049  7142 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 896)
,08-16 16:41:23.347  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:41:23.347  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.347  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.347  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 16:41:23.348  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32b99758 not in the list
08-16 16:41:23.348  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:23.348  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:23.348  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:41:23.348  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.348  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.348  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.348  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.356  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:41:23.356  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 16:41:23.359  7049  7124 D BluetoothLeScanner: could not find callback wrapper
08-16 16:41:23.359  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 16:41:23.359  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:23.359  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:23.360  7049  7124 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 16:41:23.360  7049  7124 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:41:23.360  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:41:23.360  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:41:23.362  7049  7143 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 896
08-16 16:41:23.362  7049  7143 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 896)
08-16 16:41:23.362  7049  7143 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 896)
08-16 16:41:23.363  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:41:23.363  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.363  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.363  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32b99758 not in the list
08-16 16:41:23.363  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:23.363  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:23.363  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:41:23.363  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.363  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.363  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.363  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.364  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:41:23.364  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:41:23.369  7049  7124 D BluetoothLeScanner: could not find callback wrapper
08-16 16:41:23.369  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 16:41:23.369  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:23.369  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:23.370  7049  7124 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: S,tate: NOT_STARTED, is discovering: true, is advertising: true
08-16 16:41:23.371  7049  7124 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:41:23.371  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:41:23.371  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:41:23.372  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:41:23.372  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:41:23.372  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.372  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32b99758 not in the list
08-16 16:41:23.372  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:23.372  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:23.372  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:41:23.372  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.372  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.372  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.372  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.373  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:41:23.373  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:41:23.374  7049  7124 D BluetoothLeScanner: could not find callback wrapper
08-16 16:41:23.374  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 16:41:23.374  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:23.375  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:23.376  7049  7124 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 16:41:23.385  7049  7124 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,08-16 16:41:23.385  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 16:41:23.385  7049  7124 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 16:41:23.386  7049  7124 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 16:41:23.386  7049  7124 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 16:41:23.386  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 16:41:23.387  7049  7124 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 16:41:23.387  7049  7124 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 16:41:23.387  7049  7124 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 16:41:23.387  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 16:41:23.387  7049  7124 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 16:41:23.387  7049  7124 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:41:23.387  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:41:23.387  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:41:23.388  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:41:23.388  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.388  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.388  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32b99758 not in the list
08-16 16:41:23.388  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:23.388  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:23.388  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:41:23.388  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.388  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.388  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.388  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.389  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:41:23.389  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:41:23.395  7049  7124 D BluetoothLeScanner: could not find callback wrapper
08-16 16:41:23,.395  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 16:41:23.395  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:23.395  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:23.396  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:41:23.396  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.396  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.396  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32b99758 not in the list
08-16 16:41:23.396  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:23.396  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:23.396  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:41:23.396  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:23.396  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:23.452  7049  7142 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-16 16:41:23.453  7049  7142 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 896)
,08-16 16:41:28.397  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 16:41:28.398  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
,08-16 16:41:28.398  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 16:41:28.398  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:41:28.398  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:41:28.398  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32b99758 not in the list,
08-16 16:41:28.398  7049  7124 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 16:41:28.399  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
,08-16 16:41:28.399  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,08-16 16:41:28.438  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 16:41:28.441  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:28.441  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:28.441  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32b99758 not in the list
08-16 16:41:28.441  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:28.441  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:28.441  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:41:28.441  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:28.455  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:28.455  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:28.455  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:41:28.460  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:41:28.460  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:41:28.461  7049  7124 D BluetoothLeScanner: could not find callback wrapper
08-16 16:41:28.461  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 16:41:28.461  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:28.461  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:28.464  7049  7124 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 16:41:28.464  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 16:41:28.465  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 16:41:28.466  7049  7124 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 16:41:28.466  7049  7124 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 16:41:28.467  7049  7049 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 16:41:28.467  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 16:41:28.467  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 16:41:28.468  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:41:28.469  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 16:41:28.469  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 16:41:28.469  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 16:41:28.469  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:28.469  7049  7124 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 16:41:28.471  7049  7161 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 16:41:28.471  7049  7161 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-16 16:41:28.475  7049  7049 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 16:41:28.475  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32b99758 not in the list
08-16 16:41:28.475  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:28.476  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 16:41:28.476  7049  7124 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 16:41:28.476  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 16:41:28.478  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 16:41:28.479  7049  7124 D BluetoothLeScanner: could not find callback wrapper
08-16 16:41:28.479  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 16:41:28.479  7049  7124 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 16:41:28.479  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:28.479  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:28.480  7049  7124 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 16:41:28.481  7049  7049 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 16:41:28.481  7049  7049 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 16:41:28.481  7049  7049 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 16:41:28.481  7049  7049 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 16:41:28.482  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:28.482  7049  7124 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:41:28.482  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:41:28.482  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:41:28.482  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:41:28.482  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:28.482  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:28.482  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32b99758 not in the list
08-16 16:41:28.482  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:28.482  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:28.482  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:41:28.482  7049  7,124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:28.483  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:28.483  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:28.483  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:28.484  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:41:28.484  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:41:28.484  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:28.484  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:28.485  7049  7124 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-16 16:41:28.490  7049  7124 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 16:41:28.490  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 16:41:28.493  7049  7124 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 16:41:28.493  7049  7124 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 16:41:28.494  7049  7124 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:41:28.494  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:41:28.495  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:41:28.496  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:41:28.496  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:28.496  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:28.496  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32b99758 not in the list
08-16 16:41:28.499  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 16:41:28.504  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:28.504  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:41:28.504  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:28.505  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:28.505  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:28.506  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:28.507  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:41:28.507  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:41:28.507  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:28.507  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:28.515  1035  2053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 16:41:28.519  1035  1982 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 16:41:28.520  1035  2077 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 16:41:28.521  7049  7124 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:41:28.521  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:41:28.521  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:41:28.521  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:41:28.521  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:28.521  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:28.521  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32b99758 not in the list
08-16 16:41:28.521  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:28.522  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:28.522  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:41:28.522  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:28.522  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:28.522  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:28.522  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:28.523  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:41:28.523  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:41:28.523  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:28.523  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:28.524  7049  7124 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:41:28.524  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:41:28.524  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:41:28.525  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:41:28.525  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:28.525  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:28.525  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32b99758 not in the list
08-,16 16:41:28.525  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:28.525  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:28.525  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:41:28.525  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:28.525  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:28.525  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:28.525  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:28.526  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:41:28.526  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:41:28.526  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:28.526  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3270b1 not in the list
08-16 16:41:28.528  7049  7124 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 16:41:28.528  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 16:41:28.528  7049  7124 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 16:41:28.528  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 16:41:28.528  7049  7124 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 16:41:28.528  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 16:41:28.531  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 16:41:28.531  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 16:41:28.531  7049  7124 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 16:41:28.532  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 16:41:28.532  7049  7124 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 16:41:28.532  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 16:41:28.532  7049  7124 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 16:41:28.532  7049  7124 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 16:41:28.533  7049  7124 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 16:41:28.533  7049  7124 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 16:41:28.534  7049  7124 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 16:41:28.534  7049  7124 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 16:41:28.534  7049  7124 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 16:41:28.534  7049  7124 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-16 16:41:28.539  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 16:41:28.539  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@215ec56e added. We now have 3 listener(s)
08-16 16:41:28.539  7049  7124 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 16:41:28.550  7049  7124 D BluetoothAdapter: enable(): BT is already enabled..!
08-16 16:41:28.551  1035  1720 D WifiServiceImplEx: setWifiEnabled: true pid=7049, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 16:41:28.551  1035  1720 D WifiService: setWifiEnabled: true pid=7049, uid=10118
08-16 16:41:28.551  1035  1720 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 16:41:28.983  7049  7049 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 16:41:33.564  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 16:41:33.564  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3695c40f added. We now have 4 listener(s)
08-16 16:41:33.564  7049  7124 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 16:41:33.580  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:33.580  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3695c40f removed from the list
08-16 16:41:33.580  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:41:33.580  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:33.580  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:33.581  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 16:41:33.581  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@121b3c9c added. We now have 4 listener(s)
08-16 16:41:33.581  7049  7124 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 16:41:33.586  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:41:33.586  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@121b3c9c removed from the list
08-16 16:41:33.586  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:41:33.586  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:33.586  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:33.586  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 16:41:33.587  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3eb886a5 added. We now have 4 listener(s)
08-16 16:41:33.587  7049  7124 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 16:41:33.590  1035  1051 D WifiServiceImplEx: setWifiEnabled: false pid=7049, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 16:41:33.590  1035  1051 D WifiService: setWifiEnabled: false pid=7049, uid=10118
08-16 16:41:33.590  1035  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 16:41:33.611  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 16:41:33.612  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 16:41:33.612  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-16 16:41:33.614  1035  1525 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 16:41:33.614  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 16:41:33.614  1035  1525 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-16 16:41:33.615  1035  1525 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 16:41:33.616  1035  1525 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 16:41:33.616  1035  1525 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 16:41:33.616  1035  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 16:41:33.616  1035  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 16:41:33.617  1035  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 16:41:33.617  1035  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 16:41:33.619  1035  2053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 16:41:33.620  1035  2053 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@14fca036 mBinding = false
,08-16 16:41:33.626  1035  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 16:41:33.627  1035  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:33.627  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:33.627  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 16:41:33.627  2581  2581 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 16:41:33.629  1035  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 16:41:33.629  1035  1525 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 16:41:33.629  1035  1525 D WifiNative-wlan0: SET ps 1: returned true
08-16 16:41:33.630  1035  2778 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:33.638  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 16:41:33.638  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-16 16:41:33.640  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-16 16:41:33.641  1035  1117 D BluetoothManagerService: Message: 2
08-16 16:41:33.642  1035  1117 D BluetoothManagerService: Sending off request.
08-16 16:41:33.643  4139  4285 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 16:41:33.644  4139  4229 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 16:41:33.644  4139  4229 D BluetoothAdapterProperties: Setting state to 13
08-16 16:41:33.644  4139  4229 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 16:41:33.645  4139  4229 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 16:41:33.645  4139  4229 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 16:41:33.650  4139  4251 D BluetoothAdapterProperties: Scan Mode:20
,08-16 16:41:33.654  4139  4229 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 16:41:33.656  4139  4229 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 16:41:33.658  4139  4554 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 16:41:33.658  4139  4554 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 16:41:33.658  4139  4554 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 16:41:33.658  4139  4554 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 16:41:33.658  4139  4554 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 16:41:33.658  4139  4554 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 16:41:33.658  4139  4554 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 16:41:33.658  4139  4554 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-16 16:41:33.658  4139  4557 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 16:41:33.659  4139  4577 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 16:41:33.659  4139  4578 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 16:41:33.659  4139  4591 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 16:41:33.663  4139  4396 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
,08-16 16:41:33.663  4139  4396 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-16 16:41:33.669  4139  4396 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 16:41:33.669  4139  4396 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 16:41:33.669  4139  4396 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 16:41:33.669  4139  4396 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 16:41:33.669  4139  4396 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 16:41:33.669  4139  4396 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 16:41:33.669  4139  4396 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 16:41:33.669  4139  4396 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 16:41:33.669  4139  4396 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 16:41:33.669  4139  4396 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 16:41:33.669  4139  4396 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 16:41:33.669  4139  4396 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 16:41:33.673  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:33.673  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:41:33.673  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:33.673  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:33.673  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:41:33.673  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:41:33.673  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:41:33.673  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:41:33.673  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 16:41:33.686  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:33.686  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 16:41:33.696  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:33.696  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:41:33.696  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:33.696  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:33.696  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:41:33.696  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:41:33.696  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:41:33.696  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:41:33.696  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 16:41:33.703  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:33.703  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 16:41:33.707  1035  1117 D BluetoothManagerService: Message: 60
08-16 16:41:33.707  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 16:41:33.707  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-16 16:41:33.708   319   878 D CommandListener: Clearing all IP addresses on wlan0
08-16 16:41:33.751  1035  1113 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7192 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 16:41:33.755  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 16:41:33.758  1959  1959 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:33.759  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 16:41:33.761  4139  4139 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:33.761  4139  4139 D BluetoothMapService: STATE_TURNING_OFF
08-16 16:41:33.761  4139  4139 V BluetoothMapService: Handler(): got msg=4
08-16 16:41:33.761  4139  4139 D BluetoothMapService: MAP Service closeService in
08-16 16:41:33.761  4139  4139 D BluetoothMapMasInstance: MAP Service shutdown
08-16 16:41:33.761  4139  4139 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 16:41:33.761  4139  4139 V BluetoothMapService: MAP Service closeService out
08-16 16:41:33.762  4139  4139 V BtOppService: Receiver DISABLED_ACTION 
,08-16 16:41:33.765  4139  4139 I BtOppRfcommListener: stopping Accept Thread
08-16 16:41:33.765  4139  4139 V BtOppRfcommListener: close mBtServerSocket
08-16 16:41:33.766  4139  4139 V BtOppRfcommListener: waiting for thread to terminate
08-16 16:41:33.766  4139  4577 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 16:41:33.766  4139  4139 V BtOppRfcommListener: done waiting for thread to terminate
08-16 16:41:33.768  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:33.769  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:33.771  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:33.771  7049  7124 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 16:41:33.771  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:33.771  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:33.771  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:41:33.771  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:41:33.771  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:41:33.771  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:41:33.771  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 16:41:33.772  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:33.772  7049  7124 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 16:41:33.772  7049  7124 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 16:41:33.774  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:41:33.779  1035  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 16:41:33.779  1035  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-16 16:41:33.812  1035  1113 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7218 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 16:41:33.817  1035  1531 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 16:41:33.817  1035  1531 D DSQN    : disableDataServiceNotify
08-16 16:41:33.817  1035  1531 D DSQN    : stop dsqn bin
08-16 16:41:33.818  4139  4139 V BtOppService: onDestroy
08-16 16:41:33.819  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-16 16:41:33.820  1959  1959 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-16 16:41:33.821  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:33.821  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:33.821  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 16:41:33.822  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:33.822  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:41:33.822  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:33.822  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:33.822  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:41:33.822  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:41:33.822  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:41:33.822  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:41:33.822  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 16:41:33.823  1035  1531 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-16 16:41:33.823  1035  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:41:33.823  1035  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 16:41:33.823  1035  1531 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 16:41:33.823  1035  1531 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-16 16:41:33.824  1589  1796 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-16 16:41:33.824  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-16 16:41:33.824  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:33.824  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:33.824  1035  1531 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-16 16:41:33.824  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 16:41:33.824  1035  1531 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-16 16:41:33.824  1035  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 16:41:33.825  1035  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 16:41:33.825  1035  2770 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:33.825  1035  2770 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:33.825  1035  2770 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 16:41:33.825  4139  4139 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 16:41:33.826  1035  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 16:41:33.826  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:33.826  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:41:33.831  1035  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 16:41:33.831  1035  1531 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:41:33.831  1035  1531 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:41:33.832  1035  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:33.832  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:33.832  1035  1521 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@13a243be
08-16 16:41:33.832  1035  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 16:41:33.832  1035  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 16:41:33.832  1035 , 1521 D LGWifiP2pService: P2pDisablingState
08-16 16:41:33.832  1035  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 16:41:33.832  1035  1521 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:33.832  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 16:41:33.833  1035  1521 D LGWifiP2pService: p2p socket connection lost
08-16 16:41:33.833  1035  1521 D LGWifiP2pService: P2pDisabledState
08-16 16:41:33.833  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 16:41:33.833  1035  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 16:41:33.833  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 16:41:33.833  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 16:41:33.833  1035  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 16:41:33.834  1035  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 16:41:33.834  1035  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 16:41:33.834  1035  1525 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 16:41:33.835  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:33.835  1035  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,08-16 16:41:33.835  1035  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 16:41:33.835  1035  1531 D NetworkManagementService: Removing idletimer
08-16 16:41:33.835  1035  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 16:41:33.836  1035  1531 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:33.836  1035  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
,08-16 16:41:33.836  1035  1531 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-16 16:41:33.837  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:41:33.837  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 16:41:33.838  1862  1862 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:41:33.838  1862  1862 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 16:41:33.842  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:33.845  1035  1521 D LGWifiP2pService: P2pDisabledState{ when=-9ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:33.845  1035  1521 D LGWifiP2pService: DefaultState{ when=-9ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:33.845  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:41:33.845  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 16:41:33.845  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 16:41:33.845  2581  2581 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 16:41:33.846  1035  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 16:41:33.846  1035  1525 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 16:41:33.846  1035  1525 D WifiNative-wlan0: SET ps 1: returned true
08-16 16:41:33.846   319   878 D CommandListener: Clearing all IP addresses on wlan0
08-16 16:41:33.846  1035  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,08-16 16:41:33.846  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 16:41:33.847  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 16:41:33.847  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 16:41:33.847  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 16:41:33.847  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:33.849  1959  1959 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 16:41:33.849  1959  1959 D WfdsService: WifiP2pState is changed : false
08-16 16:41:33.849  1959  2274 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 16:41:33.849  1959  2274 D WfdsService: Set the WFDS Monitor: false
08-16 16:41:33.849  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 16:41:33.849  1035  1035 D RttService: SCAN_AVAILABLE : 1
08-16 16:41:33.849  1035  1543 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:33.849  1959  2274 D WfdsMonitor: WFDS Monitor is stopped
08-16 16:41:33.849  1035  1544 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:33.849  1959  2274 D WfdsService: STATE : WfdsDisabledState - enter
08-16 16:41:33.850  1959  2276 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-16 16:41:33.850  1959  2658 D CtrlSupplicant: Received on exit socket, terminate
08-16 16:41:33.850  1959  2658 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 16:41:33.850  1959  2658 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 16:41:33.850  1959  2658 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 16:41:33.850  1959  2274 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 16:41:33.851  1035  1525 D WifiNative-p2p0: doBoolean: TERMINATE
08-16 16:41:33.851  1035  1525 D WifiNative-p2p0: TERMINATE: returned true
08-16 16:41:33.851  1035  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 16:41:33.851  1035  1525 E WifiStateMachine: useWiFiOffloading() : false
08-16 16:41:33.851  1035  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 16:41:33.852  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-16 16:41:33.854  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:33.854  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:33.854  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 16:41:33.855  1035  1525 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:41:33.856  1035  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 16:41:33.857  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 16:41:33.857  1959  1959 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 16:41:33.858  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:33.858  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:41:33.858  ,7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:33.858  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:33.858  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:41:33.858  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:41:33.858  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:41:33.858  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:41:33.858  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:41:33.859  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:33.859  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 16:41:33.861  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 16:41:33.861  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 16:41:33.862  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:33.862  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:41:33.862  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:33.862  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:33.862  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:41:33.862  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:41:33.862  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:41:33.862  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:41:33.862  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:41:33.863  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:33.863  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:41:33.866  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:33.866  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:41:33.866  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:33.866  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:33.866  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:41:33.866  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:41:33.866  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:41:33.866  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:41:33.866  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:41:33.866  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:33.867  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:41:33.878  7218  7218 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 16:41:33.878  7218  7218 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-16 16:41:33.878  7218  7218 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 16:41:33.879  7218  7218 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-16 16:41:33.879  7218  7218 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 16:41:33.880  7218  7218 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 16:41:33.883  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 16:41:33.883  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:33.884  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:33.900  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 16:41:33.900  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:33.901  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:33.901  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 16:41:33.901  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 16:41:33.902  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 16:41:33.918  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 16:41:33.919  7192  7192 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-16 16:41:33.919  7192  7192 W LG Account v2.2: No ProfileInfo entries
08-16 16:41:33.919  7192  7192 I LG Account v2.2: isEnabled: false
08-16 16:41:33.919  7192  7192 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 16:41:33.919  7192  7192 I Feature : [Lifetracker]Country: EU
08-16 16:41:33.919  7192  7192 I Feature : [Lifetracker]Operator: OPEN
08-16 16:41:33.919  7192  7192 I Feature : [Lifetracker]Ranking support: false
08-16 16:41:33.919  7192  7192 I Feature : [Lifetracker]Comfort support: false
08-16 16:41:33.919  7192  7192 I Feature : [Lifetracker]Accessory: true
08-16 16:41:33.919  7192  7192 I Feature : [Lifetracker]Health device: true
08-16 16:41:33.919  7192  7192 I Feature : [Lifetracker]Extra Pedometer: false
08-16 16:41:33.919  7192  7192 I Feature : [Lifetracker]Blood glucose device: false
08-16 16:41:33.919  7192  7192 I Feature : [Lifetracker]Device Number: 3
08-16 16:41:33.922  2581  2581 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 16:41:33.922  2581  2581 I wpa_supplicant: monitor socket send errors count : 1
08-16 16:41:33.922  2581  2581 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1959-2\x00 that cannot receive messages
08-16 16:41:33.923  1035  2642 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-16 16:41:33.923  1035  2642 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 16:41:33.929  6342  6342 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:41:33.933  1035  2778 D DhcpStateMachine: StoppedState
08-16 16:41:33.933  1035  2778 D DhcpStateMachine: StoppedState{ when=-87ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 16:41:33.960  2581  2581 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 16:41:33.960  1035  2642 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-16 16:41:33.960  1035  2642 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 16:41:33.960  1035  2642 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 16:41:33.961  1035  2642 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-16 16:41:33.961  2581  2581 W wpa_supplicant: USIM:  scard_deinit function
08-16 16:41:33.961  1035  1525 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=365994
08-16 16:41:33.962  1035  1117 D Tethering: InitialState.processMessage what=4
08-16 16:41:33.962  1035  2642 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 16:41:33.962  1035  2642 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 16:41:33.962  1035  1525 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=365994
08-16 16:41:33.962  1035  1525 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=365994  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 16:41:33.963  1035  1525 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=365995  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,08-16 16:41:33.968  1035  1914 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7240 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 16:41:33.970  1035  1914 I ActivityManager: Killing 6705:com.qualcomm.timeservice/1000 (adj 15): empty #17
08-16 16:41:33.977   354   354 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 196us total 10.836ms
08-16 16:41:33.977  7218  7218 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 16:41:33.987   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 196us total 9.367ms
,08-16 16:41:33.997   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 188us total 9.431ms
,08-16 16:41:34.016  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 16:41:34.018  1035  1525 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-16 16:41:34.019  1035  1525 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-16 16:41:34.023  1035  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_6705/cgroup.procs: No such file or directory
08-16 16:41:34.025  1035  1525 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-16 16:41:34.025  1035  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 16:41:34.025  1035  1117 D BluetoothManagerService: Message: 20
08-16 16:41:34.025  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@36b14b10:true
08-16 16:41:34.030  4139  4139 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 16:41:34.030  4139  4139 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:34.030  4139  4139 V BluetoothPbapReceiver: ***********state = 13
08-16 16:41:34.032  4139  4139 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-16 16:41:34.033  4139  4139 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:34.033  4139  4139 V BluetoothPbapService: state: 13
08-16 16:41:34.033  4139  4139 V BluetoothPbapService: Pbap Service closeService in
08-16 16:41:34.034  1035  1117 D BluetoothManagerService: Message: 30
08-16 16:41:34.041  4139  4139 V BluetoothPbapService: successfully stopped pbap service
08-16 16:41:34.041  4139  4139 V BluetoothPbapService: Pbap Service closeService out
08-16 16:41:34.041  4139  4139 V BluetoothPbapService: Pbap Service onDestroy
08-16 16:41:34.041  4139  4139 V BluetoothPbapService: Pbap Service closeService in
08-16 16:41:34.041  2205  2205 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 16:41:34.041  4139  4139 V BluetoothPbapService: Pbap Service closeService out
08-16 16:41:34.041  4139  4139 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-16 16:41:34.043  1035  1117 D BluetoothManagerService: Message: 30
,08-16 16:41:34.049  7218  7218 D LocalBluetoothProfileManager: Adding local MAP profile
08-16 16:41:34.050  2581  2581 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-16 16:41:34.051  7218  7218 D BluetoothMap: Create BluetoothMap proxy object
08-16 16:41:34.051  1035  1117 D BluetoothManagerService: Message: 30
08-16 16:41:34.051  1035  2642 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 16:41:34.051  1035  2642 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 16:41:34.052  1035  2642 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 16:41:34.052  1035  1525 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-16 16:41:34.056  1035  1117 D BluetoothManagerService: Message: 30
08-16 16:41:34.057  7218  7218 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-16 16:41:34.058  7218  7218 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,08-16 16:41:34.068  7218  7218 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-16 16:41:34.071  7218  7218 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-16 16:41:34.077  7218  7218 D DockEventReceiver: finishStartingService: stopping service
,08-16 16:41:34.079  7218  7218 D BluetoothInputDevice: Proxy object connected
08-16 16:41:34.080  7218  7218 D HidProfile: Bluetooth service connected
08-16 16:41:34.085  7218  7218 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 16:41:34.086  7218  7218 D PanProfile: Bluetooth service connected
08-16 16:41:34.086  7218  7218 D BluetoothMap: Proxy object connected
08-16 16:41:34.087  7218  7218 D MapProfile: Bluetooth service connected
08-16 16:41:34.087  7218  7218 D BluetoothMap: getConnectedDevices()
08-16 16:41:34.087  7218  7218 D BluetoothMap: Bluetooth is Not enabled
08-16 16:41:34.087  7218  7218 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-16 16:41:34.089  7218  7218 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 16:41:34.093  7218  7218 D BluetoothPermissionRequest: onReceive
08-16 16:41:34.095  7218  7218 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-16 16:41:34.100  7240  7240 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-16 16:41:34.102  7218  7218 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 16:41:34.104  1035  2086 I ActivityManager: Killing 6724:com.android.calendar/u0a13 (adj 15): empty #17
08-16 16:41:34.104  7240  7240 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 16:41:34.104  7240  7240 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 16:41:34.138  4139  4139 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-16 16:41:34.138  4139  4139 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-16 16:41:34.139  4139  4139 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-16 16:41:34.142  1035  1956 W libprocessgroup: failed to open /acct/uid_10013/pid_6724/cgroup.procs: No such file or directory
08-16 16:41:34.155  1035  1525 D WifiOffDelayIfNotUsed: stopMonitoring
08-16 16:41:34.155  1035  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 16:41:34.155  1035  1525 E WifiStateMachine: useWiFiOffloading() : false
08-16 16:41:34.155  1035  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-16 16:41:34.160  6840  6840 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:34.161  1959  1959 D WfdsService: Supplicant Connection state is changed : false
08-16 16:41:34.161  1959  2274 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-16 16:41:34.162  1959  2274 D WfdsService: Set the WFDS Monitor: false
08-16 16:41:34.162  1959  2274 D WfdsMonitor: WFDS Monitor is stopped
08-16 16:41:34.162  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-16 16:41:34.162  4139  4139 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:34.162  4139  4139 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 16:41:34.162  1959  1959 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 16:41:34.163  1035  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 16:41:34.163  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:34.163  1035  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 16:41:34.166  4139  4139 V BluetoothFtpService: Ftp Service onStartCommand
08-16 16:41:34.167  4139  4139 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:34.167  2484  2484 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:34.167  4139  4139 V BluetoothFtpService: Ftp Service closeService
08-16 16:41:34.167  4139  4139 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 16:41:34.169  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:41:34.171  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:34.173  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:34.178  4139  4139 V BluetoothFtpService: successfully stopped ftp service
08-16 16:41:34.179  4139  4139 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 16:41:34.179  4139  4139 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 16:41:34.179  4139  4139 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 16:41:34.179  4139  4139 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:34.179  4139  4139 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-16 16:41:34.179  4139  4139 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 16:41:34.180  4139  4139 V BluetoothFtpService: Ftp Service onDestroy
08-16 16:41:34.180  4139  4139 V BluetoothFtpService: Ftp Service closeService
08-16 16:41:34.189  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 16:41:34.236  1035  1562 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7270 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 16:41:34.238  4139  4139 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:34.238  4139  4139 V BluetoothSapService: state: 13
08-16 16:41:34.239  4139  4139 V BluetoothSapService: Stopping SAP server process
,08-16 16:41:34.240  4139  4139 V BluetoothSapService: Sap Service closeSapService in
08-16 16:41:34.240  4139  4139 V BluetoothSapService: Close listen Socket : 
08-16 16:41:34.241  4139  4139 V BluetoothSapService: Close rfcomm Socket : 
08-16 16:41:34.241  4139  4139 V BluetoothSapService: Close sapd  Socket : 
08-16 16:41:34.242  4139  4139 V BluetoothSapService: Sap Service closeSapService out
08-16 16:41:34.242  7218  7218 D LgDataFeature: LgDataFeature() Constructor: none
08-16 16:41:34.242  7218  7218 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 16:41:34.243  4139  4139 V BluetoothSapService: Sap Service onDestroy
08-16 16:41:34.243  4139  4139 V BluetoothSapService: Sap Service closeSapService in
08-16 16:41:34.243  4139  4139 V BluetoothSapService: Close listen Socket : 
08-16 16:41:34.243  4139  4139 V BluetoothSapService: Close rfcomm Socket : 
08-16 16:41:34.243  4139  4139 V BluetoothSapService: Close sapd  Socket : 
08-16 16:41:34.243  4139  4139 V BluetoothSapService: Sap Service closeSapService out
,08-16 16:41:34.255  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 16:41:34.325  1035  2053 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7287 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-16 16:41:34.327  1035  2053 I ActivityManager: Killing 6658:com.lge.clock/u0a10 (adj 15): empty #17
,08-16 16:41:34.386  1035  1956 W libprocessgroup: failed to open /acct/uid_10010/pid_6658/cgroup.procs: No such file or directory
08-16 16:41:34.412  7270  7270 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 16:41:34.417  7287  7287 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 16:41:34.432  1035  1720 I ActivityManager: Killing 6682:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-16 16:41:34.531  1035  1050 W libprocessgroup: failed to open /acct/uid_10085/pid_6682/cgroup.procs: No such file or directory
,08-16 16:41:34.543  7287  7287 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-16 16:41:34.602  7287  7287 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-16 16:41:34.603  7287  7287 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-16 16:41:34.603  7287  7287 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,08-16 16:41:34.603  7287  7287 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-16 16:41:34.604  7287  7287 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-16 16:41:34.606  7287  7287 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-16 16:41:34.613  7287  7287 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-16 16:41:34.621  7287  7287 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 16:41:34.627  7287  7287 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 16:41:34.666  7287  7287 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 16:41:34.680  4139  4251 D bt_hci_bdroid: cleanup
08-16 16:41:34.680  4139  4398 I bt_lpm  : LPM is already off!!!
08-16 16:41:34.681  6342  6342 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:41:34.681  4139  4529 I bt_userial_mct: exiting userial_read_thread
08-16 16:41:34.681  4139  4529 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 16:41:34.681  4139  4396 W bt-btif : ag scb idx 1 not allocated
08-16 16:41:34.681  4139  4396 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 16:41:34.681  4139  4396 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 16:41:34.681  4139  4396 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 16:41:34.681  4139  4396 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 16:41:34.681  4139  4396 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 16:41:34.681  4139  4396 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 16:41:34.681  4139  4396 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 16:41:34.681  4139  4396 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 16:41:34.681  4139  4396 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 16:41:34.681  4139  4396 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,08-16 16:41:34.681  4139  4396 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 16:41:34.681  4139  4396 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 16:41:34.681  4139  4396 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 16:41:34.681  4139  4396 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 16:41:34.681  4139  4396 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 16:41:34.681  4139  4396 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 16:41:34.681  4139  4396 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 16:41:34.681  4139  4396 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 16:41:34.681  4139  4396 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 16:41:34.681  4139  4396 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 16:41:34.682  4139  4251 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 16:41:34.682  4139  4398 I bt_vendor: hw_epilog_process
08-16 16:41:34.682  4139  4251 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 16:41:34.682  4139  4251 D bt_userial_mct: userial_close
08-16 16:41:34.682  4139  4251 E bt_userial_mct: pthread_join() FAILED result:3
08-16 16:41:34.682  4139  4251 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-16 16:41:34.688  7287  7287 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-16 16:41:34.688  7240  7240 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 16:41:34.688  7240  7240 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 16:41:34.688  7240  7240 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 16:41:34.691  7287  7287 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-16 16:41:34.695  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 16:41:34.704  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 16:41:34.712  7287  7287 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 16:41:34.713  7287  7287 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 16:41:34.715  7287  7287 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 16:41:34.718  6342  6342 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:41:34.721  7240  7240 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 16:41:34.721  7240  7240 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 16:41:34.721  7240  7240 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 16:41:34.726  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 16:41:34.733  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 16:41:34.742  7287  7287 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 16:41:34.742  7287  7287 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 16:41:34.744  7287  7287 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 16:41:34.755  4139  4251 D bt_hci_bdroid: set_power 0
08-16 16:41:34.755  4139  4251 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 16:41:34.756  4139  4251 I bt_vendor: bluetooth satus is on
08-16 16:41:34.756  4139  4251 I bt_vendor: bt-vendor : resetting BT status
,08-16 16:41:34.756  4139  4251 I bt_vendor: Starting hciattach daemon
08-16 16:41:34.756  4139  4251 I bt_vendor: try to set false
08-16 16:41:34.757  4139  4251 I bt_vendor: Starting hciattach daemon
08-16 16:41:34.757  4139  4251 I bt_vendor: try to set false
08-16 16:41:34.758  4139  4251 I bt_vendor: cleanup
,08-16 16:41:34.759  4139  4396 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 16:41:34.760  4139  4251 I GKI_LINUX: GKI_exit_task 0 done
08-16 16:41:34.760  4139  4251 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 16:41:34.762  4139  4229 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 16:41:34.813  1035  1914 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7311 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-16 16:41:34.819  4139  4139 D HeadsetService: Received stop request...Stopping profile...
08-16 16:41:34.820  4139  4139 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 16:41:34.820  4139  4139 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 16:41:34.820  4139  4139 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ceb47d9
08-16 16:41:34.821  4139  4286 D HeadsetStateMachine: Exit Disconnected: -1
08-16 16:41:34.823  1862  1862 D BluetoothHeadset: Proxy object disconnected
08-16 16:41:34.823  1035  1035 D BluetoothHeadset: Proxy object disconnected
08-16 16:41:34.823  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 16:41:34.823  1862  1862 D BluetoothHeadset: Proxy object disconnected
08-16 16:41:34.824  1862  1862 D BluetoothHeadset: Proxy object disconnected
08-16 16:41:34.824  4139  4139 D A2dpService: Received stop request...Stopping profile...
08-16 16:41:34.826  4139  4349 D A2dpStateMachine: Exit Disconnected: -1
08-16 16:41:34.826  4139  4139 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-16 16:41:34.828  4139  4229 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 16:41:34.829  4139  4139 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 16:41:34.829  4139  4139 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 16:41:34.829  4139  4139 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ceb47d9
08-16 16:41:34.830  1035  1035 D BluetoothA2dp: Proxy object disconnected
08-16 16:41:34.830  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 16:41:34.831  4139  4139 D HidService: Received stop request...Stopping profile...
08-16 16:41:34.831  4139  4139 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ceb47d9
08-16 16:41:34.833  4139  4139 D HeadsetStateMachine: Unbinding service...
08-16 16:41:34.833  7218  7218 D BluetoothInputDevice: Proxy object disconnected
08-16 16:41:34.833  4139  4139 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 16:41:34.833  4139  4139 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 16:41:34.833  4139  4139 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 16:41:34.834  4139  4139 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 16:41:34.834  4139  4139 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 16:41:34.834  4139  4139 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 16:41:34.834  4139  4139 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 16:41:34.835  4139  4139 D HealthService: Received stop request...Stopping profile...
08-16 16:41:34.835  4139  4139 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ceb47d9
08-16 16:41:34.836  4139  4139 D PanService: Received stop request...Stopping profile...
08-16 16:41:34.837  7218  7218 D HidProfile: Bluetooth service disconnected
08-16 16:41:34.837  4139  4139 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ceb47d9
,08-16 16:41:34.838  4139  4139 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 16:41:34.839  4139  4139 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 16:41:34.839  4139  4139 D BtGatt.GattService: stop()
08-16 16:41:34.839  4139  4139 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 16:41:34.840  4139  4139 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ceb47d9
08-16 16:41:34.842  4139  4139 D BluetoothMapService: Received stop request...Stopping profile...
08-16 16:41:34.842  4139  4139 D BluetoothMapService: stop()
08-16 16:41:34.842  7218  7218 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 16:41:34.842  4139  4139 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 16:41:34.842  4139  4139 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 16:41:34.842  7218  7218 D PanProfile: Bluetooth service disconnected
08-16 16:41:34.843  4139  4139 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ceb47d9
08-16 16:41:34.843  7218  7218 D BluetoothMap: Proxy object disconnected
08-16 16:41:34.843  7218  7218 D MapProfile: Bluetooth service disconnected
08-16 16:41:34.844  4139  4139 I BluetoothA2dpServiceJni: cleanupNative
08-16 16:41:34.844  4139  4350 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 16:41:34.844  4139  4139 I GKI_LINUX: GKI_exit_task 2 done
08-16 16:41:34.844  4139  4139 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 16:41:34.844  4139  4139 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 16:41:34.844  4139  4139 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 16:41:34.845  4139  4139 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 16:41:34.845  4139  4139 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 16:41:34.845  4139  4139 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 16:41:34.845  4139  4139 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 16:41:34.845  4139  4139 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 16:41:34.846  4139  4139 V BluetoothMapService: Handler(): got msg=4
08-16 16:41:34.846  4139  4139 D BluetoothMapService: MAP Service closeService in
08-16 16:41:34.846  4139  4139 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 16:41:34.846  4139  4139 V BluetoothMapService: MAP Service closeService out
08-16 16:41:34.847  4139  4139 D BluetoothMapService: cleanup()
08-16 16:41:34.847  4139  4139 D BluetoothMapService: MAP Service closeService in
08-16 16:41:34.847  4139  4139 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 16:41:34.847  4139  4139 V BluetoothMapService: MAP Service closeService out
08-16 16:41:34.847  4139  4229 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 16:41:34.847  4139  4229 D BluetoothAdapterProperties: Setting state to 10
08-16 16:41:34.847  4139  4229 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 16:41:34.847  1035  1117 D BluetoothManagerService: Message: 60
08-16 16:41:34.847  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 16:41:34.847  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-16 16:41:34.847  4139  4229 I BluetoothAdapterState: Entering OffState
08-16 16:41:34.848  7218  7235 D BluetoothPan: onBluetoothStateChange on: false
08-16 16:41:34.848  7218  7236 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 16:41:34.849  1862  4733 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 16:41:34.850  7218  7235 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 16:41:34.850  7218  7236 D BluetoothMap: onBluetoothStateChange: up=false
,08-16 16:41:34.851  1862  1877 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 16:41:34.851  1862  1878 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 16:41:34.852  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 16:41:34.852  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 16:41:34.853  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 16:41:34.853  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-16 16:41:34.856  1035  1117 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 16:41:34.856  1035  1117 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 16:41:34.856  1035  1117 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@14fca036 mBinding = false
08-16 16:41:34.857  1035  1117 D BluetoothManagerService: Sending unbind request.
08-16 16:41:34.859  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-16 16:41:34.865  4139  4251 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-16 16:41:34.865  4139  4139 I GKI_LINUX: GKI_exit_task 1 done
08-16 16:41:34.865  4139  4139 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 16:41:34.866  4139  4139 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 16:41:34.866  4139  4139 I art     : --- WEIRD: removing null entry 246
08-16 16:41:34.866  4139  4139 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-16 16:41:34.866  4139  4139 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-16 16:41:34.869  4139  4139 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-16 16:41:34.870  1959  1959 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:34.870  1959  2148 D LGBluetoothAPIService: Message: 2
08-16 16:41:34.871  1959  2148 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2b01ba6e mBinding = false
08-16 16:41:34.871  1959  2148 D LGBluetoothAPIService: Sending unbind request.
08-16 16:41:34.871  4139  4139 I art     : System.exit called, status: 0
08-16 16:41:34.871  4139  4139 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 16:41:34.875  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 16:41:34.877  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:34.878  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:34.878  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:34.885  7218  7218 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 16:41:34.887  7218  7218 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-16 16:41:34.887  7218  7218 D LGBluetoothEventManager: [BTUI] clear device connection state
08-16 16:41:34.891  7218  7218 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 16:41:34.894   326  4290 V AudioFlinger: 4139 died, releasing its sessions
08-16 16:41:34.894   326  4290 V AudioFlinger:  pid 1862 @ 0
08-16 16:41:34.894   326  4290 V AudioFlinger:  pid 3296 @ 1
08-16 16:41:34.894   326  4290 V AudioFlinger:  pid 3296 @ 2
08-16 16:41:34.896  1589  1589 D BluetoothAdapter: 351435803: getState() :  mService = null. Returning STATE_OFF
08-16 16:41:34.896  1589  1589 D BluetoothAdapter: 351435803: getState() :  mService = null. Returning STATE_OFF
08-16 16:41:34.925  1035  1051 I ActivityManager: Process com.android.bluetooth (pid 4139) has died
08-16 16:41:34.925  1035  1051 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-16 16:41:34.930  7218  7218 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-16 16:41:34.973  1035  2022 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7336 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-16 16:41:34.979  7218  7218 D DockEventReceiver: finishStartingService: stopping service
08-16 16:41:34.995  7240  7240 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 16:41:35.001  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 16:41:35.010  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 16:41:35.020  7311  7355 W FormManager: Network not available. Please check & try again.
,08-16 16:41:35.038  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 16:41:35.039  7218  7218 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 16:41:35.039  7218  7218 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-16 16:41:35.039  7218  7218 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 16:41:35.040  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-16 16:41:35.044  7311  7356 V FormManager: Network unavailable.
08-16 16:41:35.044  7336  7336 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-16 16:41:35.045  7336  7336 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 16:41:35.045  7336  7336 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-16 16:41:35.046  7336  7336 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 16:41:35.048  7311  7356 V FormManager: Network unavailable.
08-16 16:41:35.057  7218  7218 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 16:41:35.058  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 16:41:35.058  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 16:41:35.058  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 16:41:35.058  7218  7218 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 16:41:35.058  7218  7218 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-16 16:41:35.063  4627  4627 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 16:41:35.064  4627  4627 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 16:41:35.064  7336  7336 D BluetoothAdapterApp: Loading JNI Library
08-16 16:41:35.066  4627  4627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 16:41:35.069  4627  4627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 16:41:35.077  7240  7240 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-16 16:41:35.078  7240  7240 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 16:41:35.078  7240  7240 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 16:41:35.080  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 16:41:35.085  4627  7361 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 16:41:35.088  4627  7361 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 16:41:35.090  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 16:41:35.094  7311  7362 W FormManager: Network not available. Please check & try again.
08-16 16:41:35.102  7336  7336 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2ee23c6 Instance Count = 1
,08-16 16:41:35.103  7311  7363 V FormManager: Network unavailable.
08-16 16:41:35.107  4627  7359 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 16:41:35.110  7336  7336 D BluetoothAdapterApp: onCreate
08-16 16:41:35.111  7287  7287 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 16:41:35.112  7311  7363 V FormManager: Network unavailable.
08-16 16:41:35.113  7287  7287 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 16:41:35.113  7287  7287 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-16 16:41:35.118  1035  1051 I ActivityManager: Killing 6537:com.lge.bnr/1000 (adj 15): empty #17
,08-16 16:41:35.131  7336  7336 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-16 16:41:35.132  7336  7336 D ProfileConfigQcom: Adding HeadsetService
,08-16 16:41:35.132  7336  7336 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-16 16:41:35.132  7336  7336 D ProfileConfigQcom: Adding A2dpService
,08-16 16:41:35.132  7336  7336 D ProfileConfigQcom: [BTUI] HidService is supported
08-16 16:41:35.132  7336  7336 D ProfileConfigQcom: Adding HidService
08-16 16:41:35.133  7336  7336 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 16:41:35.133  7336  7336 D ProfileConfigQcom: Adding HealthService
08-16 16:41:35.133  7336  7336 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-16 16:41:35.134  7336  7336 D ProfileConfigQcom: [BTUI] PanService is supported
08-16 16:41:35.134  7336  7336 D ProfileConfigQcom: Adding PanService
08-16 16:41:35.135  7336  7336 D ProfileConfigQcom: [BTUI] GattService is supported
08-16 16:41:35.135  7336  7336 D ProfileConfigQcom: Adding GattService
,08-16 16:41:35.135  7336  7336 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 16:41:35.135  7336  7336 D ProfileConfigQcom: Adding BluetoothMapService
08-16 16:41:35.136  7336  7336 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 16:41:35.136  7336  7336 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 16:41:35.138  7336  7336 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:35.138  7336  7336 V BluetoothPbapReceiver: ***********state = 10
08-16 16:41:35.139  7336  7336 V LGMDMManagerInternal: Create singleton instance
,08-16 16:41:35.151  7287  7287 D LgDataFeature: LgDataFeature() Constructor: none
08-16 16:41:35.151  7287  7287 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 16:41:35.158  7287  7287 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-16 16:41:35.164  7287  7287 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-16 16:41:35.164  7287  7287 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-16 16:41:35.164  7287  7287 V SoundPool: doLoad: loading sample sampleID=1
08-16 16:41:35.165  7287  7368 V SoundPool: Start decode
08-16 16:41:35.165  7287  7368 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-16 16:41:35.166   326  4290 V MediaPlayerService: decode(22, 10857164, 17813)
08-16 16:41:35.166   326  4290 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-16 16:41:35.167  7287  7287 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 16:41:35.167   326  4290 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-16 16:41:35.167   326  4290 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-16 16:41:35.167   326  4290 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-16 16:41:35.167   326  4290 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-16 16:41:35.167   326  4290 V MediaPlayerService: player type = 3
08-16 16:41:35.167   326  4290 V AwesomePlayer: AwesomePlayer create()
08-16 16:41:35.168   326  4290 V AwesomePlayer: reset_l() 
08-16 16:41:35.168   326  4290 V AwesomePlayer: cancelPlayerEvents
08-16 16:41:35.168   326  4290 V AwesomePlayer: setAudioSink() 
08-16 16:41:35.168   326  4290 V AwesomePlayer: reset_l() 
08-16 16:41:35.168   326  4290 V AudioCache: notify(0xb5474b40, 8, 0, 0)
08-16 16:41:35.168   326  4290 V AudioCache: ignored
08-16 16:41:35.168   326  4290 V AwesomePlayer: cancelPlayerEvents
08-16 16:41:35.168   326  4290 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
,08-16 16:41:35.168   326  4290 V AwesomePlayer: setDataSource_l dataSource
08-16 16:41:35.168   326  4290 V LGParserOSAL: SniffLGParser start
,08-16 16:41:35.169   326  4290 V LGParserOSAL: MainType:5, SubType=0
08-16 16:41:35.169   326  4290 V LGParserOSAL: #### check Mime : application/ogg
08-16 16:41:35.169   326  4290 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-16 16:41:35.169   326  4290 E MediaExtractor: Use LGExtractor :application/ogg 
,08-16 16:41:35.196  1035  1913 W libprocessgroup: failed to open /acct/uid_1000/pid_6537/cgroup.procs: No such file or directory
,08-16 16:41:35.226   326  4290 V LGParserOSAL: supported mime: application/ogg
08-16 16:41:35.226   326  4290 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-16 16:41:35.226   326  4290 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
,08-16 16:41:35.226   326  4290 V AwesomePlayer: mBitrate = -1 bits/sec
08-16 16:41:35.226   326  4290 V AwesomePlayer: AudioTrack Setting
08-16 16:41:35.226   326  4290 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-16 16:41:35.226   326  4290 V AwesomePlayer: setAudioSource() 
08-16 16:41:35.226   326  4290 V MediaPlayerService: prepare
08-16 16:41:35.226   326  4290 V AwesomePlayer: prepareAsync_l() 
08-16 16:41:35.226   326  4290 V MediaPlayerService: wait for prepare
08-16 16:41:35.226   326  7369 V AwesomePlayer: onPrepareAsyncEvent() 
08-16 16:41:35.226   326  7369 V AwesomePlayer: initAudioDecoder() 
08-16 16:41:35.226   326  7369 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 16:41:35.226   326  7369 V AudioSystem: isOffloadSupported()
08-16 16:41:35.226   326  7369 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 16:41:35.226   326  7369 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 16:41:35.226   326  7369 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 16:41:35.226   326  7369 V AwesomePlayer: getUseOffload() = 0 
08-16 16:41:35.226   326  7369 V OMXCodec: OMXCodec::Create
08-16 16:41:35.227   326  7369 V OMXCodec: findMatchingCodecs()
,08-16 16:41:35.227   326  7369 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-16 16:41:35.227   326  7369 V OMXCodec: matchingCodecs.size()=1
08-16 16:41:35.227   326  7369 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-16 16:41:35.229   326  7369 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-16 16:41:35.229   326  7369 V LGCodecAdapter: LG Codec Adapter start
08-16 16:41:35.229   326  7369 V OMXCodec: OMXCodec Createtor
08-16 16:41:35.229   326  7369 V OMXCodec: setComponentRole
08-16 16:41:35.229   326  7369 V OMXCodec: configureCodec protected=0
08-16 16:41:35.229   326  7369 V LGCodecAdapter: called getLGCodecSpecificData
08-16 16:41:35.229   326  7369 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-16 16:41:35.229   326  7369 V LGCodecOSAL: Called LGconfigureCodecMETA
08-16 16:41:35.229   326  7369 V LGCodecOSAL: Called LGconfigureCodecMSG
08-16 16:41:35.229   326  7369 V LGCodecOSAL: Not support LGCodec
08-16 16:41:35.229   326  7369 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 16:41:35.229   326  7369 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-16 16:41:35.229   326  7369 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-16 16:41:35.229   326  7369 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-16 16:41:35.229   326  7369 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 16:41:35.229   326  7369 V AudioSystem: isOffloadSupported()
08-16 16:41:35.229   326  7369 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 16:41:35.229   326  7369 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 16:41:35.229   326  7369 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-16 16:41:35.229   326  7369 V OMXCodec: init()
08-16 16:41:35.229   326  7369 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-16 16:41:35.229   326  7369 V OMXCodec: allocateBuffers
08-16 16:41:35.230   326  7369 V OMXCodec: allocateBuffersOnPort portIndex=0
08-16 16:41:35.230   326  7369 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-16 16:41:35.230   326  7369 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on input port
08-16 16:41:35.230   326  7369 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on input port
08-16 16:41:35.230   326  7369 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
08-16 16:41:35.230   326  7369 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
08-16 16:41:35.230   326  7369 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 16:41:35.230   326  7369 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 16:41:35.230   326  7369 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on output port
08-16 16:41:35.230   326  7369 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-16 16:41:35.230   326  7369 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-16 16:41:35.230   326  7369 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040ff60 on output port
08-16 16:41:35.230   326  7369 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 16:41:35.231   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 16:41:35.231   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 16:41:35.231   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-1,6 16:41:35.231   326  7369 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 16:41:35.231   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-16 16:41:35.231   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-16 16:41:35.231   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-16 16:41:35.231   326  7369 V OMXCodec: init() mAsyncCompletion wait free! 
08-16 16:41:35.231   326  7369 V AwesomePlayer: finishAsyncPrepare_l() 
08-16 16:41:35.231   326  7369 V AudioCache: notify(0xb5474b40, 5, 0, 0)
08-16 16:41:35.231   326  7369 V AudioCache: ignored
08-16 16:41:35.231   326  7369 V AudioCache: notify(0xb5474b40, 1, 0, 0)
08-16 16:41:35.231   326  7369 V AudioCache: prepared
08-16 16:41:35.231   326  4290 V AudioCache: wait - success
08-16 16:41:35.231   326  4290 V MediaPlayerService: start
08-16 16:41:35.231   326  4290 V AwesomePlayer: play_l() 
08-16 16:41:35.231   326  4290 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-16 16:41:35.231   326  4290 V AwesomePlayer: createAudioPlayer_l
08-16 16:41:35.231   326  4290 V AwesomePlayer: seekAudioIfNecessary_l() 
08-16 16:41:35.231   326  4290 V AwesomePlayer: startAudioPlayer_l() 
08-16 16:41:35.231   326  4290 D AudioPlayer: start of Playback, useOffload 0
08-16 16:41:35.231   326  4290 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 16:41:35.231   326  4290 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 16:41:35.234   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-16 16:41:35.234   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-16 16:41:35.234   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-16 16:41:35.234   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-16 16:41:35.234   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-16 16:41:35.234   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 16:41:35.234   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048256
08-16 16:41:35.234   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 16:41:35.234   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048416
08-16 16:41:35.234   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 16:41:35.234   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048496
08-16 16:41:35.234   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 16:41:35.234   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957049696
08-16 16:41:35.234   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 16:41:35.235   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-16 16:41:35.235   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 16:41:35.235   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-16 16:41:35.235   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-16 16:41:35.235   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-16 16:41:35.235   326  7371 V OMXCodec: allocateBuffersOnPort portIndex=1
,08-16 16:41:35.235   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 16:41:35.235   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-16 16:41:35.235   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-16 16:41:35.235   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on output port
08-16 16:41:35.235   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434330 on output port
08-16 16:41:35.235   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-16 16:41:35.235   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-16 16:41:35.236   326  4290 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-16 16:41:35.236   326  4290 V AudioCache: notify(0xb5474b40, 6, 0, 0)
08-16 16:41:35.236   326  4290 V AudioCache: ignored
08-16 16:41:35.237   326  4290 V MediaPlayerService: wait for playback complete
08-16 16:41:35.237   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.237   326  7372 V AudioCache: memcpy(0xac300000, 0xb57c0000, 4096)
08-16 16:41:35.239   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.239   326  7372 V AudioCache: memcpy(0xac301000, 0xb57c0000, 4096)
08-16 16:41:35.239   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.239   326  7372 V AudioCache: memcpy(0xac302000, 0xb57c0000, 4096)
,08-16 16:41:35.240   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.240   326  7372 V AudioCache: memcpy(0xac303000, 0xb57c0000, 4096)
08-16 16:41:35.240   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.240   326  7372 V AudioCache: memcpy(0xac304000, 0xb57c0000, 4096)
,08-16 16:41:35.241   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.241   326  7372 V AudioCache: memcpy(0xac305000, 0xb57c0000, 4096)
08-16 16:41:35.242   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.242   326  7372 V AudioCache: memcpy(0xac306000, 0xb57c0000, 4096)
08-16 16:41:35.243   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.243   326  7372 V AudioCache: memcpy(0xac307000, 0xb57c0000, 4096)
08-16 16:41:35.243   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.243   326  7372 V AudioCache: memcpy(0xac308000, 0xb57c0000, 4096)
08-16 16:41:35.244   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.244   326  7372 V AudioCache: memcpy(0xac309000, 0xb57c0000, 4096)
08-16 16:41:35.245   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.245   326  7372 V AudioCache: memcpy(0xac30a000, 0xb57c0000, 4096)
08-16 16:41:35.245   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.245   326  7372 V AudioCache: memcpy(0xac30b000, 0xb57c0000, 4096)
08-16 16:41:35.246   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.246   326  7372 V AudioCache: memcpy(0xac30c000, 0xb57c0000, 4096)
08-16 16:41:35.247   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.247   326  7372 V AudioCache: memcpy(0xac30d000, 0xb57c0000, 4096)
08-16 16:41:35.247   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.247   326  7372 V AudioCache: memcpy(0xac30e000, 0xb57c0000, 4096)
08-16 16:41:35.248   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.248   326  7372 V AudioCache: memcpy(0xac30f000, 0xb57c0000, 4096)
08-16 16:41:35.249   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.249   326  7372 V AudioCache: memcpy(0xac310000, 0xb57c0000, 4096)
08-16 16:41:35.249   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.249   326  7372 V AudioCache: memcpy(0xac311000, 0xb57c0000, 4096)
08-16 16:41:35.250   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.250   326  7372 V AudioCache: memcpy(0xac312000, 0xb57c0000, 4096)
08-16 16:41:35.251   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.251   326  7372 V AudioCache: memcpy(0xac313000, 0xb57c0000, 4096)
08-16 16:41:35.251   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.251   326  7372 V AudioCache: memcpy(0xac314000, 0xb57c0000, 4096)
08-16 16:41:35.252   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.252   326  7372 V AudioCache: memcpy(0xac315000, 0xb57c0000, 4096)
,08-16 16:41:35.253   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.253   326  7372 V AudioCache: memcpy(0xac316000, 0xb57c0000, 4096)
08-16 16:41:35.253   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.253   326  7372 V AudioCache: memcpy(0xac317000, 0xb57c0000, 4096)
08-16 16:41:35.254   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.254   326  7372 V AudioCache: memcpy(0xac318000, 0xb57c0000, 4096)
08-16 16:41:35.255   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.255   326  7372 V AudioCache: memcpy(0xac319000, 0xb57c0000, 4096)
08-16 16:41:35.256   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.256   326  7372 V AudioCache: memcpy(0xac31a000, 0xb57c0000, 4096)
08-16 16:41:35.256   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.256   326  7372 V AudioCache: memcpy(0xac31b000, 0xb57c0000, 4096)
08-16 16:41:35.257   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.257   326  7372 V AudioCache: memcpy(0xac31c000, 0xb57c0000, 4096)
08-16 16:41:35.258   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.258   326  7372 V AudioCache: memcpy(0xac31d000, 0xb57c0000, 4096)
08-16 16:41:35.258   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.258   326  7372 V AudioCache: memcpy(0xac31e000, 0xb57c0000, 4096)
08-16 16:41:35.259   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.259   326  7372 V AudioCache: memcpy(0xac31f000, 0xb57c0000, 4096)
08-16 16:41:35.259   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.259   326  7372 V AudioCache: memcpy(0xac320000, 0xb57c0000, 4096)
08-16 16:41:35.260   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.260   326  7372 V AudioCache: memcpy(0xac321000, 0xb57c0000, 4096)
08-16 16:41:35.261   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.261   326  7372 V AudioCache: memcpy(0xac322000, 0xb57c0000, 4096)
08-16 16:41:35.261   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.261   326  7372 V AudioCache: memcpy(0xac323000, 0xb57c0000, 4096)
08-16 16:41:35.262   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.262   326  7372 V AudioCache: memcpy(0xac324000, 0xb57c0000, 4096)
08-16 16:41:35.262   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.262   326  7372 V AudioCache: memcpy(0xac325000, 0xb57c0000, 4096)
08-16 16:41:35.263   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.263   326  7372 V AudioCache: memcpy(0xac326000, 0xb57c0000, 4096)
08-16 16:41:35.263   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.263   326  7372 V AudioCache: memcpy(0xac327000, 0xb57c0000, 4096)
,08-16 16:41:35.263   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.263   326  7372 V AudioCache: memcpy(0xac328000, 0xb57c0000, 4096)
08-16 16:41:35.264   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.264   326  7372 V AudioCache: memcpy(0xac329000, 0xb57c0000, 4096)
08-16 16:41:35.264   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.264   326  7372 V AudioCache: memcpy(0xac32a000, 0xb57c0000, 4096)
08-16 16:41:35.264   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.264   326  7372 V AudioCache: memcpy(0xac32b000, 0xb57c0000, 4096)
08-16 16:41:35.265   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.265   326  7372 V AudioCache: memcpy(0xac32c000, 0xb57c0000, 4096)
08-16 16:41:35.266   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.266   326  7372 V AudioCache: memcpy(0xac32d000, 0xb57c0000, 4096)
08-16 16:41:35.266   326  7372 V AudioCache: write(0xb57c0000, 4096)
,08-16 16:41:35.266   326  7372 V AudioCache: memcpy(0xac32e000, 0xb57c0000, 4096)
08-16 16:41:35.268  1035  1914 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7373 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 16:41:35.269  7287  7287 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-16 16:41:35.269   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-16 16:41:35.269   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.269   326  7372 V AudioCache: memcpy(0xac32f000, 0xb57c0000, 4096)
08-16 16:41:35.269   326  7372 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 16:41:35.270   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.270   326  7372 V AudioCache: memcpy(0xac330000, 0xb57c0000, 4096)
08-16 16:41:35.270   326  7372 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 16:41:35.270   326  7372 V AudioCache: write(0xb57c0000, 4096)
08-16 16:41:35.270   326  7372 V AudioCache: memcpy(0xac331000, 0xb57c0000, 4096)
08-16 16:41:35.270   326  7372 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 16:41:35.270   326  7372 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 16:41:35.270   326  7372 V AwesomePlayer: postAudioEOS() 
08-16 16:41:35.270   326  7372 V AudioCache: write(0xb57c0000, 280)
08-16 16:41:35.270   326  7372 V AudioCache: memcpy(0xac332000, 0xb57c0000, 280)
08-16 16:41:35.272   326  7369 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-16 16:41:35.272   326  7369 V AwesomePlayer: onStreamDone
08-16 16:41:35.272   326  7369 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-16 16:41:35.272   326  7369 V AudioCache: notify(0xb5474b40, 2, 0, 0)
08-16 16:41:35.272   326  7369 V AudioCache: playback complete
08-16 16:41:35.272   326  7369 V AwesomePlayer: pause_l() 
08-16 16:41:35.272   326  7369 V AudioCache: notify(0xb5474b40, 7, 0, 0)
08-16 16:41:35.272   326  7369 V AudioCache: ignored
08-16 16:41:35.272   326  7369 V AwesomePlayer: cancelPlayerEvents
08-16 16:41:35.272   326  4290 V AudioCache: wait - success
08-16 16:41:35.272   326  4290 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-16 16:41:35.272   326  7369 D AudioPlayer: Pause Playback at 1068125
08-16 16:41:35.272   326  4290 V AwesomePlayer: reset_l() 
08-16 16:41:35.272   326  4290 V AudioCache: notify(0xb5474b40, 8, 0, 0)
08-16 16:41:35.272   326  4290 V AudioCache: ignored
08-16 16:41:35.272   326  4290 V AwesomePlayer: cancelPlayerEvents
08-16 16:41:35.272   326  4290 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-16 16:41:35.273   326  4290 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-16 16:41:35.273   326  4290 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-16 16:41:35.272  7287  7287 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 16:41:35.273   326  4290 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-16 16:41:35.273   326  4290 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 16:41:35.273   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 16:41:35.273   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 16:41:35.273   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-16 16:41:35.273   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
08-16 16:41:35.273   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIn,dex=0,bufIndex=3
08-16 16:41:35.273   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
08-16 16:41:35.273   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-16 16:41:35.273   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 0
08-16 16:41:35.273   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-16 16:41:35.273   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 0
08-16 16:41:35.273   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-16 16:41:35.273   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 16:41:35.273   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434330 on port 1
08-16 16:41:35.273   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-16 16:41:35.273   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 1
08-16 16:41:35.273   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-16 16:41:35.273   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 1
08-16 16:41:35.273   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-16 16:41:35.273   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
08-16 16:41:35.273   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 16:41:35.273   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-16 16:41:35.273   326  4290 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 16:41:35.273   326  4290 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 16:41:35.273   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-16 16:41:35.273   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-16 16:41:35.273   326  7371 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-16 16:41:35.273  7287  7287 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 16:41:35.273   326  4290 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 16:41:35.273   326  4290 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-16 16:41:35.273   326  4290 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-16 16:41:35.274   326  4290 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-16 16:41:35.274   326  4290 D AudioPlayer: AudioPlayer releasing audio source
08-16 16:41:35.274   326  4290 D AudioPlayer: AudioPlayer done releasing audio source
08-16 16:41:35.274   326  4290 V AwesomePlayer: reset_l() 
08-16 16:41:35.274   326  4290 V AwesomePlayer: cancelPlayerEvents
08-16 16:41:35.274   326  4290 V AwesomePlayer: ~AwesomePlayer call
08-16 16:41:35.275   326  4290 V AwesomePlayer: reset_l() 
08-16 16:41:35.275   326  4290 V AwesomePlayer: cancelPlayerEvents
08-16 16:41:35.275  7287  7368 V SoundPool: close(31)
08-16 16:41:35.275  7287  7368 V SoundPool: pointer = 0x9fe3f000, size = 205080, sampleRate = 48000, numChannels = 2
08-16 16:41:35.276  7218  7218 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-16 16:41:35.277  2205  2205 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 16:41:35.277  1035  2022 I ActivityManager: Killing 6747:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-16 16:41:35.295  7287  7287 V LGMDMManager: Create singleton instance
,08-16 16:41:35.336  1035  2086 W libprocessgroup: failed to open /acct/uid_10046/pid_6747/cgroup.procs: No such file or directory
,08-16 16:41:35.344  7287  7287 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 16:41:35.345  7287  7287 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-16 16:41:35.355  7287  7287 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9008
,08-16 16:41:35.365  7218  7218 D BluetoothPermissionRequest: onReceive
08-16 16:41:35.368  7218  7218 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 16:41:35.368  7218  7218 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-16 16:41:35.372  7218  7218 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 16:41:35.376  7336  7336 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-16 16:41:35.379  7336  7336 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:35.382  7336  7336 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-16 16:41:35.382  7336  7336 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 16:41:35.382  7336  7336 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 16:41:35.383  7336  7336 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:35.383  7336  7336 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-16 16:41:35.385  7373  7373 D UEI.SmartControl: Quickset Services start...
08-16 16:41:35.387  7373  7373 I UEI.SmartControl: Manufacture = LGE
08-16 16:41:35.388  7373  7373 D UEI.SmartControl: Id = LGNevo
08-16 16:41:35.389  7373  7373 D UEI.SmartControl: File observer start...
08-16 16:41:35.389  7270  7270 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-16 16:41:35.389  7373  7373 E UEI.SmartControl: IR Port is disabled: false
08-16 16:41:35.389  7373  7373 D UEI.SmartControl: Starting file observer...
08-16 16:41:35.390  7373  7373 D UEI.SmartControl: Extracting JNI libs...
08-16 16:41:35.390  7373  7373 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-16 16:41:35.464  7373  7373 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-16 16:41:35.464  7373  7373 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,08-16 16:41:35.464  7373  7373 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-16 16:41:35.490  7373  7373 I UEI.SmartControl: --- Selecting new region: 6
,08-16 16:41:35.492  7373  7373 I UEI.SmartControl: Model = LG-D855
,08-16 16:41:35.494  7373  7373 D UEI.SmartControl: QS Service created
,08-16 16:41:35.524  7373  7373 I UEI.SmartControl: Service initServices...
,08-16 16:41:35.529  7373  7373 D UEI.SmartControl: QS start get config
08-16 16:41:35.579  7373  7373 D UEI.SmartControl: Loading JNI Libs...
,08-16 16:41:35.830  7373  7373 I UEI.SmartControl: Supports setup maps: true
,08-16 16:41:35.833  7373  7373 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 16:41:35.833  7373  7373 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 16:41:35.833  7373  7373 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 16:41:35.833  7373  7373 I UEI.SmartControl: ### init IR Blaster...
08-16 16:41:35.839  7373  7373 D serial_port: Configuring serial port
08-16 16:41:35.849  7373  7373 E UEI.SmartControl: UEIBLaster setting for 616
,08-16 16:41:35.849  7373  7373 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 16:41:35.853  7373  7373 I UEI.SmartControl: configuring settings for MAXQ616
08-16 16:41:35.853  7373  7373 I UEI.SmartControl: Get version...
08-16 16:41:35.869  7373  7398 D UEI.SmartControl: serial port data available: 21
,08-16 16:41:35.900  7373  7373 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-16 16:41:35.900  7373  7373 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 16:41:35.900  7373  7373 I UEI.SmartControl: QS saving settings...,
08-16 16:41:35.903  7373  7373 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 16:41:35.921  7373  7398 D UEI.SmartControl: serial port data available: 4
,08-16 16:41:35.955  7373  7401 I UEI.SmartControl: Device manager: loading config....
08-16 16:41:35.956  7373  7373 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-16 16:41:35.956  7373  7401 D UEI.SmartControl: ----------- loading internal config...
08-16 16:41:35.960  7373  7373 E UEI.SmartControl: Services init done
08-16 16:41:35.960  7373  7373 D UEI.SmartControl: QS Service init finished
08-16 16:41:35.961  7373  7373 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 16:41:35.961  7373  7373 D UEI.SmartControl: QS Service version code: 201091
,08-16 16:41:35.962  7373  7373 D UEI.SmartControl: Service requested: Control
08-16 16:41:35.968  7373  7401 E UEI.SmartControl: Loading SETTINGS...
08-16 16:41:35.973  7373  7373 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-16 16:41:35.974  7373  7401 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 16:41:35.976  7287  7287 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-16 16:41:35.977  7373  7388 I UEI.SmartControl: ------ IControl API: 11
08-16 16:41:35.977  7373  7373 D UEI.SmartControl: Internal service binding...
08-16 16:41:35.978  7373  7388 I UEI.SmartControl: Registering callback...
08-16 16:41:35.979  7373  7388 I UEI.SmartControl: ------ IControl API: 19
08-16 16:41:35.980  7373  7388 I UEI.SmartControl: Registering Services Ready callback...
08-16 16:41:35.993  7373  7400 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-16 16:41:35.993  7373  7400 D UEI.SmartControl: -----service ready thread exits
08-16 16:41:35.993  7287  7303 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-16 16:41:35.994  7287  7366 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-16 16:41:35.994  7287  7366 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,08-16 16:41:35.994  7287  7287 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-16 16:41:35.995  7287  7287 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-16 16:41:35.996  7373  7389 I UEI.SmartControl: ------ IControl API: 8
08-16 16:41:35.998  7287  7287 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-16 16:41:35.998  7287  7287 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-16 16:41:35.999  7287  7287 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-16 16:41:35.999  7287  7287 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-16 16:41:36.000  7287  7287 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-16 16:41:36.000  7287  7287 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-16 16:41:36.002  7287  7287 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-16 16:41:36.004  7287  7287 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 16:41:36.005  7287  7287 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 16:41:36.007  7287  7287 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 16:41:36.007  7287  7287 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 16:41:36.008  7287  7287 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-16 16:41:36.010  7287  7287 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-16 16:41:36.011  7287  7287 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-16 16:41:36.013  7287  7287 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471358496012]
08-16 16:41:36.018  7287  7287 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-16 16:41:36.023  1035  2053 I ActivityManager: Killing 6774:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-16 16:41:36.115  1035  2053 I ActivityManager: Killing 6813:com.android.providers.calendar/u0a14 (adj 15): empty #18
,08-16 16:41:36.185  1035  2077 I art     : Explicit concurrent mark sweep GC freed 50618(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 42MB/64MB, paused 2.274ms total 140.219ms
,08-16 16:41:36.190  7287  7403 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
08-16 16:41:36.206  1035  1982 W libprocessgroup: failed to open /acct/uid_10014/pid_6813/cgroup.procs: No such file or directory
,08-16 16:41:36.214  1035  1956 W libprocessgroup: failed to open /acct/uid_10005/pid_6774/cgroup.procs: No such file or directory
08-16 16:41:36.214  7287  7287 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-16 16:41:36.215  7287  7287 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 16:41:36.215  7287  7287 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-16 16:41:36.216  7287  7287 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
,08-16 16:41:36.216  7287  7287 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-16 16:41:36.216  7287  7287 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-16 16:41:36.217  7287  7287 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-16 16:41:36.227  7287  7287 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
08-16 16:41:36.827  1035  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 16:41:36.844  1035  1117 D Tethering: MasterInitialState.processMessage what=3
08-16 16:41:36.856  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:41:36.862  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:36.863  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:36.864  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 16:41:36.865  1035  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 16:41:36.868  6342  6342 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-16 16:41:36.873  6342  7239 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 16:41:36.882  1035  1117 D Tethering: MasterInitialState.processMessage what=3
,08-16 16:41:36.889  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:36.889  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:36.891  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:36.898  5763  5763 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 16:41:36.908  5763  5763 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 16:41:36.940  2205  2205 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 16:41:36.959  6888  6888 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 16:41:36.959  6888  6888 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 16:41:36.961  6888  6888 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 16:41:36.961  6888  6888 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 16:41:36.967  6888  6888 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 16:41:36.977  6888  6888 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1356dadd
08-16 16:41:36.977  6888  6888 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 16:41:36.978  6888  6888 D AppUp4:CustFacade: isPhone : true
08-16 16:41:36.978  6888  6888 D AppUp4:CustModeStarterReceiver: begin check event
08-16 16:41:36.979  6888  6888 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-16 16:41:36.979  6888  6888 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-16 16:41:36.980  6888  6908 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-16 16:41:36.980  6888  6908 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-16 16:41:36.980  6888  6908 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-16 16:41:36.984  4627  4627 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 16:41:36.985  4627  4627 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 16:41:36.986  4627  4627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 16:41:36.989  4627  4627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 16:41:37.007  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 16:41:37.026  4627  7416 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 16:41:37.045  4627  7425 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 16:41:37.045  4627  7425 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 16:41:37.052  1035  2022 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7433 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-16 16:41:37.057  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:41:37.058  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 16:41:37.107  7433  7433 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 16:41:37.108  7433  7433 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 16:41:37.109  7433  7433 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 16:41:37.110  7433  7433 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 16:41:37.196  7433  7433 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 16:41:37.216  7433  7433 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-16 16:41:37.253  7433  7433 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 16:41:37.285  7433  7433 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 16:41:37.285  7433  7433 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 16:41:37.418  7433  7433 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 16:41:37.463  3296  3296 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 16:41:37.463  3296  3296 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 16:41:37.463  3296  3296 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-16 16:41:37.468  7433  7433 I HubEmail: JNI_OnLoad()
08-16 16:41:37.468  7433  7433 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 16:41:37.468  7433  7433 I HubEmail: registerNatives()
08-16 16:41:37.468  7433  7433 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 16:41:37.468  7433  7433 I HubEmail: registerNativeMethods()
08-16 16:41:37.468  7433  7433 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 16:41:37.469  7433  7433 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-16 16:41:37.508  1035  1982 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7467 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-16 16:41:37.519  7433  7464 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:37.537  7311  7466 V FormManager: Network unavailable.
,08-16 16:41:37.542  7311  7466 V FormManager: Network unavailable.
08-16 16:41:37.547  7311  7465 W FormManager: Network not available. Please check & try again.
08-16 16:41:37.550  1035  2022 I ActivityManager: Killing 6840:com.google.android.talk/u0a72 (adj 15): empty #17
,08-16 16:41:37.638  1035  1050 W libprocessgroup: failed to open /acct/uid_10072/pid_6840/cgroup.procs: No such file or directory
,08-16 16:41:37.771  7467  7467 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 16:41:37.771  7467  7467 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 16:41:37.775  7467  7467 D PhoneMonitor: Register our PhoneStateListener
,08-16 16:41:37.797  7467  7467 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-16 16:41:37.800  7467  7467 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 16:41:37.824  7467  7467 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-16 16:41:37.825  7467  7467 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-16 16:41:37.827  7467  7467 D TelephonyAutoProfiling: [parse] Load xml
08-16 16:41:37.835  7467  7467 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-16 16:41:37.835  7467  7467 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-16 16:41:37.835  7467  7467 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-16 16:41:37.835  7467  7467 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-16 16:41:37.835  7467  7467 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-16 16:41:37.835  7467  7467 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-16 16:41:37.836  7467  7467 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-16 16:41:37.836  7467  7467 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-16 16:41:37.836  7467  7467 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-16 16:41:37.836  7467  7467 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-16 16:41:37.836  7467  7467 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-16 16:41:37.836  7467  7467 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-16 16:41:37.836  7467  7467 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-16 16:41:37.836  7467  7467 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-16 16:41:37.836  7467  7467 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-16 16:41:37.836  7467  7467 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-16 16:41:37.837  7467  7467 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-16 16:41:37.856  7467  7467 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-16 16:41:37.870  1035  1051 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7493 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 16:41:37.873  1035  1051 I ActivityManager: Killing 6910:com.android.contacts/u0a19 (adj 15): empty #17
08-16 16:41:37.907  1035  1982 W libprocessgroup: failed to open /acct/uid_10019/pid_6910/cgroup.procs: No such file or directory
,08-16 16:41:38.105  1035  2053 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7511 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-16 16:41:38.105  1035  2053 I ActivityManager: Killing 6936:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-16 16:41:38.208  1035  2077 W libprocessgroup: failed to open /acct/uid_10027/pid_6936/cgroup.procs: No such file or directory
,08-16 16:41:38.323  1035  2053 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7528 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 16:41:38.324  1035  2053 I ActivityManager: Killing 5923:com.android.vending/u0a44 (adj 15): empty #17
,08-16 16:41:38.386  1035  1720 W libprocessgroup: failed to open /acct/uid_10044/pid_5923/cgroup.procs: No such file or directory
,08-16 16:41:38.425  7528  7528 I art     : Almond Protected OAT
,08-16 16:41:38.483  7528  7528 D WeatherApplication: removeAccount
,08-16 16:41:38.485  7528  7528 D WeatherApplication: Account.length = 0
,08-16 16:41:38.485  7528  7528 E WeatherApplication: OPERATOR:OPEN
,08-16 16:41:38.491  7528  7528 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:41:38
,08-16 16:41:38.494  7528  7528 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 16:41:38.494  7528  7528 D Weather.Utils: 2 : All the weather widget is gone.
08-16 16:41:38.496  7528  7528 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 16:41:38.499  7528  7528 D WeatherAncestor: connectivity changed - connection : true
08-16 16:41:38.501  7528  7528 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-16 16:41:38.513  7528  7528 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-16 16:41:38.513  7528  7528 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 16:41:38.514  7528  7528 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-16 16:41:38.536  7528  7528 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 16:41:38.537  7528  7528 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:41:38
,08-16 16:41:38.604  1035  1982 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7546 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 16:41:38.612  1035  1982 I ActivityManager: Killing 6956:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-16 16:41:38.626   354   354 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 468us total 22.054ms
,08-16 16:41:38.648   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 562us total 20.639ms
,08-16 16:41:38.670   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 413us total 21.688ms
,08-16 16:41:38.678  1035  1051 W libprocessgroup: failed to open /acct/uid_10080/pid_6956/cgroup.procs: No such file or directory
08-16 16:41:38.773   278   339 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-16 16:41:38.773   278   339 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 16:41:38.773   278   339 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 16:41:38.775  1035  1792 D WifiServiceImplEx: setWifiEnabled: true pid=7049, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 16:41:38.776  1035  1792 D WifiService: setWifiEnabled: true pid=7049, uid=10118
08-16 16:41:38.776  1035  1792 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 16:41:38.778  7546  7564 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 16:41:38.781   278   339 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 16:41:38.781   278   339 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 16:41:38.781   278   339 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 16:41:38.782  7546  7564 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 16:41:38.789   278   339 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 16:41:38.789   278   339 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 16:41:38.789   278   339 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 16:41:38.790  7546  7568 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 16:41:38.793   278   339 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 16:41:38.793   278   339 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 16:41:38.793   278   339 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 16:41:38.796  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 16:41:38.796  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 16:41:38.796  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-16 16:41:38.797  1035  1525 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-16 16:41:38.797  1035  1525 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-16 16:41:38.798  7546  7568 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 16:41:38.798  1035  1525 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 16:41:38.798  1035  1525 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 16:41:38.798  1035  1525 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 16:41:38.798  1035  1525 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 16:41:38.798  1035  1525 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 16:41:38.798  1035  1525 E WifiHW  : unknown target_country: EU , set to default
08-16 16:41:38.798  1035  1525 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-16 16:41:38.798  1035  1525 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-16 16:41:38.798  1035  1525 I WifiUtil: gEnableBmps=1
08-16 16:41:38.836  1035  1521 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 16:41:38.836  1035  1521 D LGWifiP2pService: DefaultState{ when=-4ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:39.032  7546  7546 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 16:41:39.063  7546  7546 I LibraryLoader: Loading: webviewchromium
,08-16 16:41:39.069  7546  7546 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 1106-1114)
,08-16 16:41:39.070  7546  7546 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 16:41:39.078  7546  7546 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1e94c105}
,08-16 16:41:39.079  7546  7546 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 16:41:39.080  7546  7546 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 16:41:39.095  7546  7546 I BrowserStartupController: Initializing chromium process, renderers=0
08-16 16:41:39.097  7546  7546 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 16:41:39.115  7546  7546 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-16 16:41:39.119  7546  7546 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-16 16:41:39.120  7546  7546 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-16 16:41:39.128   326  1367 V AudioPolicyService: registerClient() client 0xb557c040, uid 10093
08-16 16:41:39.130  7546  7589 W AudioManagerAndroid: Requires BLUETOOTH permission
08-16 16:41:39.162  7546  7546 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 16:41:39.162  7546  7546 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 16:41:39.162  7546  7546 I Adreno-EGL: Build Date: 12/12/14 금
08-16 16:41:39.162  7546  7546 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 16:41:39.162  7546  7546 I Adreno-EGL: Remote Branch: 
08-16 16:41:39.162  7546  7546 I Adreno-EGL: Local Patches: 
08-16 16:41:39.162  7546  7546 I Adreno-EGL: Reconstruct Branch: 
,08-16 16:41:39.268  7546  7546 I NSApplication: Starting up...
,08-16 16:41:39.318  1035  1050 I ActivityManager: Killing 7240:com.lge.sync/1000 (adj 15): empty #17
,08-16 16:41:39.358  1035  1956 W libprocessgroup: failed to open /acct/uid_1000/pid_7240/cgroup.procs: No such file or directory
,08-16 16:41:39.371  6342  6342 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-16 16:41:39.374  6342  7239 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 16:41:39.405  2205  2205 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 16:41:39.424  6888  6888 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 16:41:39.424  6888  6888 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 16:41:39.424  6888  6888 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 16:41:39.424  6888  6888 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 16:41:39.426  6888  6888 I AppUp4:CustModeStarterReceiver: onReceive
08-16 16:41:39.430  6888  6888 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1356dadd
08-16 16:41:39.430  6888  6888 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 16:41:39.430  6888  6888 D AppUp4:CustFacade: isPhone : true
08-16 16:41:39.431  6888  6888 D AppUp4:CustModeStarterReceiver: begin check event
08-16 16:41:39.431  6888  6888 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 16:41:39.435  4627  4627 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 16:41:39.435  4627  4627 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 16:41:39.437  4627  4627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 16:41:39.439  4627  4627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 16:41:39.448  7433  7433 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 16:41:39.448  4627  7612 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 16:41:39.458  4627  7613 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 16:41:39.458  4627  7613 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 16:41:39.471  3296  3296 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 16:41:39.471  3296  3296 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-16 16:41:39.471  3296  3296 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-16 16:41:39.475  7467  7467 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 16:41:39.476  7467  7467 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 16:41:39.497  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 16:41:39.497  1035  1117 D Tethering: InitialState.processMessage what=4
08-16 16:41:39.498  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 16:41:39.500   319   878 D SoftapController: Softap fwReload - Ok
08-16 16:41:39.502  1035  1525 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (697ms)
08-16 16:41:39.507   319   878 D CommandListener: Setting iface cfg
08-16 16:41:39.507   319   878 D CommandListener: Trying to bring down wlan0
08-16 16:41:39.508   319   878 D CommandListener: Clearing all IP addresses on wlan0
08-16 16:41:39.510  1035  1525 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-16 16:41:39.511  1035  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 16:41:39.511  1035  1525 E WifiStateMachine: useWiFiOffloading() : false
08-16 16:41:39.511  1035  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 16:41:39.512  7433  7614 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:39.514  7528  7528 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:41:39
08-16 16:41:39.516  1035  1525 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 16:41:39.516  1035  1525 D WifiMonitor: connecting to supplicant
08-16 16:41:39.505  7628  7628 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 16:41:39.505  7628  7628 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 16:41:39.521  1959  1959 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-16 16:41:39.522  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:39.525  7528  7528 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 16:41:39.525  7528  7528 D Weather.Utils: 2 : All the weather widget is gone.
08-16 16:41:39.525  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-16 16:41:39.528  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:41:39.528  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:39.529  7311  7617 W FormManager: Network not available. Please check & try again.
08-16 16:41:39.530  7528  7528 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 16:41:39.530  7528  7528 D WeatherAncestor: connectivity changed - connection : true
08-16 16:41:39.530  7528  7528 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1ae7e59e
08-16 16:41:39.531  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:39.531  7311  7618 V FormManager: Network unavailable.
08-16 16:41:39.531  7528  7528 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 16:41:39.531  7528  7528 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 16:41:39.531  7528  7528 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 16:41:39.531  7528  7528 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 16:41:39.532  7528  7528 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:41:39
08-16 16:41:39.537  7311  7618 V FormManager: Network unavailable.
08-16 16:41:39.542  7628  7628 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-16 16:41:39.564  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-16 16:41:39.564  7218  7218 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 16:41:39.564  7218  7218 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 16:41:39.564  7218  7218 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 16:41:39.564  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-16 16:41:39.566  7218  7218 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 16:41:39.566  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 16:41:39.566  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 16:41:39.566  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 16:41:39.566  7218  7218 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 16:41:39.567  7218  7218 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 16:41:39.575  7628  7628 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 16:41:39.576  7628  7628 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-16 16:41:39.609  1035  1720 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7636 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 16:41:39.614  7311  7633 W FormManager: Network not available. Please check & try again.
08-16 16:41:39.618  7311  7634 V FormManager: Network unavailable.
08-16 16:41:39.621  7311  7634 V FormManager: Network unavailable.
,08-16 16:41:39.659  7628  7628 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 16:41:39.668  7636  7636 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 16:41:39.678  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 16:41:39.681  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 16:41:39.682  1035  1051 I ActivityManager: Killing 7192:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-16 16:41:39.686  7628  7628 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-16 16:41:39.690  1035  1525 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-16 16:41:39.691  1035  1525 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-16 16:41:39.691  1035  1525 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 16:41:39.692  1035  1525 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 16:41:39.693  1035  1525 E WifiStateMachine:  SupplicantStartingState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 16:41:39.693  1035  1525 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 16:41:39.694  1035  1525 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 16:41:39.694  1035  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 16:41:39.695  1035  1525 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 16:41:39.695  1035  1525 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 16:41:39.695  1035  1525 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 16:41:39.696  1035  1525 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 16:41:39.696  1035  1525 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-16 16:41:39.701  7628  7628 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-16 16:41:39.701  1035  7655 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-16 16:41:39.701  1035  7655 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-16 16:41:39.726  1035  7655 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,08-16 16:41:39.726  7628  7628 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-16 16:41:39.726  1035  7655 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 16:41:39.726  1035  7655 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-16 16:41:39.726  1035  7655 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 16:41:39.727  1035  7655 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,08-16 16:41:39.727  1035  7655 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-16 16:41:39.744  1035  1913 W libprocessgroup: failed to open /acct/uid_10037/pid_7192/cgroup.procs: No such file or directory
08-16 16:41:39.745  1035  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 16:41:39.745  1035  1525 E WifiStateMachine: useWiFiOffloading() : false
08-16 16:41:39.745  1035  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-16 16:41:39.750  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 16:41:39.750  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:39.750  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:39.751  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:39.751  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 16:41:39.751  1035  1525 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 16:41:39.753  1959  1959 D WfdService: Waiting for WifiP2p enabling
08-16 16:41:39.754  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:39.751  1035  1525 D WifiNative-wlan0: SET update_config 1: returned true
08-16 16:41:39.754  1035  1525 D WifiConfigStore: Loading config and enabling all networks 
08-16 16:41:39.754  1035  1525 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 16:41:39.755  1035  1525 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 16:41:39.756  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 16:41:39.756  1035  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-16 16:41:39.764  1035  1525 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-16 16:41:39.776  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:39.776  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:41:39.776  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:39.776  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:39.776  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:41:39.776  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:41:39.776  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:41:39.776  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:41:39.776  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:41:39.776  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:39.776  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:41:39.778  1035  1525 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 16:41:39.778  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:39.778  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:41:39.778  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:39.778  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:39.778  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:41:39.778  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:41:39.778  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:41:39.778  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:41:39.778  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:41:39.778  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:39.778  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:41:39.778  1035  1525 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-16 16:41:39.779  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 16:41:39.779  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:41:39.779  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:39.779  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:39.779  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:41:39.779  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:41:39.779  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:41:39.779  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:41:39.779  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:41:39.779  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:39.779  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:41:39.781  1035  1525 D WifiStateMachine: enableVerboseLogging : level 2
08-16 16:41:39.781  1035  1525 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-16 16:41:39.781  1035  1525 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 16:41:39.781  1035  1525 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 16:41:39.782  1035  1525 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 16:41:39.782  1035  1525 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-16 16:41:39.783  1035  1525 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 16:41:39.783  1035  1525 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
,08-16 16:41:39.783  1035  1525 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 16:41:39.783  1035  1525 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-16 16:41:39.784  7636  7636 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 16:41:39.784  1035  1525 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
,08-16 16:41:39.784  1035  1525 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-16 16:41:39.785  1035  1525 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 16:41:39.785  1035  1525 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-16 16:41:39.785  1035  1525 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-16 16:41:39.787  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 16:41:39.789  1035  1525 D WifiStateMachine: Setting OUI to DA-A1-19
,08-16 16:41:39.789  1035  1525 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-16 16:41:39.789  1035  1525 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 16:41:39.789  1035  1525 D WifiNative-HAL: Setting external_sim to 1
08-16 16:41:39.789  1035  1525 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 16:41:39.790  1959  1959 D WfdsService: Supplicant Connection state is changed : true
08-16 16:41:39.790  1035  1525 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 16:41:39.790  1035  1525 I WifiNative-HAL: startHal
08-16 16:41:39.790  1959  2274 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 16:41:39.790  1959  2274 D WfdsService: Set the WFDS Monitor: true
08-16 16:41:39.790  1035  1525 D wifi    : setting scan oui 0xaf6f1fa0
08-16 16:41:39.790  1959  2274 D WfdsMonitor: WfdsMonitorThread create
08-16 16:41:39.790  1959  2274 D WfdsMonitor: WFDS Monitor is created and started
08-16 16:41:39.790  1959  2274 D WfdsService: WiFi: Supplicant connection re-established
08-16 16:41:39.790  1035  1525 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 16:41:39.790  1035  1525 I WifiNative-HAL: startHal
08-16 16:41:39.790  1035  1525 D wifi    : setting scan oui 0xaf6f1fa0
08-16 16:41:39.791  1035  1525 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 16:41:39.792  1959  7659 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 16:41:39.792  1035  1525 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-16 16:41:39.792  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 16:41:39.792  7628  7628 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 16:41:39.792  1959  7659 E CtrlSupplicant: Succeed to open control connection
08-16 16:41:39.792  1959  7659 E CtrlSupplicant: Succeed to open monitor connection
08-16 16:41:39.792  1959  7659 D WfdsMonitor: Supplicant connection established
08-16 16:41:39.793  1035  1525 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
,08-16 16:41:39.793  1959  2274 D WfdsService: Connected to the supplicant for wfds
08-16 16:41:39.793  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 16:41:39.793  7628  7628 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 16:41:39.793  1035  1525 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
,08-16 16:41:39.793  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-16 16:41:39.793  7628  7628 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-16 16:41:39.794  7311  7657 W FormManager: Network not available. Please check & try again.
08-16 16:41:39.794  1035  1525 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 16:41:39.794  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 16:41:39.794  7628  7628 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 16:41:39.794  1035  1525 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
,08-16 16:41:39.794  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 16:41:39.794  7628  7628 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 16:41:39.795  1035  1525 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 16:41:39.795  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 16:41:39.795  7628  7628 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-16 16:41:39.796  1035  1525 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-16 16:41:39.797  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
,08-16 16:41:39.797  7628  7628 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 16:41:39.798  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 16:41:39.799  1035  1525 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 16:41:39.801  1035  1525 E WifiNative: : [371,831,947 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-16 16:41:39.801  1035  1525 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 16:41:39.803  1035  1525 D WifiNative-wlan0: RECONNECT: returned true
08-16 16:41:39.803  1035  1525 D WifiNative-wlan0: doString: [STATUS]
08-16 16:41:39.803  1035  7655 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 16:41:39.803  1035  7655 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 16:41:39.804  1035  1525 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 16:41:39.804  1035  1525 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 16:41:39.804  1035  1525 D WifiNative-wlan0: SET ps 1: returned true
08-16 16:41:39.804  1035  1521 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:39.805  7311  7658 V FormManager: Network unavailable.
08-16 16:41:39.806   319   878 D CommandListener: Setting iface cfg
08-16 16:41:39.806   319   878 D CommandListener: Trying to bring up p2p0
08-16 16:41:39.807  1035  1521 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 16:41:39.807  1035  1521 D LGWifiP2pService: P2pEnablingState
08-16 16:41:39.807  1035  1521 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:39.807  1035  1521 D LGWifiP2pService: P2p socket connection successful
08-16 16:41:39.807  1035  1521 D LGWifiP2pService: P2pEnabledState
08-16 16:41:39.809  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 16:41:39.809  1035  1035 D RttService: SCAN_AVAILABLE : 3
08-16 16:41:39.809  1035  1543 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:39.809  1035  1543 I WifiNative-HAL: startHal
08-16 16:41:39.809  1035  1543 D wifi    : getting scan capabilities on interface[1] = 0xaf6f1fa0
08-16 16:41:39.809  1035  1543 D wifi    : failed to get capabilities : -3
08-16 16:41:39.809  1035  1543 E WifiScanningService: could not get scan capabilities
08-16 16:41:39.809  1035  1544 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 16:41:39.811  1035  1525 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-16 16:41:39.811  1035  1521 D LGWifiP2pService: sending p2p connection changed broadcast
08-16 16:41:39.812  1035  1525 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 16:41:39.812  1035  1521 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-16 16:41:39.812  1035  1525 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 16:41:39.813  1035  1525 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-16 16:41:39.813  1035  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=371845  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 16:41:39.813  1959  1959 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 16:41:39.813  1959  1959 D WfdsService: WifiP2pState is changed : true
08-16 16:41:39.813  1035  1521 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-16 16:41:39.814  1959  2274 D WfdsService: Receive the WFDS_ENABLE Method
08-16 16:41:39.814  1959  2274 D WfdsService: Set the WFDS Monitor: true
08-16 16:41:39.814  1959  2274 D WfdsService: Connected to the supplicant for wfds
08-16 16:41:39.814  1959  2274 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 16:41:39.814  7628  7628 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-16 16:41:39.814  1959  2274 D WfdsService: selectPreferredScanChannel [36]
08-16 16:41:39.814  1959  2274 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-16 16:41:39.814  1959  1959 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-16 16:41:39.815  1959  1959 D WfdsService: isConnected: false
08-16 16:41:39.815  1035  1521 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 16:41:39.816  1035  1521 D WifiNative-p2p0: SET device_name G3: returned true
08-16 16:41:39.816  1035  1521 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 16:41:39.816  1035  1521 D LGWifiP2pService: before postfix = G3
08-16 16:41:39.816  1035  1521 D WifiServerServiceExt: postfix byte check : 2
08-16 16:41:39.816  1035  1521 D LGWifiP2pService: after postfix = G3
08-16 16:41:39.816  1035  1521 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-16 16:41:39.816  1035  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=371849  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 16:41:39.817  1035  1525 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-16 16:41:39.817  1035  1521 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 16:41:39.818  1035  1525 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 16:41:39.818  1035  1521 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-16 16:41:39.818  1035  1521 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 16:41:39.818  1035  1521 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 16:41:39.819  1035  1525 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 16:41:39.819  1035  1521 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 16:41:39.819  1035  1521 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-16 16:41:39.819  1035  1525 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 16:41:39.819  7628  7628 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 16:41:39.819  1035  1521 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 16:41:39.819  1035  1521 D WifiNative-HAL: p2pGetDeviceAddress
08-16 16:41:39.820  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:41:39.820  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 16:41:39.820  1035  1521 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-16 16:41:39.821  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:39.821  1035  1525 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 16:41:39.822  1035  1525 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 16:41:39.822  1035  1525 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-16 16:41:39.822  1035  1525 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-16 16:41:39.822  7628  7628 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 16:41:39.823  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:39.823  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:39.823  1035  1521 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-16 16:41:39.823  1035  1521 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 16:41:39.823  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 16:41:39.824  1035  1521 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 16:41:39.824  1035  1521 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-16 16:41:39.824  1959  1959 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 16:41:39.825  1959  1959 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 16:41:39.825  1959  1959 D WfdsService: Update P2p Interface State: 3
08-16 16:41:39.825  1035  1525 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 16:41:39.825  7311  7658 V FormManager: Network unavailable.
08-16 16:41:39.825  1035  1525 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 16:41:39.826  1035  1525 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 16:41:39.826  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-16 16:41:39.826  1035  1521 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 16:41:39.826  1035  1521 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 16:41:39.826  1035  1521 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 16:41:39.826  1035  1521 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-16 16:41:39.829  4627  4627 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 16:41:39.829  4627  4627 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 16:41:39.831  4627  4627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 16:41:39.833  4627  4627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 16:41:39.839  4627  7660 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 16:41:39.840  1035  1521 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 16:41:39.841  7628  7628 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 16:41:39.840  1035  1521 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-16 16:41:39.842  7628  7628 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 16:41:39.842  1035  7655 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
,08-16 16:41:39.842  1035  7655 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 16:41:39.842  1035  7655 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 16:41:39.842  1035  7655 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 16:41:39.842  7628  7628 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 16:41:39.842  7628  7628 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:41:39.843  1035  7655 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 16:41:39.843  1035  7655 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:41:39.843  1035  7655 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:41:39.843  1035  7655 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:41:39.843  7628  7628 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:41:39.843  1035  7655 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 16:41:39.843  1035  7655 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:41:39.843  1035  7655 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:41:39.843  1035  7655 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:41:39.844  1959  7659 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 16:41:39.844  1959  7659 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 16:41:39.844  4627  7662 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 16:41:39.844  1035  1525 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-16 16:41:39.844  4627  7662 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 16:41:39.845  1035  1525 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 16:41:39.845  1035  1525 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 16:41:39.846  1035  1525 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 16:41:39.846  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 16:41:39.846  7628  7628 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 16:41:39.846  7628  7628 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 16:41:39.846  1035  7655 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 16:41:39.846  1035  7655 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 16:41:39.846  1035  7655 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 16:41:39.846  1035  7655 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 16:41:39.847  1035  1525 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 16:41:39.847  1035  1525 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-16 16:41:39.847  1035  1525 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-16 16:41:39.847  1035  1525 D WifiNative-wlan0: doBoolean: SCAN
08-16 16:41:39.848  1035  1525 D WifiNative-wlan0: SCAN: returned false
,08-16 16:41:39.848  1035  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=371880  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-16 16:41:39.887  1035  1914 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7663 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-16 16:41:39.888  1035  1521 D LGWifiP2pService: InactiveState
08-16 16:41:39.888  1035  1521 D LGWifiP2pService: InactiveState{ when=-62ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:39.888  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-62ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:39.888  1035  1521 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-16 16:41:39.889  7628  7628 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-16 16:41:39.889  7628  7628 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 16:41:39.890  7628  7628 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 16:41:39.890  1035  7655 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 16:41:39.890  1035  7655 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 16:41:39.890  7628  7628 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:41:39.890  1035  7655 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 16:41:39.891  1035  7655 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 16:41:39.891  1035  7655 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 16:41:39.891  1035  7655 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:41:39.891  1035  7655 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:41:39.891  1035  7655 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:41:39.891  1035  1521 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 16:41:39.891  1035  1521 D LGWifiP2pService: InactiveState{ when=-47ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:39.891  7628  7628 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:41:39.891  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-47ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:39.891  1035  1521 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:39.891  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:39.891  1035  1521 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:39.892  1035  1521 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:39.892  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:39.892  1035  1521 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:39.892  1035  1521 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:39.892  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:39.892  1035  1521 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:39.892  1035  1521 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:39.892  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:39.892  1035  1521 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:39.892  1035  1035 E WifiServerServiceExt: No p2p device connected
08-16 16:41:39.893  1959  2274 W WfdsService: DefaultState - msg [9441285] is not handled
08-16 16:41:39.893  1035  7655 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 16:41:39.893  1035  7655 E WifiMonitor: WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:41:39.893  ,1035  7655 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:41:39.893  1035  7655 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:41:39.893  1959  7659 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 16:41:39.893  1959  7659 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 16:41:39.893  1959  7659 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 16:41:39.894  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:41:39.894  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 16:41:39.895  1035  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=371927  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 16:41:39.896  1035  1525 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 16:41:39.898  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:39.898  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:39.898  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 16:41:39.899  1035  1525 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 16:41:39.899  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:39.899  1035  1525 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 16:41:39.900  1035  1525 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 16:41:39.901  1035  1525 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 16:41:39.903  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 16:41:39.903  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-16 16:41:39.904  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 16:41:39.904  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-16 16:41:40.007  7663  7663 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 16:41:40.007  7663  7663 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-16 16:41:40.017  7663  7663 V [BNRBootReceiver]: Boot Receiver Return
,08-16 16:41:40.018  7663  7663 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-16 16:41:40.022  6342  6342 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 16:41:40.050  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 16:41:40.064  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 16:41:40.082  7287  7287 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 16:41:40.082  7287  7287 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 16:41:40.084  7287  7287 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 16:41:40.089  6342  6342 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:41:40.105  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 16:41:40.113  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 16:41:40.128  7287  7287 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 16:41:40.129  7287  7287 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 16:41:40.132  7287  7287 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 16:41:40.135  1035  1982 I ActivityManager: Killing 7270:com.lge.settings.easy/1000 (adj 15): empty #17
,08-16 16:41:40.193  1035  1720 W libprocessgroup: failed to open /acct/uid_1000/pid_7270/cgroup.procs: No such file or directory
,08-16 16:41:40.418  7628  7628 E wpa_supplicant: USIM:  scard_init function
08-16 16:41:40.419  7628  7628 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-16 16:41:40.425  1035  7655 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-16 16:41:40.426  1035  7655 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 16:41:40.426  1035  7655 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-16 16:41:40.426  1035  7655 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-16 16:41:40.426  1035  7655 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 16:41:40.426  1035  7655 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-16 16:41:40.426  1035  7655 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-16 16:41:40.428  1035  1525 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-16 16:41:40.428  1035  1525 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-16 16:41:40.429  1035  1525 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-16 16:41:40.429  1035  1525 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-16 16:41:40.429  1035  1525 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-16 16:41:40.446  1035  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=372478  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-16 16:41:40.456  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:41:40.456  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 16:41:40.458  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:40.461  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:40.462  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:40.462  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-16 16:41:40.465  1035  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=372498  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 16:41:40.467  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 16:41:40.467  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-16 16:41:40.469  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-16 16:41:40.483  7218  7218 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-16 16:41:40.491  6342  6342 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 16:41:40.508  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 16:41:40.522  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 16:41:40.530  7287  7287 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 16:41:40.530  7287  7287 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 16:41:40.530  7287  7287 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 16:41:40.536  7628  7628 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-16 16:41:40.541  1035  7655 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 16:41:40.541  1035  7655 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-16 16:41:40.541  1035  7655 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 16:41:40.541  1035  7655 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 16:41:40.541  1035  7655 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 16:41:40.542  1035  7655 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 16:41:40.544  7628  7628 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 16:41:40.544  7628  7628 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-16 16:41:40.551  1035  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=372583  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-16 16:41:40.552  1035  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=372584  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 16:41:40.552  1035  1525 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=372584
08-16 16:41:40.552  1035  1525 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=372585
08-16 16:41:40.553  1035  1525 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=372585
08-16 16:41:40.553  1035  1525 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=372585
08-16 16:41:40.553  1035  1525 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=372586
,08-16 16:41:40.558  1035  7655 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 16:41:40.558  1035  7655 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 16:41:40.559  1035  7655 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-16 16:41:40.559  1035  7655 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 16:41:40.559  1035  7655 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 16:41:40.559  1035  7655 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 16:41:40.559  1035  7655 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 16:41:40.560  1035  7655 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 16:41:40.560  1035  7655 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 16:41:40.560  1035  7655 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-16 16:41:40.571  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 16:41:40.576  1035  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=372608  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 16:41:40.580  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 16:41:40.580  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 16:41:40.581  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:40.582  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:40.582  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:40.582  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 16:41:40.583  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 16:41:40.583  7218  7218 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 16:41:40.583  7218  7218 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 16:41:40.583  7218  7218 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 16:41:40.584  1035  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=372616  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 16:41:40.587  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:40.587  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:40.587  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-16 16:41:40.588  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 16:41:40.588  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-16 16:41:40.588  1035  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=372620  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 16:41:40.589  1035  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=372621  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 16:41:40.589  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 16:41:40.590  1035  1525 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=372622
08-16 16:41:40.590  7218  7218 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 16:41:40.590  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 16:41:40.590  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 16:41:40.590  1035  1525 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=372622
08-16 16:41:40.590  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 16:41:40.590  7218  7218 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 16:41:40.590  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 16:41:40.590  1035  1525 D WifiNative-wlan0: doString: [STATUS]
08-16 16:41:40.590  7218  7218 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 16:41:40.591  1035  7655 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 16:41:40.591  1035  7655 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-16 16:41:40.592  1035  1525 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 16:41:40.593  1035  1525 I WifiServiceExtension: setVHTCapabilityType  : false
08-16 16:41:40.599  6342  6342 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:41:40.604  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:41:40.604  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 16:41:40.606  1035  1525 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-16 16:41:40.606  1035  1525 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-16 16:41:40.607  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 16:41:40.610  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:40.610  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:40.610  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 16:41:40.611  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:40.611  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:40.611  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 16:41:40.614  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 16:41:40.616  1035  1525 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-16 16:41:40.617  1035  1531 D ConnectivityService: Got NetworkAgent Messenger
08-16 16:41:40.617  1035  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 16:41:40.617  1035  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 16:41:40.617  1035  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 16:41:40.617  1035  1531 D ConnectivityService: NetworkAgent connected
08-16 16:41:40.617  1035  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 16:41:40.617  1035  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-16 16:41:40.621  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 16:41:40.624  1035  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 16:41:40.624  1035  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 16:41:40.624  1035  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 16:41:40.625  1035  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 16:41:40.625  1035  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 16:41:40.627  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:41:40.627  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 16:41:40.628  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:40.628  7287  7287 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 16:41:40.629  7287  7287 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 16:41:40.629  7287  7287 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 16:41:40.630  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:41:40.630  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 16:41:40.631  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:40.632  1035  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 16:41:40.633  6342  6342 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:41:40.633   319   878 D CommandListener: Setting iface cfg
08-16 16:41:40.638  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 16:41:40.639  1035  7708 D DhcpStateMachine: StoppedState
08-16 16:41:40.639  1035  1525 E WifiStateMachine: Start Dhcp Watchdog 2
08-16 16:41:40.639  1035  7708 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:40.639  1035  7708 D DhcpStateMachine: WaitBeforeStartState
08-16 16:41:40.639  1035  1525 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=372671  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 16:41:40.640  1035  1525 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=372672  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 16:41:40.640  1035  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=372672  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 16:41:40.641  1035  1525 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-16 16:41:40.641  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
,08-16 16:41:40.641  1035  1525 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 16:41:40.642  1035  1525 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 16:41:40.642  1035  1525 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 16:41:40.642  1035  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-16 16:41:40.643  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 16:41:40.643  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-16 16:41:40.644  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 16:41:40.644  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 16:41:40.645  1035  1525 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=372677  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 16:41:40.646  1035  1525 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=372678  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 16:41:40.646  1035  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=372678  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 16:41:40.647  1035  1525 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:326501] from screen [on:0 period:-1815281881] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 16:41:40.647  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1815281881] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 16:41:40.647  1035  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 16:41:40.650  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:40.651  1035  1531 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-16 16:41:40.651  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 16:41:40.652  1035  1525 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 16:41:40.652  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 16:41:40.652  1035  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 16:41:40.653  1035  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 16:41:40.653  1035  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-16 16:41:40.653  1035  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 16:41:40.654  1035  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 16:41:40.655  1035  1525 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=197,0,0
08-16 16:41:40.655  7287  7287 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 16:41:40.655  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=197,0,0
08-16 16:41:40.656  7287  7287 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 16:41:40.655  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 16:41:40.656  7628  7628 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-16 16:41:40.656  7287  7287 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 16:41:40.656  1035  1525 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 16:41:40.656  1035  1525 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 16:41:40.656  1035  1525 D WifiNative-wlan0: SET ps 0: returned true
08-16 16:41:40.656  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-16 16:41:40.656  7628  7628 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 16:41:40.657  1035  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 16:41:40.657  1035  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@51ddef9 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:40.657  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@51ddef9 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:40.657  1035  7708 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 16:41:40.657  1035  7708 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 16:41:40.658  6342  6342 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:41:40.658  1035  1525 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 16:41:40.658  1035  1525 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 16:41:40.658  1035  1525 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 16:41:40.659   319   878 D CommandListener: Setting iface cfg
08-16 16:41:40.660   319   878 D CommandListener: Trying to bring up wlan0
08-16 16:41:40.660  1035  1525 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-16 16:41:40.661  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 16:41:40.661  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 16:41:40.661  1035  1525 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 16:41:40.662  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 16:41:40.662  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 16:41:40.662  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 16:41:40.662  1035  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 16:41:40.663  1035  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 16:41:40.663  1035  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 16:41:40.663  1035  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 16:41:40.664  1035  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 16:41:40.664  1035  1525 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 16:41:40.665  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 16:41:40.665  1035  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:40.665  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:40.665  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 16:41:40.666  7628  7628 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 16:41:40.666  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 16:41:40.666  1035  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 16:41:40.666  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-16 16:41:40.666  7628  7628 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
,08-16 16:41:40.667  1035  1525 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
,08-16 16:41:40.667  1035  1525 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 16:41:40.671  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 16:41:40.677  7287  7287 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 16:41:40.677  7287  7287 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 16:41:40.677  7287  7287 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 16:41:40.679  6342  6342 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:41:40.685  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 16:41:40.688  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 16:41:40.692  7287  7287 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 16:41:40.692  7287  7287 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 16:41:40.693  7287  7287 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 16:41:40.693  1035  1525 D WifiNative-wlan0: SET ps 1: returned true
08-16 16:41:40.694  1035  1525 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 16:41:40.694  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 16:41:40.694  1035  1525 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-16 16:41:40.694  1035  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 16:41:40.694  1035  1531 D ConnectivityService: ignoring duplicate network state non-change
08-16 16:41:40.698  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:41:40.698  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 16:41:40.700  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:40.701  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:40.701  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:40.701  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 16:41:40.704  1035  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 16:41:40.705  1035  1531 D ConnectivityService: Adding iface wlan0 to network 101
08-16 16:41:40.708  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:40.708  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:40.708  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 16:41:40.710  1035  1525 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 16:41:40.711  6342  6342 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:41:40.712  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 16:41:40.715  1959  1959 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-16 16:41:40.720  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:40.720  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:40.720  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 16:41:40.722  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 16:41:40.722  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:40.722  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:40.722  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 16:41:40.724  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:41:40.724  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 16:41:40.725  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:40.728  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 16:41:40.728  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 16:41:40.728  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:40.732  1035  1531 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 16:41:40.732  1035  1531 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-16 16:41:40.734  1035  1531 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-16 16:41:40.734  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 16:41:40.735   319   878 E Netd    : netlink response contains error (File exists)
08-16 16:41:40.735  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:41:40.735  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 16:41:40.736  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:40.736  1035  1531 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-16 16:41:40.736  1035  1531 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 16:41:40.736  1035  1531 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-16 16:41:40.736  1035  1531 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-16 16:41:40.737  1035  1531 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 16:41:40.737  1035  1531 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 16:41:40.737  1035  1531 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-16 16:41:40.737  1035  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 16:41:40.737  1035  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 16:41:40.737  1035  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 16:41:40.737  1035  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 16:41:40.738  1035  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:41:40.738  1035  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 16:41:40.738  1035  1531 D ConnectivityService: currentScore = 0, newScore = 20
08-16 16:41:40.738  1035  1531 D ConnectivityService:    accepting network in place of null
08-16 16:41:40.738  1035  1531 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:41:40.738  1035  1525 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:41:40.738  1035  7707 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:40.738  1035  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 16:41:40.738  1035  7707 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 16:41:40.738  1035  7707 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0, what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:40.738  1035  7707 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 16:41:40.741  1862  1862 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:41:40.741  1862  1862 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 16:41:40.742   319  7713 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-16 16:41:40.744  1035  1531 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 16:41:40.744  1035  1531 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 16:41:40.744  1035  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 16:41:40.744  1035  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 16:41:40.744  1035  1531 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 16:41:40.745  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-16 16:41:40.745  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 16:41:40.745  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 16:41:40.745  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 16:41:40.746  1035  1531 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,08-16 16:41:40.747  1035  1531 D ConnectivityService: validation of new default Network = false
08-16 16:41:40.747  1035  1531 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 16:41:40.747  1035  1531 D DSQN    : enableDataServiceNotify 
08-16 16:41:40.747  1035  1531 D DSQN    : start dsqn bin
08-16 16:41:40.754  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 16:41:40.755  1035  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 16:41:40.755  1035  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:41:40.755  1035  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 16:41:40.756  1035  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 16:41:40.756  1589  1796 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 16:41:40.745  7714  7714 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 16:41:40.745  7714  7714 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 16:41:40.765  1035  1520 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-16 16:41:40.767  7714  7714 E DSQN    : DSQN ssw
08-16 16:41:40.769  7287  7287 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 16:41:40.770  7287  7287 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 16:41:40.773  7287  7287 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 16:41:40.780  6342  6342 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:41:40.784   319  7713 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-16 16:41:40.788  1826  7718 I CheckinService: active receiver: enabled
,08-16 16:41:40.809  1826  7718 I CheckinService: Preparing to send checkin request
08-16 16:41:40.809  1826  7718 I EventLogService: Accumulating logs since 1471358361833
08-16 16:41:40.817  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 16:41:40.818   319  7713 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-16 16:41:40.827  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 16:41:40.830  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:40.830  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 16:41:40.832  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:40.835  7287  7287 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 16:41:40.835  7287  7287 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 16:41:40.836  7287  7287 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 16:41:40.839  6342  6342 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:41:40.842  1826  7718 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-16 16:41:40.843  7636  7636 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 16:41:40.846  7636  7636 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 16:41:40.848   319   877 D LGDataListener: argv[0]=dsqncommand
08-16 16:41:40.848   319   877 D LGDataListener: argv[1]=wlan0
08-16 16:41:40.848   319   877 D LGDataListener: argv[2]=1
08-16 16:41:40.848   319   877 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,08-16 16:41:40.849  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 16:41:40.849  1035  1115 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 16:41:40.849  1035  1115 D DSQN    : start to monitor internet connection
08-16 16:41:40.855  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 16:41:40.859  1035  7708 D DhcpStateMachine: DHCPV4 request on wlan0
,08-16 16:41:40.859  1035  7708 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-16 16:41:40.859  1035  7708 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-16 16:41:40.861  7287  7287 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 16:41:40.862  7287  7287 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 16:41:40.862  7287  7287 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 16:41:40.845  7722  7722 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 16:41:40.845  7722  7722 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 16:41:40.863  7287  7287 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 16:41:40.864  7287  7287 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 16:41:40.868  6342  6342 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:41:40.870  7636  7636 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 16:41:40.870  7636  7636 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 16:41:40.872  7722  7722 I dhcpcd  : version 5.5.6 starting
08-16 16:41:40.873  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 16:41:40.874  7722  7722 E dhcpcd  : get_duid: m
08-16 16:41:40.874  7722  7722 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 16:41:40.874  7722  7722 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-16 16:41:40.875  1035  7707 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 14:41:40 GMT], X-Android-Received-Millis=[1471358500875], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471358500847]}
08-16 16:41:40.875  1035  7707 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 16:41:40.875  1035  7707 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 16:41:40.876  1035  1531 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-16 16:41:40.876  1035  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 16:41:40.876  1035  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 16:41:40.876  1035  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 16:41:40.876  1035  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 16:41:40.876  1035  1531 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-16 16:41:40.876  1035  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 16:41:40.876  1035  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:41:40.876  1035  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 16:41:40.876  1035  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 16:41:40.877  1035  1531 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:41:40.877  1589  1796 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 16:41:40.877  1035  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 16:41:40.877  1035  1525 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:41:40.877  1035  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 16:41:40.878  1862  1862 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:41:40.878  1862  1862 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 16:41:40.880  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 16:41:40.889  7287  7287 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 16:41:40.889  7287  7287 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 16:41:40.889  7287  7287 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 16:41:40.890  7287  7287 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 16:41:40.890  7287  7287 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-16 16:41:40.902  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 16:41:40.903  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:40.904  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:40.926  7722  7722 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 16:41:40.926  7722  7722 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-16 16:41:40.926  7722  7722 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-16 16:41:40.926  7722  7722 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-16 16:41:40.926  7722  7722 D dhcpcd  : wlan0: sending REQUEST (xid 0x390e11d6), next in 4.95 seconds
08-16 16:41:40.944  7722  7722 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-16 16:41:40.955  7373  7402 D UEI.SmartControl: Internal timer expired: 1
,08-16 16:41:40.955  7373  7402 D UEI.SmartControl: unbind internal service
08-16 16:41:40.963  1035  1562 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7729 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-16 16:41:40.967  7722  7722 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-16 16:41:40.967  7722  7722 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
,08-16 16:41:40.968  7722  7722 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-16 16:41:40.968  7722  7722 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-16 16:41:40.969  7722  7722 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 16:41:40.969  7722  7722 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 16:41:40.969  7722  7722 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 16:41:40.969  7722  7722 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-16 16:41:41.009  7729  7729 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-16 16:41:41.009  7729  7729 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-16 16:41:41.026  7373  7399 D serial_port: close(fd = 25)
,08-16 16:41:41.029  7373  7399 I UEI.SmartControl: Serial port is closed.
08-16 16:41:41.031  7729  7729 I MultiDex: VM with version 2.1.0 has multidex support
08-16 16:41:41.031  7729  7729 I MultiDex: install
08-16 16:41:41.031  7729  7729 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-16 16:41:41.038  7729  7729 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-16 16:41:41.043  2205  2205 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-16 16:41:41.052  2205  2205 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-16 16:41:41.065  2205  2205 D c       : Getting all permits...
08-16 16:41:41.065  2205  2205 D a       : Opening database...
,08-16 16:41:41.069  2205  2205 D a       : Opening database auth.proximity.permit_store...
,08-16 16:41:41.070  2205  2205 D a       : Closing database...
08-16 16:41:41.262  1035  7708 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-16 16:41:41.265  1035  7708 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-16 16:41:41.265  1035  7708 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,08-16 16:41:41.266  1035  7708 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-16 16:41:41.266  1035  7708 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-16 16:41:41.266  1035  7708 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 16:41:41.267  1035  7708 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-16 16:41:41.267  1035  7708 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-16 16:41:41.267  1035  7708 D DhcpStateMachine: RunningState
08-16 16:41:41.460  7776  7776 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-16 16:41:41.537  7776  7776 I dex2oat : dex2oat took 76.980ms (threads: 4)
,08-16 16:41:41.559  7729  7745 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 16:41:41.559  7729  7745 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 16:41:41.559  7729  7745 I Adreno-EGL: Build Date: 12/12/14 금
08-16 16:41:41.559  7729  7745 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 16:41:41.559  7729  7745 I Adreno-EGL: Remote Branch: 
08-16 16:41:41.559  7729  7745 I Adreno-EGL: Local Patches: 
08-16 16:41:41.559  7729  7745 I Adreno-EGL: Reconstruct Branch: 
,08-16 16:41:41.716  1035  1525 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-16 16:41:41.717  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-16 16:41:41.717  1035  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 16:41:41.717  1035  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-16 16:41:41.718  1035  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-16 16:41:41.718  1035  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 16:41:41.718  1035  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-16 16:41:41.718  1035  1531 D ConnectivityService: identical MTU - not setting
08-16 16:41:41.718  1035  1531 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 16:41:41.718  1035  1531 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 16:41:41.719  1035  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:41:41.719  1035  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 16:41:41.719  1035  1531 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 16:41:41.720  1589  1796 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-16 16:41:41.756  1035  1531 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-16 16:41:41.915  7729  7745 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 16:41:41.915  7729  7745 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 16:41:41.992  7729  7745 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 16:41:41.992  7729  7745 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 16:41:41.992  7729  7745 I Adreno-EGL: Build Date: 12/12/14 금
08-16 16:41:41.992  7729  7745 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 16:41:41.992  7729  7745 I Adreno-EGL: Remote Branch: 
08-16 16:41:41.992  7729  7745 I Adreno-EGL: Local Patches: 
08-16 16:41:41.992  7729  7745 I Adreno-EGL: Reconstruct Branch: 
,08-16 16:41:42.081  7729  7745 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 16:41:42.081  7729  7745 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 16:41:42.081  7729  7745 I Adreno-EGL: Build Date: 12/12/14 금
08-16 16:41:42.081  7729  7745 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 16:41:42.081  7729  7745 I Adreno-EGL: Remote Branch: 
08-16 16:41:42.081  7729  7745 I Adreno-EGL: Local Patches: 
08-16 16:41:42.081  7729  7745 I Adreno-EGL: Reconstruct Branch: 
,08-16 16:41:42.210   319  7784 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 16:41:42.211   319  7784 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-16 16:41:42.257   319  7784 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-16 16:41:42.279  1035  1407 V AlarmManager: ELAPSED_WAKEUP set : Alarm{8199716 type 2 when 374309 com.google.android.gms} when 374309
,08-16 16:41:42.298   319  7786 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 16:41:42.298   319  7786 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-16 16:41:42.302  7287  7287 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-16 16:41:42.302  7287  7287 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9008
,08-16 16:41:42.339   319  7786 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-16 16:41:42.449  1826  7718 I CheckinTask: Sending checkin request (7913 bytes)
,08-16 16:41:42.656  2205  7788 D GCM     : Connected
,08-16 16:41:42.701  2205  7788 D GCM     : Message class com.google.e.a.a.q
,08-16 16:41:42.728  1826  7718 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-16 16:41:42.738  1826  7718 I CheckinService: active receiver: disabled
,08-16 16:41:42.771  2205  2205 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-16 16:41:42.789  2205  2205 I GCM     : GCM config loaded
,08-16 16:41:42.806  7467  7467 V SetupWizard: Connected to Gservices successfully
,08-16 16:41:43.657  1035  1525 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=98.5, 0.0, 0.0  rx=137.5 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1815278871] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 16:41:43.660  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=98.5, 0.0, 0.0  rx=137.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1815278868] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 16:41:43.660  1035  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 16:41:43.683  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 16:41:43.714  1035  1526 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-16 16:41:43.746  1035  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 16:41:43.753  1035  1117 D Tethering: MasterInitialState.processMessage what=3
08-16 16:41:43.761  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:43.761  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:41:43.761  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:43.761  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:43.761  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:41:43.761  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:41:43.761  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:41:43.761  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:41:43.761  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 16:41:43.761  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:43.761  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 16:41:43.766  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:43.766  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:41:43.766  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:43.766  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:43.766  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:41:43.766  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:41:43.766  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:41:43.766  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:41:43.766  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 16:41:43.766  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:43.766  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 16:41:43.773  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:43.773  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:41:43.773  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:43.773  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:43.773  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:41:43.773  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:41:43.773  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:41:43.773  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:41:43.773  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 16:41:43.773  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:43.773  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 16:41:43.778  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 16:41:43.786  6342  6342 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 16:41:43.792  5763  5763 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-16 16:41:43.800  6342  7239 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 16:41:43.806  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 16:41:43.824  1035  2022 D WifiServiceImplEx: setWifiEnabled: false pid=7049, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 16:41:43.824  1035  2022 D WifiService: setWifiEnabled: false pid=7049, uid=10118
08-16 16:41:43.824  1035  2022 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 16:41:43.847  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 16:41:43.847  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 16:41:43.847  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-16 16:41:43.851  1035  1525 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 16:41:43.851  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 16:41:43.852  1035  1525 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-16 16:41:43.852  1035  1525 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 16:41:43.852  1035  1525 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 16:41:43.852  1035  1525 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 16:41:43.852  1035  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 16:41:43.853  1035  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 16:41:43.853  1035  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 16:41:43.853  1035  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 16:41:43.871  1035  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 16:41:43.871  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 16:41:43.871  1035  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:43.871  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:43.871  7628  7628 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 16:41:43.872  1035  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 16:41:43.872  1035  1525 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 16:41:43.872  1035  1525 D WifiNative-wlan0: SET ps 1: returned true
08-16 16:41:43.872   319   878 D CommandListener: Clearing all IP addresses on wlan0
08-16 16:41:43.875  1035  7708 D DhcpStateMachine: RunningState{ when=-3ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 16:41:43.897  2205  2205 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 16:41:43.899  7546  7566 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-16 16:41:43.904  1035  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 16:41:43.904  1035  1531 D ConnectivityService: ignoring duplicate network state non-change
08-16 16:41:43.904  1035  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-16 16:41:43.906  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-16 16:41:43.907  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:41:43.907  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 16:41:43.910  1959  1959 V WfdStateTracker: handleWifiStateChangedEvent: 0
,08-16 16:41:43.913  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:43.913  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:43.914  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 16:41:43.914  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:43.919  1035  1525 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 16:41:43.920  1035  1521 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:43.920  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:43.920  1035  1521 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@13a243be
08-16 16:41:43.920  1035  1521 D LGWifiP2pService: P2pDisablingState
08-16 16:41:43.920  1035  1521 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:43.920  1035  1521 D LGWifiP2pService: p2p socket connection lost
08-16 16:41:43.920  1035  1521 D LGWifiP2pService: P2pDisabledState
,08-16 16:41:43.928  1959  1959 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 16:41:43.929  1959  1959 D WfdsService: WifiP2pState is changed : false
08-16 16:41:43.929  1959  2274 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 16:41:43.929  1959  2274 D WfdsService: Set the WFDS Monitor: false
08-16 16:41:43.930  1959  2274 D WfdsMonitor: WFDS Monitor is stopped
08-16 16:41:43.930  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-16 16:41:43.930  1959  2274 D WfdsService: STATE : WfdsDisabledState - enter
08-16 16:41:43.930  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:43.930  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:43.930  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 16:41:43.930  1959  7659 D CtrlSupplicant: Received on exit socket, terminate
08-16 16:41:43.930  1959  7659 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 16:41:43.930  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 16:41:43.930  1959  7659 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 16:41:43.930  1035  1035 D RttService: SCAN_AVAILABLE : 1
08-16 16:41:43.930  1959  7659 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 16:41:43.930  1959  2276 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-16 16:41:43.930  1035  1543 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:43.931  1035  1544 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:43.931  1035  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-16 16:41:43.931  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 16:41:43.931  1035  1521 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:43.931  1959  2274 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 16:41:43.931  7628  7628 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 16:41:43.931  1035  1521 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:43.932  1035  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 16:41:43.932  1035  1525 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 16:41:43.932  1035  1525 D WifiNative-wlan0: SET ps 1: returned true
08-16 16:41:43.936  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:41:43.936  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 16:41:43.937  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:43.939  6888  6888 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 16:41:43.939  6888  6888 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 16:41:43.939  6888  6888 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 16:41:43.939  6888  6888 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 16:41:43.942  6888  6888 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 16:41:43.949  1035  1562 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
08-16 16:41:43.950  1035  7707 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:43.950  1035  7707 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:43.950  1035  7707 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 16:41:43.950  1035  7707 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:43.950  1035  7707 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-16 16:41:43.956   319   878 D CommandListener: Clearing all IP addresses on wlan0
,08-16 16:41:43.956  1035  1531 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 16:41:43.956  1035  1531 D DSQN    : disableDataServiceNotify
08-16 16:41:43.956  1035  1531 D DSQN    : stop dsqn bin
08-16 16:41:43.958   319  7821 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 16:41:43.958  1035  1525 D WifiNative-p2p0: doBoolean: TERMINATE
08-16 16:41:43.958  6888  6888 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1356dadd
08-16 16:41:43.958  1035  7707 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-16 16:41:43.958  6888  6888 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 16:41:43.958  6888  6888 D AppUp4:CustFacade: isPhone : true
08-16 16:41:43.958  6888  6888 D AppUp4:CustModeStarterReceiver: begin check event
08-16 16:41:43.958  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 16:41:43.958  6888  6888 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 16:41:43.959  1035  1525 D WifiNative-p2p0: TERMINATE: returned true
08-16 16:41:43.959  1035  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 16:41:43.959  1035  1525 E WifiStateMachine: useWiFiOffloading() : false
08-16 16:41:43.959  1035  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 16:41:43.959  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 16:41:43.959  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 16:41:43.959  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-16 16:41:43.960  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:43.960  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:43.960  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 16:41:43.960  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:43.962  4627  4627 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 16:41:43.962  4627  4627 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 16:41:43.963  4627  4627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 16:41:43.963  1959  1959 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 16:41:43.965  1035  1531 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-16 16:41:43.965  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 16:41:43.965  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 16:41:43.965  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 16:41:43.965  1035  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:41:43.965  1035  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 16:41:43.966  1035  1531 D ConnectivityService: sending notification LOST for, NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 16:41:43.966  1035  1531 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-16 16:41:43.966  1035  7707 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:43.966  1035  7707 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:43.966  1035  7707 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 16:41:43.966  1589  1796 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 16:41:43.967  1035  1531 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-16 16:41:43.967  1035  1531 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 16:41:43.967  1035  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 16:41:43.968  4627  4627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 16:41:43.969  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:43.969  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:41:43.969  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:43.969  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:43.969  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:41:43.969  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:41:43.969  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:41:43.969  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:41:43.969  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 16:41:43.969  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:43.970  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:41:43.970  1035  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 16:41:43.970  1035  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 16:41:43.971  1035  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 16:41:43.971  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 16:41:43.971  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 16:41:43.971  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 16:41:43.971  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 16:41:43.973  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:43.973  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:41:43.973  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:43.973  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:43.973  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:41:43.973  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:41:43.973  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:41:43.973  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:41:43.973  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 16:41:43.973  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:43.973  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:41:43.974  4627  7822 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 16:41:43.976  4627  7823 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 16:41:43.976  4627  7823 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 16:41:43.978  1035  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 16:41:43.978  1035  1531 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:41:43.978  1035  1531 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:41:43.979  1035  1531 D NetworkManagementService: Removing idletimer
08-16 16:41:43.979  1035  1531 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:43.979  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:43.979  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:41:43.979  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:43.979  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:43.979  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:41:43.979  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:41:43.979  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:41:43.979  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:41:43.979  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 16:41:43.979  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:43.979  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:41:43.980  1035  1525 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:41:43.980  1035  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 16:41:43.980  1862  1862 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:41:43.980  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:43.981  1862  1862 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 16:41:43.982  1035  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 16:41:43.982  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 16:41:43.982  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 16:41:43.982  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 16:41:43.982  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 16:41:43.987  7433  7433 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 16:41:44.005  7433  7824 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:44.010  7311  7826 W FormManager: Network not available. Please check & try again.
08-16 16:41:44.011  7311  7827 V FormManager: Network unavailable.
08-16 16:41:44.014  7311  7827 V FormManager: Network unavailable.
08-16 16:41:44.016  7628  7628 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 16:41:44.016  7628  7628 I wpa_supplicant: monitor socket send errors count : 1
08-16 16:41:44.016  7628  7628 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1959-4\x00 that cannot receive messages
08-16 16:41:44.016  1035  7655 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-16 16:41:44.016  1035  7655 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 16:41:44.021  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 16:41:44.022  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:44.022  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:44.026  3296  3296 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 16:41:44.026  3296  3296 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 16:41:44.026  3296  3296 I LgeMiscReceiver: networkInfo.isConnected() = true
08-16 16:41:44.026  3296  3296 D PhoneState: setPdpRejectCasuse : false
08-16 16:41:44.030  7467  7467 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 16:41:44.030  7467  7467 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 16:41:44.038  7528  7528 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:41:44
08-16 16:41:44.039  7528  7528 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 16:41:44.039  7528  7528 D Weather.Utils: 2 : All the weather widget is gone.
08-16 16:41:44.041  7528  7528 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 16:41:44.041  7528  7528 D WeatherAncestor: connectivity changed - connection : true
08-16 16:41:44.041  7528  7528 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1ae7e59e
,08-16 16:41:44.042  7528  7528 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 16:41:44.042  7528  7528 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 16:41:44.042  7528  7528 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 16:41:44.042  7528  7528 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 16:41:44.043  7528  7528 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:41:44
08-16 16:41:44.054  7628  7628 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 16:41:44.054  1035  7655 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
,08-16 16:41:44.054  1035  7655 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 16:41:44.054  1035  7655 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 16:41:44.054  1035  7655 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-16 16:41:44.055  7628  7628 W wpa_supplicant: USIM:  scard_deinit function
08-16 16:41:44.056  1035  7655 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 16:41:44.056  1035  7655 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 16:41:44.056  1035  1525 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=376088
08-16 16:41:44.057  1035  1525 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=376089
08-16 16:41:44.057  1035  1117 D Tethering: InitialState.processMessage what=4
08-16 16:41:44.058  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 16:41:44.058  1035  1525 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=376090  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 16:41:44.059  1035  1525 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=376091  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 16:41:44.059  1035  1525 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-16 16:41:44.060  1035  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-16 16:41:44.075  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 16:41:44.077  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:44.078  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:44.080  6342  6342 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:41:44.085  7636  7636 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 16:41:44.088  1035  7708 D DhcpStateMachine: StoppedState
08-16 16:41:44.088  1035  7708 D DhcpStateMachine: StoppedState{ when=-156ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:44.090  1035  1525 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-16 16:41:44.090  1035  1525 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-16 16:41:44.092  7636  7636 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 16:41:44.092  7636  7636 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 16:41:44.098  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 16:41:44.108  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 16:41:44.121  7287  7287 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 16:41:44.122  7287  7287 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 16:41:44.126  7287  7287 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 16:41:44.134  6342  6342 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 16:41:44.142  7636  7636 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 16:41:44.142  7636  7636 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 16:41:44.142  7636  7636 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 16:41:44.149  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 16:41:44.150  7628  7628 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-16 16:41:44.153  1035  7655 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 16:41:44.153  1035  7655 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 16:41:44.153  1035  7655 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 16:41:44.155  1035  1525 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
08-16 16:41:44.158  1035  1525 D WifiOffDelayIfNotUsed: stopMonitoring
08-16 16:41:44.159  1035  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 16:41:44.159  1035  1525 E WifiStateMachine: useWiFiOffloading() : false
08-16 16:41:44.159  1035  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 16:41:44.159  1959  1959 D WfdsService: Supplicant Connection state is changed : false
08-16 16:41:44.159  1959  2274 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-16 16:41:44.159  1959  2274 D WfdsService: Set the WFDS Monitor: false
08-16 16:41:44.159  1959  2274 D WfdsMonitor: WFDS Monitor is stopped
08-16 16:41:44.161  1959  1959 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 16:41:44.162  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:41:44.163  2484  2484 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:44.163  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 16:41:44.165  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:44.165  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:41:44.165  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:44.165  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:44.165  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:41:44.165  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:41:44.165  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:41:44.165  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:41:44.165  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:41:44.166  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-16 16:41:44.166  1035  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 16:41:44.166  1035  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 16:41:44.168  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:44.168  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:41:44.168  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:44.168  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:44.168  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:41:44.168  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:41:44.168  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:41:44.168  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:41:44.168  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:41:44.169  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:44.169  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:41:44.169  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:44.169  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:44.169  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:41:44.169  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:41:44.169  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:41:44.169  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:41:44.169  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:41:44.180  7287  7287 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 16:41:44.181  7287  7287 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 16:41:44.183  7287  7287 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 16:41:44.188  6342  6342 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:41:44.193  7636  7636 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 16:41:44.193  7636  7636 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 16:41:44.193  7636  7636 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 16:41:44.199  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 16:41:44.206  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 16:41:44.212  7287  7287 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 16:41:44.212  7287  7287 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 16:41:44.214  7287  7287 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 16:41:44.223  7636  7636 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 16:41:44.226  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 16:41:44.234  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 16:41:44.241  7311  7832 V FormManager: Network unavailable.
08-16 16:41:44.241  7311  7831 W FormManager: Network not available. Please check & try again.
,08-16 16:41:44.252  7311  7832 V FormManager: Network unavailable.
,08-16 16:41:44.254  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 16:41:44.254  7218  7218 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 16:41:44.254  7218  7218 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 16:41:44.254  7218  7218 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 16:41:44.255  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 16:41:44.255  7218  7218 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 16:41:44.256  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 16:41:44.256  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 16:41:44.256  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 16:41:44.256  7218  7218 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 16:41:44.256  7218  7218 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 16:41:44.263  4627  4627 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 16:41:44.263  4627  4627 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 16:41:44.266  4627  4627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 16:41:44.268  4627  4627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 16:41:44.273  4627  7833 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 16:41:44.276  4627  7834 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 16:41:44.276  4627  7834 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 16:41:44.277  7636  7636 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-16 16:41:44.278  7636  7636 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 16:41:44.278  7636  7636 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 16:41:44.281  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 16:41:44.284  7311  7836 W FormManager: Network not available. Please check & try again.
,08-16 16:41:44.289  7311  7837 V FormManager: Network unavailable.
08-16 16:41:44.291  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 16:41:44.291  7311  7837 V FormManager: Network unavailable.
,08-16 16:41:46.700  1035  1525 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1815275828] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 16:41:46.702  1035  1525 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1815275826] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 16:41:46.973  1035  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 16:41:46.983  1035  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 16:41:46.988  1035  1117 D Tethering: MasterInitialState.processMessage what=3
08-16 16:41:47.001  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:41:47.005  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:47.006  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:47.008  1035  1117 D Tethering: MasterInitialState.processMessage what=3
08-16 16:41:47.010  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 16:41:47.018  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:41:47.023  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:47.024  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:47.030  6342  6342 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 16:41:47.033  6342  7239 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-16 16:41:47.045  5763  5763 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 16:41:47.054  5763  5763 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 16:41:47.076  2205  2205 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 16:41:47.093  6888  6888 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 16:41:47.093  6888  6888 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 16:41:47.093  6888  6888 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 16:41:47.093  6888  6888 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 16:41:47.098  6888  6888 I AppUp4:CustModeStarterReceiver: onReceive
08-16 16:41:47.101  6888  6888 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1356dadd
08-16 16:41:47.101  6888  6888 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 16:41:47.101  6888  6888 D AppUp4:CustFacade: isPhone : true
08-16 16:41:47.102  6888  6888 D AppUp4:CustModeStarterReceiver: begin check event
08-16 16:41:47.102  6888  6888 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 16:41:47.107  4627  4627 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 16:41:47.107  4627  4627 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 16:41:47.108  4627  4627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 16:41:47.114  4627  4627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 16:41:47.122  7433  7433 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 16:41:47.134  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 16:41:47.141  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:41:47.141  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:41:47.144  4627  7859 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 16:41:47.154  7433  7862 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:47.156  4627  7860 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 16:41:47.156  4627  7860 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 16:41:47.166  3296  3296 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 16:41:47.166  3296  3296 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 16:41:47.166  3296  3296 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 16:41:47.168  7311  7866 W FormManager: Network not available. Please check & try again.
08-16 16:41:47.171  7467  7467 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 16:41:47.172  7467  7467 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 16:41:47.187  7528  7528 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:41:47
,08-16 16:41:47.188  7311  7867 V FormManager: Network unavailable.
,08-16 16:41:47.189  7528  7528 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 16:41:47.189  7528  7528 D Weather.Utils: 2 : All the weather widget is gone.
08-16 16:41:47.190  7528  7528 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 16:41:47.190  7528  7528 D WeatherAncestor: connectivity changed - connection : true
08-16 16:41:47.190  7528  7528 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1ae7e59e
08-16 16:41:47.191  7528  7528 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-16 16:41:47.191  7528  7528 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 16:41:47.191  7311  7867 V FormManager: Network unavailable.
08-16 16:41:47.191  7528  7528 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 16:41:47.191  7528  7528 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 16:41:47.191  7528  7528 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:41:47
08-16 16:41:47.214  6342  6342 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 16:41:47.216  6342  7239 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-16 16:41:47.217  1035  1913 I ActivityManager: Killing 7663:com.lge.bnr/1000 (adj 15): empty #17
08-16 16:41:47.252  1035  2086 W libprocessgroup: failed to open /acct/uid_1000/pid_7663/cgroup.procs: No such file or directory
,08-16 16:41:47.270  2205  2205 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 16:41:47.278  6888  6888 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 16:41:47.278  6888  6888 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 16:41:47.278  6888  6888 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,08-16 16:41:47.278  6888  6888 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 16:41:47.279  6888  6888 I AppUp4:CustModeStarterReceiver: onReceive
08-16 16:41:47.283  6888  6888 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1356dadd
08-16 16:41:47.283  6888  6888 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 16:41:47.283  6888  6888 D AppUp4:CustFacade: isPhone : true
08-16 16:41:47.284  6888  6888 D AppUp4:CustModeStarterReceiver: begin check event
08-16 16:41:47.284  6888  6888 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-16 16:41:47.288  4627  4627 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-16 16:41:47.289  4627  4627 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 16:41:47.291  4627  4627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 16:41:47.294  4627  4627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 16:41:47.300  7433  7433 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 16:41:47.304  4627  7871 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 16:41:47.306  4627  7872 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 16:41:47.307  4627  7872 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 16:41:47.328  7433  7873 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 16:41:47.330  7311  7875 W FormManager: Network not available. Please check & try again.
08-16 16:41:47.345  3296  3296 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 16:41:47.345  3296  3296 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 16:41:47.345  3296  3296 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-16 16:41:47.353  7467  7467 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 16:41:47.353  7467  7467 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 16:41:47.372  7528  7528 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:41:47
,08-16 16:41:47.374  7528  7528 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-16 16:41:47.374  7311  7876 V FormManager: Network unavailable.
08-16 16:41:47.375  7528  7528 D Weather.Utils: 2 : All the weather widget is gone.
08-16 16:41:47.375  7528  7528 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 16:41:47.376  7528  7528 D WeatherAncestor: connectivity changed - connection : true
08-16 16:41:47.376  7528  7528 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1ae7e59e
08-16 16:41:47.377  7528  7528 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 16:41:47.377  7528  7528 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 16:41:47.377  7528  7528 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 16:41:47.377  7528  7528 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 16:41:47.377  7528  7528 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:41:47
08-16 16:41:47.378  7311  7876 V FormManager: Network unavailable.
08-16 16:41:48.852  1035  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 16:41:48.853  1035  1956 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-16 16:41:48.877  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 16:41:48.877  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 16:41:48.877  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-16 16:41:48.880  1035  1117 D BluetoothManagerService: Message: 1
08-16 16:41:48.880  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-16 16:41:48.909  1035  1117 D BluetoothManagerService: Message: 20
08-16 16:41:48.909  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@36515b4d:true
,08-16 16:41:48.913  7336  7336 D BluetoothAdapterState: make
,08-16 16:41:48.917  7336  7336 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 16:41:48.918  7336  7336 I bluedroid-qcom: init
08-16 16:41:48.919  7336  7889 I BluetoothAdapterState: Entering OffState
08-16 16:41:48.919  7336  7336 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 16:41:48.920  7336  7336 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 16:41:48.920  7336  7336 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 16:41:48.920  7336  7336 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 16:41:48.920  7336  7336 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 16:41:48.922  7336  7336 I bluedroid-qcom: get_profile_interface socket
08-16 16:41:48.922  7336  7336 I bluedroid-qcom: get_profile_interface map_client
,08-16 16:41:48.928  1035  1521 D LGWifiP2pService: P2pDisabledState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:48.928  1035  1521 D LGWifiP2pService: DefaultState{ when=-8ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:41:48.928  7336  7893 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 16:41:48.930  7336  7893 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 16:41:48.915  7892  7892 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 16:41:48.915  7892  7892 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 16:41:48.938  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 16:41:48.939  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
,08-16 16:41:48.945  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-16 16:41:48.946  1035  1117 D BluetoothManagerService: Message: 40
08-16 16:41:48.946  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 16:41:48.947  7336  7352 I bluedroid-qcom: config_hci_snoop_log
08-16 16:41:48.949  7892  7892 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 16:41:48.949  7892  7892 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 16:41:48.949  7892  7892 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-16 16:41:48.950  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 16:41:48.950  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 16:41:48.952  7892  7892 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-16 16:41:48.962  1035  1525 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-16 16:41:48.962  1035  1525 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-16 16:41:48.967  7336  7889 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-16 16:41:48.969  7336  7893 D BluetoothAdapterProperties: Name is: G3
08-16 16:41:48.970  7336  7889 D BluetoothAdapterProperties: Setting state to 11
08-16 16:41:48.970  7336  7889 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 16:41:48.971  1035  1117 D BluetoothManagerService: Message: 60
08-16 16:41:48.971  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 16:41:48.971  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-16 16:41:48.973  7336  7889 I LGBluetoothServiceJni: classInitNative: succeeds
08-16 16:41:48.977  1959  1959 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:48.978  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-16 16:41:48.984  7892  7892 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 16:41:48.984  7892  7892 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-16 16:41:48.989  7218  7218 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-16 16:41:48.991  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:41:48.998  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:49.003  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:41:49.008  7336  7336 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 16:41:49.008  7336  7336 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:49.008  7336  7336 V BluetoothPbapReceiver: ***********state = 11
08-16 16:41:49.020  2205  2205 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 16:41:49.025  7336  7889 D BluetoothBondStateMachine: make
08-16 16:41:49.029  7336  7889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae7e59e
08-16 16:41:49.029  7336  7889 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 16:41:49.030  7336  7889 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae7e59e
08-16 16:41:49.030  7336  7889 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 16:41:49.030  7336  7889 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-16 16:41:49.031  7336  7906 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 16:41:49.075  1035  1982 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7911 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 16:41:49.160  1035  2053 I art     : Explicit concurrent mark sweep GC freed 148781(6MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 1.892ms total 127.431ms
,08-16 16:41:49.161  7336  7889 E BluetoothAdapterService: File transfer profiles supported!!
08-16 16:41:49.169  7336  7889 E BluetoothAdapterService: File transfer profiles supported!!
08-16 16:41:49.174  7336  7889 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 16:41:49.174  7336  7336 D HeadsetService: Received start request. Starting profile...
08-16 16:41:49.175  7336  7336 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 16:41:49.176  7336  7336 D LGBluetoothHfpAdapter: Version 1.6
08-16 16:41:49.178  7336  7336 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 16:41:49.179  7336  7336 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 16:41:49.180  7336  7336 D HeadsetStateMachine: make
08-16 16:41:49.181  7336  7889 E BluetoothAdapterService: File transfer profiles supported!!
08-16 16:41:49.186  7336  7889 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 16:41:49.196  7336  7889 E BluetoothAdapterService: File transfer profiles supported!!
08-16 16:41:49.200  7336  7889 E BluetoothAdapterService: File transfer profiles supported!!
08-16 16:41:49.201  7911  7911 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-16 16:41:49.202  7911  7911 W LG Account v2.2: No ProfileInfo entries
08-16 16:41:49.202  7911  7911 I LG Account v2.2: isEnabled: false
08-16 16:41:49.202  7911  7911 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 16:41:49.202  7911  7911 I Feature : [Lifetracker]Country: EU
08-16 16:41:49.202  7911  7911 I Feature : [Lifetracker]Operator: OPEN
08-16 16:41:49.202  7911  7911 I Feature : [Lifetracker]Ranking support: false
08-16 16:41:49.202  7911  7911 I Feature : [Lifetracker]Comfort support: false
08-16 16:41:49.202  7911  7911 I Feature : [Lifetracker]Accessory: true
,08-16 16:41:49.203  7911  7911 I Feature : [Lifetracker]Health device: true
08-16 16:41:49.203  7911  7911 I Feature : [Lifetracker]Extra Pedometer: false
,08-16 16:41:49.203  7911  7911 I Feature : [Lifetracker]Blood glucose device: false
08-16 16:41:49.203  7911  7911 I Feature : [Lifetracker]Device Number: 3
08-16 16:41:49.203  7336  7336 D LgDataFeature: LgDataFeature() Constructor: none
08-16 16:41:49.203  7336  7336 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 16:41:49.208  7336  7336 D HeadsetStateMachine: max_hf_connections = 1
08-16 16:41:49.208  7336  7336 I bluedroid-qcom: get_profile_interface handsfree
08-16 16:41:49.209  7336  7336 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-16 16:41:49.210   326  1366 V AudioPolicyService: registerClient() client 0xb0410240, uid 1002
08-16 16:41:49.210   326  1367 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-16 16:41:49.210   326  1367 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 16:41:49.210   326  1367 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 16:41:49.210  7336  7336 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 16:41:49.211   326   326 V AudioFlinger: registerClient() client 0xb5581820, pid 7336
08-16 16:41:49.211   326  1361 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 16:41:49.211   326  1361 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 16:41:49.211  7336  7336 V ToneGenerator: Create Track: 0xb4928a80
08-16 16:41:49.211  7336  7336 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 16:41:49.211  7336  7336 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 16:41:49.211  1035  1982 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 16:41:49.212  1035  1982 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 16:41:49.212   326  1366 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 16:41:49.212   326  1366 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-16 16:41:49.212   326  1366 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 16:41:49.212  1589  1924 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 16:41:49.212   326  1366 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 16:41:49.212  1589  1924 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 16:41:49.212   326  1362 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 16:41:49.212   326  1362 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 16:41:49.212  7218  7218 D BluetoothPermissionRequest: onReceive
08-16 16:41:49.212  7336  7336 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 16:41:49.212  7336  7353 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 16:41:49.212  7336  7353 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-16 16:41:49.212   326  1366 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 16:41:49.213  1862  1878 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 16:41:49.213  1862  1878 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 16:41:49.213  3296  3315 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 16:41:49.213  3296  3315 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 16:41:49.213  1035  1957 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 16:41:49.213  1035  1957 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 16:41:49.214  1589  2508 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 16:41:49.214  1589  2508 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 16:41:49.214  1862  4732 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 1,6:41:49.214  1862  4732 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 16:41:49.214  3296  3316 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 16:41:49.214  3296  3316 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 16:41:49.214  7336  7352 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 16:41:49.214  7336  7352 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 16:41:49.214   326  1367 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 16:41:49.214   326  1367 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 16:41:49.214   326  1367 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 16:41:49.214   326  1367 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 16:41:49.214  7336  7336 V AudioSystem: getLatency() output 2, latency 50
08-16 16:41:49.214  7336  7336 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 16:41:49.214  7336  7336 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 16:41:49.215   326  1366 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 16:41:49.215   326  1366 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 16:41:49.215   326  1366 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 16:41:49.215   326  1366 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 16:41:49.215   326  1366 V AudioFlinger: createTrack() lSessionId: 22
08-16 16:41:49.215  7336  7889 V LGMDMManager: Create singleton instance
08-16 16:41:49.216  7336  7336 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 16:41:49.216   326  4290 V AudioFlinger: acquiring 22 from 7336, for 7336
08-16 16:41:49.216   326  4290 V AudioFlinger:  added new entry for 22
,08-16 16:41:49.216  7336  7336 V ToneGenerator: ToneGenerator INIT OK, time: 381261
08-16 16:41:49.216  7336  7336 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae7e59e
08-16 16:41:49.217  7336  7931 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-16 16:41:49.217  7336  7931 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 16:41:49.217  7336  7931 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 16:41:49.217  7336  7931 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-16 16:41:49.218  7336  7336 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae7e59e
08-16 16:41:49.218   326  4290 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7336
08-16 16:41:49.218  7218  7218 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 16:41:49.218   326  4290 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 16:41:49.218   326  4290 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 16:41:49.218   326  4290 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 16:41:49.218   326  4290 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 16:41:49.218   326  4290 V voice   : voice_set_parameters: exit with code(0)
08-16 16:41:49.218   326  4290 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 16:41:49.218   326  4290 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 16:41:49.218   326  4290 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 16:41:49.218   326  4290 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 16:41:49.218   326  4290 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 16:41:49.218   326  4290 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 16:41:49.218  7336  7931 V ToneGenerator: ToneGenerator destructor
08-16 16:41:49.218  7336  7931 V ToneGenerator: stopTone
08-16 16:41:49.218  7336  7931 V ToneGenerator: Delete Track: 0xb4928a80
08-16 16:41:49.219  7336  7336 D A2dpService: Received start request. Starting profile...
08-16 16:41:49.219  7336  7336 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 16:41:49.220  7336  7931 V AudioTrack: ~AudioTrack, releasing session id from 7336 on behalf of 7336
08-16 16:41:49.220   326  1367 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 16:41:49.220   326  1367 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 16:41:49.220   326   326 V AudioFlinger: releasing 22 from 7336 for 7336
08-16 16:41:49.220   326   326 V AudioFlinger:  decremented refcount to 0
08-16 16:41:49.220   326  1367 V AudioFlinger: PlaybackThread::Track destructor
08-16 16:41:49.220   326  1273 V AudioPolicyService: AudioCommandThread() waking up
08-16 16:41:49.220   326   326 V AudioFlinger: purging stale effects
08-16 16:41:49.220   326  1367 V AudioFlinger: removeClient_l() pid 7336, calling pid 326
08-16 16:41:49.220   326  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 16:41:49.220   326  1273 V AudioPolicyManager: releaseOutput() 2
08-16 16:41:49.220   326  1273 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 16:41:49.221  7336  7336 V Avrcp   : make
08-16 16:41:49.221  7336  7889 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 16:41:49.221  7336  7336 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-16 16:41:49.221  7336  7336 I bluedroid-qcom: get_profile_interface avrcp
08-16 16:41:49.222  1035  1957 W Process : Unable to open /proc/7933/status
08-16 16:41:49.229  7336  7336 V AudioManager: registerRemoteController: size of Media player list: 0
,08-16 16:41:49.230  7336  7336 E AudioManager: No RCC entry present to update
08-16 16:41:49.230  7336  7336 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-16 16:41:49.232  7336  7336 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-16 16:41:49.233  7336  7336 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-16 16:41:49.233  7336  7336 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-16 16:41:49.236  7336  7336 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 16:41:49.355  1035  1982 V SIM_STK : Menu title from STK is T-Mobile
08-16 16:41:49.356  1035  1982 V SIM_STK : Menu title from STK is T-Mobile
,08-16 16:41:49.472  1035  2053 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 16:41:49.499  7336  7336 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-16 16:41:49.504  7336  7336 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 16:41:49.506  7336  7336 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 16:41:49.506  7336  7336 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 16:41:49.506  7336  7336 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 16:41:49.507  7336  7336 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 16:41:49.507  7336  7336 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 16:41:49.507  7336  7336 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 16:41:49.507  7336  7336 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 16:41:49.507  7336  7336 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 16:41:49.508  7336  7336 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 16:41:49.509  7336  7336 I BluetoothA2dpServiceJni: classInitNative
08-16 16:41:49.510  7336  7336 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 16:41:49.510  7336  7336 D A2dpStateMachine: make
08-16 16:41:49.515  7336  7336 I bluedroid-qcom: get_profile_interface a2dp
08-16 16:41:49.516  7336  7943 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-16 16:41:49.533  7336  7336 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
,08-16 16:41:49.534  7336  7336 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,08-16 16:41:49.539  7336  7336 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae7e59e
08-16 16:41:49.541  7336  7939 D A2dpStateMachine: Enter Disconnected: -2
08-16 16:41:49.544  7336  7336 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 16:41:49.550  7336  7336 D HidService: Received start request. Starting profile...
08-16 16:41:49.550  7336  7336 I bluedroid-qcom: get_profile_interface hidhost
,08-16 16:41:49.550  7336  7336 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae7e59e
,08-16 16:41:49.554  7336  7336 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 16:41:49.558  7336  7336 D HealthService: Received start request. Starting profile...
,08-16 16:41:49.561  7336  7336 I bluedroid-qcom: get_profile_interface health
08-16 16:41:49.561  7336  7336 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-16 16:41:49.562  7336  7336 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae7e59e
08-16 16:41:49.563  7336  7336 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 16:41:49.565  7336  7336 D PanService: Received start request. Starting profile...
,08-16 16:41:49.565  7336  7336 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 16:41:49.565  7336  7336 I bluedroid-qcom: get_profile_interface pan
08-16 16:41:49.578  7336  7336 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-16 16:41:49.578  7336  7336 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae7e59e
08-16 16:41:49.579  7336  7336 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-16 16:41:49.586  7336  7336 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 16:41:49.587  7336  7336 D BtGatt.GattService: Received start request. Starting profile...
08-16 16:41:49.587  7336  7336 D BtGatt.GattService: start()
08-16 16:41:49.587  7336  7336 I bluedroid-qcom: get_profile_interface gatt
08-16 16:41:49.588  7336  7336 D BtGatt.AdvertiseManager: advertise manager created
08-16 16:41:49.595  7336  7336 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae7e59e
,08-16 16:41:49.598  7336  7336 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae7e59e
08-16 16:41:49.598  7336  7336 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-16 16:41:49.599  7336  7336 V BluetoothMapService: BluetoothMapBinder()
,08-16 16:41:49.600  7336  7336 D BluetoothMapService: Received start request. Starting profile...
08-16 16:41:49.600  7336  7336 D BluetoothMapService: start()
08-16 16:41:49.604  7336  7336 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 16:41:49.604  7336  7336 D BluetoothMapEmailAppObserver: createReceiver()
08-16 16:41:49.605  7336  7336 D BluetoothMapEmailAppObserver: initObservers()
08-16 16:41:49.605  7336  7336 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-16 16:41:49.615  7336  7336 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae7e59e
08-16 16:41:49.615  7336  7336 D HeadsetStateMachine: Proxy object connected
08-16 16:41:49.616  7336  7336 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 16:41:49.616  7336  7336 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-16 16:41:49.621  7336  7336 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 16:41:49.622  7336  7931 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 16:41:49.623  7336  7931 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 16:41:49.623  7336  7931 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-16 16:41:49.627  7336  7336 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 16:41:49.630  7336  7336 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 16:41:49.635  7336  7336 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 16:41:49.635  7336  7336 V PanService: [BTUI] SIM Extra State :ABSENT
08-16 16:41:49.639  7336  7336 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 16:41:49.642  7336  7336 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-16 16:41:49.642  7336  7336 V BluetoothMapService: Handler(): got msg=1
08-16 16:41:49.644  7336  7889 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 16:41:49.644  7336  7889 I bluedroid-qcom: enable
08-16 16:41:49.644  7336  7889 I bt_hci_bdroid: init
,08-16 16:41:49.646  7336  7889 I bt_vendor: bt-vendor : init
08-16 16:41:49.646  7336  7889 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 16:41:49.646  7336  7889 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 16:41:49.646  7336  7889 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 16:41:49.646  7336  7889 D bt_userial_mct: userial_init
08-16 16:41:49.647  7336  7336 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:49.650  7336  7889 D bt_hci_bdroid: set_power 1
08-16 16:41:49.650  7336  7889 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-16 16:41:49.650  7336  7889 I bt_vendor: Starting hciattach daemon
08-16 16:41:49.650  7336  7889 I bt_vendor: try to set true
08-16 16:41:49.650  7336  7336 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 16:41:49.650  7336  7950 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 16:41:49.650  7336  7950 I bt-btu  : btu_task pending for preload complete event
08-16 16:41:49.651  7336  7336 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 16:41:49.651  7336  7336 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 16:41:49.651  7336  7336 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:49.651  7336  7336 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-16 16:41:49.635  7953  7953 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 16:41:49.635  7953  7953 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 16:41:49.681  7954  7954 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 16:41:49.707  1035  2022 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7956 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 16:41:49.753  7980  7980 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 16:41:49.765  7982  7982 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 16:41:49.781  7956  7956 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 16:41:49.789  7990  7990 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-16 16:41:49.798  1035  1051 I ActivityManager: Killing 7373:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-16 16:41:49.799  7992  7992 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-16 16:41:49.814  7287  7287 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-16 16:41:49.814  7287  7287 W System.err: android.os.DeadObjectException
,08-16 16:41:49.814  7287  7287 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 16:41:49.815  7287  7287 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 16:41:49.815  7287  7287 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-16 16:41:49.815  7287  7287 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-16 16:41:49.815  7287  7287 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 16:41:49.815  7287  7287 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 16:41:49.815  7287  7287 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
,08-16 16:41:49.815  7287  7287 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 16:41:49.815  7287  7287 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 16:41:49.815  7287  7287 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 16:41:49.815  7287  7287 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 16:41:49.815  7287  7287 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 16:41:49.815  7287  7287 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 16:41:49.815  7287  7287 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 16:41:49.816  7287  7287 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-16 16:41:49.816  7287  7287 W System.err: android.os.DeadObjectException
08-16 16:41:49.816  7287  7287 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 16:41:49.816  7287  7287 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 16:41:49.816  7287  7287 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-16 16:41:49.816  7287  7287 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-16 16:41:49.816  7287  7287 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 16:41:49.816  7287  7287 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 16:41:49.816  7287  7287 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 16:41:49.816  7287  7287 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 16:41:49.816  7287  7287 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 16:41:49.816  7287  7287 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 16:41:49.816  7287  7287 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 16:41:49.816  7287  7287 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 16:41:49.816  7287  7287 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 16:41:49.817  7287  7287 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 16:41:49.817  7287  7287 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-16 16:41:49.817  7287  7287 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-16 16:41:49.818  7993  7993 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-16 16:41:49.829  7996  7996 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-16 16:41:49.850  7999  7999 I libmdmdetect: ESOC framework not supported
08-16 16:41:49.851  7999  7999 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-16 16:41:49.861  7999  7999 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-16 16:41:49.861  7999  7999 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-16 16:41:49.861  7999  7999 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-16 16:41:49.861  7999  7999 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 16:41:49.861  7999  7999 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-16 16:41:49.861  7999  7999 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-16 16:41:49.861  7999  7999 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-16 16:41:49.905  7999  8000 E QC-QMI  : qmi_client [7999] 14: failed to locate client data
,08-16 16:41:49.906   472   472 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-16 16:41:49.906   472   472 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-16 16:41:49.917  1035  1914 W libprocessgroup: failed to open /acct/uid_1000/pid_7373/cgroup.procs: No such file or directory
08-16 16:41:49.919  1035  1914 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-16 16:41:49.930  7287  7287 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-16 16:41:49.931  7287  7287 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 16:41:49.966  8001  8001 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 16:41:49.984  8002  8002 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 16:41:49.994  1035  2053 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8003 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 16:41:49.996  7287  7287 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-16 16:41:50.013  7336  7889 I bt_vendor: bluetooth satus is on
08-16 16:41:50.013  7336  7889 D bt_hci_bdroid: preload
08-16 16:41:50.014  7336  7952 D bt_userial_mct: userial_open(port:0)
08-16 16:41:50.014  7336  7952 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-16 16:41:50.017  7336  7952 I bt_vendor: Done intiailizing UART
08-16 16:41:50.018  7336  7952 I bt_vendor: Done intiailizing UART
08-16 16:41:50.018  7336  7952 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 16:41:50.018  7336  7952 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 16:41:50.019  7336  7950 I bt-btu  : btu_task received preload complete event
08-16 16:41:50.019  7336  8019 D bt_userial_mct: Entering userial_read_thread()
08-16 16:41:50.020  7336  7950 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 16:41:50.020  7336  7950 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-16 16:41:50.025  7336  7950 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-16 16:41:50.028  7336  7950 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 16:41:50.028  7336  7950 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 16:41:50.028  7336  7950 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 16:41:50.028  7336  7950 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 16:41:50.028  7336  7950 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 16:41:50.028  7336  7950 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 16:41:50.028  7336  7950 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 16:41:50.028  7336  7950 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 16:41:50.029  7336  7950 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 16:41:50.029  7336  7950 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 16:41:50.029  7336  7950 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 16:41:50.029  7336  7950 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 16:41:50.029  7336  7950 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 16:41:50.029  7336  7950 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 16:41:50.029  7336  7950 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 16:41:50.029  7336  7950 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 16:41:50.075  7336  7950 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-16 16:41:50.075  7336  7950 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa014b061 
,08-16 16:41:50.075  7336  7950 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa014b061 
,08-16 16:41:50.092  8003  8003 D UEI.SmartControl: Quickset Services start...
08-16 16:41:50.095  8003  8003 I UEI.SmartControl: Manufacture = LGE
08-16 16:41:50.095  8003  8003 D UEI.SmartControl: Id = LGNevo
,08-16 16:41:50.096  7336  7893 E bt-btif : Calling BTA_HhEnable
08-16 16:41:50.097  8003  8003 D UEI.SmartControl: File observer start...
08-16 16:41:50.097  7336  7950 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-16 16:41:50.097  7336  7950 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-16 16:41:50.097  7336  7950 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 16:41:50.096  7336  7893 E bt-btif : L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 16:41:50.098  8003  8003 E UEI.SmartControl: IR Port is disabled: false
08-16 16:41:50.098  7336  7893 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 16:41:50.098  8003  8003 D UEI.SmartControl: Starting file observer...
,08-16 16:41:50.098  8003  8003 D UEI.SmartControl: Extracting JNI libs...
08-16 16:41:50.098  8003  8003 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-16 16:41:50.100  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 16:41:50.101  7336  7950 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 16:41:50.101  7336  7950 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-16 16:41:50.101  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 16:41:50.102  7336  7893 D BluetoothAdapterProperties: Name is: G3
08-16 16:41:50.103  7336  7893 D BluetoothAdapterProperties: Scan Mode:20
,08-16 16:41:50.104  7336  7893 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 16:41:50.104  7336  7893 D bt_hci_bdroid: postload
08-16 16:41:50.104  7336  7952 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 16:41:50.105  7336  7952 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 16:41:50.106  7336  7950 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
,08-16 16:41:50.107  7336  7893 D bte_conf: Device ID record 1 : primary
08-16 16:41:50.107  7336  7893 D bte_conf:   vendorId            = 00c4
08-16 16:41:50.107  7336  7893 D bte_conf:   vendorIdSource      = 0001
08-16 16:41:50.107  7336  7893 D bte_conf:   product             = 13a1
,08-16 16:41:50.107  7336  7893 D bte_conf:   version             = 1000
08-16 16:41:50.107  7336  7893 D bte_conf:   clientExecutableURL = 
08-16 16:41:50.107  7336  7893 D bte_conf:   serviceDescription  = 
08-16 16:41:50.107  7336  7893 D bte_conf:   documentationURL    = 
,08-16 16:41:50.107  7336  7893 D bte_conf: bte_load_did_conf no section named DID2.
08-16 16:41:50.108  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:50.109  7336  7952 D bt_hci_bdroid: Used up Tx Cmd credits
,08-16 16:41:50.095  8024  8024 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 16:41:50.109  7336  7952 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 16:41:50.111  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:50.095  8024  8024 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 16:41:50.114  7336  7893 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 16:41:50.114  7336  7889 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-16 16:41:50.115  7336  7889 D BluetoothAdapterProperties: ScanMode =  20
08-16 16:41:50.115  7336  7889 D BluetoothAdapterProperties: State =  11
08-16 16:41:50.115  7336  7889 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 16:41:50.116  7336  7889 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 16:41:50.116  7336  7889 D BluetoothAdapterProperties: Setting state to 12
08-16 16:41:50.116  7336  7889 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 16:41:50.117  7336  7950 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 16:41:50.117  7336  7950 W bt-smp  : Plain text(LSB ~ MSB) = ec 85 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 16:41:50.117  7336  7950 W bt-smp  : Encrypted text(LSB ~ MSB) = 12 40 d9 8b a6 f6 4a 57 9e 43 41 b2 39 d0 8c d7 
08-16 16:41:50.117  7336  7952 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 16:41:50.118  7336  7950 W bt-btm  : Stopping oneshot timer
08-16 16:41:50.119  7336  7893 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 16:41:50.120  7336  8019 E bt_mct  : hci lib postload completed
08-16 16:41:50.121  1035  1117 D BluetoothManagerService: Message: 60
08-16 16:41:50.121  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 16:41:50.121  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-16 16:41:50.122  7336  7889 I BluetoothAdapterState: Entering On State
08-16 16:41:50.124  7336  7889 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 16:41:50.124  7336  7889 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 16:41:50.124  7336  7889 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-16 16:41:50.125  7336  7889 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-16 16:41:50.126  7218  7235 D BluetoothPan: onBluetoothStateChange on: true
08-16 16:41:50.126  7218  7235 D BluetoothPan: onBluetoothStateChange call bindService
08-16 16:41:50.130  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:41:50.130  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:50.130  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:50.130  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:41:50.130  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:41:50.130  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:41:50.130  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:41:50.130  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 16:41:50.133  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:41:50.135  7218  7236 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 16:41:50.138  7218  7218 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 16:41:50.138  7218  7218 D PanProfile: Bluetooth service connected
08-16 16:41:50.138  7336  7950 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 16:41:50.139  7336  7950 W bt-smp  : Plain text(LSB ~ MSB) = 8d 0b 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 16:41:50.139  7336  7950 W bt-smp  : Encrypted text(LSB ~ MSB) = 87 cc f3 48 7b 3d 23 dc 95 94 cb d6 3f 19 b3 de 
08-16 16:41:50.139  7336  7950 W bt-btm  : Stopping oneshot timer
08-16 16:41:50.141  1862  1877 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 16:41:50.143  7218  7218 D BluetoothInputDevice: Proxy object connected
08-16 16:41:50.143  7218  7218 D HidProfile: Bluetooth service connected
,08-16 16:41:50.146  7336  7893 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 16:41:50.146  7336  7893 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-16 16:41:50.148  7218  7408 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 16:41:50.150  1862  1862 D BluetoothHeadset: Proxy object connected
08-16 16:41:50.151  7218  7236 D BluetoothMap: onBluetoothStateChange: up=true
08-16 16:41:50.153  1862  1878 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 16:41:50.154  7218  7218 D BluetoothMap: Proxy object connected
08-16 16:41:50.154  7218  7218 D MapProfile: Bluetooth service connected
08-16 16:41:50.154  7218  7218 D BluetoothMap: getConnectedDevices()
08-16 16:41:50.155  7336  7353 V BluetoothMapService: getConnectedDevices()
08-16 16:41:50.155  7336  7950 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 16:41:50.155  7336  7950 W bt-smp  : Plain text(LSB ~ MSB) = 2c 53 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 16:41:50.155  7336  7950 W bt-smp  : Encrypted text(LSB ~ MSB) = 8d 17 14 63 45 1b 3f 61 a1 f3 2d ce a0 8b f4 cc 
08-16 16:41:50.155  7336  7950 W bt-btm  : Stopping oneshot timer
,08-16 16:41:50.156  1862  1862 D BluetoothHeadset: Proxy object connected
08-16 16:41:50.157  1862  2520 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 16:41:50.159  1862  1862 D BluetoothHeadset: Proxy object connected
08-16 16:41:50.160  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 16:41:50.160  1035  1035 D BluetoothHeadset: Proxy object connected
08-16 16:41:50.161  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 16:41:50.162  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 16:41:50.162  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 16:41:50.164  1035  1035 D BluetoothA2dp: Proxy object connected
08-16 16:41:50.169  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 16:41:50.170  1959  1959 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:50.170  7336  7950 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 16:41:50.171  7336  7950 W bt-smp  : Plain text(LSB ~ MSB) = 72 35 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 16:41:50.171  7336  7950 W bt-smp  : Encrypted text(LSB ~ MSB) = 81 55 0f 2b db 00 35 02 9b 1f 55 99 3f 08 bb 7a 
08-16 16:41:50.171  7336  7950 W bt-btm  : Stopping oneshot timer
08-16 16:41:50.171  1959  2148 D LGBluetoothAPIService: Message: 1
08-16 16:41:50.171  1959  2148 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-16 16:41:50.172  7336  7889 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-16 16:41:50.173  8030  8030 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-16 16:41:50.174  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,08-16 16:41:50.175  7049  7049 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 16:41:50.176  1035  1117 D BluetoothManagerService: Message: 40
08-16 16:41:50.176  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-16 16:41:50.179  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:41:50.179  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:50.179  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:50.179  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:41:50.179  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:41:50.179  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:41:50.179  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:41:50.179  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:41:50.180  7336  7336 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:50.180  7336  7336 D BluetoothMapService: STATE_ON
08-16 16:41:50.181  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:41:50.181  1959  2148 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-16 16:41:50.182  7218  7218 D LocalBluetoothProfileManager: Adding local A2DP profile
08-16 16:41:50.184  1035  1117 D BluetoothManagerService: Message: 30
08-16 16:41:50.184  7336  7950 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 16:41:50.184  7336  7950 W bt-smp  : Plain text(LSB ~ MSB) = 75 e3 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 16:41:50.184  7336  7950 W bt-smp  : Encrypted text(LSB ~ MSB) = ec e2 df 9a 9f 91 7b 61 59 01 9c cf a5 44 99 9b 
08-16 16:41:50.184  7336  7950 W bt-btm  : Stopping oneshot timer
08-16 16:41:50.185  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:41:50.185  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:50.185  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:50.185  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:41:50.185  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:41:50.185  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:41:50.185  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:41:50.185  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:41:50.187  7218  7218 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-16 16:41:50.190  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:41:50.192  1035  1117 D BluetoothManagerService: Message: 30
08-16 16:41:50.192  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:50.195  7218  7218 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 16:41:50.196  7218  7218 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 16:41:50.197  7336  7336 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae7e59e
08-16 16:41:50.197  7336  7336 V BluetoothPbapService: Pbap Service onCreate
08-16 16:41:50.197  7336  7336 V BluetoothPbapService: Starting PBAP service
08-16 16:41:50.198  7336  7336 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
,08-16 16:41:50.198  7336  7336 V BluetoothPbapService: Pbap Service onBind
08-16 16:41:50.198  7218  7218 D BluetoothA2dp: Proxy object connected
08-16 16:41:50.199  7218  7218 D A2dpProfile: Bluetooth service connected
08-16 16:41:50.201  7336  7336 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:50.201  7336  7336 V BluetoothPbapService: state: 12
08-16 16:41:50.201  7218  7218 D BluetoothHeadset: Proxy object connected
08-16 16:41:50.201  7336  7336 V BluetoothMapService: Handler(): got msg=1
08-16 16:41:50.202  7218  7218 D HeadsetProfile: Bluetooth service connected
08-16 16:41:50.202  7336  7336 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 16:41:50.204  7336  8032 D BluetoothMapMasInstance: MAS initSocket()
08-16 16:41:50.204  7336  8032 D BluetoothMapMasInstance:   masId = 00
08-16 16:41:50.204  7336  8032 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 16:41:50.204  7336  8032 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 16:41:50.204  7336  8032 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-16 16:41:50.204  7336  7336 D LGBluetoothAPIServer: [BTUI] onCreate()
08-16 16:41:50.204  7336  7336 D LGBluetoothAPIServer: [BTUI] onBind()
08-16 16:41:50.205  7336  7336 V BluetoothPbapService: Handler(): got msg=1
08-16 16:41:50.205  1959  1959 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 16:41:50.205  1959  2148 D LGBluetoothAPIService: Message: 100
08-16 16:41:50.205  1959  2148 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-16 16:41:50.206  7336  7336 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-16 16:41:50.206  7336  7336 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 16:41:50.206  7336  7336 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:50.206  7336  7336 V BluetoothPbapReceiver: ***********state = 12
08-16 16:41:50.207  7336  8034 V BluetoothPbapService: Pbap Service initSocket
08-16 16:41:50.207  1035  2086 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 16:41:50.209  2205  2205 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 16:41:50.210  2205  2205 D c       : Getting all permits...
08-16 16:41:50.210  2205  2205 D a       : Opening database...
08-16 16:41:50.213  2205  2205 D a       : Opening database auth.proximity.permit_store...
08-16 16:41:50.214  1035  1792 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 16:41:50.214  2205  2205 D a       : Closing database...
08-16 16:41:50.214  7218  7218 D DockEventReceiver: finishStartingService: stopping service
08-16 16:41:50.215  7218  7218 D BluetoothPbap: Proxy object connected
08-16 16:41:50.216  7218  7218 D PbapServerProfile: Bluetooth service connected
08-16 16:41:50.222  7336  8034 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 16:41:50.222  7336  8032 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 16:41:50.225  7336  7893 D BluetoothAdapterProperties: Scan Mode:21
08-16 16:41:50.225  7336  7893 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 16:41:50.225  7336  8032 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=0
08-16 16:41:50.226  7336  8032 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 16:41:50.226  7336  8032 D BluetoothMapMasInstance: Accepting socket connection...
08-16 16:41:50.226  7336  8034 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=75
08-16 16:41:50.226  7336  8034 V BluetoothPbapService: Succeed to create listening socket 
08-16 16:41:50.226  7336  8034 V BluetoothPbapService: Accepting socket connection...
08-16 16:41:50.227  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:50.228  7218  7218 D BluetoothPermissionRequest: onReceive
,08-16 16:41:50.228  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:50.229  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:50.230  8003  8003 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-16 16:41:50.230  8003  8003 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-16 16:41:50.230  8003  8003 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-16 16:41:50.232  7218  7218 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 16:41:50.234  7218  7218 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 16:41:50.237  7336  7336 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-16 16:41:50.239  7336  7336 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-16 16:41:50.243  7336  7336 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-16 16:41:50.255  8003  8003 I UEI.SmartControl: --- Selecting new region: 6
08-16 16:41:50.256  8003  8003 I UEI.SmartControl: Model = LG-D855
08-16 16:41:50.257  8003  8003 D UEI.SmartControl: QS Service created
08-16 16:41:50.260  7336  7336 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 16:41:50.260  7336  7336 V BtOppService: onCreate
,08-16 16:41:50.263  7336  7336 V BluetoothOppNotification: send message
08-16 16:41:50.265  7336  7336 V BtOppService: Starting RfcommListener
08-16 16:41:50.268  7336  7336 D BluetoothOppPreference: Dumping Names:  
08-16 16:41:50.268  8003  8003 I UEI.SmartControl: Service initServices...
08-16 16:41:50.268  7336  7336 D BluetoothOppPreference: {}
08-16 16:41:50.269  7336  7336 D BluetoothOppPreference: Dumping Channels:  
08-16 16:41:50.269  7336  7336 D BluetoothOppPreference: {}
08-16 16:41:50.269  7336  7336 V BtOppService: onStartCommand
08-16 16:41:50.272  7336  8040 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 16:41:50.274  7336  8037 V BtOppService: Deleted complete outbound shares, number =  0
,08-16 16:41:50.275  7336  7336 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:50.275  7336  7336 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-16 16:41:50.275  7336  8037 V BtOppService: Deleted complete inbound failed shares, number = 0
08-16 16:41:50.276  7336  8037 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-16 16:41:50.277  7336  8037 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ab4636b on behalf of 
08-16 16:41:50.277  7336  8040 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 16:41:50.278  7336  7336 V BluetoothOppNotification: new notify threadi!
08-16 16:41:50.278  8003  8003 D UEI.SmartControl: QS start get config
08-16 16:41:50.278  7336  7336 V BluetoothOppNotification: send delay message
08-16 16:41:50.279  7336  7336 V BtOppService: start RfcommListener
08-16 16:41:50.281  7336  7336 V BtOppService: RfcommListener started
08-16 16:41:50.281  7336  8041 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 16:41:50.281  7336  7336 V BtOppService: ContentObserver received notification
08-16 16:41:50.281  7336  7336 V BtOppService: ContentObserver received notification
08-16 16:41:50.282  7336  8040 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24db1ec8 on behalf of 
08-16 16:41:50.283  7336  8041 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b5d3b61 on behalf of 
08-16 16:41:50.284  7336  8042 V BtOppRfcommListener: Starting RFCOMM listener....
08-16 16:41:50.284  7336  8041 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 16:41:50.285  1035  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 16:41:50.286  7336  8041 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 16:41:50.288  7336  8041 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@cd00686 on behalf of 
08-16 16:41:50.288  7336  8042 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 16:41:50.289  7336  8040 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 16:41:50.289  7336  8040 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-16 16:41:50.290  7336  8042 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=73
08-16 16:41:50.290  7336  8040 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2833cb47 on behalf of 
08-16 16:41:50.290  7336  8042 V BtOppRfcommListener: Started RFCOMM listener....
08-16 16:41:50.291  7336  8042 I BtOppRfcommListener: Accept thread started.
08-16 16:41:50.291  7336  8040 V BluetoothOppNotification: update too frequent, put in queue
08-16 16:41:50.291  7336  8042 V BtOppRfcommListener: Accepting connection...
08-16 16:41:50.291  7336  8040 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 16:41:50.294  7336  7336 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae7e59e
08-16 16:41:50.294  7336  7336 V BluetoothFtpService: Ftp Service onCreate
08-16 16:41:50.294  7336  7336 I BluetoothFtpService: Ftp Service onCreate
08-16 16:41:50.294  7336  7336 V BluetoothFtpService: Ftp Service onStartCommand
08-16 16:41:50.294  7336  7336 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:50.294  7336  7336 V BluetoothFtpService: Starting Listening on sockets
08-16 16:41:50.294  7336  7336 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 16:41:50.295  7336  7336 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 16:41:50.295  7336  7336 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 16:41:50.295  7336  7336 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:50.295  7336  7336 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 16:41:50.295  7336  7336 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 16:41:50.296  7336  8041 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 16:41:50.296  7336  7336 V BluetoothFtpService: Handler(): got msg=1
08-16 16:41:50.298  7336  7336 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-16 16:41:50.298  7336  7336 V BluetoothFtpService: Ftp Service initSocket
08-16 16:41:50.300  1035  2086 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 16:41:50.301  7336  7336 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 16:41:50.303  7336  7336 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-16 16:41:50.304  7336  7336 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-16 16:41:50.305  7336  8041 V BluetoothOppNotification: outbound notification was removed.
08-16 16:41:50.305  7336  8043 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-16 16:41:50.305  7336  8041 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 16:41:50.307  7336  8041 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a512c9d on behalf of 
08-16 16:41:50.307  7336  8041 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 16:41:50.309  7336  8041 V BluetoothOppNotification: inbound notification was removed.
08-16 16:41:50.309  7336  8041 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-16 16:41:50.310  7336  8041 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e960512 on behalf of 
08-16 16:41:50.331  7336  7336 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae7e59e
08-16 16:41:50.331  7336  7336 V BluetoothSapService: Sap Service onCreate
,08-16 16:41:50.333  7336  7336 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:50.333  7336  7336 V BluetoothSapService: state: 12
08-16 16:41:50.333  7336  7336 V BluetoothSapService: Starting SAP server process
08-16 16:41:50.334  7336  7336 V BluetoothSapService: SAP Service startRfcommListenerThread
08-16 16:41:50.325  8044  8044 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 16:41:50.336  7336  8045 V BluetoothSapService: Sap Service initRfcommSocket
08-16 16:41:50.325  8044  8044 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 16:41:50.336  1035  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 16:41:50.337  7336  8045 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 16:41:50.338  7336  8045 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-16 16:41:50.338  7336  8045 V BluetoothSapService: Succeed to create listening socket 
08-16 16:41:50.338  7336  8045 V BluetoothSapService: Accepting socket connection...
08-16 16:41:50.339  8003  8003 D UEI.SmartControl: Loading JNI Libs...
08-16 16:41:50.341  8044  8044 V BT_SAP  : Event pipe created
08-16 16:41:50.341  8044  8044 V BT_SAP  : create_server_socket qcom.sap.server
08-16 16:41:50.341  8044  8044 V BT_SAP  : created socket fd 6
08-16 16:41:50.685  8003  8003 I UEI.SmartControl: Supports setup maps: true
,08-16 16:41:50.691  8003  8003 D UEI.SmartControl: QS start statue = true Error code = 0
,08-16 16:41:50.692  8003  8003 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 16:41:50.692  8003  8003 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-16 16:41:50.692  8003  8003 I UEI.SmartControl: ### init IR Blaster...
08-16 16:41:50.698  8003  8003 D serial_port: Configuring serial port
08-16 16:41:50.704  8003  8003 E UEI.SmartControl: UEIBLaster setting for 616
08-16 16:41:50.704  8003  8003 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 16:41:50.706  8003  8003 I UEI.SmartControl: configuring settings for MAXQ616
08-16 16:41:50.707  8003  8003 I UEI.SmartControl: Get version...,
,08-16 16:41:50.723  8003  8052 D UEI.SmartControl: serial port data available: 21
,08-16 16:41:50.751  8003  8003 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-16 16:41:50.751  8003  8003 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-16 16:41:50.753  8003  8003 I UEI.SmartControl: QS saving settings...
08-16 16:41:50.768  8003  8003 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 16:41:50.792  8003  8052 D UEI.SmartControl: serial port data available: 4
,08-16 16:41:50.832  8003  8003 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-16 16:41:50.841  8003  8058 I UEI.SmartControl: Device manager: loading config....
08-16 16:41:50.841  8003  8058 D UEI.SmartControl: ----------- loading internal config...
08-16 16:41:50.848  8003  8003 E UEI.SmartControl: Services init done
08-16 16:41:50.848  8003  8003 D UEI.SmartControl: QS Service init finished
,08-16 16:41:50.853  8003  8003 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 16:41:50.853  8003  8003 D UEI.SmartControl: QS Service version code: 201091
08-16 16:41:50.871  1589  1589 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-16 16:41:50.906  1035  1464 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 16:41:50.962  1035  1113 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8060 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-16 16:41:50.983  2078  2078 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 16:41:50.988  8003  8003 D UEI.SmartControl: Service requested: Control
08-16 16:41:50.990  1589  1589 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-16 16:41:50.990  8003  8058 E UEI.SmartControl: Loading SETTINGS...
08-16 16:41:50.990  1589  1589 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-16 16:41:50.998  8003  8003 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-16 16:41:51.003  7287  7287 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-16 16:41:51.003  8003  8020 I UEI.SmartControl: ------ IControl API: 11
08-16 16:41:51.004  8003  8020 I UEI.SmartControl: Registering callback...
08-16 16:41:51.005  1035  2022 I ActivityManager: Killing 7287:com.lge.qremote/u0a112 (adj 15): empty #17
08-16 16:41:51.005  8003  8021 I UEI.SmartControl: ------ IControl API: 19
08-16 16:41:51.006  8003  8021 I UEI.SmartControl: Registering Services Ready callback...
08-16 16:41:51.007  1035  1035 D administrator: Handling package changes for user 0
08-16 16:41:51.012  8003  8058 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-16 16:41:51.013  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 16:41:51.027  8003  8057 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 16:41:51.027  8003  8057 D UEI.SmartControl: -----service ready thread exits
,08-16 16:41:51.086  8003  8003 D UEI.SmartControl: Internal service binding...
,08-16 16:41:51.092  1035  2077 W libprocessgroup: failed to open /acct/uid_10112/pid_7287/cgroup.procs: No such file or directory
08-16 16:41:51.101  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-16 16:41:51.101  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 16:41:51.110  8060  8060 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 16:41:51.157  1035  1112 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 16:41:51.164  1035  1112 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-16 16:41:51.174  2484  2484 V GmsNetworkLocationProvi: DISABLE
08-16 16:41:51.176  2078  2078 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-16 16:41:51.188  8060  8060 D LgDataFeature: LgDataFeature() Constructor: none
08-16 16:41:51.189  8060  8060 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 16:41:51.211  1035  1112 D LocationProviderProxy: applying state to connected service
08-16 16:41:51.212  2484  2484 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-16 16:41:51.280  7336  7336 V BluetoothOppNotification: new notify threadi!
,08-16 16:41:51.281  7336  7336 V BluetoothOppNotification: send delay message
08-16 16:41:51.282  7336  8105 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 16:41:51.284  7336  8105 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@254b605e on behalf of 
08-16 16:41:51.284  7336  8105 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 16:41:51.286  7336  8105 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 16:41:51.288  7336  8105 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f28dc3f on behalf of 
08-16 16:41:51.288  7336  8105 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 16:41:51.290  7336  8105 V BluetoothOppNotification: outbound notification was removed.
08-16 16:41:51.290  7336  8105 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 16:41:51.294  7336  8105 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f3b290c on behalf of 
08-16 16:41:51.294  7336  8105 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 16:41:51.297  7336  8105 V BluetoothOppNotification: inbound notification was removed.
08-16 16:41:51.297  7336  8105 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-16 16:41:51.298  7336  8105 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2dfa5255 on behalf of 
,08-16 16:41:51.326  8060  8108 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-16 16:41:51.329  8060  8108 I Babel   : MmsConfig.loadMmsSettings
08-16 16:41:51.333  8060  8108 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 16:41:51.333  8060  8108 I Babel   : MmsConfig.loadFromDatabase
,08-16 16:41:51.350  8060  8108 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-16 16:41:51.350  8060  8108 I Babel   : MmsConfig.loadFromResources
08-16 16:41:51.353  8060  8108 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-16 16:41:51.353  8060  8108 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 16:41:51.354  8060  8106 W AudioCapabilities: Unsupported mime audio/evrc
08-16 16:41:51.356  8060  8106 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 16:41:51.358  8060  8106 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 16:41:51.363  8060  8060 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:41:51.376  8060  8106 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-16 16:41:51.380  8060  8106 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 16:41:51.385  8060  8106 W AudioCapabilities: Unsupported mime audio/evrc
08-16 16:41:51.396  1826  8109 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-16 16:41:51.396  1826  8109 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-16 16:41:51.398  6888  6888 I AppUp4:CustModeStarterReceiver: onReceive
08-16 16:41:51.409  6888  6888 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1356dadd
,08-16 16:41:51.409  6888  6888 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 16:41:51.409  6888  6888 D AppUp4:CustFacade: isPhone : true
08-16 16:41:51.409  6888  6888 D AppUp4:CustModeStarterReceiver: begin check event
08-16 16:41:51.409  6888  6888 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-16 16:41:51.413  1826  5104 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-16 16:41:51.418  8060  8106 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-16 16:41:51.426  8060  8106 W VideoCapabilities: Unsupported mime video/divx
08-16 16:41:51.429  8060  8106 W VideoCapabilities: Unsupported mime video/divx311
08-16 16:41:51.450  1035  2022 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8112 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-16 16:41:51.451  8060  8106 W VideoCapabilities: Unsupported mime video/divx4
08-16 16:41:51.461  8060  8106 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-16 16:41:51.469  1035  1913 I ActivityManager: Killing 7636:com.lge.sync/1000 (adj 15): empty #17
,08-16 16:41:51.487  8060  8106 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 16:41:51.490  8060  8106 W AudioCapabilities: Unsupported mime audio/eac3
08-16 16:41:51.491  8060  8106 W AudioCapabilities: Unsupported mime audio/ac3
08-16 16:41:51.492  8060  8106 W AudioCapabilities: Unsupported mime audio/g726
08-16 16:41:51.493  8060  8106 W AudioCapabilities: Unsupported mime audio/wma-voice
08-16 16:41:51.494  8060  8106 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-16 16:41:51.494  8060  8106 W AudioCapabilities: Unsupported mime audio/adpcm
08-16 16:41:51.496  8060  8106 W VideoCapabilities: Unsupported mime video/theora
08-16 16:41:51.498  8060  8106 W VideoCapabilities: Unsupported mime video/mjpg
,08-16 16:41:51.569  1035  1956 W libprocessgroup: failed to open /acct/uid_1000/pid_7636/cgroup.procs: No such file or directory
,08-16 16:41:51.608  8112  8112 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 16:41:51.608  8112  8112 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 16:41:51.608  8112  8112 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 16:41:51.610  8112  8112 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-16 16:41:51.610  8112  8112 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-16 16:41:51.704  8112  8112 I SystemConfig: BUILD Country: EU
08-16 16:41:51.704  8112  8112 I SystemConfig: BUILD Operator: OPEN
,08-16 16:41:51.759  1035  1913 I ActivityManager: Killing 7729:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-16 16:41:51.796  1035  1792 W libprocessgroup: failed to open /acct/uid_10005/pid_7729/cgroup.procs: No such file or directory
,08-16 16:41:51.849  1035  2022 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8133 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-16 16:41:51.857  8112  8131 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-16 16:41:51.857  8112  8131 I SystemConfig: existFile = false
08-16 16:41:51.857  8112  8131 I SystemConfig: canReadFile = false
08-16 16:41:51.857  8112  8131 I SystemConfig: systemFeature RCS result false
08-16 16:41:51.858  8112  8131 D SystemConfig: refreshRcsSupport() :false
,08-16 16:41:51.920  8133  8133 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 16:41:51.920  8133  8133 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 16:41:51.921  8133  8133 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 16:41:51.921  8133  8133 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 16:41:52.042  8133  8133 I AppConfig: Total System Memory = 2995761152
,08-16 16:41:52.055  8133  8133 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-16 16:41:52.148  1035  1562 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8158 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 16:41:52.151  1035  1562 I ActivityManager: Killing 7433:com.lge.email/u0a23 (adj 15): empty #17
,08-16 16:41:52.216  1035  1914 W libprocessgroup: failed to open /acct/uid_10023/pid_7433/cgroup.procs: No such file or directory
,08-16 16:41:52.388  8158  8158 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-16 16:41:52.462  8158  8158 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 16:41:52.463  8158  8158 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 16:41:52.510  8158  8158 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-16 16:41:52.529  8158  8158 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 16:41:52.532  8158  8158 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-16 16:41:52.562  8158  8158 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-16 16:41:52.562  8158  8158 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-16 16:41:52.583  1035  1982 I ActivityManager: Killing 7311:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-16 16:41:52.617  1035  1792 W libprocessgroup: failed to open /acct/uid_10026/pid_7311/cgroup.procs: No such file or directory
,08-16 16:41:52.625  4923  8195 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-16 16:41:52.626  2862  2887 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-16 16:41:52.636  2862  2887 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@c2f5e2d on behalf of 8158
,08-16 16:41:52.678  1035  1914 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8196 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-16 16:41:52.705   354   354 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 474us total 30.239ms
,08-16 16:41:52.730   354   354 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 437us total 22.223ms
08-16 16:41:52.767   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.347ms total 36.289ms
,08-16 16:41:52.770  8158  8158 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-16 16:41:52.785  8158  8158 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-16 16:41:52.790  8196  8196 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-16 16:41:52.811  8196  8196 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-16 16:41:52.811  8196  8196 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-16 16:41:52.812  8196  8196 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-16 16:41:52.812  8196  8196 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-16 16:41:52.812  8196  8196 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-16 16:41:52.812  8196  8196 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-16 16:41:52.826  1035  1792 I ActivityManager: Killing 6342:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-16 16:41:52.861  1035  1913 W libprocessgroup: failed to open /acct/uid_1000/pid_6342/cgroup.procs: No such file or directory
,08-16 16:41:53.141  1035  1051 V SIM_STK : Menu title from STK is T-Mobile
,08-16 16:41:53.155  4923  8195 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 525 ms] updated apps [took 525 ms] 
,08-16 16:41:53.888  1035  2053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 16:41:53.889  1035  2053 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2a5ad366 mBinding = false
,08-16 16:41:53.925  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 16:41:53.926  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 16:41:53.926  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-16 16:41:53.929  1035  1117 D BluetoothManagerService: Message: 2
08-16 16:41:53.930  1035  1117 D BluetoothManagerService: Sending off request.
08-16 16:41:53.931  7336  8026 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 16:41:53.932  7336  7889 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 16:41:53.932  7336  7889 D BluetoothAdapterProperties: Setting state to 13
08-16 16:41:53.932  7336  7889 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 16:41:53.933  7336  7889 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 16:41:53.933  7336  7889 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 16:41:53.935  7336  7893 D BluetoothAdapterProperties: Scan Mode:20
08-16 16:41:53.936  7336  7889 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 16:41:53.937  7336  8034 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 16:41:53.940  7336  8032 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 16:41:53.940  7336  8032 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 16:41:53.940  7336  8032 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 16:41:53.940  7336  8032 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 16:41:53.940  7336  8032 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 16:41:53.940  7336  8032 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 16:41:53.940  7336  8032 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 16:41:53.940  7336  8032 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-16 16:41:53.943  7336  8042 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 16:41:53.944  7336  7889 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 16:41:53.946  7336  8045 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 16:41:53.947  7336  7950 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-16 16:41:53.947  7336  7950 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-16 16:41:53.946  7336  8043 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 16:41:53.950  7336  7950 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 16:41:53.950  7336  7950 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 16:41:53.950  7336  7950 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 16:41:53.950  7336  7950 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 16:41:53.950  7336  7950 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 16:41:53.950  7336  7950 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 16:41:53.950  7336  7950 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 16:41:53.950  7336  7950 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 16:41:53.950  7336  7950 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 16:41:53.950  7336  7950 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 16:41:53.950  7336  7950 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 16:41:53.950  7336  7950 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 16:41:53.955  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:53.956  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:41:53.956  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:53.956  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:53.956  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:41:53.956  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:41:53.956  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:41:53.956  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:41:53.956  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 16:41:53.960  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:53.960  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:41:53.972  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:53.972  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:41:53.972  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:53.972  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:53.972  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:41:53.972  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:41:53.972  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:41:53.972  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:41:53.972  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 16:41:53.976  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:53.976  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:41:53.978  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:53.978  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:41:53.978  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:41:53.978  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:41:53.978  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:41:53.978  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 16:41:53.978  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:41:53.978  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:41:53.978  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:41:53.980  7049  7049 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 16:41:53.980  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:41:53.981  1035  1117 D BluetoothManagerService: Message: 60
08-16 16:41:53.981  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 16:41:53.981  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-16 16:41:53.983  1959  1959 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:53.984  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 16:41:53.986  1035  1531 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-16 16:41:53.993  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:53.995  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:53.996  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:53.999  7336  7336 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:53.999  7336  7336 D BluetoothMapService: STATE_TURNING_OFF
08-16 16:41:53.999  7336  7336 V BluetoothMapService: Handler(): got msg=4
08-16 16:41:53.999  7336  7336 D BluetoothMapService: MAP Service closeService in
08-16 16:41:53.999  7336  7336 D BluetoothMapMasInstance: MAP Service shutdown
08-16 16:41:54.000  7336  7336 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 16:41:54.000  7336  7336 V BluetoothMapService: MAP Service closeService out
,08-16 16:41:54.003  7336  7336 V BtOppService: Receiver DISABLED_ACTION 
08-16 16:41:54.003  7336  7336 I BtOppRfcommListener: stopping Accept Thread
08-16 16:41:54.003  7336  7336 V BtOppRfcommListener: close mBtServerSocket
08-16 16:41:54.003  7336  8042 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 16:41:54.004  7336  7336 V BtOppRfcommListener: waiting for thread to terminate
08-16 16:41:54.004  7336  7336 V BtOppRfcommListener: done waiting for thread to terminate
,08-16 16:41:54.015  7218  7218 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-16 16:41:54.017  7218  7218 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 16:41:54.021  7336  7336 V BtOppService: onDestroy
08-16 16:41:54.022  7336  7336 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 16:41:54.025  7336  7336 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 16:41:54.025  7336  7336 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:54.025  7336  7336 V BluetoothPbapReceiver: ***********state = 13
,08-16 16:41:54.029  7336  7336 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-16 16:41:54.031  7336  7336 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:54.031  7336  7336 V BluetoothPbapService: state: 13
08-16 16:41:54.032  7336  7336 V BluetoothPbapService: Pbap Service closeService in
08-16 16:41:54.035  2205  2205 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 16:41:54.036  7336  7336 V BluetoothPbapService: successfully stopped pbap service
08-16 16:41:54.036  7336  7336 V BluetoothPbapService: Pbap Service closeService out
08-16 16:41:54.037  7336  7336 V BluetoothPbapService: Pbap Service onDestroy
08-16 16:41:54.037  7336  7336 V BluetoothPbapService: Pbap Service closeService in
08-16 16:41:54.037  7336  7336 V BluetoothPbapService: Pbap Service closeService out
08-16 16:41:54.037  7336  7336 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-16 16:41:54.064  7218  7218 D DockEventReceiver: finishStartingService: stopping service
,08-16 16:41:54.066  7218  7218 D BluetoothPbap: Proxy object disconnected
08-16 16:41:54.066  7218  7218 D PbapServerProfile: Bluetooth service disconnected
08-16 16:41:54.071  7218  7218 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-16 16:41:54.076  7218  7218 D BluetoothPermissionRequest: onReceive
,08-16 16:41:54.076  7218  7218 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-16 16:41:54.087  7218  7218 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 16:41:54.094  7336  7336 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-16 16:41:54.095  7336  7336 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-16 16:41:54.096  7336  7336 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-16 16:41:54.102  7336  7336 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:54.102  7336  7336 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 16:41:54.104  7336  7336 V BluetoothFtpService: Ftp Service onStartCommand
08-16 16:41:54.104  7336  7336 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:54.104  7336  7336 V BluetoothFtpService: Ftp Service closeService
08-16 16:41:54.104  7336  7336 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 16:41:54.105  7336  7336 V BluetoothFtpService: successfully stopped ftp service
08-16 16:41:54.106  7336  7336 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 16:41:54.106  7336  7336 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 16:41:54.106  7336  7336 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 16:41:54.106  7336  7336 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:54.106  7336  7336 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
,08-16 16:41:54.106  7336  7336 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 16:41:54.108  7336  7336 V BluetoothFtpService: Ftp Service onDestroy
08-16 16:41:54.108  7336  7336 V BluetoothFtpService: Ftp Service closeService
08-16 16:41:54.112  7336  7336 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:54.112  7336  7336 V BluetoothSapService: state: 13
08-16 16:41:54.112  7336  7336 V BluetoothSapService: Stopping SAP server process
08-16 16:41:54.115  7336  7336 V BluetoothSapService: Sap Service closeSapService in
08-16 16:41:54.115  7336  7336 V BluetoothSapService: Close listen Socket : 
08-16 16:41:54.115  7336  7336 V BluetoothSapService: Close rfcomm Socket : 
08-16 16:41:54.115  7336  7336 V BluetoothSapService: Close sapd  Socket : 
08-16 16:41:54.117  7336  7336 V BluetoothSapService: Sap Service closeSapService out
,08-16 16:41:54.118  7336  7336 V BluetoothSapService: Sap Service onDestroy
08-16 16:41:54.118  7336  7336 V BluetoothSapService: Sap Service closeSapService in
08-16 16:41:54.118  7336  7336 V BluetoothSapService: Close listen Socket : 
08-16 16:41:54.118  7336  7336 V BluetoothSapService: Close rfcomm Socket : 
08-16 16:41:54.118  7336  7336 V BluetoothSapService: Close sapd  Socket : 
08-16 16:41:54.123  7336  7336 V BluetoothSapService: Sap Service closeSapService out
,08-16 16:41:54.857  7336  7893 D bt_hci_bdroid: cleanup
,08-16 16:41:54.864  7336  7952 I bt_lpm  : LPM is already off!!!
08-16 16:41:54.866  7336  7950 W bt-btif : ag scb idx 1 not allocated
08-16 16:41:54.866  7336  7950 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 16:41:54.866  7336  7950 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 16:41:54.866  7336  7950 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 16:41:54.866  7336  7950 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 16:41:54.866  7336  7950 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 16:41:54.866  7336  7950 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 16:41:54.866  7336  7950 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 16:41:54.866  7336  7950 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 16:41:54.866  7336  7950 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 16:41:54.866  7336  7950 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 16:41:54.866  7336  7950 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 16:41:54.866  7336  7950 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 16:41:54.866  7336  7950 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 16:41:54.866  7336  7950 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 16:41:54.866  7336  7950 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 16:41:54.866  7336  7950 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 16:41:54.866  7336  7950 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 16:41:54.866  7336  7950 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 16:41:54.866  7336  7950 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 16:41:54.866  7336  7950 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 16:41:54.867  7336  8019 I bt_userial_mct: exiting userial_read_thread
08-16 16:41:54.867  7336  8019 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 16:41:54.868  7336  7893 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 16:41:54.868  7336  7952 I bt_vendor: hw_epilog_process
08-16 16:41:54.868  7336  7893 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 16:41:54.868  7336  7893 D bt_userial_mct: userial_close
08-16 16:41:54.868  7336  7893 E bt_userial_mct: pthread_join() FAILED result:3
08-16 16:41:54.868  7336  7893 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-16 16:41:54.876  7336  7893 D bt_hci_bdroid: set_power 0
08-16 16:41:54.876  7336  7893 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 16:41:54.876  7336  7893 I bt_vendor: bluetooth satus is on
08-16 16:41:54.876  7336  7893 I bt_vendor: bt-vendor : resetting BT status
08-16 16:41:54.876  7336  7893 I bt_vendor: Starting hciattach daemon
08-16 16:41:54.876  7336  7893 I bt_vendor: try to set false
,08-16 16:41:54.883  7336  7893 I bt_vendor: Starting hciattach daemon
08-16 16:41:54.883  7336  7893 I bt_vendor: try to set false
08-16 16:41:54.884  7336  7893 I bt_vendor: cleanup
08-16 16:41:54.885  7336  7950 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 16:41:54.885  7336  7893 I GKI_LINUX: GKI_exit_task 0 done
08-16 16:41:54.885  7336  7893 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 16:41:54.887  7336  7889 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 16:41:54.891  7336  7336 D HeadsetService: Received stop request...Stopping profile...
,08-16 16:41:54.895  7336  7336 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 16:41:54.895  7336  7336 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 16:41:54.895  7336  7336 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae7e59e
08-16 16:41:54.896  7336  7931 D HeadsetStateMachine: Exit Disconnected: -1
08-16 16:41:54.901  7336  7336 D A2dpService: Received stop request...Stopping profile...
08-16 16:41:54.901  7336  7939 D A2dpStateMachine: Exit Disconnected: -1
08-16 16:41:54.903  7336  7336 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-16 16:41:54.904  1035  1035 D BluetoothHeadset: Proxy object disconnected
08-16 16:41:54.904  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-16 16:41:54.907  1862  1862 D BluetoothHeadset: Proxy object disconnected
08-16 16:41:54.907  1862  1862 D BluetoothHeadset: Proxy object disconnected
08-16 16:41:54.908  1862  1862 D BluetoothHeadset: Proxy object disconnected
08-16 16:41:54.913  7336  7336 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 16:41:54.913  7336  7336 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 16:41:54.913  7336  7336 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae7e59e
08-16 16:41:54.915  7336  7889 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 16:41:54.916  1035  1035 D BluetoothA2dp: Proxy object disconnected
08-16 16:41:54.916  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-16 16:41:54.919  7336  7336 D HidService: Received stop request...Stopping profile...
08-16 16:41:54.919  7336  7336 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae7e59e
08-16 16:41:54.923  7336  7336 D HealthService: Received stop request...Stopping profile...
08-16 16:41:54.923  7336  7336 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae7e59e
08-16 16:41:54.924  7336  7336 D HeadsetStateMachine: Unbinding service...
08-16 16:41:54.926  7336  7336 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 16:41:54.926  7336  7336 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 16:41:54.926  7336  7336 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 16:41:54.926  7336  7336 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 16:41:54.926  7336  7336 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 16:41:54.926  7336  7336 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 16:41:54.926  7336  7336 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 16:41:54.927  7336  7336 D PanService: Received stop request...Stopping profile...
08-16 16:41:54.928  7336  7336 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae7e59e
,08-16 16:41:54.931  7336  7336 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 16:41:54.933  7336  7336 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 16:41:54.933  7336  7336 D BtGatt.GattService: stop()
08-16 16:41:54.934  7336  7336 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 16:41:54.935  7336  7336 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae7e59e
08-16 16:41:54.936  7336  7336 D BluetoothMapService: Received stop request...Stopping profile...
08-16 16:41:54.936  7336  7336 D BluetoothMapService: stop()
08-16 16:41:54.937  7336  7336 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 16:41:54.937  7336  7336 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 16:41:54.937  7336  7336 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ae7e59e
08-16 16:41:54.939  7336  7336 I BluetoothA2dpServiceJni: cleanupNative
,08-16 16:41:54.941  7336  7943 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 16:41:54.942  7336  7336 I GKI_LINUX: GKI_exit_task 2 done
08-16 16:41:54.942  7336  7336 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 16:41:54.942  7336  7336 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 16:41:54.942  7336  7336 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 16:41:54.943  7336  7336 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 16:41:54.944  7336  7336 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 16:41:54.944  7336  7336 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 16:41:54.944  7336  7336 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 16:41:54.944  7336  7336 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 16:41:54.946  7336  7336 V BluetoothMapService: Handler(): got msg=4
08-16 16:41:54.946  7336  7336 D BluetoothMapService: MAP Service closeService in
08-16 16:41:54.946  7336  7336 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 16:41:54.946  7336  7336 V BluetoothMapService: MAP Service closeService out
08-16 16:41:54.947  7336  7889 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 16:41:54.947  7336  7889 D BluetoothAdapterProperties: Setting state to 10
08-16 16:41:54.947  7336  7889 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 16:41:54.947  1035  1117 D BluetoothManagerService: Message: 60
08-16 16:41:54.947  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 16:41:54.947  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-16 16:41:54.948  7336  7889 I BluetoothAdapterState: Entering OffState
08-16 16:41:54.950  7336  7336 D BluetoothMapService: cleanup()
08-16 16:41:54.950  7336  7336 D BluetoothMapService: MAP Service closeService in
08-16 16:41:54.950  7336  7336 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 16:41:54.950  7336  7336 V BluetoothMapService: MAP Service closeService out
08-16 16:41:54.950  7218  7408 D BluetoothPan: onBluetoothStateChange on: false
,08-16 16:41:54.957  7218  7408 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 16:41:54.959  7218  7408 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 16:41:54.960  1862  2520 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 16:41:54.960  7218  7408 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 16:41:54.961  7218  7408 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 16:41:54.962  7218  7408 D BluetoothMap: onBluetoothStateChange: up=false
08-16 16:41:54.962  1862  4733 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 16:41:54.964  1862  1878 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 16:41:54.965  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 16:41:54.965  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 16:41:54.966  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 16:41:54.966  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-16 16:41:54.968  1035  1117 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 16:41:54.968  1035  1117 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 16:41:54.968  1035  1117 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2a5ad366 mBinding = false
08-16 16:41:54.969  1035  1117 D BluetoothManagerService: Sending unbind request.
08-16 16:41:54.973  7336  7893 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-16 16:41:54.975  7336  7336 I GKI_LINUX: GKI_exit_task 1 done
08-16 16:41:54.975  7336  7336 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 16:41:54.975  7336  7336 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 16:41:54.976  7336  7336 I art     : --- WEIRD: removing null entry 248
08-16 16:41:54.976  7336  7336 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-16 16:41:54.976  7336  7336 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,08-16 16:41:54.979  7336  7336 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-16 16:41:54.980  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-16 16:41:54.982  7336  7336 I art     : System.exit called, status: 0
08-16 16:41:54.982  7336  7336 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 16:41:55.002   326  4290 V AudioFlinger: 7336 died, releasing its sessions
08-16 16:41:55.002   326  4290 V AudioFlinger:  pid 1862 @ 0
08-16 16:41:55.002   326  4290 V AudioFlinger:  pid 3296 @ 1
08-16 16:41:55.002   326  4290 V AudioFlinger:  pid 3296 @ 2
,08-16 16:41:55.012  1959  1959 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-16 16:41:55.013  1959  2148 D LGBluetoothAPIService: Message: 101
08-16 16:41:55.013  7218  7218 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-16 16:41:55.013  1959  2148 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-16 16:41:55.013  1959  2148 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-16 16:41:55.013  1959  2148 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
,08-16 16:41:55.145  1035  1982 I ActivityManager: Process com.android.bluetooth (pid 7336) has died
,08-16 16:41:55.146  1035  1982 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-16 16:41:55.146  1035  1982 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
08-16 16:41:55.156  1959  1959 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:55.157  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 16:41:55.157  1959  2148 D LGBluetoothAPIService: Message: 2
08-16 16:41:55.157  1959  2148 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-16 16:41:55.161  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:41:55.164  7218  7218 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-16 16:41:55.164  7218  7218 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-16 16:41:55.165  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:55.167  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:41:55.171  7218  7218 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 16:41:55.174  1589  1589 D BluetoothAdapter: 351435803: getState() :  mService = null. Returning STATE_OFF
08-16 16:41:55.174  1589  1589 D BluetoothAdapter: 351435803: getState() :  mService = null. Returning STATE_OFF
08-16 16:41:55.215  1035  2053 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=8286 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-16 16:41:55.217  7218  7218 D DockEventReceiver: finishStartingService: stopping service
,08-16 16:41:55.405  1035  2022 I art     : Explicit concurrent mark sweep GC freed 29562(1478KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.470ms total 151.741ms
,08-16 16:41:55.439  8286  8286 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-16 16:41:55.440  8286  8286 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 16:41:55.440  8286  8286 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-16 16:41:55.441  8286  8286 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 16:41:55.460  8286  8286 D BluetoothAdapterApp: Loading JNI Library
,08-16 16:41:55.494  8286  8286 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2ee23c6 Instance Count = 1
,08-16 16:41:55.499  8286  8286 D BluetoothAdapterApp: onCreate
,08-16 16:41:55.523  8286  8286 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-16 16:41:55.524  8286  8286 D ProfileConfigQcom: Adding HeadsetService
08-16 16:41:55.524  8286  8286 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-16 16:41:55.524  8286  8286 D ProfileConfigQcom: Adding A2dpService
08-16 16:41:55.524  8286  8286 D ProfileConfigQcom: [BTUI] HidService is supported
08-16 16:41:55.525  8286  8286 D ProfileConfigQcom: Adding HidService
08-16 16:41:55.525  8286  8286 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 16:41:55.525  8286  8286 D ProfileConfigQcom: Adding HealthService
08-16 16:41:55.525  8286  8286 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-16 16:41:55.526  8286  8286 D ProfileConfigQcom: [BTUI] PanService is supported
08-16 16:41:55.526  8286  8286 D ProfileConfigQcom: Adding PanService
08-16 16:41:55.527  8286  8286 D ProfileConfigQcom: [BTUI] GattService is supported
08-16 16:41:55.527  8286  8286 D ProfileConfigQcom: Adding GattService
08-16 16:41:55.527  8286  8286 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 16:41:55.527  8286  8286 D ProfileConfigQcom: Adding BluetoothMapService
08-16 16:41:55.528  8286  8286 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 16:41:55.529  8286  8286 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 16:41:55.530  8286  8286 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:55.530  8286  8286 V BluetoothPbapReceiver: ***********state = 10
,08-16 16:41:55.532  8286  8286 V LGMDMManagerInternal: Create singleton instance
08-16 16:41:55.619  2205  2205 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 16:41:55.620  8286  8286 D LGBluetoothAPIServer: [BTUI] onCreate()
08-16 16:41:55.620  8286  8286 D LGBluetoothAPIServer: [BTUI] onBind()
,08-16 16:41:55.634  1959  1959 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 16:41:55.635  1959  2148 D LGBluetoothAPIService: Message: 100
,08-16 16:41:55.635  1959  2148 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,08-16 16:41:55.639  7218  7218 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-16 16:41:55.655  7218  7218 D BluetoothPermissionRequest: onReceive
08-16 16:41:55.657  7218  7218 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 16:41:55.657  7218  7218 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-16 16:41:55.660  7218  7218 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 16:41:55.666  8286  8286 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-16 16:41:55.671  8286  8286 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-16 16:41:55.674  8286  8286 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 16:41:55.675  8286  8286 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 16:41:55.675  8286  8286 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 16:41:55.677  8286  8286 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:41:55.677  8286  8286 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-16 16:41:55.686  7956  7956 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-16 16:41:55.831  8003  8059 D UEI.SmartControl: Internal timer expired: 1
,08-16 16:41:55.832  8003  8059 D UEI.SmartControl: unbind internal service
,08-16 16:41:55.849  8003  8003 D UEI.SmartControl: Service.onUnbind: IControl
08-16 16:41:55.851  8003  8003 D UEI.SmartControl: Service.onDestroy
08-16 16:41:55.851  8003  8003 D UEI.SmartControl: Lock is in USE false
08-16 16:41:55.851  8003  8003 D UEI.SmartControl: unbind internal service
08-16 16:41:55.851  8003  8003 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2716504c
,08-16 16:41:55.852  8003  8003 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-16 16:41:55.854  8003  8003 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-16 16:41:55.855  8003  8003 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-16 16:41:55.855  8003  8003 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-16 16:41:55.855  8003  8003 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-16 16:41:55.855  8003  8003 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-16 16:41:55.855  8003  8003 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-16 16:41:55.855  8003  8003 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-16 16:41:55.855  8003  8003 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 16:41:55.855  8003  8003 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 16:41:55.855  8003  8003 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 16:41:55.855  8003  8003 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 16:41:55.855  8003  8003 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 16:41:55.855  8003  8003 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 16:41:55.856  8003  8003 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 16:41:55.856  8003  8003 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2716504c
08-16 16:41:55.858  8003  8003 D serial_port: close(fd = 25)
08-16 16:41:55.861  8003  8003 I UEI.SmartControl: Serial port is closed.
08-16 16:41:55.861  8003  8003 I UEI.SmartControl: Serial port is closed.
08-16 16:41:55.862  8003  8003 D UEI.SmartControl: Blaster closed
08-16 16:41:55.862  8003  8003 D UEI.SmartControl: Shut down QS...
08-16 16:41:55.862  8003  8003 D UEI.SmartControl: Stopping QS lib
08-16 16:41:55.862  8003  8003 D UEI.SmartControl: QS lib stop result = true
08-16 16:41:55.862  8003  8003 D UEI.SmartControl: Stopped QS lib
08-16 16:41:55.865  8003  8003 D UEI.SmartControl: Stopped file observer...
08-16 16:41:55.865  8003  8003 D UEI.SmartControl: QS shutdown complete
,08-16 16:41:59.016  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:41:59.016  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:41:59.028  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 16:41:59.028  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3eb886a5 removed from the list,
08-16 16:41:59.028  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:41:59.028  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:59.028  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:59.031  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 16:41:59.031  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cf4922b added. We now have 4 listener(s)
08-16 16:41:59.031  7049  7124 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 16:41:59.035  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 16:41:59.043  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cf4922b removed from the list
08-16 16:41:59.043  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:41:59.043  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:41:59.043  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:41:59.045  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 16:41:59.045  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ed8688 added. We now have 4 listener(s)
08-16 16:41:59.045  7049  7124 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 16:41:59.046  1035  2022 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 16:41:59.046  1035  2022 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-16 16:41:59.047  1035  1117 D BluetoothManagerService: Message: 2
08-16 16:42:00.042  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-16 16:42:00.042  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
08-16 16:42:00.042  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-16 16:42:00.043  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,08-16 16:42:00.058  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
08-16 16:42:00.058  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
08-16 16:42:00.059  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
08-16 16:42:00.061  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
,08-16 16:42:04.053  7049  7124 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:42:04.062  1035  1562 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 16:42:04.062  1035  1562 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-16 16:42:04.082  1035  1117 D BluetoothManagerService: Message: 1
08-16 16:42:04.082  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-16 16:42:04.088  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 16:42:04.088  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 16:42:04.088  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-16 16:42:04.118  1035  1117 D BluetoothManagerService: Message: 20
08-16 16:42:04.118  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b1b95f9:true
,08-16 16:42:04.122  8286  8286 D BluetoothAdapterState: make
08-16 16:42:04.127  8286  8286 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 16:42:04.127  8286  8286 I bluedroid-qcom: init
08-16 16:42:04.128  8286  8318 I BluetoothAdapterState: Entering OffState
08-16 16:42:04.129  8286  8286 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 16:42:04.129  8286  8286 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 16:42:04.129  8286  8286 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 16:42:04.129  8286  8286 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 16:42:04.129  8286  8286 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 16:42:04.131  8286  8286 I bluedroid-qcom: get_profile_interface socket
08-16 16:42:04.131  8286  8286 I bluedroid-qcom: get_profile_interface map_client
,08-16 16:42:04.137  8286  8322 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 16:42:04.125  8321  8321 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 16:42:04.125  8321  8321 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 16:42:04.148  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-16 16:42:04.151  1035  1117 D BluetoothManagerService: Message: 40
08-16 16:42:04.151  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 16:42:04.152  8286  8302 I bluedroid-qcom: config_hci_snoop_log
08-16 16:42:04.153  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 16:42:04.153  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 16:42:04.157  8321  8321 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 16:42:04.157  8321  8321 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 16:42:04.157  8321  8321 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-16 16:42:04.159  8321  8321 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-16 16:42:04.161  8286  8322 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-16 16:42:04.166  8321  8321 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 16:42:04.166  8321  8321 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-16 16:42:04.167  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 16:42:04.168  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 16:42:04.168  8286  8322 D BluetoothAdapterProperties: Name is: G3
08-16 16:42:04.172  8286  8318 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-16 16:42:04.172  8286  8318 D BluetoothAdapterProperties: Setting state to 11
08-16 16:42:04.172  8286  8318 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 16:42:04.173  8286  8318 I LGBluetoothServiceJni: classInitNative: succeeds
,08-16 16:42:04.177  1035  1117 D BluetoothManagerService: Message: 60
08-16 16:42:04.178  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 16:42:04.178  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-16 16:42:04.182  1959  1959 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:42:04.184  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:42:04.184  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 16:42:04.187  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:42:04.196  7218  7218 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-16 16:42:04.200  8286  8286 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 16:42:04.201  8286  8286 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:42:04.201  8286  8286 V BluetoothPbapReceiver: ***********state = 11
,08-16 16:42:04.217  8286  8318 D BluetoothBondStateMachine: make
,08-16 16:42:04.222  8286  8335 I BluetoothBondStateMachine: StableState(): Entering Off State
08-16 16:42:04.222  8286  8318 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12e7187f
08-16 16:42:04.223  8286  8318 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 16:42:04.223  8286  8318 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12e7187f
08-16 16:42:04.223  8286  8318 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 16:42:04.223  8286  8318 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-16 16:42:04.224  2205  2205 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 16:42:04.229  8286  8318 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 16:42:04.237  8286  8318 E BluetoothAdapterService: File transfer profiles supported!!
08-16 16:42:04.238  8286  8286 D HeadsetService: Received start request. Starting profile...
08-16 16:42:04.239  8286  8286 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 16:42:04.239  8286  8286 D LGBluetoothHfpAdapter: Version 1.6
,08-16 16:42:04.242  8286  8286 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 16:42:04.243  8286  8286 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 16:42:04.244  8286  8286 D HeadsetStateMachine: make
08-16 16:42:04.248  7218  7218 D BluetoothPermissionRequest: onReceive
08-16 16:42:04.252  8286  8318 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 16:42:04.255  7218  7218 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 16:42:04.262  8286  8318 E BluetoothAdapterService: File transfer profiles supported!!
08-16 16:42:04.267  8286  8318 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 16:42:04.273  8286  8318 E BluetoothAdapterService: File transfer profiles supported!!
08-16 16:42:04.278  8286  8318 E BluetoothAdapterService: File transfer profiles supported!!
08-16 16:42:04.283  8286  8286 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 16:42:04.284  8286  8286 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 16:42:04.289  8286  8286 D HeadsetStateMachine: max_hf_connections = 1
08-16 16:42:04.289  8286  8286 I bluedroid-qcom: get_profile_interface handsfree
08-16 16:42:04.291  8286  8286 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-16 16:42:04.292   326  1367 V AudioPolicyService: registerClient() client 0xb04106a0, uid 1002
08-16 16:42:04.292   326   326 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-16 16:42:04.292   326   326 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 16:42:04.292   326   326 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 16:42:04.292  8286  8286 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 16:42:04.295   326  4290 V AudioFlinger: registerClient() client 0xb5581628, pid 8286
08-16 16:42:04.295  8286  8286 V ToneGenerator: Create Track: 0xb4928080
08-16 16:42:04.295  8286  8286 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 16:42:04.295  8286  8286 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 16:42:04.296   326  1367 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 16:42:04.296   326  1367 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-16 16:42:04.296   326  1367 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 16:42:04.296   326  1367 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 16:42:04.298  8286  8286 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 16:42:04.299   326  4290 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 16:42:04.299   326  1366 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 16:42:04.299   326  1366 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 16:42:04.299   326  1366 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 16:42:04.299   326  1366 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 16:42:04.299  8286  8286 V AudioSystem: getLatency() output 2, latency 50
08-16 16:42:04.300  8286  8286 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 16:42:04.300  8286  8286 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 16:42:04.300  8286  8286 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 16:42:04.300   326  1366 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 16:42:04.300   326  1366 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 16:42:04.300   326  1366 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 16:42:04.300   326  1366 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 16:42:04.300   326  1366 V AudioFlinger: createTrack() lSessionId: 23
,08-16 16:42:04.303   326  1361 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 16:42:04.303   326  1361 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 16:42:04.303  8286  8286 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 16:42:04.303   326  1362 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 16:42:04.303   326  1362 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 16:42:04.303  1035  2086 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 16:42:04.303  1035  2086 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 16:42:04.304  1035  2086 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 16:42:04.304  1035  2086 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 16:42:04.304  8286  8302 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 16:42:04.304  8286  8302 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-16 16:42:04.304  8286  8302 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 16:42:04.304  8286  8302 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 16:42:04.305  1589  1607 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 16:42:04.305  1589  1607 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 16:42:04.305  1862  2520 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 16:42:04.305  1589  1607 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 16:42:04.305  1862  2520 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 16:42:04.305  1589  1607 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 16:42:04.305  1862  2520 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 16:42:04.305  1862  2520 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 16:42:04.305   326   326 V AudioFlinger: acquiring 23 from 8286, for 8286
08-16 16:42:04.305   326   326 V AudioFlinger:  added new entry for 23
08-16 16:42:04.306  8286  8286 V ToneGenerator: ToneGenerator INIT OK, time: 396350
08-16 16:42:04.306  8286  8286 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12e7187f
08-16 16:42:04.306  3296  3315 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 16:42:04.306  3296  3315 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 16:42:04.306  3296  3315 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 16:42:04.306  3296  3315 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 16:42:04.307  8286  8341 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-16 16:42:04.307  8286  8318 V LGMDMManager: Create singleton instance
08-16 16:42:04.307  8286  8286 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12e7187f
08-16 16:42:04.307  8286  8341 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 16:42:04.309  8286  8341 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 16:42:04.309  8286  8318 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 16:42:04.309  8286  8341 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-16 16:42:04.309  8286  8286 D A2dpService: Received start request. Starting profile...
08-16 16:42:04.310   326  1367 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 8286
08-16 16:42:04.310   326  1367 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 16:42:04.310   326  1367 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 16:42:04.310   326  1367 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 16:42:04.,310   326  1367 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 16:42:04.310   326  1367 V voice   : voice_set_parameters: exit with code(0)
08-16 16:42:04.310   326  1367 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 16:42:04.310   326  1367 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 16:42:04.310   326  1367 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 16:42:04.310   326  1367 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 16:42:04.310   326  1367 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 16:42:04.310  8286  8286 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 16:42:04.310   326  1367 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 16:42:04.310  8286  8341 V ToneGenerator: ToneGenerator destructor
08-16 16:42:04.310  8286  8341 V ToneGenerator: stopTone
08-16 16:42:04.310  8286  8341 V ToneGenerator: Delete Track: 0xb4928080
08-16 16:42:04.311  8286  8341 V AudioTrack: ~AudioTrack, releasing session id from 8286 on behalf of 8286
08-16 16:42:04.311   326  4290 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 16:42:04.311   326  4290 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 16:42:04.311   326  4290 V AudioFlinger: PlaybackThread::Track destructor
08-16 16:42:04.311   326  1273 V AudioPolicyService: AudioCommandThread() waking up
,08-16 16:42:04.311   326  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
,08-16 16:42:04.311   326  4290 V AudioFlinger: removeClient_l() pid 8286, calling pid 326
08-16 16:42:04.311   326  1273 V AudioPolicyManager: releaseOutput() 2
08-16 16:42:04.311   326  1273 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 16:42:04.311   326  4290 V AudioFlinger: releasing 23 from 8286 for 8286
08-16 16:42:04.311   326  4290 V AudioFlinger:  decremented refcount to 0
08-16 16:42:04.311   326  4290 V AudioFlinger: purging stale effects
08-16 16:42:04.312  8286  8286 V Avrcp   : make
08-16 16:42:04.313  8286  8286 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-16 16:42:04.313  8286  8286 I bluedroid-qcom: get_profile_interface avrcp
08-16 16:42:04.322  8286  8286 V AudioManager: registerRemoteController: size of Media player list: 0
08-16 16:42:04.324  8286  8286 E AudioManager: No RCC entry present to update
,08-16 16:42:04.324  8286  8286 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 16:42:04.327  8286  8286 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-16 16:42:04.329  8286  8286 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-16 16:42:04.329  8286  8286 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-16 16:42:04.332  8286  8286 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 16:42:04.437  1035  2022 V SIM_STK : Menu title from STK is T-Mobile
08-16 16:42:04.437  1035  2022 V SIM_STK : Menu title from STK is T-Mobile
,08-16 16:42:04.508  1035  2086 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 16:42:04.517  8286  8286 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 16:42:04.521  8286  8286 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 16:42:04.521  8286  8286 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,08-16 16:42:04.522  8286  8286 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 16:42:04.522  8286  8286 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 16:42:04.522  8286  8286 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 16:42:04.522  8286  8286 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 16:42:04.522  8286  8286 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 16:42:04.522  8286  8286 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 16:42:04.522  8286  8286 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 16:42:04.522  8286  8286 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 16:42:04.522  8286  8286 I BluetoothA2dpServiceJni: classInitNative
08-16 16:42:04.522  8286  8286 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 16:42:04.522  8286  8286 D A2dpStateMachine: make
08-16 16:42:04.525  8286  8286 I bluedroid-qcom: get_profile_interface a2dp
08-16 16:42:04.526  8286  8347 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-16 16:42:04.528  8286  8286 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-16 16:42:04.528  8286  8286 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-16 16:42:04.529  8286  8286 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12e7187f
08-16 16:42:04.530  8286  8346 D A2dpStateMachine: Enter Disconnected: -2
08-16 16:42:04.531  8286  8286 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 16:42:04.532  8286  8286 D HidService: Received start request. Starting profile...
08-16 16:42:04.532  8286  8286 I bluedroid-qcom: get_profile_interface hidhost
08-16 16:42:04.533  8286  8286 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12e7187f
08-16 16:42:04.533  8286  8286 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 16:42:04.534  8286  8286 D HealthService: Received start request. Starting profile...
08-16 16:42:04.537  8286  8286 I bluedroid-qcom: get_profile_interface health
08-16 16:42:04.537  8286  8286 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-16 16:42:04.538  8286  8286 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12e7187f
08-16 16:42:04.538  8286  8286 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 16:42:04.541  8286  8286 D PanService: Received start request. Starting profile...
08-16 16:42:04.541  8286  8286 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 16:42:04.541  8286  8286 I bluedroid-qcom: get_profile_interface pan
08-16 16:42:04.548  8286  8286 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-16 16:42:04.548  8286  8286 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12e7187f
08-16 16:42:04.549  8286  8286 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-16 16:42:04.553  8286  8286 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 16:42:04.553  8286  8286 D BtGatt.GattService: Received start request. Starting profile...
08-16 16:42:04.553  8286  8286 D BtGatt.GattService: start()
08-16 16:42:04.553  8286  8286 I bluedroid-qcom: get_profile_interface gatt
08-16 16:42:04.554  8286  8286 D BtGatt.AdvertiseManager: advertise manager created
08-16 16:42:04.564  8286  8286 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12e7187f
08-16 16:42:04.565  8286  8286 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12e7187f
08-16 16:42:04.565  8286  8286 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
,08-16 16:42:04.566  8286  8286 V BluetoothMapService: BluetoothMapBinder()
08-16 16:42:04.567  8286  8286 D BluetoothMapService: Received start request. Starting profile...
08-16 16:42:04.567  8286  8286 D BluetoothMapService: start()
08-16 16:42:04.568  8286  8286 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 16:42:04.569  8286  8286 D BluetoothMapEmailAppObserver: createReceiver()
08-16 16:42:04.569  8286  8286 D BluetoothMapEmailAppObserver: initObservers()
08-16 16:42:04.569  8286  8286 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-16 16:42:04.574  8286  8286 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12e7187f
08-16 16:42:04.575  8286  8286 D HeadsetStateMachine: Proxy object connected
08-16 16:42:04.575  8286  8286 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 16:42:04.575  8286  8286 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-16 16:42:04.577  8286  8341 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 16:42:04.578  8286  8341 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 16:42:04.579  8286  8341 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,08-16 16:42:04.582  8286  8286 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 16:42:04.583  8286  8286 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 16:42:04.585  8286  8286 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-16 16:42:04.588  8286  8286 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 16:42:04.589  8286  8286 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 16:42:04.592  8286  8286 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 16:42:04.592  8286  8286 V PanService: [BTUI] SIM Extra State :ABSENT
,08-16 16:42:04.595  8286  8286 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-16 16:42:04.595  8286  8286 V BluetoothMapService: Handler(): got msg=1
08-16 16:42:04.596  8286  8286 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 16:42:04.596  8286  8286 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-16 16:42:04.596  8286  8286 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 16:42:04.596  8286  8286 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:42:04.596  8286  8286 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-16 16:42:04.597  8286  8318 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 16:42:04.597  8286  8318 I bluedroid-qcom: enable
08-16 16:42:04.598  8286  8357 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 16:42:04.598  8286  8357 I bt-btu  : btu_task pending for preload complete event
08-16 16:42:04.598  8286  8318 I bt_hci_bdroid: init
08-16 16:42:04.601  8286  8318 I bt_vendor: bt-vendor : init
08-16 16:42:04.601  8286  8318 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 16:42:04.601  8286  8318 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 16:42:04.601  8286  8318 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 16:42:04.601  8286  8318 D bt_userial_mct: userial_init
08-16 16:42:04.602  8286  8318 D bt_hci_bdroid: set_power 1
08-16 16:42:04.602  8286  8318 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 16:42:04.602  8286  8318 I bt_vendor: Starting hciattach daemon
08-16 16:42:04.602  8286  8318 I bt_vendor: try to set true
08-16 16:42:04.585  8360  8360 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 16:42:04.585  8360  8360 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 16:42:04.622  8361  8361 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 16:42:04.731  8367  8367 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 16:42:04.748  8368  8368 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 16:42:04.784  8370  8370 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 16:42:04.797  8371  8371 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-16 16:42:04.811  8372  8372 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-16 16:42:04.824  8373  8373 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-16 16:42:04.850  8375  8375 I libmdmdetect: ESOC framework not supported
,08-16 16:42:04.852  8375  8375 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-16 16:42:04.863  8375  8375 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-16 16:42:04.863  8375  8375 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,08-16 16:42:04.863  8375  8375 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,08-16 16:42:04.863  8375  8375 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 16:42:04.863  8375  8375 D bthci_qcomm_common: [BTUI]     LE: Class 2
,08-16 16:42:04.863  8375  8375 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
,08-16 16:42:04.864  8375  8375 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-16 16:42:04.918  8375  8376 E QC-QMI  : qmi_client [8375] 15: failed to locate client data
,08-16 16:42:04.922   472   472 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-16 16:42:04.922   472   472 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-16 16:42:04.962  8383  8383 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 16:42:04.978  8384  8384 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 16:42:05.004  8286  8318 I bt_vendor: bluetooth satus is on
08-16 16:42:05.004  8286  8318 D bt_hci_bdroid: preload
,08-16 16:42:05.006  8286  8359 D bt_userial_mct: userial_open(port:0)
08-16 16:42:05.006  8286  8359 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-16 16:42:05.010  8286  8359 I bt_vendor: Done intiailizing UART
08-16 16:42:05.011  8286  8359 I bt_vendor: Done intiailizing UART
08-16 16:42:05.011  8286  8359 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 16:42:05.012  8286  8359 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 16:42:05.012  8286  8357 I bt-btu  : btu_task received preload complete event
08-16 16:42:05.012  8286  8357 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 16:42:05.012  8286  8357 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-16 16:42:05.014  8286  8357 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-16 16:42:05.017  8286  8386 D bt_userial_mct: Entering userial_read_thread()
,08-16 16:42:05.022  8286  8357 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 16:42:05.022  8286  8357 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 16:42:05.022  8286  8357 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 16:42:05.022  8286  8357 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 16:42:05.022  8286  8357 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 16:42:05.022  8286  8357 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 16:42:05.022  8286  8357 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 16:42:05.022  8286  8357 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 16:42:05.022  8286  8357 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 16:42:05.022  8286  8357 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 16:42:05.022  8286  8357 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 16:42:05.022  8286  8357 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 16:42:05.022  8286  8357 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 16:42:05.022  8286  8357 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 16:42:05.022  8286  8357 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 16:42:05.022  8286  8357 I         : BTE_InitTraceLevels -- TRC_BTIF
08-16 16:42:05.077  8286  8357 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-16 16:42:05.077  8286  8357 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa014b061 
08-16 16:42:05.077  8286  8357 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa014b061 
,08-16 16:42:05.116  8286  8322 E bt-btif : Calling BTA_HhEnable
08-16 16:42:05.116  8286  8322 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-16 16:42:05.121  8286  8322 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 16:42:05.123  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 16:42:05.124  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 16:42:05.125  8286  8357 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-16 16:42:05.126  8286  8357 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-16 16:42:05.126  8286  8357 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 16:42:05.126  8286  8357 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 16:42:05.126  8286  8357 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-16 16:42:05.127  8286  8322 D BluetoothAdapterProperties: Name is: G3
08-16 16:42:05.131  8286  8322 D BluetoothAdapterProperties: Scan Mode:20
08-16 16:42:05.131  8286  8322 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 16:42:05.131  8286  8322 D bt_hci_bdroid: postload
,08-16 16:42:05.138  8286  8359 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 16:42:05.140  8286  8357 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-16 16:42:05.141  8286  8322 D bte_conf: Device ID record 1 : primary
08-16 16:42:05.141  8286  8322 D bte_conf:   vendorId            = 00c4
08-16 16:42:05.141  8286  8322 D bte_conf:   vendorIdSource      = 0001
08-16 16:42:05.141  8286  8322 D bte_conf:   product             = 13a1
08-16 16:42:05.141  8286  8322 D bte_conf:   version             = 1000
08-16 16:42:05.141  8286  8322 D bte_conf:   clientExecutableURL = 
08-16 16:42:05.141  8286  8322 D bte_conf:   serviceDescription  = 
08-16 16:42:05.141  8286  8322 D bte_conf:   documentationURL    = 
08-16 16:42:05.141  8286  8322 D bte_conf: bte_load_did_conf no section named DID2.
08-16 16:42:05.143  8286  8359 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 16:42:05.147  8286  8359 D bt_hci_bdroid: Used up Tx Cmd credits
,08-16 16:42:05.151  8286  8318 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-16 16:42:05.151  8286  8318 D BluetoothAdapterProperties: ScanMode =  20
08-16 16:42:05.151  8286  8318 D BluetoothAdapterProperties: State =  11
08-16 16:42:05.151  8286  8318 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 16:42:05.153  8286  8318 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 16:42:05.153  8286  8318 D BluetoothAdapterProperties: Setting state to 12
08-16 16:42:05.153  8286  8318 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 16:42:05.154  8286  8322 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 16:42:05.154  8286  8322 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 16:42:05.145  8388  8388 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 16:42:05.145  8388  8388 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 16:42:05.162  1035  1117 D BluetoothManagerService: Message: 60
08-16 16:42:05.162  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 16:42:05.162  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,08-16 16:42:05.168  8286  8318 I BluetoothAdapterState: Entering On State
08-16 16:42:05.172  8286  8357 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 16:42:05.172  8286  8357 W bt-smp  : Plain text(LSB ~ MSB) = bc 3f 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 16:42:05.172  8286  8357 W bt-smp  : Encrypted text(LSB ~ MSB) = 0b 7d a5 ac 97 33 f3 1f 58 9e 1f d0 2c 37 a2 26 
08-16 16:42:05.172  8286  8359 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 16:42:05.172  8286  8357 W bt-btm  : Stopping oneshot timer
08-16 16:42:05.177  8286  8318 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 16:42:05.177  8286  8318 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 16:42:05.177  8286  8318 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-16 16:42:05.186  8286  8318 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-16 16:42:05.186  8286  8386 E bt_mct  : hci lib postload completed
08-16 16:42:05.214  8286  8322 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 16:42:05.214  8286  8322 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-16 16:42:05.219  8286  8318 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-16 16:42:05.219  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:42:05.219  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:42:05.219  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:42:05.219  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:42:05.219  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:42:05.219  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:42:05.219  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:42:05.219  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:42:05.226  8286  8357 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 16:42:05.226  8286  8357 W bt-smp  : Plain text(LSB ~ MSB) = 78 c7 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 16:42:05.226  8286  8357 W bt-smp  : Encrypted text(LSB ~ MSB) = 12 a0 41 f3 7e 45 38 2a b8 11 c2 db c5 6d af 88 
,08-16 16:42:05.229  8286  8357 W bt-btm  : Stopping oneshot timer
08-16 16:42:05.230  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:42:05.241  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:42:05.241  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:42:05.241  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:42:05.241  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:42:05.241  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:42:05.241  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:42:05.241  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:42:05.241  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 16:42:05.243  8286  8357 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 16:42:05.243  8286  8357 W bt-smp  : Plain text(LSB ~ MSB) = b5 8e 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 16:42:05.243  8286  8357 W bt-smp  : Encrypted text(LSB ~ MSB) = 9e 80 1d 90 67 33 0a 71 83 5d b5 5d f2 ac e2 bb 
08-16 16:42:05.244  8286  8357 W bt-btm  : Stopping oneshot timer
08-16 16:42:05.255  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 16:42:05.258  8286  8357 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 16:42:05.258  8286  8357 W bt-smp  : Plain text(LSB ~ MSB) = a6 68 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 16:42:05.258  8286  8357 W bt-smp  : Encrypted text(LSB ~ MSB) = 18 a5 ab 8d ea 33 9d 8e 7e 28 a7 45 19 58 b1 59 
08-16 16:42:05.258  8286  8357 W bt-btm  : Stopping oneshot timer
08-16 16:42:05.260  7218  7408 D BluetoothPan: onBluetoothStateChange on: true
08-16 16:42:05.260  7218  7408 D BluetoothPan: onBluetoothStateChange call bindService
08-16 16:42:05.271  7218  7408 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 16:42:05.277  8286  8357 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 16:42:05.277  8286  8357 W bt-smp  : Plain text(LSB ~ MSB) = c5 ba 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 16:42:05.277  8286  8357 W bt-smp  : Encrypted text(LSB ~ MSB) = 9f db 33 73 09 fe a5 b2 a8 22 ba 82 6b d4 8d bc 
08-16 16:42:05.278  8286  8357 W bt-btm  : Stopping oneshot timer
08-16 16:42:05.284  7218  7218 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 16:42:05.285  7218  7218 D PanProfile: Bluetooth service connected
,08-16 16:42:05.289  7218  7235 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 16:42:05.298  7218  7218 D BluetoothInputDevice: Proxy object connected
08-16 16:42:05.299  7218  7218 D HidProfile: Bluetooth service connected
08-16 16:42:05.299  1862  1878 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 16:42:05.304  8406  8406 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-16 16:42:05.309  7218  7236 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 16:42:05.309  1862  1862 D BluetoothHeadset: Proxy object connected
08-16 16:42:05.310  7218  7218 D BluetoothA2dp: Proxy object connected
08-16 16:42:05.310  7218  7218 D A2dpProfile: Bluetooth service connected
08-16 16:42:05.311  7218  7408 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 16:42:05.314  7218  7218 D BluetoothHeadset: Proxy object connected
08-16 16:42:05.314  7218  7218 D HeadsetProfile: Bluetooth service connected
08-16 16:42:05.315  7218  7235 D BluetoothMap: onBluetoothStateChange: up=true
08-16 16:42:05.316  1862  4732 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 16:42:05.318  1862  1862 D BluetoothHeadset: Proxy object connected
08-16 16:42:05.318  7218  7218 D BluetoothMap: Proxy object connected
08-16 16:42:05.318  7218  7218 D MapProfile: Bluetooth service connected
08-16 16:42:05.318  7218  7218 D BluetoothMap: getConnectedDevices()
08-16 16:42:05.319  1862  4733 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 16:42:05.319  8286  8302 V BluetoothMapService: getConnectedDevices()
08-16 16:42:05.321  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 16:42:05.321  1862  1862 D BluetoothHeadset: Proxy object connected
08-16 16:42:05.322  1035  1035 D BluetoothHeadset: Proxy object connected
08-16 16:42:05.322  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 16:42:05.323  1035  1035 D BluetoothA2dp: Proxy object connected
08-16 16:42:05.326  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-16 16:42:05.326  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 16:42:05.326  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 16:42:05.327  1035  1117 D BluetoothManagerService: Message: 40
08-16 16:42:05.327  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-16 16:42:05.327  1959  1959 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:42:05.328  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-16 16:42:05.329  1959  2148 D LGBluetoothAPIService: Message: 1
08-16 16:42:05.329  1959  2148 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-16 16:42:05.329  1959  2148 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-16 16:42:05.330  1959  2148 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-16 16:42:05.336  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:42:05.336  8286  8286 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:42:05.336  8286  8286 D BluetoothMapService: STATE_ON
08-16 16:42:05.337  8286  8286 V BluetoothMapService: Handler(): got msg=1
08-16 16:42:05.337  8286  8286 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 16:42:05.340  8286  8412 D BluetoothMapMasInstance: MAS initSocket()
08-16 16:42:05.341  8286  8412 D BluetoothMapMasInstance:   masId = 00
08-16 16:42:05.341  8286  8412 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 16:42:05.341  8286  8412 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 16:42:05.341  8286  8412 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
,08-16 16:42:05.344  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:42:05.345  1035  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 16:42:05.346  8286  8412 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 16:42:05.347  8286  8412 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-16 16:42:05.348  8286  8412 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 16:42:05.348  8286  8412 D BluetoothMapMasInstance: Accepting socket connection...
08-16 16:42:05.349  8286  8322 D BluetoothAdapterProperties: Scan Mode:21
08-16 16:42:05.350  8286  8322 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 16:42:05.355  7218  7218 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 16:42:05.355  8286  8286 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12e7187f
08-16 16:42:05.355  8286  8286 V BluetoothPbapService: Pbap Service onCreate
08-16 16:42:05.355  8286  8286 V BluetoothPbapService: Starting PBAP service
,08-16 16:42:05.357  8286  8286 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-16 16:42:05.358  8286  8286 V BluetoothPbapService: Pbap Service onBind
08-16 16:42:05.357  7218  7218 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 16:42:05.359  8286  8286 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:42:05.359  8286  8286 V BluetoothPbapService: state: 12
08-16 16:42:05.359  8286  8286 V BluetoothPbapService: Handler(): got msg=1
08-16 16:42:05.360  8286  8286 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-16 16:42:05.361  7218  7218 D BluetoothPbap: Proxy object connected
08-16 16:42:05.361  7218  7218 D PbapServerProfile: Bluetooth service connected
08-16 16:42:05.361  8286  8414 V BluetoothPbapService: Pbap Service initSocket
08-16 16:42:05.363  1035  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 16:42:05.363  8286  8286 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 16:42:05.363  8286  8286 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:42:05.363  8286  8286 V BluetoothPbapReceiver: ***********state = 12
08-16 16:42:05.364  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:42:05.365  8286  8414 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 16:42:05.366  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:42:05.368  2205  2205 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 16:42:05.369  2205  2205 D c       : Getting all permits...
08-16 16:42:05.369  2205  2205 D a       : Opening database...
,08-16 16:42:05.370  8286  8414 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-16 16:42:05.370  8286  8414 V BluetoothPbapService: Succeed to create listening socket 
08-16 16:42:05.370  8286  8414 V BluetoothPbapService: Accepting socket connection...
08-16 16:42:05.371  7218  7218 D DockEventReceiver: finishStartingService: stopping service
08-16 16:42:05.372  2205  2205 D a       : Opening database auth.proximity.permit_store...
08-16 16:42:05.373  2205  2205 D a       : Closing database...
08-16 16:42:05.383  7218  7218 D BluetoothPermissionRequest: onReceive
,08-16 16:42:05.386  7218  7218 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 16:42:05.387  7218  7218 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 16:42:05.390  8286  8286 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-16 16:42:05.391  8286  8286 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-16 16:42:05.396  8286  8286 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-16 16:42:05.413  8286  8286 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-16 16:42:05.413  8286  8286 V BtOppService: onCreate
08-16 16:42:05.418  8286  8286 V BluetoothOppNotification: send message
08-16 16:42:05.421  8286  8286 V BtOppService: Starting RfcommListener
08-16 16:42:05.426  8286  8286 D BluetoothOppPreference: Dumping Names:  
08-16 16:42:05.426  8286  8286 D BluetoothOppPreference: {}
08-16 16:42:05.426  8286  8286 D BluetoothOppPreference: Dumping Channels:  
08-16 16:42:05.426  8286  8286 D BluetoothOppPreference: {}
,08-16 16:42:05.429  8286  8286 V BtOppService: onStartCommand
08-16 16:42:05.431  8286  8423 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 16:42:05.434  8286  8286 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:42:05.434  8286  8286 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 16:42:05.435  8286  8423 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 16:42:05.435  8286  8420 V BtOppService: Deleted complete outbound shares, number =  0
08-16 16:42:05.437  8286  8286 V BluetoothOppNotification: new notify threadi!
08-16 16:42:05.438  8286  8286 V BluetoothOppNotification: send delay message
08-16 16:42:05.439  8286  8424 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-16 16:42:05.441  8286  8424 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ab4636b on behalf of 
08-16 16:42:05.441  8286  8420 V BtOppService: Deleted complete inbound failed shares, number = 0
08-16 16:42:05.441  8286  8286 V BtOppService: start RfcommListener
08-16 16:42:05.442  8286  8420 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-16 16:42:05.443  8286  8424 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 16:42:05.443  8286  8423 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24db1ec8 on behalf of 
08-16 16:42:05.443  8286  8420 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b5d3b61 on behalf of 
08-16 16:42:05.445  8286  8423 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 16:42:05.445  8286  8423 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 16:42:05.445  8286  8423 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@cd00686 on behalf of 
08-16 16:42:05.446  8286  8423 V BluetoothOppNotification: update too frequent, put in queue
08-16 16:42:05.446  8286  8424 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 16:42:05.447  8286  8424 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2833cb47 on behalf of 
08-16 16:42:05.447  8286  8286 V BtOppService: RfcommListener started
08-16 16:42:05.447  8286  8423 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 16:42:05.447  8286  8286 V BtOppService: ContentObserver received notification
08-16 16:42:05.448  8286  8425 V BtOppRfcommListener: Starting RFCOMM listener....
08-16 16:42:05.449  1035  1720 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 16:42:05.449  8286  8425 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 16:42:05.450  8286  8426 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 16:42:05.450  8286  8426 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 16:42:05.450  8286  8424 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 16:42:05.450  8286  8425 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
,08-16 16:42:05.451  8286  8425 V BtOppRfcommListener: Started RFCOMM listener....
08-16 16:42:05.451  8286  8425 I BtOppRfcommListener: Accept thread started.
08-16 16:42:05.451  8286  8426 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25e75f74 on behalf of 
08-16 16:42:05.451  8286  8425 V BtOppRfcommListener: Accepting connection...
08-16 16:42:05.452  8286  8426 V BluetoothOppNotification: update too frequent, put in queue
08-16 16:42:05.455  8286  8426 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 16:42:05.456  8286  8424 V BluetoothOppNotification: outbound notification was removed.
08-16 16:42:05.456  8286  8424 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 16:42:05.458  8286  8424 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a512c9d on behalf of 
08-16 16:42:05.459  8286  8424 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 16:42:05.460  8286  8424 V BluetoothOppNotification: inbound notification was removed.
08-16 16:42:05.460  8286  8424 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 16:42:05.462  8286  8424 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e960512 on behalf of 
,08-16 16:42:05.471  8286  8286 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12e7187f
08-16 16:42:05.471  8286  8286 V BluetoothFtpService: Ftp Service onCreate
08-16 16:42:05.471  8286  8286 I BluetoothFtpService: Ftp Service onCreate
08-16 16:42:05.471  8286  8286 V BluetoothFtpService: Ftp Service onStartCommand
,08-16 16:42:05.471  8286  8286 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:42:05.471  8286  8286 V BluetoothFtpService: Starting Listening on sockets
08-16 16:42:05.472  8286  8286 V BtOppService: ContentObserver received notification
08-16 16:42:05.472  8286  8286 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 16:42:05.472  8286  8286 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 16:42:05.472  8286  8286 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 16:42:05.472  8286  8286 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:42:05.472  8286  8286 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 16:42:05.472  8286  8286 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 16:42:05.474  8286  8427 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 16:42:05.474  8286  8286 V BluetoothFtpService: Handler(): got msg=1
08-16 16:42:05.474  8286  8427 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-16 16:42:05.475  8286  8286 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-16 16:42:05.475  8286  8286 V BluetoothFtpService: Ftp Service initSocket
08-16 16:42:05.476  8286  8427 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@37d4fee0 on behalf of 
08-16 16:42:05.477  8286  8427 V BluetoothOppNotification: update too frequent, put in queue
08-16 16:42:05.478  8286  8427 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 16:42:05.480  1035  1913 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 16:42:05.481  8286  8286 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 16:42:05.482  8286  8286 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-16 16:42:05.482  8286  8286 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-16 16:42:05.485  8286  8428 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-16 16:42:05.493  8286  8286 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12e7187f
,08-16 16:42:05.493  8286  8286 V BluetoothSapService: Sap Service onCreate
08-16 16:42:05.495  8286  8286 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 16:42:05.495  8286  8286 V BluetoothSapService: state: 12
08-16 16:42:05.496  8286  8286 V BluetoothSapService: Starting SAP server process
08-16 16:42:05.497  8286  8286 V BluetoothSapService: SAP Service startRfcommListenerThread
08-16 16:42:05.485  8430  8430 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 16:42:05.485  8430  8430 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 16:42:05.500  8286  8429 V BluetoothSapService: Sap Service initRfcommSocket
08-16 16:42:05.501  1035  2086 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 16:42:05.503  8286  8429 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 16:42:05.504  8286  8429 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-16 16:42:05.505  8286  8429 V BluetoothSapService: Succeed to create listening socket 
08-16 16:42:05.505  8286  8429 V BluetoothSapService: Accepting socket connection...
,08-16 16:42:05.507  8430  8430 V BT_SAP  : Event pipe created
,08-16 16:42:05.507  8430  8430 V BT_SAP  : create_server_socket qcom.sap.server
08-16 16:42:05.507  8430  8430 V BT_SAP  : created socket fd 6
08-16 16:42:06.441  8286  8286 V BluetoothOppNotification: new notify threadi!
08-16 16:42:06.441  8286  8286 V BluetoothOppNotification: send delay message
,08-16 16:42:06.455  8286  8440 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-16 16:42:06.459  8286  8440 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f3b290c on behalf of 
,08-16 16:42:06.467  8286  8440 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 16:42:06.469  8286  8440 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 16:42:06.470  8286  8440 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2dfa5255 on behalf of 
08-16 16:42:06.470  8286  8440 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 16:42:06.472  8286  8440 V BluetoothOppNotification: outbound notification was removed.
08-16 16:42:06.472  8286  8440 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 16:42:06.473  8286  8440 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b69246a on behalf of 
08-16 16:42:06.474  8286  8440 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-16 16:42:06.479  8286  8440 V BluetoothOppNotification: inbound notification was removed.
08-16 16:42:06.479  8286  8440 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 16:42:06.480  8286  8440 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@8d8fd5b on behalf of 
08-16 16:42:09.121  7049  7124 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:42:09.121  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:42:09.121  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:42:09.121  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 16:42:09.121  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:42:09.121  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:42:09.121  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:42:09.121  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 16:42:09.130  7049  7124 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 16:42:09.131  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:42:09.131  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ed8688 removed from the list
08-16 16:42:09.131  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:42:09.131  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:42:09.131  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:42:09.132  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 16:42:09.132  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@194fe821 added. We now have 4 listener(s)
08-16 16:42:09.132  7049  7124 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 16:42:09.134  1035  1051 D WifiServiceImplEx: setWifiEnabled: false pid=7049, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-16 16:42:09.134  1035  1051 D WifiService: setWifiEnabled: false pid=7049, uid=10118
08-16 16:42:09.134  1035  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 16:42:14.144  7049  7124 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:42:14.159  1035  2022 D WifiServiceImplEx: setWifiEnabled: true pid=7049, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 16:42:14.160  1035  2022 D WifiService: setWifiEnabled: true pid=7049, uid=10118
08-16 16:42:14.160  1035  2022 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 16:42:14.180  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 16:42:14.181  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 16:42:14.181  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-16 16:42:14.182  1035  1525 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-16 16:42:14.182  1035  1525 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-16 16:42:14.185  1035  1525 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 16:42:14.185  1035  1525 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 16:42:14.185  1035  1525 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 16:42:14.185  1035  1525 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 16:42:14.185  1035  1525 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 16:42:14.185  1035  1525 E WifiHW  : unknown target_country: EU , set to default
08-16 16:42:14.185  1035  1525 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-16 16:42:14.185  1035  1525 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-16 16:42:14.185  1035  1525 I WifiUtil: gEnableBmps=1
08-16 16:42:14.764   319   878 D SoftapController: Softap fwReload - Ok
,08-16 16:42:14.773  1035  1525 E NetdConnector: NDC Command {82 softap fwreload wlan0 STA} took too long (584ms)
08-16 16:42:14.776   319   878 D CommandListener: Setting iface cfg
08-16 16:42:14.776   319   878 D CommandListener: Trying to bring down wlan0
08-16 16:42:14.787  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-16 16:42:14.794   319   878 D CommandListener: Clearing all IP addresses on wlan0
08-16 16:42:14.808  1035  1525 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-16 16:42:14.815  8451  8451 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 16:42:14.831  1035  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 16:42:14.831  1035  1525 E WifiStateMachine: useWiFiOffloading() : false
08-16 16:42:14.831  1035  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 16:42:14.832  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 16:42:14.832  7218  7218 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 16:42:14.832  7218  7218 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 16:42:14.832  7218  7218 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 16:42:14.815  8451  8451 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 16:42:14.877  8451  8451 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-16 16:42:14.905  1035  1525 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 16:42:14.905  1035  1525 D WifiMonitor: connecting to supplicant
,08-16 16:42:14.915  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 16:42:14.918  1959  1959 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-16 16:42:14.923  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-16 16:42:14.924  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:42:14.925  7218  7218 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 16:42:14.926  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 16:42:14.926  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 16:42:14.926  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 16:42:14.926  7218  7218 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 16:42:14.926  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 16:42:14.926  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:42:14.926  7218  7218 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 16:42:14.927  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:42:14.936  8451  8451 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 16:42:14.936  8451  8451 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-16 16:42:14.939  1035  1117 D Tethering: InitialState.processMessage what=4
,08-16 16:42:14.975  1035  2086 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8467 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-16 16:42:14.979  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 16:42:15.036  8451  8451 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 16:42:15.085  1035  1913 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8490 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 16:42:15.089  8467  8488 W FormManager: Network not available. Please check & try again.
08-16 16:42:15.094  8451  8451 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-16 16:42:15.095  8467  8489 V FormManager: Network unavailable.
08-16 16:42:15.097  8467  8489 V FormManager: Network unavailable.
,08-16 16:42:15.103  8451  8451 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-16 16:42:15.104  8451  8451 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-16 16:42:15.104  1035  1525 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-16 16:42:15.104  1035  1525 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-16 16:42:15.106  1035  1525 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 16:42:15.106  1035  1525 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 16:42:15.107  1035  1525 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 16:42:15.107  1035  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-16 16:42:15.108  1035  1525 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 16:42:15.108  1035  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 16:42:15.109  1035  1525 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 16:42:15.109  1035  1525 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 16:42:15.109  1035  1525 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 16:42:15.109  1035  8507 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-16 16:42:15.110  1035  8507 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 16:42:15.110  1035  1525 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 16:42:15.110  1035  8507 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-16 16:42:15.110  1035  1525 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-16 16:42:15.110  1035  8507 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 16:42:15.110  1035  8507 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 16:42:15.110  1035  8507 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-16 16:42:15.110  1035  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 16:42:15.110  1035  1525 E WifiStateMachine: useWiFiOffloading() : false
08-16 16:42:15.110  1035  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 16:42:15.110  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:42:15.110  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:42:15.110  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:42:15.110  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:42:15.110  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 16:42:15.110  1035  1525 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 16:42:15.111  1035  1525 D WifiNative-wlan0: SET update_config 1: returned true
08-16 16:42:15.111  1035  1525 D WifiConfigStore: Loading config and enabling all networks 
08-16 16:42:15.111  1035  1525 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 16:42:15.111  1035  1525 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 16:42:15.113  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 16:42:15.115  1959  1959 D WfdService: Waiting for WifiP2p enabling
08-16 16:42:15.117  1035  1525 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-16 16:42:15.118  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:42:15.118  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:42:15.118  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:42:15.118  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:42:15.118  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:42:15.118  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:42:15.118  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:42:15.118  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:42:15.119  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:42:15.120  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 16:42:15.120  1035  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-16 16:42:15.121  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:42:15.121  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:42:15.121  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:42:15.121  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:42:15.121  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:42:15.121  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 16:42:15.121  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 16:42:15.121  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 16:42:15.123  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 16:42:15.125  1035  1525 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 16:42:15.125  1035  1525 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-16 16:42:15.128  1035  1525 D WifiStateMachine: enableVerboseLogging : level 2
08-16 16:42:15.128  1035  1525 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-16 16:42:15.128  1035  1525 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 16:42:15.128  1035  1525 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 16:42:15.129  1035  1525 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 16:42:15.129  1035  1525 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-16 16:42:15.129  1035  1525 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 16:42:15.129  1035  1525 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 16:42:15.129  1035  1525 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 16:42:15.129  1035  1525 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-16 16:42:15.129  1035  1525 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-16 16:42:15.129  1035  1525 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-16 16:42:15.130  1035  1525 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 16:42:15.130  1035  1525 D WifiNative-wlan0: doBoolean: SET device_type 1,0-0050F204-5
08-16 16:42:15.130  1035  1525 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-16 16:42:15.131  1959  1959 D WfdsService: Supplicant Connection state is changed : true
08-16 16:42:15.131  1959  2274 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 16:42:15.131  1959  2274 D WfdsService: Set the WFDS Monitor: true
08-16 16:42:15.131  1959  2274 D WfdsMonitor: WfdsMonitorThread create
08-16 16:42:15.131  1959  2274 D WfdsMonitor: WFDS Monitor is created and started
08-16 16:42:15.131  1959  2274 D WfdsService: WiFi: Supplicant connection re-established
08-16 16:42:15.131  1035  1525 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 16:42:15.131  1035  1525 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-16 16:42:15.132  1035  1525 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 16:42:15.132  1959  8509 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 16:42:15.132  1035  1525 D WifiNative-HAL: Setting external_sim to 1
08-16 16:42:15.132  1035  1525 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 16:42:15.132  1035  1525 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 16:42:15.132  1035  1525 I WifiNative-HAL: startHal
08-16 16:42:15.132  1035  1525 D wifi    : setting scan oui 0xaf6f1fa0
08-16 16:42:15.132  1959  8509 E CtrlSupplicant: Succeed to open control connection
08-16 16:42:15.132  1959  8509 E CtrlSupplicant: Succeed to open monitor connection
08-16 16:42:15.132  1959  8509 D WfdsMonitor: Supplicant connection established
08-16 16:42:15.133  1035  1525 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 16:42:15.133  1035  1525 I WifiNative-HAL: startHal
08-16 16:42:15.133  1959  2274 D WfdsService: Connected to the supplicant for wfds
08-16 16:42:15.133  1035  1525 D wifi    : setting scan oui 0xaf6f1fa0
08-16 16:42:15.133  1035  1525 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 16:42:15.133  1035  1525 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-16 16:42:15.133  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
,08-16 16:42:15.133  8451  8451 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 16:42:15.133  1035  1525 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 16:42:15.134  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 16:42:15.134  8451  8451 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 16:42:15.134  1035  1525 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 16:42:15.134  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-16 16:42:15.134  8451  8451 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-16 16:42:15.134  1035  1525 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 16:42:15.134  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 16:42:15.134  8451  8451 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 16:42:15.134  1035  1525 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 16:42:15.134  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 16:42:15.134  8451  8451 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 16:42:15.135  1035  1525 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 16:42:15.135  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 16:42:15.135  8451  8451 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-16 16:42:15.135  1035  1525 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-16 16:42:15.135  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 16:42:15.135  8060  8060 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:42:15.135  8451  8451 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 16:42:15.135  1035  1525 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 16:42:15.136  1035  1525 E WifiNative: : [407,168,079 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-16 16:42:15.136  1035  1525 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 16:42:15.136  1035  1913 I ActivityManager: Killing 7467:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-16 16:42:15.137  1035  1525 D WifiNative-wlan0: RECONNECT: returned true
08-16 16:42:15.137  1035  1525 D WifiNative-wlan0: doString: [STATUS]
08-16 16:42:15.138  1035  8507 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 16:42:15.138  1035  8507 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 16:42:15.139  1035  1525 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 16:42:15.139  1035  1525 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 16:42:15.139  1035  1525 D WifiNative-wlan0: SET ps 1: returned true
08-16 16:42:15.139  1035  1521 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:42:15.141   319   878 D CommandListener: Setting iface cfg
08-16 16:42:15.141   319   878 D CommandListener: Trying to bring up p2p0
08-16 16:42:15.141  1035  1521 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 16:42:15.141  1035  1521 D LGWifiP2pService: P2pEnablingState
08-16 16:42:15.141  1035  1521 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:42:15.141  1035  1521 D LGWifiP2pService: P2p socket connection successful
08-16 16:42:15.141  1035  1521 D LGWifiP2pService: P2pEnabledState
08-16 16:42:15.166  8490  8490 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 16:42:15.177  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 16:42:15.178  1035  1521 D LGWifiP2pService: sending p2p connection changed broadcast
08-16 16:42:15.178  1035  1521 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-16 16:42:15.178  1035  1792 W libprocessgroup: failed to open /acct/uid_10046/pid_7467/cgroup.procs: No such file or directory
08-16 16:42:15.179  1035  1521 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-16 16:42:15.179  1035  1521 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 16:42:15.179  1035  1521 D WifiNative-p2p0: SET device_name G3: returned true
08-16 16:42:15.179  1035  1521 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 16:42:15.179  1035  1521 D LGWifiP2pService: before postfix = G3
08-16 16:42:15.179  1035  1521 D WifiServerServiceExt: postfix byte check : 2
08-16 16:42:15.179  1035  1521 D LGWifiP2pService: after postfix = G3
08-16 16:42:15.179  1035  1521 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-16 16:42:15.179  1035  1521 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 16:42:15.179  1035  1521 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
,08-16 16:42:15.180  1035  1521 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 16:42:15.180  1035  1521 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 16:42:15.181  1035  1521 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 16:42:15.181  1035  1521 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-16 16:42:15.182  1035  1525 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-16 16:42:15.182  1959  1959 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 16:42:15.182  1035  1521 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 16:42:15.182  1035  1521 D WifiNative-HAL: p2pGetDeviceAddress
08-16 16:42:15.182  1035  1525 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 16:42:15.182  1959  1959 D WfdsService: WifiP2pState is changed : true
08-16 16:42:15.182  1959  2274 D WfdsService: Receive the WFDS_ENABLE Method
08-16 16:42:15.183  1959  2274 D WfdsService: Set the WFDS Monitor: true
08-16 16:42:15.183  1035  1525 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 16:42:15.183  1959  2274 D WfdsService: Connected to the supplicant for wfds
08-16 16:42:15.183  1959  2274 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 16:42:15.183  8451  8451 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-16 16:42:15.183  1035  1525 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-16 16:42:15.183  1959  2274 D WfdsService: selectPreferredScanChannel [36]
08-16 16:42:15.183  1959  2274 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-16 16:42:15.183  1035  1525 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-16 16:42:15.184  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 16:42:15.184  1035  1525 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 16:42:15.184  1035  1035 D RttService: SCAN_AVAILABLE : 3
08-16 16:42:15.184  1035  1543 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:42:15.184  1035  1543 I WifiNative-HAL: startHal
08-16 16:42:15.184  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 16:42:15.184  1035  1525 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 16:42:15.184  1035  1544 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:42:15.184  1035  1525 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 16:42:15.184  1959  1959 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-16 16:42:15.184  8451  8451 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 16:42:15.184  1959  1959 D WfdsService: isConnected: false
08-16 16:42:15.185  1035  1521 D WifiNative-HAL: p2pGetDeviceAddress returning 
08-16 16:42:15.185  1035  1543 D wifi    : getting scan capabilities on interface[1] = 0xaf6f1fa0
08-16 16:42:15.185  1035  1543 D wifi    : failed to get capabilities : -3
08-16 16:42:15.185  1035  1543 E WifiScanningService: could not get scan capabilities
08-16 16:42:15.187  1035  1525 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 16:42:15.187  1035  2086 I ActivityManager: Killing 7493:com.android.chrome/u0a57 (adj 15): empty #17
08-16 16:42:15.187  1035  1525 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 16:42:15.188  1035  1525 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-16 16:42:15.188  1035  1525 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-16 16:42:15.188  8451  8451 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 16:42:15.189  1035  1525 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 16:42:15.189  1035  1525 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 16:42:15.189  1035  1525 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 16:42:,15.189  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-16 16:42:15.190  8451  8451 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 16:42:15.192  8451  8451 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 16:42:15.192  1035  8507 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 16:42:15.192  1035  8507 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 16:42:15.192  1035  8507 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 16:42:15.192  1035  8507 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-16 16:42:15.192  8451  8451 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 16:42:15.193  8451  8451 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-16 16:42:15.193  8451  8451 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:42:15.193  1959  8509 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 16:42:15.194  1959  8509 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 16:42:15.194  1035  1525 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-16 16:42:15.194  1035  8507 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 16:42:15.194  1035  8507 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:42:15.194  1035  8507 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:42:15.194  1035  8507 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:42:15.194  1035  8507 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 16:42:15.194  1035  8507 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:42:15.194  1035  8507 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:42:15.194  1035  8507 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:42:15.194  1035  1525 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 16:42:15.195  1035  1525 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 16:42:15.196  1035  1525 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 16:42:15.196  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 16:42:15.196  8451  8451 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 16:42:15.196  8451  8451 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 16:42:15.196  1035  8507 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 16:42:15.196  1035  8507 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 16:42:15.196  1035  8507 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 16:42:15.196  1035  8507 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 16:42:15.197  1035  1525 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 16:42:15.197  1035  1525 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-16 16:42:15.197  1035  1525 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-16 16:42:15.197  1035  1525 D WifiNative-wlan0: doBoolean: SCAN
08-16 16:42:15.198  1035  1525 D WifiNative-wlan0: SCAN: returned false
08-16 16:42:15.199  1035  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=407231  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 16:42:15.218  1035  1982 W libprocessgroup: failed to open /acct/uid_10057/pid_7493/cgroup.procs: No such file or directory
,08-16 16:42:15.221  1035  1521 D LGWifiP2pService: DeviceAddress: 
08-16 16:42:15.221  1035  1521 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 16:42:15.222  1035  1521 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 16:42:15.222  1035  1521 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-16 16:42:15.222  1959  1959 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 16:42:15.222  1959  1959 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 16:42:15.222  1959  1959 D WfdsService: Update P2p Interface State: 3
08-16 16:42:15.222  1035  1521 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 16:42:15.222  1035  1521 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 16:42:15.223  1035  1521 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 16:42:15.223  1035  1521 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-16 16:42:15.225  1035  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=407258  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 16:42:15.226  1035  1525 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 16:42:15.226  1035  1525 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 16:42:15.226  1035  1525 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 16:42:15.227  1035  1525 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 16:42:15.227  1035  1525 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 16:42:15.228  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:42:15.228  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 16:42:15.229  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:42:15.232  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:42:15.232  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:42:15.232  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,08-16 16:42:15.235  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 16:42:15.235  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 16:42:15.236  1035  1521 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 16:42:15.236  1035  1521 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-16 16:42:15.236  1035  1521 D LGWifiP2pService: InactiveState
08-16 16:42:15.237  1035  1521 D LGWifiP2pService: InactiveState{ when=-43ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:42:15.237  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-44ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:42:15.237  1035  1521 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-16 16:42:15.238  8451  8451 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 16:42:15.238  8451  8451 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 16:42:15.238  1959  8509 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 16:42:15.238  1035  8507 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 16:42:15.238  1035  8507 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 16:42:15.238  1035  8507 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 16:42:15.238  1035  8507 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 16:42:15.240  8451  8451 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 16:42:15.240  8451  8451 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:42:15.240  1959  8509 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 16:42:15.240  1035  8507 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 16:42:15.240  1035  8507 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:42:15.240  1035  8507 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:42:15.241  1035  8507 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:42:15.241  1035  1521 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 16:42:15.241  1035  1521 D LGWifiP2pService: InactiveState{ when=-19ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:42:15.241  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-19ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:42:15.241  1035  1521 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:42:15.241  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:42:15.241  1035  1521 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:42:15.242  1035  1521 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 16:42:15.242  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:42:15.242  1035  1521 D LGWifiP2pService: DefaultState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:42:15.242  8451  8451 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:42:15.242  1959  8509 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 16:42:15.242  1959  2274 W WfdsService: DefaultState - msg [9441285] is not handled
,08-16 16:42:15.242  1035  1521 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:42:15.242  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:42:15.242  1035  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:42:15.242  1035  8507 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-16 16:42:15.242  1035  8507 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:42:15.242  1035  8507 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:42:15.242  1035  8507 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 16:42:15.243  1035  1521 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 16:42:15.243  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:42:15.243  1035  1521 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:42:15.243  1035  1035 E WifiServerServiceExt: No p2p device connected
08-16 16:42:15.249  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-16 16:42:15.249  7218  7218 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 16:42:15.249  7218  7218 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 16:42:15.249  7218  7218 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-16 16:42:15.250  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 16:42:15.250  7218  7218 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 16:42:15.250  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 16:42:15.250  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 16:42:15.250  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 16:42:15.250  7218  7218 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 16:42:15.250  7218  7218 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 16:42:15.261  8490  8490 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 16:42:15.268  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 16:42:15.273  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 16:42:15.274  8467  8513 W FormManager: Network not available. Please check & try again.
08-16 16:42:15.281  8467  8514 V FormManager: Network unavailable.
,08-16 16:42:15.291  8467  8514 V FormManager: Network unavailable.
08-16 16:42:15.295  4627  4627 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-16 16:42:15.295  4627  4627 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 16:42:15.298  4627  4627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 16:42:15.302  4627  4627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 16:42:15.307  4627  8515 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 16:42:15.312  4627  8516 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 16:42:15.313  4627  8516 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 16:42:15.367  1035  2077 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8517 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-16 16:42:15.521  8517  8517 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 16:42:15.522  8517  8517 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-16 16:42:15.534  8517  8517 V [BNRBootReceiver]: Boot Receiver Return
08-16 16:42:15.534  8517  8517 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-16 16:42:15.593  1035  1792 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8538 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 16:42:15.596  1035  1792 I ActivityManager: Killing 7511:com.lge.drmservice/u0a62 (adj 15): empty #17
08-16 16:42:15.646  1035  1050 W libprocessgroup: failed to open /acct/uid_10062/pid_7511/cgroup.procs: No such file or directory
,08-16 16:42:15.668  8538  8538 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 16:42:15.688  8538  8538 D PluginManager: init()
,08-16 16:42:15.760  1035  8507 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-16 16:42:15.760  1035  8507 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 16:42:15.761  1035  8507 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-16 16:42:15.761  1035  8507 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-16 16:42:15.761  1035  8507 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 16:42:15.761  8451  8451 E wpa_supplicant: USIM:  scard_init function
08-16 16:42:15.762  8451  8451 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-16 16:42:15.770  1035  8507 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-16 16:42:15.770  1035  8507 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-16 16:42:15.770  1035  1525 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-16 16:42:15.771  1035  1525 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-16 16:42:15.772  1035  1525 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-16 16:42:15.774  1035  1525 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-16 16:42:15.774  1035  1525 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-16 16:42:15.786  1035  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=407818  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-16 16:42:15.788  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:42:15.788  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:42:15.788  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 16:42:15.790  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:42:15.790  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 16:42:15.791  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:42:15.791  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:42:15.791  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 16:42:15.792  1035  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=407824  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 16:42:15.793  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:42:15.793  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 16:42:15.793  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-16 16:42:15.796  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:42:15.796  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 16:42:15.797  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:42:15.889  8451  8451 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-16 16:42:15.892  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 16:42:15.893  1035  8507 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 16:42:15.893  1035  8507 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-16 16:42:15.894  1035  1525 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-16 16:42:15.894  1035  8507 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 16:42:15.894  1035  1525 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 16:42:15.894  1035  8507 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 16:42:15.894  1035  1525 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 16:42:15.894  1035  1525 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 16:42:15.894  1035  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-16 16:42:15.895  1035  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=407927  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 16:42:15.895  1035  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=407927  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 16:42:15.896  1035  1525 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=407928
08-16 16:42:15.896  1035  1525 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=407928
08-16 16:42:15.896  1035  1525 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=407928
08-16 16:42:15.896  1035  1525 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=407928
08-16 16:42:15.896  1035  1525 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=407929
08-16 16:42:15.897  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 16:42:15.897  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-16 16:42:15.899  1035  8507 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 16:42:15.899  1035  8507 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 16:42:15.900  1035  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=407932  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 16:42:15.901  1035  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=407933  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 16:42:15.905  8451  8451 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 16:42:15.905  8451  8451 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 16:42:15.906  1035  8507 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 16:42:15.906  1035  8507 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 16:42:15.906  1035  8507 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-16 16:42:15.906  1035  8507 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 16:42:15.907  1035  8507 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 16:42:15.907  1035  8507 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 16:42:15.907  1035  8507 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 16:42:15.907  1035  8507 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 16:42:15.907  1035  8507 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 16:42:15.907  1035  8507 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 16:42:15.908  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:42:15.909  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:42:15.909  103,5  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-16 16:42:15.911  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:42:15.911  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 16:42:15.912  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:42:15.914  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:42:15.914  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:42:15.914  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-16 16:42:15.915  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:42:15.915  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 16:42:15.915  1035  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=407947  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 16:42:15.915  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:42:15.916  1035  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=407948  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 16:42:15.917  1035  1525 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=407949
08-16 16:42:15.918  1035  1525 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=407950
08-16 16:42:15.918  1035  1525 D WifiNative-wlan0: doString: [STATUS]
08-16 16:42:15.918  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 16:42:15.918  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-16 16:42:15.919  1035  8507 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 16:42:15.919  1035  8507 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 16:42:15.919  1035  1525 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 16:42:15.921  1035  1525 I WifiServiceExtension: setVHTCapabilityType  : false
,08-16 16:42:15.926  1035  1525 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-16 16:42:15.926  1035  1525 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-16 16:42:15.929  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:42:15.929  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:42:15.929  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 16:42:15.932  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:42:15.932  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 16:42:15.933  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:42:15.934  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:42:15.935  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:42:15.935  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-16 16:42:15.937  1035  1525 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-16 16:42:15.938  1035  1531 D ConnectivityService: Got NetworkAgent Messenger
08-16 16:42:15.938  1035  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 16:42:15.938  1035  1531 D ConnectivityService: NetworkAgent connected
08-16 16:42:15.938  1035  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 16:42:15.938  1035  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 16:42:15.938  1035  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 16:42:15.938  1035  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 16:42:15.943  1035  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 16:42:15.943  1035  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 16:42:15.943  1035  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 16:42:15.943  1035  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 16:42:15.943  1035  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 16:42:15.946  1035  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 16:42:15.948   319   878 D CommandListener: Setting iface cfg
,08-16 16:42:15.950  1035  8557 D DhcpStateMachine: StoppedState
08-16 16:42:15.950  1035  1525 E WifiStateMachine: Start Dhcp Watchdog 3
08-16 16:42:15.950  1035  8557 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:42:15.950  1035  8557 D DhcpStateMachine: WaitBeforeStartState
08-16 16:42:15.951  1035  1525 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=407983  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 16:42:15.952  1035  1525 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=407984  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 16:42:15.952  1035  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=407984  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 16:42:15.952  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:42:15.952  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 16:42:15.953  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 16:42:15.953  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 16:42:15.953  1035  1525 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=407985  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 16:42:15.953  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:42:15.953  1035  1525 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=407985  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 16:42:15.954  1035  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=407986  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 16:42:15.955  1035  1525 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:29252] from screen [on:0 period:-1815246573] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 16:42:15.956  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1815246572] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 16:42:15.956  1035  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 16:42:15.961  1035  1531 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,08-16 16:42:15.962  1035  1525 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 16:42:15.962  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 16:42:15.962  1035  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 16:42:15.963  1035  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 16:42:15.963  1035  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 16:42:15.963  1035  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 16:42:15.964  1035  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 16:42:15.965  1035  1525 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=233,0,0
08-16 16:42:15.965  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=233,0,0
08-16 16:42:15.965  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 16:42:15.966  8451  8451 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-16 16:42:15.966  1035  1525 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 16:42:15.966  1035  1525 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 16:42:15.968  1035  1525 D WifiNative-wlan0: SET ps 0: returned true
08-16 16:42:15.968  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-16 16:42:15.969  8451  8451 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 16:42:15.969  1035  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 16:42:15.969  1035  1525 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 16:42:15.969  1035  1525 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 16:42:15.969  1035  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@15d098e6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:42:15.969  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@15d098e6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:42:15.969  1035  1525 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 16:42:15.969  1035  8557 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:42:15.969  1035  8557 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 16:42:15.970   319   878 D CommandListener: Setting iface cfg
08-16 16:42:15.970   319   878 D CommandListener: Trying to bring up wlan0
08-16 16:42:15.971  1035  1525 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-16 16:42:15.972  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 16:42:15.972  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 16:42:15.972  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:42:15.973  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 16:42:15.973  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 16:42:15.974  1035  1525 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-16 16:42:15.974  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-16 16:42:15.974  1035  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:42:15.974  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 16:42:15.975  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 16:42:15.975  8451  8451 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 16:42:15.975  1035  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 16:42:15.975  1035  1525 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
,08-16 16:42:15.975  8451  8451 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-16 16:42:15.976  1035  1525 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-16 16:42:15.976  1035  1525 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 16:42:15.994  1035  1525 D WifiNative-wlan0: SET ps 1: returned true
08-16 16:42:15.994  1035  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,08-16 16:42:15.994  1035  1525 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 16:42:15.995  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 16:42:15.996  1035  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 16:42:15.996  1035  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 16:42:15.996  1035  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 16:42:15.997  1035  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 16:42:15.997  1035  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 16:42:15.998  1035  1525 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 16:42:15.998  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 16:42:15.998  1035  1525 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 16:42:15.999  1035  1531 D ConnectivityService: ignoring duplicate network state non-change
08-16 16:42:16.001  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:42:16.001  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 16:42:16.002  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:42:16.002  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:42:16.002  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:42:16.002  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 16:42:16.005  1035  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 16:42:16.006  1035  1531 D ConnectivityService: Adding iface wlan0 to network 102
08-16 16:42:16.008  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:42:16.008  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:42:16.008  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 16:42:16.008  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 16:42:16.010  1959  1959 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-16 16:42:16.013  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:42:16.013  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:42:16.013  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 16:42:16.014  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 16:42:16.015  1035  1525 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 16:42:16.018  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 16:42:16.018  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 16:42:16.018  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 16:42:16.025  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:42:16.025  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 16:42:16.026  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:42:16.028  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:42:16.028  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 16:42:16.028  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:42:16.031  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:42:16.032  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 16:42:16.032  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 16:42:16.033  1035  1531 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 16:42:16.033  1035  1531 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-16 16:42:16.034  1035  1531 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-16 16:42:16.035   319   878 E Netd    : netlink response contains error (File exists)
08-16 16:42:16.035  1035  1531 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-16 16:42:16.036  1035  1531 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 16:42:16.036  1035  1531 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-16 16:42:16.036  1035  1531 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-16 16:42:16.037  1035  1531 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 16:42:16.037  1035  1531 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 16:42:16.037  1035  1531 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-16 16:42:16.037  1035  8556 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:42:16.037  1035  8556 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 16:42:16.037  1035  8556 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 16:42:16.037  1035  8556 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 16:42:16.039  1035  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 16:42:16.039  1035  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 16:42:16.039  1035  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 16:42:16.039  1035  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 16:42:16.039  1035  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:42:16.039  1035  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 16:42:16.039  1035  1531 D ConnectivityService: currentScore = 0, newScore = 20
08-16 16:42:16.039  1035  1531 D ConnectivityService:    accepting network in place of null
08-16 16:42:16.039  1035  1531 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:42:16.040  1862  1862 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:42:16.040   319  8566 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-16 16:42:16.040  1862  1862 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 16:42:16.041  1035  1525 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:42:16.041  1035  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 16:42:16.042  1035  1531 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 16:42:16.042  1035  1531 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-16 16:42:16.043  1035  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 16:42:16.043  1035  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 16:42:16.043  1035  1531 D CSLegacyTypeTracker: [e] ,list.add(nai) empty : false size: 1
,08-16 16:42:16.044  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-16 16:42:16.045  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 16:42:16.045  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 16:42:16.045  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 16:42:16.046  1035  1531 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-16 16:42:16.047  1035  1531 D ConnectivityService: validation of new default Network = false
08-16 16:42:16.047  1035  1531 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 16:42:16.047  1035  1531 D DSQN    : enableDataServiceNotify 
08-16 16:42:16.047  1035  1531 D DSQN    : start dsqn bin
08-16 16:42:16.054  1035  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 16:42:16.054  1035  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:42:16.054  1035  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 16:42:16.054  1035  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-16 16:42:16.055  1589  1796 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-16 16:42:16.045  8567  8567 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 16:42:16.045  8567  8567 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 16:42:16.058  1035  1520 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-16 16:42:16.069  8567  8567 E DSQN    : DSQN ssw
,08-16 16:42:16.075  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 16:42:16.076  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:42:16.076  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:42:16.100  8538  8538 W ExternalStrings: load override strings
08-16 16:42:16.100  8538  8538 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-16 16:42:16.100  8538  8538 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-16 16:42:16.100  8538  8538 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-16 16:42:16.100  8538  8538 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-16 16:42:16.100  8538  8538 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-16 16:42:16.100  8538  8538 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-16 16:42:16.100  8538  8538 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-16 16:42:16.100  8538  8538 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-16 16:42:16.100  8538  8538 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-16 16:42:16.100  8538  8538 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-16 16:42:16.100  8538  8538 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-16 16:42:16.100  8538  8538 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 16:42:16.100  8538  8538 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-16 16:42:16.100  8538  8538 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 16:42:16.100  8538  8538 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 16:42:16.100  8538  8538 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 16:42:16.100  8538  8538 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 16:42:16.100  8538  8538 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-16 16:42:16.101  8538  8538 D StatusProvider: onCreate
08-16 16:42:16.122   319  8566 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-16 16:42:16.137  8538  8538 V Signer  : override build config not found
,08-16 16:42:16.137  8538  8538 D Signer  : value of property debug is false
,08-16 16:42:16.161  8538  8538 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,08-16 16:42:16.161  8538  8538 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-16 16:42:16.161  8538  8538 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-16 16:42:16.161  8538  8538 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-16 16:42:16.161  8538  8538 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
,08-16 16:42:16.161  8538  8538 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
,08-16 16:42:16.162  8538  8538 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-16 16:42:16.162  8538  8538 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-16 16:42:16.162  8538  8538 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-16 16:42:16.162  8538  8538 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
,08-16 16:42:16.162  8538  8538 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-16 16:42:16.162  8538  8538 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-16 16:42:16.163  8538  8538 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-16 16:42:16.164   319  8566 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-16 16:42:16.169  8538  8538 V LGMDMManager: Create singleton instance
,08-16 16:42:16.174  1035  8557 D DhcpStateMachine: DHCPV4 request on wlan0
,08-16 16:42:16.175  1035  8557 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-16 16:42:16.175  1035  8557 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-16 16:42:16.165  8572  8572 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 16:42:16.165  8572  8572 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 16:42:16.204  8572  8572 I dhcpcd  : version 5.5.6 starting
08-16 16:42:16.205   319   877 D LGDataListener: argv[0]=dsqncommand
08-16 16:42:16.205   319   877 D LGDataListener: argv[1]=wlan0
08-16 16:42:16.205   319   877 D LGDataListener: argv[2]=1
08-16 16:42:16.205   319   877 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-16 16:42:16.206  8538  8538 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
08-16 16:42:16.208  8572  8572 E dhcpcd  : get_duid: m
08-16 16:42:16.208  8572  8572 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 16:42:16.208  8572  8572 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-16 16:42:16.209  1035  1115 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 16:42:16.209  1035  1115 D DSQN    : start to monitor internet connection
,08-16 16:42:16.290  8538  8538 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 16:42:16.292  8538  8582 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 16:42:16.306  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 16:42:16.307  8572  8572 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-16 16:42:16.307  8572  8572 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 16:42:16.307  8572  8572 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 16:42:16.308  8572  8572 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-16 16:42:16.308  8572  8572 D dhcpcd  : wlan0: sending REQUEST (xid 0x1fb0a354), next in 4.50 seconds
08-16 16:42:16.315  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 16:42:16.354  8572  8572 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-16 16:42:16.384  1035  1050 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8586 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-16 16:42:16.385  8572  8572 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-16 16:42:16.385  8572  8572 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-16 16:42:16.386  8572  8572 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-16 16:42:16.386  1035  1050 I ActivityManager: Killing 7528:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-16 16:42:16.386  8572  8572 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-16 16:42:16.387  8572  8572 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 16:42:16.387  8572  8572 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 16:42:16.388  8572  8572 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 16:42:16.388  8572  8572 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-16 16:42:16.436  8538  8581 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-16 16:42:16.465  1035  1051 W libprocessgroup: failed to open /acct/uid_10085/pid_7528/cgroup.procs: No such file or directory
,08-16 16:42:16.479  8586  8586 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 16:42:16.491  8586  8586 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-16 16:42:16.523  8586  8586 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-16 16:42:16.523  8586  8586 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-16 16:42:16.524  8586  8586 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-16 16:42:16.524  8586  8586 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-16 16:42:16.525  8586  8586 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-16 16:42:16.527  8586  8586 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-16 16:42:16.532  8586  8586 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-16 16:42:16.537  8586  8586 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 16:42:16.540  8586  8586 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 16:42:16.551  8586  8586 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 16:42:16.552  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-16 16:42:16.555  8586  8586 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-16 16:42:16.556  7218  7218 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-16 16:42:16.557  8586  8586 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-16 16:42:16.558  8538  8538 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:42:16.558  8538  8582 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 16:42:16.563  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 16:42:16.567  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 16:42:16.571  8586  8586 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 16:42:16.571  8586  8586 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 16:42:16.572  8586  8586 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 16:42:16.574  8538  8538 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:42:16.574  8538  8582 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 16:42:16.580  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 16:42:16.580  1035  8557 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-16 16:42:16.581  1035  8557 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-16 16:42:16.581  1035  8557 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 16:42:16.581  1035  8557 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-16 16:42:16.581  1035  8557 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-16 16:42:16.581  1035  8557 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 16:42:16.581  1035  8557 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-16 16:42:16.581  1035  8557 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-16 16:42:16.582  1035  8557 D DhcpStateMachine: RunningState
08-16 16:42:16.583  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 16:42:16.587  8586  8586 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 16:42:16.588  8586  8586 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 16:42:16.588  8586  8586 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 16:42:16.590  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 16:42:16.590  7218  7218 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 16:42:16.590  7218  7218 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 16:42:16.590  7218  7218 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 16:42:16.590  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-16 16:42:16.591  7218  7218 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 16:42:16.591  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 16:42:16.592  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 16:42:16.592  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 16:42:16.592  7218  7218 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 16:42:16.592  7218  7218 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 16:42:16.592  7218  7218 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 16:42:16.595  8538  8538 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:42:16.596  8538  8582 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 16:42:16.601  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 16:42:16.602  8538  8581 D LgDataFeature: LgDataFeature() Constructor: none
08-16 16:42:16.602  8538  8581 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 16:42:16.606  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 16:42:16.612  8586  8586 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 16:42:16.613  8586  8586 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 16:42:16.613  8586  8586 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 16:42:16.616  8538  8538 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:42:16.616  8538  8582 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 16:42:16.622  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 16:42:16.636  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 16:42:16.647  8586  8586 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 16:42:16.648  8586  8586 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 16:42:16.649  8586  8586 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 16:42:16.651  8538  8538 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:42:16.651  8538  8582 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 16:42:16.657  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 16:42:16.663  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 16:42:16.669  8586  8586 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 16:42:16.670  8586  8586 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 16:42:16.670  8586  8586 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 16:42:16.674  8538  8538 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:42:16.674  8538  8582 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 16:42:16.681  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 16:42:16.703  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 16:42:16.712  8586  8586 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 16:42:16.713  8586  8586 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 16:42:16.713  8586  8586 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 16:42:16.730  8538  8538 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:42:16.730  8538  8582 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 16:42:16.739  8538  8581 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-16 16:42:16.755  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 16:42:16.756  8538  8581 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-16 16:42:16.763  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 16:42:16.770  8586  8586 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 16:42:16.770  8586  8586 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 16:42:16.773  8538  8581 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-16 16:42:16.774  8538  8581 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-16 16:42:16.774  8538  8581 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-16 16:42:16.775  8538  8581 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-16 16:42:16.776  8538  8581 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-16 16:42:16.776  8586  8586 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 16:42:16.779  8538  8538 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:42:16.780  8538  8582 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 16:42:16.784  8538  8581 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,08-16 16:42:16.786  8538  8581 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-16 16:42:16.790  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 16:42:16.797  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 16:42:16.806  8586  8586 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 16:42:16.806  8586  8586 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 16:42:16.808  8586  8586 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 16:42:16.812  8538  8538 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 16:42:16.814  8538  8582 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 16:42:16.819  8490  8490 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 16:42:16.826  8490  8490 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 16:42:16.831  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 16:42:16.837  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 16:42:16.843  8586  8586 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 16:42:16.844  8586  8586 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 16:42:16.847  8586  8586 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-16 16:42:16.849  8586  8586 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 16:42:16.849  8586  8586 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 16:42:16.854  8538  8538 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:42:16.857  8538  8582 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 16:42:16.857  8490  8490 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-16 16:42:16.858  8490  8490 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 16:42:16.862  7218  7218 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 16:42:16.867  7218  7218 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 16:42:16.874  8586  8586 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 16:42:16.874  8586  8586 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 16:42:16.876  8586  8586 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 16:42:16.876  8586  8586 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 16:42:16.877  8586  8586 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 16:42:16.879  8538  8538 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 16:42:16.884  8586  8586 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-16 16:42:16.885  8586  8586 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 16:42:16.886  8586  8586 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-16 16:42:16.925  8586  8586 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 16:42:16.926  8586  8586 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 16:42:16.933  8586  8586 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-16 16:42:16.934  8586  8586 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-16 16:42:16.934  8586  8586 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-16 16:42:16.934  8586  8586 V SoundPool: doLoad: loading sample sampleID=1
08-16 16:42:16.935  8586  8586 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 16:42:16.937  8586  8641 V SoundPool: Start decode
08-16 16:42:16.937  8586  8641 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-16 16:42:16.939   326  1366 V MediaPlayerService: decode(22, 10857164, 17813)
08-16 16:42:16.939   326  1366 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
,08-16 16:42:16.939   326  1366 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-16 16:42:16.939   326  1366 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-16 16:42:16.939   326  1366 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-16 16:42:16.939   326  1366 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-16 16:42:16.939   326  1366 V MediaPlayerService: player type = 3
08-16 16:42:16.939   326  1366 V AwesomePlayer: AwesomePlayer create()
08-16 16:42:16.940   326  1366 V AwesomePlayer: reset_l() 
08-16 16:42:16.940   326  1366 V AwesomePlayer: cancelPlayerEvents
08-16 16:42:16.940   326  1366 V AwesomePlayer: setAudioSink() 
08-16 16:42:16.940   326  1366 V AwesomePlayer: reset_l() 
08-16 16:42:16.940   326  1366 V AudioCache: notify(0xb1432280, 8, 0, 0)
08-16 16:42:16.940   326  1366 V AudioCache: ignored
08-16 16:42:16.940   326  1366 V AwesomePlayer: cancelPlayerEvents
08-16 16:42:16.940   326  1366 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-16 16:42:16.940   326  1366 V AwesomePlayer: setDataSource_l dataSource
08-16 16:42:16.940   326  1366 V LGParserOSAL: SniffLGParser start
08-16 16:42:16.940   326  1366 V LGParserOSAL: MainType:5, SubType=0
08-16 16:42:16.940   326  1366 V LGParserOSAL: #### check Mime : application/ogg
08-16 16:42:16.940   326  1366 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-16 16:42:16.940   326  1366 E MediaExtractor: Use LGExtractor :application/ogg 
08-16 16:42:16.945  8003  8003 D UEI.SmartControl: QS Service created
08-16 16:42:16.946  8586  8586 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-16 16:42:16.950  8586  8586 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 16:42:16.951  8586  8586 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 16:42:16.961  8003  8003 I UEI.SmartControl: Service initServices...
,08-16 16:42:16.961  8003  8003 D UEI.SmartControl: QS start get config
,08-16 16:42:16.978  8586  8586 V LGMDMManager: Create singleton instance
,08-16 16:42:16.995   326  1366 V LGParserOSAL: supported mime: application/ogg
08-16 16:42:16.995   326  1366 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-16 16:42:16.996   326  1366 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-16 16:42:16.996   326  1366 V AwesomePlayer: mBitrate = -1 bits/sec
08-16 16:42:16.996   326  1366 V AwesomePlayer: AudioTrack Setting
08-16 16:42:16.996   326  1366 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-16 16:42:16.996   326  1366 V AwesomePlayer: setAudioSource() 
,08-16 16:42:16.996   326  1366 V MediaPlayerService: prepare
08-16 16:42:16.996   326  1366 V AwesomePlayer: prepareAsync_l() 
08-16 16:42:16.996   326  1366 V MediaPlayerService: wait for prepare
08-16 16:42:16.996   326  8642 V AwesomePlayer: onPrepareAsyncEvent() 
08-16 16:42:16.996   326  8642 V AwesomePlayer: initAudioDecoder() 
08-16 16:42:16.996   326  8642 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 16:42:16.996   326  8642 V AudioSystem: isOffloadSupported()
08-16 16:42:16.996   326  8642 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 16:42:16.996   326  8642 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 16:42:16.996   326  8642 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 16:42:16.996   326  8642 V AwesomePlayer: getUseOffload() = 0 
08-16 16:42:16.996   326  8642 V OMXCodec: OMXCodec::Create
08-16 16:42:16.996   326  8642 V OMXCodec: findMatchingCodecs()
08-16 16:42:16.996   326  8642 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-16 16:42:16.996   326  8642 V OMXCodec: matchingCodecs.size()=1
08-16 16:42:16.996   326  8642 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-16 16:42:17.008   326  8642 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-16 16:42:17.008   326  8642 V LGCodecAdapter: LG Codec Adapter start
08-16 16:42:17.008   326  8642 V OMXCodec: OMXCodec Createtor
08-16 16:42:17.008   326  8642 V OMXCodec: setComponentRole
08-16 16:42:17.008   326  8642 V OMXCodec: configureCodec protected=0
08-16 16:42:17.008   326  8642 V LGCodecAdapter: called getLGCodecSpecificData
08-16 16:42:17.008   326  8642 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
,08-16 16:42:17.008   326  8642 V LGCodecOSAL: Called LGconfigureCodecMETA
08-16 16:42:17.008   326  8642 V LGCodecOSAL: Called LGconfigureCodecMSG
08-16 16:42:17.008   326  8642 V LGCodecOSAL: Not support LGCodec
08-16 16:42:17.008   326  8642 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 16:42:17.008   326  8642 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-16 16:42:17.008   326  8642 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-16 16:42:17.008   326  8642 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-16 16:42:17.008   326  8642 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 16:42:17.008   326  8642 V AudioSystem: isOffloadSupported()
08-16 16:42:17.008   326  8642 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 16:42:17.008   326  8642 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 16:42:17.008   326  8642 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-16 16:42:17.008   326  8642 V OMXCodec: init()
08-16 16:42:17.008   326  8642 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
,08-16 16:42:17.008   326  8642 V OMXCodec: allocateBuffers
08-16 16:42:17.009   326  8642 V OMXCodec: allocateBuffersOnPort portIndex=0
08-16 16:42:17.009   326  8642 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-16 16:42:17.009   326  8642 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on input port
08-16 16:42:17.009   326  8642 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on input port
08-16 16:42:17.009   326  8642 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
08-16 16:42:17.009   326  8642 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
08-16 16:42:17.009   326  8642 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 16:42:17.009   326  8642 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 16:42:17.009   326  8642 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on output port
08-16 16:42:17.009   326  8642 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-16 16:42:17.009   326  8642 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-16 16:42:17.009   326  8642 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
08-16 16:42:17.009   326  8642 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 16:42:17.009   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 16:42:17.009   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 16:42:17.009   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-16 16:42:17.009   326  8642 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 16:42:17.010   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-16 16:42:17.010   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-16 16:42:17.010   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-16 16:42:17.010   326  8642 V OMXCodec: init() mAsyncCompletion wait free! 
08-16 16:42:17.010   326  8642 V AwesomePlayer: finishAsyncPrepare_l() 
08-16 16:42:17.010   326  8642 V AudioCache: notify(0xb1432280, 5, 0, 0)
08-16 16:42:17.010   326  8642 V AudioCache: ignored
08-16 16:42:17.010   326  8642 V AudioCache: notify(0xb1432280, 1, 0, 0)
08-16 16:42:17.010   326  8642 V AudioCache: prepared
08-16 16:42:17.010   326  1366 V AudioCache: wait - success
08-16 16:42:17.010   326  1366 V MediaPlayerService: start
08-16 16:42:17.010   326  1366 V AwesomePlayer: play_l() 
08-16 16:42:17.010   326  1366 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-16 16:42:17.010   326  1366 V AwesomePlayer: createAudioPlayer_l
08-16 16:42:17.010   326  1366 V AwesomePlayer: seekAudioIfNecessary_l() 
08-16 16:42:17.010   326  1366 V AwesomePlayer: startAudioPlayer_l() 
08-16 16:42:17.010   326  1366 D AudioPlayer: start of Playback, useOffload 0
08-16 16:42:17.010   326  1366 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 16:42:17.010   326  1366 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 16:42:17.012   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-16 16:42:17.012   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-16 16:42:17.012   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-16 16:42:17.012   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-16 16:42:17.012   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-16 16:42:17.012   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 16:42:17.012   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048256
08-16 16:42:17.012   326  8644 V OMXCodec: [OMX.google.vorbi,s.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 16:42:17.012   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048416
08-16 16:42:17.012   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 16:42:17.012   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048496
08-16 16:42:17.012   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 16:42:17.012   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048656
,08-16 16:42:17.012   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 16:42:17.012   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-16 16:42:17.013   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 16:42:17.013   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-16 16:42:17.013   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-16 16:42:17.013   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-16 16:42:17.013   326  8644 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 16:42:17.013   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 16:42:17.013   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-16 16:42:17.013   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-16 16:42:17.013   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on output port
08-16 16:42:17.013   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14342e0 on output port
08-16 16:42:17.013   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-16 16:42:17.013   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-16 16:42:17.013   326  1366 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-16 16:42:17.014   326  1366 V AudioCache: notify(0xb1432280, 6, 0, 0)
08-16 16:42:17.014   326  1366 V AudioCache: ignored
08-16 16:42:17.014   326  1366 V MediaPlayerService: wait for playback complete
08-16 16:42:17.015   326  8645 V AudioCache: write(0xb57cd000, 4096)
,08-16 16:42:17.015   326  8645 V AudioCache: memcpy(0xac000000, 0xb57cd000, 4096)
08-16 16:42:17.025   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.025   326  8645 V AudioCache: memcpy(0xac001000, 0xb57cd000, 4096)
08-16 16:42:17.025   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.025   326  8645 V AudioCache: memcpy(0xac002000, 0xb57cd000, 4096)
08-16 16:42:17.026   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.026   326  8645 V AudioCache: memcpy(0xac003000, 0xb57cd000, 4096)
08-16 16:42:17.026   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.026   326  8645 V AudioCache: memcpy(0xac004000, 0xb57cd000, 4096)
08-16 16:42:17.027   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.027   326  8645 V AudioCache: memcpy(0xac005000, 0xb57cd000, 4096)
,08-16 16:42:17.027   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.027   326  8645 V AudioCache: memcpy(0xac006000, 0xb57cd000, 4096)
08-16 16:42:17.027   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.027   326  8645 V AudioCache: memcpy(0xac007000, 0xb57cd000, 4096)
08-16 16:42:17.028   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.028   326  8645 V AudioCache: memcpy(0xac008000, 0xb57cd000, 4096)
08-16 16:42:17.028   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.028   326  8645 V AudioCache: memcpy(0xac009000, 0xb57cd000, 4096)
08-16 16:42:17.028   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.029   326  8645 V AudioCache: memcpy(0xac00a000, 0xb57cd000, 4096)
08-16 16:42:17.029   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.029   326  8645 V AudioCache: memcpy(0xac00b000, 0xb57cd000, 4096)
08-16 16:42:17.029   326  8645 V AudioCache: write(0xb57cd000, 4096)
,08-16 16:42:17.029   326  8645 V AudioCache: memcpy(0xac00c000, 0xb57cd000, 4096)
08-16 16:42:17.030   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.030   326  8645 V AudioCache: memcpy(0xac00d000, 0xb57cd000, 4096)
08-16 16:42:17.030   326  8645 V AudioCache: write(0xb57cd000, 4096)
,08-16 16:42:17.030   326  8645 V AudioCache: memcpy(0xac00e000, 0xb57cd000, 4096)
08-16 16:42:17.030   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.030   326  8645 V AudioCache: memcpy(0xac00f000, 0xb57cd000, 4096)
08-16 16:42:17.035   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.035   326  8645 V AudioCache: memcpy(0xac010000, 0xb57cd000, 4096)
08-16 16:42:17.036   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.036   326  8645 V AudioCache: memcpy(0xac011000, 0xb57cd000, 4096)
08-16 16:42:17.036   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.036   326  8645 V AudioCache: memcpy(0xac012000, 0xb57cd000, 4096)
08-16 16:42:17.037   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.037   326  8645 V AudioCache: memcpy(0xac013000, 0xb57cd000, 4096)
08-16 16:42:17.037   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.037   326  8645 V AudioCache: memcpy(0xac014000, 0xb57cd000, 4096)
08-16 16:42:17.038   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.038   326  8645 V AudioCache: memcpy(0xac015000, 0xb57cd000, 4096)
08-16 16:42:17.038   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.038   326  8645 V AudioCache: memcpy(0xac016000, 0xb57cd000, 4096)
08-16 16:42:17.039   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.039   326  8645 V AudioCache: memcpy(0xac017000, 0xb57cd000, 4096)
08-16 16:42:17.039   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.039   326  8645 V AudioCache: memcpy(0xac018000, 0xb57cd000, 4096)
08-16 16:42:17.040   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.040   326  8645 V AudioCache: memcpy(0xac019000, 0xb57cd000, 4096)
08-16 16:42:17.040   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.040   326  8645 V AudioCache: memcpy(0xac01a000, 0xb57cd000, 4096)
08-16 16:42:17.041   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.041   326  8645 V AudioCache: memcpy(0xac01b000, 0xb57cd000, 4096)
08-16 16:42:17.041   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.041   326  8645 V AudioCache: memcpy(0xac01c000, 0xb57cd000, 4096)
08-16 16:42:17.042   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.042   326  8645 V AudioCache: memcpy(0xac01d000, 0xb57cd000, 4096)
08-16 16:42:17.042   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.042   326  8645 V AudioCache: memcpy(0xac01e000, 0xb57cd000, 4096)
08-16 16:42:17.043   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.043   326  8645 V AudioCache: memcpy(0xac01f000, 0xb57cd000, 4096)
08-16 16:42:17.043   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.043   326  8645 V AudioCache: memcpy(0xac020000, 0xb57cd000, 4096)
08-16 16:42:17.044   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.044   326  8645 V AudioCache: memcpy(0xac021000, 0xb57cd000, 4096)
08-16 16:42:17.045   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.045   326  8645 V AudioCache: memcpy(0xac022000, 0xb57cd000, 4096)
08-16 16:42:17.045   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.045   326  8645 V AudioCache: memcpy(0xac023000, 0xb57cd000, 4096)
08-16 16:42:17.046   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.046   326  8645 V AudioCache: memcpy(0xac024000, 0xb57cd000, 4096)
08-16 16:42:17.046   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.046   326  8645 V AudioCache: memcpy(0xac025000, 0xb57cd000, 4096)
08-16 16:42:17.047   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.047   326  8645 V AudioCache: memcpy(0xac026000, 0xb57cd000, 4096)
,08-16 16:42:17.047   326  8645 V AudioCache: write(0xb57cd000, 4096)
,08-16 16:42:17.047   326  8645 V AudioCache: memcpy(0xac027000, 0xb57cd000, 4096)
08-16 16:42:17.048   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.048   326  8645 V AudioCache: memcpy(0xac028000, 0xb57cd000, 4096)
08-16 16:42:17.048   326  8645 V AudioCache: write(0xb57cd000, 4096)
,08-16 16:42:17.048   326  8645 V AudioCache: memcpy(0xac029000, 0xb57cd000, 4096)
08-16 16:42:17.049   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.049   326  8645 V AudioCache: memcpy(0xac02a000, 0xb57cd000, 4096)
08-16 16:42:17.049   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.049   326  8645 V AudioCache: memcpy(0xac02b000, 0xb57cd000, 4096)
08-16 16:42:17.050   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.050   326  8645 V AudioCache: memcpy(0xac02c000, 0xb57cd000, 4096)
08-16 16:42:17.050   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.050   326  8645 V AudioCache: memcpy(0xac02d000, 0xb57cd000, 4096)
08-16 16:42:17.050   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.050   326  8645 V AudioCache: memcpy(0xac02e000, 0xb57cd000, 4096)
08-16 16:42:17.051   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-16 16:42:17.051   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.051   326  8645 V AudioCache: memcpy(0xac02f000, 0xb57cd000, 4096)
08-16 16:42:17.051   326  8645 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 16:42:17.051   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.051   326  8645 V AudioCache: memcpy(0xac030000, 0xb57cd000, 4096)
08-16 16:42:17.051   326  8645 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 16:42:17.051   326  8645 V AudioCache: write(0xb57cd000, 4096)
08-16 16:42:17.051   326  8645 V AudioCache: memcpy(0xac031000, 0xb57cd000, 4096)
08-16 16:42:17.051   326  8645 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 16:42:17.051   326  8645 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 16:42:17.051   326  8645 V AwesomePlayer: postAudioEOS() 
08-16 16:42:17.051   326  8645 V AudioCache: write(0xb57cd000, 280)
08-16 16:42:17.051   326  8645 V AudioCache: memcpy(0xac032000, 0xb57cd000, 280)
08-16 16:42:17.052   326  8642 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-16 16:42:17.053   326  8642 V AwesomePlayer: onStreamDone
08-16 16:42:17.053   326  8642 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-16 16:42:17.053   326  8642 V AudioCache: notify(0xb1432280, 2, 0, 0)
08-16 16:42:17.053   326  8642 V AudioCache: playback complete
08-16 16:42:17.053   326  8642 V AwesomePlayer: pause_l() 
08-16 16:42:17.053   326  1366 V AudioCache: wait - success
08-16 16:42:17.053   326  8642 V AudioCache: notify(0xb1432280, 7, 0, 0)
08-16 16:42:17.053   326  1366 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-16 16:42:17.053   326  8642 V AudioCache: ignored
08-16 16:42:17.053   326  8642 V AwesomePlayer: cancelPlayerEvents
08-16 16:42:17.053   326  8642 D AudioPlayer: Pause Playback at 1068125
08-16 16:42:17.053   326  1366 V AwesomePlayer: reset_l() 
08-16 16:42:17.053   326  1366 V AudioCache: notify(0xb1432280, 8, 0, 0)
08-16 16:42:17.053   326  1366 V AudioCache: ignored
08-16 16:42:17.053   326  1366 V AwesomePlayer: cancelPlayerEvents
08-16 16:42:17.053   326  1366 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-16 16:42:17.053   326  1366 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-16 16:42:17.053   326  1366 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-16 16:42:17.053   326  1366 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-16 16:42:17.053   326  1366 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 16:42:17.053   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 16:42:17.053   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 16:42:17.053   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-16 16:42:17.053   326  8644 V, OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
08-16 16:42:17.053   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-16 16:42:17.053   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
08-16 16:42:17.054   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-16 16:42:17.054   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 0
08-16 16:42:17.054   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-16 16:42:17.054   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 0
08-16 16:42:17.054   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-16 16:42:17.054   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 16:42:17.054   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14342e0 on port 1
08-16 16:42:17.054   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-16 16:42:17.054   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 1
08-16 16:42:17.054   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-16 16:42:17.054   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 1
08-16 16:42:17.054   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-16 16:42:17.054   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
08-16 16:42:17.054   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 16:42:17.054   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-16 16:42:17.054   326  1366 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 16:42:17.054   326  1366 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 16:42:17.054   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-16 16:42:17.054   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-16 16:42:17.054   326  8644 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-16 16:42:17.054   326  1366 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 16:42:17.054   326  1366 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-16 16:42:17.054   326  1366 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-16 16:42:17.055   326  1366 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-16 16:42:17.056   326  1366 D AudioPlayer: AudioPlayer releasing audio source
08-16 16:42:17.056   326  1366 D AudioPlayer: AudioPlayer done releasing audio source
08-16 16:42:17.056   326  1366 V AwesomePlayer: reset_l() 
08-16 16:42:17.056   326  1366 V AwesomePlayer: cancelPlayerEvents
08-16 16:42:17.056   326  1366 V AwesomePlayer: ~AwesomePlayer call
08-16 16:42:17.056   326  1366 V AwesomePlayer: reset_l() 
08-16 16:42:17.056   326  1366 V AwesomePlayer: cancelPlayerEvents
08-16 16:42:17.056  8586  8641 V SoundPool: close(31)
08-16 16:42:17.056  8586  8641 V SoundPool: pointer = 0x9fe35000, size = 205080, sampleRate = 48000, numChannels = 2
08-16 16:42:17.058  8586  8586 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 16:42:17.059  8586  8586 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-16 16:42:17.062  8586  8586 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5476
,08-16 16:42:17.065  8538  8538 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:42:17.108  8538  8538 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 16:42:17.113  8538  8538 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:42:17.116  8538  8538 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:42:17.120  8538  8538 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:42:17.123  8538  8538 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:42:17.126  8538  8538 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 16:42:17.130  8538  8538 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:42:17.134  8538  8538 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 16:42:17.147  8538  8538 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 16:42:17.319  8003  8003 I UEI.SmartControl: Supports setup maps: true
,08-16 16:42:17.323  8003  8003 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 16:42:17.323  8003  8003 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 16:42:17.323  8003  8003 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 16:42:17.323  8003  8003 I UEI.SmartControl: ### init IR Blaster...
08-16 16:42:17.326  8003  8003 D serial_port: Configuring serial port
08-16 16:42:17.327  8003  8003 E UEI.SmartControl: UEIBLaster setting for 616
08-16 16:42:17.327  8003  8003 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 16:42:17.327  8003  8003 I UEI.SmartControl: configuring settings for MAXQ616
08-16 16:42:17.327  8003  8003 I UEI.SmartControl: Get version...
08-16 16:42:17.342  8003  8650 D UEI.SmartControl: serial port data available: 21
,08-16 16:42:17.369  8003  8003 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-16 16:42:17.369  8003  8003 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 16:42:17.369  8003  8003 I UEI.SmartControl: QS saving settings...
08-16 16:42:17.372  8003  8003 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 16:42:17.395  8003  8650 D UEI.SmartControl: serial port data available: 4
,08-16 16:42:17.433  8003  8656 I UEI.SmartControl: Device manager: loading config....
,08-16 16:42:17.434  8003  8656 D UEI.SmartControl: ----------- loading internal config...
08-16 16:42:17.439  8003  8003 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-16 16:42:17.443  8003  8003 E UEI.SmartControl: Services init done
08-16 16:42:17.444  8003  8003 D UEI.SmartControl: QS Service init finished
08-16 16:42:17.447  8003  8003 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 16:42:17.447  8003  8003 D UEI.SmartControl: QS Service version code: 201091
08-16 16:42:17.458  8003  8003 D UEI.SmartControl: Service requested: Control
,08-16 16:42:17.463  8003  8656 E UEI.SmartControl: Loading SETTINGS...
08-16 16:42:17.464  8003  8003 D UEI.SmartControl: Request IControl service: devices are loaded...
08-16 16:42:17.466  8586  8586 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-16 16:42:17.467  8003  8020 I UEI.SmartControl: ------ IControl API: 11
08-16 16:42:17.467  8003  8020 D UEI.SmartControl: File observer start...
08-16 16:42:17.468  8003  8020 E UEI.SmartControl: IR Port is disabled: false
08-16 16:42:17.468  8003  8020 D UEI.SmartControl: Starting file observer...
08-16 16:42:17.468  8003  8020 I UEI.SmartControl: Registering callback...
08-16 16:42:17.468  8003  8003 D UEI.SmartControl: Internal service binding...
08-16 16:42:17.469  8003  8091 I UEI.SmartControl: ------ IControl API: 19
08-16 16:42:17.469  8003  8091 I UEI.SmartControl: Registering Services Ready callback...
08-16 16:42:17.473  8003  8656 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-16 16:42:17.498  8003  8655 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-16 16:42:17.501  8586  8604 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-16 16:42:17.502  8586  8639 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-16 16:42:17.502  8586  8639 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-16 16:42:17.502  8586  8586 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-16 16:42:17.503  8586  8586 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-16 16:42:17.503  8003  8021 I UEI.SmartControl: ------ IControl API: 8
08-16 16:42:17.504  8003  8655 D UEI.SmartControl: -----service ready thread exits
08-16 16:42:17.505  8586  8586 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-16 16:42:17.506  8586  8586 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-16 16:42:17.506  8586  8586 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-16 16:42:17.506  8586  8586 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-16 16:42:17.507  8586  8586 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-16 16:42:17.508  8586  8586 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-16 16:42:17.511  8586  8586 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-16 16:42:17.517  8586  8586 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 16:42:17.518  8586  8586 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 16:42:17.518  8586  8586 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 16:42:17.519  8586  8586 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 16:42:17.520  8586  8586 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 16:42:17.521  8586  8586 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-16 16:42:17.521  8586  8586 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-16 16:42:17.522  8586  8586 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471358537522]
08-16 16:42:17.526  8586  8586 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-16 16:42:17.532  1035  2022 I ActivityManager: Killing 7546:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-16 16:42:17.579  8586  8661 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-16 16:42:17.586  1035  2077 W libprocessgroup: failed to open /acct/uid_10093/pid_7546/cgroup.procs: No such file or directory
08-16 16:42:17.593  8586  8586 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-16 16:42:17.596  8586  8586 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 16:42:17.597  8586  8586 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-16 16:42:17.597  8586  8586 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-16 16:42:17.598  8586  8586 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-16 16:42:17.598  8586  8586 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-16 16:42:17.598  8586  8586 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-16 16:42:17.608  8586  8586 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-16 16:42:17.797  1035  1525 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 16:42:17.798  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 16:42:17.799  1035  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 16:42:17.800  1035  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 16:42:17.801  1035  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 16:42:17.802  1035  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-16 16:42:17.811  1035  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
,08-16 16:42:17.812  1035  1531 D ConnectivityService: identical MTU - not setting
08-16 16:42:17.812  1035  1531 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 16:42:17.812  1035  1531 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 16:42:17.812  1035  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:42:17.812  1035  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 16:42:17.814  1035  1531 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 16:42:17.816  1589  1796 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-16 16:42:18.966  1035  1525 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=116.5, 0.0, 0.0  rx=152.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1815243562] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 16:42:18.969  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=116.5, 0.0, 0.0  rx=152.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1815243559] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 16:42:18.969  1035  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 16:42:18.989  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 16:42:19.011  1035  1526 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-16 16:42:19.045  1035  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 16:42:19.062  1035  1117 D Tethering: MasterInitialState.processMessage what=3
,08-16 16:42:19.077  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:42:19.077  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:42:19.077  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:42:19.077  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:42:19.077  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:42:19.077  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:42:19.077  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:42:19.077  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 16:42:19.082  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 16:42:19.091  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:42:19.091  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:42:19.091  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:42:19.091  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:42:19.091  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:42:19.091  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:42:19.091  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:42:19.091  7049  7049 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 16:42:19.096  7049  7049 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 16:42:19.100  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 16:42:19.103  8538  8538 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 16:42:19.113  5763  5763 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-16 16:42:19.122  8538  8581 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 16:42:19.141  2205  2205 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 16:42:19.154  6888  6888 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 16:42:19.154  6888  6888 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 16:42:19.154  6888  6888 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 16:42:19.154  6888  6888 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 16:42:19.159  6888  6888 I AppUp4:CustModeStarterReceiver: onReceive
08-16 16:42:19.162  6888  6888 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1356dadd
08-16 16:42:19.162  6888  6888 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 16:42:19.162  6888  6888 D AppUp4:CustFacade: isPhone : true
08-16 16:42:19.163  6888  6888 D AppUp4:CustModeStarterReceiver: begin check event
08-16 16:42:19.163  6888  6888 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 16:42:19.168  4627  4627 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 16:42:19.168  4627  4627 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 16:42:19.169  4627  4627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 16:42:19.176  4627  4627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 16:42:19.180  2862  2862 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
08-16 16:42:19.196  7049  7124 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 16:42:19.196  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:42:19.196  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:42:19.196  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:42:19.196  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:42:19.196  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:42:19.196  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:42:19.196  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 16:42:19.206  7049  7124 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 16:42:19.206  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:42:19.206  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@194fe821 removed from the list
08-16 16:42:19.206  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:42:19.206  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:42:19.207  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:42:19.209  2862  2862 V DownloadManager: DownloadService onCreate
,08-16 16:42:19.222  7049  8663 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-16 16:42:19.222  7049  8663 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 16:42:19.227  2862  8664 I DownloadManager: in removeSpuriousFiles
08-16 16:42:19.229  2862  8664 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-16 16:42:19.230  4627  8678 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 16:42:19.232  4627  8678 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-16 16:42:19.238  2862  8664 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@22aaff62 on behalf of 2862
,08-16 16:42:19.238  4627  8680 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 16:42:19.238  4627  8680 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 16:42:19.238  2862  8664 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-16 16:42:19.239  2862  8664 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-16 16:42:19.239  2862  8664 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-16 16:42:19.239  2862  8664 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-16 16:42:19.239  2862  8664 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-16 16:42:19.239  2862  8664 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-16 16:42:19.239  2862  8664 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-16 16:42:19.239  2862  8664 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-16 16:42:19.239  2862  8664 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-16 16:42:19.239  2862  8664 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-16 16:42:19.239  2862  8664 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-16 16:42:19.240  1035  1050 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8681 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-16 16:42:19.246  2862  8664 I DownloadManager: in trimDatabase
08-16 16:42:19.246  2862  8664 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-16 16:42:19.247  4627  8678 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-16 16:42:19.248  2862  8664 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@46ac8f3 on behalf of 2862
08-16 16:42:19.253  4627  4627 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-16 16:42:19.254  4627  4627 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-16 16:42:19.254  4627  4627 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,08-16 16:42:19.257  4627  4627 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-16 16:42:19.257  2862  2862 V DownloadManager: DownloadService onStartCommand
08-16 16:42:19.258  2862  8665 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-16 16:42:19.266  2862  8665 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@10bdafae on behalf of 2862
08-16 16:42:19.267   319  8703 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 16:42:19.268   319  8703 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,08-16 16:42:19.268  4627  4627 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-16 16:42:19.271  2862  8665 V DownloadManager: processing inserted download 1
08-16 16:42:19.271  2862  8665 V DownloadManager: processing inserted download 4
08-16 16:42:19.273  2862  8665 V DownloadManager: processing inserted download 7
08-16 16:42:19.275  2862  8665 V DownloadManager: processing inserted download 8
08-16 16:42:19.275  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 16:42:19.277  2862  8665 V DownloadManager: processing inserted download 9
08-16 16:42:19.277  2862  8665 V DownloadManager: processing inserted download 10
08-16 16:42:19.278  2862  8665 V DownloadManager: processing inserted download 11
08-16 16:42:19.278  2862  8665 V DownloadManager: processing inserted download 12
08-16 16:42:19.279  2862  8665 V DownloadManager: processing inserted download 13
08-16 16:42:19.280  2862  8665 V DownloadManager: processing inserted download 14
08-16 16:42:19.280  2862  8665 V DownloadManager: processing inserted download 16
,08-16 16:42:19.284  2862  2862 V DownloadManager: DownloadService onDestroy
08-16 16:42:19.287  8681  8681 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 16:42:19.288  8681  8681 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 16:42:19.289  8681  8681 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 16:42:19.289  8681  8681 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 16:42:19.333  8681  8681 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 16:42:19.342  8681  8681 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-16 16:42:19.512  1035  1956 I art     : Explicit concurrent mark sweep GC freed 71603(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.042ms total 124.098ms
,08-16 16:42:19.543  8681  8681 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 16:42:19.582  8681  8681 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 16:42:19.583  8681  8681 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 16:42:19.717  8681  8681 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 16:42:19.760  8681  8681 I HubEmail: JNI_OnLoad()
08-16 16:42:19.760  8681  8681 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 16:42:19.760  8681  8681 I HubEmail: registerNatives()
08-16 16:42:19.760  8681  8681 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 16:42:19.760  8681  8681 I HubEmail: registerNativeMethods()
08-16 16:42:19.760  8681  8681 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 16:42:19.761  8681  8681 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-16 16:42:19.777  8681  8715 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 16:42:19.810  3296  3296 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 16:42:19.810  3296  3296 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 16:42:19.810  3296  3296 I LgeMiscReceiver: networkInfo.isConnected() = true
08-16 16:42:19.810  3296  3296 D PhoneState: setPdpRejectCasuse : false
,08-16 16:42:19.819   319  8719 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 16:42:19.819   319  8719 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
08-16 16:42:19.865  1035  1050 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8720 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-16 16:42:20.001  8720  8720 D LgDataFeature: LgDataFeature() Constructor: none
08-16 16:42:20.001  8720  8720 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 16:42:20.005  8720  8720 D PhoneMonitor: Register our PhoneStateListener
08-16 16:42:20.044  8720  8720 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-16 16:42:20.049  8720  8720 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 16:42:20.073  8720  8720 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-16 16:42:20.074  8720  8720 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-16 16:42:20.074  8720  8720 D TelephonyAutoProfiling: [parse] Load xml
08-16 16:42:20.078  8720  8720 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-16 16:42:20.078  8720  8720 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-16 16:42:20.078  8720  8720 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-16 16:42:20.078  8720  8720 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-16 16:42:20.078  8720  8720 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-16 16:42:20.078  8720  8720 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-16 16:42:20.078  8720  8720 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-16 16:42:20.078  8720  8720 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-16 16:42:20.078  8720  8720 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-16 16:42:20.078  8720  8720 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-16 16:42:20.078  8720  8720 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-16 16:42:20.078  8720  8720 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-16 16:42:20.078  8720  8720 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-16 16:42:20.078  8720  8720 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-16 16:42:20.079  8720  8720 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-16 16:42:20.079  8720  8720 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-16 16:42:20.079  8720  8720 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-16 16:42:20.085  8720  8720 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-16 16:42:20.120  1035  2086 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8740 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 16:42:20.122  1035  2086 I ActivityManager: Killing 8060:com.google.android.talk/u0a72 (adj 15): empty #17
,08-16 16:42:20.186  1035  1792 W libprocessgroup: failed to open /acct/uid_10072/pid_8060/cgroup.procs: No such file or directory
,08-16 16:42:20.204  1826  8757 I CheckinService: active receiver: enabled
,08-16 16:42:20.219  1826  8757 I CheckinService: Preparing to send checkin request
,08-16 16:42:20.219  1826  8757 I EventLogService: Accumulating logs since 1471358500809
,08-16 16:42:20.266  1826  8757 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-16 16:42:20.384  1035  1050 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8760 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-16 16:42:20.439  1035  1913 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8777 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-16 16:42:20.445  1035  1051 I ActivityManager: Killing 8112:com.android.contacts/u0a19 (adj 15): empty #17
08-16 16:42:20.463   354   354 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 451us total 24.726ms
,08-16 16:42:20.486   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 405us total 21.906ms
,08-16 16:42:20.505   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 405us total 18.839ms
,08-16 16:42:20.534  1035  1956 W libprocessgroup: failed to open /acct/uid_10019/pid_8112/cgroup.procs: No such file or directory
08-16 16:42:20.562  8760  8760 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-16 16:42:20.563  8760  8760 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-16 16:42:20.624  8760  8760 I MultiDex: VM with version 2.1.0 has multidex support
08-16 16:42:20.624  8760  8760 I MultiDex: install
08-16 16:42:20.624  8760  8760 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-16 16:42:20.632  1035  1720 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8794 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 16:42:20.634  1035  1720 I ActivityManager: Killing 8133:com.android.gallery3d/u0a27 (adj 15): empty #17
08-16 16:42:20.642  1035  1525 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-16 16:42:20.642  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-16 16:42:20.643  1035  1525 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-16 16:42:20.643  1035  1525 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-16 16:42:20.644  1035  1525 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-16 16:42:20.644  1035  1525 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-16 16:42:20.706  1035  2086 W libprocessgroup: failed to open /acct/uid_10027/pid_8133/cgroup.procs: No such file or directory
,08-16 16:42:20.719  8760  8760 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-16 16:42:20.743  8794  8794 I art     : Almond Protected OAT
,08-16 16:42:20.807  8794  8794 D WeatherApplication: removeAccount
,08-16 16:42:20.812  8794  8794 D WeatherApplication: Account.length = 0
08-16 16:42:20.813  8794  8794 E WeatherApplication: OPERATOR:OPEN
08-16 16:42:20.818  8794  8794 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:42:20
08-16 16:42:20.821  8794  8794 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 16:42:20.821  8794  8794 D Weather.Utils: 2 : All the weather widget is gone.
,08-16 16:42:20.823  8794  8794 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 16:42:20.826  8794  8794 D WeatherAncestor: connectivity changed - connection : true
08-16 16:42:20.827  8794  8794 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-16 16:42:20.841  8794  8794 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-16 16:42:20.841  8794  8794 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 16:42:20.841  8794  8794 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-16 16:42:20.864  8794  8794 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 16:42:20.864  8794  8794 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:42:20
,08-16 16:42:20.941  1035  2077 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8813 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 16:42:20.943  1035  2077 I ActivityManager: Killing 8196:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-16 16:42:20.986  1035  1051 W libprocessgroup: failed to open /acct/uid_10080/pid_8196/cgroup.procs: No such file or directory
,08-16 16:42:21.090   278   339 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-16 16:42:21.090   278   339 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 16:42:21.090   278   339 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 16:42:21.093  8813  8831 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-16 16:42:21.097   278   339 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 16:42:21.097   278   339 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 16:42:21.097   278   339 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 16:42:21.097  8813  8831 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 16:42:21.118   278   339 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 16:42:21.119   278   339 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 16:42:21.119   278   339 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 16:42:21.119  8813  8836 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 16:42:21.121   278   339 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 16:42:21.121   278   339 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 16:42:21.121   278   339 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 16:42:21.121  8813  8836 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-16 16:42:21.124  8834  8834 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-16 16:42:21.179  8834  8834 I dex2oat : dex2oat took 54.695ms (threads: 4)
,08-16 16:42:21.192  8760  8775 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 16:42:21.192  8760  8775 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 16:42:21.192  8760  8775 I Adreno-EGL: Build Date: 12/12/14 금
08-16 16:42:21.192  8760  8775 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 16:42:21.192  8760  8775 I Adreno-EGL: Remote Branch: 
08-16 16:42:21.192  8760  8775 I Adreno-EGL: Local Patches: 
08-16 16:42:21.192  8760  8775 I Adreno-EGL: Reconstruct Branch: 
,08-16 16:42:21.289  8813  8813 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 16:42:21.297  8813  8813 I LibraryLoader: Loading: webviewchromium
08-16 16:42:21.299  8813  8813 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3341-3344)
08-16 16:42:21.299  8813  8813 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 16:42:21.307  8813  8813 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a26438b}
08-16 16:42:21.307  8813  8813 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 16:42:21.308  8813  8813 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 16:42:21.315  8813  8813 I BrowserStartupController: Initializing chromium process, renderers=0
08-16 16:42:21.316  8813  8813 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 16:42:21.338   326   326 V AudioPolicyService: registerClient() client 0xb557c100, uid 10093
08-16 16:42:21.339  8813  8867 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-16 16:42:21.341  8813  8813 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-16 16:42:21.343  8813  8813 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-16 16:42:21.344  8813  8813 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-16 16:42:21.369  8813  8813 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 16:42:21.369  8813  8813 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 16:42:21.369  8813  8813 I Adreno-EGL: Build Date: 12/12/14 금
08-16 16:42:21.369  8813  8813 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 16:42:21.369  8813  8813 I Adreno-EGL: Remote Branch: 
08-16 16:42:21.369  8813  8813 I Adreno-EGL: Local Patches: 
08-16 16:42:21.369  8813  8813 I Adreno-EGL: Reconstruct Branch: 
,08-16 16:42:21.441  8813  8813 I NSApplication: Starting up...
,08-16 16:42:21.461  8760  8775 D LgDataFeature: LgDataFeature() Constructor: none
08-16 16:42:21.461  8760  8775 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 16:42:21.471  1035  2022 I ActivityManager: Killing 8158:com.android.vending/u0a44 (adj 15): empty #17
,08-16 16:42:21.537  1035  1956 W libprocessgroup: failed to open /acct/uid_10044/pid_8158/cgroup.procs: No such file or directory
,08-16 16:42:21.549  2205  2205 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-16 16:42:21.559  2205  2205 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-16 16:42:21.559  2205  2205 D c       : Getting all permits...
08-16 16:42:21.559  2205  2205 D a       : Opening database...
08-16 16:42:21.564  2205  2205 D a       : Opening database auth.proximity.permit_store...
08-16 16:42:21.567  2205  2205 D a       : Closing database...
,08-16 16:42:21.598  8760  8775 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 16:42:21.598  8760  8775 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 16:42:21.598  8760  8775 I Adreno-EGL: Build Date: 12/12/14 금
08-16 16:42:21.598  8760  8775 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 16:42:21.598  8760  8775 I Adreno-EGL: Remote Branch: 
08-16 16:42:21.598  8760  8775 I Adreno-EGL: Local Patches: 
08-16 16:42:21.598  8760  8775 I Adreno-EGL: Reconstruct Branch: 
,08-16 16:42:21.688  8760  8775 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 16:42:21.688  8760  8775 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 16:42:21.688  8760  8775 I Adreno-EGL: Build Date: 12/12/14 금
08-16 16:42:21.688  8760  8775 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 16:42:21.688  8760  8775 I Adreno-EGL: Remote Branch: 
08-16 16:42:21.688  8760  8775 I Adreno-EGL: Local Patches: 
08-16 16:42:21.688  8760  8775 I Adreno-EGL: Reconstruct Branch: 
,08-16 16:42:21.844   319  8886 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 16:42:21.844   319  8886 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-16 16:42:21.885   319  8886 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-16 16:42:21.996  1035  1525 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=64.2, 0.0, 0.0  rx=78.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1815240533] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 16:42:21.997  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2447 sc=60 link=72 tx=64.2, 0.0, 0.0  rx=78.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1815240531] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 16:42:21.997  1035  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 16:42:22.233  7049  8663 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-16 16:42:22.234  7049  8663 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-16 16:42:22.240  7049  8663 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 16:42:22.241  7049  8893 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-16 16:42:22.241  7049  8893 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-16 16:42:22.241  7049  8893 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 16:42:22.241  7049  8893 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 16:42:22.241  7049  8893 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-16 16:42:22.246  7049  8663 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 16:42:22.246  7049  8663 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-16 16:42:22.248  7049  8896 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 929, name: IncomingSocketThread/Receiver)
08-16 16:42:22.249  7049  8896 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 929, thread name: IncomingSocketThread/Receiver)
08-16 16:42:22.249  7049  8896 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-16 16:42:22.249  7049  8896 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 929, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-16 16:42:22.253  7049  8895 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 928, name: IncomingSocketThread/Sender)
,08-16 16:42:22.259  7049  8898 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 930, name: OutgoingSocketThread/Receiver)
08-16 16:42:22.259  7049  8898 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 930, thread name: OutgoingSocketThread/Receiver)
08-16 16:42:22.260  7049  8898 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-16 16:42:22.260  7049  8898 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 930, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-16 16:42:22.261   319  8899 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 16:42:22.261   319  8899 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
08-16 16:42:22.263  7049  8897 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 927, name: OutgoingSocketThread/Sender)
08-16 16:42:22.282  1826  8757 I CheckinTask: Sending checkin request (7909 bytes)
,08-16 16:42:22.434  8003  8657 D UEI.SmartControl: Internal timer expired: 2
,08-16 16:42:22.434  8003  8657 D UEI.SmartControl: unbind internal service
,08-16 16:42:22.468  8003  8651 D serial_port: close(fd = 24)
,08-16 16:42:22.480  8003  8651 I UEI.SmartControl: Serial port is closed.
08-16 16:42:23.359   319  8899 D libc-netbsd: res_queryN name = www.google.com succeed
,08-16 16:42:23.381   319  8901 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-16 16:42:23.384   319  8901 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-16 16:42:23.384   319  8901 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-16 16:42:24.050  1035  8556 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 14:42:23 GMT], X-Android-Received-Millis=[1471358544049], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471358536204]}
08-16 16:42:24.050  1035  8556 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 16:42:24.051  1035  8556 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,08-16 16:42:24.063  1035  1531 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-16 16:42:24.064  1035  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 16:42:24.064  1035  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 16:42:24.064  1035  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 16:42:24.064  1035  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 16:42:24.065  1035  1531 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-16 16:42:24.066  1035  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 16:42:24.066  1035  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:42:24.066  1035  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 16:42:24.067  1035  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 16:42:24.073  1589  1796 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-16 16:42:24.079  1035  1531 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:42:24.080  1862  1862 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:42:24.080  1862  1862 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 16:42:24.081  1035  1525 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 16:42:24.081  1035  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 16:42:24.081  1035  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 16:42:24.095  1035  1527 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-16 16:42:24.111  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 16:42:24.112  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 16:42:24.113  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 16:42:24.248  1826  8757 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-16 16:42:24.265  1826  8757 I CheckinService: active receiver: disabled
,08-16 16:42:24.320  2205  2205 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-16 16:42:24.337  2205  2205 I GCM     : GCM config loaded
,08-16 16:42:24.359  8720  8720 V SetupWizard: Connected to Gservices successfully
,08-16 16:42:24.473   319  8703 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-16 16:42:24.786  2205  8922 D GCM     : Connected
,08-16 16:42:24.804  1035  1407 D PowerManagerServiceEx: acquireWakeLockInternal: lock=506009113, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,08-16 16:42:24.818  8586  8586 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-16 16:42:24.818  8586  8586 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:5476
,08-16 16:42:24.858  2613  2613 D [Concierge]Service: onStartCommand(). Type : 9
,08-16 16:42:24.874   319  8719 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-16 16:42:24.886  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=506009113 [*alarm*], flags=0x0
08-16 16:42:24.894  2205  8922 D GCM     : Message class com.google.e.a.a.q
,08-16 16:42:24.933  8467  8716 V FormManager: There are no updated forms. The schedule will be deleted.
,08-16 16:42:24.938  8467  8716 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-16 16:42:24.984  1035  1913 I ActivityManager: Killing 7911:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-16 16:42:25.010  1035  1525 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=38.6, 0.0, 0.0  rx=40.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1815237518] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 16:42:25.013  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=38.6, 0.0, 0.0  rx=40.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1815237516] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 16:42:25.013  1035  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 16:42:25.061  1035  1792 W libprocessgroup: failed to open /acct/uid_10037/pid_7911/cgroup.procs: No such file or directory
,08-16 16:42:25.217  7049  7124 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-16 16:42:25.218  7049  7124 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-16 16:42:25.219  7049  7124 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@39975802 Bundle[{}]
08-16 16:42:25.220  7049  7124 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 16:42:25.220  7049  7124 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-16 16:42:25.221  7049  7124 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-16 16:42:25.222  7049  7124 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 16:42:25.222  7049  7124 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-16 16:42:25.223  7049  7124 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 16:42:25.233  7049  7124 I System.out: Running OutgoingSocketThread
08-16 16:42:25.236  7049  8940 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-16 16:42:25.236  7049  8940 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-16 16:42:26.115  8813  8833 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-16 16:42:26.836  1035  2053 I ActivityManager: Killing 7956:com.lge.settings.easy/1000 (adj 15): empty #17
,08-16 16:42:26.874  1035  1720 W libprocessgroup: failed to open /acct/uid_1000/pid_7956/cgroup.procs: No such file or directory
,08-16 16:42:28.021  1035  1525 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=40.3, 0.0, 0.0  rx=38.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1815234508] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 16:42:28.033  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=40.3, 0.0, 0.0  rx=38.5 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1815234495] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 16:42:28.033  1035  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 16:42:28.248  7049  8940 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-16 16:42:28.248  7049  8940 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-16 16:42:28.248  7049  8940 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 16:42:28.248  7049  8940 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 16:42:28.249  7049  8940 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-16 16:42:28.253  7049  8943 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-16 16:42:28.253  7049  8943 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-16 16:42:28.253  7049  8943 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 16:42:28.254  7049  8943 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 16:42:28.254  7049  8943 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-16 16:42:28.256  7049  8946 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 940, name: OutgoingSocketThread/Receiver)
08-16 16:42:28.256  7049  8946 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 940, thread name: OutgoingSocketThread/Receiver)
08-16 16:42:28.256  7049  8946 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-16 16:42:28.256  7049  8946 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 940, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-16 16:42:28.258  7049  8945 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 939, name: OutgoingSocketThread/Sender)
08-16 16:42:28.260  7049  8948 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 942, name: IncomingSocketThread/Receiver)
08-16 16:42:28.260  7049  8948 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 942, thread name: IncomingSocketThread/Receiver)
08-16 16:42:28.260  7049  8948 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-16 16:42:28.260  7049  8948 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 942, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-16 16:42:28.262  7049  8947 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 941, name: IncomingSocketThread/Sender)
08-16 16:42:30.293  1589  1589 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-16 16:42:30.355  1035  1464 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 16:42:30.399  1035  1113 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8949 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-16 16:42:30.404  2078  2078 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-16 16:42:30.414  1035  1035 D administrator: Handling package changes for user 0
,08-16 16:42:30.446  1589  1589 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-16 16:42:30.447  1589  1589 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-16 16:42:30.454  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 16:42:30.479  8949  8949 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 16:42:30.509  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-16 16:42:30.509  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 16:42:30.545  1035  1112 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 16:42:30.548  1035  1112 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-16 16:42:30.550  8949  8949 D LgDataFeature: LgDataFeature() Constructor: none
08-16 16:42:30.550  8949  8949 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 16:42:30.553  2078  2078 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-16 16:42:30.555  2484  2484 V GmsNetworkLocationProvi: DISABLE
08-16 16:42:30.579  2484  2484 E GCoreFlp: Bound FusedProviderService with LocationManager
08-16 16:42:30.580  1035  1112 D LocationProviderProxy: applying state to connected service
,08-16 16:42:30.727  8949  8994 I Babel   : MmsConfig: mnc/mcc: 0/0
08-16 16:42:30.727  8949  8994 I Babel   : MmsConfig.loadMmsSettings
08-16 16:42:30.735  8949  8994 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 16:42:30.735  8949  8994 I Babel   : MmsConfig.loadFromDatabase
,08-16 16:42:30.754  8949  8994 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,08-16 16:42:30.754  8949  8994 I Babel   : MmsConfig.loadFromResources
08-16 16:42:30.756  8949  8994 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-16 16:42:30.757  8949  8994 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 16:42:30.767  8949  8949 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 16:42:30.776  8949  8992 W AudioCapabilities: Unsupported mime audio/evrc
08-16 16:42:30.777  8949  8992 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 16:42:30.780  8949  8992 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 16:42:30.792  8949  8992 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-16 16:42:30.794  8949  8992 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 16:42:30.796  8949  8992 W AudioCapabilities: Unsupported mime audio/evrc
08-16 16:42:30.804  1826  8995 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-16 16:42:30.804  1826  8995 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-16 16:42:30.809  6888  6888 I AppUp4:CustModeStarterReceiver: onReceive
08-16 16:42:30.815  6888  6888 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1356dadd
08-16 16:42:30.815  6888  6888 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 16:42:30.815  6888  6888 D AppUp4:CustFacade: isPhone : true
08-16 16:42:30.815  6888  6888 D AppUp4:CustModeStarterReceiver: begin check event
08-16 16:42:30.815  6888  6888 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-16 16:42:30.818  1826  5104 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-16 16:42:30.825  8949  8992 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-16 16:42:30.828  8949  8992 W VideoCapabilities: Unsupported mime video/divx
08-16 16:42:30.830  8949  8992 W VideoCapabilities: Unsupported mime video/divx311
,08-16 16:42:30.832  8949  8992 W VideoCapabilities: Unsupported mime video/divx4
,08-16 16:42:30.839  8949  8992 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-16 16:42:30.851  1035  1982 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8999 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-16 16:42:30.863  1035  1562 I ActivityManager: Killing 8517:com.lge.bnr/1000 (adj 15): empty #17
08-16 16:42:30.869  8949  8992 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-16 16:42:30.873  8949  8992 W AudioCapabilities: Unsupported mime audio/eac3
08-16 16:42:30.874  8949  8992 W AudioCapabilities: Unsupported mime audio/ac3
,08-16 16:42:30.876  8949  8992 W AudioCapabilities: Unsupported mime audio/g726
08-16 16:42:30.876  8949  8992 W AudioCapabilities: Unsupported mime audio/wma-voice
08-16 16:42:30.878  8949  8992 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-16 16:42:30.879  8949  8992 W AudioCapabilities: Unsupported mime audio/adpcm
08-16 16:42:30.880  8949  8992 W VideoCapabilities: Unsupported mime video/theora
08-16 16:42:30.882  8949  8992 W VideoCapabilities: Unsupported mime video/mjpg
,08-16 16:42:30.955  1035  1914 W libprocessgroup: failed to open /acct/uid_1000/pid_8517/cgroup.procs: No such file or directory
08-16 16:42:30.978  8999  8999 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 16:42:30.979  8999  8999 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 16:42:30.979  8999  8999 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 16:42:30.981  8999  8999 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,08-16 16:42:30.981  8999  8999 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 16:42:31.051  1035  1525 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=20.7, 0.0, 0.0  rx=19.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1815231477] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 16:42:31.052  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=20.7, 0.0, 0.0  rx=19.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1815231476] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 16:42:31.052  1035  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 16:42:31.056  8999  8999 I SystemConfig: BUILD Country: EU
08-16 16:42:31.056  8999  8999 I SystemConfig: BUILD Operator: OPEN
08-16 16:42:31.101  1035  2077 I ActivityManager: Killing 8490:com.lge.sync/1000 (adj 15): empty #17
,08-16 16:42:31.246  1035  1792 W libprocessgroup: failed to open /acct/uid_1000/pid_8490/cgroup.procs: No such file or directory
,08-16 16:42:31.264  7049  7124 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 951)
08-16 16:42:31.269  8999  9018 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-16 16:42:31.269  8999  9018 I SystemConfig: existFile = false
08-16 16:42:31.269  7049  7124 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-16 16:42:31.269  7049  7124 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 952)
08-16 16:42:31.269  8999  9018 I SystemConfig: canReadFile = false
08-16 16:42:31.269  8999  9018 I SystemConfig: systemFeature RCS result false
,08-16 16:42:31.269  8999  9018 D SystemConfig: refreshRcsSupport() :false
08-16 16:42:31.275  7049  7124 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 16:42:31.275  7049  7124 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a461446 added. We now have 3 listener(s)
08-16 16:42:31.309  1035  2077 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=9023 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
08-16 16:42:31.309  1035  2086 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 16:42:31.312  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 16:42:31.312  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 16:42:31.312  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 16:42:31.312  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 16:42:31.312  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e282607 added. We now have 4 listener(s)
08-16 16:42:31.313  7049  7124 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 16:42:31.313  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 16:42:31.316  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 16:42:31.319  7049  7124 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 16:42:31.319  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:42:31.319  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:42:31.319  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:42:31.319  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:42:31.319  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:42:31.319  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:42:31.319  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 16:42:31.321  7049  7124 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 16:42:31.321  7049  7124 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 16:42:31.322  7049  7124 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:42:31.323  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:42:31.323  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:42:31.323  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:42:31.323  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:42:31.323  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 16:42:31.323  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 16:42:31.323  7049  7124 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a461446 removed from the list
08-16 16:42:31.323  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:42:31.323  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e282607 removed from the list
08-16 16:42:31.323  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:42:31.325  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:42:31.327  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:42:31.327  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:42:31.327  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:42:31.327  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:42:31.330  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:42:31.330  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:42:31.330  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:42:31.330  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e282607 not in the list
08-16 16:42:31.330  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:42:31.330  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:42:31.332  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:42:31.332  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:42:31.332  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:42:31.332  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e282607 not in the list
08-16 16:42:31.332  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:42:31.332  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:42:31.332  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:42:31.332  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a461446 not in the list
08-16 16:42:31.333  7049  7124 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 16:42:31.333  7049  7124 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a1e55d added. We now have 3 listener(s)
08-16 16:42:31.333  1035  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 16:42:31.336  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 16:42:31.336  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 16:42:31.336  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 16:42:31.337  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 16:42:31.337  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16bf2ed2 added. We now have 4 listener(s)
08-16 16:42:31.337  7049  7124 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 16:42:31.337  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 16:42:31.347  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 16:42:31.351  7049  7124 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 16:42:31.351  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:42:31.351  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:42:31.351  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:42:31.351  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:42:31.351  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:42:31.351  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:42:31.351  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 16:42:31.353  7049  7124 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 16:42:31.354  7049  7124 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 16:42:31.356  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 16:42:31.356  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:42:31.356  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 16:42:31.356  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 16:42:31.356  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 16:42:31.356  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 16:42:31.358  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:42:31.360  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 16:42:31.360  1035  1562 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 16:42:31.368  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 16:42:31.368  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 16:42:31.370  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 16:42:31.371  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 16:42:31.372  7049  7124 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 16:42:31.373  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:42:31.373  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:42:31.389  9023  9023 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 16:42:31.389  9023  9023 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 16:42:31.389  9023  9023 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 16:42:31.390  9023  9023 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 16:42:31.494  9023  9023 I AppConfig: Total System Memory = 2995761152
,08-16 16:42:31.506  9023  9023 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-16 16:42:31.613  1035  2053 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=9042 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 16:42:31.615  1035  2053 I ActivityManager: Killing 7218:com.android.settings/1000 (adj 15): empty #17
,08-16 16:42:31.686  1035  2077 W libprocessgroup: failed to open /acct/uid_1000/pid_7218/cgroup.procs: No such file or directory
,08-16 16:42:31.943  9042  9042 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-16 16:42:32.022  9042  9042 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 16:42:32.022  9042  9042 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 16:42:32.077  9042  9042 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-16 16:42:32.099  9042  9042 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 16:42:32.100  9042  9042 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-16 16:42:32.117  9042  9042 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-16 16:42:32.117  9042  9042 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-16 16:42:32.134  1035  2022 I ActivityManager: Killing 8681:com.lge.email/u0a23 (adj 15): empty #17
,08-16 16:42:32.167  1035  1982 W libprocessgroup: failed to open /acct/uid_10023/pid_8681/cgroup.procs: No such file or directory
,08-16 16:42:32.177  2862  4276 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-16 16:42:32.178  4923  9082 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-16 16:42:32.180  2862  4276 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1573d0dc on behalf of 9042
,08-16 16:42:32.222  1035  1956 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=9083 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-16 16:42:32.252  9042  9042 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-16 16:42:32.304  9042  9042 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-16 16:42:32.340  9083  9083 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-16 16:42:32.442  1035  1720 I art     : Explicit concurrent mark sweep GC freed 42914(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.176ms total 128.210ms
,08-16 16:42:32.458  9083  9083 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-16 16:42:32.458  9083  9083 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-16 16:42:32.458  9083  9083 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,08-16 16:42:32.458  9083  9083 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-16 16:42:32.458  9083  9083 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-16 16:42:32.458  9083  9083 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-16 16:42:32.471  1035  1792 I ActivityManager: Killing 8467:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-16 16:42:32.528  1035  1051 W libprocessgroup: failed to open /acct/uid_10026/pid_8467/cgroup.procs: No such file or directory
,08-16 16:42:32.761  1035  1982 V SIM_STK : Menu title from STK is T-Mobile
,08-16 16:42:32.774  4923  9082 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 595 ms] updated apps [took 595 ms] 
,08-16 16:42:34.072  1035  1525 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=10.3, 0.0, 0.0  rx=9.6 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1815228457] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 16:42:34.082  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=10.3, 0.0, 0.0  rx=9.6 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1815228453] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 16:42:34.082  1035  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 16:42:34.374  7049  7124 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:42:34.374  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:42:34.374  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 16:42:34.384  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:42:34.384  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:42:34.384  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 16:42:34.385  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 16:42:34.386  7049  7124 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a1e55d removed from the list
08-16 16:42:34.386  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:42:34.387  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16bf2ed2 removed from the list
08-16 16:42:34.387  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:42:34.387  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:42:34.388  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:42:34.388  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:42:34.391  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:42:34.391  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:42:34.392  7049  7124 D BluetoothLeScanner: could not find callback wrapper
08-16 16:42:34.392  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 16:42:34.392  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:42:34.392  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16bf2ed2 not in the list
08-16 16:42:34.392  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:42:34.392  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:42:34.393  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 16:42:34.397  7049  7124 D BluetoothLeScanner: could not find callback wrapper
08-16 16:42:34.397  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 16:42:34.397  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:42:34.397  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:42:34.397  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16bf2ed2 not in the list
08-16 16:42:34.397  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:42:34.397  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:42:34.397  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:42:34.397  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a1e55d not in the list
08-16 16:42:34.398  7049  7124 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 16:42:34.398  7049  7124 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63d661e added. We now have 3 listener(s)
08-16 16:42:34.399  1035  2086 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 16:42:34.403  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 16:42:34.403  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 16:42:34.403  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 16:42:34.403  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 16:42:34.404  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3675ceff added. We now have 4 listener(s)
08-16 16:42:34.404  7049  7124 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 16:42:34.404  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 16:42:34.408  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 16:42:34.415  7049  7124 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 16:42:34.415  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:42:34.415  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:42:34.415  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:42:34.415  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:42:34.415  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:42:34.415  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:42:34.415  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 16:42:34.418  7049  7124 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 16:42:34.418  7049  7124 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 16:42:34.420  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 16:42:34.424  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:42:34.424  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-16 16:42:34.426  7049  7124 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-16 16:42:34.426  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-16 16:42:34.429  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-16 16:42:34.429  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-16 16:42:34.429  7049  7124 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 16:42:34.429  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 16:42:34.433  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 16:42:34.434  7049  7124 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 16:42:34.434  7049  7124 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-16 16:42:34.437  7049  7049 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 16:42:34.438  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 16:42:34.439  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-16 16:42:34.439  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 16:42:34.439  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 16:42:34.443  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 16:42:34.445  1035  2086 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 16:42:34.451  1035  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 16:42:34.452  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 16:42:34.453  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 16:42:34.455  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 16:42:34.456  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-16 16:42:34.459  7049  7124 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-16 16:42:34.461  7049  9125 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 16:42:34.462  8286  8411 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-16 16:42:34.463  7049  9125 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-16 16:42:37.104  1035  1525 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=5.7, 0.0, 0.0  rx=5.3 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1815225424] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 16:42:37.118  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=5.7, 0.0, 0.0  rx=5.3 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1815225410] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 16:42:37.118  1035  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 16:42:37.464  7049  7124 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 16:42:37.465  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:42:37.465  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 16:42:37.465  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 16:42:37.465  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 16:42:37.465  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-16 16:42:37.478  7049  9125 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-16 16:42:37.478  7049  9125 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 16:42:37.479  7049  9125 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 16:42:37.479  7049  7049 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 16:42:37.480  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 16:42:37.480  7049  7124 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 16:42:37.480  7049  7049 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 16:42:37.480  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 16:42:37.480  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:42:37.481  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 16:42:37.483  7049  7049 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:42:37.483  7049  7049 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-16 16:42:37.485  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:42:37.485  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:42:37.485  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 16:42:37.485  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 16:42:37.485  7049  7124 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63d661e removed from the list
08-16 16:42:37.485  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:42:37.485  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3675ceff removed from the list
08-16 16:42:37.485  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:42:37.485  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:42:37.486  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:42:37.486  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:42:37.487  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:42:37.488  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 16:42:37.491  7049  7124 D BluetoothLeScanner: could not find callback wrapper
08-16 16:42:37.492  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 16:42:37.492  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:42:37.492  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3675ceff not in the list
08-16 16:42:37.492  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:42:37.492  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:42:37.493  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:42:37.494  7049  7124 D BluetoothLeScanner: could not find callback wrapper
08-16 16:42:37.494  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 16:42:37.494  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:42:37.494  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:42:37.494  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3675ceff not in the list
08-16 16:42:37.494  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:42:37.494  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:42:37.494  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:42:37.494  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63d661e not in the list
08-16 16:42:37.496  7049  7124 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 16:42:37.496  7049  7124 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11e25c1b added. We now have 3 listener(s)
08-16 16:42:37.498  1035  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 16:42:37.501  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 16:42:37.502  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 16:42:37.502  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 16:42:37.502  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 16:42:37.502  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d53a1b8 added. We now have 4 listener(s)
08-16 16:42:37.502  7049  7124 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 16:42:37.506  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 16:42:37.510  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 16:42:37.515  7049  7124 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 16:42:37.515  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:42:37.515  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:42:37.515  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:42:37.515  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:42:37.515  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:42:37.515  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:42:37.515  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 16:42:37.518  7049  7124 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 16:42:37.519  7049  7124 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 16:42:37.521  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:42:37.522  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:42:37.524  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 16:42:37.524  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 16:42:37.524  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 16:42:37.524  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 16:42:37.524  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 16:42:37.528  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 16:42:37.530  1035  1562 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 16:42:37.535  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 16:42:37.537  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 16:42:37.539  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 16:42:37.539  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 16:42:37.541  7049  7124 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-16 16:42:40.137  1035  1525 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1815222392] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 16:42:40.140  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-47 f=2447 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1815222388] gl rssi=-47 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 16:42:40.140  1035  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 16:42:40.550  7049  7124 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 16:42:40.551  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:42:40.551  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 16:42:40.561  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 16:42:40.561  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 16:42:40.561  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 16:42:40.561  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 16:42:40.561  7049  7124 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11e25c1b removed from the list
08-16 16:42:40.561  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:42:40.561  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d53a1b8 removed from the list
08-16 16:42:40.562  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:42:40.562  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:42:40.565  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:42:40.565  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:42:40.570  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:42:40.571  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 16:42:40.578  7049  7124 D BluetoothLeScanner: could not find callback wrapper
08-16 16:42:40.578  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 16:42:40.578  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:42:40.578  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d53a1b8 not in the list
08-16 16:42:40.578  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:42:40.578  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:42:40.581  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:42:40.582  7049  7124 D BluetoothLeScanner: could not find callback wrapper
08-16 16:42:40.582  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 16:42:40.582  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:42:40.582  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:42:40.582  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d53a1b8 not in the list
08-16 16:42:40.582  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:42:40.582  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:42:40.582  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:42:40.582  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11e25c1b not in the list
08-16 16:42:40.583  7049  7124 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 16:42:40.583  7049  7124 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@307d2164 added. We now have 3 listener(s)
08-16 16:42:40.584  1035  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 16:42:40.589  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 16:42:40.589  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 16:42:40.589  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 16:42:40.589  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 16:42:40.589  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ccbdfcd added. We now have 4 listener(s)
08-16 16:42:40.589  7049  7124 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 16:42:40.593  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 16:42:40.599  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 16:42:40.602  7049  7124 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 16:42:40.602  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 16:42:40.602  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 16:42:40.602  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 16:42:40.602  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 16:42:40.602  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 16:42:40.602  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 16:42:40.602  7049  7124 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 16:42:40.608  7049  7124 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 16:42:40.608  7049  7124 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 16:42:40.611  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:42:40.613  7049  7049 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 16:42:40.614  7049  7124 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 16:42:40.614  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 16:42:40.614  7049  7124 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 16:42:40.615  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:42:40.615  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:42:40.615  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 16:42:40.615  7049  7124 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 16:42:40.615  7049  7124 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@307d2164 removed from the list
08-16 16:42:40.615  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:42:40.615  7049  7124 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ccbdfcd removed from the list
08-16 16:42:40.615  7049  7124 D io.jxcore.node.ConnectivityMonitor: stop
08-16 16:42:40.615  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:42:40.616  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:42:40.616  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 16:42:40.620  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:42:40.620  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:42:40.620  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:42:40.621  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ccbdfcd not in the list
08-16 16:42:40.621  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:42:40.621  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:42:40.622  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 16:42:40.622  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 16:42:40.623  7049  7124 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 16:42:40.623  7049  7124 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ccbdfcd not in the list
08-16 16:42:40.623  7049  7124 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 16:42:40.623  7049  7124 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 16:42:40.623  7049  7124 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 16:42:40.623  7049  7124 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@307d2164 not in the list
08-16 16:42:40.624  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 16:42:40.624  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 16:42:40.624  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 16:42:40.625  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 16:42:40.625  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 16:42:40.625  7049  7124 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 16:42:42.646  7049  9126 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 961, name: My test thread name)
,08-16 16:42:43.164  1035  1525 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1815219364] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 16:42:43.174  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1815219354] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 16:42:43.174  1035  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 16:42:44.643  7049  7124 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 961
08-16 16:42:44.643  7049  7124 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 961, name: My test thread name)
,08-16 16:42:44.658  7049  9127 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 962, name: My test thread name)
08-16 16:42:44.659  7049  9127 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 962, thread name: My test thread name)
08-16 16:42:44.659  7049  9127 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 962, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
08-16 16:42:44.661  7049  7124 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 16:42:44.665  7049  9128 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 966, name: My test thread name)
08-16 16:42:44.665  7049  9128 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 966, thread name: My test thread name): Test exception.
08-16 16:42:44.665  7049  9128 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 966, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-16 16:42:44.671  7049  7124 I jxcore-log: Total number of executed tests:  82
08-16 16:42:44.671  7049  7124 I jxcore-log: 
08-16 16:42:44.671  7049  7124 I jxcore-log: Number of passed tests:  82
08-16 16:42:44.671  7049  7124 I jxcore-log: 
08-16 16:42:44.672  7049  7124 I jxcore-log: Number of failed tests:  0
08-16 16:42:44.672  7049  7124 I jxcore-log: 
08-16 16:42:44.672  7049  7124 I jxcore-log: Number of ignored tests:  0
08-16 16:42:44.672  7049  7124 I jxcore-log: 
08-16 16:42:44.672  7049  7124 I jxcore-log: Total duration:  101641
08-16 16:42:44.672  7049  7124 I jxcore-log: 
08-16 16:42:44.673  7049  7124 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-16 16:42:44.673  7049  7124 I jxcore-log: 
08-16 16:42:44.691  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:42:44.691  7049  7124 I jxcore-log: 
08-16 16:42:44.695  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:42:44.695  7049  7124 I jxcore-log: 
,08-16 16:42:44.700  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:42:44.700  7049  7124 I jxcore-log: 
08-16 16:42:44.701  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:42:44.701  7049  7124 I jxcore-log: 
08-16 16:42:44.702  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:42:44.702  7049  7124 I jxcore-log: 
08-16 16:42:44.703  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:42:44.703  7049  7124 I jxcore-log: 
08-16 16:42:44.713  7049  7049 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-16 16:42:44.718  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 16:42:44.718  7049  7124 I jxcore-log: 
08-16 16:42:44.720  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:42:44.720  7049  7124 I jxcore-log: 
08-16 16:42:44.721  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:42:44.721  7049  7124 I jxcore-log: 
08-16 16:42:44.722  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:42:44.722  7049  7124 I jxcore-log: 
08-16 16:42:44.723  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 16:42:44.723  7049  7124 I jxcore-log: 
08-16 16:42:44.724  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 16:42:44.724  7049  7124 I jxcore-log: 
08-16 16:42:44.725  7049  9126 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 961, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,08-16 16:42:44.729  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 16:42:44.729  7049  7124 I jxcore-log: 
08-16 16:42:44.730  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 16:42:44.730  7049  7124 I jxcore-log: 
08-16 16:42:44.732  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 16:42:44.732  7049  7124 I jxcore-log: 
08-16 16:42:44.732  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 16:42:44.732  7049  7124 I jxcore-log: 
08-16 16:42:44.733  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 16:42:44.733  7049  7124 I jxcore-log: 
08-16 16:42:44.734  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:42:44.734  7049  7124 I jxcore-log: 
08-16 16:42:44.735  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:42:44.735  7049  7124 I jxcore-log: 
08-16 16:42:44.736  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:42:44.736  7049  7124 I jxcore-log: 
08-16 16:42:44.737  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 16:42:44.737  7049  7124 I jxcore-log: 
08-16 16:42:44.738  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 16:42:44.738  7049  7124 I jxcore-log: 
08-16 16:42:44.739  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 16:42:44.739  7049  7124 I jxcore-log: 
08-16 16:42:44.739  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 16:42:44.739  7049  7124 I jxcore-log: 
08-16 16:42:44.740  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 16:42:44.740  7049  7124 I jxcore-log: 
08-16 16:42:44.741  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 16:42:44.741  7049  7124 I jxcore-log: 
08-16 16:42:44.742  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 16:42:44.742  7049  7124 I jxcore-log: 
08-16 16:42:44.742  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 16:42:44.742  7049  7124 I jxcore-log: 
08-16 16:42:44.743  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 16:42:44.743  7049  7124 I jxcore-log: 
08-16 16:42:44.744  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetoo,th":"on","wifi":"off","cellular":"doNotCare"}
08-16 16:42:44.744  7049  7124 I jxcore-log: 
08-16 16:42:44.744  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 16:42:44.744  7049  7124 I jxcore-log: 
08-16 16:42:44.746  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 16:42:44.746  7049  7124 I jxcore-log: 
08-16 16:42:44.747  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 16:42:44.747  7049  7124 I jxcore-log: 
08-16 16:42:44.748  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 16:42:44.748  7049  7124 I jxcore-log: 
08-16 16:42:44.748  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:42:44.748  7049  7124 I jxcore-log: 
08-16 16:42:44.749  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:42:44.749  7049  7124 I jxcore-log: 
08-16 16:42:44.750  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:42:44.750  7049  7124 I jxcore-log: 
08-16 16:42:44.751  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:42:44.751  7049  7124 I jxcore-log: 
08-16 16:42:44.752  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:42:44.752  7049  7124 I jxcore-log: 
08-16 16:42:44.752  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:42:44.752  7049  7124 I jxcore-log: 
08-16 16:42:44.753  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:42:44.753  7049  7124 I jxcore-log: 
08-16 16:42:44.754  7049  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 16:42:44.754  7049  7124 I jxcore-log: 
,08-16 16:42:45.010  9129  9129 D AndroidRuntime: 
08-16 16:42:45.010  9129  9129 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-16 16:42:45.017  9129  9129 D AndroidRuntime: CheckJNI is OFF
08-16 16:42:45.135  9129  9129 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 16:42:45.147  1035  1113 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-16 16:42:45.150  1035  1113 I ActivityManager: Killing 7049:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-16 16:42:45.210  1035  1050 I WindowState: WIN DEATH: Window{2b782a98 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-16 16:42:45.212  1035  1530 D WifiService: Client connection lost with reason: 4
08-16 16:42:45.215  1035  1050 D InputDispatcher: Window went away: Window{2b782a98 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 16:42:45.370  1035  1113 I ActivityManager:   Force finishing activity ActivityRecord{2a5dd44d u0 com.test.thalitest/.MainActivity t6}
,08-16 16:42:45.417   350   360 E GBMv2   : DFP En is all cleared set to be enabled
,08-16 16:42:45.425  1035  1051 W ActivityManager: Spurious death for ProcessRecord{a422d0c 7049:com.test.thalitest/u0a118}, curProc for 7049: null
08-16 16:42:45.426  1035  1123 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-16 16:42:45.432  1035  1123 I ActivityManager:   Force finishing activity ActivityRecord{2a5dd44d u0 com.test.thalitest/.MainActivity t6 f}
,08-16 16:42:45.433  1035  1123 W ActivityManager: Duplicate finish request for ActivityRecord{2a5dd44d u0 com.test.thalitest/.MainActivity t6 f}
,08-16 16:42:45.484  1959  2343 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-16 16:42:45.484  1959  2343 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2b0f32b co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-16 16:42:45.485  2078  2078 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-16 16:42:45.485  1959  1977 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-16 16:42:45.485  1959  1977 D SplitWindowPolicy: topRunningActivity=ActivityInfo{db0d388 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-16 16:42:45.489  2078  2078 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-16 16:42:45.490  1589  1589 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-16 16:42:45.502  2484  2638 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-16 16:42:45.503  1035  1464 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-16 16:42:45.513  4923  4923 I art     : Explicit concurrent mark sweep GC freed 22770(1306KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 2.092ms total 73.446ms
08-16 16:42:45.515  2035  2035 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-16 16:42:45.515  3763  3763 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-16 16:42:45.517  8286  8286 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-16 16:42:45.517  8286  8286 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 16:42:45.533  4793  4793 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-16 16:42:45.533  4793  4793 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-16 16:42:45.533  4793  4793 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-16 16:42:45.533  4793  4793 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-16 16:42:45.533  4793  4793 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 16:42:45.533  4793  4793 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 16:42:45.533  4793  4793 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 16:42:45.533  4793  4793 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
,08-16 16:42:45.533  4793  4793 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 16:42:45.533  4793  4793 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 16:42:45.534  4793  4793 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 16:42:45.534  4793  4793 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 16:42:45.541  1035  1913 V SIM_STK : Menu title from STK is T-Mobile
08-16 16:42:45.556  1035  1112 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-16 16:42:45.609  8538  8538 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-16 16:42:45.622  2078  2078 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,08-16 16:42:45.625  2078  2161 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-16 16:42:45.629  1035  1035 I art     : Explicit concurrent mark sweep GC freed 15417(1018KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.324ms total 151.099ms
08-16 16:42:45.647  1589  1589 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-16 16:42:45.648  1589  1637 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 16:42:45.648  1589  1637 D KeyguardModel: createShortcutInfo...
08-16 16:42:45.651  2078  2078 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-16 16:42:45.652  1915  1915 D ActionManagerService: notifyUserLog: 1000003
08-16 16:42:45.652  3763  4816 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-16 16:42:45.652  1826  1826 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-16 16:42:45.653  2078  2078 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-16 16:42:45.679  2078  2078 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-16 16:42:45.680  2078  2078 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-16 16:42:45.684  1589  1637 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 16:42:45.684  1589  1637 D KeyguardModel: createShortcutInfo...
08-16 16:42:45.684  1915  1915 D ActionManagerService: notifyUserLog: 1000004
08-16 16:42:45.685  2078  2078 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-16 16:42:45.685  3763  4816 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-16 16:42:45.689  1035  1051 V SIM_STK : Menu title from STK is T-Mobile
08-16 16:42:45.689  1035  1051 V SIM_STK : Menu title from STK is T-Mobile
08-16 16:42:45.691  1589  1637 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-16 16:42:45.691  1589  1637 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 16:42:45.691  1589  1637 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 16:42:45.692  1589  1637 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 16:42:45.694  3763  3781 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-16 16:42:45.699  2205  2205 I ConfigService: onCreate
08-16 16:42:45.700  2205  2205 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-16 16:42:45.700  1879  1879 D SplitUIManager: split_name #11 / not available #0
08-16 16:42:45.701  1879  1879 D SplitUIService: removed split : 
08-16 16:42:45.704  1589  1637 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 16:42:45.704  1589  1637 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-16 16:42:45.714  1589  1637 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 16:42:45.714  1589  1637 D KeyguardModel: createShortcutInfo...
,08-16 16:42:45.719  1589  1637 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-16 16:42:45.719  1589  1637 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 16:42:45.722  1589  1637 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 16:42:45.722  1589  1637 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-16 16:42:45.723  1589  1637 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-16 16:42:45.723  1589  1637 D KeyguardModel: createShortcutInfo...
08-16 16:42:45.724  2078  2078 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-16 16:42:45.724  2078  2078 I GBoardWebViewUtils: , create_time: 1430832262123
08-16 16:42:45.724  2078  2078 I GBoardWebViewUtils: , expire_time: 0
08-16 16:42:45.724  2078  2078 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-16 16:42:45.724  2078  2078 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-16 16:42:45.724  2078  2078 I GBoardWebViewUtils: , display: false
08-16 16:42:45.724  2078  2078 I GBoardWebViewUtils: , animation: false }
08-16 16:42:45.724  2078  2078 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-16 16:42:45.724  2078  2078 I GBoardWebViewUtils: , create_time: 1430832262287
08-16 16:42:45.724  2078  2078 I GBoardWebViewUtils: , expire_time: 0
08-16 16:42:45.724  2078  2078 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 16:42:45.724  2078  2078 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 16:42:45.724  2078  2078 I GBoardWebViewUtils: , display: false
08-16 16:42:45.724  2078  2078 I GBoardWebViewUtils: , animation: false }
08-16 16:42:45.724  2078  2078 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-16 16:42:45.724  2078  2078 I GBoardWebViewUtils: , create_time: 1471007226523
08-16 16:42:45.724  2078  2078 I GBoardWebViewUtils: , expire_time: 0
08-16 16:42:45.724  2078  2078 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-16 16:42:45.724  2078  2078 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 16:42:45.724  2078  2078 I GBoardWebViewUtils: , display: false
08-16 16:42:45.724  2078  2078 I GBoardWebViewUtils: , animation: false }
08-16 16:42:45.726  1826  1826 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-16 16:42:45.727  2078  9162 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-16 16:42:45.731  2205  2205 I ConfigService: onBind returning update interface
08-16 16:42:45.731  2205  2205 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-16 16:42:45.731  2205  2205 I ConfigService: onBind returning config service
08-16 16:42:45.737  1589  1637 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 16:42:45.737  1589  1637 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 16:42:45.737  1589  1637 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 16:42:45.737  1589  1637 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 16:42:45.738  1589  1637 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 16:42:45.738  1589  1637 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-16 16:42:45.740  1589  1637 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 16:42:45.740  1589  1637 D KeyguardModel: createShortcutInfo...
08-16 16:42:45.740  1589  1589 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-16 16:42:45.740  1589  1589 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-16 16:42:45.742  1879  1879 D SplitUIManager: split_name #11 / not available #0
08-16 16:42:45.742  1879  1879 I SplitUIService: split app #11
08-16 16:42:45.744  1035  1035 D administrator: Handling package changes for user 0
08-16 16:42:45.745  1589  1589 D KeyguardModel: handleShortcutListChanged...
08-16 16:42:45.745  1589  1589 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-16 16:42:45.749  1589  1637 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 16:42:45.749  1589  1637 D KeyguardModel: createShortcutInfo...
08-16 16:42:45.750  1589  1637 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 16:42:45.750  1589  1637 D KeyguardModel: createShortcutInfo...
08-16 16:42:45.751  2078  2078 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 16:42:45.751  2078  2078 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-16 16:42:45.752  1589  1637 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 16:42:45.752  1589  1637 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-16 16:42:45.753  1589  1637 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 16:42:45.753  1589  1637 D KeyguardModel: createShortcutInfo...
,08-16 16:42:45.759  1035  1913 V SIM_STK : Menu title from STK is T-Mobile
08-16 16:42:45.765  1589  1637 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 16:42:45.766  1589  1637 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-16 16:42:45.767  1589  1637 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-16 16:42:45.767  1589  1637 D KeyguardModel: createShortcutInfo...
08-16 16:42:45.769  1035  1792 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-16 16:42:45.769  8286  8286 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 16:42:45.769  8286  8286 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 16:42:45.769  1589  1637 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 16:42:45.769  8286  8286 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 16:42:45.769  8286  8286 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 16:42:45.769  1589  1637 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-16 16:42:45.769  8286  8286 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 16:42:45.769  8286  8286 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 16:42:45.769  8286  8286 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 16:42:45.769  8286  8286 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 16:42:45.769  8286  8286 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 16:42:45.769  8286  8286 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 16:42:45.769  8286  8286 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 16:42:45.770  1589  1637 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 16:42:45.770  1589  1637 D KeyguardModel: createShortcutInfo...
08-16 16:42:45.778  2205  2205 I ConfigService: onDestroy
,08-16 16:42:45.800  1589  1589 D KeyguardModel: handleShortcutListChanged...
08-16 16:42:45.800  1589  1589 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-16 16:42:45.812  2078  2078 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-16 16:42:45.821  1826  9164 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-16 16:42:45.826  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,08-16 16:42:45.826  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 16:42:45.826  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-16 16:42:45.828  1035  1564 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-16 16:42:45.842  2078  2093 I art     : Background partial concurrent mark sweep GC freed 7181(327KB) AllocSpace objects, 6(19MB) LOS objects, 34% free, 60MB/92MB, paused 13.703ms total 38.214ms
08-16 16:42:45.842  5813  9166 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-16 16:42:45.858  1826  9171 I PeopleContactsSync: CP2 sync disabled
,08-16 16:42:45.862  1826  5104 I Icing   : doRemovePackageData com.test.thalitest
08-16 16:42:45.883  1826  9170 W GmsApplication: Using Auth Proxy for data requests.
,08-16 16:42:45.886  1826  9170 W GmsApplication: Using Auth Proxy for data requests.
,08-16 16:42:45.886  6888  6888 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-16 16:42:45.895  2165  9173 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-16 16:42:45.911   344   415 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-16 16:42:45.912  3229  9174 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-16 16:42:45.922  1035  2086 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=9176 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-16 16:42:45.926  2078  2078 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-16 16:42:45.929  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 16:42:45.931  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-16 16:42:45.932  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-16 16:42:45.933  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-16 16:42:45.935  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-16 16:42:45.949  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{34d18bdf u0 com.lge.launcher2/.Launcher t5} time:437994
08-16 16:42:45.958  2078  2078 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-16 16:42:45.958  2078  2270 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-16 16:42:45.958  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 16:42:45.958  2078  2270 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-16 16:42:45.962  1035  1123 I art     : Explicit concurrent mark sweep GC freed 12118(810KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.364ms total 325.638ms
,08-16 16:42:45.968  9176  9176 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 16:42:45.968  9176  9176 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 16:42:45.969  9176  9176 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 16:42:45.969  9176  9176 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 16:42:45.976  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-16 16:42:45.977  2078  2078 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 16:42:45.977  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 16:42:45.988  2078  2078 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-16 16:42:45.990  2613  2613 D [Concierge]Service: onStartCommand(). Type : 8
08-16 16:42:45.990  2613  2613 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-16 16:42:45.992  2613  2613 D [Concierge]Service: Update widget ID : 11
08-16 16:42:45.993  2078  2078 D [Concierge]WidgetView: change position of spinner
08-16 16:42:45.994  2078  2078 I [Concierge]WidgetView: initWebView(). Time : 1471358565994
08-16 16:42:45.994  2613  2613 D [Concierge]Service: onStartCommand(). Type : 0
08-16 16:42:46.021  2078  2078 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 95042715
08-16 16:42:46.021  2078  2078 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-16 16:42:46.022  2078  2078 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-16 16:42:46.024  9176  9176 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-16 16:42:46.024  2078  2078 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@33524607
08-16 16:42:46.024  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,08-16 16:42:46.027  2078  2078 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 16:42:46.027  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 16:42:46.031  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-16 16:42:46.032  2078  2078 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-16 16:42:46.032  2078  2078 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-16 16:42:46.032  9176  9176 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-16 16:42:46.032  2078  2078 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471358156162, New one : 1471358565994
08-16 16:42:46.032  2078  2078 D [Concierge]WidgetView: Unregister all receivers
08-16 16:42:46.032  2078  2078 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-16 16:42:46.033  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 16:42:46.034  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-16 16:42:46.036  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-16 16:42:46.037  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-16 16:42:46.038  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-16 16:42:46.039  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,08-16 16:42:46.044  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 16:42:46.044  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 16:42:46.071  9129  9129 D AndroidRuntime: Shutting down VM
,08-16 16:42:46.081  2078  2078 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-16 16:42:46.084  9176  9176 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 16:42:46.089  2078  2078 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-16 16:42:46.089  1035  1112 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 16:42:46.089  2078  2078 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-16 16:42:46.091  2078  2078 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 16:42:46.101  1035  1112 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-16 16:42:46.107  2078  2078 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-16 16:42:46.110  2078  2078 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1915e010 time:438154
08-16 16:42:46.110  9176  9176 D LgDataFeature: LgDataFeature() Constructor: none
08-16 16:42:46.110  9176  9176 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 16:42:46.156  9176  9176 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-16 16:42:46.166  1035  1914 I ActivityManager: Killing 8740:com.android.chrome/u0a57 (adj 15): empty #17
08-16 16:42:46.192  1035  1525 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1815216336] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 16:42:46.192  1035  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1815216336] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 16:42:46.192  1035  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 16:42:46.209  2078  2078 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-16 16:42:46.243  2078  2893 I GBoardtInterface: onReloaded()
,08-16 16:42:46.244  2078  2078 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-16 16:42:46.256  2035  2035 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-16 16:42:46.256  2035  2035 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-16 16:42:46.256  1035  1050 W libprocessgroup: failed to open /acct/uid_10057/pid_8740/cgroup.procs: No such file or directory
,08-16 16:42:46.258  2035  2035 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-16 16:42:46.258  3763  3781 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 16:42:46.261  8538  8538 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-16 16:42:46.261  3763  3782 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 16:42:46.292  1035  2022 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=9202 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 16:42:46.322  1035  1123 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=9219 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-16 16:42:46.328  1915  1915 D ActionManagerService: notifyUserLog: 1000001
08-16 16:42:46.329  3763  4816 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-16 16:42:46.329  3763  4816 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-16 16:42:46.332  1915  1915 D ActionManagerService: notifyUserLog: 1000001
08-16 16:42:46.333  3763  4816 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-16 16:42:46.334  3763  4816 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-16 16:42:46.334  3763  4816 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-16 16:42:46.334  3763  4816 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-16 16:42:46.334  3763  3781 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-16 16:42:46.336  2078  2078 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
,08-16 16:42:46.336  2078  2078 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-16 16:42:46.338  2078  2078 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-16 16:42:46.338  2078  2078 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 16:42:46.339  2078  2078 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-16 16:42:46.339  2078  2078 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-16 16:42:46.377  1035  1957 I ActivityManager: Killing 8777:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-16 16:42:46.377  9202  9202 E SQLiteDatabase: Failed to open database '/data/data/com.lge.lifetracker/databases/lifetracker2.db'.
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 16:42:46.377  9202  9202 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: Unable to open database for writing.
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at android.os.Looper.loop(Looper.java:135)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 16:42:46.378  9202  9202 E LifetrackerProvider2: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 16:42:46.447  1035  1913 W libprocessgroup: failed to open /acct/uid_10062/pid_8777/cgroup.procs: No such file or directory

```
