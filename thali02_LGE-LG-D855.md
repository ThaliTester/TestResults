#### Test 82865362403aafb_thali02_LGE-LG-D855 Logs


```
--------- beginning of system
08-30 12:22:29.960  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=290167141 [*alarm*], flags=0x0
,--------- beginning of main
08-30 12:22:46.382  6726  6726 D AndroidRuntime: 
08-30 12:22:46.382  6726  6726 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 12:22:46.389  6726  6726 D AndroidRuntime: CheckJNI is OFF
08-30 12:22:46.590  6726  6726 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 12:22:46.600  1035  1938 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 12:22:46.616  1939  1954 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-30 12:22:46.622  1035  1938 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-30 12:22:46.624  1035  1938 D ActivityManager: setTaskToReturnTo : TaskRecord{3be166e1 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 12:22:46.624  1035  1938 D ActivityManager: setTaskToReturnTo : TaskRecord{3be166e1 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 12:22:46.626  1035  1938 D WindowStateEx: AppWindowTokenEx init.. 
08-30 12:22:46.627   337   360 E GBMv2   : DFP En is all cleared set to be enabled
08-30 12:22:46.656  1035  1938 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6741 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 12:22:46.658  6726  6726 D AndroidRuntime: Shutting down VM
08-30 12:22:46.709  1939  2904 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-30 12:22:46.709  1939  2904 D SplitWindowPolicy: topRunningActivity=ActivityInfo{bec3c01 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 12:22:46.710  1939  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-30 12:22:46.710  1939  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{37a40aa6 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 12:22:46.772  6741  6741 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-30 12:22:46.879  6741  6741 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-30 12:22:46.887  6741  6741 I LibraryLoader: Loading: webviewchromium
08-30 12:22:46.891  6741  6741 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 4131-4135)
,08-30 12:22:46.891  6741  6741 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 12:22:46.908  6741  6741 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {175ac657}
,08-30 12:22:46.910  6741  6741 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 12:22:46.911  6741  6741 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 12:22:46.919  6741  6741 I BrowserStartupController: Initializing chromium process, renderers=0
08-30 12:22:46.920  6741  6741 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 12:22:46.931  6741  6741 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-30 12:22:46.931  6741  6741 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-30 12:22:46.932  6741  6741 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-30 12:22:46.942  6741  6741 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 12:22:46.942  6741  6741 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 12:22:46.942  6741  6741 I Adreno-EGL: Build Date: 12/12/14 금
08-30 12:22:46.942  6741  6741 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 12:22:46.942  6741  6741 I Adreno-EGL: Remote Branch: 
08-30 12:22:46.942  6741  6741 I Adreno-EGL: Local Patches: 
08-30 12:22:46.942  6741  6741 I Adreno-EGL: Reconstruct Branch: 
,08-30 12:22:46.965   322  1396 V AudioPolicyService: registerClient() client 0xb558a940, uid 10118
,08-30 12:22:46.971  1035  1117 D BluetoothManagerService: Message: 20
08-30 12:22:46.971  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@36aea463:true
08-30 12:22:47.023  6741  6775 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-30 12:22:47.027  6741  6741 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-30 12:22:47.042  6741  6741 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 12:22:47.047  6741  6741 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 12:22:47.051  6741  6741 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-30 12:22:47.054  6741  6741 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-30 12:22:47.054  6741  6741 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-30 12:22:47.067  6741  6741 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-30 12:22:47.075  6741  6741 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 12:22:47.075  6741  6741 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 12:22:47.113  6741  6788 D OpenGLRenderer: Render dirty regions requested: true
08-30 12:22:47.113  6741  6788 I OpenGLRenderer: Initialized EGL, version 1.4
08-30 12:22:47.118  6741  6788 D OpenGLRenderer: Enabling debug mode 0
08-30 12:22:47.132  6741  6741 D Atlas   : Validating map...
,08-30 12:22:47.137  1035  1993 D SplitWindow: check instance of lgWin Window{2a65ae45 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 12:22:47.173  6741  6786 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 12:22:47.173  6741  6786 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:22:47.266  1035  1118 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +558ms (total +638ms)
08-30 12:22:47.266  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1f578c06 u0 com.test.thalitest/.MainActivity t6} time:284511
08-30 12:22:47.277  6741  6741 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2b624d12 time:284521
,08-30 12:22:47.386  6741  6741 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-30 12:22:47.386  6741  6741 I chromium: 
,08-30 12:22:47.444  6741  6741 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 12:22:47.505  6741  6786 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-30 12:22:47.505  6741  6786 I chromium: 
,08-30 12:22:47.642  6741  6799 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435135488
,08-30 12:22:47.649   337   362 E GBMv2   : DFP En is all cleared set to be enabled
08-30 12:22:47.649   337   362 E GBMv2   : Set value is all cleared set the max
08-30 12:22:47.649   337   362 I GBMv2   : DFP Enabled. Ignore VFP set
08-30 12:22:47.658  6741  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 12:22:47.658  6741  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 12:22:47.658  6741  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 12:22:47.658  6741  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 12:22:47.658  6741  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 12:22:47.658  6741  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1086e536 added. We now have 1 listener(s)
08-30 12:22:47.664  1035  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 12:22:47.668  6741  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-30 12:22:47.670  6741  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 12:22:47.672  6741  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:22:47.672  6741  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:22:47.681  6741  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 12:22:47.681  6741  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 12:22:47.681  6741  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 12:22:47.681  6741  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-30 12:22:47.681  6741  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 12:22:47.681  6741  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 12:22:47.681  6741  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 12:22:47.681  6741  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 12:22:47.681  6741  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 12:22:47.681  6741  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 12:22:47.681  6741  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 12:22:47.681  6741  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 12:22:47.681  6741  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 12:22:47.681  6741  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 12:22:47.681  6741  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1215df0d added. We now have 1 listener(s)
08-30 12:22:47.682  6741  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:22:47.686  1035  1485 D WifiService: New client listening to asynchronous messages
08-30 12:22:47.691  6741  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 12:22:47.691  6741  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 12:22:47.692  6741  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 12:22:47.692  6741  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 12:22:47.692  6741  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 12:22:47.696  6741  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:22:47.697  1035  1975 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 12:22:47.698  6741  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-30 12:22:47.707  6741  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 12:22:47.708  6741  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:22:47.708  6741  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:22:47.708  6741  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:22:47.708  6741  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:22:47.708  6741  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:22:47.708  6741  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:22:47.708  6741  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:22:47.708  6741  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:22:47.708  6741  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 12:22:47.708  6741  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:22:47.710  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:22:47.713  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:22:47.717  6741  6799 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 12:22:47.752  6741  6741 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 12:22:48.939  6741  6802 W jxcore-log: Initializing JXcore engine
08-30 12:22:48.939  6741  6802 W jxcore-log: JXcore engine is ready
,08-30 12:22:48.966  6802  6802 W Thread-772: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10268]" dev="sockfs" ino=10268 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-30 12:22:48.966  6802  6802 W Thread-772: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-30 12:22:48.966  6802  6802 W Thread-772: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9896]" dev="sockfs" ino=9896 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-30 12:22:48.966  6802  6802 W Thread-772: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,08-30 12:22:48.966  6802  6802 W Thread-772: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32015]" dev="sockfs" ino=32015 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-30 12:22:48.997  6741  6802 W jxcore-log: Starting JXcore engine
08-30 12:22:49.080  6741  6802 W jxcore-log: Platform android
08-30 12:22:49.080  6741  6802 W jxcore-log: 
08-30 12:22:49.080  6741  6802 W jxcore-log: Process ARCH arm
08-30 12:22:49.080  6741  6802 W jxcore-log: 
,08-30 12:22:49.278  6741  6802 I jxcore-log: JXcore Cordova bridge is ready!
08-30 12:22:49.278  6741  6802 I jxcore-log: 
08-30 12:22:49.278  6741  6802 W jxcore-log: JXcore engine is started
,08-30 12:22:49.286  6741  6799 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-30 12:22:49.292  6741  6741 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 12:23:00.060  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-30 12:23:00.061  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-30 12:23:00.061  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-30 12:23:00.061  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-30 12:23:00.069  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-30 12:23:00.069  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-30 12:23:00.071  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-30 12:23:00.072  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
08-30 12:23:04.294  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 12:23:04.294  6741  6802 I jxcore-log: 
,08-30 12:23:04.297  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 12:23:04.297  6741  6802 I jxcore-log: 
,08-30 12:23:04.302  6741  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:23:04.302  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:04.302  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:04.302  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:23:04.302  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:23:04.302  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:23:04.302  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:23:04.302  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:23:04.305  6741  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:23:04.308  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 12:23:04.308  6741  6802 I jxcore-log: 
,08-30 12:23:04.310  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 12:23:04.310  6741  6802 I jxcore-log: 
08-30 12:23:04.651  6741  6802 I jxcore-log: Running unit tests
08-30 12:23:04.651  6741  6802 I jxcore-log: 
08-30 12:23:04.652  6741  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 12:23:04.652  6741  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25eced8d added. We now have 2 listener(s)
08-30 12:23:04.653  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 12:23:04.655  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 12:23:04.655  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:23:04.655  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:23:04.655  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:23:04.655  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e504b42 added. We now have 2 listener(s)
08-30 12:23:04.655  6741  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:23:04.655  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 12:23:04.658  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:23:04.661  6741  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:23:04.661  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:04.661  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:04.661  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:23:04.661  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:23:04.661  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:23:04.661  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:23:04.661  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:23:04.662  6741  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:23:04.662  6741  6802 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:23:04.663  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:23:04.664  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:04.665  6741  6802 D executeNativeTests: Running unit tests
,08-30 12:23:04.740  6741  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 12:23:04.740  6741  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ceb55c0 added. We now have 3 listener(s)
08-30 12:23:04.741  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
08-30 12:23:04.742  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-30 12:23:04.743  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 12:23:04.743  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:23:04.743  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 12:23:04.743  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 added. We now have 3 listener(s),
08-30 12:23:04.743  6741  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:23:04.743  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
08-30 12:23:04.745  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:23:04.747  6741  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:23:04.747  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:04.747  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:04.747  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:23:04.747  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:23:04.747  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:23:04.747  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true,
08-30 12:23:04.747  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:23:04.748  6741  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-30 12:23:04.748  6741  6802 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 12:23:04.749  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-30 12:23:04.750  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-30 12:23:04.752  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 12:23:04.754  6741  6802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 12:23:04.754  6741  6802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 12:23:04.754  6741  6802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 12:23:04.756  6741  6802 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-30 12:23:04.757  6741  6802 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 12:23:04.757  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect,
08-30 12:23:04.757  6741  6802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:23:04.757  6741  6802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:23:04.757  6741  6802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:23:04.758  6741  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:23:04.758  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:23:04.758  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:23:04.759  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:23:04.759  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:04.759  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:23:04.759  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 12:23:04.759  6741  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ceb55c0 removed from the list
08-30 12:23:04.759  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:04.759  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 removed from the list
08-30 12:23:04.759  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:23:04.759  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:04.760  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:04.760  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:04.761  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:23:04.761  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:23:04.761  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:04.761  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:04.762  6741  6802 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 12:23:04.762  6741  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:23:04.762  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:23:04.762  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:23:04.763  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:23:04.763  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:04.763  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:04.763  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ceb55c0 not in the list
08-30 12:23:04.763  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:04.763  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:04.763  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:23:04.763  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:04.763  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:04.763  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:04.763  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:04.765  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:23:04.766  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:23:04.766  6741  6,802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:04.766  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:04.770  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 12:23:04.770  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 12:23:04.770  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 12:23:04.770  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 12:23:04.770  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 12:23:04.770  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 12:23:04.770  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 12:23:04.770  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 12:23:04.770  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 12:23:04.770  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 12:23:04.770  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 12:23:04.770  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 12:23:04.770  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 12:23:04.770  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 12:23:04.770  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 12:23:04.770  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 12:23:04.771  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 12:23:04.771  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 12:23:04.771  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 12:23:04.771  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 12:23:04.771  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 12:23:04.771  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 12:23:04.771  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 12:23:04.771  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 12:23:04.771  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 12:23:04.771  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 12:23:04.771  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 12:23:04.771  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 12:23:04.771  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 12:23:04.771  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 12:23:04.771  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 12:23:04.771  6741  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:23:04.771  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:23:04.771  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:23:04.772  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:23:04.772  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:04.772  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:04.772  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ceb55c0 not in the list
08-30 12:23:04.772  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:04.772  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:04.772  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:23:04.772  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:04.772  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:04.772  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:04.772  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:04.773  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:23:04.773  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:23:04.773  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:04.773  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:04.773  6741  6802 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 12:23:04.775  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:23:04.777  6741  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:23:04.777  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:04.777  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:04.777  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:23:04.777  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:23:04.777  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:23:04.777  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:23:04.777  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:23:04.778  6741  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:23:04.778  6741  6802 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:23:04.779  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:04.780  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:04.780  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 12:23:04.780  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 12:23:04.781  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 12:23:04.781  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:23:04.781  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 12:23:04.783  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 12:23:04.783  1035  1784 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:23:04.787  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 12:23:04.791  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 12:23:04.792  6741  6802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 12:23:04.793  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 12:23:04.794  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:23:04.795  6741  6802 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 12:23:04.795  6741  6802 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 12:23:09.807  6741  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:23:09.807  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:23:09.807  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:23:09.811  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:23:09.811  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:09.811  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:23:09.811  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ceb55c0 not in the list
08-30 12:23:09.811  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:09.811  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:09.811  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:23:09.811  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:14.813  6741  6802 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 12:23:14.827  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:23:14.838  6741  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:23:14.838  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:14.838  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:14.838  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:23:14.838  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:23:14.838  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:23:14.838  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:23:14.838  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:23:14.842  6741  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:23:14.842  6741  6802 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:23:14.844  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:14.846  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:14.846  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 12:23:14.847  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 12:23:14.847  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 12:23:14.847  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:23:14.847  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 12:23:14.852  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 12:23:14.854  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:23:14.856  6741  6802 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 12:23:14.857  6741  6802 I io.jxcore.node.ConnectionHelper: start: OK
08-30 12:23:14.859  6741  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:23:14.859  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:23:14.859  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:23:14.859  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:23:14.859  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:14.860  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:23:14.860  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ceb55c0 not in the list
08-30 12:23:14.860  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:14.860  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:14.860  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:23:14.860  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:14.861  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:14.861  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:14.861  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:23:14.862  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:23:14.864  6741  6802 D BluetoothLeScanner: could not find callback wrapper
08-30 12:23:14.864  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:23:14.864  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:14.864  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:14.865  6741  6802 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 12:23:14.872  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:23:14.877  6741  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:23:14.877  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:14.877  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:14.877  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:23:14.877  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:23:14.877  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:23:14.877  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:23:14.877  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:23:14.878  6741  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:23:14.879  6741  6802 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 12:23:14.882  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:14.884  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:14.885  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 12:23:14.885  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 12:23:14.885  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 12:23:14.885  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:23:14.885  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 12:23:14.890  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 12:23:14.892  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:23:14.894  6741  6802 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 12:23:14.894  6741  6802 I io.jxcore.node.ConnectionHelper: start: OK
08-30 12:23:19.895  6741  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 12:23:19.901  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:23:19.901  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:23:24.906  6741  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:23:24.906  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:23:24.907  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:23:24.913  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:23:24.913  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:24.913  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:23:24.914  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ceb55c0 not in the list
08-30 12:23:24.914  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:24.914  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:24.914  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:23:24.914  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:24.917  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:24.918  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:24.919  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:23:24.919  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:23:24.919  6741  6802 D BluetoothLeScanner: could not find callback wrapper
08-30 12:23:24.920  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:23:24.920  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:24.920  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:24.921  6741  6802 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-30 12:23:24.921  6741  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:23:24.921  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:23:24.921  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:23:24.922  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:23:24.922  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:24.922  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:24.922  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ceb55c0 not in the list
08-30 12:23:24.923  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:24.923  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:24.923  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:23:24.923  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:24.923  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Blu,etoothManager: release: 2 listener(s) left
08-30 12:23:24.923  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:24.923  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:23:24.927  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:23:24.927  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:23:24.928  6741  6802 D BluetoothLeScanner: could not find callback wrapper
08-30 12:23:24.928  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:23:24.928  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:24.928  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:24.930  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 12:23:24.930  6741  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:23:24.930  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:23:24.930  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:23:24.931  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:23:24.931  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:24.931  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:24.931  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ceb55c0 not in the list
08-30 12:23:24.931  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:24.931  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:24.931  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:23:24.931  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:24.931  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:24.931  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:24.931  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:24.933  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:23:24.933  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:23:24.934  6741  6802 D BluetoothLeScanner: could not find callback wrapper
08-30 12:23:24.934  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:23:24.934  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:24.934  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:24.935  6741  6802 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 12:23:24.936  6741  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:23:24.936  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: ,false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:23:24.936  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:23:24.939  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:23:24.939  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:24.939  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:24.939  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ceb55c0 not in the list
08-30 12:23:24.939  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:24.940  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:24.940  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:23:24.940  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:24.940  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:24.940  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:24.940  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:24.942  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:23:24.942  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:23:24.942  6741  6802 D BluetoothLeScanner: could not find callback wrapper
08-30 12:23:24.942  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:23:24.942  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:24.942  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:24.944  6741  6802 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 12:23:24.944  6741  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:23:24.944  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:23:24.944  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:23:24.944  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:23:24.944  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:24.944  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:24.945  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ceb55c0 not in the list
08-30 12:23:24.945  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:24.945  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:24.945  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:23:24.945  6741  6,802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:24.945  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:24.945  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:24.945  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:24.947  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:23:24.947  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 12:23:24.951  6741  6802 D BluetoothLeScanner: could not find callback wrapper
08-30 12:23:24.951  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:23:24.951  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:24.952  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:24.953  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 12:23:24.956  6741  6802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 12:23:24.956  6741  6802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 12:23:24.956  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 12:23:24.957  6741  6802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:23:24.957  6741  6802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:23:24.958  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 12:23:24.958  6741  6802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 12:23:24.959  6741  6802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 12:23:24.961  6741  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:23:24.962  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:23:24.962  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:23:24.962  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:23:24.962  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:24.962  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:24.962  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ceb55c0 not in the list
08-30 12:23:24.963  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:24.963  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:24.963  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:23:24.963  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:24.963  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:24.963  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:24.963  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:24.965  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:23:24.965  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:23:24.966  6741  6802 D BluetoothLeScanner: could not find callback wrapper
08-30 12:23:24.966  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:23:24.966  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:24.966  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:24.970  6741  6802 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 12:23:24.972  6741  6802 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 12:23:24.972  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-30 12:23:24.981  6741  6802 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 12:23:24.981  6741  6802 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 12:23:24.981  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 12:23:24.981  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 12:23:24.981  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 12:23:24.982  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 12:23:24.982  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 12:23:24.982  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 12:23:24.982  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 12:23:24.982  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 12:23:24.982  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 12:23:24.982  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 12:23:24.982  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 12:23:24.982  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 12:23:24.982  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 12:23:24.982  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 12:23:24.982  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 12:23:24.982  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 12:23:24.982  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 12:23:24.982  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 12:23:24.982  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 12:23:24.982  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 12:23:24.982  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 12:23:24.982  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 12:23:24.982  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 12:23:24.982  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 12:23:24.982  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2,410:2410:2410:2410:2410]
08-30 12:23:24.983  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 12:23:24.983  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 12:23:24.983  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 12:23:24.983  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 12:23:24.983  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 12:23:24.983  6741  6802 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 12:23:24.983  6741  6802 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 12:23:24.983  6741  6802 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 12:23:24.983  6741  6802 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-30 12:23:24.983  6741  6802 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 12:23:24.983  6741  6802 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 12:23:24.984  6741  6802 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 12:23:24.984  6741  6802 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 12:23:24.984  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 12:23:24.987  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-30 12:23:24.989  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 12:23:24.989  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 12:23:24.990  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 12:23:24.990  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 12:23:24.990  6741  6802 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 12:23:24.990  6741  6802 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-30 12:23:24.990  6741  6802 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 12:23:24.991  6741  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:23:24.991  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:23:24.991  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:23:24.999  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:23:24.999  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:24.999  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:25.001  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 12:23:25.002  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ceb55c0 not in the list
08-30 12:23:25.002  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:25.002  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:25.002  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:23:25.002  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:25.002  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:25.002  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:25.002  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:25.003  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:23:25.003  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 12:23:25.007  6741  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 836)
08-30 12:23:25.007  6741  6802 D BluetoothLeScanner: could not find callback wrapper
08-30 12:23:25.008  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:23:25.008  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:25.008  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:25.009  6741  6802 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 12:23:25.009  6741  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:23:25.009  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:23:25.009  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:23:25.011  6741  6816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 836
08-30 12:23:25.012  6741  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 836)
08-30 12:23:25.013  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:23:25.013  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:25.013  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:25.013  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ceb55c0 not in the list
08-30 12:23:25.013  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:25.013  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:25.013  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:23:25.013  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:25.013  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:25.013  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:25.013  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:25.015  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:23:25.015  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:23:25.017  6741  6802 D BluetoothLeScanner: could not find callback wrapper
08-30 12:23:25.017  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:23:25.017  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:25.017  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:25.018  6741  6802 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: Stat,e: NOT_STARTED, is discovering: true, is advertising: true
08-30 12:23:25.019  6741  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:23:25.019  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:23:25.019  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:23:25.022  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:23:25.022  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:25.022  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:25.022  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ceb55c0 not in the list
08-30 12:23:25.022  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:25.022  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:25.022  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:23:25.022  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:25.022  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:25.023  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:25.023  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:25.024  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:23:25.024  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:23:25.025  6741  6802 D BluetoothLeScanner: could not find callback wrapper
08-30 12:23:25.025  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:23:25.025  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:25.025  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:25.026  6741  6802 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 12:23:25.026  6741  6802 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 12:23:25.026  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 12:23:25.026  6741  6802 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 12:23:25.026  6741  6802 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 12:23:25.027  6741  6802 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 12:23:25.027  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 12:23:25.027  6741  6802 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 12:23:25.027  6741  6802 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 12:23:25.027  6741  6802 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 12:23:25.027  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 12:23:25.0,27  6741  6802 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 12:23:25.027  6741  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:23:25.027  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:23:25.027  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:23:25.028  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:23:25.028  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:25.028  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:25.029  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ceb55c0 not in the list
08-30 12:23:25.029  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:25.029  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:25.029  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:23:25.029  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:25.029  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:25.029  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:25.029  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:23:25.031  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:23:25.031  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 12:23:25.036  6741  6802 D BluetoothLeScanner: could not find callback wrapper
08-30 12:23:25.036  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:23:25.036  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:25.036  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:25.037  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:23:25.037  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:25.037  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:25.037  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ceb55c0 not in the list
08-30 12:23:25.037  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:25.037  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:25.037  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:23:25.037  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:25.037  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:30.039  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:30.039  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:30.039  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:23:30.039  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:30.040  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:30.040  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ceb55c0 not in the list
08-30 12:23:30.040  6741  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:23:30.040  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:23:30.040  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:23:30.052  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-30 12:23:30.053  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:30.053  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:30.053  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ceb55c0 not in the list
08-30 12:23:30.053  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:30.053  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:30.053  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:23:30.053  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:30.053  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:30.053  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:30.054  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:23:30.061  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:23:30.061  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:23:30.062  6741  6802 D BluetoothLeScanner: could not find callback wrapper
08-30 12:23:30.062  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:23:30.062  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:30.062  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:30.065  6741  6802 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 12:23:30.066  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:23:30.066  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 12:23:30.068  6741  6802 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 12:23:30.068  6741  6802 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 12:23:30.068  6741  6741 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-30 12:23:30.071  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 12:23:30.071  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 12:23:30.077  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:23:30.077  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 12:23:30.077  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 12:23:30.077  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 12:23:30.077  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:30.077  6741  6802 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 12:23:30.078  6741  6741 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 12:23:30.078  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ceb55c0 not in the list
08-30 12:23:30.078  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:30.078  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 12:23:30.078  6741  6802 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 12:23:30.078  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 12:23:30.080  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 12:23:30.083  1035  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:23:30.086  6741  6802 D BluetoothLeScanner: could not find callback wrapper
08-30 12:23:30.086  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:23:30.086  6741  6802 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 12:23:30.086  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:30.086  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:30.088  6741  6802 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:23:30.088  6741  6741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:23:30.088  6741  6741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 12:23:30.088  6741  6741 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 12:23:30.089  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:30.089  6741  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:23:30.089  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:23:30.089  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:23:30.090  6741  6817 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:23:30.092  3835  3851 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-30 12:23:30.094  6741  6817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 12:23:30.094  6741  6817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 12:23:30.094  6741  6817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-30 12:23:30.097  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:23:30.097  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:30.097  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:30.097  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ceb55c0 not in the list
08-30 12:23:30.097  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:30.097  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:30.097  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:23:30.097  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:30.097  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:30.097  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:30.097  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:30.098  6741  6741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 12:23:30.100  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:23:30.100  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:23:30.101  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:30.101  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:30.102  6741  6802 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 12:23:30.103  6741  6802 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 12:23:30.103  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 12:23:30.104  6741  6802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:23:30.104  6741  6802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 12:23:30.107  6741  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:23:30.107  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:23:30.107  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:23:30.110  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:23:30.110  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:30.110  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:30.110  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ceb55c0 not in the list
08-30 12:23:30.110  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:30.110  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:30.110  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:23:30.110  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:30.110  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:30.110  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:30.110  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:30.112  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:23:30.112  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:23:30.112  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:30.112  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:30.116  1035  2029 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:23:30.117  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:23:30.120  1035  1784 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 12:23:30.123  6741  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:23:30.123  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:23:30.123  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:23:30.123  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:23:30.123  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:30.123  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:30.123  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ceb55c0 not in the list
08-30 12:23:30.123  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:30.123  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:30.123  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:23:30.123  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:30.123  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:30.124  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:30.124  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:30.125  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:23:30.125  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:23:30.125  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:30.125  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:30.127  6741  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:23:30.127  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:23:30.127  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:23:30.127  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:23:30.127  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:30.127  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:30.127  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ceb55c0 not in the list
08-30 12:23:30.127  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:30.128  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryMana,ger@16d432f9 not in the list
08-30 12:23:30.128  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:23:30.128  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:30.128  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:30.128  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:30.128  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:30.129  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:23:30.129  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:23:30.129  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:30.129  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16d432f9 not in the list
08-30 12:23:30.131  6741  6802 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 12:23:30.131  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 12:23:30.131  6741  6802 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 12:23:30.131  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 12:23:30.131  6741  6802 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2,
08-30 12:23:30.131  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 12:23:30.134  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 12:23:30.134  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 12:23:30.135  6741  6802 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 12:23:30.137  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-30 12:23:30.137  6741  6802 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 12:23:30.137  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 12:23:30.137  6741  6802 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 12:23:30.137  6741  6802 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 12:23:30.138  6741  6802 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,08-30 12:23:30.138  6741  6802 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 12:23:30.139  6741  6802 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 12:23:30.139  6741  6802 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 12:23:30.139  6741  6802 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 12:23:30.139  6741  6802 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 12:23:30.141  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 12:23:30.141  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2547db16 added. We now have 3 listener(s)
08-30 12:23:30.141  6741  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:23:30.150  6741  6802 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 12:23:30.152  1035  2045 D WifiServiceImplEx: setWifiEnabled: true pid=6741, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 12:23:30.153  1035  2045 D WifiService: setWifiEnabled: true pid=6741, uid=10118
08-30 12:23:30.153  1035  2045 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 12:23:30.589  6741  6741 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 12:23:35.160  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 12:23:35.161  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d5d2c97 added. We now have 4 listener(s)
08-30 12:23:35.161  6741  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:23:35.179  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:35.179  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d5d2c97 removed from the list
08-30 12:23:35.179  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:23:35.179  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:35.179  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:35.180  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:23:35.180  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@280c2e84 added. We now have 4 listener(s)
08-30 12:23:35.180  6741  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:23:35.185  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:23:35.185  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@280c2e84 removed from the list
08-30 12:23:35.185  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:23:35.185  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:23:35.185  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:23:35.186  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:23:35.186  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@174366d added. We now have 4 listener(s)
08-30 12:23:35.186  6741  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:23:35.190  1035  1957 D WifiServiceImplEx: setWifiEnabled: false pid=6741, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 12:23:35.190  1035  1957 D WifiService: setWifiEnabled: false pid=6741, uid=10118
08-30 12:23:35.190  1035  1957 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 12:23:35.212  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 12:23:35.213  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 12:23:35.213  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-30 12:23:35.214  1035  1437 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 12:23:35.215  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 12:23:35.215  1035  1437 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 12:23:35.216  1035  1437 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 12:23:35.216  1035  1437 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 12:23:35.217  1035  1437 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 12:23:35.217  1035  1437 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 12:23:35.217  1035  1437 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 12:23:35.218  1035  1437 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 12:23:35.218  1035  1437 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 12:23:35.220  1035  1725 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:23:35.220  1035  1725 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3b36d2ab mBinding = false
,08-30 12:23:35.229  1035  1437 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 12:23:35.229  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 12:23:35.229  2700  2700 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 12:23:35.230  1035  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:35.230  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:35.231  1035  1437 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 12:23:35.231  1035  1437 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 12:23:35.232  1035  1437 D WifiNative-wlan0: SET ps 1: returned true
08-30 12:23:35.235  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-30 12:23:35.241  1035  1117 D BluetoothManagerService: Message: 2
08-30 12:23:35.242  1035  1117 D BluetoothManagerService: Sending off request.
08-30 12:23:35.243  3835  3851 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 12:23:35.243  3835  3912 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 12:23:35.243  3835  3912 D BluetoothAdapterProperties: Setting state to 13
08-30 12:23:35.243  3835  3912 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 12:23:35.244  3835  3912 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 12:23:35.244  3835  3912 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 12:23:35.248  3835  3917 D BluetoothAdapterProperties: Scan Mode:20
,08-30 12:23:35.251  3835  3912 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 12:23:35.252  3835  3912 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 12:23:35.253  3835  4158 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 12:23:35.253  3835  4158 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 12:23:35.253  3835  4158 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 12:23:35.253  3835  4158 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 12:23:35.253  3835  4158 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 12:23:35.253  3835  4158 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 12:23:35.253  3835  4158 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 12:23:35.253  3835  4158 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-30 12:23:35.254  3835  4160 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 12:23:35.255  3835  4201 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 12:23:35.255  3835  4202 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 12:23:35.256  3835  4204 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 12:23:35.257  3835  3993 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 12:23:35.257  3835  3993 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-30 12:23:35.259  3835  3993 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 12:23:35.259  3835  3993 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 12:23:35.259  3835  3993 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 12:23:35.259  3835  3993 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 12:23:35.259  3835  3993 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:23:35.259  3835  3993 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 12:23:35.259  3835  3993 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 12:23:35.259  3835  3993 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 12:23:35.259  3835  3993 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 12:23:35.259  3835  3993 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 12:23:35.259  3835  3993 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 12:23:35.259  3835  3993 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 12:23:35.267  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 12:23:35.267  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-30 12:23:35.271  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:23:35.286  1035  1117 D BluetoothManagerService: Message: 60
08-30 12:23:35.286  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-30 12:23:35.286  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-30 12:23:35.291  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:35.291  6741  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:23:35.291  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:35.291  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:35.291  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:23:35.291  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:23:35.291  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:23:35.291  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:23:35.291  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:23:35.292  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:35.292  6741  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:23:35.292  6741  6802 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:23:35.294  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:35.298  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:23:35.309  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:35.309  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:23:35.309  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:35.309  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:35.309  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:23:35.309  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:23:35.309  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:23:35.309  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:23:35.309  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:23:35.312  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:35.312  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:23:35.322  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:35.322  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:23:35.322  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:35.322  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:35.322  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:23:35.322  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:23:35.322  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:23:35.322  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:23:35.322  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:23:35.325  1035  2842 D DhcpStateMachine: RunningState{ when=-93ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:35.330   316   893 D CommandListener: Clearing all IP addresses on wlan0
08-30 12:23:35.345  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:35.346  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:23:35.353  1035  1113 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6831 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-30 12:23:35.356  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:35.357  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 12:23:35.359  3835  3835 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:35.359  3835  3835 D BluetoothMapService: STATE_TURNING_OFF
08-30 12:23:35.359  3835  3835 V BluetoothMapService: Handler(): got msg=4
08-30 12:23:35.360  3835  3835 D BluetoothMapService: MAP Service closeService in
08-30 12:23:35.360  3835  3835 D BluetoothMapMasInstance: MAP Service shutdown
08-30 12:23:35.360  3835  3835 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 12:23:35.360  3835  3835 V BluetoothMapService: MAP Service closeService out
,08-30 12:23:35.362  3835  3835 V BtOppService: Receiver DISABLED_ACTION 
08-30 12:23:35.363  3835  3835 I BtOppRfcommListener: stopping Accept Thread
08-30 12:23:35.363  3835  3835 V BtOppRfcommListener: close mBtServerSocket
08-30 12:23:35.363  3835  4201 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 12:23:35.364  3835  3835 V BtOppRfcommListener: waiting for thread to terminate
08-30 12:23:35.364  3835  3835 V BtOppRfcommListener: done waiting for thread to terminate
08-30 12:23:35.365  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:35.381  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:23:35.385  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:35.391  1035  1495 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 12:23:35.391  1035  1495 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-30 12:23:35.408  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:35.408  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:23:35.408  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:35.408  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:35.408  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:23:35.408  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:23:35.408  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:23:35.408  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:23:35.408  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:23:35.410  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:35.411  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:23:35.421  1035  1113 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6850 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 12:23:35.424  1035  1437 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:23:35.425  1035  1437 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:23:35.425  1035  1390 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:35.425  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 12:23:35.426  1035  1390 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@202396cd
08-30 12:23:35.426  1035  1390 D LGWifiP2pService: P2pDisablingState
08-30 12:23:35.426  1035  1390 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:35.426  1035  1390 D LGWifiP2pService: p2p socket connection lost
08-30 12:23:35.426  1035  1390 D LGWifiP2pService: P2pDisabledState
08-30 12:23:35.427  3835  3835 V BtOppService: onDestroy
08-30 12:23:35.429  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-30 12:23:35.431  1939  1939 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-30 12:23:35.433  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:35.433  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:35.433  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 12:23:35.434  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-30 12:23:35.436  1035  1437 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:23:35.436  1035  1437 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:23:35.436  1035  1437 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:23:35.437  1035  1437 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:23:35.438  1035  1437 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 12:23:35.438  1035  1437 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 12:23:35.439  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:35.439  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:35.439  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 12:23:35.440  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 12:23:35.440  1035  1555 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:35.440  1035  1035 D RttService: SCAN_AVAILABLE : 1
08-30 12:23:35.441  1035  1556 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:35.442  3835  3835 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,08-30 12:23:35.451  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=-12ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:35.451  1035  1390 D LGWifiP2pService: DefaultState{ when=-12ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:35.451  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 12:23:35.451  2700  2700 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 12:23:35.453  1035  1437 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 12:23:35.453  1035  1437 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 12:23:35.454  1035  1437 D WifiNative-wlan0: SET ps 1: returned true
08-30 12:23:35.455  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 12:23:35.455  1939  1939 D WfdsService: WifiP2pState is changed : false
08-30 12:23:35.456  1939  2319 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 12:23:35.456  1939  2319 D WfdsService: Set the WFDS Monitor: false
08-30 12:23:35.457   316   893 D CommandListener: Clearing all IP addresses on wlan0
08-30 12:23:35.458  1035  1495 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 12:23:35.458  1035  1495 D DSQN    : disableDataServiceNotify
,08-30 12:23:35.458  1035  1495 D DSQN    : stop dsqn bin
08-30 12:23:35.462  1035  1437 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 12:23:35.462  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-30 12:23:35.463  1939  2319 D WfdsMonitor: WFDS Monitor is stopped
08-30 12:23:35.463  1939  2319 D WfdsService: STATE : WfdsDisabledState - enter
08-30 12:23:35.463  1939  2743 D CtrlSupplicant: Received on exit socket, terminate
08-30 12:23:35.463  1939  2743 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 12:23:35.463  1939  2743 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 12:23:35.463  1939  2743 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 12:23:35.463  1939  2321 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 12:23:35.464  1939  2319 W WfdsService: DefaultState - msg [9445378] is not handled
08-30 12:23:35.464  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:35.464  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:35.464  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 12:23:35.466  1035  1495 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 12:23:35.466  1035  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:23:35.466  1035  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:23:35.466  1035  1495 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:23:35.466  1035  1495 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-30 12:23:35.466  1035  2839 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:35.466  1035  2839 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:35.466  1601  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 12:23:35.466  1035  2839 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 12:23:35.467  1035  1495 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-30 12:23:35.467  1035  1495 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 12:23:35.467  1035  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 12:23:35.467  1035  1495 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:35.468  1035  1437 D WifiNative-p2p0: TERMINATE: returned true
08-30 12:23:35.468  1035  1437 E WifiStateMachine: Couldn't get getWiFiOffloadingIfa,ce : 
08-30 12:23:35.468  1035  1437 E WifiStateMachine: useWiFiOffloading() : false
08-30 12:23:35.468  1035  1437 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 12:23:35.468  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 12:23:35.470  1035  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 12:23:35.470  1035  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-30 12:23:35.476  1035  1495 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:35.476  1035  1495 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:23:35.476  1035  1495 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:23:35.476  1035  1495 D NetworkManagementService: Removing idletimer
08-30 12:23:35.477  1850  1850 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:23:35.477  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 12:23:35.477  1035  1495 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:35.478  1035  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 12:23:35.479  1035  1437 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:23:35.479  1035  1437 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 12:23:35.480  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-30 12:23:35.481  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:23:35.481  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:23:35.482  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:35.484  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:35.484  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:23:35.484  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:35.484  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:35.484  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:23:35.484  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:23:35.484  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:23:35.484  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:23:35.484  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:23:35.484  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:35.485  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:23:35.499  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:35.499  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:23:35.499  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:35.499  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:35.499  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:23:35.499  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:23:35.499  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:23:35.499  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:23:35.499  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:23:35.500  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:35.500  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:23:35.503  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:35.503  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:23:35.503  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:35.503  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:35.503  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:23:35.503  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:23:35.503  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:23:35.503  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:23:35.503  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:23:35.504  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:35.504  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:23:35.506  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:23:35.506  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:23:35.509  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 12:23:35.510  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 12:23:35.510  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:23:35.511  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:35.528  6850  6850 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:23:35.529  6850  6850 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-30 12:23:35.529  6850  6850 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 12:23:35.530  6850  6850 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-30 12:23:35.530  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 12:23:35.530  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:35.531  6850  6850 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 12:23:35.531  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:35.531  6850  6850 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 12:23:35.551  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 12:23:35.552  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:35.552  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:35.553  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:35.561  1035  1725 I art     : Explicit concurrent mark sweep GC freed 54514(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 3.766ms total 160.022ms
08-30 12:23:35.562  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 12:23:35.562  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 12:23:35.562  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:23:35.562  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 12:23:35.562  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 12:23:35.562  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 12:23:35.562  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 12:23:35.562  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 12:23:35.562  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 12:23:35.562  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 12:23:35.563  1035  1495 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-30 12:23:35.579  1035  2842 D DhcpStateMachine: StoppedState
08-30 12:23:35.579  1035  2842 D DhcpStateMachine: StoppedState{ when=-125ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 12:23:35.579  1035  1437 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-30 12:23:35.579  1035  1437 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-30 12:23:35.583  6831  6831 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-30 12:23:35.584  6831  6831 W LG Account v2.2: No ProfileInfo entries
08-30 12:23:35.584  6831  6831 I LG Account v2.2: isEnabled: false
08-30 12:23:35.584  6831  6831 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 12:23:35.584  6831  6831 I Feature : [Lifetracker]Country: EU
08-30 12:23:35.584  6831  6831 I Feature : [Lifetracker]Operator: OPEN
08-30 12:23:35.584  6831  6831 I Feature : [Lifetracker]Ranking support: false
08-30 12:23:35.584  6831  6831 I Feature : [Lifetracker]Comfort support: false
08-30 12:23:35.584  6831  6831 I Feature : [Lifetracker]Accessory: true
08-30 12:23:35.584  6831  6831 I Feature : [Lifetracker]Health device: true
08-30 12:23:35.584  6831  6831 I Feature : [Lifetracker]Extra Pedometer: false
08-30 12:23:35.584  6831  6831 I Feature : [Lifetracker]Blood glucose device: false
08-30 12:23:35.584  6831  6831 I Feature : [Lifetracker]Device Number: 3
08-30 12:23:35.586  2700  2700 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 12:23:35.586  2700  2700 I wpa_supplicant: monitor socket send errors count : 1
08-30 12:23:35.586  2700  2700 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1939-2\x00 that cannot receive messages
08-30 12:23:35.587  1035  2736 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 12:23:35.587  1035  2736 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 12:23:35.592  6420  6420 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 12:23:35.622  2700  2700 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 12:23:35.623  2700  2700 W wpa_supplicant: USIM:  scard_deinit function
08-30 12:23:35.623  1035  1117 D Tethering: InitialState.processMessage what=4
,08-30 12:23:35.624  1035  2736 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-30 12:23:35.624  1035  2736 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 12:23:35.624  1035  2736 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 12:23:35.625  1035  2736 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 12:23:35.625  1035  2736 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 12:23:35.625  1035  2736 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 12:23:35.625  1035  1437 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=332858
,08-30 12:23:35.625  1035  1437 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=332858
08-30 12:23:35.626  1035  1437 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=332859  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 12:23:35.626  1035  1437 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=332859  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 12:23:35.629  6850  6850 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 12:23:35.643  1035  1956 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6881 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 12:23:35.644  1035  1956 I ActivityManager: Killing 6216:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-30 12:23:35.679  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 12:23:35.682  3835  3835 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 12:23:35.682  3835  3835 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:35.683  3835  3835 V BluetoothPbapReceiver: ***********state = 13
08-30 12:23:35.684  1035  1437 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:23:35.684  3835  3835 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-30 12:23:35.684  1035  1437 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:23:35.689  1035  1725 W libprocessgroup: failed to open /acct/uid_10014/pid_6216/cgroup.procs: No such file or directory
,08-30 12:23:35.693  3835  3835 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:35.693  3835  3835 V BluetoothPbapService: state: 13
08-30 12:23:35.694  3835  3835 V BluetoothPbapService: Pbap Service closeService in
08-30 12:23:35.694  2205  2205 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 12:23:35.696  3835  3835 V BluetoothPbapService: successfully stopped pbap service
08-30 12:23:35.697  3835  3835 V BluetoothPbapService: Pbap Service closeService out
08-30 12:23:35.697  3835  3835 V BluetoothPbapService: Pbap Service onDestroy
08-30 12:23:35.697  3835  3835 V BluetoothPbapService: Pbap Service closeService in
08-30 12:23:35.697  3835  3835 V BluetoothPbapService: Pbap Service closeService out
08-30 12:23:35.697  3835  3835 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-30 12:23:35.703  1035  1117 D BluetoothManagerService: Message: 20
08-30 12:23:35.703  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37fe21dd:true
,08-30 12:23:35.716  2700  2700 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 12:23:35.716  1035  2736 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-30 12:23:35.716  1035  2736 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-30 12:23:35.716  1035  2736 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-30 12:23:35.717  1035  1437 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-30 12:23:35.726  1035  1117 D BluetoothManagerService: Message: 30
08-30 12:23:35.734  1035  1117 D BluetoothManagerService: Message: 30
,08-30 12:23:35.737  6850  6850 D LocalBluetoothProfileManager: Adding local MAP profile
08-30 12:23:35.739  6850  6850 D BluetoothMap: Create BluetoothMap proxy object
08-30 12:23:35.739  1035  1117 D BluetoothManagerService: Message: 30
08-30 12:23:35.744  1035  1117 D BluetoothManagerService: Message: 30
08-30 12:23:35.746  6850  6850 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-30 12:23:35.747  6850  6850 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-30 12:23:35.747  6881  6881 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 12:23:35.751  6881  6881 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 12:23:35.752  6881  6881 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 12:23:35.754  1035  1574 I ActivityManager: Killing 6322:com.android.defcontainer/u0a4 (adj 15): empty #17
08-30 12:23:35.788  1035  1956 W libprocessgroup: failed to open /acct/uid_10004/pid_6322/cgroup.procs: No such file or directory
,08-30 12:23:35.790  6850  6850 D LGBluetoothUserBindClient: [BTUI] initUserBindClient,
08-30 12:23:35.794  6850  6850 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-30 12:23:35.804  6850  6850 D DockEventReceiver: finishStartingService: stopping service
,08-30 12:23:35.820  1035  1437 D WifiOffDelayIfNotUsed: stopMonitoring
08-30 12:23:35.821  1035  1437 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 12:23:35.821  1035  1437 E WifiStateMachine: useWiFiOffloading() : false
08-30 12:23:35.821  1035  1437 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-30 12:23:35.821  1939  1939 D WfdsService: Supplicant Connection state is changed : false
08-30 12:23:35.821  1939  2319 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 12:23:35.821  1939  2319 D WfdsService: Set the WFDS Monitor: false
08-30 12:23:35.821  1939  2319 D WfdsMonitor: WFDS Monitor is stopped
08-30 12:23:35.824  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:35.825  2503  2503 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:35.825  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 12:23:35.826  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 12:23:35.826  1035  1466 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 12:23:35.827  1035  1466 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 12:23:35.827  6850  6850 D BluetoothInputDevice: Proxy object connected
08-30 12:23:35.829  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:35.829  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:23:35.829  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:35.829  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:35.829  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:23:35.829  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:23:35.829  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:23:35.829  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:23:35.829  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:23:35.830  6850  6850 D HidProfile: Bluetooth service connected
08-30 12:23:35.832  6850  6850 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 12:23:35.833  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:35.833  6850  6850 D PanProfile: Bluetooth service connected
08-30 12:23:35.833  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:23:35.833  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:35.833  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:35.833  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:23:35.833  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:23:35.833  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:23:35.833  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:23:35.833  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:23:35.836  6850  6850 D BluetoothMap: Proxy object connected
08-30 12:23:35.838  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:35.838  6850  6850 D MapProfile: Bluetooth service connected
08-30 12:23:35.838  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:23:35.838  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:35.838  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:35.838  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:23:35.838  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:23:35.838  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:23:35.838  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:23:35.838  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:23:35.838  6850  6850 D BluetoothMap: getConnectedDevices()
08-30 12:23:35.839  6850  6850 D BluetoothMap: Bluetooth is Not enabled
08-30 12:23:35.855  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:23:35.892  6850  6850 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:23:35.892  6850  6850 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:23:35.903  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 12:23:35.905  6850  6850 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 12:23:35.908  6850  6850 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-30 12:23:35.913  6850  6850 D BluetoothPermissionRequest: onReceive
08-30 12:23:35.917  6850  6850 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 12:23:35.926  6850  6850 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 12:23:35.927  1035  1975 I ActivityManager: Killing 6465:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-30 12:23:35.985  1035  1574 W libprocessgroup: failed to open /acct/uid_10008/pid_6465/cgroup.procs: No such file or directory
,08-30 12:23:35.987  3835  3835 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-30 12:23:35.987  3835  3835 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-30 12:23:35.989  3835  3835 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-30 12:23:35.997  3835  3835 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:35.997  3835  3835 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 12:23:36.081  1035  1725 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6909 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-30 12:23:36.086  3835  3835 V BluetoothFtpService: Ftp Service onStartCommand
08-30 12:23:36.087  3835  3835 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:36.088  3835  3835 V BluetoothFtpService: Ftp Service closeService
08-30 12:23:36.088  3835  3835 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-30 12:23:36.096  3835  3835 V BluetoothFtpService: successfully stopped ftp service
08-30 12:23:36.096  3835  3835 V BluetoothFtpService: Ftp Service onDestroy
08-30 12:23:36.096  3835  3835 V BluetoothFtpService: Ftp Service closeService
,08-30 12:23:36.102   356   356 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 489us total 21.477ms
,08-30 12:23:36.103  3835  3835 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 12:23:36.103  3835  3835 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 12:23:36.103  3835  3835 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 12:23:36.103  3835  3835 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:36.103  3835  3835 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 12:23:36.103  3835  3835 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 12:23:36.105  3835  3835 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:36.105  3835  3835 V BluetoothSapService: state: 13
08-30 12:23:36.105  3835  3835 V BluetoothSapService: Stopping SAP server process
08-30 12:23:36.106  3835  3835 V BluetoothSapService: Sap Service closeSapService in
08-30 12:23:36.107  3835  3835 V BluetoothSapService: Close listen Socket : 
08-30 12:23:36.107  3835  3835 V BluetoothSapService: Close rfcomm Socket : 
08-30 12:23:36.107  3835  3835 V BluetoothSapService: Close sapd  Socket : 
08-30 12:23:36.122   356   356 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 421us total 19.772ms
,08-30 12:23:36.141   356   356 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 367us total 17.186ms
,08-30 12:23:36.189  1035  1725 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6926 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 12:23:36.197  3835  3835 V BluetoothSapService: Sap Service closeSapService out
08-30 12:23:36.197  3835  3835 V BluetoothSapService: Sap Service onDestroy
08-30 12:23:36.197  3835  3835 V BluetoothSapService: Sap Service closeSapService in
08-30 12:23:36.197  3835  3835 V BluetoothSapService: Close listen Socket : 
08-30 12:23:36.197  3835  3835 V BluetoothSapService: Close rfcomm Socket : 
08-30 12:23:36.197  3835  3835 V BluetoothSapService: Close sapd  Socket : 
08-30 12:23:36.198  3835  3835 V BluetoothSapService: Sap Service closeSapService out
08-30 12:23:36.226  6909  6909 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 12:23:36.261  3835  3917 D bt_hci_bdroid: cleanup
08-30 12:23:36.261  3835  3995 I bt_lpm  : LPM is already off!!!
,08-30 12:23:36.261  3835  4137 I bt_userial_mct: exiting userial_read_thread
08-30 12:23:36.261  3835  4137 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 12:23:36.261  3835  3993 W bt-btif : ag scb idx 1 not allocated
08-30 12:23:36.262  3835  3993 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 12:23:36.262  3835  3993 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 12:23:36.262  3835  3993 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:23:36.262  3835  3993 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 12:23:36.262  3835  3993 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 12:23:36.262  3835  3993 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 12:23:36.262  3835  3993 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 12:23:36.262  3835  3993 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 12:23:36.262  3835  3993 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:23:36.262  3835  3993 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 12:23:36.262  3835  3993 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 12:23:36.262  3835  3993 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 12:23:36.262  3835  3993 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 12:23:36.262  3835  3993 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 12:23:36.262  3835  3993 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:23:36.262  3835  3993 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 12:23:36.262  3835  3993 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 12:23:36.262  3835  3993 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 12:23:36.262  3835  3993 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 12:23:36.262  3835  3993 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 12:23:36.262  3835  3917 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 12:23:36.262  3835  3995 I bt_vendor: hw_epilog_process
08-30 12:23:36.263  3835  3917 D bt_hci_bdroid: cleanup Finalizing cleanup
08-30 12:23:36.263  3835  3917 D bt_userial_mct: userial_close
08-30 12:23:36.263  3835  3917 E bt_userial_mct: pthread_join() FAILED result:3
08-30 12:23:36.263  3835  3917 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-30 12:23:36.265  6909  6909 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-30 12:23:36.268  6926  6926 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 12:23:36.286  1035  1784 I ActivityManager: Killing 5983:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-30 12:23:36.310  6909  6909 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-30 12:23:36.311  6909  6909 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-30 12:23:36.311  6909  6909 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-30 12:23:36.312  6909  6909 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-30 12:23:36.312  6909  6909 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-30 12:23:36.314  6909  6909 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-30 12:23:36.320  6909  6909 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-30 12:23:36.330  1035  1050 W libprocessgroup: failed to open /acct/uid_10011/pid_5983/cgroup.procs: No such file or directory
,08-30 12:23:36.336  3835  3917 D bt_hci_bdroid: set_power 0
08-30 12:23:36.336  3835  3917 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 12:23:36.336  3835  3917 I bt_vendor: bluetooth satus is on
08-30 12:23:36.336  3835  3917 I bt_vendor: bt-vendor : resetting BT status
08-30 12:23:36.336  3835  3917 I bt_vendor: Starting hciattach daemon
08-30 12:23:36.336  3835  3917 I bt_vendor: try to set false
08-30 12:23:36.338  3835  3917 I bt_vendor: Starting hciattach daemon
08-30 12:23:36.338  3835  3917 I bt_vendor: try to set false
08-30 12:23:36.339  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:23:36.340  3835  3917 I bt_vendor: cleanup
08-30 12:23:36.340  3835  3993 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 12:23:36.341  3835  3917 I GKI_LINUX: GKI_exit_task 0 done
08-30 12:23:36.341  3835  3917 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 12:23:36.342  3835  3912 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 12:23:36.345  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 12:23:36.347  3835  3835 D HeadsetService: Received stop request...Stopping profile...
08-30 12:23:36.350  3835  3835 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 12:23:36.350  3835  3835 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 12:23:36.350  3835  3942 D HeadsetStateMachine: Exit Disconnected: -1
08-30 12:23:36.350  3835  3835 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@185f2544
08-30 12:23:36.353  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-30 12:23:36.353  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-30 12:23:36.353  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-30 12:23:36.353  1035  1035 D BluetoothHeadset: Proxy object disconnected
08-30 12:23:36.353  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 12:23:36.354  3835  3835 D A2dpService: Received stop request...Stopping profile...
08-30 12:23:36.354  3835  3979 D A2dpStateMachine: Exit Disconnected: -1
08-30 12:23:36.355  3835  3835 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-30 12:23:36.357  3835  3912 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 12:23:36.358  3835  3835 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-30 12:23:36.358  3835  3835 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 12:23:36.358  3835  3835 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@185f2544
,08-30 12:23:36.360  1035  1035 D BluetoothA2dp: Proxy object disconnected
08-30 12:23:36.360  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 12:23:36.362  3835  3835 D HidService: Received stop request...Stopping profile...
08-30 12:23:36.362  3835  3835 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@185f2544
08-30 12:23:36.363  6850  6850 D BluetoothInputDevice: Proxy object disconnected
08-30 12:23:36.363  6850  6850 D HidProfile: Bluetooth service disconnected
08-30 12:23:36.364  3835  3835 D HealthService: Received stop request...Stopping profile...
08-30 12:23:36.364  3835  3835 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@185f2544
08-30 12:23:36.365  3835  3835 D HeadsetStateMachine: Unbinding service...
08-30 12:23:36.366  3835  3835 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 12:23:36.366  3835  3835 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 12:23:36.366  3835  3835 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 12:23:36.366  3835  3835 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 12:23:36.366  3835  3835 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 12:23:36.366  3835  3835 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 12:23:36.366  3835  3835 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 12:23:36.367  3835  3835 D PanService: Received stop request...Stopping profile...
08-30 12:23:36.367  3835  3835 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@185f2544
08-30 12:23:36.368  3835  3835 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 12:23:36.369  3835  3835 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 12:23:36.369  3835  3835 D BtGatt.GattService: stop()
08-30 12:23:36.369  6850  6850 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 12:23:36.369  6850  6850 D PanProfile: Bluetooth service disconnected
08-30 12:23:36.369  3835  3835 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 12:23:36.370  3835  3835 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@185f2544
,08-30 12:23:36.371  3835  3835 D BluetoothMapService: Received stop request...Stopping profile...
08-30 12:23:36.371  3835  3835 D BluetoothMapService: stop()
08-30 12:23:36.372  3835  3835 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 12:23:36.372  3835  3835 D BluetoothMapEmailAppObserver: removeReceiver()
08-30 12:23:36.373  3835  3835 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@185f2544
,08-30 12:23:36.373  6850  6850 D BluetoothMap: Proxy object disconnected
08-30 12:23:36.373  6850  6850 D MapProfile: Bluetooth service disconnected
08-30 12:23:36.374  3835  3835 I BluetoothA2dpServiceJni: cleanupNative
08-30 12:23:36.374  3835  3980 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 12:23:36.374  3835  3835 I GKI_LINUX: GKI_exit_task 2 done
08-30 12:23:36.374  3835  3835 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 12:23:36.375  3835  3835 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 12:23:36.375  3835  3835 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 12:23:36.375  3835  3835 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 12:23:36.375  3835  3835 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 12:23:36.375  3835  3835 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 12:23:36.376  3835  3835 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 12:23:36.376  3835  3835 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 12:23:36.377  3835  3835 V BluetoothMapService: Handler(): got msg=4
08-30 12:23:36.377  3835  3835 D BluetoothMapService: MAP Service closeService in
08-30 12:23:36.377  3835  3835 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 12:23:36.377  3835  3835 V BluetoothMapService: MAP Service closeService out
08-30 12:23:36.378  3835  3912 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 12:23:36.378  3835  3912 D BluetoothAdapterProperties: Setting state to 10
08-30 12:23:36.378  3835  3912 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 12:23:36.378  1035  1117 D BluetoothManagerService: Message: 60
08-30 12:23:36.378  3835  3912 I BluetoothAdapterState: Entering OffState
08-30 12:23:36.379  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 12:23:36.379  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-30 12:23:36.379  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 12:23:36.379  3835  3835 D BluetoothMapService: cleanup()
08-30 12:23:36.379  3835  3835 D BluetoothMapService: MAP Service closeService in
08-30 12:23:36.379  3835  3835 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 12:23:36.379  3835  3835 V BluetoothMapService: MAP Service closeService out
08-30 12:23:36.379  6850  6875 D BluetoothMap: onBluetoothStateChange: up=false
08-30 12:23:36.381  6850  6871 D BluetoothPan: onBluetoothStateChange on: false
08-30 12:23:36.381  6909  6909 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 12:23:36.382  6850  6875 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 12:23:36.384  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:23:36.385  1850  3944 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 12:23:36.386  6909  6909 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-30 12:23:36.387  6850  6871 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 12:23:36.388  1850  1866 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:23:36.388  1850  3951 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:23:36.389  6420  6420 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:23:36.390  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 12:23:36.390  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 12:23:36.392  6909  6909 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-30 12:23:36.394  1035  1117 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 12:23:36.394  1035  1117 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 12:23:36.395  1035  1117 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3b36d2ab mBinding = false
08-30 12:23:36.396  1035  1117 D BluetoothManagerService: Sending unbind request.
08-30 12:23:36.398  6881  6881 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 12:23:36.398  6881  6881 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 12:23:36.398  6881  6881 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 12:23:36.400  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-30 12:23:36.404  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 12:23:36.406  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:36.406  1939  2123 D LGBluetoothAPIService: Message: 2
08-30 12:23:36.406  1939  2123 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@e7b4ce7 mBinding = false
08-30 12:23:36.406  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 12:23:36.406  1939  2123 D LGBluetoothAPIService: Sending unbind request.
08-30 12:23:36.409  3835  3917 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-30 12:23:36.409  3835  3835 I GKI_LINUX: GKI_exit_task 1 done
08-30 12:23:36.409  3835  3835 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 12:23:36.410  3835  3835 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 12:23:36.410  3835  3835 I art     : --- WEIRD: removing null entry 246
08-30 12:23:36.410  3835  3835 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-30 12:23:36.410  3835  3835 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-30 12:23:36.410  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:36.411  3835  3835 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-30 12:23:36.412  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:36.413  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:36.414  1601  1601 D BluetoothAdapter: 292588892: getState() :  mService = null. Returning STATE_OFF
08-30 12:23:36.414  1601  1601 D BluetoothAdapter: 292588892: getState() :  mService = null. Returning STATE_OFF
08-30 12:23:36.415  3835  3835 I art     : System.exit called, status: 0
08-30 12:23:36.415  3835  3835 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 12:23:36.422  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:23:36.423  6850  6850 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-30 12:23:36.424  6850  6850 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 12:23:36.424  6850  6850 D LGBluetoothEventManager: [BTUI] clear device connection state
08-30 12:23:36.426  6850  6850 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 12:23:36.436   322  1396 V AudioFlinger: 3835 died, releasing its sessions
08-30 12:23:36.436   322  1396 V AudioFlinger:  pid 1850 @ 0
08-30 12:23:36.436   322  1396 V AudioFlinger:  pid 3415 @ 1
08-30 12:23:36.436   322  1396 V AudioFlinger:  pid 3415 @ 2
,08-30 12:23:36.437  6850  6850 D DockEventReceiver: finishStartingService: stopping service
08-30 12:23:36.440  6850  6850 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-30 12:23:36.455  1035  1784 I ActivityManager: Process com.android.bluetooth (pid 3835) has died
,08-30 12:23:36.456  1035  1784 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-30 12:23:36.462  2205  2205 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 12:23:36.463  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:23:36.464  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:23:36.467  6909  6909 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 12:23:36.472  6420  6420 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:23:36.479  6881  6881 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 12:23:36.479  6881  6881 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 12:23:36.479  6881  6881 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 12:23:36.483  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:23:36.491  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:23:36.491  6850  6850 D BluetoothPermissionRequest: onReceive
08-30 12:23:36.495  6850  6850 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 12:23:36.495  6850  6850 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-30 12:23:36.497  6850  6850 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 12:23:36.549  1035  2045 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6950 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-30 12:23:36.562  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:23:36.563  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:23:36.565  6909  6909 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 12:23:36.648  1035  1574 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6967 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-30 12:23:36.670  6950  6950 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-30 12:23:36.671  6950  6950 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 12:23:36.671  6950  6950 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-30 12:23:36.672  6950  6950 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 12:23:36.690  6950  6950 D BluetoothAdapterApp: Loading JNI Library
,08-30 12:23:36.719  6950  6950 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1aa25d75 Instance Count = 1
,08-30 12:23:36.726  6950  6950 D BluetoothAdapterApp: onCreate
08-30 12:23:36.746  6950  6950 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-30 12:23:36.746  6950  6950 D ProfileConfigQcom: Adding HeadsetService
08-30 12:23:36.746  6950  6950 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-30 12:23:36.746  6950  6950 D ProfileConfigQcom: Adding A2dpService
08-30 12:23:36.746  6950  6950 D ProfileConfigQcom: [BTUI] HidService is supported
08-30 12:23:36.746  6950  6950 D ProfileConfigQcom: Adding HidService
08-30 12:23:36.747  6950  6950 D ProfileConfigQcom: [BTUI] HealthService is supported
08-30 12:23:36.747  6950  6950 D ProfileConfigQcom: Adding HealthService
08-30 12:23:36.747  6950  6950 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-30 12:23:36.749  6950  6950 D ProfileConfigQcom: [BTUI] PanService is supported
08-30 12:23:36.749  6950  6950 D ProfileConfigQcom: Adding PanService
,08-30 12:23:36.749  6950  6950 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 12:23:36.750  6950  6950 D ProfileConfigQcom: Adding GattService
08-30 12:23:36.750  6950  6950 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-30 12:23:36.750  6950  6950 D ProfileConfigQcom: Adding BluetoothMapService
08-30 12:23:36.750  6950  6950 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 12:23:36.751  6950  6950 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-30 12:23:36.755  6850  6850 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 12:23:36.757  6950  6950 V LGMDMManagerInternal: Create singleton instance
08-30 12:23:36.761  6881  6881 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 12:23:36.764  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 12:23:36.773  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:23:36.788  6967  6990 W FormManager: Network not available. Please check & try again.
08-30 12:23:36.789  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 12:23:36.789  6850  6850 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-30 12:23:36.789  6850  6850 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 12:23:36.789  6850  6850 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 12:23:36.789  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 12:23:36.803  6850  6850 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 12:23:36.803  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 12:23:36.803  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 12:23:36.803  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 12:23:36.803  6850  6850 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 12:23:36.804  6850  6850 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-30 12:23:36.807  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 12:23:36.807  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 12:23:36.808  6967  6991 V FormManager: Network unavailable.
08-30 12:23:36.808  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:23:36.811  6967  6991 V FormManager: Network unavailable.
08-30 12:23:36.814  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:23:36.814  6950  6950 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:36.817  4306  6994 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 12:23:36.819  6950  6950 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-30 12:23:36.820  6950  6950 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 12:23:36.821  6950  6950 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 12:23:36.822  4306  6995 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 12:23:36.822  4306  6995 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 12:23:36.822  6881  6881 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-30 12:23:36.822  6950  6950 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:36.822  6881  6881 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 12:23:36.822  6881  6881 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 12:23:36.822  6950  6950 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-30 12:23:36.826  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 12:23:36.834  6926  6926 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-30 12:23:36.839  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:23:36.843  1035  1051 I ActivityManager: Killing 6005:com.android.contacts/u0a19 (adj 15): empty #17
08-30 12:23:36.874  1035  1993 W libprocessgroup: failed to open /acct/uid_10019/pid_6005/cgroup.procs: No such file or directory
,08-30 12:23:36.880  6967  6997 W FormManager: Network not available. Please check & try again.
08-30 12:23:36.882  6967  6998 V FormManager: Network unavailable.
08-30 12:23:36.886  6967  6998 V FormManager: Network unavailable.
08-30 12:23:36.895  6909  6909 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-30 12:23:36.899  6909  6909 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 12:23:36.899  6909  6909 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-30 12:23:36.899  1035  1884 I ActivityManager: Killing 6513:com.lge.email/u0a23 (adj 15): empty #17
,08-30 12:23:36.934  6909  6909 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:23:36.934  6909  6909 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:23:36.941  6909  6909 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-30 12:23:36.942  6909  6909 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-30 12:23:36.942  6909  6909 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-30 12:23:36.942  6909  6909 V SoundPool: doLoad: loading sample sampleID=1
08-30 12:23:36.943  6909  6909 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 12:23:36.945  6909  7006 V SoundPool: Start decode
08-30 12:23:36.945  6909  7006 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-30 12:23:36.945   322  2133 V MediaPlayerService: decode(23, 10857164, 17813)
08-30 12:23:36.945   322  2133 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-30 12:23:36.945   322  2133 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-30 12:23:36.945   322  2133 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-30 12:23:36.945   322  2133 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-30 12:23:36.945   322  2133 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-30 12:23:36.945   322  2133 V MediaPlayerService: player type = 3
08-30 12:23:36.945   322  2133 V AwesomePlayer: AwesomePlayer create()
08-30 12:23:36.946   322  2133 V AwesomePlayer: reset_l() 
08-30 12:23:36.946   322  2133 V AwesomePlayer: cancelPlayerEvents
08-30 12:23:36.946   322  2133 V AwesomePlayer: setAudioSink() 
08-30 12:23:36.946   322  2133 V AwesomePlayer: reset_l() 
08-30 12:23:36.946   322  2133 V AudioCache: notify(0xb16a6ac0, 8, 0, 0)
08-30 12:23:36.946   322  2133 V AudioCache: ignored
08-30 12:23:36.946   322  2133 V AwesomePlayer: cancelPlayerEvents
08-30 12:23:36.946   322  2133 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-30 12:23:36.946   322  2133 V AwesomePlayer: setDataSource_l dataSource
08-30 12:23:36.946   322  2133 V LGParserOSAL: SniffLGParser start
08-30 12:23:36.946   322  2133 V LGParserOSAL: MainType:5, SubType=0
08-30 12:23:36.946   322  2133 V LGParserOSAL: #### check Mime : application/ogg
08-30 12:23:36.946   322  2133 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-30 12:23:36.946   322  2133 E MediaExtractor: Use LGExtractor :application/ogg 
08-30 12:23:36.980   322  2133 V LGParserOSAL: supported mime: application/ogg
08-30 12:23:36.980   322  2133 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-30 12:23:36.980   322  2133 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-30 12:23:36.980   322  2133 V AwesomePlayer: mBitrate = -1 bits/sec
08-30 12:23:36.980   322  2133 V AwesomePlayer: AudioTrack Setting
08-30 12:23:36.980   322  2133 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-30 12:23:36.980   322  2133 V AwesomePlayer: setAudioSource() 
08-30 12:23:36.980   322  2133 V MediaPlayerService: prepare
08-30 12:23:36.980   322  2133 V AwesomePlayer: prepareAsync_l() 
08-30 12:23:36.980   322  2133 V MediaPlayerService: wait for prepare
08-30 12:23:36.981   322  7007 V AwesomePlayer: onPrepareAsyncEvent() 
08-30 12:23:36.981   322  7007 V AwesomePlayer: initAudioDecoder() 
08-30 12:23:36.981   322  7007 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 12:23:36.981   322  7007 V AudioSystem: isOffloadSupported()
08-30 12:23:36.981   322  7007 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 12:23:36.981   322  7007 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 12:23:36.981   322  7007 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 12:23:36.981   322  7007 V AwesomePlayer: getUseOffload() = 0 
08-30 12:23:36.981   322  7007 V OMXCodec: OMXCodec::Create
08-30 12:23:36.981   322  7007 V OMXCodec: findMatchingCodecs()
08-30 12:23:36.981   322  7007 V OMXCodec: matching 'OMX.google.vorbis.decoder' quir,ks 0x00000000
08-30 12:23:36.981   322  7007 V OMXCodec: matchingCodecs.size()=1
08-30 12:23:36.982   322  7007 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-30 12:23:36.988   322  7007 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-30 12:23:36.988   322  7007 V LGCodecAdapter: LG Codec Adapter start
08-30 12:23:36.988   322  7007 V OMXCodec: OMXCodec Createtor
08-30 12:23:36.988   322  7007 V OMXCodec: setComponentRole
08-30 12:23:36.988   322  7007 V OMXCodec: configureCodec protected=0
08-30 12:23:36.988  1035  1938 W libprocessgroup: failed to open /acct/uid_10023/pid_6513/cgroup.procs: No such file or directory
08-30 12:23:36.988   322  7007 V LGCodecAdapter: called getLGCodecSpecificData
08-30 12:23:36.988   322  7007 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-30 12:23:36.988   322  7007 V LGCodecOSAL: Called LGconfigureCodecMETA
08-30 12:23:36.988   322  7007 V LGCodecOSAL: Called LGconfigureCodecMSG
08-30 12:23:36.988   322  7007 V LGCodecOSAL: Not support LGCodec
08-30 12:23:36.988   322  7007 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 12:23:36.989   322  7007 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-30 12:23:36.989   322  7007 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-30 12:23:36.989   322  7007 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-30 12:23:36.989   322  7007 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 12:23:36.989   322  7007 V AudioSystem: isOffloadSupported()
08-30 12:23:36.989   322  7007 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 12:23:36.989   322  7007 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 12:23:36.989   322  7007 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-30 12:23:36.989   322  7007 V OMXCodec: init()
08-30 12:23:36.989   322  7007 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-30 12:23:36.990   322  7007 V OMXCodec: allocateBuffers
08-30 12:23:36.990   322  7007 V OMXCodec: allocateBuffersOnPort portIndex=0
08-30 12:23:36.990   322  7007 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-30 12:23:36.991   322  7007 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-30 12:23:36.991   322  7007 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-30 12:23:36.991   322  7007 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-30 12:23:36.991   322  7007 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-30 12:23:36.991   322  7007 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 12:23:36.991   322  7007 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 12:23:36.992   322  7007 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-30 12:23:36.992   322  7007 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-30 12:23:36.992   322  7007 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-30 12:23:36.992   322  7007 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd1f0 on output port
08-30 12:23:36.992   322  7007 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 12:23:36.992   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 12:23:36.992   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 12:23:36.992   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-30 12:23:36.993   322  7007 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 12:23:36.993   322  7009 V OMXCodec: [OMX.google.vorbis.decod,er] onStateChange 3
08-30 12:23:36.993   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-30 12:23:36.993   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-30 12:23:36.993   322  7007 V OMXCodec: init() mAsyncCompletion wait free! 
08-30 12:23:36.993   322  7007 V AwesomePlayer: finishAsyncPrepare_l() 
08-30 12:23:36.993   322  7007 V AudioCache: notify(0xb16a6ac0, 5, 0, 0)
08-30 12:23:36.993   322  7007 V AudioCache: ignored
08-30 12:23:36.993   322  7007 V AudioCache: notify(0xb16a6ac0, 1, 0, 0)
08-30 12:23:36.993   322  7007 V AudioCache: prepared
08-30 12:23:36.993   322  2133 V AudioCache: wait - success
08-30 12:23:36.994   322  2133 V MediaPlayerService: start
08-30 12:23:36.994   322  2133 V AwesomePlayer: play_l() 
08-30 12:23:36.994   322  2133 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-30 12:23:36.995   322  2133 V AwesomePlayer: createAudioPlayer_l
08-30 12:23:36.995   322  2133 V AwesomePlayer: seekAudioIfNecessary_l() 
08-30 12:23:36.995   322  2133 V AwesomePlayer: startAudioPlayer_l() 
08-30 12:23:36.995   322  2133 D AudioPlayer: start of Playback, useOffload 0
08-30 12:23:36.995   322  2133 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 12:23:36.995   322  2133 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 12:23:36.996  6909  6909 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-30 12:23:36.999  6909  6909 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 12:23:36.999  6909  6909 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 12:23:36.999  6656  6656 D UEI.SmartControl: QS Service created
,08-30 12:23:37.005   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-30 12:23:37.005   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
,08-30 12:23:37.005   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-30 12:23:37.005   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-30 12:23:37.005   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-30 12:23:37.005   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 12:23:37.005   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-30 12:23:37.005   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 12:23:37.005   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
08-30 12:23:37.006   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 12:23:37.006   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
08-30 12:23:37.006   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-30 12:23:37.006   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044790768
08-30 12:23:37.006   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 12:23:37.006   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-30 12:23:37.006   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 12:23:37.006   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-30 12:23:37.006   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-30 12:23:37.006   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-30 12:23:37.006   322  7009 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 12:23:37.006   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,08-30 12:23:37.006   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-30 12:23:37.006   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-30 12:23:37.006   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-30 12:23:37.006   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bd6a0 on output port
08-30 12:23:37.013  6909  6909 V LGMDMManager: Create singleton instance
08-30 12:23:37.015   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-30 12:23:37.015   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-30 12:23:37.016   322  2133 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-30 12:23:37.017   322  2133 V AudioCache: notify(0xb16a6ac0, 6, 0, 0)
,08-30 12:23:37.017   322  2133 V AudioCache: ignored
,08-30 12:23:37.018   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.018   322  7011 V AudioCache: memcpy(0xaf004000, 0xb16f6000, 4096)
08-30 12:23:37.018   322  2133 V MediaPlayerService: wait for playback complete
08-30 12:23:37.020   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.020   322  7011 V AudioCache: memcpy(0xaf005000, 0xb16f6000, 4096)
08-30 12:23:37.020   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.020   322  7011 V AudioCache: memcpy(0xaf006000, 0xb16f6000, 4096)
08-30 12:23:37.021   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.021   322  7011 V AudioCache: memcpy(0xaf007000, 0xb16f6000, 4096)
08-30 12:23:37.021   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.021   322  7011 V AudioCache: memcpy(0xaf008000, 0xb16f6000, 4096)
08-30 12:23:37.022   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.022   322  7011 V AudioCache: memcpy(0xaf009000, 0xb16f6000, 4096)
08-30 12:23:37.022   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.022   322  7011 V AudioCache: memcpy(0xaf00a000, 0xb16f6000, 4096)
08-30 12:23:37.022   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.023   322  7011 V AudioCache: memcpy(0xaf00b000, 0xb16f6000, 4096)
08-30 12:23:37.023   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.023   322  7011 V AudioCache: memcpy(0xaf00c000, 0xb16f6000, 4096)
08-30 12:23:37.024   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.024   322  7011 V AudioCache: memcpy(0xaf00d000, 0xb16f6000, 4096)
08-30 12:23:37.024   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.024   322  7011 V AudioCache: memcpy(0xaf00e000, 0xb16f6000, 4096)
08-30 12:23:37.024   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.024   322  7011 V AudioCache: memcpy(0xaf00f000, 0xb16f6000, 4096)
08-30 12:23:37.024   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.024   322  7011 V AudioCache: memcpy(0xaf010000, 0xb16f6000, 4096)
08-30 12:23:37.025   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.025   322  7011 V AudioCache: memcpy(0xaf011000, 0xb16f6000, 4096)
08-30 12:23:37.026   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.026   322  7011 V AudioCache: memcpy(0xaf012000, 0xb16f6000, 4096)
08-30 12:23:37.026   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.026   322  7011 V AudioCache: memcpy(0xaf013000, 0xb16f6000, 4096)
08-30 12:23:37.027   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.027   322  7011 V AudioCache: memcpy(0xaf014000, 0xb16f6000, 4096)
08-30 12:23:37.027   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.027   322  7011 V AudioCache: memcpy(0xaf015000, 0xb16f6000, 4096)
08-30 12:23:37.028   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.028   322  7011 V AudioCache: memcpy(0xaf016000, 0xb16f6000, 4096)
08-30 12:23:37.028   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.028   322  7011 V AudioCache: memcpy(0xaf017000, 0xb16f6000, 4096)
08-30 12:23:37.029   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.029   322  7011 V AudioCache: memcpy(0xaf018000, 0xb16f6000, 4096)
08-30 12:23:37.030   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.030   322  7011 V AudioCache: memcpy(0xaf019000, 0xb16f6000, 4096)
,08-30 12:23:37.030   322  7011 V AudioCache: write(0xb16f6000, 4096),
08-30 12:23:37.030   322  7011 V AudioCache: memcpy(0xaf01a000, 0xb16f6000, 4096)
08-30 12:23:37.031   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.031   322  7011 V AudioCache: memcpy(0xaf01b000, 0xb16f6000, 4096)
08-30 12:23:37.032  6656  6656 I UEI.SmartControl: Service initServices...
08-30 12:23:37.032   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.032   322  7011 V AudioCache: memcpy(0xaf01c000, 0xb16f6000, 4096),
08-30 12:23:37.032  6656  6656 D UEI.SmartControl: QS start get config
08-30 12:23:37.032   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.032   322  7011 V AudioCache: memcpy(0xaf01d000, 0xb16f6000, 4096)
08-30 12:23:37.033   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.033   322  7011 V AudioCache: memcpy(0xaf01e000, 0xb16f6000, 4096)
08-30 12:23:37.034   322  7011 V AudioCache: write(0xb16f6000, 4096)
,08-30 12:23:37.034   322  7011 V AudioCache: memcpy(0xaf01f000, 0xb16f6000, 4096)
08-30 12:23:37.035   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.035   322  7011 V AudioCache: memcpy(0xaf020000, 0xb16f6000, 4096)
08-30 12:23:37.035   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.035   322  7011 V AudioCache: memcpy(0xaf021000, 0xb16f6000, 4096)
08-30 12:23:37.036   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.036   322  7011 V AudioCache: memcpy(0xaf022000, 0xb16f6000, 4096)
08-30 12:23:37.037   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.037   322  7011 V AudioCache: memcpy(0xaf023000, 0xb16f6000, 4096)
08-30 12:23:37.037   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.037   322  7011 V AudioCache: memcpy(0xaf024000, 0xb16f6000, 4096)
08-30 12:23:37.038   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.038   322  7011 V AudioCache: memcpy(0xaf025000, 0xb16f6000, 4096)
08-30 12:23:37.038   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.038   322  7011 V AudioCache: memcpy(0xaf026000, 0xb16f6000, 4096)
08-30 12:23:37.039   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.039   322  7011 V AudioCache: memcpy(0xaf027000, 0xb16f6000, 4096)
08-30 12:23:37.039   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.040   322  7011 V AudioCache: memcpy(0xaf028000, 0xb16f6000, 4096)
08-30 12:23:37.040   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.040   322  7011 V AudioCache: memcpy(0xaf029000, 0xb16f6000, 4096)
08-30 12:23:37.041   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.041   322  7011 V AudioCache: memcpy(0xaf02a000, 0xb16f6000, 4096)
08-30 12:23:37.041   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.041   322  7011 V AudioCache: memcpy(0xaf02b000, 0xb16f6000, 4096)
,08-30 12:23:37.042   322  7011 V AudioCache: write(0xb16f6000, 4096)
,08-30 12:23:37.042   322  7011 V AudioCache: memcpy(0xaf02c000, 0xb16f6000, 4096)
08-30 12:23:37.043   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.043   322  7011 V AudioCache: memcpy(0xaf02d000, 0xb16f6000, 4096)
08-30 12:23:37.043   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.043   322  7011 V AudioCache: memcpy(0xaf02e000, 0xb16f6000, 4096)
08-30 12:23:37.044   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.044   322  7011 V AudioCache: memcpy(0xaf02f000, 0xb16f6000, 4096)
08-30 12:23:37.045   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.045   322  7011 V AudioCache: memcpy(0xaf030000, 0xb16f6000, 4096)
08-30 12:23:37.046   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.046   322  7011 V AudioCache: memcpy(0xaf031000, 0xb16f6000, 4096)
08-30 12:23:37.046   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.046   322  7011 V AudioCache: memcpy(0xaf032000, 0xb16f6000, 4096)
08-30 12:23:37.047   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.047   322  7011 V AudioCache: memcpy(0xaf033000, 0xb16f6000, 4096)
08-30 12:23:37.047   322  7011 V AudioCache: write(0xb16f6000, 4096)
,08-30 12:23:37.047   322  7011 V AudioCache: memcpy(0xaf034000, 0xb16f6000, 4096)
08-30 12:23:37.048   322  7011 V AudioCache: write(0xb16f6000, 4096)
08-30 12:23:37.048   322  7011 V AudioCache: memcpy(0xaf035000, 0xb16f6000, 4096)
08-30 12:23:37.048   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-30 12:23:37.049   322  7011 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 12:23:37.049   322  7011 V AwesomePlayer: postAudioEOS() 
08-30 12:23:37.049   322  7011 V AudioCache: write(0xb16f6000, 280)
08-30 12:23:37.049   322  7011 V AudioCache: memcpy(0xaf036000, 0xb16f6000, 280)
08-30 12:23:37.050   322  7007 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-30 12:23:37.050   322  7007 V AwesomePlayer: onStreamDone
08-30 12:23:37.050   322  7007 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-30 12:23:37.050   322  7007 V AudioCache: notify(0xb16a6ac0, 2, 0, 0)
08-30 12:23:37.050   322  7007 V AudioCache: playback complete
,08-30 12:23:37.050   322  7007 V AwesomePlayer: pause_l() 
08-30 12:23:37.050   322  7007 V AudioCache: notify(0xb16a6ac0, 7, 0, 0)
08-30 12:23:37.050   322  7007 V AudioCache: ignored
08-30 12:23:37.050   322  7007 V AwesomePlayer: cancelPlayerEvents
08-30 12:23:37.050   322  2133 V AudioCache: wait - success
08-30 12:23:37.050   322  2133 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-30 12:23:37.050   322  7007 D AudioPlayer: Pause Playback at 1068125
08-30 12:23:37.051   322  2133 V AwesomePlayer: reset_l() 
08-30 12:23:37.051   322  2133 V AudioCache: notify(0xb16a6ac0, 8, 0, 0)
08-30 12:23:37.051   322  2133 V AudioCache: ignored
08-30 12:23:37.051   322  2133 V AwesomePlayer: cancelPlayerEvents
08-30 12:23:37.051   322  2133 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
,08-30 12:23:37.051   322  2133 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-30 12:23:37.051   322  2133 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-30 12:23:37.051   322  2133 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-30 12:23:37.051   322  2133 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 12:23:37.051   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 12:23:37.051   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 12:23:37.051   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-30 12:23:37.051   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-30 12:23:37.051   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-30 12:23:37.052   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-30 12:23:37.052   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-30 12:23:37.052   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
,08-30 12:23:37.052   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-30 12:23:37.052   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-30 12:23:37.052   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-30 12:23:37.052   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 12:23:37.052   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bd6a0 on port 1
08-30 12:23:37.052   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-30 12:23:37.052   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-30 12:23:37.052   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-30 12:23:37.052   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
08-30 12:23:37.052   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-30 12:23:37.052   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
,08-30 12:23:37.052   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 12:23:37.052   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-30 12:23:37.052   322  2133 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 12:23:37.052   322  2133 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 12:23:37.052   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-30 12:23:37.052   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-30 12:23:37.052   322  7009 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-30 12:23:37.052   322  2133 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 12:23:37.052   322  2133 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-30 12:23:37.052   322  2133 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-30 12:23:37.053   322  2133 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-30 12:23:37.053   322  2133 D AudioPlayer: AudioPlayer releasing audio source
,08-30 12:23:37.053   322  2133 D AudioPlayer: AudioPlayer done releasing audio source
08-30 12:23:37.053   322  2133 V AwesomePlayer: reset_l() 
08-30 12:23:37.053   322  2133 V AwesomePlayer: cancelPlayerEvents
08-30 12:23:37.054   322  2133 V AwesomePlayer: ~AwesomePlayer call
08-30 12:23:37.054   322  2133 V AwesomePlayer: reset_l() 
08-30 12:23:37.054   322  2133 V AwesomePlayer: cancelPlayerEvents
08-30 12:23:37.054  6909  7006 V SoundPool: close(31)
08-30 12:23:37.054  6909  7006 V SoundPool: pointer = 0x9fe78000, size = 205080, sampleRate = 48000, numChannels = 2
,08-30 12:23:37.101  6909  6909 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 12:23:37.103  6909  6909 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-30 12:23:37.105  6909  6909 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4781
,08-30 12:23:37.331  6656  6656 I UEI.SmartControl: Supports setup maps: true,
,08-30 12:23:37.334  6656  6656 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 12:23:37.334  6656  6656 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 12:23:37.334  6656  6656 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 12:23:37.334  6656  6656 I UEI.SmartControl: ### init IR Blaster...
08-30 12:23:37.337  6656  6656 D serial_port: Configuring serial port
08-30 12:23:37.337  6656  6656 E UEI.SmartControl: UEIBLaster setting for 616
08-30 12:23:37.338  6656  6656 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 12:23:37.338  6656  6656 I UEI.SmartControl: configuring settings for MAXQ616
08-30 12:23:37.338  6656  6656 I UEI.SmartControl: Get version...
08-30 12:23:37.352  6656  7015 D UEI.SmartControl: serial port data available: 21
,08-30 12:23:37.384  6656  6656 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-30 12:23:37.384  6656  6656 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 12:23:37.384  6656  6656 I UEI.SmartControl: QS saving settings...
,08-30 12:23:37.386  6656  6656 D UEI.SmartControl: IR Blaster version: 25672567
08-30 12:23:37.406  6656  7015 D UEI.SmartControl: serial port data available: 4
,08-30 12:23:37.441  6656  7021 I UEI.SmartControl: Device manager: loading config....
,08-30 12:23:37.442  6656  7021 D UEI.SmartControl: ----------- loading internal config...
,08-30 12:23:37.443  6656  6656 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-30 12:23:37.450  6656  6656 E UEI.SmartControl: Services init done
08-30 12:23:37.450  6656  6656 D UEI.SmartControl: QS Service init finished
08-30 12:23:37.452  6656  6656 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 12:23:37.452  6656  6656 D UEI.SmartControl: QS Service version code: 201091
08-30 12:23:37.453  6656  6656 D UEI.SmartControl: Service requested: Control
08-30 12:23:37.468  6656  6656 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-30 12:23:37.478  6909  6909 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-30 12:23:37.480  6656  6672 I UEI.SmartControl: ------ IControl API: 11
08-30 12:23:37.480  6656  6656 D UEI.SmartControl: Internal service binding...
08-30 12:23:37.481  6656  6672 D UEI.SmartControl: File observer start...
08-30 12:23:37.482  6656  6672 E UEI.SmartControl: IR Port is disabled: false
08-30 12:23:37.482  6656  6672 D UEI.SmartControl: Starting file observer...
08-30 12:23:37.484  6656  6672 I UEI.SmartControl: Registering callback...
,08-30 12:23:37.490  6656  6671 I UEI.SmartControl: ------ IControl API: 19
08-30 12:23:37.491  6656  6671 I UEI.SmartControl: Registering Services Ready callback...
08-30 12:23:37.492  6656  7021 E UEI.SmartControl: Loading SETTINGS...
08-30 12:23:37.496  6656  7021 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 12:23:37.521  6656  7020 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-30 12:23:37.524  6909  6924 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-30 12:23:37.524  6909  7004 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-30 12:23:37.525  6909  7004 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-30 12:23:37.525  6909  6909 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-30 12:23:37.526  6656  7020 D UEI.SmartControl: -----service ready thread exits
08-30 12:23:37.526  6909  6909 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-30 12:23:37.527  6656  6672 I UEI.SmartControl: ------ IControl API: 8
08-30 12:23:37.529  6909  6909 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-30 12:23:37.529  6909  6909 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-30 12:23:37.529  6909  6909 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-30 12:23:37.530  6909  6909 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-30 12:23:37.531  6909  6909 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-30 12:23:37.531  6909  6909 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-30 12:23:37.535  6909  6909 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-30 12:23:37.541  6909  6909 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 12:23:37.542  6909  6909 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 12:23:37.542  6909  6909 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 12:23:37.543  6909  6909 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 12:23:37.544  6909  6909 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 12:23:37.545  6909  6909 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-30 12:23:37.545  6909  6909 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-30 12:23:37.547  6909  6909 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472552617546]
08-30 12:23:37.552  6909  6909 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-30 12:23:37.558  1035  1993 I ActivityManager: Killing 6034:com.android.gallery3d/u0a27 (adj 15): empty #17
08-30 12:23:37.594  6909  7026 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-30 12:23:37.600  1035  1956 W libprocessgroup: failed to open /acct/uid_10027/pid_6034/cgroup.procs: No such file or directory
08-30 12:23:37.607  6909  6909 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-30 12:23:37.610  6909  6909 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 12:23:37.610  6909  6909 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-30 12:23:37.610  6909  6909 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-30 12:23:37.611  6909  6909 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-30 12:23:37.611  6909  6909 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-30 12:23:37.611  6909  6909 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-30 12:23:37.620  6909  6909 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-30 12:23:37.628  1035  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=290167141, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
08-30 12:23:37.629  1035  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{170ec7ac type 2 when 334859 com.google.android.gms} when 334859
08-30 12:23:37.638   316  7028 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 12:23:37.639  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-30 12:23:37.659  2575  2575 D [Concierge]Service: onStartCommand(). Type : 9
,08-30 12:23:37.701  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=290167141 [*alarm*], flags=0x0
,08-30 12:23:38.351  1035  3527 I LocationManagerService: remove e94d8e3
08-30 12:23:38.352  1035  3527 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-30 12:23:38.352  1035  3527 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 12:23:38.353  1035  3527 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-30 12:23:38.355  1035  3527 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,08-30 12:23:38.365  1035  3527 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-30 12:23:38.471  1035  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:23:38.488  1035  1117 D Tethering: MasterInitialState.processMessage what=3
08-30 12:23:38.500  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:23:38.504  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:38.508  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:38.510  1035  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:38.512  1035  1117 D Tethering: MasterInitialState.processMessage what=3
,08-30 12:23:38.517  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:38.524  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:23:38.527  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:38.528  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:38.530  6420  6420 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 12:23:38.534  6420  6879 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 12:23:38.544  5736  5736 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 12:23:38.552  5736  5736 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 12:23:38.571  2205  2205 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:23:38.616  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:23:38.646  1035  1574 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7038 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-30 12:23:38.662  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 12:23:38.663  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 12:23:38.712  7038  7038 I AppUp4:AppBoxCP: onCreate
08-30 12:23:38.713  7038  7038 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-30 12:23:38.718  7038  7038 I AppUp4:DB:  setFingerPrint start
08-30 12:23:38.719  7038  7038 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-30 12:23:38.723  7038  7038 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-30 12:23:38.723  7038  7038 I AppUp4:DB:  SDK version = 21
08-30 12:23:38.723  7038  7038 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-30 12:23:38.725  7038  7038 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-30 12:23:38.726  7038  7038 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 12:23:38.726  7038  7038 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:38.727  7038  7038 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 12:23:38.727  7038  7038 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 12:23:38.733  7038  7038 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 12:23:38.758  7038  7038 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:23:38.758  7038  7038 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:23:38.763  7038  7038 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@175ac657
08-30 12:23:38.763  7038  7038 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 12:23:38.763  7038  7038 D AppUp4:CustFacade: isPhone : true
08-30 12:23:38.764  7038  7038 D AppUp4:CustModeStarterReceiver: begin check event
08-30 12:23:38.764  7038  7038 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-30 12:23:38.764  7038  7038 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-30 12:23:38.765  7038  7070 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-30 12:23:38.765  7038  7070 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-30 12:23:38.766  7038  7070 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-30 12:23:38.769  1035  1993 I ActivityManager: Killing 6100:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-30 12:23:38.861  1035  2045 W libprocessgroup: failed to open /acct/uid_10080/pid_6100/cgroup.procs: No such file or directory
,08-30 12:23:38.863  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:38.864  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 12:23:38.873  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:23:38.879  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:23:38.894  4306  7075 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 12:23:38.903  4306  7076 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:38.903  4306  7076 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 12:23:38.976  1035  2029 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7077 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 12:23:39.083  7077  7077 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:23:39.084  7077  7077 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 12:23:39.086  7077  7077 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 12:23:39.087  7077  7077 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-30 12:23:39.194  7077  7077 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-30 12:23:39.210  7077  7077 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-30 12:23:39.267  7077  7077 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 12:23:39.309  7077  7077 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 12:23:39.309  7077  7077 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:23:39.449  7077  7077 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 12:23:39.502  3415  3415 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 12:23:39.502  3415  3415 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:39.503  3415  3415 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-30 12:23:39.513  7077  7077 I HubEmail: JNI_OnLoad()
08-30 12:23:39.513  7077  7077 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 12:23:39.513  7077  7077 I HubEmail: registerNatives()
08-30 12:23:39.513  7077  7077 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 12:23:39.513  7077  7077 I HubEmail: registerNativeMethods()
08-30 12:23:39.513  7077  7077 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 12:23:39.513  7077  7077 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-30 12:23:39.560  1035  1975 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7109 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-30 12:23:39.571  6967  7106 W FormManager: Network not available. Please check & try again.
08-30 12:23:39.575  7077  7108 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 12:23:39.581  6967  7107 V FormManager: Network unavailable.
08-30 12:23:39.591  6967  7107 V FormManager: Network unavailable.
,08-30 12:23:39.600  1035  1993 I ActivityManager: Killing 6553:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-30 12:23:39.723  1035  1574 W libprocessgroup: failed to open /acct/uid_10061/pid_6553/cgroup.procs: No such file or directory
,08-30 12:23:39.805  7109  7109 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:23:39.805  7109  7109 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:23:39.809  7109  7109 D PhoneMonitor: Register our PhoneStateListener
08-30 12:23:39.833  7109  7109 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-30 12:23:39.838  7109  7109 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 12:23:39.858  7109  7109 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-30 12:23:39.859  7109  7109 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-30 12:23:39.859  7109  7109 D TelephonyAutoProfiling: [parse] Load xml
08-30 12:23:39.863  7109  7109 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-30 12:23:39.863  7109  7109 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-30 12:23:39.863  7109  7109 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-30 12:23:39.863  7109  7109 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-30 12:23:39.863  7109  7109 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-30 12:23:39.863  7109  7109 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-30 12:23:39.863  7109  7109 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-30 12:23:39.863  7109  7109 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-30 12:23:39.863  7109  7109 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-30 12:23:39.863  7109  7109 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-30 12:23:39.863  7109  7109 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-30 12:23:39.863  7109  7109 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-30 12:23:39.863  7109  7109 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-30 12:23:39.864  7109  7109 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-30 12:23:39.864  7109  7109 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-30 12:23:39.864  7109  7109 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-30 12:23:39.864  7109  7109 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-30 12:23:39.877  7109  7109 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-30 12:23:39.908  1035  2045 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7134 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 12:23:39.909  1035  2045 I ActivityManager: Killing 6129:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-30 12:23:39.968  1035  1784 W libprocessgroup: failed to open /acct/uid_10097/pid_6129/cgroup.procs: No such file or directory
,08-30 12:23:40.225  1035  1784 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7158 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-30 12:23:40.241  1035  1784 I ActivityManager: Killing 6610:com.lge.eula/1000 (adj 15): empty #17
,08-30 12:23:40.325  1035  1050 D WifiServiceImplEx: setWifiEnabled: true pid=6741, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 12:23:40.326  1035  1957 W libprocessgroup: failed to open /acct/uid_1000/pid_6610/cgroup.procs: No such file or directory
08-30 12:23:40.327  1035  1050 D WifiService: setWifiEnabled: true pid=6741, uid=10118
08-30 12:23:40.327  1035  1050 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 12:23:40.336  1035  1437 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-30 12:23:40.336  1035  1437 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-30 12:23:40.340  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 12:23:40.341  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 12:23:40.341  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-30 12:23:40.341  1035  1437 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-30 12:23:40.341  1035  1437 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 12:23:40.341  1035  1437 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-30 12:23:40.341  1035  1437 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 12:23:40.341  1035  1437 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 12:23:40.341  1035  1437 E WifiHW  : unknown target_country: EU , set to default
08-30 12:23:40.341  1035  1437 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-30 12:23:40.341  1035  1437 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 12:23:40.341  1035  1437 I WifiUtil: gEnableBmps=1
,08-30 12:23:40.431  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:40.431  1035  1390 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 12:23:40.503  1035  1784 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7191 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 12:23:40.506  1035  1784 I ActivityManager: Killing 2126:com.lge.music/u0a34 (adj 15): empty #17
08-30 12:23:40.548   322   322 V AudioFlinger: 2126 died, releasing its sessions
08-30 12:23:40.548   322   322 V AudioFlinger:  pid 1850 @ 0
08-30 12:23:40.548   322   322 V AudioFlinger:  pid 3415 @ 1
08-30 12:23:40.548   322   322 V AudioFlinger:  pid 3415 @ 2
,08-30 12:23:40.577  1035  2029 W libprocessgroup: failed to open /acct/uid_10034/pid_2126/cgroup.procs: No such file or directory
,08-30 12:23:40.629  7191  7191 I art     : Almond Protected OAT
,08-30 12:23:40.689  7191  7191 D WeatherApplication: removeAccount
,08-30 12:23:40.692  7191  7191 D WeatherApplication: Account.length = 0
,08-30 12:23:40.692  7191  7191 E WeatherApplication: OPERATOR:OPEN
,08-30 12:23:40.703  7191  7191 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:23:40
,08-30 12:23:40.707  7191  7191 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-30 12:23:40.707  7191  7191 D Weather.Utils: 2 : All the weather widget is gone.
08-30 12:23:40.711  7191  7191 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-30 12:23:40.715  7191  7191 D WeatherAncestor: connectivity changed - connection : true
,08-30 12:23:40.716  7191  7191 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-30 12:23:40.728  7191  7191 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 12:23:40.729  7191  7191 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 12:23:40.729  7191  7191 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-30 12:23:40.753  7191  7191 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-30 12:23:40.753  7191  7191 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:23:40
,08-30 12:23:40.811  1035  1884 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7212 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 12:23:40.814  1035  1884 I ActivityManager: Killing 6630:com.lge.bnr/1000 (adj 15): empty #17
,08-30 12:23:40.855  1035  1885 W libprocessgroup: failed to open /acct/uid_1000/pid_6630/cgroup.procs: No such file or directory
,08-30 12:23:40.982   280   444 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-30 12:23:40.983   280   444 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 12:23:40.983   280   444 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 12:23:40.985  7212  7235 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-30 12:23:40.988   280   444 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 12:23:40.988   280   444 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 12:23:40.988   280   444 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 12:23:40.988  7212  7235 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 12:23:41.011   280   444 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 12:23:41.011   280   444 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 12:23:41.011   280   444 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 12:23:41.012  7212  7242 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-30 12:23:41.016   280   444 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 12:23:41.016   280   444 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 12:23:41.016   280   444 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 12:23:41.016  7212  7242 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 12:23:41.158  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 12:23:41.158  1035  1117 D Tethering: InitialState.processMessage what=4
08-30 12:23:41.158  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 12:23:41.163   316   893 D SoftapController: Softap fwReload - Ok
08-30 12:23:41.166  1035  1437 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (817ms)
08-30 12:23:41.169   316   893 D CommandListener: Setting iface cfg
08-30 12:23:41.169   316   893 D CommandListener: Trying to bring down wlan0
08-30 12:23:41.169   316   893 D CommandListener: Clearing all IP addresses on wlan0
08-30 12:23:41.171  1035  1437 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-30 12:23:41.166  7248  7248 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 12:23:41.166  7248  7248 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:23:41.201  7248  7248 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-30 12:23:41.235  7248  7248 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 12:23:41.235  7248  7248 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-30 12:23:41.272  1035  1437 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 12:23:41.272  1035  1437 E WifiStateMachine: useWiFiOffloading() : false
08-30 12:23:41.272  1035  1437 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 12:23:41.273  1035  1437 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 12:23:41.273  1035  1437 D WifiMonitor: connecting to supplicant
,08-30 12:23:41.274  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-30 12:23:41.276  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:41.277  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-30 12:23:41.279  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:41.280  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:41.280  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:41.344  7248  7248 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 12:23:41.374  7212  7212 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-30 12:23:41.383  7212  7212 I LibraryLoader: Loading: webviewchromium
08-30 12:23:41.387  7212  7212 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 8627-8631)
08-30 12:23:41.387  7212  7212 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 12:23:41.393  7212  7212 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2aee86e0}
,08-30 12:23:41.394  7212  7212 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 12:23:41.394  7212  7212 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 12:23:41.404  7248  7248 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-30 12:23:41.404  7212  7212 I BrowserStartupController: Initializing chromium process, renderers=0
08-30 12:23:41.405  7212  7212 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 12:23:41.419  1035  1437 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-30 12:23:41.420  1035  1437 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 12:23:41.420  1035  1437 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-30 12:23:41.421  1035  1437 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-30 12:23:41.421  1035  1437 E WifiStateMachine:  SupplicantStartingState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 12:23:41.422  7248  7248 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-30 12:23:41.422  7248  7248 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 12:23:41.423  1035  1437 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 12:23:41.423  7212  7212 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-30 12:23:41.423  7212  7212 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,08-30 12:23:41.424  7212  7212 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-30 12:23:41.424  1035  1437 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:23:41.425  1035  1437 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:23:41.426  1035  7273 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-30 12:23:41.426  1035  7273 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 12:23:41.426  1035  7273 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 12:23:41.426  1035  1437 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 12:23:41.426  1035  1437 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-30 12:23:41.426  1035  7273 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-30 12:23:41.427  1035  7273 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 12:23:41.427  1035  7273 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-30 12:23:41.428  1035  1437 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 12:23:41.428  1035  1437 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-30 12:23:41.428  1035  1437 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-30 12:23:41.429  1035  1437 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 12:23:41.429  1035  1437 E WifiStateMachine: useWiFiOffloading() : false
08-30 12:23:41.429  1035  1437 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 12:23:41.429  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:41.430  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:41.430  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:41.430  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:41.430  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 12:23:41.431  1035  1437 D WifiNative-wlan0: doBoolean: SET update_config 1
08-30 12:23:41.432  1035  1437 D WifiNative-wlan0: SET update_config 1: returned true
08-30 12:23:41.432  1035  1437 D WifiConfigStore: Loading config and enabling all networks 
08-30 12:23:41.433  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:41.433  1035  1437 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 12:23:41.433  1939  1939 D WfdService: Waiting for WifiP2p enabling
08-30 12:23:41.435  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-30 12:23:41.435  1035  1466 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-30 12:23:41.436  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:41.436  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:23:41.436  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:41.436  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:41.436  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:23:41.436  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:23:41.436  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:23:41.436  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:23:41.436  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:23:41.436  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:23:41.436  1035  1437 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-30 12:23:41.437  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:23:41.440  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:41.440  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:23:41.440  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:41.440  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:41.440  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:23:41.440  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:23:41.440  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:23:41.440  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:23:41.440  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:23:41.440  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:41.440  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:23:41.440  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:41.440  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:23:41.440  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:41.440  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:41.440  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:23:41.440  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:23:41.440  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:23:41.440  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:23:41.440  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:23:41.440  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:41.441  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:23:41.443  1035  1437 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-30 12:23:41.447   322  2132 V AudioPolicyService: registerClient() client 0xb1427180, uid 10093
08-30 12:23:41.448  7212  7272 W AudioManagerAndroid: Requires BLUETOOTH permission
08-30 12:23:41.450  1035  1437 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-30 12:23:41.450  1035  1437 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 12:23:41.451  1035  1437 D WifiStateMachine: enableVerboseLogging : level 2
08-30 12:23:41.451  1035  1437 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 12:23:41.,451  1035  1437 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-30 12:23:41.451  1035  1437 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-30 12:23:41.452  1035  1437 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 12:23:41.452  1035  1437 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 12:23:41.452  1035  1437 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 12:23:41.452  1035  1437 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 12:23:41.452  1035  1437 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-30 12:23:41.452  1035  1437 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-30 12:23:41.453  1035  1437 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 12:23:41.453  1035  1437 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 12:23:41.453  1035  1437 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 12:23:41.453  1035  1437 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 12:23:41.454  1035  1437 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,08-30 12:23:41.455  1035  1437 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 12:23:41.455  1035  1437 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-30 12:23:41.455  1939  1939 D WfdsService: Supplicant Connection state is changed : true
08-30 12:23:41.455  1035  1437 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 12:23:41.455  1035  1437 D WifiNative-HAL: Setting external_sim to 1
08-30 12:23:41.455  1035  1437 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-30 12:23:41.455  1939  2319 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-30 12:23:41.455  1939  2319 D WfdsService: Set the WFDS Monitor: true
08-30 12:23:41.456  1939  2319 D WfdsMonitor: WfdsMonitorThread create
08-30 12:23:41.456  1939  2319 D WfdsMonitor: WFDS Monitor is created and started
08-30 12:23:41.456  1939  2319 D WfdsService: WiFi: Supplicant connection re-established
08-30 12:23:41.456  1035  1437 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 12:23:41.456  1035  1437 I WifiNative-HAL: startHal
08-30 12:23:41.456  1035  1437 D wifi    : setting scan oui 0xaf7181e0
08-30 12:23:41.457  1035  1437 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 12:23:41.457  1035  1437 I WifiNative-HAL: startHal
08-30 12:23:41.457  1035  1437 D wifi    : setting scan oui 0xaf7181e0
08-30 12:23:41.457  1035  1437 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 12:23:41.457  1035  1437 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 12:23:41.457  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 12:23:41.457  7248  7248 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 12:23:41.458  1035  1437 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 12:23:41.458  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 12:23:41.458  7248  7248 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 12:23:41.458  1035  1437 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 12:23:41.458  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 12:23:41.458  7248  7248 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-30 12:23:41.458  1035  1437 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 12:23:41.458  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 12:23:41.459  7248  7248 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 12:23:41.459  1035  1437 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 12:23:41.459  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 12:23:41.459  7248  7248 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 12:23:41.459  1035  1437 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 12:23:41.459  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 12:23:41.459  7248  7248 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 12:23:41.459  1035  1437 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 12:23:41.460  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 12:23:41.460  7248  7248 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 12:23:41.460  1035  1437 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 12:23:41.460  1939  7281 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 12:23:41.460  1035  1437 E WifiNative: : [338,693,356 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 12:23:41.460  1035  1437 D WifiNative-wlan0: doBoolean: RECONNECT
08-30 12:23:41.461  1939  7281 E CtrlSupplicant: Succeed to open control connection
08-30 12:23:41.461  1035  1437 D WifiNative-wlan0: RECONNECT: returned true
08-30 12:23:41.461  1035  1437 D WifiNative-wlan0: doString: [STATUS]
08-30 12:23:41.461  1939  7281 E CtrlSupplicant: Succeed to open monitor connection
08-30 12:23:41.461  1939  7281 D WfdsMonitor: Suppl,icant connection established
08-30 12:23:41.461  1035  7273 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 12:23:41.461  1035  7273 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 12:23:41.461  1035  1437 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 12:23:41.461  1035  1437 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 12:23:41.462  1939  2319 D WfdsService: Connected to the supplicant for wfds
08-30 12:23:41.462  1035  1437 D WifiNative-wlan0: SET ps 1: returned true
08-30 12:23:41.462  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:41.462  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 12:23:41.462  1035  1035 D RttService: SCAN_AVAILABLE : 3
08-30 12:23:41.463  1035  1556 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:41.463  1035  1437 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 12:23:41.463  1035  1555 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:41.463  1035  1555 I WifiNative-HAL: startHal
08-30 12:23:41.463  1035  1555 D wifi    : getting scan capabilities on interface[1] = 0xaf7181e0
08-30 12:23:41.463  1035  1555 D wifi    : failed to get capabilities : -3
08-30 12:23:41.463  1035  1555 E WifiScanningService: could not get scan capabilities
08-30 12:23:41.463  1035  1437 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 12:23:41.464  1035  1437 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
,08-30 12:23:41.464  1035  1437 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 12:23:41.464  1035  1437 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 12:23:41.464  1035  1437 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 12:23:41.465  1035  1437 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 12:23:41.465  1035  1437 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-30 12:23:41.465  7248  7248 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-30 12:23:41.466   316   893 D CommandListener: Setting iface cfg
08-30 12:23:41.466  1035  1437 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-30 12:23:41.466   316   893 D CommandListener: Trying to bring up p2p0
08-30 12:23:41.466  1035  1437 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-30 12:23:41.466  1035  1390 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 12:23:41.466  1035  1390 D LGWifiP2pService: P2pEnablingState
08-30 12:23:41.466  1035  1390 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:41.466  1035  1437 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 12:23:41.466  1035  1390 D LGWifiP2pService: P2p socket connection successful
08-30 12:23:41.466  1035  1437 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-30 12:23:41.466  1035  1390 D LGWifiP2pService: P2pEnabledState
08-30 12:23:41.466  7248  7248 E wpa_supplicant: disconnect_rssi_lvl: -100
08-30 12:23:41.467  1035  1437 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 12:23:41.467  1035  1437 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 12:23:41.468  1035  1437 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 12:23:41.468  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-30 12:23:41.468  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-30 12:23:41.468  1939  1939 D WfdsService: WifiP2pState is changed : true
08-30 12:23:41.468  1939  2319 D WfdsService: Receive the WFDS_ENABLE Method
08-30 12:23:41.468  1939  2319 D WfdsService: Set the WFDS Monitor: true
08-30 12:23:41.468  7248  7248 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 12:23:41.468  1939  2319 D WfdsService: Connected to the supplicant for wfds
08-30 12:23:41.468  1939  2319 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 12:23:41.469  7248  7248 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:23:41.469  1035  7273 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 12:23:41.469  1035  7273 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:23:41.469  1035  7273 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:23:41.469  1035  7273 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:23:41.469  7248  7248 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 12:23:41.469  7248  7248 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 12:23:41.469  7248  7248 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:23:41.469  1035  7273 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:23:41.469  1035  7273 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:23:41.470  1035  7273 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:23:41.470  1035  1437 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-30 12:23:41.470  7248  7248 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:23:41.470  1035  7273 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE ini,t=DRIVER type=WORLD
08-30 12:23:41.470  1035  7273 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:23:41.470  1035  7273 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:23:41.470  1035  1437 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 12:23:41.470  1939  2319 D WfdsService: selectPreferredScanChannel [36]
08-30 12:23:41.470  1939  2319 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 12:23:41.470  1035  1437 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 12:23:41.471  1035  7273 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:23:41.471  1035  7273 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:23:41.471  1939  7281 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:23:41.471  1035  1390 D LGWifiP2pService: sending p2p connection changed broadcast
08-30 12:23:41.471  1939  7281 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:23:41.471  1035  1437 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-30 12:23:41.471  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-30 12:23:41.471  7248  7248 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 12:23:41.471  7248  7248 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 12:23:41.471  1035  7273 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 12:23:41.471  1035  7273 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 12:23:41.471  1035  1390 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 12:23:41.471  1035  7273 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 12:23:41.472  1035  7273 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 12:23:41.472  1939  1939 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 12:23:41.473  1939  1939 D WfdsService: isConnected: false
08-30 12:23:41.473  1035  1437 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 12:23:41.473  1035  1437 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 12:23:41.473  1035  1437 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 12:23:41.475  1035  1437 D WifiNative-wlan0: doBoolean: SCAN
08-30 12:23:41.475  1035  1390 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 12:23:41.475  7212  7212 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 12:23:41.475  7212  7212 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 12:23:41.475  7212  7212 I Adreno-EGL: Build Date: 12/12/14 금
08-30 12:23:41.475  7212  7212 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 12:23:41.475  7212  7212 I Adreno-EGL: Remote Branch: 
08-30 12:23:41.475  7212  7212 I Adreno-EGL: Local Patches: 
08-30 12:23:41.475  7212  7212 I Adreno-EGL: Reconstruct Branch: 
08-30 12:23:41.475  1035  1390 D WifiNative-p2p0: doBoolean: SET device_name G3
08-30 12:23:41.476  1035  1437 D WifiNative-wlan0: SCAN: returned false
08-30 12:23:41.476  1035  1390 D WifiNative-p2p0: SET device_name G3: returned true
08-30 12:23:41.476  1035  1390 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 12:23:41.476  1035  1390 D LGWifiP2pService: before postfix = G3
08-30 12:23:41.476  1035  1390 D WifiServerServiceExt: postfix byte check : 2
08-30 12:23:41.476  1035  1390 D LGWifiP2pService: after postfix = G3
08-30 12:23:41.476  1035  1390 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 12:23:41.476  1035  1437 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=338709  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANN,ING
08-30 12:23:41.477  1035  1390 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 12:23:41.477  1035  1390 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 12:23:41.478  1035  1390 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 12:23:41.478  1035  1390 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-30 12:23:41.478  1035  1390 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 12:23:41.478  1035  1390 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 12:23:41.478  1035  1390 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 12:23:41.478  1035  1390 D WifiNative-HAL: p2pGetDeviceAddress
08-30 12:23:41.479  1035  1390 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-30 12:23:41.480  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:23:41.480  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:23:41.481  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:41.481  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:41.481  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:41.482  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 12:23:41.483  1035  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=338716  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 12:23:41.483  1035  1390 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-30 12:23:41.483  1035  1437 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 12:23:41.483  1035  1390 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-30 12:23:41.484  1035  1437 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 12:23:41.484  1035  1390 D WifiNative-p2p0: P2P_FLUSH: returned true
08-30 12:23:41.484  1035  1390 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 12:23:41.484  1035  1437 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 12:23:41.485  1939  1939 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 12:23:41.485  1035  1437 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 12:23:41.485  1939  1939 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 12:23:41.485  1939  1939 D WfdsService: Update P2p Interface State: 3
08-30 12:23:41.485  1035  1390 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-30 12:23:41.485  1035  1390 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 12:23:41.485  1035  1437 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 12:23:41.485  1035  1390 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 12:23:41.485  1035  1390 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-30 12:23:41.486  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:23:41.486  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
08-30 12:23:41.501  1035  1390 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-30 12:23:41.501  1035  1390 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-30 12:23:41.502  1035  1390 D LGWifiP2pService: InactiveState
08-30 12:23:41.502  1035  1390 D LGWifiP2pService: InactiveState{ when=-32ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:41.502  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-32ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:41.502  1035  1390 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-30 12:23:41.502  7248  7248 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 12:23:41.503  7248  7248 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-30 12:23:41.503  7248  7248 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 12:23:41.503  7248  7248 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:23:41.504  7248  7248 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:23:41.505  1939  7281 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 12:23:41.505  1939  7281 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:23:41.505  1939  7281 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:23:41.505  1035  7273 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 12:23:41.505  1035  7273 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:23:41.506  1035  1390 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 12:23:41.506  1035  1390 D LGWifiP2pService: InactiveState{ when=-21ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:41.506  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-21ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:41.506  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:41.506  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:41.506  1035  1390 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:41.506  1035  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:41.506  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:41.506  1035  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:41.507  1035  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:41.507  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:41.507  1035  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:41.507  1939  2319 W WfdsService: DefaultState - msg [9441285] is not handled
08-30 12:23:41.507  1035  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:41.507  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:41.507  1035  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:41.507  1035  1035 E WifiServerServiceExt: No p2p device connected
08-30 12:23:41.508  1035  7273 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:23:41.508  1035  7273 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:23:41.508  1035  7273 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:23:41.508  1035  7273 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:23:41.508  1035  7273 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:23:41.508  1035  7273 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:23:41.508  1035  7273 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:23:41.508  1035  7273 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:23:41.508  1035  7273 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:23:41.508  1035  7273 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:23:41.523  7212  7212 I NSApplication: Starting up...
,08-30 12:23:41.599  1035  1784 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7287 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-30 12:23:41.600  1035  2045 I ActivityManager: Killing 6061:com.android.vending/u0a44 (adj 15): empty #17
08-30 12:23:41.623   356   356 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 484us total 21.876ms
,08-30 12:23:41.646   356   356 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 419us total 21.110ms
,08-30 12:23:41.666   356   356 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 369us total 20.009ms
,08-30 12:23:41.694  1035  1957 W libprocessgroup: failed to open /acct/uid_10044/pid_6061/cgroup.procs: No such file or directory
,08-30 12:23:41.722  7287  7287 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 12:23:41.988  6420  6420 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-30 12:23:41.993  6420  6879 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 12:23:42.016  2205  2205 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:23:42.026  7038  7038 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-30 12:23:42.027  7038  7038 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:42.027  7038  7038 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 12:23:42.027  7038  7038 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 12:23:42.028  7038  7038 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 12:23:42.035  7038  7038 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@175ac657
08-30 12:23:42.035  7038  7038 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 12:23:42.035  7038  7038 D AppUp4:CustFacade: isPhone : true
08-30 12:23:42.035  7038  7038 D AppUp4:CustModeStarterReceiver: begin check event
08-30 12:23:42.035  7038  7038 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 12:23:42.039  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:42.039  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 12:23:42.041  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:23:42.043  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 12:23:42.051  7077  7077 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 12:23:42.052  4306  7316 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 12:23:42.059  7248  7248 E wpa_supplicant: USIM:  scard_init function
08-30 12:23:42.060  7248  7248 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-30 12:23:42.064  1035  7273 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-30 12:23:42.064  1035  7273 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 12:23:42.064  1035  7273 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-30 12:23:42.064  1035  7273 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-30 12:23:42.064  1035  7273 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-30 12:23:42.064  1035  7273 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-30 12:23:42.064  1035  7273 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-30 12:23:42.064  1035  1437 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-30 12:23:42.065  1035  1437 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-30 12:23:42.065  4306  7318 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:42.066  4306  7318 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 12:23:42.066  1035  1437 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-30 12:23:42.066  1035  1437 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-30 12:23:42.066  1035  1437 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-30 12:23:42.172  7248  7248 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 12:23:42.172  1035  7273 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-30 12:23:42.172  1035  7273 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-30 12:23:42.173  1035  7273 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-30 12:23:42.173  1035  7273 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-30 12:23:42.173  1035  7273 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 12:23:42.173  1035  7273 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 12:23:42.187  1035  1957 I art     : Explicit concurrent mark sweep GC freed 62184(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 4.215ms total 131.503ms
,08-30 12:23:42.197  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 12:23:42.204  1035  1437 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=339437  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-30 12:23:42.214  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:42.214  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:42.214  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 12:23:42.215  7248  7248 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 12:23:42.215  1035  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=339448  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 12:23:42.215  7248  7248 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 12:23:42.216  1035  1437 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=339448  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 12:23:42.216  1035  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=339449  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 12:23:42.217  1035  7273 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 12:23:42.217  1035  7273 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 12:23:42.217  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:23:42.217  1035  1437 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=339450
08-30 12:23:42.217  1035  7273 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 12:23:42.217  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:23:42.217  1035  7273 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 12:23:42.217  1035  7273 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 12:23:42.217  1035  7273 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 12:23:42.217  1035  7273 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 12:23:42.217  1035  7273 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 12:23:42.218  1035  7273 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 12:23:42.218  1035  7273 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 12:23:42.219  1035  1437 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=339451
08-30 12:23:42.219  1035  1437 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=339452
08-30 12:23:42.219  1035  1437 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=339452
08-30 12:23:42.219  1035  1437 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=339452
08-30 12:23:42.220  1035  1437 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=339453  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-30 12:23:42.221  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:42.224  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:42.224  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:42.224  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 12:23:42.228  7077  7325 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:42.232  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:42.232  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:42.232  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 12:23:42.233  1035  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=339465  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 12:23:42.233  1035  1437 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:23:42.234  1035  1437 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:23:42.234  1035  1437 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:23:42.234  1035  1437 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:23:42.235  1035  1437 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-30 12:23:42.235  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:42.235  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:42.235  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 12:23:42.241  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:23:42.241  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:23:42.242  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:42.244  1035  1437 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=339477  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 12:23:42.245  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:23:42.245  1035  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=339478  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 12:23:42.245  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:23:42.245  1035  1437 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=339478
08-30 12:23:42.246  1035  1437 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=339479
08-30 12:23:42.246  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:23:42.246  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-30 12:23:42.246  1035  1437 D WifiNative-wlan0: doString: [STATUS]
08-30 12:23:42.247  1035  7273 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 12:23:42.247  1035  7273 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 12:23:42.247  1035  1437 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 12:23:42.247  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 12:23:42.248  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:23:42.248  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:23:42.250  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:42.251  1035  1437 I WifiServiceExtension: setVHTCapabilityType  : false
08-30 12:23:42.252  6967  7329 W FormManager: Network not available. Please check & try again.
08-30 12:23:42.253  6967  7330 V FormManager: Network unavailable.
08-30 12:23:42.253  3415  3415 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 12:23:42.253  3415  3415 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:42.253  3415  3415 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 12:23:42.256  7109  7109 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 12:23:42.256  7109  7109 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 12:23:42.267  1035  1437 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 12:23:42.267  1035  1437 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-30 12:23:42.268  6967  7330 V FormManager: Network unavailable.
08-30 12:23:42.273  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:42.273  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:42.273  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 12:23:42.275  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:42.275  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:42.275  1035  1437 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-30 12:23:42.275  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 12:23:42.275  1035  1495 D ConnectivityService: Got NetworkAgent Messenger
08-30 12:23:42.275  1035  1495 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 12:23:42.276  1035  1495 D ConnectivityService: NetworkAgent connected
08-30 12:23:42.276  1035  1437 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 12:23:42.276  1035  1437 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 12:23:42.276  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:23:42.276  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:23:42.277  1035  1437 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 12:23:42.277  1035  1437 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 12:23:42.278  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:42.280  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:23:42.280  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 12:23:42.282  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:42.282  1035  1437 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 12:23:42.282  1035  1437 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 12:23:42.282  1035  1437 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 12:23:42.282  1035  1437 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 12:23:42.282  1035  1437 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 12:23:42.284  7191  7191 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:23:42
08-30 12:23:42.286  7191  7191 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 12:23:42.286  7191  7191 D Weather.Utils: 2 : All the weather widget is gone.
08-30 12:23:42.286  1035  1437 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 12:23:42.287   316   893 D CommandListener: Setting iface cfg
08-30 12:23:42.288  7191  7191 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 12:23:42.288  7191  7191 D WeatherAncestor: connectivity changed - connection : true
08-30 12:23:42.288  7191  7191 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3475c62d
08-30 12:23:42.289  7191  7191 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 12:23:42.289  7191  7191 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 12:23:42.289  7191  7191 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 12:23:42.289  7191  7191 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 12:23:42.289  7191  7191 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:23:42
08-30 12:23:42.289  1035  1437 E WifiStateMachine: Start Dhcp Watchdog 2
08-30 12:23:42.289  1035  7333 D DhcpStateMachine: StoppedState
08-30 12:23:42.290  1035  7333 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:42.290  1035  7333 D DhcpStateMachine: WaitBeforeStartState
08-30 12:23:42.290  1035  1437 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=339523  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 12:23:42.290  1035  1437 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=339523  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 12:23:42.291  1035  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=339524  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 12:23:42.295  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:23:42.295  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,08-30 12:23:42.296  1035  1437 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=339529  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 12:23:42.297  1035  1437 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=339529  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 12:23:42.297  1035  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=339530  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 12:23:42.298  1035  1437 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:293232] from screen [on:0 period:-621160230] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 12:23:42.299  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-621160229] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 12:23:42.299  1035  1437 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 12:23:42.303  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:42.305  1035  1495 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-30 12:23:42.305  1035  1437 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:23:42.306  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:23:42.306  1035  1437 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:23:42.307  1035  1437 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:23:42.307  1035  1437 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:23:42.308  1035  1437 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:23:42.308  1035  1495 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 12:23:42.309  1035  1437 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=102,0,0
,08-30 12:23:42.309  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=102,0,0
08-30 12:23:42.310  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-30 12:23:42.311  7248  7248 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-30 12:23:42.311  1035  1437 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-30 12:23:42.311  1035  1437 D WifiNative-wlan0: doBoolean: SET ps 0
08-30 12:23:42.312  1035  1437 D WifiNative-wlan0: SET ps 0: returned true
08-30 12:23:42.312  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 12:23:42.312  7248  7248 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-30 12:23:42.312  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 12:23:42.312  6850  6850 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 12:23:42.312  6850  6850 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 12:23:42.312  6850  6850 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 12:23:42.312  1035  1437 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-30 12:23:42.313  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 12:23:42.313  1035  1437 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 12:23:42.313  1035  1437 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 12:23:42.313  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2dbdfc1b target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:42.313  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2dbdfc1b target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:42.313  1035  1437 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 12:23:42.313  1035  7333 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:42.313  1035  7333 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 12:23:42.314   316   893 D CommandListener: Setting iface cfg
08-30 12:23:42.315   316   893 D CommandListener: Trying to bring up wlan0
08-30 12:23:42.315  6850  6850 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 12:23:42.315  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-30 12:23:42.315  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 12:23:42.315  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 12:23:42.315  6850  6850 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 12:23:42.316  1035  1437 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-30 12:23:42.316  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-30 12:23:42.316  6850  6850 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 12:23:42.316  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:23:42.316  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 12:23:42.320  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:23:42.320  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 12:23:42.321  1035  1437 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:23:42.321  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:23:42.321  1035  1437 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:23:42.322  1035  1437 E Wif,iStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-30 12:23:42.322  1035  1437 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:23:42.322  1035  1437 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:23:42.323  1035  1437 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 12:23:42.323  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 12:23:42.323  1035  1390 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:42.323  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:42.323  1035  1495 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 12:23:42.324  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 12:23:42.324  7248  7248 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 12:23:42.324  1035  1437 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
,08-30 12:23:42.324  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 12:23:42.324  7248  7248 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-30 12:23:42.324  1035  1437 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 12:23:42.324  1035  1437 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 12:23:42.324  6881  6881 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 12:23:42.328  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 12:23:42.332  6967  7335 W FormManager: Network not available. Please check & try again.
,08-30 12:23:42.336  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:23:42.340  1035  1437 D WifiNative-wlan0: SET ps 1: returned true
08-30 12:23:42.341  1035  1495 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 12:23:42.341  1035  1437 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 12:23:42.342  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 12:23:42.342  1035  1437 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 12:23:42.342  6967  7336 V FormManager: Network unavailable.
08-30 12:23:42.342  1035  1495 D ConnectivityService: ignoring duplicate network state non-change
08-30 12:23:42.345  6967  7336 V FormManager: Network unavailable.
,08-30 12:23:42.349  1035  1495 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 12:23:42.349  1035  1495 D ConnectivityService: Adding iface wlan0 to network 101
08-30 12:23:42.350  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:23:42.350  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:23:42.351  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:42.354  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:42.354  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:42.354  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 12:23:42.359  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 12:23:42.359  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:42.359  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 12:23:42.362  1939  1939 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-30 12:23:42.365  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 12:23:42.365  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:42.365  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:42.365  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 12:23:42.365  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 12:23:42.366  1035  1437 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 12:23:42.367  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:42.367  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:42.368  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 12:23:42.373  1035  1495 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 12:23:42.373  1035  1495 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-30 12:23:42.374  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:23:42.374  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:23:42.375  1035  1495 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-30 12:23:42.375  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:42.375   316   893 E Netd    : netlink response contains error (File exists)
08-30 12:23:42.376  6881  6881 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 12:23:42.376  1035  1495 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-30 12:23:42.377  1035  1495 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 12:23:42.377  1035  1495 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-30 12:23:42.377  1035  1495 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-30 12:23:42.377  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:23:42.377  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 12:23:42.377  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:42.378  1035  1495 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 12:23:42.378  1035  1495 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-30 12:23:42.378  1035  1495 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-30 12:23:42.380  1035  1495 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-30 12:23:42.380  1035  7332 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:42.381  1035  7332 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
,08-30 12:23:42.381  1035  7332 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:42.381  1035  7332 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 12:23:42.382  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 12:23:42.382  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:23:42.382  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 12:23:42.383  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:42.383  1035  1495 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 12:23:42.383  1035  1495 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:23:42.383   316  7341 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-30 12:23:42.383  1035  1495 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 12:23:42.383  1035  1495 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:23:42.384  1035  1495 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 12:23:42.384  1035  1495 D ConnectivityService: currentScore = 0, newScore = 20
08-30 12:23:42.384  1035  1495 D ConnectivityService:    accepting network in place of null
08-30 12:23:42.384  1035  1495 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:23:42.385  1850  1850 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:23:42.385  1035  1437 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:23:42.385  1035  1437 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 12:23:42.385  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 12:23:42.386  1035  1495 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 12:23:42.386  1035  1495 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 12:23:42.386  1035  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CON,NECTIVITY_CHANGE_IMMEDIATE
08-30 12:23:42.387  1035  1495 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:42.387  1035  1495 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 12:23:42.387  1035  1495 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-30 12:23:42.388  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-30 12:23:42.388  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 12:23:42.388  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 12:23:42.388  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 12:23:42.388  1035  1495 D ConnectivityService: validation of new default Network = false
08-30 12:23:42.388  1035  1495 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 12:23:42.388  1035  1495 D DSQN    : enableDataServiceNotify 
08-30 12:23:42.388  1035  1495 D DSQN    : start dsqn bin
,08-30 12:23:42.390  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:23:42.394  1035  1495 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-30 12:23:42.394  1035  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:23:42.394  1035  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:23:42.376  7344  7344 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:23:42.395  1035  1495 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:23:42.396  1601  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 12:23:42.376  7344  7344 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 12:23:42.406  7344  7344 E DSQN    : DSQN ssw
,08-30 12:23:42.413  1035  1389 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-30 12:23:42.425  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 12:23:42.426  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 12:23:42.427  1815  7348 I CheckinService: active receiver: enabled
08-30 12:23:42.427  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 12:23:42.434  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:23:42.434   316  7350 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 12:23:42.435   316  7350 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
08-30 12:23:42.435  1815  7348 I CheckinService: Preparing to send checkin request
08-30 12:23:42.435  1815  7348 I EventLogService: Accumulating logs since 1472552341239
08-30 12:23:42.441  6656  7022 D UEI.SmartControl: Internal timer expired: 2
08-30 12:23:42.441  6656  7022 D UEI.SmartControl: unbind internal service
08-30 12:23:42.445  4306  7352 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 12:23:42.447  4306  7353 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 12:23:42.447  4306  7353 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 12:23:42.448  4306  7352 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-30 12:23:42.452   316  7341 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-30 12:23:42.455  1035  1956 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7354 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-30 12:23:42.460  4306  7352 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-30 12:23:42.460  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-30 12:23:42.460  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:42.461  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:42.463  4306  4306 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-30 12:23:42.464  4306  4306 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-30 12:23:42.464  4306  4306 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-30 12:23:42.465  4306  4306 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-30 12:23:42.467  4306  4306 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-30 12:23:42.472  1815  7348 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-30 12:23:42.477   316  7350 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-30 12:23:42.489   316  7341 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-30 12:23:42.491   316   892 D LGDataListener: argv[0]=dsqncommand
08-30 12:23:42.491   316   892 D LGDataListener: argv[1]=wlan0
,08-30 12:23:42.491   316   892 D LGDataListener: argv[2]=1
08-30 12:23:42.491   316   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-30 12:23:42.491  1035  1115 D DSQN    : DSQM DsqnNotification wlan0  1
08-30 12:23:42.491  1035  1115 D DSQN    : start to monitor internet connection
08-30 12:23:42.515  1035  7333 D DhcpStateMachine: DHCPV4 request on wlan0
08-30 12:23:42.515  1035  7333 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-30 12:23:42.515  1035  7333 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-30 12:23:42.506  7373  7373 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:23:42.506  7373  7373 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:23:42.520  6967  7343 V FormManager: There are no updated forms. The schedule will be deleted.
08-30 12:23:42.524  7373  7373 I dhcpcd  : version 5.5.6 starting
08-30 12:23:42.525  7373  7373 E dhcpcd  : get_duid: m
08-30 12:23:42.525  7373  7373 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 12:23:42.525  7373  7373 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-30 12:23:42.526  6967  7343 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-30 12:23:42.537  1035  1725 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7376 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-30 12:23:42.540  1035  7332 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 10:23:42 GMT], X-Android-Received-Millis=[1472552622539], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472552622514]}
08-30 12:23:42.540  1035  7332 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 12:23:42.540  1035  7332 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,08-30 12:23:42.542  1035  1495 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-30 12:23:42.542  1035  1495 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-30 12:23:42.542  1035  1495 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 12:23:42.542  1035  1495 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:23:42.542  1035  1495 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 12:23:42.542  1035  1495 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-30 12:23:42.542  1035  1495 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-30 12:23:42.542  1035  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:23:42.542  1035  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:23:42.542  1035  1495 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:23:42.543  1035  1495 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:23:42.543  1601  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-30 12:23:42.543  1035  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-30 12:23:42.544  1035  1437 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:23:42.544  1850  1850 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:23:42.544  1035  1437 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 12:23:42.544  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 12:23:42.546  7354  7354 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 12:23:42.547  7354  7354 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-30 12:23:42.548  6656  7016 D serial_port: close(fd = 24)
08-30 12:23:42.558  6656  7016 I UEI.SmartControl: Serial port is closed.
,08-30 12:23:42.560  7354  7354 V [BNRBootReceiver]: Boot Receiver Return
08-30 12:23:42.562  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 12:23:42.563  7354  7354 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 12:23:42.563  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:42.563  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:42.564  6420  6420 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:23:42.565  7373  7373 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 12:23:42.565  7373  7373 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 12:23:42.565  7373  7373 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 12:23:42.565  7373  7373 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 12:23:42.565  7373  7373 D dhcpcd  : wlan0: sending REQUEST (xid 0x43492f3f), next in 4.29 seconds
08-30 12:23:42.568  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 12:23:42.571  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 12:23:42.580  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:23:42.580  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:23:42.581  6909  6909 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 12:23:42.583  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-30 12:23:42.584  6850  6850 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-30 12:23:42.586  7376  7376 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 12:23:42.587  7376  7376 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 12:23:42.587  6420  6420 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:23:42.591  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 12:23:42.594  7373  7373 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-30 12:23:42.594  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 12:23:42.598  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:23:42.599  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:23:42.599  6909  6909 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 12:23:42.602  6420  6420 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:23:42.605  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:23:42.608  7373  7373 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-30 12:23:42.608  7373  7373 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-30 12:23:42.608  7373  7373 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-30 12:23:42.608  7373  7373 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-30 12:23:42.608  7373  7373 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 12:23:42.608  7373  7373 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 12:23:42.608  7373  7373 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 12:23:42.608  7373  7373 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-30 12:23:42.609  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:23:42.614  7376  7376 I MultiDex: VM with version 2.1.0 has multidex support
08-30 12:23:42.614  7376  7376 I MultiDex: install
08-30 12:23:42.614  7376  7376 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-30 12:23:42.618  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:23:42.618  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:23:42.618  6909  6909 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 12:23:42.621  6420  6420 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:23:42.628  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:23:42.632  7376  7376 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-30 12:23:42.633  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:23:42.637  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:23:42.637  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:23:42.637  6909  6909 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 12:23:42.640  6420  6420 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 12:23:42.646  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:23:42.654  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:23:42.661  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:23:42.662  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:23:42.662  6909  6909 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 12:23:42.665  6420  6420 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 12:23:42.672  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:23:42.679  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:23:42.684  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:23:42.685  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:23:42.685  6909  6909 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 12:23:42.688  6420  6420 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 12:23:42.694  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 12:23:42.698  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:23:42.703  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:23:42.703  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:23:42.704  6909  6909 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 12:23:42.708  6420  6420 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:23:42.716  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:23:42.720  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:23:42.725  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:23:42.725  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:23:42.728  6909  6909 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 12:23:42.730  6420  6420 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 12:23:42.738  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:23:42.742  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:23:42.748  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:23:42.748  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:23:42.749  6909  6909 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 12:23:42.752  6420  6420 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 12:23:42.755  6881  6881 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 12:23:42.760  6881  6881 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 12:23:42.763  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 12:23:42.767  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:23:42.772  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:23:42.773  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:23:42.773  6909  6909 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 12:23:42.774  6909  6909 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 12:23:42.774  6909  6909 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-30 12:23:42.778  6420  6420 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:23:42.781  6881  6881 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 12:23:42.781  6881  6881 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 12:23:42.785  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:23:42.791  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:23:42.799  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:23:42.799  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:23:42.799  6909  6909 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 12:23:42.800  6909  6909 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-30 12:23:42.800  6909  6909 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-30 12:23:42.802  1035  1784 I ActivityManager: Killing 6831:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-30 12:23:42.848  1035  1725 W libprocessgroup: failed to open /acct/uid_10037/pid_6831/cgroup.procs: No such file or directory
,08-30 12:23:42.854  2205  2205 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-30 12:23:42.867  7376  7395 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:23:42.867  7376  7395 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:23:42.876  2205  2205 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-30 12:23:42.876  2205  2205 D c       : Getting all permits...
,08-30 12:23:42.876  2205  2205 D a       : Opening database...
08-30 12:23:42.885  2205  2205 D a       : Opening database auth.proximity.permit_store...
08-30 12:23:42.887  2205  2205 D a       : Closing database...
,08-30 12:23:42.919  1035  7333 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-30 12:23:42.922  1035  7333 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-30 12:23:42.923  1035  7333 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 12:23:42.923  1035  7333 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-30 12:23:42.923  1035  7333 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-30 12:23:42.923  1035  7333 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 12:23:42.923  1035  7333 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-30 12:23:42.923  1035  7333 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-30 12:23:42.924  1035  7333 D DhcpStateMachine: RunningState
,08-30 12:23:43.048  7421  7421 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-30 12:23:43.142  7421  7421 I dex2oat : dex2oat took 94.103ms (threads: 4),
,08-30 12:23:43.172  7376  7395 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 12:23:43.172  7376  7395 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 12:23:43.172  7376  7395 I Adreno-EGL: Build Date: 12/12/14 금
08-30 12:23:43.172  7376  7395 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 12:23:43.172  7376  7395 I Adreno-EGL: Remote Branch: 
08-30 12:23:43.172  7376  7395 I Adreno-EGL: Local Patches: 
08-30 12:23:43.172  7376  7395 I Adreno-EGL: Reconstruct Branch: 
,08-30 12:23:43.322  7376  7395 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 12:23:43.322  7376  7395 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 12:23:43.322  7376  7395 I Adreno-EGL: Build Date: 12/12/14 금
08-30 12:23:43.322  7376  7395 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 12:23:43.322  7376  7395 I Adreno-EGL: Remote Branch: 
08-30 12:23:43.322  7376  7395 I Adreno-EGL: Local Patches: 
08-30 12:23:43.322  7376  7395 I Adreno-EGL: Reconstruct Branch: 
,08-30 12:23:43.398  1035  1495 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-30 12:23:43.493  7376  7395 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 12:23:43.493  7376  7395 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 12:23:43.493  7376  7395 I Adreno-EGL: Build Date: 12/12/14 금
08-30 12:23:43.493  7376  7395 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 12:23:43.493  7376  7395 I Adreno-EGL: Remote Branch: 
08-30 12:23:43.493  7376  7395 I Adreno-EGL: Local Patches: 
08-30 12:23:43.493  7376  7395 I Adreno-EGL: Reconstruct Branch: 
,08-30 12:23:43.688   316  7436 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-30 12:23:43.690   316  7436 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-30 12:23:43.737   316  7436 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-30 12:23:43.924  1815  7348 I CheckinTask: Sending checkin request (7861 bytes)
,08-30 12:23:44.012  1035  1437 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 12:23:44.014  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 12:23:44.015  1035  1437 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-30 12:23:44.025  1035  1437 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 12:23:44.031  1035  1437 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 12:23:44.033  1035  1437 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 12:23:44.038  1035  1495 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-30 12:23:44.038  1035  1495 D ConnectivityService: identical MTU - not setting
08-30 12:23:44.038  1035  1495 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 12:23:44.038  1035  1495 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-30 12:23:44.039  1035  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:23:44.039  1035  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:23:44.039  1035  1495 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-30 12:23:44.042  1601  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-30 12:23:44.145  1815  7348 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-30 12:23:44.162  1815  7348 I CheckinService: active receiver: disabled
,08-30 12:23:44.192  2205  2205 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-30 12:23:44.223  2205  2205 I GCM     : GCM config loaded
,08-30 12:23:44.231   316  7447 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 12:23:44.231   316  7447 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-30 12:23:44.242  7109  7109 V SetupWizard: Connected to Gservices successfully
,08-30 12:23:44.264   316  7447 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-30 12:23:44.564  2205  7459 D GCM     : Connected
,08-30 12:23:44.603  2205  7459 D GCM     : Message class com.google.e.a.a.q
,08-30 12:23:45.307  1035  1437 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=51.0, 0.0, 0.0  rx=48.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-621157221] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 12:23:45.308  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=51.0, 0.0, 0.0  rx=48.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-621157220] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 12:23:45.308  1035  1437 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 12:23:45.327  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 12:23:45.338  1035  1975 D WifiServiceImplEx: setWifiEnabled: false pid=6741, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 12:23:45.338  1035  1975 D WifiService: setWifiEnabled: false pid=6741, uid=10118
08-30 12:23:45.338  1035  1975 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 12:23:45.360  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 12:23:45.361  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 12:23:45.361  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-30 12:23:45.362  1035  1437 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 12:23:45.363  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 12:23:45.363  1035  1437 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 12:23:45.363  1035  1437 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 12:23:45.364  1035  1437 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 12:23:45.364  1035  1437 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 12:23:45.364  1035  1437 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 12:23:45.364  1035  1437 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 12:23:45.365  1035  1437 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 12:23:45.365  1035  1437 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 12:23:45.366  1035  1449 V WifiInternetCheck: Single check msg out of sync, ignoring.
08-30 12:23:45.373  1035  1437 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-30 12:23:45.378  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 12:23:45.378  7248  7248 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 12:23:45.379  1035  1390 D LGWifiP2pService: InactiveState{ when=-6ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:45.379  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:45.379  1035  1437 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 12:23:45.379  1035  1437 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 12:23:45.380  1035  1437 D WifiNative-wlan0: SET ps 1: returned true
08-30 12:23:45.380  1035  7333 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:45.386   316   893 D CommandListener: Clearing all IP addresses on wlan0
08-30 12:23:45.396  1035  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:23:45.403  1035  1117 D Tethering: MasterInitialState.processMessage what=3
08-30 12:23:45.422  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:45.422  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:23:45.422  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:45.422  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:45.422  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:23:45.422  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:23:45.422  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:23:45.422  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:23:45.422  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:23:45.422  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:45.422  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:23:45.432  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:45.432  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:23:45.432  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:45.432  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:45.432  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:23:45.432  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:23:45.432  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:23:45.432  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:23:45.432  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:23:45.432  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:45.432  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:23:45.444  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:45.444  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:23:45.444  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:45.444  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:45.444  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:23:45.444  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:23:45.444  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:23:45.444  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:23:45.444  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:23:45.444  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:45.444  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:23:45.467  1035  1495 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 12:23:45.467  1035  1495 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-30 12:23:45.478  1035  1035 D WifiHS20: hidePasspointNotification off =false
,08-30 12:23:45.493  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:45.500  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:23:45.506  6420  6420 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 12:23:45.509  6420  6879 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-30 12:23:45.515  1939  1939 V WfdStateTracker: handleWifiStateChangedEvent: 0
,08-30 12:23:45.516  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:23:45.516  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:23:45.516  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:45.517  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:45.517  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 12:23:45.518  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:45.518  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:45.518  1035  1390 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@202396cd
08-30 12:23:45.518  1035  1437 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:23:45.518  1035  1390 D LGWifiP2pService: P2pDisablingState
08-30 12:23:45.518  1035  1390 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:45.518  1035  1390 D LGWifiP2pService: p2p socket connection lost
08-30 12:23:45.518  1035  1437 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:23:45.519  1035  1390 D LGWifiP2pService: P2pDisabledState
08-30 12:23:45.519  1035  1437 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:23:45.519  1035  1437 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,08-30 12:23:45.520  1035  1437 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:23:45.520  1035  1437 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:23:45.521  1035  1437 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 12:23:45.521  1035  1437 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 12:23:45.521  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 12:23:45.521  7248  7248 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 12:23:45.523  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 12:23:45.523  1939  1939 D WfdsService: WifiP2pState is changed : false
08-30 12:23:45.524  1939  2319 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 12:23:45.524  1939  2319 D WfdsService: Set the WFDS Monitor: false
08-30 12:23:45.525  1939  2319 D WfdsMonitor: WFDS Monitor is stopped
08-30 12:23:45.525  1939  2319 D WfdsService: STATE : WfdsDisabledState - enter
08-30 12:23:45.525  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-30 12:23:45.525  1939  7281 D CtrlSupplicant: Received on exit socket, terminate
08-30 12:23:45.525  1939  7281 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 12:23:45.525  1939  7281 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 12:23:45.525  1939  7281 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 12:23:45.525  1939  2321 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 12:23:45.526  1939  2319 W WfdsService: DefaultState - msg [9445378] is not handled
,08-30 12:23:45.526  1035  1437 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 12:23:45.526  1035  1437 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 12:23:45.527  1035  1437 D WifiNative-wlan0: SET ps 1: returned true
08-30 12:23:45.529  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:45.529  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:45.530  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 12:23:45.530  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:45.530  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
,08-30 12:23:45.530  1035  1035 D RttService: SCAN_AVAILABLE : 1
08-30 12:23:45.531  1035  1555 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:45.533  1035  1556 D RttService: EnabledState got{ when=-3ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:45.533  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=-12ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:45.533  1035  1390 D LGWifiP2pService: DefaultState{ when=-12ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:45.541  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:23:45.541  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:23:45.543  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:45.544  5736  5736 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 12:23:45.550  1035  1975 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
08-30 12:23:45.551  1035  7332 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:45.551  1035  7332 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:45.551  1035  7332 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-30 12:23:45.551  1035  7332 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:45.551  1035  7332 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-30 12:23:45.555   316   893 D CommandListener: Clearing all IP addresses on wlan0
08-30 12:23:45.556   316  7485 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 12:23:45.557  1035  7332 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,08-30 12:23:45.558  1035  1115 D DSQN    : Dns fail occured do internet check.
08-30 12:23:45.558  1035  1035 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-30 12:23:45.558  1035  1035 D DSQN    : try Internet connection check
08-30 12:23:45.561  1035  1437 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 12:23:45.561  1035  1495 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 12:23:45.561  1035  1495 D DSQN    : disableDataServiceNotify
08-30 12:23:45.561  1035  1495 D DSQN    : stop dsqn bin
08-30 12:23:45.561  1035  1437 D WifiNative-p2p0: TERMINATE: returned true
08-30 12:23:45.561  1035  1437 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 12:23:45.561  1035  1437 E WifiStateMachine: useWiFiOffloading() : false
08-30 12:23:45.561  1035  1437 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 12:23:45.563  1035  1035 D WifiHS20: hidePasspointNotification off =false
,08-30 12:23:45.563  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:45.563  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:45.564  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 12:23:45.564  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 12:23:45.564  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:23:45.565  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:45.568  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
,08-30 12:23:45.572  1035  1495 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-30 12:23:45.572  1035  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:23:45.572  1035  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:23:45.572  1035  1495 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:23:45.572  1035  1495 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-30 12:23:45.573  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 12:23:45.573  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:23:45.573  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 12:23:45.573  1035  1495 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-30 12:23:45.573  1035  1495 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 12:23:45.573  1035  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 12:23:45.573  1035  1495 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:45.574  1035  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 12:23:45.574  1035  7332 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:45.574  1035  7332 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:45.574  1035  7332 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 12:23:45.574  1601  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 12:23:45.575  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:45.575  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:23:45.575  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:45.575  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:45.575  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:23:45.575  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:23:45.575  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:23:45.575  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:23:45.575  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:23:45.575  6741  6741 W org.thaliproject.p2p.btconnectorlib.interna,l.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:45.575  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:23:45.576  1035  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 12:23:45.577  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 12:23:45.577  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 12:23:45.577  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 12:23:45.577  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 12:23:45.577   316  7488 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 12:23:45.578  1035  7487 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
08-30 12:23:45.578  1035  7486 D DSQN    : ThreadInternetCheck internet check NOK 
08-30 12:23:45.579  1035  7486 D DSQN    : InternetcheckProgress is not set don't send DS quality intent
08-30 12:23:45.579  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 12:23:45.580  1035  1495 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:45.580  1035  1495 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:23:45.580  1035  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 12:23:45.580  1035  1495 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:23:45.580  1035  1495 D NetworkManagementService: Removing idletimer
08-30 12:23:45.580  1035  1495 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:45.580  1035  1437 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:23:45.580  1035  1437 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 12:23:45.581  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 12:23:45.581  1035  1495 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 12:23:45.581  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 12:23:45.581  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 12:23:45.581  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 12:23:45.581  1850  1850 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:23:45.581  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 12:23:45.584  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:45.584  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:23:45.584  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:45.584  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:45.584  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:23:45.584  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:23:45.584  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:23:45.584  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:23:45.584  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:23:45.584  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:45.584  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:23:45.584  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:45.584  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:23:45.584  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:45.584  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:45.584  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:23:45.584  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:23:45.584  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:23:45.584  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:23:45.584  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:23:45.585  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:45.585  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:23:45.586  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:45.589  2205  2205 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:23:45.609  7038  7038 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 12:23:45.609  7038  7038 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:45.609  7038  7038 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 12:23:45.609  7038  7038 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 12:23:45.617  7038  7038 I AppUp4:CustModeStarterReceiver: onReceive
08-30 12:23:45.620  7038  7038 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@175ac657
08-30 12:23:45.620  7038  7038 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 12:23:45.620  7038  7038 D AppUp4:CustFacade: isPhone : true
08-30 12:23:45.620  7038  7038 D AppUp4:CustModeStarterReceiver: begin check event
08-30 12:23:45.620  7038  7038 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 12:23:45.624  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:45.624  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 12:23:45.625  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:23:45.627  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:23:45.631  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 12:23:45.631  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:45.631  7077  7077 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 12:23:45.632  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:45.635  4306  7490 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 12:23:45.636  7248  7248 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 12:23:45.636  7248  7248 I wpa_supplicant: monitor socket send errors count : 1
08-30 12:23:45.636  7248  7248 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1939-4\x00 that cannot receive messages
08-30 12:23:45.639  1035  7273 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 12:23:45.639  1035  7273 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 12:23:45.647  7077  7493 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 12:23:45.649  6967  7494 W FormManager: Network not available. Please check & try again.
08-30 12:23:45.652  3415  3415 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 12:23:45.652  3415  3415 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:45.652  3415  3415 I LgeMiscReceiver: networkInfo.isConnected() = true
08-30 12:23:45.652  3415  3415 D PhoneState: setPdpRejectCasuse : false
08-30 12:23:45.654  4306  7491 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:45.654  4306  7491 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 12:23:45.655  7109  7109 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 12:23:45.656  7109  7109 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 12:23:45.656  6967  7495 V FormManager: Network unavailable.
08-30 12:23:45.663  6967  7495 V FormManager: Network unavailable.
,08-30 12:23:45.666  7191  7191 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:23:45
08-30 12:23:45.668  7191  7191 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 12:23:45.668  7191  7191 D Weather.Utils: 2 : All the weather widget is gone.
,08-30 12:23:45.668  7191  7191 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 12:23:45.668  7191  7191 D WeatherAncestor: connectivity changed - connection : true
08-30 12:23:45.669  7191  7191 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3475c62d
08-30 12:23:45.669  7191  7191 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 12:23:45.669  7191  7191 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 12:23:45.669  7191  7191 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 12:23:45.669  7191  7191 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 12:23:45.669  7191  7191 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:23:45
08-30 12:23:45.676  7248  7248 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 12:23:45.676  1035  7273 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-30 12:23:45.676  1035  7273 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 12:23:45.677  1035  7273 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 12:23:45.677  7248  7248 W wpa_supplicant: USIM:  scard_deinit function
08-30 12:23:45.677  1035  7273 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 12:23:45.677  1035  7273 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 12:23:45.677  1035  7273 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 12:23:45.678  1035  1437 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=342911
08-30 12:23:45.679  1035  1117 D Tethering: InitialState.processMessage what=4
08-30 12:23:45.679  1035  1437 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=342912
08-30 12:23:45.680  1035  1437 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=342912  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 12:23:45.680  1035  1437 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=342913  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 12:23:45.680  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 12:23:45.681  1035  1437 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:23:45.681  1035  1437 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:23:45.683  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 12:23:45.684  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:45.685  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:23:45.692  1035  7333 D DhcpStateMachine: StoppedState
08-30 12:23:45.692  1035  7333 D DhcpStateMachine: StoppedState{ when=-166ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 12:23:45.693  1035  1437 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-30 12:23:45.694  1035  1437 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-30 12:23:45.695  6420  6420 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:23:45.699  6881  6881 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 12:23:45.699  6881  6881 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 12:23:45.699  6881  6881 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 12:23:45.703  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:23:45.708  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:23:45.715  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 12:23:45.716  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:23:45.718  6909  6909 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 12:23:45.722  6420  6420 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:23:45.725  6881  6881 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 12:23:45.725  6881  6881 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 12:23:45.725  6881  6881 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 12:23:45.729  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:23:45.739  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:23:45.747  7248  7248 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-30 12:23:45.747  1035  7273 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-30 12:23:45.748  1035  7273 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-30 12:23:45.748  1035  7273 D WifiMonitor: Disconnecting from the supplicant, no more events
08-30 12:23:45.750  1035  1437 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-30 12:23:45.750  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:23:45.751  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:23:45.754  6909  6909 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 12:23:45.759  6420  6420 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 12:23:45.766  6881  6881 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 12:23:45.767  6881  6881 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 12:23:45.767  6881  6881 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 12:23:45.773  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:23:45.784  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 12:23:45.796  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 12:23:45.797  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:23:45.800  6909  6909 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 12:23:45.812  6881  6881 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 12:23:45.817  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 12:23:45.824  6967  7498 W FormManager: Network not available. Please check & try again.
,08-30 12:23:45.830  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 12:23:45.831  6967  7499 V FormManager: Network unavailable.
08-30 12:23:45.842  6967  7499 V FormManager: Network unavailable.
,08-30 12:23:45.857  1035  1437 D WifiOffDelayIfNotUsed: stopMonitoring
08-30 12:23:45.857  1035  1437 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 12:23:45.857  1035  1437 E WifiStateMachine: useWiFiOffloading() : false
08-30 12:23:45.857  1035  1437 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 12:23:45.858  1939  1939 D WfdsService: Supplicant Connection state is changed : false
08-30 12:23:45.858  1939  2319 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 12:23:45.858  1939  2319 D WfdsService: Set the WFDS Monitor: false
08-30 12:23:45.858  1939  2319 D WfdsMonitor: WFDS Monitor is stopped
08-30 12:23:45.862  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 12:23:45.862  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 12:23:45.866  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:45.866  2503  2503 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:45.867  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:23:45.867  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:45.867  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:45.867  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:23:45.867  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:23:45.867  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:23:45.867  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:23:45.867  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:23:45.874  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:45.874  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:23:45.874  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:45.874  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:45.874  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:23:45.874  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:23:45.874  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:23:45.874  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:23:45.874  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:23:45.874  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 12:23:45.876  1035  1466 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 12:23:45.876  1035  1466 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 12:23:45.876  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:45.885  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 12:23:45.885  6850  6850 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 12:23:45.885  6850  6850 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-30 12:23:45.885  6850  6850 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 12:23:45.886  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 12:23:45.893  6850  6850 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 12:23:45.893  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 12:23:45.893  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 12:23:45.893  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 12:23:45.893  6850  6850 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 12:23:45.893  6850  6850 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 12:23:45.897  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 12:23:45.898  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 12:23:45.900  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:23:45.903  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 12:23:45.912  4306  7500 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 12:23:45.913  6881  6881 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-30 12:23:45.913  6881  6881 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 12:23:45.913  6881  6881 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 12:23:45.917  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 12:23:45.923  4306  7501 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 12:23:45.923  6967  7503 W FormManager: Network not available. Please check & try again.
08-30 12:23:45.923  4306  7501 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 12:23:45.925  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:23:45.939  6967  7504 V FormManager: Network unavailable.
,08-30 12:23:45.944  6967  7504 V FormManager: Network unavailable.
08-30 12:23:46.021  7212  7243 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-30 12:23:46.580  1035  1035 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
,08-30 12:23:46.999  1035  1574 I ActivityManager: Killing 6926:com.lge.settings.easy/1000 (adj 15): empty #17
,08-30 12:23:47.032  1035  2029 W libprocessgroup: failed to open /acct/uid_1000/pid_6926/cgroup.procs: No such file or directory
,08-30 12:23:48.337  1035  1437 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-621154192] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 12:23:48.339  1035  1437 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-621154189] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 12:23:48.577  1035  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:23:48.590  1035  1117 D Tethering: MasterInitialState.processMessage what=3
08-30 12:23:48.606  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:23:48.611  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:48.613  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:48.615  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:48.616  1035  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:48.620  6420  6420 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-30 12:23:48.624  6420  6879 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 12:23:48.633  1035  1117 D Tethering: MasterInitialState.processMessage what=3
,08-30 12:23:48.642  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:48.643  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:48.644  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:48.650  5736  5736 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 12:23:48.658  5736  5736 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 12:23:48.679  2205  2205 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:23:48.701  7038  7038 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 12:23:48.701  7038  7038 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:48.701  7038  7038 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 12:23:48.701  7038  7038 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 12:23:48.706  7038  7038 I AppUp4:CustModeStarterReceiver: onReceive
08-30 12:23:48.709  7038  7038 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@175ac657
08-30 12:23:48.709  7038  7038 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 12:23:48.709  7038  7038 D AppUp4:CustFacade: isPhone : true
08-30 12:23:48.710  7038  7038 D AppUp4:CustModeStarterReceiver: begin check event
08-30 12:23:48.710  7038  7038 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 12:23:48.714  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:48.715  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 12:23:48.719  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:23:48.722  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:23:48.729  7077  7077 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 12:23:48.743  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:23:48.747  4306  7528 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 12:23:48.751  4306  7530 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:48.752  4306  7530 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 12:23:48.761  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:23:48.762  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 12:23:48.766  7077  7531 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:48.767  6967  7536 W FormManager: Network not available. Please check & try again.
08-30 12:23:48.773  6967  7537 V FormManager: Network unavailable.
08-30 12:23:48.776  3415  3415 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 12:23:48.776  3415  3415 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:48.776  3415  3415 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-30 12:23:48.780  7109  7109 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-30 12:23:48.780  6967  7537 V FormManager: Network unavailable.
08-30 12:23:48.780  7109  7109 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 12:23:48.792  7191  7191 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:23:48
,08-30 12:23:48.794  7191  7191 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-30 12:23:48.794  7191  7191 D Weather.Utils: 2 : All the weather widget is gone.
08-30 12:23:48.795  7191  7191 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 12:23:48.795  7191  7191 D WeatherAncestor: connectivity changed - connection : true
08-30 12:23:48.795  7191  7191 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3475c62d
08-30 12:23:48.796  7191  7191 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 12:23:48.796  7191  7191 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 12:23:48.796  7191  7191 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 12:23:48.796  7191  7191 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 12:23:48.796  7191  7191 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:23:48
08-30 12:23:48.808  1035  1975 I ActivityManager: Killing 7354:com.lge.bnr/1000 (adj 15): empty #17
,08-30 12:23:48.888  1035  2045 W libprocessgroup: failed to open /acct/uid_1000/pid_7354/cgroup.procs: No such file or directory
,08-30 12:23:48.922  6420  6420 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-30 12:23:48.925  6420  6879 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 12:23:48.957  2205  2205 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:23:48.970  7038  7038 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 12:23:48.970  7038  7038 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:48.971  7038  7038 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 12:23:48.971  7038  7038 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 12:23:48.973  7038  7038 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 12:23:48.980  7038  7038 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@175ac657
08-30 12:23:48.980  7038  7038 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 12:23:48.980  7038  7038 D AppUp4:CustFacade: isPhone : true
08-30 12:23:48.980  7038  7038 D AppUp4:CustModeStarterReceiver: begin check event
08-30 12:23:48.980  7038  7038 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 12:23:48.986  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:48.986  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 12:23:48.991  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:23:48.996  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:23:49.003  4306  7540 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 12:23:49.008  7077  7077 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 12:23:49.011  4306  7541 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:49.011  4306  7541 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 12:23:49.054  7077  7542 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 12:23:49.062  3415  3415 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 12:23:49.062  3415  3415 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 12:23:49.063  3415  3415 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 12:23:49.063  6967  7547 W FormManager: Network not available. Please check & try again.
08-30 12:23:49.063  6967  7548 V FormManager: Network unavailable.
08-30 12:23:49.069  7109  7109 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 12:23:49.069  7109  7109 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 12:23:49.072  6967  7548 V FormManager: Network unavailable.
08-30 12:23:49.083  7191  7191 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:23:49
,08-30 12:23:49.085  7191  7191 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 12:23:49.085  7191  7191 D Weather.Utils: 2 : All the weather widget is gone.
08-30 12:23:49.086  7191  7191 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 12:23:49.086  7191  7191 D WeatherAncestor: connectivity changed - connection : true
08-30 12:23:49.086  7191  7191 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3475c62d
08-30 12:23:49.087  7191  7191 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 12:23:49.087  7191  7191 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 12:23:49.087  7191  7191 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 12:23:49.087  7191  7191 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 12:23:49.087  7191  7191 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:23:49
08-30 12:23:49.570  6909  6909 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-30 12:23:49.571  6909  6909 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:4781
,08-30 12:23:50.369  1035  1920 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 12:23:50.370  1035  1920 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-30 12:23:50.395  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 12:23:50.396  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 12:23:50.396  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-30 12:23:50.396  1035  1117 D BluetoothManagerService: Message: 1
08-30 12:23:50.396  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-30 12:23:50.423  1035  1117 D BluetoothManagerService: Message: 20
08-30 12:23:50.423  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e6c9706:true
,08-30 12:23:50.427  6950  6950 D BluetoothAdapterState: make
08-30 12:23:50.432  6950  6950 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 12:23:50.432  6950  6950 I bluedroid-qcom: init
08-30 12:23:50.434  6950  7562 I BluetoothAdapterState: Entering OffState
08-30 12:23:50.434  6950  6950 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 12:23:50.434  6950  6950 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 12:23:50.434  6950  6950 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 12:23:50.434  6950  6950 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 12:23:50.434  6950  6950 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 12:23:50.436  6950  6950 I bluedroid-qcom: get_profile_interface socket
08-30 12:23:50.436  6950  6950 I bluedroid-qcom: get_profile_interface map_client
,08-30 12:23:50.441  6950  7566 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 12:23:50.444  6950  7566 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 12:23:50.436  7565  7565 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:23:50.436  7565  7565 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:23:50.454  7565  7565 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 12:23:50.454  7565  7565 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 12:23:50.454  7565  7565 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-30 12:23:50.462  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-30 12:23:50.462  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 12:23:50.463  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 12:23:50.463  1035  1117 D BluetoothManagerService: Message: 40
08-30 12:23:50.463  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 12:23:50.464  6950  6966 I bluedroid-qcom: config_hci_snoop_log
08-30 12:23:50.466  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 12:23:50.466  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 12:23:50.467  7565  7565 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-30 12:23:50.475  7565  7565 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 12:23:50.475  7565  7565 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-30 12:23:50.479  6950  7562 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-30 12:23:50.481  6950  7566 D BluetoothAdapterProperties: Name is: G3
08-30 12:23:50.481  6950  7562 D BluetoothAdapterProperties: Setting state to 11
08-30 12:23:50.481  6950  7562 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 12:23:50.482  1035  1117 D BluetoothManagerService: Message: 60
08-30 12:23:50.482  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 12:23:50.482  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-30 12:23:50.484  6950  7562 I LGBluetoothServiceJni: classInitNative: succeeds
08-30 12:23:50.489  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 12:23:50.492  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 12:23:50.495  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:50.498  6850  6850 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-30 12:23:50.499  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:50.505  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:23:50.509  6950  6950 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 12:23:50.510  6950  6950 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:50.510  6950  6950 V BluetoothPbapReceiver: ***********state = 11
08-30 12:23:50.516  2205  2205 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 12:23:50.538  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=-8ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 12:23:50.539  1035  1390 D LGWifiP2pService: DefaultState{ when=-20ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:23:50.563  1035  1437 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-30 12:23:50.563  1035  1437 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-30 12:23:50.574  1035  1993 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7581 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-30 12:23:50.578  6950  7562 D BluetoothBondStateMachine: make
,08-30 12:23:50.582  6950  7591 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 12:23:50.582  6950  7562 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3475c62d
08-30 12:23:50.582  6950  7562 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 12:23:50.582  6950  7562 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3475c62d
08-30 12:23:50.582  6950  7562 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-30 12:23:50.583  6950  7562 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-30 12:23:50.588  6950  7562 E BluetoothAdapterService: File transfer profiles supported!!
08-30 12:23:50.594  6950  7562 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 12:23:50.598  6950  6950 D HeadsetService: Received start request. Starting profile...
08-30 12:23:50.599  6950  6950 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 12:23:50.599  6950  6950 D LGBluetoothHfpAdapter: Version 1.6
08-30 12:23:50.601  6950  7562 E BluetoothAdapterService: File transfer profiles supported!!
08-30 12:23:50.606  6950  6950 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 12:23:50.607  6950  7562 E BluetoothAdapterService: File transfer profiles supported!!
08-30 12:23:50.608  6950  6950 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 12:23:50.609  6950  6950 D HeadsetStateMachine: make
,08-30 12:23:50.613  6950  7562 E BluetoothAdapterService: File transfer profiles supported!!
08-30 12:23:50.618  6950  7562 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 12:23:50.627  6950  7562 E BluetoothAdapterService: File transfer profiles supported!!
08-30 12:23:50.654  6950  6950 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:23:50.654  6950  6950 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:23:50.655  6950  7562 V LGMDMManager: Create singleton instance
,08-30 12:23:50.657  6950  7562 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 12:23:50.659  6950  6950 D HeadsetStateMachine: max_hf_connections = 1
08-30 12:23:50.659  6950  6950 I bluedroid-qcom: get_profile_interface handsfree
08-30 12:23:50.661  6950  6950 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-30 12:23:50.662   322  2133 V AudioPolicyService: registerClient() client 0xb0403e60, uid 1002
08-30 12:23:50.662   322   322 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 12:23:50.662   322   322 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 12:23:50.662   322   322 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 12:23:50.662  6950  6950 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 12:23:50.663   322  2132 V AudioFlinger: registerClient() client 0xb14330a0, pid 6950
08-30 12:23:50.663   322  1391 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 12:23:50.663   322  1391 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 12:23:50.664  6950  6950 V ToneGenerator: Create Track: 0xb4928080
08-30 12:23:50.664  6950  6950 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 12:23:50.664  6950  6950 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 12:23:50.664   322  1397 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 12:23:50.664   322  1397 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 12:23:50.664   322  1397 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 12:23:50.664   322  1397 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 12:23:50.664  1035  1957 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 12:23:50.664  6950  6950 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 12:23:50.664  1035  1957 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 12:23:50.664  6950  6965 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 12:23:50.664  6950  6965 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 12:23:50.664  3415  3430 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,08-30 12:23:50.664  3415  3430 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 12:23:50.664   322  2132 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 12:23:50.665   322  1396 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 12:23:50.665   322  1396 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-30 12:23:50.665   322  1396 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 12:23:50.665   322  1396 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 12:23:50.665   322  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 12:23:50.665  6950  6950 V AudioSystem: getLatency() output 2, latency 50
08-30 12:23:50.665   322  1392 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 12:23:50.665  6950  6950 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 12:23:50.665  6950  6950 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 12:23:50.665  1035  1574 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 12:23:50.665  1035  1574 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 12:23:50.665  3415  3431 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 12:23:50.665  1601  1618 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 12:23:50.665  6950  6966 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 12:23:50.665  3415  3431 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 12:23:50.665  1601  1618 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 12:23:50.665  6950  6966 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 12:23:50.665  1601  1618 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 12:23:50.665  1601  1618 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 12:23:50.665  1850  1865 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 12:23:50.665  1850  1865 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 12:23:50.665  1850  1865 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 12:23:50.665  1850  1865 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 12:23:50.666   322   322 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 12:23:50.666   322   322 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 12:23:50.666   322   322 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 12:23:50.666   322   322 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 12:23:50.666   322   322 V AudioFlinger: createTrack() lSessionId: 22
08-30 12:23:50.666  6950  6950 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 12:23:50.667   322   322 V AudioFlinger: acquiring 22 from 6950, for 6950
08-30 12:23:50.667   322   322 V AudioFlinger:  added new entry for 22
08-30 12:23:50.667  6950  6950 V ToneGenerator: ToneGenerator INIT OK, time: 347911
08-30 12:23:50.667  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3475c62d
08-30 12:23:50.667  6950  7600 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 12:23:50.668  6950  7600 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 12:23:50.668  6950  7600 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 12:23:50.668  6950  7600 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 12:23:50.668   322  2132 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6950
08-30 12:23:50.668  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3475c62d
08-30 12:23:50.6,69   322  2132 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 12:23:50.669   322  2132 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 12:23:50.669   322  2132 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 12:23:50.669   322  2132 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 12:23:50.669   322  2132 V voice   : voice_set_parameters: exit with code(0)
08-30 12:23:50.669   322  2132 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 12:23:50.669   322  2132 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 12:23:50.669   322  2132 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 12:23:50.669   322  2132 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 12:23:50.669   322  2132 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 12:23:50.669   322  2132 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 12:23:50.669  6950  7600 V ToneGenerator: ToneGenerator destructor
08-30 12:23:50.669  6950  7600 V ToneGenerator: stopTone
08-30 12:23:50.669  6950  7600 V ToneGenerator: Delete Track: 0xb4928080
08-30 12:23:50.669  6950  7600 V AudioTrack: ~AudioTrack, releasing session id from 6950 on behalf of 6950
08-30 12:23:50.670   322  1397 V AudioFlinger: releasing 22 from 6950 for 6950
08-30 12:23:50.670   322  1397 V AudioFlinger:  decremented refcount to 0
08-30 12:23:50.670   322  1397 V AudioFlinger: purging stale effects
08-30 12:23:50.670   322  1397 V AudioPolicyService: AudioCommandThread() adding release output 2
08-30 12:23:50.670   322  1397 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 12:23:50.670   322  1270 V AudioPolicyService: AudioCommandThread() waking up
08-30 12:23:50.670   322  1270 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 12:23:50.670   322  1270 V AudioPolicyManager: releaseOutput() 2
08-30 12:23:50.670   322  1270 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 12:23:50.670   322  1397 V AudioFlinger: PlaybackThread::Track destructor
08-30 12:23:50.670   322  1397 V AudioFlinger: removeClient_l() pid 6950, calling pid 322
08-30 12:23:50.671  6950  6950 D A2dpService: Received start request. Starting profile...
08-30 12:23:50.672  6950  6950 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 12:23:50.672  6950  6950 V Avrcp   : make
08-30 12:23:50.673  6950  6950 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 12:23:50.673  6950  6950 I bluedroid-qcom: get_profile_interface avrcp
08-30 12:23:50.674  1035  1956 W Process : Unable to open /proc/7605/status
,08-30 12:23:50.682  6950  6950 V AudioManager: registerRemoteController: size of Media player list: 0
,08-30 12:23:50.684  6950  6950 E AudioManager: No RCC entry present to update
08-30 12:23:50.685  6950  6950 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 12:23:50.688  6950  6950 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-30 12:23:50.689  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
,08-30 12:23:50.689  6950  6950 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,08-30 12:23:50.693  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 12:23:50.744  7581  7581 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-30 12:23:50.745  7581  7581 W LG Account v2.2: No ProfileInfo entries
08-30 12:23:50.745  7581  7581 I LG Account v2.2: isEnabled: false
08-30 12:23:50.746  7581  7581 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 12:23:50.746  7581  7581 I Feature : [Lifetracker]Country: EU
,08-30 12:23:50.746  7581  7581 I Feature : [Lifetracker]Operator: OPEN
08-30 12:23:50.746  7581  7581 I Feature : [Lifetracker]Ranking support: false
08-30 12:23:50.746  7581  7581 I Feature : [Lifetracker]Comfort support: false
08-30 12:23:50.746  7581  7581 I Feature : [Lifetracker]Accessory: true
08-30 12:23:50.746  7581  7581 I Feature : [Lifetracker]Health device: true
08-30 12:23:50.747  7581  7581 I Feature : [Lifetracker]Extra Pedometer: false
08-30 12:23:50.747  7581  7581 I Feature : [Lifetracker]Blood glucose device: false
08-30 12:23:50.747  7581  7581 I Feature : [Lifetracker]Device Number: 3
,08-30 12:23:50.765  6850  6850 D BluetoothPermissionRequest: onReceive
,08-30 12:23:50.772  6850  6850 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 12:23:50.810  1035  1975 V SIM_STK : Menu title from STK is T-Mobile
08-30 12:23:50.810  1035  1975 V SIM_STK : Menu title from STK is T-Mobile
,08-30 12:23:50.883  1035  2045 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-30 12:23:50.891  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-30 12:23:50.895  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-30 12:23:50.896  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,08-30 12:23:50.896  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 12:23:50.896  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 12:23:50.896  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 12:23:50.896  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 12:23:50.896  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 12:23:50.896  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 12:23:50.896  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 12:23:50.897  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 12:23:50.897  6950  6950 I BluetoothA2dpServiceJni: classInitNative
08-30 12:23:50.897  6950  6950 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 12:23:50.897  6950  6950 D A2dpStateMachine: make
08-30 12:23:50.901  6950  6950 I bluedroid-qcom: get_profile_interface a2dp
08-30 12:23:50.901  6950  7611 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-30 12:23:50.904  6950  6950 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 12:23:50.904  6950  6950 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-30 12:23:50.904  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3475c62d
08-30 12:23:50.905  6950  7610 D A2dpStateMachine: Enter Disconnected: -2
08-30 12:23:50.905  6950  6950 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 12:23:50.907  6950  6950 D HidService: Received start request. Starting profile...
08-30 12:23:50.907  6950  6950 I bluedroid-qcom: get_profile_interface hidhost
08-30 12:23:50.907  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3475c62d
08-30 12:23:50.907  6950  6950 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 12:23:50.909  6950  6950 D HealthService: Received start request. Starting profile...
08-30 12:23:50.912  6950  6950 I bluedroid-qcom: get_profile_interface health
08-30 12:23:50.912  6950  6950 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 12:23:50.912  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3475c62d
08-30 12:23:50.912  6950  6950 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 12:23:50.914  6950  6950 D PanService: Received start request. Starting profile...
08-30 12:23:50.914  6950  6950 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 12:23:50.914  6950  6950 I bluedroid-qcom: get_profile_interface pan
08-30 12:23:50.921  6950  6950 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-30 12:23:50.921  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3475c62d
08-30 12:23:50.921  6950  6950 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-30 12:23:50.925  6950  6950 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 12:23:50.925  6950  6950 D BtGatt.GattService: Received start request. Starting profile...
,08-30 12:23:50.925  6950  6950 D BtGatt.GattService: start()
08-30 12:23:50.925  6950  6950 I bluedroid-qcom: get_profile_interface gatt
08-30 12:23:50.925  6950  6950 D BtGatt.AdvertiseManager: advertise manager created
08-30 12:23:50.938  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3475c62d
,08-30 12:23:50.941  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3475c62d
08-30 12:23:50.942  6950  6950 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-30 12:23:50.944  6950  6950 V BluetoothMapService: BluetoothMapBinder()
08-30 12:23:50.946  6950  6950 D BluetoothMapService: Received start request. Starting profile...
08-30 12:23:50.946  6950  6950 D BluetoothMapService: start()
08-30 12:23:50.953  6950  6950 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-30 12:23:50.953  6950  6950 D BluetoothMapEmailAppObserver: createReceiver()
,08-30 12:23:50.956  6950  6950 D BluetoothMapEmailAppObserver: initObservers()
08-30 12:23:50.956  6950  6950 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 12:23:50.972  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3475c62d
08-30 12:23:50.972  6950  6950 D HeadsetStateMachine: Proxy object connected
08-30 12:23:50.973  6950  6950 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 12:23:50.973  6950  6950 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-30 12:23:50.979  6950  6950 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 12:23:50.980  6950  7600 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 12:23:50.981  6950  7600 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 12:23:50.982  6950  7600 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-30 12:23:50.986  6950  6950 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 12:23:50.990  6950  6950 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 12:23:50.994  6950  6950 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 12:23:50.998  6950  6950 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 12:23:50.998  6950  6950 V PanService: [BTUI] SIM Extra State :ABSENT
08-30 12:23:51.002  6950  6950 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-30 12:23:51.003  6950  6950 V BluetoothMapService: Handler(): got msg=1
08-30 12:23:51.004  6950  7562 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 12:23:51.004  6950  7562 I bluedroid-qcom: enable
08-30 12:23:51.005  6950  7562 I bt_hci_bdroid: init
08-30 12:23:51.005  6950  7621 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 12:23:51.006  6950  7621 I bt-btu  : btu_task pending for preload complete event
08-30 12:23:51.006  6950  6950 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:51.007  6950  7562 I bt_vendor: bt-vendor : init
08-30 12:23:51.007  6950  7562 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 12:23:51.007  6950  7562 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 12:23:51.007  6950  7562 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 12:23:51.007  6950  7562 D bt_userial_mct: userial_init
08-30 12:23:51.009  6950  7562 D bt_hci_bdroid: set_power 1
08-30 12:23:51.009  6950  7562 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 12:23:51.009  6950  7562 I bt_vendor: Starting hciattach daemon
08-30 12:23:51.009  6950  7562 I bt_vendor: try to set true
08-30 12:23:50.996  7624  7624 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:23:51.014  6950  6950 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 12:23:51.014  6950  6950 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 12:23:51.014  6950  6950 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 12:23:50.996  7624  7624 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:23:51.015  6950  6950 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-30 12:23:51.018  6950  6950 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,08-30 12:23:51.034  7625  7625 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 12:23:51.083  1035  1957 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7630 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 12:23:51.121  7648  7648 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 12:23:51.133  7649  7649 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 12:23:51.150  7630  7630 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 12:23:51.156  7651  7651 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-30 12:23:51.166  1035  1574 I ActivityManager: Killing 6881:com.lge.sync/1000 (adj 15): empty #17
08-30 12:23:51.167  7652  7652 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-30 12:23:51.178  7653  7653 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 12:23:51.189  7654  7654 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-30 12:23:51.213  7656  7656 I libmdmdetect: ESOC framework not supported
,08-30 12:23:51.214  7656  7656 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-30 12:23:51.222  7656  7656 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-30 12:23:51.222  7656  7656 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-30 12:23:51.222  7656  7656 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-30 12:23:51.222  7656  7656 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-30 12:23:51.222  7656  7656 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-30 12:23:51.222  7656  7656 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-30 12:23:51.222  7656  7656 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-30 12:23:51.227  1035  1784 W libprocessgroup: failed to open /acct/uid_1000/pid_6881/cgroup.procs: No such file or directory
,08-30 12:23:51.261  7656  7657 E QC-QMI  : qmi_client [7656] 14: failed to locate client data
08-30 12:23:51.262   484   484 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-30 12:23:51.262   484   484 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-30 12:23:51.306  7658  7658 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 12:23:51.324  7659  7659 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 12:23:51.362  6950  7562 I bt_vendor: bluetooth satus is on
,08-30 12:23:51.362  6950  7562 D bt_hci_bdroid: preload
08-30 12:23:51.363  6950  7623 D bt_userial_mct: userial_open(port:0)
08-30 12:23:51.363  6950  7623 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-30 12:23:51.366  6950  7623 I bt_vendor: Done intiailizing UART
08-30 12:23:51.367  6950  7623 I bt_vendor: Done intiailizing UART
08-30 12:23:51.367  6950  7623 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 12:23:51.367  6950  7623 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-30 12:23:51.368  6950  7661 D bt_userial_mct: Entering userial_read_thread()
08-30 12:23:51.368  6950  7621 I bt-btu  : btu_task received preload complete event
08-30 12:23:51.368  6950  7621 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
,08-30 12:23:51.368  6950  7621 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-30 12:23:51.370  6950  7621 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-30 12:23:51.373  6950  7621 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 12:23:51.374  6950  7621 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 12:23:51.374  6950  7621 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 12:23:51.374  6950  7621 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 12:23:51.374  6950  7621 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 12:23:51.374  6950  7621 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 12:23:51.374  6950  7621 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 12:23:51.374  6950  7621 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 12:23:51.374  6950  7621 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-30 12:23:51.374  6950  7621 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 12:23:51.374  6950  7621 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 12:23:51.374  6950  7621 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 12:23:51.374  6950  7621 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 12:23:51.374  6950  7621 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 12:23:51.374  6950  7621 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 12:23:51.374  6950  7621 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 12:23:51.466  6950  7621 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-30 12:23:51.466  6950  7621 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa018e061 
08-30 12:23:51.467  6950  7621 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa018e061 
,08-30 12:23:51.527  6950  7566 E bt-btif : Calling BTA_HhEnable
08-30 12:23:51.527  6950  7566 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-30 12:23:51.528  6950  7566 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-30 12:23:51.537  6950  7621 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-30 12:23:51.537  6950  7621 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-30 12:23:51.537  6950  7621 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 12:23:51.538  6950  7621 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 12:23:51.538  6950  7621 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-30 12:23:51.542  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 12:23:51.542  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 12:23:51.544  6950  7566 D BluetoothAdapterProperties: Name is: G3
,08-30 12:23:51.557  6950  7566 D BluetoothAdapterProperties: Scan Mode:20
08-30 12:23:51.557  6950  7566 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 12:23:51.557  6950  7566 D bt_hci_bdroid: postload
08-30 12:23:51.557  6950  7623 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 12:23:51.558  6950  7621 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 12:23:51.559  6950  7566 D bte_conf: Device ID record 1 : primary
08-30 12:23:51.559  6950  7566 D bte_conf:   vendorId            = 00c4
08-30 12:23:51.559  6950  7566 D bte_conf:   vendorIdSource      = 0001
08-30 12:23:51.559  6950  7566 D bte_conf:   product             = 13a1
08-30 12:23:51.559  6950  7566 D bte_conf:   version             = 1000
08-30 12:23:51.559  6950  7566 D bte_conf:   clientExecutableURL = 
08-30 12:23:51.559  6950  7566 D bte_conf:   serviceDescription  = 
08-30 12:23:51.559  6950  7566 D bte_conf:   documentationURL    = 
08-30 12:23:51.559  6950  7566 D bte_conf: bte_load_did_conf no section named DID2.
08-30 12:23:51.563  6950  7621 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 12:23:51.563  6950  7621 W bt-smp  : Plain text(LSB ~ MSB) = 31 cd 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 12:23:51.563  6950  7621 W bt-smp  : Encrypted text(LSB ~ MSB) = 68 98 c5 d4 61 1c 0d 6d 9b c0 4a 87 a2 04 44 f5 
,08-30 12:23:51.567  6950  7623 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 12:23:51.567  6950  7621 W bt-btm  : Stopping oneshot timer
08-30 12:23:51.567  6950  7661 E bt_mct  : hci lib postload completed
08-30 12:23:51.556  7670  7670 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:23:51.556  7670  7670 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:23:51.572  6950  7562 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 12:23:51.572  6950  7562 D BluetoothAdapterProperties: ScanMode =  20
08-30 12:23:51.572  6950  7562 D BluetoothAdapterProperties: State =  11
08-30 12:23:51.572  6950  7562 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 12:23:51.573  6950  7562 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-30 12:23:51.573  6950  7562 D BluetoothAdapterProperties: Setting state to 12
08-30 12:23:51.573  6950  7562 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 12:23:51.573  6950  7566 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 12:23:51.574  6950  7566 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 12:23:51.581  6950  7562 I BluetoothAdapterState: Entering On State
,08-30 12:23:51.588  1035  1117 D BluetoothManagerService: Message: 60
08-30 12:23:51.588  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 12:23:51.588  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-30 12:23:51.588  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 12:23:51.608  6950  7621 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-30 12:23:51.611  6950  7621 W bt-smp  : Plain text(LSB ~ MSB) = ad 35 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 12:23:51.611  6950  7621 W bt-smp  : Encrypted text(LSB ~ MSB) = b2 69 c0 3b 1d 67 27 dd 78 3d 87 1e 49 7d bb c5 
08-30 12:23:51.611  6950  7621 W bt-btm  : Stopping oneshot timer
08-30 12:23:51.616  6950  7566 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 12:23:51.616  6950  7566 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-30 12:23:51.617  6950  7562 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 12:23:51.617  6950  7562 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 12:23:51.617  6950  7562 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-30 12:23:51.625  6950  7562 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-30 12:23:51.632  6950  7562 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-30 12:23:51.637  6950  7621 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 12:23:51.637  6950  7621 W bt-smp  : Plain text(LSB ~ MSB) = d4 96 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 12:23:51.637  6950  7621 W bt-smp  : Encrypted text(LSB ~ MSB) = 4b 10 74 df ce bb d0 ec ce 1f ad 27 54 16 f7 98 
08-30 12:23:51.638  6950  7621 W bt-btm  : Stopping oneshot timer
,08-30 12:23:51.646  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:23:51.646  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:51.646  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:51.646  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:23:51.646  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:23:51.646  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:23:51.646  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:23:51.646  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:23:51.649  1035  1035 D BluetoothA2dp: Proxy object connected
08-30 12:23:51.650  6950  7621 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 12:23:51.650  6950  7621 W bt-smp  : Plain text(LSB ~ MSB) = c5 6d 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 12:23:51.650  6950  7621 W bt-smp  : Encrypted text(LSB ~ MSB) = 95 2d 27 3d b2 c4 7b 1f 87 89 27 5e 9d 40 89 2b 
,08-30 12:23:51.652  6950  7621 W bt-btm  : Stopping oneshot timer
08-30 12:23:51.664  6950  7621 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 12:23:51.664  6950  7621 W bt-smp  : Plain text(LSB ~ MSB) = 6c 45 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 12:23:51.664  6950  7621 W bt-smp  : Encrypted text(LSB ~ MSB) = 35 31 15 f6 2a 0a 9e c0 00 3e d5 d3 88 0e ee 72 
,08-30 12:23:51.667  6950  7621 W bt-btm  : Stopping oneshot timer
08-30 12:23:51.667  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:23:51.699  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:23:51.699  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:51.699  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:51.699  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:23:51.699  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:23:51.699  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:23:51.699  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:23:51.699  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:23:51.703  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:23:51.707  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:23:51.707  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:51.707  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:51.707  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:23:51.707  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:23:51.707  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:23:51.707  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:23:51.707  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:23:51.709  7676  7676 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-30 12:23:51.713  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:23:51.714  6850  6871 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 12:23:51.719  6850  6949 D BluetoothPan: onBluetoothStateChange on: true
08-30 12:23:51.719  6850  6949 D BluetoothPan: onBluetoothStateChange call bindService
08-30 12:23:51.720  6850  6850 D BluetoothMap: Proxy object connected
08-30 12:23:51.721  6850  6850 D MapProfile: Bluetooth service connected
08-30 12:23:51.721  6850  6850 D BluetoothMap: getConnectedDevices()
08-30 12:23:51.723  6850  6871 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 12:23:51.724  6950  6965 V BluetoothMapService: getConnectedDevices()
08-30 12:23:51.724  6850  6850 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 12:23:51.724  6850  6850 D PanProfile: Bluetooth service connected
08-30 12:23:51.727  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 12:23:51.728  1850  1866 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:23:51.730  1035  1035 D BluetoothHeadset: Proxy object connected
08-30 12:23:51.731  1850  1850 D BluetoothHeadset: Proxy object connected
08-30 12:23:51.732  6850  6875 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 12:23:51.732  6850  6850 D BluetoothInputDevice: Proxy object connected
08-30 12:23:51.732  6850  6850 D HidProfile: Bluetooth service connected
08-30 12:23:51.735  1850  2397 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:23:51.737  1850  1850 D BluetoothHeadset: Proxy object connected
08-30 12:23:51.738  1850  2397 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:23:51.740  1850  1850 D BluetoothHeadset: Proxy object connected
,08-30 12:23:51.742  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-30 12:23:51.743  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-30 12:23:51.743  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-30 12:23:51.744  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:51.744  1939  2123 D LGBluetoothAPIService: Message: 1
08-30 12:23:51.744  1939  2123 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-30 12:23:51.747  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 12:23:51.748  1035  1117 D BluetoothManagerService: Message: 40
08-30 12:23:51.748  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 12:23:51.756  6950  6950 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:51.757  6950  6950 D BluetoothMapService: STATE_ON
08-30 12:23:51.758  6850  6850 D LocalBluetoothProfileManager: Adding local A2DP profile
08-30 12:23:51.758  6950  6950 D LGBluetoothAPIServer: [BTUI] onCreate()
08-30 12:23:51.758  6950  6950 D LGBluetoothAPIServer: [BTUI] onBind()
,08-30 12:23:51.760  1939  1939 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-30 12:23:51.760  6741  6741 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 12:23:51.763  1939  2123 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-30 12:23:51.763  1939  2123 D LGBluetoothAPIService: Message: 100
08-30 12:23:51.763  1939  2123 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-30 12:23:51.766  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:51.766  1035  1117 D BluetoothManagerService: Message: 30
08-30 12:23:51.770  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:51.770  6850  6850 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-30 12:23:51.777  1035  1117 D BluetoothManagerService: Message: 30
08-30 12:23:51.779  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3475c62d
08-30 12:23:51.779  6950  6950 V BluetoothPbapService: Pbap Service onCreate
08-30 12:23:51.779  6950  6950 V BluetoothPbapService: Starting PBAP service
08-30 12:23:51.781  6950  6950 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 12:23:51.781  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:51.781  6950  6950 V BluetoothMapService: Handler(): got msg=1
08-30 12:23:51.781  6950  6950 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 12:23:51.782  6950  6950 V BluetoothPbapService: Pbap Service onBind
08-30 12:23:51.783  6950  7694 D BluetoothMapMasInstance: MAS initSocket()
08-30 12:23:51.783  6950  7694 D BluetoothMapMasInstance:   masId = 00
08-30 12:23:51.783  6950  7694 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 12:23:51.783  6950  7694 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 12:23:51.783  6950  7694 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 12:23:51.783  6950  6950 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:51.784  6950  6950 V BluetoothPbapService: state: 12
08-30 12:23:51.784  6950  6950 V BluetoothPbapService: Handler(): got msg=1
08-30 12:23:51.784  6950  6950 V BluetoothPbapService: Pbap Service startRfcommSocketListener
,08-30 12:23:51.787  6950  7695 V BluetoothPbapService: Pbap Service initSocket
08-30 12:23:51.788  1035  1993 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:23:51.789  1035  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:23:51.790  6950  7695 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:23:51.791  6850  6850 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-30 12:23:51.791  6950  7694 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:23:51.792  6950  7695 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-30 12:23:51.792  6950  7695 V BluetoothPbapService: Succeed to create listening socket 
08-30 12:23:51.793  6950  7695 V BluetoothPbapService: Accepting socket connection...
08-30 12:23:51.793  6850  6850 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 12:23:51.796  6950  7566 D BluetoothAdapterProperties: Scan Mode:21
08-30 12:23:51.796  6950  7694 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-30 12:23:51.796  6950  7566 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-30 12:23:51.796  6950  7694 V BluetoothMapMasInstance: Succeed to create listening socket 
08-30 12:23:51.796  6950  7694 D BluetoothMapMasInstance: Accepting socket connection...
08-30 12:23:51.796  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:23:51.799  6850  6850 D BluetoothA2dp: Proxy object connected
08-30 12:23:51.800  6850  6850 D A2dpProfile: Bluetooth service connected
08-30 12:23:51.802  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:51.804  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:51.806  6950  6950 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 12:23:51.806  6950  6950 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:51.806  6950  6950 V BluetoothPbapReceiver: ***********state = 12
08-30 12:23:51.807  6850  6850 D BluetoothPbap: Proxy object connected
08-30 12:23:51.808  6850  6850 D PbapServerProfile: Bluetooth service connected
08-30 12:23:51.808  6850  6850 D BluetoothHeadset: Proxy object connected
,08-30 12:23:51.809  6850  6850 D HeadsetProfile: Bluetooth service connected
08-30 12:23:51.810  2205  2205 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 12:23:51.811  2205  2205 D c       : Getting all permits...
08-30 12:23:51.811  2205  2205 D a       : Opening database...
08-30 12:23:51.813  6850  6850 D DockEventReceiver: finishStartingService: stopping service
08-30 12:23:51.816  2205  2205 D a       : Opening database auth.proximity.permit_store...
08-30 12:23:51.817  2205  2205 D a       : Closing database...
08-30 12:23:51.828  6850  6850 D BluetoothPermissionRequest: onReceive
,08-30 12:23:51.830  6850  6850 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 12:23:51.831  6850  6850 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 12:23:51.835  6950  6950 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-30 12:23:51.837  6950  6950 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 12:23:51.844  6950  6950 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-30 12:23:51.865  6950  6950 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 12:23:51.865  6950  6950 V BtOppService: onCreate
,08-30 12:23:51.981  1035  1938 I art     : Explicit concurrent mark sweep GC freed 123826(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.670ms total 113.701ms
,08-30 12:23:51.983  6950  6950 V BluetoothOppNotification: send message
08-30 12:23:51.988  6950  6950 V BtOppService: Starting RfcommListener
08-30 12:23:51.996  6950  6950 D BluetoothOppPreference: Dumping Names:  
08-30 12:23:51.996  6950  6950 D BluetoothOppPreference: {}
08-30 12:23:51.996  6950  6950 D BluetoothOppPreference: Dumping Channels:  
08-30 12:23:51.996  6950  6950 D BluetoothOppPreference: {}
08-30 12:23:51.997  6950  6950 V BtOppService: onStartCommand
,08-30 12:23:52.000  6950  6950 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:52.000  6950  6950 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 12:23:52.004  6950  6950 V BluetoothOppNotification: new notify threadi!
08-30 12:23:52.005  6950  6950 V BluetoothOppNotification: send delay message
08-30 12:23:52.006  6950  6950 V BtOppService: start RfcommListener
08-30 12:23:52.007  6950  7704 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 12:23:52.009  6950  6950 V BtOppService: RfcommListener started
,08-30 12:23:52.013  6950  7701 V BtOppService: Deleted complete outbound shares, number =  0
08-30 12:23:52.014  6950  7706 V BtOppRfcommListener: Starting RFCOMM listener....
08-30 12:23:52.014  1035  1725 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:23:52.015  6950  7705 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 12:23:52.016  6950  7706 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:23:52.016  6950  7704 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 12:23:52.017  6950  7705 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12df2dbe on behalf of 
08-30 12:23:52.017  6950  7706 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-30 12:23:52.017  6950  7706 V BtOppRfcommListener: Started RFCOMM listener....
,08-30 12:23:52.017  6950  7705 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 12:23:52.017  6950  7706 I BtOppRfcommListener: Accept thread started.
08-30 12:23:52.018  6950  7701 V BtOppService: Deleted complete inbound failed shares, number = 0
08-30 12:23:52.018  6950  7706 V BtOppRfcommListener: Accepting connection...
08-30 12:23:52.018  6950  7701 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-30 12:23:52.019  6950  7705 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 12:23:52.019  6950  7704 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27ea8e1f on behalf of 
08-30 12:23:52.020  6950  7705 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@126256c on behalf of 
08-30 12:23:52.020  6950  7705 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 12:23:52.021  6950  7701 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a2d0735 on behalf of 
08-30 12:23:52.022  6950  7704 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 12:23:52.023  6950  7705 V BluetoothOppNotification: outbound notification was removed.
08-30 12:23:52.024  6950  7705 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 12:23:52.024  6950  7705 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@55c67ca on behalf of 
08-30 12:23:52.025  6950  7705 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-30 12:23:52.026  6950  7705 V BluetoothOppNotification: inbound notification was removed.
08-30 12:23:52.026  6950  7705 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 12:23:52.027  6950  7705 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33ed3b on behalf of 
08-30 12:23:52.041  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3475c62d
08-30 12:23:52.041  6950  6950 V BluetoothFtpService: Ftp Service onCreate
08-30 12:23:52.041  6950  6950 I BluetoothFtpService: Ftp Service onCreate
08-30 12:23:52.041  6950  6950 V BluetoothFtpService: Ftp Service onStartCommand
08-30 12:23:52.041  6950  6950 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 12:23:52.041  6950  6950 V BluetoothFtpService: Starting Listening on sockets
,08-30 12:23:52.042  6950  6950 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 12:23:52.042  6950  6950 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 12:23:52.042  6950  6950 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 12:23:52.042  6950  6950 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:52.042  6950  6950 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 12:23:52.042  6950  6950 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 12:23:52.044  6950  6950 V BtOppService: ContentObserver received notification
08-30 12:23:52.044  6950  6950 V BtOppService: ContentObserver received notification
08-30 12:23:52.044  6950  6950 V BluetoothFtpService: Handler(): got msg=1
08-30 12:23:52.045  6950  6950 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 12:23:52.045  6950  6950 V BluetoothFtpService: Ftp Service initSocket
08-30 12:23:52.047  1035  1884 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:23:52.048  6950  6950 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:23:52.048  6950  6950 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-30 12:23:52.049  6950  6950 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-30 12:23:52.050  6950  7708 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-30 12:23:52.050  6950  7707 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 12:23:52.050  6950  7707 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 12:23:52.051  6950  7707 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b33e1b1 on behalf of 
08-30 12:23:52.052  6950  7707 V BluetoothOppNotification: update too frequent, put in queue
08-30 12:23:52.052  6950  7707 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 12:23:52.063  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3475c62d
08-30 12:23:52.063  6950  6950 V BluetoothSapService: Sap Service onCreate
,08-30 12:23:52.065  6950  6950 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 12:23:52.065  6950  6950 V BluetoothSapService: state: 12
08-30 12:23:52.065  6950  6950 V BluetoothSapService: Starting SAP server process
08-30 12:23:52.066  6950  6950 V BluetoothSapService: SAP Service startRfcommListenerThread
08-30 12:23:52.056  7709  7709 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:23:52.068  6950  7710 V BluetoothSapService: Sap Service initRfcommSocket
08-30 12:23:52.056  7709  7709 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:23:52.068  1035  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:23:52.069  6950  7710 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:23:52.070  6950  7710 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-30 12:23:52.070  6950  7710 V BluetoothSapService: Succeed to create listening socket 
08-30 12:23:52.070  6950  7710 V BluetoothSapService: Accepting socket connection...
08-30 12:23:52.079  7709  7709 V BT_SAP  : Event pipe created
08-30 12:23:52.079  7709  7709 V BT_SAP  : create_server_socket qcom.sap.server
08-30 12:23:52.079  7709  7709 V BT_SAP  : created socket fd 6
,08-30 12:23:52.514  1601  1601 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-30 12:23:52.538  1035  1380 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 12:23:52.541  2030  2030 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-30 12:23:52.608  1035  1113 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7720 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-30 12:23:52.615  1601  1601 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-30 12:23:52.616  1601  1601 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-30 12:23:52.645  1035  1035 D administrator: Handling package changes for user 0
,08-30 12:23:52.703  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 12:23:52.717  7720  7720 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 12:23:52.775  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,08-30 12:23:52.776  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-30 12:23:52.794  7720  7720 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:23:52.794  7720  7720 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:23:52.858  1035  1112 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 12:23:52.864  1035  1112 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-30 12:23:52.871  2030  2030 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-30 12:23:52.873  2503  2503 V GmsNetworkLocationProvi: DISABLE
,08-30 12:23:52.903  1035  1112 D LocationProviderProxy: applying state to connected service
,08-30 12:23:52.905  2503  2503 E GCoreFlp: Bound FusedProviderService with LocationManager
08-30 12:23:52.927  7720  7766 I Babel   : MmsConfig: mnc/mcc: 0/0
08-30 12:23:52.927  7720  7766 I Babel   : MmsConfig.loadMmsSettings
,08-30 12:23:52.930  7720  7766 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-30 12:23:52.930  7720  7766 I Babel   : MmsConfig.loadFromDatabase
,08-30 12:23:52.952  7720  7766 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-30 12:23:52.952  7720  7766 I Babel   : MmsConfig.loadFromResources
08-30 12:23:52.953  7720  7766 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-30 12:23:52.954  7720  7766 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-30 12:23:52.968  7720  7764 W AudioCapabilities: Unsupported mime audio/evrc
08-30 12:23:52.968  7720  7764 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 12:23:52.969  7720  7764 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-30 12:23:52.975  7720  7764 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-30 12:23:52.977  7720  7764 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 12:23:52.977  7720  7764 W AudioCapabilities: Unsupported mime audio/evrc
08-30 12:23:52.978  7720  7720 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:23:52.983  7720  7764 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-30 12:23:52.984  7720  7764 W VideoCapabilities: Unsupported mime video/divx
08-30 12:23:52.985  7720  7764 W VideoCapabilities: Unsupported mime video/divx311
08-30 12:23:52.986  7720  7764 W VideoCapabilities: Unsupported mime video/divx4
,08-30 12:23:52.991  7720  7764 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-30 12:23:53.006  6950  6950 V BluetoothOppNotification: new notify threadi!
08-30 12:23:53.006  6950  6950 V BluetoothOppNotification: send delay message
08-30 12:23:53.007  6950  7767 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 12:23:53.009  6950  7767 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19f3e7ed on behalf of 
08-30 12:23:53.010  7720  7764 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-30 12:23:53.012  6950  7767 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 12:23:53.013  6950  7767 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 12:23:53.016  6950  7767 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2bd22622 on behalf of 
08-30 12:23:53.018  1815  7769 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-30 12:23:53.018  6950  7767 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 12:23:53.018  1815  7769 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-30 12:23:53.025  6950  7767 V BluetoothOppNotification: outbound notification was removed.
08-30 12:23:53.025  6950  7767 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 12:23:53.027  6950  7767 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1064c8b3 on behalf of 
08-30 12:23:53.027  6950  7767 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-30 12:23:53.028  7038  7038 I AppUp4:CustModeStarterReceiver: onReceive
08-30 12:23:53.031  7720  7764 W AudioCapabilities: Unsupported mime audio/eac3
08-30 12:23:53.032  6950  7767 V BluetoothOppNotification: inbound notification was removed.
08-30 12:23:53.033  6950  7767 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 12:23:53.033  1815  4733 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-30 12:23:53.034  7038  7038 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@175ac657
08-30 12:23:53.034  7038  7038 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 12:23:53.034  7038  7038 D AppUp4:CustFacade: isPhone : true
08-30 12:23:53.035  7038  7038 D AppUp4:CustModeStarterReceiver: begin check event
08-30 12:23:53.035  7038  7038 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-30 12:23:53.035  7720  7764 W AudioCapabilities: Unsupported mime audio/ac3
,08-30 12:23:53.037  6950  7767 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d822e70 on behalf of 
08-30 12:23:53.046  7720  7764 W AudioCapabilities: Unsupported mime audio/g726
08-30 12:23:53.047  7720  7764 W AudioCapabilities: Unsupported mime audio/wma-voice
,08-30 12:23:53.048  7720  7764 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-30 12:23:53.049  7720  7764 W AudioCapabilities: Unsupported mime audio/adpcm
08-30 12:23:53.052  7720  7764 W VideoCapabilities: Unsupported mime video/theora
08-30 12:23:53.054  7720  7764 W VideoCapabilities: Unsupported mime video/mjpg
08-30 12:23:53.072  1035  1784 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7772 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-30 12:23:53.108  1035  1956 I ActivityManager: Killing 7376:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-30 12:23:53.110  7772  7772 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:23:53.110  7772  7772 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 12:23:53.110  7772  7772 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 12:23:53.111  7772  7772 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-30 12:23:53.111  7772  7772 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 12:23:53.200  1035  1920 W libprocessgroup: failed to open /acct/uid_10005/pid_7376/cgroup.procs: No such file or directory
,08-30 12:23:53.211  1035  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{15238496 type 2 when 350443 com.google.android.gms} when 350443
08-30 12:23:53.246  7772  7772 I SystemConfig: BUILD Country: EU
08-30 12:23:53.246  7772  7772 I SystemConfig: BUILD Operator: OPEN
,08-30 12:23:53.298  1035  1050 I ActivityManager: Killing 7077:com.lge.email/u0a23 (adj 15): empty #17
,08-30 12:23:53.428  1035  1885 W libprocessgroup: failed to open /acct/uid_10023/pid_7077/cgroup.procs: No such file or directory,
,08-30 12:23:53.441  7772  7790 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-30 12:23:53.441  7772  7790 I SystemConfig: existFile = false
08-30 12:23:53.441  7772  7790 I SystemConfig: canReadFile = false
08-30 12:23:53.441  7772  7790 I SystemConfig: systemFeature RCS result false
08-30 12:23:53.441  7772  7790 D SystemConfig: refreshRcsSupport() :false
08-30 12:23:53.491  1035  1050 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7795 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-30 12:23:53.570  7795  7795 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:23:53.570  7795  7795 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 12:23:53.570  7795  7795 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 12:23:53.571  7795  7795 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-30 12:23:53.672  7795  7795 I AppConfig: Total System Memory = 2995761152
,08-30 12:23:53.685  7795  7795 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-30 12:23:53.788  1035  1784 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7814 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 12:23:53.793  1035  1784 I ActivityManager: Killing 6967:com.lge.formmanager/u0a26 (adj 15): empty #17
08-30 12:23:53.889  1035  1574 W libprocessgroup: failed to open /acct/uid_10026/pid_6967/cgroup.procs: No such file or directory
,08-30 12:23:54.090  7814  7814 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-30 12:23:54.197  7814  7814 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:23:54.197  7814  7814 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:23:54.251  7814  7814 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-30 12:23:54.272  7814  7814 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 12:23:54.274  7814  7814 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-30 12:23:54.291  7814  7814 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 12:23:54.292  7814  7814 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-30 12:23:54.314  1035  1884 I ActivityManager: Killing 6420:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-30 12:23:54.349  1035  1725 W libprocessgroup: failed to open /acct/uid_1000/pid_6420/cgroup.procs: No such file or directory
,08-30 12:23:54.351  3484  3500 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-30 12:23:54.354  3484  3500 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1ee19b4b on behalf of 7814
08-30 12:23:54.356  4590  7854 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-30 12:23:54.412  1035  2045 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7855 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-30 12:23:54.450  7814  7814 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-30 12:23:54.487  7814  7814 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-30 12:23:54.516  7855  7855 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-30 12:23:54.544  7855  7855 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-30 12:23:54.544  7855  7855 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-30 12:23:54.544  7855  7855 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-30 12:23:54.544  7855  7855 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-30 12:23:54.544  7855  7855 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-30 12:23:54.544  7855  7855 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-30 12:23:54.564   316  7888 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-30 12:23:54.566  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 12:23:54.569  1035  1885 I ActivityManager: Killing 7109:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-30 12:23:54.599  1035  1956 W libprocessgroup: failed to open /acct/uid_10046/pid_7109/cgroup.procs: No such file or directory
,08-30 12:23:54.766  1035  1993 V SIM_STK : Menu title from STK is T-Mobile
,08-30 12:23:54.792  4590  7854 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 436 ms] updated apps [took 436 ms] 
,08-30 12:23:55.409  1035  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 12:23:55.409  1035  1938 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3a82fdff mBinding = false
,08-30 12:23:55.438  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 12:23:55.438  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 12:23:55.438  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-30 12:23:55.441  1035  1117 D BluetoothManagerService: Message: 2
08-30 12:23:55.442  1035  1117 D BluetoothManagerService: Sending off request.
08-30 12:23:55.443  6950  6966 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 12:23:55.444  6950  7562 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 12:23:55.444  6950  7562 D BluetoothAdapterProperties: Setting state to 13
08-30 12:23:55.444  6950  7562 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 12:23:55.445  6950  7562 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 12:23:55.445  6950  7562 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 12:23:55.447  6950  7566 D BluetoothAdapterProperties: Scan Mode:20
08-30 12:23:55.448  6950  7562 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 12:23:55.449  6950  7695 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 12:23:55.451  6950  7694 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 12:23:55.451  6950  7694 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 12:23:55.451  6950  7694 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 12:23:55.451  6950  7694 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 12:23:55.451  6950  7694 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 12:23:55.451  6950  7694 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 12:23:55.451  6950  7694 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 12:23:55.451  6950  7694 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-30 12:23:55.455  6950  7706 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 12:23:55.455  6950  7710 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 12:23:55.456  6950  7621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 12:23:55.456  6950  7708 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 12:23:55.457  6950  7621 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-30 12:23:55.459  6950  7621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 12:23:55.459  6950  7621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 12:23:55.459  6950  7621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 12:23:55.459  6950  7621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 12:23:55.459  6950  7621 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:23:55.459  6950  7621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 12:23:55.459  6950  7621 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 12:23:55.459  6950  7621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 12:23:55.459  6950  7621 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 12:23:55.459  6950  7621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 12:23:55.459  6950  7621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 12:23:55.459  6950  7621 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 12:23:55.460  6950  7562 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 12:23:55.466  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:55.466  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:23:55.466  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:55.466  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:55.466  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:23:55.466  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:23:55.466  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:23:55.466  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:23:55.466  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:23:55.479  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 12:23:55.481  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:23:55.487  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:55.487  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:23:55.487  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:55.487  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:55.487  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:23:55.487  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:23:55.487  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:23:55.487  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:23:55.487  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:23:55.488  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:55.488  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:23:55.491  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:55.491  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:23:55.491  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:23:55.491  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:23:55.491  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:23:55.491  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 12:23:55.491  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:23:55.491  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:23:55.491  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:23:55.495  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 12:23:55.495  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:23:55.496  1035  1117 D BluetoothManagerService: Message: 60
08-30 12:23:55.496  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-30 12:23:55.496  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-30 12:23:55.498  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:55.500  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 12:23:55.504  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:23:55.509  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:55.511  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:55.513  6950  6950 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:55.513  6950  6950 D BluetoothMapService: STATE_TURNING_OFF
08-30 12:23:55.513  6950  6950 V BluetoothMapService: Handler(): got msg=4
08-30 12:23:55.513  6950  6950 D BluetoothMapService: MAP Service closeService in
08-30 12:23:55.513  6950  6950 D BluetoothMapMasInstance: MAP Service shutdown
08-30 12:23:55.514  6950  6950 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 12:23:55.514  6950  6950 V BluetoothMapService: MAP Service closeService out
08-30 12:23:55.515  6950  6950 V BtOppService: Receiver DISABLED_ACTION 
08-30 12:23:55.515  6950  6950 I BtOppRfcommListener: stopping Accept Thread
08-30 12:23:55.515  6950  6950 V BtOppRfcommListener: close mBtServerSocket
08-30 12:23:55.516  6950  7706 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 12:23:55.516  6950  6950 V BtOppRfcommListener: waiting for thread to terminate
08-30 12:23:55.516  6950  6950 V BtOppRfcommListener: done waiting for thread to terminate
,08-30 12:23:55.528  6850  6850 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-30 12:23:55.530  6850  6850 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 12:23:55.531  6950  6950 V BtOppService: onDestroy
08-30 12:23:55.532  6950  6950 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 12:23:55.537  6950  6950 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 12:23:55.537  6950  6950 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:55.537  6950  6950 V BluetoothPbapReceiver: ***********state = 13
,08-30 12:23:55.541  6950  6950 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-30 12:23:55.543  6950  6950 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:55.543  6950  6950 V BluetoothPbapService: state: 13
08-30 12:23:55.544  6950  6950 V BluetoothPbapService: Pbap Service closeService in
08-30 12:23:55.547  2205  2205 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 12:23:55.548  6950  6950 V BluetoothPbapService: successfully stopped pbap service
08-30 12:23:55.548  6950  6950 V BluetoothPbapService: Pbap Service closeService out
08-30 12:23:55.549  6950  6950 V BluetoothPbapService: Pbap Service onDestroy
08-30 12:23:55.549  6950  6950 V BluetoothPbapService: Pbap Service closeService in
08-30 12:23:55.549  6950  6950 V BluetoothPbapService: Pbap Service closeService out
08-30 12:23:55.549  6950  6950 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-30 12:23:55.568  6850  6850 D DockEventReceiver: finishStartingService: stopping service
,08-30 12:23:55.572  6850  6850 D BluetoothPbap: Proxy object disconnected
,08-30 12:23:55.572  6850  6850 D PbapServerProfile: Bluetooth service disconnected
08-30 12:23:55.587  1035  1495 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-30 12:23:55.596  6850  6850 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-30 12:23:55.601  6850  6850 D BluetoothPermissionRequest: onReceive
08-30 12:23:55.601  6850  6850 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 12:23:55.612  6850  6850 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 12:23:55.619  6950  6950 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-30 12:23:55.619  6950  6950 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-30 12:23:55.621  6950  6950 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-30 12:23:55.625  6950  6950 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:55.626  6950  6950 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 12:23:55.627  6950  6950 V BluetoothFtpService: Ftp Service onStartCommand
08-30 12:23:55.627  6950  6950 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:55.628  6950  6950 V BluetoothFtpService: Ftp Service closeService
08-30 12:23:55.628  6950  6950 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-30 12:23:55.633  6950  6950 V BluetoothFtpService: successfully stopped ftp service
08-30 12:23:55.633  6950  6950 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-30 12:23:55.633  6950  6950 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 12:23:55.633  6950  6950 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 12:23:55.633  6950  6950 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:55.633  6950  6950 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 12:23:55.634  6950  6950 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 12:23:55.636  6950  6950 V BluetoothFtpService: Ftp Service onDestroy
08-30 12:23:55.636  6950  6950 V BluetoothFtpService: Ftp Service closeService
08-30 12:23:55.643  6950  6950 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:55.643  6950  6950 V BluetoothSapService: state: 13
08-30 12:23:55.643  6950  6950 V BluetoothSapService: Stopping SAP server process
08-30 12:23:55.644  6950  6950 V BluetoothSapService: Sap Service closeSapService in
08-30 12:23:55.644  6950  6950 V BluetoothSapService: Close listen Socket : 
08-30 12:23:55.644  6950  6950 V BluetoothSapService: Close rfcomm Socket : 
08-30 12:23:55.644  6950  6950 V BluetoothSapService: Close sapd  Socket : 
,08-30 12:23:55.648  6950  6950 V BluetoothSapService: Sap Service closeSapService out,
08-30 12:23:55.648  6950  6950 V BluetoothSapService: Sap Service onDestroy
08-30 12:23:55.648  6950  6950 V BluetoothSapService: Sap Service closeSapService in
08-30 12:23:55.648  6950  6950 V BluetoothSapService: Close listen Socket : 
08-30 12:23:55.648  6950  6950 V BluetoothSapService: Close rfcomm Socket : 
08-30 12:23:55.648  6950  6950 V BluetoothSapService: Close sapd  Socket : 
08-30 12:23:55.649  6950  6950 V BluetoothSapService: Sap Service closeSapService out
08-30 12:23:56.380  6950  7566 D bt_hci_bdroid: cleanup
,08-30 12:23:56.388  6950  7623 I bt_lpm  : LPM is already off!!!
08-30 12:23:56.389  6950  7661 I bt_userial_mct: exiting userial_read_thread
08-30 12:23:56.389  6950  7661 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 12:23:56.389  6950  7621 W bt-btif : ag scb idx 1 not allocated
08-30 12:23:56.389  6950  7621 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 12:23:56.389  6950  7621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 12:23:56.389  6950  7621 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:23:56.389  6950  7621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 12:23:56.389  6950  7621 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 12:23:56.389  6950  7621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 12:23:56.389  6950  7621 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-30 12:23:56.389  6950  7621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 12:23:56.389  6950  7621 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:23:56.389  6950  7621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 12:23:56.389  6950  7621 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 12:23:56.389  6950  7621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 12:23:56.389  6950  7621 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 12:23:56.389  6950  7621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 12:23:56.389  6950  7621 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 12:23:56.389  6950  7621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 12:23:56.390  6950  7621 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 12:23:56.390  6950  7621 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 12:23:56.390  6950  7621 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 12:23:56.390  6950  7621 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 12:23:56.390  6950  7566 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 12:23:56.391  6950  7623 I bt_vendor: hw_epilog_process
08-30 12:23:56.391  6950  7566 D bt_hci_bdroid: cleanup Finalizing cleanup
08-30 12:23:56.391  6950  7566 D bt_userial_mct: userial_close
08-30 12:23:56.391  6950  7566 E bt_userial_mct: pthread_join() FAILED result:3
08-30 12:23:56.391  6950  7566 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-30 12:23:56.396  6950  7566 D bt_hci_bdroid: set_power 0
08-30 12:23:56.396  6950  7566 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 12:23:56.396  6950  7566 I bt_vendor: bluetooth satus is on
08-30 12:23:56.396  6950  7566 I bt_vendor: bt-vendor : resetting BT status
08-30 12:23:56.396  6950  7566 I bt_vendor: Starting hciattach daemon
08-30 12:23:56.396  6950  7566 I bt_vendor: try to set false
08-30 12:23:56.400  6950  7566 I bt_vendor: Starting hciattach daemon
08-30 12:23:56.400  6950  7566 I bt_vendor: try to set false
,08-30 12:23:56.406  6950  7566 I bt_vendor: cleanup
08-30 12:23:56.406  6950  7621 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 12:23:56.407  6950  7566 I GKI_LINUX: GKI_exit_task 0 done
08-30 12:23:56.407  6950  7566 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 12:23:56.408  6950  7562 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 12:23:56.413  6950  6950 D HeadsetService: Received stop request...Stopping profile...
08-30 12:23:56.415  6950  6950 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 12:23:56.415  6950  6950 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 12:23:56.415  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3475c62d
,08-30 12:23:56.417  6950  7600 D HeadsetStateMachine: Exit Disconnected: -1
08-30 12:23:56.420  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-30 12:23:56.420  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-30 12:23:56.421  1850  1850 D BluetoothHeadset: Proxy object disconnected
08-30 12:23:56.422  1035  1035 D BluetoothHeadset: Proxy object disconnected
08-30 12:23:56.422  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 12:23:56.424  6950  6950 D A2dpService: Received stop request...Stopping profile...
08-30 12:23:56.424  6950  7610 D A2dpStateMachine: Exit Disconnected: -1
08-30 12:23:56.428  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-30 12:23:56.433  6950  7562 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 12:23:56.434  6950  6950 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-30 12:23:56.434  6950  6950 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 12:23:56.434  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3475c62d
08-30 12:23:56.436  1035  1035 D BluetoothA2dp: Proxy object disconnected
08-30 12:23:56.436  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 12:23:56.437  6950  6950 D HidService: Received stop request...Stopping profile...
08-30 12:23:56.437  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3475c62d
08-30 12:23:56.440  6950  6950 D HeadsetStateMachine: Unbinding service...
,08-30 12:23:56.443  6950  6950 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 12:23:56.443  6950  6950 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 12:23:56.444  6950  6950 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 12:23:56.444  6950  6950 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 12:23:56.444  6950  6950 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 12:23:56.444  6950  6950 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 12:23:56.444  6950  6950 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 12:23:56.446  6950  6950 D HealthService: Received stop request...Stopping profile...
08-30 12:23:56.446  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3475c62d
08-30 12:23:56.448  6950  6950 D PanService: Received stop request...Stopping profile...
08-30 12:23:56.448  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3475c62d
08-30 12:23:56.450  6950  6950 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 12:23:56.451  6950  6950 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 12:23:56.451  6950  6950 D BtGatt.GattService: stop()
08-30 12:23:56.451  6950  6950 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 12:23:56.452  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3475c62d
,08-30 12:23:56.456  6950  6950 D BluetoothMapService: Received stop request...Stopping profile...
08-30 12:23:56.456  6950  6950 D BluetoothMapService: stop()
08-30 12:23:56.456  6950  6950 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 12:23:56.457  6950  6950 D BluetoothMapEmailAppObserver: removeReceiver()
08-30 12:23:56.457  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3475c62d
08-30 12:23:56.458  6950  6950 I BluetoothA2dpServiceJni: cleanupNative
08-30 12:23:56.459  6950  7611 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 12:23:56.459  6950  6950 I GKI_LINUX: GKI_exit_task 2 done
08-30 12:23:56.459  6950  6950 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 12:23:56.459  6950  6950 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 12:23:56.459  6950  6950 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 12:23:56.460  6950  6950 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 12:23:56.460  6950  6950 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 12:23:56.460  6950  6950 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 12:23:56.460  6950  6950 V BluetoothMapService: Handler(): got msg=4
08-30 12:23:56.460  6950  6950 D BluetoothMapService: MAP Service closeService in
08-30 12:23:56.460  6950  6950 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 12:23:56.460  6950  6950 V BluetoothMapService: MAP Service closeService out
08-30 12:23:56.462  6950  7562 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 12:23:56.463  6950  7562 D BluetoothAdapterProperties: Setting state to 10
08-30 12:23:56.463  6950  7562 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 12:23:56.465  1035  1117 D BluetoothManagerService: Message: 60
08-30 12:23:56.465  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 12:23:56.465  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-30 12:23:56.465  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 12:23:56.469  6950  6950 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 12:23:56.469  6950  6950 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 12:23:56.471  6950  6950 D BluetoothMapService: cleanup()
08-30 12:23:56.471  6950  6950 D BluetoothMapService: MAP Service closeService in
08-30 12:23:56.471  6950  6950 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 12:23:56.471  6950  6950 V BluetoothMapService: MAP Service closeService out
08-30 12:23:56.472  6950  7562 I BluetoothAdapterState: Entering OffState
08-30 12:23:56.472  6850  6949 D BluetoothMap: onBluetoothStateChange: up=false
08-30 12:23:56.473  6850  6949 D BluetoothPan: onBluetoothStateChange on: false
08-30 12:23:56.478  6850  6949 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 12:23:56.480  6850  6949 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 12:23:56.481  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:23:56.481  1850  3505 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:23:56.482  6850  6949 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 12:23:56.482  6850  6949 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:23:56.483  1850  1866 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:23:56.484  1850  3506 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 12:23:56.485  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 12:23:56.485  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 12:23:56.487  1035  1117 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 12:23:56.487  1035  1117 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 12:23:56.487  1035  1117 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3a82fdff mBinding = false
08-30 12:23:56.488  1035  1117 D BluetoothManagerService: Sending unbind request.
08-30 12:23:56.493  6950  7566 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-30 12:23:56.496  6950  6950 I GKI_LINUX: GKI_exit_task 1 done
08-30 12:23:56.496  6950  6950 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 12:23:56.496  6950  6950 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 12:23:56.496  6950  6950 I art     : --- WEIRD: removing null entry 248
08-30 12:23:56.496  6950  6950 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-30 12:23:56.497  6950  6950 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-30 12:23:56.498  6950  6950 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-30 12:23:56.500  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-30 12:23:56.502  6950  6950 I art     : System.exit called, status: 0
08-30 12:23:56.502  6950  6950 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 12:23:56.521   322  2133 V AudioFlinger: 6950 died, releasing its sessions
08-30 12:23:56.521   322  2133 V AudioFlinger:  pid 1850 @ 0
08-30 12:23:56.521   322  2133 V AudioFlinger:  pid 3415 @ 1
08-30 12:23:56.521   322  2133 V AudioFlinger:  pid 3415 @ 2
,08-30 12:23:56.528  1939  1939 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-30 12:23:56.528  1939  2123 D LGBluetoothAPIService: Message: 101
08-30 12:23:56.528  1939  2123 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-30 12:23:56.529  1939  2123 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-30 12:23:56.529  1939  2123 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-30 12:23:56.533  6850  6850 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-30 12:23:56.666  1035  1725 I ActivityManager: Process com.android.bluetooth (pid 6950) has died
08-30 12:23:56.667  1035  1725 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-30 12:23:56.667  1035  1725 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,08-30 12:23:56.682  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-30 12:23:56.687  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:56.687  1939  2123 D LGBluetoothAPIService: Message: 2
08-30 12:23:56.687  1939  2123 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-30 12:23:56.689  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:56.691  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:56.692  6850  6850 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 12:23:56.692  6850  6850 D LGBluetoothEventManager: [BTUI] clear device connection state
08-30 12:23:56.692  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:23:56.695  6850  6850 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 12:23:56.699  1601  1601 D BluetoothAdapter: 292588892: getState() :  mService = null. Returning STATE_OFF
08-30 12:23:56.699  1601  1601 D BluetoothAdapter: 292588892: getState() :  mService = null. Returning STATE_OFF
,08-30 12:23:56.764  1035  1885 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7946 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-30 12:23:56.766  6850  6850 D DockEventReceiver: finishStartingService: stopping service
,08-30 12:23:56.859  7946  7946 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-30 12:23:56.859  7946  7946 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 12:23:56.860  7946  7946 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-30 12:23:56.860  7946  7946 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 12:23:56.882  7946  7946 D BluetoothAdapterApp: Loading JNI Library
,08-30 12:23:56.918  7946  7946 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1aa25d75 Instance Count = 1
,08-30 12:23:56.925  7946  7946 D BluetoothAdapterApp: onCreate
,08-30 12:23:56.954  7946  7946 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-30 12:23:56.954  7946  7946 D ProfileConfigQcom: Adding HeadsetService
08-30 12:23:56.955  7946  7946 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-30 12:23:56.955  7946  7946 D ProfileConfigQcom: Adding A2dpService
08-30 12:23:56.956  7946  7946 D ProfileConfigQcom: [BTUI] HidService is supported
08-30 12:23:56.956  7946  7946 D ProfileConfigQcom: Adding HidService
08-30 12:23:56.957  7946  7946 D ProfileConfigQcom: [BTUI] HealthService is supported
08-30 12:23:56.958  7946  7946 D ProfileConfigQcom: Adding HealthService
08-30 12:23:56.958  7946  7946 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-30 12:23:56.960  7946  7946 D ProfileConfigQcom: [BTUI] PanService is supported
08-30 12:23:56.961  7946  7946 D ProfileConfigQcom: Adding PanService
08-30 12:23:56.961  7946  7946 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 12:23:56.962  7946  7946 D ProfileConfigQcom: Adding GattService
08-30 12:23:56.962  7946  7946 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-30 12:23:56.963  7946  7946 D ProfileConfigQcom: Adding BluetoothMapService
08-30 12:23:56.964  7946  7946 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 12:23:56.966  7946  7946 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 12:23:56.967  7946  7946 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:56.968  7946  7946 V BluetoothPbapReceiver: ***********state = 10
,08-30 12:23:56.970  7946  7946 V LGMDMManagerInternal: Create singleton instance
08-30 12:23:57.078  2205  2205 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 12:23:57.081  6850  6850 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 12:23:57.082  7946  7946 D LGBluetoothAPIServer: [BTUI] onCreate()
08-30 12:23:57.083  7946  7946 D LGBluetoothAPIServer: [BTUI] onBind()
08-30 12:23:57.084  1939  1939 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-30 12:23:57.084  1939  2123 D LGBluetoothAPIService: Message: 100
08-30 12:23:57.084  1939  2123 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-30 12:23:57.103  6850  6850 D BluetoothPermissionRequest: onReceive
,08-30 12:23:57.107  6850  6850 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 12:23:57.107  6850  6850 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-30 12:23:57.109  6850  6850 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 12:23:57.114  7946  7946 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-30 12:23:57.117  7946  7946 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-30 12:23:57.121  7946  7946 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 12:23:57.122  7946  7946 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 12:23:57.122  7946  7946 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 12:23:57.123  7946  7946 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:23:57.123  7946  7946 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-30 12:23:57.131  7630  7630 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-30 12:24:00.048  1601  1601 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-30 12:24:00.048  1601  1601 I KeyguardUpdateMonitor: called onTimeUpdated()
08-30 12:24:00.048  1601  1601 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-30 12:24:00.049  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
,08-30 12:24:00.063  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-30 12:24:00.063  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-30 12:24:00.068  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-30 12:24:00.069  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
,08-30 12:24:00.513  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 12:24:00.513  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:24:00.524  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:24:00.525  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@174366d removed from the list
08-30 12:24:00.525  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:24:00.525  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:24:00.525  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:24:00.528  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:24:00.528  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@203dfb33 added. We now have 4 listener(s)
08-30 12:24:00.528  6741  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:24:00.531  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:24:00.531  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@203dfb33 removed from the list
08-30 12:24:00.531  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:24:00.531  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:24:00.531  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:24:00.531  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:24:00.532  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@195faef0 added. We now have 4 listener(s)
08-30 12:24:00.532  6741  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:24:00.535  1035  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 12:24:00.535  1035  1885 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-30 12:24:00.536  1035  1117 D BluetoothManagerService: Message: 2
08-30 12:24:03.037  1035  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=290167141, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,08-30 12:24:03.049  1035  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3dac012a type 2 when 360262 com.google.android.gms} when 360262
08-30 12:24:03.058   316  7977 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-30 12:24:03.066  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 12:24:03.080  2575  2575 D [Concierge]Service: onStartCommand(). Type : 9
,08-30 12:24:03.108  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=290167141 [*alarm*], flags=0x0
,08-30 12:24:05.543  6741  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:24:05.550  1035  1884 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:24:05.551  1035  1884 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-30 12:24:05.574  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 12:24:05.574  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 12:24:05.574  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-30 12:24:05.575  1035  1117 D BluetoothManagerService: Message: 1
08-30 12:24:05.575  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-30 12:24:05.601  1035  1117 D BluetoothManagerService: Message: 20
08-30 12:24:05.602  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2964adf7:true
,08-30 12:24:05.606  7946  7946 D BluetoothAdapterState: make
08-30 12:24:05.610  7946  7946 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 12:24:05.611  7946  7946 I bluedroid-qcom: init
08-30 12:24:05.612  7946  7980 I BluetoothAdapterState: Entering OffState
08-30 12:24:05.612  7946  7946 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 12:24:05.612  7946  7946 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 12:24:05.613  7946  7946 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 12:24:05.613  7946  7946 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 12:24:05.613  7946  7946 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 12:24:05.615  7946  7946 I bluedroid-qcom: get_profile_interface socket
08-30 12:24:05.615  7946  7946 I bluedroid-qcom: get_profile_interface map_client
,08-30 12:24:05.607  7983  7983 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:24:05.621  7946  7984 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 12:24:05.623  7946  7984 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 12:24:05.607  7983  7983 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:24:05.633  7983  7983 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 12:24:05.633  7983  7983 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 12:24:05.633  7983  7983 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-30 12:24:05.637  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 12:24:05.637  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 12:24:05.640  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-30 12:24:05.641  1035  1117 D BluetoothManagerService: Message: 40
08-30 12:24:05.641  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 12:24:05.641  7946  7961 I bluedroid-qcom: config_hci_snoop_log
08-30 12:24:05.643  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 12:24:05.643  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 12:24:05.643  7946  7984 D BluetoothAdapterProperties: Name is: G3
08-30 12:24:05.644  7983  7983 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-30 12:24:05.650  7983  7983 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 12:24:05.650  7983  7983 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-30 12:24:05.656  7946  7980 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-30 12:24:05.656  7946  7980 D BluetoothAdapterProperties: Setting state to 11
08-30 12:24:05.657  7946  7980 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 12:24:05.658  7946  7980 I LGBluetoothServiceJni: classInitNative: succeeds
08-30 12:24:05.661  1035  1117 D BluetoothManagerService: Message: 60
08-30 12:24:05.662  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 12:24:05.662  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-30 12:24:05.666  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 12:24:05.669  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 12:24:05.672  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:24:05.673  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:24:05.675  6850  6850 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-30 12:24:05.682  7946  7946 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 12:24:05.682  7946  7946 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:24:05.682  7946  7946 V BluetoothPbapReceiver: ***********state = 11
,08-30 12:24:05.692  2205  2205 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 12:24:05.704  7946  7980 D BluetoothBondStateMachine: make
,08-30 12:24:05.712  7946  7997 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 12:24:05.712  7946  7980 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c554762
08-30 12:24:05.713  7946  7980 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 12:24:05.713  7946  7980 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c554762
08-30 12:24:05.713  7946  7980 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-30 12:24:05.714  7946  7980 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-30 12:24:05.724  6850  6850 D BluetoothPermissionRequest: onReceive
,08-30 12:24:05.726  7946  7980 E BluetoothAdapterService: File transfer profiles supported!!
08-30 12:24:05.729  6850  6850 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 12:24:05.740  7946  7946 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-30 12:24:05.744  7946  7980 E BluetoothAdapterService: File transfer profiles supported!!
08-30 12:24:05.744  7946  7946 D HeadsetService: Received start request. Starting profile...
08-30 12:24:05.745  7946  7946 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 12:24:05.745  7946  7946 D LGBluetoothHfpAdapter: Version 1.6
08-30 12:24:05.748  7946  7946 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 12:24:05.750  7946  7946 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 12:24:05.750  7946  7946 D HeadsetStateMachine: make
08-30 12:24:05.751  7946  7980 E BluetoothAdapterService: File transfer profiles supported!!
08-30 12:24:05.765  7946  7980 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 12:24:05.773  7946  7980 E BluetoothAdapterService: File transfer profiles supported!!
08-30 12:24:05.780  7946  7980 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 12:24:05.792  7946  7980 E BluetoothAdapterService: File transfer profiles supported!!
08-30 12:24:05.803  7946  7946 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:24:05.803  7946  7946 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:24:05.810  7946  7946 D HeadsetStateMachine: max_hf_connections = 1
08-30 12:24:05.810  7946  7946 I bluedroid-qcom: get_profile_interface handsfree
08-30 12:24:05.812  7946  7946 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-30 12:24:05.813   322  1397 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 1002
08-30 12:24:05.814   322  2133 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 12:24:05.814   322  2133 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 12:24:05.814   322  2133 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 12:24:05.814  7946  7946 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 12:24:05.815  7946  7980 V LGMDMManager: Create singleton instance
08-30 12:24:05.816   322   322 V AudioFlinger: registerClient() client 0xb1433298, pid 7946
,08-30 12:24:05.818   322  1391 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 12:24:05.818   322  1391 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 12:24:05.819  7946  7980 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 12:24:05.819   322  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 12:24:05.819   322  1392 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 12:24:05.819  1850  3952 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 12:24:05.819  1850  3952 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 12:24:05.820  1850  3952 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 12:24:05.820  1850  3952 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 12:24:05.820  1601  2075 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 12:24:05.820  7946  7961 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 12:24:05.820  1601  2075 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 12:24:05.820  7946  7961 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 12:24:05.820  1035  1956 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 12:24:05.820  1035  1956 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 12:24:05.820  7946  7961 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 12:24:05.820  7946  7961 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 12:24:05.820  1035  1956 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 12:24:05.820  1601  2075 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 12:24:05.820  1035  1956 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 12:24:05.820  1601  2075 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 12:24:05.820  7946  7946 V ToneGenerator: Create Track: 0xb4928a80
08-30 12:24:05.821  7946  7946 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 12:24:05.821  7946  7946 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 12:24:05.821   322  1396 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 12:24:05.821   322  1396 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 12:24:05.821   322  1396 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 12:24:05.821   322  1396 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 12:24:05.821  3415  3430 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 12:24:05.821  3415  3430 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 12:24:05.821  3415  3430 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 12:24:05.821  3415  3430 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 12:24:05.821   322  1397 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 12:24:05.822   322  2133 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 12:24:05.822   322  2133 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-30 12:24:05.822   322  2133 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 12:24:05.822   322  2133 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 12:24:05.822  7946  7946 V AudioSystem: getLatency() output 2, latency 50
08-30 12:24:05.822  7946  7946 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 12:24:05.822  7946  7946 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 12:24:05.822   322   322 V AudioFlinger: [MABL_AudioFlinger] PlaybackThrea,d::setMABLEnable(), enable = 0 
08-30 12:24:05.822   322   322 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 12:24:05.822   322   322 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 12:24:05.822   322   322 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 12:24:05.822   322   322 V AudioFlinger: createTrack() lSessionId: 23
08-30 12:24:05.823  7946  7946 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 12:24:05.824   322   322 V AudioFlinger: acquiring 23 from 7946, for 7946
08-30 12:24:05.824   322   322 V AudioFlinger:  added new entry for 23
08-30 12:24:05.824  7946  7946 V ToneGenerator: ToneGenerator INIT OK, time: 363068
08-30 12:24:05.824  7946  7946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c554762
08-30 12:24:05.825  7946  8002 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 12:24:05.826  7946  8002 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 12:24:05.826  7946  7946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c554762
08-30 12:24:05.826  7946  8002 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 12:24:05.827  7946  7946 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 12:24:05.827  7946  7946 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 12:24:05.827  7946  7946 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 12:24:05.827  7946  7946 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:24:05.827  7946  7946 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-30 12:24:05.827  7946  8002 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 12:24:05.827   322  2132 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7946
08-30 12:24:05.830  7946  7946 D A2dpService: Received start request. Starting profile...
08-30 12:24:05.830   322  2132 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 12:24:05.830   322  2132 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 12:24:05.830   322  2132 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 12:24:05.830   322  2132 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 12:24:05.830   322  2132 V voice   : voice_set_parameters: exit with code(0)
08-30 12:24:05.830   322  2132 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 12:24:05.830   322  2132 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 12:24:05.831   322  2132 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 12:24:05.831  7946  7946 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 12:24:05.831   322  2132 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 12:24:05.831   322  2132 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 12:24:05.831   322  2132 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 12:24:05.832  7946  7946 V Avrcp   : make
08-30 12:24:05.832  7946  8002 V ToneGenerator: ToneGenerator destructor
08-30 12:24:05.832  7946  8002 V ToneGenerator: stopTone
08-30 12:24:05.832  7946  8002 V ToneGenerator: Delete Track: 0xb4928a80
08-30 12:24:05.833  7946  7946 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 12:24:05.833  7946  7946 I bluedroid-qcom: get_profile_interface avrcp
08-30 12:24:05.834   322  1396 V AudioPolicyService: AudioCommandThread() adding release output 2
,08-30 12:24:05.835   322  1396 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 12:24:05.835   322  1270 V AudioPolicyService: AudioCommandThread() waking up
08-30 12:24:05.835   322  1270 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 12:24:05.835   322  1270 V AudioPolicyManager: releaseOutput() 2
08-30 12:24:05.835   322  1270 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 12:24:05.835   322  1396 V AudioFlinger: PlaybackThread::Track destructor
08-30 12:24:05.835   322  1396 V AudioFlinger: removeClient_l() pid 7946, calling pid 322
,08-30 12:24:05.837  7946  8002 V AudioTrack: ~AudioTrack, releasing session id from 7946 on behalf of 7946
08-30 12:24:05.838   322  2132 V AudioFlinger: releasing 23 from 7946 for 7946
08-30 12:24:05.838   322  2132 V AudioFlinger:  decremented refcount to 0
08-30 12:24:05.838   322  2132 V AudioFlinger: purging stale effects
08-30 12:24:05.847  7946  7946 V AudioManager: registerRemoteController: size of Media player list: 0
08-30 12:24:05.849  7946  7946 E AudioManager: No RCC entry present to update
08-30 12:24:05.849  7946  7946 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 12:24:05.853  7946  7946 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-30 12:24:05.855  7946  7946 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 12:24:05.855  7946  7946 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-30 12:24:05.860  7946  7946 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 12:24:05.994  1035  1051 V SIM_STK : Menu title from STK is T-Mobile
08-30 12:24:05.995  1035  1051 V SIM_STK : Menu title from STK is T-Mobile
,08-30 12:24:06.134  1035  1938 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-30 12:24:06.147  7946  7946 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-30 12:24:06.154  7946  7946 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 12:24:06.161  7946  7946 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 12:24:06.161  7946  7946 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 12:24:06.161  7946  7946 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 12:24:06.161  7946  7946 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 12:24:06.161  7946  7946 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 12:24:06.161  7946  7946 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 12:24:06.161  7946  7946 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 12:24:06.161  7946  7946 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 12:24:06.161  7946  7946 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 12:24:06.162  7946  7946 I BluetoothA2dpServiceJni: classInitNative
08-30 12:24:06.162  7946  7946 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 12:24:06.162  7946  7946 D A2dpStateMachine: make
,08-30 12:24:06.166  7946  7946 I bluedroid-qcom: get_profile_interface a2dp
08-30 12:24:06.167  7946  8014 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 12:24:06.173  7946  7946 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 12:24:06.174  7946  7946 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,08-30 12:24:06.177  7946  7946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c554762
08-30 12:24:06.177  7946  8013 D A2dpStateMachine: Enter Disconnected: -2
08-30 12:24:06.179  7946  7946 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 12:24:06.181  7946  7946 D HidService: Received start request. Starting profile...
08-30 12:24:06.181  7946  7946 I bluedroid-qcom: get_profile_interface hidhost
08-30 12:24:06.181  7946  7946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c554762
08-30 12:24:06.182  7946  7946 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 12:24:06.184  7946  7946 D HealthService: Received start request. Starting profile...
08-30 12:24:06.186  7946  7946 I bluedroid-qcom: get_profile_interface health
08-30 12:24:06.186  7946  7946 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 12:24:06.186  7946  7946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c554762
,08-30 12:24:06.188  7946  7946 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 12:24:06.190  7946  7946 D PanService: Received start request. Starting profile...
08-30 12:24:06.190  7946  7946 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 12:24:06.190  7946  7946 I bluedroid-qcom: get_profile_interface pan
08-30 12:24:06.196  7946  7946 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-30 12:24:06.197  7946  7946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c554762
08-30 12:24:06.198  7946  7946 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-30 12:24:06.204  7946  7946 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 12:24:06.204  7946  7946 D BtGatt.GattService: Received start request. Starting profile...
08-30 12:24:06.204  7946  7946 D BtGatt.GattService: start()
08-30 12:24:06.204  7946  7946 I bluedroid-qcom: get_profile_interface gatt
08-30 12:24:06.205  7946  7946 D BtGatt.AdvertiseManager: advertise manager created
08-30 12:24:06.210  7946  7946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c554762
,08-30 12:24:06.212  7946  7946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c554762
08-30 12:24:06.213  7946  7946 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-30 12:24:06.214  7946  7946 V BluetoothMapService: BluetoothMapBinder()
08-30 12:24:06.215  7946  7946 D BluetoothMapService: Received start request. Starting profile...
08-30 12:24:06.215  7946  7946 D BluetoothMapService: start()
08-30 12:24:06.218  7946  7946 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-30 12:24:06.218  7946  7946 D BluetoothMapEmailAppObserver: createReceiver()
08-30 12:24:06.219  7946  7946 D BluetoothMapEmailAppObserver: initObservers()
08-30 12:24:06.220  7946  7946 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 12:24:06.228  7946  7946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c554762
,08-30 12:24:06.229  7946  7946 D HeadsetStateMachine: Proxy object connected
08-30 12:24:06.229  7946  7946 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 12:24:06.230  7946  7946 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-30 12:24:06.236  7946  7946 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 12:24:06.237  7946  8002 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 12:24:06.238  7946  8002 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 12:24:06.238  7946  8002 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-30 12:24:06.240  7946  7946 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 12:24:06.243  7946  7946 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 12:24:06.246  7946  7946 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 12:24:06.246  7946  7946 V PanService: [BTUI] SIM Extra State :ABSENT
08-30 12:24:06.249  7946  7946 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 12:24:06.252  7946  7946 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-30 12:24:06.252  7946  7946 V BluetoothMapService: Handler(): got msg=1
,08-30 12:24:06.253  7946  7980 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 12:24:06.253  7946  7980 I bluedroid-qcom: enable
08-30 12:24:06.254  7946  7980 I bt_hci_bdroid: init
08-30 12:24:06.255  7946  7980 I bt_vendor: bt-vendor : init
08-30 12:24:06.255  7946  7980 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 12:24:06.255  7946  7980 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 12:24:06.255  7946  7980 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 12:24:06.255  7946  7980 D bt_userial_mct: userial_init
08-30 12:24:06.256  7946  7980 D bt_hci_bdroid: set_power 1
08-30 12:24:06.256  7946  7980 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 12:24:06.256  7946  7980 I bt_vendor: Starting hciattach daemon
08-30 12:24:06.256  7946  7980 I bt_vendor: try to set true
08-30 12:24:06.258  7946  8021 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 12:24:06.258  7946  8021 I bt-btu  : btu_task pending for preload complete event
08-30 12:24:06.246  8024  8024 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:24:06.246  8024  8024 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 12:24:06.296  8025  8025 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 12:24:06.377  8031  8031 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 12:24:06.392  8032  8032 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-30 12:24:06.419  8034  8034 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 12:24:06.432  8035  8035 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-30 12:24:06.456  8036  8036 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 12:24:06.468  8037  8037 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-30 12:24:06.489  8039  8039 I libmdmdetect: ESOC framework not supported
08-30 12:24:06.490  8039  8039 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-30 12:24:06.497  8039  8039 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-30 12:24:06.497  8039  8039 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-30 12:24:06.498  8039  8039 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-30 12:24:06.498  8039  8039 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-30 12:24:06.498  8039  8039 D bthci_qcomm_common: [BTUI]     LE: Class 2
,08-30 12:24:06.498  8039  8039 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-30 12:24:06.498  8039  8039 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-30 12:24:06.538  8039  8040 E QC-QMI  : qmi_client [8039] 15: failed to locate client data
,08-30 12:24:06.550   484   484 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-30 12:24:06.550   484   484 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-30 12:24:06.572  8044  8044 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 12:24:06.588  8045  8045 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 12:24:06.612  7946  7980 I bt_vendor: bluetooth satus is on
08-30 12:24:06.612  7946  7980 D bt_hci_bdroid: preload
,08-30 12:24:06.615  7946  8023 D bt_userial_mct: userial_open(port:0)
08-30 12:24:06.615  7946  8023 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-30 12:24:06.619  7946  8023 I bt_vendor: Done intiailizing UART
08-30 12:24:06.620  7946  8023 I bt_vendor: Done intiailizing UART
08-30 12:24:06.620  7946  8023 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 12:24:06.620  7946  8023 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-30 12:24:06.621  7946  8021 I bt-btu  : btu_task received preload complete event
08-30 12:24:06.621  7946  8021 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-30 12:24:06.621  7946  8021 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-30 12:24:06.623  7946  8021 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-30 12:24:06.626  7946  8047 D bt_userial_mct: Entering userial_read_thread()
,08-30 12:24:06.631  7946  8021 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 12:24:06.631  7946  8021 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-30 12:24:06.631  7946  8021 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 12:24:06.631  7946  8021 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 12:24:06.631  7946  8021 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 12:24:06.631  7946  8021 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 12:24:06.631  7946  8021 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-30 12:24:06.631  7946  8021 I         : BTE_InitTraceLevels -- TRC_BTM,
08-30 12:24:06.631  7946  8021 I         : BTE_InitTraceLevels -- TRC_HID_HOST,
08-30 12:24:06.631  7946  8021 I         : BTE_InitTraceLevels -- TRC_GAP,
08-30 12:24:06.631  7946  8021 I         : BTE_InitTraceLevels -- TRC_PAN,
08-30 12:24:06.631  7946  8021 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 12:24:06.631  7946  8021 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 12:24:06.631  7946  8021 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 12:24:06.631  7946  8021 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 12:24:06.631  7946  8021 I         : BTE_InitTraceLevels -- TRC_BTIF
08-30 12:24:06.731  7946  8021 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-30 12:24:06.731  7946  8021 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa018e061 ,
,08-30 12:24:06.731  7946  8021 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa018e061 ,
,08-30 12:24:06.773  7946  7984 E bt-btif : Calling BTA_HhEnable
08-30 12:24:06.773  7946  7984 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-30 12:24:06.773  7946  7984 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-30 12:24:06.778  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 12:24:06.778  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 12:24:06.778  7946  8021 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-30 12:24:06.778  7946  8021 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-30 12:24:06.778  7946  8021 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 12:24:06.779  7946  8021 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 12:24:06.779  7946  8021 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-30 12:24:06.779  7946  7984 D BluetoothAdapterProperties: Name is: G3
08-30 12:24:06.780  7946  7984 D BluetoothAdapterProperties: Scan Mode:20
08-30 12:24:06.780  7946  7984 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 12:24:06.781  7946  7984 D bt_hci_bdroid: postload
08-30 12:24:06.781  7946  8023 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 12:24:06.782  7946  8021 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 12:24:06.782  7946  8023 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 12:24:06.783  7946  7984 D bte_conf: Device ID record 1 : primary
08-30 12:24:06.783  7946  7984 D bte_conf:   vendorId            = 00c4
08-30 12:24:06.783  7946  7984 D bte_conf:   vendorIdSource      = 0001
08-30 12:24:06.783  7946  7984 D bte_conf:   product             = 13a1
08-30 12:24:06.783  7946  7984 D bte_conf:   version             = 1000
08-30 12:24:06.783  7946  7984 D bte_conf:   clientExecutableURL = 
08-30 12:24:06.783  7946  7984 D bte_conf:   serviceDescription  = 
08-30 12:24:06.783  7946  7984 D bte_conf:   documentationURL    = 
08-30 12:24:06.783  7946  7984 D bte_conf: bte_load_did_conf no section named DID2.
08-30 12:24:06.784  7946  8023 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 12:24:06.786  7946  8023 D bt_hci_bdroid: Used up Tx Cmd credits
,08-30 12:24:06.792  7946  8047 E bt_mct  : hci lib postload completed
08-30 12:24:06.792  7946  7980 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 12:24:06.793  7946  7980 D BluetoothAdapterProperties: ScanMode =  20
08-30 12:24:06.793  7946  7980 D BluetoothAdapterProperties: State =  11
08-30 12:24:06.793  7946  7980 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 12:24:06.793  7946  7980 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-30 12:24:06.793  7946  7980 D BluetoothAdapterProperties: Setting state to 12
08-30 12:24:06.793  7946  7980 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 12:24:06.794  7946  7984 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 12:24:06.794  7946  7984 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 12:24:06.786  8049  8049 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:24:06.786  8049  8049 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:24:06.800  1035  1117 D BluetoothManagerService: Message: 60
08-30 12:24:06.800  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 12:24:06.800  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-30 12:24:06.800  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 12:24:06.807  7946  8021 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 12:24:06.807  7946  8021 W bt-smp  : Plain text(LSB ~ MSB) = 46 20 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 12:24:06.807  7946  8021 W bt-smp  : Encrypted text(LSB ~ MSB) = e8 ed e2 ae 7d 2c 27 6c f9 77 74 9a e1 04 73 cc 
08-30 12:24:06.807  7946  8021 W bt-btm  : Stopping oneshot timer
08-30 12:24:06.823  7946  7980 I BluetoothAdapterState: Entering On State
,08-30 12:24:06.830  7946  8021 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 12:24:06.830  7946  8021 W bt-smp  : Plain text(LSB ~ MSB) = b2 84 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 12:24:06.830  7946  8021 W bt-smp  : Encrypted text(LSB ~ MSB) = d1 ee a2 c5 f4 b5 0b 21 cd 40 94 83 c9 bb ac ac 
08-30 12:24:06.830  7946  8021 W bt-btm  : Stopping oneshot timer
08-30 12:24:06.831  7946  7984 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 12:24:06.831  7946  7984 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-30 12:24:06.846  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:24:06.846  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:24:06.846  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:24:06.846  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:24:06.846  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:24:06.846  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:24:06.846  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:24:06.846  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:24:06.849  7946  8021 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 12:24:06.849  7946  8021 W bt-smp  : Plain text(LSB ~ MSB) = 4c c8 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 12:24:06.849  7946  8021 W bt-smp  : Encrypted text(LSB ~ MSB) = 73 1c cb 22 cd ec 11 cf 9c 27 e1 31 c2 b7 ca 7b 
08-30 12:24:06.849  7946  8021 W bt-btm  : Stopping oneshot timer
08-30 12:24:06.857  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:24:06.866  7946  8021 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 12:24:06.866  7946  8021 W bt-smp  : Plain text(LSB ~ MSB) = cb 8c 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 12:24:06.866  7946  8021 W bt-smp  : Encrypted text(LSB ~ MSB) = 19 c9 a6 fb 56 85 c4 a5 34 94 14 2f 79 02 5c 9d 
,08-30 12:24:06.868  7946  8021 W bt-btm  : Stopping oneshot timer
08-30 12:24:06.870  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:24:06.870  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:24:06.870  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:24:06.870  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:24:06.870  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:24:06.870  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:24:06.870  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:24:06.870  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:24:06.880  7946  7980 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 12:24:06.880  7946  7980 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 12:24:06.880  7946  7980 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-30 12:24:06.883  7946  7980 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-30 12:24:06.884  7946  7980 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-30 12:24:06.885  1035  1035 D BluetoothA2dp: Proxy object connected
08-30 12:24:06.891  7946  8021 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 12:24:06.891  7946  8021 W bt-smp  : Plain text(LSB ~ MSB) = 6c 86 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 12:24:06.892  7946  8021 W bt-smp  : Encrypted text(LSB ~ MSB) = e5 ff cc fc 18 87 2a 49 d4 95 7c a8 83 92 37 3e 
08-30 12:24:06.892  7946  8021 W bt-btm  : Stopping oneshot timer
,08-30 12:24:06.917  6850  6875 D BluetoothMap: onBluetoothStateChange: up=true
08-30 12:24:06.918  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:24:06.925  6850  6850 D BluetoothMap: Proxy object connected
,08-30 12:24:06.925  6850  6871 D BluetoothPan: onBluetoothStateChange on: true
08-30 12:24:06.926  6850  6871 D BluetoothPan: onBluetoothStateChange call bindService
08-30 12:24:06.925  6850  6850 D MapProfile: Bluetooth service connected
08-30 12:24:06.926  6850  6850 D BluetoothMap: getConnectedDevices()
08-30 12:24:06.927  7946  7961 V BluetoothMapService: getConnectedDevices()
08-30 12:24:06.930  6850  6875 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 12:24:06.932  6850  6875 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 12:24:06.935  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:24:06.937  1850  1866 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:24:06.937  1035  1035 D BluetoothHeadset: Proxy object connected
08-30 12:24:06.939  1850  1850 D BluetoothHeadset: Proxy object connected
08-30 12:24:06.939  8071  8071 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-30 12:24:06.939  6850  6949 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 12:24:06.939  6850  6850 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 12:24:06.939  6850  6850 D PanProfile: Bluetooth service connected
08-30 12:24:06.943  6850  6875 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 12:24:06.943  6850  6850 D BluetoothA2dp: Proxy object connected
08-30 12:24:06.943  6850  6850 D A2dpProfile: Bluetooth service connected
08-30 12:24:06.945  6850  6850 D BluetoothInputDevice: Proxy object connected
08-30 12:24:06.945  6850  6850 D HidProfile: Bluetooth service connected
08-30 12:24:06.945  1850  1865 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 12:24:06.956  6850  6850 D BluetoothHeadset: Proxy object connected
08-30 12:24:06.956  6850  6850 D HeadsetProfile: Bluetooth service connected
08-30 12:24:07.057  1035  1117 I art     : Explicit concurrent mark sweep GC freed 28580(1398KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.644ms total 109.879ms
08-30 12:24:07.058  1850  1850 D BluetoothHeadset: Proxy object connected
08-30 12:24:07.058  1850  2397 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 12:24:07.060  1850  1850 D BluetoothHeadset: Proxy object connected
08-30 12:24:07.060  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-30 12:24:07.061  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-30 12:24:07.062  1939  1939 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:24:07.063  1939  2123 D LGBluetoothAPIService: Message: 1
08-30 12:24:07.063  1939  2123 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-30 12:24:07.063  1939  2123 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-30 12:24:07.063  1939  2123 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-30 12:24:07.064  1601  1601 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 12:24:07.066  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-30 12:24:07.067  1035  1117 D BluetoothManagerService: Message: 40
08-30 12:24:07.067  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 12:24:07.070  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:24:07.075  7946  7946 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:24:07.075  7946  7946 D BluetoothMapService: STATE_ON
,08-30 12:24:07.076  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:24:07.077  6850  6850 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-30 12:24:07.079  6850  6850 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 12:24:07.084  7946  7946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c554762
08-30 12:24:07.084  7946  7946 V BluetoothPbapService: Pbap Service onCreate
08-30 12:24:07.084  7946  7946 V BluetoothPbapService: Starting PBAP service
08-30 12:24:07.085  7946  7946 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 12:24:07.085  7946  7946 V BluetoothPbapService: Pbap Service onBind
,08-30 12:24:07.086  7946  7946 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:24:07.086  7946  7946 V BluetoothPbapService: state: 12
08-30 12:24:07.086  7946  7946 V BluetoothMapService: Handler(): got msg=1
08-30 12:24:07.087  6850  6850 D DockEventReceiver: finishStartingService: stopping service
08-30 12:24:07.087  7946  7946 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 12:24:07.087  7946  7946 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 12:24:07.087  7946  7946 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:24:07.087  7946  7946 V BluetoothPbapReceiver: ***********state = 12
08-30 12:24:07.088  6850  6850 D BluetoothPbap: Proxy object connected
08-30 12:24:07.088  6850  6850 D PbapServerProfile: Bluetooth service connected
08-30 12:24:07.088  7946  8075 D BluetoothMapMasInstance: MAS initSocket()
08-30 12:24:07.089  7946  8075 D BluetoothMapMasInstance:   masId = 00
08-30 12:24:07.089  7946  8075 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 12:24:07.089  7946  8075 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 12:24:07.089  7946  8075 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 12:24:07.089  7946  7946 V BluetoothPbapService: Handler(): got msg=1
08-30 12:24:07.089  7946  7946 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-30 12:24:07.091  7946  8076 V BluetoothPbapService: Pbap Service initSocket
08-30 12:24:07.092  1035  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:24:07.092  1035  1884 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:24:07.093  7946  8075 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:24:07.093  2205  2205 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 12:24:07.094  2205  2205 D c       : Getting all permits...
08-30 12:24:07.094  2205  2205 D a       : Opening database...
08-30 12:24:07.094  7946  8075 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-30 12:24:07.095  7946  7984 D BluetoothAdapterProperties: Scan Mode:21
08-30 12:24:07.095  7946  7984 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-30 12:24:07.095  7946  8075 V BluetoothMapMasInstance: Succeed to create listening socket 
08-30 12:24:07.096  7946  8075 D BluetoothMapMasInstance: Accepting socket connection...
,08-30 12:24:07.097  2205  2205 D a       : Opening database auth.proximity.permit_store...
08-30 12:24:07.098  2205  2205 D a       : Closing database...
08-30 12:24:07.099  7946  8076 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:24:07.100  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:24:07.101  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:24:07.102  7946  8076 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-30 12:24:07.102  7946  8076 V BluetoothPbapService: Succeed to create listening socket 
08-30 12:24:07.102  7946  8076 V BluetoothPbapService: Accepting socket connection...
08-30 12:24:07.109  6850  6850 D BluetoothPermissionRequest: onReceive
,08-30 12:24:07.111  6850  6850 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-30 12:24:07.113  6850  6850 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 12:24:07.115  7946  7946 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-30 12:24:07.116  7946  7946 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 12:24:07.120  7946  7946 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-30 12:24:07.139  7946  7946 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-30 12:24:07.140  7946  7946 V BtOppService: onCreate
08-30 12:24:07.144  7946  7946 V BluetoothOppNotification: send message
08-30 12:24:07.147  7946  7946 V BtOppService: Starting RfcommListener
08-30 12:24:07.156  7946  7946 D BluetoothOppPreference: Dumping Names:  
,08-30 12:24:07.156  7946  7946 D BluetoothOppPreference: {}
08-30 12:24:07.156  7946  7946 D BluetoothOppPreference: Dumping Channels:  
08-30 12:24:07.156  7946  7946 D BluetoothOppPreference: {}
08-30 12:24:07.158  7946  7946 V BtOppService: onStartCommand
08-30 12:24:07.163  7946  7946 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:24:07.163  7946  8083 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 12:24:07.163  7946  7946 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 12:24:07.166  7946  7946 V BluetoothOppNotification: new notify threadi!
08-30 12:24:07.167  7946  7946 V BluetoothOppNotification: send delay message
08-30 12:24:07.168  7946  7946 V BtOppService: start RfcommListener
,08-30 12:24:07.173  7946  7946 V BtOppService: RfcommListener started
08-30 12:24:07.184  7946  8080 V BtOppService: Deleted complete outbound shares, number =  0
,08-30 12:24:07.185  7946  8085 V BtOppRfcommListener: Starting RFCOMM listener....
08-30 12:24:07.187  7946  8080 V BtOppService: Deleted complete inbound failed shares, number = 0
08-30 12:24:07.187  1035  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:24:07.188  7946  8080 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-30 12:24:07.189  7946  8084 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 12:24:07.189  7946  8085 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:24:07.190  7946  8080 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12df2dbe on behalf of 
08-30 12:24:07.191  7946  8084 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27ea8e1f on behalf of 
08-30 12:24:07.192  7946  8085 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-30 12:24:07.193  7946  8084 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 12:24:07.193  7946  8085 V BtOppRfcommListener: Started RFCOMM listener....
08-30 12:24:07.193  7946  8085 I BtOppRfcommListener: Accept thread started.
08-30 12:24:07.194  7946  8085 V BtOppRfcommListener: Accepting connection...
08-30 12:24:07.194  7946  8083 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 12:24:07.195  7946  8084 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 12:24:07.196  7946  8083 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@126256c on behalf of 
08-30 12:24:07.197  7946  8084 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a2d0735 on behalf of 
08-30 12:24:07.199  7946  8084 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 12:24:07.199  7946  8083 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-30 12:24:07.202  7946  8084 V BluetoothOppNotification: outbound notification was removed.
08-30 12:24:07.202  7946  8084 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 12:24:07.205  7946  8084 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@55c67ca on behalf of 
08-30 12:24:07.207  7946  8084 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 12:24:07.208  7946  8084 V BluetoothOppNotification: inbound notification was removed.
08-30 12:24:07.209  7946  8084 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 12:24:07.210  7946  8084 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33ed3b on behalf of 
08-30 12:24:07.211  7946  7946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c554762
,08-30 12:24:07.211  7946  7946 V BluetoothFtpService: Ftp Service onCreate
08-30 12:24:07.211  7946  7946 I BluetoothFtpService: Ftp Service onCreate
08-30 12:24:07.211  7946  7946 V BluetoothFtpService: Ftp Service onStartCommand
08-30 12:24:07.211  7946  7946 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:24:07.211  7946  7946 V BluetoothFtpService: Starting Listening on sockets
08-30 12:24:07.212  7946  7946 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 12:24:07.212  7946  7946 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 12:24:07.212  7946  7946 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 12:24:07.212  7946  7946 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:24:07.212  7946  7946 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 12:24:07.212  7946  7946 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 12:24:07.215  7946  7946 V BtOppService: ContentObserver received notification
08-30 12:24:07.215  7946  7946 V BtOppService: ContentObserver received notification
08-30 12:24:07.215  7946  7946 V BluetoothFtpService: Handler(): got msg=1
08-30 12:24:07.216  7946  7946 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 12:24:07.216  7946  7946 V BluetoothFtpService: Ftp Service initSocket
08-30 12:24:07.218  7946  8086 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 12:24:07.218  7946  8086 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 12:24:07.221  7946  8086 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b33e1b1 on behalf of 
08-30 12:24:07.222  1035  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:24:07.222  7946  8086 V BluetoothOppNotification: update too frequent, put in queue
08-30 12:24:07.224  7946  7946 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:24:07.224  7946  8086 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-30 12:24:07.226  7946  7946 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-30 12:24:07.226  7946  7946 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-30 12:24:07.228  7946  8087 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-30 12:24:07.251  7946  7946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c554762
,08-30 12:24:07.251  7946  7946 V BluetoothSapService: Sap Service onCreate
08-30 12:24:07.253  7946  7946 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 12:24:07.253  7946  7946 V BluetoothSapService: state: 12
08-30 12:24:07.253  7946  7946 V BluetoothSapService: Starting SAP server process
08-30 12:24:07.256  7946  7946 V BluetoothSapService: SAP Service startRfcommListenerThread
08-30 12:24:07.246  8088  8088 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:24:07.257  7946  8089 V BluetoothSapService: Sap Service initRfcommSocket
08-30 12:24:07.246  8088  8088 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:24:07.258  1035  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:24:07.259  7946  8089 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:24:07.260  7946  8089 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-30 12:24:07.260  7946  8089 V BluetoothSapService: Succeed to create listening socket 
08-30 12:24:07.260  7946  8089 V BluetoothSapService: Accepting socket connection...
08-30 12:24:07.269  8088  8088 V BT_SAP  : Event pipe created
08-30 12:24:07.269  8088  8088 V BT_SAP  : create_server_socket qcom.sap.server
08-30 12:24:07.269  8088  8088 V BT_SAP  : created socket fd 6
,08-30 12:24:08.170  7946  7946 V BluetoothOppNotification: new notify threadi!
,08-30 12:24:08.171  7946  7946 V BluetoothOppNotification: send delay message
,08-30 12:24:08.183  7946  8099 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 12:24:08.187  7946  8099 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19f3e7ed on behalf of 
08-30 12:24:08.188  7946  8099 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 12:24:08.191  7946  8099 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-30 12:24:08.194  7946  8099 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2bd22622 on behalf of 
08-30 12:24:08.195  7946  8099 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 12:24:08.196  7946  8099 V BluetoothOppNotification: outbound notification was removed.
08-30 12:24:08.197  7946  8099 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 12:24:08.198  7946  8099 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1064c8b3 on behalf of 
08-30 12:24:08.198  7946  8099 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 12:24:08.201  7946  8099 V BluetoothOppNotification: inbound notification was removed.
08-30 12:24:08.201  7946  8099 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 12:24:08.203  7946  8099 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d822e70 on behalf of 
,08-30 12:24:10.603  6741  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:24:10.603  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:24:10.603  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:24:10.603  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 12:24:10.603  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:24:10.603  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:24:10.603  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:24:10.603  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:24:10.610  6741  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:24:10.611  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:24:10.611  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@195faef0 removed from the list
08-30 12:24:10.611  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:24:10.611  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:24:10.611  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:24:10.612  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 12:24:10.612  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32aacc69 added. We now have 4 listener(s),
,08-30 12:24:10.612  6741  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:24:10.615  1035  2045 D WifiServiceImplEx: setWifiEnabled: false pid=6741, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 12:24:10.615  1035  2045 D WifiService: setWifiEnabled: false pid=6741, uid=10118
08-30 12:24:10.615  1035  2045 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 12:24:15.624  6741  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:24:15.639  1035  1938 D WifiServiceImplEx: setWifiEnabled: true pid=6741, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 12:24:15.641  1035  1938 D WifiService: setWifiEnabled: true pid=6741, uid=10118
08-30 12:24:15.641  1035  1938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 12:24:15.656  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 12:24:15.656  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 12:24:15.656  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-30 12:24:15.660  1035  1437 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-30 12:24:15.660  1035  1437 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-30 12:24:15.663  1035  1437 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-30 12:24:15.663  1035  1437 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 12:24:15.663  1035  1437 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-30 12:24:15.663  1035  1437 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 12:24:15.663  1035  1437 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 12:24:15.664  1035  1437 E WifiHW  : unknown target_country: EU , set to default
08-30 12:24:15.664  1035  1437 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-30 12:24:15.664  1035  1437 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 12:24:15.664  1035  1437 I WifiUtil: gEnableBmps=1
08-30 12:24:16.238   316   893 D SoftapController: Softap fwReload - Ok
,08-30 12:24:16.243  1035  1437 E NetdConnector: NDC Command {82 softap fwreload wlan0 STA} took too long (576ms)
08-30 12:24:16.247   316   893 D CommandListener: Setting iface cfg
08-30 12:24:16.247   316   893 D CommandListener: Trying to bring down wlan0
08-30 12:24:16.256   316   893 D CommandListener: Clearing all IP addresses on wlan0
,08-30 12:24:16.262  1035  1437 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-30 12:24:16.276  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 12:24:16.286  8110  8110 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 12:24:16.304  1035  1437 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 12:24:16.304  1035  1437 E WifiStateMachine: useWiFiOffloading() : false
08-30 12:24:16.304  1035  1437 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 12:24:16.307  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:24:16.296  8110  8110 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:24:16.326  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-30 12:24:16.356  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 12:24:16.359  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:24:16.361  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-30 12:24:16.361  1035  1437 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 12:24:16.361  1035  1437 D WifiMonitor: connecting to supplicant
08-30 12:24:16.384  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 12:24:16.385  6850  6850 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 12:24:16.385  6850  6850 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 12:24:16.385  6850  6850 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-30 12:24:16.386  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 12:24:16.388  6850  6850 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 12:24:16.388  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-30 12:24:16.388  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 12:24:16.388  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 12:24:16.388  6850  6850 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 12:24:16.388  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-30 12:24:16.389  6850  6850 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 12:24:16.390  8110  8110 I wpa_supplicant: Successfully initialized wpa_supplicant
08-30 12:24:16.429  8110  8110 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 12:24:16.429  8110  8110 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-30 12:24:16.434  1035  1117 D Tethering: InitialState.processMessage what=4
,08-30 12:24:16.445  1035  1938 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8127 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-30 12:24:16.447  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 12:24:16.467   356   356 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 383us total 19.390ms
,08-30 12:24:16.484   356   356 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 288us total 15.274ms
,08-30 12:24:16.505   356   356 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 450us total 18.646ms
08-30 12:24:16.522  8110  8110 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 12:24:16.570  1035  1574 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8150 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 12:24:16.575  8127  8148 W FormManager: Network not available. Please check & try again.
08-30 12:24:16.580  8110  8110 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-30 12:24:16.586  8127  8149 V FormManager: Network unavailable.
,08-30 12:24:16.588  8110  8110 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 12:24:16.590  1035  1437 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-30 12:24:16.591  1035  8166 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 12:24:16.591  1035  8166 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-30 12:24:16.591  1035  8166 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 12:24:16.591  1035  8166 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-30 12:24:16.591  1035  1437 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 12:24:16.591  8127  8149 V FormManager: Network unavailable.
08-30 12:24:16.592  1035  1437 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-30 12:24:16.592  1035  1437 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-30 12:24:16.593  1035  1437 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:24:16.593  1035  1437 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-30 12:24:16.594  1035  1437 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:24:16.595  1035  1437 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:24:16.595  1035  1437 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 12:24:16.595  1035  1437 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-30 12:24:16.596  1035  1437 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 12:24:16.596  1035  1437 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-30 12:24:16.596  1035  1437 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-30 12:24:16.597  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:16.597  1035  1437 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 12:24:16.597  1035  1437 E WifiStateMachine: useWiFiOffloading() : false
08-30 12:24:16.597  1035  1437 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 12:24:16.597  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:16.597  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:16.597  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:16.597  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 12:24:16.599  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:24:16.599  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-30 12:24:16.600  1035  1466 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-30 12:24:16.600  1939  1939 D WfdService: Waiting for WifiP2p enabling
08-30 12:24:16.602  1035  1437 D WifiNative-wlan0: doBoolean: SET update_config 1
08-30 12:24:16.602  1035  1437 D WifiNative-wlan0: SET update_config 1: returned true
08-30 12:24:16.602  1035  1437 D WifiConfigStore: Loading config and enabling all networks 
08-30 12:24:16.603  1035  1437 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 12:24:16.603  1035  1437 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,08-30 12:24:16.604  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:24:16.604  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:24:16.604  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:24:16.604  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:24:16.604  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:24:16.604  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:24:16.604  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:24:16.604  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:24:16.607  1035  1975 I ActivityManager: Killing 7134:com.android.chrome/u0a57 (adj 15): empty #17
08-30 12:24:16.609  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:24:16.609  1035  1437 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-30 12:24:16.611  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:24:16.611  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:24:16.611  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:24:16.611  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:24:16.611  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:24:16.611  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:24:16.611  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:24:16.611  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:24:16.613  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 12:24:16.617  1035  1437 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-30 12:24:16.618  1035  1437 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 12:24:16.649  1035  1437 D WifiStateMachine: enableVerboseLogging : level 2
08-30 12:24:16.649  1035  1437 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 12:24:16.649  1035  1574 W libprocessgroup: failed to open /acct/uid_10057/pid_7134/cgroup.procs: No such file or directory
08-30 12:24:16.650  1035  1437 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-30 12:24:16.650  1035  1437 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-30 12:24:16.650  1035  1437 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 12:24:16.650  1035  1437 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 12:24:16.651  1035  1437 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 12:24:16.651  1035  1437 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 12:24:16.651  1035  1437 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-30 12:24:16.651  1035  1437 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-30 12:24:16.652  1035  1437 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 12:24:16.652  1035  1437 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 12:24:16.652  1035  1437 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 12:24:16.652  1035  1437 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 12:24:16.652  1035  1437 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-30 12:24:16.653  1035  1437 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 12:24:16.653  1035  1437 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-30 12:24:16.653  1939  1939 D WfdsService: Supplicant Connection state is changed : true
08-30 12:24:16.653  1035  1437 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 12:24:16.653  1939  2319 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-30 12:24:16.654  1035  1437 D WifiNative-HAL: Setting external_sim to 1
08-30 12:24:16.654  1939  2319 D WfdsService: Set the WFDS Monitor: true
08-30 12:24:16.654  1035  1437 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-30 12:24:16.654  1939  2319 D WfdsMonitor: WfdsMonitorThread create
08-30 12:24:16.654  1939  2319 D WfdsMonitor: WFDS Monitor is created and started
08-30 12:24:16.654  1939  2319 D WfdsService: WiFi: Supplicant connection re-established
08-30 12:24:16.654  7720  7720 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:16.654  1035  1437 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 12:24:16.654  1035  1437 I WifiNative-HAL: startHal
08-30 12:24:16.654  1939  8169 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 12:24:16.654  1035  1437 D wifi    : setting scan oui 0xaf7181e0
08-30 12:24:16.655  1939  8169 E CtrlSupplicant: Succeed to open control connection
08-30 12:24:16.655  1035  1437 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 12:24:16.655  1035  1437 I WifiNative-HAL: startHal
08-30 12:24:16.655  1035  1437 D wifi    : setting scan oui 0xaf7181e0
08-30 12:24:16.655  1939  8169 E CtrlSupplicant: Succeed to open monitor connection
08-30 12:24:16.655  1939  8169 D WfdsMonitor: Supplicant connection established
08-30 12:24:16.655  1035  1437 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 12:24:16.655  1939  2319 D WfdsService: Connected to the supplicant for wfds
08-30 12:24:16.656  1035  1437 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 12:24:16.656  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 12:24:16.656  8110  8110 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 12:24:16.657  1035  1437 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 12:24:16.657  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 12:24:16.657  8110  8110 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILT,ER-STOP
08-30 12:24:16.658  1035  1437 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 12:24:16.658  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 12:24:16.658  8110  8110 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-30 12:24:16.659  1035  1437 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 12:24:16.659  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 12:24:16.659  8110  8110 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 12:24:16.660  1035  1437 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 12:24:16.660  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 12:24:16.660  8110  8110 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 12:24:16.662  1035  1437 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 12:24:16.662  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 12:24:16.662  8110  8110 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 12:24:16.663  1035  1437 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 12:24:16.663  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 12:24:16.663  8110  8110 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 12:24:16.663  1035  1437 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 12:24:16.665  1035  1437 E WifiNative: : [373,897,031 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 12:24:16.665  1035  1437 D WifiNative-wlan0: doBoolean: RECONNECT
08-30 12:24:16.666  1035  1437 D WifiNative-wlan0: RECONNECT: returned true
,08-30 12:24:16.666  1035  1437 D WifiNative-wlan0: doString: [STATUS]
08-30 12:24:16.667  1035  8166 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 12:24:16.667  1035  8166 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 12:24:16.667  1035  1437 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 12:24:16.667  1035  1437 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 12:24:16.668  1035  1437 D WifiNative-wlan0: SET ps 1: returned true
08-30 12:24:16.668  1035  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:16.669  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 12:24:16.669  1035  1035 D RttService: SCAN_AVAILABLE : 3
08-30 12:24:16.669  1035  1555 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:16.669  1035  1555 I WifiNative-HAL: startHal
08-30 12:24:16.669  1035  1555 D wifi    : getting scan capabilities on interface[1] = 0xaf7181e0
08-30 12:24:16.669  1035  1555 D wifi    : failed to get capabilities : -3
08-30 12:24:16.669  1035  1555 E WifiScanningService: could not get scan capabilities
08-30 12:24:16.669  1035  1556 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:16.669  1035  1437 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 12:24:16.670  1035  1437 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 12:24:16.670  1035  1437 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-30 12:24:16.671   316   893 D CommandListener: Setting iface cfg
08-30 12:24:16.671   316   893 D CommandListener: Trying to bring up p2p0
08-30 12:24:16.671  1035  1390 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 12:24:16.671  1035  1390 D LGWifiP2pService: P2pEnablingState
08-30 12:24:16.671  1035  1437 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 12:24:16.671  1035  1390 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:16.671  1035  1390 D LGWifiP2pService: P2p socket connection successful
08-30 12:24:16.671  1035  1390 D LGWifiP2pService: P2pEnabledState
08-30 12:24:16.672  1035  1390 D LGWifiP2pService: sending p2p connection changed broadcast
08-30 12:24:16.672  1035  1437 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 12:24:16.672  1035  1437 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 12:24:16.672  1939  1939 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-30 12:24:16.673  1939  1939 D WfdsService: WifiP2pState is changed : true
08-30 12:24:16.673  1035  1437 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 12:24:16.673  1035  1437 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-30 12:24:16.673  1939  2319 D WfdsService: Receive the WFDS_ENABLE Method
08-30 12:24:16.673  1939  2319 D WfdsService: Set the WFDS Monitor: true
08-30 12:24:16.673  1035  1390 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 12:24:16.673  1939  2319 D WfdsService: Connected to the supplicant for wfds
08-30 12:24:16.673  8110  8110 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-30 12:24:16.673  1939  2319 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 12:24:16.673  1035  1390 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 12:24:16.673  8110  8110 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 12:24:16.673  1035  1390 D WifiNative-p2p0: doBoolean: SET device_name G3
08-30 12:24:16.674  1035  1390 D WifiNative-p2p0: SET device_name G3: returned true
08-30 12:24:16.674  1035  1390 D LGWifiP2pService: [LGE_P2P] i,nitializeP2pSettings() check postfix
08-30 12:24:16.674  1035  1390 D LGWifiP2pService: before postfix = G3
08-30 12:24:16.674  1035  1390 D WifiServerServiceExt: postfix byte check : 2
08-30 12:24:16.674  1035  1390 D LGWifiP2pService: after postfix = G3
08-30 12:24:16.674  1035  1390 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 12:24:16.675  1035  1390 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 12:24:16.675  1035  1390 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 12:24:16.675  1035  1390 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 12:24:16.675  1035  1390 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-30 12:24:16.676  1939  2319 D WfdsService: selectPreferredScanChannel [36]
08-30 12:24:16.676  1939  2319 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 12:24:16.676  1939  1939 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 12:24:16.676  1035  1390 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 12:24:16.676  1035  1390 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 12:24:16.676  1939  1939 D WfdsService: isConnected: false
08-30 12:24:16.677  1035  1390 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 12:24:16.677  1035  1390 D WifiNative-HAL: p2pGetDeviceAddress
08-30 12:24:16.677  1035  1390 D WifiNative-HAL: p2pGetDeviceAddress returning 
08-30 12:24:16.677  1035  1390 D LGWifiP2pService: DeviceAddress: 
08-30 12:24:16.678  1035  1390 D WifiNative-p2p0: doBoolean: P2P_FLUSH
,08-30 12:24:16.678  1035  1437 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-30 12:24:16.678  1939  1939 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 12:24:16.678  1939  1939 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 12:24:16.679  1035  1437 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-30 12:24:16.679  1035  1437 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 12:24:16.679  1035  1437 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-30 12:24:16.679  8110  8110 E wpa_supplicant: disconnect_rssi_lvl: -100
08-30 12:24:16.680  1035  1437 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 12:24:16.680  1035  1390 D WifiNative-p2p0: P2P_FLUSH: returned true
08-30 12:24:16.680  1035  1390 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 12:24:16.680  1035  1437 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 12:24:16.680  1035  1390 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-30 12:24:16.680  1035  1390 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 12:24:16.680  1035  1437 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 12:24:16.680  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-30 12:24:16.681  1035  1390 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 12:24:16.681  1035  1390 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-30 12:24:16.682  1939  1939 D WfdsService: Update P2p Interface State: 3
08-30 12:24:16.690  1035  1390 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-30 12:24:16.690  1035  1390 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-30 12:24:16.691  1035  1390 D LGWifiP2pService: InactiveState
08-30 12:24:16.691  1035  1390 D LGWifiP2pService: InactiveState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:16.691  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:16.691  1035  1390 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,08-30 12:24:16.692  8110  8110 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 12:24:16.693  8110  8110 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:24:16.693  1939  8169 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 12:24:16.693  1035  8166 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 12:24:16.694  1035  8166 E WifiMonitor: WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:24:16.694  1035  8166 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:24:16.694  1035  8166 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:24:16.694  8110  8110 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 12:24:16.694  8110  8110 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:24:16.694  1939  8169 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:24:16.694  1035  8166 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:24:16.694  1035  8166 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:24:16.694  1035  8166 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:24:16.694  1035  8166 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:24:16.695  1035  1390 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 12:24:16.695  1035  1390 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:16.695  8110  8110 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:24:16.695  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:16.695  1035  1390 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:16.695  1939  8169 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:24:16.695  1035  8166 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:24:16.695  1035  1390 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:16.695  1035  8166 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:24:16.695  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:16.695  1035  8166 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:24:16.695  1035  1390 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:16.695  1035  8166 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:24:16.695  1035  1390 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:16.695  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:16.695  1035  1390 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:16.696  1035  1390 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:16.696  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24,:16.696  1035  1390 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:16.698  1035  1035 E WifiServerServiceExt: No p2p device connected
08-30 12:24:16.698  1939  2319 W WfdsService: DefaultState - msg [9441285] is not handled
08-30 12:24:16.698  8110  8110 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 12:24:16.698  8110  8110 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:24:16.699  1035  8166 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 12:24:16.699  1035  8166 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:24:16.699  1035  8166 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:24:16.699  1035  8166 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 12:24:16.699  8110  8110 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 12:24:16.699  8110  8110 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:24:16.699  1939  8169 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:24:16.700  1035  8166 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:24:16.700  1035  8166 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:24:16.700  1035  8166 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:24:16.700  1035  8166 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:24:16.700  1035  1437 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-30 12:24:16.700  8110  8110 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:24:16.700  1035  8166 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:24:16.700  1035  1437 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 12:24:16.700  1035  8166 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:24:16.700  1035  8166 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:24:16.700  1035  8166 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 12:24:16.701  1035  1437 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 12:24:16.701  1939  8169 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 12:24:16.701  1035  1437 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-30 12:24:16.701  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-30 12:24:16.701  8110  8110 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
,08-30 12:24:16.701  1035  1390 D LGWifiP2pService: InactiveState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:16.701  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:16.701  8110  8110 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 12:24:16.702  1035  8166 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 12:24:16.702  1035  8166 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 12:24:16.702  1035  8166 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 12:24:16.702  1035  8166 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 12:24:16.702  8150  8150 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 12:24:16.702  1035  1437 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 12:24:16.702  1035  1437 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 12:24:16.703  1035  1437 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 12:24:16.703  1035  1437 D WifiNative-wlan0: doBoolean: SCAN
08-30 12:24:16.703  1035  1437 D WifiNative-wlan0: SCAN: returned false
,08-30 12:24:16.704  1035  1437 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=373937  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 12:24:16.705  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 12:24:16.710  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:24:16.710  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:24:16.711  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:16.711  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:16.711  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 12:24:16.712  1035  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=373944  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 12:24:16.712  1035  1437 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 12:24:16.713  1035  1437 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 12:24:16.713  1035  1437 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 12:24:16.714  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:24:16.714  1035  1437 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 12:24:16.714  1035  1437 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 12:24:16.715  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:24:16.716  1035  1938 I ActivityManager: Killing 7158:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-30 12:24:16.759  1035  1920 W libprocessgroup: failed to open /acct/uid_10062/pid_7158/cgroup.procs: No such file or directory
,08-30 12:24:16.764  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:24:16.764  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
08-30 12:24:16.775  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 12:24:16.775  6850  6850 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 12:24:16.775  6850  6850 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 12:24:16.775  6850  6850 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 12:24:16.776  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-30 12:24:16.776  6850  6850 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 12:24:16.777  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 12:24:16.777  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 12:24:16.777  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 12:24:16.777  6850  6850 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 12:24:16.777  6850  6850 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 12:24:16.784  8150  8150 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 12:24:16.787  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 12:24:16.793  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:24:16.805  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-30 12:24:16.805  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 12:24:16.807  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:24:16.807  8127  8173 W FormManager: Network not available. Please check & try again.
08-30 12:24:16.810  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:24:16.816  4306  8175 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 12:24:16.819  4306  8176 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 12:24:16.819  4306  8176 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 12:24:16.885  1035  1993 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8177 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 12:24:16.892  8127  8174 V FormManager: Network unavailable.
08-30 12:24:16.896  8127  8174 V FormManager: Network unavailable.
,08-30 12:24:17.002  8177  8177 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 12:24:17.002  8177  8177 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-30 12:24:17.013  8177  8177 V [BNRBootReceiver]: Boot Receiver Return
08-30 12:24:17.015  8177  8177 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 12:24:17.063  1035  1885 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8195 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 12:24:17.064  1035  1885 I ActivityManager: Killing 7191:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-30 12:24:17.121  1035  1975 W libprocessgroup: failed to open /acct/uid_10085/pid_7191/cgroup.procs: No such file or directory
,08-30 12:24:17.157  8195  8195 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 12:24:17.181  8195  8195 D PluginManager: init()
,08-30 12:24:17.301  8110  8110 E wpa_supplicant: USIM:  scard_init function
,08-30 12:24:17.301  1035  8166 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-30 12:24:17.301  1035  8166 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 12:24:17.301  8110  8110 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-30 12:24:17.301  1035  8166 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,08-30 12:24:17.301  1035  8166 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
08-30 12:24:17.301  1035  8166 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-30 12:24:17.302  1035  8166 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-30 12:24:17.302  1035  8166 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-30 12:24:17.303  1035  1437 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-30 12:24:17.305  1035  1437 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-30 12:24:17.306  1035  1437 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-30 12:24:17.308  1035  1437 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-30 12:24:17.308  1035  1437 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,08-30 12:24:17.322  1035  1437 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=374555  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-30 12:24:17.329  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 12:24:17.329  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:24:17.332  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:24:17.332  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:17.332  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:17.332  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 12:24:17.335  1035  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=374568  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 12:24:17.340  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:17.340  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:17.341  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-30 12:24:17.341  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-30 12:24:17.341  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-30 12:24:17.356  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:24:17.357  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 12:24:17.359  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:24:17.419  8110  8110 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-30 12:24:17.419  1035  8166 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-30 12:24:17.419  1035  8166 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,08-30 12:24:17.419  1035  8166 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-30 12:24:17.420  1035  8166 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-30 12:24:17.420  1035  8166 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 12:24:17.420  1035  8166 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 12:24:17.422  1035  1437 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=374654  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 12:24:17.423  1035  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=374656  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 12:24:17.425  1035  1437 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=374658
08-30 12:24:17.426  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 12:24:17.426  1035  1437 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=374659
08-30 12:24:17.427  1035  1437 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=374660
08-30 12:24:17.427  1035  1437 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=374660
08-30 12:24:17.428  1035  1437 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=374661
,08-30 12:24:17.428  1035  1437 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=374661  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 12:24:17.431  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:24:17.431  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:24:17.433  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:17.433  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:17.433  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 12:24:17.434  1035  8166 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 12:24:17.434  1035  8166 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 12:24:17.435  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:24:17.435  8110  8110 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 12:24:17.436  8110  8110 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-30 12:24:17.438  1035  8166 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 12:24:17.438  1035  8166 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 12:24:17.438  1035  8166 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 12:24:17.438  1035  8166 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 12:24:17.438  1035  8166 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 12:24:17.438  1035  8166 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 12:24:17.439  1035  8166 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 12:24:17.440  1035  8166 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 12:24:17.441  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:17.441  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:17.441  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 12:24:17.442  1035  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=374675  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 12:24:17.443  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:24:17.443  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-30 12:24:17.444  1035  1437 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:24:17.444  1035  1437 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:24:17.445  1035  1437 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:24:17.445  1035  1437 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:24:17.445  1035  1437 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 12:24:17.446  1035  1437 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=374679  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 12:24:17.447  1035  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=374679  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 12:24:17.447  1035  1437 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=374680
08-30 12:24:17.448  1035  1437 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=374680
08-30 12:24:17.448  1035  1437 D WifiNative-wlan0: doString: [STATUS]
08-30 12:24:17.448  1035  8166 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 12:24:17.448  1035  8166 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 12:24:17.449  1035  1437 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 12:24:17.450  1035  1437 I WifiServiceExtension: setVHTCapabilityType  : false
,08-30 12:24:17.456  1035  1437 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 12:24:17.456  1035  1437 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-30 12:24:17.459  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:17.459  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:17.459  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 12:24:17.461  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:24:17.461  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 12:24:17.464  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:17.464  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:17.464  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 12:24:17.466  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:24:17.467  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:24:17.467  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:24:17.470  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:24:17.471  1035  1437 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-30 12:24:17.471  1035  1437 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 12:24:17.471  1035  1437 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 12:24:17.471  1035  1495 D ConnectivityService: Got NetworkAgent Messenger
08-30 12:24:17.471  1035  1495 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 12:24:17.471  1035  1495 D ConnectivityService: NetworkAgent connected
08-30 12:24:17.471  1035  1437 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 12:24:17.471  1035  1437 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 12:24:17.472  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:24:17.472  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:24:17.473  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 12:24:17.477  1035  1437 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 12:24:17.477  1035  1437 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 12:24:17.477  1035  1437 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 12:24:17.477  1035  1437 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 12:24:17.477  1035  1437 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 12:24:17.483  1035  1437 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 12:24:17.484   316   893 D CommandListener: Setting iface cfg
08-30 12:24:17.486  1035  8213 D DhcpStateMachine: StoppedState
08-30 12:24:17.486  1035  1437 E WifiStateMachine: Start Dhcp Watchdog 3
08-30 12:24:17.486  1035  8213 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:17.486  1035  8213 D DhcpStateMachine: WaitBeforeStartState
08-30 12:24:17.487  1035  1437 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=374719  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 12:24:17.487  1035  1437 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=374720  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 12:24:17.487  1035  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=374720  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-30 12:24:17.489  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:24:17.489  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-30 12:24:17.491  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:24:17.491  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-30 12:24:17.491  1035  1437 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=374724  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 12:24:17.492  1035  1437 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=374725  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 12:24:17.492  1035  1437 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=374725  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 12:24:17.493  1035  1437 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:29153] from screen [on:0 period:-621125035] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 12:24:17.494  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-621125034] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 12:24:17.494  1035  1437 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 12:24:17.498  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:24:17.499  1035  1495 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-30 12:24:17.499  1035  1437 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:24:17.500  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:24:17.500  1035  1437 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:24:17.500  1035  1437 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:24:17.501  1035  1437 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-30 12:24:17.501  1035  1437 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 12:24:17.502  1035  1495 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 12:24:17.502  1035  1437 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=145,0,0
08-30 12:24:17.502  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=145,0,0
08-30 12:24:17.502  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-30 12:24:17.503  8110  8110 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-30 12:24:17.503  1035  1437 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-30 12:24:17.503  1035  1437 D WifiNative-wlan0: doBoolean: SET ps 0
08-30 12:24:17.504  1035  1437 D WifiNative-wlan0: SET ps 0: returned true
08-30 12:24:17.504  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 12:24:17.504  8110  8110 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-30 12:24:17.504  1035  1437 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-30 12:24:17.504  1035  1437 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 12:24:17.504  1035  1437 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 12:24:17.504  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@229b794c target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:17.504  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@229b794c target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:17.505  1035  1437 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 12:24:17.505  1035  8213 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:17.505  1035  8213 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 12:24:17.506   316   893 D CommandListener: Setting iface cfg
08-30 12:24:17.506   316   893 D CommandListener: Trying to bring up wlan0
08-30 12:24:17.506  1035  1437 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-30 12:24:17.508  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:24:17.508  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 12:24:17.508  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 12:24:17.508  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 12:24:17.509  1035  1437 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-30 12:24:17.509  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-30 12:24:17.509  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 12:24:17.510  1035  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:17.510  1035  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:17.510  8110  8110 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 12:24:17.510  1035  1437 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 12:24:17.510  1035  1437 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 12:24:17.510  8110  8110 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-30 12:24:17.510  1035  1437 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 12:24:17.510  1035  1437 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 12:24:17.533  1035  1437 D WifiNative-wlan0: SET ps 1: returned true
08-30 12:24:17.533  1035  1495 D Connectiv,ityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 12:24:17.534  1035  1437 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 12:24:17.534  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-30 12:24:17.535  1035  1437 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 12:24:17.536  1035  1437 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 12:24:17.537  1035  1437 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 12:24:17.537  1035  1437 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 12:24:17.538  1035  1495 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 12:24:17.538  1035  1437 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 12:24:17.539  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 12:24:17.539  1035  1437 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 12:24:17.539  1035  1495 D ConnectivityService: ignoring duplicate network state non-change
08-30 12:24:17.541  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:24:17.541  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:24:17.542  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:17.542  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:17.542  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 12:24:17.544  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 12:24:17.548  1035  1495 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 12:24:17.549  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:17.549  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:17.550  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 12:24:17.552  1035  1495 D ConnectivityService: Adding iface wlan0 to network 102
08-30 12:24:17.552  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 12:24:17.559  1939  1939 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-30 12:24:17.566  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:17.566  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 12:24:17.566  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 12:24:17.567  8195  8195 W ExternalStrings: load override strings
08-30 12:24:17.567  8195  8195 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-30 12:24:17.567  8195  8195 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-30 12:24:17.567  8195  8195 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-30 12:24:17.567  8195  8195 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-30 12:24:17.567  8195  8195 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-30 12:24:17.567  8195  8195 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-30 12:24:17.567  8195  8195 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-30 12:24:17.567  8195  8195 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-30 12:24:17.567  8195  8195 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-30 12:24:17.567  8195  8195 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-30 12:24:17.567  8195  8195 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-30 12:24:17.567  8195  8195 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:24:17.567  8195  8195 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:24:17.567  8195  8195 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 12:24:17.567  8195  8195 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:24:17.567  8195  8195 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:24:17.567  8195  8195 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 12:24:17.567  8195  8195 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 12:24:17.567  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:24:17.567  1601  1601 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 12:24:17.567  1035  1437 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 12:24:17.568  8195  8195 D StatusProvider: onCreate
08-30 12:24:17.569  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:24:17.569  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 12:24:17.572  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:24:17.572  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 12:24:17.572  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 12:24:17.578  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:17.578  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:17.578  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 12:24:17.587  1035  1495 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 12:24:17.588  1035  1495 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-30 12:24:17.589  1035  1495 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-30 12:24:17.589  1601  1601 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:24:17.589  1601  1601 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 12:24:17.589   316   893 E Netd    : netlink response contains error (File exists)
08-30 12:24:17.589  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:24:17.590  1035  1495 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-30 12:24:17.591  1035  1495 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 12:24:17.591  1035  1495 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-30 12:24:17.591  1035  1495 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-30 12:24:17.592  1035  1495 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 12:24:17.592  1035  1495 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 12:24:17.592  1035  1495 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-30 12:24:17.592  1035  1495 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 12:24:17.592  1035  1495 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 12:24:17.592  1035  1495 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:24:17.592  1035  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:17.592  1035  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-30 12:24:17.592  1035  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:17.592  1035  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 12:24:17.593  1035  1495 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 12:24:17.593  1035  1495 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:24:17.593  1035  1495 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 12:24:17.593  1035  1495 D ConnectivityService: currentScore = 0, newScore = 20
08-30 12:24:17.593  1035  1495 D ConnectivityService:    accepting network in place of null
08-30 12:24:17.593  1035  1495 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:24:17.594  1035  1437 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:24:17.594  1035  1437 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 12:24:17.594   316  8217 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-30 12:24:17.595  1035  1495 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkA,ddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 12:24:17.595  1035  1495 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-30 12:24:17.595  1035  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 12:24:17.596  1850  1850 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:24:17.596  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 12:24:17.597  1035  1495 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 12:24:17.597  1035  1495 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 12:24:17.597  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-30 12:24:17.597  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 12:24:17.597  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 12:24:17.598  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-30 12:24:17.605  1035  1389 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-30 12:24:17.610  1035  1495 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-30 12:24:17.610  1035  1495 D ConnectivityService: validation of new default Network = false
08-30 12:24:17.610  1035  1495 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 12:24:17.610  1035  1495 D DSQN    : enableDataServiceNotify 
08-30 12:24:17.610  1035  1495 D DSQN    : start dsqn bin
08-30 12:24:17.606  8218  8218 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 12:24:17.606  8218  8218 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 12:24:17.615  1035  1495 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 12:24:17.615  1035  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:24:17.615  1035  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:24:17.615  1035  1495 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:24:17.615  1601  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 12:24:17.628  8218  8218 E DSQN    : DSQN ssw
08-30 12:24:17.629  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-30 12:24:17.630  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:24:17.631  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:24:17.638   316  8217 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-30 12:24:17.641  8195  8195 V Signer  : override build config not found
08-30 12:24:17.641  8195  8195 D Signer  : value of property debug is false
,08-30 12:24:17.672   316  8217 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-30 12:24:17.680  8195  8195 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,08-30 12:24:17.681  8195  8195 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-30 12:24:17.681  8195  8195 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-30 12:24:17.681  8195  8195 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-30 12:24:17.682  8195  8195 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-30 12:24:17.682  8195  8195 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-30 12:24:17.682  8195  8195 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-30 12:24:17.682  8195  8195 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-30 12:24:17.683  8195  8195 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-30 12:24:17.683  8195  8195 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-30 12:24:17.683  8195  8195 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-30 12:24:17.683  8195  8195 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-30 12:24:17.684  8195  8195 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-30 12:24:17.697  8195  8195 V LGMDMManager: Create singleton instance
,08-30 12:24:17.707  1035  8213 D DhcpStateMachine: DHCPV4 request on wlan0
08-30 12:24:17.707   316   892 D LGDataListener: argv[0]=dsqncommand
08-30 12:24:17.707   316   892 D LGDataListener: argv[1]=wlan0
08-30 12:24:17.707   316   892 D LGDataListener: argv[2]=1
08-30 12:24:17.708   316   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-30 12:24:17.708  1035  1115 D DSQN    : DSQM DsqnNotification wlan0  1
08-30 12:24:17.709  1035  1115 D DSQN    : start to monitor internet connection
08-30 12:24:17.709  1035  8213 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-30 12:24:17.709  1035  8213 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-30 12:24:17.706  8224  8224 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 12:24:17.706  8224  8224 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 12:24:17.733  1035  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 10:24:17 GMT], X-Android-Received-Millis=[1472552657733], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472552657706]}
08-30 12:24:17.734  1035  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,08-30 12:24:17.734  1035  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-30 12:24:17.734  1035  1495 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-30 12:24:17.734  1035  1495 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 12:24:17.734  1035  1495 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 12:24:17.735  1035  1495 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:24:17.735  1035  1495 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 12:24:17.735  1035  1495 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-30 12:24:17.735  1035  1495 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,08-30 12:24:17.735  1035  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:24:17.735  1035  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:24:17.736  1035  1495 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:24:17.738  1601  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 12:24:17.740  1035  1495 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:24:17.740  8224  8224 I dhcpcd  : version 5.5.6 starting
08-30 12:24:17.741  1035  1437 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:24:17.741  1035  1437 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 12:24:17.742  1035  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-30 12:24:17.745  8224  8224 E dhcpcd  : get_duid: m
08-30 12:24:17.745  8224  8224 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 12:24:17.746  8224  8224 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-30 12:24:17.746  1850  1850 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:24:17.746  1850  1850 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 12:24:17.762  1601  1601 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 12:24:17.762  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 12:24:17.763  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 12:24:17.796  8224  8224 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 12:24:17.796  8224  8224 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 12:24:17.796  8224  8224 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 12:24:17.796  8224  8224 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 12:24:17.797  8224  8224 D dhcpcd  : wlan0: sending REQUEST (xid 0x9beab3ea), next in 4.56 seconds
08-30 12:24:17.797  8195  8195 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-30 12:24:17.816  8224  8224 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-30 12:24:17.835  8224  8224 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-30 12:24:17.835  8224  8224 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-30 12:24:17.836  8224  8224 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-30 12:24:17.836  8224  8224 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-30 12:24:17.836  8224  8224 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 12:24:17.836  8224  8224 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 12:24:17.836  8224  8224 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 12:24:17.836  8224  8224 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-30 12:24:17.857  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:24:17.858  8195  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 12:24:17.880  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:24:17.885  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:24:17.891  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 12:24:17.891  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:24:17.893  6909  6909 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 12:24:17.896  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-30 12:24:17.905  6850  6850 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-30 12:24:17.907  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:24:17.907  8195  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 12:24:17.912  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:24:17.919  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:24:17.924  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:24:17.924  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:24:17.926  6909  6909 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 12:24:17.996  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 12:24:17.996  8195  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 12:24:17.999  8195  8233 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-30 12:24:18.008  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:24:18.013  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:24:18.018  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:24:18.018  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:24:18.018  6909  6909 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 12:24:18.021  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 12:24:18.021  6850  6850 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 12:24:18.021  6850  6850 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 12:24:18.021  6850  6850 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 12:24:18.021  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-30 12:24:18.023  6850  6850 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 12:24:18.023  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-30 12:24:18.023  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 12:24:18.023  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
,08-30 12:24:18.023  6850  6850 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 12:24:18.023  6850  6850 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-30 12:24:18.023  6850  6850 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 12:24:18.027  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:24:18.028  8195  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 12:24:18.035  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:24:18.039  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:24:18.048  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 12:24:18.048  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:24:18.048  6909  6909 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 12:24:18.052  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:24:18.052  8195  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 12:24:18.058  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:24:18.061  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:24:18.066  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 12:24:18.067  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:24:18.068  6909  6909 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 12:24:18.070  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:24:18.070  8195  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 12:24:18.076  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:24:18.081  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:24:18.088  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 12:24:18.089  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 12:24:18.090  6909  6909 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 12:24:18.093  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:24:18.094  8195  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 12:24:18.101  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:24:18.107  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:24:18.114  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 12:24:18.115  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:24:18.116  1035  8213 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-30 12:24:18.116  6909  6909 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 12:24:18.119  1035  8213 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-30 12:24:18.119  1035  8213 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 12:24:18.120  1035  8213 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-30 12:24:18.120  1035  8213 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-30 12:24:18.120  1035  8213 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 12:24:18.120  1035  8213 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-30 12:24:18.120  1035  8213 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-30 12:24:18.121  1035  8213 D DhcpStateMachine: RunningState
08-30 12:24:18.122  8195  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 12:24:18.123  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:24:18.134  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:24:18.140  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:24:18.151  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:24:18.151  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:24:18.152  6909  6909 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 12:24:18.159  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:24:18.163  8195  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 12:24:18.170  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:24:18.176  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 12:24:18.185  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:24:18.186  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:24:18.187  6909  6909 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 12:24:18.193  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 12:24:18.193  8195  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 12:24:18.198  8150  8150 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-30 12:24:18.203  8150  8150 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 12:24:18.209  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 12:24:18.216  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:24:18.224  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:24:18.225  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 12:24:18.226  6909  6909 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 12:24:18.227  6909  6909 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 12:24:18.227  6909  6909 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 12:24:18.233  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 12:24:18.233  8195  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 12:24:18.237  8150  8150 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 12:24:18.238  8150  8150 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 12:24:18.242  6850  6850 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 12:24:18.249  6850  6850 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 12:24:18.258  6909  6909 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 12:24:18.258  6909  6909 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 12:24:18.259  6909  6909 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 12:24:18.260  6909  6909 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 12:24:18.261  6909  6909 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-30 12:24:18.267  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 12:24:18.269  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 12:24:18.270  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 12:24:18.273  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 12:24:18.274  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-30 12:24:18.277  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 12:24:18.278  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 12:24:18.280  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 12:24:18.282  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 12:24:18.284  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 12:24:18.286  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-30 12:24:18.288  1035  1975 I ActivityManager: Killing 7212:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-30 12:24:18.293  8195  8233 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:24:18.294  8195  8233 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:24:18.429  8195  8233 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-30 12:24:18.554  1035  1884 W libprocessgroup: failed to open /acct/uid_10093/pid_7212/cgroup.procs: No such file or directory
,08-30 12:24:18.583  8195  8233 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-30 12:24:18.588  1035  1437 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 12:24:18.589  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 12:24:18.589  1035  1437 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 12:24:18.589  1035  1437 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 12:24:18.590  1035  1437 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 12:24:18.590  1035  1437 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 12:24:18.591  1035  1495 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-30 12:24:18.591  1035  1495 D ConnectivityService: identical MTU - not setting
08-30 12:24:18.592  1035  1495 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 12:24:18.592  1035  1495 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 12:24:18.592  1035  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:24:18.592  1035  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:24:18.592  1035  1495 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:24:18.593  1601  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-30 12:24:18.596  8195  8233 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,08-30 12:24:18.597  8195  8233 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-30 12:24:18.597  8195  8233 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-30 12:24:18.599  8195  8233 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-30 12:24:18.600  8195  8233 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-30 12:24:18.603  8195  8233 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-30 12:24:18.605  8195  8233 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,08-30 12:24:20.503  1035  1437 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=72.5, 0.0, 0.0  rx=65.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-621122025] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 12:24:20.514  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=72.5, 0.0, 0.0  rx=65.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-621122015] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 12:24:20.514  1035  1437 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 12:24:20.530  1601  1601 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 12:24:20.554  1035  1449 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-30 12:24:20.600  1035  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:24:20.619  1035  1117 D Tethering: MasterInitialState.processMessage what=3
08-30 12:24:20.638  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:24:20.638  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:24:20.638  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:24:20.638  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:24:20.638  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:24:20.638  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:24:20.638  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:24:20.638  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:24:20.643  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:24:20.648  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:24:20.648  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:24:20.648  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:24:20.648  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:24:20.648  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:24:20.648  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:24:20.648  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:24:20.648  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:24:20.650  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:24:20.651  1035  1112 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:24:20.661  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 12:24:20.665  5736  5736 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-30 12:24:20.673  6741  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 12:24:20.673  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:24:20.673  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:24:20.673  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:24:20.673  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:24:20.673  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:24:20.673  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:24:20.673  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:24:20.676  6741  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:24:20.677  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:24:20.677  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32aacc69 removed from the list
08-30 12:24:20.677  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:24:20.677  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:24:20.677  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:24:20.683  6741  8278 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-30 12:24:20.683  6741  8278 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 12:24:20.726  8195  8233 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-30 12:24:20.744  2205  2205 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:24:20.766  7038  7038 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 12:24:20.766  7038  7038 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 12:24:20.766  7038  7038 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 12:24:20.766  7038  7038 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 12:24:20.770   316  8294 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 12:24:20.771   316  8294 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-30 12:24:20.773  7038  7038 I AppUp4:CustModeStarterReceiver: onReceive
08-30 12:24:20.773  1035  1957 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
08-30 12:24:20.774  1035  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:20.774  1035  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:20.774  1035  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
,08-30 12:24:20.774  1035  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:20.774  1035  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 12:24:20.776  7038  7038 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@175ac657
08-30 12:24:20.776  7038  7038 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 12:24:20.776  7038  7038 D AppUp4:CustFacade: isPhone : true
08-30 12:24:20.777  7038  7038 D AppUp4:CustModeStarterReceiver: begin check event
08-30 12:24:20.777  7038  7038 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-30 12:24:20.788  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 12:24:20.788  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 12:24:20.790  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:24:20.793  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 12:24:20.796  3484  3484 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,08-30 12:24:20.800  4306  8298 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 12:24:20.801  3484  3484 V DownloadManager: DownloadService onCreate
08-30 12:24:20.803  4306  8298 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-30 12:24:20.804   316  8294 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-30 12:24:20.808  4306  8300 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 12:24:20.808  4306  8300 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 12:24:20.811  1035  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 10:24:20 GMT], X-Android-Received-Millis=[1472552660811], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472552660779]}
08-30 12:24:20.811  1035  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 12:24:20.811  1035  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-30 12:24:20.811  3484  8301 I DownloadManager: in removeSpuriousFiles
08-30 12:24:20.811  1035  1495 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-30 12:24:20.812  1035  1495 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 12:24:20.812  1035  1495 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 12:24:20.812  1035  1495 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,08-30 12:24:20.812  1035  1495 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,08-30 12:24:20.812  1035  1495 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-30 12:24:20.812  1035  1495 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 12:24:20.812  1035  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:24:20.812  1035  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:24:20.813  1035  1495 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:24:20.813  1601  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 12:24:20.814  3484  8301 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-30 12:24:20.815  3484  8301 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@a622928 on behalf of 3484
08-30 12:24:20.816  3484  8301 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
,08-30 12:24:20.817  3484  8301 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-30 12:24:20.817  3484  8301 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-30 12:24:20.817  3484  8301 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-30 12:24:20.817  3484  8301 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-30 12:24:20.817  3484  8301 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-30 12:24:20.817  3484  8301 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-30 12:24:20.817  3484  8301 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-30 12:24:20.817  3484  8301 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-30 12:24:20.817  3484  8301 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-30 12:24:20.817  3484  8301 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-30 12:24:20.818  3484  8301 I DownloadManager: in trimDatabase
08-30 12:24:20.818  3484  8301 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-30 12:24:20.820  3484  8301 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1145e641 on behalf of 3484
08-30 12:24:20.837  1035  1725 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8304 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 12:24:20.839  1035  1112 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 12:24:20.841  3484  3484 V DownloadManager: DownloadService onStartCommand
08-30 12:24:20.841  3484  8302 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-30 12:24:20.843  4306  8298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,08-30 12:24:20.843  3484  8302 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2044afd4 on behalf of 3484
08-30 12:24:20.845  3484  8302 V DownloadManager: processing inserted download 1
08-30 12:24:20.846  4306  4306 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-30 12:24:20.848  4306  4306 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-30 12:24:20.848  4306  4306 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-30 12:24:20.851  4306  4306 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
,08-30 12:24:20.856  4306  4306 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-30 12:24:20.858  3484  8302 V DownloadManager: processing inserted download 4
08-30 12:24:20.859  3484  8302 V DownloadManager: processing inserted download 7
08-30 12:24:20.860  3484  8302 V DownloadManager: processing inserted download 8
08-30 12:24:20.860  3484  8302 V DownloadManager: processing inserted download 9
08-30 12:24:20.861  3484  8302 V DownloadManager: processing inserted download 10
08-30 12:24:20.862  3484  8302 V DownloadManager: processing inserted download 11
08-30 12:24:20.863  3484  8302 V DownloadManager: processing inserted download 12
08-30 12:24:20.864  3484  8302 V DownloadManager: processing inserted download 13
08-30 12:24:20.864  3484  8302 V DownloadManager: processing inserted download 14
08-30 12:24:20.865  3484  8302 V DownloadManager: processing inserted download 16
08-30 12:24:20.868  3484  3484 V DownloadManager: DownloadService onDestroy
,08-30 12:24:20.894  8304  8304 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:24:20.894  8304  8304 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 12:24:20.896  8304  8304 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 12:24:20.896  8304  8304 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 12:24:20.960  8304  8304 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-30 12:24:20.985  8304  8304 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-30 12:24:21.047  8304  8304 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 12:24:21.087  8304  8304 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 12:24:21.088  8304  8304 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:24:21.269  8304  8304 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 12:24:21.341  3415  3415 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 12:24:21.341  3415  3415 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 12:24:21.341  3415  3415 I LgeMiscReceiver: networkInfo.isConnected() = true
08-30 12:24:21.341  3415  3415 D PhoneState: setPdpRejectCasuse : false
,08-30 12:24:21.351  8304  8304 I HubEmail: JNI_OnLoad()
08-30 12:24:21.351  8304  8304 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 12:24:21.351  8304  8304 I HubEmail: registerNatives()
08-30 12:24:21.351  8304  8304 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 12:24:21.351  8304  8304 I HubEmail: registerNativeMethods()
08-30 12:24:21.351  8304  8304 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 12:24:21.351  8304  8304 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-30 12:24:21.389  1035  1975 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8346 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-30 12:24:21.398  8304  8337 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 12:24:21.400   316  8362 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 12:24:21.400   316  8362 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,08-30 12:24:21.457   316  8362 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-30 12:24:21.500  8346  8346 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:24:21.500  8346  8346 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:24:21.507  8346  8346 D PhoneMonitor: Register our PhoneStateListener
08-30 12:24:21.531  8346  8346 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-30 12:24:21.533  8346  8346 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 12:24:21.553  8346  8346 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-30 12:24:21.554  8346  8346 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-30 12:24:21.555  8346  8346 D TelephonyAutoProfiling: [parse] Load xml
,08-30 12:24:21.558  8127  8336 V FormManager: There are no updated forms. The schedule will be deleted.
,08-30 12:24:21.560  8127  8336 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-30 12:24:21.561  8346  8346 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-30 12:24:21.562  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-30 12:24:21.562  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-30 12:24:21.562  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-30 12:24:21.562  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-30 12:24:21.562  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-30 12:24:21.562  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-30 12:24:21.562  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-30 12:24:21.562  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-30 12:24:21.563  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-30 12:24:21.563  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-30 12:24:21.563  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-30 12:24:21.563  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-30 12:24:21.563  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-30 12:24:21.563  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-30 12:24:21.563  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-30 12:24:21.563  8346  8346 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-30 12:24:21.571  8346  8346 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-30 12:24:21.588  1035  1050 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8371 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 12:24:21.590  1035  1050 I ActivityManager: Killing 7720:com.google.android.talk/u0a72 (adj 15): empty #17
08-30 12:24:21.632  1035  1993 W libprocessgroup: failed to open /acct/uid_10072/pid_7720/cgroup.procs: No such file or directory
,08-30 12:24:21.672  1035  1920 I ActivityManager: Killing 7772:com.android.contacts/u0a19 (adj 15): empty #17
,08-30 12:24:21.775   316  8390 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 12:24:21.775   316  8390 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
08-30 12:24:21.777  1035  1574 W libprocessgroup: failed to open /acct/uid_10019/pid_7772/cgroup.procs: No such file or directory
08-30 12:24:21.778  1815  8388 I CheckinService: active receiver: enabled
,08-30 12:24:21.792  1815  8388 I CheckinService: Preparing to send checkin request
08-30 12:24:21.792  1815  8388 I EventLogService: Accumulating logs since 1472552622436
08-30 12:24:21.809   316  8390 D libc-netbsd: res_queryN name = www.google.com succeed
,08-30 12:24:21.814   316  8393 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 12:24:21.815   316  8393 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-30 12:24:21.815   316  8393 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-30 12:24:21.850  1035  1956 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8394 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-30 12:24:21.851  1815  8388 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-30 12:24:21.852  1035  1956 I ActivityManager: Killing 7795:com.android.gallery3d/u0a27 (adj 15): empty #17
08-30 12:24:21.858  1035  1450 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
08-30 12:24:21.908  1035  1993 W libprocessgroup: failed to open /acct/uid_10027/pid_7795/cgroup.procs: No such file or directory
,08-30 12:24:22.052  1035  2045 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8414 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 12:24:22.105  1035  2029 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8431 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-30 12:24:22.107  1035  2045 I ActivityManager: Killing 7814:com.android.vending/u0a44 (adj 15): empty #17
,08-30 12:24:22.217  1035  1993 W libprocessgroup: failed to open /acct/uid_10044/pid_7814/cgroup.procs: No such file or directory
,08-30 12:24:22.250  8414  8414 I art     : Almond Protected OAT
,08-30 12:24:22.274  8431  8431 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-30 12:24:22.274  8431  8431 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-30 12:24:22.292  1035  1437 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-30 12:24:22.292  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-30 12:24:22.293  1035  1437 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-30 12:24:22.293  1035  1437 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-30 12:24:22.294  1035  1437 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-30 12:24:22.294  1035  1437 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-30 12:24:22.307  8414  8414 D WeatherApplication: removeAccount
,08-30 12:24:22.309  8414  8414 D WeatherApplication: Account.length = 0
08-30 12:24:22.310  8414  8414 E WeatherApplication: OPERATOR:OPEN
08-30 12:24:22.315  8414  8414 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:24:22
08-30 12:24:22.318  8414  8414 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 12:24:22.318  8431  8431 I MultiDex: VM with version 2.1.0 has multidex support
08-30 12:24:22.318  8414  8414 D Weather.Utils: 2 : All the weather widget is gone.
08-30 12:24:22.318  8431  8431 I MultiDex: install
08-30 12:24:22.318  8431  8431 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-30 12:24:22.321  8414  8414 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 12:24:22.323  8414  8414 D WeatherAncestor: connectivity changed - connection : true
08-30 12:24:22.324  8414  8414 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-30 12:24:22.334  8431  8431 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-30 12:24:22.339  8414  8414 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 12:24:22.339  8414  8414 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 12:24:22.339  8414  8414 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-30 12:24:22.363  8414  8414 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 12:24:22.363  8414  8414 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:24:22
,08-30 12:24:22.414  1035  1993 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8451 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 12:24:22.419  1035  1993 I ActivityManager: Killing 7855:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-30 12:24:22.457  1035  2045 W libprocessgroup: failed to open /acct/uid_10080/pid_7855/cgroup.procs: No such file or directory
,08-30 12:24:22.572   280   444 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 12:24:22.572   280   444 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 12:24:22.572   280   444 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 12:24:22.573  8451  8469 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-30 12:24:22.580   280   444 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 12:24:22.580   280   444 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 12:24:22.580   280   444 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 12:24:22.581  8451  8469 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-30 12:24:22.597   280   444 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 12:24:22.597   280   444 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 12:24:22.597   280   444 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 12:24:22.598  8451  8473 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-30 12:24:22.600   280   444 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 12:24:22.600   280   444 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 12:24:22.600   280   444 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 12:24:22.600  8451  8473 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-30 12:24:22.799  8451  8451 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-30 12:24:22.810  8451  8451 I LibraryLoader: Loading: webviewchromium
08-30 12:24:22.814  8451  8451 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 54-58)
08-30 12:24:22.814  8451  8451 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 12:24:22.821  8451  8451 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {694285e}
08-30 12:24:22.823  8451  8451 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 12:24:22.824  8451  8451 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 12:24:22.831  8431  8447 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 12:24:22.831  8431  8447 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:24:22.848  8451  8451 I BrowserStartupController: Initializing chromium process, renderers=0
08-30 12:24:22.849  8451  8451 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 12:24:22.862  8451  8451 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-30 12:24:22.863  8451  8451 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-30 12:24:22.863  8451  8451 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-30 12:24:22.869   322  2132 V AudioPolicyService: registerClient() client 0xb558aba0, uid 10093
08-30 12:24:22.870  8451  8493 W AudioManagerAndroid: Requires BLUETOOTH permission
08-30 12:24:22.883  8451  8451 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 12:24:22.883  8451  8451 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 12:24:22.883  8451  8451 I Adreno-EGL: Build Date: 12/12/14 금
08-30 12:24:22.883  8451  8451 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 12:24:22.883  8451  8451 I Adreno-EGL: Remote Branch: 
08-30 12:24:22.883  8451  8451 I Adreno-EGL: Local Patches: 
08-30 12:24:22.883  8451  8451 I Adreno-EGL: Reconstruct Branch: 
,08-30 12:24:23.048  8506  8506 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-30 12:24:23.128  8506  8506 I dex2oat : dex2oat took 79.321ms (threads: 4)
,08-30 12:24:23.140  1035  2029 I art     : Explicit concurrent mark sweep GC freed 79909(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.385ms total 159.849ms
08-30 12:24:23.141  8451  8451 I NSApplication: Starting up...
08-30 12:24:23.147  8431  8447 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 12:24:23.147  8431  8447 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 12:24:23.147  8431  8447 I Adreno-EGL: Build Date: 12/12/14 금
08-30 12:24:23.147  8431  8447 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 12:24:23.147  8431  8447 I Adreno-EGL: Remote Branch: 
08-30 12:24:23.147  8431  8447 I Adreno-EGL: Local Patches: 
08-30 12:24:23.147  8431  8447 I Adreno-EGL: Reconstruct Branch: 
,08-30 12:24:23.170  1035  2029 I ActivityManager: Killing 7581:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-30 12:24:23.270  1035  1885 W libprocessgroup: failed to open /acct/uid_10037/pid_7581/cgroup.procs: No such file or directory
,08-30 12:24:23.289  2205  2205 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-30 12:24:23.306  2205  2205 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-30 12:24:23.306  2205  2205 D c       : Getting all permits...
08-30 12:24:23.306  2205  2205 D a       : Opening database...
08-30 12:24:23.310  2205  2205 D a       : Opening database auth.proximity.permit_store...
08-30 12:24:23.310  8431  8447 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 12:24:23.310  8431  8447 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 12:24:23.310  8431  8447 I Adreno-EGL: Build Date: 12/12/14 금
08-30 12:24:23.310  8431  8447 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 12:24:23.310  8431  8447 I Adreno-EGL: Remote Branch: 
08-30 12:24:23.310  8431  8447 I Adreno-EGL: Local Patches: 
08-30 12:24:23.310  8431  8447 I Adreno-EGL: Reconstruct Branch: 
08-30 12:24:23.311  2205  2205 D a       : Closing database...
,08-30 12:24:23.480  8431  8447 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 12:24:23.480  8431  8447 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 12:24:23.480  8431  8447 I Adreno-EGL: Build Date: 12/12/14 금
08-30 12:24:23.480  8431  8447 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 12:24:23.480  8431  8447 I Adreno-EGL: Remote Branch: 
08-30 12:24:23.480  8431  8447 I Adreno-EGL: Local Patches: 
08-30 12:24:23.480  8431  8447 I Adreno-EGL: Reconstruct Branch: 
,08-30 12:24:23.541  1035  1437 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2437 sc=60 link=72 tx=41.2, 0.0, 0.0  rx=35.5 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-621118987] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 12:24:23.545  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2437 sc=60 link=72 tx=41.2, 0.0, 0.0  rx=35.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-621118984] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 12:24:23.545  1035  1437 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 12:24:23.683  6741  8278 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-30 12:24:23.683  6741  8278 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-30 12:24:23.684  6741  8278 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 12:24:23.684  6741  8278 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 12:24:23.684  6741  8278 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-30 12:24:23.684  6741  8519 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-30 12:24:23.684  6741  8519 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-30 12:24:23.684  6741  8519 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 12:24:23.685  6741  8519 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 12:24:23.685  6741  8519 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-30 12:24:23.686  6741  8524 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 870, name: IncomingSocketThread/Receiver)
08-30 12:24:23.686  6741  8524 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 870, thread name: IncomingSocketThread/Receiver)
08-30 12:24:23.686  6741  8524 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-30 12:24:23.687  6741  8524 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 870, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-30 12:24:23.688  6741  8523 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 869, name: IncomingSocketThread/Sender)
08-30 12:24:23.688  6741  8522 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 868, name: OutgoingSocketThread/Receiver)
08-30 12:24:23.689  6741  8522 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 868, thread name: OutgoingSocketThread/Receiver)
08-30 12:24:23.689  6741  8522 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 12:24:23.689  6741  8522 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 868, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-30 12:24:23.690  6741  8521 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 867, name: OutgoingSocketThread/Sender)
08-30 12:24:23.693   316  8526 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 12:24:23.693   316  8526 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-30 12:24:23.734   316  8526 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-30 12:24:23.826  1815  8388 I CheckinTask: Sending checkin request (7855 bytes)
,08-30 12:24:24.040  1815  8388 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-30 12:24:24.057  1815  8388 I CheckinService: active receiver: disabled
,08-30 12:24:24.087  2205  2205 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-30 12:24:24.105  2205  2205 I GCM     : GCM config loaded
,08-30 12:24:24.126  8346  8346 V SetupWizard: Connected to Gservices successfully
,08-30 12:24:24.138   316  8533 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-30 12:24:24.140   316  8533 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-30 12:24:24.140   316  8533 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-30 12:24:24.432  2205  8535 D GCM     : Connected
,08-30 12:24:24.466  2205  8535 D GCM     : Message class com.google.e.a.a.q
,08-30 12:24:26.564  1035  1437 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=30.6, 0.0, 0.0  rx=25.2 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-621115964] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 12:24:26.577  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=30.6, 0.0, 0.0  rx=25.2 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-621115951] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 12:24:26.577  1035  1437 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 12:24:26.696  6741  6802 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-30 12:24:26.697  6741  6802 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-30 12:24:26.699  6741  6802 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2c572361 Bundle[{}]
08-30 12:24:26.700  6741  6802 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 12:24:26.700  6741  6802 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 12:24:26.701  6741  6802 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-30 12:24:26.702  6741  6802 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 12:24:26.702  6741  6802 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-30 12:24:26.703  6741  6802 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 12:24:26.721  6741  6802 I System.out: Running OutgoingSocketThread
,08-30 12:24:26.726  6741  8536 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-30 12:24:26.726  6741  8536 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-30 12:24:27.593  8451  8471 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-30 12:24:28.684  1035  1975 I ActivityManager: Killing 7630:com.lge.settings.easy/1000 (adj 15): empty #17
,08-30 12:24:28.723  1035  1993 W libprocessgroup: failed to open /acct/uid_1000/pid_7630/cgroup.procs: No such file or directory
,08-30 12:24:29.597  1035  1437 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=25.8, 0.0, 0.0  rx=21.6 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-621112931] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 12:24:29.600  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=25.8, 0.0, 0.0  rx=21.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-621112928] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 12:24:29.600  1035  1437 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 12:24:29.739  6741  8536 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-30 12:24:29.739  6741  8536 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-30 12:24:29.739  6741  8536 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 12:24:29.740  6741  8536 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 12:24:29.740  6741  8536 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-30 12:24:29.749  6741  8539 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-30 12:24:29.749  6741  8539 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-30 12:24:29.749  6741  8539 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 12:24:29.749  6741  8539 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 12:24:29.751  6741  8542 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 880, name: OutgoingSocketThread/Receiver)
08-30 12:24:29.752  6741  8542 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 880, thread name: OutgoingSocketThread/Receiver)
08-30 12:24:29.752  6741  8542 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 12:24:29.752  6741  8542 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 880, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-30 12:24:29.753  6741  8539 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-30 12:24:29.755  6741  8541 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 879, name: OutgoingSocketThread/Sender)
08-30 12:24:29.756  6741  8543 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 881, name: IncomingSocketThread/Sender)
08-30 12:24:29.758  6741  8544 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 882, name: IncomingSocketThread/Receiver)
08-30 12:24:29.758  6741  8544 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 882, thread name: IncomingSocketThread/Receiver)
08-30 12:24:29.758  6741  8544 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-30 12:24:29.758  6741  8544 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 882, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-30 12:24:31.855  1035  1380 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 12:24:31.861  1601  1601 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
08-30 12:24:31.977  1035  1113 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8545 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-30 12:24:31.987  1035  1035 D administrator: Handling package changes for user 0
08-30 12:24:31.991   356   356 I art     : Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 476us total 49.726ms
08-30 12:24:32.012   356   356 I art     : Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 437us total 20.325ms
08-30 12:24:32.024  1601  1601 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-30 12:24:32.027  1601  1601 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-30 12:24:32.032  2030  2030 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-30 12:24:32.033   356   356 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 415us total 20ms
08-30 12:24:32.038  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 12:24:32.057  8545  8545 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 12:24:32.086  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-30 12:24:32.086  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-30 12:24:32.148  8545  8545 D LgDataFeature: LgDataFeature() Constructor: none
08-30 12:24:32.149  8545  8545 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 12:24:32.156  1035  1112 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:24:32.162  1035  1112 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-30 12:24:32.172  2030  2030 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-30 12:24:32.173  2503  2503 V GmsNetworkLocationProvi: DISABLE
08-30 12:24:32.200  1035  1112 D LocationProviderProxy: applying state to connected service
,08-30 12:24:32.202  2503  2503 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-30 12:24:32.280  8545  8590 I Babel   : MmsConfig: mnc/mcc: 0/0
08-30 12:24:32.280  8545  8590 I Babel   : MmsConfig.loadMmsSettings
,08-30 12:24:32.286  8545  8590 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-30 12:24:32.286  8545  8590 I Babel   : MmsConfig.loadFromDatabase
,08-30 12:24:32.306  8545  8590 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-30 12:24:32.306  8545  8590 I Babel   : MmsConfig.loadFromResources
08-30 12:24:32.312  8545  8590 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-30 12:24:32.312  8545  8590 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-30 12:24:32.331  8545  8545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 12:24:32.349  8545  8588 W AudioCapabilities: Unsupported mime audio/evrc
08-30 12:24:32.352  8545  8588 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 12:24:32.354  8545  8588 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 12:24:32.361  7038  7038 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 12:24:32.362  1815  8593 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-30 12:24:32.363  1815  8593 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-30 12:24:32.365  7038  7038 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@175ac657
08-30 12:24:32.365  7038  7038 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 12:24:32.365  7038  7038 D AppUp4:CustFacade: isPhone : true
08-30 12:24:32.366  7038  7038 D AppUp4:CustModeStarterReceiver: begin check event
08-30 12:24:32.366  7038  7038 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-30 12:24:32.367  8545  8588 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-30 12:24:32.370  8545  8588 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 12:24:32.371  8545  8588 W AudioCapabilities: Unsupported mime audio/evrc
,08-30 12:24:32.387  8545  8588 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-30 12:24:32.390  8545  8588 W VideoCapabilities: Unsupported mime video/divx
08-30 12:24:32.392  8545  8588 W VideoCapabilities: Unsupported mime video/divx311
08-30 12:24:32.394  8545  8588 W VideoCapabilities: Unsupported mime video/divx4
,08-30 12:24:32.401  8545  8588 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-30 12:24:32.412  1035  2029 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8596 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-30 12:24:32.418  1035  2029 I ActivityManager: Killing 8177:com.lge.bnr/1000 (adj 15): empty #17
08-30 12:24:32.435  1815  4733 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-30 12:24:32.445  8545  8588 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-30 12:24:32.449  8545  8588 W AudioCapabilities: Unsupported mime audio/eac3
08-30 12:24:32.450  8545  8588 W AudioCapabilities: Unsupported mime audio/ac3
,08-30 12:24:32.451  8545  8588 W AudioCapabilities: Unsupported mime audio/g726
08-30 12:24:32.452  8545  8588 W AudioCapabilities: Unsupported mime audio/wma-voice
08-30 12:24:32.453  8545  8588 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-30 12:24:32.454  8545  8588 W AudioCapabilities: Unsupported mime audio/adpcm
08-30 12:24:32.456  8545  8588 W VideoCapabilities: Unsupported mime video/theora
08-30 12:24:32.457  8545  8588 W VideoCapabilities: Unsupported mime video/mjpg
08-30 12:24:32.517  1035  1957 W libprocessgroup: failed to open /acct/uid_1000/pid_8177/cgroup.procs: No such file or directory
,08-30 12:24:32.534  8596  8596 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:24:32.534  8596  8596 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 12:24:32.534  8596  8596 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 12:24:32.535  8596  8596 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,08-30 12:24:32.536  8596  8596 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-30 12:24:32.628  1035  1437 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=13.4, 0.0, 0.0  rx=10.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-621109900] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 12:24:32.630  8596  8596 I SystemConfig: BUILD Country: EU
08-30 12:24:32.630  8596  8596 I SystemConfig: BUILD Operator: OPEN
08-30 12:24:32.631  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=13.4, 0.0, 0.0  rx=10.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-621109897] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 12:24:32.631  1035  1437 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 12:24:32.680  1035  1574 I ActivityManager: Killing 8150:com.lge.sync/1000 (adj 15): empty #17
,08-30 12:24:32.737  6741  6802 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 891)
08-30 12:24:32.739  6741  6802 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-30 12:24:32.739  6741  6802 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 892)
08-30 12:24:32.748  6741  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 12:24:32.748  6741  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f3736ee added. We now have 3 listener(s)
08-30 12:24:32.855  1035  1993 W libprocessgroup: failed to open /acct/uid_1000/pid_8150/cgroup.procs: No such file or directory
,08-30 12:24:32.863  1035  1884 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 12:24:32.873  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 12:24:32.873  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:24:32.873  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:24:32.874  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:24:32.874  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@753178f added. We now have 4 listener(s)
08-30 12:24:32.877  6741  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:24:32.878  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 12:24:32.879  8596  8614 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-30 12:24:32.880  8596  8614 I SystemConfig: existFile = false
08-30 12:24:32.880  8596  8614 I SystemConfig: canReadFile = false
08-30 12:24:32.881  8596  8614 I SystemConfig: systemFeature RCS result false
08-30 12:24:32.881  8596  8614 D SystemConfig: refreshRcsSupport() :false
,08-30 12:24:32.931  1035  1574 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8619 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-30 12:24:32.938  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:24:32.943  6741  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:24:32.943  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:24:32.943  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:24:32.943  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:24:32.943  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:24:32.943  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:24:32.943  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:24:32.943  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:24:32.945  6741  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:24:32.945  6741  6802 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:24:32.947  6741  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:24:32.947  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 12:24:32.947  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:24:32.948  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:24:32.948  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:24:32.948  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:24:32.948  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 12:24:32.948  6741  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f3736ee removed from the list
08-30 12:24:32.948  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:24:32.948  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@753178f removed from the list
08-30 12:24:32.950  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:24:32.952  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:24:32.952  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:24:32.952  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:24:32.953  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:24:32.953  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:24:32.954  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:24:32.954  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:24:32.954  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:24:32.954  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@753178f not in the list
08-30 12:24:32.954  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:24:32.954  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:24:32.955  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:24:32.955  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:24:32.955  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:24:32.955  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@753178f not in the list
08-30 12:24:32.955  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:24:32.955  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:24:32.955  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:24:32.955  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f3736ee not in the list
08-30 12:24:32.956  6741  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 12,:24:32.956  6741  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@179ac625 added. We now have 3 listener(s)
08-30 12:24:32.957  1035  1920 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:24:32.960  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 12:24:32.960  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:24:32.960  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:24:32.960  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:24:32.960  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ae3d3fa added. We now have 4 listener(s)
08-30 12:24:32.960  6741  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:24:32.960  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 12:24:32.964  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:24:32.968  6741  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:24:32.968  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:24:32.968  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:24:32.968  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:24:32.968  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:24:32.968  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:24:32.968  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:24:32.968  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:24:32.974  6741  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:24:32.974  6741  6802 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:24:32.975  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 12:24:32.975  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 12:24:32.975  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 12:24:32.975  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:24:32.975  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 12:24:32.977  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:24:32.979  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:24:32.981  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 12:24:32.981  1035  1725 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:24:32.986  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 12:24:32.986  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 12:24:32.988  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 12:24:32.989  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:24:32.991  6741  6802 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 12:24:32.991  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:24:32.991  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:24:33.001  8619  8619 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 12:24:33.001  8619  8619 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 12:24:33.001  8619  8619 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 12:24:33.002  8619  8619 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-30 12:24:33.117  8619  8619 I AppConfig: Total System Memory = 2995761152
,08-30 12:24:33.128  8619  8619 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-30 12:24:33.220  1035  1725 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8638 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 12:24:33.221  1035  1725 I ActivityManager: Killing 6656:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-30 12:24:33.257  6909  6909 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-30 12:24:33.257  6909  6909 W System.err: android.os.DeadObjectException
08-30 12:24:33.258  6909  6909 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 12:24:33.258  6909  6909 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 12:24:33.258  6909  6909 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-30 12:24:33.258  6909  6909 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-30 12:24:33.258  6909  6909 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 12:24:33.258  6909  6909 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 12:24:33.258  6909  6909 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 12:24:33.258  6909  6909 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 12:24:33.258  6909  6909 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:24:33.258  6909  6909 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 12:24:33.258  6909  6909 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:24:33.258  6909  6909 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:24:33.258  6909  6909 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 12:24:33.258  6909  6909 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 12:24:33.259  6909  6909 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-30 12:24:33.259  6909  6909 W System.err: android.os.DeadObjectException
08-30 12:24:33.259  6909  6909 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 12:24:33.259  6909  6909 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 12:24:33.259  6909  6909 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-30 12:24:33.259  6909  6909 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-30 12:24:33.259  6909  6909 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 12:24:33.259  6909  6909 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 12:24:33.259  6909  6909 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 12:24:33.259  6909  6909 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 12:24:33.259  6909  6909 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:24:33.259  6909  6909 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 12:24:33.260  6909  6909 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:24:33.260  6909  6909 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:24:33.260  6909  6909 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 12:24:33.260  6909  6909 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 12:24:33.260  6909  6909 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-30 12:24:33.260  6909  6909 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-30 12:24:33.329  1035  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_6656/cgroup.procs: No such file or directory
,08-30 12:24:33.330  1035  1051 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-30 12:24:33.338  6909  6909 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-30 12:24:33.338  6909  6909 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-30 12:24:33.432  1035  1885 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8656 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 12:24:33.434  6909  6909 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-30 12:24:33.517  8656  8656 D UEI.SmartControl: Quickset Services start...
08-30 12:24:33.519  8656  8656 I UEI.SmartControl: Manufacture = LGE
08-30 12:24:33.519  8656  8656 D UEI.SmartControl: Id = LGNevo
08-30 12:24:33.522  8656  8656 D UEI.SmartControl: File observer start...
08-30 12:24:33.523  8656  8656 E UEI.SmartControl: IR Port is disabled: false
08-30 12:24:33.524  8656  8656 D UEI.SmartControl: Starting file observer...
08-30 12:24:33.524  8656  8656 D UEI.SmartControl: Extracting JNI libs...
08-30 12:24:33.525  8656  8656 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-30 12:24:33.615  8638  8638 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-30 12:24:33.650  8656  8656 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-30 12:24:33.650  8656  8656 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-30 12:24:33.651  8656  8656 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-30 12:24:33.688  8656  8656 I UEI.SmartControl: --- Selecting new region: 6
,08-30 12:24:33.691  8656  8656 I UEI.SmartControl: Model = LG-D855
08-30 12:24:33.692  8656  8656 D UEI.SmartControl: QS Service created
08-30 12:24:33.704  8638  8638 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 12:24:33.704  8638  8638 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 12:24:33.708  8656  8656 I UEI.SmartControl: Service initServices...
08-30 12:24:33.712  8656  8656 D UEI.SmartControl: QS start get config
,08-30 12:24:33.751  8638  8638 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-30 12:24:33.765  8656  8656 D UEI.SmartControl: Loading JNI Libs...
,08-30 12:24:33.780  8638  8638 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 12:24:33.782  8638  8638 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 12:24:33.799  8638  8638 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 12:24:33.800  8638  8638 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-30 12:24:33.815  1035  1957 I ActivityManager: Killing 6850:com.android.settings/1000 (adj 15): empty #17
,08-30 12:24:33.880  1035  1885 W libprocessgroup: failed to open /acct/uid_1000/pid_6850/cgroup.procs: No such file or directory
,08-30 12:24:33.895  4590  8693 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-30 12:24:33.946  1035  1956 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8694 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-30 12:24:33.957  3484  3499 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-30 12:24:33.958  3484  3499 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@df5bc72 on behalf of 8638
08-30 12:24:33.972  8638  8638 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-30 12:24:33.992  8638  8638 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-30 12:24:34.025  8694  8694 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-30 12:24:34.031  8656  8656 I UEI.SmartControl: Supports setup maps: true
08-30 12:24:34.038  8656  8656 D UEI.SmartControl: QS start statue = true Error code = 0
,08-30 12:24:34.038  8656  8656 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 12:24:34.038  8656  8656 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 12:24:34.038  8656  8656 I UEI.SmartControl: ### init IR Blaster...
,08-30 12:24:34.044  8656  8656 D serial_port: Configuring serial port
08-30 12:24:34.047  8694  8694 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-30 12:24:34.047  8694  8694 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-30 12:24:34.047  8694  8694 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-30 12:24:34.047  8694  8694 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-30 12:24:34.047  8694  8694 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-30 12:24:34.047  8694  8694 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-30 12:24:34.050  8656  8656 E UEI.SmartControl: UEIBLaster setting for 616
08-30 12:24:34.050  8656  8656 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 12:24:34.051  8656  8656 I UEI.SmartControl: configuring settings for MAXQ616
08-30 12:24:34.051  8656  8656 I UEI.SmartControl: Get version...
08-30 12:24:34.061  1035  1725 I ActivityManager: Killing 6909:com.lge.qremote/u0a112 (adj 15): empty #17
,08-30 12:24:34.067  8656  8718 D UEI.SmartControl: serial port data available: 21
,08-30 12:24:34.090  1035  1050 W libprocessgroup: failed to open /acct/uid_10112/pid_6909/cgroup.procs: No such file or directory
,08-30 12:24:34.094  8656  8656 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-30 12:24:34.094  8656  8656 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 12:24:34.095  8656  8656 I UEI.SmartControl: QS saving settings...
08-30 12:24:34.095  8656  8656 D UEI.SmartControl: IR Blaster version: 25672567
08-30 12:24:34.111  8656  8718 D UEI.SmartControl: serial port data available: 4
,08-30 12:24:34.145  8656  8724 I UEI.SmartControl: Device manager: loading config....
08-30 12:24:34.145  8656  8724 D UEI.SmartControl: ----------- loading internal config...
,08-30 12:24:34.146  8656  8656 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 12:24:34.152  8656  8656 E UEI.SmartControl: Services init done
08-30 12:24:34.152  8656  8656 D UEI.SmartControl: QS Service init finished
08-30 12:24:34.153  8656  8656 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 12:24:34.153  8656  8656 D UEI.SmartControl: QS Service version code: 201091
08-30 12:24:34.154  8656  8724 E UEI.SmartControl: Loading SETTINGS...
08-30 12:24:34.156  8656  8656 D UEI.SmartControl: Service requested: Control
08-30 12:24:34.157  8656  8656 D UEI.SmartControl: Service.onUnbind: IControl
08-30 12:24:34.158  8656  8656 D UEI.SmartControl: Service.onDestroy
08-30 12:24:34.158  8656  8656 D UEI.SmartControl: Lock is in USE false
08-30 12:24:34.159  8656  8656 D UEI.SmartControl: unbind internal service
,08-30 12:24:34.161  8656  8656 D serial_port: close(fd = 25)
08-30 12:24:34.162  8656  8724 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 12:24:34.164  8656  8723 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 12:24:34.164  8656  8723 D UEI.SmartControl: -----service ready thread exits
08-30 12:24:34.164  8656  8656 I UEI.SmartControl: Serial port is closed.
08-30 12:24:34.165  8656  8656 I UEI.SmartControl: Serial port is closed.
08-30 12:24:34.165  8656  8656 D UEI.SmartControl: Blaster closed
08-30 12:24:34.165  8656  8656 D UEI.SmartControl: Shut down QS...
08-30 12:24:34.165  8656  8656 D UEI.SmartControl: Stopping QS lib
08-30 12:24:34.165  8656  8656 D UEI.SmartControl: QS lib stop result = true
08-30 12:24:34.166  8656  8656 D UEI.SmartControl: Stopped QS lib
08-30 12:24:34.167  8656  8656 D UEI.SmartControl: Stopped file observer...
08-30 12:24:34.167  8656  8656 D UEI.SmartControl: QS shutdown complete
08-30 12:24:34.169  8656  8656 D UEI.SmartControl: QS Service created
,08-30 12:24:34.204  8656  8656 I UEI.SmartControl: Service initServices...
08-30 12:24:34.204  8656  8656 D UEI.SmartControl: QS start get config
,08-30 12:24:34.258  1035  1725 V SIM_STK : Menu title from STK is T-Mobile
,08-30 12:24:34.271  4590  8693 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 375 ms] updated apps [took 375 ms] 
08-30 12:24:34.523  8656  8656 I UEI.SmartControl: Supports setup maps: true
,08-30 12:24:34.529  8656  8656 D UEI.SmartControl: QS start statue = true Error code = 0
,08-30 12:24:34.529  8656  8656 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-30 12:24:34.529  8656  8656 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 12:24:34.529  8656  8656 I UEI.SmartControl: ### init IR Blaster...
08-30 12:24:34.533  8656  8656 D serial_port: Configuring serial port
08-30 12:24:34.533  8656  8656 E UEI.SmartControl: UEIBLaster setting for 616
08-30 12:24:34.533  8656  8656 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 12:24:34.533  8656  8656 I UEI.SmartControl: configuring settings for MAXQ616
08-30 12:24:34.533  8656  8656 I UEI.SmartControl: Get version...
08-30 12:24:34.552  8656  8730 D UEI.SmartControl: serial port data available: 21
,08-30 12:24:34.578  8656  8656 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-30 12:24:34.579  8656  8656 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 12:24:34.579  8656  8656 I UEI.SmartControl: QS saving settings...
,08-30 12:24:34.581  8656  8656 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 12:24:34.599  8656  8730 D UEI.SmartControl: serial port data available: 4
,08-30 12:24:34.629  8656  8656 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-30 12:24:34.640  8656  8656 E UEI.SmartControl: Services init done
08-30 12:24:34.640  8656  8656 D UEI.SmartControl: QS Service init finished
08-30 12:24:34.642  8656  8656 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 12:24:34.642  8656  8656 D UEI.SmartControl: QS Service version code: 201091
08-30 12:24:34.646  8656  8656 D UEI.SmartControl: Service requested: Control
,08-30 12:24:34.650  8656  8739 I UEI.SmartControl: Device manager: loading config....
08-30 12:24:34.651  8656  8739 D UEI.SmartControl: ----------- loading internal config...
08-30 12:24:34.655  8656  8739 E UEI.SmartControl: Loading SETTINGS...
08-30 12:24:34.655  8656  8656 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 12:24:34.659  1035  1884 I ActivityManager: Killing 8304:com.lge.email/u0a23 (adj 15): empty #17
,08-30 12:24:34.678  8656  8739 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-30 12:24:34.691  8656  8738 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 12:24:34.691  8656  8738 D UEI.SmartControl: -----service ready thread exits
08-30 12:24:34.718  1035  1885 W libprocessgroup: failed to open /acct/uid_10023/pid_8304/cgroup.procs: No such file or directory
,08-30 12:24:34.728  8656  8656 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@33db70f3 that was originally bound here
08-30 12:24:34.728  8656  8656 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@33db70f3 that was originally bound here
08-30 12:24:34.728  8656  8656 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-30 12:24:34.728  8656  8656 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-30 12:24:34.728  8656  8656 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-30 12:24:34.728  8656  8656 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-30 12:24:34.728  8656  8656 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-30 12:24:34.728  8656  8656 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-30 12:24:34.728  8656  8656 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-30 12:24:34.728  8656  8656 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-30 12:24:34.728  8656  8656 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-30 12:24:34.728  8656  8656 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-30 12:24:34.728  8656  8656 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-30 12:24:34.728  8656  8656 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:24:34.728  8656  8656 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:24:34.728  8656  8656 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 12:24:34.728  8656  8656 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:24:34.728  8656  8656 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:24:34.728  8656  8656 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 12:24:34.728  8656  8656 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 12:24:34.746  8656  8656 D UEI.SmartControl: Internal service binding...
,08-30 12:24:35.158  8656  8726 D UEI.SmartControl: Internal timer expired: 2
,08-30 12:24:35.654  1035  1437 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=6.7, 0.0, 0.0  rx=5.4 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-621106874] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 12:24:35.664  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=6.7, 0.0, 0.0  rx=5.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-621106864] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 12:24:35.664  1035  1437 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 12:24:35.992  6741  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:24:35.992  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:24:35.992  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:24:36.003  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:24:36.004  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:24:36.004  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:24:36.004  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 12:24:36.004  6741  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@179ac625 removed from the list
08-30 12:24:36.004  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:24:36.004  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ae3d3fa removed from the list
08-30 12:24:36.004  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:24:36.005  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:24:36.007  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:24:36.007  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:24:36.011  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:24:36.011  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:24:36.017  6741  6802 D BluetoothLeScanner: could not find callback wrapper
08-30 12:24:36.017  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:24:36.017  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:24:36.017  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ae3d3fa not in the list
08-30 12:24:36.017  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:24:36.017  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:24:36.021  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:24:36.022  6741  6802 D BluetoothLeScanner: could not find callback wrapper
08-30 12:24:36.022  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:24:36.022  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:24:36.022  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:24:36.022  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ae3d3fa not in the list
08-30 12:24:36.022  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:24:36.022  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:24:36.022  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:24:36.022  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@179ac625 not in the list
08-30 12:24:36.023  6741  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 12:24:36.023  6741  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@98b35c6 added. We now have 3 listener(s)
08-30 12:24:36.024  1035  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:24:36.027  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 12:24:36.027  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:24:36.027  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:24:36.027  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:24:36.027  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17cc6987 added. We now have 4 listener(s)
08-30 12:24:36.027  6741  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:24:36.029  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 12:24:36.036  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:24:36.040  6741  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:24:36.040  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:24:36.040  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:24:36.040  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:24:36.040  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:24:36.040  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:24:36.040  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:24:36.040  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:24:36.043  6741  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:24:36.043  6741  6802 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 12:24:36.048  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:24:36.050  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:24:36.051  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 12:24:36.052  6741  6802 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-30 12:24:36.052  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-30 12:24:36.055  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 12:24:36.055  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-30 12:24:36.055  6741  6802 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 12:24:36.055  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 12:24:36.060  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 12:24:36.061  6741  6802 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 12:24:36.061  6741  6802 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 12:24:36.062  6741  6741 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 12:24:36.063  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 12:24:36.063  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-30 12:24:36.063  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:24:36.063  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 12:24:36.069  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 12:24:36.073  1035  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:24:36.078  1035  1920 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:24:36.079  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 12:24:36.080  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 12:24:36.081  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 12:24:36.083  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-30 12:24:36.086  6741  6802 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 12:24:36.088  6741  8741 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 12:24:36.089  7946  7961 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-30 12:24:36.090  6741  8741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-30 12:24:38.525  8656  8667 E UEI.SmartControl: file observer is disposed!
,08-30 12:24:38.685  1035  1437 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-621103843] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-30 12:24:38.696  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-621103833] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-30 12:24:38.696  1035  1437 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 12:24:39.092  6741  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:24:39.092  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:24:39.092  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 12:24:39.092  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 12:24:39.093  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 12:24:39.093  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-30 12:24:39.105  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:24:39.105  6741  6802 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 12:24:39.106  6741  8741 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 12:24:39.106  6741  8741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 12:24:39.106  6741  8741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 12:24:39.107  6741  6741 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 12:24:39.109  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 12:24:39.110  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:24:39.110  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:24:39.117  6741  6741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:24:39.118  6741  6741 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-30 12:24:39.118  6741  6741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-30 12:24:39.121  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:24:39.121  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:24:39.121  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:24:39.121  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 12:24:39.121  6741  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@98b35c6 removed from the list
08-30 12:24:39.121  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:24:39.121  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17cc6987 removed from the list
08-30 12:24:39.121  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:24:39.121  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:24:39.123  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:24:39.123  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:24:39.124  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:24:39.124  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:24:39.126  6741  6802 D BluetoothLeScanner: could not find callback wrapper
08-30 12:24:39.126  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:24:39.126  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:24:39.126  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17cc6987 not in the list
08-30 12:24:39.126  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:24:39.126  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:24:39.127  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:24:39.128  6741  6802 D BluetoothLeScanner: could not find callback wrapper
08-30 12:24:39.128  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:24:39.128  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:24:39.128  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:24:39.128  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17cc6987 not in the list
08-30 12:24:39.128  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:24:39.128  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:24:39.128  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:24:39.128  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@98b35c6 not in the list
08-30 12:24:39.129  6741  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 12:24:39.129  6741 , 6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7c1723 added. We now have 3 listener(s)
08-30 12:24:39.130  1035  1784 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:24:39.132  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 12:24:39.132  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:24:39.132  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:24:39.132  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:24:39.133  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f4b420 added. We now have 4 listener(s)
08-30 12:24:39.133  6741  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:24:39.138  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 12:24:39.143  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:24:39.147  6741  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:24:39.147  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:24:39.147  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:24:39.147  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:24:39.147  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:24:39.147  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:24:39.147  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:24:39.147  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:24:39.151  6741  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:24:39.151  6741  6802 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:24:39.154  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:24:39.156  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:24:39.157  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 12:24:39.157  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 12:24:39.157  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 12:24:39.157  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:24:39.157  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 12:24:39.161  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 12:24:39.163  1035  1885 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:24:39.168  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 12:24:39.169  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 12:24:39.170  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 12:24:39.171  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:24:39.173  6741  6802 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-30 12:24:39.628  8656  8740 D UEI.SmartControl: Internal timer expired: 3
,08-30 12:24:39.628  8656  8740 D UEI.SmartControl: unbind internal service
,08-30 12:24:39.648  8656  8656 D UEI.SmartControl: Service.onUnbind: IControl
,08-30 12:24:39.651  8656  8656 D UEI.SmartControl: Service.onDestroy
08-30 12:24:39.651  8656  8656 D UEI.SmartControl: Lock is in USE false
08-30 12:24:39.651  8656  8656 D UEI.SmartControl: unbind internal service
08-30 12:24:39.652  8656  8656 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2ae460ba
08-30 12:24:39.653  8656  8656 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-30 12:24:39.653  8656  8656 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-30 12:24:39.653  8656  8656 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-30 12:24:39.653  8656  8656 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-30 12:24:39.653  8656  8656 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-30 12:24:39.653  8656  8656 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-30 12:24:39.653  8656  8656 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-30 12:24:39.653  8656  8656 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-30 12:24:39.653  8656  8656 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:24:39.653  8656  8656 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:24:39.653  8656  8656 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 12:24:39.653  8656  8656 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:24:39.653  8656  8656 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:24:39.653  8656  8656 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 12:24:39.653  8656  8656 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 12:24:39.653  8656  8656 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2ae460ba
08-30 12:24:39.657  8656  8656 D serial_port: close(fd = 24)
08-30 12:24:39.661  8656  8656 I UEI.SmartControl: Serial port is closed.
08-30 12:24:39.661  8656  8656 I UEI.SmartControl: Serial port is closed.
08-30 12:24:39.661  8656  8656 D UEI.SmartControl: Blaster closed
08-30 12:24:39.661  8656  8656 D UEI.SmartControl: Shut down QS...
08-30 12:24:39.661  8656  8656 D UEI.SmartControl: Stopping QS lib
08-30 12:24:39.661  8656  8656 D UEI.SmartControl: QS lib stop result = true
08-30 12:24:39.661  8656  8656 D UEI.SmartControl: Stopped QS lib
08-30 12:24:39.661  8656  8656 D UEI.SmartControl: QS shutdown complete
,08-30 12:24:40.978  1035  1920 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
,08-30 12:24:40.981  1035  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:40.981  1035  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:40.981  1035  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-30 12:24:40.981  1035  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 12:24:40.982  1035  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 12:24:41.009  1035  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 10:24:41 GMT], X-Android-Received-Millis=[1472552681009], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472552680985]}
08-30 12:24:41.009  1035  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 12:24:41.010  1035  8212 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,08-30 12:24:41.013  1035  1495 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
,08-30 12:24:41.013  1035  1495 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 12:24:41.013  1035  1495 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 12:24:41.013  1035  1495 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:24:41.013  1035  1495 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 12:24:41.014  1035  1495 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-30 12:24:41.014  1035  1495 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 12:24:41.014  1035  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 12:24:41.014  1035  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:24:41.015  1035  1495 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 12:24:41.016  1601  2071 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 12:24:41.716  1035  1437 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-621100813] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 12:24:41.719  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-621100809] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 12:24:41.719  1035  1437 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 12:24:42.181  6741  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:24:42.181  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:24:42.182  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 12:24:42.189  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:24:42.189  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:24:42.189  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:24:42.189  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 12:24:42.189  6741  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7c1723 removed from the list
08-30 12:24:42.189  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:24:42.189  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f4b420 removed from the list
08-30 12:24:42.189  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:24:42.189  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:24:42.190  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:24:42.190  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:24:42.191  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:24:42.191  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:24:42.192  6741  6802 D BluetoothLeScanner: could not find callback wrapper
08-30 12:24:42.192  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:24:42.192  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:24:42.192  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f4b420 not in the list
08-30 12:24:42.192  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:24:42.192  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:24:42.193  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:24:42.194  6741  6802 D BluetoothLeScanner: could not find callback wrapper
08-30 12:24:42.194  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 12:24:42.194  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:24:42.194  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:24:42.194  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f4b420 not in the list
08-30 12:24:42.194  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:24:42.194  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:24:42.194  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:24:42.194  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7c1723 not in the list
08-30 12:24:42.195  6741  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 12:24:42.195  6741  68,02 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c0f24c added. We now have 3 listener(s)
08-30 12:24:42.196  1035  1884 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 12:24:42.202  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 12:24:42.202  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:24:42.202  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:24:42.202  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 12:24:42.202  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fc28295 added. We now have 4 listener(s)
08-30 12:24:42.202  6741  6802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:24:42.207  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 12:24:42.212  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:24:42.217  6741  6802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:24:42.217  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:24:42.217  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 12:24:42.217  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:24:42.217  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:24:42.217  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:24:42.217  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:24:42.217  6741  6802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:24:42.220  6741  6802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 12:24:42.220  6741  6802 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:24:42.222  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:24:42.224  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:24:42.226  6741  6802 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 12:24:42.226  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 12:24:42.226  6741  6802 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 12:24:42.227  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:24:42.227  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:24:42.227  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 12:24:42.227  6741  6802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 12:24:42.227  6741  6802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c0f24c removed from the list
08-30 12:24:42.227  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:24:42.227  6741  6802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fc28295 removed from the list
08-30 12:24:42.227  6741  6802 D io.jxcore.node.ConnectivityMonitor: stop
08-30 12:24:42.227  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:24:42.228  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:24:42.228  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 12:24:42.232  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:24:42.232  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:24:42.232  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:24:42.233  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fc28295 not in the list
08-30 12:24:42.233  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:24:42.233  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:24:42.234  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 12:24:42.234  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 12:24:42.234  6741  6802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 12:24:42.234  6741  6802 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fc28295 not in the list
08-30 12:24:42.234  6741  6802 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 12:24:42.234  6741  6802 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 12:24:42.234  6741  6802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 12:24:42.234  6741  6802 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c0f24c not in the list
08-30 12:24:42.235  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 12:24:42.235  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 12:24:42.236  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 12:24:42.236  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 12:24:42.236  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 12:24:42.237  6741  6802 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 12:24:44.257  6741  8742 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 901, name: My test thread name)
,08-30 12:24:44.746  1035  1437 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-621097782] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-30 12:24:44.749  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2437 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-621097779] gl rssi=-42 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 12:24:44.749  1035  1437 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 12:24:46.254  6741  6802 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 901
,08-30 12:24:46.254  6741  6802 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 901, name: My test thread name)
,08-30 12:24:46.269  6741  8743 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 902, name: My test thread name)
08-30 12:24:46.269  6741  8743 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 902, thread name: My test thread name)
08-30 12:24:46.269  6741  8743 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 902, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
08-30 12:24:46.272  6741  6802 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 12:24:46.277  6741  8744 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 906, name: My test thread name)
08-30 12:24:46.278  6741  8744 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 906, thread name: My test thread name): Test exception.
08-30 12:24:46.278  6741  8744 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 906, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
08-30 12:24:46.281  6741  6802 I jxcore-log: Total number of executed tests:  82
08-30 12:24:46.281  6741  6802 I jxcore-log: 
08-30 12:24:46.282  6741  6802 I jxcore-log: Number of passed tests:  82
08-30 12:24:46.282  6741  6802 I jxcore-log: 
08-30 12:24:46.282  6741  6802 I jxcore-log: Number of failed tests:  0
08-30 12:24:46.282  6741  6802 I jxcore-log: 
08-30 12:24:46.282  6741  6802 I jxcore-log: Number of ignored tests:  0
08-30 12:24:46.282  6741  6802 I jxcore-log: 
08-30 12:24:46.282  6741  6802 I jxcore-log: Total duration:  101541
08-30 12:24:46.282  6741  6802 I jxcore-log: 
08-30 12:24:46.285  6741  6802 I jxcore-log: Unit Test app is loaded
08-30 12:24:46.285  6741  6802 I jxcore-log: 
08-30 12:24:46.305  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:24:46.305  6741  6802 I jxcore-log: 
,08-30 12:24:46.320  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:24:46.320  6741  6802 I jxcore-log: 
08-30 12:24:46.321  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:24:46.321  6741  6802 I jxcore-log: 
08-30 12:24:46.322  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:24:46.322  6741  6802 I jxcore-log: 
08-30 12:24:46.324  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:24:46.324  6741  6802 I jxcore-log: 
,08-30 12:24:46.333  6741  6741 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 12:24:46.333  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:24:46.333  6741  6802 I jxcore-log: 
08-30 12:24:46.337  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 12:24:46.337  6741  6802 I jxcore-log: 
08-30 12:24:46.339  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:24:46.339  6741  6802 I jxcore-log: 
08-30 12:24:46.340  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:24:46.340  6741  6802 I jxcore-log: 
08-30 12:24:46.341  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:24:46.341  6741  6802 I jxcore-log: 
08-30 12:24:46.342  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 12:24:46.342  6741  6802 I jxcore-log: 
08-30 12:24:46.343  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:24:46.343  6741  6802 I jxcore-log: 
08-30 12:24:46.344  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:24:46.344  6741  6802 I jxcore-log: 
08-30 12:24:46.345  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:24:46.345  6741  6802 I jxcore-log: 
,08-30 12:24:46.349  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 12:24:46.349  6741  6802 I jxcore-log: 
08-30 12:24:46.350  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 12:24:46.350  6741  6802 I jxcore-log: 
08-30 12:24:46.351  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 12:24:46.351  6741  6802 I jxcore-log: 
08-30 12:24:46.353  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:24:46.353  6741  6802 I jxcore-log: 
08-30 12:24:46.353  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:24:46.353  6741  6802 I jxcore-log: 
08-30 12:24:46.354  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:24:46.354  6741  6802 I jxcore-log: 
08-30 12:24:46.355  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:24:46.355  6741  6802 I jxcore-log: 
08-30 12:24:46.358  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:24:46.358  6741  6802 I jxcore-log: 
08-30 12:24:46.358  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:24:46.358  6741  6802 I jxcore-log: 
08-30 12:24:46.359  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 12:24:46.359  6741  6802 I jxcore-log: 
08-30 12:24:46.360  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 12:24:46.360  6741  6802 I jxcore-log: 
08-30 12:24:46.361  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 12:24:46.361  6741  6802 I jxcore-log: 
08-30 12:24:46.362  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:24:46.362  6741  6802 I jxcore-log: 
08-30 12:24:46.362  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:24:46.362  6741  6802 I jxcore-log: 
08-30 12:24:46.363  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 12:24:46.363  6741  6802 I jxcore-log: 
08-30 12:24:46.364  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 12:24:46.364  6741  6802 I jxcore-log: 
,08-30 12:24:46.367  6741  8742 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 901, name: My test thread name), during the lifetime of the thread the total number of bytes read was 176 and the total number of bytes written 176
08-30 12:24:46.369  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 12:24:46.369  6741  6802 I jxcore-log: 
08-30 12:24:46.370  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 12:24:46.370  6741  6802 I jxcore-log: 
08-30 12:24:46.371  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 12:24:46.371  6741  6802 I jxcore-log: 
08-30 12:24:46.372  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 12:24:46.372  6741  6802 I jxcore-log: 
08-30 12:24:46.372  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:24:46.372  6741  6802 I jxcore-log: 
08-30 12:24:46.373  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:24:46.373  6741  6802 I jxcore-log: 
08-30 12:24:46.374  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:24:46.374  6741  6802 I jxcore-log: 
08-30 12:24:46.375  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:24:46.375  6741  6802 I jxcore-log: 
08-30 12:24:46.376  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:24:46.376  6741  6802 I jxcore-log: 
08-30 12:24:46.377  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:24:46.377  6741  6802 I jxcore-log: 
08-30 12:24:46.377  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:24:46.377  6741  6802 I jxcore-log: 
08-30 12:24:46.378  6741  6802 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 12:24:46.378  6741  6802 I jxcore-log: 
08-30 12:24:46.381  6741  6802 I jxcore-log: My device name is: LGE-LG-D855
08-30 12:24:46.381  6741  6802 I jxcore-log: 
08-30 12:24:46.382  6741  6802 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 12:24:46.382  6741  6802 I jxcore-log: 
,08-30 12:24:46.427  1035  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{14e0f8f0 type 2 when 403659 com.google.android.gms} when 403659
,08-30 12:24:46.444   316  8750 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-30 12:24:46.444   316  8750 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-30 12:24:46.445   316  8750 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-30 12:24:46.737  2205  8752 D GCM     : Connected
,08-30 12:24:46.773  2205  8752 D GCM     : Message class com.google.e.a.a.q
08-30 12:24:47.776  1035  1437 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-621094752] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 12:24:47.778  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-621094750] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 12:24:47.778  1035  1437 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 12:24:48.995  6741  6802 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 12:24:48.995  6741  6802 I jxcore-log: 
,08-30 12:24:49.439  6741  6802 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 12:24:49.439  6741  6802 I jxcore-log: 
,08-30 12:24:49.465  6741  6802 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 12:24:49.465  6741  6802 I jxcore-log: 
,08-30 12:24:50.798  1035  1437 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=4.7, 0.0, 0.0  rx=4.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-621091730] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 12:24:50.801  1035  1437 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=4.7, 0.0, 0.0  rx=4.4 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-621091728] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 12:24:50.801  1035  1437 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 12:24:50.814  6741  6802 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 12:24:50.814  6741  6802 I jxcore-log: 
,08-30 12:24:51.042  6741  6802 I jxcore-log: ERROR runTests: 
08-30 12:24:51.042  6741  6802 I jxcore-log: 
,08-30 12:24:51.046  6741  6802 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 12:24:51.046  6741  6802 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-30 12:24:51.048  6741  6802 I jxcore-log: WARN testUtils: logCallback not set!
08-30 12:24:51.048  6741  6802 I jxcore-log: 
08-30 12:24:51.058  6741  6802 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 12:24:51.058  6741  6802 I jxcore-log:     _functionName: 'loadFile',
08-30 12:24:51.058  6741  6802 I jxcore-log:     _lineNumber: '26',
08-30 12:24:51.058  6741  6802 I jxcore-log:     _columnNumber: '11',
08-30 12:24:51.058  6741  6802 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 12:24:51.058  6741  6802 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 12:24:51.058  6741  6802 I jxcore-log:     _functionName: '',
08-30 12:24:51.058  6741  6802 I jxcore-log:     _lineNumber: '38',
08-30 12:24:51.058  6741  6802 I jxcore-log:     _columnNumber: '7',
08-30 12:24:51.058  6741  6802 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 12:24:51.058  6741  6802 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 12:24:51.058  6741  6802 I jxcore-log:     _functionName: '',
08-30 12:24:51.058  6741  6802 I jxcore-log:     _lineNumber: '35',
08-30 12:24:51.058  6741  6802 I jxcore-log:     _columnNumber: '3',
08-30 12:24:51.058  6741  6802 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 12:24:51.058  6741  6802 I jxcore-log:   { _fileName: 'module.js',
08-30 12:24:51.058  6741  6802 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 12:24:51.058  6741  6802 I jxcore-log:     _lineNumber: '621',
08-30 12:24:51.058  6741  6802 I jxcore-log:     _columnNumber: '8',
08-30 12:24:51.058  6741  6802 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 12:24:51.058  6741  6802 I jxcore-log:   { _fileName: 'module.js',
08-30 12:24:51.058  6741  6802 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 12:24:51.058  6741  6802 I jxcore-log:     _lineNumber: '651',
08-30 12:24:51.058  6741  6802 I jxcore-log:     _columnNumber: '1',
08-30 12:24:51.058  6741  6802 I jxcore-log:    
08-30 12:24:51.058  6741  6802 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 12:24:51.058  6741  6802 I jxcore-log: 
08-30 12:24:51.059  6741  6802 E jxcore-log: Error: 
08-30 12:24:51.059  6741  6802 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 12:24:51.059  6741  6802 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 12:24:51.059  6741  6802 E jxcore-log: 
,08-30 12:24:51.439  8754  8754 D AndroidRuntime: 
08-30 12:24:51.439  8754  8754 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-30 12:24:51.453  8754  8754 D AndroidRuntime: CheckJNI is OFF
08-30 12:24:51.706  8754  8754 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 12:24:51.728  1035  1113 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-30 12:24:51.729  1035  1113 I ActivityManager: Killing 6741:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-30 12:24:51.845  1035  1379 W InputDispatcher: channel '2a65ae45 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
08-30 12:24:51.845  1035  1379 E InputDispatcher: channel '2a65ae45 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,08-30 12:24:51.847  1035  1920 I WindowState: WIN DEATH: Window{2a65ae45 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 12:24:51.848  1035  1920 W InputDispatcher: Attempted to unregister already unregistered input channel '2a65ae45 com.test.thalitest/com.test.thalitest.MainActivity (server)'
08-30 12:24:51.848  1035  1485 D WifiService: Client connection lost with reason: 4
08-30 12:24:51.853  1035  1113 I ActivityManager:   Force finishing activity ActivityRecord{1f578c06 u0 com.test.thalitest/.MainActivity t6}
08-30 12:24:51.858  1035  1920 D InputDispatcher: Window went away: Window{2a65ae45 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 12:24:51.908   337   360 E GBMv2   : DFP En is all cleared set to be enabled
,08-30 12:24:51.916  1035  1142 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-30 12:24:51.918  1035  1142 I ActivityManager:   Force finishing activity ActivityRecord{1f578c06 u0 com.test.thalitest/.MainActivity t6 f}
08-30 12:24:51.918  1035  1142 W ActivityManager: Duplicate finish request for ActivityRecord{1f578c06 u0 com.test.thalitest/.MainActivity t6 f}
,08-30 12:24:51.931  1035  1975 W ActivityManager: Spurious death for ProcessRecord{29434e69 6741:com.test.thalitest/u0a118}, curProc for 6741: null
08-30 12:24:51.934  1939  1955 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-30 12:24:51.934  1939  1955 D SplitWindowPolicy: topRunningActivity=ActivityInfo{18f3e200 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 12:24:51.937  1939  1954 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
,08-30 12:24:51.937  1939  1954 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3ab36a39 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 12:24:51.948  2030  2030 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-30 12:24:51.949  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-30 12:24:51.951  2030  2030 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-30 12:24:51.954  1035  1380 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-30 12:24:51.980  4477  4477 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-30 12:24:51.981  2503  2691 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 12:24:51.983  1994  1994 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-30 12:24:51.983  3781  3781 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-30 12:24:51.984  7946  7946 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-30 12:24:51.984  7946  7946 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 12:24:52.003  4590  4590 I art     : Explicit concurrent mark sweep GC freed 15442(886KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 412us total 80.539ms
,08-30 12:24:52.006  2030  2030 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-30 12:24:52.006  2030  2125 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-30 12:24:52.009  8195  8195 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-30 12:24:52.011  4477  4477 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-30 12:24:52.011  4477  4477 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-30 12:24:52.011  4477  4477 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-30 12:24:52.011  4477  4477 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 12:24:52.011  4477  4477 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 12:24:52.011  4477  4477 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:24:52.011  4477  4477 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 12:24:52.011  4477  4477 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:24:52.011  4477  4477 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:24:52.011  4477  4477 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 12:24:52.011  4477  4477 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 12:24:52.021  1035  1885 V SIM_STK : Menu title from STK is T-Mobile
,08-30 12:24:52.050  1601  1601 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-30 12:24:52.054  2030  2030 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-30 12:24:52.057  1903  1903 D ActionManagerService: notifyUserLog: 1000003
08-30 12:24:52.057  1815  1815 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-30 12:24:52.057  2030  2030 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-30 12:24:52.058  3781  4467 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-30 12:24:52.059  2030  2030 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-30 12:24:52.059  1601  1652 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 12:24:52.059  1601  1652 D KeyguardModel: createShortcutInfo...
08-30 12:24:52.060  2030  2030 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-30 12:24:52.065  1601  1652 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 12:24:52.065  1601  1652 D KeyguardModel: createShortcutInfo...
08-30 12:24:52.066  1903  1903 D ActionManagerService: notifyUserLog: 1000004
,08-30 12:24:52.072  2030  2030 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-30 12:24:52.072  3781  4467 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-30 12:24:52.074  1601  1601 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-30 12:24:52.074  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-30 12:24:52.074  3781  4466 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 12:24:52.077  2030  2030 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-30 12:24:52.077  2030  2030 I GBoardWebViewUtils: , create_time: 1430832262123
08-30 12:24:52.077  2030  2030 I GBoardWebViewUtils: , expire_time: 0
08-30 12:24:52.077  2030  2030 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-30 12:24:52.077  2030  2030 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-30 12:24:52.077  2030  2030 I GBoardWebViewUtils: , display: false
08-30 12:24:52.077  2030  2030 I GBoardWebViewUtils: , animation: false }
08-30 12:24:52.077  2030  2030 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-30 12:24:52.077  2030  2030 I GBoardWebViewUtils: , create_time: 1430832262287
08-30 12:24:52.077  2030  2030 I GBoardWebViewUtils: , expire_time: 0
08-30 12:24:52.077  2030  2030 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 12:24:52.077  2030  2030 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 12:24:52.077  2030  2030 I GBoardWebViewUtils: , display: false
08-30 12:24:52.077  2030  2030 I GBoardWebViewUtils: , animation: false }
08-30 12:24:52.078  2030  2030 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-30 12:24:52.078  2030  2030 I GBoardWebViewUtils: , create_time: 1472216588858
08-30 12:24:52.078  2030  2030 I GBoardWebViewUtils: , expire_time: 0
08-30 12:24:52.078  2030  2030 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 12:24:52.078  2030  2030 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 12:24:52.078  2030  2030 I GBoardWebViewUtils: , display: false
08-30 12:24:52.078  2030  2030 I GBoardWebViewUtils: , animation: false }
08-30 12:24:52.082  1601  1652 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,08-30 12:24:52.082  1601  1652 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:24:52.083  1601  1652 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 12:24:52.083  1601  1652 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 12:24:52.084  2030  8780 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-30 12:24:52.091  1867  1867 D SplitUIManager: split_name #11 / not available #0
08-30 12:24:52.091  1867  1867 D SplitUIService: removed split : 
08-30 12:24:52.100  1601  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 12:24:52.100  1601  1652 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 12:24:52.101  2030  2030 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 12:24:52.101  2030  2030 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-30 12:24:52.107  1601  1652 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 12:24:52.107  1601  1652 D KeyguardModel: createShortcutInfo...
,08-30 12:24:52.108  1035  1975 V SIM_STK : Menu title from STK is T-Mobile
08-30 12:24:52.108  1035  1975 V SIM_STK : Menu title from STK is T-Mobile
08-30 12:24:52.112  1815  1815 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-30 12:24:52.117  1601  1652 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 12:24:52.117  1601  1652 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 12:24:52.129  1601  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 12:24:52.129  1601  1652 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 12:24:52.130  1601  1652 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 12:24:52.130  1601  1652 D KeyguardModel: createShortcutInfo...
08-30 12:24:52.132  2205  2205 I ConfigService: onCreate
,08-30 12:24:52.140  2205  2205 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-30 12:24:52.141  1867  1867 D SplitUIManager: split_name #11 / not available #0
08-30 12:24:52.141  1867  1867 I SplitUIService: split app #11
,08-30 12:24:52.148  1601  1652 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:24:52.148  1601  1652 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 12:24:52.148  1601  1652 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 12:24:52.148  1601  1652 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 12:24:52.156  1601  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 12:24:52.156  1601  1652 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 12:24:52.157  1601  1652 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 12:24:52.157  1601  1652 D KeyguardModel: createShortcutInfo...
08-30 12:24:52.160  1035  1035 I art     : Explicit concurrent mark sweep GC freed 50360(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 3.753ms total 230.150ms
08-30 12:24:52.160  1601  1601 D KeyguardModel: handleShortcutListChanged...
08-30 12:24:52.160  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-30 12:24:52.167  1035  1574 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-30 12:24:52.167  7946  7946 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 12:24:52.168  7946  7946 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 12:24:52.168  7946  7946 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 12:24:52.168  7946  7946 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 12:24:52.168  7946  7946 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 12:24:52.168  7946  7946 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 12:24:52.168  7946  7946 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 12:24:52.168  7946  7946 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 12:24:52.168  7946  7946 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 12:24:52.168  7946  7946 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 12:24:52.168  7946  7946 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 12:24:52.168  1601  1652 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 12:24:52.168  1601  1652 D KeyguardModel: createShortcutInfo...
08-30 12:24:52.170  1601  1652 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 12:24:52.170  1601  1652 D KeyguardModel: createShortcutInfo...
08-30 12:24:52.172  1035  1142 I art     : WaitForGcToComplete blocked for 72.217ms for cause Explicit
08-30 12:24:52.177  1601  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 12:24:52.177  1601  1652 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-30 12:24:52.178  1601  1652 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 12:24:52.178  1601  1652 D KeyguardModel: createShortcutInfo...
08-30 12:24:52.179  1601  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 12:24:52.179  1601  1652 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 12:24:52.184  1035  1957 V SIM_STK : Menu title from STK is T-Mobile
08-30 12:24:52.185  1601  1652 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 12:24:52.185  1601  1652 D KeyguardModel: createShortcutInfo...
08-30 12:24:52.186  1601  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 12:24:52.186  1601  1652 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 12:24:52.187  2205  2205 I ConfigService: onBind returning update interface
08-30 12:24:52.188  1601  1652 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 12:24:52.188  1601  1652 D KeyguardModel: createShortcutInfo...
08-30 12:24:52.190  2030  2030 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-30 12:24:52.210  1035  1035 D administrator: Handling package changes for user 0
,08-30 12:24:52.217  2205  2205 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-30 12:24:52.217  2205  2205 I ConfigService: onBind returning config service
08-30 12:24:52.224  1601  1601 D KeyguardModel: handleShortcutListChanged...
08-30 12:24:52.224  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-30 12:24:52.235  1815  8785 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-30 12:24:52.241  2205  2205 I ConfigService: onDestroy
08-30 12:24:52.249  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-30 12:24:52.249  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 12:24:52.250  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 12:24:52.259  1035  1576 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-30 12:24:52.265  2030  2030 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-30 12:24:52.269  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 12:24:52.270  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-30 12:24:52.271  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-30 12:24:52.272  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-30 12:24:52.274  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-30 12:24:52.280  7038  7038 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-30 12:24:52.287  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3560188a u0 com.lge.launcher2/.Launcher t5} time:409532
,08-30 12:24:52.297  2030  2030 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-30 12:24:52.297  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 12:24:52.297  2030  2177 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,08-30 12:24:52.298  2030  2177 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-30 12:24:52.299  2341  8792 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 12:24:52.311  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-30 12:24:52.312  2030  2030 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 12:24:52.312  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 12:24:52.320  2030  2030 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-30 12:24:52.323  1035  1884 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8794 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-30 12:24:52.325  2575  2575 D [Concierge]Service: onStartCommand(). Type : 8
08-30 12:24:52.325  2575  2575 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-30 12:24:52.327  2575  2575 D [Concierge]Service: Update widget ID : 11
08-30 12:24:52.328  2030  2030 D [Concierge]WidgetView: change position of spinner
08-30 12:24:52.330  2030  2030 I [Concierge]WidgetView: initWebView(). Time : 1472552692330
08-30 12:24:52.331  2575  2575 D [Concierge]Service: onStartCommand(). Type : 0
08-30 12:24:52.344  2030  2030 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 239156234
08-30 12:24:52.344  2030  2030 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-30 12:24:52.345  2030  2030 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-30 12:24:52.345  5906  8808 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-30 12:24:52.348  2030  2030 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@340e00df
08-30 12:24:52.348  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,08-30 12:24:52.349  2030  2030 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,08-30 12:24:52.349  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 12:24:52.350  1815  8809 I PeopleContactsSync: CP2 sync disabled
08-30 12:24:52.355  1815  4733 I Icing   : doRemovePackageData com.test.thalitest
08-30 12:24:52.355  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-30 12:24:52.355  2030  2030 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-30 12:24:52.355  2030  2030 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 12:24:52.356  2030  2030 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472552311751, New one : 1472552692330
08-30 12:24:52.356  2030  2030 D [Concierge]WidgetView: Unregister all receivers
08-30 12:24:52.356  2030  2030 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 12:24:52.358  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 12:24:52.360  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-30 12:24:52.361  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-30 12:24:52.362  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-30 12:24:52.363  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-30 12:24:52.363  1815  8791 W GmsApplication: Using Auth Proxy for data requests.
08-30 12:24:52.364  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,08-30 12:24:52.367  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 12:24:52.367  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 12:24:52.373  1815  8791 W GmsApplication: Using Auth Proxy for data requests.
08-30 12:24:52.379  8794  8794 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:24:52.379  8794  8794 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 12:24:52.380  8794  8794 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 12:24:52.380  8794  8794 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-30 12:24:52.397  2030  2030 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-30 12:24:52.405  2030  2030 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-30 12:24:52.405  2030  2030 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-30 12:24:52.406  2030  2030 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 12:24:52.429  2030  2030 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@641bf07 time:409673
,08-30 12:24:52.431  1035  1142 I art     : Explicit concurrent mark sweep GC freed 8128(429KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.671ms total 258.728ms
08-30 12:24:52.445   331   418 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-30 12:24:52.445  3211  8815 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-30 12:24:52.463  8794  8794 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-30 12:24:52.473  8794  8794 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-30 12:24:52.497  8794  8794 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 12:24:52.517  8794  8794 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 12:24:52.517  8794  8794 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 12:24:52.519  8754  8754 D AndroidRuntime: Shutting down VM
08-30 12:24:52.556  1035  1142 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8821 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-30 12:24:52.593  8794  8794 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-30 12:24:52.596  1035  1112 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-30 12:24:52.598  2030  2030 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-30 12:24:52.599  1035  1725 I ActivityManager: Killing 8127:com.lge.formmanager/u0a26 (adj 15): empty #17
08-30 12:24:52.641  2030  2973 I GBoardtInterface: onReloaded()
,08-30 12:24:52.643  2030  2030 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-30 12:24:52.696  1035  2045 W libprocessgroup: failed to open /acct/uid_10026/pid_8127/cgroup.procs: No such file or directory
,08-30 12:24:52.699  3781  4466 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 12:24:52.699  1035  1725 I ActivityManager: Killing 8371:com.android.chrome/u0a57 (adj 15): empty #17
08-30 12:24:52.711  1035  1112 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 12:24:52.715  1035  1112 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-30 12:24:52.736  1994  1994 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-30 12:24:52.736  1994  1994 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-30 12:24:52.737  1035  1957 W libprocessgroup: failed to open /acct/uid_10057/pid_8371/cgroup.procs: No such file or directory
08-30 12:24:52.739  1994  1994 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-30 12:24:52.740  3781  3797 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 12:24:52.741  8195  8195 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-30 12:24:52.775  1035  1884 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=8840 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-30 12:24:52.776  1903  1903 D ActionManagerService: notifyUserLog: 1000001
08-30 12:24:52.777  3781  4467 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 12:24:52.777  3781  4467 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-30 12:24:52.781  1903  1903 D ActionManagerService: notifyUserLog: 1000001
08-30 12:24:52.783  3781  3797 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 12:24:52.783  3781  4467 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 12:24:52.783  3781  4467 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-30 12:24:52.783  3781  4467 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-30 12:24:52.783  3781  4467 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-30 12:24:52.785  2030  2030 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-30 12:24:52.785  2030  2030 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-30 12:24:52.787  2030  2030 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
,08-30 12:24:52.787  2030  2030 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 12:24:52.789  2030  2030 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
,08-30 12:24:52.789  2030  2030 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 12:24:52.791  2030  2030 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-30 12:24:52.827  8840  8840 E SQLiteDatabase: Failed to open database '/data/data/com.lge.lifetracker/databases/lifetracker2.db'.
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 12:24:52.827  8840  8840 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: Unable to open database for writing.
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:24:52.827  8840  8840 E Lifetra,ckerProvider2: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at com.lge.lifetracker.core.provider.LifetrackerProvider2.onCreate(LifetrackerProvider2.java:56)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 12:24:52.827  8840  8840 E LifetrackerProvider2: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-30 12:24:52.839  8840  8840 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-30 12:24:52.840  8840  8840 W LG Account v2.2: No ProfileInfo entries
08-30 12:24:52.840  8840  8840 I LG Account v2.2: isEnabled: false
08-30 12:24:52.840  8840  8840 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 12:24:52.840  8840  8840 I Feature : [Lifetracker]Country: EU
08-30 12:24:52.840  8840  8840 I Feature : [Lifetracker]Operator: OPEN
08-30 12:24:52.840  8840  8840 I Feature : [Lifetracker]Ranking support: false
08-30 12:24:52.840  8840  8840 I Feature : [Lifetracker]Comfort support: false
08-30 12:24:52.841  8840  8840 I Feature : [Lifetracker]Accessory: true
08-30 12:24:52.845  8840  8840 I Feature : [Lifetracker]Health device: true
08-30 12:24:52.845  8840  8840 I Feature : [Lifetracker]Extra Pedometer: false
,08-30 12:24:52.845  8840  8840 I Feature : [Lifetracker]Blood glucose device: false
08-30 12:24:52.845  8840  8840 I Feature : [Lifetracker]Device Number: 3
08-30 12:24:52.846  8840  8840 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-30 12:24:52.865  1035  1725 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8860 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 12:24:52.866  1035  1725 I ActivityManager: Killing 8394:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-30 12:24:52.899  4477  4504 E SQLiteLog: (3850) statement aborts at 11: [INSERT INTO t010(f004,f002,f003) VALUES (?,?,?)] disk I/O error
08-30 12:24:52.900  4477  4504 E SQLiteDatabase: Error inserting f004=1682508 f002=1472552692897 f003=66
08-30 12:24:52.900  4477  4504 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 12:24:52.900  4477  4504 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-30 12:24:52.900  4477  4504 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
08-30 12:24:52.900  4477  4504 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
08-30 12:24:52.900  4477  4504 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-30 12:24:52.900  4477  4504 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
08-30 12:24:52.900  4477  4504 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
08-30 12:24:52.900  4477  4504 E SQLiteDatabase: 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
08-30 12:24:52.900  4477  4504 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
08-30 12:24:52.900  4477  4504 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
08-30 12:24:52.900  4477  4504 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertResourceInfo(MltMonitorService.java:2996)
08-30 12:24:52.900  4477  4504 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$3200(MltMonitorService.java:38)
08-30 12:24:52.900  4477  4504 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3451)
08-30 12:24:52.900  4477  4504 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:24:52.900  4477  4504 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-30 12:24:52.900  4477  4504 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)

```
