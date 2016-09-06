#### Test 828946820542738_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-06 19:11:00.100  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-06 19:11:00.100  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
09-06 19:11:00.100  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-06 19:11:00.101  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,09-06 19:11:00.114  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
09-06 19:11:00.114  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
09-06 19:11:00.116  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
09-06 19:11:00.118  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
09-06 19:11:00.424  6717  6717 D AndroidRuntime: 
09-06 19:11:00.424  6717  6717 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-06 19:11:00.429  6717  6717 D AndroidRuntime: CheckJNI is OFF
09-06 19:11:00.634  6717  6717 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-06 19:11:00.645  1032  1929 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-06 19:11:00.661  1969  3935 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-06 19:11:00.667  1032  1929 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-06 19:11:00.669  1032  1929 D ActivityManager: setTaskToReturnTo : TaskRecord{1e9b59ad #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-06 19:11:00.669  1032  1929 D ActivityManager: setTaskToReturnTo : TaskRecord{1e9b59ad #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-06 19:11:00.671  1032  1929 D WindowStateEx: AppWindowTokenEx init.. 
09-06 19:11:00.672   347   353 E GBMv2   : DFP En is all cleared set to be enabled
09-06 19:11:00.701  1032  1929 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6732 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-06 19:11:00.704  6717  6717 D AndroidRuntime: Shutting down VM
09-06 19:11:00.760  1969  1984 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-06 19:11:00.761  1969  1984 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1b546f7a co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-06 19:11:00.761  1969  1985 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-06 19:11:00.762  1969  1985 D SplitWindowPolicy: topRunningActivity=ActivityInfo{f46d32b co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-06 19:11:00.812  6732  6732 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-06 19:11:00.905  6732  6732 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-06 19:11:00.917  6732  6732 I LibraryLoader: Loading: webviewchromium
09-06 19:11:00.920  6732  6732 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9167-9170)
09-06 19:11:00.920  6732  6732 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-06 19:11:00.948  6732  6732 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {26a68538}
,09-06 19:11:00.951  6732  6732 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 19:11:00.951  6732  6732 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,09-06 19:11:00.964  6732  6732 I BrowserStartupController: Initializing chromium process, renderers=0
,09-06 19:11:00.965  6732  6732 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 19:11:00.988  6732  6732 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-06 19:11:00.989  6732  6732 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-06 19:11:00.989  6732  6732 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,09-06 19:11:00.999   331  3958 V AudioPolicyService: registerClient() client 0xb1022c80, uid 10118
09-06 19:11:01.009  6732  6732 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 19:11:01.009  6732  6732 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 19:11:01.009  6732  6732 I Adreno-EGL: Build Date: 12/12/14 금
09-06 19:11:01.009  6732  6732 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 19:11:01.009  6732  6732 I Adreno-EGL: Remote Branch: 
09-06 19:11:01.009  6732  6732 I Adreno-EGL: Local Patches: 
09-06 19:11:01.009  6732  6732 I Adreno-EGL: Reconstruct Branch: 
,09-06 19:11:01.031  1032  1094 D BluetoothManagerService: Message: 20
09-06 19:11:01.031  1032  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a5f20cf:true
,09-06 19:11:01.113  6732  6777 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
09-06 19:11:01.115  6732  6732 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,09-06 19:11:01.130  6732  6732 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 19:11:01.136  6732  6732 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-06 19:11:01.139  6732  6732 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-06 19:11:01.143  6732  6732 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-06 19:11:01.143  6732  6732 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,09-06 19:11:01.159  6732  6732 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-06 19:11:01.167  6732  6732 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 19:11:01.167  6732  6732 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 19:11:01.234  6732  6790 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:11:01.234  6732  6790 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:11:01.259  1032  1090 W ActivityManager: Activity pause timeout for ActivityRecord{264614e2 u0 com.test.thalitest/.MainActivity t6}
,09-06 19:11:01.335  1032  1575 I art     : Explicit concurrent mark sweep GC freed 30827(1420KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.011ms total 146.665ms
,09-06 19:11:01.341  6732  6797 D OpenGLRenderer: Render dirty regions requested: true
,09-06 19:11:01.342  6732  6797 I OpenGLRenderer: Initialized EGL, version 1.4
09-06 19:11:01.355  6732  6797 D OpenGLRenderer: Enabling debug mode 0
,09-06 19:11:01.366  6732  6732 D Atlas   : Validating map...
09-06 19:11:01.369  1032  2003 D SplitWindow: check instance of lgWin Window{9fdc251 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-06 19:11:01.461  1032  1095 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +702ms (total +788ms)
,09-06 19:11:01.463  1032  1095 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{264614e2 u0 com.test.thalitest/.MainActivity t6} time:189713
09-06 19:11:01.464  6732  6732 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@7776d67 time:189714
09-06 19:11:01.565  6732  6732 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-06 19:11:01.565  6732  6732 I chromium: 
,09-06 19:11:01.612  6732  6732 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-06 19:11:01.681  6732  6790 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-06 19:11:01.681  6732  6790 I chromium: 
,09-06 19:11:01.835  6732  6807 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435133056
,09-06 19:11:01.849  6732  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-06 19:11:01.849  6732  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-06 19:11:01.849  6732  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-06 19:11:01.849  6732  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-06 19:11:01.849  6732  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-06 19:11:01.850  6732  6807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f91057b added. We now have 1 listener(s)
09-06 19:11:01.856  1032  2004 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:01.859  6732  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-06 19:11:01.862  6732  6807 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:11:01.863  6732  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:11:01.864  6732  6807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:11:01.873  6732  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-06 19:11:01.873  6732  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-06 19:11:01.873  6732  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-06 19:11:01.873  6732  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-06 19:11:01.873  6732  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-06 19:11:01.873  6732  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-06 19:11:01.873  6732  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-06 19:11:01.873  6732  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-06 19:11:01.873  6732  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-06 19:11:01.873  6732  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-06 19:11:01.873  6732  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-06 19:11:01.873  6732  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-06 19:11:01.873  6732  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-06 19:11:01.873  6732  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-06 19:11:01.873  6732  6807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a25bd6 added. We now have 1 listener(s)
09-06 19:11:01.873  6732  6807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:11:01.878  1032  1544 D WifiService: New client listening to asynchronous messages
,09-06 19:11:01.883  6732  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:11:01.883  6732  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-06 19:11:01.885  6732  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-06 19:11:01.885  6732  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-06 19:11:01.885  6732  6807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-06 19:11:01.889  6732  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:11:01.890  1032  2323 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 19:11:01.891  6732  6807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-06 19:11:01.901  6732  6807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-06 19:11:01.901  6732  6807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:11:01.901  6732  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,09-06 19:11:01.901  6732  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:01.901  6732  6807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:11:01.901  6732  6807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:11:01.901  6732  6807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:11:01.901  6732  6807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:11:01.901  6732  6807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:11:01.901  6732  6807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-06 19:11:01.901  6732  6807 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:11:01.902  6732  6807 I io.jxcore.node.LifeCycleMonitor: start: OK
09-06 19:11:01.904  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:01.906  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:01.944  6732  6732 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-06 19:11:02.563   347   355 E GBMv2   : DFP En is all cleared set to be enabled
09-06 19:11:02.563   347   355 E GBMv2   : Set value is all cleared set the max
09-06 19:11:02.563   347   355 I GBMv2   : DFP Enabled. Ignore VFP set
,09-06 19:11:02.573  6732  6810 W jxcore-log: Initializing JXcore engine
09-06 19:11:02.573  6732  6810 W jxcore-log: JXcore engine is ready
09-06 19:11:02.608  6810  6810 W Thread-757: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8371]" dev="sockfs" ino=8371 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-06 19:11:02.608  6810  6810 W Thread-757: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-06 19:11:02.608  6810  6810 W Thread-757: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7873]" dev="sockfs" ino=7873 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-06 19:11:02.608  6810  6810 W Thread-757: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,09-06 19:11:02.608  6810  6810 W Thread-757: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32171]" dev="sockfs" ino=32171 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-06 19:11:02.626  6732  6810 W jxcore-log: Starting JXcore engine
09-06 19:11:02.702  6732  6810 W jxcore-log: Platform android
09-06 19:11:02.702  6732  6810 W jxcore-log: 
09-06 19:11:02.702  6732  6810 W jxcore-log: Process ARCH arm
09-06 19:11:02.702  6732  6810 W jxcore-log: 
,09-06 19:11:02.891  6732  6810 I jxcore-log: JXcore Cordova bridge is ready!
09-06 19:11:02.891  6732  6810 I jxcore-log: 
09-06 19:11:02.891  6732  6810 W jxcore-log: JXcore engine is started
,09-06 19:11:02.908  6732  6807 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-06 19:11:02.912  6732  6732 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-06 19:11:12.281  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-06 19:11:12.281  6732  6810 I jxcore-log: 
,09-06 19:11:12.284  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-06 19:11:12.284  6732  6810 I jxcore-log: 
09-06 19:11:12.290  6732  6810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:11:12.290  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:12.290  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:12.290  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:11:12.290  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:11:12.290  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:11:12.290  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:11:12.290  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:11:12.294  6732  6810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:11:12.296  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-06 19:11:12.296  6732  6810 I jxcore-log: 
,09-06 19:11:12.298  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-06 19:11:12.298  6732  6810 I jxcore-log: 
09-06 19:11:12.804  6732  6810 D executeNativeTests: Running unit tests
,09-06 19:11:12.885  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:11:12.885  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c7078b added. We now have 2 listener(s)
09-06 19:11:12.885  1032  1929 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:12.887  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:11:12.887  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:11:12.887  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:11:12.887  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:11:12.887  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 added. We now have 2 listener(s)
09-06 19:11:12.887  6732  6810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:11:12.890  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:11:12.891  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:11:12.894  6732  6810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:11:12.894  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:12.894  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:12.894  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:11:12.894  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:11:12.894  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:11:12.894  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:11:12.894  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:11:12.895  6732  6810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:11:12.896  6732  6810 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:11:12.898  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:11:12.900  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:11:12.901  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:12.904  6732  6810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:11:12.904  6732  6810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:11:12.906  6732  6810 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-06 19:11:12.907  6732  6810 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 19:11:12.907  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:11:12.907  6732  6810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:11:12.907  6732  6810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:11:12.908  6732  6810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:11:12.908  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:11:12.909  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:12.909  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:12.909  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.909  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:11:12.909  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:11:12.909  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c7078b removed from the list
09-06 19:11:12.910  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:12.910  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 removed from the list
09-06 19:11:12.910  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:11:12.910  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:12.911  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.911  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:11:12.914  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:12.914  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:12.914  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:12.914  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:12.915  6732  6810 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-06 19:11:12.915  6732  6810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:11:12.915  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:11:12.915  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:12.916  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:12.916  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.916  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:12.916  6732  6810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c7078b not in the list
09-06 19:11:12.916  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:12.916  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:12.916  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:11:12.916  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.916  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:12.916  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.916  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:12.916  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:12.916  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:11:12.916  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:12.917  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:11:12.922  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 19:11:12.922  6732  6810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:11:12.922  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:11:12.922  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:12.922  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:12.922  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.923  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:12.923  6732  6810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c7078b not in the list
09-06 19:11:12.923  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:12.923  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:12.923  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:11:12.923  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.923  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:12.923  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.923  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:12.923  6732  6810 I org.thaliproject.p2p.btconnec,torlib.DiscoveryManager: stopAdvertising
09-06 19:11:12.923  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:12.923  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:12.923  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:12.924  6732  6810 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 19:11:12.925  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:11:12.928  6732  6810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:11:12.928  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:12.928  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:12.928  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:11:12.928  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:11:12.928  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:11:12.928  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:11:12.928  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:11:12.931  6732  6810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:11:12.931  6732  6810 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:11:12.932  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:12.933  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:11:12.933  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:11:12.933  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-06 19:11:12.933  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:11:12.933  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
09-06 19:11:12.933  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:11:12.936  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:11:12.936  1032  2323 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
09-06 19:11:12.939  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:11:12.943  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 19:11:12.944  6732  6810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
,09-06 19:11:12.945  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:11:12.946  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:11:12.947  6732  6810 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 19:11:12.947  6732  6810 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 19:11:12.949  6732  6810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:11:12.949  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:11:12.949  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:12.950  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:11:12.950  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-06 19:11:12.950  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:11:12.950  6732  6810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c7078b not in the list
,09-06 19:11:12.950  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:12.950  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
,09-06 19:11:12.950  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:11:12.950  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:11:12.950  6732  6810 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 19:11:12.952  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:11:12.954  6732  6810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:11:12.954  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:12.954  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
,09-06 19:11:12.954  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:11:12.954  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:11:12.954  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:11:12.954  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:11:12.954  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:11:12.955  6732  6810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:11:12.955  6732  6810 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:11:12.957  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-06 19:11:12.958  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:12.958  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:11:12.958  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:11:12.958  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:11:12.958  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
09-06 19:11:12.958  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:11:12.960  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:11:12.961  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:11:12.961  6732  6810 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 19:11:12.962  6732  6810 I io.jxcore.node.ConnectionHelper: start: OK,
09-06 19:11:12.963  6732  6810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:11:12.963  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:11:12.963  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:12.963  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:11:12.963  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.963  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:11:12.963  6732  6810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c7078b not in the list
09-06 19:11:12.963  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:12.963  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:12.963  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:11:12.963  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:12.964  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.964  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:12.964  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:12.964  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:12.965  6732  6810 D BluetoothLeScanner: could not find callback wrapper
09-06 19:11:12.965  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:11:12.965  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:12.965  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:12.966  6732  6810 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 19:11:12.967  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:11:12.970  6732  6810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:11:12.970  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:12.970  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:12.970  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:11:12.970  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:11:12.970  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:11:12.970  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:11:12.970  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:11:12.971  6732  6810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:11:12.971  6732  6810 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:11:12.972  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:12.973  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:12.973  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:11:12.973  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:11:12.973  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:11:12.973  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:11:12.973  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:11:12.975  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:11:12.976  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:11:12.977  6732  6810 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 19:11:12.977  6732  6810 I io.jxcore.node.ConnectionHelper: start: OK
09-06 19:11:12.977  6732  6810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:11:12.977  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:11:12.977  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:12.978  6732  6810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:11:12.978  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:11:12.978  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:12.978  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:12.978  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.978  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:11:12.978  6732  6810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c7078b not in the list
09-06 19:11:12.978  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:12.978  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:12.978  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:11:12.978  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:12.978  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.978  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:12.979  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:12.979  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:12.980  6732  6810 D BluetoothLeScanner: could not find callback wrapper
09-06 19:11:12.980  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:11:12.980  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:12.980  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:12.980  6732  6810 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-06 19:11:12.981  6732  6810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:11:12.981  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:11:12.981  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:12.981  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:12.981  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.981  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:12.981  6732  6810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c7078b not in the list
09-06 19:11:12.981  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:12.981  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:12.981  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:11:12.981  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.981  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:12.981  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.981  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:12.982  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:12.982  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:12.982  6732  6810 D BluetoothLeScanner: could not find callback wrapper
09-06 19:11:12.982  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:11:12.982  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:12.982  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:12.983  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 19:11:12.983  6732  6810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:11:12.983  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:11:12.983  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:12.983  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:12.983  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.983  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:12.983  6732  6810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c7078b not in the list
09-06 19:11:12.983  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:12.983  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:12.983  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:11:12.983  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.983  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:12.983  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.983  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:12.984  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:12.984  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:12.985  6732  6810 D BluetoothLeScanner: could not find callback wrapper
09-06 19:11:12.985  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:11:12.985  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:12.985  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:12.985  6732  6810 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-06 19:11:12.985  6732  6810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:11:12.985  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:11:12.985  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:12.985  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:12.985  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.985  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:12.985  6732  6810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c7078b not in the list
09-06 19:11:12.985  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:12.985  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:12.985  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:11:12.985  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.985  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-06 19:11:12.985  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.985  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:12.986  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:12.986  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:12.987  6732  6810 D BluetoothLeScanner: could not find callback wrapper
09-06 19:11:12.987  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:11:12.987  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:12.987  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:12.987  6732  6810 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-06 19:11:12.987  6732  6810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:11:12.987  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:11:12.987  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:12.987  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:12.987  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.987  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:12.988  6732  6810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c7078b not in the list
09-06 19:11:12.988  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:12.988  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:12.988  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:11:12.988  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.988  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:12.988  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.988  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:12.988  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:12.989  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:12.989  6732  6810 D BluetoothLeScanner: could not find callback wrapper
09-06 19:11:12.989  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:11:12.989  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:12.989  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:12.989  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:11:12.990  6732  6810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:11:12.990  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:11:12.990  6732  6810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:11:12.990  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:11:12.991  6732  6810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:11:12.991  6732  6810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:11:12.991  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:11:12.991  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:12.991  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:12.991  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.991  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:12.991  6732  6810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c7078b not in the list
09-06 19:11:12.991  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:12.991  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:12.991  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:11:12.991  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.991  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:12.991  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:12.991  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:12.992  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:12.992  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:12.992  6732  6810 D BluetoothLeScanner: could not find callback wrapper
09-06 19:11:12.992  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:11:12.992  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:12.992  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:12.993  6732  6810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:11:12.993  6732  6810 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 19:11:12.993  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 19:11:12.995  6732  6810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:11:12.995  6732  6810 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:11:12.995  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 19:11:12.995  6732  6810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-06 19:11:12.996  6732  6810 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:11:12.996  6732  6810 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-06 19:11:12.996  6732  6810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:11:12.996  6732  6810 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:11:12.996  6732  6810 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-06 19:11:12.996  6732  6810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:11:12.996  6732  6810 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:11:12.996  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-06 19:11:12.998  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-06 19:11:12.999  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-06 19:11:12.999  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-06 19:11:13.000  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-06 19:11:13.000  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-06 19:11:13.000  6732  6810 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-06 19:11:13.000  6732  6810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:11:13.000  6732  6810 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-06 19:11:13.005  6732  6810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:11:13.005  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:11:13.005  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:13.006  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:13.006  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.006  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.007  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-06 19:11:13.008  6732  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 821)
09-06 19:11:13.011  6732  6810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c7078b not in the list
09-06 19:11:13.011  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:13.011  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:13.011  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:11:13.011  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.011  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.011  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.011  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.013  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:13.013  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:13.014  6732  6810 D BluetoothLeScanner: could not find callback wrapper
09-06 19:11:13.014  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:11:13.014  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:13.014  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:13.014  6732  6810 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-06 19:11:13.014  6732  6810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:11:13.014  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:11:13.015  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:13.015  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:13.015  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.015  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.015  6732  6810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c7078b not in the list
09-06 19:11:13.015  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:13.015  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:13.015  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:11:13.015  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.015  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.015  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.015  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.015  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:13.015  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:13.016  6732  6810 D BluetoothLeScanner: could not find callback wrapper
09-06 19:11:13.016  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:11:13.016  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:13.016  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:13.016  6732  6810 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-06 19:11:13.016  6732  6810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:11:13.017  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:11:13.017  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:13.017  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:13.022  6732  6821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 821
09-06 19:11:13.022  6732  6821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 821)
09-06 19:11:13.022  6732  6821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 821)
09-06 19:11:13.022  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.022  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.022  6732  6810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c7078b not in the list
09-06 19:11:13.022  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:13.022  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:13.023  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:11:13.023  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.023  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.023  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.023  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.026  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:13.026  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:13.026  6732  6810 D BluetoothLeScanner: could not find callback wrapper
09-06 19:11:13.026  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:11:13.026  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:13.026  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:13.027  6732  6810 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-06 19:11:13.027  6732  6810 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-06 19:11:13.027  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:11:13.027  6732  6810 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-06 19:11:13.027  6732  6810 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 19:11:13.027  6732  6810 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-06 19:11:13.027  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:11:13.027  6732  6810 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-06 19:11:13.027  6732  6810 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 19:11:13.027  6732  6810 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 19:11:13.027  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:11:13.027  6732  6810 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-06 19:11:13.027  6732  6810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:11:13.027  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:11:13.027  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:13.027  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:13.027  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.027  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.027  6732  6810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c7078b not in the list
09-06 19:11:13.027  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:13.028  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:13.028  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:11:13.028  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.028  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.028  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.028  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.031  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:13.031  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:13.032  6732  6810 D BluetoothLeScanner: could not find callback wrapper
09-06 19:11:13.032  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:11:13.032  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:13.032  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:13.033  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:13.033  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.033  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.033  6732  6810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c7078b not in the list
09-06 19:11:13.033  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:13.033  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:13.033  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:11:13.033  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.033  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.033  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:13.033  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:13.033  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:13.033  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.033  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.033  6732  6810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c7078b not in the list
09-06 19:11:13.033  6732  6810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:11:13.033  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should, start/stop everything
09-06 19:11:13.033  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:13.034  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:13.034  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.034  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.034  6732  6810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c7078b not in the list
09-06 19:11:13.034  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:13.034  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:13.034  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:11:13.034  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.034  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.034  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.034  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:11:13.035  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:13.035  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:13.037  6732  6810 D BluetoothLeScanner: could not find callback wrapper
09-06 19:11:13.037  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:11:13.037  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:13.037  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:13.040  6732  6810 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-06 19:11:13.040  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:11:13.043  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-06 19:11:13.044  6732  6810 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-06 19:11:13.044  6732  6810 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-06 19:11:13.044  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-06 19:11:13.044  6732  6732 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-06 19:11:13.044  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:11:13.045  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:13.045  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-06 19:11:13.045  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-06 19:11:13.046  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-06 19:11:13.046  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.046  6732  6810 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-06 19:11:13.046  6732  6810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c7078b not in the list
09-06 19:11:13.046  6732  6732 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-06 19:11:13.046  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:13.046  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:11:13.046  6732  6810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:11:13.046  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:11:13.047  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:11:13.047  6732  6824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-06 19:11:13.047  6732  6824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-06 19:11:13.049  6732  6810 D BluetoothLeScanner: could not find callback wrapper
09-06 19:11:13.049  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:11:13.049  6732  6810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:11:13.049  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.049  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.050  6732  6810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:11:13.051  6732  6732 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:11:13.051  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:13.051  6732  6732 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:11:13.051  6732  6810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:11:13.051  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:11:13.051  6732  6732 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-06 19:11:13.051  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:13.051  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:13.051  6732  6732 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:11:13.051  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.051  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.051  6732  6810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c7078b not in the list
09-06 19:11:13.051  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:13.051  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:13.051  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:11:13.051  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.051  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.051  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.051  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.052  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:13.052  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:13.052  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:13.052  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:13.052  6732  6810 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-06 19:11:13.053  6732  6810 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 19:11:13.053  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:11:13.054  6732  6810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:11:13.054  6732  6810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:11:13.054  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:11:13.054  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:13.054  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:13.054  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.054  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.054  6732  6810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c7078b not in the list
09-06 19:11:13.054  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:13.054  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:13.054  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:11:13.054  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.054  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.054  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.054  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.055  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:13.055  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:13.055  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:13.055  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:13.055  1032  2327 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:13.056  1032  2049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:13.056  1032  2003 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:13.057  6732  6810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:11:13.057  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:11:13.057  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:13.057  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:13.057  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.057  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.057  6732  6810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c7078b not in the list
09-06 19:11:13.057  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:13.057  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:13.057  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:11:13.057  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.057  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.057  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.057  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.058  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:13.058  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:13.058  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:13.058  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:13.058  6732  6810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:11:13.058  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:11:13.058  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:13.059  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:13.059  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.059  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.059  6732  6810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c7078b not in the list
09-06 19:11:13.059  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:13.059  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:13.059  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:11:13.059  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.059  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.059  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:13.059  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:13.059  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:13.059  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:13.059  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:13.059  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@368cc068 not in the list
09-06 19:11:13.060  6732  6810 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-06 19:11:13.060  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:11:13.060  6732  6810 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-06 19:11:13.060  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:11:13.060  6732  6810 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-06 19:11:13.060  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:11:13.062  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 19:11:13.062  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-06 19:11:13.062  6732  6810 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-06 19:11:13.062  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:11:13.063  6732  6810 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-06 19:11:13.063  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:11:13.063  6732  6810 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-06 19:11:13.063  6732  6810 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-06 19:11:13.063  6732  6810 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-06 19:11:13.063  6732  6810 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-06 19:11:13.064  6732  6810 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-06 19:11:13.064  6732  6810 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-06 19:11:13.064  6732  6810 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-06 19:11:13.064  6732  6810 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-06 19:11:13.065  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:11:13.066  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@31568ab9 added. We now have 2 listener(s)
09-06 19:11:13.066  6732  6810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:11:13.067  6732  6810 D Blueto,othAdapter: enable(): BT is already enabled..!
09-06 19:11:13.067  1032  1968 D WifiServiceImplEx: setWifiEnabled: true pid=6732, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 19:11:13.068  1032  1968 D WifiService: setWifiEnabled: true pid=6732, uid=10118
09-06 19:11:13.068  1032  1968 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-06 19:11:13.069  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:11:13.069  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24339efe added. We now have 3 listener(s)
09-06 19:11:13.070  6732  6810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:11:13.073  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:11:13.073  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ae0465f added. We now have 4 listener(s)
09-06 19:11:13.073  6732  6810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:11:13.074  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-06 19:11:13.074  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@136918ac added. We now have 5 listener(s)
09-06 19:11:13.074  6732  6810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:11:13.076  1032  1929 D WifiServiceImplEx: setWifiEnabled: false pid=6732, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 19:11:13.076  1032  1929 D WifiService: setWifiEnabled: false pid=6732, uid=10118
09-06 19:11:13.076  1032  1929 E WifiService: Invoking mWifiStateMachine.setWifiEnabled,
,09-06 19:11:13.100  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network],
09-06 19:11:13.100  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:11:13.100  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-06 19:11:13.101  1032  2004 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:13.101  1032  2004 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@19f545d8 mBinding = false
09-06 19:11:13.101  1032  1538 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-06 19:11:13.102  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-06 19:11:13.102  1032  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-06 19:11:13.103  1032  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-06 19:11:13.103  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-06 19:11:13.103  1032  1538 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-06 19:11:13.103  1032  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:11:13.104  1032  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 19:11:13.104  1032  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 19:11:13.104  1032  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-06 19:11:13.112  6732  6815 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
,09-06 19:11:13.112  6732  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 821)
09-06 19:11:13.115  1032  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 19:11:13.115  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 19:11:13.115  2648  2648 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 19:11:13.115  1032  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 19:11:13.115  1032  1538 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:11:13.116  1032  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:13.116  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:13.116  1032  1538 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:11:13.116   327   899 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:11:13.116  1032  2823 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:13.122  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 19:11:13.122  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:11:13.122  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-06 19:11:13.122  1032  1094 D BluetoothManagerService: Message: 2
09-06 19:11:13.123  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:11:13.125  1032  1094 D BluetoothManagerService: Sending off request.
09-06 19:11:13.126  6732  6810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:11:13.126  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:13.126  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:13.126  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:11:13.126  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:11:13.126  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:11:13.126  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:11:13.126  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:11:13.126  3836  3951 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-06 19:11:13.127  3836  3915 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-06 19:11:13.127  3836  3915 D BluetoothAdapterProperties: Setting state to 13
09-06 19:11:13.127  3836  3915 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 19:11:13.127  3836  3915 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 19:11:13.127  3836  3915 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-06 19:11:13.130  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:11:13.130  1032  1094 D BluetoothManagerService: Message: 60
09-06 19:11:13.130  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-06 19:11:13.130  6732  6810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:11:13.130  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-06 19:11:13.130  6732  6810 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:11:13.131  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:11:13.132  3836  3836 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:13.133  3836  3836 D BluetoothMapService: STATE_TURNING_OFF
09-06 19:11:13.133  3836  3836 V BtOppService: Receiver DISABLED_ACTION 
09-06 19:11:13.133  3836  3836 V BluetoothMapService: Handler(): got msg=4
09-06 19:11:13.133  3836  3836 D BluetoothMapService: MAP Service closeService in
09-06 19:11:13.133  3836  3836 D BluetoothMapMasInstance: MAP Service shutdown
09-06 19:11:13.133  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:11:13.136  3836  4248 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-06 19:11:13.136  3836  4248 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:11:13.136  3836  4248 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-06 19:11:13.136  3836  4248 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-06 19:11:13.136  3836  4248 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-06 19:11:13.136  3836  4248 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-06 19:11:13.136  3836  4248 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-06 19:11:13.136  3836  4248 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-06 19:11:13.137  3836  3836 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 19:11:13.137  3836  3836 V BluetoothMapService: MAP Service closeService out
09-06 19:11:13.137  3836  3836 I BtOppRfcommListener: stopping Accept Thread
09-06 19:11:13.137  3836  3836 V BtOppRfcommListener: close mBtServerSocket
09-06 19:11:13.137  3836  3836 V BtOppRfcommListener: waiting for thread to terminate
09-06 19:11:13.137  3836  4316 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:11:13.137  3836  4316 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-06 19:11:13.138  3836  3836 V BtOppRfcommListener: done waiting for thread to terminate
09-06 19:11:13.141  1032  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-06 19:11:13.141  1032  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
09-06 19:11:13.157  1032  1090 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6829 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-06 19:11:13.157  6732  6732 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:11:13.157  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:11:13.157  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:13.157  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:13.157  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:11:13.157  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:11:13.157  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:11:13.157  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:11:13.157  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:11:13.158  1032  1929 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
09-06 19:11:13.158  6732  6732 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:11:13.158  6732  6732 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:11:13.158  1032  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:13.158  1032  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:13.158  1032  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-06 19:11:13.158  1032  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:13.158  1032  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
09-06 19:11:13.161  1032  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:13.161  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:13.162  1032  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:13.162  1032  1538 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 19:11:13.162  1032  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:13.162  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:13.162  1032  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:13.163  3836  3836 V BtOppService: onDestroy
09-06 19:11:13.163  1032  1537 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:13.163  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:13.163  1032  1537 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@11f06c96
09-06 19:11:13.164  1032  1537 D LGWifiP2pService: P2pDisablingState
09-06 19:11:13.164  3836  3836 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-06 19:11:13.164  1032  1537 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:13.164  1032  1537 D LGWifiP2pService: p2p socket connection lost
09-06 19:11:13.164  1032  1537 D LGWifiP2pService: P2pDisabledState
09-06 19:11:13.164  6732  6732 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:11:13.164  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:11:13.164  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:13.164  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:13.164  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:11:13.164  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:11:13.164  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:11:13.164  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:11:13.164  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - acti,ve network type is Wi-Fi: true
09-06 19:11:13.165  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-06 19:11:13.165  6732  6732 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:11:13.165  6732  6732 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:11:13.166  1032  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-06 19:11:13.167  3836  3919 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:11:13.167  3836  3915 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-06 19:11:13.167  3836  4318 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:11:13.167  3836  3915 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-06 19:11:13.168  3836  4252 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:11:13.168  3836  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-06 19:11:13.168  3836  3999 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-06 19:11:13.168  1969  1969 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-06 19:11:13.169  6732  6732 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:11:13.169  3836  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:11:13.169  3836  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:11:13.169  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:11:13.169  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:13.169  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:13.169  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:11:13.169  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:11:13.169  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:11:13.169  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:11:13.169  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:11:13.169  3836  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:11:13.169  3836  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:11:13.169  3836  3999 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:11:13.169  3836  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:11:13.169  3836  3999 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:11:13.169  3836  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:11:13.169  3836  3999 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:11:13.169  3836  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-06 19:11:13.169  3836  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-06 19:11:13.169  3836  3999 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-06 19:11:13.169  6732  6732 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:11:13.169  6732  6732 D io.jxcore.node.JXcoreEx,tension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:11:13.170  3836  4322 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-06 19:11:13.170  1032  1537 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:13.170  1032  1537 D LGWifiP2pService: DefaultState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:13.170  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 19:11:13.170  2648  2648 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 19:11:13.170  1032  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 19:11:13.170  1032  1538 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:11:13.170  1032  1538 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:11:13.173  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:13.173  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:13.173  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:13.173  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:11:13.174  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:13.175  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:13.177  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-06 19:11:13.179  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:13.179  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:13.179  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:11:13.180  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 1
09-06 19:11:13.181  1032  1556 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:11:13.183  1032  1032 D RttService: SCAN_AVAILABLE : 1
09-06 19:11:13.183  1032  1557 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:13.184  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-06 19:11:13.185  1969  1969 D WfdsService: WifiP2pState is changed : false
09-06 19:11:13.185  1969  2312 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-06 19:11:13.185  1969  2312 D WfdsService: Set the WFDS Monitor: false
09-06 19:11:13.187   327   899 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:11:13.187  1032  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-06 19:11:13.187  1032  1545 D DSQN    : disableDataServiceNotify
09-06 19:11:13.187  1032  1545 D DSQN    : stop dsqn bin
09-06 19:11:13.188   327  6849 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-06 19:11:13.188  1032  1092 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-06 19:11:13.188  1969  2312 D WfdsMonitor: WFDS Monitor is stopped
09-06 19:11:13.188  1969  2312 D WfdsService: STATE : WfdsDisabledState - enter
09-06 19:11:13.188  1969  2739 D CtrlSupplicant: Received on exit socket, terminate
09-06 19:11:13.189  1969  2739 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-06 19:11:13.189  1032  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-06 19:11:13.189  1969  2739 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-06 19:11:13.189  1969  2739 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-06 19:11:13.189  1969  2314 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-06 19:11:13.189  1969  2312 W WfdsService: DefaultState - msg [9445378] is not handled
09-06 19:11:13.210  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-06 19:11:13.210  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:11:13.210  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:13.214  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:13.214  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:11:13.215  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:13.220  1032  1090 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6851 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-06 19:11:13.221  1032  1538 D WifiNative-p2p0: doBoolean: TERMINATE
,09-06 19:11:13.226  1032  1538 D WifiNative-p2p0: TERMINATE: returned true
09-06 19:11:13.226  1032  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:11:13.226  1032  1538 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:11:13.226  1032  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:11:13.228  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-06 19:11:13.230  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:13.230  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:13.230  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:11:13.232  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
,09-06 19:11:13.235  6732  6732 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:11:13.235  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:11:13.235  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:13.235  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:13.235  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:11:13.235  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:11:13.235  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:11:13.235  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:11:13.235  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:11:13.235  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-06 19:11:13.235  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:11:13.235  1032  1032 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-06 19:11:13.235  6732  6732 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:11:13.236  6732  6732 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:11:13.237  6732  6732 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:11:13.237  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:11:13.237  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:13.237  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:13.237  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:11:13.237  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:11:13.237  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:11:13.237  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:11:13.237  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:11:13.237  6732  6732 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:11:13.237  6732  6732 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:11:13.244  6829  6829 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:11:13.244  6829  6829 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-06 19:11:13.244  6829  6829 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:11:13.244  6829  6829 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-06 19:11:13.245  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable:, false, isConnectedToProvisioningNetwork: false]
09-06 19:11:13.245  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:11:13.245  6829  6829 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-06 19:11:13.245  6829  6829 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-06 19:11:13.246  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:11:13.265  1032  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-06 19:11:13.265  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:13.265  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:11:13.265  1032  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:11:13.266  1032  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-06 19:11:13.266  1032  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:13.266  1032  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:13.266  1032  2820 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-06 19:11:13.266  1032  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-06 19:11:13.266  1032  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-06 19:11:13.266  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:11:13.267  1603  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-06 19:11:13.268  1032  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:13.268  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:11:13.269  1032  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-06 19:11:13.269  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-06 19:11:13.269  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 19:11:13.270  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 19:11:13.270  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 19:11:13.270  1032  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:13.271  1032  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:13.271  1032  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:13.271  1032  1545 D NetworkManagementService: Removing idletimer
09-06 19:11:13.271  1032  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:13.271  103,2  1545 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-06 19:11:13.272  1032  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-06 19:11:13.272  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-06 19:11:13.272  1032  1538 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:13.272  1032  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:11:13.272  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 19:11:13.272  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 19:11:13.272  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 19:11:13.273  1878  1878 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:13.273  1878  1878 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,09-06 19:11:13.278  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:11:13.300  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 19:11:13.301  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:13.302  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:11:13.314  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 19:11:13.315  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:13.315  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:13.320  1032  2823 D DhcpStateMachine: StoppedState
,09-06 19:11:13.320  1032  2823 D DhcpStateMachine: StoppedState{ when=-149ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:13.321  1032  1538 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-06 19:11:13.321  1032  1538 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-06 19:11:13.330  2648  2648 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-06 19:11:13.330  2648  2648 I wpa_supplicant: monitor socket send errors count : 1
09-06 19:11:13.330  2648  2648 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1969-2\x00 that cannot receive messages
09-06 19:11:13.331  1032  2710 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-06 19:11:13.331  1032  2710 D WifiMonitor: Dropping event because (p2p0) is stopped
,09-06 19:11:13.342  6829  6829 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-06 19:11:13.344  3836  3836 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 19:11:13.344  3836  3836 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:13.344  3836  3836 V BluetoothPbapReceiver: ***********state = 13
,09-06 19:11:13.345  3836  3836 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-06 19:11:13.346  3836  3836 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:13.346  3836  3836 V BluetoothPbapService: state: 13
09-06 19:11:13.346  3836  3836 V BluetoothPbapService: Pbap Service closeService in
09-06 19:11:13.347  2201  2201 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:11:13.347  3836  3836 V BluetoothPbapService: successfully stopped pbap service
09-06 19:11:13.348  3836  3836 V BluetoothPbapService: Pbap Service closeService out
09-06 19:11:13.348  3836  3836 V BluetoothPbapService: Pbap Service onDestroy
09-06 19:11:13.348  3836  3836 V BluetoothPbapService: Pbap Service closeService in
09-06 19:11:13.348  3836  3836 V BluetoothPbapService: Pbap Service closeService out
09-06 19:11:13.348  3836  3836 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-06 19:11:13.349  1032  1094 D BluetoothManagerService: Message: 20
09-06 19:11:13.349  1032  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3d4c833:true
09-06 19:11:13.358  1032  1094 D BluetoothManagerService: Message: 30
,09-06 19:11:13.359  6851  6851 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-06 19:11:13.360  6851  6851 W LG Account v2.2: No ProfileInfo entries
,09-06 19:11:13.360  6851  6851 I LG Account v2.2: isEnabled: false
09-06 19:11:13.360  6851  6851 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-06 19:11:13.361  6851  6851 I Feature : [Lifetracker]Country: EU
09-06 19:11:13.361  6851  6851 I Feature : [Lifetracker]Operator: OPEN
09-06 19:11:13.361  6851  6851 I Feature : [Lifetracker]Ranking support: false
09-06 19:11:13.361  6851  6851 I Feature : [Lifetracker]Comfort support: false
09-06 19:11:13.361  6851  6851 I Feature : [Lifetracker]Accessory: true
09-06 19:11:13.361  6851  6851 I Feature : [Lifetracker]Health device: true
09-06 19:11:13.361  6851  6851 I Feature : [Lifetracker]Extra Pedometer: false
09-06 19:11:13.361  1032  1094 D BluetoothManagerService: Message: 30
09-06 19:11:13.361  6851  6851 I Feature : [Lifetracker]Blood glucose device: false
09-06 19:11:13.361  6851  6851 I Feature : [Lifetracker]Device Number: 3
09-06 19:11:13.363  6829  6829 D LocalBluetoothProfileManager: Adding local MAP profile
09-06 19:11:13.364  6829  6829 D BluetoothMap: Create BluetoothMap proxy object
09-06 19:11:13.364  1032  1645 I ActivityManager: Killing 5927:com.android.providers.calendar/u0a14 (adj 15): empty #17
09-06 19:11:13.364  1032  1094 D BluetoothManagerService: Message: 30
09-06 19:11:13.368  2648  2648 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:11:13.369  2648  2648 W wpa_supplicant: USIM:  scard_deinit function
09-06 19:11:13.369  1032  2710 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-06 19:11:13.369  1032  1094 D Tethering: InitialState.processMessage what=4
09-06 19:11:13.370  1032  2710 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:11:13.370  1032  2710 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:11:13.371  1032  2710 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-06 19:11:13.371  1032  2710 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:11:13.371  1032  2710 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-06 19:11:13.371  1032  1538 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=201605
09-06 19:11:13.372  1032  1538 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=201605
09-06 19:11:13.372  1032  1538 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=201605  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-06 19:11:13.372  1032  1538 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=201606  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-06 19:11:13.395  1032  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-06 19:11:13.395  1032  2028 W libprocessgroup: failed to open /acct/uid_10014/pid_5927/cgroup.procs: No such file or directory
,09-06 19:11:13.399  1032  1538 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:11:13.399  1032  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:11:13.401  1032  1094 D BluetoothManagerService: Message: 30
09-06 19:11:13.403  6829  6829 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-06 19:11:13.405  6829  6829 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-06 19:11:13.409  6402  6402 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:11:13.431  2648  2648 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-06 19:11:13.432  1032  2710 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-06 19:11:13.432  1032  2710 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-06 19:11:13.432  1032  2710 D WifiMonitor: Disconnecting from the supplicant, no more events
,09-06 19:11:13.434  1032  1538 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
09-06 19:11:13.473  1032  2004 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6873 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-06 19:11:13.478  6829  6829 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,09-06 19:11:13.482  6829  6829 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-06 19:11:13.496  6829  6829 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:11:13.498  6829  6829 D BluetoothInputDevice: Proxy object connected
09-06 19:11:13.501  6829  6829 D HidProfile: Bluetooth service connected
09-06 19:11:13.502  6829  6829 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:11:13.503  6829  6829 D PanProfile: Bluetooth service connected
09-06 19:11:13.520  6829  6829 D BluetoothMap: Proxy object connected
,09-06 19:11:13.520  6829  6829 D MapProfile: Bluetooth service connected
09-06 19:11:13.521  6829  6829 D BluetoothMap: getConnectedDevices()
09-06 19:11:13.522  6829  6829 D BluetoothMap: Bluetooth is Not enabled
09-06 19:11:13.522  6829  6829 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-06 19:11:13.524  6829  6829 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-06 19:11:13.533  6829  6829 D BluetoothPermissionRequest: onReceive
,09-06 19:11:13.537  1969  1969 D WfdsService: Supplicant Connection state is changed : false
,09-06 19:11:13.537  1969  2312 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-06 19:11:13.537  1969  2312 D WfdsService: Set the WFDS Monitor: false
09-06 19:11:13.537  1969  2312 D WfdsMonitor: WFDS Monitor is stopped
09-06 19:11:13.537  6829  6829 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-06 19:11:13.537  1032  1538 D WifiOffDelayIfNotUsed: stopMonitoring
09-06 19:11:13.537  1032  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:11:13.537  1032  1538 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:11:13.537  1032  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:11:13.540  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:13.541  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-06 19:11:13.542  2469  2469 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:13.544  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-06 19:11:13.544  1032  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-06 19:11:13.544  1032  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
,09-06 19:11:13.553  6732  6732 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:11:13.553  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:11:13.553  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:13.553  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:13.553  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:11:13.553  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:11:13.553  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:11:13.553  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:11:13.553  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:11:13.556  6829  6829 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-06 19:11:13.556  6732  6732 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:11:13.556  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:11:13.556  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:13.556  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:13.556  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:11:13.556  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:11:13.556  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:11:13.556  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:11:13.556  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:11:13.556  6732  6732 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-06 19:11:13.558  1032  2327 I ActivityManager: Killing 6281:com.android.defcontainer/u0a4 (adj 15): empty #17
09-06 19:11:13.599  1032  1049 W libprocessgroup: failed to open /acct/uid_10004/pid_6281/cgroup.procs: No such file or directory
,09-06 19:11:13.600  3836  3836 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,09-06 19:11:13.600  3836  3836 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-06 19:11:13.601  6873  6873 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 19:11:13.602  3836  3836 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-06 19:11:13.606  6873  6873 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:11:13.607  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:11:13.611  3836  3836 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:13.611  3836  3836 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,09-06 19:11:13.613  3836  3836 V BluetoothFtpService: Ftp Service onStartCommand
09-06 19:11:13.613  3836  3836 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:13.614  3836  3836 V BluetoothFtpService: Ftp Service closeService
09-06 19:11:13.614  3836  3836 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-06 19:11:13.615  3836  3836 V BluetoothFtpService: successfully stopped ftp service
09-06 19:11:13.616  3836  3836 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:11:13.616  3836  3836 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:11:13.616  3836  3836 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:11:13.616  3836  3836 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:13.616  3836  3836 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-06 19:11:13.616  3836  3836 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-06 19:11:13.619  3836  3836 V BluetoothFtpService: Ftp Service onDestroy
09-06 19:11:13.619  3836  3836 V BluetoothFtpService: Ftp Service closeService
09-06 19:11:13.623  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:11:13.656  6829  6829 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:11:13.656  6829  6829 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:11:13.668  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 19:11:13.679  1032  2049 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6900 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-06 19:11:13.679  3836  3836 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:13.679  3836  3836 V BluetoothSapService: state: 13
09-06 19:11:13.680  3836  3836 V BluetoothSapService: Stopping SAP server process
09-06 19:11:13.680  3836  3836 V BluetoothSapService: Sap Service closeSapService in
09-06 19:11:13.681  3836  3836 V BluetoothSapService: Close listen Socket : 
09-06 19:11:13.681  3836  3836 V BluetoothSapService: Close rfcomm Socket : 
09-06 19:11:13.681  3836  3836 V BluetoothSapService: Close sapd  Socket : 
09-06 19:11:13.683  3836  3836 V BluetoothSapService: Sap Service closeSapService out
09-06 19:11:13.683  3836  3836 V BluetoothSapService: Sap Service onDestroy
09-06 19:11:13.683  3836  3836 V BluetoothSapService: Sap Service closeSapService in
09-06 19:11:13.683  3836  3836 V BluetoothSapService: Close listen Socket : 
09-06 19:11:13.683  3836  3836 V BluetoothSapService: Close rfcomm Socket : 
09-06 19:11:13.683  3836  3836 V BluetoothSapService: Close sapd  Socket : 
09-06 19:11:13.690  3836  3836 V BluetoothSapService: Sap Service closeSapService out
,09-06 19:11:13.744  1032  2049 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6917 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-06 19:11:13.745  1032  2049 I ActivityManager: Killing 6449:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,09-06 19:11:13.837  1032  1048 W libprocessgroup: failed to open /acct/uid_10008/pid_6449/cgroup.procs: No such file or directory
,09-06 19:11:13.868  6900  6900 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-06 19:11:13.879  6917  6917 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:11:13.885  1032  1949 I ActivityManager: Killing 6037:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-06 19:11:13.994  1032  1645 W libprocessgroup: failed to open /acct/uid_10011/pid_6037/cgroup.procs: No such file or directory
,09-06 19:11:14.000  6917  6917 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-06 19:11:14.038  6917  6917 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-06 19:11:14.039  6917  6917 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-06 19:11:14.039  6917  6917 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-06 19:11:14.040  6917  6917 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-06 19:11:14.040  6917  6917 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-06 19:11:14.042  6917  6917 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-06 19:11:14.049  6917  6917 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-06 19:11:14.057  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 19:11:14.062  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:11:14.085  6917  6917 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-06 19:11:14.092  6917  6917 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-06 19:11:14.094  6402  6402 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:11:14.097  6917  6917 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,09-06 19:11:14.102  6873  6873 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 19:11:14.102  6873  6873 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:11:14.102  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:11:14.106  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:11:14.114  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:14.122  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:11:14.122  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:11:14.125  6917  6917 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:11:14.128  6402  6402 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:11:14.133  6873  6873 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 19:11:14.133  6873  6873 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:11:14.133  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:11:14.136  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:11:14.143  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:14.150  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:11:14.151  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:11:14.155  6917  6917 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:11:14.173  3836  3999 W bt-btif : ag scb idx 1 not allocated
09-06 19:11:14.174  3836  3999 E bt-btif : BTA AG is already disabled, ignoring ...
09-06 19:11:14.174  3836  3919 D bt_hci_bdroid: cleanup
09-06 19:11:14.174  3836  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:11:14.174  3836  3999 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:11:14.174  3836  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:11:14.174  3836  3999 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:11:14.174  3836  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:11:14.174  3836  3999 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:11:14.174  3836  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:11:14.174  3836  3999 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:11:14.174  3836  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:11:14.174  3836  3999 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:11:14.174  3836  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:11:14.174  3836  3999 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:11:14.174  3836  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:11:14.174  3836  3999 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:11:14.174  3836  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:11:14.174  3836  3999 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:11:14.174  3836  3999 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:11:14.174  3836  3999 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:11:14.174  3836  3999 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-06 19:11:14.174  3836  4008 I bt_lpm  : LPM is already off!!!
09-06 19:11:14.174  3836  4233 I bt_userial_mct: exiting userial_read_thread
09-06 19:11:14.175  3836  4233 D bt_userial_mct: Leaving userial_evt_read_thread()
09-06 19:11:14.175  3836  3919 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-06 19:11:14.175  3836  4008 I bt_vendor: hw_epilog_process
09-06 19:11:14.176  3836  3919 D bt_hci_bdroid: cleanup Finalizing cleanup
09-06 19:11:14.176  3836  3919 D bt_userial_mct: userial_close
09-06 19:11:14.176  3836  3919 E bt_userial_mct: pthread_join() FAILED result:3
09-06 19:11:14.176  3836  3919 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-06 19:11:14.224  1032  1575 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6941 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-06 19:11:14.250  3836  3919 D bt_hci_bdroid: set_power 0
09-06 19:11:14.250  3836  3919 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 19:11:14.250  3836  3919 I bt_vendor: bluetooth satus is on
09-06 19:11:14.250  3836  3919 I bt_vendor: bt-vendor : resetting BT status
09-06 19:11:14.250  3836  3919 I bt_vendor: Starting hciattach daemon
09-06 19:11:14.250  3836  3919 I bt_vendor: try to set false
09-06 19:11:14.251  3836  3919 I bt_vendor: Starting hciattach daemon
09-06 19:11:14.251  3836  3919 I bt_vendor: try to set false
09-06 19:11:14.252  3836  3919 I bt_vendor: cleanup
09-06 19:11:14.253  3836  3999 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-06 19:11:14.253  3836  3919 I GKI_LINUX: GKI_exit_task 0 done
09-06 19:11:14.253  3836  3919 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-06 19:11:14.255  3836  3915 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-06 19:11:14.259  3836  3836 D HeadsetService: Received stop request...Stopping profile...
09-06 19:11:14.261  3836  3836 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-06 19:11:14.261  3836  3836 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:11:14.261  3836  3836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cdf911
09-06 19:11:14.262  3836  3952 D HeadsetStateMachine: Exit Disconnected: -1
09-06 19:11:14.263  1878  1878 D BluetoothHeadset: Proxy object disconnected
09-06 19:11:14.263  1878  1878 D BluetoothHeadset: Proxy object disconnected
09-06 19:11:14.264  1032  1032 D BluetoothHeadset: Proxy object disconnected
09-06 19:11:14.264  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-06 19:11:14.265  3836  3836 D A2dpService: Received stop request...Stopping profile...
09-06 19:11:14.265  3836  3979 D A2dpStateMachine: Exit Disconnected: -1
09-06 19:11:14.266  1878  1878 D BluetoothHeadset: Proxy object disconnected
,09-06 19:11:14.266  3836  3836 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-06 19:11:14.267  3836  3915 D BluetoothAdapterState: Stopping profile services that were post enabled
09-06 19:11:14.268  3836  3836 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-06 19:11:14.268  3836  3836 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:11:14.268  3836  3836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cdf911
09-06 19:11:14.269  1032  1032 D BluetoothA2dp: Proxy object disconnected
09-06 19:11:14.269  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-06 19:11:14.270  3836  3836 D HidService: Received stop request...Stopping profile...
09-06 19:11:14.270  3836  3836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cdf911
09-06 19:11:14.272  6829  6829 D BluetoothInputDevice: Proxy object disconnected
,09-06 19:11:14.272  6829  6829 D HidProfile: Bluetooth service disconnected
09-06 19:11:14.275  3836  3836 D HealthService: Received stop request...Stopping profile...
09-06 19:11:14.275  3836  3836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cdf911
09-06 19:11:14.276  3836  3836 D HeadsetStateMachine: Unbinding service...
09-06 19:11:14.277  3836  3836 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 19:11:14.277  3836  3836 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 19:11:14.277  3836  3836 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 19:11:14.277  3836  3836 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 19:11:14.277  3836  3836 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 19:11:14.277  3836  3836 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:11:14.277  3836  3836 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-06 19:11:14.278  3836  3836 D PanService: Received stop request...Stopping profile...
09-06 19:11:14.278  3836  3836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cdf911
09-06 19:11:14.280  3836  3836 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 19:11:14.280  3836  3836 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 19:11:14.280  3836  3836 D BtGatt.GattService: stop()
09-06 19:11:14.280  3836  3836 D BtGatt.AdvertiseManager: advertise clients cleared
09-06 19:11:14.281  6829  6829 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 19:11:14.281  6829  6829 D PanProfile: Bluetooth service disconnected
09-06 19:11:14.281  3836  3836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cdf911
09-06 19:11:14.282  3836  3836 D BluetoothMapService: Received stop request...Stopping profile...
09-06 19:11:14.282  3836  3836 D BluetoothMapService: stop()
09-06 19:11:14.283  3836  3836 D BluetoothMapEmailAppObserver: deinitObservers()
09-06 19:11:14.283  3836  3836 D BluetoothMapEmailAppObserver: removeReceiver()
09-06 19:11:14.284  3836  3836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cdf911
,09-06 19:11:14.287  3836  3836 I BluetoothA2dpServiceJni: cleanupNative
09-06 19:11:14.288  3836  3980 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-06 19:11:14.288  3836  3836 I GKI_LINUX: GKI_exit_task 2 done
09-06 19:11:14.288  3836  3836 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-06 19:11:14.289  3836  3836 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 19:11:14.289  3836  3836 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 19:11:14.289  3836  3836 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 19:11:14.289  3836  3836 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:11:14.289  3836  3836 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:11:14.289  3836  3836 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 19:11:14.289  3836  3836 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-06 19:11:14.290  6829  6829 D BluetoothMap: Proxy object disconnected
09-06 19:11:14.290  6829  6829 D MapProfile: Bluetooth service disconnected
09-06 19:11:14.290  3836  3836 V BluetoothMapService: Handler(): got msg=4
09-06 19:11:14.290  3836  3836 D BluetoothMapService: MAP Service closeService in
09-06 19:11:14.290  3836  3836 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 19:11:14.290  3836  3836 V BluetoothMapService: MAP Service closeService out
09-06 19:11:14.291  3836  3915 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-06 19:11:14.291  3836  3915 D BluetoothAdapterProperties: Setting state to 10
09-06 19:11:14.291  3836  3915 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-06 19:11:14.291  1032  1094 D BluetoothManagerService: Message: 60
09-06 19:11:14.291  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-06 19:11:14.291  3836  3915 I BluetoothAdapterState: Entering OffState
09-06 19:11:14.291  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-06 19:11:14.292  6829  6850 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-06 19:11:14.292  3836  3836 D BluetoothMapService: cleanup()
09-06 19:11:14.292  3836  3836 D BluetoothMapService: MAP Service closeService in
09-06 19:11:14.292  3836  3836 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 19:11:14.292  3836  3836 V BluetoothMapService: MAP Service closeService out
09-06 19:11:14.292  6829  6848 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 19:11:14.293  1032  1094 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:11:14.293  1878  2583 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:11:14.294  1878  1894 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:11:14.294  6829  6850 D BluetoothMap: onBluetoothStateChange: up=false
09-06 19:11:14.295  1032  1094 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:11:14.295  1878  1893 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:11:14.295  6829  6848 D BluetoothPan: onBluetoothStateChange on: false
,09-06 19:11:14.296  1032  1094 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-06 19:11:14.297  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-06 19:11:14.299  1032  1094 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-06 19:11:14.300  1032  1094 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-06 19:11:14.300  1032  1094 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@19f545d8 mBinding = false
09-06 19:11:14.301  1032  1094 D BluetoothManagerService: Sending unbind request.
09-06 19:11:14.307  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,09-06 19:11:14.309  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:14.310  1969  2192 D LGBluetoothAPIService: Message: 2
09-06 19:11:14.310  1969  2192 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@13c13388 mBinding = false
09-06 19:11:14.310  1969  2192 D LGBluetoothAPIService: Sending unbind request.
09-06 19:11:14.311  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:11:14.317  3836  3919 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-06 19:11:14.318  3836  3836 I GKI_LINUX: GKI_exit_task 1 done
09-06 19:11:14.318  3836  3836 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-06 19:11:14.319  3836  3836 I BluetoothServiceJni: cleanupNative: return from cleanup
09-06 19:11:14.319  3836  3836 I art     : --- WEIRD: removing null entry 246
09-06 19:11:14.319  3836  3836 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-06 19:11:14.319  3836  3836 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-06 19:11:14.319  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:14.320  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:14.321  6829  6829 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-06 19:11:14.321  3836  3836 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-06 19:11:14.322  6829  6829 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-06 19:11:14.322  6829  6829 D LGBluetoothEventManager: [BTUI] clear device connection state
09-06 19:11:14.325  6829  6829 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-06 19:11:14.330  3836  3836 I art     : System.exit called, status: 0
09-06 19:11:14.330  3836  3836 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-06 19:11:14.333  6829  6829 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:11:14.334  1603  1603 D BluetoothAdapter: 51489737: getState() :  mService = null. Returning STATE_OFF
09-06 19:11:14.334  1603  1603 D BluetoothAdapter: 51489737: getState() :  mService = null. Returning STATE_OFF
09-06 19:11:14.354   331  3957 V AudioFlinger: 3836 died, releasing its sessions
09-06 19:11:14.354   331  3957 V AudioFlinger:  pid 1878 @ 0
,09-06 19:11:14.354   331  3957 V AudioFlinger:  pid 3357 @ 1
09-06 19:11:14.354   331  3957 V AudioFlinger:  pid 3357 @ 2
09-06 19:11:14.355  6829  6829 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-06 19:11:14.380  1032  1929 I ActivityManager: Process com.android.bluetooth (pid 3836) has died
09-06 19:11:14.380  1032  1929 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,09-06 19:11:14.384  2201  2201 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:11:14.394  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 19:11:14.405  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:11:14.411  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:14.413  6829  6829 D BluetoothPermissionRequest: onReceive
09-06 19:11:14.413  6941  6968 W FormManager: Network not available. Please check & try again.
,09-06 19:11:14.415  6829  6829 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-06 19:11:14.415  6829  6829 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-06 19:11:14.417  6829  6829 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:11:14.458  1032  1048 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6970 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-06 19:11:14.479   359   359 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 447us total 20.937ms
,09-06 19:11:14.487  6941  6969 V FormManager: Network unavailable.
09-06 19:11:14.490  6941  6969 V FormManager: Network unavailable.
09-06 19:11:14.497  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 19:11:14.497  6829  6829 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,09-06 19:11:14.497  6829  6829 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 19:11:14.497  6829  6829 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-06 19:11:14.498   359   359 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 372us total 18.258ms
09-06 19:11:14.498  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-06 19:11:14.514   359   359 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 283us total 16.159ms
,09-06 19:11:14.517  6829  6829 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 19:11:14.518  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-06 19:11:14.518  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 19:11:14.518  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 19:11:14.518  6829  6829 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 19:11:14.518  6829  6829 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-06 19:11:14.520  1032  2028 I ActivityManager: Killing 6060:com.android.contacts/u0a19 (adj 15): empty #17
09-06 19:11:14.522  6970  6970 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-06 19:11:14.522  6970  6970 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:11:14.523  6970  6970 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-06 19:11:14.523  6970  6970 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-06 19:11:14.535  6970  6970 D BluetoothAdapterApp: Loading JNI Library
,09-06 19:11:14.557  6970  6970 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@382b459e Instance Count = 1
,09-06 19:11:14.625  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:11:14.625  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-06 19:11:14.625  1032  1048 W libprocessgroup: failed to open /acct/uid_10019/pid_6060/cgroup.procs: No such file or directory
09-06 19:11:14.629  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:11:14.636  6970  6970 D BluetoothAdapterApp: onCreate
09-06 19:11:14.641  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-06 19:11:14.655  4326  6989 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-06 19:11:14.662  6873  6873 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-06 19:11:14.662  6873  6873 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:11:14.662  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:11:14.668  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:11:14.672  4326  6990 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:11:14.677  4326  6990 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 19:11:14.678  6941  6992 W FormManager: Network not available. Please check & try again.
09-06 19:11:14.684  6970  6970 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-06 19:11:14.684  6941  6993 V FormManager: Network unavailable.
09-06 19:11:14.684  6970  6970 D ProfileConfigQcom: Adding HeadsetService
09-06 19:11:14.684  6970  6970 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-06 19:11:14.684  6970  6970 D ProfileConfigQcom: Adding A2dpService
09-06 19:11:14.684  6970  6970 D ProfileConfigQcom: [BTUI] HidService is supported
,09-06 19:11:14.685  6970  6970 D ProfileConfigQcom: Adding HidService
09-06 19:11:14.685  6970  6970 D ProfileConfigQcom: [BTUI] HealthService is supported
09-06 19:11:14.685  6970  6970 D ProfileConfigQcom: Adding HealthService
09-06 19:11:14.685  6970  6970 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-06 19:11:14.686  6941  6993 V FormManager: Network unavailable.
09-06 19:11:14.686  6970  6970 D ProfileConfigQcom: [BTUI] PanService is supported
09-06 19:11:14.686  6970  6970 D ProfileConfigQcom: Adding PanService
09-06 19:11:14.687  6970  6970 D ProfileConfigQcom: [BTUI] GattService is supported
09-06 19:11:14.687  6970  6970 D ProfileConfigQcom: Adding GattService
09-06 19:11:14.687  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:14.687  6970  6970 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-06 19:11:14.687  6970  6970 D ProfileConfigQcom: Adding BluetoothMapService
09-06 19:11:14.688  6970  6970 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-06 19:11:14.691  6970  6970 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-06 19:11:14.696  6829  6829 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,09-06 19:11:14.702  6970  6970 V LGMDMManagerInternal: Create singleton instance
09-06 19:11:14.706  6917  6917 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-06 19:11:14.707  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-06 19:11:14.708  6917  6917 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-06 19:11:14.745  6917  6917 D LgDataFeature: LgDataFeature() Constructor: none
,09-06 19:11:14.745  6917  6917 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 19:11:14.752  6917  6917 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-06 19:11:14.756  6917  6917 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-06 19:11:14.756  6917  6917 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-06 19:11:14.756  6917  6917 V SoundPool: doLoad: loading sample sampleID=1
09-06 19:11:14.756  6917  6997 V SoundPool: Start decode
09-06 19:11:14.756  6917  6997 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-06 19:11:14.757   331  1382 V MediaPlayerService: decode(23, 10857164, 17813)
09-06 19:11:14.757   331  1382 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-06 19:11:14.757   331  1382 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-06 19:11:14.757   331  1382 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-06 19:11:14.757   331  1382 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
,09-06 19:11:14.757   331  1382 W MediaPlayerFactory: [getPlayerType:fd] nType = 3,
09-06 19:11:14.757   331  1382 V MediaPlayerService: player type = 3,
09-06 19:11:14.757   331  1382 V AwesomePlayer: AwesomePlayer create(),
09-06 19:11:14.757  6917  6917 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind,
09-06 19:11:14.758   331  1382 V AwesomePlayer: reset_l() ,
09-06 19:11:14.758   331  1382 V AwesomePlayer: cancelPlayerEvents
,09-06 19:11:14.758   331  1382 V AwesomePlayer: setAudioSink() ,
09-06 19:11:14.758   331  1382 V AwesomePlayer: reset_l() ,
09-06 19:11:14.758   331  1382 V AudioCache: notify(0xb5474680, 8, 0, 0),
09-06 19:11:14.758   331  1382 V AudioCache: ignored,
,09-06 19:11:14.758   331  1382 V AwesomePlayer: cancelPlayerEvents
09-06 19:11:14.758   331  1382 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk,
,09-06 19:11:14.758   331  1382 V AwesomePlayer: setDataSource_l dataSource
09-06 19:11:14.758   331  1382 V LGParserOSAL: SniffLGParser start
,09-06 19:11:14.758   331  1382 V LGParserOSAL: MainType:5, SubType=0
09-06 19:11:14.758   331  1382 V LGParserOSAL: #### check Mime : application/ogg
09-06 19:11:14.758   331  1382 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
,09-06 19:11:14.758   331  1382 E MediaExtractor: Use LGExtractor :application/ogg 
09-06 19:11:14.765  6623  6623 D UEI.SmartControl: QS Service created
09-06 19:11:14.778  6970  6970 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:11:14.781  6917  6917 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-06 19:11:14.782  6970  6970 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:11:14.783  6917  6917 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 19:11:14.783  6970  6970 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:11:14.783  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-06 19:11:14.783  6970  6970 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:11:14.784  6970  6970 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:14.784  6970  6970 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-06 19:11:14.792  6900  6900 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-06 19:11:14.796   331  1382 V LGParserOSAL: supported mime: application/ogg
09-06 19:11:14.796   331  1382 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-06 19:11:14.796   331  1382 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-06 19:11:14.796   331  1382 V AwesomePlayer: mBitrate = -1 bits/sec
09-06 19:11:14.796   331  1382 V AwesomePlayer: AudioTrack Setting
09-06 19:11:14.796   331  1382 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-06 19:11:14.796   331  1382 V AwesomePlayer: setAudioSource() 
09-06 19:11:14.796   331  1382 V MediaPlayerService: prepare
09-06 19:11:14.796   331  1382 V AwesomePlayer: prepareAsync_l() 
09-06 19:11:14.796   331  1382 V MediaPlayerService: wait for prepare
09-06 19:11:14.797   331  6999 V AwesomePlayer: onPrepareAsyncEvent() 
09-06 19:11:14.797   331  6999 V AwesomePlayer: initAudioDecoder() 
09-06 19:11:14.797   331  6999 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-06 19:11:14.797   331  6999 V AudioSystem: isOffloadSupported()
09-06 19:11:14.797   331  6999 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-06 19:11:14.797   331  6999 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-06 19:11:14.797   331  6999 I AudioFlinger: isAudioPlaybackHookOn() false
09-06 19:11:14.797   331  6999 V AwesomePlayer: getUseOffload() = 0 
09-06 19:11:14.797   331  6999 V OMXCodec: OMXCodec::Create
09-06 19:11:14.797   331  6999 V OMXCodec: findMatchingCodecs()
09-06 19:11:14.797   331  6999 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
,09-06 19:11:14.797   331  6999 V OMXCodec: matchingCodecs.size()=1
09-06 19:11:14.797   331  6999 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-06 19:11:14.798  6917  6917 V LGMDMManager: Create singleton instance
09-06 19:11:14.800   331  6999 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-06 19:11:14.800   331  6999 V LGCodecAdapter: LG Codec Adapter start
09-06 19:11:14.800   331  6999 V OMXCodec: OMXCodec Createtor
09-06 19:11:14.800   331  6999 V OMXCodec: setComponentRole
09-06 19:11:14.800  6623  6623 I UEI.SmartControl: Service initServices...
09-06 19:11:14.800   331  6999 V OMXCodec: configureCodec protected=0
09-06 19:11:14.800   331  6999 V LGCodecAdapter: called getLGCodecSpecificData
09-06 19:11:14.800   331  6999 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-06 19:11:14.800   331  6999 V LGCodecOSAL: Called LGconfigureCodecMETA
09-06 19:11:14.800   331  6999 V LGCodecOSAL: Called LGconfigureCodecMSG
09-06 19:11:14.800   331  6999 V LGCodecOSAL: Not support LGCodec
09-06 19:11:14.800   331  6999 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-06 19:11:14.800   331  6999 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-06 19:11:14.800  6623  6623 D UEI.SmartControl: QS start get config
09-06 19:11:14.800   331  6999 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-06 19:11:14.800   331  6999 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-06 19:11:14.800   331  6999 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-06 19:11:14.800   331  6999 V AudioSystem: isOffloadSupported()
09-06 19:11:14.800   331  6999 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-06 19:11:14.800   331  6999 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-06 19:11:14.800   331  6999 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-06 19:11:14.800   331  6999 V OMXCodec: init()
09-06 19:11:14.800   331  6999 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-06 19:11:14.800   331  6999 V OMXCodec: allocateBuffers
09-06 19:11:14.800   331  6999 V OMXCodec: allocateBuffersOnPort portIndex=0
09-06 19:11:14.800   331  6999 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-06 19:11:14.800   331  6999 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
09-06 19:11:14.800   331  6999 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
09-06 19:11:14.801   331  6999 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
09-06 19:11:14.801   331  6999 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
09-06 19:11:14.801   331  6999 V OMXCodec: allocateBuffersOnPort portIndex=1
09-06 19:11:14.801   331  6999 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-06 19:11:14.801   331  6999 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
09-06 19:11:14.801   331  6999 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
09-06 19:11:14.801   331  6999 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
09-06 19:11:14.801   331  6999 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f9100 on output port
09-06 19:11:14.801   331  6999 V OMXCodec: init() mAsyncCompletion wait!!! 
09-06 19:11:14.801   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-06 19:11:14.801   331  7001 V OMXCodec: [OMX.google.vorbis.deco,der] Now Idle.
09-06 19:11:14.801   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-06 19:11:14.801   331  6999 V OMXCodec: init() mAsyncCompletion wait!!! 
09-06 19:11:14.801   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-06 19:11:14.801   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-06 19:11:14.801   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-06 19:11:14.801   331  6999 V OMXCodec: init() mAsyncCompletion wait free! 
09-06 19:11:14.801   331  6999 V AwesomePlayer: finishAsyncPrepare_l() 
09-06 19:11:14.801   331  6999 V AudioCache: notify(0xb5474680, 5, 0, 0)
09-06 19:11:14.801   331  6999 V AudioCache: ignored
09-06 19:11:14.801   331  6999 V AudioCache: notify(0xb5474680, 1, 0, 0)
09-06 19:11:14.801   331  6999 V AudioCache: prepared
09-06 19:11:14.801   331  1382 V AudioCache: wait - success
09-06 19:11:14.801   331  1382 V MediaPlayerService: start
09-06 19:11:14.801   331  1382 V AwesomePlayer: play_l() 
09-06 19:11:14.802   331  1382 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-06 19:11:14.802   331  1382 V AwesomePlayer: createAudioPlayer_l
09-06 19:11:14.802   331  1382 V AwesomePlayer: seekAudioIfNecessary_l() 
09-06 19:11:14.802   331  1382 V AwesomePlayer: startAudioPlayer_l() 
09-06 19:11:14.802   331  1382 D AudioPlayer: start of Playback, useOffload 0
09-06 19:11:14.802   331  1382 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-06 19:11:14.802   331  1382 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-06 19:11:14.804   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-06 19:11:14.804   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-06 19:11:14.804   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-06 19:11:14.804   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-06 19:11:14.804   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-06 19:11:14.804   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-06 19:11:14.804   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
09-06 19:11:14.804   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:11:14.804   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
09-06 19:11:14.804   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:11:14.804   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
09-06 19:11:14.804   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:11:14.804   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045036288
09-06 19:11:14.804   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:11:14.804   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-06 19:11:14.804   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-06 19:11:14.804   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-06 19:11:14.804   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-06 19:11:14.804   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-06 19:11:14.804   331  7001 V OMXCodec: allocateBuffersOnPort portIndex=1
09-06 19:11:14.804   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-06 19:11:14.804   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
09-06 19:11:14.805   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
09-06 19:11:14.805   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
09-06 19:11:14.805   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f95b0 on output port
09-06 19:11:14.805   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-06 19:11:14.805   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-06 19:11:14.806   331  1382 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-06 19:11:14.806   331  1382 V AudioCache: notify(0xb5474680, 6, 0, 0)
09-06 19:11:14.806   331  1382 V AudioCache: ignored
09-06 19:11:14.806   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.806   331  7002 V AudioCache: memcpy(0xaf006000, 0xb16e2000, 4096)
09-06 19:11:14.806   331  1382 V MediaPlayerService: wait for playback complete
09-06 19:11:14.810   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.810   331  7002 V AudioCache: memcpy(0xaf007000, 0xb16e2000, 4096)
09-06 19:11:14.811   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.811   331  7002 V AudioCache: memcpy(0xaf008000, 0xb16e2000, 4096)
09-06 19:11:14.811   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.811   331  7002 V AudioCache: memcpy(0xaf009000, 0xb16e2000, 4096)
09-06 19:11:14.811   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.811   331  7002 V AudioCache: memcpy(0xaf00a000, 0xb16e2000, 4096)
09-06 19:11:14.811   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.811   331  7002 V AudioCache: memcpy(0xaf00b000, 0xb16e2000, 4096)
09-06 19:11:14.812   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.813   331  7002 V AudioCache: memcpy(0xaf00c000, 0xb16e2000, 4096)
09-06 19:11:14.813   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.813   331  7002 V AudioCache: memcpy(0xaf00d000, 0xb16e2000, 4096)
09-06 19:11:14.813   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.813   331  7002 V AudioCache: memcpy(0xaf00e000, 0xb16e2000, 4096)
09-06 19:11:14.813   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.813   331  7002 V AudioCache: memcpy(0xaf00f000, 0xb16e2000, 4096)
09-06 19:11:14.814   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.814   331  7002 V AudioCache: memcpy(0xaf010000, 0xb16e2000, 4096)
09-06 19:11:14.814   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.814   331  7002 V AudioCache: memcpy(0xaf011000, 0xb16e2000, 4096)
09-06 19:11:14.814   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.814   331  7002 V AudioCache: memcpy(0xaf012000, 0xb16e2000, 4096)
09-06 19:11:14.814   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.814   331  7002 V AudioCache: memcpy(0xaf013000, 0xb16e2000, 4096)
09-06 19:11:14.816   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.816   331  7002 V AudioCache: memcpy(0xaf014000, 0xb16e2000, 4096)
09-06 19:11:14.817   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.817   331  7002 V AudioCache: memcpy(0xaf015000, 0xb16e2000, 4096)
09-06 19:11:14.817   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.817   331  7002 V AudioCache: memcpy(0xaf016000, 0xb16e2000, 4096)
09-06 19:11:14.818   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.818   331  7002 V AudioCache: memcpy(0xaf017000, 0xb16e2000, 4096)
09-06 19:11:14.819   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.819   331  7002 V AudioCache: memcpy(0xaf018000, 0xb16e2000, 4096)
09-06 19:11:14.819   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.819   331  7002 V AudioCache: memcpy(0xaf019000, 0xb16e2000, 4096)
09-06 19:11:14.821   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.821   331  7002 V AudioCache: memcpy(0xaf01a000, 0xb16e2000, 4096)
09-06 19:11:14.821   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.821   331  7002 V AudioCache: memcpy(0xaf01b000, 0xb16e2000, 4096)
09-06 19:11:14.822   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.822   331  7002 V AudioCache: memcpy(0xaf01c000, 0xb16e2000, 4096)
09-06 19:11:14.823   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.823   331  7002 V AudioCache: memcpy(0xaf01d000, 0xb16e2000, 4096)
09-06 19:11:14.823   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.823   331  7002 V AudioCache: memcpy(0xaf01e000, 0xb16e2000, 4096)
09-06 19:11:14.824   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.824   331  7002 V AudioCache: memcpy(0xaf01f000, 0xb16e2000, 4096)
09-06 19:11:14.824   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.824   331  7002 V AudioCache: memcpy(0xaf020000, 0xb16e2000, 4096)
09-06 19:11:14.825   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.825   331  7002 V AudioCache: memcpy(0xaf021000, 0xb16e2000, 4096)
09-06 19:11:14.825   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.825   331  7002 V AudioCache: memcpy(0xaf022000, 0xb16e2000, 4096)
09-06 19:11:14.826   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.826   331  7002 V AudioCache: memcpy(0xaf023000, 0xb16e2000, 4096)
09-06 19:11:14.827   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.827   331  7002 V AudioCache: memcpy(0xaf024000, 0xb16e2000, 4096)
09-06 19:11:14.827   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.827   331  7002 V AudioCache: memcpy(0xaf025000, 0xb16e2000, 4096)
09-06 19:11:14.828   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.828   331  7002 V AudioCache: memcpy(0xaf026000, 0xb16e2000, 4096)
09-06 19:11:14.828   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.828   331  7002 V AudioCache: memcpy(0xaf027000, 0xb16e2000, 4096)
09-06 19:11:14.829   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.829   331  7002 V AudioCache: memcpy(0xaf028000, 0xb16e2000, 4096)
09-06 19:11:14.830   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.830   331  7002 V AudioCache: memcpy(0xaf029000, 0xb16e2000, 4096)
09-06 19:11:14.830   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.830   331  7002 V AudioCache: memcpy(0xaf02a000, 0xb16e2000, 4096)
09-06 19:11:14.831   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.831   331  7002 V AudioCache: memcpy(0xaf02b000, 0xb16e2000, 4096)
09-06 19:11:14.832   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.832   331  7002 V AudioCache: memcpy(0xaf02c000, 0xb16e2000, 4096)
09-06 19:11:14.833   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.833   331  7002 V AudioCache: memcpy(0xaf02d000, 0xb16e2000, 4096)
09-06 19:11:14.834   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.834   331  7002 V AudioCache: memcpy(0xaf02e000, 0xb16e2000, 4096)
09-06 19:11:14.834   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.834   331  7002 V AudioCache: memcpy(0xaf02f000, 0xb16e2000, 4096)
09-06 19:11:14.835   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.835   331  7002 V AudioCache: memcpy(0xaf030000, 0xb16e2000, 4096)
09-06 19:11:14.835   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.835   331  7002 V AudioCache: memcpy(0xaf031000, 0xb16e2000, 4096)
09-06 19:11:14.836   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.836   331  7002 V AudioCache: memcpy(0xaf032000, 0xb16e2000, 4096)
09-06 19:11:14.836   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.836   331  7002 V AudioCache: memcpy(0xaf033000, 0xb16e2000, 4096)
09-06 19:11:14.837   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.837   331  7002 V AudioCache: memcpy(0xaf034000, 0xb16e2000, 4096)
09-06 19:11:14.837   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-06 19:11:14.837   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.837   331  7002 V AudioCache: memcpy(0xaf035000, 0xb16e2000, 4096)
09-06 19:11:14.837   331  7002 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-06 19:11:14.837   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.837   331  7002 V AudioCache: memcpy(0xaf036000, 0xb16e2000, 4096)
09-06 19:11:14.837   331  7002 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-06 19:11:14.837   331  7002 V AudioCache: write(0xb16e2000, 4096)
09-06 19:11:14.837   331  7002 V AudioCache: memcpy(0xaf037000, 0xb16e2000, 4096)
09-06 19:11:14.837   331  7002 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-06 19:11:14.837   331  7002 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-06 19:11:14.837   331  7002 V AwesomePlayer: postAudioEOS() 
09-06 19:11:14.838   331  7002 V AudioCache: write(0xb16e2000, 280)
09-06 19:11:14.838   331  7002 V AudioCache: memcpy(0xaf038000, 0xb16e2000, 280)
09-06 19:11:14.839   331  6999 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-06 19:11:14.839   331  6999 V AwesomePlayer: onStreamDone
09-06 19:11:14.839   331  6999 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-06 19:11:14.839   331  6999 V AudioCache: notify(0xb5474680, 2, 0, 0)
09-06 19:11:14.839   331  6999 V AudioCache: playback complete
09-06 19:11:14.839   331  6999 V AwesomePlayer: pause_l() 
09-06 19:11:14.839   331  6999 V AudioCache: notify(0xb5474680, 7, 0, 0)
09-06 19:11:14.839   331  1382 V AudioCache: wait - success
09-06 19:11:14.839   331  6999 V AudioCache: ignored
09-06 19:11:14.839   331  6999 V AwesomePlayer: cancelPlayerEvents
09-06 19:11:14.839   331  1382 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-06 19:11:14.839   331  6999 D AudioPlayer: Pause Playback at 1068125
,09-06 19:11:14.840   331  1382 V AwesomePlayer: reset_l() 
09-06 19:11:14.840   331  1382 V AudioCache: notify(0xb5474680, 8, 0, 0)
09-06 19:11:14.840   331  1382 V AudioCache: ignored
09-06 19:11:14.840   331  1382 V AwesomePlayer: cancelPlayerEvents
09-06 19:11:14.840   331  1382 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-06 19:11:14.840   331  1382 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-06 19:11:14.840   331  1382 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-06 19:11:14.840   331  1382 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-06 19:11:14.840   331  1382 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-06 19:11:14.840   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-06 19:11:14.840   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-06 19:11:14.840   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-06 19:11:14.840   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
09-06 19:11:14.840   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-06 19:11:14.840   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
09-06 19:11:14.840   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-06 19:11:14.840   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
09-06 19:11:14.840   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-06 19:11:14.840   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
09-06 19:11:14.840   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-06 19:11:14.840   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-06 19:11:14.840   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57f95b0 on port 1
09-06 19:11:14.840   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-06 19:11:14.840   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
09-06 19:11:14.840   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-06 19:11:14.840   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
09-06 19:11:14.840   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-06 19:11:14.840   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
09-06 19:11:14.840   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-06 19:11:14.840   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-06 19:11:14.841   331  1382 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-06 19:11:14.841   331  1382 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-06 19:11:14.841   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-06 19:11:14.841   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-06 19:11:14.841   331  7001 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-06 19:11:14.841   331  1382 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-06 19:11:14.841   331  1382 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-06 19:11:14.841   331  1382 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-06 19:11:14.842   331  1382 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-06 19:11:14.842   331  1382 D AudioPlayer: AudioPlayer releasing audio source
09-06 19:11:14.842   331  1382 D AudioPlayer: AudioPlayer done releasing audio source
09-06 19:11:14.842   331  1382 V AwesomePlayer: reset_l() 
09-06 19:11:14.842   331  1382 V AwesomePlayer: cancelPlayerEvents
09-06 19:11:14.842   331  1382 V AwesomePlayer: ~AwesomePlayer call
09-06 19:11:14.842   331  1382 V AwesomePlayer: reset_l() 
09-06 19:11:14.842   331  1382 V AwesomePlayer: cancelPlayerEvents
09-06 19:11:14.842  6917  6997 V SoundPool: close(31)
09-06 19:11:14.842  6917  6997 V SoundPool: pointer = 0xa0006000, size = 205080, sampleRate = 48000, numChannels = 2
09-06 19:11:14.859  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-06 19:11:14.859  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,09-06 19:11:14.861  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:495
,09-06 19:11:15.106  6623  6623 I UEI.SmartControl: Supports setup maps: true
,09-06 19:11:15.111  6623  6623 D UEI.SmartControl: QS start statue = true Error code = 0
09-06 19:11:15.111  6623  6623 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-06 19:11:15.111  6623  6623 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-06 19:11:15.111  6623  6623 I UEI.SmartControl: ### init IR Blaster...
09-06 19:11:15.114  6623  6623 D serial_port: Configuring serial port
09-06 19:11:15.115  6623  6623 E UEI.SmartControl: UEIBLaster setting for 616
09-06 19:11:15.115  6623  6623 I UEI.SmartControl: Setting serial record hearder size = 2
09-06 19:11:15.115  6623  6623 I UEI.SmartControl: configuring settings for MAXQ616
09-06 19:11:15.115  6623  6623 I UEI.SmartControl: Get version...
09-06 19:11:15.135  6623  7003 D UEI.SmartControl: serial port data available: 21
,09-06 19:11:15.162  6623  6623 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-06 19:11:15.162  6623  6623 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-06 19:11:15.162  6623  6623 I UEI.SmartControl: QS saving settings...
09-06 19:11:15.164  6623  6623 D UEI.SmartControl: IR Blaster version: 25672567
,09-06 19:11:15.180  6623  7003 D UEI.SmartControl: serial port data available: 4
,09-06 19:11:15.212  6623  7012 I UEI.SmartControl: Device manager: loading config....
09-06 19:11:15.213  6623  7012 D UEI.SmartControl: ----------- loading internal config...
09-06 19:11:15.214  6623  6623 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-06 19:11:15.220  6623  6623 E UEI.SmartControl: Services init done
,09-06 19:11:15.221  6623  6623 D UEI.SmartControl: QS Service init finished
09-06 19:11:15.223  6623  6623 D UEI.SmartControl: QS Service version name: 2.1.91
09-06 19:11:15.223  6623  6623 D UEI.SmartControl: QS Service version code: 201091
09-06 19:11:15.225  6623  6623 D UEI.SmartControl: Service requested: Control
09-06 19:11:15.233  6623  7012 E UEI.SmartControl: Loading SETTINGS...
09-06 19:11:15.236  6623  6623 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-06 19:11:15.254  6917  6917 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-06 19:11:15.255  6623  6638 I UEI.SmartControl: ------ IControl API: 11
09-06 19:11:15.255  6623  6638 D UEI.SmartControl: File observer start...
09-06 19:11:15.256  6623  6638 E UEI.SmartControl: IR Port is disabled: false
09-06 19:11:15.256  6623  6638 D UEI.SmartControl: Starting file observer...
09-06 19:11:15.257  6623  6638 I UEI.SmartControl: Registering callback...
09-06 19:11:15.258  6623  6623 D UEI.SmartControl: Internal service binding...
09-06 19:11:15.259  6623  6639 I UEI.SmartControl: ------ IControl API: 19
09-06 19:11:15.260  6623  6639 I UEI.SmartControl: Registering Services Ready callback...
09-06 19:11:15.265  6623  7012 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-06 19:11:15.274  6623  7011 I UEI.SmartControl: Notify AllClients services are ready: 0
09-06 19:11:15.275  6917  6932 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-06 19:11:15.276  6917  6995 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-06 19:11:15.276  6917  6995 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-06 19:11:15.276  6917  6917 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-06 19:11:15.277  6917  6917 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-06 19:11:15.277  6623  6638 I UEI.SmartControl: ------ IControl API: 8
09-06 19:11:15.278  6623  7011 D UEI.SmartControl: -----service ready thread exits
,09-06 19:11:15.281  6917  6917 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-06 19:11:15.282  6917  6917 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-06 19:11:15.282  6917  6917 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-06 19:11:15.282  6917  6917 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-06 19:11:15.283  6917  6917 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-06 19:11:15.284  6917  6917 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-06 19:11:15.287  6917  6917 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-06 19:11:15.290  6917  6917 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-06 19:11:15.292  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-06 19:11:15.293  6917  6917 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 19:11:15.293  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-06 19:11:15.294  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-06 19:11:15.295  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-06 19:11:15.296  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-06 19:11:15.297  6917  6917 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473181875296]
09-06 19:11:15.301  6917  6917 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,09-06 19:11:15.306  1032  1781 I ActivityManager: Killing 6090:com.android.gallery3d/u0a27 (adj 15): empty #17
09-06 19:11:15.342  6917  7017 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-06 19:11:15.346  1032  1781 I ActivityManager: Killing 6492:com.lge.email/u0a23 (adj 15): empty #18
09-06 19:11:15.381  1032  2004 W libprocessgroup: failed to open /acct/uid_10027/pid_6090/cgroup.procs: No such file or directory
,09-06 19:11:15.386  1032  2327 W libprocessgroup: failed to open /acct/uid_10023/pid_6492/cgroup.procs: No such file or directory
09-06 19:11:15.392  6917  6917 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-06 19:11:15.394  6917  6917 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-06 19:11:15.394  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-06 19:11:15.395  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-06 19:11:15.395  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-06 19:11:15.395  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-06 19:11:15.396  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,09-06 19:11:15.406  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
09-06 19:11:16.135  1032  1575 D WifiServiceImplEx: setWifiEnabled: true pid=6732, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 19:11:16.137  1032  1575 D WifiService: setWifiEnabled: true pid=6732, uid=10118
09-06 19:11:16.137  1032  1575 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:11:16.166  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 19:11:16.167  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:11:16.167  1032  1032 D Ulp_jni : JNI:system_update. Event-4
,09-06 19:11:16.170  1032  1538 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-06 19:11:16.171  1032  1538 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-06 19:11:16.173  1032  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-06 19:11:16.173  1032  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-06 19:11:16.173  1032  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-06 19:11:16.173  1032  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-06 19:11:16.173  1032  1538 I WifiUtil: Intf0MacAddress=C49A027FFB5D
,09-06 19:11:16.174  1032  1538 E WifiHW  : unknown target_country: EU , set to default,
09-06 19:11:16.174  1032  1538 E WifiHW  : [wifi_ensure_config_files] default country1 = GB,
09-06 19:11:16.174  1032  1538 E WifiHW  : [wifi_ensure_config_files] default country2 = GB,
09-06 19:11:16.174  1032  1538 I WifiUtil: gEnableBmps=1,
09-06 19:11:16.271  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,09-06 19:11:16.302  1032  1094 D Tethering: MasterInitialState.processMessage what=3
,09-06 19:11:16.315  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:11:16.319  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:16.322  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:16.325  1032  1094 D Tethering: MasterInitialState.processMessage what=3
09-06 19:11:16.334  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:11:16.338  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:16.338  1032  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:16.340  6402  6402 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-06 19:11:16.343  6402  6871 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-06 19:11:16.344  5786  5786 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-06 19:11:16.368  5786  5786 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-06 19:11:16.385  2201  2201 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:11:16.447  1032  2004 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7019 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-06 19:11:16.457  1032  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:16.459  1032  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:16.460  1032  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-06 19:11:16.538  7019  7019 I AppUp4:AppBoxCP: onCreate
09-06 19:11:16.539  7019  7019 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-06 19:11:16.550  7019  7019 I AppUp4:DB:  setFingerPrint start
09-06 19:11:16.550  7019  7019 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-06 19:11:16.559  7019  7019 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-06 19:11:16.559  7019  7019 I AppUp4:DB:  SDK version = 21
09-06 19:11:16.559  7019  7019 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-06 19:11:16.561  7019  7019 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,09-06 19:11:16.563  7019  7019 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-06 19:11:16.563  7019  7019 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:16.566  7019  7019 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 19:11:16.566  7019  7019 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-06 19:11:16.575  7019  7019 I AppUp4:CustModeStarterReceiver: onReceive
,09-06 19:11:16.615  7019  7019 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:11:16.615  7019  7019 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:11:16.624  7019  7019 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@26a68538
09-06 19:11:16.624  7019  7019 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 19:11:16.624  7019  7019 D AppUp4:CustFacade: isPhone : true
09-06 19:11:16.625  7019  7019 D AppUp4:CustModeStarterReceiver: begin check event
09-06 19:11:16.625  7019  7019 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-06 19:11:16.626  7019  7019 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-06 19:11:16.627  7019  7053 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-06 19:11:16.627  7019  7053 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-06 19:11:16.627  7019  7053 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-06 19:11:16.629  1032  1049 I ActivityManager: Killing 6163:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,09-06 19:11:16.662  1032  2049 W libprocessgroup: failed to open /acct/uid_10080/pid_6163/cgroup.procs: No such file or directory
,09-06 19:11:16.665  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:16.666  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:11:16.670  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:11:16.674  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:11:16.686  4326  7055 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-06 19:11:16.692  4326  7056 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:16.693  4326  7056 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 19:11:16.746  1032  2003 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7064 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-06 19:11:16.833  7064  7064 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:11:16.834  7064  7064 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:11:16.836  7064  7064 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-06 19:11:16.836  7064  7064 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-06 19:11:16.879  1032  1094 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-06 19:11:16.884  1032  1094 D Tethering: InitialState.processMessage what=4
09-06 19:11:16.885  1032  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:11:16.894   327   899 D SoftapController: Softap fwReload - Ok
,09-06 19:11:16.895  1032  1538 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (715ms)
,09-06 19:11:16.900   327   899 D CommandListener: Setting iface cfg
09-06 19:11:16.900   327   899 D CommandListener: Trying to bring down wlan0
09-06 19:11:16.902   327   899 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:11:16.907  1032  1538 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-06 19:11:16.908  7082  7082 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-06 19:11:16.908  7082  7082 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:11:16.940  7082  7082 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-06 19:11:16.956  7064  7064 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-06 19:11:16.970  7064  7064 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-06 19:11:16.973  7082  7082 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-06 19:11:16.973  7082  7082 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-06 19:11:17.008  1032  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:11:17.008  1032  1538 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:11:17.008  1032  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:11:17.008  1032  1538 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-06 19:11:17.008  1032  1538 D WifiMonitor: connecting to supplicant
,09-06 19:11:17.011  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:17.014  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-06 19:11:17.015  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-06 19:11:17.015  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:17.016  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:17.046  7064  7064 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:11:17.046  7082  7082 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 19:11:17.098  7064  7064 D LgDataFeature: LgDataFeature() Constructor: none
,09-06 19:11:17.098  7064  7064 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 19:11:17.118  7082  7082 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-06 19:11:17.138  1032  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,09-06 19:11:17.139  1032  1538 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-06 19:11:17.140  7082  7082 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-06 19:11:17.141  7082  7082 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,09-06 19:11:17.141  1032  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-06 19:11:17.142  1032  7085 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-06 19:11:17.142  1032  1538 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-06 19:11:17.142  1032  7085 D WifiMonitor: Dropping event because (p2p0) is stopped
09-06 19:11:17.142  1032  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:11:17.142  1032  7085 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-06 19:11:17.142  1032  7085 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-06 19:11:17.142  1032  7085 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-06 19:11:17.142  1032  7085 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-06 19:11:17.143  1032  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:11:17.143  1032  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:11:17.143  1032  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-06 19:11:17.144  1032  1538 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-06 19:11:17.144  1032  1538 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-06 19:11:17.145  1032  1538 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-06 19:11:17.146  1032  1538 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-06 19:11:17.146  1032  1538 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-06 19:11:17.147  1032  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:11:17.147  1032  1538 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:11:17.147  1032  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:11:17.147  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:17.147  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:17.148  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:17.148  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:17.148  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:11:17.148  1032  1538 D WifiNative-wlan0: doBoolean: SET update_config 1
09-06 19:11:17.150  1969  1969 D WfdService: Waiting for WifiP2p enabling
09-06 19:11:17.151  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:17.151  1032  1538 D WifiNative-wlan0: SET update_config 1: returned true
,09-06 19:11:17.151  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-06 19:11:17.151  1032  1538 D WifiConfigStore: Loading config and enabling all networks 
09-06 19:11:17.151  1032  1538 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-06 19:11:17.152  6732  6732 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:11:17.152  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:11:17.152  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:17.152  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:17.152  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:11:17.152  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:11:17.152  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:11:17.152  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:11:17.152  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:11:17.152  6732  6732 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:11:17.152  6732  6732 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:11:17.152  1032  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-06 19:11:17.153  1032  1538 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-06 19:11:17.154  6732  6732 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:11:17.154  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:11:17.154  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:17.154  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:17.154  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:11:17.154  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:11:17.154  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:11:17.154  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:11:17.154  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:11:17.154  6732  6732 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:11:17.154  6732  6732 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:11:17.170  1032  1538 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,09-06 19:11:17.185  1032  1538 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,09-06 19:11:17.186  1032  1538 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-06 19:11:17.187  1032  1538 D WifiStateMachine: enableVerboseLogging : level 2
09-06 19:11:17.187  1032  1538 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-06 19:11:17.187  1032  1538 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-06 19:11:17.187  1032  1538 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-06 19:11:17.188  1032  1538 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-06 19:11:17.188  1032  1538 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-06 19:11:17.188  1032  1538 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-06 19:11:17.188  1032  1538 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-06 19:11:17.189  1032  1538 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-06 19:11:17.189  1032  1538 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-06 19:11:17.190  1032  1538 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-06 19:11:17.190  1032  1538 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-06 19:11:17.190  1032  1538 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-06 19:11:17.190  1032  1538 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-06 19:11:17.191  1032  1538 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-06 19:11:17.192  1032  1538 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:11:17.192  1032  1538 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-06 19:11:17.192  1969  1969 D WfdsService: Supplicant Connection state is changed : true
09-06 19:11:17.192  1969  2312 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-06 19:11:17.192  1969  2312 D WfdsService: Set the WFDS Monitor: true
09-06 19:11:17.192  1969  2312 D WfdsMonitor: WfdsMonitorThread create
09-06 19:11:17.192  1969  2312 D WfdsMonitor: WFDS Monitor is created and started
09-06 19:11:17.192  1969  2312 D WfdsService: WiFi: Supplicant connection re-established
09-06 19:11:17.193  1032  1538 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-06 19:11:17.193  1032  1538 D WifiNative-HAL: Setting external_sim to 1
09-06 19:11:17.193  1032  1538 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-06 19:11:17.193  1969  7088 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-06 19:11:17.193  1032  1538 D WifiNative-wlan0: SET external_sim 1: returned true
09-06 19:11:17.193  1032  1538 I WifiNative-HAL: startHal
09-06 19:11:17.193  1032  1538 D wifi    : setting scan oui 0xaf67d5c0
09-06 19:11:17.194  1969  7088 E CtrlSupplicant: Succeed to open control connection
09-06 19:11:17.194  1969  7088 E CtrlSupplicant: Succeed to open monitor connection
09-06 19:11:17.194  1032  1538 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:11:17.194  1032  1538 I WifiNative-HAL: startHal
09-06 19:11:17.194  1032  1538 D wifi    : setting scan oui 0xaf67d5c0
09-06 19:11:17.194  1969  7088 D WfdsMonitor: Supplicant connection established
09-06 19:11:17.194  1032  1538 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-06 19:11:17.194  1969  2312 D WfdsService: Connected to the supplicant for wfds
09-06 19:11:17.195  1032  1538 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-06 19:11:17.195  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-06 19:11:17.195  7082  7082 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-06 19:11:17.195  1032  1538 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-06 19:11:17.195  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-06 19:11:17.195  7082  7082 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-06 19:11:17.196  1032  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-06 19:11:17.196  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-06 19:11:17.196  7082  7082 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-06 19:11:17.196  1032 , 1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-06 19:11:17.196  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-06 19:11:17.196  7082  7082 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,09-06 19:11:17.197  1032  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-06 19:11:17.197  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-06 19:11:17.197  7082  7082 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-06 19:11:17.197  1032  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-06 19:11:17.197  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-06 19:11:17.197  7082  7082 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-06 19:11:17.198  1032  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-06 19:11:17.198  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-06 19:11:17.198  7082  7082 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-06 19:11:17.198  1032  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-06 19:11:17.199  1032  1538 E WifiNative: : [205,431,933 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-06 19:11:17.199  1032  1538 D WifiNative-wlan0: doBoolean: RECONNECT
09-06 19:11:17.200  1032  1538 D WifiNative-wlan0: RECONNECT: returned true
09-06 19:11:17.200  1032  1538 D WifiNative-wlan0: doString: [STATUS]
09-06 19:11:17.200  1032  7085 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-06 19:11:17.200  1032  7085 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-06 19:11:17.201  1032  1538 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-06 19:11:17.201  1032  1538 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:11:17.201  1032  1538 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:11:17.202  1032  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:17.203   327   899 D CommandListener: Setting iface cfg
09-06 19:11:17.203   327   899 D CommandListener: Trying to bring up p2p0
09-06 19:11:17.204  1032  1537 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-06 19:11:17.204  1032  1537 D LGWifiP2pService: P2pEnablingState
09-06 19:11:17.204  1032  1537 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:17.204  1032  1537 D LGWifiP2pService: P2p socket connection successful
09-06 19:11:17.204  1032  1537 D LGWifiP2pService: P2pEnabledState
09-06 19:11:17.204  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 3
09-06 19:11:17.205  1032  1032 D RttService: SCAN_AVAILABLE : 3
09-06 19:11:17.205  1032  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:17.205  1032  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:17.205  1032  1556 I WifiNative-HAL: startHal
09-06 19:11:17.205  1032  1538 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-06 19:11:17.205  1032  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf67d5c0
09-06 19:11:17.205  1032  1556 D wifi    : failed to get capabilities : -3
09-06 19:11:17.205  1032  1556 E WifiScanningService: could not get scan capabilities
09-06 19:11:17.205  1032  1538 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-06 19:11:17.206  1032  1538 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-06 19:11:17.206  1032  1538 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-06 19:11:17.207  1032  1538 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-06 19:11:17.207  1032  1538 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-06 19:11:17.208  1032  1538 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-06 19:11:17.208  1032  1538 I Wifi,ServerServiceExt: setWifiDualbandAPConnection band : 1
09-06 19:11:17.208  7082  7082 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-06 19:11:17.209  1032  1538 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-06 19:11:17.209  1032  1538 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-06 19:11:17.209  1032  1538 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-06 19:11:17.209  1032  1538 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
,09-06 19:11:17.209  7082  7082 E wpa_supplicant: disconnect_rssi_lvl: -100
09-06 19:11:17.210  1032  1538 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-06 19:11:17.211  1032  1538 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-06 19:11:17.211  1032  1538 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-06 19:11:17.211  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-06 19:11:17.212  7082  7082 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-06 19:11:17.213  7082  7082 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:11:17.214  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-06 19:11:17.214  1969  1969 D WfdsService: WifiP2pState is changed : true
09-06 19:11:17.214  1032  7085 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 19:11:17.214  1032  7085 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:11:17.214  1032  7085 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:11:17.214  1032  7085 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:11:17.214  1969  2312 D WfdsService: Receive the WFDS_ENABLE Method
09-06 19:11:17.214  1969  2312 D WfdsService: Set the WFDS Monitor: true
09-06 19:11:17.214  1969  2312 D WfdsService: Connected to the supplicant for wfds
09-06 19:11:17.214  1969  2312 D WfdsJNI : doCommand: WFDS_SET TRUE
09-06 19:11:17.214  7082  7082 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-06 19:11:17.214  7082  7082 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:17.215  1969  7088 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:11:17.215  7082  7082 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:17.215  1032  7085 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:11:17.215  1032  7085 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:17.216  1969  7088 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:11:17.216  1032  7085 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:17.216  1032  7085 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:17.216  7082  7082 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-06 19:11:17.216  1032  1537 D LGWifiP2pService: sending p2p connection changed broadcast
09-06 19:11:17.216  1032  7085 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:11:17.216  1032  7085 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:17.216  1032  7085 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:17.216  1032  7085 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:17.216  1969  2312 D WfdsService: selectPreferredScanChannel [36]
09-06 19:11:17.216  1969  2312 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-06 19:11:17.216  1032  1537 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-06 19:11:17.216  1032  1538 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-06 19:11:17.217  1032  1538 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-06 19:11:17.217  1032  1538 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-06 19:11:17.218  1032  1538 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-06 19:11:17.218  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-06 19:11:17.218  1969  1969 D Wf,dsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-06 19:11:17.218  7082  7082 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-06 19:11:17.218  7082  7082 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:11:17.218  1032  7085 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-06 19:11:17.218  1032  7085 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:11:17.218  1032  7085 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:11:17.218  1032  7085 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:11:17.219  1969  1969 D WfdsService: isConnected: false
09-06 19:11:17.219  1032  1538 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-06 19:11:17.219  1032  1538 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-06 19:11:17.219  1032  1538 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-06 19:11:17.219  1032  1538 D WifiNative-wlan0: doBoolean: SCAN
09-06 19:11:17.220  1032  1537 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-06 19:11:17.220  1032  1537 D WifiNative-p2p0: doBoolean: SET device_name G3
09-06 19:11:17.220  1032  1538 D WifiNative-wlan0: SCAN: returned false
09-06 19:11:17.221  1032  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=205454  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 19:11:17.222  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=205455  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 19:11:17.222  1032  1537 D WifiNative-p2p0: SET device_name G3: returned true
09-06 19:11:17.222  1032  1537 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-06 19:11:17.222  1032  1537 D LGWifiP2pService: before postfix = G3
09-06 19:11:17.222  1032  1537 D WifiServerServiceExt: postfix byte check : 2
09-06 19:11:17.222  1032  1537 D LGWifiP2pService: after postfix = G3
,09-06 19:11:17.222  1032  1537 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-06 19:11:17.223  1032  1537 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-06 19:11:17.223  1032  1537 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-06 19:11:17.223  1032  1537 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-06 19:11:17.223  1032  1537 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-06 19:11:17.223  1032  1537 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-06 19:11:17.223  1032  1537 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-06 19:11:17.223  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:17.224  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:11:17.224  1032  1537 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-06 19:11:17.224  1032  1537 D WifiNative-HAL: p2pGetDeviceAddress
09-06 19:11:17.224  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:17.224  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:17.224  1032  1537 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-06 19:11:17.224  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-06 19:11:17.225  1032  1538 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:11:17.225  1032  1538 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:11:17.226  1032  1538 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:11:17.226  1032  1538 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:11:17.226  1032  1538 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:11:17.228  1032  1537 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-06 19:11:17.228  1032  1537 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-06 19:11:17.229  1969  1969 I WfdStateTracker: handleP2pThisDeviceChanged
09-06 19:11:17.229  1969  1969 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-06 19:11:17.229  1032  1537 D WifiNative-p2p0: P2P_FLUSH: returned true
09-06 19:11:17.229  1032  1537 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-06 19:11:17.229  1969  1969 D WfdsService: Update P2p Interface State: 3
09-06 19:11:17.229  1032  1537 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-06 19:11:17.229  1032  1537 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-06 19:11:17.230  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:11:17.230  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
09-06 19:11:17.230  1032  1537 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-06 19:11:17.231  1032  1537 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-06 19:11:17.231  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:17.239  1032  1537 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-06 19:11:17.239  1032  1537 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-06 19:11:17.239  1032  1537 D LGWifiP2pService: InactiveState
09-06 19:11:17.240  1032  1537 D LGWifiP2pService: InactiveState{ when=-23ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:17.240  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-23ms what=143376 obj=CZ target=com.,android.internal.util.StateMachine$SmHandler }
09-06 19:11:17.240  1032  1537 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,09-06 19:11:17.242  7082  7082 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-06 19:11:17.243  7082  7082 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:11:17.243  1969  7088 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 19:11:17.243  1032  7085 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 19:11:17.243  1032  7085 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:11:17.243  1032  7085 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:11:17.243  1032  7085 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:11:17.243  7082  7082 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-06 19:11:17.243  7082  7082 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:17.243  1032  1537 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-06 19:11:17.244  1969  7088 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:11:17.244  1032  7085 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:11:17.244  1032  7085 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:17.244  1032  7085 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:17.244  7082  7082 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:17.244  1032  7085 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:17.244  1969  7088 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:11:17.244  1032  7085 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:11:17.244  1032  7085 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:17.244  1032  7085 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:17.244  1032  7085 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:17.245  1032  1537 D LGWifiP2pService: InactiveState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:17.245  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:17.245  1032  1537 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:17.245  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:17.245  1032  1537 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:17.245  1032  1537 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:17.245  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:17.245  1032  1537 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:17.245  1032  1537 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:17.245  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:17.245  1032  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:17.245  1969  2312 W ,WfdsService: DefaultState - msg [9441285] is not handled
09-06 19:11:17.246  1032  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:17.246  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:17.246  1032  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:17.246  1032  1032 E WifiServerServiceExt: No p2p device connected
09-06 19:11:17.258  7064  7064 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-06 19:11:17.283  3357  3357 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 19:11:17.283  3357  3357 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:17.283  3357  3357 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-06 19:11:17.287  7064  7064 I HubEmail: JNI_OnLoad()
09-06 19:11:17.287  7064  7064 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-06 19:11:17.287  7064  7064 I HubEmail: registerNatives()
09-06 19:11:17.287  7064  7064 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-06 19:11:17.287  7064  7064 I HubEmail: registerNativeMethods()
09-06 19:11:17.287  7064  7064 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-06 19:11:17.287  7064  7064 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-06 19:11:17.323  1032  1929 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7094 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-06 19:11:17.329  7064  7093 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:17.332  6941  7091 W FormManager: Network not available. Please check & try again.
09-06 19:11:17.333  6941  7092 V FormManager: Network unavailable.
09-06 19:11:17.336  6941  7092 V FormManager: Network unavailable.
,09-06 19:11:17.348  1032  2049 I ActivityManager: Killing 6533:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,09-06 19:11:17.412  1032  2004 W libprocessgroup: failed to open /acct/uid_10061/pid_6533/cgroup.procs: No such file or directory
09-06 19:11:17.491  7094  7094 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:11:17.492  7094  7094 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:11:17.497  7094  7094 D PhoneMonitor: Register our PhoneStateListener
,09-06 19:11:17.516  7094  7094 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-06 19:11:17.520  7094  7094 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-06 19:11:17.545  7094  7094 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,09-06 19:11:17.548  7094  7094 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-06 19:11:17.551  7094  7094 D TelephonyAutoProfiling: [parse] Load xml
09-06 19:11:17.556  7094  7094 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-06 19:11:17.557  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-06 19:11:17.557  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-06 19:11:17.557  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-06 19:11:17.557  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-06 19:11:17.557  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-06 19:11:17.557  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-06 19:11:17.557  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-06 19:11:17.557  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-06 19:11:17.557  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-06 19:11:17.557  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-06 19:11:17.557  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-06 19:11:17.557  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-06 19:11:17.557  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-06 19:11:17.557  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-06 19:11:17.558  7094  7094 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-06 19:11:17.558  7094  7094 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,09-06 19:11:17.570  7094  7094 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,09-06 19:11:17.579  1032  2004 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7117 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:11:17.580  1032  2004 I ActivityManager: Killing 6192:com.google.android.apps.plus/u0a97 (adj 15): empty #17
09-06 19:11:17.630  1032  1967 W libprocessgroup: failed to open /acct/uid_10097/pid_6192/cgroup.procs: No such file or directory
,09-06 19:11:17.734  7082  7082 E wpa_supplicant: USIM:  scard_init function
09-06 19:11:17.735  7082  7082 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-06 19:11:17.737  1032  7085 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-06 19:11:17.737  1032  7085 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,09-06 19:11:17.737  1032  7085 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-06 19:11:17.737  1032  7085 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
09-06 19:11:17.737  1032  7085 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-06 19:11:17.738  1032  7085 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-06 19:11:17.738  1032  7085 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-06 19:11:17.738  1032  1538 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-06 19:11:17.739  1032  1538 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-06 19:11:17.740  1032  1538 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-06 19:11:17.740  1032  1538 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-06 19:11:17.740  1032  1538 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-06 19:11:17.747  1032  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=205981  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-06 19:11:17.754  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:17.756  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:17.756  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:11:17.756  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:17.757  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-06 19:11:17.760  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:11:17.765  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:17.765  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:11:17.765  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-06 19:11:17.766  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=205999  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-06 19:11:17.767  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:11:17.767  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-06 19:11:17.781  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:17.781  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-06 19:11:17.784  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:17.843  1032  1929 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7135 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-06 19:11:17.845  1032  1929 I ActivityManager: Killing 6585:com.lge.eula/1000 (adj 15): empty #17
,09-06 19:11:17.864  7082  7082 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-06 19:11:17.867  1032  7085 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-06 19:11:17.867  1032  7085 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-06 19:11:17.868  1032  7085 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-06 19:11:17.868  1032  7085 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-06 19:11:17.868  1032  7085 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:11:17.868  1032  7085 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:11:17.869  1032  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=206102  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-06 19:11:17.869  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=206102  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-06 19:11:17.871  1032  1538 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206104
09-06 19:11:17.871  1032  1538 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206104
09-06 19:11:17.872  1032  1538 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206105
09-06 19:11:17.873  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206106
09-06 19:11:17.873  1032  1538 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206106
09-06 19:11:17.874  7082  7082 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:11:17.874  7082  7082 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 19:11:17.875  1032  7085 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:11:17.875  1032  7085 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:11:17.875  1032  7085 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-06 19:11:17.875  1032  7085 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:11:17.875  1032  7085 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:11:17.875  1032  7085 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-06 19:11:17.875  1032  7085 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 19:11:17.875  1032  7085 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 19:11:17.876  1032  7085 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:11:17.876  1032  7085 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:11:17.876  1032  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=206109  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-06 19:11:17.890  1032  2323 W libprocessgroup: failed to open /acct/uid_1000/pid_6585/cgroup.procs: No such file or directory
,09-06 19:11:17.893  1032  1094 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:11:17.895  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:17.895  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:11:17.897  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=206130  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-06 19:11:17.898  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:17.898  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:17.898  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-06 19:11:17.899  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:17.900  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:17.900  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:17.900  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-06 19:11:17.901  1032  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=206134  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-06 19:11:17.901  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=206135  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-06 19:11:17.902  1032  1538 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=206135
09-06 19:11:17.902  1032  1538 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=206136
09-06 19:11:17.903  1032  1538 D WifiNative-wlan0: doString: [STATUS]
,09-06 19:11:17.904  1032  7085 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:11:17.904  1032  7085 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:11:17.904  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:17.904  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:11:17.905  1032  1538 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-06 19:11:17.905  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:17.906  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:11:17.906  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-06 19:11:17.907  1032  1538 I WifiServiceExtension: setVHTCapabilityType  : false
,09-06 19:11:17.922  1032  1538 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-06 19:11:17.922  1032  1538 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-06 19:11:17.925  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:17.925  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:17.925  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:11:17.925  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:17.925  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-06 19:11:17.928  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:17.928  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:17.928  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-06 19:11:17.929  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:11:17.931  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:17.931  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:11:17.932  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:17.934  1032  1538 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-06 19:11:17.934  1032  1545 D ConnectivityService: Got NetworkAgent Messenger
09-06 19:11:17.935  1032  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-06 19:11:17.935  1032  1545 D ConnectivityService: NetworkAgent connected
09-06 19:11:17.935  1032  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:11:17.935  1032  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 19:11:17.936  1032  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 19:11:17.936  1032  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 19:11:17.944  1032  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 19:11:17.944  1032  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:11:17.944  1032  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,09-06 19:11:17.944  1032  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 19:11:17.944  1032  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 19:11:17.952  1032  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 19:11:17.954   327   899 D CommandListener: Setting iface cfg
09-06 19:11:17.957  1032  1538 E WifiStateMachine: Start Dhcp Watchdog 2
09-06 19:11:17.957  1032  7153 D DhcpStateMachine: StoppedState
09-06 19:11:17.957  1032  7153 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:17.957  1032  7153 D DhcpStateMachine: WaitBeforeStartState
09-06 19:11:17.957  1032  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=206191  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:11:17.958  1032  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=206191  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-06 19:11:17.958  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=206192  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:11:17.959  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:11:17.960  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:11:17.960  1032  1538 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:11:17.961  1032  1538 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:11:17.961  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:11:17.962  1032  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:11:17.962  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:11:17.963  1032  1032 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-06 19:11:17.963  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:11:17.964  1032  1032 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-06 19:11:17.964  1032  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=206197  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:11:17.965  1032  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=206198  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:11:17.965  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=206198  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:11:17.966  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:160329] from screen [on:0 period:8095438] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-06 19:11:17.967  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:8095439] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-06 19:11:17.967  1032  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-06 19:11:17.971  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:11:17.972  1032  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-06 19:11:17.972  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,09-06 19:11:17.972  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:17.973  1032  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:17.973  1032  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:17.974  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:17.974  1032  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:17.975  1032  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-06 19:11:17.975  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=166,0,0
09-06 19:11:17.975  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=166,0,0
09-06 19:11:17.975  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-06 19:11:17.976  7082  7082 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-06 19:11:17.978  1032  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-06 19:11:17.978  1032  1538 D WifiNative-wlan0: doBoolean: SET ps 0
09-06 19:11:17.979  1032  1538 D WifiNative-wlan0: SET ps 0: returned true
09-06 19:11:17.979  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-06 19:11:17.979  7082  7082 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-06 19:11:17.980  1032  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-06 19:11:17.980  1032  1538 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-06 19:11:17.980  1032  1538 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-06 19:11:17.980  1032  1538 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-06 19:11:17.981   327   899 D CommandListener: Setting iface cfg
09-06 19:11:17.981   327   899 D CommandListener: Trying to bring up wlan0
09-06 19:11:17.982  1032  1537 D LGWifiP2pService: InactiveState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f0bcc28 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:17.982  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f0bcc28 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:17.983  1032  1538 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-06 19:11:17.983  1032  7153 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:17.983  1032  7153 D DhcpStateMachine: DHCP Start wake lock is acquired.
,09-06 19:11:18.013  1032  2003 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7154 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:11:18.015  1032  2003 I ActivityManager: Killing 6602:com.lge.bnr/1000 (adj 15): empty #17
,09-06 19:11:18.103  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:11:18.104  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,09-06 19:11:18.121  1032  1967 W libprocessgroup: failed to open /acct/uid_1000/pid_6602/cgroup.procs: No such file or directory
09-06 19:11:18.121  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:18.123  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:18.124  1032  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:18.126  1032  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,09-06 19:11:18.127  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:18.131  1032  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:18.133  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:11:18.133  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-06 19:11:18.134  1032  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-06 19:11:18.135  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-06 19:11:18.136  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-06 19:11:18.136  1032  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:18.136  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:18.136  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 19:11:18.137  7082  7082 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 19:11:18.137  1032  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 19:11:18.137  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-06 19:11:18.138  7082  7082 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-06 19:11:18.140  1032  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-06 19:11:18.140  1032  1538 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:11:18.156  1032  1538 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:11:18.157  1032  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,09-06 19:11:18.157  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-06 19:11:18.158  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-06 19:11:18.158  1032  1538 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-06 19:11:18.160  1032  1545 D ConnectivityService: ignoring duplicate network state non-change
09-06 19:11:18.160  1032  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-06 19:11:18.161  1032  1545 D ConnectivityService: Adding iface wlan0 to network 101
09-06 19:11:18.164  1032  1537 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:18.164  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:18.164  1032  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:18.165  1032  1538 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-06 19:11:18.169  7154  7154 I art     : Almond Protected OAT
,09-06 19:11:18.184  1032  7153 D DhcpStateMachine: DHCPV4 request on wlan0
09-06 19:11:18.185  1032  7153 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-06 19:11:18.185  1032  7153 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-06 19:11:18.178  7172  7172 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:11:18.178  7172  7172 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-06 19:11:18.194  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:18.194  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:11:18.197  7172  7172 I dhcpcd  : version 5.5.6 starting
,09-06 19:11:18.202  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:18.202  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:18.202  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-06 19:11:18.203  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:18.204  7172  7172 E dhcpcd  : get_duid: m
09-06 19:11:18.204  7172  7172 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-06 19:11:18.204  7172  7172 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-06 19:11:18.209  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:18.209  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:11:18.212  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:11:18.224  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:18.224  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:18.224  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-06 19:11:18.225  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-06 19:11:18.227  1032  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-06 19:11:18.227  1032  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-06 19:11:18.228  1032  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-06 19:11:18.229   327   899 E Netd    : netlink response contains error (File exists)
09-06 19:11:18.230  1032  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-06 19:11:18.231  1032  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-06 19:11:18.231  1032  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-06 19:11:18.231  1032  1545 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-06 19:11:18.234  1032  1538 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 19:11:18.234  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 19:11:18.236  1032  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 19:11:18.236  1032  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 19:11:18.236  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 19:11:18.237  1032  1538 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-06 19:11:18.239  1969  1969 V WfdStateTracker: handleWifiStateChangedEvent: 1
,09-06 19:11:18.243  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:18.243  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:18.243  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-06 19:11:18.244  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-06 19:11:18.252  1032  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-06 19:11:18.252  1032  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-06 19:11:18.252  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:18.252  1032  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-06 19:11:18.252  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:18.252  1032  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-06 19:11:18.252  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-06 19:11:18.252  1032  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:11:18.252  1032  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:11:18.252  1032  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-06 19:11:18.252  1032  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:18.252  1032  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-06 19:11:18.252  1032  1545 D ConnectivityService: currentScore = 0, newScore = 20
09-06 19:11:18.252  1032  1545 D ConnectivityService:    accepting network in place of null
09-06 19:11:18.252  1032  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-06 19:11:18.253  1032  7152 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:18.253  1032  7152 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-06 19:11:18.253  1032  7152 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:18.253  1032  7152 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-06 19:11:18.255  1032  1538 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:18.255  1032  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:11:18.256  1878  1878 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:18.256  1878  1878 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 19:11:18.261  1032  1545 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-06 19:11:18.261  1032  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-06 19:11:18.261  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:11:18.261  1032  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:18.261  1032  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-06 19:11:18.262  1032  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-06 19:11:18.264   327  7187 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-06 19:11:18.264   327  7187 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-06 19:11:18.266  1032  1032 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-06 19:11:18.267  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 19:11:18.267  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToP,rovisioningNetwork: false] info.getType():1
09-06 19:11:18.267  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 19:11:18.270  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:18.271  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-06 19:11:18.271  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:18.272  7172  7172 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-06 19:11:18.272  7172  7172 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-06 19:11:18.272  7172  7172 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,09-06 19:11:18.272  7172  7172 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-06 19:11:18.273  7172  7172 D dhcpcd  : wlan0: sending REQUEST (xid 0x79c98506), next in 3.12 seconds
,09-06 19:11:18.274  1032  1536 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-06 19:11:18.275  1032  1545 D ConnectivityService: validation of new default Network = false
09-06 19:11:18.275  1032  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-06 19:11:18.275  1032  1545 D DSQN    : enableDataServiceNotify 
09-06 19:11:18.275  1032  1545 D DSQN    : start dsqn bin
09-06 19:11:18.279  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:18.279  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-06 19:11:18.279  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:11:18.297  7154  7154 D WeatherApplication: removeAccount
,09-06 19:11:18.298  7154  7154 D WeatherApplication: Account.length = 0
09-06 19:11:18.298  7154  7154 E WeatherApplication: OPERATOR:OPEN
09-06 19:11:18.304  7154  7154 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:11:18
09-06 19:11:18.305  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 19:11:18.306  1817  7188 I CheckinService: active receiver: enabled
09-06 19:11:18.307  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:18.308  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:18.309  7172  7172 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-06 19:11:18.311   327  7187 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-06 19:11:18.320  7172  7172 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-06 19:11:18.320  7172  7172 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,09-06 19:11:18.320  7172  7172 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-06 19:11:18.320  7172  7172 D dhcpcd  : wlan0: adding default route via 192.168.1.1
,09-06 19:11:18.320  7172  7172 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-06 19:11:18.320  7172  7172 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-06 19:11:18.320  7172  7172 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-06 19:11:18.320  7172  7172 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-06 19:11:18.383  1032  7152 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 06 Sep 2016 17:11:18 GMT], X-Android-Received-Millis=[1473181878383], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473181878348]}
09-06 19:11:18.383  1032  7152 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-06 19:11:18.383  1032  7152 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,09-06 19:11:18.451  1032  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-06 19:11:18.451  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:18.451  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:11:18.452  1032  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:11:18.452  1032  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-06 19:11:18.452  1032  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-06 19:11:18.452  1032  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:11:18.452  1032  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:11:18.452  1032  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-06 19:11:18.452  1032  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-06 19:11:18.452  1032  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-06 19:11:18.452  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:18.452  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:11:18.452  1032  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:11:18.452  1603  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 19:11:18.452  1032  1545 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:18.453  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-06 19:11:18.453  1878  1878 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:18.453  1878  1878 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 19:11:18.454  1032  1538 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:18.454  1032  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-06 19:11:18.454  1603  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 19:11:18.448  7193  7193 W dsqn    : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:11:18.448  7193  7193 W dsqn    : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:11:18.456  1817  7188 I CheckinService: Preparing to send checkin request
09-06 19:11:18.457  1817  7188 I EventLogService: Accumulating logs since 1473181729950
09-06 19:11:18.457  7154  7154 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 19:11:18.457  7154  7154 D Weather.Utils: 2 : All the weather widget is gone.
09-06 19:11:18.459  7154  7154 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 19:11:18.475  7154  7154 D WeatherAncestor: connectivity changed - connection : true
09-06 19:11:18.475  7154  7154 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-06 19:11:18.478  7193  7193 E DSQN    : DSQN ssw
,09-06 19:11:18.481  7154  7154 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 19:11:18.481  7154  7154 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 19:11:18.481  7154  7154 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,09-06 19:11:18.490  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 19:11:18.491  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:18.491  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:18.499  7154  7154 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 19:11:18.499  7154  7154 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:11:18
09-06 19:11:18.542  1032  2049 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7211 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:11:18.546  1032  2049 I ActivityManager: Killing 2219:com.lge.music/u0a34 (adj 15): empty #17
09-06 19:11:18.561   331  3957 V AudioFlinger: 2219 died, releasing its sessions
09-06 19:11:18.561   331  3957 V AudioFlinger:  pid 1878 @ 0
09-06 19:11:18.561   331  3957 V AudioFlinger:  pid 3357 @ 1
09-06 19:11:18.561   331  3957 V AudioFlinger:  pid 3357 @ 2
,09-06 19:11:18.588  1032  7153 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-06 19:11:18.588  1032  7153 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-06 19:11:18.588  1032  7153 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,09-06 19:11:18.588  1032  7153 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-06 19:11:18.589  1032  7153 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-06 19:11:18.589  1032  7153 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-06 19:11:18.589  1032  7153 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-06 19:11:18.589  1032  7153 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-06 19:11:18.589  1032  7153 D DhcpStateMachine: RunningState
09-06 19:11:18.590  1817  7188 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-06 19:11:18.591  1032  2003 W libprocessgroup: failed to open /acct/uid_10034/pid_2219/cgroup.procs: No such file or directory
,09-06 19:11:18.669   278   319 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-06 19:11:18.669   278   319 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-06 19:11:18.669   278   319 W Vold    : Returning OperationFailed - no handler for errno 0
09-06 19:11:18.671  7211  7233 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-06 19:11:18.680   278   319 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-06 19:11:18.680   278   319 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-06 19:11:18.680   278   319 W Vold    : Returning OperationFailed - no handler for errno 0
09-06 19:11:18.681  7211  7233 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-06 19:11:18.692   278   319 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-06 19:11:18.692   278   319 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-06 19:11:18.692   278   319 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:11:18.693  7211  7237 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-06 19:11:18.698   278   319 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-06 19:11:18.698   278   319 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-06 19:11:18.698   278   319 W Vold    : Returning OperationFailed - no handler for errno 0
09-06 19:11:18.699  7211  7237 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-06 19:11:18.715  1032  2028 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7238 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-06 19:11:18.762  7238  7238 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-06 19:11:18.762  7238  7238 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-06 19:11:18.780  7238  7238 I MultiDex: VM with version 2.1.0 has multidex support
09-06 19:11:18.780  7238  7238 I MultiDex: install
09-06 19:11:18.780  7238  7238 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-06 19:11:18.901  7211  7211 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-06 19:11:18.909  7211  7211 I LibraryLoader: Loading: webviewchromium
09-06 19:11:18.912  7211  7211 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 7158-7162)
09-06 19:11:18.912  7211  7211 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-06 19:11:18.916  7211  7211 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {27037903}
09-06 19:11:18.918  7211  7211 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 19:11:18.918  7211  7211 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-06 19:11:18.928  7211  7211 I BrowserStartupController: Initializing chromium process, renderers=0
,09-06 19:11:18.930  7211  7211 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 19:11:18.940   331   331 V AudioPolicyService: registerClient() client 0xb558a460, uid 10093
09-06 19:11:18.950  7211  7275 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-06 19:11:18.955  7211  7211 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-06 19:11:18.956  1032  1781 I art     : Explicit concurrent mark sweep GC freed 105644(5MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/64MB, paused 3.152ms total 170.827ms
09-06 19:11:18.956  7211  7211 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-06 19:11:18.956  7211  7211 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-06 19:11:18.963  7238  7238 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,09-06 19:11:18.974  7211  7211 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 19:11:18.974  7211  7211 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 19:11:18.974  7211  7211 I Adreno-EGL: Build Date: 12/12/14 금
09-06 19:11:18.974  7211  7211 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 19:11:18.974  7211  7211 I Adreno-EGL: Remote Branch: 
09-06 19:11:18.974  7211  7211 I Adreno-EGL: Local Patches: 
09-06 19:11:18.974  7211  7211 I Adreno-EGL: Reconstruct Branch: 
,09-06 19:11:19.056  7211  7211 I NSApplication: Starting up...
,09-06 19:11:19.121  1032  1048 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7288 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-06 19:11:19.122  1032  1048 I ActivityManager: Killing 6125:com.android.vending/u0a44 (adj 15): empty #17
,09-06 19:11:19.181  1032  1538 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:11:19.181  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:11:19.181  1032  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:11:19.182  1032  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:11:19.182  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:11:19.182  1032  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:11:19.182  1032  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
09-06 19:11:19.182  1032  1545 D ConnectivityService: identical MTU - not setting
09-06 19:11:19.183  1032  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-06 19:11:19.183  1032  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-06 19:11:19.183  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:19.183  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:11:19.183  1032  1545 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-06 19:11:19.184  1603  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-06 19:11:19.202  1032  1929 W libprocessgroup: failed to open /acct/uid_10044/pid_6125/cgroup.procs: No such file or directory
,09-06 19:11:19.211  1032  2049 D WifiServiceImplEx: setWifiEnabled: false pid=6732, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 19:11:19.211  1032  2049 D WifiService: setWifiEnabled: false pid=6732, uid=10118
09-06 19:11:19.211  1032  2049 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-06 19:11:19.223  1032  1538 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-06 19:11:19.223  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-06 19:11:19.223  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 19:11:19.224  1032  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-06 19:11:19.224  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:11:19.224  1032  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-06 19:11:19.224  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-06 19:11:19.224  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-06 19:11:19.224  1032  1538 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-06 19:11:19.224  1032  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:11:19.224  1032  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 19:11:19.224  1032  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 19:11:19.224  1032  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 19:11:19.228  1032  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 19:11:19.228  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 19:11:19.228  7082  7082 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 19:11:19.228  1032  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:19.229  1032  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 19:11:19.229  1032  1538 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:11:19.229  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:19.229  1032  1538 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:11:19.229  1032  7153 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:19.229   327   899 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:11:19.240  7288  7288 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:11:19.261  1032  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-06 19:11:19.261  1032  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
09-06 19:11:19.262  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-06 19:11:19.264  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:19.264  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-06 19:11:19.265  1969  1969 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-06 19:11:19.267  1032  1537 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:19.267  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:19.267  1032  1537 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@11f06c96
09-06 19:11:19.267  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:19.267  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:19.267  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:11:19.268  1032  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:19.268  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:19.268  1032  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:19.269  1032  1538 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 19:11:19.269  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:19.270  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-06 19:11:19.272  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:19.272  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:19.272  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-06 19:11:19.272  7305  7305 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
09-06 19:11:19.272  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 1
09-06 19:11:19.273  1032  1032 D RttService: SCAN_AVAILABLE : 1
09-06 19:11:19.274  1032  1537 D LGWifiP2pService: P2pDisablingState
09-06 19:11:19.274  1032  1537 D LGWifiP2pService: P2pDisablingState{ when=-8ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:19.274  1032  1537 D LGWifiP2pService: p2p socket connection lost
09-06 19:11:19.275  1032  1537 D LGWifiP2pService: P2pDisabledState
09-06 19:11:19.275  1032  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-06 19:11:19.275  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 19:11:19.275  7082  7082 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 19:11:19.276  1032  1537 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:19.276  1032  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:19.276  1032  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 19:11:19.276  1032  1538 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:11:19.276  1032  1538 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:11:19.277  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-06 19:11:19.278  1969  1969 D WfdsService: WifiP2pState is changed : false
09-06 19:11:19.278  1032  1557 D RttService: EnabledState got{ when=-5ms what=160513 target=com.android.internal.util.S,tateMachine$SmHandler }
09-06 19:11:19.278  1969  2312 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-06 19:11:19.278  1969  2312 D WfdsService: Set the WFDS Monitor: false
09-06 19:11:19.279  1969  2312 D WfdsMonitor: WFDS Monitor is stopped
09-06 19:11:19.279  1969  2312 D WfdsService: STATE : WfdsDisabledState - enter
09-06 19:11:19.279  1969  7088 D CtrlSupplicant: Received on exit socket, terminate
09-06 19:11:19.279  1969  7088 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-06 19:11:19.279  1969  7088 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-06 19:11:19.279  1969  7088 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-06 19:11:19.279  1969  2314 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-06 19:11:19.279  1969  2312 W WfdsService: DefaultState - msg [9445378] is not handled
09-06 19:11:19.280  1032  1556 D WifiScanningService: DefaultState got{ when=-7ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:11:19.290  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:19.290  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:11:19.292  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:19.306  1032  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-06 19:11:19.306   327   899 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:11:19.306  1032  1545 D DSQN    : disableDataServiceNotify
,09-06 19:11:19.306  1032  1545 D DSQN    : stop dsqn bin
09-06 19:11:19.307  1032  1538 D WifiNative-p2p0: doBoolean: TERMINATE
09-06 19:11:19.308  1032  1538 D WifiNative-p2p0: TERMINATE: returned true
09-06 19:11:19.308  1032  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:11:19.308  1032  1538 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:11:19.308  1032  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:11:19.308  1032  1032 D WifiHS20: hidePasspointNotification off =false
,09-06 19:11:19.311  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-06 19:11:19.311  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:11:19.312  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:19.312  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:19.312  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,09-06 19:11:19.312  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:19.314  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-06 19:11:19.314  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:11:19.314  1032  1032 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-06 19:11:19.315  1032  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-06 19:11:19.315  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:19.315  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:11:19.315  1032  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:11:19.316  1032  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-06 19:11:19.316  1603  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-06 19:11:19.316  6732  6732 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:11:19.316  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:11:19.316  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:19.316  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:19.316  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:11:19.316  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:11:19.316  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:11:19.316  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:11:19.316  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:11:19.316  6732  6732 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:11:19.316  6732  6732 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:11:19.316  1032  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-06 19:11:19.316  1032  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-06 19:11:19.316  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:11:19.316  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-06 19:11:19.316  1032  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:19.316  1032  7152 D NetworkMo,nitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:19.316  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:11:19.317  1032  7152 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:19.317  1032  7152 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-06 19:11:19.317  6732  6732 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:11:19.317  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:11:19.317  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:19.317  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:19.317  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:11:19.317  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:11:19.317  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:11:19.317  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:11:19.317  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:11:19.317  6732  6732 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:11:19.317  6732  6732 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:11:19.322  1032  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-06 19:11:19.323  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-06 19:11:19.323  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 19:11:19.323  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 19:11:19.323  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-06 19:11:19.325  1032  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:19.325  1032  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:19.325  1032  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:19.326  1032  1538 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:19.326  1032  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:11:19.326  1032  1545 D NetworkManagementService: Removing idletimer
09-06 19:11:19.326  1032  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:19.326  1032  1545 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-06 19:11:19.326  1878  1878 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:19.327  1878  1878 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 19:11:19.327  1032  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-06 19:11:19.328  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-06 19:11:19.328  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 19:11:19.328  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 19:11:19.328  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-06 19:11:19.334  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:11:19.346  7305  7305 I dex2oat : dex2oat took 73.775ms (threads: 4)
09-06 19:11:19.350  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 19:11:19.351  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:19.352  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:19.354  7238  7255 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 19:11:19.354  7238  7255 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 19:11:19.354  7238  7255 I Adreno-EGL: Build Date: 12/12/14 금
09-06 19:11:19.354  7238  7255 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 19:11:19.354  7238  7255 I Adreno-EGL: Remote Branch: 
09-06 19:11:19.354  7238  7255 I Adreno-EGL: Local Patches: 
09-06 19:11:19.354  7238  7255 I Adreno-EGL: Reconstruct Branch: 
,09-06 19:11:19.365  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 19:11:19.366  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:19.367  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:11:19.403  7082  7082 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-06 19:11:19.403  7082  7082 I wpa_supplicant: monitor socket send errors count : 1
09-06 19:11:19.403  7082  7082 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1969-4\x00 that cannot receive messages
,09-06 19:11:19.405  1032  7085 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-06 19:11:19.406  1032  7085 D WifiMonitor: Dropping event because (p2p0) is stopped
09-06 19:11:19.437  1032  7153 D DhcpStateMachine: StoppedState
09-06 19:11:19.437  1032  7153 D DhcpStateMachine: StoppedState{ when=-161ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:19.437  1032  1538 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-06 19:11:19.437  1032  1538 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,09-06 19:11:19.443  7082  7082 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:11:19.444  1032  7085 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-06 19:11:19.444  1032  7085 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:11:19.444  1032  7085 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:11:19.444  1032  7085 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-06 19:11:19.445  1032  1538 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=207678
09-06 19:11:19.445  1032  7085 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:11:19.445  7082  7082 W wpa_supplicant: USIM:  scard_deinit function
09-06 19:11:19.445  1032  1538 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=207679
09-06 19:11:19.445  1032  7085 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:11:19.446  1032  1538 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=207679  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-06 19:11:19.446  1032  1538 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=207679  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-06 19:11:19.447  1032  1094 D Tethering: InitialState.processMessage what=4
09-06 19:11:19.449  1032  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:11:19.450  1032  1538 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:11:19.450  1032  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-06 19:11:19.455  1032  1545 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
09-06 19:11:19.528  6402  6402 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-06 19:11:19.531  7238  7255 D LgDataFeature: LgDataFeature() Constructor: none
,09-06 19:11:19.531  7238  7255 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 19:11:19.531  6402  6871 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-06 19:11:19.546  2201  2201 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:11:19.552  7019  7019 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-06 19:11:19.552  7019  7019 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:19.552  7019  7019 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 19:11:19.552  7019  7019 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-06 19:11:19.554  7019  7019 I AppUp4:CustModeStarterReceiver: onReceive
09-06 19:11:19.556  7019  7019 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@26a68538
09-06 19:11:19.556  7019  7019 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 19:11:19.556  7019  7019 D AppUp4:CustFacade: isPhone : true
09-06 19:11:19.557  7019  7019 D AppUp4:CustModeStarterReceiver: begin check event
09-06 19:11:19.557  7019  7019 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-06 19:11:19.564  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:19.564  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:11:19.566  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-06 19:11:19.568  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:11:19.573  7064  7064 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-06 19:11:19.575  4326  7327 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 19:11:19.578  4326  7328 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:19.579  4326  7328 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-06 19:11:19.582  7082  7082 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-06 19:11:19.582  1032  7085 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-06 19:11:19.583  1032  7085 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
09-06 19:11:19.583  1032  7085 D WifiMonitor: Disconnecting from the supplicant, no more events
09-06 19:11:19.583  1032  1538 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
09-06 19:11:19.590  7064  7330 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:11:19.596  3357  3357 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 19:11:19.596  3357  3357 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:19.596  3357  3357 I LgeMiscReceiver: networkInfo.isConnected() = false
09-06 19:11:19.600  7094  7094 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-06 19:11:19.600  7094  7094 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-06 19:11:19.606  6941  7335 W FormManager: Network not available. Please check & try again.
,09-06 19:11:19.613  7154  7154 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:11:19
,09-06 19:11:19.615  7154  7154 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 19:11:19.615  7154  7154 D Weather.Utils: 2 : All the weather widget is gone.
09-06 19:11:19.616  7154  7154 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 19:11:19.616  7154  7154 D WeatherAncestor: connectivity changed - connection : true
09-06 19:11:19.616  7154  7154 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@17bc6a76
09-06 19:11:19.616  7154  7154 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 19:11:19.616  7154  7154 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 19:11:19.617  7154  7154 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-06 19:11:19.617  7154  7154 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 19:11:19.617  7154  7154 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:11:19
,09-06 19:11:19.621  6941  7336 V FormManager: Network unavailable.
09-06 19:11:19.627  6941  7336 V FormManager: Network unavailable.
,09-06 19:11:19.642  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 19:11:19.642  6829  6829 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,09-06 19:11:19.642  6829  6829 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 19:11:19.642  6829  6829 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-06 19:11:19.642  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-06 19:11:19.643  6829  6829 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,09-06 19:11:19.643  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-06 19:11:19.643  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 19:11:19.643  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 19:11:19.643  6829  6829 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 19:11:19.643  6829  6829 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-06 19:11:19.648  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:11:19.651  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:11:19.656  6941  7338 W FormManager: Network not available. Please check & try again.
09-06 19:11:19.660  6941  7339 V FormManager: Network unavailable.
09-06 19:11:19.661  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:19.665  6941  7339 V FormManager: Network unavailable.
09-06 19:11:19.677  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 19:11:19.681  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 19:11:19.684  1032  1538 D WifiOffDelayIfNotUsed: stopMonitoring
09-06 19:11:19.684  1032  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:11:19.684  1032  1538 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:11:19.684  1032  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:11:19.684  1969  1969 D WfdsService: Supplicant Connection state is changed : false
09-06 19:11:19.685  1969  2312 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-06 19:11:19.685  1969  2312 D WfdsService: Set the WFDS Monitor: false
09-06 19:11:19.685  1969  2312 D WfdsMonitor: WFDS Monitor is stopped
09-06 19:11:19.685  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:19.686  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-06 19:11:19.688  1032  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-06 19:11:19.688  1032  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-06 19:11:19.689  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,09-06 19:11:19.689  6732  6732 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:11:19.689  2469  2469 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:19.689  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:11:19.689  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:19.689  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:19.689  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:11:19.689  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:11:19.689  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:11:19.689  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:11:19.689  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:11:19.690  6732  6732 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:11:19.690  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:11:19.690  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:19.690  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:19.690  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:11:19.690  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:11:19.690  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:11:19.690  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:11:19.690  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:11:19.693  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:19.695  6941  7342 V FormManager: Network unavailable.
,09-06 19:11:19.704  6941  7341 W FormManager: Network not available. Please check & try again.
09-06 19:11:19.705  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:11:19.705  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:11:19.706  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:11:19.707  6941  7342 V FormManager: Network unavailable.
09-06 19:11:19.710  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:11:19.716  7238  7255 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 19:11:19.716  7238  7255 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 19:11:19.716  7238  7255 I Adreno-EGL: Build Date: 12/12/14 금
09-06 19:11:19.716  7238  7255 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 19:11:19.716  7238  7255 I Adreno-EGL: Remote Branch: 
09-06 19:11:19.716  7238  7255 I Adreno-EGL: Local Patches: 
09-06 19:11:19.716  7238  7255 I Adreno-EGL: Reconstruct Branch: 
,09-06 19:11:19.718  4326  7343 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-06 19:11:19.719  4326  7344 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:11:19.719  4326  7344 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 19:11:19.750  1032  1968 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7345 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-06 19:11:19.797  7238  7255 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 19:11:19.797  7238  7255 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 19:11:19.797  7238  7255 I Adreno-EGL: Build Date: 12/12/14 금
09-06 19:11:19.797  7238  7255 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 19:11:19.797  7238  7255 I Adreno-EGL: Remote Branch: 
09-06 19:11:19.797  7238  7255 I Adreno-EGL: Local Patches: 
09-06 19:11:19.797  7238  7255 I Adreno-EGL: Reconstruct Branch: 
,09-06 19:11:19.834  7345  7345 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-06 19:11:19.834  7345  7345 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-06 19:11:19.840  7345  7345 V [BNRBootReceiver]: Boot Receiver Return
09-06 19:11:19.840  7345  7345 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-06 19:11:19.843  6402  6402 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:11:19.850  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:11:19.855  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:19.861  1032  1423 D PowerManagerServiceEx: acquireWakeLockInternal: lock=520497475, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
09-06 19:11:19.870  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:11:19.870  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:11:19.873  6917  6917 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:11:19.876  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-06 19:11:19.879  6829  6829 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-06 19:11:19.883  6402  6402 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:11:19.888  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:11:19.899  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:19.904   327  7364 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-06 19:11:19.905  1817  7188 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
09-06 19:11:19.905  1032  1092 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-06 19:11:19.907  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 19:11:19.908  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:11:19.912  6917  6917 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:11:19.912  1817  7188 I CheckinService: active receiver: disabled
,09-06 19:11:19.930  6402  6402 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:11:19.949  2680  2680 D [Concierge]Service: onStartCommand(). Type : 9
,09-06 19:11:19.954  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 19:11:19.959  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:19.978  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 19:11:19.978  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:11:19.980  6917  6917 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:11:19.986  6402  6402 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:11:19.997  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:11:20.005  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 19:11:20.013  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:11:20.014  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:11:20.015  6917  6917 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 19:11:20.020  6402  6402 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:11:20.029  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:11:20.040  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:20.052  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:11:20.053  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:11:20.054  6917  6917 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 19:11:20.060  6402  6402 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:11:20.075  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:11:20.090  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 19:11:20.105  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:11:20.106  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:11:20.107  6917  6917 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 19:11:20.117  6402  6402 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:11:20.138  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:11:20.153  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 19:11:20.167  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-06 19:11:20.168  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:11:20.169  6917  6917 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 19:11:20.191  6402  6402 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:11:20.212  6623  7013 D UEI.SmartControl: Internal timer expired: 2
09-06 19:11:20.213  6623  7013 D UEI.SmartControl: unbind internal service
09-06 19:11:20.215  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:11:20.229  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:20.244  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:11:20.245  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:11:20.251  6917  6917 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:11:20.260  6402  6402 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:11:20.284  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:11:20.298  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:20.312  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:11:20.313  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:11:20.315  6917  6917 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 19:11:20.320  6623  7007 D serial_port: close(fd = 24)
09-06 19:11:20.323  6623  7007 I UEI.SmartControl: Serial port is closed.
09-06 19:11:20.326  6402  6402 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:11:20.334  6873  6873 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-06 19:11:20.346  1032  1544 D WifiService: New client listening to asynchronous messages
09-06 19:11:20.347  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:11:20.352  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:11:20.362  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 19:11:20.374  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:11:20.375  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:11:20.376  6917  6917 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-06 19:11:20.379  6917  6917 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-06 19:11:20.379  6917  6917 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-06 19:11:20.388  6402  6402 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:11:20.400  6873  6873 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-06 19:11:20.403  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 19:11:20.412  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:11:20.424  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:20.436  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:11:20.437  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:11:20.439  6917  6917 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-06 19:11:20.441  6917  6917 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-06 19:11:20.442  6917  6917 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-06 19:11:20.448  1032  2049 I ActivityManager: Killing 6851:com.lge.lifetracker/u0a37 (adj 15): empty #17
09-06 19:11:20.493  1032  1949 W libprocessgroup: failed to open /acct/uid_10037/pid_6851/cgroup.procs: No such file or directory
,09-06 19:11:20.500  2201  2201 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-06 19:11:20.516  2201  2201 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-06 19:11:20.517  2201  2201 D c       : Getting all permits...
09-06 19:11:20.517  2201  2201 D a       : Opening database...
09-06 19:11:20.526  2201  2201 D a       : Opening database auth.proximity.permit_store...
,09-06 19:11:20.528  2201  2201 D a       : Closing database...
09-06 19:11:20.546  6402  6402 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:11:20.554  6873  6873 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 19:11:20.554  6873  6873 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:11:20.554  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:11:20.562  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:11:20.577  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:20.590  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:11:20.591  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:11:20.595  6917  6917 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:11:20.603  6402  6402 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:11:20.612  6873  6873 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 19:11:20.612  6873  6873 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:11:20.612  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 19:11:20.618  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:11:20.624  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:20.635  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:11:20.635  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:11:20.638  6917  6917 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-06 19:11:20.644  6402  6402 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:11:20.647  6873  6873 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-06 19:11:20.647  6873  6873 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:11:20.647  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:11:20.653  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:11:20.661  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:20.672  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:11:20.672  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-06 19:11:20.674  6917  6917 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-06 19:11:20.692  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 19:11:20.699  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 19:11:20.706  6941  7372 W FormManager: Network not available. Please check & try again.
,09-06 19:11:20.713  6941  7373 V FormManager: Network unavailable.
09-06 19:11:20.714  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:20.726  6941  7373 V FormManager: Network unavailable.
,09-06 19:11:20.739  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:11:20.739  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:11:20.741  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-06 19:11:20.744  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:11:20.752  6873  6873 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,09-06 19:11:20.752  6873  6873 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-06 19:11:20.752  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:11:20.752  4326  7374 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 19:11:20.756  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 19:11:20.758  4326  7375 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:11:20.758  4326  7375 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-06 19:11:20.765  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 19:11:20.777  6941  7377 W FormManager: Network not available. Please check & try again.
,09-06 19:11:20.783  6941  7378 V FormManager: Network unavailable.
09-06 19:11:20.784  6917  6917 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
09-06 19:11:20.784  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:495
09-06 19:11:20.786  1032  1032 D PowerManagerServiceEx: releaseWakeLockInternal: lock=520497475 [*alarm*], flags=0x0
09-06 19:11:20.791  2201  2201 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-06 19:11:20.793  6941  7378 V FormManager: Network unavailable.
,09-06 19:11:20.975  1032  1538 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:8098447] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-06 19:11:20.977  1032  1538 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:8098449] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-06 19:11:21.264  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:11:21.279  1032  1094 D Tethering: MasterInitialState.processMessage what=3
09-06 19:11:21.288  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:11:21.292  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:21.296  1032  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:21.298  6402  6402 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-06 19:11:21.300  6402  6871 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-06 19:11:21.311  5786  5786 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-06 19:11:21.331  2201  2201 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:11:21.350  7019  7019 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-06 19:11:21.350  7019  7019 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:21.351  7019  7019 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 19:11:21.351  7019  7019 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-06 19:11:21.355  7019  7019 I AppUp4:CustModeStarterReceiver: onReceive
09-06 19:11:21.359  7019  7019 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@26a68538
09-06 19:11:21.359  7019  7019 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 19:11:21.359  7019  7019 D AppUp4:CustFacade: isPhone : true
09-06 19:11:21.360  7019  7019 D AppUp4:CustModeStarterReceiver: begin check event
09-06 19:11:21.360  7019  7019 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-06 19:11:21.365  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:21.365  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:11:21.367  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-06 19:11:21.372  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:11:21.380  7064  7064 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-06 19:11:21.403  4326  7387 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-06 19:11:21.410  7064  7386 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:21.419  4326  7388 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:21.419  4326  7388 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-06 19:11:21.434  6941  7389 W FormManager: Network not available. Please check & try again.
,09-06 19:11:21.434  1032  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-06 19:11:21.440  6941  7390 V FormManager: Network unavailable.
09-06 19:11:21.447  3357  3357 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 19:11:21.447  3357  3357 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:21.447  3357  3357 I LgeMiscReceiver: networkInfo.isConnected() = true
09-06 19:11:21.447  3357  3357 D PhoneState: setPdpRejectCasuse : false
,09-06 19:11:21.450  6941  7390 V FormManager: Network unavailable.
,09-06 19:11:21.451  7094  7094 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-06 19:11:21.451  7094  7094 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-06 19:11:21.465  7154  7154 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:11:21
,09-06 19:11:21.466  7154  7154 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 19:11:21.466  7154  7154 D Weather.Utils: 2 : All the weather widget is gone.
09-06 19:11:21.467  7154  7154 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 19:11:21.467  7154  7154 D WeatherAncestor: connectivity changed - connection : true
09-06 19:11:21.467  7154  7154 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@17bc6a76
09-06 19:11:21.468  7154  7154 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 19:11:21.468  7154  7154 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 19:11:21.468  7154  7154 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-06 19:11:21.468  7154  7154 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 19:11:21.468  7154  7154 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:11:21
09-06 19:11:22.225  1032  2004 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:22.226  1032  2004 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-06 19:11:22.259  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-06 19:11:22.262  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:11:22.262  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-06 19:11:22.263  1032  1094 D BluetoothManagerService: Message: 1
09-06 19:11:22.263  1032  1094 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,09-06 19:11:22.294  1032  1094 D BluetoothManagerService: Message: 20
09-06 19:11:22.294  1032  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@380fa301:true
,09-06 19:11:22.297  6970  6970 D BluetoothAdapterState: make
09-06 19:11:22.303  6970  6970 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-06 19:11:22.303  6970  6970 I bluedroid-qcom: init
09-06 19:11:22.304  6970  7419 I BluetoothAdapterState: Entering OffState
09-06 19:11:22.305  6970  6970 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-06 19:11:22.305  6970  6970 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-06 19:11:22.305  6970  6970 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-06 19:11:22.305  6970  6970 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-06 19:11:22.305  6970  6970 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-06 19:11:22.307  6970  6970 I bluedroid-qcom: get_profile_interface socket
09-06 19:11:22.307  6970  6970 I bluedroid-qcom: get_profile_interface map_client
,09-06 19:11:22.312  6970  7423 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-06 19:11:22.317  6970  7423 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-06 19:11:22.308  7422  7422 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:11:22.308  7422  7422 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:11:22.325  7422  7422 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-06 19:11:22.325  7422  7422 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-06 19:11:22.326  7422  7422 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-06 19:11:22.328  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:22.331  1032  1094 D Tethering: MasterInitialState.processMessage what=3
09-06 19:11:22.332  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:22.334  7422  7422 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-06 19:11:22.340  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:11:22.344  7422  7422 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-06 19:11:22.344  7422  7422 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-06 19:11:22.345  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:22.353  1032  1094 D Tethering: MasterInitialState.processMessage what=3
,09-06 19:11:22.358  6970  7423 D BluetoothAdapterProperties: Name is: G3
09-06 19:11:22.364  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:22.366  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:11:22.369  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-06 19:11:22.369  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
09-06 19:11:22.370  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-06 19:11:22.370  1032  1094 D BluetoothManagerService: Message: 40
09-06 19:11:22.370  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-06 19:11:22.371  6970  6987 I bluedroid-qcom: config_hci_snoop_log
09-06 19:11:22.372  1032  1094 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-06 19:11:22.372  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-06 19:11:22.376  6402  6402 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-06 19:11:22.379  6402  6871 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-06 19:11:22.387  1032  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:22.390  1032  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:22.394  5786  5786 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-06 19:11:22.402  1032  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:22.402  1032  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:22.402  6970  7419 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-06 19:11:22.403  6970  7419 D BluetoothAdapterProperties: Setting state to 11
09-06 19:11:22.403  6970  7419 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-06 19:11:22.404  5786  5786 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-06 19:11:22.405  1032  1094 D BluetoothManagerService: Message: 60
09-06 19:11:22.405  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-06 19:11:22.405  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-06 19:11:22.409  6970  7419 I LGBluetoothServiceJni: classInitNative: succeeds
,09-06 19:11:22.413  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:22.414  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:22.415  6829  6829 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-06 19:11:22.416  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:11:22.420  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:22.428  6970  6970 V BluetoothPbapReceiver: PbapReceiver onReceive 
,09-06 19:11:22.429  6970  6970 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:22.429  6970  6970 V BluetoothPbapReceiver: ***********state = 11
09-06 19:11:22.432  2201  2201 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:22.433  6970  7419 D BluetoothBondStateMachine: make
09-06 19:11:22.441  6970  7419 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17bc6a76
09-06 19:11:22.441  6970  7419 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-06 19:11:22.441  6970  7419 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17bc6a76
09-06 19:11:22.441  6970  7419 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
,09-06 19:11:22.442  6970  7419 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-06 19:11:22.443  6970  7441 I BluetoothBondStateMachine: StableState(): Entering Off State
09-06 19:11:22.445  2201  2201 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:11:22.446  6970  7419 E BluetoothAdapterService: File transfer profiles supported!!
,09-06 19:11:22.490  1032  2049 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7443 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-06 19:11:22.501  6970  6970 D HeadsetService: Received start request. Starting profile...
09-06 19:11:22.502  6970  6970 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 19:11:22.502  6970  6970 D LGBluetoothHfpAdapter: Version 1.6
,09-06 19:11:22.505  6970  6970 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-06 19:11:22.506  6970  6970 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 19:11:22.507  6970  6970 D HeadsetStateMachine: make
09-06 19:11:22.509  6970  7419 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:11:22.512   359   359 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.298ms total 20.989ms
09-06 19:11:22.528  6970  7419 E BluetoothAdapterService: File transfer profiles supported!!
,09-06 19:11:22.524  7019  7019 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-06 19:11:22.531  7019  7019 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:22.532  7019  7019 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 19:11:22.532  7019  7019 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-06 19:11:22.532   359   359 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 696us total 19.365ms
09-06 19:11:22.537  6970  7419 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:11:22.541  6970  7419 E BluetoothAdapterService: File transfer profiles supported!!
,09-06 19:11:22.543  7019  7019 I AppUp4:CustModeStarterReceiver: onReceive
09-06 19:11:22.545  6970  6970 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:11:22.545  6970  6970 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 19:11:22.547  6970  7419 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:11:22.550  6970  6970 D HeadsetStateMachine: max_hf_connections = 1
09-06 19:11:22.550  6970  6970 I bluedroid-qcom: get_profile_interface handsfree
09-06 19:11:22.552   359   359 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 449us total 19.192ms
09-06 19:11:22.552  6970  6970 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,09-06 19:11:22.553   331  1382 V AudioPolicyService: registerClient() client 0xb1022dc0, uid 1002
09-06 19:11:22.554   331  3957 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-06 19:11:22.554   331  3957 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 19:11:22.554   331  3957 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 19:11:22.554  6970  6970 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-06 19:11:22.555  6970  7419 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:11:22.555   331   331 V AudioFlinger: registerClient() client 0xb10190b8, pid 6970
09-06 19:11:22.555   331  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:11:22.555   331  1377 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:11:22.555  6970  6970 V ToneGenerator: Create Track: 0xb4928a80
09-06 19:11:22.555  6970  6970 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-06 19:11:22.556  6970  6970 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-06 19:11:22.556  1032  1048 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:11:22.556  1032  1048 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:11:22.556   331  1381 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-06 19:11:22.556   331  1381 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-06 19:11:22.556   331  1381 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 19:11:22.556   331  1381 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 19:11:22.556  6970  6970 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-06 19:11:22.556  6970  6986 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:11:22.556  6970  6986 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-06 19:11:22.556  3357  3373 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:11:22.556  3357  3373 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:11:22.556   331  3957 I AudioFlinger: isAudioPlaybackHookOn() false
09-06 19:11:22.556   331   331 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-06 19:11:22.556   331   331 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-06 19:11:22.557   331   331 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 19:11:22.557  1878  2362 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:11:22.557   331   331 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 19:11:22.557  1878  2362 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:11:22.557  1603  2673 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:11:22.557  1603  2673 V AudioSystem: ioConfigChanged() opening already existing output! 4
,09-06 19:11:22.557   331  1376 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:11:22.557   331  1376 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:11:22.558  1032  1967 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:11:22.558  1032  1967 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:11:22.558  3357  3372 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:11:22.558  3357  3372 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:11:22.558  6970  6986 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:11:22.558  6970  6986 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-06 19:11:22.558  6970  6970 V AudioSystem: getLatency() output 2, latency 50
09-06 19:11:22.558  6970  6970 V AudioSystem: getFrameCount() output 2, frameCount 960
09-06 19:11:22.558  6970  6970 V AudioTrack: createTrack_l() output 2 afLatency 50
09-06 19:11:22.558   331  1381 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-06 19:11:22.558   331  1381 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-06 19:11:22.558   331  1381 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-06 19:11:22.558   331  1381 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-06 19:11:22.558   331  1381 V AudioFlinger: createTrack() lSessionId: 22
09-06 19:11:22.559  1878  1893 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:11:22.559  1878  1893 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:11:22.559  6970  6970 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-06 19:11:22.560   331  1381 V AudioFlinger: acquiring 22 from 6970, for 6970
09-06 19:11:22.560   331  1381 V AudioFlinger:  added new entry for 22
09-06 19:11:22.560  6970  6970 V ToneGenerator: ToneGenerator INIT OK, time: 210810
09-06 19:11:22.560  6970  6970 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17bc6a76
09-06 19:11:22.560  1603  2557 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:11:22.561  1603  2557 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:11:22.561  7019  7019 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@26a68538
09-06 19:11:22.561  7019  7019 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 19:11:22.561  6970  7458 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-06 19:11:22.561  7019  7019 D AppUp4:CustFacade: isPhone : true
09-06 19:11:22.561  6970  7458 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 19:11:22.561  6970  7458 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 19:11:22.561  6970  7458 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-06 19:11:22.561   331  1382 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6970
09-06 19:11:22.561  7019  7019 D AppUp4:CustModeStarterReceiver: begin check event
09-06 19:11:22.561  6970  6970 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17bc6a76
09-06 19:11:22.561   331  1382 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-06 19:11:22.562   331  1382 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-06 19:11:22.562   331  1382 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-06 19:11:22.562   331  1382 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-06 19:11:22.562   331  1382 V voice   : voice_set_parameters: exit with code(0)
09-06 19:11:22.562   331  1382 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-06 19:11:22.562   331  1382 V msm8974_platform:, platform_set_parameters: enter: bt_samplerate=8000
09-06 19:11:22.562  7019  7019 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-06 19:11:22.562   331  1382 V msm8974_platform: platform_set_parameters: exit with code(0)
09-06 19:11:22.562   331  1382 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-06 19:11:22.562   331  1382 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-06 19:11:22.562   331  1382 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-06 19:11:22.563  6970  6970 D A2dpService: Received start request. Starting profile...
09-06 19:11:22.563  6970  6970 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-06 19:11:22.564  6970  6970 V Avrcp   : make
09-06 19:11:22.564  6970  6970 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-06 19:11:22.564  6970  6970 I bluedroid-qcom: get_profile_interface avrcp
09-06 19:11:22.564  6970  7458 V ToneGenerator: ToneGenerator destructor
09-06 19:11:22.564  6970  7458 V ToneGenerator: stopTone
09-06 19:11:22.564  6970  7458 V ToneGenerator: Delete Track: 0xb4928a80
,09-06 19:11:22.569  6970  7458 V AudioTrack: ~AudioTrack, releasing session id from 6970 on behalf of 6970
09-06 19:11:22.569   331  3957 V AudioFlinger: releasing 22 from 6970 for 6970
09-06 19:11:22.569   331  3957 V AudioFlinger:  decremented refcount to 0
09-06 19:11:22.569   331  3957 V AudioFlinger: purging stale effects
09-06 19:11:22.569   331  3957 V AudioPolicyService: AudioCommandThread() adding release output 2
09-06 19:11:22.569   331  3957 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-06 19:11:22.570   331  1257 V AudioPolicyService: AudioCommandThread() waking up
09-06 19:11:22.570   331  1257 V AudioPolicyService: AudioCommandThread() processing release output 2
09-06 19:11:22.570   331  1257 V AudioPolicyManager: releaseOutput() 2
09-06 19:11:22.570   331  1257 V AudioPolicyService: AudioCommandThread() going to sleep
09-06 19:11:22.570   331  3957 V AudioFlinger: PlaybackThread::Track destructor
09-06 19:11:22.570   331  3957 V AudioFlinger: removeClient_l() pid 6970, calling pid 331
09-06 19:11:22.571  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:22.571  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-06 19:11:22.573  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:11:22.574  6970  7419 V LGMDMManager: Create singleton instance
09-06 19:11:22.575  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:11:22.577  6970  6970 V AudioManager: registerRemoteController: size of Media player list: 0
,09-06 19:11:22.580  6970  6970 E AudioManager: No RCC entry present to update
09-06 19:11:22.580  6970  6970 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-06 19:11:22.582  6970  6970 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-06 19:11:22.583  6970  6970 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-06 19:11:22.583  6970  6970 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-06 19:11:22.583  7064  7064 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-06 19:11:22.583  6970  7419 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-06 19:11:22.586  4326  7465 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 19:11:22.587  6970  6970 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-06 19:11:22.593  4326  7466 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:22.593  4326  7466 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-06 19:11:22.627  7443  7443 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-06 19:11:22.628  7443  7443 W LG Account v2.2: No ProfileInfo entries
09-06 19:11:22.628  7443  7443 I LG Account v2.2: isEnabled: false
09-06 19:11:22.628  7443  7443 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-06 19:11:22.628  7443  7443 I Feature : [Lifetracker]Country: EU
09-06 19:11:22.628  7443  7443 I Feature : [Lifetracker]Operator: OPEN
09-06 19:11:22.628  7443  7443 I Feature : [Lifetracker]Ranking support: false
09-06 19:11:22.628  7443  7443 I Feature : [Lifetracker]Comfort support: false
09-06 19:11:22.628  7443  7443 I Feature : [Lifetracker]Accessory: true
09-06 19:11:22.628  7443  7443 I Feature : [Lifetracker]Health device: true
09-06 19:11:22.628  7443  7443 I Feature : [Lifetracker]Extra Pedometer: false
09-06 19:11:22.629  7443  7443 I Feature : [Lifetracker]Blood glucose device: false
09-06 19:11:22.629  7443  7443 I Feature : [Lifetracker]Device Number: 3
,09-06 19:11:22.632  7064  7469 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:22.643  6941  7471 W FormManager: Network not available. Please check & try again.
,09-06 19:11:22.653  3357  3357 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,09-06 19:11:22.653  3357  3357 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:22.653  3357  3357 I LgeMiscReceiver: networkInfo.isConnected() = false
09-06 19:11:22.657  6941  7472 V FormManager: Network unavailable.
,09-06 19:11:22.662  7094  7094 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-06 19:11:22.663  7094  7094 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-06 19:11:22.664  6829  6829 D BluetoothPermissionRequest: onReceive
09-06 19:11:22.665  1032  2003 V SIM_STK : Menu title from STK is T-Mobile
09-06 19:11:22.665  1032  2003 V SIM_STK : Menu title from STK is T-Mobile
09-06 19:11:22.671  6941  7472 V FormManager: Network unavailable.
,09-06 19:11:22.675  6829  6829 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:11:22.679  7154  7154 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:11:22
09-06 19:11:22.680  7154  7154 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 19:11:22.680  7154  7154 D Weather.Utils: 2 : All the weather widget is gone.
09-06 19:11:22.680  7154  7154 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 19:11:22.681  7154  7154 D WeatherAncestor: connectivity changed - connection : true
09-06 19:11:22.681  7154  7154 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@17bc6a76
09-06 19:11:22.681  7154  7154 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 19:11:22.681  7154  7154 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 19:11:22.681  7154  7154 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-06 19:11:22.681  7154  7154 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 19:11:22.682  7154  7154 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:11:22
09-06 19:11:22.701  6402  6402 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-06 19:11:22.706  6402  6871 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-06 19:11:22.715  2201  2201 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:22.716  1032  2003 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-06 19:11:22.721  6970  6970 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-06 19:11:22.724  6970  6970 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,09-06 19:11:22.724  6970  6970 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-06 19:11:22.725  6970  6970 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-06 19:11:22.725  6970  6970 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-06 19:11:22.725  6970  6970 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 19:11:22.725  6970  6970 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-06 19:11:22.725  6970  6970 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-06 19:11:22.725  6970  6970 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-06 19:11:22.725  6970  6970 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 19:11:22.725  6970  6970 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-06 19:11:22.725  6970  6970 I BluetoothA2dpServiceJni: classInitNative
09-06 19:11:22.725  6970  6970 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 19:11:22.725  6970  6970 D A2dpStateMachine: make
09-06 19:11:22.726  7019  7019 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-06 19:11:22.726  7019  7019 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:22.726  7019  7019 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-06 19:11:22.726  7019  7019 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-06 19:11:22.727  6970  6970 I bluedroid-qcom: get_profile_interface a2dp
09-06 19:11:22.727  6970  7475 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-06 19:11:22.729  7019  7019 I AppUp4:CustModeStarterReceiver: onReceive
09-06 19:11:22.729  6970  6970 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-06 19:11:22.729  6970  6970 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-06 19:11:22.731  6970  6970 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17bc6a76
09-06 19:11:22.731  6970  7474 D A2dpStateMachine: Enter Disconnected: -2
09-06 19:11:22.731  6970  6970 I BluetoothHidServiceJni: classInitNative: succeeds
09-06 19:11:22.733  7019  7019 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@26a68538
09-06 19:11:22.733  7019  7019 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 19:11:22.733  7019  7019 D AppUp4:CustFacade: isPhone : true
09-06 19:11:22.733  6970  6970 D HidService: Received start request. Starting profile...
09-06 19:11:22.733  6970  6970 I bluedroid-qcom: get_profile_interface hidhost
09-06 19:11:22.733  6970  6970 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17bc6a76
09-06 19:11:22.734  6970  6970 I BluetoothHealthServiceJni: classInitNative: succeeds
09-06 19:11:22.735  7019  7019 D AppUp4:CustModeStarterReceiver: begin check event
09-06 19:11:22.736  7019  7019 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-06 19:11:22.736  6970  6970 D HealthService: Received start request. Starting profile...
09-06 19:11:22.738  6970  6970 I bluedroid-qcom: get_profile_interface health
09-06 19:11:22.739  6970  6970 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-06 19:11:22.739  6970  6970 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17bc6a76
09-06 19:11:22.740  6970  6970 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-06 19:11:22.740  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:22.740  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-06 19:11:22.741  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:11:22.742  6970  6970 D PanService: Received start request. Starting profile...
09-06 19:11:22.742  6970  6970 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 19:11:22.742  6970  6970 I bluedroid-qcom: get_profile_interface pan
09-06 19:11:22.743  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:11:22.749  6970  6970 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-06 19:11:22.749  6970  6970 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17bc6a76
09-06 19:11:22.749  7064  7064 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-06 19:11:22.749  6970  6970 D HeadsetStateMachine: Proxy object connected
09-06 19:11:22.750  6970  6970 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-06 19:11:22.750  6970  6970 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-06 19:11:22.751  4326  7480 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-06 19:11:22.752  6970  6970 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,09-06 19:11:22.757  6970  6970 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 19:11:22.757  6970  6970 D BtGatt.GattService: Received start request. Starting profile...
09-06 19:11:22.757  6970  6970 D BtGatt.GattService: start()
09-06 19:11:22.757  6970  6970 I bluedroid-qcom: get_profile_interface gatt
09-06 19:11:22.757  6970  6970 D BtGatt.AdvertiseManager: advertise manager created
09-06 19:11:22.758  4326  7481 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:22.758  4326  7481 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-06 19:11:22.764  7064  7482 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:11:22.766  6970  6970 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17bc6a76
09-06 19:11:22.767  6941  7485 W FormManager: Network not available. Please check & try again.
09-06 19:11:22.768  6970  6970 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17bc6a76
09-06 19:11:22.769  6970  6970 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-06 19:11:22.770  6970  6970 V BluetoothMapService: BluetoothMapBinder()
09-06 19:11:22.770  6941  7486 V FormManager: Network unavailable.
09-06 19:11:22.771  6970  6970 D BluetoothMapService: Received start request. Starting profile...
09-06 19:11:22.771  6970  6970 D BluetoothMapService: start()
09-06 19:11:22.776  6970  6970 D BluetoothMapEmailSettingsLoader: Found 0 applications
,09-06 19:11:22.776  6970  6970 D BluetoothMapEmailAppObserver: createReceiver()
09-06 19:11:22.778  6970  6970 D BluetoothMapEmailAppObserver: initObservers()
09-06 19:11:22.779  6970  6970 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-06 19:11:22.780  6941  7486 V FormManager: Network unavailable.
09-06 19:11:22.784  3357  3357 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-06 19:11:22.784  3357  3357 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:22.784  3357  3357 I LgeMiscReceiver: networkInfo.isConnected() = false
09-06 19:11:22.787  6970  6970 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17bc6a76
09-06 19:11:22.788  7094  7094 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-06 19:11:22.788  7094  7094 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-06 19:11:22.792  6970  6970 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 19:11:22.792  6970  7458 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-06 19:11:22.792  6970  7458 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 19:11:22.792  6970  7458 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-06 19:11:22.794  6970  6970 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 19:11:22.796  6970  6970 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 19:11:22.798  6970  6970 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 19:11:22.798  6970  6970 V PanService: [BTUI] SIM Extra State :ABSENT
09-06 19:11:22.801  6970  6970 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-06 19:11:22.804  6970  6970 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,09-06 19:11:22.804  6970  6970 V BluetoothMapService: Handler(): got msg=1
09-06 19:11:22.804  6970  7419 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-06 19:11:22.805  6970  7419 I bluedroid-qcom: enable
09-06 19:11:22.805  6970  7419 I bt_hci_bdroid: init
09-06 19:11:22.805  6970  7489 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-06 19:11:22.805  6970  7489 I bt-btu  : btu_task pending for preload complete event
09-06 19:11:22.806  6970  7419 I bt_vendor: bt-vendor : init
09-06 19:11:22.806  6970  7419 I bt_vendor: bt-vendor : get_bt_soc_type
09-06 19:11:22.806  6970  7419 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-06 19:11:22.806  6970  7419 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-06 19:11:22.806  6970  7419 D bt_userial_mct: userial_init
09-06 19:11:22.806  6970  6970 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:22.806  6970  7419 D bt_hci_bdroid: set_power 1
09-06 19:11:22.806  6970  7419 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-06 19:11:22.806  6970  7419 I bt_vendor: Starting hciattach daemon
09-06 19:11:22.806  6970  7419 I bt_vendor: try to set true
09-06 19:11:22.806  7154  7154 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:11:22
09-06 19:11:22.807  6970  6970 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:11:22.807  6970  6970 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:11:22.807  6970  6970 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:11:22.807  7154  7154 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-06 19:11:22.807  7154  7154 D Weather.Utils: 2 : All the weather widget is gone.
09-06 19:11:22.807  6970  6970 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:22.807  6970  6970 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-06 19:11:22.808  7154  7154 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-06 19:11:22.808  7154  7154 D WeatherAncestor: connectivity changed - connection : true
09-06 19:11:22.808  7154  7154 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@17bc6a76
09-06 19:11:22.798  7492  7492 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:11:22.808  7154  7154 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-06 19:11:22.808  7154  7154 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-06 19:11:22.808  7154  7154 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-06 19:11:22.808  7154  7154 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-06 19:11:22.808  7154  7154 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:11:22
09-06 19:11:22.798  7492  7492 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:11:22.825  7493  7493 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-06 19:11:22.908  7499  7499 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-06 19:11:22.927  7500  7500 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 19:11:22.971  7502  7502 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 19:11:22.984  7503  7503 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-06 19:11:22.997  7504  7504 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 19:11:23.011  7505  7505 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-06 19:11:23.040  7507  7507 I libmdmdetect: ESOC framework not supported
09-06 19:11:23.041  7507  7507 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-06 19:11:23.049  7507  7507 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-06 19:11:23.049  7507  7507 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-06 19:11:23.049  7507  7507 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-06 19:11:23.049  7507  7507 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-06 19:11:23.049  7507  7507 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-06 19:11:23.049  7507  7507 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-06 19:11:23.049  7507  7507 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-06 19:11:23.089  7507  7511 E QC-QMI  : qmi_client [7507] 14: failed to locate client data
09-06 19:11:23.095   481   481 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-06 19:11:23.096   481   481 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,09-06 19:11:23.168  7515  7515 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-06 19:11:23.193  7516  7516 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 19:11:23.208  6970  7419 I bt_vendor: bluetooth satus is on
09-06 19:11:23.208  6970  7419 D bt_hci_bdroid: preload
09-06 19:11:23.208  6970  7491 D bt_userial_mct: userial_open(port:0)
09-06 19:11:23.208  6970  7491 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-06 19:11:23.211  6970  7491 I bt_vendor: Done intiailizing UART
09-06 19:11:23.216  6970  7491 I bt_vendor: Done intiailizing UART
09-06 19:11:23.216  6970  7491 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-06 19:11:23.216  6970  7491 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-06 19:11:23.216  6970  7518 D bt_userial_mct: Entering userial_read_thread()
,09-06 19:11:23.216  6970  7489 I bt-btu  : btu_task received preload complete event
09-06 19:11:23.217  6970  7489 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-06 19:11:23.217  6970  7489 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-06 19:11:23.219  6970  7489 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-06 19:11:23.222  6970  7489 I         : BTE_InitTraceLevels -- TRC_HCI
09-06 19:11:23.222  6970  7489 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 19:11:23.222  6970  7489 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-06 19:11:23.222  6970  7489 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 19:11:23.222  6970  7489 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 19:11:23.222  6970  7489 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 19:11:23.222  6970  7489 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 19:11:23.222  6970  7489 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 19:11:23.222  6970  7489 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-06 19:11:23.222  6970  7489 I         : BTE_InitTraceLevels -- TRC_GAP
09-06 19:11:23.222  6970  7489 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 19:11:23.222  6970  7489 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 19:11:23.223  6970  7489 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 19:11:23.223  6970  7489 I         : BTE_InitTraceLevels -- TRC_SMP
09-06 19:11:23.223  6970  7489 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 19:11:23.223  6970  7489 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-06 19:11:23.311  6970  7489 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-06 19:11:23.311  6970  7489 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0214061 
09-06 19:11:23.311  6970  7489 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0214061 
,09-06 19:11:23.327  6970  7423 E bt-btif : Calling BTA_HhEnable
,09-06 19:11:23.327  6970  7423 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-06 19:11:23.327  6970  7489 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-06 19:11:23.327  6970  7489 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-06 19:11:23.327  6970  7489 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-06 19:11:23.327  6970  7489 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-06 19:11:23.327  6970  7489 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-06 19:11:23.327  6970  7423 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-06 19:11:23.329  6970  7423 D BluetoothAdapterProperties: Name is: G3
09-06 19:11:23.330  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-06 19:11:23.331  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
,09-06 19:11:23.332  6970  7423 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:11:23.332  6970  7423 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:11:23.333  6970  7423 D bt_hci_bdroid: postload
09-06 19:11:23.333  6970  7491 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 19:11:23.334  6970  7489 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-06 19:11:23.334  6970  7423 D bte_conf: Device ID record 1 : primary
09-06 19:11:23.334  6970  7423 D bte_conf:   vendorId            = 00c4
09-06 19:11:23.334  6970  7423 D bte_conf:   vendorIdSource      = 0001
09-06 19:11:23.334  6970  7423 D bte_conf:   product             = 13a1
09-06 19:11:23.334  6970  7423 D bte_conf:   version             = 1000
09-06 19:11:23.334  6970  7423 D bte_conf:   clientExecutableURL = 
09-06 19:11:23.334  6970  7423 D bte_conf:   serviceDescription  = 
09-06 19:11:23.334  6970  7423 D bte_conf:   documentationURL    = 
09-06 19:11:23.334  6970  7423 D bte_conf: bte_load_did_conf no section named DID2.
09-06 19:11:23.335  6970  7491 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 19:11:23.336  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:23.337  6970  7419 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-06 19:11:23.338  6970  7419 D BluetoothAdapterProperties: ScanMode =  20
09-06 19:11:23.338  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:23.338  6970  7419 D BluetoothAdapterProperties: State =  11
09-06 19:11:23.338  6970  7419 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-06 19:11:23.338  6970  7419 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-06 19:11:23.338  6970  7491 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 19:11:23.338  6970  7419 D BluetoothAdapterProperties: Setting state to 12
09-06 19:11:23.338  6970  7419 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-06 19:11:23.340  6970  7419 I BluetoothAdapterState: Entering On State
09-06 19:11:23.338  7520  7520 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:11:23.338  7520  7520 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:11:23.341  1032  1094 D BluetoothManagerService: Message: 60
09-06 19:11:23.341  6970  7423 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-06 19:11:23.341  6970  7423 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-06 19:11:23.350  6970  7489 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:11:23.350  6970  7489 W bt-smp  : Plain text(LSB ~ MSB) = 30 9e 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:11:23.350  6970  7489 W bt-smp  : Encrypted text(LSB ~ MSB) = 46 1a bf 16 3b 53 b8 50 27 c0 6d 27 fa 0a 14 1e 
09-06 19:11:23.350  6970  7489 W bt-btm  : Stopping oneshot timer
09-06 19:11:23.350  6970  7491 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 19:11:23.350  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-06 19:11:23.351  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-06 19:11:23.353  6970  7518 E bt_mct  : hci lib postload completed
09-06 19:11:23.353  6829  6848 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-06 19:11:23.355  6970  7423 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:11:23.355  6970  7423 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-06 19:11:23.362  6970  7419 D LGBluetoothServiceAdapter: [BTUI] OnState
09-06 19:11:23.362  6970  7419 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-06 19:11:23.363  6970  7419 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,09-06 19:11:23.367  6970  7419 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-06 19:11:23.369  6829  6848 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 19:11:23.371  1032  1094 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:11:23.374  1032  1032 D BluetoothA2dp: Proxy object connected
09-06 19:11:23.377  1878  1894 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 19:11:23.384  6970  7489 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:11:23.384  6970  7489 W bt-smp  : Plain text(LSB ~ MSB) = ae 55 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:11:23.384  6970  7489 W bt-smp  : Encrypted text(LSB ~ MSB) = 72 74 a9 46 09 13 f9 52 48 8c d1 9d 08 7c 19 b4 
09-06 19:11:23.384  6970  7489 W bt-btm  : Stopping oneshot timer
09-06 19:11:23.386  1878  1878 D BluetoothHeadset: Proxy object connected
09-06 19:11:23.386  1878  2362 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:11:23.390  1878  1878 D BluetoothHeadset: Proxy object connected
,09-06 19:11:23.392  6970  7419 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,09-06 19:11:23.393  6829  6850 D BluetoothMap: onBluetoothStateChange: up=true
09-06 19:11:23.400  1032  1094 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:11:23.409  1032  1032 D BluetoothHeadset: Proxy object connected
,09-06 19:11:23.412  6970  7489 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:11:23.412  6970  7489 W bt-smp  : Plain text(LSB ~ MSB) = 9a db 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:11:23.412  6970  7489 W bt-smp  : Encrypted text(LSB ~ MSB) = fe d0 62 6c cd bb b0 3c 28 7d 51 c8 a3 3d 7c 4b 
09-06 19:11:23.412  6970  7489 W bt-btm  : Stopping oneshot timer
09-06 19:11:23.413  1878  2583 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:11:23.414  6829  6829 D BluetoothInputDevice: Proxy object connected
09-06 19:11:23.414  6829  6829 D HidProfile: Bluetooth service connected
09-06 19:11:23.415  1878  1878 D BluetoothHeadset: Proxy object connected
09-06 19:11:23.415  6829  7522 D BluetoothPan: onBluetoothStateChange on: true
09-06 19:11:23.415  6829  7522 D BluetoothPan: onBluetoothStateChange call bindService
09-06 19:11:23.417  6829  6829 D BluetoothMap: Proxy object connected
09-06 19:11:23.417  6829  6829 D MapProfile: Bluetooth service connected
09-06 19:11:23.417  6829  6829 D BluetoothMap: getConnectedDevices()
09-06 19:11:23.419  6970  7439 V BluetoothMapService: getConnectedDevices()
09-06 19:11:23.421  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-06 19:11:23.421  1032  1094 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-06 19:11:23.421  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-06 19:11:23.422  1032  1094 D BluetoothManagerService: Message: 40
09-06 19:11:23.422  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-06 19:11:23.422  6829  6829 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:11:23.422  6829  6829 D PanProfile: Bluetooth service connected
,09-06 19:11:23.424  6970  7489 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:11:23.424  6970  7489 W bt-smp  : Plain text(LSB ~ MSB) = 5f 79 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:11:23.424  6970  7489 W bt-smp  : Encrypted text(LSB ~ MSB) = 9f 7a 77 9d 7a 55 9f 99 e3 74 34 ef fe 08 d1 39 
09-06 19:11:23.424  6970  7489 W bt-btm  : Stopping oneshot timer
09-06 19:11:23.427  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:11:23.430  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:23.430  1969  2192 D LGBluetoothAPIService: Message: 1
09-06 19:11:23.430  1969  2192 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-06 19:11:23.431  7531  7531 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-06 19:11:23.435  1969  2192 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,09-06 19:11:23.436  6970  7489 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:11:23.436  6970  7489 W bt-smp  : Plain text(LSB ~ MSB) = 61 1b 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:11:23.436  6970  7489 W bt-smp  : Encrypted text(LSB ~ MSB) = 0b 0f 89 b3 11 5b 7b c8 50 90 e5 8d 2d 41 aa 39 
09-06 19:11:23.436  6970  7489 W bt-btm  : Stopping oneshot timer
09-06 19:11:23.438  6970  6970 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:23.438  6970  6970 D BluetoothMapService: STATE_ON
09-06 19:11:23.440  6970  6970 D LGBluetoothAPIServer: [BTUI] onCreate()
09-06 19:11:23.440  6970  6970 D LGBluetoothAPIServer: [BTUI] onBind()
09-06 19:11:23.441  6970  6970 V BluetoothMapService: Handler(): got msg=1
09-06 19:11:23.442  6970  6970 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-06 19:11:23.443  6732  6732 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-06 19:11:23.444  1969  1969 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-06 19:11:23.444  1969  2192 D LGBluetoothAPIService: Message: 100
09-06 19:11:23.444  1969  2192 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-06 19:11:23.446  6829  6829 D LocalBluetoothProfileManager: Adding local A2DP profile
09-06 19:11:23.448  1032  1094 D BluetoothManagerService: Message: 30
,09-06 19:11:23.451  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:11:23.451  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:23.451  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:23.451  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:11:23.451  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:11:23.451  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:11:23.451  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:11:23.451  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:11:23.453  6732  6732 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:11:23.453  6970  7538 D BluetoothMapMasInstance: MAS initSocket()
09-06 19:11:23.453  6970  7538 D BluetoothMapMasInstance:   masId = 00
09-06 19:11:23.453  6970  7538 D BluetoothMapMasInstance:   msgTypes = 0e
09-06 19:11:23.453  6970  7538 D BluetoothMapMasInstance:   masName = SMS/MMS
09-06 19:11:23.453  6970  7538 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-06 19:11:23.455  1032  2004 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:23.458  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:11:23.458  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:23.458  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:23.458  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:11:23.458  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:11:23.458  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:11:23.458  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:11:23.458  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:11:23.458  6970  7538 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:11:23.459  6829  6829 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-06 19:11:23.460  6970  7538 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-06 19:11:23.460  6970  7423 D BluetoothAdapterProperties: Scan Mode:21
09-06 19:11:23.460  6970  7538 V BluetoothMapMasInstance: Succeed to create listening socket 
09-06 19:11:23.460  6970  7538 D BluetoothMapMasInstance: Accepting socket connection...
09-06 19:11:23.460  6970  7423 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,09-06 19:11:23.464  6970  6970 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17bc6a76
09-06 19:11:23.465  6970  6970 V BluetoothPbapService: Pbap Service onCreate
09-06 19:11:23.465  6970  6970 V BluetoothPbapService: Starting PBAP service
09-06 19:11:23.466  1032  1094 D BluetoothManagerService: Message: 30
09-06 19:11:23.466  6970  6970 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-06 19:11:23.467  6970  6970 V BluetoothPbapService: Pbap Service onBind
09-06 19:11:23.468  6970  6970 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:23.468  6970  6970 V BluetoothPbapService: state: 12
09-06 19:11:23.468  6970  6970 V BluetoothPbapService: Handler(): got msg=1
09-06 19:11:23.468  6970  6970 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-06 19:11:23.470  6970  7539 V BluetoothPbapService: Pbap Service initSocket
,09-06 19:11:23.471  6732  6732 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:11:23.472  1032  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:23.473  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:23.474  6970  7539 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:11:23.474  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:23.475  6970  7539 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
,09-06 19:11:23.475  6970  7539 V BluetoothPbapService: Succeed to create listening socket 
09-06 19:11:23.475  6970  7539 V BluetoothPbapService: Accepting socket connection...
09-06 19:11:23.477  6829  6829 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-06 19:11:23.479  6829  6829 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-06 19:11:23.483  6970  6970 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 19:11:23.483  6970  6970 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:23.483  6970  6970 V BluetoothPbapReceiver: ***********state = 12
09-06 19:11:23.483  6829  6829 D BluetoothA2dp: Proxy object connected
09-06 19:11:23.484  6829  6829 D A2dpProfile: Bluetooth service connected
09-06 19:11:23.485  2201  2201 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:11:23.486  2201  2201 D c       : Getting all permits...
09-06 19:11:23.486  2201  2201 D a       : Opening database...
09-06 19:11:23.486  6829  6829 D BluetoothPbap: Proxy object connected
09-06 19:11:23.487  6829  6829 D PbapServerProfile: Bluetooth service connected
09-06 19:11:23.487  6829  6829 D BluetoothHeadset: Proxy object connected
09-06 19:11:23.488  6829  6829 D HeadsetProfile: Bluetooth service connected
09-06 19:11:23.491  2201  2201 D a       : Opening database auth.proximity.permit_store...
09-06 19:11:23.492  2201  2201 D a       : Closing database...
09-06 19:11:23.492  6829  6829 D DockEventReceiver: finishStartingService: stopping service
09-06 19:11:23.502  6829  6829 D BluetoothPermissionRequest: onReceive
,09-06 19:11:23.503  6829  6829 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-06 19:11:23.505  6829  6829 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:11:23.508  6970  6970 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-06 19:11:23.509  6970  6970 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-06 19:11:23.516  6970  6970 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-06 19:11:23.539  6970  6970 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-06 19:11:23.539  6970  6970 V BtOppService: onCreate
,09-06 19:11:23.544  6970  6970 V BluetoothOppNotification: send message
09-06 19:11:23.547  6970  6970 V BtOppService: Starting RfcommListener
09-06 19:11:23.551  6970  6970 D BluetoothOppPreference: Dumping Names:  
09-06 19:11:23.551  6970  6970 D BluetoothOppPreference: {}
09-06 19:11:23.551  6970  6970 D BluetoothOppPreference: Dumping Channels:  
,09-06 19:11:23.551  6970  6970 D BluetoothOppPreference: {}
,09-06 19:11:23.552  6970  6970 V BtOppService: onStartCommand
,09-06 19:11:23.555  6970  7548 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 19:11:23.556  6970  6970 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:23.556  6970  6970 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-06 19:11:23.559  6970  6970 V BluetoothOppNotification: new notify threadi!
09-06 19:11:23.560  6970  6970 V BluetoothOppNotification: send delay message
09-06 19:11:23.560  6970  6970 V BtOppService: start RfcommListener
09-06 19:11:23.561  6970  7548 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 19:11:23.563  6970  7545 V BtOppService: Deleted complete outbound shares, number =  0
09-06 19:11:23.564  6970  6970 V BtOppService: RfcommListener started
09-06 19:11:23.564  6970  7548 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31e9b4e3 on behalf of 
,09-06 19:11:23.566  6970  7545 V BtOppService: Deleted complete inbound failed shares, number = 0
09-06 19:11:23.567  6970  7545 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-06 19:11:23.568  6970  7550 V BtOppRfcommListener: Starting RFCOMM listener....
09-06 19:11:23.569  6970  7549 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-06 19:11:23.569  6970  7545 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@315ee0 on behalf of 
09-06 19:11:23.569  1032  1575 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:23.570  6970  7550 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:11:23.571  6970  7549 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@212dd599 on behalf of 
09-06 19:11:23.572  6970  7549 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-06 19:11:23.572  6970  7550 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
09-06 19:11:23.573  6970  7550 V BtOppRfcommListener: Started RFCOMM listener....
09-06 19:11:23.573  6970  7550 I BtOppRfcommListener: Accept thread started.
09-06 19:11:23.573  6970  7550 V BtOppRfcommListener: Accepting connection...
09-06 19:11:23.573  6970  7549 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-06 19:11:23.575  6970  7549 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24eec05e on behalf of 
09-06 19:11:23.575  6970  7549 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-06 19:11:23.577  6970  7548 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-06 19:11:23.578  6970  7549 V BluetoothOppNotification: outbound notification was removed.
09-06 19:11:23.578  6970  7549 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-06 19:11:23.580  6970  7549 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ef8bc3f on behalf of 
09-06 19:11:23.580  6970  7549 V BluetoothOppNotification: inbound: succ-0  fail-0
09-06 19:11:23.582  6970  7549 V BluetoothOppNotification: inbound notification was removed.
09-06 19:11:23.582  6970  7549 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-06 19:11:23.583  6970  7549 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10fd890c on behalf of 
09-06 19:11:23.588  6970  6970 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17bc6a76
,09-06 19:11:23.588  6970  6970 V BluetoothFtpService: Ftp Service onCreate
09-06 19:11:23.588  6970  6970 I BluetoothFtpService: Ftp Service onCreate
09-06 19:11:23.588  6970  6970 V BluetoothFtpService: Ftp Service onStartCommand
09-06 19:11:23.588  6970  6970 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:23.588  6970  6970 V BluetoothFtpService: Starting Listening on sockets
09-06 19:11:23.589  6970  6970 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:11:23.589  6970  6970 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:11:23.589  6970  6970 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:11:23.589  6970  6970 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:23.589  6970  6970 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-06 19:11:23.589  6970  6970 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-06 19:11:23.593  6970  6970 V BtOppService: ContentObserver received notification
09-06 19:11:23.594  6970  6970 V BtOppService: ContentObserver received notification
09-06 19:11:23.594  6970  6970 V BluetoothFtpService: Handler(): got msg=1
09-06 19:11:23.594  6970  6970 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-06 19:11:23.594  6970  6970 V BluetoothFtpService: Ftp Service initSocket
09-06 19:11:23.596  6970  7551 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 19:11:23.596  6970  7551 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 19:11:23.597  6970  7551 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21e2846a on behalf of 
09-06 19:11:23.598  6970  7551 V BluetoothOppNotification: update too frequent, put in queue
09-06 19:11:23.598  1032  1781 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:23.599  6970  7551 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-06 19:11:23.599  6970  6970 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:11:23.601  6970  6970 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-06 19:11:23.603  6970  7552 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-06 19:11:23.624  6970  6970 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17bc6a76
09-06 19:11:23.624  6970  6970 V BluetoothSapService: Sap Service onCreate
,09-06 19:11:23.733  1032  1949 I art     : Explicit concurrent mark sweep GC freed 93588(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.402ms total 101.589ms
,09-06 19:11:23.737  6970  6970 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:23.737  6970  6970 V BluetoothSapService: state: 12
09-06 19:11:23.737  6970  6970 V BluetoothSapService: Starting SAP server process
09-06 19:11:23.738  6970  6970 V BluetoothSapService: SAP Service startRfcommListenerThread
09-06 19:11:23.739  7211  7235 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
09-06 19:11:23.740  6970  7555 V BluetoothSapService: Sap Service initRfcommSocket
09-06 19:11:23.740  1032  2323 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:23.740  6970  7555 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:11:23.738  7554  7554 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:11:23.738  7554  7554 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:11:23.743  6970  7555 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-06 19:11:23.744  6970  7555 V BluetoothSapService: Succeed to create listening socket 
09-06 19:11:23.744  6970  7555 V BluetoothSapService: Accepting socket connection...
09-06 19:11:23.769  7554  7554 V BT_SAP  : Event pipe created
,09-06 19:11:23.769  7554  7554 V BT_SAP  : create_server_socket qcom.sap.server
09-06 19:11:23.769  7554  7554 V BT_SAP  : created socket fd 6
09-06 19:11:24.277  1032  1537 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:24.277  1032  1537 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:11:24.312  1032  1538 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-06 19:11:24.313  1032  1538 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-06 19:11:24.538  1032  2003 I ActivityManager: Killing 7345:com.lge.bnr/1000 (adj 15): empty #17
,09-06 19:11:24.561  6970  6970 V BluetoothOppNotification: new notify threadi!
09-06 19:11:24.562  6970  6970 V BluetoothOppNotification: send delay message
,09-06 19:11:24.566  6970  7566 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-06 19:11:24.571  6970  7566 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c9c7d36 on behalf of 
09-06 19:11:24.571  6970  7566 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-06 19:11:24.573  6970  7566 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-06 19:11:24.574  6970  7566 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a8bf437 on behalf of 
,09-06 19:11:24.577  6970  7566 V BluetoothOppNotification: outbound: succ-0  fail-0
09-06 19:11:24.578  6970  7566 V BluetoothOppNotification: outbound notification was removed.
09-06 19:11:24.579  6970  7566 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-06 19:11:24.581  6970  7566 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b89eda4 on behalf of 
09-06 19:11:24.582  6970  7566 V BluetoothOppNotification: inbound: succ-0  fail-0
09-06 19:11:24.584  6970  7566 V BluetoothOppNotification: inbound notification was removed.
09-06 19:11:24.584  6970  7566 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-06 19:11:24.585  6970  7566 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30fa570d on behalf of 
09-06 19:11:24.590  1032  2049 W libprocessgroup: failed to open /acct/uid_1000/pid_7345/cgroup.procs: No such file or directory
,09-06 19:11:24.895  1032  1049 I ActivityManager: Killing 6873:com.lge.sync/1000 (adj 15): empty #17
,09-06 19:11:24.927  1032  1544 D WifiService: Client connection lost with reason: 4
,09-06 19:11:24.933  1032  2323 W libprocessgroup: failed to open /acct/uid_1000/pid_6873/cgroup.procs: No such file or directory
,09-06 19:11:25.283  1032  2003 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:25.283  1032  2003 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@287060dd mBinding = false
,09-06 19:11:25.315  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-06 19:11:25.318  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:11:25.318  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-06 19:11:25.319  1032  1094 D BluetoothManagerService: Message: 2
09-06 19:11:25.320  1032  1094 D BluetoothManagerService: Sending off request.
09-06 19:11:25.321  6970  7536 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-06 19:11:25.321  6970  7419 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-06 19:11:25.322  6970  7419 D BluetoothAdapterProperties: Setting state to 13
09-06 19:11:25.322  6970  7419 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 19:11:25.322  6970  7419 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 19:11:25.323  6970  7419 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-06 19:11:25.324  6970  7423 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:11:25.326  6970  7419 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-06 19:11:25.328  6970  7538 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-06 19:11:25.328  6970  7538 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:11:25.328  6970  7538 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-06 19:11:25.328  6970  7538 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-06 19:11:25.328  6970  7538 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-06 19:11:25.328  6970  7538 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-06 19:11:25.328  6970  7538 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-06 19:11:25.328  6970  7538 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,09-06 19:11:25.333  6970  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-06 19:11:25.333  6970  7489 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-06 19:11:25.335  6970  7539 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:11:25.335  6970  7550 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:11:25.335  6970  7552 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:11:25.335  6970  7555 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:11:25.336  6970  7419 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-06 19:11:25.343  6970  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,09-06 19:11:25.343  6970  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:11:25.349  6970  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:11:25.349  6970  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:11:25.349  6970  7489 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:11:25.349  6970  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:11:25.350  6970  7489 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:11:25.350  6970  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:11:25.350  6970  7489 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:11:25.350  6970  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-06 19:11:25.350  6970  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-06 19:11:25.350  6970  7489 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-06 19:11:25.353  6732  6732 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:11:25.353  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:11:25.353  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:25.353  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:25.353  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:11:25.353  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:11:25.353  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:11:25.353  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:11:25.353  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:11:25.355  6732  6732 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:11:25.355  6732  6732 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:11:25.362  6732  6732 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:11:25.365  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:11:25.365  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:25.365  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:25.365  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:11:25.365  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:11:25.365  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:11:25.365  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:11:25.365  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:11:25.366  6732  6732 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:11:25.366  6732  6732 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:11:25.367  1032  1094 D BluetoothManagerService: Message: 60
09-06 19:11:25.367  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-06 19:11:25.367  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-06 19:11:25.370  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:25.372  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:11:25.377  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:11:25.380  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:25.383  6970  6970 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:25.383  6970  6970 D BluetoothMapService: STATE_TURNING_OFF
09-06 19:11:25.383  6970  6970 V BluetoothMapService: Handler(): got msg=4
09-06 19:11:25.383  6970  6970 D BluetoothMapService: MAP Service closeService in
09-06 19:11:25.383  6970  6970 D BluetoothMapMasInstance: MAP Service shutdown
09-06 19:11:25.384  6970  6970 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 19:11:25.384  6970  6970 V BluetoothMapService: MAP Service closeService out
09-06 19:11:25.385  6970  6970 V BtOppService: Receiver DISABLED_ACTION 
09-06 19:11:25.385  6970  6970 I BtOppRfcommListener: stopping Accept Thread
09-06 19:11:25.385  6970  6970 V BtOppRfcommListener: close mBtServerSocket
09-06 19:11:25.386  6970  7550 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-06 19:11:25.386  6970  6970 V BtOppRfcommListener: waiting for thread to terminate
09-06 19:11:25.386  6970  6970 V BtOppRfcommListener: done waiting for thread to terminate
09-06 19:11:25.390  6829  6829 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,09-06 19:11:25.403  6829  6829 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-06 19:11:25.406  6970  6970 V BtOppService: onDestroy
09-06 19:11:25.408  6970  6970 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-06 19:11:25.413  6970  6970 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 19:11:25.413  6970  6970 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:25.413  6970  6970 V BluetoothPbapReceiver: ***********state = 13
09-06 19:11:25.416  6970  6970 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,09-06 19:11:25.418  6970  6970 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:25.418  6970  6970 V BluetoothPbapService: state: 13
09-06 19:11:25.419  6970  6970 V BluetoothPbapService: Pbap Service closeService in
09-06 19:11:25.422  2201  2201 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:11:25.423  6970  6970 V BluetoothPbapService: successfully stopped pbap service
09-06 19:11:25.423  6970  6970 V BluetoothPbapService: Pbap Service closeService out
09-06 19:11:25.424  6970  6970 V BluetoothPbapService: Pbap Service onDestroy
09-06 19:11:25.424  6970  6970 V BluetoothPbapService: Pbap Service closeService in
09-06 19:11:25.424  6970  6970 V BluetoothPbapService: Pbap Service closeService out
09-06 19:11:25.424  6970  6970 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-06 19:11:25.444  6829  6829 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:11:25.448  6829  6829 D BluetoothPbap: Proxy object disconnected
09-06 19:11:25.448  6829  6829 D PbapServerProfile: Bluetooth service disconnected
09-06 19:11:25.451  6829  6829 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-06 19:11:25.458  6829  6829 D BluetoothPermissionRequest: onReceive
09-06 19:11:25.458  6829  6829 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-06 19:11:25.467  6829  6829 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:11:25.480  6970  6970 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-06 19:11:25.480  6970  6970 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,09-06 19:11:25.484  6970  6970 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-06 19:11:25.488  6970  6970 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:25.488  6970  6970 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-06 19:11:25.490  6970  6970 V BluetoothFtpService: Ftp Service onStartCommand
09-06 19:11:25.490  6970  6970 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:25.491  6970  6970 V BluetoothFtpService: Ftp Service closeService
09-06 19:11:25.491  6970  6970 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-06 19:11:25.494  6970  6970 V BluetoothFtpService: successfully stopped ftp service
09-06 19:11:25.494  6970  6970 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:11:25.494  6970  6970 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,09-06 19:11:25.494  6970  6970 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:11:25.494  6970  6970 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:11:25.494  6970  6970 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-06 19:11:25.495  6970  6970 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-06 19:11:25.496  6970  6970 V BluetoothFtpService: Ftp Service onDestroy
09-06 19:11:25.496  6970  6970 V BluetoothFtpService: Ftp Service closeService
09-06 19:11:25.501  6970  6970 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:25.501  6970  6970 V BluetoothSapService: state: 13
09-06 19:11:25.501  6970  6970 V BluetoothSapService: Stopping SAP server process
09-06 19:11:25.502  6970  6970 V BluetoothSapService: Sap Service closeSapService in
09-06 19:11:25.502  6970  6970 V BluetoothSapService: Close listen Socket : 
09-06 19:11:25.502  6970  6970 V BluetoothSapService: Close rfcomm Socket : 
09-06 19:11:25.502  6970  6970 V BluetoothSapService: Close sapd  Socket : 
09-06 19:11:25.507  6970  6970 V BluetoothSapService: Sap Service closeSapService out
09-06 19:11:25.507  6970  6970 V BluetoothSapService: Sap Service onDestroy
09-06 19:11:25.507  6970  6970 V BluetoothSapService: Sap Service closeSapService in
09-06 19:11:25.507  6970  6970 V BluetoothSapService: Close listen Socket : 
09-06 19:11:25.507  6970  6970 V BluetoothSapService: Close rfcomm Socket : 
09-06 19:11:25.507  6970  6970 V BluetoothSapService: Close sapd  Socket : 
,09-06 19:11:25.513  6970  6970 V BluetoothSapService: Sap Service closeSapService out
,09-06 19:11:26.244  6970  7423 D bt_hci_bdroid: cleanup
,09-06 19:11:26.253  6970  7491 I bt_lpm  : LPM is already off!!!
09-06 19:11:26.254  6970  7518 I bt_userial_mct: exiting userial_read_thread
09-06 19:11:26.254  6970  7518 D bt_userial_mct: Leaving userial_evt_read_thread()
09-06 19:11:26.255  6970  7489 W bt-btif : ag scb idx 1 not allocated
09-06 19:11:26.255  6970  7489 E bt-btif : BTA AG is already disabled, ignoring ...
09-06 19:11:26.255  6970  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:11:26.255  6970  7489 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:11:26.255  6970  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:11:26.255  6970  7489 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:11:26.255  6970  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:11:26.255  6970  7489 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:11:26.255  6970  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:11:26.255  6970  7489 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:11:26.255  6970  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:11:26.255  6970  7489 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:11:26.255  6970  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:11:26.255  6970  7489 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:11:26.255  6970  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-06 19:11:26.256  6970  7489 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:11:26.256  6970  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-06 19:11:26.256  6970  7489 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:11:26.256  6970  7489 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-06 19:11:26.256  6970  7489 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:11:26.256  6970  7489 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-06 19:11:26.259  6970  7423 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-06 19:11:26.262  6970  7491 I bt_vendor: hw_epilog_process
,09-06 19:11:26.265  6970  7423 D bt_hci_bdroid: cleanup Finalizing cleanup
09-06 19:11:26.265  6970  7423 D bt_userial_mct: userial_close
09-06 19:11:26.265  6970  7423 E bt_userial_mct: pthread_join() FAILED result:3
09-06 19:11:26.265  6970  7423 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-06 19:11:26.270  6970  7423 D bt_hci_bdroid: set_power 0
09-06 19:11:26.270  6970  7423 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 19:11:26.271  6970  7423 I bt_vendor: bluetooth satus is on
09-06 19:11:26.271  6970  7423 I bt_vendor: bt-vendor : resetting BT status
09-06 19:11:26.271  6970  7423 I bt_vendor: Starting hciattach daemon
09-06 19:11:26.271  6970  7423 I bt_vendor: try to set false
09-06 19:11:26.273  6970  7423 I bt_vendor: Starting hciattach daemon
09-06 19:11:26.273  6970  7423 I bt_vendor: try to set false
,09-06 19:11:26.277  6970  7423 I bt_vendor: cleanup
09-06 19:11:26.278  6970  7489 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-06 19:11:26.278  6970  7423 I GKI_LINUX: GKI_exit_task 0 done
09-06 19:11:26.278  6970  7423 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-06 19:11:26.280  6970  7419 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-06 19:11:26.287  6970  6970 D HeadsetService: Received stop request...Stopping profile...
,09-06 19:11:26.292  6970  7419 D BluetoothAdapterState: Stopping profile services that were post enabled
09-06 19:11:26.293  6970  7458 D HeadsetStateMachine: Exit Disconnected: -1
09-06 19:11:26.294  6970  6970 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-06 19:11:26.294  6970  6970 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:11:26.294  6970  6970 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17bc6a76
09-06 19:11:26.296  1878  1878 D BluetoothHeadset: Proxy object disconnected
09-06 19:11:26.296  1878  1878 D BluetoothHeadset: Proxy object disconnected
09-06 19:11:26.296  1878  1878 D BluetoothHeadset: Proxy object disconnected
09-06 19:11:26.296  1032  1032 D BluetoothHeadset: Proxy object disconnected
09-06 19:11:26.297  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-06 19:11:26.298  6970  6970 D A2dpService: Received stop request...Stopping profile...
09-06 19:11:26.298  6970  7474 D A2dpStateMachine: Exit Disconnected: -1
09-06 19:11:26.301  6970  6970 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,09-06 19:11:26.304  6970  6970 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-06 19:11:26.304  6970  6970 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:11:26.304  6970  6970 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17bc6a76
09-06 19:11:26.306  1032  1032 D BluetoothA2dp: Proxy object disconnected
09-06 19:11:26.306  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-06 19:11:26.307  6970  6970 D HidService: Received stop request...Stopping profile...
09-06 19:11:26.307  6970  6970 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17bc6a76
09-06 19:11:26.309  6970  6970 D HealthService: Received stop request...Stopping profile...
09-06 19:11:26.309  6970  6970 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17bc6a76
09-06 19:11:26.310  6970  6970 D PanService: Received stop request...Stopping profile...
09-06 19:11:26.312  6970  6970 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17bc6a76
,09-06 19:11:26.316  6970  6970 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 19:11:26.317  6970  6970 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 19:11:26.317  6970  6970 D BtGatt.GattService: stop()
09-06 19:11:26.317  6970  6970 D BtGatt.AdvertiseManager: advertise clients cleared
09-06 19:11:26.318  6970  6970 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17bc6a76
09-06 19:11:26.320  6970  6970 D BluetoothMapService: Received stop request...Stopping profile...
09-06 19:11:26.320  6970  6970 D BluetoothMapService: stop()
09-06 19:11:26.321  6970  6970 D BluetoothMapEmailAppObserver: deinitObservers()
09-06 19:11:26.321  6970  6970 D BluetoothMapEmailAppObserver: removeReceiver()
09-06 19:11:26.321  6970  6970 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17bc6a76
09-06 19:11:26.323  6970  6970 D HeadsetStateMachine: Unbinding service...
09-06 19:11:26.326  6970  6970 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 19:11:26.326  6970  6970 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 19:11:26.326  6970  6970 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 19:11:26.326  6970  6970 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 19:11:26.326  6970  6970 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 19:11:26.326  6970  6970 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:11:26.326  6970  6970 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-06 19:11:26.327  6970  6970 I BluetoothA2dpServiceJni: cleanupNative
,09-06 19:11:26.329  6970  7475 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-06 19:11:26.330  6970  6970 I GKI_LINUX: GKI_exit_task 2 done
09-06 19:11:26.330  6970  6970 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-06 19:11:26.331  6970  6970 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 19:11:26.331  6970  6970 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 19:11:26.331  6970  6970 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 19:11:26.331  6970  6970 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:11:26.331  6970  6970 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:11:26.332  6970  6970 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 19:11:26.332  6970  6970 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-06 19:11:26.334  6970  6970 V BluetoothMapService: Handler(): got msg=4
09-06 19:11:26.334  6970  6970 D BluetoothMapService: MAP Service closeService in
09-06 19:11:26.334  6970  6970 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 19:11:26.334  6970  6970 V BluetoothMapService: MAP Service closeService out
09-06 19:11:26.336  6970  7419 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-06 19:11:26.336  6970  7419 D BluetoothAdapterProperties: Setting state to 10
09-06 19:11:26.336  6970  7419 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-06 19:11:26.336  6970  6970 D BluetoothMapService: cleanup()
09-06 19:11:26.336  6970  6970 D BluetoothMapService: MAP Service closeService in
09-06 19:11:26.336  6970  6970 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-06 19:11:26.336  6970  6970 V BluetoothMapService: MAP Service closeService out
09-06 19:11:26.337  1032  1094 D BluetoothManagerService: Message: 60
09-06 19:11:26.337  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-06 19:11:26.337  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-06 19:11:26.338  6970  7419 I BluetoothAdapterState: Entering OffState
09-06 19:11:26.338  6829  6850 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-06 19:11:26.344  6829  6850 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 19:11:26.344  6829  6850 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:11:26.345  1032  1094 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:11:26.345  6829  6850 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:11:26.346  1878  2362 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:11:26.347  1878  2583 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:11:26.348  6829  6850 D BluetoothMap: onBluetoothStateChange: up=false
09-06 19:11:26.349  1032  1094 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:11:26.349  1878  1893 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:11:26.350  6829  6850 D BluetoothPan: onBluetoothStateChange on: false
,09-06 19:11:26.353  1032  1094 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-06 19:11:26.353  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-06 19:11:26.355  1032  1094 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-06 19:11:26.355  1032  1094 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-06 19:11:26.355  1032  1094 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@287060dd mBinding = false
09-06 19:11:26.356  1032  1094 D BluetoothManagerService: Sending unbind request.
09-06 19:11:26.360  6970  7423 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-06 19:11:26.362  6970  6970 I GKI_LINUX: GKI_exit_task 1 done
09-06 19:11:26.362  6970  6970 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-06 19:11:26.362  6970  6970 I BluetoothServiceJni: cleanupNative: return from cleanup
09-06 19:11:26.362  6970  6970 I art     : --- WEIRD: removing null entry 248
09-06 19:11:26.362  6970  6970 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-06 19:11:26.362  6970  6970 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,09-06 19:11:26.365  6970  6970 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-06 19:11:26.366  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-06 19:11:26.368  6970  6970 I art     : System.exit called, status: 0
09-06 19:11:26.369  6970  6970 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-06 19:11:26.388   331  1381 V AudioFlinger: 6970 died, releasing its sessions
09-06 19:11:26.389   331  1381 V AudioFlinger:  pid 1878 @ 0
09-06 19:11:26.389   331  1381 V AudioFlinger:  pid 3357 @ 1
09-06 19:11:26.389   331  1381 V AudioFlinger:  pid 3357 @ 2
,09-06 19:11:26.392  1969  1969 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
09-06 19:11:26.393  1969  2192 D LGBluetoothAPIService: Message: 101
,09-06 19:11:26.393  1969  2192 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED,
09-06 19:11:26.393  1969  2192 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-06 19:11:26.393  1969  2192 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
09-06 19:11:26.394  6829  6829 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected,
09-06 19:11:26.404  1032  2004 I ActivityManager: Process com.android.bluetooth (pid 6970) has died
09-06 19:11:26.406  1032  2004 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms,
,09-06 19:11:26.406  1032  2004 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,09-06 19:11:26.414  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:26.414  1969  2192 D LGBluetoothAPIService: Message: 2
09-06 19:11:26.414  1969  2192 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
09-06 19:11:26.415  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:11:26.417  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:26.419  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:11:26.423  6829  6829 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-06 19:11:26.423  6829  6829 D LGBluetoothEventManager: [BTUI] clear device connection state
09-06 19:11:26.424  6829  6829 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-06 19:11:26.427  1603  1603 D BluetoothAdapter: 51489737: getState() :  mService = null. Returning STATE_OFF
09-06 19:11:26.427  1603  1603 D BluetoothAdapter: 51489737: getState() :  mService = null. Returning STATE_OFF
,09-06 19:11:26.484  1032  2327 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7613 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
09-06 19:11:26.487  6829  6829 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:11:26.537  7613  7613 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-06 19:11:26.538  7613  7613 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:11:26.538  7613  7613 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,09-06 19:11:26.539  7613  7613 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:11:26.558  7613  7613 D BluetoothAdapterApp: Loading JNI Library
,09-06 19:11:26.593  7613  7613 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@382b459e Instance Count = 1
,09-06 19:11:26.600  7613  7613 D BluetoothAdapterApp: onCreate
,09-06 19:11:26.623  7613  7613 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-06 19:11:26.623  7613  7613 D ProfileConfigQcom: Adding HeadsetService
09-06 19:11:26.623  7613  7613 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-06 19:11:26.623  7613  7613 D ProfileConfigQcom: Adding A2dpService
09-06 19:11:26.623  7613  7613 D ProfileConfigQcom: [BTUI] HidService is supported
,09-06 19:11:26.623  7613  7613 D ProfileConfigQcom: Adding HidService
09-06 19:11:26.624  7613  7613 D ProfileConfigQcom: [BTUI] HealthService is supported
09-06 19:11:26.624  7613  7613 D ProfileConfigQcom: Adding HealthService
09-06 19:11:26.624  7613  7613 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,09-06 19:11:26.626  7613  7613 D ProfileConfigQcom: [BTUI] PanService is supported
,09-06 19:11:26.626  7613  7613 D ProfileConfigQcom: Adding PanService
09-06 19:11:26.626  7613  7613 D ProfileConfigQcom: [BTUI] GattService is supported
09-06 19:11:26.626  7613  7613 D ProfileConfigQcom: Adding GattService
09-06 19:11:26.626  7613  7613 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-06 19:11:26.627  7613  7613 D ProfileConfigQcom: Adding BluetoothMapService
09-06 19:11:26.627  7613  7613 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-06 19:11:26.628  7613  7613 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 19:11:26.629  7613  7613 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:26.629  7613  7613 V BluetoothPbapReceiver: ***********state = 10
09-06 19:11:26.631  7613  7613 V LGMDMManagerInternal: Create singleton instance
,09-06 19:11:26.698  2201  2201 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:11:26.704  7613  7613 D LGBluetoothAPIServer: [BTUI] onCreate()
09-06 19:11:26.704  7613  7613 D LGBluetoothAPIServer: [BTUI] onBind()
09-06 19:11:26.705  6829  6829 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-06 19:11:26.711  1969  1969 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,09-06 19:11:26.712  1969  2192 D LGBluetoothAPIService: Message: 100
09-06 19:11:26.712  1969  2192 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-06 19:11:26.723  6829  6829 D BluetoothPermissionRequest: onReceive
09-06 19:11:26.728  6829  6829 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-06 19:11:26.728  6829  6829 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,09-06 19:11:26.732  6829  6829 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:11:26.740  7613  7613 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,09-06 19:11:26.744  7613  7613 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:26.748  7613  7613 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:11:26.749  7613  7613 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:11:26.749  7613  7613 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:11:26.750  7613  7613 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:26.750  7613  7613 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-06 19:11:26.759  6900  6900 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-06 19:11:28.388  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:11:28.388  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:11:28.556  1603  1603 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-06 19:11:28.629  2077  2077 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-06 19:11:28.654  1032  1090 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7642 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-06 19:11:28.672  1032  1480 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-06 19:11:28.684  1032  1032 D administrator: Handling package changes for user 0
09-06 19:11:28.687  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-06 19:11:28.688  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,09-06 19:11:28.727  7642  7642 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-06 19:11:28.735  2077  2077 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-06 19:11:28.806  1032  1032 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,09-06 19:11:28.806  1032  1032 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-06 19:11:28.820  7642  7642 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:11:28.820  7642  7642 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:11:28.839  1032  1089 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:11:28.844  1032  1089 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-06 19:11:28.852  2077  2077 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-06 19:11:28.852  2469  2469 V GmsNetworkLocationProvi: DISABLE
09-06 19:11:28.877  1032  1089 D LocationProviderProxy: applying state to connected service
,09-06 19:11:28.880  2469  2469 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-06 19:11:28.968  7642  7686 I Babel   : MmsConfig: mnc/mcc: 0/0
09-06 19:11:28.968  7642  7686 I Babel   : MmsConfig.loadMmsSettings
,09-06 19:11:28.977  7642  7686 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,09-06 19:11:28.977  7642  7686 I Babel   : MmsConfig.loadFromDatabase
,09-06 19:11:29.009  7642  7686 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-06 19:11:29.009  7642  7686 I Babel   : MmsConfig.loadFromResources
09-06 19:11:29.013  7642  7686 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-06 19:11:29.014  7642  7686 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-06 19:11:29.018  7642  7642 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:11:29.029  7642  7685 W AudioCapabilities: Unsupported mime audio/evrc
09-06 19:11:29.030  7642  7685 W AudioCapabilities: Unsupported mime audio/qcelp
,09-06 19:11:29.034  7642  7685 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-06 19:11:29.044  1817  7690 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-06 19:11:29.044  1817  7690 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,09-06 19:11:29.048  7019  7019 I AppUp4:CustModeStarterReceiver: onReceive
,09-06 19:11:29.058  7019  7019 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@26a68538
09-06 19:11:29.058  7642  7685 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-06 19:11:29.058  7019  7019 D AppUp4:CustFacade: isCustomizationCompleted : false
09-06 19:11:29.058  7019  7019 D AppUp4:CustFacade: isPhone : true
09-06 19:11:29.059  7019  7019 D AppUp4:CustModeStarterReceiver: begin check event
09-06 19:11:29.059  7019  7019 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-06 19:11:29.060  1817  4758 I Icing   : updateResources: need to parse e{com.google.android.gms}
09-06 19:11:29.061  7642  7685 W AudioCapabilities: Unsupported mime audio/qcelp
09-06 19:11:29.063  7642  7685 W AudioCapabilities: Unsupported mime audio/evrc
09-06 19:11:29.086  7642  7685 W VideoCapabilities: Unsupported mime video/x-ms-wmv
09-06 19:11:29.088  7642  7685 W VideoCapabilities: Unsupported mime video/divx
,09-06 19:11:29.090  7642  7685 W VideoCapabilities: Unsupported mime video/divx311,
09-06 19:11:29.092  7642  7685 W VideoCapabilities: Unsupported mime video/divx4
09-06 19:11:29.099  7642  7685 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-06 19:11:29.106  1032  1575 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7693 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-06 19:11:29.110  1032  1645 I ActivityManager: Killing 6623:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
09-06 19:11:29.128  6917  6917 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,09-06 19:11:29.129  7642  7685 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
09-06 19:11:29.129  6917  6917 W System.err: android.os.DeadObjectException
09-06 19:11:29.129  6917  6917 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-06 19:11:29.129  6917  6917 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-06 19:11:29.129  6917  6917 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-06 19:11:29.129  6917  6917 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-06 19:11:29.129  6917  6917 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-06 19:11:29.129  6917  6917 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-06 19:11:29.129  6917  6917 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 19:11:29.129  6917  6917 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 19:11:29.130  6917  6917 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:11:29.130  6917  6917 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 19:11:29.130  6917  6917 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:11:29.130  6917  6917 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:11:29.130  6917  6917 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 19:11:29.130  6917  6917 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 19:11:29.130  6917  6917 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-06 19:11:29.130  6917  6917 W System.err: android.os.DeadObjectException
09-06 19:11:29.131  6917  6917 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-06 19:11:29.131  6917  6917 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-06 19:11:29.131  6917  6917 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-06 19:11:29.131  6917  6917 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-06 19:11:29.131  6917  6917 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-06 19:11:29.131  6917  6917 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-06 19:11:29.131  6917  6917 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 19:11:29.131  6917  6917 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 19:11:29.131  6917  6917 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:11:29.131  6917  6917 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 19:11:29.131  6917  6917 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:11:29.131  6917  6917 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:11:29.131  6917  6917 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 19:11:29.131  6917  6917 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 19:11:29.131  6917  6917 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-06 19:11:29.131  6917  6917 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-06 19:11:29.139  7642  7685 W AudioCapabilities: Unsupported mime audio/eac3
09-06 19:11:29.140  7642  7685 W AudioCapabilities: Unsupported mime audio/ac3
09-06 19:11:29.140  7642  7685 W AudioCapabilities: Unsupported mime audio/g726
,09-06 19:11:29.141  7642  7685 W AudioCapabilities: Unsupported mime audio/wma-voice
09-06 19:11:29.142  7642  7685 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-06 19:11:29.143  7642  7685 W AudioCapabilities: Unsupported mime audio/adpcm
09-06 19:11:29.144  7642  7685 W VideoCapabilities: Unsupported mime video/theora
09-06 19:11:29.146  7642  7685 W VideoCapabilities: Unsupported mime video/mjpg
09-06 19:11:29.318  1032  1645 E libprocessgroup: failed to kill 1 processes for processgroup 6623
,09-06 19:11:29.450  1032  1968 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-06 19:11:29.461  6917  6917 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-06 19:11:29.461  6917  6917 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-06 19:11:29.483  7693  7693 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:11:29.483  7693  7693 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:11:29.483  7693  7693 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-06 19:11:29.485  7693  7693 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-06 19:11:29.485  7693  7693 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-06 19:11:29.501  1032  2003 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7714 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-06 19:11:29.502  6917  6917 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-06 19:11:29.556  7714  7714 D UEI.SmartControl: Quickset Services start...
,09-06 19:11:29.561  7693  7693 I SystemConfig: BUILD Country: EU
09-06 19:11:29.561  7693  7693 I SystemConfig: BUILD Operator: OPEN
09-06 19:11:29.562  7714  7714 I UEI.SmartControl: Manufacture = LGE
09-06 19:11:29.563  7714  7714 D UEI.SmartControl: Id = LGNevo
09-06 19:11:29.566  7714  7714 D UEI.SmartControl: File observer start...
09-06 19:11:29.567  7714  7714 E UEI.SmartControl: IR Port is disabled: false
09-06 19:11:29.568  7714  7714 D UEI.SmartControl: Starting file observer...
09-06 19:11:29.568  7714  7714 D UEI.SmartControl: Extracting JNI libs...
09-06 19:11:29.569  7714  7714 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,09-06 19:11:29.597  1032  2323 I ActivityManager: Killing 6917:com.lge.qremote/u0a112 (adj 15): empty #17
,09-06 19:11:29.652  7714  7714 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-06 19:11:29.652  7714  7714 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,09-06 19:11:29.652  7714  7714 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-06 19:11:29.672  1032  1968 W libprocessgroup: failed to open /acct/uid_10112/pid_6917/cgroup.procs: No such file or directory
,09-06 19:11:29.683  7714  7714 I UEI.SmartControl: --- Selecting new region: 6
,09-06 19:11:29.685  7714  7714 I UEI.SmartControl: Model = LG-D855
09-06 19:11:29.685  7693  7738 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-06 19:11:29.685  7693  7738 I SystemConfig: existFile = false
09-06 19:11:29.686  7714  7714 D UEI.SmartControl: QS Service created
09-06 19:11:29.686  7693  7738 I SystemConfig: canReadFile = false
09-06 19:11:29.687  7693  7738 I SystemConfig: systemFeature RCS result false
09-06 19:11:29.688  7693  7738 D SystemConfig: refreshRcsSupport() :false
09-06 19:11:29.757  1032  2323 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7740 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-06 19:11:29.779  7714  7714 I UEI.SmartControl: Service initServices...
,09-06 19:11:29.785  7714  7714 D UEI.SmartControl: QS start get config
,09-06 19:11:29.842  7714  7714 D UEI.SmartControl: Loading JNI Libs...
,09-06 19:11:29.855  7740  7740 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:11:29.856  7740  7740 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-06 19:11:29.856  7740  7740 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-06 19:11:29.856  7740  7740 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-06 19:11:29.940  7740  7740 I AppConfig: Total System Memory = 2995761152
,09-06 19:11:29.951  7740  7740 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-06 19:11:29.999  1032  2327 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7760 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:11:30.000  1032  2327 I ActivityManager: Killing 7064:com.lge.email/u0a23 (adj 15): empty #17
,09-06 19:11:30.132  1032  1048 W libprocessgroup: failed to open /acct/uid_10023/pid_7064/cgroup.procs: No such file or directory
,09-06 19:11:30.144  7714  7714 I UEI.SmartControl: Supports setup maps: true
,09-06 19:11:30.147  7714  7714 D UEI.SmartControl: QS start statue = true Error code = 0
09-06 19:11:30.147  7714  7714 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-06 19:11:30.147  7714  7714 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-06 19:11:30.147  7714  7714 I UEI.SmartControl: ### init IR Blaster...
,09-06 19:11:30.155  7714  7714 D serial_port: Configuring serial port
09-06 19:11:30.159  7714  7714 E UEI.SmartControl: UEIBLaster setting for 616
09-06 19:11:30.159  7714  7714 I UEI.SmartControl: Setting serial record hearder size = 2
09-06 19:11:30.159  7714  7714 I UEI.SmartControl: configuring settings for MAXQ616
09-06 19:11:30.159  7714  7714 I UEI.SmartControl: Get version...
09-06 19:11:30.177  7714  7777 D UEI.SmartControl: serial port data available: 21
,09-06 19:11:30.204  7714  7714 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-06 19:11:30.204  7714  7714 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-06 19:11:30.204  7714  7714 I UEI.SmartControl: QS saving settings...
09-06 19:11:30.205  7714  7714 D UEI.SmartControl: IR Blaster version: 25672567
,09-06 19:11:30.223  7714  7777 D UEI.SmartControl: serial port data available: 4
,09-06 19:11:30.258  7714  7784 I UEI.SmartControl: Device manager: loading config....
09-06 19:11:30.258  7714  7784 D UEI.SmartControl: ----------- loading internal config...
,09-06 19:11:30.270  7714  7714 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-06 19:11:30.270  7714  7784 E UEI.SmartControl: Loading SETTINGS...
09-06 19:11:30.273  7714  7714 E UEI.SmartControl: Services init done
09-06 19:11:30.273  7714  7714 D UEI.SmartControl: QS Service init finished
,09-06 19:11:30.276  7714  7784 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-06 19:11:30.276  7714  7714 D UEI.SmartControl: QS Service version name: 2.1.91
09-06 19:11:30.277  7714  7714 D UEI.SmartControl: QS Service version code: 201091
09-06 19:11:30.279  7714  7714 D UEI.SmartControl: Service requested: Control
09-06 19:11:30.282  7714  7714 D UEI.SmartControl: Service.onUnbind: IControl
09-06 19:11:30.283  7714  7714 D UEI.SmartControl: Service.onDestroy
,09-06 19:11:30.283  7714  7714 D UEI.SmartControl: Lock is in USE false
09-06 19:11:30.283  7714  7714 D UEI.SmartControl: unbind internal service
09-06 19:11:30.290  7714  7714 D serial_port: close(fd = 25)
,09-06 19:11:30.295  7714  7714 I UEI.SmartControl: Serial port is closed.
09-06 19:11:30.295  7714  7714 I UEI.SmartControl: Serial port is closed.
09-06 19:11:30.295  7714  7714 D UEI.SmartControl: Blaster closed
09-06 19:11:30.295  7714  7714 D UEI.SmartControl: Shut down QS...
09-06 19:11:30.295  7714  7714 D UEI.SmartControl: Stopping QS lib
09-06 19:11:30.295  7714  7714 D UEI.SmartControl: QS lib stop result = true
09-06 19:11:30.295  7714  7714 D UEI.SmartControl: Stopped QS lib
09-06 19:11:30.296  7714  7714 D UEI.SmartControl: Stopped file observer...
09-06 19:11:30.296  7714  7714 D UEI.SmartControl: QS shutdown complete
09-06 19:11:30.296  7714  7782 I UEI.SmartControl: Notify AllClients services are ready: 11
09-06 19:11:30.297  7714  7782 D UEI.SmartControl: -----service ready thread exits
09-06 19:11:30.298  7714  7714 D UEI.SmartControl: QS Service created
09-06 19:11:30.313  7714  7714 I UEI.SmartControl: Service initServices...
09-06 19:11:30.313  7714  7714 D UEI.SmartControl: QS start get config
,09-06 19:11:30.324  7760  7760 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
09-06 19:11:30.387  7760  7760 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:11:30.387  7760  7760 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:11:30.437  7760  7760 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-06 19:11:30.457  7760  7760 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-06 19:11:30.460  7760  7760 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-06 19:11:30.493  7760  7760 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-06 19:11:30.493  7760  7760 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-06 19:11:30.514  1032  1929 I ActivityManager: Killing 6941:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-06 19:11:30.698  1032  1049 W libprocessgroup: failed to open /acct/uid_10026/pid_6941/cgroup.procs: No such file or directory
,09-06 19:11:30.711  4627  7806 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-06 19:11:30.768  7714  7714 I UEI.SmartControl: Supports setup maps: true
,09-06 19:11:30.776  7714  7714 D UEI.SmartControl: QS start statue = true Error code = 0
09-06 19:11:30.776  7714  7714 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-06 19:11:30.776  7714  7714 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-06 19:11:30.776  7714  7714 I UEI.SmartControl: ### init IR Blaster...
09-06 19:11:30.780  7714  7714 D serial_port: Configuring serial port
09-06 19:11:30.780  7714  7714 E UEI.SmartControl: UEIBLaster setting for 616
09-06 19:11:30.780  7714  7714 I UEI.SmartControl: Setting serial record hearder size = 2
09-06 19:11:30.780  7714  7714 I UEI.SmartControl: configuring settings for MAXQ616
09-06 19:11:30.780  7714  7714 I UEI.SmartControl: Get version...
09-06 19:11:30.788  1032  2028 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7807 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-06 19:11:30.797  7714  7811 D UEI.SmartControl: serial port data available: 21
09-06 19:11:30.800  2850  2866 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-06 19:11:30.805  2850  2866 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@34f6e14f on behalf of 7760
,09-06 19:11:30.821  7760  7760 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
09-06 19:11:30.824  7714  7714 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-06 19:11:30.824  7714  7714 I UEI.SmartControl: IR Blaster version: 256702256704300002
,09-06 19:11:30.824  7714  7714 I UEI.SmartControl: QS saving settings...
09-06 19:11:30.824  7714  7714 D UEI.SmartControl: IR Blaster version: 25672567
09-06 19:11:30.843  7714  7811 D UEI.SmartControl: serial port data available: 4
,09-06 19:11:30.850  7760  7760 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
09-06 19:11:30.871  7714  7830 I UEI.SmartControl: Device manager: loading config....
09-06 19:11:30.871  7714  7830 D UEI.SmartControl: ----------- loading internal config...
09-06 19:11:30.871  7714  7714 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-06 19:11:30.874  7714  7714 E UEI.SmartControl: Services init done
09-06 19:11:30.874  7714  7714 D UEI.SmartControl: QS Service init finished
09-06 19:11:30.875  7714  7714 D UEI.SmartControl: QS Service version name: 2.1.91
09-06 19:11:30.875  7714  7714 D UEI.SmartControl: QS Service version code: 201091
09-06 19:11:30.876  7714  7714 D UEI.SmartControl: Service requested: Control
09-06 19:11:30.877  7807  7807 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
09-06 19:11:30.878  7714  7830 E UEI.SmartControl: Loading SETTINGS...
09-06 19:11:30.881  7714  7714 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-06 19:11:30.884  1032  1048 I ActivityManager: Killing 6402:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,09-06 19:11:30.887  7714  7830 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-06 19:11:30.910  7714  7829 I UEI.SmartControl: Notify AllClients services are ready: 0
09-06 19:11:30.910  7714  7829 D UEI.SmartControl: -----service ready thread exits
,09-06 19:11:30.982  1032  2004 W libprocessgroup: failed to open /acct/uid_1000/pid_6402/cgroup.procs: No such file or directory
09-06 19:11:30.986  7714  7714 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@32dabce4 that was originally bound here
09-06 19:11:30.986  7714  7714 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@32dabce4 that was originally bound here
09-06 19:11:30.986  7714  7714 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
09-06 19:11:30.986  7714  7714 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
09-06 19:11:30.986  7714  7714 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
09-06 19:11:30.986  7714  7714 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
09-06 19:11:30.986  7714  7714 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
09-06 19:11:30.986  7714  7714 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
09-06 19:11:30.986  7714  7714 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
09-06 19:11:30.986  7714  7714 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
09-06 19:11:30.986  7714  7714 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
09-06 19:11:30.986  7714  7714 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
09-06 19:11:30.986  7714  7714 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
09-06 19:11:30.986  7714  7714 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:11:30.986  7714  7714 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:11:30.986  7714  7714 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 19:11:30.986  7714  7714 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:11:30.986  7714  7714 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:11:30.986  7714  7714 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 19:11:30.986  7714  7714 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-06 19:11:30.991  7714  7714 D UEI.SmartControl: Internal service binding...
,09-06 19:11:31.031  7807  7807 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-06 19:11:31.031  7807  7807 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-06 19:11:31.031  7807  7807 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-06 19:11:31.031  7807  7807 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-06 19:11:31.031  7807  7807 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-06 19:11:31.031  7807  7807 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,09-06 19:11:31.073  1032  1048 I ActivityManager: Killing 7094:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-06 19:11:31.131  1032  1967 W libprocessgroup: failed to open /acct/uid_10046/pid_7094/cgroup.procs: No such file or directory
,09-06 19:11:31.283  7714  7789 D UEI.SmartControl: Internal timer expired: 2
,09-06 19:11:31.387  1032  2028 V SIM_STK : Menu title from STK is T-Mobile
,09-06 19:11:31.401  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:11:31.402  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37a6ad0a added. We now have 6 listener(s)
,09-06 19:11:31.402  6732  6810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:11:31.404  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:11:31.405  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a6ce97b added. We now have 7 listener(s)
09-06 19:11:31.405  6732  6810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:11:31.405  6732  6810 I System.out: IsBluetoothEnabled
09-06 19:11:31.407  1032  1929 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:31.407  1032  1929 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-06 19:11:31.408  1032  1094 D BluetoothManagerService: Message: 2
09-06 19:11:31.411  6732  6810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:31.412  1032  1968 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:31.412  1032  1968 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-06 19:11:31.425  1032  1094 D BluetoothManagerService: Message: 1
09-06 19:11:31.425  1032  1094 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-06 19:11:31.425  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 19:11:31.426  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:11:31.426  1032  1032 D Ulp_jni : JNI:system_update. Event-4
,09-06 19:11:31.428  4627  7806 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 716 ms] updated apps [took 716 ms] 
09-06 19:11:31.444  1032  1094 D BluetoothManagerService: Message: 20
09-06 19:11:31.444  1032  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@921b31b:true
09-06 19:11:31.445  7613  7613 D BluetoothAdapterState: make
,09-06 19:11:31.450  7613  7613 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-06 19:11:31.451  7613  7613 I bluedroid-qcom: init
09-06 19:11:31.451  7613  7845 I BluetoothAdapterState: Entering OffState
09-06 19:11:31.452  7613  7613 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-06 19:11:31.452  7613  7613 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-06 19:11:31.452  7613  7613 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-06 19:11:31.452  7613  7613 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-06 19:11:31.452  7613  7613 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-06 19:11:31.454  7613  7613 I bluedroid-qcom: get_profile_interface socket
09-06 19:11:31.455  7613  7613 I bluedroid-qcom: get_profile_interface map_client
09-06 19:11:31.448  7848  7848 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:11:31.448  7848  7848 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-06 19:11:31.456  7613  7849 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-06 19:11:31.459  7613  7849 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-06 19:11:31.462  7613  7849 D BluetoothAdapterProperties: Name is: G3
09-06 19:11:31.462  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-06 19:11:31.462  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
09-06 19:11:31.462  7848  7848 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-06 19:11:31.462  7848  7848 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-06 19:11:31.462  7848  7848 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-06 19:11:31.463  7848  7848 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-06 19:11:31.463  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-06 19:11:31.463  1032  1094 D BluetoothManagerService: Message: 40
09-06 19:11:31.463  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-06 19:11:31.464  7613  7629 I bluedroid-qcom: config_hci_snoop_log
09-06 19:11:31.466  1032  1094 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-06 19:11:31.466  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-06 19:11:31.468  7848  7848 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-06 19:11:31.468  7848  7848 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,09-06 19:11:31.473  7613  7845 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-06 19:11:31.473  7613  7845 D BluetoothAdapterProperties: Setting state to 11
09-06 19:11:31.473  7613  7845 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-06 19:11:31.474  1032  1094 D BluetoothManagerService: Message: 60
09-06 19:11:31.474  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-06 19:11:31.474  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-06 19:11:31.477  6829  6829 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-06 19:11:31.478  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:11:31.479  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:31.481  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:11:31.488  7613  7845 I LGBluetoothServiceJni: classInitNative: succeeds
09-06 19:11:31.490  7613  7613 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 19:11:31.490  7613  7613 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:31.490  7613  7613 V BluetoothPbapReceiver: ***********state = 11
09-06 19:11:31.494  2201  2201 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:11:31.497  7613  7845 D BluetoothBondStateMachine: make
09-06 19:11:31.503  7613  7845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10ed7877
09-06 19:11:31.503  7613  7845 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-06 19:11:31.503  7613  7845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10ed7877
09-06 19:11:31.503  7613  7845 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-06 19:11:31.504  7613  7845 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-06 19:11:31.506  7613  7855 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-06 19:11:31.512  7613  7845 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:11:31.521  6829  6829 D BluetoothPermissionRequest: onReceive
09-06 19:11:31.522  7613  7845 E BluetoothAdapterService: File transfer profiles supported!!
,09-06 19:11:31.523  7613  7613 D HeadsetService: Received start request. Starting profile...
09-06 19:11:31.524  7613  7613 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 19:11:31.524  7613  7613 D LGBluetoothHfpAdapter: Version 1.6
09-06 19:11:31.529  7613  7613 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-06 19:11:31.530  7613  7845 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:11:31.530  7613  7613 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 19:11:31.531  7613  7613 D HeadsetStateMachine: make
09-06 19:11:31.531  6829  6829 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:11:31.540  7613  7845 E BluetoothAdapterService: File transfer profiles supported!!
,09-06 19:11:31.545  7613  7845 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:11:31.551  7613  7845 E BluetoothAdapterService: File transfer profiles supported!!
09-06 19:11:31.557  7613  7845 E BluetoothAdapterService: File transfer profiles supported!!
,09-06 19:11:31.578  7613  7613 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:11:31.578  7613  7613 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-06 19:11:31.583  7613  7613 D HeadsetStateMachine: max_hf_connections = 1
09-06 19:11:31.583  7613  7613 I bluedroid-qcom: get_profile_interface handsfree
09-06 19:11:31.586  7613  7845 V LGMDMManager: Create singleton instance
09-06 19:11:31.586  7613  7613 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-06 19:11:31.587   331  3958 V AudioPolicyService: registerClient() client 0xb1022b40, uid 1002
09-06 19:11:31.587  7613  7845 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-06 19:11:31.587   331  3958 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-06 19:11:31.587   331  3958 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 19:11:31.587   331  3958 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 19:11:31.588  7613  7613 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-06 19:11:31.589   331  1382 V AudioFlinger: registerClient() client 0xb55815f8, pid 7613
09-06 19:11:31.589   331  1376 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:11:31.589   331  1376 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:11:31.589  3357  3373 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:11:31.589  3357  3373 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:11:31.589  1878  1894 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:11:31.590  1878  1894 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:11:31.590  1603  2557 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:11:31.590  1603  2557 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:11:31.590  1032  1049 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:11:31.590  1032  1049 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-06 19:11:31.590  7613  7629 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-06 19:11:31.591   331  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:11:31.591   331  1377 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:11:31.591  1603  1622 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:11:31.591  1603  1622 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:11:31.591  3357  3372 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:11:31.591  3357  3372 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:11:31.591  1878  2362 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:11:31.591  1878  2362 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:11:31.594  1032  2028 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:11:31.594  1032  2028 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-06 19:11:31.594  7613  7629 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-06 19:11:31.595  7613  7613 V ToneGenerator: Create Track: 0xb4928a80
09-06 19:11:31.595  7613  7613 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-06 19:11:31.595  7613  7613 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-06 19:11:31.595  7613  7629 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-06 19:11:31.595  7613  7629 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-06 19:11:31.595   331  1381 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-06 19:11:31.595   331  1381 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-06 19:11:31.595   331  1381 V AudioPolicyManagerEx: Aud,ioPolicyManagerEx: getOutputForDevice
09-06 19:11:31.595   331  1381 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 19:11:31.596   331  3958 I AudioFlinger: isAudioPlaybackHookOn() false
,09-06 19:11:31.597   331   331 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-06 19:11:31.597   331   331 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-06 19:11:31.597   331   331 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-06 19:11:31.597   331   331 V AudioPolicyManagerEx: getOutput() returns output 2
09-06 19:11:31.598  7613  7613 V AudioSystem: getLatency() output 2, latency 50
09-06 19:11:31.598  7613  7613 V AudioSystem: getFrameCount() output 2, frameCount 960
09-06 19:11:31.598  7613  7613 V AudioTrack: createTrack_l() output 2 afLatency 50
09-06 19:11:31.600   331  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-06 19:11:31.600   331  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-06 19:11:31.600   331  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-06 19:11:31.600   331  1382 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-06 19:11:31.600   331  1382 V AudioFlinger: createTrack() lSessionId: 23
09-06 19:11:31.601  7613  7613 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-06 19:11:31.601   331  1382 V AudioFlinger: acquiring 23 from 7613, for 7613
09-06 19:11:31.601   331  1382 V AudioFlinger:  added new entry for 23
09-06 19:11:31.601  7613  7613 V ToneGenerator: ToneGenerator INIT OK, time: 219852
09-06 19:11:31.602  7613  7613 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10ed7877
09-06 19:11:31.602  7613  7856 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-06 19:11:31.602  7613  7856 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-06 19:11:31.603  7613  7856 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-06 19:11:31.603  7613  7856 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-06 19:11:31.603   331  3957 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7613
09-06 19:11:31.603   331  3957 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-06 19:11:31.603   331  3957 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-06 19:11:31.603  7613  7613 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10ed7877
09-06 19:11:31.603   331  3957 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-06 19:11:31.603   331  3957 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-06 19:11:31.604   331  3957 V voice   : voice_set_parameters: exit with code(0)
09-06 19:11:31.604   331  3957 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-06 19:11:31.604   331  3957 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-06 19:11:31.604   331  3957 V msm8974_platform: platform_set_parameters: exit with code(0)
09-06 19:11:31.604   331  3957 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-06 19:11:31.604   331  3957 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-06 19:11:31.604   331  3957 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-06 19:11:31.604  7613  7856 V ToneGenerator: ToneGenerator destructor
09-06 19:11:31.604  7613  7856 V ToneGenerator: stopTone
09-06 19:11:31.604  7613  7856 V ToneGenerator: Delete Track: 0xb4928a80
09-06 19:11:31.605  7613  7856 V AudioTrack: ~AudioTrack, releasing session id from 7613 on behalf of 7613
09-06 19:11:31.605   331  1381 V AudioFlinger: releasing 23 from 7613 for 7613
09-06 19:11:31.605   331  1381 V AudioFlinger:  decremented refcount to 0
09-06 19:11:31.605   331  1381 V AudioFlinger: purging stale effects
09-06 19:11:31.605   331  1381 V AudioPolicyService: AudioCommandThread() ad,ding release output 2
09-06 19:11:31.606   331  1381 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-06 19:11:31.606   331  1257 V AudioPolicyService: AudioCommandThread() waking up
09-06 19:11:31.606   331  1257 V AudioPolicyService: AudioCommandThread() processing release output 2
09-06 19:11:31.606   331  1257 V AudioPolicyManager: releaseOutput() 2
09-06 19:11:31.606   331  1257 V AudioPolicyService: AudioCommandThread() going to sleep
09-06 19:11:31.606   331  1381 V AudioFlinger: PlaybackThread::Track destructor
09-06 19:11:31.606   331  1381 V AudioFlinger: removeClient_l() pid 7613, calling pid 331
09-06 19:11:31.607  7613  7613 D A2dpService: Received start request. Starting profile...
09-06 19:11:31.608  7613  7613 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-06 19:11:31.609  7613  7613 V Avrcp   : make
,09-06 19:11:31.610  7613  7613 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-06 19:11:31.610  7613  7613 I bluedroid-qcom: get_profile_interface avrcp
09-06 19:11:31.621  7613  7613 V AudioManager: registerRemoteController: size of Media player list: 0
,09-06 19:11:31.624  7613  7613 E AudioManager: No RCC entry present to update
09-06 19:11:31.624  7613  7613 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-06 19:11:31.628  7613  7613 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-06 19:11:31.630  7613  7613 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-06 19:11:31.630  7613  7613 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-06 19:11:31.634  7613  7613 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-06 19:11:31.759  1032  1575 V SIM_STK : Menu title from STK is T-Mobile
09-06 19:11:31.759  1032  1575 V SIM_STK : Menu title from STK is T-Mobile
,09-06 19:11:31.831  1032  2049 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-06 19:11:31.841  7613  7613 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-06 19:11:31.845  7613  7613 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-06 19:11:31.845  7613  7613 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-06 19:11:31.845  7613  7613 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-06 19:11:31.845  7613  7613 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-06 19:11:31.845  7613  7613 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 19:11:31.845  7613  7613 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-06 19:11:31.845  7613  7613 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-06 19:11:31.845  7613  7613 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-06 19:11:31.846  7613  7613 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 19:11:31.846  7613  7613 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-06 19:11:31.846  7613  7613 I BluetoothA2dpServiceJni: classInitNative
09-06 19:11:31.846  7613  7613 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 19:11:31.846  7613  7613 D A2dpStateMachine: make
,09-06 19:11:31.850  7613  7613 I bluedroid-qcom: get_profile_interface a2dp
09-06 19:11:31.851  7613  7863 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-06 19:11:31.857  7613  7613 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-06 19:11:31.857  7613  7613 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-06 19:11:31.860  7613  7613 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10ed7877
09-06 19:11:31.860  7613  7862 D A2dpStateMachine: Enter Disconnected: -2
,09-06 19:11:31.863  7613  7613 I BluetoothHidServiceJni: classInitNative: succeeds
09-06 19:11:31.868  7613  7613 D HidService: Received start request. Starting profile...
09-06 19:11:31.868  7613  7613 I bluedroid-qcom: get_profile_interface hidhost
09-06 19:11:31.868  7613  7613 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10ed7877
09-06 19:11:31.870  7613  7613 I BluetoothHealthServiceJni: classInitNative: succeeds
09-06 19:11:31.871  7613  7613 D HealthService: Received start request. Starting profile...
09-06 19:11:31.876  7613  7613 I bluedroid-qcom: get_profile_interface health
,09-06 19:11:31.876  7613  7613 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-06 19:11:31.876  7613  7613 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10ed7877
09-06 19:11:31.878  7613  7613 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-06 19:11:31.880  7613  7613 D PanService: Received start request. Starting profile...
09-06 19:11:31.880  7613  7613 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 19:11:31.880  7613  7613 I bluedroid-qcom: get_profile_interface pan
09-06 19:11:31.888  7613  7613 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-06 19:11:31.889  7613  7613 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10ed7877
,09-06 19:11:31.890  7613  7613 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-06 19:11:31.899  7613  7613 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 19:11:31.900  7613  7613 D BtGatt.GattService: Received start request. Starting profile...
09-06 19:11:31.900  7613  7613 D BtGatt.GattService: start()
09-06 19:11:31.900  7613  7613 I bluedroid-qcom: get_profile_interface gatt
09-06 19:11:31.900  7613  7613 D BtGatt.AdvertiseManager: advertise manager created
09-06 19:11:31.913  7613  7613 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10ed7877
,09-06 19:11:31.915  7613  7613 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10ed7877
09-06 19:11:31.915  7613  7613 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-06 19:11:31.916  7613  7613 V BluetoothMapService: BluetoothMapBinder()
09-06 19:11:31.918  7613  7613 D BluetoothMapService: Received start request. Starting profile...
09-06 19:11:31.918  7613  7613 D BluetoothMapService: start()
09-06 19:11:31.922  7613  7613 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-06 19:11:31.923  7613  7613 D BluetoothMapEmailAppObserver: createReceiver()
09-06 19:11:31.924  7613  7613 D BluetoothMapEmailAppObserver: initObservers()
09-06 19:11:31.924  7613  7613 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-06 19:11:31.934  7613  7613 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10ed7877
,09-06 19:11:31.934  7613  7613 D HeadsetStateMachine: Proxy object connected
09-06 19:11:31.935  7613  7613 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-06 19:11:31.935  7613  7613 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-06 19:11:31.942  7613  7613 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 19:11:31.942  7613  7856 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-06 19:11:31.943  7613  7856 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 19:11:31.944  7613  7856 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-06 19:11:31.946  7613  7613 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 19:11:31.949  7613  7613 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:11:31.967  7613  7613 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-06 19:11:31.978  7613  7613 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-06 19:11:31.985  7613  7613 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-06 19:11:31.986  7613  7613 V PanService: [BTUI] SIM Extra State :ABSENT
,09-06 19:11:31.995  7613  7613 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-06 19:11:31.995  7613  7613 V BluetoothMapService: Handler(): got msg=1
09-06 19:11:31.997  7613  7845 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-06 19:11:31.997  7613  7613 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:11:31.997  7613  7845 I bluedroid-qcom: enable
09-06 19:11:31.997  7613  7613 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:11:31.997  7613  7613 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:11:31.998  7613  7613 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:31.998  7613  7613 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-06 19:11:31.998  7613  7845 I bt_hci_bdroid: init
,09-06 19:11:32.006  7613  7845 I bt_vendor: bt-vendor : init
,09-06 19:11:32.006  7613  7845 I bt_vendor: bt-vendor : get_bt_soc_type
,09-06 19:11:32.006  7613  7845 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-06 19:11:32.006  7613  7845 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-06 19:11:32.006  7613  7845 D bt_userial_mct: userial_init
09-06 19:11:32.007  7613  7876 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-06 19:11:32.007  7613  7876 I bt-btu  : btu_task pending for preload complete event
09-06 19:11:32.010  7613  7845 D bt_hci_bdroid: set_power 1
09-06 19:11:32.010  7613  7845 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-06 19:11:32.010  7613  7845 I bt_vendor: Starting hciattach daemon
09-06 19:11:32.010  7613  7845 I bt_vendor: try to set true
09-06 19:11:32.008  7879  7879 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:11:32.008  7879  7879 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-06 19:11:32.044  7880  7880 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-06 19:11:32.116  7890  7890 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-06 19:11:32.128  7892  7892 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-06 19:11:32.153  7894  7894 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 19:11:32.167  7895  7895 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-06 19:11:32.182  7896  7896 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 19:11:32.196  7897  7897 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-06 19:11:32.222  7899  7899 I libmdmdetect: ESOC framework not supported
,09-06 19:11:32.228  7899  7899 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
09-06 19:11:32.239  7899  7899 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-06 19:11:32.239  7899  7899 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-06 19:11:32.239  7899  7899 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-06 19:11:32.239  7899  7899 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-06 19:11:32.240  7899  7899 D bthci_qcomm_common: [BTUI]     LE: Class 2
,09-06 19:11:32.240  7899  7899 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-06 19:11:32.240  7899  7899 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-06 19:11:32.284  7899  7901 E QC-QMI  : qmi_client [7899] 15: failed to locate client data
,09-06 19:11:32.284   481   481 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-06 19:11:32.284   481   481 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
09-06 19:11:32.350  7905  7905 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-06 19:11:32.362  7906  7906 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 19:11:32.434  7613  7845 I bt_vendor: bluetooth satus is on
09-06 19:11:32.435  7613  7845 D bt_hci_bdroid: preload
,09-06 19:11:32.441  7613  7878 D bt_userial_mct: userial_open(port:0)
09-06 19:11:32.441  7613  7878 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-06 19:11:32.445  7613  7878 I bt_vendor: Done intiailizing UART
09-06 19:11:32.446  7613  7878 I bt_vendor: Done intiailizing UART
09-06 19:11:32.446  7613  7878 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-06 19:11:32.447  7613  7878 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-06 19:11:32.447  7613  7876 I bt-btu  : btu_task received preload complete event
09-06 19:11:32.448  7613  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-06 19:11:32.448  7613  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-06 19:11:32.450  7613  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-06 19:11:32.454  7613  7911 D bt_userial_mct: Entering userial_read_thread()
,09-06 19:11:32.458  7613  7876 I         : BTE_InitTraceLevels -- TRC_HCI
,09-06 19:11:32.459  7613  7876 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 19:11:32.459  7613  7876 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-06 19:11:32.459  7613  7876 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 19:11:32.459  7613  7876 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 19:11:32.459  7613  7876 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 19:11:32.459  7613  7876 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 19:11:32.459  7613  7876 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 19:11:32.459  7613  7876 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-06 19:11:32.459  7613  7876 I         : BTE_InitTraceLevels -- TRC_GAP
09-06 19:11:32.459  7613  7876 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 19:11:32.459  7613  7876 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 19:11:32.459  7613  7876 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 19:11:32.459  7613  7876 I         : BTE_InitTraceLevels -- TRC_SMP
,09-06 19:11:32.459  7613  7876 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 19:11:32.459  7613  7876 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-06 19:11:32.567  7613  7876 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,09-06 19:11:32.567  7613  7876 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0214061 
,09-06 19:11:32.580  7613  7876 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0214061 
09-06 19:11:32.626  7613  7849 E bt-btif : Calling BTA_HhEnable
09-06 19:11:32.627  7613  7849 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-06 19:11:32.627  7613  7849 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-06 19:11:32.637  7613  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,09-06 19:11:32.637  7613  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,09-06 19:11:32.637  7613  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-06 19:11:32.638  7613  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-06 19:11:32.638  7613  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-06 19:11:32.643  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,09-06 19:11:32.644  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
09-06 19:11:32.648  7613  7849 D BluetoothAdapterProperties: Name is: G3
,09-06 19:11:32.661  7613  7849 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:11:32.661  7613  7849 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:11:32.661  7613  7849 D bt_hci_bdroid: postload
09-06 19:11:32.663  7613  7878 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 19:11:32.664  7613  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-06 19:11:32.664  7613  7849 D bte_conf: Device ID record 1 : primary
09-06 19:11:32.664  7613  7849 D bte_conf:   vendorId            = 00c4
09-06 19:11:32.665  7613  7849 D bte_conf:   vendorIdSource      = 0001
09-06 19:11:32.665  7613  7849 D bte_conf:   product             = 13a1
09-06 19:11:32.665  7613  7849 D bte_conf:   version             = 1000
09-06 19:11:32.665  7613  7849 D bte_conf:   clientExecutableURL = 
09-06 19:11:32.665  7613  7849 D bte_conf:   serviceDescription  = 
09-06 19:11:32.665  7613  7849 D bte_conf:   documentationURL    = 
09-06 19:11:32.665  7613  7849 D bte_conf: bte_load_did_conf no section named DID2.
09-06 19:11:32.668  7613  7845 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-06 19:11:32.669  7613  7845 D BluetoothAdapterProperties: ScanMode =  20
09-06 19:11:32.669  7613  7845 D BluetoothAdapterProperties: State =  11
,09-06 19:11:32.672  7613  7845 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-06 19:11:32.672  7613  7845 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-06 19:11:32.672  7613  7845 D BluetoothAdapterProperties: Setting state to 12
09-06 19:11:32.672  7613  7845 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-06 19:11:32.673  7613  7849 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-06 19:11:32.673  7613  7849 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-06 19:11:32.678  7913  7913 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-06 19:11:32.678  7913  7913 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:11:32.696  7613  7845 I BluetoothAdapterState: Entering On State
,09-06 19:11:32.701  1032  1094 D BluetoothManagerService: Message: 60
09-06 19:11:32.701  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-06 19:11:32.701  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
09-06 19:11:32.701  7613  7876 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:11:32.701  7613  7876 W bt-smp  : Plain text(LSB ~ MSB) = c2 e7 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:11:32.701  7613  7876 W bt-smp  : Encrypted text(LSB ~ MSB) = e0 e5 ca a7 be 53 c0 ff 47 c7 bb 3e f5 2d 02 1d 
09-06 19:11:32.702  7613  7878 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 19:11:32.702  7613  7876 W bt-btm  : Stopping oneshot timer
09-06 19:11:32.704  7613  7878 D bt_hci_bdroid: Used up Tx Cmd credits
09-06 19:11:32.705  7613  7845 D LGBluetoothServiceAdapter: [BTUI] OnState
09-06 19:11:32.705  7613  7845 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-06 19:11:32.705  7613  7845 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-06 19:11:32.708  7613  7845 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-06 19:11:32.710  7613  7878 D bt_hci_bdroid: Used up Tx Cmd credits
,09-06 19:11:32.715  7613  7911 E bt_mct  : hci lib postload completed
09-06 19:11:32.734  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:11:32.734  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:32.734  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:32.734  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:11:32.734  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:11:32.734  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:11:32.734  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:11:32.734  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:11:32.746  7613  7876 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:11:32.746  7613  7876 W bt-smp  : Plain text(LSB ~ MSB) = 52 89 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:11:32.746  7613  7876 W bt-smp  : Encrypted text(LSB ~ MSB) = 7e 3d f4 7a 45 ae be 7c d6 b1 81 cf 1d 04 5d 04 
09-06 19:11:32.748  7613  7845 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,09-06 19:11:32.749  7613  7876 W bt-btm  : Stopping oneshot timer
09-06 19:11:32.752  7613  7849 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:11:32.752  7613  7849 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-06 19:11:32.755  6732  6732 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:11:32.756  1032  1423 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3519d1a9 type 2 when 220913 com.google.android.gms} when 220913
09-06 19:11:32.760  7613  7876 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:11:32.760  7613  7876 W bt-smp  : Plain text(LSB ~ MSB) = 04 4d 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:11:32.760  7613  7876 W bt-smp  : Encrypted text(LSB ~ MSB) = b0 74 02 2e 6c c9 b6 26 a3 16 ac 3d e2 50 17 9d 
,09-06 19:11:32.763  7613  7876 W bt-btm  : Stopping oneshot timer
09-06 19:11:32.764  6829  6850 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-06 19:11:32.774  6829  6850 D BluetoothPbap: onBluetoothStateChange: up=true
,09-06 19:11:32.784  7613  7876 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:11:32.784  7613  7876 W bt-smp  : Plain text(LSB ~ MSB) = 23 22 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:11:32.784  7613  7876 W bt-smp  : Encrypted text(LSB ~ MSB) = 29 a4 46 d1 73 b7 71 60 ee 13 fc 1f 58 29 1b e9 
09-06 19:11:32.784  7613  7876 W bt-btm  : Stopping oneshot timer
09-06 19:11:32.786  6829  7522 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:11:32.799  1032  1094 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:11:32.807  1032  1032 D BluetoothA2dp: Proxy object connected
09-06 19:11:32.808  7613  7876 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-06 19:11:32.808  7613  7876 W bt-smp  : Plain text(LSB ~ MSB) = 9b 24 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-06 19:11:32.808  7613  7876 W bt-smp  : Encrypted text(LSB ~ MSB) = 9d fd d4 f5 74 54 11 cd 88 d5 88 55 34 75 08 41 
09-06 19:11:32.808  7613  7876 W bt-btm  : Stopping oneshot timer
09-06 19:11:32.809  6829  6850 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:11:32.812  6829  6829 D BluetoothInputDevice: Proxy object connected
09-06 19:11:32.812  6829  6829 D HidProfile: Bluetooth service connected
09-06 19:11:32.816  1878  1893 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 19:11:32.821  1878  1878 D BluetoothHeadset: Proxy object connected
09-06 19:11:32.825  1878  2362 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:11:32.826   327  7935 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-06 19:11:32.827  1032  1092 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-06 19:11:32.835  6829  6829 D BluetoothA2dp: Proxy object connected
09-06 19:11:32.836  6829  6829 D A2dpProfile: Bluetooth service connected
09-06 19:11:32.837  6829  6829 D BluetoothHeadset: Proxy object connected
09-06 19:11:32.837  6829  6829 D HeadsetProfile: Bluetooth service connected
,09-06 19:11:32.840  7936  7936 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-06 19:11:32.940  1032  1094 I art     : Explicit concurrent mark sweep GC freed 27341(1347KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.642ms total 108.800ms
09-06 19:11:32.941  1878  1878 D BluetoothHeadset: Proxy object connected
09-06 19:11:32.942  6829  6848 D BluetoothMap: onBluetoothStateChange: up=true
,09-06 19:11:32.950  1032  1094 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:11:32.950  1032  1032 D BluetoothHeadset: Proxy object connected
09-06 19:11:32.951  1878  1894 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:11:32.952  6829  6829 D BluetoothMap: Proxy object connected
09-06 19:11:32.952  6829  6829 D MapProfile: Bluetooth service connected
09-06 19:11:32.952  6829  6829 D BluetoothMap: getConnectedDevices()
09-06 19:11:32.954  1878  1878 D BluetoothHeadset: Proxy object connected
09-06 19:11:32.954  7613  7630 V BluetoothMapService: getConnectedDevices()
09-06 19:11:32.954  6829  7522 D BluetoothPan: onBluetoothStateChange on: true
09-06 19:11:32.954  6829  7522 D BluetoothPan: onBluetoothStateChange call bindService
,09-06 19:11:32.957  1032  1094 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-06 19:11:32.957  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-06 19:11:32.959  6829  6829 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:11:32.959  6829  6829 D PanProfile: Bluetooth service connected
09-06 19:11:32.959  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-06 19:11:32.962  1032  1094 D BluetoothManagerService: Message: 40
09-06 19:11:32.962  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-06 19:11:32.966  1969  1969 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:32.967  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-06 19:11:32.967  1969  2192 D LGBluetoothAPIService: Message: 1
09-06 19:11:32.968  1969  2192 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-06 19:11:32.968  1969  2192 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-06 19:11:32.969  1969  2192 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-06 19:11:32.980  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:32.984  7613  7613 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:32.985  7613  7613 D BluetoothMapService: STATE_ON
09-06 19:11:32.988  6829  6829 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,09-06 19:11:32.992  6829  6829 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-06 19:11:33.003  6829  6829 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:11:33.017  7613  7613 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10ed7877
09-06 19:11:33.017  7613  7613 V BluetoothPbapService: Pbap Service onCreate
,09-06 19:11:33.017  7613  7613 V BluetoothPbapService: Starting PBAP service
09-06 19:11:33.018  7613  7613 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-06 19:11:33.019  7613  7613 V BluetoothPbapService: Pbap Service onBind
09-06 19:11:33.019  7613  7613 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:33.020  7613  7613 V BluetoothPbapService: state: 12
09-06 19:11:33.020  6829  6829 D BluetoothPbap: Proxy object connected
09-06 19:11:33.020  6829  6829 D PbapServerProfile: Bluetooth service connected
09-06 19:11:33.020  7613  7613 V BluetoothMapService: Handler(): got msg=1
09-06 19:11:33.020  7613  7613 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-06 19:11:33.021  7613  7613 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-06 19:11:33.021  7613  7613 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:33.021  7613  7613 V BluetoothPbapReceiver: ***********state = 12
09-06 19:11:33.022  7613  7939 D BluetoothMapMasInstance: MAS initSocket()
09-06 19:11:33.022  7613  7939 D BluetoothMapMasInstance:   masId = 00
09-06 19:11:33.022  7613  7939 D BluetoothMapMasInstance:   msgTypes = 0e
09-06 19:11:33.022  7613  7939 D BluetoothMapMasInstance:   masName = SMS/MMS
09-06 19:11:33.022  7613  7939 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-06 19:11:33.025  1032  2004 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:33.025  7613  7613 V BluetoothPbapService: Handler(): got msg=1
09-06 19:11:33.026  7613  7613 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-06 19:11:33.027  2201  2201 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:11:33.027  7613  7940 V BluetoothPbapService: Pbap Service initSocket
09-06 19:11:33.027  2201  2201 D c       : Getting all permits...
09-06 19:11:33.027  2201  2201 D a       : Opening database...
09-06 19:11:33.027  7613  7939 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:11:33.028  1032  1929 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:33.029  7613  7940 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:11:33.030  7613  7849 D BluetoothAdapterProperties: Scan Mode:21
09-06 19:11:33.030  7613  7849 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-06 19:11:33.030  7613  7939 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-06 19:11:33.031  7613  7939 V BluetoothMapMasInstance: Succeed to create listening socket 
09-06 19:11:33.031  7613  7939 D BluetoothMapMasInstance: Accepting socket connection...
,09-06 19:11:33.031  7613  7940 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-06 19:11:33.031  7613  7940 V BluetoothPbapService: Succeed to create listening socket 
09-06 19:11:33.031  7613  7940 V BluetoothPbapService: Accepting socket connection...
09-06 19:11:33.033  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:33.035  2201  2201 D a       : Opening database auth.proximity.permit_store...
09-06 19:11:33.036  2201  2201 D a       : Closing database...
09-06 19:11:33.048  6829  6829 D BluetoothPermissionRequest: onReceive
,09-06 19:11:33.050  6829  6829 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-06 19:11:33.052  6829  6829 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-06 19:11:33.056  7613  7613 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-06 19:11:33.058  7613  7613 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-06 19:11:33.065  7613  7613 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-06 19:11:33.093  7613  7613 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-06 19:11:33.093  7613  7613 V BtOppService: onCreate
,09-06 19:11:33.098  7613  7613 V BluetoothOppNotification: send message
09-06 19:11:33.102  7613  7613 V BtOppService: Starting RfcommListener
09-06 19:11:33.111  7613  7613 D BluetoothOppPreference: Dumping Names:  
09-06 19:11:33.112  7613  7613 D BluetoothOppPreference: {}
,09-06 19:11:33.112  7613  7613 D BluetoothOppPreference: Dumping Channels:  
09-06 19:11:33.112  7613  7613 D BluetoothOppPreference: {}
09-06 19:11:33.112  7613  7613 V BtOppService: onStartCommand
09-06 19:11:33.114  7613  7947 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 19:11:33.120  7613  7613 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:33.120  7613  7613 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-06 19:11:33.123  7613  7944 V BtOppService: Deleted complete outbound shares, number =  0
09-06 19:11:33.124  7613  7613 V BluetoothOppNotification: new notify threadi!
09-06 19:11:33.124  7613  7947 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 19:11:33.126  7613  7944 V BtOppService: Deleted complete inbound failed shares, number = 0
09-06 19:11:33.126  7613  7613 V BluetoothOppNotification: send delay message
09-06 19:11:33.127  7613  7944 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-06 19:11:33.127  7613  7613 V BtOppService: start RfcommListener
09-06 19:11:33.130  7613  7948 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-06 19:11:33.131  7613  7613 V BtOppService: RfcommListener started
,09-06 19:11:33.131  7613  7613 V BtOppService: ContentObserver received notification
09-06 19:11:33.134  7613  7949 V BtOppRfcommListener: Starting RFCOMM listener....
09-06 19:11:33.136  1032  1967 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:33.138  7613  7948 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31e9b4e3 on behalf of 
09-06 19:11:33.138  7613  7944 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@315ee0 on behalf of 
09-06 19:11:33.140  7613  7949 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:11:33.141  7613  7948 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-06 19:11:33.140  7613  7947 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@212dd599 on behalf of 
09-06 19:11:33.142  7613  7949 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=75
09-06 19:11:33.143  7613  7949 V BtOppRfcommListener: Started RFCOMM listener....
09-06 19:11:33.143  7613  7949 I BtOppRfcommListener: Accept thread started.
09-06 19:11:33.143  7613  7949 V BtOppRfcommListener: Accepting connection...
09-06 19:11:33.144  7613  7947 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 19:11:33.144  7613  7947 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 19:11:33.147  7613  7948 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-06 19:11:33.148  7613  7947 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24eec05e on behalf of 
,09-06 19:11:33.148  7613  7948 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ef8bc3f on behalf of 
09-06 19:11:33.150  7613  7948 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-06 19:11:33.150  7613  7613 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10ed7877
09-06 19:11:33.150  7613  7613 V BluetoothFtpService: Ftp Service onCreate
09-06 19:11:33.150  7613  7613 I BluetoothFtpService: Ftp Service onCreate
09-06 19:11:33.151  7613  7613 V BluetoothFtpService: Ftp Service onStartCommand
09-06 19:11:33.151  7613  7613 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:33.151  7613  7613 V BluetoothFtpService: Starting Listening on sockets
09-06 19:11:33.151  7613  7613 V BtOppService: ContentObserver received notification
09-06 19:11:33.151  7613  7613 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-06 19:11:33.151  7613  7613 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-06 19:11:33.151  7613  7613 V BluetoothSapReceiver: SapReceiver onReceive 
09-06 19:11:33.151  7613  7613 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:33.152  7613  7613 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-06 19:11:33.152  7613  7947 V BluetoothOppNotification: update too frequent, put in queue
09-06 19:11:33.152  7613  7613 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-06 19:11:33.153  7613  7948 V BluetoothOppNotification: outbound notification was removed.
09-06 19:11:33.153  7613  7948 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-06 19:11:33.155  7613  7947 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-06 19:11:33.155  7613  7613 V BluetoothFtpService: Handler(): got msg=1
09-06 19:11:33.156  7613  7948 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@6fd3255 on behalf of 
09-06 19:11:33.155  7613  7947 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-06 19:11:33.158  7613  7613 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-06 19:11:33.158  7613  7613 V BluetoothFtpService: Ftp Service initSocket
09-06 19:11:33.159  7613  7947 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21e2846a on behalf of 
09-06 19:11:33.159  7613  7948 V BluetoothOppNotification: inbound: succ-0  fail-0
09-06 19:11:33.160  7613  7947 V BluetoothOppNotification: update too frequent, put in queue
09-06 19:11:33.161  1032  2003 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:33.161  7613  7947 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-06 19:11:33.162  7613  7613 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:11:33.163  7613  7613 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-06 19:11:33.163  7613  7948 V BluetoothOppNotification: inbound notification was removed.
09-06 19:11:33.164  7613  7948 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-06 19:11:33.165  7613  7950 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-06 19:11:33.165  7613  7948 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5c6dd5b on behalf of 
09-06 19:11:33.179  7613  7613 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10ed7877
,09-06 19:11:33.179  7613  7613 V BluetoothSapService: Sap Service onCreate
,09-06 19:11:33.181  7613  7613 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:11:33.181  7613  7613 V BluetoothSapService: state: 12
09-06 19:11:33.181  7613  7613 V BluetoothSapService: Starting SAP server process
09-06 19:11:33.184  7613  7613 V BluetoothSapService: SAP Service startRfcommListenerThread
09-06 19:11:33.178  7951  7951 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:11:33.178  7951  7951 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:11:33.185  7613  7952 V BluetoothSapService: Sap Service initRfcommSocket
09-06 19:11:33.185  1032  2028 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:33.186  7613  7952 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:11:33.187  7613  7952 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
09-06 19:11:33.187  7613  7952 V BluetoothSapService: Succeed to create listening socket 
09-06 19:11:33.187  7613  7952 V BluetoothSapService: Accepting socket connection...
09-06 19:11:33.206  7951  7951 V BT_SAP  : Event pipe created
09-06 19:11:33.206  7951  7951 V BT_SAP  : create_server_socket qcom.sap.server
09-06 19:11:33.206  7951  7951 V BT_SAP  : created socket fd 6
,09-06 19:11:33.455  6732  6810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:11:33.455  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:33.455  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:33.455  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:11:33.455  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:11:33.455  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:11:33.455  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:11:33.455  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:11:33.472  6732  6810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:11:33.476  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:11:33.476  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3fa51398 added. We now have 8 listener(s)
09-06 19:11:33.476  6732  6810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:11:33.479  1032  1575 D WifiServiceImplEx: setWifiEnabled: false pid=6732, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 19:11:33.479  1032  1575 D WifiService: setWifiEnabled: false pid=6732, uid=10118
09-06 19:11:33.479  1032  1575 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-06 19:11:33.484  6732  6810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:11:33.488  1032  1967 D WifiServiceImplEx: setWifiEnabled: true pid=6732, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-06 19:11:33.489  1032  1967 D WifiService: setWifiEnabled: true pid=6732, uid=10118
09-06 19:11:33.489  1032  1967 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:11:33.506  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-06 19:11:33.506  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-06 19:11:33.506  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-06 19:11:33.508  1032  1538 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-06 19:11:33.508  1032  1538 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-06 19:11:33.511  1032  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-06 19:11:33.511  1032  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-06 19:11:33.511  1032  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-06 19:11:33.511  1032  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-06 19:11:33.511  1032  1538 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-06 19:11:33.511  1032  1538 E WifiHW  : unknown target_country: EU , set to default
09-06 19:11:33.511  1032  1538 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-06 19:11:33.511  1032  1538 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-06 19:11:33.511  1032  1538 I WifiUtil: gEnableBmps=1
09-06 19:11:34.122   327   899 D SoftapController: Softap fwReload - Ok
,09-06 19:11:34.132  7613  7613 V BluetoothOppNotification: new notify threadi!
09-06 19:11:34.140  7613  7613 V BluetoothOppNotification: send delay message
,09-06 19:11:34.144  1032  1538 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (628ms)
09-06 19:11:34.146   327   899 D CommandListener: Setting iface cfg
09-06 19:11:34.146   327   899 D CommandListener: Trying to bring down wlan0
09-06 19:11:34.148  1032  1094 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:11:34.154   327   899 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:11:34.166  1032  1538 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,09-06 19:11:34.182  1032  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:11:34.182  1032  1538 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:11:34.182  1032  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-06 19:11:34.178  7973  7973 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:11:34.188  7973  7973 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:11:34.191  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:34.198  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,09-06 19:11:34.221  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,09-06 19:11:34.225  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:34.227  1032  1538 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-06 19:11:34.228  1032  1538 D WifiMonitor: connecting to supplicant
09-06 19:11:34.235  7613  7972 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-06 19:11:34.238  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 19:11:34.238  6829  6829 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-06 19:11:34.238  6829  6829 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 19:11:34.238  6829  6829 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-06 19:11:34.244  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-06 19:11:34.246  6829  6829 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 19:11:34.247  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-06 19:11:34.247  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 19:11:34.247  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 19:11:34.247  6829  6829 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 19:11:34.247  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-06 19:11:34.248  6829  6829 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-06 19:11:34.258  7973  7973 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-06 19:11:34.260  7613  7972 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a8bf437 on behalf of 
09-06 19:11:34.262  7613  7972 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-06 19:11:34.266  7613  7972 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-06 19:11:34.267  7613  7972 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b89eda4 on behalf of 
09-06 19:11:34.268  7613  7972 V BluetoothOppNotification: outbound: succ-0  fail-0
09-06 19:11:34.270  7613  7972 V BluetoothOppNotification: outbound notification was removed.
09-06 19:11:34.270  7613  7972 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-06 19:11:34.271  7613  7972 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30fa570d on behalf of 
,09-06 19:11:34.273  7613  7972 V BluetoothOppNotification: inbound: succ-0  fail-0
09-06 19:11:34.282  7613  7972 V BluetoothOppNotification: inbound notification was removed.
09-06 19:11:34.283  7613  7972 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-06 19:11:34.285  7613  7972 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22b36c2 on behalf of 
,09-06 19:11:34.293  7973  7973 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-06 19:11:34.293  7973  7973 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-06 19:11:34.296  1032  1094 D Tethering: InitialState.processMessage what=4
09-06 19:11:34.311  1032  2327 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7990 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
09-06 19:11:34.313  1032  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-06 19:11:34.390  7973  7973 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 19:11:34.435  7973  7973 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-06 19:11:34.437  1032  2028 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8013 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-06 19:11:34.441  7973  7973 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-06 19:11:34.442  1032  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-06 19:11:34.442  1032  1538 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-06 19:11:34.443  1032  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-06 19:11:34.443  1032  1538 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-06 19:11:34.443  1032  8022 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-06 19:11:34.443  1032  8022 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-06 19:11:34.443  1032  8022 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-06 19:11:34.443  1032  8022 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-06 19:11:34.443  1032  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:11:34.444  7990  8011 W FormManager: Network not available. Please check & try again.
09-06 19:11:34.444  1032  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:11:34.444  1032  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:11:34.445  1032  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:11:34.445  1032  1538 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-06 19:11:34.445  1032  1538 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-06 19:11:34.446  1032  1538 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-06 19:11:34.446  1032  1538 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-06 19:11:34.447  1032  1538 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-06 19:11:34.447  1032  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-06 19:11:34.447  1032  1538 E WifiStateMachine: useWiFiOffloading() : false
09-06 19:11:34.447  1032  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-06 19:11:34.448  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:34.448  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:34.448  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:34.448  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:34.448  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,09-06 19:11:34.451  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-06 19:11:34.452  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:34.453  1969  1969 D WfdService: Waiting for WifiP2p enabling
09-06 19:11:34.454  1032  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-06 19:11:34.454  1032  1538 D WifiNative-wlan0: doBoolean: SET update_config 1
09-06 19:11:34.454  1032  1538 D WifiNative-wlan0: SET update_config 1: returned true
09-06 19:11:34.455  1032  1538 D WifiConfigStore: Loading config and enabling all networks 
09-06 19:11:34.455  1032  1538 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-06 19:11:34.455  1032  1538 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-06 19:11:34.456  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:11:34.456  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:34.456  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:34.456  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:11:34.456  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:11:34.456  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:11:34.456  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:11:34.456  6732  6732 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:11:34.459  6732  6732 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:11:34.460  7990  8012 V FormManager: Network unavailable.
09-06 19:11:34.460  1032  1538 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-06 19:11:34.462  7990  8012 V FormManager: Network unavailable.
09-06 19:11:34.474  1032  1049 I ActivityManager: Killing 7117:com.android.chrome/u0a57 (adj 15): empty #17
,09-06 19:11:34.475  1032  1538 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-06 19:11:34.475  1032  1538 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-06 19:11:34.501  1032  1538 D WifiStateMachine: enableVerboseLogging : level 2
09-06 19:11:34.501  1032  1538 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-06 19:11:34.501  1032  1968 W libprocessgroup: failed to open /acct/uid_10057/pid_7117/cgroup.procs: No such file or directory
,09-06 19:11:34.501  1032  1538 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-06 19:11:34.501  1032  1538 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-06 19:11:34.501  1032  1538 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-06 19:11:34.501  1032  1538 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-06 19:11:34.502  1032  1538 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-06 19:11:34.502  1032  1538 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-06 19:11:34.503  1032  1538 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-06 19:11:34.503  1032  1538 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-06 19:11:34.503  1032  1538 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-06 19:11:34.503  1032  1538 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-06 19:11:34.503  1032  1538 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-06 19:11:34.503  1032  1538 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-06 19:11:34.504  1032  1538 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,09-06 19:11:34.507  1032  1538 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:11:34.507  1032  1538 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-06 19:11:34.507  7642  7642 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:34.507  1032  1538 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-06 19:11:34.507  1032  1538 D WifiNative-HAL: Setting external_sim to 1
09-06 19:11:34.507  1032  1538 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-06 19:11:34.508  1969  1969 D WfdsService: Supplicant Connection state is changed : true
09-06 19:11:34.508  1969  2312 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-06 19:11:34.508  1969  2312 D WfdsService: Set the WFDS Monitor: true
09-06 19:11:34.508  1969  2312 D WfdsMonitor: WfdsMonitorThread create
09-06 19:11:34.508  1969  2312 D WfdsMonitor: WFDS Monitor is created and started
09-06 19:11:34.508  1969  2312 D WfdsService: WiFi: Supplicant connection re-established
09-06 19:11:34.508  1032  1538 D WifiNative-wlan0: SET external_sim 1: returned true
09-06 19:11:34.508  1032  1538 I WifiNative-HAL: startHal
09-06 19:11:34.508  1032  1538 D wifi    : setting scan oui 0xaf67d5c0
09-06 19:11:34.509  1969  8032 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-06 19:11:34.509  1032  1538 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:11:34.509  1032  1538 I WifiNative-HAL: startHal
09-06 19:11:34.509  1032  1538 D wifi    : setting scan oui 0xaf67d5c0
09-06 19:11:34.509  1032  1538 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-06 19:11:34.509  1969  8032 E CtrlSupplicant: Succeed to open control connection
09-06 19:11:34.509  1969  8032 E CtrlSupplicant: Succeed to open monitor connection
09-06 19:11:34.509  1969  8032 D WfdsMonitor: Supplicant connection established
09-06 19:11:34.510  1969  2312 D WfdsService: Connected to the supplicant for wfds
09-06 19:11:34.510  1032  1538 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-06 19:11:34.510  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-06 19:11:34.510  7973  7973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-06 19:11:34.510  1032  1538 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-06 19:11:34.510  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-06 19:11:34.511  7973  7973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-06 19:11:34.511  1032  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-06 19:11:34.511  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-06 19:11:34.511  7973  7973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-06 19:11:34.511  1032  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-06 19:11:34.511  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-06 19:11:34.511  7973  7973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-06 19:11:34.512  1032  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-06 19:11:34.512  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-06 19:11:34.512  7973  7973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-06 19:11:34.512  1032  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-06 19:11:34.512  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-06 19:11:34.512  7973  7973 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-06 19:11:34.513  1032  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-06 19:11:34.513  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-06 19:11:34.513  7973  7973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-06 19:11:34.514  1032  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
,09-06 19:11:34.515  1032  1538 E WifiNative: : [222,748,038 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-06 19:11:34.517  1032  1538 D WifiNative-wlan0: doBoolean: RECONNECT
09-06 19:11:34.517  1032  1538 D WifiNative-wlan0: RECONNECT: returned true
09-06 19:11:34.517  1032  1538 D WifiNative-wlan0: doString: [STATUS]
,09-06 19:11:34.517  1032  8022 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-06 19:11:34.518  1032  8022 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-06 19:11:34.518  1032  1538 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-06 19:11:34.518  1032  1538 D WifiNative-wlan0: doBoolean: SET ps 1
09-06 19:11:34.518  1032  1538 D WifiNative-wlan0: SET ps 1: returned true
09-06 19:11:34.519  1032  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:34.519  6732  6810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:11:34.519  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:34.519  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:34.519  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:11:34.519  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:11:34.519  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:11:34.519  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:11:34.519  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:11:34.520   327   899 D CommandListener: Setting iface cfg
09-06 19:11:34.520   327   899 D CommandListener: Trying to bring up p2p0
09-06 19:11:34.520  1032  1537 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-06 19:11:34.520  1032  1537 D LGWifiP2pService: P2pEnablingState
09-06 19:11:34.520  1032  1537 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:34.520  1032  1537 D LGWifiP2pService: P2p socket connection successful
09-06 19:11:34.520  1032  1537 D LGWifiP2pService: P2pEnabledState
09-06 19:11:34.521  6732  6810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:11:34.521  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 3
09-06 19:11:34.521  1032  1032 D RttService: SCAN_AVAILABLE : 3
09-06 19:11:34.521  1032  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:34.521  1032  1556 I WifiNative-HAL: startHal
09-06 19:11:34.521  1032  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf67d5c0
09-06 19:11:34.521  1032  1556 D wifi    : failed to get capabilities : -3
09-06 19:11:34.521  1032  1556 E WifiScanningService: could not get scan capabilities
09-06 19:11:34.521  1032  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:34.522  1032  1538 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-06 19:11:34.522  1969  1969 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-06 19:11:34.522  1032  1538 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-06 19:11:34.522  1969  1969 D WfdsService: WifiP2pState is changed : true
09-06 19:11:34.522  1969  2312 D WfdsService: Receive the WFDS_ENABLE Method
09-06 19:11:34.522  1969  2312 D WfdsService: Set the WFDS Monitor: true
09-06 19:11:34.522  1969  2312 D WfdsService: Connected to the supplicant for wfds
09-06 19:11:34.522  1969  2312 D WfdsJNI : doCommand: WFDS_SET TRUE
,09-06 19:11:34.523  7973  7973 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-06 19:11:34.523  1969  2312 D WfdsService: selectPreferredScanChannel [36]
09-06 19:11:34.523  1969  2312 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-06 19:11:34.523  1032  1538 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-06 19:11:34.524  1032  1537 D LGWifiP2pService: sending p2p connection changed broadcast
09-06 19:11:34.524  1032  1538 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-06 19:11:34.524  1032  1537 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-06 19:11:34.524  1032  1537 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-06 19:11:34.525  1032  1537 D WifiNative-p2p0: doBoolean: SET device_name G3
09-06 19:11:34.525  1969  1969 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-06 19:11:34.525  1032  1537 D WifiNative-p2p0: SET device_name G3: returned true
09-06 19:11:34.525  1032  1537 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-06 19:11:34.525  1032  1537 D LGWifiP2pService: before postfix = G3
09-06 19:11:34.525  1032  1537 D WifiServerServiceExt: postfix byte check : 2
09-06 19:11:34.525  1969  1969 D WfdsService: isConnected: false
09-06 19:11:34.525  1032  1537 D LGWifiP2pService: after postfix = G3
,09-06 19:11:34.525  1032  1537 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-06 19:11:34.525  6732  6810 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-06 19:11:34.525  1032  1537 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-06 19:11:34.525  1032  1537 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-06 19:11:34.526  1032  1537 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-06 19:11:34.526  1032  1537 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-06 19:11:34.526  6732  6810 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-06 19:11:34.526  1032  1537 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-06 19:11:34.526  1032  1537 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-06 19:11:34.526  1032  1537 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-06 19:11:34.526  1032  1537 D WifiNative-HAL: p2pGetDeviceAddress
09-06 19:11:34.527  1032  1537 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-06 19:11:34.527  1032  1537 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-06 19:11:34.527  1032  1537 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-06 19:11:34.527  1032  1537 D WifiNative-p2p0: P2P_FLUSH: returned true
,09-06 19:11:34.527  1032  1537 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-06 19:11:34.528  1969  1969 I WfdStateTracker: handleP2pThisDeviceChanged
09-06 19:11:34.528  1969  1969 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-06 19:11:34.528  1969  1969 D WfdsService: Update P2p Interface State: 3
09-06 19:11:34.528  1032  1537 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-06 19:11:34.528  1032  1537 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-06 19:11:34.528  1032  1537 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-06 19:11:34.528  1032  1537 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-06 19:11:34.530  1032  1538 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-06 19:11:34.530  1032  1538 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-06 19:11:34.531  1032  1538 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-06 19:11:34.531  1032  1538 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-06 19:11:34.532  6732  6810 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2e35455a Bundle[{}]
,09-06 19:11:34.534  6732  6810 I io.jxcore.node.LifeCycleMonitor: start: OK
09-06 19:11:34.534  6732  6810 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-06 19:11:34.535  6732  6810 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-06 19:11:34.535  6732  6810 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-06 19:11:34.536  6732  6810 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-06 19:11:34.537  8013  8013 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:11:34.537  6732  6810 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-06 19:11:34.538  7973  7973 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-06 19:11:34.539  1032  1537 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-06 19:11:34.539  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 19:11:34.539  1032  1537 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-06 19:11:34.539  1032  1537 D LGWifiP2pService: InactiveState
09-06 19:11:34.539  1032  1537 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:34.539  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:34.540  1032  1538 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-06 19:11:34.540  1032  1538 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-06 19:11:34.541  1032  1538 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-06 19:11:34.541  1032  1538 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-06 19:11:34.541  7973  7973 E wpa_supplicant: disconnect_rssi_lvl: -100
09-06 19:11:34.541  1032  1537 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-06 19:11:34.541  1032  1537 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-06 19:11:34.541  7973  7973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-06 19:11:34.541  1032  1537 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:34.542  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:34.542  1032  1537 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:34.542  7973  7973 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:11:34.542  7973  7973 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-06 19:11:34.542  7973  7973 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:34.543  7973  7973 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:34.543  6732  6810 I System.out: Running OutgoingSocketThread
09-06 19:11:34.544  1032  8022 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 19:11:34.544  1032  8022 E WifiMonitor: WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:11:34.544  1969  8032 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 19:11:34.544  1032  8022 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:11:34.544  1969  8032 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:11:34.544  1032  8022 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:11:34.544  1969  8032 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:11:34.544  1032  8022 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:11:34.544  1032  8022 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER ,type=WORLD
09-06 19:11:34.544  1032  8022 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:34.544  1032  8022 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:34.544  1032  1537 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:34.544  1032  8022 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:11:34.544  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:34.544  1032  8022 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:34.544  1032  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:34.544  1032  8022 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:34.544  1032  8022 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:34.544  1032  1537 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:34.544  6732  8035 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 851)
09-06 19:11:34.544  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:34.544  1032  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:34.544  1032  1537 D LGWifiP2pService: InactiveState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:34.544  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:34.544  1032  1537 D LGWifiP2pService: DefaultState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:34.545  1032  1032 E WifiServerServiceExt: No p2p device connected
09-06 19:11:34.545  6732  8035 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 33752
09-06 19:11:34.545  1032  1538 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-06 19:11:34.545  6732  8035 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-06 19:11:34.546  1032  1538 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
,09-06 19:11:34.546  1032  1538 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-06 19:11:34.546  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-06 19:11:34.546  1969  2312 W WfdsService: DefaultState - msg [9441285] is not handled
09-06 19:11:34.547  7973  7973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-06 19:11:34.547  7973  7973 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:11:34.547  1032  8022 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-06 19:11:34.547  1032  8022 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,09-06 19:11:34.547  1032  8022 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:11:34.547  1032  8022 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-06 19:11:34.547  7973  7973 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-06 19:11:34.548  7973  7973 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:34.548  7973  7973 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:34.549  1969  8032 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:11:34.549  1969  8032 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:11:34.549  1032  1538 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-06 19:11:34.550  1032  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:34.550  1032  8022 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:11:34.550  1032  8022 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:34.550  1032  8022 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:34.550  1032  8022 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:34.550  1032  8022 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-06 19:11:34.550  1032  8022 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:34.550  1032  8022 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:34.550  1032  8022 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-06 19:11:34.550  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:34.550  1032  1538 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-06 19:11:34.551  1032  1538 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-06 19:11:34.551  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:34.551  1032  1538 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-06 19:11:34.551  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-06 19:11:34.552  1032  2028 I ActivityManager: Killing 7135:com.lge.drmservice/u0a62 (adj 15): empty #17
09-06 19:11:34.552  7973  7973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-06 19:11:34.552  7973  7973 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:11:34.553  1032  8022 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-06 19:11:34.553  1032  8022 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:11:34.553  1032  8022 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:11:34.553  1032  8022 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-06 19:11:34.553  1032  1538 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-06 19:11:34.554  1032  1538 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-06 19:11:34.554  1032  1538 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-06 19:11:34.554  1032  1538 D WifiNative-wlan0: doBoolean: SCAN
09-06 19:11:34.554  1032  1538 D WifiNative-wlan0: SCAN: returned false
09-06 19:11:34.555  1032  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=222788  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 19:11:34.571  7714  7725 E UEI.SmartControl: file observer is disposed!
,09-06 19:11:34.592  1032  1967 W libprocessgroup: failed to open /acct/uid_10062/pid_7135/cgroup.procs: No such file or directory
,09-06 19:11:34.592  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=222826  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-06 19:11:34.593  1032  1538 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:11:34.593  1032  1538 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:11:34.594  1032  1538 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:11:34.594  1032  1538 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:11:34.595  1032  1538 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-06 19:11:34.597  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:34.597  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:34.597  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-06 19:11:34.598  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:11:34.599  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
09-06 19:11:34.599  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:34.599  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:11:34.600  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:34.614  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 19:11:34.614  6829  6829 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-06 19:11:34.614  6829  6829 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,09-06 19:11:34.614  6829  6829 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-06 19:11:34.615  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-06 19:11:34.616  6829  6829 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 19:11:34.616  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-06 19:11:34.616  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 19:11:34.616  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 19:11:34.616  6829  6829 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 19:11:34.616  6829  6829 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-06 19:11:34.629  8013  8013 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-06 19:11:34.634  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-06 19:11:34.639  7990  8037 W FormManager: Network not available. Please check & try again.
09-06 19:11:34.640  7990  8038 V FormManager: Network unavailable.
09-06 19:11:34.644  7990  8038 V FormManager: Network unavailable.
09-06 19:11:34.645  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 19:11:34.668  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:11:34.669  4326  4326 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-06 19:11:34.671  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:11:34.675  4326  4326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-06 19:11:34.686  4326  8039 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-06 19:11:34.688  4326  8040 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-06 19:11:34.688  4326  8040 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-06 19:11:34.743  1032  1781 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8041 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-06 19:11:34.870  8041  8041 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-06 19:11:34.870  8041  8041 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-06 19:11:34.879  8041  8041 V [BNRBootReceiver]: Boot Receiver Return
,09-06 19:11:34.880  8041  8041 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-06 19:11:34.932  1032  2028 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8059 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-06 19:11:34.934  1032  2028 I ActivityManager: Killing 7154:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,09-06 19:11:34.958   359   359 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 390us total 23.277ms
,09-06 19:11:34.975   359   359 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 279us total 14.918ms
,09-06 19:11:34.990   359   359 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 272us total 12.941ms
,09-06 19:11:35.010  1032  2049 W libprocessgroup: failed to open /acct/uid_10085/pid_7154/cgroup.procs: No such file or directory
,09-06 19:11:35.030  8059  8059 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-06 19:11:35.067  8059  8059 D PluginManager: init()
,09-06 19:11:35.074  7973  7973 E wpa_supplicant: USIM:  scard_init function
09-06 19:11:35.075  7973  7973 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-06 19:11:35.075  1032  8022 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-06 19:11:35.076  1032  8022 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-06 19:11:35.076  1032  8022 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-06 19:11:35.076  1032  8022 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
09-06 19:11:35.076  1032  8022 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-06 19:11:35.076  1032  8022 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-06 19:11:35.076  1032  8022 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-06 19:11:35.077  1032  1538 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-06 19:11:35.078  1032  1538 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-06 19:11:35.078  1032  1538 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-06 19:11:35.079  1032  1538 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-06 19:11:35.079  1032  1538 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-06 19:11:35.085  1032  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=223318  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-06 19:11:35.088  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:35.088  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:35.088  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-06 19:11:35.090  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:35.090  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:11:35.093  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=223326  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-06 19:11:35.097  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:35.097  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:35.097  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-06 19:11:35.102  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:35.102  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:11:35.102  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-06 19:11:35.105  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:35.106  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-06 19:11:35.109  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:35.195  7973  7973 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-06 19:11:35.199  1032  8022 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-06 19:11:35.200  1032  8022 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-06 19:11:35.200  1032  8022 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-06 19:11:35.200  1032  8022 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-06 19:11:35.200  1032  8022 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:11:35.200  1032  8022 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:11:35.201  1032  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=223434  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-06 19:11:35.201  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=223434  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-06 19:11:35.202  1032  1538 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=223435
09-06 19:11:35.202  1032  1538 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=223436
09-06 19:11:35.203  1032  1538 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=223436
09-06 19:11:35.203  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=223436
09-06 19:11:35.204  1032  1538 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=223437
09-06 19:11:35.205  1032  8022 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:11:35.205  1032  8022 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-06 19:11:35.205  7973  7973 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:11:35.206  7973  7973 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 19:11:35.206  1032  8022 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-06 19:11:35.206  1032  8022 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:11:35.206  1032  8022 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:11:35.206  1032  8022 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-06 19:11:35.206  1032  8022 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 19:11:35.206  1032  8022 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-06 19:11:35.206  1032  8022 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:11:35.207  1032  1094 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:11:35.210  1032  8022 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-06 19:11:35.213  1032  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=223447  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-06 19:11:35.215  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:35.215  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:11:35.217  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:35.217  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:35.217  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=223450  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-06 19:11:35.217  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:35.217  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-06 19:11:35.218  1032  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=223452  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-06 19:11:35.219  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=223452  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-06 19:11:35.221  1032  1538 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=223455
09-06 19:11:35.222  1032  1538 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=223455
09-06 19:11:35.222  1032  1538 D WifiNative-wlan0: doString: [STATUS]
09-06 19:11:35.223  1032  8022 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-06 19:11:35.223  1032  8022 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-06 19:11:35.223  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:35.223  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:35.223  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-06 19:11:35.223  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:11:35.223  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-06 19:11:35.224  1032  1538 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-06 19:11:35.227  1032  1538 I WifiServiceExtension: setVHTCapabilityType  : false
09-06 19:11:35.237  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:35.237  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-06 19:11:35.239  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:35.242  1032  1538 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-06 19:11:35.242  1032  1538 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-06 19:11:35.245  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:35.245  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:35.246  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-06 19:11:35.248  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:35.248  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:35.248  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-06 19:11:35.253  1032  1423 V AlarmManager: RTC_WAKEUP set : Alarm{4070797 type 0 when 1473181889905 com.google.android.gms} when 1473181889905
09-06 19:11:35.253  1032  1423 V AlarmManager: ELAPSED_WAKEUP set : Alarm{11186d84 type 2 when 223165 android} when 223165
09-06 19:11:35.259  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:35.259  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:11:35.261  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-06 19:11:35.261  1032  1538 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-06 19:11:35.261  1032  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:11:35.261  1032  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 19:11:35.262  1032  1545 D ConnectivityService: Got NetworkAgent Messenger
09-06 19:11:35.262  1032  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-06 19:11:35.262  1032  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 19:11:35.262  1032  1545 D ConnectivityService: NetworkAgent connected
09-06 19:11:35.262  1032  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-06 19:11:35.263  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:35.263  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:11:35.264  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:35.271  1032  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 19:11:35.271  1032  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:11:35.271  1032  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-06 19:11:35.271  1032  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-06 19:11:35.271  1032  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-06 19:11:35.278  1032  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-06 19:11:35.280   327   899 D CommandListener: Setting iface cfg
09-06 19:11:35.283  1032  1538 E WifiStateMachine: Start Dhcp Watchdog 3
09-06 19:11:35.283  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:11:35.284  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:11:35.284  1032  1538 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:11:35.284  1032  1538 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:11:35.285  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:11:35.285  1032  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-06 19:11:35.285  1032  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=223519  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:11:35.286  1032  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=223519  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:11:35.286  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=223519  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:11:35.287  1032  8080 D DhcpStateMachine: StoppedState
09-06 19:11:35.287  1032  8080 D DhcpStateMachine: StoppedState{ when=-4ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:35.287  1032  8080 D DhcpStateMachine: WaitBeforeStartState
09-06 19:11:35.287  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:11:35.287  1032  1032 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,09-06 19:11:35.288  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:11:35.288  1032  1032 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-06 19:11:35.289  1032  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=223522  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:11:35.290  1032  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=223523  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:11:35.291  1032  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=223525  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-06 19:11:35.293  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14315] from screen [on:0 period:8112765] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-06 19:11:35.294  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:8112765] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-06 19:11:35.294  1032  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-06 19:11:35.298  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:35.298  1032  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-06 19:11:35.298  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:35.298  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:35.299  1032  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:35.299  1032  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:35.299  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:35.300  1032  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:35.300  1032  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-06 19:11:35.301  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:11:35.301  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-06 19:11:35.302  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=175,0,0
09-06 19:11:35.302  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=175,0,0
09-06 19:11:35.302  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-06 19:11:35.303  7973  7973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-06 19:11:35.303  1032  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-06 19:11:35.303  1032  1538 D WifiNative-wlan0: doBoolean: SET ps 0
09-06 19:11:35.303  1032  1538 D WifiNative-wlan0: SET ps 0: returned true
09-06 19:11:35.303  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-06 19:11:35.303  7973  7973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-06 19:11:35.304  1032  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-06 19:11:35.304  1032  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1a1dfd7f target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:35.304  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1a1dfd7f target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:35.304  1032  8080 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:35.304  1032  8080 D DhcpStateMachine: DHCP Start wake lock is ac,quired.
09-06 19:11:35.305  1032  1538 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-06 19:11:35.305  1032  1538 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-06 19:11:35.305  1032  1538 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-06 19:11:35.306   327   899 D CommandListener: Setting iface cfg
09-06 19:11:35.306   327   899 D CommandListener: Trying to bring up wlan0
09-06 19:11:35.307  1032  1538 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-06 19:11:35.308  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-06 19:11:35.308  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-06 19:11:35.309  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:35.309  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:35.310  1032  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:35.310  1032  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:35.311  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:35.311  1032  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-06 19:11:35.311  1032  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-06 19:11:35.312  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-06 19:11:35.312  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-06 19:11:35.312  1032  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:35.312  1032  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:35.313  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-06 19:11:35.313  7973  7973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-06 19:11:35.313  1032  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-06 19:11:35.313  1032  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-06 19:11:35.313  7973  7973 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-06 19:11:35.314  1032  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-06 19:11:35.314  1032  1538 D WifiNative-wlan0: doBoolean: SET ps 1
,09-06 19:11:35.331  1032  1538 D WifiNative-wlan0: SET ps 1: returned true
,09-06 19:11:35.331  1032  1538 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-06 19:11:35.332  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-06 19:11:35.332  1032  1538 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-06 19:11:35.333  1032  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-06 19:11:35.333  1032  1545 D ConnectivityService: ignoring duplicate network state non-change
09-06 19:11:35.334  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:35.334  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:11:35.336  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:35.337  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:35.337  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:35.337  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-06 19:11:35.338  1032  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-06 19:11:35.339  1032  1545 D ConnectivityService: Adding iface wlan0 to network 102
09-06 19:11:35.344  1032  1538 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-06 19:11:35.345  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:35.345  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:35.345  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-06 19:11:35.346  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-06 19:11:35.350  1969  1969 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-06 19:11:35.353  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:35.353  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:35.353  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-06 19:11:35.354  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-06 19:11:35.358  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:35.358  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-06 19:11:35.359  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:35.359  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:35.360  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:11:35.360  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-06 19:11:35.362  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:35.362  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-06 19:11:35.362  1032  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-06 19:11:35.363  1032  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-06 19:11:35.363  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:35.364  1032  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-06 19:11:35.364   327   899 E Netd    : netlink response contains error (File exists)
09-06 19:11:35.364  1032  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-06 19:11:35.365  1032  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-06 19:11:35.365  1032  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-06 19:11:35.365  1032  1545 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-06 19:11:35.366  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:11:35.366  1032  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-06 19:11:35.366  1032  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-06 19:11:35.366  1032  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-06 19:11:35.366  1032  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-06 19:11:35.366  1032  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:11:35.366  1032  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:11:35.366  1032  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-06 19:11:35.366  1032  8079 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:35.366  1032  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:35.366  1032  8079 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-06 19:11:35.366  1032  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-06 19:11:35.366  1032  1545 D ConnectivityService: currentScore = 0, newScore = 20
09-06 19:11:35.366  1032  1545 D ConnectivityService:    accepting network in place of null
09-06 19:11:35.366  1032  8079 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:11:35.366  1032  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:35.366  1032  8079 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-06 19:11:35.367  1032  1538 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:35.367  1032  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:11:35.369  1032  1545 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576,Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-06 19:11:35.369  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-06 19:11:35.369  1032  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-06 19:11:35.369  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:11:35.369  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:35.370   327  8089 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-06 19:11:35.371  1878  1878 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:35.371  1878  1878 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 19:11:35.372  1032  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-06 19:11:35.372  1032  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-06 19:11:35.372  1032  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-06 19:11:35.373  1032  1545 D ConnectivityService: validation of new default Network = false
09-06 19:11:35.373  1032  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-06 19:11:35.373  1032  1545 D DSQN    : enableDataServiceNotify 
09-06 19:11:35.373  1032  1545 D DSQN    : start dsqn bin
09-06 19:11:35.374  1032  1032 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-06 19:11:35.375  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-06 19:11:35.375  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-06 19:11:35.375  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-06 19:11:35.391  1032  1536 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-06 19:11:35.395  1032  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-06 19:11:35.395  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:35.395  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:11:35.388  8090  8090 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:11:35.395  1032  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:11:35.396  1603  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 19:11:35.388  8090  8090 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:11:35.403  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 19:11:35.404  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:35.405  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:35.410  8090  8090 E DSQN    : DSQN ssw
09-06 19:11:35.443   327  8089 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-06 19:11:35.478   327  8089 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-06 19:11:35.507  1032  8080 D DhcpStateMachine: DHCPV4 request on wlan0
,09-06 19:11:35.508  1032  8080 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,09-06 19:11:35.508  1032  8080 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,09-06 19:11:35.508  8095  8095 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:11:35.515   327   898 D LGDataListener: argv[0]=dsqncommand
09-06 19:11:35.516   327   898 D LGDataListener: argv[1]=wlan0
09-06 19:11:35.516   327   898 D LGDataListener: argv[2]=1
09-06 19:11:35.516   327   898 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-06 19:11:35.508  8095  8095 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-06 19:11:35.516  1032  1092 D DSQN    : DSQM DsqnNotification wlan0  1
09-06 19:11:35.517  1032  1092 D DSQN    : start to monitor internet connection
09-06 19:11:35.520  8095  8095 I dhcpcd  : version 5.5.6 starting
09-06 19:11:35.522  8095  8095 E dhcpcd  : get_duid: m
09-06 19:11:35.522  8095  8095 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-06 19:11:35.522  8095  8095 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-06 19:11:35.545  6732  6810 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 852)
09-06 19:11:35.546  6732  6810 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 852)
09-06 19:11:35.551  1032  8079 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 06 Sep 2016 17:11:35 GMT], X-Android-Received-Millis=[1473181895551], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473181895515]}
09-06 19:11:35.552  1032  8079 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-06 19:11:35.552  1032  8079 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-06 19:11:35.552  1032  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-06 19:11:35.552  1032  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-06 19:11:35.552  1032  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:11:35.552  1032  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:11:35.552  1032  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-06 19:11:35.552  1032  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-06 19:11:35.553  1032  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,09-06 19:11:35.553  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:35.553  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:11:35.554  1032  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:11:35.554  1603  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 19:11:35.556  1032  1545 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:35.556  1032  1538 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:35.556  1032  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:11:35.557  1878  1878 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:35.558  1032  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-06 19:11:35.558  1878  1878 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-06 19:11:35.558  6732  6810 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 857)
09-06 19:11:35.561  6732  6810 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-06 19:11:35.562  6732  6810 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 858)
09-06 19:11:35.569  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:11:35.569  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24d1d7f1 added. We now have 2 listener(s)
09-06 19:11:35.570  1032  2028 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:35.574  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-06 19:11:35.575  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:35.576  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-06 19:11:35.578  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:11:35.578  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:11:35.578  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:11:35.578  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:11:35.578  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@128a8fd6 added. We now have 9 listener(s)
09-06 19:11:35.578  6732  6810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:11:35.579  8059  8059 W ExternalStrings: load override strings
09-06 19:11:35.579  8059  8059 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-06 19:11:35.579  8059  8059 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-06 19:11:35.579  8059  8059 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-06 19:11:35.579  8059  8059 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-06 19:11:35.579  8059  8059 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-06 19:11:35.579  8059  8059 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-06 19:11:35.579  8059  8059 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-06 19:11:35.579  8059  8059 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-06 19:11:35.579  8059  8059 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-06 19:11:35.579  8059  8059 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-06 19:11:35.579  8059  8059 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-06 19:11:35.579  8059  8059 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:11:35.579  8059  8059 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:11:35.579  8059  8059 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 19:11:35.579  8059  8059 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:11:35.579  8059  8059 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:11:35.579  8059  8059 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 19:11:35.579  8059  8059 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 19:11:35.579  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:11:35.581  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.blueto,oth.BluetoothManager: bind: Binding a new listener
,09-06 19:11:35.583  8059  8059 D StatusProvider: onCreate
09-06 19:11:35.586  6732  6810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:11:35.586  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:35.586  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:35.586  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:11:35.586  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:11:35.586  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:11:35.586  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:11:35.586  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:11:35.588  6732  6810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:11:35.588  6732  6810 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:11:35.588  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:11:35.588  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3aa3d144 added. We now have 3 listener(s)
09-06 19:11:35.589  1032  1575 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:35.590  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:35.592  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:11:35.592  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:11:35.592  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:11:35.592  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:11:35.592  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b022d added. We now have 10 listener(s)
09-06 19:11:35.592  6732  6810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:11:35.592  6732  6810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:11:35.593  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:11:35.593  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:35.593  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:11:35.593  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:35.593  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:35.593  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:11:35.594  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:11:35.594  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24d1d7f1 removed from the list
09-06 19:11:35.594  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:35.594  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@128a8fd6 removed from the list
09-06 19:11:35.594  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:11:35.594  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:35.594  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:35.594  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:35.594  8095  8095 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-06 19:11:35.594  8095  8095 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-06 19:11:35.595  8095  8095 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-06 19:11:35.595  8095  8095 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-06 19:11:35.595  8095  8095 D dhcpcd  : wlan0: sending REQUEST (xid 0x94d39354), next in 4.07 seconds
09-06 19:11:35.595  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:35.595  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:35.595  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:35.595  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@128a8fd6 not in the list
09-06 19:11:35.595  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:35.595  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:35.596  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:35.596  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:35.596  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:35.596  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b022d removed from the list
09-06 19:11:35.596  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:35.596  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:35.596  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:35.596  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:11:35.596  6732  6810 V org.thal,iproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3aa3d144 removed from the list
09-06 19:11:35.597  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:11:35.597  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21f7d362 added. We now have 2 listener(s)
09-06 19:11:35.597  1032  1949 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:35.600  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:11:35.600  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:11:35.600  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:11:35.600  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:11:35.600  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18b90cf3 added. We now have 9 listener(s)
09-06 19:11:35.600  6732  6810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:11:35.609  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:11:35.611  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:11:35.620  8095  8095 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-06 19:11:35.620  6732  6810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:11:35.620  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:35.620  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:35.620  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:11:35.620  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:11:35.620  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:11:35.620  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:11:35.620  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:11:35.621  6732  6810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:11:35.621  6732  6810 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:11:35.621  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:11:35.621  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21529429 added. We now have 3 listener(s)
,09-06 19:11:35.622  1032  1781 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:35.623  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:35.624  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:11:35.624  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:11:35.624  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:11:35.624  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:11:35.624  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a03c3ae added. We now have 10 listener(s)
09-06 19:11:35.624  6732  6810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:11:35.624  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:11:35.624  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:11:35.624  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:11:35.624  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:11:35.624  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:11:35.628  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:35.628  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:11:35.628  1032  1645 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:35.632  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:11:35.633  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:11:35.634  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:11:35.634  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:11:35.636  6732  6810 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 19:11:35.636  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:11:35.636  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:35.638  6732  6810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:11:35.638  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:11:35.638  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:35.638  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:35.638  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:35.638  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:11:35.638  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:11:35.638  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21f7d362 removed from the list
09-06 19:11:35.638  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:35.638  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18b90cf3 removed from the list
09-06 19:11:35.638  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:11:35.638  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:35.639  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:35.639  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:35.639  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:35.639  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:35.639  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:35.639  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18b90cf3 not in the list
09-06 19:11:35.639  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:35.639  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:35.640  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:35.641  6732  6810 D BluetoothLeScanner: could not find callback wrapper
09-06 19:11:35.641  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stop,ped
09-06 19:11:35.641  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:35.641  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:35.641  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a03c3ae removed from the list
09-06 19:11:35.641  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:35.641  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:35.641  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:35.641  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:11:35.641  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21529429 removed from the list
09-06 19:11:35.642  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:11:35.642  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b5749e5 added. We now have 2 listener(s)
09-06 19:11:35.642  1032  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:35.645  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:11:35.645  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:11:35.645  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:11:35.645  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:11:35.645  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cc6cba added. We now have 9 listener(s)
09-06 19:11:35.645  6732  6810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:11:35.645  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:11:35.647  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:11:35.650  8095  8095 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-06 19:11:35.650  8095  8095 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-06 19:11:35.650  8095  8095 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-06 19:11:35.650  8095  8095 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-06 19:11:35.650  8095  8095 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-06 19:11:35.650  8095  8095 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-06 19:11:35.651  8095  8095 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-06 19:11:35.651  8095  8095 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-06 19:11:35.651  6732  6810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:11:35.651  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:35.651  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:35.651  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:11:35.651  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:11:35.651  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:11:35.651  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:11:35.651  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:11:35.653  6732  6810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:11:35.653  6732  6810 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:11:35.653  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:11:35.653  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ad092c8 added. We now have 3 listener(s)
09-06 19:11:35.654  1032  2004 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:35.655  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:35.657  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:11:35.658  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:11:35.658  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:11:35.658  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:11:35.658  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:11:35.658  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16379f61 added. We now have 10 listener(s)
09-06 19:11:35.658  6732  6810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:11:35.658  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:11:35.659  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:11:35.659  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:11:35.659  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:11:35.659  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:11:35.659  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:11:35.662  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:11:35.662  1032  1968 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:35.667  8059  8059 V Signer  : override build config not found
09-06 19:11:35.667  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:11:35.668  8059  8059 D Signer  : value of property debug is false
09-06 19:11:35.668  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 19:11:35.670  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:11:35.671  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:11:35.673  6732  6810 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 19:11:35.673  6732  6810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:11:35.673  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:11:35.673  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:35.673  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:35.673  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:35.673  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:11:35.673  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:11:35.673  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b5749e5 removed from the list
09-06 19:11:35.673  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:35.673  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cc6cba removed from the list
09-06 19:11:35.673  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:11:35.673  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:35.674  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:35.674  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:35.675  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:35.675  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:35.675  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:35.675  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cc6cba not in the list
09-06 19:11:35.675  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:35.675  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:35.676  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:35.677  6732  6810 D BluetoothLeScanner: could not find callback wrapper
09-06 19:11:35.677  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:11:35.677  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:35.677  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:35.677  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16379f61 removed from the list
09-06 19:11:35.677  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:35.677  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-0,6 19:11:35.677  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:35.677  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:11:35.677  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ad092c8 removed from the list
09-06 19:11:35.679  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:11:35.679  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c01374 added. We now have 2 listener(s)
09-06 19:11:35.679  1032  2004 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:35.681  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:11:35.681  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:11:35.681  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:11:35.682  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:11:35.682  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@126dd09d added. We now have 9 listener(s)
09-06 19:11:35.682  6732  6810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:11:35.682  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:11:35.685  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:11:35.691  6732  6810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:11:35.691  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:35.691  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:35.691  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:11:35.691  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:11:35.691  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:11:35.691  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:11:35.691  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:11:35.693  6732  6810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:11:35.693  6732  6810 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:11:35.695  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:11:35.696  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:35.696  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fbf18e3 added. We now have 3 listener(s)
09-06 19:11:35.696  1032  2003 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-06 19:11:35.698  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:11:35.700  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:11:35.701  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:11:35.701  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:11:35.701  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:11:35.701  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3084f2e0 added. We now have 10 listener(s)
09-06 19:11:35.701  6732  6810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:11:35.701  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:11:35.701  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:11:35.701  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:11:35.701  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:11:35.701  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:11:35.705  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:11:35.705  1032  2004 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:35.719  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:11:35.720  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:11:35.724  8059  8059 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
09-06 19:11:35.724  8059  8059 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
09-06 19:11:35.724  8059  8059 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
09-06 19:11:35.724  8059  8059 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
09-06 19:11:35.725  8059  8059 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-06 19:11:35.725  8059  8059 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
09-06 19:11:35.725  8059  8059 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
09-06 19:11:35.725  8059  8059 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
09-06 19:11:35.726  8059  8059 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
09-06 19:11:35.726  8059  8059 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
09-06 19:11:35.726  8059  8059 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
09-06 19:11:35.726  8059  8059 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
09-06 19:11:35.727  8059  8059 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
09-06 19:11:35.728  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:11:35.729  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:11:35.730  6732  6810 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-06 19:11:35.732  6732  6810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:11:35.732  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:11:35.732  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:35.732  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:35.732  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:35.732  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:11:35.732  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:11:35.732  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c01374 removed from the list
09-06 19:11:35.732  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:35.732  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@126dd09d removed from the list
09-06 19:11:35.732  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:11:35.732  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:35.733  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:35.733  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:35.733  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:35.733  6732  6810 I org.thali,project.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:11:35.733  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:35.734  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@126dd09d not in the list
09-06 19:11:35.734  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:35.734  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:11:35.737  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:35.738  6732  6810 D BluetoothLeScanner: could not find callback wrapper
09-06 19:11:35.738  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:11:35.738  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:35.738  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:35.738  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3084f2e0 removed from the list
09-06 19:11:35.738  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:35.738  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:35.738  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:35.738  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:11:35.738  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fbf18e3 removed from the list
09-06 19:11:35.739  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:11:35.739  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ec0603f added. We now have 2 listener(s)
09-06 19:11:35.740  1032  2028 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:35.743  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-06 19:11:35.743  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:11:35.743  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:11:35.743  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:11:35.743  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34f65d0c added. We now have 9 listener(s)
09-06 19:11:35.743  6732  6810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:11:35.744  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:11:35.747  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:11:35.753  8059  8059 V LGMDMManager: Create singleton instance
09-06 19:11:35.756  6732  6810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:11:35.756  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:11:35.756  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-06 19:11:35.756  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:11:35.756  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:11:35.756  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:11:35.756  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:11:35.756  6732  6810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:11:35.757  6732  6810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:11:35.758  6732  6810 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:11:35.758  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:11:35.758  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a79786a added. We now have 3 listener(s)
09-06 19:11:35.758  1032  2028 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-06 19:11:35.760  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:11:35.761  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:11:35.761  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-06 19:11:35.761  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:11:35.761  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:11:35.761  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:11:35.761  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3464c15b added. We now have 10 listener(s)
09-06 19:11:35.761  6732  6810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:11:35.762  6732  6810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:11:35.762  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:11:35.762  6732  6810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:11:35.762  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:35.762  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:35.762  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:11:35.762  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:11:35.762  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ec0603f removed from the list
09-06 19:11:35.762  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:35.762  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34f65d0c removed from the list
09-06 19:11:35.762  6732  6810 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:11:35.762  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:35.763  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:35.763  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:35.764  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:35.764  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:35.764  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:11:35.764  6732  6810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34f65d0c not in the list
09-06 19:11:35.764  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:35.764  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:35.764  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:11:35.765  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:11:35.765  6732  6810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09,-06 19:11:35.765  6732  6810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3464c15b removed from the list
09-06 19:11:35.765  6732  6810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:11:35.765  6732  6810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:11:35.765  6732  6810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:11:35.765  6732  6810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:11:35.765  6732  6810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a79786a removed from the list
09-06 19:11:35.765  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-06 19:11:35.765  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-06 19:11:35.766  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-06 19:11:35.766  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:11:35.766  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-06 19:11:35.766  6732  6810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:11:35.774  6732  8117 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 865, name: My test thread name)
09-06 19:11:35.774  6732  8117 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 865, thread name: My test thread name)
09-06 19:11:35.774  6732  8117 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 865, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-06 19:11:35.777  6732  8118 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 867, name: My test thread name)
09-06 19:11:35.777  6732  8118 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 867, thread name: My test thread name)
09-06 19:11:35.777  6732  8118 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 867, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-06 19:11:35.779  6732  6810 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-06 19:11:35.779  6732  6810 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-06 19:11:35.779  6732  6810 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-06 19:11:35.779  6732  6810 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-06 19:11:35.779  6732  6810 D com.test.thalitest.ThaliTestRunner: Total duration: 22896 ms
09-06 19:11:35.780  6732  6810 I jxcore-log: *Native tests were executed*
09-06 19:11:35.780  6732  6810 I jxcore-log: 
09-06 19:11:35.780  6732  6810 I jxcore-log: Total number of executed tests:  80
09-06 19:11:35.780  6732  6810 I jxcore-log: 
09-06 19:11:35.781  6732  6810 I jxcore-log: Number of passed tests:  80
09-06 19:11:35.781  6732  6810 I jxcore-log: 
09-06 19:11:35.781  6732  6810 I jxcore-log: Number of failed tests:  0
09-06 19:11:35.781  6732  6810 I jxcore-log: 
09-06 19:11:35.781  6732  6810 I jxcore-log: Number of ignored tests:  0
09-06 19:11:35.781  6732  6810 I jxcore-log: 
09-06 19:11:35.781  6732  6810 I jxcore-log: Total duration:  22896
09-06 19:11:35.781  6732  6810 I jxcore-log: 
09-06 19:11:35.781  6732  6810 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-06 19:11:35.781  6732  6810 I jxcore-log: 
09-06 19:11:35.788  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:11:35.788  6732  6810 I jxcore-log: 
,09-06 19:11:35.791  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:11:35.791  6732  6810 I jxcore-log: 
09-06 19:11:35.792  6732  6732 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-06 19:11:35.793  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:11:35.793  6732  6810 I jxcore-log: 
09-06 19:11:35.794  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:11:35.794  6732  6810 I jxcore-log: 
09-06 19:11:35.795  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:11:35.795  6732  6810 I jxcore-log: 
09-06 19:11:35.796  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:11:35.796  6732  6810 I jxcore-log: 
09-06 19:11:35.799  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:11:35.799  6732  6810 I jxcore-log: 
09-06 19:11:35.801  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:11:35.801  6732  6810 I jxcore-log: 
09-06 19:11:35.801  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:11:35.801  6732  6810 I jxcore-log: 
,09-06 19:11:35.802  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:11:35.802  6732  6810 I jxcore-log: 
09-06 19:11:35.803  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:11:35.803  6732  6810 I jxcore-log: 
09-06 19:11:35.804  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:11:35.804  6732  6810 I jxcore-log: 
09-06 19:11:35.806  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:11:35.806  6732  6810 I jxcore-log: 
09-06 19:11:35.806  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:11:35.806  6732  6810 I jxcore-log: 
09-06 19:11:35.807  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:11:35.807  6732  6810 I jxcore-log: 
09-06 19:11:35.808  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:11:35.808  6732  6810 I jxcore-log: 
09-06 19:11:35.809  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:11:35.809  6732  6810 I jxcore-log: 
09-06 19:11:35.809  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:11:35.809  6732  6810 I jxcore-log: 
09-06 19:11:35.810  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:11:35.810  6732  6810 I jxcore-log: 
09-06 19:11:35.811  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:11:35.811  6732  6810 I jxcore-log: 
09-06 19:11:35.812  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:11:35.812  6732  6810 I jxcore-log: 
09-06 19:11:35.812  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:11:35.812  6732  6810 I jxcore-log: 
,09-06 19:11:35.813  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:11:35.813  6732  6810 I jxcore-log: 
09-06 19:11:35.814  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:11:35.814  6732  6810 I jxcore-log: 
09-06 19:11:35.815  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:11:35.815  6732  6810 I jxcore-log: 
09-06 19:11:35.815  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:11:35.815  6732  6810 I jxcore-log: 
09-06 19:11:35.816  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:11:35.816  6732  6810 I jxcore-log: 
09-06 19:11:35.817  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:11:35.817  6732  6810 I jxcore-log: 
09-06 19:11:35.818  6732  6810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:11:35.818  6732  6810 I jxcore-log: 
09-06 19:11:35.837  8059  8059 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,09-06 19:11:35.877  7714  7831 D UEI.SmartControl: Internal timer expired: 3
09-06 19:11:35.877  7714  7831 D UEI.SmartControl: unbind internal service
,09-06 19:11:35.880  7714  7714 D UEI.SmartControl: Service.onUnbind: IControl
09-06 19:11:35.880  7714  7714 D UEI.SmartControl: Service.onDestroy
09-06 19:11:35.880  7714  7714 D UEI.SmartControl: Lock is in USE false
09-06 19:11:35.880  7714  7714 D UEI.SmartControl: unbind internal service
09-06 19:11:35.881  7714  7714 D serial_port: close(fd = 24)
09-06 19:11:35.884  7714  7714 I UEI.SmartControl: Serial port is closed.
09-06 19:11:35.884  7714  7714 I UEI.SmartControl: Serial port is closed.
09-06 19:11:35.884  7714  7714 D UEI.SmartControl: Blaster closed
09-06 19:11:35.884  7714  7714 D UEI.SmartControl: Shut down QS...
09-06 19:11:35.884  7714  7714 D UEI.SmartControl: Stopping QS lib
09-06 19:11:35.884  7714  7714 D UEI.SmartControl: QS lib stop result = true
09-06 19:11:35.884  7714  7714 D UEI.SmartControl: Stopped QS lib
09-06 19:11:35.884  7714  7714 D UEI.SmartControl: QS shutdown complete
09-06 19:11:35.901  8059  8059 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:11:35.902  8059  8130 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-06 19:11:35.913  1032  8080 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-06 19:11:35.914  1032  8080 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-06 19:11:35.914  1032  8080 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-06 19:11:35.915  1032  8080 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-06 19:11:35.915  1032  8080 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-06 19:11:35.915  1032  8080 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-06 19:11:35.915  1032  8080 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-06 19:11:35.915  1032  8080 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-06 19:11:35.915  1032  8080 D DhcpStateMachine: RunningState
09-06 19:11:35.916  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:11:35.923  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:35.962  1032  1968 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8133 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-06 19:11:35.963  1032  1968 I ActivityManager: Killing 7211:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,09-06 19:11:36.007  8127  8127 D AndroidRuntime: 
09-06 19:11:36.007  8127  8127 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-06 19:11:36.010  8127  8127 D AndroidRuntime: CheckJNI is OFF
,09-06 19:11:36.075  8059  8129 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-06 19:11:36.133  8127  8127 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-06 19:11:36.182  1032  1090 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,09-06 19:11:36.182  1032  1090 I ActivityManager: Killing 6732:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,09-06 19:11:36.240  1032  2327 I WindowState: WIN DEATH: Window{9fdc251 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-06 19:11:36.242  1032  1544 D WifiService: Client connection lost with reason: 4
09-06 19:11:36.260  1032  2327 D InputDispatcher: Window went away: Window{9fdc251 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-06 19:11:36.396  1032  1090 I ActivityManager:   Force finishing activity ActivityRecord{264614e2 u0 com.test.thalitest/.MainActivity t6}
,09-06 19:11:36.457   347   353 E GBMv2   : DFP En is all cleared set to be enabled
,09-06 19:11:36.475  1032  1967 W libprocessgroup: failed to open /acct/uid_10093/pid_7211/cgroup.procs: No such file or directory
,09-06 19:11:36.485  1032  1968 W ActivityManager: Spurious death for ProcessRecord{37ab3180 6732:com.test.thalitest/u0a118}, curProc for 6732: null
09-06 19:11:36.488  1032  1115 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,09-06 19:11:36.493  1032  1115 I ActivityManager:   Force finishing activity ActivityRecord{264614e2 u0 com.test.thalitest/.MainActivity t6 f}
09-06 19:11:36.493  1032  1115 W ActivityManager: Duplicate finish request for ActivityRecord{264614e2 u0 com.test.thalitest/.MainActivity t6 f}
09-06 19:11:36.514  8133  8133 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-06 19:11:36.519  2077  2077 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-06 19:11:36.520  1969  1985 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-06 19:11:36.521  1969  1985 D SplitWindowPolicy: topRunningActivity=ActivityInfo{29dd7707 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-06 19:11:36.521  2077  2077 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-06 19:11:36.523  1969  1984 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-06 19:11:36.523  1969  1984 D SplitWindowPolicy: topRunningActivity=ActivityInfo{23fa0034 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-06 19:11:36.523  2077  2077 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-06 19:11:36.524  2077  2197 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-06 19:11:36.543  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-06 19:11:36.546  2029  2029 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-06 19:11:36.546  3790  3790 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,09-06 19:11:36.547  4518  4518 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-06 19:11:36.547  4518  4518 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-06 19:11:36.547  4518  4518 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-06 19:11:36.547  4518  4518 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
,09-06 19:11:36.548  4518  4518 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 19:11:36.548  4518  4518 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 19:11:36.548  4518  4518 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:11:36.548  4518  4518 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-06 19:11:36.548  4518  4518 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:11:36.548  4518  4518 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:11:36.548  4518  4518 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-06 19:11:36.548  4518  4518 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-06 19:11:36.550  2469  2598 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-06 19:11:36.551  7613  7613 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-06 19:11:36.551  7613  7613 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-06 19:11:36.568  4627  4627 I art     : Explicit concurrent mark sweep GC freed 8186(467KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 1.251ms total 66.699ms
,09-06 19:11:36.581  1032  1480 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-06 19:11:36.595  1032  1089 W InputMethodInfo: Duplicated subtype definition found: , voice
,09-06 19:11:36.609  1032  2327 V SIM_STK : Menu title from STK is T-Mobile
,09-06 19:11:36.637  1032  1032 D administrator: Handling package changes for user 0
09-06 19:11:36.653  1930  1930 D ActionManagerService: notifyUserLog: 1000003
09-06 19:11:36.653  2077  2077 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,09-06 19:11:36.655  3790  4504 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-06 19:11:36.658  2077  2077 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-06 19:11:36.660  2077  2077 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-06 19:11:36.660  2077  2077 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-06 19:11:36.663  1603  1660 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-06 19:11:36.663  1603  1660 D KeyguardModel: createShortcutInfo...
09-06 19:11:36.664  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,09-06 19:11:36.665  8133  8133 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-06 19:11:36.667  2077  2077 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-06 19:11:36.669  1930  1930 D ActionManagerService: notifyUserLog: 1000004
09-06 19:11:36.669  3790  4502 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-06 19:11:36.672  3790  4504 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-06 19:11:36.674  2077  2077 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
,09-06 19:11:36.674  2077  2077 I GBoardWebViewUtils: , create_time: 1430832262123
09-06 19:11:36.674  2077  2077 I GBoardWebViewUtils: , expire_time: 0
09-06 19:11:36.674  2077  2077 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-06 19:11:36.674  2077  2077 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-06 19:11:36.674  2077  2077 I GBoardWebViewUtils: , display: false
09-06 19:11:36.674  2077  2077 I GBoardWebViewUtils: , animation: false }
09-06 19:11:36.674  2077  2077 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-06 19:11:36.674  2077  2077 I GBoardWebViewUtils: , create_time: 1430832262287
09-06 19:11:36.674  2077  2077 I GBoardWebViewUtils: , expire_time: 0
09-06 19:11:36.674  2077  2077 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-06 19:11:36.674  2077  2077 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-06 19:11:36.674  2077  2077 I GBoardWebViewUtils: , display: false
09-06 19:11:36.674  2077  2077 I GBoardWebViewUtils: , animation: false }
09-06 19:11:36.674  2077  2077 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472828323135
09-06 19:11:36.674  2077  2077 I GBoardWebViewUtils: , create_time: 1472828323917
09-06 19:11:36.674  2077  2077 I GBoardWebViewUtils: , expire_time: 0
09-06 19:11:36.674  2077  2077 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-06 19:11:36.674  2077  2077 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-06 19:11:36.674  2077  2077 I GBoardWebViewUtils: , display: false
09-06 19:11:36.674  2077  2077 I GBoardWebViewUtils: , animation: false }
09-06 19:11:36.679  2077  8167 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,09-06 19:11:36.692  1603  1660 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-06 19:11:36.692  1603  1660 D KeyguardModel: createShortcutInfo...
,09-06 19:11:36.699  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
,09-06 19:11:36.700  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-06 19:11:36.705  1603  1660 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-06 19:11:36.705  1603  1660 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:11:36.705  1603  1660 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-06 19:11:36.706  1603  1660 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-06 19:11:36.709  1603  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:11:36.709  1603  1660 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-06 19:11:36.709  2077  2077 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-06 19:11:36.710  2077  2077 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-06 19:11:36.719  1603  1660 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-06 19:11:36.719  1603  1660 D KeyguardModel: createShortcutInfo...
09-06 19:11:36.725  1895  1895 D SplitUIManager: split_name #11 / not available #0
09-06 19:11:36.726  1895  1895 D SplitUIService: removed split : 
09-06 19:11:36.730  1603  1660 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-06 19:11:36.730  1603  1660 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-06 19:11:36.733  1603  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:11:36.733  1603  1660 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-06 19:11:36.734  1603  1660 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-06 19:11:36.734  1603  1660 D KeyguardModel: createShortcutInfo...
09-06 19:11:36.737  1603  1660 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:11:36.737  1603  1660 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-06 19:11:36.737  1603  1660 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-06 19:11:36.737  1603  1660 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-06 19:11:36.742  1603  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:11:36.742  1603  1660 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,09-06 19:11:36.744  1032  2004 V SIM_STK : Menu title from STK is T-Mobile
09-06 19:11:36.744  1032  2004 V SIM_STK : Menu title from STK is T-Mobile
09-06 19:11:36.759  1603  1660 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-06 19:11:36.759  1603  1660 D KeyguardModel: createShortcutInfo...
,09-06 19:11:36.764  1603  1603 D KeyguardModel: handleShortcutListChanged...
09-06 19:11:36.764  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-06 19:11:36.772  1895  1895 D SplitUIManager: split_name #11 / not available #0
09-06 19:11:36.772  1895  1895 I SplitUIService: split app #11
09-06 19:11:36.773  1603  1660 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-06 19:11:36.773  1603  1660 D KeyguardModel: createShortcutInfo...
09-06 19:11:36.780  1603  1660 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-06 19:11:36.780  1603  1660 D KeyguardModel: createShortcutInfo...
,09-06 19:11:36.783  1603  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:11:36.783  1603  1660 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-06 19:11:36.785  1603  1660 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-06 19:11:36.785  1603  1660 D KeyguardModel: createShortcutInfo...
09-06 19:11:36.792  1603  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:11:36.793  1603  1660 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-06 19:11:36.793  1603  1660 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-06 19:11:36.793  1603  1660 D KeyguardModel: createShortcutInfo...
09-06 19:11:36.794  1603  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:11:36.794  1603  1660 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-06 19:11:36.796  1603  1660 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-06 19:11:36.796  1603  1660 D KeyguardModel: createShortcutInfo...
09-06 19:11:36.796  1032  1968 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-06 19:11:36.797  7613  7613 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-06 19:11:36.797  7613  7613 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-06 19:11:36.797  7613  7613 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-06 19:11:36.797  7613  7613 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-06 19:11:36.797  7613  7613 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-06 19:11:36.797  7613  7613 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 19:11:36.797  7613  7613 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-06 19:11:36.797  7613  7613 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-06 19:11:36.797  7613  7613 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-06 19:11:36.797  7613  7613 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-06 19:11:36.797  7613  7613 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-06 19:11:36.804  1032  1032 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-06 19:11:36.804  1032  1032 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-06 19:11:36.804  1032  1032 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-06 19:11:36.819  1032  1967 V SIM_STK : Menu title from STK is T-Mobile
,09-06 19:11:36.821  1032  1577 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-06 19:11:36.826  8059  8129 D LgDataFeature: LgDataFeature() Constructor: none
09-06 19:11:36.826  8059  8129 D LgDataFeature: LgDataFeature() Constructor Done, null
09-06 19:11:36.830  8133  8133 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-06 19:11:36.830  8133  8133 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-06 19:11:36.831  8133  8133 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-06 19:11:36.831  8133  8133 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-06 19:11:36.831  8133  8133 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-06 19:11:36.832  8133  8133 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-06 19:11:36.833  2077  2091 I art     : Background partial concurrent mark sweep GC freed 6965(317KB) AllocSpace objects, 6(19MB) LOS objects, 34% free, 60MB/92MB, paused 8.671ms total 33.528ms
09-06 19:11:36.836  8133  8133 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,09-06 19:11:36.840  1603  1603 D KeyguardModel: handleShortcutListChanged...
09-06 19:11:36.840  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-06 19:11:36.858  2077  2077 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-06 19:11:36.859  2077  2077 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,09-06 19:11:36.863  2077  2077 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:11:36.864  2077  2077 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-06 19:11:36.865  2077  2077 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-06 19:11:36.866  2077  2077 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-06 19:11:36.867  2077  2077 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-06 19:11:36.883  2077  2077 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-06 19:11:36.883  2077  2077 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:11:36.890  2077  2285 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-06 19:11:36.890  2077  2285 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-06 19:11:36.896  2077  2077 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,09-06 19:11:36.898  2077  2077 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-06 19:11:36.898  1032  1095 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{eb6f7d7 u0 com.lge.launcher2/.Launcher t5} time:225149
09-06 19:11:36.898  2077  2077 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:11:36.906  2077  2077 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-06 19:11:36.909  2077  2077 D [Concierge]WidgetView: change position of spinner
09-06 19:11:36.909  2680  2680 D [Concierge]Service: onStartCommand(). Type : 8
09-06 19:11:36.910  2680  2680 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,09-06 19:11:36.911  2680  2680 D [Concierge]Service: Update widget ID : 11
09-06 19:11:36.911  2680  2680 D [Concierge]Service: onStartCommand(). Type : 0
09-06 19:11:36.911  2077  2077 I [Concierge]WidgetView: initWebView(). Time : 1473181896911
09-06 19:11:36.916  8133  8133 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:11:36.917  8133  8133 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:11:36.920  8059  8129 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
09-06 19:11:36.925  8133  8133 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-06 19:11:36.929  8133  8133 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-06 19:11:36.929  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-06 19:11:36.931  6829  6829 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-06 19:11:36.932  8133  8133 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-06 19:11:36.933  8059  8059 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:11:36.933  8059  8130 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:11:36.942  8059  8129 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,09-06 19:11:36.944  2077  2077 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 588810111
09-06 19:11:36.945  2077  2077 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-06 19:11:36.945  2077  2077 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-06 19:11:36.945  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 19:11:36.949  8059  8129 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
09-06 19:11:36.949  8059  8129 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-06 19:11:36.950  8059  8129 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-06 19:11:36.950  2077  2077 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@20f3ceff
09-06 19:11:36.950  2077  2077 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-06 19:11:36.951  8059  8129 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-06 19:11:36.952  2077  2077 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-06 19:11:36.952  2077  2077 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:11:36.952  8059  8129 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
09-06 19:11:36.953  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:36.955  8059  8129 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,09-06 19:11:36.964  2077  2077 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-06 19:11:36.964  2077  2077 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-06 19:11:36.965  2077  2077 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-06 19:11:36.965  2077  2077 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473181700185, New one : 1473181896911
09-06 19:11:36.965  2077  2077 D [Concierge]WidgetView: Unregister all receivers
09-06 19:11:36.965  2077  2077 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-06 19:11:36.967  2077  2077 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:11:36.968  2077  2077 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-06 19:11:36.969  2077  2077 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-06 19:11:36.971  2077  2077 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-06 19:11:36.971  8133  8133 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:11:36.971  8133  8133 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:11:36.972  2077  2077 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-06 19:11:36.973  2077  2077 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-06 19:11:36.973  8059  8129 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
09-06 19:11:36.974  2077  2077 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:11:36.974  2077  2077 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-06 19:11:36.981  8133  8133 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-06 19:11:36.984  1032  1115 I art     : Explicit concurrent mark sweep GC freed 82956(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.722ms total 457.375ms
09-06 19:11:36.985  8059  8059 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:11:36.985  8059  8130 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-06 19:11:37.009  1032  1089 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:11:37.010  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 19:11:37.015  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:37.020  8133  8133 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:11:37.021  8133  8133 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:11:37.021  8133  8133 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 19:11:37.023  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-06 19:11:37.023  6829  6829 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-06 19:11:37.023  6829  6829 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-06 19:11:37.023  6829  6829 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-06 19:11:37.023  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-06 19:11:37.023  6829  6829 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-06 19:11:37.023  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-06 19:11:37.023  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-06 19:11:37.023  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-06 19:11:37.023  6829  6829 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-06 19:11:37.023  6829  6829 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-06 19:11:37.024  6829  6829 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-06 19:11:37.025  8059  8059 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:11:37.025  8059  8130 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:11:37.028  2077  2077 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-06 19:11:37.029  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:11:37.032  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:37.036  8133  8133 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:11:37.036  8133  8133 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:11:37.036  8133  8133 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:11:37.038  8059  8059 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:11:37.038  8059  8130 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:11:37.039  1032  1089 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-06 19:11:37.045  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:11:37.047  2077  2077 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-06 19:11:37.047  2077  2077 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-06 19:11:37.050  2077  2077 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-06 19:11:37.052  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:37.056  8133  8133 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:11:37.056  8133  8133 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:11:37.057  8133  8133 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-06 19:11:37.063  8059  8059 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:11:37.065  8059  8130 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:11:37.067  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 19:11:37.067  2077  2077 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-06 19:11:37.070  2077  2077 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@34e0128 time:225320
,09-06 19:11:37.073  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:37.077  8133  8133 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:11:37.077  8133  8133 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:11:37.078  8133  8133 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:11:37.080  8059  8059 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:11:37.080  8059  8130 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-06 19:11:37.083  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:11:37.088  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:37.090  1032  1538 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:11:37.090  1032  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:11:37.091  1032  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:11:37.091  1032  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:11:37.091  1032  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:11:37.091  1032  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-06 19:11:37.092  1032  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-06 19:11:37.092  1032  1545 D ConnectivityService: identical MTU - not setting
09-06 19:11:37.092  1032  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-06 19:11:37.092  1032  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-06 19:11:37.092  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:11:37.092  1032  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:11:37.092  8133  8133 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:11:37.092  1032  1545 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-06 19:11:37.092  8133  8133 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:11:37.092  8133  8133 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:11:37.094  1603  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-06 19:11:37.104  8059  8059 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:11:37.104  8059  8130 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-06 19:11:37.112  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 19:11:37.113  1817  8182 I CheckinService: active receiver: enabled
,09-06 19:11:37.117  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-06 19:11:37.136  8133  8133 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:11:37.136  8133  8133 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:11:37.137  1817  8182 I CheckinService: Preparing to send checkin request
09-06 19:11:37.137  1817  8182 I EventLogService: Accumulating logs since 1473181878457
09-06 19:11:37.141  8133  8133 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:11:37.144  8059  8059 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:11:37.147  8127  8127 D AndroidRuntime: Shutting down VM
09-06 19:11:37.162  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-06 19:11:37.166  2077  2077 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
09-06 19:11:37.167  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:37.173  8133  8133 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:11:37.173  8133  8133 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:11:37.173  8133  8133 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-06 19:11:37.175  8059  8059 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:11:37.178  8013  8013 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-06 19:11:37.180  8013  8013 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:11:37.183  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 19:11:37.185  1817  8182 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-06 19:11:37.188  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:37.193  8133  8133 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:11:37.193  8133  8133 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:11:37.193  8133  8133 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-06 19:11:37.194  8133  8133 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-06 19:11:37.194  8133  8133 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-06 19:11:37.196  8059  8059 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-06 19:11:37.200  8013  8013 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-06 19:11:37.202  8013  8013 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-06 19:11:37.204  2077  2928 I GBoardtInterface: onReloaded()
09-06 19:11:37.206  2077  2077 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-06 19:11:37.207  6829  6829 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-06 19:11:37.207  3790  4502 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,09-06 19:11:37.209  3790  3806 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-06 19:11:37.213  6829  6829 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-06 19:11:37.215  1930  1930 D ActionManagerService: notifyUserLog: 1000001
09-06 19:11:37.217  8133  8133 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-06 19:11:37.218  8133  8133 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-06 19:11:37.218  3790  4504 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-06 19:11:37.218  3790  4504 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,09-06 19:11:37.219  8133  8133 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-06 19:11:37.219  8133  8133 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-06 19:11:37.220  8133  8133 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-06 19:11:37.222  8059  8059 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-06 19:11:37.222  1930  1930 D ActionManagerService: notifyUserLog: 1000001
09-06 19:11:37.226  8059  8059 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-06 19:11:37.226  3790  4504 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-06 19:11:37.226  3790  4504 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-06 19:11:37.226  3790  4504 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-06 19:11:37.226  3790  4504 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-06 19:11:37.227  1817  1817 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-06 19:11:37.227  3790  4502 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-06 19:11:37.233  2201  2201 I ConfigService: onCreate
,09-06 19:11:37.233  2201  2201 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-06 19:11:37.233  2077  2077 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-06 19:11:37.233  2077  2077 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-06 19:11:37.234  1817  1817 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-06 19:11:37.236  2077  2077 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-06 19:11:37.236  2077  2077 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-06 19:11:37.239  2077  2077 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-06 19:11:37.239  2077  2077 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1472828323135&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-06 19:11:37.244  2201  2201 I ConfigService: onBind returning update interface
,09-06 19:11:37.247  2201  2201 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-06 19:11:37.247  2201  2201 I ConfigService: onBind returning config service
09-06 19:11:37.252  2201  2201 I ConfigService: onDestroy
09-06 19:11:37.255  1817  8187 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-06 19:11:37.282  5966  8192 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,09-06 19:11:37.292  1817  8194 I PeopleContactsSync: CP2 sync disabled
09-06 19:11:37.294  1817  4758 I Icing   : doRemovePackageData com.test.thalitest
,09-06 19:11:37.311  1817  8193 W GmsApplication: Using Auth Proxy for data requests.
,09-06 19:11:37.332  2201  4281 I art     : Explicit concurrent mark sweep GC freed 7483(439KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 832us total 16.909ms
,09-06 19:11:37.335  1817  8193 W GmsApplication: Using Auth Proxy for data requests.
09-06 19:11:37.361  7019  7019 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,09-06 19:11:37.392  7238  7254 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-06 19:11:37.392  7238  7254 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-06 19:11:37.392  7238  7254 I Adreno-EGL: Build Date: 12/12/14 금
09-06 19:11:37.392  7238  7254 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-06 19:11:37.392  7238  7254 I Adreno-EGL: Remote Branch: 
09-06 19:11:37.392  7238  7254 I Adreno-EGL: Local Patches: 
09-06 19:11:37.392  7238  7254 I Adreno-EGL: Reconstruct Branch: 
,09-06 19:11:37.398  1032  1115 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8197 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-06 19:11:37.405  2258  8207 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-06 19:11:37.431  1032  1048 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8216 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-06 19:11:37.494  1817  8189 I art     : Explicit concurrent mark sweep GC freed 32063(2MB) AllocSpace objects, 18(284KB) LOS objects, 51% free, 30MB/62MB, paused 1.111ms total 24.734ms
09-06 19:11:37.496  1817  1829 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
09-06 19:11:37.497  1817  1829 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
09-06 19:11:37.497  1817  1829 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,09-06 19:11:37.516  1817  8189 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-06 19:11:37.516  1817  8189 E DriveAsyncService: disk I/O error (code 3850)
09-06 19:11:37.516  1817  8189 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-06 19:11:37.516  1817  8189 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-06 19:11:37.516  1817  8189 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
09-06 19:11:37.516  1817  8189 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-06 19:11:37.516  1817  8189 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-06 19:11:37.516  1817  8189 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-06 19:11:37.516  1817  8189 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
09-06 19:11:37.516  1817  8189 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.c(SourceFile:438)
09-06 19:11:37.516  1817  8189 E DriveAsyncService: 	at com.google.android.gms.drive.database.d.g(SourceFile:1384)
09-06 19:11:37.516  1817  8189 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.al.a(SourceFile:15)
09-06 19:11:37.516  1817  8189 E DriveAsyncService: 	at com.google.android.gms.common.service.c.onHandleIntent(SourceFile:60)
09-06 19:11:37.516  1817  8189 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-06 19:11:37.516  1817  8189 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:11:37.516  1817  8189 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:11:37.516  1817  8189 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 19:11:37.520  2258  8207 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
09-06 19:11:37.521  2258  8207 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-06 19:11:37.521  2258  8207 E AndroidRuntime: Process: android.process.acore, PID: 2258
09-06 19:11:37.521  2258  8207 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-06 19:11:37.521  2258  8207 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-06 19:11:37.521  2258  8207 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
09-06 19:11:37.521  2258  8207 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
09-06 19:11:37.521  2258  8207 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-06 19:11:37.521  2258  8207 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
09-06 19:11:37.521  2258  8207 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
09-06 19:11:37.521  2258  8207 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
09-06 19:11:37.521  2258  8207 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
09-06 19:11:37.521  2258  8207 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
09-06 19:11:37.521  2258  8207 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
09-06 19:11:37.521  2258  8207 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-06 19:11:37.521  225,8  8207 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-06 19:11:37.521  2258  8207 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-06 19:11:37.521  2258  8207 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:11:37.521  2258  8207 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
09-06 19:11:37.521  2258  8207 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 19:11:37.526  2258  8207 I Process : Sending signal. PID: 2258 SIG: 9
,09-06 19:11:37.532  1032  8234 E DropBoxManagerService: Can't write: system_app_crash
09-06 19:11:37.532  1032  8234 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-06 19:11:37.532  1032  8234 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-06 19:11:37.532  1032  8234 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 19:11:37.532  1032  8234 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 19:11:37.532  1032  8234 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 19:11:37.532  1032  8234 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-06 19:11:37.532  1032  8234 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
09-06 19:11:37.532  1032  8234 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 19:11:37.532  1032  8234 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 19:11:37.532  1032  8234 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 19:11:37.532  1032  8234 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-06 19:11:37.532  1032  8234 E DropBoxManagerService: 	... 5 more
,09-06 19:11:37.539  8216  8216 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:11:37.539  8216  8216 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-06 19:11:37.540  8216  8216 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-06 19:11:37.540  8216  8216 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-06 19:11:37.556   341   426 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,09-06 19:11:37.557  3227  8236 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-06 19:11:37.567   347   355 E GBMv2   : DFP En is all cleared set to be enabled
09-06 19:11:37.567   347   355 E GBMv2   : Set value is all cleared set the max
09-06 19:11:37.568   347   355 I GBMv2   : DFP Enabled. Ignore VFP set

```
