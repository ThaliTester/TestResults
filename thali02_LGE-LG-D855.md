#### Test 807613747a577d4_thali02_LGE-LG-D855 Logs


```
--------- beginning of system
08-16 12:13:06.056  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=881370966 [*alarm*], flags=0x0
,--------- beginning of main
08-16 12:13:51.522  6799  6799 D AndroidRuntime: 
08-16 12:13:51.522  6799  6799 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 12:13:51.529  6799  6799 D AndroidRuntime: CheckJNI is OFF
08-16 12:13:51.730  6799  6799 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-16 12:13:51.741  1036  1560 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 12:13:51.758  1926  1941 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-16 12:13:51.764  1036  1560 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-16 12:13:51.766  1036  1560 D ActivityManager: setTaskToReturnTo : TaskRecord{15a33f22 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 12:13:51.766  1036  1560 D ActivityManager: setTaskToReturnTo : TaskRecord{15a33f22 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 12:13:51.768  1036  1560 D WindowStateEx: AppWindowTokenEx init.. 
08-16 12:13:51.769   340   350 E GBMv2   : DFP En is all cleared set to be enabled
08-16 12:13:51.798  1036  1560 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6814 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-16 12:13:51.801  6799  6799 D AndroidRuntime: Shutting down VM
08-16 12:13:51.855  1926  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-16 12:13:51.856  1926  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{394e13f co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 12:13:51.856  1926  3157 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-16 12:13:51.857  1926  3157 D SplitWindowPolicy: topRunningActivity=ActivityInfo{18bf4a0c co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 12:13:51.931  6814  6814 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-16 12:13:52.028  6814  6814 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 12:13:52.038  6814  6814 I LibraryLoader: Loading: webviewchromium
08-16 12:13:52.041  6814  6814 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 2082-2086)
,08-16 12:13:52.042  6814  6814 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 12:13:52.071  6814  6814 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c671445}
,08-16 12:13:52.073  6814  6814 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 12:13:52.073  6814  6814 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 12:13:52.083  6814  6814 I BrowserStartupController: Initializing chromium process, renderers=0
,08-16 12:13:52.084  6814  6814 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 12:13:52.098  6814  6814 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-16 12:13:52.099  6814  6814 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-16 12:13:52.099  6814  6814 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-16 12:13:52.105   315   315 V AudioPolicyService: registerClient() client 0xb1005640, uid 10118
08-16 12:13:52.112  6814  6814 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 12:13:52.112  6814  6814 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 12:13:52.112  6814  6814 I Adreno-EGL: Build Date: 12/12/14 금
08-16 12:13:52.112  6814  6814 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 12:13:52.112  6814  6814 I Adreno-EGL: Remote Branch: 
08-16 12:13:52.112  6814  6814 I Adreno-EGL: Local Patches: 
08-16 12:13:52.112  6814  6814 I Adreno-EGL: Reconstruct Branch: 
08-16 12:13:52.113  1036  1119 D BluetoothManagerService: Message: 20
08-16 12:13:52.113  1036  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f94129c:true
,08-16 12:13:52.197  6814  6854 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-16 12:13:52.200  6814  6814 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-16 12:13:52.219  6814  6814 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 12:13:52.224  6814  6814 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-16 12:13:52.229  6814  6814 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,08-16 12:13:52.233  6814  6814 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-16 12:13:52.233  6814  6814 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-16 12:13:52.249  6814  6814 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-16 12:13:52.256  6814  6814 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 12:13:52.256  6814  6814 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 12:13:52.300  6814  6866 D OpenGLRenderer: Render dirty regions requested: true
,08-16 12:13:52.300  6814  6866 I OpenGLRenderer: Initialized EGL, version 1.4
,08-16 12:13:52.308  6814  6866 D OpenGLRenderer: Enabling debug mode 0
08-16 12:13:52.320  6814  6814 D Atlas   : Validating map...
,08-16 12:13:52.324  1036  1637 D SplitWindow: check instance of lgWin Window{23f9c0f6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-16 12:13:52.354  1036  1110 W ActivityManager: Activity pause timeout for ActivityRecord{2a0a6db3 u0 com.test.thalitest/.MainActivity t6}
,08-16 12:13:52.363  6814  6864 D LgDataFeature: LgDataFeature() Constructor: none
08-16 12:13:52.363  6814  6864 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 12:13:52.490  1036  1120 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +634ms (total +718ms)
,08-16 12:13:52.490  6814  6814 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@129c0bd8 time:302535
08-16 12:13:52.491  1036  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2a0a6db3 u0 com.test.thalitest/.MainActivity t6} time:302536
08-16 12:13:52.601  6814  6814 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-16 12:13:52.601  6814  6814 I chromium: 
,08-16 12:13:52.629  6814  6814 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 12:13:52.701  6814  6864 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-16 12:13:52.701  6814  6864 I chromium: 
,08-16 12:13:52.846  6814  6881 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435060736
,08-16 12:13:52.869  6814  6881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 12:13:52.869  6814  6881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 12:13:52.869  6814  6881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 12:13:52.869  6814  6881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 12:13:52.869  6814  6881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-16 12:13:52.869  6814  6881 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17cb891c added. We now have 1 listener(s)
08-16 12:13:52.875  1036  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 12:13:52.878  6814  6881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-16 12:13:52.880  6814  6881 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 12:13:52.881  6814  6881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:13:52.882  6814  6881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:13:52.890  6814  6881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 12:13:52.890  6814  6881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 12:13:52.890  6814  6881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 12:13:52.890  6814  6881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-16 12:13:52.890  6814  6881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 12:13:52.890  6814  6881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 12:13:52.890  6814  6881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 12:13:52.890  6814  6881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 12:13:52.890  6814  6881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 12:13:52.890  6814  6881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 12:13:52.890  6814  6881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 12:13:52.890  6814  6881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 12:13:52.890  6814  6881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 12:13:52.890  6814  6881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-16 12:13:52.890  6814  6881 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2548a8ab added. We now have 1 listener(s)
08-16 12:13:52.891  6814  6881 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 12:13:52.895  1036  1529 D WifiService: New client listening to asynchronous messages
08-16 12:13:52.899  6814  6881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 12:13:52.900  6814  6881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-16 12:13:52.900  6814  6881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 12:13:52.900  6814  6881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 12:13:52.900  6814  6881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-16 12:13:52.904  6814  6881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:13:52.905  1036  1944 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:13:52.907  6814  6881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-16 12:13:52.917  6814  6881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-16 12:13:52.917  6814  6881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:13:52.917  6814  6881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:13:52.917  6814  6881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:13:52.917  6814  6881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:13:52.917  6814  6881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:13:52.917  6814  6881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:13:52.917  6814  6881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:13:52.917  6814  6881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:13:52.918  6814  6881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 12:13:52.918  6814  6881 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:13:52.920  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:13:52.922  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:13:52.924  6814  6881 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 12:13:52.960  6814  6814 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 12:13:53.698   340   352 E GBMv2   : DFP En is all cleared set to be enabled
08-16 12:13:53.699   340   352 E GBMv2   : Set value is all cleared set the max
08-16 12:13:53.699   340   352 I GBMv2   : DFP Enabled. Ignore VFP set
,08-16 12:13:54.081  6814  6884 W jxcore-log: Initializing JXcore engine
08-16 12:13:54.081  6814  6884 W jxcore-log: JXcore engine is ready
,08-16 12:13:54.111  6884  6884 W Thread-802: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7512]" dev="sockfs" ino=7512 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-16 12:13:54.111  6884  6884 W Thread-802: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-16 12:13:54.111  6884  6884 W Thread-802: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8622]" dev="sockfs" ino=8622 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-16 12:13:54.111  6884  6884 W Thread-802: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-16 12:13:54.111  6884  6884 W Thread-802: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[33377]" dev="sockfs" ino=33377 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-16 12:13:54.134  6814  6884 W jxcore-log: Starting JXcore engine
08-16 12:13:54.300  6814  6884 W jxcore-log: Platform android
08-16 12:13:54.300  6814  6884 W jxcore-log: 
08-16 12:13:54.300  6814  6884 W jxcore-log: Process ARCH arm
08-16 12:13:54.300  6814  6884 W jxcore-log: 
,08-16 12:13:54.744  6814  6884 I jxcore-log: JXcore Cordova bridge is ready!
08-16 12:13:54.744  6814  6884 I jxcore-log: 
08-16 12:13:54.744  6814  6884 W jxcore-log: JXcore engine is started
,08-16 12:13:54.751  6814  6881 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-16 12:13:54.754  6814  6814 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-16 12:14:00.059  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-16 12:14:00.059  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
08-16 12:14:00.060  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-16 12:14:00.060  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
,08-16 12:14:00.066  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
08-16 12:14:00.066  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
08-16 12:14:00.068  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
08-16 12:14:00.069  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
,08-16 12:14:11.001  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 12:14:11.001  6814  6884 I jxcore-log: 
,08-16 12:14:11.004  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 12:14:11.004  6814  6884 I jxcore-log: 
08-16 12:14:11.008  6814  6884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:14:11.008  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:14:11.008  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:14:11.008  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:14:11.008  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:14:11.008  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:14:11.008  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:14:11.008  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:14:11.010  6814  6884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:14:11.012  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 12:14:11.012  6814  6884 I jxcore-log: 
08-16 12:14:11.014  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 12:14:11.014  6814  6884 I jxcore-log: 
,08-16 12:14:11.351  6814  6884 I jxcore-log: Running unit tests
08-16 12:14:11.351  6814  6884 I jxcore-log: 
,08-16 12:14:11.352  6814  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 12:14:11.353  6814  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28113fd6 added. We now have 2 listener(s)
,08-16 12:14:11.353  1036  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:14:11.355  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 12:14:11.355  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:14:11.355  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 12:14:11.355  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:14:11.355  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64f9257 added. We now have 2 listener(s)
08-16 12:14:11.355  6814  6884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:14:11.356  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 12:14:11.358  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:14:11.360  6814  6884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:14:11.360  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:14:11.360  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:14:11.360  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:14:11.360  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:14:11.360  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:14:11.360  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:14:11.360  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:14:11.361  6814  6884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:14:11.361  6814  6884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:14:11.362  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:14:11.363  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:14:11.364  6814  6884 D ExecuteNativeTests: Running unit tests
08-16 12:14:16.518  6814  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:14:16.519  6814  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f64409d added. We now have 3 listener(s)
,08-16 12:14:16.527  1036  1944 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:14:16.536  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 12:14:16.536  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:14:16.536  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:14:16.537  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:14:16.537  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 added. We now have 3 listener(s)
08-16 12:14:16.537  6814  6884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 12:14:16.539  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 12:14:16.544  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:14:16.547  6814  6884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:14:16.547  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:14:16.547  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:14:16.547  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:14:16.547  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:14:16.547  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:14:16.547  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:14:16.547  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:14:16.549  6814  6884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:14:16.549  6814  6884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 12:14:16.554  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:14:16.556  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:14:16.560  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 12:14:16.563  6814  6884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 12:14:16.563  6814  6884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 12:14:16.567  6814  6884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 12:14:16.571  6814  6884 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-16 12:14:16.573  6814  6884 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 12:14:16.573  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 12:14:16.576  6814  6884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 12:14:16.576  6814  6884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 12:14:16.576  6814  6884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 12:14:16.579  6814  6884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:14:16.580  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:14:16.580  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 12:14:16.582  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:14:16.582  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:16.582  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 12:14:16.582  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:14:16.583  6814  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f64409d removed from the list
08-16 12:14:16.583  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:16.583  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 removed from the list
08-16 12:14:16.583  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:14:16.583  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:16.584  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:16.584  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:16.585  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:14:16.585  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:14:16.585  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:16.586  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:16.588  6814  6884 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-16 12:14:16.588  6814  6884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:14:16.588  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:14:16.588  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:14:16.589  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:14:16.589  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:16.589  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:16.589  6814  6884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f64409d not in the list
08-16 12:14:16.589  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:16.589  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:16.589  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:14:16.589  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:16.589  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16, 12:14:16.589  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:16.589  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:16.591  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:14:16.591  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:14:16.591  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:16.592  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
,08-16 12:14:16.603  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 12:14:16.603  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 12:14:16.603  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 12:14:16.603  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 12:14:16.603  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 12:14:16.603  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 12:14:16.603  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 12:14:16.603  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 12:14:16.603  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 12:14:16.603  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 12:14:16.603  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 12:14:16.603  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 12:14:16.603  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 12:14:16.603  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 12:14:16.604  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 12:14:16.604  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 12:14:16.604  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 12:14:16.604  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 12:14:16.604  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 12:14:16.604  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 12:14:16.604  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 12:14:16.604  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 12:14:16.604  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 12:14:16.604  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 12:14:16.604  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 12:14:16.604  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 12:14:16.604  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
08-16 12:14:16.604  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 12:14:16.604  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 12:14:16.604  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 12:14:16.604  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 12:14:16.604  6814  6884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:14:16.604  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:14:16.604  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:14:16.607  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:14:16.607  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:16.607  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:16.607  6814  6884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f64409d not in the list
08-16 12:14:16.607  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:16.607  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:16.607  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:14:16.607  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:16.607  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:16.607  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:16.607  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:14:16.613  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:14:16.613  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:14:16.613  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:16.613  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:16.614  6814  6884 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 12:14:16.617  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:14:16.621  6814  6884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:14:16.621  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:14:16.621  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:14:16.621  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:14:16.621  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:14:16.621  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:14:16.621  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:14:16.621  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:14:16.624  6814  6884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:14:16.624  6814  6884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:14:16.626  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:14:16.628  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:14:16.629  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:14:16.629  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 12:14:16.630  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 12:14:16.630  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:14:16.630  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 12:14:16.634  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 12:14:16.636  1036  1058 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:14:16.643  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 12:14:16.650  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 12:14:16.654  6814  6884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 12:14:16.656  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 12:14:16.657  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 12:14:16.659  6814  6884 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 12:14:16.660  6814  6884 I io.jxcore.node.ConnectionHelper: start: OK
08-16 12:14:21.671  6814  6884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:14:21.672  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:14:21.672  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 12:14:21.678  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:14:21.679  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:21.679  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 12:14:21.679  6814  6884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f64409d not in the list
08-16 12:14:21.679  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:21.679  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:21.679  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:14:21.679  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:24.003  1036  3448 I LocationManagerService: remove 17665f66
08-16 12:14:24.004  1036  3448 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-16 12:14:24.004  1036  3448 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-16 12:14:24.013  1036  3448 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-16 12:14:24.016  1036  3448 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-16 12:14:24.017  1036  3448 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-16 12:14:26.680  6814  6884 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 12:14:26.695  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:14:26.701  6814  6884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:14:26.701  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:14:26.701  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:14:26.701  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:14:26.701  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:14:26.701  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:14:26.701  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:14:26.701  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:14:26.704  6814  6884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:14:26.704  6814  6884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:14:26.706  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:14:26.708  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:14:26.709  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:14:26.709  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 12:14:26.709  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 12:14:26.709  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:14:26.709  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 12:14:26.715  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 12:14:26.717  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 12:14:26.719  6814  6884 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 12:14:26.719  6814  6884 I io.jxcore.node.ConnectionHelper: start: OK
08-16 12:14:26.722  6814  6884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:14:26.722  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:14:26.722  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:14:26.722  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:14:26.722  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:26.722  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 12:14:26.722  6814  6884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f64409d not in the list
08-16 12:14:26.722  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:26.723  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:26.723  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:14:26.723  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:26.723  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:26.723  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:26.724  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:14:26.724  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:14:26.727  6814  6884 D BluetoothLeScanner: could not find callback wrapper
08-16 12:14:26.727  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:14:26.727  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:26.727  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:26.728  6814  6884 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 12:14:26.734  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:14:26.739  6814  6884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:14:26.739  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:14:26.739  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:14:26.739  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:14:26.739  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:14:26.739  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:14:26.739  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:14:26.739  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:14:26.740  6814  6884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:14:26.741  6814  6884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 12:14:26.744  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:14:26.746  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:14:26.747  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:14:26.747  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 12:14:26.747  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 12:14:26.747  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:14:26.747  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 12:14:26.753  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 12:14:26.755  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 12:14:26.757  6814  6884 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 12:14:26.757  6814  6884 I io.jxcore.node.ConnectionHelper: start: OK
08-16 12:14:31.757  6814  6884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:14:31.758  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:14:31.758  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 12:14:36.768  6814  6884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:14:36.768  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:14:36.768  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 12:14:36.776  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 12:14:36.776  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.776  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 12:14:36.776  6814  6884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f64409d not in the list
08-16 12:14:36.776  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:36.776  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:36.776  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:14:36.776  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.779  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.779  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.782  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:14:36.782  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 12:14:36.788  6814  6884 D BluetoothLeScanner: could not find callback wrapper
08-16 12:14:36.788  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:14:36.789  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:36.789  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:36.790  6814  6884 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 12:14:36.791  6814  6884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:14:36.791  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:14:36.791  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:14:36.791  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:14:36.791  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.791  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.791  6814  6884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f64409d not in the list
08-16 12:14:36.791  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:36.791  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:36.792  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:14:36.792  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.792  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.792  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.792  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.793  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:14:36.793  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:14:36.794  6814  6884 D BluetoothLeScanner: could not find callback wrapper
08-16 12:14:36.794  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:14:36.794  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:36.794  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:36.795  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 12:14:36.796  6814  6884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:14:36.796  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:14:36.796  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The, current state already matches the desired outcome of this operation, skipping...
08-16 12:14:36.796  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:14:36.796  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.796  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.797  6814  6884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f64409d not in the list
08-16 12:14:36.797  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:36.797  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:36.797  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:14:36.797  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.797  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.797  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.797  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:14:36.804  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:14:36.804  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:14:36.805  6814  6884 D BluetoothLeScanner: could not find callback wrapper
08-16 12:14:36.805  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:14:36.805  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:36.805  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:36.806  6814  6884 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-16 12:14:36.806  6814  6884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:14:36.806  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:14:36.806  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:14:36.807  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:14:36.807  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.807  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.807  6814  6884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f64409d not in the list
08-16 12:14:36.807  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:36.807  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:36.807  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:14:36.807  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.807  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.808  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.808  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.809  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:14:36.809  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:14:36.811  6814  6884 D BluetoothLeScanner: could not find callback wrapper
08-16 12:14:36.811  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:14:36.811  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:36.811  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:36.812  6814  6884 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 12:14:36.812  6814  6884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:14:36.812  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connecti,vity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:14:36.812  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 12:14:36.816  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:14:36.816  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.816  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.816  6814  6884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f64409d not in the list
08-16 12:14:36.816  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:36.816  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:36.816  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:14:36.817  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.817  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.817  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.817  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.818  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:14:36.819  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:14:36.819  6814  6884 D BluetoothLeScanner: could not find callback wrapper
08-16 12:14:36.819  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:14:36.819  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:36.819  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:36.820  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 12:14:36.824  6814  6884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 12:14:36.824  6814  6884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 12:14:36.828  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 12:14:36.829  6814  6884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 12:14:36.829  6814  6884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 12:14:36.829  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 12:14:36.829  6814  6884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 12:14:36.830  6814  6884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 12:14:36.830  6814  6884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:14:36.830  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:14:36.831  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:14:36.831  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:14:36.831  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.831  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.831  6814  6884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f64409d not in the list
08-16 12:14:36.831  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:36.832  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:36.832  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:14:36.832  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.832  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.832  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.832  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.834  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:14:36.834  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:14:36.835  6814  6884 D BluetoothLeScanner: could not find callback wrapper
08-16 12:14:36.835  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:14:36.835  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:36.836  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:36.841  6814  6884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 12:14:36.841  6814  6884 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 12:14:36.841  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-16 12:14:36.851  6814  6884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 12:14:36.853  6814  6884 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 12:14:36.853  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 12:14:36.854  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 12:14:36.854  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 12:14:36.854  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 12:14:36.854  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 12:14:36.854  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 12:14:36.854  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 12:14:36.854  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 12:14:36.854  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 12:14:36.854  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 12:14:36.854  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 12:14:36.854  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 12:14:36.854  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 12:14:36.854  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 12:14:36.854  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 12:14:36.854  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 12:14:36.854  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 12:14:36.854  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 12:14:36.854  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 12:14:36.854  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 12:14:36.854  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 12:14:36.854  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 12:14:36.854  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 12:14:36.854  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 12:14:36.854  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2,410:2410:2410:2410:2410]
08-16 12:14:36.855  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 12:14:36.855  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 12:14:36.855  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 12:14:36.855  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 12:14:36.855  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-16 12:14:36.859  6814  6884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 12:14:36.859  6814  6884 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 12:14:36.860  6814  6884 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 12:14:36.860  6814  6884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 12:14:36.860  6814  6884 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 12:14:36.860  6814  6884 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 12:14:36.861  6814  6884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 12:14:36.861  6814  6884 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 12:14:36.861  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-16 12:14:36.863  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 12:14:36.864  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 12:14:36.864  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 12:14:36.867  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 12:14:36.867  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 12:14:36.867  6814  6884 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 12:14:36.867  6814  6884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 12:14:36.867  6814  6884 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 12:14:36.868  6814  6884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:14:36.868  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:14:36.868  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:14:36.868  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:14:36.868  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.869  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.869  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 12:14:36.869  6814  6884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f64409d not in the list
08-16 12:14:36.869  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:36.869  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:36.869  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:14:36.869  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.869  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.869  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.869  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:14:36.874  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:14:36.875  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:14:36.876  6814  6884 D BluetoothLeScanner: could not find callback wrapper
08-16 12:14:36.876  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:14:36.876  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:36.876  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:36.880  6814  6884 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 12:14:36.880  6814  6884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:14:36.880  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:14:36.880  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:14:36.881  6814  6898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 866
,08-16 12:14:36.884  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:14:36.884  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.884  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.884  6814  6884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f64409d not in the list
08-16 12:14:36.884  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:36.884  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:36.885  6814  6897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 866)
08-16 12:14:36.885  6814  6897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 866)
08-16 12:14:36.886  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:14:36.886  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.886  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.886  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.886  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.887  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:14:36.887  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:14:36.888  6814  6884 D BluetoothLeScanner: could not find callback wrapper
08-16 12:14:36.888  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:14:36.888  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:36.888  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:36.889  6814  6884 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 12:14:36.890  6814  6884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:14:36.890  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:14:36.890  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:14:36.890  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:14:36.890  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.890  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.891  6814  6884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f64409d not in the list
08-16 12:14:36.891  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:,14:36.891  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:36.891  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:14:36.891  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.891  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.891  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.891  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.892  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:14:36.892  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:14:36.893  6814  6884 D BluetoothLeScanner: could not find callback wrapper
08-16 12:14:36.894  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:14:36.894  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:36.894  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:36.894  6814  6884 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 12:14:36.895  6814  6884 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,08-16 12:14:36.899  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 12:14:36.899  6814  6884 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 12:14:36.899  6814  6884 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 12:14:36.900  6814  6884 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 12:14:36.900  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 12:14:36.900  6814  6884 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 12:14:36.900  6814  6884 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 12:14:36.900  6814  6884 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 12:14:36.900  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 12:14:36.900  6814  6884 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 12:14:36.900  6814  6884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:14:36.901  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:14:36.901  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:14:36.901  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:14:36.901  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.901  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.901  6814  6884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f64409d not in the list
08-16 12:14:36.901  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:36.901  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:36.901  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:14:36.901  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.901  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.901  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.902  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.903  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:14:36.903  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:14:36.903  6814  6884 D BluetoothLeScanner: could not find callback wrapper
08-16 12:14:36,.904  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:14:36.904  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:36.904  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:36.904  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:14:36.904  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.904  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:36.904  6814  6884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f64409d not in the list,
,08-16 12:14:36.904  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:36.904  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:36.905  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:14:36.905  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:36.905  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-16 12:14:41.906  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:14:41.906  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:41.906  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:14:41.906  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:41.907  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-16 12:14:41.907  6814  6884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f64409d not in the list
08-16 12:14:41.907  6814  6884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:14:41.908  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:14:41.908  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:14:41.923  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:14:41.923  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:41.923  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:14:41.923  6814  6884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f64409d not in the list
08-16 12:14:41.928  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:41.928  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:41.928  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop,
,08-16 12:14:41.928  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:41.928  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:41.928  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:41.928  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:14:41.933  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:14:41.933  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:14:41.934  6814  6884 D BluetoothLeScanner: could not find callback wrapper
08-16 12:14:41.934  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:14:41.934  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:41.934  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:41.938  6814  6884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 12:14:41.939  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:14:41.941  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 12:14:41.942  6814  6884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 12:14:41.942  6814  6884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-16 12:14:41.944  6814  6814 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 12:14:41.945  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 12:14:41.946  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 12:14:41.947  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:14:41.947  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 12:14:41.947  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 12:14:41.947  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 12:14:41.947  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:41.947  6814  6884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 12:14:41.950  6814  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 12:14:41.950  6814  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 12:14:41.952  6814  6814 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 12:14:41.952  6814  6884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f64409d not in the list
08-16 12:14:41.952  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:41.953  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 12:14:41.953  6814  6884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 12:14:41.953  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 12:14:41.954  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 12:14:41.958  6814  6884 D BluetoothLeScanner: could not find callback wrapper
08-16 12:14:41.958  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:14:41.958  6814  6884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 12:14:41.958  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:41.958  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:41.960  6814  6884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 12:14:41.960  6814  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 12:14:41.960  6814  6814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 12:14:41.960  6814  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 12:14:41.961  6814  6814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 12:14:41.961  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:41.961  6814  6884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:14:41.961  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:14:41.961  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:14:41.962  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:14:41.962  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:41.962  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:41.962  6814  6884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f64409d not in the list
08-16 12:14:41.962  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:41.962  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:41.962  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:14:41.962  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:41.962  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:41.962  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:14:41.962  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:41.963  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:14:41.963  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:14:41.963  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:41.964  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list,
08-16 12:14:41.967  6814  6884 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-16 12:14:41.973  6814  6884 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 12:14:41.973  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 12:14:41.974  6814  6884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 12:14:41.976  6814  6884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 12:14:41.977  6814  6884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:14:41.977  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:14:41.977  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:14:41.979  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:14:41.979  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:41.979  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:41.979  6814  6884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f64409d not in the list
08-16 12:14:41.979  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:41.980  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:41.980  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:14:41.980  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:41.980  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:41.980  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:41.980  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:41.982  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:14:41.982  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:14:41.982  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:41.982  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
,08-16 12:14:41.987  1036  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:14:41.988  1036  1871 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:14:41.989  1036  1980 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:14:41.991  6814  6884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:14:41.991  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:14:41.991  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:14:41.991  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:14:41.991  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:41.991  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:41.991  6814  6884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f64409d not in the list
08-16 12:14:41.991  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:41.991  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:41.991  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:14:41.991  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:41.991  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:41.991  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:41.992  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:41.993  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:14:41.993  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:14:41.993  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:41.993  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:41.994  6814  6884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:14:41.994  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:14:41.994  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:14:41.996  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:14:41.996  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:41.996  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:41.996  6814  6884 E org.thaliproject.p2p.btconnectorlib.Con,nectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f64409d not in the list
08-16 12:14:41.996  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:41.996  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:41.996  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:14:41.996  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:41.996  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:41.996  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:41.996  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:14:42.001  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:14:42.001  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:14:42.001  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:42.002  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcd8912 not in the list
08-16 12:14:42.124  1036  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=881370966, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,08-16 12:14:42.174  2582  2582 D [Concierge]Service: onStartCommand(). Type : 9
,08-16 12:14:42.221  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=881370966 [*alarm*], flags=0x0
,08-16 12:14:42.461  6814  6814 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 12:14:47.006  6814  6884 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 12:14:47.007  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 12:14:47.008  6814  6884 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 12:14:47.008  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 12:14:47.008  6814  6884 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 12:14:47.008  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-16 12:14:47.023  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 12:14:47.024  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 12:14:47.027  6814  6884 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 12:14:47.027  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 12:14:47.027  6814  6884 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 12:14:47.027  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 12:14:47.028  6814  6884 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 12:14:47.028  6814  6884 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 12:14:47.029  6814  6884 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 12:14:47.029  6814  6884 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 12:14:47.029  6814  6884 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 12:14:47.030  6814  6884 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 12:14:47.030  6814  6884 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 12:14:47.030  6814  6884 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-16 12:14:47.031  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:14:47.031  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3166b15b added. We now have 3 listener(s)
08-16 12:14:47.031  6814  6884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:14:47.034  6814  6884 D BluetoothAdapter: enable(): BT is already enabled..!
,08-16 12:14:47.039  1036  1907 D WifiServiceImplEx: setWifiEnabled: true pid=6814, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 12:14:47.040  1036  1907 D WifiService: setWifiEnabled: true pid=6814, uid=10118
08-16 12:14:47.040  1036  1907 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 12:14:52.049  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:14:52.049  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a256df8 added. We now have 4 listener(s)
08-16 12:14:52.049  6814  6884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 12:14:52.062  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:52.062  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a256df8 removed from the list
08-16 12:14:52.062  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:14:52.062  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:52.062  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:52.063  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:14:52.063  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f4192d1 added. We now have 4 listener(s)
08-16 12:14:52.063  6814  6884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:14:52.065  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:14:52.065  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f4192d1 removed from the list
08-16 12:14:52.065  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:14:52.065  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:14:52.065  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:14:52.066  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:14:52.066  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@184d6136 added. We now have 4 listener(s)
08-16 12:14:52.066  6814  6884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 12:14:52.072  1036  1944 D WifiServiceImplEx: setWifiEnabled: false pid=6814, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 12:14:52.072  1036  1944 D WifiService: setWifiEnabled: false pid=6814, uid=10118
08-16 12:14:52.073  1036  1944 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 12:14:52.092  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 12:14:52.093  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 12:14:52.093  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-16 12:14:52.094  1036  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 12:14:52.095  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 12:14:52.096  1036  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-16 12:14:52.096  1036  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 12:14:52.096  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 12:14:52.097  1036  1523 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 12:14:52.097  1036  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 12:14:52.097  1036  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 12:14:52.098  1036  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 12:14:52.098  1036  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 12:14:52.100  1036  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:14:52.100  1036  1962 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@399f37c4 mBinding = false
,08-16 12:14:52.108  1036  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 12:14:52.108  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 12:14:52.108  2679  2679 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 12:14:52.109  1036  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:52.109  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:52.110  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 12:14:52.110  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 12:14:52.111  1036  1523 D WifiNative-wlan0: SET ps 1: returned true
08-16 12:14:52.112  1036  2837 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:52.116   311   894 D CommandListener: Clearing all IP addresses on wlan0
,08-16 12:14:52.130  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 12:14:52.131  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 12:14:52.131  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-16 12:14:52.131  1036  1119 D BluetoothManagerService: Message: 2
08-16 12:14:52.132  1036  1119 D BluetoothManagerService: Sending off request.
08-16 12:14:52.133  4296  4318 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 12:14:52.152  4296  4374 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 12:14:52.152  4296  4374 D BluetoothAdapterProperties: Setting state to 13
08-16 12:14:52.152  4296  4374 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-16 12:14:52.163  4296  4374 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 12:14:52.163  4296  4374 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 12:14:52.167  4296  4381 D BluetoothAdapterProperties: Scan Mode:20
,08-16 12:14:52.169  4296  4374 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-16 12:14:52.172  4296  4701 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 12:14:52.172  4296  4701 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 12:14:52.172  4296  4701 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 12:14:52.172  4296  4701 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 12:14:52.172  4296  4701 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 12:14:52.172  4296  4701 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 12:14:52.172  4296  4701 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 12:14:52.172  4296  4701 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-16 12:14:52.173  4296  4702 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 12:14:52.173  4296  4748 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 12:14:52.174  4296  4750 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 12:14:52.174  4296  4756 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 12:14:52.175  4296  4374 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 12:14:52.177  4296  4523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-16 12:14:52.177  4296  4523 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-16 12:14:52.178  4296  4523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 12:14:52.178  4296  4523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 12:14:52.178  4296  4523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 12:14:52.178  4296  4523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 12:14:52.178  4296  4523 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 12:14:52.178  4296  4523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 12:14:52.178  4296  4523 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 12:14:52.178  4296  4523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 12:14:52.179  4296  4523 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 12:14:52.179  4296  4523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 12:14:52.179  4296  4523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 12:14:52.179  4296  4523 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-16 12:14:52.217  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:14:52.225  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 12:14:52.225  1036  1119 D BluetoothManagerService: Message: 60
08-16 12:14:52.225  1036  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 12:14:52.226  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-16 12:14:52.226  1036  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-16 12:14:52.240  1036  1110 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6927 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-16 12:14:52.248  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-16 12:14:52.250  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:14:52.253  4296  4296 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:14:52.253  4296  4296 D BluetoothMapService: STATE_TURNING_OFF
08-16 12:14:52.253  4296  4296 V BluetoothMapService: Handler(): got msg=4
08-16 12:14:52.253  4296  4296 D BluetoothMapService: MAP Service closeService in
,08-16 12:14:52.253  4296  4296 D BluetoothMapMasInstance: MAP Service shutdown
08-16 12:14:52.253  4296  4296 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 12:14:52.253  4296  4296 V BluetoothMapService: MAP Service closeService out
08-16 12:14:52.254  4296  4296 V BtOppService: Receiver DISABLED_ACTION 
08-16 12:14:52.254  4296  4296 I BtOppRfcommListener: stopping Accept Thread
08-16 12:14:52.254  4296  4296 V BtOppRfcommListener: close mBtServerSocket
08-16 12:14:52.254  4296  4296 V BtOppRfcommListener: waiting for thread to terminate
08-16 12:14:52.255  4296  4748 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 12:14:52.256  4296  4296 V BtOppRfcommListener: done waiting for thread to terminate
08-16 12:14:52.260  1036  1058 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-16 12:14:52.260  1036  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 12:14:52.260  1036  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:52.260  1036  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 12:14:52.260  1036  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:52.261  1036  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-16 12:14:52.263  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:14:52.263  6814  6884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:14:52.263  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:14:52.263  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:14:52.263  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:14:52.263  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:14:52.263  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:14:52.263  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:14:52.263  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:14:52.264  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:14:52.264  6814  6884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:14:52.264  6814  6884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:14:52.269  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:14:52.269  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:14:52.269  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:14:52.269  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:14:52.269  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:14:52.269  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:14:52.269  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:14:52.269  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:14:52.269  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:14:52.274  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:14:52.280  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:14:52.280  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:14:52.280  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:14:52.280  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:14:52.280  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:14:52.280  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:14:52.280  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:14:52.280  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:14:52.280  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:14:52.281  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:14:52.281  6814  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:14:52.283  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:14:52.283  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:14:52.283  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:14:52.283  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:14:52.283  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:14:52.283  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:14:52.283  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:14:52.283  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:14:52.283  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:14:52.284  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:14:52.284  6814  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:14:52.287  1036  1530 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 12:14:52.287  1036  1530 D DSQN    : disableDataServiceNotify
08-16 12:14:52.287   311  6941 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-16 12:14:52.288  1036  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 12:14:52.289  1036  1530 D DSQN    : stop dsqn bin
08-16 12:14:52.289  1036  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-16 12:14:52.291  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:14:52.292  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:14:52.293  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:14:52.295  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:14:52.297  1036  1530 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-16 12:14:52.297  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:14:52.297  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:14:52.298  1036  1530 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:14:52.298  1036  1530 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-16 12:14:52.299  1036  1530 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-16 12:14:52.299  1036  1530 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-16 12:14:52.299  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 12:14:52.299  1036  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:52.299  1036  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:52.299  1036  2824 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,08-16 12:14:52.302  1587  2059 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 12:14:52.303  1036  1110 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6942 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 12:14:52.304  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-16 12:14:52.306  1926  1926 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-16 12:14:52.306  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:52.306  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:52.307  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 12:14:52.307  1036  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 12:14:52.307  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 12:14:52.308  4296  4296 V BtOppService: onDestroy
08-16 12:14:52.308  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 12:14:52.308  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 12:14:52.308  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 12:14:52.308  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 12:14:52.309  1036  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 12:14:52.310  1036  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 12:14:52.310  1036  1530 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:14:52.310  1036  1530 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:14:52.310  1036  1530 D NetworkManagementService: Removing idletimer
08-16 12:14:52.310  4296  4296 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 12:14:52.311  1036  1530 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:52.311  1036  1530 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-16 12:14:52.311  1837  1837 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-16 12:14:52.311  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 12:14:52.312  1036  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 12:14:52.312  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 12:14:52.312  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 12:14:52.312  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 12:14:52.312  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 12:14:52.313  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-16 12:14:52.314  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:14:52.314  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:14:52.315  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:52.315  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:52.315  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 12:14:52.316  1036  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:14:52.316  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:14:52.316  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:14:52.316  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:14:52.316  1036  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:14:52.317  1036  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:52.317  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:52.317  1036  1522 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1f9bde6b
08-16 12:14:52.317  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:14:52.317  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:14:52.317  1036  1522 D LGWifiP2pService: P2pDisablingState
08-16 12:14:52.317  1036  1522 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:52.317  1036  1522 D LGWifiP2pService: p2p socket connection lost
08-16 12:14:52.317  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 12:14:52.317  1036  1522 D LGWifiP2pService: P2pDisabledState
08-16 12:14:52.317  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-16 12:14:52.318  1036  1523 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 12:14:52.318  1036  1541 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:52.318  1036  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:14:52.318  1036  1542 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:52.318  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROP,ERTIES 0 0
08-16 12:14:52.318  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:14:52.319  1036  1523 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:14:52.319  1036  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 12:14:52.319  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 12:14:52.319  1926  1926 D WfdsService: WifiP2pState is changed : false
08-16 12:14:52.319  1926  2300 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 12:14:52.319  1926  2300 D WfdsService: Set the WFDS Monitor: false
08-16 12:14:52.319  1036  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-16 12:14:52.319  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 12:14:52.319  1036  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:52.319  2679  2679 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 12:14:52.319  1036  1522 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:52.319  1926  2300 D WfdsMonitor: WFDS Monitor is stopped
08-16 12:14:52.319  1926  2300 D WfdsService: STATE : WfdsDisabledState - enter
08-16 12:14:52.320  1926  2751 D CtrlSupplicant: Received on exit socket, terminate
08-16 12:14:52.320  1926  2751 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 12:14:52.320  1926  2751 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 12:14:52.320  1926  2751 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 12:14:52.320  1926  2301 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-16 12:14:52.320  1926  2300 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 12:14:52.322  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 12:14:52.322  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 12:14:52.322  1036  1523 D WifiNative-wlan0: SET ps 1: returned true
08-16 12:14:52.323   311   894 D CommandListener: Clearing all IP addresses on wlan0
08-16 12:14:52.326  1036  1523 D WifiNative-p2p0: doBoolean: TERMINATE
08-16 12:14:52.326  1036  1523 D WifiNative-p2p0: TERMINATE: returned true
08-16 12:14:52.326  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-16 12:14:52.327  1036  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 12:14:52.327  1036  1523 E WifiStateMachine: useWiFiOffloading() : false
08-16 12:14:52.327  1036  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 12:14:52.327  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:52.327  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:52.327  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 12:14:52.330  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 12:14:52.332  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 12:14:52.334  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:14:52.334  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 12:14:52.339  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:14:52.339  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:14:52.339  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:14:52.339  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:14:52.339  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:14:52.339  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:14:52.339  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:14:52.339  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:14:52.339  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:14:52.344  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:14:52.344  6814  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:14:52.348  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:14:52.348  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:14:52.348  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:14:52.348  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:14:52.348  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:14:52.348  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:14:52.348  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:14:52.348  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:14:52.348  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:14:52.348  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:14:52.348  6814  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:14:52.350  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:14:52.350  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:14:52.350  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:14:52.350  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:14:52.350  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:14:52.350  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:14:52.350  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:14:52.350  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:14:52.350  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:14:52.353  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:14:52.353  6814  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 12:14:52.364  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 12:14:52.365  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:14:52.366  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:14:52.369  6942  6942 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 12:14:52.369  6942  6942 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-16 12:14:52.370  6942  6942 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 12:14:52.370  6942  6942 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-16 12:14:52.371  6942  6942 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 12:14:52.371  6942  6942 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 12:14:52.378  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 12:14:52.379  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:14:52.379  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:14:52.380  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:14:52.380  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:14:52.380  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:14:52.386  2679  2679 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 12:14:52.386  2679  2679 I wpa_supplicant: monitor socket send errors count : 1
08-16 12:14:52.386  2679  2679 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1926-2\x00 that cannot receive messages
08-16 12:14:52.388  1036  2740 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-16 12:14:52.388  1036  2740 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 12:14:52.397  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 12:14:52.397  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:14:52.398  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 12:14:52.399  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:14:52.412  6927  6927 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-16 12:14:52.413  6927  6927 W LG Account v2.2: No ProfileInfo entries
08-16 12:14:52.413  6927  6927 I LG Account v2.2: isEnabled: false
08-16 12:14:52.413  6927  6927 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 12:14:52.413  6927  6927 I Feature : [Lifetracker]Country: EU
08-16 12:14:52.413  6927  6927 I Feature : [Lifetracker]Operator: OPEN
08-16 12:14:52.413  6927  6927 I Feature : [Lifetracker]Ranking support: false
08-16 12:14:52.413  6927  6927 I Feature : [Lifetracker]Comfort support: false
08-16 12:14:52.413  6927  6927 I Feature : [Lifetracker]Accessory: true
08-16 12:14:52.413  6927  6927 I Feature : [Lifetracker]Health device: true
08-16 12:14:52.413  6927  6927 I Feature : [Lifetracker]Extra Pedometer: false
08-16 12:14:52.413  6927  6927 I Feature : [Lifetracker]Blood glucose device: false
08-16 12:14:52.413  6927  6927 I Feature : [Lifetracker]Device Number: 3
,08-16 12:14:52.420  6441  6441 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:14:52.424  2679  2679 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 12:14:52.425  1036  2740 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-16 12:14:52.425  1036  2740 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 12:14:52.425  1036  2740 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 12:14:52.425  2679  2679 W wpa_supplicant: USIM:  scard_deinit function
08-16 12:14:52.425  1036  2740 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
,08-16 12:14:52.425  1036  2740 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 12:14:52.425  1036  2740 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 12:14:52.426  1036  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=362459
08-16 12:14:52.426  1036  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=362459
08-16 12:14:52.427  1036  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=362459  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 12:14:52.427  1036  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=362460  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 12:14:52.427  1036  1119 D Tethering: InitialState.processMessage what=4
08-16 12:14:52.431  1036  2837 D DhcpStateMachine: StoppedState
08-16 12:14:52.431  1036  2837 D DhcpStateMachine: StoppedState{ when=-109ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:52.446  6942  6942 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 12:14:52.455  1036  1998 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6970 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 12:14:52.456  1036  1998 I ActivityManager: Killing 6342:com.android.defcontainer/u0a4 (adj 15): empty #17
08-16 12:14:52.486  2679  2679 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-16 12:14:52.486  1036  2740 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 12:14:52.486  1036  2740 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 12:14:52.487  1036  2740 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 12:14:52.487  1036  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-16 12:14:52.490  1036  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 12:14:52.493  1036  1637 W libprocessgroup: failed to open /acct/uid_10004/pid_6342/cgroup.procs: No such file or directory
08-16 12:14:52.496  1036  1119 D BluetoothManagerService: Message: 20
08-16 12:14:52.496  1036  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@357205cf:true
08-16 12:14:52.496  4296  4296 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 12:14:52.497  4296  4296 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:14:52.497  4296  4296 V BluetoothPbapReceiver: ***********state = 13
08-16 12:14:52.498  4296  4296 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-16 12:14:52.501  4296  4296 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:14:52.501  4296  4296 V BluetoothPbapService: state: 13
08-16 12:14:52.501  4296  4296 V BluetoothPbapService: Pbap Service closeService in
08-16 12:14:52.504  2168  2168 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 12:14:52.505  4296  4296 V BluetoothPbapService: successfully stopped pbap service
08-16 12:14:52.505  4296  4296 V BluetoothPbapService: Pbap Service closeService out
08-16 12:14:52.505  4296  4296 V BluetoothPbapService: Pbap Service onDestroy
08-16 12:14:52.505  4296  4296 V BluetoothPbapService: Pbap Service closeService in
08-16 12:14:52.505  4296  4296 V BluetoothPbapService: Pbap Service closeService out
08-16 12:14:52.505  4296  4296 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-16 12:14:52.513  1036  1119 D BluetoothManagerService: Message: 30
,08-16 12:14:52.518  1036  1119 D BluetoothManagerService: Message: 30
08-16 12:14:52.520  6942  6942 D LocalBluetoothProfileManager: Adding local MAP profile
08-16 12:14:52.521  6942  6942 D BluetoothMap: Create BluetoothMap proxy object
08-16 12:14:52.522  1036  1119 D BluetoothManagerService: Message: 30
08-16 12:14:52.526  1036  1119 D BluetoothManagerService: Message: 30
,08-16 12:14:52.529  6942  6942 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-16 12:14:52.530  6942  6942 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-16 12:14:52.543  6942  6942 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-16 12:14:52.547  6942  6942 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-16 12:14:52.547  6970  6970 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 12:14:52.552  6970  6970 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 12:14:52.553  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:14:52.556  1036  1637 I ActivityManager: Killing 6489:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-16 12:14:52.591  1036  1871 W libprocessgroup: failed to open /acct/uid_10008/pid_6489/cgroup.procs: No such file or directory
,08-16 12:14:52.591  6942  6942 D DockEventReceiver: finishStartingService: stopping service
,08-16 12:14:52.598  1036  1523 D WifiOffDelayIfNotUsed: stopMonitoring
08-16 12:14:52.598  1036  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 12:14:52.598  1036  1523 E WifiStateMachine: useWiFiOffloading() : false
08-16 12:14:52.598  1036  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 12:14:52.599  1926  1926 D WfdsService: Supplicant Connection state is changed : false
08-16 12:14:52.599  1926  2300 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-16 12:14:52.599  1926  2300 D WfdsService: Set the WFDS Monitor: false
08-16 12:14:52.599  1926  2300 D WfdsMonitor: WFDS Monitor is stopped
08-16 12:14:52.601  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:14:52.602  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 12:14:52.603  2466  2466 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:52.606  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:14:52.607  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-16 12:14:52.607  1036  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 12:14:52.607  1036  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
,08-16 12:14:52.610  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:14:52.612  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:14:52.614  6942  6942 D BluetoothInputDevice: Proxy object connected
08-16 12:14:52.615  6942  6942 D HidProfile: Bluetooth service connected
08-16 12:14:52.617  6942  6942 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 12:14:52.617  6942  6942 D PanProfile: Bluetooth service connected
08-16 12:14:52.618  6942  6942 D BluetoothMap: Proxy object connected
08-16 12:14:52.619  6942  6942 D MapProfile: Bluetooth service connected
08-16 12:14:52.619  6942  6942 D BluetoothMap: getConnectedDevices()
08-16 12:14:52.620  6942  6942 D BluetoothMap: Bluetooth is Not enabled
08-16 12:14:52.621  6942  6942 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-16 12:14:52.633  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:14:52.681  6942  6942 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 12:14:52.681  6942  6942 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 12:14:52.698  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:14:52.704  6942  6942 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 12:14:52.713  6942  6942 D BluetoothPermissionRequest: onReceive
08-16 12:14:52.718  6942  6942 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 12:14:52.735  1036  1060 I ActivityManager: Killing 6015:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-16 12:14:52.738  6942  6942 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 12:14:52.799  4296  4296 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-16 12:14:52.799  4296  4296 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-16 12:14:52.800  4296  4296 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-16 12:14:52.801  1036  1871 W libprocessgroup: failed to open /acct/uid_10011/pid_6015/cgroup.procs: No such file or directory
08-16 12:14:52.803  1036  1523 E WifiStateMachine:  InitialState CMD_ON_QUIT 0 0
,08-16 12:14:52.803  1036  1523 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-16 12:14:52.804  1036  1523 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:14:52.804  1036  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:14:52.825  4296  4296 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:14:52.825  4296  4296 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-16 12:14:52.827  5713  5713 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:14:52.828  4296  4296 V BluetoothFtpService: Ftp Service onStartCommand
08-16 12:14:52.828  4296  4296 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:14:52.829  4296  4296 V BluetoothFtpService: Ftp Service closeService
08-16 12:14:52.829  4296  4296 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 12:14:52.833  5713  5713 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:14:52.835  4296  4296 V BluetoothFtpService: successfully stopped ftp service
08-16 12:14:52.836  4296  4296 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 12:14:52.836  4296  4296 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 12:14:52.836  4296  4296 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 12:14:52.837  4296  4296 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:14:52.837  4296  4296 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-16 12:14:52.837  4296  4296 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 12:14:52.840  4296  4296 V BluetoothFtpService: Ftp Service onDestroy
08-16 12:14:52.840  4296  4296 V BluetoothFtpService: Ftp Service closeService
,08-16 12:14:52.911  1036  1980 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7000 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 12:14:52.915  4296  4296 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:14:52.915  4296  4296 V BluetoothSapService: state: 13
08-16 12:14:52.915  4296  4296 V BluetoothSapService: Stopping SAP server process
08-16 12:14:52.916  5713  5713 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 12:14:52.919  4296  4296 V BluetoothSapService: Sap Service closeSapService in
08-16 12:14:52.919  4296  4296 V BluetoothSapService: Close listen Socket : 
08-16 12:14:52.920  4296  4296 V BluetoothSapService: Close rfcomm Socket : 
08-16 12:14:52.920  4296  4296 V BluetoothSapService: Close sapd  Socket : 
08-16 12:14:52.925  6441  6441 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:14:52.929  6970  6970 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 12:14:52.929  6970  6970 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 12:14:52.929  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 12:14:52.935  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 12:14:52.936  4296  4296 V BluetoothSapService: Sap Service closeSapService out
08-16 12:14:52.937  4296  4296 V BluetoothSapService: Sap Service onDestroy
08-16 12:14:52.937  4296  4296 V BluetoothSapService: Sap Service closeSapService in
08-16 12:14:52.937  4296  4296 V BluetoothSapService: Close listen Socket : 
08-16 12:14:52.937  4296  4296 V BluetoothSapService: Close rfcomm Socket : 
08-16 12:14:52.937  4296  4296 V BluetoothSapService: Close sapd  Socket : 
08-16 12:14:52.937  4296  4296 V BluetoothSapService: Sap Service closeSapService out
,08-16 12:14:52.942  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:14:52.956  5713  5713 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:14:52.957  5713  5713 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 12:14:52.959  5713  5713 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 12:14:52.962  6441  6441 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:14:52.968  6970  6970 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 12:14:52.968  6970  6970 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 12:14:52.968  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:14:52.972  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:14:52.980  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:14:52.983  7000  7000 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 12:14:52.986  5713  5713 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 12:14:52.987  5713  5713 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 12:14:52.989  5713  5713 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 12:14:53.057  1036  2018 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7017 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-16 12:14:53.063  1036  2018 I ActivityManager: Killing 6041:com.android.contacts/u0a19 (adj 15): empty #17
,08-16 12:14:53.129  1036  1962 W libprocessgroup: failed to open /acct/uid_10019/pid_6041/cgroup.procs: No such file or directory
,08-16 12:14:53.183  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 12:14:53.188  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 12:14:53.188  4296  4381 D bt_hci_bdroid: cleanup
08-16 12:14:53.189  4296  4525 I bt_lpm  : LPM is already off!!!
08-16 12:14:53.189  4296  4690 I bt_userial_mct: exiting userial_read_thread
08-16 12:14:53.189  4296  4690 D bt_userial_mct: Leaving userial_evt_read_thread()
,08-16 12:14:53.189  4296  4523 W bt-btif : ag scb idx 1 not allocated
08-16 12:14:53.189  4296  4523 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 12:14:53.189  4296  4523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 12:14:53.189  4296  4523 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 12:14:53.189  4296  4523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 12:14:53.189  4296  4523 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 12:14:53.189  4296  4523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 12:14:53.189  4296  4523 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 12:14:53.189  4296  4523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 12:14:53.189  4296  4381 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 12:14:53.189  4296  4523 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 12:14:53.189  4296  4523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 12:14:53.189  4296  4523 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 12:14:53.189  4296  4523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 12:14:53.189  4296  4525 I bt_vendor: hw_epilog_process
08-16 12:14:53.189  4296  4523 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 12:14:53.189  4296  4523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 12:14:53.189  4296  4523 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 12:14:53.189  4296  4523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 12:14:53.189  4296  4523 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 12:14:53.189  4296  4523 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 12:14:53.189  4296  4523 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 12:14:53.189  4296  4523 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 12:14:53.190  4296  4381 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 12:14:53.190  4296  4381 D bt_userial_mct: userial_close
08-16 12:14:53.190  4296  4381 E bt_userial_mct: pthread_join() FAILED result:3
08-16 12:14:53.190  4296  4381 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-16 12:14:53.199  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:14:53.204  7017  7037 W FormManager: Network not available. Please check & try again.
08-16 12:14:53.221  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-16 12:14:53.221  6942  6942 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 12:14:53.221  6942  6942 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-16 12:14:53.221  6942  6942 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 12:14:53.223  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 12:14:53.229  7017  7038 V FormManager: Network unavailable.
08-16 12:14:53.232  7017  7038 V FormManager: Network unavailable.
08-16 12:14:53.233  6942  6942 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-16 12:14:53.234  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 12:14:53.234  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 12:14:53.234  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 12:14:53.234  6942  6942 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 12:14:53.234  6942  6942 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 12:14:53.238  4777  4777 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 12:14:53.239  4777  4777 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 12:14:53.241  4777  4777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:14:53.244  4777  4777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:14:53.252  6970  6970 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-16 12:14:53.252  6970  6970 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 12:14:53.252  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:14:53.254  4777  7041 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 12:14:53.258  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 12:14:53.260  4777  7043 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 12:14:53.260  4777  7043 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 12:14:53.265  4296  4381 D bt_hci_bdroid: set_power 0
08-16 12:14:53.265  4296  4381 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 12:14:53.265  4296  4381 I bt_vendor: bluetooth satus is on
08-16 12:14:53.265  4296  4381 I bt_vendor: bt-vendor : resetting BT status
,08-16 12:14:53.265  4296  4381 I bt_vendor: Starting hciattach daemon
08-16 12:14:53.265  4296  4381 I bt_vendor: try to set false
08-16 12:14:53.265  7017  7044 W FormManager: Network not available. Please check & try again.
08-16 12:14:53.266  4296  4381 I bt_vendor: Starting hciattach daemon
08-16 12:14:53.266  4296  4381 I bt_vendor: try to set false
08-16 12:14:53.267  4296  4381 I bt_vendor: cleanup
08-16 12:14:53.268  4296  4523 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 12:14:53.268  4296  4381 I GKI_LINUX: GKI_exit_task 0 done
08-16 12:14:53.268  4296  4381 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 12:14:53.270  4296  4374 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 12:14:53.270  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:14:53.276  4296  4296 D HeadsetService: Received stop request...Stopping profile...
08-16 12:14:53.278  4296  4296 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 12:14:53.278  4296  4296 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 12:14:53.278  4296  4296 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@226ed79a
08-16 12:14:53.279  4296  4475 D HeadsetStateMachine: Exit Disconnected: -1
,08-16 12:14:53.281  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-16 12:14:53.281  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 12:14:53.281  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-16 12:14:53.281  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-16 12:14:53.282  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-16 12:14:53.283  4296  4296 D A2dpService: Received stop request...Stopping profile...
,08-16 12:14:53.283  4296  4506 D A2dpStateMachine: Exit Disconnected: -1
08-16 12:14:53.284  4296  4296 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-16 12:14:53.284  7017  7045 V FormManager: Network unavailable.
08-16 12:14:53.286  4296  4296 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 12:14:53.286  4296  4296 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 12:14:53.286  4296  4296 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@226ed79a
08-16 12:14:53.290  4296  4296 D HidService: Received stop request...Stopping profile...
08-16 12:14:53.290  4296  4296 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@226ed79a
08-16 12:14:53.290  4296  4374 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 12:14:53.291  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-16 12:14:53.291  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-16 12:14:53.293  4296  4296 D HealthService: Received stop request...Stopping profile...
08-16 12:14:53.293  4296  4296 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@226ed79a
08-16 12:14:53.293  7017  7045 V FormManager: Network unavailable.
08-16 12:14:53.294  4296  4296 D HeadsetStateMachine: Unbinding service...
08-16 12:14:53.295  6942  6942 D BluetoothInputDevice: Proxy object disconnected
08-16 12:14:53.295  6942  6942 D HidProfile: Bluetooth service disconnected
08-16 12:14:53.296  4296  4296 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 12:14:53.296  4296  4296 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 12:14:53.296  4296  4296 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 12:14:53.296  4296  4296 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 12:14:53.296  4296  4296 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 12:14:53.296  4296  4296 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 12:14:53.296  4296  4296 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 12:14:53.297  4296  4296 D PanService: Received stop request...Stopping profile...
08-16 12:14:53.298  4296  4296 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@226ed79a
08-16 12:14:53.299  4296  4296 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 12:14:53.300  4296  4296 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 12:14:53.300  4296  4296 D BtGatt.GattService: stop()
08-16 12:14:53.300  6942  6942 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 12:14:53.300  6942  6942 D PanProfile: Bluetooth service disconnected
08-16 12:14:53.300  4296  4296 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 12:14:53.302  1036  1058 I ActivityManager: Killing 6538:com.lge.email/u0a23 (adj 15): empty #17
08-16 12:14:53.337  4296  4296 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@226ed79a
,08-16 12:14:53.338  1036  1637 W libprocessgroup: failed to open /acct/uid_10023/pid_6538/cgroup.procs: No such file or directory
08-16 12:14:53.344  4296  4296 D BluetoothMapService: Received stop request...Stopping profile...
08-16 12:14:53.344  4296  4296 D BluetoothMapService: stop()
08-16 12:14:53.345  4296  4296 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 12:14:53.345  4296  4296 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 12:14:53.346  4296  4296 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@226ed79a
08-16 12:14:53.348  6942  6942 D BluetoothMap: Proxy object disconnected
08-16 12:14:53.348  6942  6942 D MapProfile: Bluetooth service disconnected
08-16 12:14:53.348  4296  4296 I BluetoothA2dpServiceJni: cleanupNative
08-16 12:14:53.348  4296  4507 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 12:14:53.349  4296  4296 I GKI_LINUX: GKI_exit_task 2 done
08-16 12:14:53.349  4296  4296 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 12:14:53.349  4296  4296 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 12:14:53.349  4296  4296 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 12:14:53.350  4296  4296 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 12:14:53.350  4296  4296 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 12:14:53.350  4296  4296 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 12:14:53.351  4296  4296 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 12:14:53.351  4296  4296 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 12:14:53.352  4296  4296 V BluetoothMapService: Handler(): got msg=4
08-16 12:14:53.352  4296  4296 D BluetoothMapService: MAP Service closeService in
08-16 12:14:53.352  4296  4296 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 12:14:53.352  4296  4296 V BluetoothMapService: MAP Service closeService out
08-16 12:14:53.353  4296  4374 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 12:14:53.353  4296  4374 D BluetoothAdapterProperties: Setting state to 10
08-16 12:14:53.353  4296  4374 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-16 12:14:53.354  1036  1119 D BluetoothManagerService: Message: 60
08-16 12:14:53.354  1036  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 12:14:53.354  4296  4374 I BluetoothAdapterState: Entering OffState
08-16 12:14:53.354  1036  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-16 12:14:53.354  4296  4296 D BluetoothMapService: cleanup()
08-16 12:14:53.354  4296  4296 D BluetoothMapService: MAP Service closeService in
08-16 12:14:53.355  4296  4296 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 12:14:53.355  4296  4296 V BluetoothMapService: MAP Service closeService out
08-16 12:14:53.355  1837  2438 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:14:53.356  1036  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:14:53.357  6942  6966 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 12:14:53.358  1837  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:14:53.359  1837  2436 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:14:53.360  6942  6965 D BluetoothPan: onBluetoothStateChange on: false
08-16 12:14:53.361  1036  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 12:14:53.362  6942  6966 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 12:14:53.363  6942  6965 D BluetoothMap: onBluetoothStateChange: up=false
08-16 12:14:53.365  1036  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 12:14:53.365  1036  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-16 12:14:53.370  1036  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 12:14:53.370  1036  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 12:14:53.370  1036  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@399f37c4 mBinding = false
08-16 12:14:53.371  1036  1119 D BluetoothManagerService: Sending unbind request.
08-16 12:14:53.374  1036  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-16 12:14:53.382  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:14:53.383  1926  2118 D LGBluetoothAPIService: Message: 2
08-16 12:14:53.383  1926  2118 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@234a5f55 mBinding = false
08-16 12:14:53.383  1926  2118 D LGBluetoothAPIService: Sending unbind request.
08-16 12:14:53.385  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:14:53.385  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 12:14:53.385  4296  4381 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-16 12:14:53.387  4296  4296 I GKI_LINUX: GKI_exit_task 1 done
08-16 12:14:53.387  4296  4296 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 12:14:53.388  4296  4296 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 12:14:53.388  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:14:53.388  4296  4296 I art     : --- WEIRD: removing null entry 246
08-16 12:14:53.388  4296  4296 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-16 12:14:53.388  4296  4296 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-16 12:14:53.389  6942  6942 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 12:14:53.390  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:14:53.391  4296  4296 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,08-16 12:14:53.394  6942  6942 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
,08-16 12:14:53.394  6942  6942 D LGBluetoothEventManager: [BTUI] clear device connection state
08-16 12:14:53.398  4296  4296 I art     : System.exit called, status: 0
08-16 12:14:53.398  4296  4296 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 12:14:53.400  6942  6942 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 12:14:53.401  1587  1587 D BluetoothAdapter: 363305074: getState() :  mService = null. Returning STATE_OFF
08-16 12:14:53.401  1587  1587 D BluetoothAdapter: 363305074: getState() :  mService = null. Returning STATE_OFF
08-16 12:14:53.411  6942  6942 D DockEventReceiver: finishStartingService: stopping service
,08-16 12:14:53.431   315   315 V AudioFlinger: 4296 died, releasing its sessions
08-16 12:14:53.431   315   315 V AudioFlinger:  pid 1837 @ 0
08-16 12:14:53.431   315   315 V AudioFlinger:  pid 3288 @ 1
08-16 12:14:53.431   315   315 V AudioFlinger:  pid 3288 @ 2
08-16 12:14:53.432  6942  6942 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-16 12:14:53.436  1036  2018 I ActivityManager: Process com.android.bluetooth (pid 4296) has died
08-16 12:14:53.437  1036  2018 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-16 12:14:53.440  2168  2168 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 12:14:53.453  6942  6942 D BluetoothPermissionRequest: onReceive
,08-16 12:14:53.457  6942  6942 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 12:14:53.457  6942  6942 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-16 12:14:53.461  6942  6942 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 12:14:53.530  1036  1980 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7048 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-16 12:14:53.602  7048  7048 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-16 12:14:53.603  7048  7048 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 12:14:53.603  7048  7048 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-16 12:14:53.604  7048  7048 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 12:14:53.623  7048  7048 D BluetoothAdapterApp: Loading JNI Library
,08-16 12:14:53.652  7048  7048 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@27438253 Instance Count = 1
,08-16 12:14:53.661  7048  7048 D BluetoothAdapterApp: onCreate
,08-16 12:14:53.682  7048  7048 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-16 12:14:53.682  7048  7048 D ProfileConfigQcom: Adding HeadsetService
08-16 12:14:53.683  7048  7048 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-16 12:14:53.683  7048  7048 D ProfileConfigQcom: Adding A2dpService
08-16 12:14:53.684  7048  7048 D ProfileConfigQcom: [BTUI] HidService is supported
08-16 12:14:53.684  7048  7048 D ProfileConfigQcom: Adding HidService
08-16 12:14:53.686  7048  7048 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 12:14:53.686  7048  7048 D ProfileConfigQcom: Adding HealthService
,08-16 12:14:53.687  7048  7048 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-16 12:14:53.689  7048  7048 D ProfileConfigQcom: [BTUI] PanService is supported
,08-16 12:14:53.690  7048  7048 D ProfileConfigQcom: Adding PanService
,08-16 12:14:53.691  7048  7048 D ProfileConfigQcom: [BTUI] GattService is supported
08-16 12:14:53.691  7048  7048 D ProfileConfigQcom: Adding GattService
,08-16 12:14:53.692  7048  7048 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 12:14:53.693  7048  7048 D ProfileConfigQcom: Adding BluetoothMapService
,08-16 12:14:53.694  7048  7048 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 12:14:53.696  7048  7048 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-16 12:14:53.702  6942  6942 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-16 12:14:53.705  7048  7048 V LGMDMManagerInternal: Create singleton instance
,08-16 12:14:53.797  7048  7048 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-16 12:14:53.802  7048  7048 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-16 12:14:53.803  7048  7048 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 12:14:53.803  7048  7048 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 12:14:53.804  7048  7048 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-16 12:14:53.804  7048  7048 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-16 12:14:53.819  7000  7000 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-16 12:14:53.820  1036  1058 I ActivityManager: Killing 6063:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-16 12:14:53.852  1036  1943 W libprocessgroup: failed to open /acct/uid_10027/pid_6063/cgroup.procs: No such file or directory
,08-16 12:14:55.310  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:14:55.326  1036  1119 D Tethering: MasterInitialState.processMessage what=3
08-16 12:14:55.340  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:14:55.345  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:14:55.346  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:14:55.347  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 12:14:55.351  1036  1119 D Tethering: MasterInitialState.processMessage what=3
08-16 12:14:55.356  6441  6441 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-16 12:14:55.360  1036  1108 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 12:14:55.363  6441  6969 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 12:14:55.374  5802  5802 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 12:14:55.379  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:14:55.379  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:14:55.381  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:14:55.391  5802  5802 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 12:14:55.423  2168  2168 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:14:55.455  1036  1108 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:14:55.501  1036  1060 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7089 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-16 12:14:55.506  1036  1108 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
08-16 12:14:55.507  1036  1108 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 12:14:55.590  7089  7089 I AppUp4:AppBoxCP: onCreate
08-16 12:14:55.591  7089  7089 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-16 12:14:55.602  7089  7089 I AppUp4:DB:  setFingerPrint start
08-16 12:14:55.602  7089  7089 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-16 12:14:55.611  7089  7089 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-16 12:14:55.611  7089  7089 I AppUp4:DB:  SDK version = 21
08-16 12:14:55.611  7089  7089 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-16 12:14:55.613  7089  7089 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-16 12:14:55.615  7089  7089 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 12:14:55.615  7089  7089 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 12:14:55.618  7089  7089 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 12:14:55.618  7089  7089 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 12:14:55.626  7089  7089 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 12:14:55.678  7089  7089 D LgDataFeature: LgDataFeature() Constructor: none
08-16 12:14:55.679  7089  7089 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 12:14:55.686  7089  7089 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@c671445
08-16 12:14:55.686  7089  7089 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 12:14:55.686  7089  7089 D AppUp4:CustFacade: isPhone : true
08-16 12:14:55.687  7089  7089 D AppUp4:CustModeStarterReceiver: begin check event
08-16 12:14:55.687  7089  7089 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-16 12:14:55.687  7089  7089 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-16 12:14:55.688  7089  7109 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-16 12:14:55.688  7089  7109 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-16 12:14:55.688  7089  7109 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-16 12:14:55.690  1036  1925 I ActivityManager: Killing 6577:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-16 12:14:55.727  1036  2018 W libprocessgroup: failed to open /acct/uid_10061/pid_6577/cgroup.procs: No such file or directory
08-16 12:14:55.728  4777  4777 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 12:14:55.729  4777  4777 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-16 12:14:55.733  4777  4777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:14:55.736  4777  4777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:14:55.742  4777  7112 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 12:14:55.752  4777  7113 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:14:55.753  4777  7113 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 12:14:55.809  1036  1060 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7117 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-16 12:14:55.877  7117  7117 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 12:14:55.878  7117  7117 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 12:14:55.879  7117  7117 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 12:14:55.880  7117  7117 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 12:14:55.977  7117  7117 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 12:14:55.992  7117  7117 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-16 12:14:56.032  7117  7117 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 12:14:56.068  7117  7117 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 12:14:56.069  7117  7117 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 12:14:56.197  7117  7117 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 12:14:56.246  3288  3288 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-16 12:14:56.246  3288  3288 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 12:14:56.246  3288  3288 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 12:14:56.252  7117  7117 I HubEmail: JNI_OnLoad()
08-16 12:14:56.253  7117  7117 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 12:14:56.253  7117  7117 I HubEmail: registerNatives()
08-16 12:14:56.253  7117  7117 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 12:14:56.253  7117  7117 I HubEmail: registerNativeMethods()
08-16 12:14:56.253  7117  7117 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 12:14:56.255  7117  7117 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-16 12:14:56.297  1036  1998 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7147 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-16 12:14:56.303  7017  7144 W FormManager: Network not available. Please check & try again.
08-16 12:14:56.332   344   344 I art     : Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 531us total 26.665ms
,08-16 12:14:56.354   344   344 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 439us total 20.704ms
,08-16 12:14:56.359  7017  7145 V FormManager: Network unavailable.
08-16 12:14:56.363  7017  7145 V FormManager: Network unavailable.
08-16 12:14:56.373  1036  1962 I ActivityManager: Killing 6643:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-16 12:14:56.375   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 444us total 20.277ms
08-16 12:14:56.377  7117  7146 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:56.437  7147  7147 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 12:14:56.437  7147  7147 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 12:14:56.440  7147  7147 D PhoneMonitor: Register our PhoneStateListener
08-16 12:14:56.446  1036  1058 W libprocessgroup: failed to open /acct/uid_10080/pid_6643/cgroup.procs: No such file or directory
08-16 12:14:56.466  7147  7147 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-16 12:14:56.470  7147  7147 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 12:14:56.490  7147  7147 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-16 12:14:56.491  7147  7147 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-16 12:14:56.492  7147  7147 D TelephonyAutoProfiling: [parse] Load xml
,08-16 12:14:56.497  7147  7147 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,08-16 12:14:56.498  7147  7147 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-16 12:14:56.498  7147  7147 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-16 12:14:56.498  7147  7147 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
,08-16 12:14:56.498  7147  7147 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-16 12:14:56.498  7147  7147 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-16 12:14:56.498  7147  7147 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-16 12:14:56.498  7147  7147 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-16 12:14:56.498  7147  7147 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-16 12:14:56.498  7147  7147 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-16 12:14:56.498  7147  7147 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-16 12:14:56.498  7147  7147 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-16 12:14:56.499  7147  7147 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-16 12:14:56.499  7147  7147 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-16 12:14:56.499  7147  7147 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-16 12:14:56.499  7147  7147 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-16 12:14:56.499  7147  7147 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-16 12:14:56.510  7147  7147 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-16 12:14:56.549  1036  1907 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7177 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 12:14:56.551  1036  1907 I ActivityManager: Killing 6664:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-16 12:14:56.607  1036  1944 W libprocessgroup: failed to open /acct/uid_10097/pid_6664/cgroup.procs: No such file or directory
,08-16 12:14:56.859  1036  1944 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7199 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-16 12:14:56.861  1036  1944 I ActivityManager: Killing 6693:com.lge.eula/1000 (adj 15): empty #17
08-16 12:14:56.957  1036  1771 W libprocessgroup: failed to open /acct/uid_1000/pid_6693/cgroup.procs: No such file or directory
,08-16 12:14:56.992  1036  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{38b44884 type 2 when 367022 com.google.android.gms} when 367022
,08-16 12:14:57.107  1036  1872 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7216 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 12:14:57.108  1036  1872 I ActivityManager: Killing 5599:com.lge.bnr/1000 (adj 15): empty #17
,08-16 12:14:57.237  1036  1998 W libprocessgroup: failed to open /acct/uid_1000/pid_5599/cgroup.procs: No such file or directory
,08-16 12:14:57.276  1036  1771 D WifiServiceImplEx: setWifiEnabled: true pid=6814, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-16 12:14:57.277  1036  1771 D WifiService: setWifiEnabled: true pid=6814, uid=10118
08-16 12:14:57.277  1036  1771 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 12:14:57.291  1036  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-16 12:14:57.291  1036  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-16 12:14:57.293  1036  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 12:14:57.293  1036  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 12:14:57.293  1036  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 12:14:57.293  1036  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 12:14:57.293  1036  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 12:14:57.293  1036  1523 E WifiHW  : unknown target_country: EU , set to default
08-16 12:14:57.293  7216  7216 I art     : Almond Protected OAT
08-16 12:14:57.294  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 12:14:57.294  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 12:14:57.294  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-16 12:14:57.293  1036  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-16 12:14:57.294  1036  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-16 12:14:57.294  1036  1523 I WifiUtil: gEnableBmps=1
,08-16 12:14:57.323  1036  1522 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:57.323  1036  1522 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:57.376  7216  7216 D WeatherApplication: removeAccount
,08-16 12:14:57.386  7216  7216 D WeatherApplication: Account.length = 0
08-16 12:14:57.386  7216  7216 E WeatherApplication: OPERATOR:OPEN
08-16 12:14:57.394  7216  7216 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:14:57
,08-16 12:14:57.401  7216  7216 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 12:14:57.401  7216  7216 D Weather.Utils: 2 : All the weather widget is gone.
08-16 12:14:57.403  7216  7216 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 12:14:57.406  7216  7216 D WeatherAncestor: connectivity changed - connection : true
08-16 12:14:57.408  7216  7216 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-16 12:14:57.418  7216  7216 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 12:14:57.418  7216  7216 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 12:14:57.419  7216  7216 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-16 12:14:57.441  7216  7216 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-16 12:14:57.442  7216  7216 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:14:57
08-16 12:14:57.525  1036  1560 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7235 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 12:14:57.526  1036  1560 I ActivityManager: Killing 2128:com.lge.music/u0a34 (adj 15): empty #17
08-16 12:14:57.549   315  2144 V AudioFlinger: 2128 died, releasing its sessions
08-16 12:14:57.549   315  2144 V AudioFlinger:  pid 1837 @ 0
08-16 12:14:57.549   315  2144 V AudioFlinger:  pid 3288 @ 1
08-16 12:14:57.549   315  2144 V AudioFlinger:  pid 3288 @ 2
,08-16 12:14:57.627  1036  1943 W libprocessgroup: failed to open /acct/uid_10034/pid_2128/cgroup.procs: No such file or directory
,08-16 12:14:57.798  1036  1925 I art     : Explicit concurrent mark sweep GC freed 68427(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.912ms total 163.109ms
,08-16 12:14:57.880   278   389 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 12:14:57.880   278   389 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 12:14:57.880   278   389 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 12:14:57.881  7235  7253 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 12:14:57.883   278   389 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-16 12:14:57.883   278   389 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 12:14:57.883   278   389 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 12:14:57.883  7235  7253 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 12:14:57.900   278   389 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-16 12:14:57.900   278   389 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 12:14:57.900   278   389 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 12:14:57.900  7235  7255 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 12:14:57.904   278   389 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 12:14:57.905   278   389 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 12:14:57.905   278   389 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 12:14:57.906  7235  7255 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 12:14:58.081  1036  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 12:14:58.081  1036  1119 D Tethering: InitialState.processMessage what=4
08-16 12:14:58.082  1036  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 12:14:58.086   311   894 D SoftapController: Softap fwReload - Ok
08-16 12:14:58.088  1036  1523 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (787ms)
08-16 12:14:58.089   311   894 D CommandListener: Setting iface cfg
08-16 12:14:58.090   311   894 D CommandListener: Trying to bring down wlan0
08-16 12:14:58.091   311   894 D CommandListener: Clearing all IP addresses on wlan0
08-16 12:14:58.093  1036  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-16 12:14:58.099  1036  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 12:14:58.099  1036  1523 E WifiStateMachine: useWiFiOffloading() : false
08-16 12:14:58.099  1036  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 12:14:58.091  7279  7279 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:14:58.091  7279  7279 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:14:58.110  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-16 12:14:58.115  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-16 12:14:58.115  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:14:58.118  1036  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 12:14:58.118  1036  1523 D WifiMonitor: connecting to supplicant
08-16 12:14:58.119  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:14:58.125  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:14:58.128  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:14:58.130  7279  7279 I wpa_supplicant: Successfully initialized wpa_supplicant
08-16 12:14:58.167  7279  7279 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 12:14:58.168  7279  7279 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-16 12:14:58.190  7235  7235 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 12:14:58.204  7235  7235 I LibraryLoader: Loading: webviewchromium
,08-16 12:14:58.212  7235  7235 I LibraryLoader: Time to load native libraries: 9 ms (timestamps 8247-8256)
08-16 12:14:58.212  7235  7235 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 12:14:58.222  7235  7235 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3ace216}
,08-16 12:14:58.224  7235  7235 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 12:14:58.224  7235  7235 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 12:14:58.237  7235  7235 I BrowserStartupController: Initializing chromium process, renderers=0
08-16 12:14:58.238  7235  7235 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 12:14:58.251   315  1370 V AudioPolicyService: registerClient() client 0xb10051e0, uid 10093
08-16 12:14:58.252  7235  7291 W AudioManagerAndroid: Requires BLUETOOTH permission
08-16 12:14:58.256  7235  7235 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-16 12:14:58.257  7235  7235 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-16 12:14:58.258  7235  7235 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-16 12:14:58.263  7279  7279 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 12:14:58.270  7235  7235 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 12:14:58.270  7235  7235 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 12:14:58.270  7235  7235 I Adreno-EGL: Build Date: 12/12/14 금
08-16 12:14:58.270  7235  7235 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 12:14:58.270  7235  7235 I Adreno-EGL: Remote Branch: 
08-16 12:14:58.270  7235  7235 I Adreno-EGL: Local Patches: 
08-16 12:14:58.270  7235  7235 I Adreno-EGL: Reconstruct Branch: 
,08-16 12:14:58.319  7279  7279 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-16 12:14:58.329  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-16 12:14:58.329  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-16 12:14:58.329  7279  7279 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-16 12:14:58.330  7279  7279 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-16 12:14:58.330  1036  7304 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-16 12:14:58.330  1036  7304 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 12:14:58.330  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 12:14:58.330  1036  7304 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-16 12:14:58.330  1036  7304 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 12:14:58.330  1036  7304 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 12:14:58.330  1036  7304 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-16 12:14:58.331  7235  7235 I NSApplication: Starting up...
08-16 12:14:58.332  1036  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 12:14:58.333  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 12:14:58.333  1036  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 12:14:58.334  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:14:58.334  1036  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:14:58.335  1036  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 12:14:58.335  1036  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 12:14:58.336  1036  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 12:14:58.336  1036  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 12:14:58.336  1036  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-16 12:14:58.337  1036  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 12:14:58.337  1036  1523 E WifiStateMachine: useWiFiOffloading() : false
08-16 12:14:58.337  1036  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 12:14:58.337  1036  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
,08-16 12:14:58.340  1036  1523 D WifiNative-wlan0: SET update_config 1: returned true
08-16 12:14:58.340  1036  1523 D WifiConfigStore: Loading config and enabling all networks 
08-16 12:14:58.340  1036  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 12:14:58.340  1036  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 12:14:58.343  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:58.343  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:58.344  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:58.344  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:58.344  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 12:14:58.346  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:14:58.348  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 12:14:58.348  1926  1926 D WfdService: Waiting for WifiP2p enabling
08-16 12:14:58.348  1036  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-16 12:14:58.348  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:14:58.348  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:14:58.348  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:14:58.348  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:14:58.348  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:14:58.348  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:14:58.348  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:14:58.348  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:14:58.348  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:14:58.348  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:14:58.348  6814  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:14:58.349  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:14:58.349  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:14:58.349  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:14:58.349  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:14:58.349  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:14:58.349  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:14:58.349  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:14:58.349  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/,connecting to active network: false
08-16 12:14:58.349  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:14:58.349  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:14:58.350  6814  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 12:14:58.351  1036  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-16 12:14:58.351  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:14:58.351  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:14:58.351  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:14:58.351  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:14:58.351  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:14:58.351  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:14:58.351  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:14:58.351  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:14:58.351  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:14:58.351  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:14:58.351  6814  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:14:58.362  1036  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 12:14:58.362  1036  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 12:14:58.394  1036  1771 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7305 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-16 12:14:58.395  1036  1771 I ActivityManager: Killing 6085:com.android.vending/u0a44 (adj 15): empty #17
08-16 12:14:58.488  1036  1523 D WifiStateMachine: enableVerboseLogging : level 2
08-16 12:14:58.488  1036  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-16 12:14:58.490  1036  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 12:14:58.490  1036  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 12:14:58.491  1036  1058 W libprocessgroup: failed to open /acct/uid_10044/pid_6085/cgroup.procs: No such file or directory
,08-16 12:14:58.491  1036  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
,08-16 12:14:58.492  1036  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-16 12:14:58.497  1036  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 12:14:58.497  1036  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 12:14:58.499  1036  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 12:14:58.499  1036  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-16 12:14:58.501  1036  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-16 12:14:58.501  1036  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-16 12:14:58.502  1036  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 12:14:58.502  1036  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-16 12:14:58.503  1036  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,08-16 12:14:58.516  1036  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 12:14:58.516  1036  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-16 12:14:58.518  1036  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 12:14:58.518  1036  1523 D WifiNative-HAL: Setting external_sim to 1
08-16 12:14:58.518  1036  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 12:14:58.518  1036  1523 D WifiNative-wlan0: SET external_sim 1: returned true
,08-16 12:14:58.518  1036  1523 I WifiNative-HAL: startHal
08-16 12:14:58.518  1036  1523 D wifi    : setting scan oui 0x95715ce0
08-16 12:14:58.519  1036  1523 D WifiStateMachine: Setting OUI to DA-A1-19
,08-16 12:14:58.519  1036  1523 I WifiNative-HAL: startHal
08-16 12:14:58.519  1036  1523 D wifi    : setting scan oui 0x95715ce0
08-16 12:14:58.519  1036  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 12:14:58.519  1036  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-16 12:14:58.520  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 12:14:58.520  7279  7279 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 12:14:58.520  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 12:14:58.521  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 12:14:58.521  7279  7279 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 12:14:58.521  1926  1926 D WfdsService: Supplicant Connection state is changed : true
08-16 12:14:58.521  1926  2300 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 12:14:58.522  1926  2300 D WfdsService: Set the WFDS Monitor: true
08-16 12:14:58.522  1926  2300 D WfdsMonitor: WfdsMonitorThread create
08-16 12:14:58.522  1926  2300 D WfdsMonitor: WFDS Monitor is created and started
08-16 12:14:58.522  1926  2300 D WfdsService: WiFi: Supplicant connection re-established
,08-16 12:14:58.523  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 12:14:58.523  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-16 12:14:58.523  7279  7279 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-16 12:14:58.523  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 12:14:58.523  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 12:14:58.524  7279  7279 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 12:14:58.524  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 12:14:58.524  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 12:14:58.524  7279  7279 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 12:14:58.525  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 12:14:58.525  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 12:14:58.525  7279  7279 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-16 12:14:58.525  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-16 12:14:58.525  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 12:14:58.525  1926  7322 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 12:14:58.526  7279  7279 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 12:14:58.526  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 12:14:58.527  1926  7322 E CtrlSupplicant: Succeed to open control connection
08-16 12:14:58.527  1926  7322 E CtrlSupplicant: Succeed to open monitor connection
08-16 12:14:58.528  1036  1523 E WifiNative: : [368,559,794 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-16 12:14:58.528  1036  1523 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 12:14:58.528  1036  1523 D WifiNative-wlan0: RECONNECT: returned true
08-16 12:14:58.528  1036  1523 D WifiNative-wlan0: doString: [STATUS]
08-16 12:14:58.529  1036  7304 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 12:14:58.529  1036  7304 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 12:14:58.528  1926  7322 D WfdsMonitor: Supplicant connection established
08-16 12:14:58.530  1926  2300 D WfdsService: Connected to the supplicant for wfds
08-16 12:14:58.530  1036  1523 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 12:14:58.530  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 12:14:58.530  1036  1523 D WifiNative-wlan0: SET ps 1: returned true
08-16 12:14:58.531  1036  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:58.532  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 12:14:58.532  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-16 12:14:58.532  1036  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-16 12:14:58.533  1036  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 12:14:58.533  1036  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 12:14:58.533  1036  1541 D WifiScanningService: DefaultState got{ when=-2ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:58.533  1036  1541 I WifiNative-HAL: startHal
08-16 12:14:58.534  1036  1541 D wifi    : getting scan capabilities on interface[1] = 0x95715ce0
08-16 12:14:58.534  1036  1541 D wifi    : failed to get capabilities : -3
08-16 12:14:58.534  1036  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-16 12:14:58.534  1036  1541 E WifiScanningService: could not get scan capabilities
08-16 12:14:58.534  1036  1542 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:58.534  1036  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-16 12:14:58.535  1036  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 12:14:58.536  1036  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 12:14:58.536  1036  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 12:14:58.536   311   894 D CommandListener: Setting iface cfg
08-16 12:14:58.536  7279  7279 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 12:14:58.536   311   894 D CommandListener: Trying to bring up p2p0
08-16 12:14:58.537  1036  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 12:14:58.537  1036  1522 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 12:14:58.537  1036  1522 D LGWifiP2pService: P2pEnablingState
08-16 12:14:58.537  1036  1522 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:58.537  1036  1522 D LGWifiP2pService: P2p socket connection successful
08-16 12:14:58.537  1036  1522 D LGWifiP2pService: P2pEnabledState
08-16 12:14:58.537  1036  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 12:14:58.538  1036  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-16 12:14:58.538  1036  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-16 12:14:58.538  7279  7279 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 12:14:58.538  1036  1523 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 12:14:58.539  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 12:14:58.539  1926  1926 D WfdsService: WifiP2pState is changed : true
08-16 12:14:58.539  1926  2300 D WfdsService: Receive the WFDS_ENABLE Method
08-16 12:14:58.539  1926  2300 D WfdsService: Set the WFDS Monitor: true
08-16 12:14:58.540  1926  2300 D WfdsService: Connected to the supplicant for wfds
08-16 12:14:58.540  1926  2300 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 12:14:58.540  7279  7279 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-16 12:14:58.540  1926  2300 D WfdsService: selectPreferredScanChannel [36]
08-16 12:14:58.540  1926  2300 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-16 12:14:58.540  1036  1523 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 12:14:58.541  1036  1523 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 12:14:58.541  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
,08-16 12:14:58.545  7279  7279 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-16 12:14:58.545  1036  1522 D LGWifiP2pService: sending p2p connection changed broadcast
08-16 12:14:58.546  7279  7279 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:14:58.546  1036  7304 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 12:14:58.546  1036  7304 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:14:58.546  1036  7304 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:14:58.546  1036  7304 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:14:58.547  7279  7279 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 12:14:58.547  7279  7279 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:14:58.547  1036  1523 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-16 12:14:58.548  1036  1523 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 12:14:58.548  1036  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 12:14:58.549  1036  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 12:14:58.549  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 12:14:58.549  7279  7279 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:14:58.549  1036  7304 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:14:58.549  1036  7304 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:14:58.549  1036  7304 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:14:58.549  1036  7304 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:14:58.549  1036  1522 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-16 12:14:58.549  1036  7304 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:14:58.549  1036  7304 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:14:58.549  1036  7304 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:14:58.549  1036  7304 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:14:58.550  1926  7322 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:14:58.550  1926  7322 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:14:58.550  1926  1926 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-16 12:14:58.550  1926  1926 D WfdsService: isConnected: false
08-16 12:14:58.550  7279  7279 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 12:14:58.550  7279  7279 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 12:14:58.551  1036  7304 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 12:14:58.551  1036  7304 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 12:14:58.551  1036  7304 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 12:14:58.551  1036  7304 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 12:14:58.552  1036  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 12:14:58.552  1036  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-16 12:14:58.553  1036  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-16 12:14:58.553  1036  1523 D WifiNative-wlan0: doBoolean: SCAN
08-16 12:14:58.554  1036  1523 D WifiNative-wlan0: SCAN: returned false
,08-16 12:14:58.554  1036  1522 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-16 12:14:58.554  7305  7305 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 12:14:58.555  1036  1522 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 12:14:58.555  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=368588  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 12:14:58.555  1036  1522 D WifiNative-p2p0: SET device_name G3: returned true
08-16 12:14:58.555  1036  1522 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 12:14:58.555  1036  1522 D LGWifiP2pService: before postfix = G3
08-16 12:14:58.555  1036  1522 D WifiServerServiceExt: postfix byte check : 2
08-16 12:14:58.555  1036  1522 D LGWifiP2pService: after postfix = G3
08-16 12:14:58.555  1036  1522 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
,08-16 12:14:58.557  1036  1522 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 12:14:58.557  1036  1522 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-16 12:14:58.557  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=368590  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 12:14:58.558  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:14:58.558  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:14:58.558  1036  1523 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 12:14:58.558  1036  1522 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 12:14:58.558  1036  1522 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 12:14:58.559  1036  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 12:14:58.559  1036  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 12:14:58.559  1036  1522 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 12:14:58.559  1036  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 12:14:58.560  1036  1522 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-16 12:14:58.560  1036  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 12:14:58.560  1036  1522 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 12:14:58.560  1036  1522 D WifiNative-HAL: p2pGetDeviceAddress
08-16 12:14:58.561  1036  1522 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-16 12:14:58.561  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:58.561  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:58.561  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 12:14:58.561  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:14:58.562  1036  1522 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-16 12:14:58.562  1036  1522 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 12:14:58.563  1036  1522 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 12:14:58.563  1036  1522 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-16 12:14:58.563  1926  1926 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 12:14:58.563  1926  1926 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 12:14:58.563  1926  1926 D WfdsService: Update P2p Interface State: 3
08-16 12:14:58.564  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:14:58.564  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 12:14:58.564  1036  1522 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 12:14:58.564  1036  1522 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 12:14:58.564  1036  1522 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 12:14:58.565  1036  1522 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-16 12:14:58.576  1036  1522 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 12:14:58.576  1036  1522 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-16 12:14:58.576  1036  1522 D LGWifiP2pService: InactiveState
08-16 12:14:58.576  1036  1522 D LGWifiP2pService: InactiveState{ when=-29ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:58.576  1036,  1522 D LGWifiP2pService: P2pEnabledState{ when=-29ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:58.577  1036  1522 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-16 12:14:58.577  7279  7279 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-16 12:14:58.578  7279  7279 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:14:58.579  7279  7279 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 12:14:58.579  7279  7279 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:14:58.579  1036  1522 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 12:14:58.579  1036  1522 D LGWifiP2pService: InactiveState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:58.579  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:58.579  1036  1522 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:58.579  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:58.579  1036  1522 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:58.580  7279  7279 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:14:58.580  1036  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:58.580  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:58.580  1036  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 12:14:58.580  1926  2300 W WfdsService: DefaultState - msg [9441285] is not handled
08-16 12:14:58.580  1036  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:58.580  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:58.581  1036  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:58.581  1036  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:58.581  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:58.581  1036  1522 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:58.581  1036  1036 E WifiServerServiceExt: No p2p device connected
08-16 12:14:58.581  1926  7322 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 12:14:58.581  1926  7322 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:14:58.581  1926  7322 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-16 12:14:58.581  1036  7304 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 12:14:58.581  1036  7304 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:14:58.582  1036  7304 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:14:58.582  1036  7304 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:14:58.582  1036  7304 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:14:58.582  1036  7304 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:14:58.582  1036  7304 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:14:58.582  1036  7304 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:14:58.582  1036  7304 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:14:58.582  1036  7304 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:14:58.582  1036  7304 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:14:58.582  1036  7304 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:14:58.852  6441  6441 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 12:14:58.854  6441  6969 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-16 12:14:58.883  2168  2168 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:14:58.897  7089  7089 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-16 12:14:58.897  7089  7089 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 12:14:58.897  7089  7089 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 12:14:58.897  7089  7089 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 12:14:58.900  7089  7089 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 12:14:58.906  7089  7089 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@c671445
08-16 12:14:58.906  7089  7089 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 12:14:58.906  7089  7089 D AppUp4:CustFacade: isPhone : true
08-16 12:14:58.907  7089  7089 D AppUp4:CustModeStarterReceiver: begin check event
08-16 12:14:58.907  7089  7089 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 12:14:58.911  4777  4777 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 12:14:58.911  4777  4777 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 12:14:58.912  4777  4777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:14:58.915  4777  4777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 12:14:58.921  4777  7335 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 12:14:58.922  7117  7117 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 12:14:58.927  4777  7336 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 12:14:58.927  4777  7336 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 12:14:58.946  7117  7337 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 12:14:58.952  3288  3288 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 12:14:58.952  3288  3288 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 12:14:58.952  3288  3288 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 12:14:58.957  7147  7147 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 12:14:58.957  7147  7147 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 12:14:58.957  7017  7339 W FormManager: Network not available. Please check & try again.
08-16 12:14:58.979  7216  7216 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:14:58
08-16 12:14:58.979  7017  7340 V FormManager: Network unavailable.
,08-16 12:14:58.984  7017  7340 V FormManager: Network unavailable.
08-16 12:14:58.984  7216  7216 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 12:14:58.984  7216  7216 D Weather.Utils: 2 : All the weather widget is gone.
08-16 12:14:58.985  7216  7216 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 12:14:58.985  7216  7216 D WeatherAncestor: connectivity changed - connection : true
08-16 12:14:58.985  7216  7216 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@9fee8cb
08-16 12:14:58.986  7216  7216 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 12:14:58.986  7216  7216 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 12:14:58.986  7216  7216 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 12:14:58.986  7216  7216 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 12:14:58.986  7216  7216 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:14:58
08-16 12:14:59.014   311  7350 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-16 12:14:59.015  1036  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 12:14:59.016  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 12:14:59.016  6942  6942 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 12:14:59.016  6942  6942 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 12:14:59.016  6942  6942 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 12:14:59.017  1036  7304 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-16 12:14:59.017  1036  7304 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 12:14:59.017  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 12:14:59.017  1036  7304 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-16 12:14:59.017  1036  7304 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-16 12:14:59.017  7279  7279 E wpa_supplicant: USIM:  scard_init function
08-16 12:14:59.017  1036  7304 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 12:14:59.017  7279  7279 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-16 12:14:59.018  1036  1523 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-16 12:14:59.018  1036  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-16 12:14:59.019  1036  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-16 12:14:59.019  1036  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-16 12:14:59.019  6942  6942 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 12:14:59.019  1036  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-16 12:14:59.019  1036  7304 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-16 12:14:59.019  1036  7304 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-16 12:14:59.020  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 12:14:59.020  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 12:14:59.020  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 12:14:59.020  6942  6942 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 12:14:59.021  6942  6942 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 12:14:59.029  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=369061  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-16 12:14:59.030  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=369063  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 12:14:59.036  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:14:59.036  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:14:59.037  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:59.037  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:59.037  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 12:14:59.038  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 12:14:59.044  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 12:14:59.044  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:59.044  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 12:14:59.044  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:14:59.044  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-16 12:14:59.049  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:14:59.056  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 12:14:59.058  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:14:59.059  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:14:59.059  7017  7353 W FormManager: Network not available. Please check & try again.
08-16 12:14:59.060  7017  7354 V FormManager: Network unavailable.
08-16 12:14:59.061  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:14:59.062  7017  7354 V FormManager: Network unavailable.
08-16 12:14:59.066  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:14:59.089  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 12:14:59.092  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 12:14:59.097  7017  7356 W FormManager: Network not available. Please check & try again.
08-16 12:14:59.098  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:14:59.104  7017  7357 V FormManager: Network unavailable.
,08-16 12:14:59.113  7017  7357 V FormManager: Network unavailable.
08-16 12:14:59.115  4777  4777 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 12:14:59.115  4777  4777 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-16 12:14:59.117  4777  4777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:14:59.123  4777  4777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:14:59.128  4777  7358 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 12:14:59.131  4777  7359 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 12:14:59.131  4777  7359 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 12:14:59.136  7279  7279 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-16 12:14:59.137  1036  7304 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 12:14:59.137  1036  7304 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-16 12:14:59.138  1036  7304 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 12:14:59.138  1036  7304 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 12:14:59.138  1036  7304 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 12:14:59.138  1036  7304 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 12:14:59.140  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=369172  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-16 12:14:59.140  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=369173  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 12:14:59.141  1036  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=369174
08-16 12:14:59.141  1036  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=369174
08-16 12:14:59.141  1036  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=369174
08-16 12:14:59.142  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=369175
08-16 12:14:59.142  1036  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=369175
08-16 12:14:59.143  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=369176  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 12:14:59.145  1036  7304 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 12:14:59.145  1036  7304 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 12:14:59.146  7279  7279 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 12:14:59.146  7279  7279 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 12:14:59.148  1036  7304 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-16 12:14:59.148  1036  7304 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 12:14:59.148  1036  7304 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 12:14:59.148  1036  7304 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 12:14:59.149  1036  7304 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 12:14:59.149  1036  7304 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 12:14:59.149  1036  7304 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 12:14:59.149  1036  7304 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 12:14:59.180  1036  1925 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7361 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-16 12:14:59.183  1036  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 12:14:59.185  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=369217  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 12:14:59.188  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:14:59.188  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:14:59.189  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:59.189  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:59.189  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 12:14:59.190  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:14:59.193  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:59.193  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:59.193  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-16 12:14:59.195  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=369227  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-16 12:14:59.196  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=369229  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 12:14:59.197  1036  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=369229
08-16 12:14:59.197  1036  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=369230
08-16 12:14:59.198  1036  1523 D WifiNative-wlan0: doString: [STATUS]
08-16 12:14:59.198  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:14:59.198  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-16 12:14:59.199  1036  7304 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 12:14:59.199  1036  7304 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 12:14:59.199  1036  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 12:14:59.201  1036  1523 I WifiServiceExtension: setVHTCapabilityType  : false
08-16 12:14:59.214  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:14:59.214  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 12:14:59.215  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:14:59.218  1036  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-16 12:14:59.218  1036  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-16 12:14:59.228  1036  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-16 12:14:59.228  1036  1530 D ConnectivityService: Got NetworkAgent Messenger
,08-16 12:14:59.228  1036  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 12:14:59.228  1036  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 12:14:59.228  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 12:14:59.228  1036  1530 D ConnectivityService: NetworkAgent connected
08-16 12:14:59.228  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:59.229  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:59.229  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 12:14:59.229  1036  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 12:14:59.229  1036  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 12:14:59.232  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:59.232  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:59.232  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 12:14:59.236  1036  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 12:14:59.236  1036  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 12:14:59.236  1036  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 12:14:59.236  1036  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 12:14:59.236  1036  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 12:14:59.237  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:14:59.237  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:14:59.239  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:14:59.242  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:14:59.242  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:14:59.242  1036  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 12:14:59.243  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:14:59.243   311   894 D CommandListener: Setting iface cfg
,08-16 12:14:59.247  1036  1523 E WifiStateMachine: Start Dhcp Watchdog 2
08-16 12:14:59.247  1036  7379 D DhcpStateMachine: StoppedState
08-16 12:14:59.247  1036  7379 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:59.247  1036  7379 D DhcpStateMachine: WaitBeforeStartState
08-16 12:14:59.248  1036  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=369280  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 12:14:59.248  1036  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=369281  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 12:14:59.249  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=369281  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 12:14:59.250  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-16 12:14:59.250  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-16 12:14:59.250  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:14:59.251  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:14:59.251  1036  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:14:59.252  1036  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:14:59.253  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:14:59.253  1036  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:14:59.254  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:14:59.254  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 12:14:59.254  1036  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=369287  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 12:14:59.255  1036  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=369287  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 12:14:59.255  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=369288  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-16 12:14:59.257  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:323262] from screen [on:0 period:-1831283271] gl rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 12:14:59.259  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1831283270] gl rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 12:14:59.259  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 12:14:59.262  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:14:59.263  1036  1530 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-16 12:14:59.263  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:14:59.264  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:14:59.264  1036  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:14:59.265  1036  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:14:59.265  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:14:59.265  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:14:59.266  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 12:14:59.266  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=110,0,0
08-16 12:14:59.266  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=110,0,0
08-16 12:14:59.267  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 12:14:59.267  7279  7279 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-16 12:14:59.267  1036  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 12:14:59.267  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 12:14:59.268  1036  1523 D WifiNative-wlan0: SET ps 0: returned true
08-16 12:14:59.268  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-16 12:14:59.268  7279  7279 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 12:14:59.268  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 12:14:59.268  1036  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@7e30f6b target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:59.269  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@7e30f6b target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:59.269  1036  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 12:14:59.269  1036  7379 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:59.269  1036  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 12:14:59.269  1036  7379 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 12:14:59.269  1036  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 12:14:59.270   311   894 D CommandListener: Setting iface cfg
08-16 12:14:59.270   311   894 D CommandListener: Trying to bring up wlan0
,08-16 12:14:59.271  1036  1523 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-16 12:14:59.272  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:14:59.273  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 12:14:59.273  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:14:59.273  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 12:14:59.274  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:14:59.274  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:14:59.275  1036  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:14:59.275  1036  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:14:59.276  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:14:59.276  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:14:59.276  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 12:14:59.277  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 12:14:59.277  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 12:14:59.277  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 12:14:59.277  7279  7279 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 12:14:59.278  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 12:14:59.278  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-16 12:14:59.278  7279  7279 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-16 12:14:59.278  1036  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-16 12:14:59.278  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 12:14:59.279  1036  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:59.279  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:59.294  1036  1523 D WifiNative-wlan0: SET ps 1: returned true
08-16 12:14:59.295  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 12:14:59.296  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 12:14:59.296  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 12:14:59.296  1036  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 12:14:59.296  1036  1530 D ConnectivityService: ignoring duplicate network state non-change
,08-16 12:14:59.301  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:14:59.301  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:14:59.301  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:59.301  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:59.301  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 12:14:59.302  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 12:14:59.303  1036  1530 D ConnectivityService: Adding iface wlan0 to network 101
08-16 12:14:59.304  1036  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 12:14:59.305  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:14:59.313  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:59.313  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:59.313  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 12:14:59.314  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-16 12:14:59.320  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:59.320  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:59.321  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 12:14:59.321  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 12:14:59.323  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:59.323  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:14:59.323  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 12:14:59.325  1926  1926 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-16 12:14:59.329  7361  7361 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 12:14:59.329  7361  7361 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-16 12:14:59.331  1036  1530 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 12:14:59.331  1036  1530 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-16 12:14:59.333  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:14:59.333  1036  1530 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-16 12:14:59.333  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:14:59.334   311   894 E Netd    : netlink response contains error (File exists)
08-16 12:14:59.335  1036  1530 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-16 12:14:59.335  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:14:59.337  1036  1530 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 12:14:59.337  1036  1530 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-16 12:14:59.337  1036  1530 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-16 12:14:59.338  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:14:59.338  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
08-16 12:14:59.338  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:14:59.338  7361  7361 V [BNRBootReceiver]: Boot Receiver Return
08-16 12:14:59.340  1036  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 12:14:59.342  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:14:59.342  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
08-16 12:14:59.343  6441  6441 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:14:59.343  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:14:59.343  7361  7361 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-16 12:14:59.343  1036  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 12:14:59.343  1036  1530 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-16 12:14:59.343  1036  7378 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:59.343  1036  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 12:14:59.343  1036  7378 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 12:14:59.343  1036  7378 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:14:59.344  1036  7378 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 12:14:59.344  1036  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 12:14:59.344  1036  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,08-16 12:14:59.344  1036  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 12:14:59.344  1036  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:14:59.344  1036  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 12:14:59.344  1036  1530 D ConnectivityService: currentScore = 0, newScore = 20
08-16 12:14:59.344  1036  1530 D ConnectivityService:    accepting network in place of null
08-16 12:14:59.345  1036  1530 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:14:59.346   311  7384 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-16 12:14:59.348  1036  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:14:59.348  1036  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 12:14:59.348  1837  1837 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:14:59.348  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 12:14:59.350  1036  1530 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 12:14:59.350  1036  1530 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 12:14:59.350  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 12:14:59.353  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 12:14:59.354  1036  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 12:14:59.354  1036  1530 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 12:14:59.355  1036  1530 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-16 12:14:59.355  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
,08-16 12:14:59.355  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 12:14:59.355  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 12:14:59.355  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 12:14:59.356  1036  1530 D ConnectivityService: validation of new default Network = false
08-16 12:14:59.356  1036  1530 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 12:14:59.356  1036  1530 D DSQN    : enableDataServiceNotify 
08-16 12:14:59.356  1036  1530 D DSQN    : start dsqn bin
08-16 12:14:59.365  1036  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 12:14:59.365  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:14:59.365  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:14:59.365  1036  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:14:59.366  1587  2059 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-16 12:14:59.367  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:14:59.361  7385  7385 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:14:59.368  1036  1521 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-16 12:14:59.361  7385  7385 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:14:59.381  7385  7385 E DSQN    : DSQN ssw
08-16 12:14:59.383  5713  5713 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 12:14:59.384  5713  5713 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:14:59.387  5713  5713 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 12:14:59.390  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-16 12:14:59.400  6942  6942 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-16 12:14:59.401  1802  7389 I CheckinService: active receiver: enabled
08-16 12:14:59.401  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 12:14:59.402  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:14:59.403  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 12:14:59.414  1802  7389 I CheckinService: Preparing to send checkin request
08-16 12:14:59.414  1802  7389 I EventLogService: Accumulating logs since 1471342172659
,08-16 12:14:59.414  6441  6441 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:14:59.418   311  7384 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-16 12:14:59.421  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 12:14:59.426  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 12:14:59.432  5713  5713 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:14:59.432  5713  5713 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:14:59.433  5713  5713 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 12:14:59.435  6441  6441 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:14:59.440  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:14:59.446  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:14:59.452   311  7384 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-16 12:14:59.452  5713  5713 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:14:59.453  5713  5713 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:14:59.453  5713  5713 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 12:14:59.457  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 12:14:59.457  6942  6942 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 12:14:59.457  6942  6942 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 12:14:59.457  6942  6942 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 12:14:59.458  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 12:14:59.458  6942  6942 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 12:14:59.458  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 12:14:59.458  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 12:14:59.458  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 12:14:59.458  6942  6942 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 12:14:59.459  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 12:14:59.459  6942  6942 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 12:14:59.462  6441  6441 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:14:59.466  1802  7389 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-16 12:14:59.469  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 12:14:59.470  1036  7379 D DhcpStateMachine: DHCPV4 request on wlan0
08-16 12:14:59.471  1036  7379 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-16 12:14:59.471  1036  7379 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-16 12:14:59.461  7391  7391 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:14:59.461  7391  7391 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:14:59.475  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:14:59.480   311   893 D LGDataListener: argv[0]=dsqncommand
08-16 12:14:59.480   311   893 D LGDataListener: argv[1]=wlan0
08-16 12:14:59.480   311   893 D LGDataListener: argv[2]=1
08-16 12:14:59.480   311   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-16 12:14:59.481  1036  1117 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 12:14:59.481  1036  1117 D DSQN    : start to monitor internet connection
08-16 12:14:59.482  7391  7391 I dhcpcd  : version 5.5.6 starting
,08-16 12:14:59.483  5713  5713 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:14:59.484  7391  7391 E dhcpcd  : get_duid: m
08-16 12:14:59.484  7391  7391 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 12:14:59.484  7391  7391 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-16 12:14:59.483  5713  5713 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:14:59.486  5713  5713 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 12:14:59.491  6441  6441 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 12:14:59.497  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:14:59.501  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:14:59.505  5713  5713 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:14:59.506  5713  5713 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 12:14:59.506  5713  5713 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 12:14:59.509  1036  7378 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 10:14:59 GMT], X-Android-Received-Millis=[1471342499509], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471342499480]}
08-16 12:14:59.509  1036  7378 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 12:14:59.509  1036  7378 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 12:14:59.510  1036  1530 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-16 12:14:59.510  1036  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 12:14:59.510  1036  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 12:14:59.510  1036  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:14:59.510  1036  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 12:14:59.510  1036  1530 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-16 12:14:59.510  6441  6441 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:14:59.510  1036  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 12:14:59.510  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:14:59.510  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:14:59.511  1036  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:14:59.511  1036  1530 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:14:59.511  1587  2059 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 12:14:59.511  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 12:14:59.512  1837  1837 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:14:59.512  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 12:14:59.512  1036  1523 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:14:59.513  1036  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 12:14:59.520  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:14:59.528  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:14:59.534  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 12:14:59.535  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:14:59.535  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:14:59.536  5713  5713 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:14:59.536  5713  5713 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:14:59.536  5713  5713 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 12:14:59.538  6441  6441 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:14:59.545  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 12:14:59.549  7391  7391 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-16 12:14:59.549  7391  7391 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 12:14:59.549  7391  7391 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 12:14:59.549  7391  7391 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-16 12:14:59.549  7391  7391 D dhcpcd  : wlan0: sending REQUEST (xid 0xf2a04a7), next in 4.59 seconds
08-16 12:14:59.551  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:14:59.556  5713  5713 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:14:59.557  5713  5713 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:14:59.557  5713  5713 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 12:14:59.562  6441  6441 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 12:14:59.574  7391  7391 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-16 12:14:59.585  7391  7391 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-16 12:14:59.585  7391  7391 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
,08-16 12:14:59.585  7391  7391 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-16 12:14:59.586  7391  7391 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-16 12:14:59.586  7391  7391 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 12:14:59.586  7391  7391 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 12:14:59.586  7391  7391 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 12:14:59.586  7391  7391 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-16 12:14:59.629  1036  2018 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7402 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-16 12:14:59.633  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 12:14:59.640  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:14:59.657  5713  5713 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:14:59.657  5713  5713 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 12:14:59.662  5713  5713 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 12:14:59.667  6441  6441 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 12:14:59.676  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:14:59.684  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:14:59.702  5713  5713 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 12:14:59.702  5713  5713 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:14:59.703  5713  5713 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 12:14:59.709  6441  6441 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:14:59.716  7402  7402 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-16 12:14:59.717  7402  7402 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-16 12:14:59.717  6970  6970 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 12:14:59.726  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 12:14:59.731  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 12:14:59.736  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:14:59.746  7402  7402 I MultiDex: VM with version 2.1.0 has multidex support
08-16 12:14:59.746  7402  7402 I MultiDex: install
08-16 12:14:59.746  7402  7402 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-16 12:14:59.749  5713  5713 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:14:59.749  5713  5713 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:14:59.752  5713  5713 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 12:14:59.754  7402  7402 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-16 12:14:59.755  5713  5713 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 12:14:59.755  5713  5713 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 12:14:59.767  6441  6441 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 12:14:59.781  6970  6970 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 12:14:59.781  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:14:59.787  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:14:59.802  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:14:59.809  5713  5713 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:14:59.809  5713  5713 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:14:59.810  5713  5713 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 12:14:59.811  5713  5713 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-16 12:14:59.812  5713  5713 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 12:14:59.814  1036  1944 I ActivityManager: Killing 6927:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-16 12:14:59.873  1036  7379 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-16 12:14:59.875  1036  7379 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-16 12:14:59.875  1036  7379 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 12:14:59.876  1036  7379 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-16 12:14:59.876  1036  7379 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-16 12:14:59.876  1036  7379 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 12:14:59.876  1036  7379 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-16 12:14:59.876  1036  7379 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-16 12:14:59.876  1036  1962 W libprocessgroup: failed to open /acct/uid_10037/pid_6927/cgroup.procs: No such file or directory
08-16 12:14:59.876  1036  7379 D DhcpStateMachine: RunningState
08-16 12:14:59.878  2168  2168 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-16 12:14:59.892  2168  2168 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-16 12:14:59.892  2168  2168 D c       : Getting all permits...
,08-16 12:14:59.892  2168  2168 D a       : Opening database...
,08-16 12:14:59.894  2168  2168 D a       : Opening database auth.proximity.permit_store...
08-16 12:14:59.895  2168  2168 D a       : Closing database...
08-16 12:15:00.044  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-16 12:15:00.044  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
08-16 12:15:00.044  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-16 12:15:00.045  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
08-16 12:15:00.049  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
08-16 12:15:00.049  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
,08-16 12:15:00.051  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
,08-16 12:15:00.052  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
,08-16 12:15:00.097  7402  7419 D LgDataFeature: LgDataFeature() Constructor: none
08-16 12:15:00.097  7402  7419 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 12:15:00.368  1036  1530 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-16 12:15:00.419  7447  7447 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-16 12:15:00.486  7447  7447 I dex2oat : dex2oat took 66.351ms (threads: 4)
,08-16 12:15:00.500  7402  7419 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 12:15:00.500  7402  7419 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 12:15:00.500  7402  7419 I Adreno-EGL: Build Date: 12/12/14 금
08-16 12:15:00.500  7402  7419 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 12:15:00.500  7402  7419 I Adreno-EGL: Remote Branch: 
08-16 12:15:00.500  7402  7419 I Adreno-EGL: Local Patches: 
08-16 12:15:00.500  7402  7419 I Adreno-EGL: Reconstruct Branch: 
,08-16 12:15:00.880  7402  7419 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 12:15:00.880  7402  7419 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 12:15:00.880  7402  7419 I Adreno-EGL: Build Date: 12/12/14 금
08-16 12:15:00.880  7402  7419 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 12:15:00.880  7402  7419 I Adreno-EGL: Remote Branch: 
08-16 12:15:00.880  7402  7419 I Adreno-EGL: Local Patches: 
08-16 12:15:00.880  7402  7419 I Adreno-EGL: Reconstruct Branch: 
,08-16 12:15:00.970  7402  7419 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 12:15:00.970  7402  7419 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 12:15:00.970  7402  7419 I Adreno-EGL: Build Date: 12/12/14 금
08-16 12:15:00.970  7402  7419 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 12:15:00.970  7402  7419 I Adreno-EGL: Remote Branch: 
08-16 12:15:00.970  7402  7419 I Adreno-EGL: Local Patches: 
08-16 12:15:00.970  7402  7419 I Adreno-EGL: Reconstruct Branch: 
,08-16 12:15:01.109   311  7464 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 12:15:01.109   311  7464 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-16 12:15:01.154   311  7464 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-16 12:15:01.209  1036  1523 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-16 12:15:01.209  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 12:15:01.210  1036  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 12:15:01.210  1036  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 12:15:01.210  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 12:15:01.211  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 12:15:01.212  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-16 12:15:01.212  1036  1530 D ConnectivityService: identical MTU - not setting
08-16 12:15:01.212  1036  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 12:15:01.212  1036  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 12:15:01.212  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:15:01.212  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:15:01.213  1036  1530 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:15:01.216  1587  2059 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-16 12:15:01.352  1802  7389 I CheckinTask: Sending checkin request (7920 bytes)
,08-16 12:15:01.612  1802  7389 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-16 12:15:01.632  1802  7389 I CheckinService: active receiver: disabled
,08-16 12:15:01.665  2168  2168 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-16 12:15:01.692  2168  2168 I GCM     : GCM config loaded
,08-16 12:15:01.717   311  7487 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-16 12:15:01.717   311  7487 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-16 12:15:01.726  7147  7147 V SetupWizard: Connected to Gservices successfully
08-16 12:15:01.734  1036  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=881370966, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,08-16 12:15:01.749   311  7487 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-16 12:15:01.789  1036  1110 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7496 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-16 12:15:01.824  2582  2582 D [Concierge]Service: onStartCommand(). Type : 9
,08-16 12:15:01.893  7496  7496 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,08-16 12:15:01.899  7496  7496 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1ffb408e
,08-16 12:15:01.900  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=881370966 [*alarm*], flags=0x0
,08-16 12:15:01.902  1036  1058 I ActivityManager: Killing 7000:com.lge.settings.easy/1000 (adj 15): empty #17
08-16 12:15:01.995  2168  7515 D GCM     : Connected
,08-16 12:15:02.029  1036  2018 W libprocessgroup: failed to open /acct/uid_1000/pid_7000/cgroup.procs: No such file or directory
,08-16 12:15:02.051  2168  7515 D GCM     : Message class com.google.e.a.a.q
08-16 12:15:02.266  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=55.0, 0.0, 0.0  rx=58.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1831280262] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 12:15:02.267  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=55.0, 0.0, 0.0  rx=58.5 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1831280262] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 12:15:02.267  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 12:15:02.276  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:02.292  1036  1872 D WifiServiceImplEx: setWifiEnabled: false pid=6814, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 12:15:02.293  1036  1872 D WifiService: setWifiEnabled: false pid=6814, uid=10118
08-16 12:15:02.293  1036  1872 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 12:15:02.316  1036  1524 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-16 12:15:02.355  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:15:02.363  1036  1119 D Tethering: MasterInitialState.processMessage what=3
08-16 12:15:02.371  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:15:02.371  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:15:02.371  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:15:02.371  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:15:02.371  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:15:02.371  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:15:02.371  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:15:02.371  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:15:02.371  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:15:02.374  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:15:02.374  6814  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:15:02.378  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:15:02.378  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:15:02.378  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:15:02.378  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:15:02.378  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:15:02.378  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:15:02.378  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:15:02.378  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:15:02.378  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:15:02.378  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:15:02.378  6814  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:15:02.386  1036  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 12:15:02.386  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 12:15:02.386  1036  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-16 12:15:02.387  1036  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 12:15:02.387  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 12:15:02.387  1036  1523 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 12:15:02.387  1036  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 12:15:02.387  1036  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-16 12:15:02.396  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:15:02.396  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:15:02.396  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:15:02.396  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:15:02.396  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:15:02.396  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:15:02.396  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:15:02.396  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:15:02.396  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:15:02.396  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:15:02.396  6814  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:15:02.397  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 12:15:02.397  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 12:15:02.397  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-16 12:15:02.399  1036  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 12:15:02.399  1036  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 12:15:02.401  1036  1108 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:15:02.407  1036  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 12:15:02.407  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 12:15:02.407  7279  7279 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 12:15:02.408  1036  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:02.408  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:02.408  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 12:15:02.408  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 12:15:02.409  1036  1523 D WifiNative-wlan0: SET ps 1: returned true
08-16 12:15:02.409  1036  7379 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:02.414   311   894 D CommandListener: Clearing all IP addresses on wlan0
,08-16 12:15:02.468  6441  6441 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 12:15:02.524  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 12:15:02.524  1036  1530 D ConnectivityService: ignoring duplicate network state non-change
08-16 12:15:02.525  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-16 12:15:02.531  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-16 12:15:02.533  6441  6969 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 12:15:02.574  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:02.574  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:02.574  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-16 12:15:02.588  1926  1926 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-16 12:15:02.588  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:15:02.588  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:15:02.590  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:02.592  5802  5802 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 12:15:02.612  1036  1530 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 12:15:02.612  1036  1530 D DSQN    : disableDataServiceNotify
08-16 12:15:02.612  1036  1530 D DSQN    : stop dsqn bin
,08-16 12:15:02.622  1036  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:15:02.622  1036  1530 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-16 12:15:02.622  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:15:02.622  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:15:02.622  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:15:02.622  1036  1530 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:15:02.622  1036  1530 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-16 12:15:02.622  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:15:02.623  1036  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:15:02.623  1036  1530 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-16 12:15:02.623  1036  1530 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 12:15:02.623  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 12:15:02.623  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:15:02.624  1036  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 12:15:02.624  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 12:15:02.624  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:15:02.624  1036  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 12:15:02.624  1036  1530 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:15:02.624  1036  1530 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:15:02.624  1036  7378 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:02.624  1036  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:15:02.624  1036  7378 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 12:15:02.625  1036  7378 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 12:15:02.625  1036  1522 D LGWifiP2pService: InactiveState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:02.625  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:02.625  1036  1522 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1f9bde6b
08-16 12:15:02.626  1036  1522 D LGWifiP2pService: P2pDisablingState
08-16 12:15:02.626  1036  1522 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:02.626  1036  1522 D LGWifiP2pService: p2p socket connection lost
08-16 12:15:02.626  1036  1522 D LGWifiP2pService: P2pDisabledState
,08-16 12:15:02.626  1036  1530 D NetworkManagementService: Removing idletimer
08-16 12:15:02.626  1036  1530 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:02.627  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:15:02.628  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-16 12:15:02.628  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:15:02.628  1036  1523 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 12:15:02.629  1036  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
,08-16 12:15:02.629  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 12:15:02.629  1036  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:02.629  7279  7279 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 12:15:02.630  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 12:15:02.630  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 12:15:02.631  1036  1523 D WifiNative-wlan0: SET ps 1: returned true
08-16 12:15:02.631   311   894 D CommandListener: Clearing all IP addresses on wlan0
,08-16 12:15:02.631  1036  1522 D LGWifiP2pService: DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 12:15:02.633  1837  1837 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:15:02.633  1587  2059 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 12:15:02.634  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 12:15:02.638  1036  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 12:15:02.638  1036  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 12:15:02.639  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:02.639  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:02.639  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 12:15:02.639  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 12:15:02.639  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-16 12:15:02.639  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 12:15:02.641  1036  1523 D WifiNative-p2p0: doBoolean: TERMINATE
08-16 12:15:02.641  1036  1523 D WifiNative-p2p0: TERMINATE: returned true
08-16 12:15:02.641  1036  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 12:15:02.641  1036  1523 E WifiStateMachine: useWiFiOffloading() : false
08-16 12:15:02.641  1036  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 12:15:02.642  1036  1541 D WifiScanningService: DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 12:15:02.642  1036  1542 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:02.642  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 12:15:02.643  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 12:15:02.643  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 12:15:02.643  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 12:15:02.643  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 12:15:02.643  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 12:15:02.643  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 12:15:02.648  1036  7379 D DhcpStateMachine: StoppedState
08-16 12:15:02.648  1036  7379 D DhcpStateMachine: StoppedState{ when=-17ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:02.649  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 12:15:02.649  1926  1926 D WfdsService: WifiP2pState is changed : false
08-16 12:15:02.649  1926  2300 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 12:15:02.649  1926  2300 D WfdsService: Set the WFDS Monitor: false
08-16 12:15:02.650  1926  2300 D WfdsMonitor: WFDS Monitor is stopped
08-16 12:15:02.650  1926  2300 D WfdsService: STATE : WfdsDisabledState - enter
08-16 12:15:02.650  1926  7322 D CtrlSupplicant: Received on exit socket, terminate
08-16 12:15:02.650  1926  7322 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 12:15:02.650  1036  1108 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:15:02.650  1926  7322 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 12:15:02.650  1926  7322 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 12:15:02.651  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:15:02.651  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:15:02.651  1926  2301 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-16 12:15:02.651  1926  2300 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 12:15:02.651  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-16 12:15:02.652  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:02.652  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:02.652  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 12:15:02.653  1036  1523 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:15:02.653  1036  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 12:15:02.655  1926  1926 V W,fdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 12:15:02.658  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 12:15:02.658  1036  1523 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-16 12:15:02.659  1036  1523 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-16 12:15:02.659  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:15:02.659  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 12:15:02.660  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:02.661  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:15:02.661  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:15:02.661  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:15:02.661  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:15:02.661  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:15:02.661  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:15:02.661  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:15:02.661  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:15:02.661  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:15:02.661  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:15:02.661  6814  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:15:02.662  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:15:02.662  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:15:02.662  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:15:02.662  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:15:02.662  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:15:02.662  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:15:02.662  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:15:02.662  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:15:02.662  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:15:02.662  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:15:02.662  6814  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:15:02.664  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:15:02.664  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:15:02.664  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:15:02.664  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:15:02.664  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:15:02.664  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:15:02.664  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:15:02.664  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:15:02.664  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:15:02.664  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:15:02.664  6814  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:15:02.680  2168  2168 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:15:02.698  7089  7089 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 12:15:02.698  7089  7089 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 12:15:02.698  7089  7089 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 12:15:02.698  7089  7089 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 12:15:02.702  7089  7089 I AppUp4:CustModeStarterReceiver: onReceive
08-16 12:15:02.706  7279  7279 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 12:15:02.706  7279  7279 I wpa_supplicant: monitor socket send errors count : 1
08-16 12:15:02.706  7279  7279 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1926-4\x00 that cannot receive messages
08-16 12:15:02.707  1036  7304 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-16 12:15:02.707  1036  7304 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 12:15:02.709  7089  7089 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@c671445
08-16 12:15:02.709  7089  7089 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 12:15:02.709  7089  7089 D AppUp4:CustFacade: isPhone : true
08-16 12:15:02.710  7089  7089 D AppUp4:CustModeStarterReceiver: begin check event
08-16 12:15:02.710  7089  7089 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 12:15:02.714  4777  4777 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 12:15:02.715  4777  4777 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 12:15:02.718  4777  4777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:15:02.721  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 12:15:02.721  4777  4777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:15:02.722  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:02.723  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:02.728  4777  7549 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 12:15:02.731  7117  7117 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 12:15:02.734  4777  7550 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 12:15:02.735  4777  7550 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 12:15:02.745  7279  7279 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 12:15:02.746  7279  7279 W wpa_supplicant: USIM:  scard_deinit function
08-16 12:15:02.746  1036  1119 D Tethering: InitialState.processMessage what=4
08-16 12:15:02.747  1036  7304 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-16 12:15:02.747  1036  7304 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 12:15:02.747  1036  7304 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 12:15:02.747  1036  7304 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-16 12:15:02.747  1036  7304 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 12:15:02.747  1036  7304 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 12:15:02.748  1036  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=372781
08-16 12:15:02.749  1036  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=372782
08-16 12:15:02.750  1036  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=372782  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 12:15:02.750  1036  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=372783  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 12:15:02.755  1036  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 12:15:02.757  1036  1523 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:15:02.757  1036  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-16 12:15:02.767  7017  7552 W FormManager: Network not available. Please check & try again.
08-16 12:15:02.769  3288  3288 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 12:15:02.769  3288  3288 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 12:15:02.769  3288  3288 I LgeMiscReceiver: networkInfo.isConnected() = true
08-16 12:15:02.769  3288  3288 D PhoneState: setPdpRejectCasuse : false
08-16 12:15:02.776  7147  7147 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 12:15:02.776  7147  7147 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 12:15:02.778  7017  7553 V FormManager: Network unavailable.
,08-16 12:15:02.780  7117  7555 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:02.784  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 12:15:02.786  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:02.786  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:02.787  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 12:15:02.787  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:15:02.788  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:02.792  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:02.792  7017  7553 V FormManager: Network unavailable.
08-16 12:15:02.792  7216  7216 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:15:2
,08-16 12:15:02.793  7216  7216 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 12:15:02.794  7216  7216 D Weather.Utils: 2 : All the weather widget is gone.
08-16 12:15:02.794  7216  7216 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 12:15:02.794  7216  7216 D WeatherAncestor: connectivity changed - connection : true
08-16 12:15:02.794  7216  7216 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@9fee8cb
08-16 12:15:02.796  7216  7216 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 12:15:02.796  7216  7216 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 12:15:02.796  7216  7216 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 12:15:02.796  7216  7216 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 12:15:02.796  7216  7216 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:15:2
08-16 12:15:02.820  6441  6441 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 12:15:02.823  6970  6970 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 12:15:02.823  6970  6970 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-16 12:15:02.823  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:15:02.828  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 12:15:02.833  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 12:15:02.839  5713  5713 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:15:02.840  5713  5713 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:15:02.842  5713  5713 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 12:15:02.844  7279  7279 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-16 12:15:02.845  1036  7304 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 12:15:02.845  1036  7304 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 12:15:02.845  1036  7304 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-16 12:15:02.847  1036  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-16 12:15:02.847  6441  6441 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:15:02.851  6970  6970 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 12:15:02.851  6970  6970 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 12:15:02.851  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:15:02.854  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:15:02.861  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:15:02.868  5713  5713 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:15:02.868  5713  5713 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:15:02.869  5713  5713 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 12:15:02.873  6441  6441 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:15:02.876  6970  6970 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 12:15:02.876  6970  6970 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 12:15:02.876  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:15:02.880  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:15:02.887  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:15:02.892  5713  5713 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:15:02.892  5713  5713 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:15:02.894  5713  5713 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 12:15:02.902  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:15:02.904  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 12:15:02.911  7017  7557 W FormManager: Network not available. Please check & try again.
08-16 12:15:02.912  7235  7256 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-16 12:15:02.914  7017  7558 V FormManager: Network unavailable.
08-16 12:15:02.915  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:15:02.921  7017  7558 V FormManager: Network unavailable.
,08-16 12:15:02.934  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 12:15:02.935  6942  6942 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 12:15:02.935  6942  6942 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-16 12:15:02.935  6942  6942 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-16 12:15:02.935  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 12:15:02.936  6942  6942 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 12:15:02.936  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 12:15:02.936  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 12:15:02.936  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 12:15:02.936  6942  6942 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 12:15:02.937  6942  6942 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 12:15:02.949  1926  1926 D WfdsService: Supplicant Connection state is changed : false
,08-16 12:15:02.949  1926  2300 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-16 12:15:02.950  1926  2300 D WfdsService: Set the WFDS Monitor: false
08-16 12:15:02.950  1926  2300 D WfdsMonitor: WFDS Monitor is stopped
08-16 12:15:02.950  1036  1523 D WifiOffDelayIfNotUsed: stopMonitoring
08-16 12:15:02.951  1036  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 12:15:02.951  1036  1523 E WifiStateMachine: useWiFiOffloading() : false
08-16 12:15:02.951  1036  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 12:15:02.951  4777  4777 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 12:15:02.953  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 12:15:02.953  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:02.954  4777  4777 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 12:15:02.956  2466  2466 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:02.956  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-16 12:15:02.956  4777  4777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:15:02.956  1036  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 12:15:02.956  1036  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 12:15:02.959  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:15:02.959  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:15:02.960  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:15:02.961  4777  4777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:15:02.971  4777  7561 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 12:15:02.971  6970  6970 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-16 12:15:02.972  6970  6970 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 12:15:02.972  6970  6970 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:15:02.975  4777  7562 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 12:15:02.975  4777  7562 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 12:15:02.977  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 12:15:02.985  7017  7564 W FormManager: Network not available. Please check & try again.
,08-16 12:15:02.990  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:15:02.991  7017  7565 V FormManager: Network unavailable.
08-16 12:15:02.998  7017  7565 V FormManager: Network unavailable.
,08-16 12:15:03.858  1036  1943 I ActivityManager: Killing 7361:com.lge.bnr/1000 (adj 15): empty #17
,08-16 12:15:03.891  1036  1998 W libprocessgroup: failed to open /acct/uid_1000/pid_7361/cgroup.procs: No such file or directory
,08-16 12:15:05.279  1036  1523 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1831277249] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 12:15:05.281  1036  1523 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1831277247] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 12:15:05.626  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:15:05.643  1036  1119 D Tethering: MasterInitialState.processMessage what=3
08-16 12:15:05.660  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:15:05.665  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:15:05.666  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:15:05.669  1036  1108 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 12:15:05.670  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 12:15:05.677  6441  6441 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-16 12:15:05.684  6441  6969 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 12:15:05.698  1036  1119 D Tethering: MasterInitialState.processMessage what=3
,08-16 12:15:05.703  5802  5802 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-16 12:15:05.709  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:15:05.709  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:15:05.711  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:15:05.726  5802  5802 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 12:15:05.744  2168  2168 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:15:05.762  7089  7089 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 12:15:05.762  7089  7089 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 12:15:05.762  7089  7089 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 12:15:05.762  7089  7089 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 12:15:05.767  7089  7089 I AppUp4:CustModeStarterReceiver: onReceive
08-16 12:15:05.771  7089  7089 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@c671445
08-16 12:15:05.771  7089  7089 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 12:15:05.771  7089  7089 D AppUp4:CustFacade: isPhone : true
08-16 12:15:05.771  7089  7089 D AppUp4:CustModeStarterReceiver: begin check event
08-16 12:15:05.772  7089  7089 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 12:15:05.776  4777  4777 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:15:05.780  4777  4777 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 12:15:05.782  4777  4777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:15:05.784  4777  4777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:15:05.794  1036  1108 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:15:05.802  4777  7587 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 12:15:05.804  1036  1108 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:15:05.804  1036  1108 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:15:05.808  4777  7589 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 12:15:05.809  4777  7589 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 12:15:05.809  7117  7117 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 12:15:05.838  7117  7592 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 12:15:05.843  7017  7594 W FormManager: Network not available. Please check & try again.
08-16 12:15:05.854  3288  3288 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-16 12:15:05.854  3288  3288 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 12:15:05.854  3288  3288 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 12:15:05.860  7147  7147 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 12:15:05.861  7147  7147 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 12:15:05.866  7017  7595 V FormManager: Network unavailable.
,08-16 12:15:05.880  7216  7216 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:15:5
,08-16 12:15:05.881  7017  7595 V FormManager: Network unavailable.
08-16 12:15:05.885  7216  7216 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 12:15:05.885  7216  7216 D Weather.Utils: 2 : All the weather widget is gone.
,08-16 12:15:05.886  7216  7216 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 12:15:05.886  7216  7216 D WeatherAncestor: connectivity changed - connection : true
08-16 12:15:05.886  7216  7216 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@9fee8cb
08-16 12:15:05.887  7216  7216 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 12:15:05.887  7216  7216 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 12:15:05.887  7216  7216 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 12:15:05.887  7216  7216 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 12:15:05.887  7216  7216 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:15:5
08-16 12:15:05.912  6441  6441 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 12:15:05.913  6441  6969 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-16 12:15:05.924  2168  2168 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-16 12:15:05.935  7089  7089 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 12:15:05.935  7089  7089 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 12:15:05.935  7089  7089 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 12:15:05.935  7089  7089 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 12:15:05.937  7089  7089 I AppUp4:CustModeStarterReceiver: onReceive
08-16 12:15:05.942  7089  7089 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@c671445
08-16 12:15:05.942  7089  7089 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 12:15:05.942  7089  7089 D AppUp4:CustFacade: isPhone : true
08-16 12:15:05.943  7089  7089 D AppUp4:CustModeStarterReceiver: begin check event
08-16 12:15:05.943  7089  7089 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 12:15:05.948  4777  4777 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 12:15:05.949  4777  4777 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-16 12:15:05.953  4777  4777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:15:05.957  4777  4777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:15:05.966  7117  7117 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 12:15:05.970  4777  7599 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 12:15:05.975  4777  7600 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 12:15:05.975  4777  7600 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 12:15:05.992  7117  7601 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 12:15:06.008  7017  7603 W FormManager: Network not available. Please check & try again.
,08-16 12:15:06.021  3288  3288 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 12:15:06.021  3288  3288 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 12:15:06.022  3288  3288 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 12:15:06.024  7017  7604 V FormManager: Network unavailable.
,08-16 12:15:06.027  7147  7147 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-16 12:15:06.028  7147  7147 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 12:15:06.029  7017  7604 V FormManager: Network unavailable.
08-16 12:15:06.048  7216  7216 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:15:6
08-16 12:15:06.050  7216  7216 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 12:15:06.050  7216  7216 D Weather.Utils: 2 : All the weather widget is gone.
08-16 12:15:06.051  7216  7216 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 12:15:06.052  7216  7216 D WeatherAncestor: connectivity changed - connection : true
,08-16 12:15:06.052  7216  7216 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@9fee8cb
08-16 12:15:06.053  7216  7216 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 12:15:06.053  7216  7216 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 12:15:06.053  7216  7216 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 12:15:06.053  7216  7216 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 12:15:06.054  7216  7216 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:15:6
08-16 12:15:06.095  1036  1962 I ActivityManager: Killing 7496:com.lge.clock/u0a10 (adj 15): empty #17
,08-16 12:15:06.127  1036  1871 W libprocessgroup: failed to open /acct/uid_10010/pid_7496/cgroup.procs: No such file or directory
,08-16 12:15:07.394  1036  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 12:15:07.394  1036  1060 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-16 12:15:07.428  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 12:15:07.429  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 12:15:07.429  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-16 12:15:07.433  1036  1119 D BluetoothManagerService: Message: 1
08-16 12:15:07.433  1036  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-16 12:15:07.464  1036  1119 D BluetoothManagerService: Message: 20
08-16 12:15:07.464  1036  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a906b35:true
,08-16 12:15:07.469  7048  7048 D BluetoothAdapterState: make
08-16 12:15:07.474  7048  7048 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 12:15:07.475  7048  7048 I bluedroid-qcom: init
08-16 12:15:07.476  7048  7617 I BluetoothAdapterState: Entering OffState
08-16 12:15:07.476  7048  7048 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 12:15:07.477  7048  7048 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 12:15:07.477  7048  7048 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 12:15:07.477  7048  7048 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 12:15:07.477  7048  7048 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 12:15:07.479  7048  7048 I bluedroid-qcom: get_profile_interface socket
08-16 12:15:07.479  7048  7048 I bluedroid-qcom: get_profile_interface map_client
,08-16 12:15:07.484  7048  7621 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 12:15:07.481  7620  7620 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:15:07.490  7048  7621 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 12:15:07.481  7620  7620 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:15:07.497  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 12:15:07.497  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,08-16 12:15:07.505  7620  7620 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 12:15:07.505  7620  7620 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 12:15:07.505  7620  7620 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-16 12:15:07.506  7048  7621 D BluetoothAdapterProperties: Name is: G3
08-16 12:15:07.506  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-16 12:15:07.506  1036  1119 D BluetoothManagerService: Message: 40
08-16 12:15:07.506  1036  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 12:15:07.507  7048  7063 I bluedroid-qcom: config_hci_snoop_log
08-16 12:15:07.508  1036  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 12:15:07.509  1036  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 12:15:07.512  7620  7620 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-16 12:15:07.520  7620  7620 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 12:15:07.520  7620  7620 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-16 12:15:07.522  7048  7617 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-16 12:15:07.522  7048  7617 D BluetoothAdapterProperties: Setting state to 11
08-16 12:15:07.523  7048  7617 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 12:15:07.524  7048  7617 I LGBluetoothServiceJni: classInitNative: succeeds
08-16 12:15:07.525  1036  1119 D BluetoothManagerService: Message: 60
08-16 12:15:07.525  1036  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 12:15:07.525  1036  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-16 12:15:07.530  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 12:15:07.534  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 12:15:07.538  6942  6942 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-16 12:15:07.542  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:15:07.564  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:15:07.567  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:15:07.568  7048  7048 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 12:15:07.571  7048  7617 D BluetoothBondStateMachine: make
08-16 12:15:07.572  7048  7048 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:07.572  7048  7048 V BluetoothPbapReceiver: ***********state = 11
08-16 12:15:07.575  7048  7637 I BluetoothBondStateMachine: StableState(): Entering Off State
08-16 12:15:07.575  7048  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9fee8cb
08-16 12:15:07.576  7048  7617 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 12:15:07.576  7048  7617 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9fee8cb
08-16 12:15:07.576  7048  7617 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 12:15:07.576  2168  2168 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 12:15:07.577  7048  7617 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,08-16 12:15:07.581  7048  7617 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 12:15:07.630  1036  1980 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7640 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-16 12:15:07.630  1036  1522 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:07.630  1036  1522 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:07.639  7048  7617 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 12:15:07.640  7048  7048 D HeadsetService: Received start request. Starting profile...
08-16 12:15:07.640  7048  7048 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 12:15:07.641  7048  7048 D LGBluetoothHfpAdapter: Version 1.6
08-16 12:15:07.644  7048  7048 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 12:15:07.645  1036  1523 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-16 12:15:07.646  7048  7048 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 12:15:07.646  7048  7048 D HeadsetStateMachine: make
,08-16 12:15:07.647  1036  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-16 12:15:07.649  7048  7617 E BluetoothAdapterService: File transfer profiles supported!!
08-16 12:15:07.656  7048  7617 E BluetoothAdapterService: File transfer profiles supported!!
08-16 12:15:07.660  7048  7617 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 12:15:07.666  7048  7617 E BluetoothAdapterService: File transfer profiles supported!!
08-16 12:15:07.670  7048  7617 E BluetoothAdapterService: File transfer profiles supported!!
08-16 12:15:07.681  7048  7048 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 12:15:07.681  7048  7048 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 12:15:07.683  7048  7617 V LGMDMManager: Create singleton instance
08-16 12:15:07.685  7048  7617 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 12:15:07.685  7048  7048 D HeadsetStateMachine: max_hf_connections = 1
08-16 12:15:07.685  7048  7048 I bluedroid-qcom: get_profile_interface handsfree
08-16 12:15:07.687  7048  7048 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-16 12:15:07.687   315   315 V AudioPolicyService: registerClient() client 0xb1005320, uid 1002
08-16 12:15:07.688   315  2144 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-16 12:15:07.688   315  2144 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 12:15:07.688   315  2144 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 12:15:07.688  7048  7048 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 12:15:07.688   315  1370 V AudioFlinger: registerClient() client 0xb16de178, pid 7048
08-16 12:15:07.689   315  1364 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 12:15:07.689   315  1364 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 12:15:07.689  7048  7048 V ToneGenerator: Create Track: 0xb4928a80
08-16 12:15:07.689  7048  7048 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 12:15:07.689  7048  7048 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 12:15:07.689  1587  1604 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 12:15:07.689  1587  1604 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 12:15:07.689   315   315 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 12:15:07.689   315   315 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-16 12:15:07.689   315   315 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
,08-16 12:15:07.689  3288  3305 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 12:15:07.689   315   315 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 12:15:07.689  1036  2018 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 12:15:07.689  3288  3305 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 12:15:07.689  1036  2018 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 12:15:07.689  7048  7048 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 12:15:07.689  1837  2436 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 12:15:07.689  1837  2436 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 12:15:07.689  7048  7063 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 12:15:07.689  7048  7063 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 12:15:07.690   315  1363 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 12:15:07.690   315  1363 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 12:15:07.690  1587  2083 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 12:15:07.690  1587  2083 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 12:15:07.690   315  1369 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 12:15:07.690  1837  1853 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 12:15:07.690  1837  1853 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 12:15:07.690  3288  3304 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 12:15:07.690   315   315 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 12:15:07.690  3288  3304 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 12:15:07.690   315   315 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 12:15:07.690   315   315 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 12:15:07.690   315   315 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 12:15:07.690  7048  7048 V AudioSystem: getLatency() output 2, latency 50
08-16 12:15:07.690  1036  1060 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 12:15:07.690  1036  1060 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 12:15:07.690  7048  7048 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 12:15:07.690  7048  7048 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 12:15:07.690  7048  7063 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 12:15:07.690  7048  7063 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-16 12:15:07.690  7048  7048 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 12:15:07.691   315  2136 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 12:15:07.691   315  2136 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 12:15:07.691   315  2136 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 12:15:07.691   315  2136 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 12:15:07.691   315  2136 V AudioFlinger: createTrack() lSessionId: 22
08-16 12:15:07.691  7048  7048 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 12:15:07.692   315  1370 V AudioFlinger: acquiring 22 from 7048, for 7048
08-16 12:15:07.692   315  1370 V AudioFlinger:  added new entry for 22
08-16 12:15:07.692  7048  7048 V ToneGenerator: ToneGenerator INIT OK, time: 377737
08-16 12:15:07.692  7048  7048 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9fee8cb
08-16 12:15:07.693  7048  7651 D HeadsetStateMachine,: Enter Disconnected: -2, size: 0
08-16 12:15:07.693  7048  7651 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 12:15:07.693  7048  7651 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 12:15:07.693  7048  7651 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-16 12:15:07.693   315  2144 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7048
,08-16 12:15:07.699   315  2144 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 12:15:07.699   315  2144 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 12:15:07.699   315  2144 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 12:15:07.699   315  2144 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 12:15:07.699   315  2144 V voice   : voice_set_parameters: exit with code(0)
08-16 12:15:07.699   315  2144 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 12:15:07.699   315  2144 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 12:15:07.699   315  2144 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 12:15:07.699   315  2144 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 12:15:07.699   315  2144 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 12:15:07.699   315  2144 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 12:15:07.699  7048  7651 V ToneGenerator: ToneGenerator destructor
08-16 12:15:07.699  7048  7651 V ToneGenerator: stopTone
08-16 12:15:07.699  7048  7651 V ToneGenerator: Delete Track: 0xb4928a80
08-16 12:15:07.699  7048  7651 V AudioTrack: ~AudioTrack, releasing session id from 7048 on behalf of 7048
08-16 12:15:07.699   315  2136 V AudioFlinger: releasing 22 from 7048 for 7048
08-16 12:15:07.700   315  2136 V AudioFlinger:  decremented refcount to 0
08-16 12:15:07.700   315  2136 V AudioFlinger: purging stale effects
08-16 12:15:07.700   315  2136 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 12:15:07.700   315  2136 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 12:15:07.700   315  1270 V AudioPolicyService: AudioCommandThread() waking up
08-16 12:15:07.700   315  1270 V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 12:15:07.700   315  1270 V AudioPolicyManager: releaseOutput() 2
08-16 12:15:07.700   315  1270 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 12:15:07.700   315  2136 V AudioFlinger: PlaybackThread::Track destructor
08-16 12:15:07.700   315  2136 V AudioFlinger: removeClient_l() pid 7048, calling pid 315
08-16 12:15:07.700  1036  1871 W Process : Unable to open /proc/7660/status
,08-16 12:15:07.805  1036  1058 I art     : Explicit concurrent mark sweep GC freed 140150(6MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 1.573ms total 112.754ms
08-16 12:15:07.810  7048  7048 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9fee8cb
,08-16 12:15:07.815  7048  7048 D A2dpService: Received start request. Starting profile...
08-16 12:15:07.817  7048  7048 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 12:15:07.819  7048  7048 V Avrcp   : make
08-16 12:15:07.821  7048  7048 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-16 12:15:07.821  7048  7048 I bluedroid-qcom: get_profile_interface avrcp
08-16 12:15:07.841  7048  7048 V AudioManager: registerRemoteController: size of Media player list: 0
08-16 12:15:07.844  7048  7048 E AudioManager: No RCC entry present to update
08-16 12:15:07.844  7048  7048 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 12:15:07.851  7048  7048 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-16 12:15:07.853  7048  7048 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
,08-16 12:15:07.853  7048  7048 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-16 12:15:07.858  7048  7048 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-16 12:15:07.889  7640  7640 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-16 12:15:07.890  7640  7640 W LG Account v2.2: No ProfileInfo entries
08-16 12:15:07.891  7640  7640 I LG Account v2.2: isEnabled: false
08-16 12:15:07.891  7640  7640 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 12:15:07.891  7640  7640 I Feature : [Lifetracker]Country: EU
08-16 12:15:07.891  7640  7640 I Feature : [Lifetracker]Operator: OPEN
08-16 12:15:07.891  7640  7640 I Feature : [Lifetracker]Ranking support: false
08-16 12:15:07.892  7640  7640 I Feature : [Lifetracker]Comfort support: false
08-16 12:15:07.892  7640  7640 I Feature : [Lifetracker]Accessory: true
08-16 12:15:07.892  7640  7640 I Feature : [Lifetracker]Health device: true
08-16 12:15:07.892  7640  7640 I Feature : [Lifetracker]Extra Pedometer: false
08-16 12:15:07.892  7640  7640 I Feature : [Lifetracker]Blood glucose device: false
08-16 12:15:07.893  7640  7640 I Feature : [Lifetracker]Device Number: 3
08-16 12:15:07.910  6942  6942 D BluetoothPermissionRequest: onReceive
,08-16 12:15:07.918  6942  6942 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 12:15:07.932  1036  1962 V SIM_STK : Menu title from STK is T-Mobile
08-16 12:15:07.932  1036  1962 V SIM_STK : Menu title from STK is T-Mobile
,08-16 12:15:08.041  1036  1871 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 12:15:08.049  7048  7048 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-16 12:15:08.054  7048  7048 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 12:15:08.054  7048  7048 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 12:15:08.055  7048  7048 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
,08-16 12:15:08.055  7048  7048 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 12:15:08.055  7048  7048 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,08-16 12:15:08.055  7048  7048 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 12:15:08.055  7048  7048 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 12:15:08.055  7048  7048 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 12:15:08.055  7048  7048 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 12:15:08.056  7048  7048 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 12:15:08.056  7048  7048 I BluetoothA2dpServiceJni: classInitNative
08-16 12:15:08.056  7048  7048 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 12:15:08.056  7048  7048 D A2dpStateMachine: make
,08-16 12:15:08.062  7048  7048 I bluedroid-qcom: get_profile_interface a2dp
,08-16 12:15:08.062  7048  7666 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 12:15:08.065  7048  7048 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-16 12:15:08.066  7048  7048 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-16 12:15:08.067  7048  7048 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9fee8cb
08-16 12:15:08.067  7048  7665 D A2dpStateMachine: Enter Disconnected: -2
08-16 12:15:08.067  7048  7048 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 12:15:08.069  7048  7048 D HidService: Received start request. Starting profile...
08-16 12:15:08.069  7048  7048 I bluedroid-qcom: get_profile_interface hidhost
08-16 12:15:08.069  7048  7048 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9fee8cb
08-16 12:15:08.070  7048  7048 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 12:15:08.075  7048  7048 D HealthService: Received start request. Starting profile...
,08-16 12:15:08.076  7048  7048 I bluedroid-qcom: get_profile_interface health
08-16 12:15:08.076  7048  7048 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-16 12:15:08.076  7048  7048 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9fee8cb
08-16 12:15:08.077  7048  7048 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 12:15:08.078  7048  7048 D PanService: Received start request. Starting profile...
08-16 12:15:08.078  7048  7048 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 12:15:08.078  7048  7048 I bluedroid-qcom: get_profile_interface pan
08-16 12:15:08.084  7048  7048 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-16 12:15:08.085  7048  7048 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9fee8cb
08-16 12:15:08.085  7048  7048 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-16 12:15:08.089  7048  7048 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 12:15:08.090  7048  7048 D BtGatt.GattService: Received start request. Starting profile...
08-16 12:15:08.090  7048  7048 D BtGatt.GattService: start()
08-16 12:15:08.090  7048  7048 I bluedroid-qcom: get_profile_interface gatt
08-16 12:15:08.090  7048  7048 D BtGatt.AdvertiseManager: advertise manager created
,08-16 12:15:08.098  7048  7048 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9fee8cb
08-16 12:15:08.100  7048  7048 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9fee8cb
08-16 12:15:08.101  7048  7048 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-16 12:15:08.103  7048  7048 V BluetoothMapService: BluetoothMapBinder()
08-16 12:15:08.103  7048  7048 D BluetoothMapService: Received start request. Starting profile...
08-16 12:15:08.103  7048  7048 D BluetoothMapService: start()
,08-16 12:15:08.110  7048  7048 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 12:15:08.110  7048  7048 D BluetoothMapEmailAppObserver: createReceiver()
08-16 12:15:08.111  7048  7048 D BluetoothMapEmailAppObserver: initObservers()
08-16 12:15:08.111  7048  7048 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-16 12:15:08.120  7048  7048 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9fee8cb
08-16 12:15:08.121  7048  7048 D HeadsetStateMachine: Proxy object connected
08-16 12:15:08.121  7048  7048 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 12:15:08.121  7048  7048 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-16 12:15:08.124  7048  7651 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 12:15:08.127  7048  7651 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 12:15:08.128  7048  7651 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-16 12:15:08.129  7048  7048 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 12:15:08.135  7048  7048 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 12:15:08.139  7048  7048 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 12:15:08.142  7048  7048 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 12:15:08.143  7048  7048 V PanService: [BTUI] SIM Extra State :ABSENT
08-16 12:15:08.146  7048  7048 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 12:15:08.149  7048  7048 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-16 12:15:08.149  7048  7048 V BluetoothMapService: Handler(): got msg=1
,08-16 12:15:08.151  7048  7617 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 12:15:08.151  7048  7617 I bluedroid-qcom: enable
08-16 12:15:08.152  7048  7617 I bt_hci_bdroid: init
08-16 12:15:08.153  7048  7048 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:08.154  7048  7617 I bt_vendor: bt-vendor : init
08-16 12:15:08.154  7048  7617 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 12:15:08.154  7048  7617 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 12:15:08.154  7048  7617 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 12:15:08.154  7048  7617 D bt_userial_mct: userial_init
08-16 12:15:08.152  7048  7673 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 12:15:08.154  7048  7617 D bt_hci_bdroid: set_power 1
08-16 12:15:08.154  7048  7617 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 12:15:08.154  7048  7617 I bt_vendor: Starting hciattach daemon
08-16 12:15:08.154  7048  7617 I bt_vendor: try to set true
08-16 12:15:08.156  7048  7673 I bt-btu  : btu_task pending for preload complete event
08-16 12:15:08.151  7676  7676 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:15:08.157  7048  7048 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 12:15:08.158  7048  7048 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 12:15:08.158  7048  7048 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 12:15:08.158  7048  7048 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:08.151  7676  7676 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:15:08.158  7048  7048 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-16 12:15:08.178  7677  7677 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 12:15:08.206  1036  1872 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7680 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 12:15:08.243  7700  7700 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
08-16 12:15:08.253  7701  7701 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 12:15:08.258  7680  7680 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 12:15:08.270  1036  1771 I ActivityManager: Killing 6724:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-16 12:15:08.271  7703  7703 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-16 12:15:08.279  7704  7704 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-16 12:15:08.286  5713  5713 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-16 12:15:08.286  5713  5713 W System.err: android.os.DeadObjectException
08-16 12:15:08.286  5713  5713 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 12:15:08.286  5713  5713 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 12:15:08.286  5713  5713 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-16 12:15:08.286  5713  5713 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-16 12:15:08.286  5713  5713 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 12:15:08.286  5713  5713 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 12:15:08.286  5713  5713 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 12:15:08.286  5713  5713 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 12:15:08.286  5713  5713 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 12:15:08.286  5713  5713 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 12:15:08.286  5713  5713 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:15:08.286  5713  5713 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 12:15:08.286  5713  5713 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 12:15:08.286  5713  5713 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 12:15:08.287  5713  5713 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
,08-16 12:15:08.287  5713  5713 W System.err: android.os.DeadObjectException
08-16 12:15:08.287  5713  5713 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 12:15:08.287  5713  5713 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 12:15:08.287  5713  5713 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-16 12:15:08.287  5713  5713 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-16 12:15:08.287  5713  5713 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 12:15:08.287  5713  5713 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 12:15:08.287  5713  5713 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 12:15:08.287  5713  5713 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 12:15:08.287  5713  5713 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 12:15:08.287  5713  5713 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 12:15:08.287  5713  5713 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:15:08.287  5713  5713 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 12:15:08.287  5713  5713 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 12:15:08.287  5713  5713 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 12:15:08.287  5713  5713 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-16 12:15:08.288  5713  5713 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-16 12:15:08.288  7705  7705 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 12:15:08.296  7706  7706 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-16 12:15:08.314  7708  7708 I libmdmdetect: ESOC framework not supported
08-16 12:15:08.315  7708  7708 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-16 12:15:08.323  7708  7708 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-16 12:15:08.323  7708  7708 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-16 12:15:08.323  7708  7708 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-16 12:15:08.323  7708  7708 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 12:15:08.323  7708  7708 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-16 12:15:08.323  7708  7708 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-16 12:15:08.323  7708  7708 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-16 12:15:08.358  7708  7709 E QC-QMI  : qmi_client [7708] 14: failed to locate client data
08-16 12:15:08.360   441   441 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-16 12:15:08.360   441   441 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-16 12:15:08.389  1036  1560 W libprocessgroup: failed to open /acct/uid_1000/pid_6724/cgroup.procs: No such file or directory
,08-16 12:15:08.390  1036  1560 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-16 12:15:08.394  5713  5713 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-16 12:15:08.394  5713  5713 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 12:15:08.428  7710  7710 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 12:15:08.444  7711  7711 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 12:15:08.484  1036  1060 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7713 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 12:15:08.485  5713  5713 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-16 12:15:08.504   344   344 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 432us total 20.886ms
,08-16 12:15:08.508  7048  7617 I bt_vendor: bluetooth satus is on
08-16 12:15:08.508  7048  7617 D bt_hci_bdroid: preload
08-16 12:15:08.508  7048  7675 D bt_userial_mct: userial_open(port:0)
08-16 12:15:08.508  7048  7675 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-16 12:15:08.512  7048  7675 I bt_vendor: Done intiailizing UART
08-16 12:15:08.516  7048  7675 I bt_vendor: Done intiailizing UART
08-16 12:15:08.516  7048  7675 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 12:15:08.516  7048  7675 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 12:15:08.516  7048  7673 I bt-btu  : btu_task received preload complete event
,08-16 12:15:08.519  7048  7673 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 12:15:08.519  7048  7729 D bt_userial_mct: Entering userial_read_thread()
08-16 12:15:08.519  7048  7673 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-16 12:15:08.523   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 375us total 18.448ms
08-16 12:15:08.524  7048  7673 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-16 12:15:08.530  7048  7673 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 12:15:08.530  7048  7673 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 12:15:08.530  7048  7673 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 12:15:08.530  7048  7673 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 12:15:08.530  7048  7673 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 12:15:08.530  7048  7673 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 12:15:08.530  7048  7673 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 12:15:08.530  7048  7673 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 12:15:08.530  7048  7673 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 12:15:08.530  7048  7673 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 12:15:08.530  7048  7673 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 12:15:08.530  7048  7673 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 12:15:08.530  7048  7673 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 12:15:08.530  7048  7673 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 12:15:08.530  7048  7673 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 12:15:08.531  7048  7673 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 12:15:08.540   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 296us total 16.211ms
,08-16 12:15:08.582  7048  7673 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-16 12:15:08.582  7048  7673 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa021c061 
,08-16 12:15:08.582  7048  7673 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa021c061 
08-16 12:15:08.584  7713  7713 D UEI.SmartControl: Quickset Services start...
08-16 12:15:08.585  7713  7713 I UEI.SmartControl: Manufacture = LGE
08-16 12:15:08.585  7713  7713 D UEI.SmartControl: Id = LGNevo
08-16 12:15:08.587  7713  7713 D UEI.SmartControl: File observer start...
08-16 12:15:08.587  7713  7713 E UEI.SmartControl: IR Port is disabled: false
08-16 12:15:08.587  7713  7713 D UEI.SmartControl: Starting file observer...
08-16 12:15:08.588  7713  7713 D UEI.SmartControl: Extracting JNI libs...
08-16 12:15:08.588  7713  7713 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-16 12:15:08.594  7048  7621 E bt-btif : Calling BTA_HhEnable
08-16 12:15:08.594  7048  7621 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-16 12:15:08.595  7048  7621 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 12:15:08.596  7048  7673 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-16 12:15:08.596  7048  7673 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,08-16 12:15:08.596  7048  7673 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 12:15:08.596  7048  7621 D BluetoothAdapterProperties: Name is: G3
08-16 12:15:08.596  7048  7673 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 12:15:08.596  7048  7673 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-16 12:15:08.598  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 12:15:08.598  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 12:15:08.600  7048  7621 D BluetoothAdapterProperties: Scan Mode:20
08-16 12:15:08.600  7048  7621 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 12:15:08.600  7048  7621 D bt_hci_bdroid: postload
08-16 12:15:08.601  7048  7675 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 12:15:08.601  7048  7673 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-16 12:15:08.602  7048  7621 D bte_conf: Device ID record 1 : primary
08-16 12:15:08.602  7048  7621 D bte_conf:   vendorId            = 00c4
08-16 12:15:08.602  7048  7621 D bte_conf:   vendorIdSource      = 0001
08-16 12:15:08.602  7048  7621 D bte_conf:   product             = 13a1
08-16 12:15:08.602  7048  7621 D bte_conf:   version             = 1000
08-16 12:15:08.602  7048  7621 D bte_conf:   clientExecutableURL = 
08-16 12:15:08.602  7048  7621 D bte_conf:   serviceDescription  = 
08-16 12:15:08.602  7048  7621 D bte_conf:   documentationURL    = 
08-16 12:15:08.602  7048  7621 D bte_conf: bte_load_did_conf no section named DID2.
08-16 12:15:08.605  7048  7675 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 12:15:08.606  7048  7675 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 12:15:08.606  7048  7675 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 12:15:08.607  7048  7621 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 12:15:08.607  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:15:08.609  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:15:08.610  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:15:08.601  7733  7733 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:15:08.601  7733  7733 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:15:08.614  7048  7673 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 12:15:08.614  7048  7673 W bt-smp  : Plain text(LSB ~ MSB) = 1e 6a 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 12:15:08.614  7048  7673 W bt-smp  : Encrypted text(LSB ~ MSB) = 39 1b a5 7a 33 73 62 a9 cd 96 8a 2d 24 f5 7c 71 
08-16 12:15:08.615  7048  7675 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 12:15:08.615  7048  7673 W bt-btm  : Stopping oneshot timer
08-16 12:15:08.607  7048  7617 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-16 12:15:08.615  7048  7617 D BluetoothAdapterProperties: ScanMode =  20
08-16 12:15:08.615  7048  7617 D BluetoothAdapterProperties: State =  11
08-16 12:15:08.616  7048  7729 E bt_mct  : hci lib postload completed
08-16 12:15:08.616  7048  7617 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 12:15:08.616  7048  7617 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 12:15:08.617  7048  7617 D BluetoothAdapterProperties: Setting state to 12
08-16 12:15:08.617  7048  7617 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 12:15:08.617  7048  7621 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 12:15:08.618  7048  7617 I BluetoothAdapterState: Entering On State
08-16 12:15:08.618  1036  1119 D BluetoothManagerService: Message: 60
08-16 12:15:08.618  1036  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 12:15:08.618  1036  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-16 12:15:08.619  1837  1852 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 12:15:08.624  7048  7617 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 12:15:08.624  7048  7617 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 12:15:08.624  7048  7617 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-16 12:15:08.628  7048  7617 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-16 12:15:08.633  7048  7621 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 12:15:08.633  7048  7621 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-16 12:15:08.639  1036  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 12:15:08.640  6942  6966 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 12:15:08.643  1837  1837 D BluetoothHeadset: Proxy object connected
08-16 12:15:08.643  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 12:15:08.645  1837  1837 D BluetoothHeadset: Proxy object connected
08-16 12:15:08.645  6942  6942 D BluetoothInputDevice: Proxy object connected
08-16 12:15:08.645  6942  6942 D HidProfile: Bluetooth service connected
08-16 12:15:08.646  1036  1036 D BluetoothHeadset: Proxy object connected
08-16 12:15:08.647  7048  7673 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 12:15:08.647  7048  7673 W bt-smp  : Plain text(LSB ~ MSB) = e5 1b 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 12:15:08.647  7048  7673 W bt-smp  : Encrypted text(LSB ~ MSB) = aa bd 6f 34 ef ab c8 1a 2b fa 9d c2 d8 ff 2b 75 
08-16 12:15:08.647  7048  7673 W bt-btm  : Stopping oneshot timer
,08-16 12:15:08.651  1837  1852 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 12:15:08.653  6942  6966 D BluetoothPan: onBluetoothStateChange on: true
08-16 12:15:08.653  6942  6966 D BluetoothPan: onBluetoothStateChange call bindService
08-16 12:15:08.653  1837  1837 D BluetoothHeadset: Proxy object connected
08-16 12:15:08.655  1036  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 12:15:08.656  6942  6965 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 12:15:08.656  1036  1036 D BluetoothA2dp: Proxy object connected
08-16 12:15:08.656  6942  6942 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 12:15:08.656  6942  6942 D PanProfile: Bluetooth service connected
08-16 12:15:08.659  6942  6966 D BluetoothMap: onBluetoothStateChange: up=true
08-16 12:15:08.659  7713  7713 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-16 12:15:08.659  7713  7713 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-16 12:15:08.659  7048  7673 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-16 12:15:08.659  7713  7713 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-16 12:15:08.659  7048  7673 W bt-smp  : Plain text(LSB ~ MSB) = 8e 6b 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 12:15:08.659  7048  7673 W bt-smp  : Encrypted text(LSB ~ MSB) = 89 0b 6a 64 94 6a 8d 5a 4e e1 2e 48 bc dc 0e c2 
08-16 12:15:08.660  7048  7673 W bt-btm  : Stopping oneshot timer
08-16 12:15:08.660  1036  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 12:15:08.660  1036  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 12:15:08.663  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 12:15:08.663  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:08.664  1926  2118 D LGBluetoothAPIService: Message: 1
08-16 12:15:08.664  1926  2118 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-16 12:15:08.667  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-16 12:15:08.668  7048  7617 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-16 12:15:08.669  1926  2118 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-16 12:15:08.670  6814  6814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 12:15:08.671  7048  7048 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:08.671  7048  7048 D BluetoothMapService: STATE_ON
08-16 12:15:08.672  7048  7048 D LGBluetoothAPIServer: [BTUI] onCreate()
08-16 12:15:08.672  7048  7048 D LGBluetoothAPIServer: [BTUI] onBind()
08-16 12:15:08.672  7048  7673 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 12:15:08.672  7048  7673 W bt-smp  : Plain text(LSB ~ MSB) = 05 ba 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 12:15:08.672  7048  7673 W bt-smp  : Encrypted text(LSB ~ MSB) = f9 4c 1f ca a5 6e 8c 20 78 4d c3 35 e4 3e 84 25 
08-16 12:15:08.672  7048  7673 W bt-btm  : Stopping oneshot timer
08-16 12:15:08.673  1036  1119 D BluetoothManagerService: Message: 40
08-16 12:15:08.673  1036  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-16 12:15:08.673  1926  1926 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 12:15:08.673  1926  2118 D LGBluetoothAPIService: Message: 100
08-16 12:15:08.673  1926  2118 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,08-16 12:15:08.679  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:15:08.679  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:15:08.679  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:15:08.679  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:15:08.679  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:15:08.679  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:15:08.679  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:15:08.679  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:15:08.679  6942  6942 D LocalBluetoothProfileManager: Adding local A2DP profile
08-16 12:15:08.681  6814  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:15:08.683  1036  1119 D BluetoothManagerService: Message: 30
08-16 12:15:08.683  7048  7048 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9fee8cb
08-16 12:15:08.683  7048  7048 V BluetoothPbapService: Pbap Service onCreate
08-16 12:15:08.683  7048  7048 V BluetoothPbapService: Starting PBAP service
08-16 12:15:08.684  7048  7048 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
,08-16 12:15:08.684  7048  7048 V BluetoothPbapService: Pbap Service onBind
08-16 12:15:08.685  7048  7048 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:08.685  7048  7048 V BluetoothPbapService: state: 12
08-16 12:15:08.685  7048  7048 V BluetoothMapService: Handler(): got msg=1
08-16 12:15:08.686  7740  7740 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-16 12:15:08.686  7048  7048 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
,08-16 12:15:08.687  7048  7048 V BluetoothPbapService: Handler(): got msg=1
08-16 12:15:08.688  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:15:08.688  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:15:08.688  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:15:08.688  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:15:08.688  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:15:08.688  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:15:08.688  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:15:08.688  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:15:08.688  7048  7741 D BluetoothMapMasInstance: MAS initSocket()
08-16 12:15:08.688  7048  7048 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-16 12:15:08.688  6942  6942 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-16 12:15:08.689  7048  7741 D BluetoothMapMasInstance:   masId = 00
08-16 12:15:08.689  7048  7741 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 12:15:08.689  7048  7741 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 12:15:08.689  7048  7741 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-16 12:15:08.690  7048  7742 V BluetoothPbapService: Pbap Service initSocket
08-16 12:15:08.690  1036  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:15:08.690  7048  7673 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 12:15:08.690  7048  7673 W bt-smp  : Plain text(LSB ~ MSB) = ec 9a 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 12:15:08.690  7048  7673 W bt-smp  : Encrypted text(LSB ~ MSB) = 2b 04 19 64 73 b1 38 9c 98 04 08 fe 4e 8a a3 b1 
08-16 12:15:08.690  7048  7673 W bt-btm  : Stopping oneshot timer
08-16 12:15:08.691  1036  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:15:08.692  1036  1119 D BluetoothManagerService: Message: 30
08-16 12:15:08.693  6814  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:15:08.694  7048  7741 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 12:15:08.695  7048  7741 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-16 12:15:08.695  7048  7741 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 12:15:08.695  7048  7741 D BluetoothMapMasInstance: Accepting socket connection...
08-16 12:15:08.695  7048  7742 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 12:15:08.696  7048  7621 D BluetoothAdapterProperties: Scan Mode:21
08-16 12:15:08.696  7048  7621 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 12:15:08.697  7048  7742 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-16 12:15:08.697  7048  7742 V BluetoothPbapService: Succeed to create listening socket 
08-16 12:15:08.697  7048  7742 V BluetoothPbapService: Accepting socket connection...
,08-16 12:15:08.698  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:15:08.698  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:15:08.698  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:15:08.698  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:15:08.698  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:15:08.698  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:15:08.698  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:15:08.698  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:15:08.700  6814  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:15:08.702  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:15:08.703  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:15:08.704  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:15:08.705  6942  6942 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 12:15:08.707  6942  6942 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 12:15:08.709  6942  6942 D BluetoothMap: Proxy object connected
08-16 12:15:08.709  6942  6942 D MapProfile: Bluetooth service connected
08-16 12:15:08.709  6942  6942 D BluetoothMap: getConnectedDevices()
08-16 12:15:08.710  7048  7622 V BluetoothMapService: getConnectedDevices()
08-16 12:15:08.710  7048  7048 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 12:15:08.710  7048  7048 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-16 12:15:08.710  7048  7048 V BluetoothPbapReceiver: ***********state = 12
08-16 12:15:08.710  6942  6942 D BluetoothA2dp: Proxy object connected
08-16 12:15:08.712  6942  6942 D A2dpProfile: Bluetooth service connected
08-16 12:15:08.712  2168  2168 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 12:15:08.713  2168  2168 D c       : Getting all permits...
08-16 12:15:08.713  2168  2168 D a       : Opening database...
08-16 12:15:08.714  6942  6942 D BluetoothPbap: Proxy object connected
08-16 12:15:08.716  6942  6942 D PbapServerProfile: Bluetooth service connected
08-16 12:15:08.716  2168  2168 D a       : Opening database auth.proximity.permit_store...
08-16 12:15:08.716  6942  6942 D BluetoothHeadset: Proxy object connected
08-16 12:15:08.717  2168  2168 D a       : Closing database...
08-16 12:15:08.717  6942  6942 D HeadsetProfile: Bluetooth service connected
08-16 12:15:08.720  7713  7713 I UEI.SmartControl: --- Selecting new region: 6
08-16 12:15:08.722  7713  7713 I UEI.SmartControl: Model = LG-D855
,08-16 12:15:08.723  7713  7713 D UEI.SmartControl: QS Service created
08-16 12:15:08.724  6942  6942 D DockEventReceiver: finishStartingService: stopping service
08-16 12:15:08.728  6942  6942 D BluetoothPermissionRequest: onReceive
08-16 12:15:08.729  6942  6942 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 12:15:08.730  6942  6942 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 12:15:08.732  7048  7048 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-16 12:15:08.733  7048  7048 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-16 12:15:08.738  7048  7048 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-16 12:15:08.742  7713  7713 I UEI.SmartControl: Service initServices...
,08-16 12:15:08.746  7713  7713 D UEI.SmartControl: QS start get config
08-16 12:15:08.747  7048  7048 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 12:15:08.748  7048  7048 V BtOppService: onCreate
08-16 12:15:08.750  7048  7048 V BluetoothOppNotification: send message
08-16 12:15:08.752  7048  7048 V BtOppService: Starting RfcommListener
08-16 12:15:08.755  7048  7048 D BluetoothOppPreference: Dumping Names:  
08-16 12:15:08.755  7048  7048 D BluetoothOppPreference: {}
08-16 12:15:08.755  7048  7048 D BluetoothOppPreference: Dumping Channels:  
08-16 12:15:08.755  7048  7048 D BluetoothOppPreference: {}
,08-16 12:15:08.761  7048  7048 V BtOppService: onStartCommand
08-16 12:15:08.761  7048  7746 V BtOppService: Deleted complete outbound shares, number =  0
08-16 12:15:08.762  7048  7746 V BtOppService: Deleted complete inbound failed shares, number = 0
08-16 12:15:08.763  7048  7746 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-16 12:15:08.764  7048  7746 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13aa9de4 on behalf of 
08-16 12:15:08.764  7048  7048 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:08.764  7048  7749 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 12:15:08.765  7048  7048 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 12:15:08.765  7048  7749 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 12:15:08.766  7048  7749 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e18e24d on behalf of 
08-16 12:15:08.766  7048  7749 V BluetoothOppNotification: update too frequent, put in queue
08-16 12:15:08.767  7048  7048 V BluetoothOppNotification: new notify threadi!
08-16 12:15:08.768  7048  7048 V BluetoothOppNotification: send delay message
08-16 12:15:08.768  7048  7749 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 12:15:08.768  7048  7048 V BtOppService: start RfcommListener
,08-16 12:15:08.775  7048  7750 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 12:15:08.777  7048  7750 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a1a0102 on behalf of 
08-16 12:15:08.777  7048  7750 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 12:15:08.777  7048  7048 V BtOppService: RfcommListener started
08-16 12:15:08.778  7048  7048 V BtOppService: ContentObserver received notification
08-16 12:15:08.778  7048  7751 V BtOppRfcommListener: Starting RFCOMM listener....
08-16 12:15:08.778  7048  7048 V BtOppService: ContentObserver received notification
08-16 12:15:08.778  1036  1637 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:15:08.779  7048  7751 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 12:15:08.779  7048  7752 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 12:15:08.779  7048  7751 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
,08-16 12:15:08.780  7048  7751 V BtOppRfcommListener: Started RFCOMM listener....
08-16 12:15:08.780  7048  7751 I BtOppRfcommListener: Accept thread started.
08-16 12:15:08.780  7048  7751 V BtOppRfcommListener: Accepting connection...
08-16 12:15:08.782  7048  7750 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 12:15:08.782  7048  7752 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 12:15:08.783  7048  7752 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32ed3a13 on behalf of 
08-16 12:15:08.784  7048  7750 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3465b450 on behalf of 
08-16 12:15:08.785  7048  7752 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 12:15:08.785  7048  7750 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 12:15:08.786  7048  7750 V BluetoothOppNotification: outbound notification was removed.
08-16 12:15:08.786  7048  7750 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 12:15:08.787  7048  7750 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@121e5649 on behalf of 
08-16 12:15:08.788  7048  7750 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 12:15:08.789  7048  7750 V BluetoothOppNotification: inbound notification was removed.
08-16 12:15:08.789  7048  7750 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 12:15:08.791  7048  7750 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3aab2b4e on behalf of 
,08-16 12:15:08.792  7048  7048 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9fee8cb
08-16 12:15:08.792  7048  7048 V BluetoothFtpService: Ftp Service onCreate
08-16 12:15:08.792  7048  7048 I BluetoothFtpService: Ftp Service onCreate
08-16 12:15:08.792  7048  7048 V BluetoothFtpService: Ftp Service onStartCommand
08-16 12:15:08.792  7048  7048 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:08.792  7048  7048 V BluetoothFtpService: Starting Listening on sockets
,08-16 12:15:08.793  7048  7048 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 12:15:08.793  7048  7048 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 12:15:08.793  7048  7048 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 12:15:08.793  7048  7048 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:08.793  7048  7048 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 12:15:08.793  7048  7048 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 12:15:08.794  7048  7048 V BluetoothFtpService: Handler(): got msg=1
08-16 12:15:08.794  7048  7048 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-16 12:15:08.794  7048  7048 V BluetoothFtpService: Ftp Service initSocket
08-16 12:15:08.796  1036  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:15:08.798  7048  7048 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 12:15:08.799  7048  7048 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-16 12:15:08.799  7048  7048 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-16 12:15:08.800  7048  7753 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-16 12:15:08.813  7048  7048 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9fee8cb
08-16 12:15:08.813  7048  7048 V BluetoothSapService: Sap Service onCreate
,08-16 12:15:08.815  7048  7048 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 12:15:08.815  7048  7048 V BluetoothSapService: state: 12
08-16 12:15:08.815  7048  7048 V BluetoothSapService: Starting SAP server process
08-16 12:15:08.811  7754  7754 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:15:08.817  7048  7048 V BluetoothSapService: SAP Service startRfcommListenerThread
08-16 12:15:08.811  7754  7754 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:15:08.819  7048  7755 V BluetoothSapService: Sap Service initRfcommSocket
,08-16 12:15:08.819  1036  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
08-16 12:15:08.820  7048  7755 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 12:15:08.821  7713  7713 D UEI.SmartControl: Loading JNI Libs...,
08-16 12:15:08.821  7048  7755 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-16 12:15:08.821  7048  7755 V BluetoothSapService: Succeed to create listening socket 
08-16 12:15:08.821  7048  7755 V BluetoothSapService: Accepting socket connection...
08-16 12:15:08.824  7754  7754 V BT_SAP  : Event pipe created
,08-16 12:15:08.824  7754  7754 V BT_SAP  : create_server_socket qcom.sap.server
08-16 12:15:08.824  7754  7754 V BT_SAP  : created socket fd 6
08-16 12:15:09.122  7713  7713 I UEI.SmartControl: Supports setup maps: true
,08-16 12:15:09.142  7713  7713 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 12:15:09.143  7713  7713 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 12:15:09.143  7713  7713 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 12:15:09.143  7713  7713 I UEI.SmartControl: ### init IR Blaster...
08-16 12:15:09.150  7713  7713 D serial_port: Configuring serial port
,08-16 12:15:09.157  7713  7713 E UEI.SmartControl: UEIBLaster setting for 616
08-16 12:15:09.158  7713  7713 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 12:15:09.158  7713  7713 I UEI.SmartControl: configuring settings for MAXQ616
08-16 12:15:09.158  7713  7713 I UEI.SmartControl: Get version...
08-16 12:15:09.175  7713  7762 D UEI.SmartControl: serial port data available: 21
,08-16 12:15:09.202  7713  7713 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-16 12:15:09.202  7713  7713 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 12:15:09.203  7713  7713 I UEI.SmartControl: QS saving settings...
08-16 12:15:09.204  7713  7713 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 12:15:09.223  7713  7762 D UEI.SmartControl: serial port data available: 4
,08-16 12:15:09.278  7713  7768 I UEI.SmartControl: Device manager: loading config....
,08-16 12:15:09.295  7713  7713 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-16 12:15:09.300  7713  7713 E UEI.SmartControl: Services init done
08-16 12:15:09.300  7713  7713 D UEI.SmartControl: QS Service init finished
08-16 12:15:09.301  7713  7768 D UEI.SmartControl: ----------- loading internal config...
08-16 12:15:09.305  7713  7713 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 12:15:09.305  7713  7713 D UEI.SmartControl: QS Service version code: 201091
08-16 12:15:09.306  7713  7713 D UEI.SmartControl: Service requested: Control
08-16 12:15:09.310  7713  7768 E UEI.SmartControl: Loading SETTINGS...
,08-16 12:15:09.314  7713  7713 D UEI.SmartControl: Request IControl service: devices are loaded...
08-16 12:15:09.318  1036  1907 I ActivityManager: Killing 5713:com.lge.qremote/u0a112 (adj 15): empty #17
08-16 12:15:09.337  7713  7768 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-16 12:15:09.355  7713  7767 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 12:15:09.356  7713  7767 D UEI.SmartControl: -----service ready thread exits
,08-16 12:15:09.373  1036  1925 W libprocessgroup: failed to open /acct/uid_10112/pid_5713/cgroup.procs: No such file or directory
,08-16 12:15:09.377  7713  7713 D UEI.SmartControl: Internal service binding...
08-16 12:15:09.496  1587  1587 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-16 12:15:09.518  1036  1442 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 12:15:09.583  1036  1110 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7770 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-16 12:15:09.598  1587  1587 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-16 12:15:09.602  1587  1587 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-16 12:15:09.632  1036  1036 D administrator: Handling package changes for user 0
,08-16 12:15:09.645  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 12:15:09.678  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 12:15:09.686  7770  7770 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 12:15:09.690  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-16 12:15:09.690  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-16 12:15:09.746  1036  1108 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 12:15:09.753  1036  1108 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-16 12:15:09.762  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-16 12:15:09.764  2466  2466 V GmsNetworkLocationProvi: DISABLE
,08-16 12:15:09.770  7048  7048 V BluetoothOppNotification: new notify threadi!
08-16 12:15:09.771  7048  7048 V BluetoothOppNotification: send delay message
08-16 12:15:09.773  7048  7805 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 12:15:09.774  7048  7805 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2afd88b on behalf of 
08-16 12:15:09.776  7048  7805 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-16 12:15:09.778  7048  7805 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 12:15:09.781  7048  7805 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f5bbd68 on behalf of 
08-16 12:15:09.781  7048  7805 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 12:15:09.784  7048  7805 V BluetoothOppNotification: outbound notification was removed.
08-16 12:15:09.784  7048  7805 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 12:15:09.785  7048  7805 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14358581 on behalf of 
08-16 12:15:09.785  7048  7805 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 12:15:09.787  7048  7805 V BluetoothOppNotification: inbound notification was removed.
08-16 12:15:09.787  7048  7805 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 12:15:09.788  7048  7805 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2c3d5626 on behalf of 
,08-16 12:15:09.791  7770  7770 D LgDataFeature: LgDataFeature() Constructor: none
08-16 12:15:09.791  7770  7770 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 12:15:09.797  1036  1108 D LocationProviderProxy: applying state to connected service
08-16 12:15:09.800  2466  2466 E GCoreFlp: Bound FusedProviderService with LocationManager
08-16 12:15:09.876  1036  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2f54394e type 2 when 379908 com.google.android.gms} when 379908
,08-16 12:15:09.915  7770  7815 I Babel   : MmsConfig: mnc/mcc: 0/0
08-16 12:15:09.916  7770  7815 I Babel   : MmsConfig.loadMmsSettings
,08-16 12:15:09.929  7770  7815 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-16 12:15:09.929  7770  7815 I Babel   : MmsConfig.loadFromDatabase
,08-16 12:15:09.958  7770  7815 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-16 12:15:09.958  7770  7815 I Babel   : MmsConfig.loadFromResources
08-16 12:15:09.960  7770  7815 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-16 12:15:09.961  7770  7815 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 12:15:09.965  7770  7770 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 12:15:09.988  7770  7814 W AudioCapabilities: Unsupported mime audio/evrc
08-16 12:15:09.992  7770  7814 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 12:15:09.994  7770  7814 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 12:15:10.000  1802  7819 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-16 12:15:10.000  1802  7819 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-16 12:15:10.012  7089  7089 I AppUp4:CustModeStarterReceiver: onReceive
08-16 12:15:10.013  1802  5223 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-16 12:15:10.019  7089  7089 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@c671445
08-16 12:15:10.019  7089  7089 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 12:15:10.019  7089  7089 D AppUp4:CustFacade: isPhone : true
08-16 12:15:10.019  7089  7089 D AppUp4:CustModeStarterReceiver: begin check event
08-16 12:15:10.019  7089  7089 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-16 12:15:10.028  7770  7814 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-16 12:15:10.031  7770  7814 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 12:15:10.032  7770  7814 W AudioCapabilities: Unsupported mime audio/evrc
08-16 12:15:10.046  7770  7814 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-16 12:15:10.049  7770  7814 W VideoCapabilities: Unsupported mime video/divx
08-16 12:15:10.051  7770  7814 W VideoCapabilities: Unsupported mime video/divx311
08-16 12:15:10.054  7770  7814 W VideoCapabilities: Unsupported mime video/divx4
08-16 12:15:10.058  1036  1637 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7822 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-16 12:15:10.061  1036  2018 I ActivityManager: Killing 6970:com.lge.sync/1000 (adj 15): empty #17
,08-16 12:15:10.064  7770  7814 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-16 12:15:10.087  7770  7814 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 12:15:10.091  7770  7814 W AudioCapabilities: Unsupported mime audio/eac3
08-16 12:15:10.091  7770  7814 W AudioCapabilities: Unsupported mime audio/ac3
08-16 12:15:10.092  7770  7814 W AudioCapabilities: Unsupported mime audio/g726
08-16 12:15:10.093  7770  7814 W AudioCapabilities: Unsupported mime audio/wma-voice
08-16 12:15:10.094  7770  7814 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-16 12:15:10.095  7770  7814 W AudioCapabilities: Unsupported mime audio/adpcm
08-16 12:15:10.096  7770  7814 W VideoCapabilities: Unsupported mime video/theora
08-16 12:15:10.098  7770  7814 W VideoCapabilities: Unsupported mime video/mjpg
08-16 12:15:10.147  1036  1925 W libprocessgroup: failed to open /acct/uid_1000/pid_6970/cgroup.procs: No such file or directory
,08-16 12:15:10.201  7822  7822 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 12:15:10.202  7822  7822 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 12:15:10.203  7822  7822 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 12:15:10.206  7822  7822 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-16 12:15:10.207  7822  7822 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-16 12:15:10.291  7822  7822 I SystemConfig: BUILD Country: EU
08-16 12:15:10.291  7822  7822 I SystemConfig: BUILD Operator: OPEN
,08-16 12:15:10.346  1036  1980 I ActivityManager: Killing 7117:com.lge.email/u0a23 (adj 15): empty #17
,08-16 12:15:10.433  1036  1560 W libprocessgroup: failed to open /acct/uid_10023/pid_7117/cgroup.procs: No such file or directory
,08-16 12:15:10.502  1036  1980 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7845 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-16 12:15:10.505  7822  7840 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-16 12:15:10.505  7822  7840 I SystemConfig: existFile = false
08-16 12:15:10.506  7822  7840 I SystemConfig: canReadFile = false
08-16 12:15:10.506  7822  7840 I SystemConfig: systemFeature RCS result false
08-16 12:15:10.506  7822  7840 D SystemConfig: refreshRcsSupport() :false
,08-16 12:15:10.591  7845  7845 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 12:15:10.592  7845  7845 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 12:15:10.592  7845  7845 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 12:15:10.593  7845  7845 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 12:15:10.695  7845  7845 I AppConfig: Total System Memory = 2995761152
,08-16 12:15:10.719  7845  7845 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-16 12:15:10.798  1036  1944 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7867 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 12:15:10.799  1036  1944 I ActivityManager: Killing 7017:com.lge.formmanager/u0a26 (adj 15): empty #17
08-16 12:15:10.874  1036  1560 W libprocessgroup: failed to open /acct/uid_10026/pid_7017/cgroup.procs: No such file or directory
,08-16 12:15:11.074  7867  7867 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-16 12:15:11.197  7867  7867 D LgDataFeature: LgDataFeature() Constructor: none
08-16 12:15:11.197  7867  7867 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 12:15:11.248  7867  7867 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-16 12:15:11.267  7867  7867 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 12:15:11.268  7867  7867 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 12:15:11.284  7867  7867 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-16 12:15:11.284  7867  7867 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-16 12:15:11.306  1036  1943 I ActivityManager: Killing 6441:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-16 12:15:11.350  1036  1925 W libprocessgroup: failed to open /acct/uid_1000/pid_6441/cgroup.procs: No such file or directory
,08-16 12:15:11.357  3395  5996 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-16 12:15:11.359  5051  7910 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-16 12:15:11.362  3395  5996 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1a5f84d9 on behalf of 7867
08-16 12:15:11.418  1036  1771 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7911 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-16 12:15:11.452  7867  7867 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-16 12:15:11.480  7867  7867 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-16 12:15:11.508  7911  7911 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-16 12:15:11.530  7911  7911 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-16 12:15:11.530  7911  7911 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-16 12:15:11.530  7911  7911 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-16 12:15:11.530  7911  7911 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-16 12:15:11.530  7911  7911 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-16 12:15:11.531  7911  7911 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-16 12:15:11.551   311  7933 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 12:15:11.551  1036  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-16 12:15:11.560  1036  1943 I ActivityManager: Killing 7147:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-16 12:15:11.598  1036  1925 W libprocessgroup: failed to open /acct/uid_10046/pid_7147/cgroup.procs: No such file or directory
,08-16 12:15:11.853  1036  2018 I art     : Explicit concurrent mark sweep GC freed 28836(1431KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 3.562ms total 158.690ms
,08-16 12:15:11.919  1036  2018 V SIM_STK : Menu title from STK is T-Mobile
,08-16 12:15:11.960  5051  7910 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 602 ms] updated apps [took 602 ms] 
,08-16 12:15:12.449  1036  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 12:15:12.449  1036  1962 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3d1b4fba mBinding = false
,08-16 12:15:12.478  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 12:15:12.478  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 12:15:12.478  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-16 12:15:12.481  1036  1119 D BluetoothManagerService: Message: 2
08-16 12:15:12.482  1036  1119 D BluetoothManagerService: Sending off request.
08-16 12:15:12.483  7048  7064 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 12:15:12.484  7048  7617 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 12:15:12.484  7048  7617 D BluetoothAdapterProperties: Setting state to 13
08-16 12:15:12.484  7048  7617 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 12:15:12.485  7048  7617 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 12:15:12.485  7048  7617 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 12:15:12.487  7048  7621 D BluetoothAdapterProperties: Scan Mode:20
08-16 12:15:12.489  7048  7617 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 12:15:12.490  7048  7741 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 12:15:12.490  7048  7741 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 12:15:12.490  7048  7741 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 12:15:12.490  7048  7741 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 12:15:12.490  7048  7741 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 12:15:12.490  7048  7741 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 12:15:12.490  7048  7741 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 12:15:12.490  7048  7741 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-16 12:15:12.494  7048  7742 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 12:15:12.495  7048  7751 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 12:15:12.495  7048  7753 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 12:15:12.496  7048  7755 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 12:15:12.497  7048  7673 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-16 12:15:12.497  7048  7673 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-16 12:15:12.499  7048  7617 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 12:15:12.502  7048  7673 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 12:15:12.503  7048  7673 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 12:15:12.503  7048  7673 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 12:15:12.503  7048  7673 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 12:15:12.503  7048  7673 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 12:15:12.503  7048  7673 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 12:15:12.503  7048  7673 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 12:15:12.503  7048  7673 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 12:15:12.503  7048  7673 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 12:15:12.503  7048  7673 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 12:15:12.503  7048  7673 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 12:15:12.503  7048  7673 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-16 12:15:12.517  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:15:12.517  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:15:12.517  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:15:12.517  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:15:12.517  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:15:12.517  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:15:12.517  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:15:12.517  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:15:12.517  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:15:12.521  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:15:12.522  6814  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:15:12.524  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:15:12.524  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:15:12.524  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:15:12.524  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:15:12.524  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:15:12.524  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:15:12.524  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:15:12.524  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:15:12.524  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:15:12.526  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:15:12.526  6814  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:15:12.529  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:15:12.529  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:15:12.529  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:15:12.529  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:15:12.529  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:15:12.529  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:15:12.529  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:15:12.529  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:15:12.529  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:15:12.530  6814  6814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:15:12.530  6814  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 12:15:12.534  1036  1119 D BluetoothManagerService: Message: 60
08-16 12:15:12.534  1036  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 12:15:12.534  1036  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-16 12:15:12.537  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:12.538  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 12:15:12.543  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:15:12.548  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:15:12.549  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:15:12.550  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:15:12.550  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:15:12.551  7048  7048 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:12.552  7048  7048 D BluetoothMapService: STATE_TURNING_OFF
08-16 12:15:12.556  7048  7048 V BluetoothMapService: Handler(): got msg=4
08-16 12:15:12.556  7048  7048 D BluetoothMapService: MAP Service closeService in
08-16 12:15:12.556  7048  7048 D BluetoothMapMasInstance: MAP Service shutdown
08-16 12:15:12.556  7048  7048 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 12:15:12.556  7048  7048 V BluetoothMapService: MAP Service closeService out
,08-16 12:15:12.567  7048  7048 V BtOppService: Receiver DISABLED_ACTION 
08-16 12:15:12.567  7048  7048 I BtOppRfcommListener: stopping Accept Thread
08-16 12:15:12.567  7048  7048 V BtOppRfcommListener: close mBtServerSocket
08-16 12:15:12.568  7048  7751 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 12:15:12.570  7048  7048 V BtOppRfcommListener: waiting for thread to terminate
08-16 12:15:12.570  7048  7048 V BtOppRfcommListener: done waiting for thread to terminate
,08-16 12:15:12.576  6942  6942 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-16 12:15:12.578  6942  6942 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 12:15:12.580  7048  7048 V BtOppService: onDestroy
08-16 12:15:12.583  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:15:12.583  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@184d6136 removed from the list
08-16 12:15:12.583  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:15:12.583  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:15:12.583  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:15:12.584  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:15:12.584  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@83f71a4 added. We now have 4 listener(s)
08-16 12:15:12.584  6814  6884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 12:15:12.590  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:15:12.590  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@83f71a4 removed from the list
08-16 12:15:12.590  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:15:12.590  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:15:12.590  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:15:12.593  7048  7048 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 12:15:12.597  7048  7048 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 12:15:12.597  7048  7048 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:12.597  7048  7048 V BluetoothPbapReceiver: ***********state = 13
,08-16 12:15:12.602  7048  7048 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-16 12:15:12.603  7048  7048 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:12.603  7048  7048 V BluetoothPbapService: state: 13
08-16 12:15:12.604  7048  7048 V BluetoothPbapService: Pbap Service closeService in
08-16 12:15:12.611  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:15:12.611  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@207b8b0d added. We now have 4 listener(s)
08-16 12:15:12.611  6814  6884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 12:15:12.614  2168  2168 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 12:15:12.616  7048  7048 V BluetoothPbapService: successfully stopped pbap service
08-16 12:15:12.616  7048  7048 V BluetoothPbapService: Pbap Service closeService out
08-16 12:15:12.616  7048  7048 V BluetoothPbapService: Pbap Service onDestroy
08-16 12:15:12.616  7048  7048 V BluetoothPbapService: Pbap Service closeService in
08-16 12:15:12.616  7048  7048 V BluetoothPbapService: Pbap Service closeService out
08-16 12:15:12.617  7048  7048 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-16 12:15:12.624  1036  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:15:12.624  1036  1943 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3d1b4fba mBinding = false
08-16 12:15:12.624  1036  1119 D BluetoothManagerService: Message: 2
08-16 12:15:12.624  6942  6942 D DockEventReceiver: finishStartingService: stopping service
08-16 12:15:12.624  1036  1119 D BluetoothManagerService: Sending off request.
08-16 12:15:12.626  7048  7063 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 12:15:12.626  7048  7063 D BluetoothAdapterService: disable() : BT State is not STATE_ON. Can't disable BT
,08-16 12:15:12.627  6942  6942 D BluetoothPbap: Proxy object disconnected
08-16 12:15:12.627  6942  6942 D PbapServerProfile: Bluetooth service disconnected
08-16 12:15:12.628  1036  1119 E BluetoothManagerService: IBluetooth.disable() returned false
08-16 12:15:12.636  6942  6942 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-16 12:15:12.636  1036  1530 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-16 12:15:12.642  6942  6942 D BluetoothPermissionRequest: onReceive
,08-16 12:15:12.642  6942  6942 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-16 12:15:12.648  6942  6942 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 12:15:12.651  7048  7048 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-16 12:15:12.651  7048  7048 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-16 12:15:12.652  7048  7048 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-16 12:15:12.656  7048  7048 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:12.657  7048  7048 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 12:15:12.658  7048  7048 V BluetoothFtpService: Ftp Service onStartCommand
08-16 12:15:12.658  7048  7048 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:12.658  7048  7048 V BluetoothFtpService: Ftp Service closeService
08-16 12:15:12.658  7048  7048 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 12:15:12.659  7048  7048 V BluetoothFtpService: successfully stopped ftp service
08-16 12:15:12.659  7048  7048 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 12:15:12.659  7048  7048 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 12:15:12.660  7048  7048 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 12:15:12.660  7048  7048 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:12.660  7048  7048 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-16 12:15:12.660  7048  7048 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 12:15:12.663  7048  7048 V BluetoothFtpService: Ftp Service onDestroy
08-16 12:15:12.663  7048  7048 V BluetoothFtpService: Ftp Service closeService
08-16 12:15:12.667  7048  7048 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:12.667  7048  7048 V BluetoothSapService: state: 13
08-16 12:15:12.667  7048  7048 V BluetoothSapService: Stopping SAP server process
,08-16 12:15:12.669  7048  7048 V BluetoothSapService: Sap Service closeSapService in
,08-16 12:15:12.669  7048  7048 V BluetoothSapService: Close listen Socket : 
08-16 12:15:12.669  7048  7048 V BluetoothSapService: Close rfcomm Socket : 
08-16 12:15:12.669  7048  7048 V BluetoothSapService: Close sapd  Socket : 
08-16 12:15:12.670  7048  7048 V BluetoothSapService: Sap Service closeSapService out
08-16 12:15:12.670  7048  7048 V BluetoothSapService: Sap Service onDestroy
08-16 12:15:12.670  7048  7048 V BluetoothSapService: Sap Service closeSapService in
08-16 12:15:12.671  7048  7048 V BluetoothSapService: Close listen Socket : 
08-16 12:15:12.671  7048  7048 V BluetoothSapService: Close rfcomm Socket : 
08-16 12:15:12.671  7048  7048 V BluetoothSapService: Close sapd  Socket : 
08-16 12:15:12.671  7048  7048 V BluetoothSapService: Sap Service closeSapService out
08-16 12:15:13.404  7048  7621 D bt_hci_bdroid: cleanup
,08-16 12:15:13.416  7048  7675 I bt_lpm  : LPM is already off!!!
08-16 12:15:13.416  7048  7729 I bt_userial_mct: exiting userial_read_thread
08-16 12:15:13.416  7048  7729 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 12:15:13.417  7048  7673 W bt-btif : ag scb idx 1 not allocated
08-16 12:15:13.417  7048  7673 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 12:15:13.418  7048  7673 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 12:15:13.418  7048  7673 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 12:15:13.418  7048  7673 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 12:15:13.418  7048  7673 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 12:15:13.418  7048  7673 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 12:15:13.418  7048  7673 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 12:15:13.418  7048  7673 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 12:15:13.418  7048  7673 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 12:15:13.418  7048  7673 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 12:15:13.418  7048  7673 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 12:15:13.418  7048  7673 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 12:15:13.418  7048  7673 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 12:15:13.418  7048  7673 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-16 12:15:13.418  7048  7673 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 12:15:13.418  7048  7673 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 12:15:13.418  7048  7673 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 12:15:13.418  7048  7673 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 12:15:13.418  7048  7673 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 12:15:13.419  7048  7673 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 12:15:13.419  7048  7621 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,08-16 12:15:13.420  7048  7675 I bt_vendor: hw_epilog_process
08-16 12:15:13.421  7048  7621 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 12:15:13.421  7048  7621 D bt_userial_mct: userial_close
08-16 12:15:13.421  7048  7621 E bt_userial_mct: pthread_join() FAILED result:3
08-16 12:15:13.421  7048  7621 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-16 12:15:13.426  7048  7621 D bt_hci_bdroid: set_power 0
,08-16 12:15:13.426  7048  7621 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 12:15:13.426  7048  7621 I bt_vendor: bluetooth satus is on
08-16 12:15:13.426  7048  7621 I bt_vendor: bt-vendor : resetting BT status
08-16 12:15:13.426  7048  7621 I bt_vendor: Starting hciattach daemon
08-16 12:15:13.426  7048  7621 I bt_vendor: try to set false,
,08-16 12:15:13.433  7048  7621 I bt_vendor: Starting hciattach daemon
08-16 12:15:13.433  7048  7621 I bt_vendor: try to set false
08-16 12:15:13.436  7048  7621 I bt_vendor: cleanup
08-16 12:15:13.437  7048  7673 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 12:15:13.437  7048  7621 I GKI_LINUX: GKI_exit_task 0 done
08-16 12:15:13.437  7048  7621 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 12:15:13.438  7048  7617 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 12:15:13.446  7048  7048 D HeadsetService: Received stop request...Stopping profile...
,08-16 12:15:13.450  7048  7617 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 12:15:13.451  7048  7048 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 12:15:13.451  7048  7048 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 12:15:13.451  7048  7048 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9fee8cb
08-16 12:15:13.451  7048  7651 D HeadsetStateMachine: Exit Disconnected: -1
08-16 12:15:13.454  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-16 12:15:13.454  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-16 12:15:13.454  1837  1837 D BluetoothHeadset: Proxy object disconnected
08-16 12:15:13.456  7048  7048 D A2dpService: Received stop request...Stopping profile...
08-16 12:15:13.456  7048  7665 D A2dpStateMachine: Exit Disconnected: -1
08-16 12:15:13.457  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-16 12:15:13.457  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 12:15:13.458  7048  7048 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-16 12:15:13.461  7048  7048 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 12:15:13.461  7048  7048 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 12:15:13.461  7048  7048 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9fee8cb
,08-16 12:15:13.466  7048  7048 D HidService: Received stop request...Stopping profile...
08-16 12:15:13.466  7048  7048 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9fee8cb
08-16 12:15:13.468  7048  7048 D HealthService: Received stop request...Stopping profile...
08-16 12:15:13.468  7048  7048 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9fee8cb
08-16 12:15:13.469  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-16 12:15:13.469  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 12:15:13.470  7048  7048 D PanService: Received stop request...Stopping profile...
08-16 12:15:13.472  7048  7048 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9fee8cb
08-16 12:15:13.474  7048  7048 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 12:15:13.477  7048  7048 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 12:15:13.477  7048  7048 D BtGatt.GattService: stop()
08-16 12:15:13.477  7048  7048 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 12:15:13.478  7048  7048 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9fee8cb
08-16 12:15:13.480  7048  7048 D BluetoothMapService: Received stop request...Stopping profile...
08-16 12:15:13.480  7048  7048 D BluetoothMapService: stop()
08-16 12:15:13.481  7048  7048 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 12:15:13.481  7048  7048 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 12:15:13.481  7048  7048 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9fee8cb
08-16 12:15:13.482  7048  7048 V BluetoothMapService: Handler(): got msg=4
08-16 12:15:13.482  7048  7048 D BluetoothMapService: MAP Service closeService in
08-16 12:15:13.483  7048  7048 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 12:15:13.483  7048  7048 V BluetoothMapService: MAP Service closeService out
08-16 12:15:13.484  7048  7617 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 12:15:13.485  7048  7617 D BluetoothAdapterProperties: Setting state to 10
08-16 12:15:13.485  7048  7617 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 12:15:13.486  1036  1119 D BluetoothManagerService: Message: 60
08-16 12:15:13.486  1036  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 12:15:13.486  1036  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
,08-16 12:15:13.489  7048  7617 I BluetoothAdapterState: Entering OffState
08-16 12:15:13.490  6942  7737 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:15:13.491  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:15:13.492  1036  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:15:13.492  6942  7737 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 12:15:13.493  7048  7048 D HeadsetStateMachine: Unbinding service...
08-16 12:15:13.494  7048  7048 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 12:15:13.494  7048  7048 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 12:15:13.494  7048  7048 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 12:15:13.494  7048  7048 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 12:15:13.494  7048  7048 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 12:15:13.494  7048  7048 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 12:15:13.494  7048  7048 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 12:15:13.496  1837  2436 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:15:13.498  6942  7737 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 12:15:13.504  7048  7048 I BluetoothA2dpServiceJni: cleanupNative
08-16 12:15:13.504  7048  7666 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 12:15:13.505  7048  7048 I GKI_LINUX: GKI_exit_task 2 done
08-16 12:15:13.505  7048  7048 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 12:15:13.506  1837  2438 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:15:13.508  6942  7737 D BluetoothPan: onBluetoothStateChange on: false
08-16 12:15:13.509  7048  7048 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 12:15:13.509  7048  7048 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-16 12:15:13.512  7048  7048 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 12:15:13.512  7048  7048 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 12:15:13.512  7048  7048 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 12:15:13.513  1036  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 12:15:13.513  6942  7737 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 12:15:13.514  7048  7048 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 12:15:13.514  7048  7048 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 12:15:13.516  6942  7737 D BluetoothMap: onBluetoothStateChange: up=false
08-16 12:15:13.518  7048  7048 D BluetoothMapService: cleanup()
08-16 12:15:13.518  7048  7048 D BluetoothMapService: MAP Service closeService in
08-16 12:15:13.518  7048  7048 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 12:15:13.518  7048  7048 V BluetoothMapService: MAP Service closeService out
08-16 12:15:13.519  1036  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 12:15:13.519  1036  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-16 12:15:13.522  1036  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 12:15:13.522  1036  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 12:15:13.522  1036  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3d1b4fba mBinding = false
,08-16 12:15:13.525  1036  1119 D BluetoothManagerService: Sending unbind request.
08-16 12:15:13.530  7048  7621 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-16 12:15:13.530  7048  7048 I GKI_LINUX: GKI_exit_task 1 done
08-16 12:15:13.530  7048  7048 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 12:15:13.531  7048  7048 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 12:15:13.531  7048  7048 I art     : --- WEIRD: removing null entry 248
08-16 12:15:13.531  7048  7048 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-16 12:15:13.531  7048  7048 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-16 12:15:13.532  7048  7048 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-16 12:15:13.534  1036  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-16 12:15:13.538  7048  7048 I art     : System.exit called, status: 0
08-16 12:15:13.538  7048  7048 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 12:15:13.571   315  2144 V AudioFlinger: 7048 died, releasing its sessions
08-16 12:15:13.571   315  2144 V AudioFlinger:  pid 1837 @ 0
08-16 12:15:13.571   315  2144 V AudioFlinger:  pid 3288 @ 1
08-16 12:15:13.571   315  2144 V AudioFlinger:  pid 3288 @ 2
,08-16 12:15:13.574  6942  6942 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-16 12:15:13.574  1926  1926 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
,08-16 12:15:13.574  1926  2118 D LGBluetoothAPIService: Message: 101
08-16 12:15:13.574  1926  2118 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-16 12:15:13.575  1926  2118 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-16 12:15:13.575  1926  2118 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-16 12:15:13.655  1036  1637 I ActivityManager: Process com.android.bluetooth (pid 7048) has died
08-16 12:15:13.656  1036  1637 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-16 12:15:13.656  1036  1637 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,08-16 12:15:13.663  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 12:15:13.664  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-16 12:15:13.664  1926  2118 D LGBluetoothAPIService: Message: 2
08-16 12:15:13.664  1926  2118 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-16 12:15:13.666  6942  6942 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-16 12:15:13.666  6942  6942 D LGBluetoothEventManager: [BTUI] clear device connection state
08-16 12:15:13.666  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:15:13.668  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:15:13.672  6942  6942 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 12:15:13.683  1587  1587 D BluetoothAdapter: 363305074: getState() :  mService = null. Returning STATE_OFF
,08-16 12:15:13.684  1587  1587 D BluetoothAdapter: 363305074: getState() :  mService = null. Returning STATE_OFF
08-16 12:15:13.750  1036  1560 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7990 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-16 12:15:13.752  6942  6942 D DockEventReceiver: finishStartingService: stopping service
,08-16 12:15:13.837  7990  7990 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-16 12:15:13.838  7990  7990 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 12:15:13.838  7990  7990 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-16 12:15:13.839  7990  7990 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 12:15:13.862  7990  7990 D BluetoothAdapterApp: Loading JNI Library
,08-16 12:15:13.900  7990  7990 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@27438253 Instance Count = 1
,08-16 12:15:13.907  7990  7990 D BluetoothAdapterApp: onCreate
,08-16 12:15:13.934  7990  7990 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-16 12:15:13.935  7990  7990 D ProfileConfigQcom: Adding HeadsetService
08-16 12:15:13.936  7990  7990 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-16 12:15:13.936  7990  7990 D ProfileConfigQcom: Adding A2dpService
08-16 12:15:13.937  7990  7990 D ProfileConfigQcom: [BTUI] HidService is supported
08-16 12:15:13.937  7990  7990 D ProfileConfigQcom: Adding HidService
,08-16 12:15:13.938  7990  7990 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 12:15:13.939  7990  7990 D ProfileConfigQcom: Adding HealthService
,08-16 12:15:13.939  7990  7990 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-16 12:15:13.941  7990  7990 D ProfileConfigQcom: [BTUI] PanService is supported
08-16 12:15:13.942  7990  7990 D ProfileConfigQcom: Adding PanService
08-16 12:15:13.942  7990  7990 D ProfileConfigQcom: [BTUI] GattService is supported
08-16 12:15:13.943  7990  7990 D ProfileConfigQcom: Adding GattService
08-16 12:15:13.943  7990  7990 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 12:15:13.944  7990  7990 D ProfileConfigQcom: Adding BluetoothMapService
08-16 12:15:13.945  7990  7990 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 12:15:13.946  7990  7990 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 12:15:13.948  7990  7990 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:13.948  7990  7990 V BluetoothPbapReceiver: ***********state = 10
08-16 12:15:13.950  7990  7990 V LGMDMManagerInternal: Create singleton instance
,08-16 12:15:14.073  2168  2168 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 12:15:14.074  7990  7990 D LGBluetoothAPIServer: [BTUI] onCreate()
08-16 12:15:14.074  7990  7990 D LGBluetoothAPIServer: [BTUI] onBind()
08-16 12:15:14.075  6942  6942 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-16 12:15:14.076  1926  1926 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 12:15:14.077  1926  2118 D LGBluetoothAPIService: Message: 100
,08-16 12:15:14.077  1926  2118 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-16 12:15:14.090  6942  6942 D BluetoothPermissionRequest: onReceive
08-16 12:15:14.092  6942  6942 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 12:15:14.092  6942  6942 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-16 12:15:14.094  6942  6942 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 12:15:14.100  7990  7990 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-16 12:15:14.104  7990  7990 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:14.108  7990  7990 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 12:15:14.109  7990  7990 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 12:15:14.109  7990  7990 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 12:15:14.110  7990  7990 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:14.110  7990  7990 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-16 12:15:14.119  7680  7680 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-16 12:15:14.286  7713  7769 D UEI.SmartControl: Internal timer expired: 1
08-16 12:15:14.286  7713  7769 D UEI.SmartControl: unbind internal service
,08-16 12:15:14.306  7713  7713 D UEI.SmartControl: Service.onUnbind: IControl
,08-16 12:15:14.309  7713  7713 D UEI.SmartControl: Service.onDestroy
08-16 12:15:14.309  7713  7713 D UEI.SmartControl: Lock is in USE false
08-16 12:15:14.309  7713  7713 D UEI.SmartControl: unbind internal service
08-16 12:15:14.310  7713  7713 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2be9afc1
08-16 12:15:14.310  7713  7713 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-16 12:15:14.310  7713  7713 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-16 12:15:14.310  7713  7713 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-16 12:15:14.310  7713  7713 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-16 12:15:14.310  7713  7713 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-16 12:15:14.310  7713  7713 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-16 12:15:14.310  7713  7713 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-16 12:15:14.310  7713  7713 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-16 12:15:14.311  7713  7713 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:15:14.311  7713  7713 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 12:15:14.311  7713  7713 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 12:15:14.311  7713  7713 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:15:14.311  7713  7713 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 12:15:14.311  7713  7713 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 12:15:14.311  7713  7713 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 12:15:14.311  7713  7713 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2be9afc1
08-16 12:15:14.314  7713  7713 D serial_port: close(fd = 25)
08-16 12:15:14.317  7713  7713 I UEI.SmartControl: Serial port is closed.
08-16 12:15:14.317  7713  7713 I UEI.SmartControl: Serial port is closed.
08-16 12:15:14.317  7713  7713 D UEI.SmartControl: Blaster closed
08-16 12:15:14.317  7713  7713 D UEI.SmartControl: Shut down QS...
08-16 12:15:14.318  7713  7713 D UEI.SmartControl: Stopping QS lib
08-16 12:15:14.318  7713  7713 D UEI.SmartControl: QS lib stop result = true
08-16 12:15:14.318  7713  7713 D UEI.SmartControl: Stopped QS lib
08-16 12:15:14.318  7713  7713 D UEI.SmartControl: Stopped file observer...
08-16 12:15:14.319  7713  7713 D UEI.SmartControl: QS shutdown complete
,08-16 12:15:17.633  6814  6884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:15:17.641  1036  1907 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:15:17.642  1036  1907 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-16 12:15:17.657  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 12:15:17.657  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 12:15:17.657  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-16 12:15:17.661  1036  1119 D BluetoothManagerService: Message: 1
08-16 12:15:17.661  1036  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-16 12:15:17.690  1036  1119 D BluetoothManagerService: Message: 20
08-16 12:15:17.691  1036  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a913f9d:true
,08-16 12:15:17.694  7990  7990 D BluetoothAdapterState: make
08-16 12:15:17.699  7990  7990 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 12:15:17.699  7990  7990 I bluedroid-qcom: init
08-16 12:15:17.700  7990  8020 I BluetoothAdapterState: Entering OffState
08-16 12:15:17.701  7990  7990 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 12:15:17.701  7990  7990 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 12:15:17.701  7990  7990 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 12:15:17.701  7990  7990 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 12:15:17.701  7990  7990 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 12:15:17.703  7990  7990 I bluedroid-qcom: get_profile_interface socket
08-16 12:15:17.703  7990  7990 I bluedroid-qcom: get_profile_interface map_client
,08-16 12:15:17.708  7990  8024 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 12:15:17.702  8023  8023 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 12:15:17.702  8023  8023 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:15:17.722  8023  8023 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 12:15:17.722  8023  8023 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 12:15:17.722  8023  8023 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-16 12:15:17.727  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-16 12:15:17.727  1036  1119 D BluetoothManagerService: Message: 40
08-16 12:15:17.727  1036  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 12:15:17.728  7990  8006 I bluedroid-qcom: config_hci_snoop_log
08-16 12:15:17.729  1036  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 12:15:17.729  1036  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 12:15:17.732  7990  8024 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 12:15:17.732  8023  8023 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-16 12:15:17.735  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 12:15:17.737  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,08-16 12:15:17.739  7990  8024 D BluetoothAdapterProperties: Name is: G3
08-16 12:15:17.740  8023  8023 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 12:15:17.740  8023  8023 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-16 12:15:17.746  7990  8020 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-16 12:15:17.746  7990  8020 D BluetoothAdapterProperties: Setting state to 11
08-16 12:15:17.746  7990  8020 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 12:15:17.748  7990  8020 I LGBluetoothServiceJni: classInitNative: succeeds
08-16 12:15:17.752  1036  1119 D BluetoothManagerService: Message: 60
08-16 12:15:17.752  1036  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 12:15:17.752  1036  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-16 12:15:17.756  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:17.757  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 12:15:17.762  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:15:17.764  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:15:17.769  7990  8020 D BluetoothBondStateMachine: make
08-16 12:15:17.770  6942  6942 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-16 12:15:17.774  7990  7990 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 12:15:17.774  7990  7990 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-16 12:15:17.774  7990  7990 V BluetoothPbapReceiver: ***********state = 11
08-16 12:15:17.794  2168  2168 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 12:15:17.797  7990  8025 I BluetoothBondStateMachine: StableState(): Entering Off State
08-16 12:15:17.798  7990  8020 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@47928a8
08-16 12:15:17.798  7990  8020 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 12:15:17.799  7990  8020 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@47928a8
08-16 12:15:17.799  7990  8020 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 12:15:17.800  7990  8020 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-16 12:15:17.805  7990  8020 E BluetoothAdapterService: File transfer profiles supported!!
08-16 12:15:17.811  6942  6942 D BluetoothPermissionRequest: onReceive
,08-16 12:15:17.822  6942  6942 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 12:15:17.823  7990  7990 D HeadsetService: Received start request. Starting profile...
08-16 12:15:17.823  7990  7990 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 12:15:17.824  7990  7990 D LGBluetoothHfpAdapter: Version 1.6
08-16 12:15:17.826  7990  8020 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 12:15:17.829  7990  7990 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 12:15:17.830  7990  7990 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 12:15:17.830  7990  7990 D HeadsetStateMachine: make
08-16 12:15:17.832  7990  8020 E BluetoothAdapterService: File transfer profiles supported!!
08-16 12:15:17.838  7990  8020 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 12:15:17.844  7990  8020 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 12:15:17.849  7990  8020 E BluetoothAdapterService: File transfer profiles supported!!
08-16 12:15:17.854  7990  8020 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 12:15:17.871  7990  7990 D LgDataFeature: LgDataFeature() Constructor: none
08-16 12:15:17.871  7990  7990 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 12:15:17.873  7990  8020 V LGMDMManager: Create singleton instance
,08-16 12:15:17.875  7990  8020 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 12:15:17.877  7990  7990 D HeadsetStateMachine: max_hf_connections = 1
08-16 12:15:17.877  7990  7990 I bluedroid-qcom: get_profile_interface handsfree
08-16 12:15:17.879  7990  7990 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-16 12:15:17.880   315  1369 V AudioPolicyService: registerClient() client 0xb1005240, uid 1002
08-16 12:15:17.880   315  2144 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-16 12:15:17.880   315  2144 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 12:15:17.880   315  2144 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 12:15:17.880  7990  7990 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 12:15:17.881   315  2136 V AudioFlinger: registerClient() client 0xb55815b0, pid 7990
08-16 12:15:17.881   315  1363 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 12:15:17.881   315  1363 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 12:15:17.882  7990  8006 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 12:15:17.882  1587  2083 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 12:15:17.882  1587  2083 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 12:15:17.882  3288  3305 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 12:15:17.882  3288  3305 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 12:15:17.882  1036  1060 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 12:15:17.882  1036  1060 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 12:15:17.882  1837  1852 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 12:15:17.882  1837  1852 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 12:15:17.882   315  1364 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 12:15:17.882  7990  8006 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-16 12:15:17.882   315  1364 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 12:15:17.882  1587  3156 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 12:15:17.882  1587  3156 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 12:15:17.883  1837  1853 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 12:15:17.883  1837  1853 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 12:15:17.883  3288  3304 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 12:15:17.883  3288  3304 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 12:15:17.883  1036  1771 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 12:15:17.883  1036  1771 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 12:15:17.883  7990  7990 V ToneGenerator: Create Track: 0xb4928a80
08-16 12:15:17.883  7990  7990 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 12:15:17.883  7990  7990 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 12:15:17.883   315  1370 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 12:15:17.883   315  1370 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-16 12:15:17.883   315  1370 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 12:15:17.883   315  1370 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 12:15:17.883  7990  8005 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 12:15:17.883  7990  8005 V AudioSystem: ioConfigChanged() new output samplingRate 48000, forma,t 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 12:15:17.884   315  2144 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 12:15:17.884   315  1369 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 12:15:17.884   315  1369 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 12:15:17.884   315  1369 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 12:15:17.884   315  1369 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 12:15:17.884  7990  7990 V AudioSystem: getLatency() output 2, latency 50
08-16 12:15:17.884  7990  7990 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 12:15:17.884  7990  7990 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 12:15:17.884   315  2136 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 12:15:17.884   315  2136 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 12:15:17.884   315  2136 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 12:15:17.884   315  2136 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 12:15:17.884   315  2136 V AudioFlinger: createTrack() lSessionId: 23
08-16 12:15:17.886  7990  7990 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 12:15:17.886   315  2136 V AudioFlinger: acquiring 23 from 7990, for 7990
08-16 12:15:17.886   315  2136 V AudioFlinger:  added new entry for 23
08-16 12:15:17.886  7990  7990 V ToneGenerator: ToneGenerator INIT OK, time: 387931
08-16 12:15:17.886  7990  7990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@47928a8
,08-16 12:15:17.887  7990  8042 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-16 12:15:17.887  7990  8042 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 12:15:17.888  7990  8042 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 12:15:17.888  7990  8042 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-16 12:15:17.888   315   315 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7990
08-16 12:15:17.888   315   315 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 12:15:17.888   315   315 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 12:15:17.888   315   315 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 12:15:17.888   315   315 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 12:15:17.888   315   315 V voice   : voice_set_parameters: exit with code(0)
08-16 12:15:17.888   315   315 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 12:15:17.888   315   315 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 12:15:17.889   315   315 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 12:15:17.889   315   315 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 12:15:17.889   315   315 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 12:15:17.889   315   315 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 12:15:17.889  7990  8042 V ToneGenerator: ToneGenerator destructor
08-16 12:15:17.889  7990  8042 V ToneGenerator: stopTone
08-16 12:15:17.889  7990  8042 V ToneGenerator: Delete Track: 0xb4928a80
08-16 12:15:17.889  7990  7990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@47928a8
08-16 12:15:17.890  7990  8042 V AudioTrack: ~AudioTrack, releasing session id from 7990 on behalf of 7990
08-16 12:15:17.890   315  1370 V AudioFlinger: releasing 23 from 7990 for 7990
08-16 12:15:17.890   315  1370 V AudioFlinger:  decremented refcount to 0
08-16 12:15:17.890   315  1370 V AudioFlinger: purging stale effects
08-16 12:15:17.890   315  1370 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 12:15:17.890   315  1370 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 12:15:17.890   315  1270 V AudioPolicyService: AudioCommandThread() waking up
08-16 12:15:17.890   315  1270 V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 12:15:17.891   315  1270 V AudioPolicyManager: releaseOutput() 2
08-16 12:15:17.891   315  1270 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 12:15:17.891   315  1370 V AudioFlinger: PlaybackThread::Track destructor
08-16 12:15:17.891   315  1370 V AudioFlinger: removeClient_l() pid 7990, calling pid 315
08-16 12:15:17.892  1036  1872 W Process : Unable to open /proc/8044/status
08-16 12:15:17.893  7990  7990 D A2dpService: Received start request. Starting profile...
08-16 12:15:17.894  7990  7990 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 12:15:17.895  7990  7990 V Avrcp   : make
08-16 12:15:17.896  7990  7990 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-16 12:15:17.896  7990  7990 I bluedroid-qcom: get_profile_interface avrcp
08-16 12:15:17.905  7990  7990 V AudioManager: registerRemoteController: size of Media player list: 0
08-16 12:15:17.907  7990  7990 E AudioManager: No RCC entry present to update
08-16 12:15:17.907  7990  7990 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 12:15:17.910  7990  7990 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-16 12:15:17.912  7990  7990 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-16 12:15:17.912  7990  7990 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-16 12:15:17.916  7990  7990 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 12:15:18.031  1036  1980 V SIM_STK : Menu title from STK is T-Mobile
08-16 12:15:18.031  1036  1980 V SIM_STK : Menu title from STK is T-Mobile
,08-16 12:15:18.110  1036  1871 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 12:15:18.117  7990  7990 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 12:15:18.121  7990  7990 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 12:15:18.122  7990  7990 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 12:15:18.122  7990  7990 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 12:15:18.122  7990  7990 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 12:15:18.122  7990  7990 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 12:15:18.122  7990  7990 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 12:15:18.122  7990  7990 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 12:15:18.122  7990  7990 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 12:15:18.122  7990  7990 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 12:15:18.122  7990  7990 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 12:15:18.123  7990  7990 I BluetoothA2dpServiceJni: classInitNative
08-16 12:15:18.123  7990  7990 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 12:15:18.123  7990  7990 D A2dpStateMachine: make
,08-16 12:15:18.127  7990  7990 I bluedroid-qcom: get_profile_interface a2dp
,08-16 12:15:18.127  7990  8048 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 12:15:18.130  7990  7990 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-16 12:15:18.130  7990  7990 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-16 12:15:18.131  7990  7990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@47928a8
08-16 12:15:18.131  7990  8047 D A2dpStateMachine: Enter Disconnected: -2
08-16 12:15:18.132  7990  7990 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 12:15:18.135  7990  7990 D HidService: Received start request. Starting profile...
08-16 12:15:18.135  7990  7990 I bluedroid-qcom: get_profile_interface hidhost
08-16 12:15:18.135  7990  7990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@47928a8
,08-16 12:15:18.140  7990  7990 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 12:15:18.145  7990  7990 D HealthService: Received start request. Starting profile...
08-16 12:15:18.149  7990  7990 I bluedroid-qcom: get_profile_interface health
08-16 12:15:18.150  7990  7990 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-16 12:15:18.150  7990  7990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@47928a8
,08-16 12:15:18.153  7990  7990 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 12:15:18.157  7990  7990 D PanService: Received start request. Starting profile...
08-16 12:15:18.157  7990  7990 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 12:15:18.157  7990  7990 I bluedroid-qcom: get_profile_interface pan
,08-16 12:15:18.168  7990  7990 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-16 12:15:18.168  7990  7990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@47928a8
08-16 12:15:18.169  7990  7990 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-16 12:15:18.175  7990  7990 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 12:15:18.176  7990  7990 D BtGatt.GattService: Received start request. Starting profile...
08-16 12:15:18.176  7990  7990 D BtGatt.GattService: start()
08-16 12:15:18.176  7990  7990 I bluedroid-qcom: get_profile_interface gatt
08-16 12:15:18.176  7990  7990 D BtGatt.AdvertiseManager: advertise manager created
08-16 12:15:18.185  7990  7990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@47928a8
08-16 12:15:18.187  7990  7990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@47928a8
08-16 12:15:18.188  7990  7990 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
,08-16 12:15:18.189  7990  7990 V BluetoothMapService: BluetoothMapBinder()
08-16 12:15:18.190  7990  7990 D BluetoothMapService: Received start request. Starting profile...
08-16 12:15:18.190  7990  7990 D BluetoothMapService: start()
08-16 12:15:18.197  7990  7990 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 12:15:18.197  7990  7990 D BluetoothMapEmailAppObserver: createReceiver()
08-16 12:15:18.199  7990  7990 D BluetoothMapEmailAppObserver: initObservers()
08-16 12:15:18.199  7990  7990 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-16 12:15:18.208  7990  7990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@47928a8
,08-16 12:15:18.209  7990  7990 D HeadsetStateMachine: Proxy object connected
08-16 12:15:18.210  7990  7990 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 12:15:18.210  7990  7990 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-16 12:15:18.212  7990  8042 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 12:15:18.212  7990  8042 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 12:15:18.213  7990  8042 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-16 12:15:18.217  7990  7990 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 12:15:18.219  7990  7990 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:18.224  7990  7990 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 12:15:18.229  7990  7990 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 12:15:18.233  7990  7990 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 12:15:18.233  7990  7990 V PanService: [BTUI] SIM Extra State :ABSENT
08-16 12:15:18.237  7990  7990 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 12:15:18.240  7990  7990 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-16 12:15:18.240  7990  7990 V BluetoothMapService: Handler(): got msg=1
08-16 12:15:18.243  7990  7990 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 12:15:18.243  7990  7990 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 12:15:18.243  7990  7990 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 12:15:18.243  7990  7990 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:18.243  7990  7990 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-16 12:15:18.244  7990  8020 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 12:15:18.244  7990  8020 I bluedroid-qcom: enable
08-16 12:15:18.245  7990  8020 I bt_hci_bdroid: init
08-16 12:15:18.246  7990  8062 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 12:15:18.249  7990  8020 I bt_vendor: bt-vendor : init
08-16 12:15:18.249  7990  8020 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 12:15:18.249  7990  8020 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 12:15:18.249  7990  8020 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 12:15:18.249  7990  8020 D bt_userial_mct: userial_init
,08-16 12:15:18.252  7990  8062 I bt-btu  : btu_task pending for preload complete event
,08-16 12:15:18.252  7990  8020 D bt_hci_bdroid: set_power 1
08-16 12:15:18.252  7990  8020 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 12:15:18.252  7990  8020 I bt_vendor: Starting hciattach daemon
08-16 12:15:18.252  7990  8020 I bt_vendor: try to set true
08-16 12:15:18.241  8065  8065 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:15:18.251  8065  8065 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:15:18.281  8066  8066 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 12:15:18.352  8072  8072 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 12:15:18.366  8073  8073 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-16 12:15:18.392  8075  8075 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 12:15:18.408  8076  8076 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-16 12:15:18.419  8077  8077 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 12:15:18.432  8078  8078 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-16 12:15:18.454  8080  8080 I libmdmdetect: ESOC framework not supported
,08-16 12:15:18.456  8080  8080 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-16 12:15:18.465  8080  8080 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-16 12:15:18.465  8080  8080 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-16 12:15:18.465  8080  8080 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-16 12:15:18.465  8080  8080 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 12:15:18.465  8080  8080 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-16 12:15:18.465  8080  8080 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-16 12:15:18.465  8080  8080 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-16 12:15:18.509  8080  8081 E QC-QMI  : qmi_client [8080] 15: failed to locate client data
08-16 12:15:18.510   441   441 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-16 12:15:18.510   441   441 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-16 12:15:18.567  8083  8083 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 12:15:18.580  8084  8084 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-16 12:15:18.606  7990  8020 I bt_vendor: bluetooth satus is on
,08-16 12:15:18.606  7990  8020 D bt_hci_bdroid: preload
08-16 12:15:18.606  7990  8064 D bt_userial_mct: userial_open(port:0)
08-16 12:15:18.606  7990  8064 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-16 12:15:18.610  7990  8064 I bt_vendor: Done intiailizing UART
08-16 12:15:18.610  7990  8064 I bt_vendor: Done intiailizing UART
08-16 12:15:18.610  7990  8064 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 12:15:18.610  7990  8064 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 12:15:18.611  7990  8062 I bt-btu  : btu_task received preload complete event
08-16 12:15:18.611  7990  8086 D bt_userial_mct: Entering userial_read_thread()
,08-16 12:15:18.611  7990  8062 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 12:15:18.612  7990  8062 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-16 12:15:18.614  7990  8062 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-16 12:15:18.618  7990  8062 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 12:15:18.618  7990  8062 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 12:15:18.618  7990  8062 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 12:15:18.618  7990  8062 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 12:15:18.618  7990  8062 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 12:15:18.618  7990  8062 I         : BTE_InitTraceLevels -- TRC_A2D
,08-16 12:15:18.618  7990  8062 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-16 12:15:18.618  7990  8062 I         : BTE_InitTraceLevels -- TRC_BTM
,08-16 12:15:18.618  7990  8062 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 12:15:18.618  7990  8062 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 12:15:18.618  7990  8062 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 12:15:18.618  7990  8062 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 12:15:18.618  7990  8062 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 12:15:18.618  7990  8062 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 12:15:18.618  7990  8062 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-16 12:15:18.618  7990  8062 I         : BTE_InitTraceLevels -- TRC_BTIF
08-16 12:15:18.720  7990  8062 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled,
08-16 12:15:18.721  7990  8062 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa021c061 ,
08-16 12:15:18.721  7990  8062 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa021c061 
,08-16 12:15:18.757  7990  8024 E bt-btif : Calling BTA_HhEnable
08-16 12:15:18.757  7990  8024 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-16 12:15:18.757  7990  8024 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-16 12:15:18.760  7990  8062 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-16 12:15:18.760  7990  8062 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-16 12:15:18.760  7990  8062 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 12:15:18.760  7990  8062 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 12:15:18.760  7990  8062 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-16 12:15:18.762  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 12:15:18.762  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 12:15:18.763  7990  8024 D BluetoothAdapterProperties: Name is: G3
08-16 12:15:18.764  7990  8024 D BluetoothAdapterProperties: Scan Mode:20
08-16 12:15:18.764  7990  8024 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 12:15:18.764  7990  8024 D bt_hci_bdroid: postload
08-16 12:15:18.765  7990  8064 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 12:15:18.765  7990  8024 D bte_conf: Device ID record 1 : primary
08-16 12:15:18.766  7990  8024 D bte_conf:   vendorId            = 00c4
08-16 12:15:18.766  7990  8024 D bte_conf:   vendorIdSource      = 0001
08-16 12:15:18.766  7990  8024 D bte_conf:   product             = 13a1
08-16 12:15:18.766  7990  8024 D bte_conf:   version             = 1000
08-16 12:15:18.766  7990  8024 D bte_conf:   clientExecutableURL = 
08-16 12:15:18.766  7990  8024 D bte_conf:   serviceDescription  = 
08-16 12:15:18.766  7990  8024 D bte_conf:   documentationURL    = 
08-16 12:15:18.766  7990  8024 D bte_conf: bte_load_did_conf no section named DID2.
08-16 12:15:18.766  7990  8062 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-16 12:15:18.767  7990  8064 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 12:15:18.770  7990  8020 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-16 12:15:18.770  7990  8020 D BluetoothAdapterProperties: ScanMode =  20
08-16 12:15:18.770  7990  8020 D BluetoothAdapterProperties: State =  11
08-16 12:15:18.770  7990  8020 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
,08-16 12:15:18.776  7990  8020 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 12:15:18.776  7990  8020 D BluetoothAdapterProperties: Setting state to 12
08-16 12:15:18.776  7990  8020 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 12:15:18.777  7990  8024 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 12:15:18.777  7990  8024 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 12:15:18.771  8091  8091 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:15:18.771  8091  8091 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:15:18.783  1036  1119 D BluetoothManagerService: Message: 60
08-16 12:15:18.783  1036  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 12:15:18.784  1036  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-16 12:15:18.784  7990  8064 D bt_hci_bdroid: Used up Tx Cmd credits
,08-16 12:15:18.796  7990  8064 D bt_hci_bdroid: Used up Tx Cmd credits
,08-16 12:15:18.799  7990  8086 E bt_mct  : hci lib postload completed
08-16 12:15:18.807  7990  8062 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 12:15:18.807  7990  8062 W bt-smp  : Plain text(LSB ~ MSB) = 71 75 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 12:15:18.807  7990  8062 W bt-smp  : Encrypted text(LSB ~ MSB) = b2 4c 9e 24 dd c2 dc 7c c0 90 15 f1 28 4d 00 db 
08-16 12:15:18.809  7990  8062 W bt-btm  : Stopping oneshot timer
,08-16 12:15:18.820  7990  8024 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 12:15:18.820  7990  8024 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-16 12:15:18.823  7990  8020 I BluetoothAdapterState: Entering On State
08-16 12:15:18.829  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:15:18.829  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:15:18.829  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:15:18.829  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:15:18.829  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:15:18.829  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:15:18.829  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:15:18.829  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:15:18.836  7990  8062 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 12:15:18.836  7990  8062 W bt-smp  : Plain text(LSB ~ MSB) = f7 33 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 12:15:18.836  7990  8062 W bt-smp  : Encrypted text(LSB ~ MSB) = 09 25 f5 82 72 37 22 d8 58 f9 28 8b 08 85 15 15 
,08-16 12:15:18.838  7990  8062 W bt-btm  : Stopping oneshot timer
08-16 12:15:18.840  6814  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:15:18.852  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:15:18.852  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:15:18.852  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:15:18.852  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:15:18.852  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:15:18.852  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:15:18.852  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:15:18.852  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:15:18.858  6814  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:15:18.860  7990  8062 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 12:15:18.860  7990  8062 W bt-smp  : Plain text(LSB ~ MSB) = cc dc 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 12:15:18.860  7990  8062 W bt-smp  : Encrypted text(LSB ~ MSB) = e3 09 e1 32 60 a2 b2 ab 16 00 cd 34 89 63 b0 c0 
08-16 12:15:18.860  7990  8062 W bt-btm  : Stopping oneshot timer
08-16 12:15:18.870  7990  8020 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 12:15:18.870  7990  8020 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 12:15:18.870  7990  8020 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-16 12:15:18.874  7990  8020 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-16 12:15:18.875  7990  8020 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-16 12:15:18.884  7990  8062 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 12:15:18.884  7990  8062 W bt-smp  : Plain text(LSB ~ MSB) = 68 4a 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 12:15:18.884  6942  6965 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 12:15:18.884  7990  8062 W bt-smp  : Encrypted text(LSB ~ MSB) = 94 53 7c ee 8a 2d f1 5b dc a1 82 ed 62 1a c8 dc 
08-16 12:15:18.885  7990  8062 W bt-btm  : Stopping oneshot timer
,08-16 12:15:18.900  1837  2438 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 12:15:18.903  1837  1837 D BluetoothHeadset: Proxy object connected
08-16 12:15:18.903  1036  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 12:15:18.904  6942  6942 D BluetoothHeadset: Proxy object connected
08-16 12:15:18.904  6942  6942 D HeadsetProfile: Bluetooth service connected
,08-16 12:15:18.907  7990  8062 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 12:15:18.907  7990  8062 W bt-smp  : Plain text(LSB ~ MSB) = 2b c2 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 12:15:18.907  7990  8062 W bt-smp  : Encrypted text(LSB ~ MSB) = 35 02 84 8d bb f9 ec 30 c5 c3 10 b4 63 26 b3 92 
08-16 12:15:18.907  7990  8062 W bt-btm  : Stopping oneshot timer
08-16 12:15:18.908  1036  1036 D BluetoothHeadset: Proxy object connected
08-16 12:15:18.911  6942  6966 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 12:15:18.913  8107  8107 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-16 12:15:18.917  6942  6942 D BluetoothInputDevice: Proxy object connected
08-16 12:15:18.917  6942  6942 D HidProfile: Bluetooth service connected
,08-16 12:15:18.919  1837  2438 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 12:15:18.923  1837  1837 D BluetoothHeadset: Proxy object connected
08-16 12:15:18.923  6942  7737 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 12:15:18.928  1837  2436 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 12:15:18.928  6942  6942 D BluetoothA2dp: Proxy object connected
,08-16 12:15:18.928  6942  6942 D A2dpProfile: Bluetooth service connected
08-16 12:15:18.931  1837  1837 D BluetoothHeadset: Proxy object connected
08-16 12:15:18.931  6942  6966 D BluetoothPan: onBluetoothStateChange on: true
08-16 12:15:18.931  6942  6966 D BluetoothPan: onBluetoothStateChange call bindService
08-16 12:15:18.933  1036  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 12:15:18.934  6942  6965 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 12:15:18.934  1036  1036 D BluetoothA2dp: Proxy object connected
08-16 12:15:18.934  6942  6942 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 12:15:18.934  6942  6942 D PanProfile: Bluetooth service connected
08-16 12:15:18.937  6942  6966 D BluetoothMap: onBluetoothStateChange: up=true
08-16 12:15:18.940  6942  6942 D BluetoothMap: Proxy object connected
08-16 12:15:18.940  6942  6942 D MapProfile: Bluetooth service connected
08-16 12:15:18.940  6942  6942 D BluetoothMap: getConnectedDevices()
,08-16 12:15:18.942  7990  8005 V BluetoothMapService: getConnectedDevices()
08-16 12:15:18.943  1036  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 12:15:18.943  1036  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 12:15:18.943  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-16 12:15:18.945  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:18.945  1036  1119 D BluetoothManagerService: Message: 40
08-16 12:15:18.945  1036  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-16 12:15:18.945  1926  2118 D LGBluetoothAPIService: Message: 1
08-16 12:15:18.945  1926  2118 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-16 12:15:18.945  1926  2118 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-16 12:15:18.946  1926  2118 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-16 12:15:18.946  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 12:15:18.949  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:15:18.951  7990  7990 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:18.951  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:15:18.951  7990  7990 D BluetoothMapService: STATE_ON
,08-16 12:15:18.959  6942  6942 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 12:15:18.960  6942  6942 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 12:15:18.967  6942  6942 D DockEventReceiver: finishStartingService: stopping service
,08-16 12:15:18.970  7990  7990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@47928a8
08-16 12:15:18.970  7990  7990 V BluetoothPbapService: Pbap Service onCreate
08-16 12:15:18.970  7990  7990 V BluetoothPbapService: Starting PBAP service
08-16 12:15:18.971  7990  7990 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-16 12:15:18.971  7990  7990 V BluetoothMapService: Handler(): got msg=1
08-16 12:15:18.972  7990  7990 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 12:15:18.973  7990  7990 V BluetoothPbapService: Pbap Service onBind
08-16 12:15:18.973  7990  8117 D BluetoothMapMasInstance: MAS initSocket()
08-16 12:15:18.974  7990  7990 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:18.974  7990  7990 V BluetoothPbapService: state: 12
08-16 12:15:18.974  7990  7990 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 12:15:18.975  7990  7990 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:18.975  7990  7990 V BluetoothPbapReceiver: ***********state = 12
08-16 12:15:18.975  7990  8117 D BluetoothMapMasInstance:   masId = 00
08-16 12:15:18.975  7990  8117 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 12:15:18.975  7990  8117 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 12:15:18.975  7990  8117 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-16 12:15:18.976  6942  6942 D BluetoothPbap: Proxy object connected
08-16 12:15:18.976  6942  6942 D PbapServerProfile: Bluetooth service connected
08-16 12:15:18.976  7990  7990 V BluetoothPbapService: Handler(): got msg=1
08-16 12:15:18.977  7990  7990 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-16 12:15:18.978  7990  8118 V BluetoothPbapService: Pbap Service initSocket
,08-16 12:15:18.980  2168  2168 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 12:15:18.980  2168  2168 D c       : Getting all permits...
08-16 12:15:18.980  2168  2168 D a       : Opening database...
,08-16 12:15:18.983  1036  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:15:18.984  1036  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:15:18.985  7990  8118 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 12:15:18.986  7990  8117 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 12:15:18.987  7990  8117 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-16 12:15:18.987  7990  8117 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 12:15:18.987  7990  8117 D BluetoothMapMasInstance: Accepting socket connection...
08-16 12:15:18.987  7990  8118 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-16 12:15:18.988  7990  8024 D BluetoothAdapterProperties: Scan Mode:21
08-16 12:15:18.988  7990  8024 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 12:15:18.988  7990  8118 V BluetoothPbapService: Succeed to create listening socket 
08-16 12:15:18.991  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:15:18.988  7990  8118 V BluetoothPbapService: Accepting socket connection...
08-16 12:15:18.992  2168  2168 D a       : Opening database auth.proximity.permit_store...
08-16 12:15:18.993  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:15:18.993  2168  2168 D a       : Closing database...
08-16 12:15:19.004  6942  6942 D BluetoothPermissionRequest: onReceive
,08-16 12:15:19.006  6942  6942 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 12:15:19.008  6942  6942 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 12:15:19.011  7990  7990 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-16 12:15:19.013  7990  7990 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-16 12:15:19.019  7990  7990 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-16 12:15:19.041  7990  7990 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-16 12:15:19.041  7990  7990 V BtOppService: onCreate
08-16 12:15:19.047  7990  7990 V BluetoothOppNotification: send message
08-16 12:15:19.051  7990  7990 V BtOppService: Starting RfcommListener
08-16 12:15:19.056  7990  7990 D BluetoothOppPreference: Dumping Names:  
08-16 12:15:19.056  7990  7990 D BluetoothOppPreference: {}
08-16 12:15:19.056  7990  7990 D BluetoothOppPreference: Dumping Channels:  
08-16 12:15:19.056  7990  7990 D BluetoothOppPreference: {}
08-16 12:15:19.057  7990  7990 V BtOppService: onStartCommand
,08-16 12:15:19.062  7990  7990 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:19.062  7990  7990 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 12:15:19.062  7990  8124 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 12:15:19.066  7990  7990 V BluetoothOppNotification: new notify threadi!
08-16 12:15:19.072  7990  7990 V BluetoothOppNotification: send delay message
,08-16 12:15:19.074  7990  7990 V BtOppService: start RfcommListener
08-16 12:15:19.076  7990  8121 V BtOppService: Deleted complete outbound shares, number =  0
08-16 12:15:19.080  7990  8124 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 12:15:19.080  7990  8121 V BtOppService: Deleted complete inbound failed shares, number = 0
08-16 12:15:19.081  7990  8121 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-16 12:15:19.081  7990  8124 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13aa9de4 on behalf of 
08-16 12:15:19.082  7990  7990 V BtOppService: RfcommListener started
08-16 12:15:19.083  7990  8125 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 12:15:19.083  7990  8126 V BtOppRfcommListener: Starting RFCOMM listener....
08-16 12:15:19.083  7990  8121 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e18e24d on behalf of 
08-16 12:15:19.084  1036  1980 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:15:19.085  7990  8126 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 12:15:19.087  7990  8126 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-16 12:15:19.089  7990  8126 V BtOppRfcommListener: Started RFCOMM listener....
08-16 12:15:19.089  7990  8126 I BtOppRfcommListener: Accept thread started.
08-16 12:15:19.089  7990  8126 V BtOppRfcommListener: Accepting connection...
08-16 12:15:19.094  7990  8124 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 12:15:19.096  7990  8125 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a1a0102 on behalf of 
08-16 12:15:19.108  7990  8125 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 12:15:19.109  7990  7990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@47928a8
08-16 12:15:19.110  7990  7990 V BluetoothFtpService: Ftp Service onCreate
08-16 12:15:19.110  7990  7990 I BluetoothFtpService: Ftp Service onCreate
08-16 12:15:19.110  7990  7990 V BluetoothFtpService: Ftp Service onStartCommand
08-16 12:15:19.110  7990  7990 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:19.110  7990  7990 V BluetoothFtpService: Starting Listening on sockets
,08-16 12:15:19.111  7990  7990 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 12:15:19.111  7990  7990 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 12:15:19.111  7990  7990 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 12:15:19.111  7990  7990 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:19.111  7990  7990 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 12:15:19.111  7990  7990 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 12:15:19.113  7990  8125 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 12:15:19.114  7990  8125 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3465b450 on behalf of 
08-16 12:15:19.115  7990  7990 V BtOppService: ContentObserver received notification
08-16 12:15:19.116  7990  7990 V BtOppService: ContentObserver received notification
08-16 12:15:19.116  7990  7990 V BluetoothFtpService: Handler(): got msg=1
08-16 12:15:19.117  7990  8127 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 12:15:19.117  7990  7990 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-16 12:15:19.117  7990  8127 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 12:15:19.117  7990  7990 V BluetoothFtpService: Ftp Service initSocket
08-16 12:15:19.118  7990  8127 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@121e5649 on behalf of 
08-16 12:15:19.119  7990  8125 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 12:15:19.122  7990  8127 V BluetoothOppNotification: update too frequent, put in queue
08-16 12:15:19.123  7990  8125 V BluetoothOppNotification: outbound notification was removed.
08-16 12:15:19.123  7990  8125 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 12:15:19.124  7990  8127 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-16 12:15:19.125  1036  1771 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:15:19.126  7990  8125 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3aab2b4e on behalf of 
08-16 12:15:19.127  7990  7990 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 12:15:19.127  7990  8125 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 12:15:19.128  7990  7990 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=80
08-16 12:15:19.128  7990  7990 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-16 12:15:19.129  7990  8125 V BluetoothOppNotification: inbound notification was removed.
08-16 12:15:19.129  7990  8125 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 12:15:19.131  7990  8125 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e67646f on behalf of 
08-16 12:15:19.131  7990  8128 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-16 12:15:19.146  7990  7990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@47928a8
08-16 12:15:19.147  7990  7990 V BluetoothSapService: Sap Service onCreate
,08-16 12:15:19.149  7990  7990 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:15:19.149  7990  7990 V BluetoothSapService: state: 12
08-16 12:15:19.149  7990  7990 V BluetoothSapService: Starting SAP server process
08-16 12:15:19.152  7990  7990 V BluetoothSapService: SAP Service startRfcommListenerThread
08-16 12:15:19.141  8130  8130 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:15:19.141  8130  8130 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:15:19.156  7990  8131 V BluetoothSapService: Sap Service initRfcommSocket
08-16 12:15:19.156  1036  1872 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:15:19.158  7990  8131 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 12:15:19.160  7990  8131 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-16 12:15:19.160  7990  8131 V BluetoothSapService: Succeed to create listening socket 
08-16 12:15:19.160  7990  8131 V BluetoothSapService: Accepting socket connection...
,08-16 12:15:19.165  8130  8130 V BT_SAP  : Event pipe created
,08-16 12:15:19.165  8130  8130 V BT_SAP  : create_server_socket qcom.sap.server
08-16 12:15:19.165  8130  8130 V BT_SAP  : created socket fd 6
08-16 12:15:19.439  1036  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{362356f6 type 2 when 389469 com.google.android.gms} when 389469
,08-16 12:15:19.463   311  8139 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-16 12:15:19.465  1036  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-16 12:15:20.075  7990  7990 V BluetoothOppNotification: new notify threadi!
08-16 12:15:20.076  7990  7990 V BluetoothOppNotification: send delay message
,08-16 12:15:20.088  7990  8143 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-16 12:15:20.092  7990  8143 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2afd88b on behalf of 
08-16 12:15:20.097  7990  8143 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-16 12:15:20.104  7990  8143 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 12:15:20.107  7990  8143 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f5bbd68 on behalf of 
08-16 12:15:20.108  7990  8143 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-16 12:15:20.112  7990  8143 V BluetoothOppNotification: outbound notification was removed.
08-16 12:15:20.113  7990  8143 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 12:15:20.114  7990  8143 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14358581 on behalf of 
08-16 12:15:20.115  7990  8143 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 12:15:20.117  7990  8143 V BluetoothOppNotification: inbound notification was removed.
08-16 12:15:20.118  7990  8143 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 12:15:20.119  7990  8143 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2c3d5626 on behalf of 
08-16 12:15:22.694  6814  6884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:15:22.694  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:15:22.694  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:15:22.694  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:15:22.694  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:15:22.694  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:15:22.694  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:15:22.694  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:15:22.702  6814  6884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 12:15:22.703  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:15:22.703  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@207b8b0d removed from the list
08-16 12:15:22.703  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 12:15:22.703  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:15:22.703  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:15:22.704  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:15:22.704  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@12065ac2 added. We now have 4 listener(s)
08-16 12:15:22.704  6814  6884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:15:22.706  1036  1637 D WifiServiceImplEx: setWifiEnabled: false pid=6814, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 12:15:22.706  1036  1637 D WifiService: setWifiEnabled: false pid=6814, uid=10118
08-16 12:15:22.706  1036  1637 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 12:15:27.716  6814  6884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:15:27.729  1036  1872 D WifiServiceImplEx: setWifiEnabled: true pid=6814, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 12:15:27.729  1036  1872 D WifiService: setWifiEnabled: true pid=6814, uid=10118
08-16 12:15:27.729  1036  1872 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 12:15:27.744  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 12:15:27.744  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 12:15:27.744  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-16 12:15:27.748  1036  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-16 12:15:27.748  1036  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-16 12:15:27.751  1036  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 12:15:27.751  1036  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 12:15:27.751  1036  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 12:15:27.751  1036  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 12:15:27.751  1036  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 12:15:27.751  1036  1523 E WifiHW  : unknown target_country: EU , set to default
08-16 12:15:27.751  1036  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-16 12:15:27.751  1036  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-16 12:15:27.751  1036  1523 I WifiUtil: gEnableBmps=1
08-16 12:15:28.322   311   894 D SoftapController: Softap fwReload - Ok
,08-16 12:15:28.330  1036  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-16 12:15:28.348  1036  1523 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (594ms)
08-16 12:15:28.366   311   894 D CommandListener: Setting iface cfg
08-16 12:15:28.366   311   894 D CommandListener: Trying to bring down wlan0
,08-16 12:15:28.369   311   894 D CommandListener: Clearing all IP addresses on wlan0
08-16 12:15:28.371  1036  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-16 12:15:28.371  8154  8154 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:15:28.381  8154  8154 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 12:15:28.418  1036  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 12:15:28.418  1036  1523 E WifiStateMachine: useWiFiOffloading() : false
08-16 12:15:28.418  1036  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 12:15:28.420  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-16 12:15:28.427  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:28.435  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-16 12:15:28.445  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:15:28.448  8154  8154 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-16 12:15:28.453  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:15:28.454  1036  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 12:15:28.454  1036  1523 D WifiMonitor: connecting to supplicant
08-16 12:15:28.473  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 12:15:28.473  6942  6942 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 12:15:28.473  6942  6942 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 12:15:28.473  6942  6942 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-16 12:15:28.478  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-16 12:15:28.480  6942  6942 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-16 12:15:28.480  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 12:15:28.481  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 12:15:28.481  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 12:15:28.481  6942  6942 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 12:15:28.481  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 12:15:28.481  6942  6942 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 12:15:28.514  8154  8154 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 12:15:28.515  8154  8154 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-16 12:15:28.519  1036  1119 D Tethering: InitialState.processMessage what=4
08-16 12:15:28.536  1036  1980 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8173 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-16 12:15:28.538  1036  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 12:15:28.614  8154  8154 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 12:15:28.646  1036  1907 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8194 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 12:15:28.651  8173  8192 W FormManager: Network not available. Please check & try again.
08-16 12:15:28.656  8173  8193 V FormManager: Network unavailable.
08-16 12:15:28.665  8173  8193 V FormManager: Network unavailable.
,08-16 12:15:28.676  1036  1058 I ActivityManager: Killing 7177:com.android.chrome/u0a57 (adj 15): empty #17
,08-16 12:15:28.711  8154  8154 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-16 12:15:28.716  1036  1560 W libprocessgroup: failed to open /acct/uid_10057/pid_7177/cgroup.procs: No such file or directory
08-16 12:15:28.721  8154  8154 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-16 12:15:28.721  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-16 12:15:28.722  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-16 12:15:28.722  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 12:15:28.723  1036  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 12:15:28.724  1036  8212 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
,08-16 12:15:28.724  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:15:28.724  1036  8212 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 12:15:28.724  1036  8212 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 12:15:28.724  1036  8212 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-16 12:15:28.724  1036  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:15:28.725  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:15:28.726  1036  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:15:28.726  1036  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 12:15:28.726  1036  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 12:15:28.728  1036  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 12:15:28.728  1036  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 12:15:28.728  1036  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-16 12:15:28.729  1036  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 12:15:28.729  1036  1523 E WifiStateMachine: useWiFiOffloading() : false
08-16 12:15:28.729  1036  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 12:15:28.729  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:28.729  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:28.729  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:28.729  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:28.729  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 12:15:28.729  1036  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 12:15:28.730  1036  1523 D WifiNative-wlan0: SET update_config 1: returned true
08-16 12:15:28.731  1036  1523 D WifiConfigStore: Loading config and enabling all networks 
08-16 12:15:28.731  1036  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 12:15:28.731  1036  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 12:15:28.731  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 12:15:28.732  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:28.733  1926  1926 D WfdService: Waiting for WifiP2p enabling
08-16 12:15:28.733  1036  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-16 12:15:28.737  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:15:28.737  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:15:28.737  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:15:28.737  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:15:28.737  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:15:28.737  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:15:28.737  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:15:28.737  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:15:28.739  6814  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:15:28.742  1036  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-16 12:15:28.742  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:15:28.742  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:15:28.742  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:15:28.742  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:15:28.742  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:15:28.742  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:15:28.742  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:15:28.742  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:15:28.744  6814  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:15:28.753  1036  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 12:15:28.753  1036  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-16 12:15:28.754  1036  1523 D WifiStateMachine: enableVerboseLogging : level 2
08-16 12:15:28.754  1036  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,08-16 12:15:28.754  1036  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 12:15:28.754  1036  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 12:15:28.755  1036  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 12:15:28.755  1036  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-16 12:15:28.755  1036  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 12:15:28.755  1036  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 12:15:28.756  1036  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 12:15:28.756  1036  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-16 12:15:28.756  1036  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-16 12:15:28.756  1036  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
,08-16 12:15:28.757  1036  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 12:15:28.757  1036  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-16 12:15:28.757  1036  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-16 12:15:28.758  1036  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 12:15:28.758  1036  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-16 12:15:28.758  1036  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 12:15:28.758  1926  1926 D WfdsService: Supplicant Connection state is changed : true
08-16 12:15:28.758  1036  1523 D WifiNative-HAL: Setting external_sim to 1
08-16 12:15:28.758  1036  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 12:15:28.759  1926  2300 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 12:15:28.759  1926  2300 D WfdsService: Set the WFDS Monitor: true
08-16 12:15:28.759  1926  2300 D WfdsMonitor: WfdsMonitorThread create
08-16 12:15:28.759  1926  2300 D WfdsMonitor: WFDS Monitor is created and started
08-16 12:15:28.759  1926  2300 D WfdsService: WiFi: Supplicant connection re-established
08-16 12:15:28.759  7770  7770 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:28.759  1036  1523 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 12:15:28.759  1036  1523 I WifiNative-HAL: startHal
08-16 12:15:28.759  1036  1523 D wifi    : setting scan oui 0x95715ce0
08-16 12:15:28.760  1926  8213 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 12:15:28.760  1036  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 12:15:28.760  1036  1523 I WifiNative-HAL: startHal
08-16 12:15:28.760  1036  1523 D wifi    : setting scan oui 0x95715ce0
08-16 12:15:28.760  1036  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 12:15:28.760  1926  8213 E CtrlSupplicant: Succeed to open control connection
08-16 12:15:28.760  1926  8213 E CtrlSupplicant: Succeed to open monitor connection
08-16 12:15:28.761  1926  8213 D WfdsMonitor: Supplicant connection established
08-16 12:15:28.761  1926  2300 D WfdsService: Connected to the supplicant for wfds
08-16 12:15:28.761  1036  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-16 12:15:28.761  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 12:15:28.762  8154  8154 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 12:15:28.762  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 12:15:28.762  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 12:15:28.763  8154  8154 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 12:15:28.763  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 12:15:28.763  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-16 12:15:28.764  8154  8154 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-16 12:15:28.764  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 12:15:28.764  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 12:15:28.764  8154  8154 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 12:15:28.765  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 12:15:28.765  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 12:15:28.766  8154  8154 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 12:15:28.766  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 12:15:28.766  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 12:15:28.766  8154  8154 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-16 12:15:28.766  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-16 12:15:28.767  1036  1523 D Wifi,Native-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 12:15:28.767  8154  8154 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 12:15:28.767  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
,08-16 12:15:28.769  1036  1523 E WifiNative: : [398,800,359 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-16 12:15:28.769  1036  1523 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 12:15:28.770  1036  1523 D WifiNative-wlan0: RECONNECT: returned true
08-16 12:15:28.770  1036  1523 D WifiNative-wlan0: doString: [STATUS]
08-16 12:15:28.770  1036  8212 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 12:15:28.770  1036  8212 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 12:15:28.771  1036  1523 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 12:15:28.771  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 12:15:28.771  1036  1523 D WifiNative-wlan0: SET ps 1: returned true
08-16 12:15:28.772  1036  1522 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:28.774   311   894 D CommandListener: Setting iface cfg
08-16 12:15:28.774   311   894 D CommandListener: Trying to bring up p2p0
08-16 12:15:28.774  8194  8194 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:15:28.774  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 12:15:28.774  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-16 12:15:28.774  1036  1522 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 12:15:28.774  1036  1541 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:28.774  1036  1541 I WifiNative-HAL: startHal
08-16 12:15:28.774  1036  1522 D LGWifiP2pService: P2pEnablingState
08-16 12:15:28.774  1036  1541 D wifi    : getting scan capabilities on interface[1] = 0x95715ce0
08-16 12:15:28.774  1036  1522 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:28.774  1036  1541 D wifi    : failed to get capabilities : -3
08-16 12:15:28.774  1036  1541 E WifiScanningService: could not get scan capabilities
08-16 12:15:28.774  1036  1522 D LGWifiP2pService: P2p socket connection successful
08-16 12:15:28.774  1036  1522 D LGWifiP2pService: P2pEnabledState
08-16 12:15:28.775  1036  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-16 12:15:28.775  1036  1542 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:28.775  1036  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 12:15:28.775  1036  1522 D LGWifiP2pService: sending p2p connection changed broadcast
08-16 12:15:28.776  1036  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 12:15:28.776  1036  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-16 12:15:28.776  1036  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-16 12:15:28.777  1036  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 12:15:28.777  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 12:15:28.777  1926  1926 D WfdsService: WifiP2pState is changed : true
08-16 12:15:28.777  1036  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 12:15:28.777  1036  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 12:15:28.778  8154  8154 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 12:15:28.778  1926  2300 D WfdsService: Receive the WFDS_ENABLE Method
08-16 12:15:28.778  1926  2300 D WfdsService: Set the WFDS Monitor: true
08-16 12:15:28.778  1926  2300 D WfdsService: Connected to the supplicant for wfds
08-16 12:15:28.778  1926  2300 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 12:15:28.778  8154  8154 I wpa_supplicant: WFDS: wfds_supplicant_,wfds_cmd: cmd = SET TRUE
08-16 12:15:28.778  1926  2300 D WfdsService: selectPreferredScanChannel [36]
08-16 12:15:28.778  1926  2300 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-16 12:15:28.779  1036  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 12:15:28.779  1036  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 12:15:28.780  1036  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-16 12:15:28.780  1036  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-16 12:15:28.780  8154  8154 E wpa_supplicant: disconnect_rssi_lvl: -100
,08-16 12:15:28.785  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 12:15:28.788  1036  1522 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-16 12:15:28.788  1036  1522 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-16 12:15:28.788  1036  1522 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 12:15:28.789  1036  1522 D WifiNative-p2p0: SET device_name G3: returned true
08-16 12:15:28.789  1036  1522 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 12:15:28.789  1036  1522 D LGWifiP2pService: before postfix = G3
08-16 12:15:28.789  1036  1522 D WifiServerServiceExt: postfix byte check : 2
08-16 12:15:28.789  1036  1522 D LGWifiP2pService: after postfix = G3
08-16 12:15:28.789  1036  1522 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-16 12:15:28.789  1926  1926 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-16 12:15:28.790  1036  1522 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
,08-16 12:15:28.790  1926  1926 D WfdsService: isConnected: false
08-16 12:15:28.790  1036  1522 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-16 12:15:28.790  1036  1522 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 12:15:28.790  1036  1522 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 12:15:28.791  1036  1523 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 12:15:28.791  1036  1522 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 12:15:28.791  1036  1522 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-16 12:15:28.791  1036  1523 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 12:15:28.791  1036  1522 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 12:15:28.791  1036  1522 D WifiNative-HAL: p2pGetDeviceAddress
08-16 12:15:28.792  1036  1523 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 12:15:28.792  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-16 12:15:28.792  1036  1522 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-16 12:15:28.792  1036  1522 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-16 12:15:28.792  1036  1522 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 12:15:28.793  1036  1522 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 12:15:28.793  1036  1522 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-16 12:15:28.793  1036  1522 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 12:15:28.793  1036  1522 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 12:15:28.793  1926  1926 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 12:15:28.793  1926  1926 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 12:15:28.793  1926  1926 D WfdsService: Update P2p Interface State: 3
,08-16 12:15:28.794  1036  1522 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 12:15:28.794  1036  1522 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-16 12:15:28.795  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:15:28.797  1036  2018 I ActivityManager: Killing 7199:com.lge.drmservice/u0a62 (adj 15): empty #17
08-16 12:15:28.804  1036  1522 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 12:15:28.804  1036  1522 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-16 12:15:28.805  8154  8154 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-16 12:15:28.805  8154  8154 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:15:28.806  8154  8154 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 12:15:28.806  8154  8154 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:15:28.806  1926  8213 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:15:28.806  1036  1523 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-16 12:15:28.807  1036  8212 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 12:15:28.807  1036  8212 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:15:28.807  8154  8154 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:15:28.807  1036  1523 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 12:15:28.807  1036  8212 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:15:28.807  1926  8213 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:15:28.807  1036  8212 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:15:28.807  1036  8212 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:15:28.807  1036  8212 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:15:28.807  1036  8212 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:15:28.807  1036  8212 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:15:28.807  1036  8212 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:15:28.807  1036  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 12:15:28.807  1036  8212 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:15:28.807  1036  8212 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:15:28.807  1036  8212 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:15:28.808  1036  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 12:15:28.808  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 12:15:28.808  8154  8154 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 12:15:28.808  8154  8154 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 12:15:28.808  1036  8212 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 12:15:28.808  1036  8212 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 12:15:28.808  1036  8212 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 12:15:28.808  1036  8212 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 12:15:28.809  1036  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 12:15:28.809  1036  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-16 12:15:28.809  1036  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-16 12:15:28.809  1036  1523 D WifiNative-wlan0: doBoolean: SCAN
08-16 12:15:28.809  1036  1523 D WifiNative-wlan0: SCAN: returned false
08-16 12:15:28.810  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=398842  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 12:15:28.828  1036  1522 D LGWifiP2pService: InactiveState
08-16 12:15:28.828  1036  1522 D LGWifiP2pService: InactiveState{ when=-35ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:28.828  1036  1522 D LGWifiP2pService: P2pEnabledSt,ate{ when=-35ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:28.828  1036  1522 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-16 12:15:28.828  1036  1058 W libprocessgroup: failed to open /acct/uid_10062/pid_7199/cgroup.procs: No such file or directory
08-16 12:15:28.828  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=398861  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 12:15:28.829  8154  8154 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 12:15:28.829  1036  1523 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 12:15:28.829  8154  8154 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:15:28.829  1036  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 12:15:28.830  1036  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 12:15:28.830  8154  8154 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 12:15:28.830  1036  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-16 12:15:28.830  8154  8154 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:15:28.831  1036  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 12:15:28.831  8154  8154 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:15:28.832  1926  8213 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 12:15:28.832  1926  8213 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:15:28.833  1926  8213 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:15:28.833  1036  8212 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 12:15:28.833  1036  8212 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:15:28.833  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:15:28.833  1036  8212 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:15:28.833  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:15:28.833  1036  8212 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 12:15:28.833  1036  8212 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:15:28.833  1036  8212 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:15:28.833  1036  8212 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:15:28.833  1036  8212 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:15:28.833  1036  8212 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 12:15:28.833  1036  8212 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:15:28.833  1036  8212 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:15:28.833  1036  8212 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 12:15:28.834  1036  1522 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 12:15:28.834  1036  1522 D LGWifiP2pService: InactiveState{ when=-28ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:28.834  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-28ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:28.834  1036  1522 D LGWifiP2pService: InactiveState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:28.834  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:28.834  1036  1522 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:28.834  1036  1522 D LGWifiP2pService: InactiveState{ when=-7ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:28.834  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:28.835  1036  1522 D LGWifiP2pService: DefaultState{ when=-7ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:28.835  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:28.835  1036  1522 D LGWifiP2pService: InactiveState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-1,6 12:15:28.836  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:28.836  1036  1522 D LGWifiP2pService: DefaultState{ when=-8ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:28.836  1036  1522 D LGWifiP2pService: InactiveState{ when=-9ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:28.836  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:28.836  1036  1522 D LGWifiP2pService: DefaultState{ when=-9ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:28.836  1926  2300 W WfdsService: DefaultState - msg [9441285] is not handled
08-16 12:15:28.837  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:28.837  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:28.837  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 12:15:28.837  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:15:28.837  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 12:15:28.837  1036  1036 E WifiServerServiceExt: No p2p device connected
08-16 12:15:28.847  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 12:15:28.847  6942  6942 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 12:15:28.847  6942  6942 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 12:15:28.847  6942  6942 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 12:15:28.848  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 12:15:28.848  6942  6942 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 12:15:28.848  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 12:15:28.848  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 12:15:28.849  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 12:15:28.849  6942  6942 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 12:15:28.849  6942  6942 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-16 12:15:28.859  8194  8194 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:15:28.862  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 12:15:28.868  8173  8217 W FormManager: Network not available. Please check & try again.
08-16 12:15:28.870  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:15:28.885  8173  8218 V FormManager: Network unavailable.
,08-16 12:15:28.886  4777  4777 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 12:15:28.887  4777  4777 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 12:15:28.889  8173  8218 V FormManager: Network unavailable.
08-16 12:15:28.889  4777  4777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:15:28.891  4777  4777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:15:28.896  4777  8219 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 12:15:28.900  4777  8220 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 12:15:28.900  4777  8220 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 12:15:28.944  1036  1058 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8221 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-16 12:15:29.071  8221  8221 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 12:15:29.071  8221  8221 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-16 12:15:29.083  8221  8221 V [BNRBootReceiver]: Boot Receiver Return
,08-16 12:15:29.084  8221  8221 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-16 12:15:29.138  1036  1771 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8242 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 12:15:29.139  1036  1771 I ActivityManager: Killing 7216:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-16 12:15:29.178  1036  1637 W libprocessgroup: failed to open /acct/uid_10085/pid_7216/cgroup.procs: No such file or directory
,08-16 12:15:29.199  8242  8242 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 12:15:29.219  8242  8242 D PluginManager: init()
,08-16 12:15:29.376  1036  8212 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-16 12:15:29.376  1036  8212 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 12:15:29.376  8154  8154 E wpa_supplicant: USIM:  scard_init function
08-16 12:15:29.376  1036  8212 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-16 12:15:29.376  1036  8212 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
08-16 12:15:29.376  1036  8212 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 12:15:29.378  8154  8154 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-16 12:15:29.379  1036  1523 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 12:15:29.380  1036  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 12:15:29.380  1036  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 12:15:29.380  1036  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 12:15:29.380  1036  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-16 12:15:29.388  1036  8212 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-16 12:15:29.388  1036  8212 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-16 12:15:29.392  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=399425  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-16 12:15:29.398  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:29.399  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:29.399  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 12:15:29.400  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:15:29.400  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:15:29.401  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:29.401  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:29.401  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 12:15:29.402  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=399435  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 12:15:29.403  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:15:29.403  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-16 12:15:29.404  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:29.407  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:15:29.407  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 12:15:29.409  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:29.497  8154  8154 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 12:15:29.500  1036  8212 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 12:15:29.500  1036  8212 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-16 12:15:29.500  1036  8212 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 12:15:29.500  1036  8212 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 12:15:29.501  1036  8212 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 12:15:29.501  1036  8212 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 12:15:29.501  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=399534  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 12:15:29.502  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=399535  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 12:15:29.502  1036  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=399535
08-16 12:15:29.503  1036  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=399535
,08-16 12:15:29.503  1036  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=399536,
,08-16 12:15:29.503  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=399536
,08-16 12:15:29.503  1036  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=399536,
,08-16 12:15:29.504  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=399536  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 12:15:29.506  8154  8154 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 12:15:29.506  8154  8154 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 12:15:29.509  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:15:29.509  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 12:15:29.509  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:29.509  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:29.509  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 12:15:29.510  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:29.511  1036  8212 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 12:15:29.511  1036  8212 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-16 12:15:29.511  1036  8212 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-16 12:15:29.511  1036  8212 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 12:15:29.511  1036  8212 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 12:15:29.511  1036  8212 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
,08-16 12:15:29.511  1036  8212 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 12:15:29.511  1036  8212 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-16 12:15:29.511  1036  8212 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 12:15:29.511  1036  8212 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 12:15:29.514  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:29.514  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:29.514  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-16 12:15:29.516  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=399549  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 12:15:29.517  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-16 12:15:29.517  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-16 12:15:29.518  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=399550  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 12:15:29.518  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=399551  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 12:15:29.518  1036  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=399551
08-16 12:15:29.519  1036  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=399551
08-16 12:15:29.519  1036  1523 D WifiNative-wlan0: doString: [STATUS]
08-16 12:15:29.519  1036  8212 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 12:15:29.519  1036  8212 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 12:15:29.520  1036  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 12:15:29.521  1036  1523 I WifiServiceExtension: setVHTCapabilityType  : false
,08-16 12:15:29.526  1036  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-16 12:15:29.526  1036  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-16 12:15:29.533  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:29.533  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:29.533  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 12:15:29.533  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:29.533  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:29.533  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 12:15:29.534  1036  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 12:15:29.539  1036  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-16 12:15:29.539  1036  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 12:15:29.539  1036  1530 D ConnectivityService: Got NetworkAgent Messenger
08-16 12:15:29.539  1036  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 12:15:29.539  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 12:15:29.539  1036  1530 D ConnectivityService: NetworkAgent connected
08-16 12:15:29.540  1036  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
,08-16 12:15:29.540  1036  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 12:15:29.544  1036  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 12:15:29.544  1036  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 12:15:29.544  1036  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 12:15:29.545  1036  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
,08-16 12:15:29.545  1036  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 12:15:29.547  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:15:29.547  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:15:29.548  1036  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 12:15:29.549   311   894 D CommandListener: Setting iface cfg
08-16 12:15:29.550  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:29.553  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:15:29.553  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:15:29.553  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:29.555  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:15:29.555  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 12:15:29.557  1036  1523 E WifiStateMachine: Start Dhcp Watchdog 3
08-16 12:15:29.557  1036  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=399590  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 12:15:29.557  1036  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=399590  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 12:15:29.557  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=399590  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 12:15:29.558  1036  8263 D DhcpStateMachine: StoppedState
08-16 12:15:29.558  1036  8263 D DhcpStateMachine: StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:29.558  1036  8263 D DhcpStateMachine: WaitBeforeStartState
08-16 12:15:29.558  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:15:29.558  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-16 12:15:29.559  1036  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=399591  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 12:15:29.559  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:15:29.559  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 12:15:29.559  1036  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=399592  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 12:15:29.559  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:29.559  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=399592  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 12:15:29.560  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:24278] from screen [on:0 period:-1831252968] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 12:15:29.560  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1831252968] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 12:15:29.560  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 12:15:29.564  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:15:29.564  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:15:29.564  1036  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:15:29.564  1036  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:15:29.564  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:15:29.565  1036  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 12:15:29.565  1036  1530 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-16 12:15:29.565  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:15:29.565  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:15:29.566  1036  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:15:29.566  1036  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:15:29.566  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:15:29.566  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 12:15:29.570  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 12:15:29.575  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 12:15:29.576  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:15:29.576  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 12:15:29.576  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=145,0,0
08-16 12:15:29.576  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=145,0,0
08-16 12:15:29.576  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 12:15:29.577  8154  8154 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-16 12:15:29.577  1036  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 12:15:29.577  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 12:15:29.577  1036  1523 D WifiNative-wlan0: SET ps 0: returned true
08-16 12:15:29.577  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-16 12:15:29.577  8154  8154 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 12:15:29.577  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 12:15:29.578  1036  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 12:15:29.578  1036  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 12:15:29.578  1036  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2a7cadeb target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:29.578  1036  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 12:15:29.578  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2a7cadeb target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:29.578   311   894 D CommandListener: Setting iface cfg
08-16 12:15:29.578   311   894 D CommandListener: Trying to bring up wlan0
08-16 12:15:29.579  1036  8263 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:29.579  1036  8263 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 12:15:29.579  1036  1523 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-16 12:15:29.580  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-16 12:15:29.580  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-16 12:15:29.580  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 12:15:29.580  8154  8154 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 12:15:29.580  1036  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:29.580  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:29.580  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 12:15:29.580  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 12:15:29.581  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 12:15:29.581  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-16 12:15:29.581  8154  8154 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-16 12:15:29.581  1036  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-16 12:15:29.581  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 12:15:29.604  1036  1523 D WifiNative-wlan0: SET ps 1: returned true
,08-16 12:15:29.604  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 12:15:29.604  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 12:15:29.605  1036  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 12:15:29.605  1036  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 12:15:29.605  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 12:15:29.605  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 12:15:29.606  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 12:15:29.606  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 12:15:29.606  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 12:15:29.606  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 12:15:29.606  1036  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 12:15:29.606  1036  1530 D ConnectivityService: ignoring duplicate network state non-change
08-16 12:15:29.608  1036  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 12:15:29.609  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 12:15:29.611  1036  1530 D ConnectivityService: Adding iface wlan0 to network 102
08-16 12:15:29.612  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:29.612  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:29.612  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 12:15:29.616  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:29.616  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:29.616  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 12:15:29.617  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 12:15:29.619  1926  1926 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-16 12:15:29.620  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:29.621  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:29.621  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 12:15:29.621  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 12:15:29.625  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:29.625  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:29.625  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 12:15:29.625  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", r,oaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:15:29.625  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 12:15:29.629  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:29.632  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:15:29.632  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 12:15:29.633  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:29.635  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:15:29.635  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
08-16 12:15:29.635  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:29.641  1036  1530 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 12:15:29.641  1036  1530 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-16 12:15:29.641  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:15:29.642  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
08-16 12:15:29.642  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:29.642  1036  1530 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-16 12:15:29.642   311   894 E Netd    : netlink response contains error (File exists)
08-16 12:15:29.643  1036  1530 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-16 12:15:29.643  1036  1530 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 12:15:29.643  1036  1530 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-16 12:15:29.643  1036  1530 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-16 12:15:29.646  1036  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 12:15:29.646  1036  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 12:15:29.646  1036  1530 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-16 12:15:29.646  1036  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 12:15:29.646  1036  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 12:15:29.646  1036  8262 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:29.646  1036  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:15:29.646  1036  8262 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 12:15:29.646  1036  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 12:15:29.647  1036  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:15:29.647  1036  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 12:15:29.647  1036  1530 D ConnectivityService: currentScore = 0, newScore = 20
08-16 12:15:29.647  1036  1530 D ConnectivityService:    accepting network in place of null
08-16 12:15:29.647  1036  8262 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 12:15:29.647  1036  1530 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:15:29.647  1036  8262 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 12:15:29.647  1837  1837 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:15:29.647  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 12:15:29.647  1036  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&,NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:15:29.647  1036  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 12:15:29.648  1036  1530 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 12:15:29.648  1036  1530 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-16 12:15:29.648  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 12:15:29.649   311  8279 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-16 12:15:29.650  1036  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 12:15:29.650  1036  1530 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 12:15:29.651  1036  1530 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-16 12:15:29.652  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-16 12:15:29.652  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 12:15:29.652  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 12:15:29.652  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 12:15:29.652  1036  1530 D ConnectivityService: validation of new default Network = false
08-16 12:15:29.652  1036  1530 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 12:15:29.652  1036  1530 D DSQN    : enableDataServiceNotify 
08-16 12:15:29.652  1036  1530 D DSQN    : start dsqn bin
,08-16 12:15:29.657  1036  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 12:15:29.657  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:15:29.657  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:15:29.658  1036  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:15:29.651  8280  8280 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:15:29.651  8280  8280 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:15:29.659  1036  1521 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-16 12:15:29.660  1587  2059 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 12:15:29.671  8280  8280 E DSQN    : DSQN ssw
,08-16 12:15:29.677  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 12:15:29.678  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:29.679  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:29.703   311  8279 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-16 12:15:29.731  8242  8242 W ExternalStrings: load override strings
08-16 12:15:29.731  8242  8242 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-16 12:15:29.731  8242  8242 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-16 12:15:29.731  8242  8242 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-16 12:15:29.731  8242  8242 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-16 12:15:29.731  8242  8242 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-16 12:15:29.731  8242  8242 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-16 12:15:29.731  8242  8242 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-16 12:15:29.731  8242  8242 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-16 12:15:29.731  8242  8242 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-16 12:15:29.731  8242  8242 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-16 12:15:29.731  8242  8242 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-16 12:15:29.731  8242  8242 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:15:29.731  8242  8242 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-16 12:15:29.731  8242  8242 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 12:15:29.731  8242  8242 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:15:29.731  8242  8242 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 12:15:29.731  8242  8242 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 12:15:29.731  8242  8242 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-16 12:15:29.732  8242  8242 D StatusProvider: onCreate
08-16 12:15:29.734   311  8279 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-16 12:15:29.765   311   893 D LGDataListener: argv[0]=dsqncommand
08-16 12:15:29.765   311   893 D LGDataListener: argv[1]=wlan0
08-16 12:15:29.765   311   893 D LGDataListener: argv[2]=1
08-16 12:15:29.765   311   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-16 12:15:29.766  1036  1117 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 12:15:29.766  1036  1117 D DSQN    : start to monitor internet connection
,08-16 12:15:29.782  1036  8263 D DhcpStateMachine: DHCPV4 request on wlan0
08-16 12:15:29.786  1036  8263 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-16 12:15:29.786  1036  8263 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-16 12:15:29.781  8286  8286 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:15:29.781  8286  8286 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 12:15:29.790  8242  8242 V Signer  : override build config not found
08-16 12:15:29.791  8242  8242 D Signer  : value of property debug is false
08-16 12:15:29.794  1036  8262 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 10:15:29 GMT], X-Android-Received-Millis=[1471342529793], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471342529764]}
08-16 12:15:29.794  1036  8262 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 12:15:29.794  1036  8262 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 12:15:29.794  1036  1530 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-16 12:15:29.794  1036  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 12:15:29.795  1036  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 12:15:29.795  1036  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:15:29.795  1036  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 12:15:29.795  1036  1530 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-16 12:15:29.796  1036  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 12:15:29.796  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:15:29.796  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:15:29.796  1036  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:15:29.798  1587  2059 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 12:15:29.799  1036  1530 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:15:29.800  1837  1837 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:15:29.801  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 12:15:29.802  1036  1523 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:15:29.802  1036  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 12:15:29.802  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 12:15:29.810  8286  8286 I dhcpcd  : version 5.5.6 starting
08-16 12:15:29.812  8286  8286 E dhcpcd  : get_duid: m
08-16 12:15:29.812  8286  8286 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 12:15:29.812  8286  8286 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-16 12:15:29.835  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 12:15:29.836  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:29.837  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:15:29.868  8242  8242 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-16 12:15:29.869  8242  8242 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-16 12:15:29.869  8242  8242 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-16 12:15:29.869  8242  8242 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-16 12:15:29.870  8242  8242 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-16 12:15:29.870  8242  8242 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-16 12:15:29.870  8242  8242 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-16 12:15:29.871  8242  8242 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-16 12:15:29.871  8242  8242 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-16 12:15:29.871  8242  8242 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-16 12:15:29.871  8242  8242 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
,08-16 12:15:29.872  8242  8242 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
,08-16 12:15:29.872  8242  8242 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-16 12:15:29.883  8286  8286 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-16 12:15:29.883  8286  8286 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 12:15:29.884  8286  8286 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 12:15:29.884  8286  8286 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-16 12:15:29.885  8286  8286 D dhcpcd  : wlan0: sending REQUEST (xid 0x20849847), next in 4.79 seconds
,08-16 12:15:29.887  8242  8242 V LGMDMManager: Create singleton instance
,08-16 12:15:29.924  8286  8286 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-16 12:15:29.952  8242  8242 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-16 12:15:29.966  8286  8286 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
,08-16 12:15:29.967  8286  8286 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
,08-16 12:15:29.967  8286  8286 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-16 12:15:29.968  8286  8286 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-16 12:15:29.968  8286  8286 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 12:15:29.969  8286  8286 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 12:15:29.969  8286  8286 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 12:15:29.969  8286  8286 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-16 12:15:30.011  8242  8242 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 12:15:30.017  8242  8297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 12:15:30.019  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 12:15:30.023  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 12:15:30.075  1036  1771 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8304 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-16 12:15:30.076  1036  1771 I ActivityManager: Killing 7235:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-16 12:15:30.085   344   344 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 425us total 19.427ms
08-16 12:15:30.103   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 373us total 17.835ms
,08-16 12:15:30.120   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 295us total 16.123ms
,08-16 12:15:30.189  1036  8263 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-16 12:15:30.192  1036  8263 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-16 12:15:30.193  1036  8263 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 12:15:30.193  1036  8263 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
,08-16 12:15:30.194  1036  8263 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-16 12:15:30.194  1036  8263 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 12:15:30.194  1036  8263 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-16 12:15:30.194  1036  8263 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-16 12:15:30.195  1036  8263 D DhcpStateMachine: RunningState
08-16 12:15:30.214  8242  8296 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-16 12:15:30.338  1036  1872 W libprocessgroup: failed to open /acct/uid_10093/pid_7235/cgroup.procs: No such file or directory
,08-16 12:15:30.369  8304  8304 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 12:15:30.394  8304  8304 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-16 12:15:30.428  8304  8304 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-16 12:15:30.428  8304  8304 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-16 12:15:30.428  8304  8304 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-16 12:15:30.429  8304  8304 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-16 12:15:30.429  8304  8304 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-16 12:15:30.431  8304  8304 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-16 12:15:30.436  8304  8304 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-16 12:15:30.442  8304  8304 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:15:30.444  8242  8296 D LgDataFeature: LgDataFeature() Constructor: none
08-16 12:15:30.445  8242  8296 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 12:15:30.446  8304  8304 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 12:15:30.468  8304  8304 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 12:15:30.470  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-16 12:15:30.470  8304  8304 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-16 12:15:30.472  6942  6942 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-16 12:15:30.475  8242  8242 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:15:30.475  8242  8297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 12:15:30.476  8304  8304 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-16 12:15:30.482  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:15:30.486  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:15:30.491  8304  8304 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:15:30.491  8304  8304 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:15:30.495  8304  8304 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 12:15:30.499  8242  8242 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:15:30.499  8242  8297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 12:15:30.507  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 12:15:30.514  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:15:30.528  8304  8304 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 12:15:30.529  8304  8304 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:15:30.529  8304  8304 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 12:15:30.532  8242  8242 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:15:30.533  8242  8297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 12:15:30.539  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:15:30.547  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:15:30.553  8304  8304 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:15:30.554  8304  8304 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:15:30.555  8304  8304 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 12:15:30.558  8242  8242 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 12:15:30.560  8242  8297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 12:15:30.566  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:15:30.571  8242  8296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-16 12:15:30.573  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:15:30.579  8304  8304 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:15:30.580  8304  8304 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:15:30.581  8304  8304 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 12:15:30.584  8242  8242 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 12:15:30.584  8242  8297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 12:15:30.591  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 12:15:30.592  8242  8296 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-16 12:15:30.598  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:15:30.602  8242  8296 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-16 12:15:30.603  8242  8296 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-16 12:15:30.603  8242  8296 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-16 12:15:30.604  8304  8304 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:15:30.604  8304  8304 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:15:30.605  8304  8304 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 12:15:30.605  8242  8296 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-16 12:15:30.605  8242  8296 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-16 12:15:30.608  8242  8242 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:15:30.608  8242  8297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 12:15:30.608  8242  8296 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-16 12:15:30.611  8242  8296 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-16 12:15:30.614  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:15:30.619  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:15:30.624  8304  8304 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:15:30.625  8304  8304 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:15:30.625  8304  8304 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 12:15:30.627  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 12:15:30.627  6942  6942 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 12:15:30.627  6942  6942 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 12:15:30.627  6942  6942 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 12:15:30.629  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 12:15:30.629  6942  6942 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 12:15:30.629  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 12:15:30.629  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 12:15:30.629  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 12:15:30.629  6942  6942 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 12:15:30.629  6942  6942 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 12:15:30.629  6942  6942 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 12:15:30.636  8242  8242 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 12:15:30.638  8242  8297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 12:15:30.648  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:15:30.654  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:15:30.665  8304  8304 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:15:30.666  8304  8304 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 12:15:30.678  8304  8304 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 12:15:30.684  8242  8242 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:15:30.688  8242  8297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 12:15:30.692  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:15:30.701  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 12:15:30.711  8304  8304 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 12:15:30.711  8304  8304 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 12:15:30.713  8304  8304 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 12:15:30.718  8242  8242 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:15:30.718  8242  8297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 12:15:30.725  8194  8194 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-16 12:15:30.737  8194  8194 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 12:15:30.741  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:15:30.749  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 12:15:30.760  8304  8304 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 12:15:30.761  8304  8304 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 12:15:30.762  8304  8304 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 12:15:30.764  8304  8304 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 12:15:30.764  8304  8304 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-16 12:15:30.770  8242  8242 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:15:30.817  8194  8194 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 12:15:30.819  8194  8194 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 12:15:30.826  6942  6942 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 12:15:30.837  6942  6942 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 12:15:30.850  8304  8304 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 12:15:30.850  8304  8304 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 12:15:30.853  8304  8304 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-16 12:15:30.858  8304  8304 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 12:15:30.859  8304  8304 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-16 12:15:30.865  8242  8242 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:15:30.877  8304  8304 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-16 12:15:30.879  8304  8304 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 12:15:30.880  8304  8304 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-16 12:15:30.923  8304  8304 D LgDataFeature: LgDataFeature() Constructor: none
08-16 12:15:30.924  8304  8304 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 12:15:30.934  8304  8304 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-16 12:15:30.935  8304  8304 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-16 12:15:30.935  8304  8304 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-16 12:15:30.935  8304  8304 V SoundPool: doLoad: loading sample sampleID=1
08-16 12:15:30.936  8304  8304 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 12:15:30.941  7713  7713 D UEI.SmartControl: QS Service created
08-16 12:15:30.941  8304  8365 V SoundPool: Start decode
08-16 12:15:30.941  8304  8365 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-16 12:15:30.943  1036  1523 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 12:15:30.944   315  1370 V MediaPlayerService: decode(22, 10857164, 17813)
08-16 12:15:30.944   315  1370 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-16 12:15:30.944   315  1370 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-16 12:15:30.944   315  1370 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-16 12:15:30.944   315  1370 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
,08-16 12:15:30.944   315  1370 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-16 12:15:30.944   315  1370 V MediaPlayerService: player type = 3
08-16 12:15:30.944   315  1370 V AwesomePlayer: AwesomePlayer create()
08-16 12:15:30.946   315  1370 V AwesomePlayer: reset_l() 
08-16 12:15:30.946   315  1370 V AwesomePlayer: cancelPlayerEvents
08-16 12:15:30.946   315  1370 V AwesomePlayer: setAudioSink() 
08-16 12:15:30.946   315  1370 V AwesomePlayer: reset_l() 
08-16 12:15:30.947   315  1370 V AudioCache: notify(0xb1432f00, 8, 0, 0)
08-16 12:15:30.947   315  1370 V AudioCache: ignored
08-16 12:15:30.947   315  1370 V AwesomePlayer: cancelPlayerEvents
08-16 12:15:30.947   315  1370 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-16 12:15:30.947   315  1370 V AwesomePlayer: setDataSource_l dataSource
08-16 12:15:30.947   315  1370 V LGParserOSAL: SniffLGParser start
08-16 12:15:30.947   315  1370 V LGParserOSAL: MainType:5, SubType=0
08-16 12:15:30.947   315  1370 V LGParserOSAL: #### check Mime : application/ogg
08-16 12:15:30.947   315  1370 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-16 12:15:30.948   315  1370 E MediaExtractor: Use LGExtractor :application/ogg 
08-16 12:15:30.949  8304  8304 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-16 12:15:30.950  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 12:15:30.951  1036  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 12:15:30.952  1036  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 12:15:30.953  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 12:15:30.954  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 12:15:30.956  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-16 12:15:30.956  1036  1530 D ConnectivityService: identical MTU - not setting
08-16 12:15:30.956  1036  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 12:15:30.956  1036  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 12:15:30.956  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 12:15:30.956  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:15:30.957  1036  1530 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 12:15:30.958  1587  2059 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-16 12:15:30.958  8304  8304 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 12:15:30.958  8304  8304 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-16 12:15:30.967  7713  7713 I UEI.SmartControl: Service initServices...
08-16 12:15:30.968  7713  7713 D UEI.SmartControl: QS start get config
08-16 12:15:30.972  8304  8304 V LGMDMManager: Create singleton instance
08-16 12:15:31.001   315  1370 V LGParserOSAL: supported mime: application/ogg
08-16 12:15:31.001   315  1370 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-16 12:15:31.001   315  1370 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-16 12:15:31.001   315  1370 V AwesomePlayer: mBitrate = -1 bits/sec
08-16 12:15:31.001   315  1370 V AwesomePlayer: AudioTrack Setting
08-16 12:15:31.001   315  1370 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-16 12:15:31.001   315  1370 V AwesomePlayer: setAudioSource() 
08-16 12:15:31.001   315  1370 V MediaPlayerService: prepare
08-16 12:15:31.001   315  1370 V AwesomePlayer: prepareAsync_l() 
08-16 12:15:31.002   315  1370 V MediaPlayerService: wait for prepare
08-16 12:15:31.003   315  8366 V AwesomePlayer: onPrepareAsyncEvent() 
08-16 12:15:31.003   315  8366 V AwesomePlayer: initAudioDecoder() 
08-16 12:15:31.003   315  8366 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 12:15:31.003   315  8366 V AudioSystem: isOffloadSupported()
08-16 12:15:31.003   315  8366 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 12:15:31.003   315  8366 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 12:15:31.003   315  8366 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 12:15:31.003   315  8366 V AwesomePlayer: getUseOffload() = 0 
08-16 12:15:31.003   315  8366 V OMXCodec: OMXCodec::Create
08-16 12:15:31.003   315  8366 V OMXCodec: findMatchingCodecs()
08-16 12:15:31.003   315  8366 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-16 12:15:31.003   315  8366 V OMXCodec: matchingCodecs.size()=1
08-16 12:15:31.003   315  8366 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-16 12:15:31.005   315  8366 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-16 12:15:31.005   315  8366 V LGCodecAdapter: LG Codec Adapter start
08-16 12:15:31.005   315  8366 V OMXCodec: OMXCodec Createtor
08-16 12:15:31.005   315  8366 V OMXCodec: setComponentRole
08-16 12:15:31.005   315  8366 V OMXCodec: configureCodec protected=0
08-16 12:15:31.005   315  8366 V LGCodecAdapter: called getLGCodecSpecificData
08-16 12:15:31.005   315  8366 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-16 12:15:31.005   315  8366 V LGCodecOSAL: Called LGconfigureCodecMETA
08-16 12:15:31.005   315  8366 V LGCodecOSAL: Called LGconfigureCodecMSG
08-16 12:15:31.005   315  8366 V LGCodecOSAL: Not support LGCodec
08-16 12:15:31.005   315  8366 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 12:15:31.006   315  8366 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-16 12:15:31.006   315  8366 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-16 12:15:31.006   315  8366 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-16 12:15:31.006   315  8366 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 12:15:31.006   315  8366 V AudioSystem: isOffloadSupported()
08-16 12:15:31.006   315  8366 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 12:15:31.006   315  8366 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 12:15:31.006   315  8366 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-16 12:15:31.006   315  8366 V OMXCodec: init()
08-16 12:15:31.006   315  8366 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-16 12:15:31.006   315  8366 V OMXCodec: allocateBuffers
08-16 12:15:31.006   315  8366 V OMXCodec: allocateBuffersOnPort portIndex=0
08-16 12:15:31.006   315  8366 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-16 12:15:31.006   315  8366 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-16 12:15:31.006   315  8366 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-16 12:15:31.006   315  8366 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-16 12:15:31.006   315  8366 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
08-16 12:15:31.006   315  8366 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 12:15:31.006   315  8366 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 12:15:31.006   315  8366 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-16 12:15:31.006   315  8366 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-16 12:15:31.007   315  8366 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-16 12:15:31.007   315  8366 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-16 12:15:31.007   315  8366 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 12:15:31.007   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 12:15:31.007   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 12:15:31.007   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-16 12:15:31.007   315  8366 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 12:15:31.007   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-16 12:15:31.007   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-16 12:15:31.007   31,5  8368 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-16 12:15:31.007   315  8366 V OMXCodec: init() mAsyncCompletion wait free! 
08-16 12:15:31.007   315  8366 V AwesomePlayer: finishAsyncPrepare_l() 
08-16 12:15:31.007   315  8366 V AudioCache: notify(0xb1432f00, 5, 0, 0)
08-16 12:15:31.007   315  8366 V AudioCache: ignored
08-16 12:15:31.007   315  8366 V AudioCache: notify(0xb1432f00, 1, 0, 0)
08-16 12:15:31.007   315  8366 V AudioCache: prepared
08-16 12:15:31.007   315  1370 V AudioCache: wait - success
08-16 12:15:31.007   315  1370 V MediaPlayerService: start
08-16 12:15:31.007   315  1370 V AwesomePlayer: play_l() 
08-16 12:15:31.007   315  1370 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-16 12:15:31.007   315  1370 V AwesomePlayer: createAudioPlayer_l
08-16 12:15:31.007   315  1370 V AwesomePlayer: seekAudioIfNecessary_l() 
08-16 12:15:31.008   315  1370 V AwesomePlayer: startAudioPlayer_l() 
08-16 12:15:31.008   315  1370 D AudioPlayer: start of Playback, useOffload 0
08-16 12:15:31.008   315  1370 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 12:15:31.008   315  1370 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 12:15:31.011   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-16 12:15:31.011   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-16 12:15:31.011   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-16 12:15:31.011   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-16 12:15:31.011   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-16 12:15:31.011   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 12:15:31.011   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-16 12:15:31.011   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 12:15:31.011   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
08-16 12:15:31.011   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 12:15:31.011   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
08-16 12:15:31.011   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 12:15:31.011   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
08-16 12:15:31.011   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 12:15:31.011   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-16 12:15:31.011   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 12:15:31.011   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-16 12:15:31.012   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-16 12:15:31.012   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-16 12:15:31.012   315  8368 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 12:15:31.012   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 12:15:31.012   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-16 12:15:31.012   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-16 12:15:31.012   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-16 12:15:31.012   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd1f0 on output port
08-16 12:15:31.012   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-16 12:15:31.012   315  8368 V OMXCod,ec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-16 12:15:31.016   315  1370 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-16 12:15:31.019   315  1370 V AudioCache: notify(0xb1432f00, 6, 0, 0)
08-16 12:15:31.019   315  1370 V AudioCache: ignored
08-16 12:15:31.020   315  1370 V MediaPlayerService: wait for playback complete
08-16 12:15:31.020   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.020   315  8373 V AudioCache: memcpy(0xac300000, 0xb178a000, 4096)
08-16 12:15:31.025   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.025   315  8373 V AudioCache: memcpy(0xac301000, 0xb178a000, 4096)
08-16 12:15:31.025   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.025   315  8373 V AudioCache: memcpy(0xac302000, 0xb178a000, 4096)
08-16 12:15:31.026   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.026   315  8373 V AudioCache: memcpy(0xac303000, 0xb178a000, 4096)
08-16 12:15:31.027   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.027   315  8373 V AudioCache: memcpy(0xac304000, 0xb178a000, 4096)
08-16 12:15:31.027   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.027   315  8373 V AudioCache: memcpy(0xac305000, 0xb178a000, 4096)
08-16 12:15:31.028   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.028   315  8373 V AudioCache: memcpy(0xac306000, 0xb178a000, 4096)
08-16 12:15:31.028   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.028   315  8373 V AudioCache: memcpy(0xac307000, 0xb178a000, 4096)
08-16 12:15:31.030   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.030   315  8373 V AudioCache: memcpy(0xac308000, 0xb178a000, 4096)
08-16 12:15:31.031   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.031   315  8373 V AudioCache: memcpy(0xac309000, 0xb178a000, 4096)
08-16 12:15:31.031   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.031   315  8373 V AudioCache: memcpy(0xac30a000, 0xb178a000, 4096)
08-16 12:15:31.032   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.032   315  8373 V AudioCache: memcpy(0xac30b000, 0xb178a000, 4096)
08-16 12:15:31.032   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.032   315  8373 V AudioCache: memcpy(0xac30c000, 0xb178a000, 4096)
08-16 12:15:31.033   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.033   315  8373 V AudioCache: memcpy(0xac30d000, 0xb178a000, 4096)
08-16 12:15:31.033   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.033   315  8373 V AudioCache: memcpy(0xac30e000, 0xb178a000, 4096)
08-16 12:15:31.034   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.034   315  8373 V AudioCache: memcpy(0xac30f000, 0xb178a000, 4096)
08-16 12:15:31.034   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.034   315  8373 V AudioCache: memcpy(0xac310000, 0xb178a000, 4096)
08-16 12:15:31.035   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.035   315  8373 V AudioCache: memcpy(0xac311000, 0xb178a000, 4096)
08-16 12:15:31.035   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.036   315  8373 V AudioCache: memcpy(0xac312000, 0xb178a000, 4096)
08-16 12:15:31.036   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.036   315  8373 V AudioCache: memcpy(0xac313000, 0xb178a000, 4096)
08-16 12:15:31.036   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.036   315  8373 V AudioCache: memcpy(0xac314000, 0xb178a000, 4096)
08-16 12:15:31.037   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.037   315  8373 V AudioCache: memcpy(0xac315000, 0xb178a000, 4096)
08-16 12:15:31.037   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.037   315  8373 V AudioCache: memcpy(0xac316000, 0xb178a000, 4096)
08-16 12:15:31.038   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.038   315  8373 V AudioCache: memcpy(0xac317000, 0xb178a000, 4096)
08-16 12:15:31.038   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.038   315  8373 V AudioCache: memcpy(0xac318000, 0xb178a000, 4096)
08-16 12:15:31.039   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.039   315  8373 V AudioCache: memcpy(0xac319000, 0xb178a000, 4096)
08-16 12:15:31.040   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.040   315  8373 V AudioCache: memcpy(0xac31a000, 0xb178a000, 4096)
08-16 12:15:31.040   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.040   315  8373 V AudioCache: memcpy(0xac31b000, 0xb178a000, 4096)
08-16 12:15:31.042   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.042   315  8373 V AudioCache: memcpy(0xac31c000, 0xb178a000, 4096)
08-16 12:15:31.043   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.043   315  8373 V AudioCache: memcpy(0xac31d000, 0xb178a000, 4096)
08-16 12:15:31.043   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.043   315  8373 V AudioCache: memcpy(0xac31e000, 0xb178a000, 4096)
08-16 12:15:31.044   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.044   315  8373 V AudioCache: memcpy(0xac31f000, 0xb178a000, 4096)
08-16 12:15:31.044   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.044   315  8373 V AudioCache: memcpy(0xac320000, 0xb178a000, 4096)
08-16 12:15:31.045   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.045   315  8373 V AudioCache: memcpy(0xac321000, 0xb178a000, 4096)
,08-16 12:15:31.046   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.046   315  8373 V AudioCache: memcpy(0xac322000, 0xb178a000, 4096)
08-16 12:15:31.046   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.047   315  8373 V AudioCache: memcpy(0xac323000, 0xb178a000, 4096)
08-16 12:15:31.047   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.047   315  8373 V AudioCache: memcpy(0xac324000, 0xb178a000, 4096)
08-16 12:15:31.048   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.048   315  8373 V AudioCache: memcpy(0xac325000, 0xb178a000, 4096)
08-16 12:15:31.048   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.048   315  8373 V AudioCache: memcpy(0xac326000, 0xb178a000, 4096)
08-16 12:15:31.049   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.049   315  8373 V AudioCache: memcpy(0xac327000, 0xb178a000, 4096)
08-16 12:15:31.049   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.049   315  8373 V AudioCache: memcpy(0xac328000, 0xb178a000, 4096)
08-16 12:15:31.050   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.050   315  8373 V AudioCache: memcpy(0xac329000, 0xb178a000, 4096)
08-16 12:15:31.050   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.050   315  8373 V AudioCache: memcpy(0xac32a000, 0xb178a000, 4096)
08-16 12:15:31.051   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.051   315  8373 V AudioCache: memcpy(0xac32b000, 0xb178a000, 4096)
08-16 12:15:31.051   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.051   315  8373 V AudioCache: memcpy(0xac32c000, 0xb178a000, 4096)
08-16 12:15:31.052   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.052   315  8373 V AudioCache: memcpy(0xac32d000, 0xb178a000, 4096)
08-16 12:15:31.052   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.052   315  8373 V AudioCache: memcpy(0xac32e000, 0xb178a000, 4096)
08-16 12:15:31.053   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.053   315  8373 V AudioCache: memcpy(0xac32f000, 0xb178a000, 4096)
08-16 12:15:31.053   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.053   315  8373 V AudioCache: memcpy(0xac330000, 0xb178a000, 4096)
08-16 12:15:31.053   315  8373 V AudioCache: write(0xb178a000, 4096)
08-16 12:15:31.053   315  8373 V AudioCache: memcpy(0xac331000, 0xb178a000, 4096)
08-16 12:15:31.053   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-16 12:15:31.053   315  8373 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 12:15:31.053   315  8373 V AwesomePlayer: postAudioEOS() 
08-16 12:15:31.053   315  8373 V AudioCache: write(0xb178a000, 280)
08-16 12:15:31.054   315  8373 V AudioCache: memcpy(0xac332000, 0xb178a000, 280)
08-16 12:15:31.055   315  8366 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-16 12:15:31.055   315  8366 V AwesomePlayer: onStreamDone
08-16 12:15:31.055   315  8366 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-16 12:15:31.055   315  8366 V AudioCache: notify(0xb1432f00, 2, 0, 0)
08-16 12:15:31.055   315  8366 V AudioCache: playback complete
08-16 12:15:31.055   315  8366 V AwesomePlayer: pause_l() 
08-16 12:15:31.055   315  8366 V AudioCache: notify(0xb1432f00, 7, 0, 0)
08-16 12:15:31.055   315  8366 V AudioCache: ignored
08-16 12:15:31.055   315  8366 V AwesomePlayer: cancelPlayerEvents
08-16 12:15:31.055   315  1370 V AudioCache: wait - success
08-16 12:15:31.055   315  1370 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-16 12:15:31.055   315  8366 D AudioPlayer: Pause Playback at 1068125
08-16 12:15:31.056   315  1370 V AwesomePlayer: reset_l() 
08-16 12:15:31.056   315  1370 V AudioCache: notify(0xb1432f00, 8, 0, 0)
08-16 12:15:31.056   315  1370 V AudioCache: ignored
08-16 12:15:31.056   315  1370 V AwesomePlayer: cancelPlayerEvents
08-16 12:15:31.056   315  1370 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-16 12:15:31.056   315  1370 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-16 12:15:31.056   315  1370 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-16 12:15:31.056   315  1370 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-16 12:15:31.056   315  1370 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 12:15:31.056   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 12:15:31.056   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 12:15:31.056   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-16 12:15:31.056   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
08-16 12:15:31.056   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-16 12:15:31.056   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-16 12:15:31.056   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-16 12:15:31.056   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-16 12:15:31.056   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-16 12:15:31.057   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-16 12:15:31.057   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-16 12:15:31.057   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 12:15:31.057   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bd1f0 on port 1
08-16 12:15:31.057   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-16 12:15:31.057   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-16 12:15:31.057   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-16 12:15:31.057   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
08-16 12:15:31.057   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-16 12:15:31.057   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 1
08-16 12:15:31.057   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 12:15:31.057   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-16 12:15:31.057   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-16 12:15:31.057   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-16 12:15:31.057   315  8368 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-16 12:15:31.057   315  1370 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 12:15:31.057   315  1370 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-16 12:15:31.057   315  1370 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-16 12:15:31.058   315  1370 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-16 12:15:31.059   315  1370 D AudioPlayer: AudioPlayer releasing audio source
08-16 12:15:31.059   315  1370 D AudioPlayer: AudioPlayer done releasing audio source
08-16 12:15:31.059   315  1370 V AwesomePlayer: reset_l() 
08-16 12:15:31.059   315  1370 V AwesomePlayer: cancelPlayerEvents
08-16 12:15:31.059   315  1370 V AwesomePlayer: ~AwesomePlayer call
08-16 12:15:31.061   315  1370 V AwesomePlayer: reset_l() 
08-16 12:15:31.061   315  1370 V AwesomePlayer: cancelPlayerEvents
08-16 12:15:31.061  8304  8365 V SoundPool: close(31)
08-16 12:15:31.061  8304  8365 V SoundPool: pointer = 0xa000e000, size = 205080, sampleRate = 48000, numChannels = 2
08-16 12:15:31.082  8304  8304 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 12:15:31.083  8304  8304 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-16 12:15:31.087  8304  8304 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3118
08-16 12:15:31.093  8242  8242 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:15:31.097  8242  8242 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:15:31.100  8242  8242 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:15:31.105  8242  8242 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:15:31.106  8242  8242 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:15:31.110  8242  8242 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 12:15:31.114  8242  8242 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 12:15:31.118  8242  8242 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:15:31.120  8242  8242 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 12:15:31.301  7713  7713 I UEI.SmartControl: Supports setup maps: true
08-16 12:15:31.304  7713  7713 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 12:15:31.304  7713  7713 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 12:15:31.304  7713  7713 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 12:15:31.304  7713  7713 I UEI.SmartControl: ### init IR Blaster...
,08-16 12:15:31.308  7713  7713 D serial_port: Configuring serial port
08-16 12:15:31.308  7713  7713 E UEI.SmartControl: UEIBLaster setting for 616
08-16 12:15:31.308  7713  7713 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 12:15:31.308  7713  7713 I UEI.SmartControl: configuring settings for MAXQ616
08-16 12:15:31.308  7713  7713 I UEI.SmartControl: Get version...
08-16 12:15:31.328  7713  8376 D UEI.SmartControl: serial port data available: 21
,08-16 12:15:31.355  7713  7713 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-16 12:15:31.356  7713  7713 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-16 12:15:31.357  7713  7713 I UEI.SmartControl: QS saving settings...
08-16 12:15:31.359  7713  7713 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 12:15:31.377  7713  8376 D UEI.SmartControl: serial port data available: 4
,08-16 12:15:31.410  7713  8385 I UEI.SmartControl: Device manager: loading config....
,08-16 12:15:31.414  7713  8385 D UEI.SmartControl: ----------- loading internal config...
08-16 12:15:31.416  7713  7713 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-16 12:15:31.421  7713  7713 E UEI.SmartControl: Services init done
08-16 12:15:31.421  7713  7713 D UEI.SmartControl: QS Service init finished
08-16 12:15:31.423  7713  7713 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 12:15:31.423  7713  7713 D UEI.SmartControl: QS Service version code: 201091
08-16 12:15:31.425  7713  7713 D UEI.SmartControl: Service requested: Control
08-16 12:15:31.430  7713  8385 E UEI.SmartControl: Loading SETTINGS...
08-16 12:15:31.431  7713  7713 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-16 12:15:31.443  8304  8304 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-16 12:15:31.445  7713  7728 I UEI.SmartControl: ------ IControl API: 11
08-16 12:15:31.445  7713  7728 D UEI.SmartControl: File observer start...
08-16 12:15:31.446  7713  7728 E UEI.SmartControl: IR Port is disabled: false
08-16 12:15:31.446  7713  7728 D UEI.SmartControl: Starting file observer...
08-16 12:15:31.447  7713  7728 I UEI.SmartControl: Registering callback...
,08-16 12:15:31.449  7713  7730 I UEI.SmartControl: ------ IControl API: 19
08-16 12:15:31.451  7713  7730 I UEI.SmartControl: Registering Services Ready callback...
08-16 12:15:31.451  7713  7713 D UEI.SmartControl: Internal service binding...
08-16 12:15:31.453  7713  8385 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 12:15:31.469  7713  8384 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-16 12:15:31.472  8304  8323 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-16 12:15:31.473  8304  8363 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-16 12:15:31.473  8304  8363 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-16 12:15:31.474  8304  8304 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-16 12:15:31.474  8304  8304 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-16 12:15:31.475  7713  7728 I UEI.SmartControl: ------ IControl API: 8
08-16 12:15:31.475  7713  8384 D UEI.SmartControl: -----service ready thread exits
08-16 12:15:31.477  8304  8304 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-16 12:15:31.477  8304  8304 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-16 12:15:31.478  8304  8304 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-16 12:15:31.478  8304  8304 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-16 12:15:31.479  8304  8304 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-16 12:15:31.479  8304  8304 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-16 12:15:31.482  8304  8304 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-16 12:15:31.488  8304  8304 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 12:15:31.489  8304  8304 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 12:15:31.490  8304  8304 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 12:15:31.490  8304  8304 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 12:15:31.491  8304  8304 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 12:15:31.492  8304  8304 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-16 12:15:31.493  8304  8304 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-16 12:15:31.494  8304  8304 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471342531493]
08-16 12:15:31.498  8304  8304 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-16 12:15:31.503  1036  1907 I ActivityManager: Killing 7402:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-16 12:15:31.544  8304  8390 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-16 12:15:31.551  1036  1925 W libprocessgroup: failed to open /acct/uid_10005/pid_7402/cgroup.procs: No such file or directory
08-16 12:15:31.558  8304  8304 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-16 12:15:31.561  8304  8304 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 12:15:31.561  8304  8304 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-16 12:15:31.561  8304  8304 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-16 12:15:31.562  8304  8304 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-16 12:15:31.562  8304  8304 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-16 12:15:31.562  8304  8304 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-16 12:15:31.572  8304  8304 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-16 12:15:32.569  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=72.5, 0.0, 0.0  rx=73.0 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1831249959] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 12:15:32.572  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=72.5, 0.0, 0.0  rx=73.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1831249956] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 12:15:32.572  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 12:15:32.589  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 12:15:32.621  1036  1524 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-16 12:15:32.651  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:15:32.666  1036  1119 D Tethering: MasterInitialState.processMessage what=3
08-16 12:15:32.690  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:15:32.690  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:15:32.690  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:15:32.690  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:15:32.690  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:15:32.690  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:15:32.690  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:15:32.690  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:15:32.695  6814  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:15:32.700  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:15:32.700  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:15:32.700  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:15:32.700  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:15:32.700  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:15:32.700  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:15:32.700  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:15:32.700  6814  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:15:32.702  6814  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:15:32.712  1036  1108 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:15:32.716  8242  8242 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 12:15:32.721  8242  8296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 12:15:32.731  5802  5802 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-16 12:15:32.750  2168  2168 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:15:32.761  6814  6884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:15:32.761  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:15:32.761  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:15:32.761  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:15:32.761  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:15:32.761  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:15:32.761  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:15:32.761  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:15:32.763  6814  6884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:15:32.766  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:15:32.766  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@12065ac2 removed from the list
08-16 12:15:32.766  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:15:32.766  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:15:32.766  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:15:32.777  7089  7089 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 12:15:32.777  7089  7089 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 12:15:32.777  7089  7089 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 12:15:32.777  7089  7089 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 12:15:32.782  7089  7089 I AppUp4:CustModeStarterReceiver: onReceive
08-16 12:15:32.786  7089  7089 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@c671445
08-16 12:15:32.786  7089  7089 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 12:15:32.786  7089  7089 D AppUp4:CustFacade: isPhone : true
08-16 12:15:32.786  7089  7089 D AppUp4:CustModeStarterReceiver: begin check event
08-16 12:15:32.787  7089  7089 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 12:15:32.791  4777  4777 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 12:15:32.791  4777  4777 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 12:15:32.793  4777  4777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 12:15:32.799  4777  4777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 12:15:32.809  3395  3395 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:15:32.838  3395  3395 V DownloadManager: DownloadService onCreate
08-16 12:15:32.843  4777  8406 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 12:15:32.849  4777  8406 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-16 12:15:32.854  4777  8407 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 12:15:32.854  4777  8407 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 12:15:32.856   311  8411 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 12:15:32.856   311  8411 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-16 12:15:32.860  3395  8404 I DownloadManager: in removeSpuriousFiles
08-16 12:15:32.861  3395  8404 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,08-16 12:15:32.865  3395  8404 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2dfbde9e on behalf of 3395
08-16 12:15:32.865  3395  8404 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-16 12:15:32.865  3395  8404 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-16 12:15:32.866  3395  8404 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-16 12:15:32.866  3395  8404 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-16 12:15:32.866  3395  8404 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-16 12:15:32.866  3395  8404 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-16 12:15:32.866  3395  8404 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-16 12:15:32.866  3395  8404 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-16 12:15:32.866  3395  8404 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-16 12:15:32.866  3395  8404 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-16 12:15:32.866  3395  8404 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-16 12:15:32.867  3395  8404 I DownloadManager: in trimDatabase
08-16 12:15:32.867  3395  8404 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-16 12:15:32.867  1036  1108 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 12:15:32.868  3395  8404 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1011714c on behalf of 3395
08-16 12:15:32.873  1036  1560 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8413 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-16 12:15:32.875  3395  3395 V DownloadManager: DownloadService onStartCommand
,08-16 12:15:32.878  3395  8405 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-16 12:15:32.880  4777  8406 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-16 12:15:32.882  3395  8405 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@334346aa on behalf of 3395
08-16 12:15:32.882  4777  4777 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-16 12:15:32.883  4777  4777 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-16 12:15:32.883  4777  4777 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-16 12:15:32.884  3395  8405 V DownloadManager: processing inserted download 1
08-16 12:15:32.885  4777  4777 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-16 12:15:32.886  3395  8405 V DownloadManager: processing inserted download 4
,08-16 12:15:32.887  3395  8405 V DownloadManager: processing inserted download 7
08-16 12:15:32.887  3395  8405 V DownloadManager: processing inserted download 8
08-16 12:15:32.888  3395  8405 V DownloadManager: processing inserted download 9
08-16 12:15:32.888  4777  4777 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-16 12:15:32.888  3395  8405 V DownloadManager: processing inserted download 10
08-16 12:15:32.889  3395  8405 V DownloadManager: processing inserted download 11
08-16 12:15:32.890  3395  8405 V DownloadManager: processing inserted download 12
08-16 12:15:32.890  3395  8405 V DownloadManager: processing inserted download 13
08-16 12:15:32.891  3395  8405 V DownloadManager: processing inserted download 14
08-16 12:15:32.891  3395  8405 V DownloadManager: processing inserted download 16
08-16 12:15:32.893  3395  3395 V DownloadManager: DownloadService onDestroy
08-16 12:15:32.896   311  8411 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-16 12:15:32.917  8413  8413 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 12:15:32.917  8413  8413 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 12:15:32.918  8413  8413 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 12:15:32.918  8413  8413 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 12:15:33.036  1036  1962 I art     : Explicit concurrent mark sweep GC freed 77595(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 1.502ms total 73.698ms
,08-16 12:15:33.039  8413  8413 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 12:15:33.046  8413  8413 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-16 12:15:33.072  8413  8413 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 12:15:33.093  8413  8413 D LgDataFeature: LgDataFeature() Constructor: none
08-16 12:15:33.093  8413  8413 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 12:15:33.174  8413  8413 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 12:15:33.226  8413  8413 I HubEmail: JNI_OnLoad()
08-16 12:15:33.226  8413  8413 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,08-16 12:15:33.226  8413  8413 I HubEmail: registerNatives()
08-16 12:15:33.226  8413  8413 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 12:15:33.226  8413  8413 I HubEmail: registerNativeMethods()
08-16 12:15:33.226  8413  8413 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 12:15:33.226  8413  8413 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-16 12:15:33.241  8413  8445 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 12:15:33.267  3288  3288 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 12:15:33.267  3288  3288 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 12:15:33.267  3288  3288 I LgeMiscReceiver: networkInfo.isConnected() = true
08-16 12:15:33.267  3288  3288 D PhoneState: setPdpRejectCasuse : false
,08-16 12:15:33.274  2168  8437 D GCM     : Connected
08-16 12:15:33.281   311  8450 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-16 12:15:33.283   311  8450 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
08-16 12:15:33.317  1036  1907 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8451 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-16 12:15:33.330  2168  8437 D GCM     : Message class com.google.e.a.a.q
08-16 12:15:33.348   311  8450 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-16 12:15:33.390  8173  8447 V FormManager: There are no updated forms. The schedule will be deleted.
,08-16 12:15:33.392  8173  8447 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-16 12:15:33.418  1036  1560 I ActivityManager: Killing 7770:com.google.android.talk/u0a72 (adj 15): empty #17
,08-16 12:15:33.461  8451  8451 D LgDataFeature: LgDataFeature() Constructor: none
08-16 12:15:33.461  8451  8451 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 12:15:33.465  8451  8451 D PhoneMonitor: Register our PhoneStateListener
08-16 12:15:33.477  1036  1998 W libprocessgroup: failed to open /acct/uid_10072/pid_7770/cgroup.procs: No such file or directory
,08-16 12:15:33.504  8451  8451 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-16 12:15:33.508  8451  8451 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 12:15:33.539  8451  8451 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-16 12:15:33.541  8451  8451 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-16 12:15:33.542  8451  8451 D TelephonyAutoProfiling: [parse] Load xml
08-16 12:15:33.547  8451  8451 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-16 12:15:33.547  8451  8451 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-16 12:15:33.547  8451  8451 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-16 12:15:33.547  8451  8451 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-16 12:15:33.547  8451  8451 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-16 12:15:33.547  8451  8451 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-16 12:15:33.547  8451  8451 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-16 12:15:33.547  8451  8451 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-16 12:15:33.548  8451  8451 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-16 12:15:33.548  8451  8451 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-16 12:15:33.548  8451  8451 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-16 12:15:33.548  8451  8451 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-16 12:15:33.548  8451  8451 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-16 12:15:33.548  8451  8451 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-16 12:15:33.548  8451  8451 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-16 12:15:33.548  8451  8451 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-16 12:15:33.548  8451  8451 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-16 12:15:33.556  8451  8451 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-16 12:15:33.571  1036  1058 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8470 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 12:15:33.572  1036  1058 I ActivityManager: Killing 7822:com.android.contacts/u0a19 (adj 15): empty #17
,08-16 12:15:33.634  1036  1771 W libprocessgroup: failed to open /acct/uid_10019/pid_7822/cgroup.procs: No such file or directory
,08-16 12:15:33.652  1802  8487 I CheckinService: active receiver: enabled
,08-16 12:15:33.665  1802  8487 I CheckinService: Preparing to send checkin request
08-16 12:15:33.666  1802  8487 I EventLogService: Accumulating logs since 1471342499414
08-16 12:15:33.709  1802  8487 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-16 12:15:33.827   311  8490 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 12:15:33.827   311  8490 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,08-16 12:15:33.859   311  8490 D libc-netbsd: res_queryN name = www.google.com succeed
,08-16 12:15:33.866  1036  1771 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8491 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-16 12:15:33.871   311  8498 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 12:15:33.872   311  8498 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-16 12:15:33.872   311  8498 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-16 12:15:33.874  1036  1771 I ActivityManager: Killing 7845:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-16 12:15:33.923  1036  1525 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-16 12:15:33.936  1036  1943 W libprocessgroup: failed to open /acct/uid_10027/pid_7845/cgroup.procs: No such file or directory
,08-16 12:15:33.987  1036  1980 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8510 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-16 12:15:34.047  1036  1771 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8527 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 12:15:34.049  1036  1771 I ActivityManager: Killing 7867:com.android.vending/u0a44 (adj 15): empty #17
,08-16 12:15:34.128  1036  1962 W libprocessgroup: failed to open /acct/uid_10044/pid_7867/cgroup.procs: No such file or directory
08-16 12:15:34.148  8510  8510 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-16 12:15:34.148  8510  8510 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-16 12:15:34.167  8527  8527 I art     : Almond Protected OAT
,08-16 12:15:34.181  8510  8510 I MultiDex: VM with version 2.1.0 has multidex support
08-16 12:15:34.181  8510  8510 I MultiDex: install
08-16 12:15:34.181  8510  8510 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-16 12:15:34.194  8510  8510 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-16 12:15:34.245  8527  8527 D WeatherApplication: removeAccount
,08-16 12:15:34.247  8527  8527 D WeatherApplication: Account.length = 0
08-16 12:15:34.247  8527  8527 E WeatherApplication: OPERATOR:OPEN
08-16 12:15:34.254  8527  8527 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:15:34
08-16 12:15:34.261  8527  8527 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 12:15:34.261  8527  8527 D Weather.Utils: 2 : All the weather widget is gone.
08-16 12:15:34.263  8527  8527 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-16 12:15:34.268  8527  8527 D WeatherAncestor: connectivity changed - connection : true
,08-16 12:15:34.269  8527  8527 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-16 12:15:34.281  8527  8527 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 12:15:34.281  8527  8527 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 12:15:34.281  8527  8527 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-16 12:15:34.303  8527  8527 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 12:15:34.303  8527  8527 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:15:34
,08-16 12:15:34.369  1036  1058 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8553 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 12:15:34.371  1036  1058 I ActivityManager: Killing 7911:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-16 12:15:34.459  1036  1962 W libprocessgroup: failed to open /acct/uid_10080/pid_7911/cgroup.procs: No such file or directory
,08-16 12:15:34.598   278   389 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-16 12:15:34.598   278   389 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 12:15:34.598   278   389 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 12:15:34.598  8553  8571 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 12:15:34.601   278   389 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 12:15:34.601   278   389 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 12:15:34.601   278   389 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 12:15:34.602  8553  8571 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 12:15:34.612   278   389 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-16 12:15:34.612   278   389 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 12:15:34.612   278   389 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 12:15:34.613  8553  8573 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 12:15:34.615   278   389 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 12:15:34.615   278   389 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 12:15:34.615   278   389 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 12:15:34.615  8553  8573 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 12:15:34.637  8510  8526 D LgDataFeature: LgDataFeature() Constructor: none
08-16 12:15:34.638  8510  8526 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 12:15:34.814  8590  8590 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-16 12:15:34.846  8553  8553 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 12:15:34.856  8553  8553 I LibraryLoader: Loading: webviewchromium
08-16 12:15:34.859  8553  8553 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4900-4903)
08-16 12:15:34.859  8553  8553 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 12:15:34.865  8553  8553 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {13b20d84}
,08-16 12:15:34.867  8553  8553 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 12:15:34.867  8553  8553 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 12:15:34.870  8590  8590 I dex2oat : dex2oat took 56.894ms (threads: 4)
08-16 12:15:34.877  8553  8553 I BrowserStartupController: Initializing chromium process, renderers=0
08-16 12:15:34.878  8553  8553 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 12:15:34.886  8510  8526 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 12:15:34.886  8510  8526 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 12:15:34.886  8510  8526 I Adreno-EGL: Build Date: 12/12/14 금
08-16 12:15:34.886  8510  8526 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 12:15:34.886  8510  8526 I Adreno-EGL: Remote Branch: 
08-16 12:15:34.886  8510  8526 I Adreno-EGL: Local Patches: 
08-16 12:15:34.886  8510  8526 I Adreno-EGL: Reconstruct Branch: 
08-16 12:15:34.893  8553  8553 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-16 12:15:34.894  8553  8553 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,08-16 12:15:34.894  8553  8553 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-16 12:15:34.901   315   315 V AudioPolicyService: registerClient() client 0xb1005080, uid 10093
08-16 12:15:34.902  8553  8601 W AudioManagerAndroid: Requires BLUETOOTH permission
08-16 12:15:34.918  8553  8553 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 12:15:34.918  8553  8553 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 12:15:34.918  8553  8553 I Adreno-EGL: Build Date: 12/12/14 금
08-16 12:15:34.918  8553  8553 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 12:15:34.918  8553  8553 I Adreno-EGL: Remote Branch: 
08-16 12:15:34.918  8553  8553 I Adreno-EGL: Local Patches: 
08-16 12:15:34.918  8553  8553 I Adreno-EGL: Reconstruct Branch: 
,08-16 12:15:34.990  8553  8553 I NSApplication: Starting up...
,08-16 12:15:35.016  1036  1962 I ActivityManager: Killing 7640:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-16 12:15:35.120  8510  8526 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 12:15:35.120  8510  8526 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 12:15:35.120  8510  8526 I Adreno-EGL: Build Date: 12/12/14 금
08-16 12:15:35.120  8510  8526 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 12:15:35.120  8510  8526 I Adreno-EGL: Remote Branch: 
08-16 12:15:35.120  8510  8526 I Adreno-EGL: Local Patches: 
08-16 12:15:35.120  8510  8526 I Adreno-EGL: Reconstruct Branch: 
,08-16 12:15:35.134  1036  1998 W libprocessgroup: failed to open /acct/uid_10037/pid_7640/cgroup.procs: No such file or directory
,08-16 12:15:35.158  2168  2168 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-16 12:15:35.169  2168  2168 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-16 12:15:35.169  2168  2168 D c       : Getting all permits...
08-16 12:15:35.169  2168  2168 D a       : Opening database...
08-16 12:15:35.173  2168  2168 D a       : Opening database auth.proximity.permit_store...
08-16 12:15:35.174  2168  2168 D a       : Closing database...
,08-16 12:15:35.214  8510  8526 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 12:15:35.214  8510  8526 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 12:15:35.214  8510  8526 I Adreno-EGL: Build Date: 12/12/14 금
08-16 12:15:35.214  8510  8526 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 12:15:35.214  8510  8526 I Adreno-EGL: Remote Branch: 
08-16 12:15:35.214  8510  8526 I Adreno-EGL: Local Patches: 
08-16 12:15:35.214  8510  8526 I Adreno-EGL: Reconstruct Branch: 
,08-16 12:15:35.346   311  8623 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 12:15:35.347   311  8623 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-16 12:15:35.387   311  8623 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-16 12:15:35.573  1802  8487 I CheckinTask: Sending checkin request (7888 bytes)
,08-16 12:15:35.602  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=41.8, 0.0, 0.0  rx=39.5 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1831246926] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 12:15:35.615  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=41.8, 0.0, 0.0  rx=39.5 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1831246914] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 12:15:35.616  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 12:15:35.622  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 12:15:35.779  2168  2652 I art     : Explicit concurrent mark sweep GC freed 7610(479KB) AllocSpace objects, 4(64KB) LOS objects, 52% free, 29MB/61MB, paused 2.188ms total 42.248ms
,08-16 12:15:35.843  1802  8487 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-16 12:15:35.854  1802  8487 I CheckinService: active receiver: disabled
,08-16 12:15:35.881  2168  2168 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-16 12:15:35.900  2168  2168 I GCM     : GCM config loaded
,08-16 12:15:35.932  8451  8451 V SetupWizard: Connected to Gservices successfully
,08-16 12:15:36.412  7713  8386 D UEI.SmartControl: Internal timer expired: 2
,08-16 12:15:36.412  7713  8386 D UEI.SmartControl: unbind internal service
,08-16 12:15:36.502  7713  8380 D serial_port: close(fd = 24)
,08-16 12:15:36.512  7713  8380 I UEI.SmartControl: Serial port is closed.
08-16 12:15:37.786  6814  8641 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-16 12:15:37.786  6814  8641 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 12:15:38.631  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=39.9, 0.0, 0.0  rx=34.2 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1831243897] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 12:15:38.634  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=39.9, 0.0, 0.0  rx=34.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1831243894] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 12:15:38.635  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 12:15:39.250  1036  1523 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-16 12:15:39.251  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-16 12:15:39.252  1036  1523 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-16 12:15:39.253  1036  1523 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-16 12:15:39.255  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-16 12:15:39.267  1036  1523 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-16 12:15:39.634  8553  8574 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-16 12:15:40.347  1036  1637 I ActivityManager: Killing 7680:com.lge.settings.easy/1000 (adj 15): empty #17
,08-16 12:15:40.379  1036  1998 W libprocessgroup: failed to open /acct/uid_1000/pid_7680/cgroup.procs: No such file or directory
,08-16 12:15:40.794  6814  8641 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-16 12:15:40.795  6814  8641 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-16 12:15:40.804  6814  8641 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 12:15:40.807  6814  8644 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-16 12:15:40.807  6814  8644 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-16 12:15:40.807  6814  8644 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 12:15:40.807  6814  8644 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 12:15:40.807  6814  8644 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-16 12:15:40.808  6814  8641 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 12:15:40.809  6814  8641 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-16 12:15:40.811  6814  8647 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 899, name: IncomingSocketThread/Receiver)
08-16 12:15:40.812  6814  8647 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 899, thread name: IncomingSocketThread/Receiver)
08-16 12:15:40.812  6814  8647 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-16 12:15:40.812  6814  8647 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 899, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-16 12:15:40.815  6814  8646 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 898, name: IncomingSocketThread/Sender)
,08-16 12:15:40.819  6814  8649 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 900, name: OutgoingSocketThread/Receiver)
,08-16 12:15:40.819  6814  8649 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 900, thread name: OutgoingSocketThread/Receiver)
08-16 12:15:40.819  6814  8649 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-16 12:15:40.819  6814  8649 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 900, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-16 12:15:40.822  6814  8648 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 897, name: OutgoingSocketThread/Sender)
08-16 12:15:41.664  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=20.4, 0.0, 0.0  rx=18.6 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1831240864] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 12:15:41.678  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=20.4, 0.0, 0.0  rx=18.6 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1831240850] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 12:15:41.678  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 12:15:43.747  1587  1587 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-16 12:15:43.769  1036  1442 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 12:15:43.832  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 12:15:43.853  1036  1110 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8650 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-16 12:15:43.886  1587  1587 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-16 12:15:43.887  1587  1587 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-16 12:15:43.887  1036  1036 D administrator: Handling package changes for user 0
,08-16 12:15:43.901  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 12:15:43.947  8650  8650 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 12:15:44.026  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-16 12:15:44.026  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 12:15:44.056  8650  8650 D LgDataFeature: LgDataFeature() Constructor: none
08-16 12:15:44.056  8650  8650 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 12:15:44.068  1036  1108 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 12:15:44.074  1036  1108 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-16 12:15:44.083  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-16 12:15:44.083  2466  2466 V GmsNetworkLocationProvi: DISABLE
,08-16 12:15:44.116  2466  2466 E GCoreFlp: Bound FusedProviderService with LocationManager
08-16 12:15:44.120  1036  1108 D LocationProviderProxy: applying state to connected service
,08-16 12:15:44.211  8650  8695 I Babel   : MmsConfig: mnc/mcc: 0/0
08-16 12:15:44.212  8650  8695 I Babel   : MmsConfig.loadMmsSettings
,08-16 12:15:44.219  8650  8695 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 12:15:44.219  8650  8695 I Babel   : MmsConfig.loadFromDatabase
,08-16 12:15:44.261  8650  8695 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,08-16 12:15:44.262  8650  8695 I Babel   : MmsConfig.loadFromResources
08-16 12:15:44.264  8650  8650 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:15:44.265  8650  8695 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-16 12:15:44.266  8650  8695 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-16 12:15:44.292  8650  8693 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 12:15:44.297  1802  8697 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-16 12:15:44.297  1802  8697 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-16 12:15:44.298  8650  8693 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 12:15:44.304  7089  7089 I AppUp4:CustModeStarterReceiver: onReceive
08-16 12:15:44.304  8650  8693 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 12:15:44.320  7089  7089 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@c671445
08-16 12:15:44.320  7089  7089 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 12:15:44.320  7089  7089 D AppUp4:CustFacade: isPhone : true
08-16 12:15:44.321  7089  7089 D AppUp4:CustModeStarterReceiver: begin check event
08-16 12:15:44.321  7089  7089 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-16 12:15:44.333  1802  5223 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-16 12:15:44.334  8650  8693 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-16 12:15:44.335  8650  8693 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 12:15:44.346  8650  8693 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 12:15:44.358  8650  8693 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-16 12:15:44.361  8650  8693 W VideoCapabilities: Unsupported mime video/divx
08-16 12:15:44.363  8650  8693 W VideoCapabilities: Unsupported mime video/divx311
08-16 12:15:44.366  8650  8693 W VideoCapabilities: Unsupported mime video/divx4
08-16 12:15:44.368  1036  1907 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8700 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-16 12:15:44.374  1036  1560 I ActivityManager: Killing 8221:com.lge.bnr/1000 (adj 15): empty #17
08-16 12:15:44.374  8650  8693 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-16 12:15:44.404  8650  8693 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 12:15:44.407  8650  8693 W AudioCapabilities: Unsupported mime audio/eac3
08-16 12:15:44.408  8650  8693 W AudioCapabilities: Unsupported mime audio/ac3
08-16 12:15:44.409  8650  8693 W AudioCapabilities: Unsupported mime audio/g726
08-16 12:15:44.410  8650  8693 W AudioCapabilities: Unsupported mime audio/wma-voice
08-16 12:15:44.410  8650  8693 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-16 12:15:44.411  8650  8693 W AudioCapabilities: Unsupported mime audio/adpcm
08-16 12:15:44.412  8650  8693 W VideoCapabilities: Unsupported mime video/theora
08-16 12:15:44.414  8650  8693 W VideoCapabilities: Unsupported mime video/mjpg
08-16 12:15:44.456  1036  1871 W libprocessgroup: failed to open /acct/uid_1000/pid_8221/cgroup.procs: No such file or directory
,08-16 12:15:44.491  8700  8700 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 12:15:44.492  8700  8700 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 12:15:44.492  8700  8700 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 12:15:44.493  8700  8700 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-16 12:15:44.494  8700  8700 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-16 12:15:44.569  8700  8700 I SystemConfig: BUILD Country: EU
08-16 12:15:44.569  8700  8700 I SystemConfig: BUILD Operator: OPEN
,08-16 12:15:44.614  1036  1058 I ActivityManager: Killing 8194:com.lge.sync/1000 (adj 15): empty #17
,08-16 12:15:44.692  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=10.7, 0.0, 0.0  rx=9.3 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1831237836] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 12:15:44.694  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=10.7, 0.0, 0.0  rx=9.3 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1831237834] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 12:15:44.694  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 12:15:44.774  1036  1962 W libprocessgroup: failed to open /acct/uid_1000/pid_8194/cgroup.procs: No such file or directory
,08-16 12:15:44.790  8700  8719 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-16 12:15:44.791  8700  8719 I SystemConfig: existFile = false
08-16 12:15:44.792  8700  8719 I SystemConfig: canReadFile = false
08-16 12:15:44.792  8700  8719 I SystemConfig: systemFeature RCS result false
08-16 12:15:44.792  8700  8719 D SystemConfig: refreshRcsSupport() :false
,08-16 12:15:44.835  1036  1871 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8724 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-16 12:15:44.895  8724  8724 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 12:15:44.895  8724  8724 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 12:15:44.895  8724  8724 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 12:15:44.896  8724  8724 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 12:15:44.999  8724  8724 I AppConfig: Total System Memory = 2995761152
,08-16 12:15:45.010  8724  8724 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-16 12:15:45.101  1036  1771 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8746 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 12:15:45.107  1036  1771 I ActivityManager: Killing 6942:com.android.settings/1000 (adj 15): empty #17
08-16 12:15:45.127   344   344 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 484us total 24.969ms
,08-16 12:15:45.150   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 416us total 20.480ms
,08-16 12:15:45.172   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 413us total 19.146ms
,08-16 12:15:45.223  1036  1998 W libprocessgroup: failed to open /acct/uid_1000/pid_6942/cgroup.procs: No such file or directory
08-16 12:15:45.405  8746  8746 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-16 12:15:45.485  8746  8746 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 12:15:45.485  8746  8746 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 12:15:45.535  8746  8746 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-16 12:15:45.557  8746  8746 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 12:15:45.559  8746  8746 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 12:15:45.589  8746  8746 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 12:15:45.590  8746  8746 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-16 12:15:45.610  1036  1872 I ActivityManager: Killing 7713:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-16 12:15:45.642  8304  8304 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-16 12:15:45.642  8304  8304 W System.err: android.os.DeadObjectException
08-16 12:15:45.643  8304  8304 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 12:15:45.643  8304  8304 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 12:15:45.643  8304  8304 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-16 12:15:45.643  8304  8304 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-16 12:15:45.643  8304  8304 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 12:15:45.643  8304  8304 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 12:15:45.643  8304  8304 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 12:15:45.643  8304  8304 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 12:15:45.643  8304  8304 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 12:15:45.643  8304  8304 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 12:15:45.643  8304  8304 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:15:45.643  8304  8304 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 12:15:45.643  8304  8304 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 12:15:45.643  8304  8304 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 12:15:45.644  8304  8304 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
,08-16 12:15:45.644  8304  8304 W System.err: android.os.DeadObjectException
08-16 12:15:45.644  8304  8304 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 12:15:45.644  8304  8304 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 12:15:45.644  8304  8304 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-16 12:15:45.644  8304  8304 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-16 12:15:45.644  8304  8304 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 12:15:45.644  8304  8304 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 12:15:45.644  8304  8304 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 12:15:45.644  8304  8304 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 12:15:45.644  8304  8304 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 12:15:45.644  8304  8304 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 12:15:45.644  8304  8304 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:15:45.644  8304  8304 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 12:15:45.645  8304  8304 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
,08-16 12:15:45.645  8304  8304 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-16 12:15:45.645  8304  8304 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-16 12:15:45.645  8304  8304 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-16 12:15:45.683  1036  1771 W libprocessgroup: failed to open /acct/uid_1000/pid_7713/cgroup.procs: No such file or directory
,08-16 12:15:45.684  1036  1771 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-16 12:15:45.693  8304  8304 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-16 12:15:45.694  8304  8304 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 12:15:45.702  5051  8790 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-16 12:15:45.754  1036  1771 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8791 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 12:15:45.755  8304  8304 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-16 12:15:45.811  1036  1944 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8808 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-16 12:15:45.832  3395  3834 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-16 12:15:45.844  3395  3834 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1e8a5638 on behalf of 8746
,08-16 12:15:45.870  8791  8791 D UEI.SmartControl: Quickset Services start...
08-16 12:15:45.872  8791  8791 I UEI.SmartControl: Manufacture = LGE
08-16 12:15:45.872  8791  8791 D UEI.SmartControl: Id = LGNevo
,08-16 12:15:45.874  8791  8791 D UEI.SmartControl: File observer start...
08-16 12:15:45.875  8791  8791 E UEI.SmartControl: IR Port is disabled: false
08-16 12:15:45.875  8791  8791 D UEI.SmartControl: Starting file observer...
08-16 12:15:45.876  8791  8791 D UEI.SmartControl: Extracting JNI libs...
08-16 12:15:45.876  8791  8791 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-16 12:15:45.960  8791  8791 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-16 12:15:45.960  8791  8791 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-16 12:15:45.960  8791  8791 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-16 12:15:45.969  1036  1998 I art     : Explicit concurrent mark sweep GC freed 38359(1948KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 3.604ms total 120.321ms
08-16 12:15:45.984  8746  8746 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-16 12:15:46.000  8808  8808 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-16 12:15:46.005  8746  8746 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-16 12:15:46.019  8808  8808 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-16 12:15:46.019  8808  8808 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-16 12:15:46.019  8808  8808 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-16 12:15:46.019  8808  8808 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-16 12:15:46.019  8808  8808 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-16 12:15:46.019  8808  8808 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-16 12:15:46.026  8791  8791 I UEI.SmartControl: --- Selecting new region: 6
08-16 12:15:46.028  8791  8791 I UEI.SmartControl: Model = LG-D855
08-16 12:15:46.029  1036  1560 I ActivityManager: Killing 8304:com.lge.qremote/u0a112 (adj 15): empty #17
08-16 12:15:46.030  8791  8791 D UEI.SmartControl: QS Service created
08-16 12:15:46.056  1036  1907 W libprocessgroup: failed to open /acct/uid_10112/pid_8304/cgroup.procs: No such file or directory
,08-16 12:15:46.087  8791  8791 I UEI.SmartControl: Service initServices...
,08-16 12:15:46.092  8791  8791 D UEI.SmartControl: QS start get config
08-16 12:15:46.156  8791  8791 D UEI.SmartControl: Loading JNI Libs...
,08-16 12:15:46.236  1036  1771 V SIM_STK : Menu title from STK is T-Mobile
,08-16 12:15:46.262  5051  8790 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 558 ms] updated apps [took 558 ms] 
,08-16 12:15:46.455  8791  8791 I UEI.SmartControl: Supports setup maps: true
,08-16 12:15:46.459  8791  8791 D UEI.SmartControl: QS start statue = true Error code = 0
,08-16 12:15:46.459  8791  8791 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 12:15:46.459  8791  8791 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 12:15:46.460  8791  8791 I UEI.SmartControl: ### init IR Blaster...
08-16 12:15:46.464  8791  8791 D serial_port: Configuring serial port
08-16 12:15:46.474  8791  8791 E UEI.SmartControl: UEIBLaster setting for 616
08-16 12:15:46.474  8791  8791 I UEI.SmartControl: Setting serial record hearder size = 2
,08-16 12:15:46.484  8791  8791 I UEI.SmartControl: configuring settings for MAXQ616
,08-16 12:15:46.484  8791  8791 I UEI.SmartControl: Get version...
,08-16 12:15:46.503  8791  8839 D UEI.SmartControl: serial port data available: 21
,08-16 12:15:46.544  8791  8791 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-16 12:15:46.544  8791  8791 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-16 12:15:46.545  8791  8791 I UEI.SmartControl: QS saving settings...
,08-16 12:15:46.559  8791  8791 D UEI.SmartControl: IR Blaster version: 25672567
08-16 12:15:46.576  8791  8839 D UEI.SmartControl: serial port data available: 4
,08-16 12:15:46.618  8791  8848 I UEI.SmartControl: Device manager: loading config....
,08-16 12:15:46.619  8791  8848 D UEI.SmartControl: ----------- loading internal config...
,08-16 12:15:46.637  8791  8791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-16 12:15:46.643  8791  8791 E UEI.SmartControl: Services init done
08-16 12:15:46.643  8791  8791 D UEI.SmartControl: QS Service init finished
08-16 12:15:46.646  8791  8791 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 12:15:46.646  8791  8791 D UEI.SmartControl: QS Service version code: 201091
,08-16 12:15:46.649  8791  8791 D UEI.SmartControl: Service requested: Control
08-16 12:15:46.654  8791  8791 D UEI.SmartControl: Request IControl service: devices are loaded...
08-16 12:15:46.656  8791  8791 D UEI.SmartControl: Service.onUnbind: IControl
08-16 12:15:46.660  8791  8791 D UEI.SmartControl: Service.onDestroy
08-16 12:15:46.660  8791  8791 D UEI.SmartControl: Lock is in USE false
08-16 12:15:46.660  8791  8791 D UEI.SmartControl: unbind internal service
,08-16 12:15:46.664  8791  8791 D serial_port: close(fd = 25)
08-16 12:15:46.664  8791  8848 E UEI.SmartControl: Loading SETTINGS...
08-16 12:15:46.668  8791  8791 I UEI.SmartControl: Serial port is closed.
08-16 12:15:46.668  8791  8791 I UEI.SmartControl: Serial port is closed.
08-16 12:15:46.668  8791  8791 D UEI.SmartControl: Blaster closed
08-16 12:15:46.669  8791  8791 D UEI.SmartControl: Shut down QS...
08-16 12:15:46.669  8791  8791 D UEI.SmartControl: Stopping QS lib
08-16 12:15:46.669  8791  8791 D UEI.SmartControl: QS lib stop result = true
08-16 12:15:46.669  8791  8791 D UEI.SmartControl: Stopped QS lib
08-16 12:15:46.670  8791  8791 D UEI.SmartControl: Stopped file observer...
08-16 12:15:46.670  8791  8791 D UEI.SmartControl: QS shutdown complete
08-16 12:15:46.673  8791  8791 D UEI.SmartControl: QS Service created
,08-16 12:15:46.680  8791  8847 I UEI.SmartControl: Notify AllClients services are ready: 11
08-16 12:15:46.680  8791  8847 D UEI.SmartControl: -----service ready thread exits
08-16 12:15:46.681  8791  8848 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 12:15:46.698  8791  8791 I UEI.SmartControl: Service initServices...
08-16 12:15:46.698  8791  8791 D UEI.SmartControl: QS start get config
,08-16 12:15:47.097  8791  8791 I UEI.SmartControl: Supports setup maps: true
08-16 12:15:47.102  8791  8791 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 12:15:47.102  8791  8791 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 12:15:47.102  8791  8791 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 12:15:47.102  8791  8791 I UEI.SmartControl: ### init IR Blaster...
,08-16 12:15:47.110  8791  8791 D serial_port: Configuring serial port
08-16 12:15:47.110  8791  8791 E UEI.SmartControl: UEIBLaster setting for 616
08-16 12:15:47.110  8791  8791 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 12:15:47.111  8791  8791 I UEI.SmartControl: configuring settings for MAXQ616
08-16 12:15:47.111  8791  8791 I UEI.SmartControl: Get version...
08-16 12:15:47.128  8791  8851 D UEI.SmartControl: serial port data available: 21
,08-16 12:15:47.157  8791  8791 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-16 12:15:47.157  8791  8791 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-16 12:15:47.158  8791  8791 I UEI.SmartControl: QS saving settings...
,08-16 12:15:47.160  8791  8791 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 12:15:47.177  8791  8851 D UEI.SmartControl: serial port data available: 4
08-16 12:15:47.205  8791  8791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-16 12:15:47.209  8791  8791 E UEI.SmartControl: Services init done
08-16 12:15:47.209  8791  8791 D UEI.SmartControl: QS Service init finished
08-16 12:15:47.210  8791  8791 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 12:15:47.210  8791  8791 D UEI.SmartControl: QS Service version code: 201091
08-16 12:15:47.210  8791  8791 D UEI.SmartControl: Service requested: Control
08-16 12:15:47.213  1036  1058 I ActivityManager: Killing 8413:com.lge.email/u0a23 (adj 15): empty #17
08-16 12:15:47.224  8791  8854 I UEI.SmartControl: Device manager: loading config....
08-16 12:15:47.224  8791  8854 D UEI.SmartControl: ----------- loading internal config...
,08-16 12:15:47.238  8791  8854 E UEI.SmartControl: Loading SETTINGS...
,08-16 12:15:47.251  8791  8854 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 12:15:47.269  1036  1560 W libprocessgroup: failed to open /acct/uid_10023/pid_8413/cgroup.procs: No such file or directory
,08-16 12:15:47.276  8791  8791 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@2be9afc1 that was originally bound here
08-16 12:15:47.276  8791  8791 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@2be9afc1 that was originally bound here
08-16 12:15:47.276  8791  8791 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-16 12:15:47.276  8791  8791 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-16 12:15:47.276  8791  8791 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-16 12:15:47.276  8791  8791 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-16 12:15:47.276  8791  8791 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-16 12:15:47.276  8791  8791 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-16 12:15:47.276  8791  8791 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-16 12:15:47.276  8791  8791 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-16 12:15:47.276  8791  8791 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-16 12:15:47.276  8791  8791 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-16 12:15:47.276  8791  8791 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-16 12:15:47.276  8791  8791 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:15:47.276  8791  8791 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-16 12:15:47.276  8791  8791 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 12:15:47.276  8791  8791 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:15:47.276  8791  8791 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 12:15:47.276  8791  8791 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 12:15:47.276  8791  8791 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-16 12:15:47.276  8791  8853 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 12:15:47.277  8791  8853 D UEI.SmartControl: -----service ready thread exits
08-16 12:15:47.278  8791  8791 D UEI.SmartControl: Internal service binding...
08-16 12:15:47.658  8791  8850 D UEI.SmartControl: Internal timer expired: 2
,08-16 12:15:47.707  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=5.4, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1831234821] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 12:15:47.710  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=5.4, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1831234818] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 12:15:47.710  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 12:15:48.824  6814  6884 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-16 12:15:48.834  6814  6884 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-16 12:15:48.839  6814  6884 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@178e639f Bundle[{}]
08-16 12:15:48.840  6814  6884 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 12:15:48.840  6814  6884 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-16 12:15:48.841  6814  6884 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-16 12:15:48.842  6814  6884 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 12:15:48.842  6814  6884 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-16 12:15:48.843  6814  6884 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-16 12:15:50.735  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1831231794] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 12:15:50.750  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:16] from screen [on:0 period:-1831231778] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 12:15:50.750  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 12:15:50.862  8791  8802 E UEI.SmartControl: file observer is disposed!
,08-16 12:15:52.204  8791  8855 D UEI.SmartControl: Internal timer expired: 3
,08-16 12:15:52.204  8791  8855 D UEI.SmartControl: unbind internal service
,08-16 12:15:52.220  8791  8791 D UEI.SmartControl: Service.onUnbind: IControl
08-16 12:15:52.222  8791  8791 D UEI.SmartControl: Service.onDestroy
08-16 12:15:52.222  8791  8791 D UEI.SmartControl: Lock is in USE false
08-16 12:15:52.222  8791  8791 D UEI.SmartControl: unbind internal service
08-16 12:15:52.223  8791  8791 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1c2e64c0
08-16 12:15:52.223  8791  8791 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-16 12:15:52.223  8791  8791 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-16 12:15:52.223  8791  8791 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-16 12:15:52.223  8791  8791 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-16 12:15:52.223  8791  8791 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-16 12:15:52.223  8791  8791 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-16 12:15:52.223  8791  8791 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-16 12:15:52.223  8791  8791 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-16 12:15:52.223  8791  8791 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:15:52.223  8791  8791 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 12:15:52.223  8791  8791 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 12:15:52.224  8791  8791 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:15:52.224  8791  8791 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 12:15:52.224  8791  8791 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 12:15:52.224  8791  8791 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 12:15:52.224  8791  8791 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1c2e64c0
08-16 12:15:52.226  8791  8791 D serial_port: close(fd = 24)
,08-16 12:15:52.232  8791  8791 I UEI.SmartControl: Serial port is closed.
,08-16 12:15:52.232  8791  8791 I UEI.SmartControl: Serial port is closed.
,08-16 12:15:52.232  8791  8791 D UEI.SmartControl: Blaster closed
08-16 12:15:52.232  8791  8791 D UEI.SmartControl: Shut down QS...
08-16 12:15:52.232  8791  8791 D UEI.SmartControl: Stopping QS lib
08-16 12:15:52.232  8791  8791 D UEI.SmartControl: QS lib stop result = true
08-16 12:15:52.232  8791  8791 D UEI.SmartControl: Stopped QS lib
,08-16 12:15:52.232  8791  8791 D UEI.SmartControl: QS shutdown complete
08-16 12:15:53.772  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1831228756] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 12:15:53.787  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:15] from screen [on:0 period:-1831228741] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 12:15:53.788  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 12:15:56.808  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1831225721] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 12:15:56.811  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1831225718] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 12:15:56.811  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 12:15:58.862  6814  6884 I System.out: Running OutgoingSocketThread
,08-16 12:15:58.875  6814  8856 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-16 12:15:58.876  6814  8856 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-16 12:15:59.837  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1831222691] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 12:15:59.840  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1831222688] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 12:15:59.841  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 12:16:00.002  1036  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=881370966, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,08-16 12:16:00.055  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-16 12:16:00.055  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
08-16 12:16:00.055  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-16 12:16:00.055  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
,08-16 12:16:00.061  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
08-16 12:16:00.061  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
08-16 12:16:00.062  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
08-16 12:16:00.062  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
08-16 12:16:00.067  1036  1110 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=8857 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-16 12:16:00.111  2582  2582 D [Concierge]Service: onStartCommand(). Type : 9
,08-16 12:16:00.183  8857  8857 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 12:16:00.201  8857  8857 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-16 12:16:00.220  8857  8857 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-16 12:16:00.220  8857  8857 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-16 12:16:00.220  8857  8857 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,08-16 12:16:00.220  8857  8857 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-16 12:16:00.220  8857  8857 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-16 12:16:00.222  8857  8857 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-16 12:16:00.225  8857  8857 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-16 12:16:00.230  8857  8857 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-16 12:16:00.231  8857  8857 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:3118
08-16 12:16:00.232  8857  8857 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-16 12:16:00.232  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=881370966 [*alarm*], flags=0x0
08-16 12:16:00.233  8857  8857 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-16 12:16:00.234  8857  8857 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 12:16:00.234  8857  8857 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 12:16:00.235  8857  8857 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-16 12:16:00.271  8857  8857 D LgDataFeature: LgDataFeature() Constructor: none
08-16 12:16:00.272  8857  8857 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 12:16:00.279  8857  8857 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-16 12:16:00.280  8857  8857 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-16 12:16:00.280  8857  8857 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-16 12:16:00.280  8857  8857 V SoundPool: doLoad: loading sample sampleID=1
08-16 12:16:00.281  8857  8857 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 12:16:00.282  8857  8894 V SoundPool: Start decode
08-16 12:16:00.282  8857  8894 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-16 12:16:00.283   315   315 V MediaPlayerService: decode(22, 10857164, 17813)
08-16 12:16:00.283   315   315 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-16 12:16:00.283   315   315 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-16 12:16:00.283   315   315 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-16 12:16:00.283   315   315 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-16 12:16:00.283   315   315 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-16 12:16:00.283   315   315 V MediaPlayerService: player type = 3
08-16 12:16:00.283   315   315 V AwesomePlayer: AwesomePlayer create()
08-16 12:16:00.284   315   315 V AwesomePlayer: reset_l() 
08-16 12:16:00.284   315   315 V AwesomePlayer: cancelPlayerEvents
08-16 12:16:00.284   315   315 V AwesomePlayer: setAudioSink() 
08-16 12:16:00.285   315   315 V AwesomePlayer: reset_l() 
08-16 12:16:00.285   315   315 V AudioCache: notify(0xb54749c0, 8, 0, 0)
08-16 12:16:00.285   315   315 V AudioCache: ignored
08-16 12:16:00.285   315   315 V AwesomePlayer: cancelPlayerEvents
,08-16 12:16:00.285   315   315 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-16 12:16:00.286   315   315 V AwesomePlayer: setDataSource_l dataSource
08-16 12:16:00.286   315   315 V LGParserOSAL: SniffLGParser start
08-16 12:16:00.286   315   315 V LGParserOSAL: MainType:5, SubType=0
08-16 12:16:00.286   315   315 V LGParserOSAL: #### check Mime : application/ogg
08-16 12:16:00.287   315   315 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-16 12:16:00.288  8791  8791 D UEI.SmartControl: QS Service created
08-16 12:16:00.288   315   315 E MediaExtractor: Use LGExtractor :application/ogg 
08-16 12:16:00.296  8857  8857 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-16 12:16:00.297  8857  8857 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-16 12:16:00.298  8857  8857 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 12:16:00.310  8791  8791 I UEI.SmartControl: Service initServices...
08-16 12:16:00.310  8857  8857 V LGMDMManager: Create singleton instance
08-16 12:16:00.310  8791  8791 D UEI.SmartControl: QS start get config
08-16 12:16:00.360   315   315 V LGParserOSAL: supported mime: application/ogg
08-16 12:16:00.360   315   315 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-16 12:16:00.360   315   315 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-16 12:16:00.360   315   315 V AwesomePlayer: mBitrate = -1 bits/sec
08-16 12:16:00.361   315   315 V AwesomePlayer: AudioTrack Setting
08-16 12:16:00.361   315   315 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-16 12:16:00.361   315   315 V AwesomePlayer: setAudioSource() 
08-16 12:16:00.361   315   315 V MediaPlayerService: prepare
08-16 12:16:00.361   315   315 V AwesomePlayer: prepareAsync_l() 
08-16 12:16:00.361   315   315 V MediaPlayerService: wait for prepare
08-16 12:16:00.361   315  8895 V AwesomePlayer: onPrepareAsyncEvent() 
08-16 12:16:00.361   315  8895 V AwesomePlayer: initAudioDecoder() 
08-16 12:16:00.361   315  8895 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 12:16:00.361   315  8895 V AudioSystem: isOffloadSupported()
08-16 12:16:00.361   315  8895 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 12:16:00.361   315  8895 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 12:16:00.361   315  8895 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 12:16:00.361   315  8895 V AwesomePlayer: getUseOffload() = 0 
08-16 12:16:00.361   315  8895 V OMXCodec: OMXCodec::Create
08-16 12:16:00.361   315  8895 V OMXCodec: findMatchingCodecs()
08-16 12:16:00.361   315  8895 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-16 12:16:00.361   315  8895 V OMXCodec: matchingCodecs.size()=1
08-16 12:16:00.361   315  8895 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-16 12:16:00.364   315  8895 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-16 12:16:00.364   315  8895 V LGCodecAdapter: LG Codec Adapter start
08-16 12:16:00.364   315  8895 V OMXCodec: OMXCodec Createtor
08-16 12:16:00.364   315  8895 V OMXCodec: setComponentRole
08-16 12:16:00.364   315  8895 V OMXCodec: configureCodec protected=0
08-16 12:16:00.364   315  8895 V LGCodecAdapter: called getLGCodecSpecificData
08-16 12:16:00.364   315  8895 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-16 12:16:00.364   315  8895 V LGCodecOSAL: Called LGconfigureCodecMETA
08-16 12:16:00.365   315  8895 V LGCodecOSAL: Called LGconfigureCodecMSG
08-16 12:16:00.365   315  8895 V LGCodecOSAL: Not support LGCodec
08-16 12:16:00.365   315  8895 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 12:16:00.365   315  8895 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-16 12:16:00.365   315  8895 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-16 12:16:00.365   315  8895 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-16 12:16:00.365   315  8895 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 12:16:00.365   315  8895 V AudioSystem: isOffloadSupported()
08-16 12:16:00.365   315  8895 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 12:16:00.365   315  8895 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 12:16:00.365   315  8895 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-16 12:16:00.365   315  8895 V OMXCodec: init()
08-16 12:16:00.365   315  8895 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-16 12:16:00.365   315  8895 V OMXCodec: allocateBuffers
08-16 12:16:00.365   315  8895 V OMXCodec: allocateBuffersOnPort portIndex=0
08-16 12:16:00.365   315  8895 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-16 12:16:00.365   315  8895 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-16 12:16:00.365   315  8895 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-16 12:16:00.365   315  8895 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-16 12:16:00.365   315  8895 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
08-16 12:16:00.365   315  8895 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 12:16:00.366   315  8895 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 12:16:00.366   315  8895 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-16 12:16:00.366   315  8895 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-16 12:16:00.366   315  8895 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-16 12:16:00.366   315  8895 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
08-16 12:16:00.366   315  8895 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 12:16:00.366   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 12:16:00.366   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 12:16:00.366   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-16 12:16:00.366   315  8895 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 12:16:00.366   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-16 12:16:00.366   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-16 12:16:00.366   31,5  8897 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-16 12:16:00.366   315  8895 V OMXCodec: init() mAsyncCompletion wait free! 
08-16 12:16:00.366   315  8895 V AwesomePlayer: finishAsyncPrepare_l() 
08-16 12:16:00.366   315  8895 V AudioCache: notify(0xb54749c0, 5, 0, 0)
08-16 12:16:00.366   315  8895 V AudioCache: ignored
08-16 12:16:00.366   315  8895 V AudioCache: notify(0xb54749c0, 1, 0, 0)
08-16 12:16:00.366   315  8895 V AudioCache: prepared
08-16 12:16:00.367   315   315 V AudioCache: wait - success
08-16 12:16:00.367   315   315 V MediaPlayerService: start
08-16 12:16:00.367   315   315 V AwesomePlayer: play_l() 
08-16 12:16:00.367   315   315 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-16 12:16:00.367   315   315 V AwesomePlayer: createAudioPlayer_l
08-16 12:16:00.367   315   315 V AwesomePlayer: seekAudioIfNecessary_l() 
08-16 12:16:00.367   315   315 V AwesomePlayer: startAudioPlayer_l() 
08-16 12:16:00.367   315   315 D AudioPlayer: start of Playback, useOffload 0
08-16 12:16:00.367   315   315 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 12:16:00.367   315   315 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 12:16:00.368   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-16 12:16:00.368   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-16 12:16:00.368   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-16 12:16:00.368   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-16 12:16:00.368   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-16 12:16:00.368   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 12:16:00.368   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-16 12:16:00.368   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 12:16:00.369   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
,08-16 12:16:00.369   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 12:16:00.369   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
08-16 12:16:00.369   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 12:16:00.369   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885888
08-16 12:16:00.369   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 12:16:00.369   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-16 12:16:00.369   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 12:16:00.369   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
,08-16 12:16:00.369   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-16 12:16:00.369   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-16 12:16:00.369   315  8897 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 12:16:00.369   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 12:16:00.369   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
08-16 12:16:00.369   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-16 12:16:00.369   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-16 12:16:00.369   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on output port
08-16 12:16:00.369   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
,08-16 12:16:00.369   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-16 12:16:00.370   315   315 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-16 12:16:00.370   315   315 V AudioCache: notify(0xb54749c0, 6, 0, 0)
08-16 12:16:00.370   315   315 V AudioCache: ignored
08-16 12:16:00.371   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.371   315  8898 V AudioCache: memcpy(0xac300000, 0xb1785000, 4096)
08-16 12:16:00.371   315   315 V MediaPlayerService: wait for playback complete
08-16 12:16:00.372   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.372   315  8898 V AudioCache: memcpy(0xac301000, 0xb1785000, 4096)
08-16 12:16:00.372   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.372   315  8898 V AudioCache: memcpy(0xac302000, 0xb1785000, 4096)
,08-16 12:16:00.373   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.373   315  8898 V AudioCache: memcpy(0xac303000, 0xb1785000, 4096)
08-16 12:16:00.373   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.373   315  8898 V AudioCache: memcpy(0xac304000, 0xb1785000, 4096)
08-16 12:16:00.373   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.373   315  8898 V AudioCache: memcpy(0xac305000, 0xb1785000, 4096)
08-16 12:16:00.373   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.373   315  8898 V AudioCache: memcpy(0xac306000, 0xb1785000, 4096)
,08-16 12:16:00.374   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.374   315  8898 V AudioCache: memcpy(0xac307000, 0xb1785000, 4096)
,08-16 12:16:00.374   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.374   315  8898 V AudioCache: memcpy(0xac308000, 0xb1785000, 4096)
08-16 12:16:00.374   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.374   315  8898 V AudioCache: memcpy(0xac309000, 0xb1785000, 4096)
08-16 12:16:00.374   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.374   315  8898 V AudioCache: memcpy(0xac30a000, 0xb1785000, 4096)
08-16 12:16:00.376   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.376   315  8898 V AudioCache: memcpy(0xac30b000, 0xb1785000, 4096)
08-16 12:16:00.376   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.376   315  8898 V AudioCache: memcpy(0xac30c000, 0xb1785000, 4096)
08-16 12:16:00.377   315  8898 V AudioCache: write(0xb1785000, 4096)
,08-16 12:16:00.377   315  8898 V AudioCache: memcpy(0xac30d000, 0xb1785000, 4096)
08-16 12:16:00.377   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.377   315  8898 V AudioCache: memcpy(0xac30e000, 0xb1785000, 4096)
08-16 12:16:00.378   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.378   315  8898 V AudioCache: memcpy(0xac30f000, 0xb1785000, 4096)
08-16 12:16:00.378   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.378   315  8898 V AudioCache: memcpy(0xac310000, 0xb1785000, 4096)
08-16 12:16:00.379   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.379   315  8898 V AudioCache: memcpy(0xac311000, 0xb1785000, 4096)
08-16 12:16:00.379   315  8898 V AudioCache: write(0xb1785000, 4096)
,08-16 12:16:00.379   315  8898 V AudioCache: memcpy(0xac312000, 0xb1785000, 4096)
08-16 12:16:00.380   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.380   315  8898 V AudioCache: memcpy(0xac313000, 0xb1785000, 4096)
08-16 12:16:00.380   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.380   315  8898 V AudioCache: memcpy(0xac314000, 0xb1785000, 4096)
08-16 12:16:00.380   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.380   315  8898 V AudioCache: memcpy(0xac315000, 0xb1785000, 4096)
08-16 12:16:00.381   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.381   315  8898 V AudioCache: memcpy(0xac316000, 0xb1785000, 4096)
08-16 12:16:00.381   315  8898 V AudioCache: write(0xb1785000, 4096)
,08-16 12:16:00.381   315  8898 V AudioCache: memcpy(0xac317000, 0xb1785000, 4096)
08-16 12:16:00.382   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.382   315  8898 V AudioCache: memcpy(0xac318000, 0xb1785000, 4096)
08-16 12:16:00.382   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.382   315  8898 V AudioCache: memcpy(0xac319000, 0xb1785000, 4096)
08-16 12:16:00.383   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.383   315  8898 V AudioCache: memcpy(0xac31a000, 0xb1785000, 4096)
08-16 12:16:00.383   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.383   315  8898 V AudioCache: memcpy(0xac31b000, 0xb1785000, 4096)
08-16 12:16:00.384   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.384   315  8898 V AudioCache: memcpy(0xac31c000, 0xb1785000, 4096)
08-16 12:16:00.384   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.384   315  8898 V AudioCache: memcpy(0xac31d000, 0xb1785000, 4096)
08-16 12:16:00.384   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.384   315  8898 V AudioCache: memcpy(0xac31e000, 0xb1785000, 4096)
08-16 12:16:00.385   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.385  8857  8857 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 12:16:00.385   315  8898 V AudioCache: memcpy(0xac31f000, 0xb1785000, 4096)
08-16 12:16:00.386   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.386   315  8898 V AudioCache: memcpy(0xac320000, 0xb1785000, 4096)
08-16 12:16:00.386   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.386   315  8898 V AudioCache: memcpy(0xac321000, 0xb1785000, 4096)
08-16 12:16:00.387  8857  8857 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-16 12:16:00.387   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.387   315  8898 V AudioCache: memcpy(0xac322000, 0xb1785000, 4096)
08-16 12:16:00.387   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.387   315  8898 V AudioCache: memcpy(0xac323000, 0xb1785000, 4096)
08-16 12:16:00.388   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.388   315  8898 V AudioCache: memcpy(0xac324000, 0xb1785000, 4096)
08-16 12:16:00.388   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.388   315  8898 V AudioCache: memcpy(0xac325000, 0xb1785000, 4096)
08-16 12:16:00.389   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.389   315  8898 V AudioCache: memcpy(0xac326000, 0xb1785000, 4096)
08-16 12:16:00.389   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.389   315  8898 V AudioCache: memcpy(0xac327000, 0xb1785000, 4096)
,08-16 12:16:00.390   315  8898 V AudioCache: write(0xb1785000, 4096)
,08-16 12:16:00.390   315  8898 V AudioCache: memcpy(0xac328000, 0xb1785000, 4096)
08-16 12:16:00.390   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.390   315  8898 V AudioCache: memcpy(0xac329000, 0xb1785000, 4096)
08-16 12:16:00.391   315  8898 V AudioCache: write(0xb1785000, 4096)
,08-16 12:16:00.391   315  8898 V AudioCache: memcpy(0xac32a000, 0xb1785000, 4096)
08-16 12:16:00.391  8857  8857 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7771
,08-16 12:16:00.391   315  8898 V AudioCache: write(0xb1785000, 4096)
,08-16 12:16:00.391   315  8898 V AudioCache: memcpy(0xac32b000, 0xb1785000, 4096)
08-16 12:16:00.392   315  8898 V AudioCache: write(0xb1785000, 4096)
,08-16 12:16:00.392   315  8898 V AudioCache: memcpy(0xac32c000, 0xb1785000, 4096)
,08-16 12:16:00.392   315  8898 V AudioCache: write(0xb1785000, 4096)
08-16 12:16:00.392   315  8898 V AudioCache: memcpy(0xac32d000, 0xb1785000, 4096),
08-16 12:16:00.393   315  8898 V AudioCache: write(0xb1785000, 4096)
,08-16 12:16:00.393   315  8898 V AudioCache: memcpy(0xac32e000, 0xb1785000, 4096)
08-16 12:16:00.393   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-16 12:16:00.393   315  8898 V AudioCache: write(0xb1785000, 4096),
,08-16 12:16:00.393   315  8898 V AudioCache: memcpy(0xac32f000, 0xb1785000, 4096)
08-16 12:16:00.393   315  8898 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 12:16:00.393   315  8898 V AudioCache: write(0xb1785000, 4096),
08-16 12:16:00.393   315  8898 V AudioCache: memcpy(0xac330000, 0xb1785000, 4096)
08-16 12:16:00.393   315  8898 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 12:16:00.393   315  8898 V AudioCache: write(0xb1785000, 4096),
08-16 12:16:00.393   315  8898 V AudioCache: memcpy(0xac331000, 0xb1785000, 4096)
08-16 12:16:00.393   315  8898 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
,08-16 12:16:00.393   315  8898 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 12:16:00.393   315  8898 V AwesomePlayer: postAudioEOS() 
08-16 12:16:00.394   315  8898 V AudioCache: write(0xb1785000, 280)
,08-16 12:16:00.394   315  8898 V AudioCache: memcpy(0xac332000, 0xb1785000, 280)
08-16 12:16:00.395   315  8895 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-16 12:16:00.395   315  8895 V AwesomePlayer: onStreamDone,
08-16 12:16:00.395   315  8895 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-16 12:16:00.395   315  8895 V AudioCache: notify(0xb54749c0, 2, 0, 0)
,08-16 12:16:00.395   315  8895 V AudioCache: playback complete
08-16 12:16:00.395   315  8895 V AwesomePlayer: pause_l() 
08-16 12:16:00.395   315  8895 V AudioCache: notify(0xb54749c0, 7, 0, 0)
,08-16 12:16:00.395   315  8895 V AudioCache: ignored
08-16 12:16:00.395   315  8895 V AwesomePlayer: cancelPlayerEvents
08-16 12:16:00.395   315   315 V AudioCache: wait - success,
08-16 12:16:00.395   315   315 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-16 12:16:00.396   315  8895 D AudioPlayer: Pause Playback at 1068125
,08-16 12:16:00.396   315   315 V AwesomePlayer: reset_l() 
08-16 12:16:00.396   315   315 V AudioCache: notify(0xb54749c0, 8, 0, 0)
08-16 12:16:00.396   315   315 V AudioCache: ignored
,08-16 12:16:00.396   315   315 V AwesomePlayer: cancelPlayerEvents
08-16 12:16:00.396   315   315 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-16 12:16:00.396   315   315 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
,08-16 12:16:00.396   315   315 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-16 12:16:00.396   315   315 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-16 12:16:00.396   315   315 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
,08-16 12:16:00.396   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 12:16:00.396   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 12:16:00.396   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0,
08-16 12:16:00.396   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
08-16 12:16:00.396   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
,08-16 12:16:00.396   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-16 12:16:00.397   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
,08-16 12:16:00.397   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
,08-16 12:16:00.397   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1,
08-16 12:16:00.397   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-16 12:16:00.397   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-16 12:16:00.397   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
,08-16 12:16:00.397   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 1
08-16 12:16:00.397   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-16 12:16:00.397   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-16 12:16:00.397   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-16 12:16:00.397   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
08-16 12:16:00.397   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-16 12:16:00.397   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 1
08-16 12:16:00.397   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-16 12:16:00.397   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-16 12:16:00.397   315   315 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 12:16:00.397   315   315 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 12:16:00.397   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-16 12:16:00.397   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-16 12:16:00.397   315  8897 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-16 12:16:00.398   315   315 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 12:16:00.398   315   315 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
,08-16 12:16:00.398   315   315 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-16 12:16:00.398   315   315 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-16 12:16:00.399   315   315 D AudioPlayer: AudioPlayer releasing audio source
08-16 12:16:00.399   315   315 D AudioPlayer: AudioPlayer done releasing audio source
08-16 12:16:00.399   315   315 V AwesomePlayer: reset_l() 
08-16 12:16:00.399   315   315 V AwesomePlayer: cancelPlayerEvents
08-16 12:16:00.399   315   315 V AwesomePlayer: ~AwesomePlayer call
,08-16 12:16:00.399   315   315 V AwesomePlayer: reset_l() 
08-16 12:16:00.399   315   315 V AwesomePlayer: cancelPlayerEvents
08-16 12:16:00.399  8857  8894 V SoundPool: close(31)
08-16 12:16:00.399  8857  8894 V SoundPool: pointer = 0xa000e000, size = 205080, sampleRate = 48000, numChannels = 2
08-16 12:16:00.766  8791  8791 I UEI.SmartControl: Supports setup maps: true
08-16 12:16:00.772  8791  8791 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 12:16:00.772  8791  8791 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 12:16:00.773  8791  8791 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-16 12:16:00.773  8791  8791 I UEI.SmartControl: ### init IR Blaster...
08-16 12:16:00.777  8791  8791 D serial_port: Configuring serial port
08-16 12:16:00.777  8791  8791 E UEI.SmartControl: UEIBLaster setting for 616
08-16 12:16:00.777  8791  8791 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 12:16:00.777  8791  8791 I UEI.SmartControl: configuring settings for MAXQ616
08-16 12:16:00.777  8791  8791 I UEI.SmartControl: Get version...
08-16 12:16:00.793  8791  8906 D UEI.SmartControl: serial port data available: 21
,08-16 12:16:00.819  8791  8791 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-16 12:16:00.819  8791  8791 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 12:16:00.819  8791  8791 I UEI.SmartControl: QS saving settings...
08-16 12:16:00.820  8791  8791 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 12:16:00.837  8791  8906 D UEI.SmartControl: serial port data available: 4
,08-16 12:16:00.870  8791  8791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-16 12:16:00.870  8791  8909 I UEI.SmartControl: Device manager: loading config....
08-16 12:16:00.871  8791  8909 D UEI.SmartControl: ----------- loading internal config...
,08-16 12:16:00.880  8791  8791 E UEI.SmartControl: Services init done
,08-16 12:16:00.880  8791  8791 D UEI.SmartControl: QS Service init finished
08-16 12:16:00.880  8791  8909 E UEI.SmartControl: Loading SETTINGS...
08-16 12:16:00.885  8791  8791 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 12:16:00.885  8791  8791 D UEI.SmartControl: QS Service version code: 201091
08-16 12:16:00.886  8791  8791 D UEI.SmartControl: Service requested: Control
08-16 12:16:00.888  8791  8909 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 12:16:00.891  8857  8857 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-16 12:16:00.893  8791  8806 I UEI.SmartControl: ------ IControl API: 11
08-16 12:16:00.893  8791  8806 D UEI.SmartControl: File observer start...
08-16 12:16:00.894  8791  8806 E UEI.SmartControl: IR Port is disabled: false
08-16 12:16:00.894  8791  8806 D UEI.SmartControl: Starting file observer...
08-16 12:16:00.895  8791  8791 D UEI.SmartControl: Internal service binding...
,08-16 12:16:00.900  8791  8806 I UEI.SmartControl: Registering callback...
08-16 12:16:00.900  8791  8807 I UEI.SmartControl: ------ IControl API: 19
08-16 12:16:00.901  8791  8807 I UEI.SmartControl: Registering Services Ready callback...
08-16 12:16:00.902  8791  8807 I UEI.SmartControl: Notify client services are ready...
08-16 12:16:00.902  8857  8872 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-16 12:16:00.903  8857  8892 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-16 12:16:00.903  8857  8892 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-16 12:16:00.903  8857  8857 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-16 12:16:00.904  8857  8857 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-16 12:16:00.904  8791  8806 I UEI.SmartControl: ------ IControl API: 8
08-16 12:16:00.906  8857  8857 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-16 12:16:00.906  8857  8857 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-16 12:16:00.906  8857  8857 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-16 12:16:00.907  8857  8857 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-16 12:16:00.908  8857  8857 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-16 12:16:00.909  8857  8857 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-16 12:16:00.909  8791  8908 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-16 12:16:00.912  8857  8873 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-16 12:16:00.912  8857  8892 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-16 12:16:00.913  8857  8892 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-16 12:16:00.913  8791  8908 D UEI.SmartControl: -----service ready thread exits
08-16 12:16:00.914  8857  8857 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-16 12:16:00.915  8857  8857 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
08-16 12:16:00.916  8857  8857 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 12:16:00.916  8857  8857 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 12:16:00.917  8857  8857 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-16 12:16:00.918  8857  8857 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 12:16:00.919  8857  8857 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 12:16:00.920  8857  8857 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-16 12:16:00.920  8857  8857 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,08-16 12:16:00.921  8857  8857 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471342560921]
,08-16 12:16:00.930  8857  8857 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-16 12:16:00.934  1036  1944 I ActivityManager: Killing 8173:com.lge.formmanager/u0a26 (adj 15): empty #17
08-16 12:16:00.956  8857  8911 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-16 12:16:01.048  1036  2018 W libprocessgroup: failed to open /acct/uid_10026/pid_8173/cgroup.procs: No such file or directory
,08-16 12:16:01.061  8857  8857 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-16 12:16:01.063  8857  8857 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 12:16:01.064  8857  8857 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-16 12:16:01.066  8857  8857 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-16 12:16:01.067  8857  8857 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-16 12:16:01.068  8857  8857 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-16 12:16:01.069  8857  8857 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-16 12:16:01.091  8857  8857 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-16 12:16:01.878  6814  8856 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-16 12:16:01.878  6814  8856 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-16 12:16:01.878  6814  8856 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 12:16:01.882  6814  8856 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 12:16:01.882  6814  8856 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-16 12:16:01.884  6814  8933 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-16 12:16:01.884  6814  8933 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-16 12:16:01.884  6814  8933 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 12:16:01.884  6814  8933 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 12:16:01.884  6814  8933 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-16 12:16:01.887  6814  8936 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 910, name: OutgoingSocketThread/Receiver)
08-16 12:16:01.887  6814  8936 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 910, thread name: OutgoingSocketThread/Receiver)
08-16 12:16:01.887  6814  8936 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-16 12:16:01.887  6814  8936 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 910, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-16 12:16:01.889  6814  8935 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 909, name: OutgoingSocketThread/Sender)
08-16 12:16:01.890  6814  8937 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 911, name: IncomingSocketThread/Sender)
08-16 12:16:01.893  6814  8938 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 912, name: IncomingSocketThread/Receiver)
08-16 12:16:01.894  6814  8938 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 912, thread name: IncomingSocketThread/Receiver)
08-16 12:16:01.894  6814  8938 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-16 12:16:01.894  6814  8938 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 912, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-16 12:16:02.868  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1831219660] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 12:16:02.871  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1831219657] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 12:16:02.871  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 12:16:05.853  8791  8907 D serial_port: close(fd = 24)
,08-16 12:16:05.864  8791  8907 I UEI.SmartControl: Serial port is closed.
08-16 12:16:05.868  8791  8910 D UEI.SmartControl: Internal timer expired: 4
08-16 12:16:05.868  8791  8910 D UEI.SmartControl: unbind internal service
08-16 12:16:05.896  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1831216632] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 12:16:05.897  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1831216631] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 12:16:05.897  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 12:16:08.918  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1831213610] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 12:16:08.921  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1831213607] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 12:16:08.921  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 12:16:09.559  1036  1523 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,08-16 12:16:09.560  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
08-16 12:16:09.561  1036  1523 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
08-16 12:16:09.563  1036  1523 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
08-16 12:16:09.564  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,08-16 12:16:09.574  1036  1523 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 3 0
,08-16 12:16:09.884  6814  6884 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 921)
,08-16 12:16:09.896  6814  6884 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-16 12:16:09.896  6814  6884 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 922)
,08-16 12:16:11.944  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1831210584] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 12:16:11.956  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1831210572] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 12:16:11.956  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 12:16:14.902  6814  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 12:16:14.902  6814  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1067f0d3 added. We now have 3 listener(s)
,08-16 12:16:14.913  1036  1872 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:16:14.918  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 12:16:14.918  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:16:14.919  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:16:14.919  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:16:14.919  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd40410 added. We now have 4 listener(s)
08-16 12:16:14.919  6814  6884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:16:14.921  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 12:16:14.927  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:16:14.931  6814  6884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:16:14.931  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:16:14.931  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:16:14.931  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:16:14.931  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:16:14.931  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:16:14.931  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:16:14.931  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:16:14.933  6814  6884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:16:14.933  6814  6884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 12:16:14.939  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:16:14.941  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:16:14.941  6814  6884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:16:14.941  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:16:14.941  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:16:14.942  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:16:14.942  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:16:14.942  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 12:16:14.942  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:16:14.942  6814  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1067f0d3 removed from the list
08-16 12:16:14.942  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:16:14.942  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd40410 removed from the list
08-16 12:16:14.942  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:16:14.942  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:16:14.943  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:16:14.943  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:16:14.944  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:16:14.944  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:16:14.944  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:16:14.944  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd40410 not in the list
08-16 12:16:14.944  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:16:14.944  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:16:14.945  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:16:14.946  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:16:14.946  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:16:14.946  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd40410 not in the list
08-16 12:16:14.946  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:16:14.946  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:16:14.946  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: relea,se: 2 listener(s) left
08-16 12:16:14.946  6814  6884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1067f0d3 not in the list
08-16 12:16:14.947  6814  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:16:14.947  6814  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c63610e added. We now have 3 listener(s)
08-16 12:16:14.950  1036  1058 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 12:16:14.957  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 12:16:14.957  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:16:14.957  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:16:14.957  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:16:14.957  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb6c72f added. We now have 4 listener(s)
08-16 12:16:14.957  6814  6884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:16:14.958  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 12:16:14.961  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:16:14.966  6814  6884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:16:14.966  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:16:14.966  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:16:14.966  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:16:14.966  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:16:14.966  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:16:14.966  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:16:14.966  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:16:14.970  6814  6884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:16:14.970  6814  6884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:16:14.972  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:16:14.974  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:16:14.976  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1831207552] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 12:16:14.977  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1831207551] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 12:16:14.977  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 12:16:14.978  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:16:14.978  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 12:16:14.978  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 12:16:14.978  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:16:14.978  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 12:16:14.985  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 12:16:14.985  1036  1560 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:16:14.991  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 12:16:14.995  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 12:16:14.997  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 12:16:14.997  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 12:16:14.999  6814  6884 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 12:16:14.999  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:16:14.999  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:16:17.997  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1831204531] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 12:16:18.009  6814  6884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:16:18.009  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:16:18.009  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:16:18.009  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:16:18.010  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:16:18.010  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 12:16:18.010  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:16:18.010  6814  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c63610e removed from the list
08-16 12:16:18.010  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:16:18.010  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb6c72f removed from the list
08-16 12:16:18.010  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:16:18.010  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:16:18.011  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:16:18.011  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:16:18.012  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:16:18.012  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:16:18.013  6814  6884 D BluetoothLeScanner: could not find callback wrapper
08-16 12:16:18.013  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:16:18.013  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:16:18.013  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb6c72f not in the list
08-16 12:16:18.013  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:16:18.013  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:16:18.014  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:16:18.016  6814  6884 D BluetoothLeScanner: could not find callback wrapper
08-16 12:16:18.016  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:16:18.016  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:16:18.016  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:16:18.016  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb6c72f not in the list
08-16 12:16:18.016  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:16:18.016  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener d,oes not exist in the list - probably already removed
08-16 12:16:18.016  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:16:18.016  6814  6884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c63610e not in the list
08-16 12:16:18.017  6814  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:16:18.017  6814  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3872a74b added. We now have 3 listener(s)
08-16 12:16:18.019  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:21] from screen [on:0 period:-1831204510] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 12:16:18.019  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 12:16:18.023  1036  1872 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:16:18.027  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 12:16:18.027  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:16:18.027  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:16:18.027  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:16:18.027  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cc4528 added. We now have 4 listener(s)
08-16 12:16:18.027  6814  6884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:16:18.029  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 12:16:18.033  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:16:18.042  6814  6884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:16:18.042  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:16:18.042  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:16:18.042  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:16:18.042  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:16:18.042  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:16:18.042  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:16:18.042  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:16:18.044  6814  6884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:16:18.045  6814  6884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:16:18.047  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:16:18.049  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:16:18.051  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-16 12:16:18.052  6814  6884 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-16 12:16:18.052  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-16 12:16:18.054  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-16 12:16:18.054  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-16 12:16:18.054  6814  6884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 12:16:18.055  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:16:18.057  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 12:16:18.058  6814  6884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 12:16:18.058  6814  6884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 12:16:18.059  6814  6814 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 12:16:18.061  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 12:16:18.061  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-16 12:16:18.061  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:16:18.061  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 12:16:18.069  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 12:16:18.070  1036  1058 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:16:18.076  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 12:16:18.078  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 12:16:18.080  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 12:16:18.082  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 12:16:18.083  6814  6884 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 12:16:18.085  1036  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:16:18.088  6814  8939 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 12:16:18.091  7990  8006 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-16 12:16:18.092  6814  8939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-16 12:16:21.041  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1831201487] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 12:16:21.044  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1831201484] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 12:16:21.044  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 12:16:21.088  6814  6884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 12:16:21.089  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:16:21.089  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 12:16:21.089  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 12:16:21.089  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 12:16:21.089  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-16 12:16:21.102  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 12:16:21.102  6814  6884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 12:16:21.104  6814  8939 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-16 12:16:21.104  6814  8939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 12:16:21.104  6814  8939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 12:16:21.107  6814  6814 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 12:16:21.108  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 12:16:21.108  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:16:21.108  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 12:16:21.110  6814  6814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:16:21.111  6814  6814 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-16 12:16:21.111  6814  6814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-16 12:16:21.114  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:16:21.114  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:16:21.114  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 12:16:21.114  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:16:21.114  6814  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3872a74b removed from the list
08-16 12:16:21.114  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:16:21.114  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cc4528 removed from the list
08-16 12:16:21.114  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:16:21.114  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:16:21.115  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:16:21.115  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:16:21.117  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:16:21.117  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:16:21.118  6814  6884 D BluetoothLeScanner: could not find callback wrapper
08-16 12:16:21.118  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:16:21.118  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:16:21.118  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cc4528 not in the list
08-16 12:16:21.118  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:16:21.118  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:16:21.122  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:16:21.123  6814  6884 D BluetoothLeScanner: could not find callback wrapper
08-16 12:16:21.123  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:16:21.123  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:16:21.123  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:16:21.123  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cc4528 not in the list
08-16 12:16:21.123  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:16:21.123  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:16:21.123  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:16:21.123  6814  6884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3872a74b not in the list
08-16 12:16:21.124  6814  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:16:21.124  681,4  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f348bd4 added. We now have 3 listener(s)
,08-16 12:16:21.128  1036  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:16:21.132  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 12:16:21.132  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:16:21.132  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:16:21.132  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:16:21.132  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f2517d added. We now have 4 listener(s)
08-16 12:16:21.132  6814  6884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:16:21.134  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 12:16:21.138  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:16:21.143  6814  6884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:16:21.143  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:16:21.143  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:16:21.143  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:16:21.143  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:16:21.143  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:16:21.143  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:16:21.143  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:16:21.145  6814  6884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:16:21.145  6814  6884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:16:21.148  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:16:21.150  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:16:21.152  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:16:21.152  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 12:16:21.152  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 12:16:21.152  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:16:21.152  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 12:16:21.156  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 12:16:21.158  1036  1771 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:16:21.162  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 12:16:21.164  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 12:16:21.167  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 12:16:21.167  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 12:16:21.169  6814  6884 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 12:16:24.073  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1831198455] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 12:16:24.086  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1831198442] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 12:16:24.086  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 12:16:24.186  6814  6884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 12:16:24.190  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:16:24.190  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:16:24.190  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:16:24.190  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:16:24.191  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 12:16:24.191  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:16:24.191  6814  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f348bd4 removed from the list
08-16 12:16:24.191  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:16:24.191  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f2517d removed from the list
08-16 12:16:24.191  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:16:24.191  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:16:24.192  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:16:24.192  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:16:24.193  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:16:24.193  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:16:24.194  6814  6884 D BluetoothLeScanner: could not find callback wrapper
08-16 12:16:24.194  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:16:24.194  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:16:24.194  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f2517d not in the list
08-16 12:16:24.194  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:16:24.194  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:16:24.195  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:16:24.196  6814  6884 D BluetoothLeScanner: could not find callback wrapper
08-16 12:16:24.196  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:16:24.196  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:16:24.196  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:16:24.196  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f2517d not in the list
08-16 12:16:24.196  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:16:24.196  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:16:24.196  6814  6884 D org.thaliproject.p2p.btconnector,lib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:16:24.196  6814  6884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f348bd4 not in the list
08-16 12:16:24.197  6814  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:16:24.197  6814  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d78879 added. We now have 3 listener(s)
08-16 12:16:24.197  1036  1637 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 12:16:24.200  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 12:16:24.200  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:16:24.200  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:16:24.200  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:16:24.200  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df029be added. We now have 4 listener(s)
08-16 12:16:24.201  6814  6884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 12:16:24.207  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 12:16:24.212  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:16:24.215  6814  6884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:16:24.215  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:16:24.215  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 12:16:24.215  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:16:24.215  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:16:24.215  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:16:24.215  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:16:24.215  6814  6884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:16:24.220  6814  6884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:16:24.220  6814  6884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:16:24.223  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:16:24.225  6814  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:16:24.226  6814  6884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:16:24.226  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:16:24.226  6814  6884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:16:24.227  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:16:24.227  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:16:24.227  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 12:16:24.227  6814  6884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:16:24.227  6814  6884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d78879 removed from the list
08-16 12:16:24.227  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:16:24.227  6814  6884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df029be removed from the list
08-16 12:16:24.227  6814  6884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:16:24.227  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:16:24.228  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:16:24.228  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:16:24.232  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:16:24.232  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 12:16:24.232  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:16:24.233  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df029be not in the list
,08-16 12:16:24.233  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:16:24.233  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:16:24.234  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:16:24.234  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:16:24.234  6814  6884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:16:24.234  6814  6884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df029be not in the list
08-16 12:16:24.234  6814  6884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:16:24.234  6814  6884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:16:24.234  6814  6884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:16:24.234  6814  6884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d78879 not in the list
,08-16 12:16:26.156  1036  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3db6245c type 2 when 456180 com.google.android.gms} when 456180
,08-16 12:16:26.184  8857  8857 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-16 12:16:26.185  8857  8857 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:7771
,08-16 12:16:26.213  2168  2168 I ConfigService: onCreate
,08-16 12:16:26.216  2168  2168 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-16 12:16:26.220  1802  1802 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-16 12:16:26.236  1802  8941 I ConfigFetchService: running network task: configservice_periodic
,08-16 12:16:26.240  1802  8941 I ConfigFetchService: launchTask
08-16 12:16:26.246  2168  2168 I ConfigService: onBind returning update interface
08-16 12:16:26.248  1802  1802 I ConfigFetchService: service connected
08-16 12:16:26.249  2168  2168 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-16 12:16:26.249  2168  2168 I ConfigService: onBind returning config service
,08-16 12:16:26.252  1802  1802 I ConfigClient: service connected
08-16 12:16:26.330  1036  1060 V SIM_STK : Menu title from STK is T-Mobile
,08-16 12:16:26.345  1802  8942 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-16 12:16:26.350   311  8953 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-16 12:16:26.350   311  8953 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-16 12:16:26.350   311  8953 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-16 12:16:26.588  1802  8942 W ConfigFetchTask: bad response from server: 401 Unauthorized
08-16 12:16:26.591  1802  1802 I ConfigFetchService: fetch service done; releasing wakelock
,08-16 12:16:26.595  1802  1802 I ConfigFetchService: stopping self
08-16 12:16:26.628  2168  2168 I ConfigService: onDestroy
,08-16 12:16:27.105  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1831195424] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 12:16:27.117  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1831195411] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 12:16:27.117  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 12:16:29.237  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 12:16:29.238  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 12:16:29.238  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 12:16:29.239  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:16:29.239  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 12:16:29.240  6814  6884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 12:16:30.136  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1831192392] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 12:16:30.139  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1831192389] gl rssi=-56 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 12:16:30.139  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 12:16:33.166  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1831189363] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 12:16:33.169  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1831189360] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 12:16:33.169  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 12:16:36.194  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1831186334] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 12:16:36.205  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1831186324] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 12:16:36.206  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 12:16:36.280  6814  8961 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 931, name: My test thread name)
,08-16 12:16:38.276  6814  6884 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 931
08-16 12:16:38.277  6814  6884 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 931, name: My test thread name)
,08-16 12:16:38.292  6814  8962 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 932, name: My test thread name)
08-16 12:16:38.292  6814  8962 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 932, thread name: My test thread name)
08-16 12:16:38.292  6814  8962 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 932, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
08-16 12:16:38.297  6814  6884 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 12:16:38.303  6814  8963 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 936, name: My test thread name)
08-16 12:16:38.303  6814  8963 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 936, thread name: My test thread name): Test exception.
08-16 12:16:38.303  6814  8963 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 936, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-16 12:16:38.310  6814  6884 I jxcore-log: Total number of executed tests:  82
08-16 12:16:38.310  6814  6884 I jxcore-log: 
08-16 12:16:38.310  6814  6884 I jxcore-log: Number of passed tests:  82
08-16 12:16:38.310  6814  6884 I jxcore-log: 
08-16 12:16:38.310  6814  6884 I jxcore-log: Number of failed tests:  0
08-16 12:16:38.310  6814  6884 I jxcore-log: 
08-16 12:16:38.310  6814  6884 I jxcore-log: Number of ignored tests:  0
08-16 12:16:38.310  6814  6884 I jxcore-log: 
08-16 12:16:38.311  6814  6884 I jxcore-log: Total duration:  146794
08-16 12:16:38.311  6814  6884 I jxcore-log: 
08-16 12:16:38.311  6814  6884 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-16 12:16:38.311  6814  6884 I jxcore-log: 
08-16 12:16:38.327  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:16:38.327  6814  6884 I jxcore-log: 
08-16 12:16:38.330  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:16:38.330  6814  6884 I jxcore-log: 
08-16 12:16:38.331  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:16:38.331  6814  6884 I jxcore-log: 
,08-16 12:16:38.334  6814  8961 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 931, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
08-16 12:16:38.343  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:16:38.343  6814  6884 I jxcore-log: 
08-16 12:16:38.344  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:16:38.344  6814  6884 I jxcore-log: 
,08-16 12:16:38.353  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:16:38.353  6814  6884 I jxcore-log: 
08-16 12:16:38.357  6814  6814 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-16 12:16:38.360  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 12:16:38.360  6814  6884 I jxcore-log: 
08-16 12:16:38.362  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 12:16:38.362  6814  6884 I jxcore-log: 
08-16 12:16:38.363  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 12:16:38.363  6814  6884 I jxcore-log: 
08-16 12:16:38.364  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 12:16:38.364  6814  6884 I jxcore-log: 
08-16 12:16:38.365  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:16:38.365  6814  6884 I jxcore-log: 
08-16 12:16:38.367  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:16:38.367  6814  6884 I jxcore-log: 
08-16 12:16:38.368  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:16:38.368  6814  6884 I jxcore-log: 
08-16 12:16:38.369  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 12:16:38.369  6814  6884 I jxcore-log: 
08-16 12:16:38.370  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 12:16:38.370  6814  6884 I jxcore-log: 
08-16 12:16:38.370  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 12:16:38.370  6814  6884 I jxcore-log: 
08-16 12:16:38.371  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:16:38.371  6814  6884 I jxcore-log: 
08-16 12:16:38.372  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:16:38.372  6814  6884 I jxcore-log: 
08-16 12:16:38.373  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:16:38.373  6814  6884 I jxcore-log: 
08-16 12:16:38.374  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:16:38.374  6814  6884 I jxcore-log: 
08-16 12:16:38.374  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:16:38.374  6814  6884 I jxcore-log: 
08-16 12:16:38.376  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:16:38.376  6814  6884 I jxcore-log: 
08-16 12:16:38.377  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 12:16:38.377  6814  6884 I jxcore-log: 
08-16 12:16:38.377  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wif,i":"off","cellular":"doNotCare"}
08-16 12:16:38.377  6814  6884 I jxcore-log: 
08-16 12:16:38.378  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 12:16:38.378  6814  6884 I jxcore-log: 
08-16 12:16:38.379  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:16:38.379  6814  6884 I jxcore-log: 
08-16 12:16:38.380  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:16:38.380  6814  6884 I jxcore-log: 
08-16 12:16:38.380  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:16:38.380  6814  6884 I jxcore-log: 
08-16 12:16:38.381  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 12:16:38.381  6814  6884 I jxcore-log: 
08-16 12:16:38.382  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 12:16:38.382  6814  6884 I jxcore-log: 
08-16 12:16:38.383  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 12:16:38.383  6814  6884 I jxcore-log: 
08-16 12:16:38.383  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 12:16:38.383  6814  6884 I jxcore-log: 
08-16 12:16:38.384  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 12:16:38.384  6814  6884 I jxcore-log: 
,08-16 12:16:38.385  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:16:38.385  6814  6884 I jxcore-log: 
08-16 12:16:38.391  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:16:38.391  6814  6884 I jxcore-log: 
08-16 12:16:38.394  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:16:38.394  6814  6884 I jxcore-log: 
08-16 12:16:38.395  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:16:38.395  6814  6884 I jxcore-log: 
08-16 12:16:38.396  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:16:38.396  6814  6884 I jxcore-log: 
08-16 12:16:38.397  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:16:38.397  6814  6884 I jxcore-log: 
08-16 12:16:38.398  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:16:38.398  6814  6884 I jxcore-log: 
08-16 12:16:38.398  6814  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:16:38.398  6814  6884 I jxcore-log: 
,08-16 12:16:38.651  8964  8964 D AndroidRuntime: 
08-16 12:16:38.651  8964  8964 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-16 12:16:38.655  8964  8964 D AndroidRuntime: CheckJNI is OFF
,08-16 12:16:38.821  8964  8964 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 12:16:38.835  1036  1110 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-16 12:16:38.836  1036  1110 I ActivityManager: Killing 6814:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-16 12:16:38.878  1036  1637 I WindowState: WIN DEATH: Window{23f9c0f6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 12:16:38.879  1036  1529 D WifiService: Client connection lost with reason: 4
08-16 12:16:38.888  1036  1637 D InputDispatcher: Window went away: Window{23f9c0f6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 12:16:38.967  1036  1110 I ActivityManager:   Force finishing activity ActivityRecord{2a0a6db3 u0 com.test.thalitest/.MainActivity t6}
,08-16 12:16:38.998   340   350 E GBMv2   : DFP En is all cleared set to be enabled
,08-16 12:16:39.015  1036  1907 W ActivityManager: Spurious death for ProcessRecord{3979adbf 6814:com.test.thalitest/u0a118}, curProc for 6814: null
,08-16 12:16:39.016  1036  1125 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-16 12:16:39.019  1036  1125 I ActivityManager:   Force finishing activity ActivityRecord{2a0a6db3 u0 com.test.thalitest/.MainActivity t6 f}
08-16 12:16:39.019  1036  1125 W ActivityManager: Duplicate finish request for ActivityRecord{2a0a6db3 u0 com.test.thalitest/.MainActivity t6 f}
,08-16 12:16:39.060  1926  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-16 12:16:39.060  2019  2019 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-16 12:16:39.060  1926  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1ca83636 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-16 12:16:39.062  2019  2019 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-16 12:16:39.063  1926  3157 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-16 12:16:39.063  1926  3157 D SplitWindowPolicy: topRunningActivity=ActivityInfo{17e7b937 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-16 12:16:39.064  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-16 12:16:39.066  2019  2109 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-16 12:16:39.071  1890  1890 D ActionManagerService: notifyUserLog: 1000003
08-16 12:16:39.071  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-16 12:16:39.073  3771  4929 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-16 12:16:39.074  1587  1587 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-16 12:16:39.082  1036  1442 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 12:16:39.107  1981  1981 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-16 12:16:39.108  3771  3771 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-16 12:16:39.108  2466  2639 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-16 12:16:39.112  7990  7990 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-16 12:16:39.112  7990  7990 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-16 12:16:39.125  4937  4937 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-16 12:16:39.125  4937  4937 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-16 12:16:39.125  4937  4937 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-16 12:16:39.125  4937  4937 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-16 12:16:39.125  4937  4937 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 12:16:39.126  4937  4937 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 12:16:39.126  4937  4937 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 12:16:39.126  4937  4937 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 12:16:39.126  4937  4937 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:16:39.126  4937  4937 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 12:16:39.126  4937  4937 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 12:16:39.126  4937  4937 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 12:16:39.136  1036  2018 V SIM_STK : Menu title from STK is T-Mobile
,08-16 12:16:39.161  2019  2019 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-16 12:16:39.163  5051  5051 I art     : Explicit concurrent mark sweep GC freed 15446(886KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 422us total 139.950ms
08-16 12:16:39.164  2019  2019 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-16 12:16:39.165  8242  8242 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-16 12:16:39.166  2019  2019 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-16 12:16:39.183  1587  1587 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-16 12:16:39.195  1802  1802 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-16 12:16:39.196  1587  1650 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 12:16:39.196  1587  1650 D KeyguardModel: createShortcutInfo...
,08-16 12:16:39.212  1036  1036 I art     : Explicit concurrent mark sweep GC freed 29497(1668KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.137ms total 178.962ms
08-16 12:16:39.213  1587  1650 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 12:16:39.213  1587  1650 D KeyguardModel: createShortcutInfo...
08-16 12:16:39.220  1036  1125 I art     : WaitForGcToComplete blocked for 57.753ms for cause Explicit
08-16 12:16:39.220  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-16 12:16:39.221  1890  1890 D ActionManagerService: notifyUserLog: 1000004
08-16 12:16:39.221  1587  1650 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-16 12:16:39.222  1587  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 12:16:39.222  1587  1650 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 12:16:39.223  1587  1650 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 12:16:39.223  3771  4929 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-16 12:16:39.240  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3021] from screen [on:0 period:-1831183288] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 12:16:39.241  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-56 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1831183288] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 12:16:39.241  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 12:16:39.242  3771  3788 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 12:16:39.243  2168  2168 I ConfigService: onCreate
08-16 12:16:39.245  1036  1943 V SIM_STK : Menu title from STK is T-Mobile
08-16 12:16:39.245  1036  1943 V SIM_STK : Menu title from STK is T-Mobile
08-16 12:16:39.246  2168  2168 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-16 12:16:39.246  1587  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 12:16:39.246  1587  1650 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-16 12:16:39.247  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-16 12:16:39.247  2019  2019 I GBoardWebViewUtils: , create_time: 1430832262123
08-16 12:16:39.247  2019  2019 I GBoardWebViewUtils: , expire_time: 0
08-16 12:16:39.247  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-16 12:16:39.247  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-16 12:16:39.247  2019  2019 I GBoardWebViewUtils: , display: false
08-16 12:16:39.247  2019  2019 I GBoardWebViewUtils: , animation: false }
08-16 12:16:39.247  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-16 12:16:39.247  2019  2019 I GBoardWebViewUtils: , create_time: 1430832262287
08-16 12:16:39.247  2019  2019 I GBoardWebViewUtils: , expire_time: 0
08-16 12:16:39.247  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 12:16:39.247  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 12:16:39.247  2019  2019 I GBoardWebViewUtils: , display: false
08-16 12:16:39.247  2019  2019 I GBoardWebViewUtils: , animation: false }
08-16 12:16:39.247  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-16 12:16:39.247  2019  2019 I GBoardWebViewUtils: , create_time: 1471007226523
08-16 12:16:39.247  2019  2019 I GBoardWebViewUtils: , expire_time: 0
08-16 12:16:39.247  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-16 12:16:39.247  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 12:16:39.247  2019  2019 I GBoardWebViewUtils: , display: false
08-16 12:16:39.247  2019  2019 I GBoardWebViewUtils: , animation: false }
08-16 12:16:39.250  2168  2168 I ConfigService: onBind returning update interface
08-16 12:16:39.252  1587  1650 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 12:16:39.252  1587  1650 D KeyguardModel: createShortcutInfo...
,08-16 12:16:39.254  2019  8999 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-16 12:16:39.254  1587  1587 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-16 12:16:39.254  1587  1587 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-16 12:16:39.266  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-16 12:16:39.295  1036  1036 D administrator: Handling package changes for user 0
08-16 12:16:39.295  1036  1925 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-16 12:16:39.296  7990  7990 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 12:16:39.296  7990  7990 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 12:16:39.296  7990  7990 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 12:16:39.296  7990  7990 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 12:16:39.296  7990  7990 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 12:16:39.296  7990  7990 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 12:16:39.296  7990  7990 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 12:16:39.296  7990  7990 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 12:16:39.296  7990  7990 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 12:16:39.296  7990  7990 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 12:16:39.296  7990  7990 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 12:16:39.297  1802  1802 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-16 12:16:39.299  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 12:16:39.303  1036  2018 V SIM_STK : Menu title from STK is T-Mobile
08-16 12:16:39.303  1587  1650 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-16 12:16:39.304  1587  1650 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 12:16:39.305  2168  2168 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-16 12:16:39.305  2168  2168 I ConfigService: onBind returning config service
08-16 12:16:39.305  1587  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 12:16:39.305  1587  1650 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-16 12:16:39.313  1854  1854 D SplitUIManager: split_name #11 / not available #0
08-16 12:16:39.314  1854  1854 D SplitUIService: removed split : 
,08-16 12:16:39.319  1587  1650 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-16 12:16:39.319  1587  1650 D KeyguardModel: createShortcutInfo...
08-16 12:16:39.324  1587  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 12:16:39.324  1587  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 12:16:39.324  1587  1650 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 12:16:39.324  1587  1650 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 12:16:39.324  1587  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 12:16:39.325  1587  1650 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-16 12:16:39.334  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-16 12:16:39.336  1587  1650 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 12:16:39.336  1587  1650 D KeyguardModel: createShortcutInfo...
08-16 12:16:39.338  2019  2019 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-16 12:16:39.339  2168  2168 I ConfigService: onDestroy
08-16 12:16:39.340  1587  1587 D KeyguardModel: handleShortcutListChanged...
08-16 12:16:39.340  1587  1587 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-16 12:16:39.343  1802  9002 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-16 12:16:39.349  1854  1854 D SplitUIManager: split_name #11 / not available #0
08-16 12:16:39.349  1854  1854 I SplitUIService: split app #11
,08-16 12:16:39.374  1587  1650 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 12:16:39.374  1587  1650 D KeyguardModel: createShortcutInfo...
,08-16 12:16:39.377  1587  1650 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 12:16:39.377  1587  1650 D KeyguardModel: createShortcutInfo...
08-16 12:16:39.378  1587  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 12:16:39.378  1587  1650 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-16 12:16:39.381  1587  1650 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 12:16:39.381  1587  1650 D KeyguardModel: createShortcutInfo...
08-16 12:16:39.382  1587  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 12:16:39.382  1587  1650 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-16 12:16:39.384  1587  1650 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-16 12:16:39.384  1587  1650 D KeyguardModel: createShortcutInfo...
08-16 12:16:39.384  7089  7089 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-16 12:16:39.387  1587  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 12:16:39.387  1587  1650 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-16 12:16:39.392  1587  1650 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 12:16:39.392  1587  1650 D KeyguardModel: createShortcutInfo...
,08-16 12:16:39.402  1802  9009 I PeopleContactsSync: CP2 sync disabled
08-16 12:16:39.402  5846  9008 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-16 12:16:39.404  1802  5223 I Icing   : doRemovePackageData com.test.thalitest
08-16 12:16:39.404  1587  1587 D KeyguardModel: handleShortcutListChanged...
08-16 12:16:39.404  1587  1587 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-16 12:16:39.440  2325  9011 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-16 12:16:39.444  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-16 12:16:39.444  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 12:16:39.444  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-16 12:16:39.445  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-16 12:16:39.447  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 12:16:39.449  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-16 12:16:39.450  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-16 12:16:39.451  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-16 12:16:39.452  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-16 12:16:39.459  1036  1925 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=9012 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-16 12:16:39.461  1036  1562 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
,08-16 12:16:39.471  1036  1108 W InputMethodInfo: Duplicated subtype definition found: , voice
08-16 12:16:39.473  1802  9007 W GmsApplication: Using Auth Proxy for data requests.
08-16 12:16:39.479  1802  9007 W GmsApplication: Using Auth Proxy for data requests.
08-16 12:16:39.481  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
,08-16 12:16:39.481  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 12:16:39.482  1036  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{cefda2f u0 com.lge.launcher2/.Launcher t5} time:469526
,08-16 12:16:39.493  2019  2164 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-16 12:16:39.493  2019  2164 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-16 12:16:39.503  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-16 12:16:39.504  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 12:16:39.504  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 12:16:39.513  9012  9012 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 12:16:39.513  2019  2019 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-16 12:16:39.513  9012  9012 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 12:16:39.514  9012  9012 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 12:16:39.514  9012  9012 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 12:16:39.515  2582  2582 D [Concierge]Service: onStartCommand(). Type : 8
08-16 12:16:39.515  2582  2582 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,08-16 12:16:39.517  2582  2582 D [Concierge]Service: Update widget ID : 11
08-16 12:16:39.518  2019  2019 D [Concierge]WidgetView: change position of spinner
08-16 12:16:39.520  2019  2019 I [Concierge]WidgetView: initWebView(). Time : 1471342599519
08-16 12:16:39.520  2582  2582 D [Concierge]Service: onStartCommand(). Type : 0
08-16 12:16:39.533  2019  2019 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 354773648
08-16 12:16:39.533  2019  2019 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-16 12:16:39.534  2019  2019 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-16 12:16:39.538  2019  2019 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@65a410
08-16 12:16:39.538  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-16 12:16:39.541  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 12:16:39.541  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 12:16:39.546  1802  1814 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-16 12:16:39.546  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-16 12:16:39.546  2019  2019 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-16 12:16:39.547  1802  1814 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-16 12:16:39.547  2019  2019 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-16 12:16:39.547  1802  9004 I art     : Explicit concurrent mark sweep GC freed 51892(3MB) AllocSpace objects, 30(472KB) LOS objects, 51% free, 30MB/62MB, paused 1.028ms total 36.112ms
,08-16 12:16:39.548  1802  1814 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-16 12:16:39.549  2019  2019 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471342157356, New one : 1471342599519
08-16 12:16:39.549  2019  2019 D [Concierge]WidgetView: Unregister all receivers
08-16 12:16:39.549  2019  2019 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-16 12:16:39.549   334   414 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-16 12:16:39.549  3228  9032 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-16 12:16:39.549  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 12:16:39.551  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-16 12:16:39.552  1036  1125 I art     : Explicit concurrent mark sweep GC freed 10954(694KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.661ms total 331.244ms
08-16 12:16:39.552  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-16 12:16:39.553  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-16 12:16:39.554  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-16 12:16:39.555  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-16 12:16:39.557  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 12:16:39.558  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 12:16:39.593  2019  2019 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-16 12:16:39.600  2019  2019 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-16 12:16:39.601  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-16 12:16:39.603  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 12:16:39.619  9012  9012 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 12:16:39.624  2019  2019 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@31a68275 time:469668
08-16 12:16:39.629  9012  9012 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-16 12:16:39.658  9012  9012 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 12:16:39.660  8964  8964 D AndroidRuntime: Shutting down VM
08-16 12:16:39.681  9012  9012 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 12:16:39.681  9012  9012 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 12:16:39.695  1036  1108 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 12:16:39.699  1036  1108 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-16 12:16:39.701  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-16 12:16:39.732  9012  9012 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-16 12:16:39.745  1036  1560 I ActivityManager: Killing 8470:com.android.chrome/u0a57 (adj 15): empty #17
,08-16 12:16:39.760  2019  2019 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-16 12:16:39.794  2019  2902 I GBoardtInterface: onReloaded()
,08-16 12:16:39.797  2019  2019 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
,08-16 12:16:39.806  1981  1981 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-16 12:16:39.806  1981  1981 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-16 12:16:39.806  1036  1060 W libprocessgroup: failed to open /acct/uid_10057/pid_8470/cgroup.procs: No such file or directory
08-16 12:16:39.807  3771  3788 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-16 12:16:39.808  1981  1981 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-16 12:16:39.811  3771  4925 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 12:16:39.811  8242  8242 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-16 12:16:39.841  1036  1872 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=9039 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 12:16:39.847  1890  1890 D ActionManagerService: notifyUserLog: 1000001
08-16 12:16:39.848  3771  4929 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-16 12:16:39.849  3771  4929 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-16 12:16:39.851  1890  1890 D ActionManagerService: notifyUserLog: 1000001
08-16 12:16:39.852  3771  4929 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-16 12:16:39.852  3771  4929 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-16 12:16:39.852  3771  4929 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-16 12:16:39.852  3771  4929 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-16 12:16:39.853  3771  3788 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 12:16:39.855  2019  2019 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-16 12:16:39.855  2019  2019 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
,08-16 12:16:39.857  2019  2019 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-16 12:16:39.857  2019  2019 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 12:16:39.859  2019  2019 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-16 12:16:39.859  2019  2019 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-16 12:16:39.904  1036  1125 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=9056 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-16 12:16:39.917  9039  9039 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-16 12:16:39.918  9039  9039 W LG Account v2.2: No ProfileInfo entries
08-16 12:16:39.919  9039  9039 I LG Account v2.2: isEnabled: false
08-16 12:16:39.919  9039  9039 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 12:16:39.919  9039  9039 I Feature : [Lifetracker]Country: EU
08-16 12:16:39.919  9039  9039 I Feature : [Lifetracker]Operator: OPEN
08-16 12:16:39.919  9039  9039 I Feature : [Lifetracker]Ranking support: false
08-16 12:16:39.919  9039  9039 I Feature : [Lifetracker]Comfort support: false
08-16 12:16:39.919  9039  9039 I Feature : [Lifetracker]Accessory: true
08-16 12:16:39.919  9039  9039 I Feature : [Lifetracker]Health device: true
08-16 12:16:39.919  9039  9039 I Feature : [Lifetracker]Extra Pedometer: false
08-16 12:16:39.919  9039  9039 I Feature : [Lifetracker]Blood glucose device: false
08-16 12:16:39.919  9039  9039 I Feature : [Lifetracker]Device Number: 3
08-16 12:16:39.920  9039  9039 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED

```
