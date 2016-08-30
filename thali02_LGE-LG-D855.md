#### Test 832611203a07957_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-30 17:41:00.083  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
08-30 17:41:00.091  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
08-30 17:41:00.091  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-30 17:41:00.094  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-30 17:41:00.095  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,08-30 17:41:22.676  6758  6758 D AndroidRuntime: 
08-30 17:41:22.676  6758  6758 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 17:41:22.682  6758  6758 D AndroidRuntime: CheckJNI is OFF
08-30 17:41:22.808  6758  6758 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 17:41:22.813  1034  1785 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 17:41:22.823  1940  1957 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-30 17:41:22.826  1034  1785 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-30 17:41:22.827  1034  1785 D ActivityManager: setTaskToReturnTo : TaskRecord{1d8cfd85 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 17:41:22.827  1034  1785 D ActivityManager: setTaskToReturnTo : TaskRecord{1d8cfd85 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 17:41:22.828  1034  1785 D WindowStateEx: AppWindowTokenEx init.. 
08-30 17:41:22.829   328   338 E GBMv2   : DFP En is all cleared set to be enabled
08-30 17:41:22.863  1034  1785 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6777 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 17:41:22.864  6758  6758 D AndroidRuntime: Shutting down VM
08-30 17:41:22.924  1940  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-30 17:41:22.925  1940  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2c958d15 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 17:41:22.928  1940  3981 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-30 17:41:22.928  1940  3981 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3fe7a82a co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 17:41:22.976  6777  6777 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-30 17:41:23.050  6777  6777 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-30 17:41:23.057  6777  6777 I LibraryLoader: Loading: webviewchromium
08-30 17:41:23.059  6777  6777 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4268-4271)
08-30 17:41:23.060  6777  6777 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 17:41:23.082  6777  6777 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2edf1c8b}
08-30 17:41:23.083  6777  6777 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 17:41:23.084  6777  6777 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 17:41:23.098  6777  6777 I BrowserStartupController: Initializing chromium process, renderers=0
08-30 17:41:23.099  6777  6777 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 17:41:23.111   311  1403 V AudioPolicyService: registerClient() client 0xb558a380, uid 10118
,08-30 17:41:23.111  6777  6777 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-30 17:41:23.112  6777  6777 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-30 17:41:23.112  6777  6777 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-30 17:41:23.116  1034  1098 D BluetoothManagerService: Message: 20
08-30 17:41:23.116  1034  1098 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27b5e5e7:true
08-30 17:41:23.132  6777  6777 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 17:41:23.132  6777  6777 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 17:41:23.132  6777  6777 I Adreno-EGL: Build Date: 12/12/14 금
08-30 17:41:23.132  6777  6777 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 17:41:23.132  6777  6777 I Adreno-EGL: Remote Branch: 
08-30 17:41:23.132  6777  6777 I Adreno-EGL: Local Patches: 
08-30 17:41:23.132  6777  6777 I Adreno-EGL: Reconstruct Branch: 
,08-30 17:41:23.217  6777  6808 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-30 17:41:23.223  6777  6777 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-30 17:41:23.239  6777  6777 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 17:41:23.243  6777  6777 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 17:41:23.245  6777  6777 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-30 17:41:23.248  6777  6777 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-30 17:41:23.248  6777  6777 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-30 17:41:23.262  6777  6777 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-30 17:41:23.269  6777  6777 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 17:41:23.269  6777  6777 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 17:41:23.309  6777  6820 D OpenGLRenderer: Render dirty regions requested: true
08-30 17:41:23.309  6777  6820 I OpenGLRenderer: Initialized EGL, version 1.4
08-30 17:41:23.321  6777  6820 D OpenGLRenderer: Enabling debug mode 0
,08-30 17:41:23.332  6777  6777 D Atlas   : Validating map...
,08-30 17:41:23.338  1034  1886 D SplitWindow: check instance of lgWin Window{38fa64a9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 17:41:23.405  6777  6818 D LgDataFeature: LgDataFeature() Constructor: none
08-30 17:41:23.405  6777  6818 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 17:41:23.457  1034  1099 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +533ms (total +626ms)
08-30 17:41:23.458  1034  1099 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2424a7da u0 com.test.thalitest/.MainActivity t6} time:164670
08-30 17:41:23.458  6777  6777 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@37e5a8d6 time:164670
,08-30 17:41:23.578  6777  6777 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-30 17:41:23.578  6777  6777 I chromium: 
,08-30 17:41:23.605  6777  6777 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 17:41:23.668  6777  6818 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-30 17:41:23.668  6777  6818 I chromium: 
,08-30 17:41:23.821  6777  6840 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435153408
,08-30 17:41:23.839  6777  6840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 17:41:23.839  6777  6840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 17:41:23.839  6777  6840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 17:41:23.839  6777  6840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 17:41:23.839  6777  6840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 17:41:23.840  6777  6840 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eec35ba added. We now have 1 listener(s)
,08-30 17:41:23.847  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:23.852  6777  6840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-30 17:41:23.859  6777  6840 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 17:41:23.861  6777  6840 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:41:23.861  6777  6840 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 17:41:23.875  6777  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 17:41:23.875  6777  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 17:41:23.875  6777  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 17:41:23.875  6777  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-30 17:41:23.875  6777  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 17:41:23.875  6777  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 17:41:23.875  6777  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 17:41:23.875  6777  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 17:41:23.875  6777  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 17:41:23.875  6777  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 17:41:23.875  6777  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 17:41:23.875  6777  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 17:41:23.875  6777  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 17:41:23.875  6777  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 17:41:23.875  6777  6840 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@174cbc61 added. We now have 1 listener(s)
,08-30 17:41:23.876  6777  6840 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:41:23.880  1034  1397 D WifiService: New client listening to asynchronous messages
08-30 17:41:23.885  6777  6840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 17:41:23.885  6777  6840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 17:41:23.887  6777  6840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 17:41:23.887  6777  6840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 17:41:23.887  6777  6840 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 17:41:23.891  6777  6840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:41:23.892  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:23.894  6777  6840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-30 17:41:23.903  6777  6840 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 17:41:23.903  6777  6840 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:41:23.903  6777  6840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:23.903  6777  6840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:23.903  6777  6840 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:41:23.903  6777  6840 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:41:23.903  6777  6840 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:23.903  6777  6840 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:41:23.903  6777  6840 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:41:23.903  6777  6840 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 17:41:23.903  6777  6840 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 17:41:23.907  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:23.907  6777  6840 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 17:41:23.909  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:23.945  6777  6777 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 17:41:24.552   328   340 E GBMv2   : DFP En is all cleared set to be enabled
08-30 17:41:24.553   328   340 E GBMv2   : Set value is all cleared set the max
08-30 17:41:24.553   328   340 I GBMv2   : DFP Enabled. Ignore VFP set
,08-30 17:41:24.651  6777  6843 W jxcore-log: Initializing JXcore engine
08-30 17:41:24.651  6777  6843 W jxcore-log: JXcore engine is ready
,08-30 17:41:24.681  6843  6843 W Thread-772: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8439]" dev="sockfs" ino=8439 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-30 17:41:24.681  6843  6843 W Thread-772: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,08-30 17:41:24.681  6843  6843 W Thread-772: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10398]" dev="sockfs" ino=10398 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-30 17:41:24.681  6843  6843 W Thread-772: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-30 17:41:24.681  6843  6843 W Thread-772: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32835]" dev="sockfs" ino=32835 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-30 17:41:24.709  6777  6843 W jxcore-log: Starting JXcore engine
,08-30 17:41:24.794  6777  6843 W jxcore-log: Platform android
08-30 17:41:24.794  6777  6843 W jxcore-log: 
08-30 17:41:24.794  6777  6843 W jxcore-log: Process ARCH arm
08-30 17:41:24.794  6777  6843 W jxcore-log: 
,08-30 17:41:25.034  6777  6843 I jxcore-log: JXcore Cordova bridge is ready!
08-30 17:41:25.034  6777  6843 I jxcore-log: 
08-30 17:41:25.036  6777  6843 W jxcore-log: JXcore engine is started
,08-30 17:41:25.041  6777  6840 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 17:41:25.044  6777  6777 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 17:41:34.918  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 17:41:34.918  6777  6843 I jxcore-log: 
,08-30 17:41:34.922  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 17:41:34.922  6777  6843 I jxcore-log: 
08-30 17:41:34.926  6777  6843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:41:34.926  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:34.926  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:34.926  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:41:34.926  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:41:34.926  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:34.926  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:41:34.926  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:41:34.929  6777  6843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:34.932  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 17:41:34.932  6777  6843 I jxcore-log: 
,08-30 17:41:34.934  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 17:41:34.934  6777  6843 I jxcore-log: 
08-30 17:41:35.452  6777  6843 D executeNativeTests: Running unit tests
,08-30 17:41:35.534  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 17:41:35.534  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208f2a0a added. We now have 2 listener(s)
08-30 17:41:35.534  1034  1982 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 17:41:35.536  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 17:41:35.536  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:41:35.536  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 17:41:35.536  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:41:35.536  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b added. We now have 2 listener(s),
08-30 17:41:35.536  6777  6843 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:41:35.537  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 17:41:35.539  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:41:35.542  6777  6843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:41:35.542  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:35.542  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:35.542  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:41:35.542  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:41:35.542  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:35.542  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:41:35.542  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:41:35.544  6777  6843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:35.544  6777  6843 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:41:35.546  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:35.547  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:35.553  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 17:41:35.557  6777  6843 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 17:41:35.558  6777  6843 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 17:41:35.565  6777  6843 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-30 17:41:35.568  6777  6843 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 17:41:35.568  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 17:41:35.570  6777  6843 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 17:41:35.570  6777  6843 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 17:41:35.571  6777  6843 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:35.572  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:35.573  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:35.573  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:35.573  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.573  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:41:35.573  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:41:35.573  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208f2a0a removed from the list
08-30 17:41:35.573  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.574  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b removed from the list
08-30 17:41:35.574  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:35.574  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.575  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.575  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.575  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:35.575  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:35.575  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.576  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.578  6777  6843 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 17:41:35.578  6777  6843 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:35.578  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:35.578  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:35.579  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:35.579  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.579  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.579  6777  6843 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208f2a0a not in the list
08-30 17:41:35.579  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 17:41:35.579  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.579  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:35.579  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.579  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.579  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.579  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.580  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:35.580  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:35.580  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.580  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.586  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 17:41:35.586  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 17:41:35.586  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-30 17:41:35.586  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 17:41:35.586  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 17:41:35.586  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 17:41:35.586  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 17:41:35.586  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 17:41:35.586  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 17:41:35.586  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 17:41:35.587  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 17:41:35.587  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 17:41:35.587  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 17:41:35.587  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 17:41:35.587  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 17:41:35.587  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 17:41:35.587  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 17:41:35.587  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 17:41:35.587  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 17:41:35.587  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 17:41:35.587  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 17:41:35.587  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 17:41:35.587  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 17:41:35.587  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-30 17:41:35.587  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 17:41:35.587  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 17:41:35.587  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 17:41:35.587  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 17:41:35.587  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 17:41:35.587  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 17:41:35.587  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 17:41:35.587  6777  6843 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:35.587  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:35.587  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:35.589  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:35.589  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.589  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.589  6777  6843 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208f2a0a not in the list
08-30 17:41:35.589  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.589  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.589  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:35.589  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.589  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.589  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.589  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.590  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:35.590  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:35.590  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.590  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.591  6777  6843 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 17:41:35.593  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:41:35.595  6777  6843 V io.jxcore.node.ConnectivityMonitor: updateConnec,tivityInfo: FORCED notification:
08-30 17:41:35.595  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:35.595  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:35.595  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:41:35.595  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:41:35.595  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:35.595  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:41:35.595  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:41:35.597  6777  6843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:35.597  6777  6843 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:41:35.597  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:41:35.597  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:41:35.598  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:41:35.598  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:41:35.598  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 17:41:35.602  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:35.604  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:35.605  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 17:41:35.605  1034  2397 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:35.611  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 17:41:35.618  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 17:41:35.621  6777  6843 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 17:41:35.622  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:41:35.623  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:41:35.624  6777  6843 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 17:41:35.625  6777  6843 I io.jxcore.node.ConnectionHelper: start: OK
08-30 17:41:35.628  6777  6843 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:35.628  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:35.628  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:35.628  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:35.629  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.629  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:41:35.629  6777  6843 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208f2a0a not in the list
08-30 17:41:35.629  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.629  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.629  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:35.629  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.629  6777  6843 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 17:41:35.631  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:41:35.634  6777  6843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:41:35.634  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:35.634  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:35.634  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:41:35.634  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:41:35.634  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:35.634  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:41:35.634  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:41:35.635  6777  6843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:35.635  6777  6843 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:41:35.636  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:41:35.636  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:41:35.636  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:41:35.636  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:41:35.636  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 17:41:35.637  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:35.639  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:35.641  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:41:35.642  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:41:35.645  6777  6843 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 17:41:35.645  6777  6843 I io.jxcore.node.ConnectionHelper: start: OK
08-30 17:41:35.647  6777  6843 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:35.647  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:35.647  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:35.647  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:35.647  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.647  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:41:35.647  6777  6843 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208f2a0a not in the list
08-30 17:41:35.647  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.647  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.647  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:35.647  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.647  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.648  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.649  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:35.649  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:35.651  6777  6843 D BluetoothLeScanner: could not find callback wrapper
08-30 17:41:35.651  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:41:35.651  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.651  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.652  6777  6843 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 17:41:35.653  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:41:35.657  6777  6843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:41:35.657  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:35.657  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:35.657  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:41:35.657  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:41:35.657  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:35.657  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:41:35.657  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:41:35.659  6777  6843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:35.659  6777  6843 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:41:35.660  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:41:35.660  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:41:35.660  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:41:35.660  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:41:35.660  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 17:41:35.662  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:35.664  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:35.667  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 17:41:35.667  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:41:35.669  6777  6843 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 17:41:35.669  6777  6843 I io.jxcore.node.ConnectionHelper: start: OK
08-30 17:41:35.669  6777  6843 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:35.669  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:35.669  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:35.670  6777  6843 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:35.670  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:35.670  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:35.671  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:35.671  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.671  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:41:35.671  6777  6843 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208f2a0a not in the list
08-30 17:41:35.671  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.671  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.671  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:35.671  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.671  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.671  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.672  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:35.672  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:35.673  6777  6843 D BluetoothLeScanner: could not find callback wrapper
08-30 17:41:35.673  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:41:35.673  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.673  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.673  6777  6843 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-30 17:41:35.674  6777  6843 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:35.674  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:35.674  6777  6843 V io.jxcor,e.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:35.674  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:35.674  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.674  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.674  6777  6843 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208f2a0a not in the list
08-30 17:41:35.674  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.674  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.674  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:35.674  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.674  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.674  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.674  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.675  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:35.675  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:35.676  6777  6843 D BluetoothLeScanner: could not find callback wrapper
08-30 17:41:35.676  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:41:35.676  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.676  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.677  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 17:41:35.677  6777  6843 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:35.677  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:35.677  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:35.677  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:35.677  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.678  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.678  6777  6843 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208f2a0a not in the list
08-30 17:41:35.678  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.678  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.678  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:35.678  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.678  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.678  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.678  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.679  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:35.679  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:35.680  6777  6843 D BluetoothLeScanner: could not find callback wrapper
08-30 17:41:35.680  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:41:35.680  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.680  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.681  6777  6843 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 17:41:35.681  6777  6843 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:35.681  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:35.681  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:35.681  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:35.681  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.681  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.682  6777  6843 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208f2a0a not in the list
08-30 17:41:35.682  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.682  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.682  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:35.682  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.682  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.682  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.682  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.684  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:35.684  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:35.684  6777  6843 D BluetoothLeScanner: could not find callback wrapper
08-30 17:41:35.684  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:41:35.684  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.684  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.685  6777  6843 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 17:41:35.686  6777  6843 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:35.686  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:35.686  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:35.686  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:35.686  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.686  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.686  6777  6843 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208f2a0a not in the list
08-30 17:41:35.686  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.686  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.686  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:35.686  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.686  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.686  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.686  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.687  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:35.687  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:35.687  6777  6843 D BluetoothLeScanner: could not find callback wrapper
08-30 17:41:35.687  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:41:35.688  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.688  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.689  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 17:41:35.689  6777  6843 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 17:41:35.689  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 17:41:35.689  6777  6843 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 17:41:35.689  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 17:41:35.689  6777  6843 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 17:41:35.689  6777  6843 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:35.689  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:35.689  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:35.690  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:35.690  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.690  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.690  6777  6843 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208f2a0a not in the list
08-30 17:41:35.690  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.690  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.690  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:35.690  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.690  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.690  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.690  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.692  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:35.692  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:35.692  6777  6843 D BluetoothLeScanner: could not find callback wrapper
08-30 17:41:35.692  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:41:35.692  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.693  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.694  6777  6843 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:41:35.694  6777  6843 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 17:41:35.694  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 17:41:35.698  6777  6843 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:41:35.698  6777  6843 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 17:41:35.698  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 17:41:35.698  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 17:41:35.698  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 17:41:35.698  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 17:41:35.698  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 17:41:35.701  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 17:41:35.701  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 17:41:35.701  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 17:41:35.701  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 17:41:35.701  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 17:41:35.701  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 17:41:35.701  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 17:41:35.701  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 17:41:35.701  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 17:41:35.701  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 17:41:35.701  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 17:41:35.701  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 17:41:35.701  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 17:41:35.701  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 17:41:35.701  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 17:41:35.702  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 17:41:35.702  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 17:41:35.702  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 17:41:35.702  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 17:41:35.702  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 17:41:35.702  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 17:41:35.702  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 17:41:35.702  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 17:41:35.702  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 17:41:35.702  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 17:41:35.702  6777  6843 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,08-30 17:41:35.702  6777  6843 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 17:41:35.702  6777  6843 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 17:41:35.703  6777  6843 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:41:35.703  6777  6843 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 17:41:35.703  6777  6843 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 17:41:35.703  6777  6843 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:41:35.703  6777  6843 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 17:41:35.703  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 17:41:35.707  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-30 17:41:35.709  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 17:41:35.709  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 17:41:35.710  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 17:41:35.710  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 17:41:35.710  6777  6843 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 17:41:35.710  6777  6843 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:41:35.710  6777  6843 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 17:41:35.711  6777  6843 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:35.711  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:35.711  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:35.711  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:35.711  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.711  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.711  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 17:41:35.712  6777  6843 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208f2a0a not in the list
08-30 17:41:35.712  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.712  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.712  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:35.712  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.712  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.712  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.712  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.715  6777  6861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 836)
08-30 17:41:35.716  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:35.716  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:35.716  6777  6862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 836
08-30 17:41:35.718  6777  6843 D BluetoothLeScanner: could not find callback wrapper
08-30 17:41:35.718  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:41:35.718  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.718  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.721  6777  6843 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 17:41:35.721  6777  6843 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:35.721  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:35.721  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:35.722  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:35.722  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.722  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.722  6777  6843 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208f2a0a not in the list
08-30 17:41:35.722  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.722  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.722  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:35.722  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.722  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.722  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.722  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.724  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:35.724  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:35.724  6777  6843 D BluetoothLeScanner: could not find callback wrapper
08-30 17:41:35.724  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:41:35.725  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.725  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.726  6777  6843 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 17:41:35.726  6777  6843 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:35.727  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:35.727  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:35.727  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:35.727  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.727  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.727  6777  6843 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208f2a0a not in the list
08-30 17:41:35.727  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.727  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.727  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:35.727  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.727  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.727  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.727  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.729  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:35.729  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:35.729  6777  6843 D BluetoothLeScanner: could not find callback wrapper
08-30 17:41:35.730  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:41:35.730  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.730  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.731  6777  6843 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 17:41:35.731  6777  6843 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 17:41:35.731  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 17:41:35.731  6777  6843 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 17:41:35.731  6777  6843 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 17:41:35.731  6777  6843 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 17:41:35.731  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 17:41:35.731  6777  6843 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 17:41:35.731  6777  6843 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 17:41:35.732  6777  6843 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 17:41:35.732  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 17:41:35.732  6777  6843 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 17:41:35.732  6777  6843 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:35.732  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:35.732  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:35.734  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:35.734  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.734  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.734  6777  6843 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208f2a0a not in the list
08-30 17:41:35.734  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.734  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.734  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:35.734  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.734  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.734  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.734  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.735  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:35.735  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:35.735  6777  6843 D BluetoothLeScanner: could not find callback wrapper
08-30 17:41:35.735  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:41:35.735  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.736  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.738  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:35.738  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.738  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.738  6777  6843 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208f2a0a not in the list
08-30 17:41:35.738  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.738  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.738  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:35.738  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.739  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.740  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.740  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.740  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:35.740  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.740  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.740  6777  6843 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208f2a0a not in the list
08-30 17:41:35.740  6777  6843 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:35.740  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:35.740  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:35.742  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:35.742  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.742  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.742  6777  6843 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208f2a0a not in the list
08-30 17:41:35.742  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.742  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.742  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:35.742  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.742  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.742  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.742  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.746  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:41:35.746  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:35.747  6777  6843 D BluetoothLeScanner: could not find callback wrapper
08-30 17:41:35.747  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:41:35.747  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.747  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.750  6777  6843 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 17:41:35.750  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:41:35.758  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 17:41:35.758  6777  6843 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 17:41:35.759  6777  6843 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 17:41:35.760  6777  6777 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 17:41:35.760  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 17:41:35.760  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 17:41:35.761  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:35.761  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 17:41:35.761  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 17:41:35.761  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 17:41:35.761  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.761  6777  6843 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 17:41:35.763  6777  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 17:41:35.763  6777  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 17:41:35.763  6777  6777 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 17:41:35.764  6777  6843 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208f2a0a not in the list
08-30 17:41:35.764  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.764  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:41:35.764  6777  6843 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:41:35.764  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 17:41:35.766  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 17:41:35.769  6777  6843 D BluetoothLeScanner: could not find callback wrapper
08-30 17:41:35.769  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:41:35.769  6777  6843 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 17:41:35.769  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.769  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.771  6777  6843 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:41:35.778  6777  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 17:41:35.778  6777  6777 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 17:41:35.778  6777  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:41:35.778  6777  6777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:41:35.778  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.779  6777  6843 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:35.779  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:35.779  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:35.779  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:35.779  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.779  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.779  6777  6843 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208f2a0a not in the list
08-30 17:41:35.779  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.779  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.779  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:35.779  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.779  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.779  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.779  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.781  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:35.781  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:35.781  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.781  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.782  6777  6843 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 17:41:35.783  6777  6843 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 17:41:35.783  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 17:41:35.785  6777  6843 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 17:41:35.786  6777  6843 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connect,ions
08-30 17:41:35.786  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:35.786  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:35.786  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:35.786  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.786  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.786  6777  6843 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208f2a0a not in the list
08-30 17:41:35.786  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.786  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.786  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:35.786  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.787  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.787  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.787  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.789  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:35.789  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:35.789  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.789  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.791  1034  1982 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:35.792  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:35.793  1034  1913 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:35.794  6777  6843 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:35.794  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:35.794  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:35.794  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:35.794  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.794  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.794  6777  6843 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208f2a0a not, in the list
08-30 17:41:35.794  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.795  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.795  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:35.795  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.795  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.795  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.795  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.797  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:35.797  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:35.797  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.797  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.798  6777  6843 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:35.798  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:35.798  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:35.799  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:35.799  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.799  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.799  6777  6843 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@208f2a0a not in the list
08-30 17:41:35.799  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.799  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.799  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:35.799  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.799  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.799  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:35.799  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:35.800  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:35.801  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:35.801  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:35.801  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@980227b not in the list
08-30 17:41:35.808  6777  6843 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 17:41:35.808  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 17:41:35.808  6777  6843 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 17:41:35.808  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 17:41:35.808  6777  6843 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 17:41:35.808  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 17:41:35.810  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 17:41:35.810  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 17:41:35.811  6777  6843 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 17:41:35.811  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 17:41:35.811  6777  6843 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 17:41:35.811  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 17:41:35.811  6777  6843 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 17:41:35.811  6777  6843 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 17:41:35.812  6777  6843 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 17:41:35.812  6777  6843 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 17:41:35.812  6777  6843 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 17:41:35.813  6777  6843 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 17:41:35.813  6777  6843 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 17:41:35.813  6777  6843 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 17:41:35.814  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:41:35.814  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dffa2b0 added. We now have 2 listener(s)
08-30 17:41:35.814  6777  6843 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:41:35.815  6777  6843 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 17:41:35.816  1034  1590 D WifiServiceImplEx: setWifiEnabled: true pid=6777, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 17:41:35.817  1034  1590 D WifiService: setWifiEnabled: true pid=6777, uid=10118
08-30 17:41:35.817  1034  1590 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 17:41:35.819  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:41:35.819  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d8a1529 added. We now have 3 listener(s)
08-30 17:41:35.819  6777  6843 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:41:35.830  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:41:35.830  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2cf3b0ae added. We now have 4 listener(s)
08-30 17:41:35.830  6777  6843 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:41:35.832  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:41:35.832  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@382b6e4f added. We now have 5 listener(s)
08-30 17:41:35.832  6777  6843 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:41:35.835  1034  1590 D WifiServiceImplEx: setWifiEnabled: false pid=6777, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 17:41:35.835  1034  1590 D WifiService: setWifiEnabled: false pid=6777, uid=10118
08-30 17:41:35.835  1034  1590 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 17:41:35.844  1034  1390 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 17:41:35.845  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 17:41:35.845  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 17:41:35.845  1034  1390 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 17:41:35.845  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 17:41:35.845  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-30 17:41:35.845  1034  1390 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 17:41:35.846  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 17:41:35.846  1034  1390 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 17:41:35.846  1034  1390 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 17:41:35.846  1034  1390 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 17:41:35.847  1034  1982 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:35.847  1034  1982 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@d58d690 mBinding = false
08-30 17:41:35.847  1034  1390 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 17:41:35.847  1034  1390 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 17:41:35.848  6777  6861 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-30 17:41:35.848  6777  6861 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:41:35.849  3883  3903 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:41:35.849  3883  4069 W bt-l2cap: L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 001122334455  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
08-30 17:41:35.849  3883  3903 D LGBluetoothServiceAdapter: [BTUI] connectSocket FD=84 mFd=82
08-30 17:41:35.857  1034  1390 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 17:41:35.857  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 17:41:35.857  1034  1389 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:35.857  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:35.857  2676  2676 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 17:41:35.857  1034  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 17:41:35.857  1034  1390 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 17:41:35.858  1034  1390 D WifiNative-wlan0: SET ps 1: returned true
08-30 17:41:35.858   307   893 D CommandListener: Clearing all IP addresses on wlan0
08-30 17:41:35.859  1034  1098 D BluetoothManagerService: Message: 2
08-30 17:41:35.860  1034  1098 D BluetoothManagerService: Sending off request.
08-30 17:41:35.861  3883  3901 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 17:41:35.861  1034  2845 D DhcpStateMachine: RunningState{ when=-3ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:35.862  3883  3967 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 17:41:35.862  3883  3967 D BluetoothAdapterProperties: Setting state to 13
08-30 17:41:35.862  3883  3967 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 17:41:35.862  3883  3967 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 17:41:35.862  1034  1098 D BluetoothManagerService: Message: 60
08-30 17:41:35.862  1034  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-30 17:41:35.862  1034  1098 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-30 17:41:35.864  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:41:35.866  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:41:35.866  6777  6843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:41:35.866  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:35.866  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:35.866  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:41:35.866  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:41:35.866  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:35.866  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:41:35.866  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:41:35.868  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:41:35.868  6777  6843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:35.869  6777  6843 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:41:35.871  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:41:35.874  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 17:41:35.885  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 17:41:35.885  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 17:41:35.885  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-30 17:41:35.899  3883  3883 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:35.899  3883  3883 D BluetoothMapService: STATE_TURNING_OFF
08-30 17:41:35.899  3883  3883 V BluetoothMapService: Handler(): got msg=4
08-30 17:41:35.899  3883  3883 D BluetoothMapService: MAP Service closeService in
08-30 17:41:35.899  3883  3883 D BluetoothMapMasInstance: MAP Service shutdown
,08-30 17:41:35.902  3883  4222 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 17:41:35.902  3883  4222 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 17:41:35.902  3883  4222 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 17:41:35.902  3883  4222 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 17:41:35.902  3883  4222 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 17:41:35.902  3883  4222 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 17:41:35.902  3883  4222 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 17:41:35.902  3883  4222 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-30 17:41:35.902  3883  3883 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 17:41:35.902  3883  3883 V BluetoothMapService: MAP Service closeService out
08-30 17:41:35.903  1034  1404 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 17:41:35.903  1034  1404 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-30 17:41:35.904  3883  3883 V BtOppService: Receiver DISABLED_ACTION 
08-30 17:41:35.904  3883  3883 I BtOppRfcommListener: stopping Accept Thread
08-30 17:41:35.905  3883  3883 V BtOppRfcommListener: close mBtServerSocket
08-30 17:41:35.905  3883  3883 V BtOppRfcommListener: waiting for thread to terminate
08-30 17:41:35.905  3883  4276 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 17:41:35.905  3883  4276 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 17:41:35.905  3883  3883 V BtOppRfcommListener: done waiting for thread to terminate
08-30 17:41:35.907  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:41:35.907  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:41:35.907  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:35.907  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:35.907  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:41:35.907  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:41:35.907  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:41:35.907  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:41:35.907  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:41:35.911  1034  1091 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6878 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 17:41:35.915  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:41:35.915  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:41:35.917  1034  1390 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:35.917  1034  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:35.917  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:35.918  3883  3883 V BtOppService: onDestroy
08-30 17:41:35.918  1034  1389 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2bb90821
08-30 17:41:35.927  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 0
,08-30 17:41:35.930  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:41:35.930  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:41:35.930  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:35.930  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:35.930  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:41:35.930  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:41:35.930  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:41:35.930  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:41:35.930  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:41:35.931  1034  1389 D LGWifiP2pService: P2pDisablingState
08-30 17:41:35.931  1034  1389 D LGWifiP2pService: P2pDisablingState{ when=-13ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:35.931  1034  1389 D LGWifiP2pService: p2p socket connection lost
08-30 17:41:35.932  1034  1389 D LGWifiP2pService: P2pDisabledState
08-30 17:41:35.932  3883  3883 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 17:41:35.933  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:41:35.933  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:41:35.933  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:35.934  1034  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:35.934  1034  1390 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:35.935  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:35.935  1034  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:35.935  1034  1390 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 17:41:35.936  1034  1390 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 17:41:35.936  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:35.937  1034  1389 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:35.937  1034  1389 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:35.937  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:35.937  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 17:41:35.938  2676  2676 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 17:41:35.938  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-30 17:41:35.938  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:35.938  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:35.938  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 17:41:35.938  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-30 17:41:35.939  1034  1034 W Settings: Setting s,tay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:35.939  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:35.939  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 17:41:35.939  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 17:41:35.939  1034  1557 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:35.940  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-30 17:41:35.940  1034  1558 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:35.940  1034  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 17:41:35.940  1034  1390 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 17:41:35.941  1034  1390 D WifiNative-wlan0: SET ps 1: returned true
08-30 17:41:35.941  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,08-30 17:41:35.944  1940  1940 D WfdsService: WifiP2pState is changed : false
08-30 17:41:35.944  1940  2287 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 17:41:35.944  1940  2287 D WfdsService: Set the WFDS Monitor: false
08-30 17:41:35.944  1940  2287 D WfdsMonitor: WFDS Monitor is stopped
08-30 17:41:35.945  1940  2287 D WfdsService: STATE : WfdsDisabledState - enter
08-30 17:41:35.945  1940  2723 D CtrlSupplicant: Received on exit socket, terminate
08-30 17:41:35.945  1940  2723 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 17:41:35.945  1940  2723 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 17:41:35.945  1940  2723 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 17:41:35.945  1940  2291 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 17:41:35.945  1940  2287 W WfdsService: DefaultState - msg [9445378] is not handled
08-30 17:41:35.951  6469  6469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:41:35.959   307   893 D CommandListener: Clearing all IP addresses on wlan0
08-30 17:41:35.961  1034  1404 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 17:41:35.961  1034  1404 D DSQN    : disableDataServiceNotify
08-30 17:41:35.961  1034  1404 D DSQN    : stop dsqn bin
,08-30 17:41:35.969  1034  1404 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 17:41:35.969  1034  1404 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:35.969  1034  1404 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:41:35.970  1034  1404 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:41:35.970  1034  1404 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-30 17:41:35.970  1603  2073 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 17:41:35.970  1034  1404 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-30 17:41:35.971  1034  1404 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 17:41:35.971  1034  1404 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 17:41:35.971  1034  2841 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:35.971  1034  2841 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:35.971  1034  2841 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 17:41:35.973  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:35.973  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 17:41:35.974  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:35.974  1034  1937 I art     : Explicit concurrent mark sweep GC freed 35229(1661KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.027ms total 123.462ms
08-30 17:41:35.976  3883  3967 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 17:41:35.977  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:35.977  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:41:35.978  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:35.981  1034  1049 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6900 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 17:41:35.984  1034  1390 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 17:41:35.984  1034  1404 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:41:35.984  1034  1404 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 17:41:35.984  3883  3972 D BluetoothAdapterProperties: Scan Mode:20
08-30 17:41:35.984  1034  1404 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:35.984  1034  1390 D WifiNative-p2p0: TERMINATE: returned true
08-30 17:41:35.984  1034  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 17:41:35.984  1034  1390 E WifiStateMachine: useWiFiOffloading() : false
08-30 17:41:35.984  1034  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 17:41:35.984  3883  3967 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 17:41:35.984  1034  1404 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:35.985  3883  4226 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 17:41:35.985  3883  4279 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 17:41:35.985  3883  4069 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 17:41:35.985  3883  3967 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 17:41:35.985  3883  4069 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
,08-30 17:41:35.985  3883  4282 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 17:41:35.985  1034  1404 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:35.986  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-30 17:41:35.986  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:35.986  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:35.986  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 17:41:35.986  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 17:41:35.986  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 17:41:35.987  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 17:41:35.987  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 17:41:35.987  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 17:41:35.987  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 17:41:35.987  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 17:41:35.987  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 17:41:35.987  6777  6861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 836)
08-30 17:41:35.988  1851  1851 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:35.988  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 17:41:35.990  3883  4069 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 17:41:35.990  3883  4069 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 17:41:35.990  3883  4069 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 17:41:35.990  3883  4069 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 17:41:35.990  3883  4069 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:41:35.990  3883  4069 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 17:41:35.990  3883  4069 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:41:35.990  3883  4069 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 17:41:35.990  3883  4069 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:41:35.990  3883  4069 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 17:41:35.990  3883  4069 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 17:41:35.990  3883  4069 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 17:41:35.990  1034  1388 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 17:41:35.990  1034  1388 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 17:41:35.990  1034  1404 D NetworkManagementService: Removing idletimer
08-30 17:41:35.991  1034  1404 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.,System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:35.991  1034  1404 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 17:41:35.991  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 17:41:35.991  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:41:35.996  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 17:41:36.009  1034  1390 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:36.009  1034  1390 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-30 17:41:36.011  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:41:36.012  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:41:36.012  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:36.012  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:36.012  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:41:36.012  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:41:36.012  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:41:36.012  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:41:36.012  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:41:36.012  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:41:36.012  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:41:36.013  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-30 17:41:36.013  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 17:41:36.016  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:41:36.016  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 17:41:36.017  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:41:36.017  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:41:36.017  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:36.017  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:36.017  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:41:36.017  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:41:36.017  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:41:36.017  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:41:36.017  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:41:36.018  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:41:36.018  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:41:36.021  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:41:36.021  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:41:36.021  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:36.021  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:36.021  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30, 17:41:36.021  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:41:36.021  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:41:36.021  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:41:36.021  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:41:36.022  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:36.028  6878  6878 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:41:36.028  6878  6878 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-30 17:41:36.029  6878  6878 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 17:41:36.029  6878  6878 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-30 17:41:36.030  6878  6878 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 17:41:36.030  6878  6878 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 17:41:36.039  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 17:41:36.040  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:36.040  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:36.050  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 17:41:36.050  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:36.051  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 17:41:36.051  6900  6900 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 17:41:36.053  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:36.055  6900  6900 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 17:41:36.055  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 17:41:36.057  1034  2397 I ActivityManager: Killing 6263:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-30 17:41:36.069  1034  2845 D DhcpStateMachine: StoppedState
,08-30 17:41:36.069  1034  2845 D DhcpStateMachine: StoppedState{ when=-128ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:36.078  2676  2676 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 17:41:36.078  2676  2676 I wpa_supplicant: monitor socket send errors count : 1
08-30 17:41:36.078  2676  2676 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1940-2\x00 that cannot receive messages
08-30 17:41:36.079  1034  2718 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 17:41:36.079  1034  2718 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 17:41:36.104  1034  1590 W libprocessgroup: failed to open /acct/uid_10014/pid_6263/cgroup.procs: No such file or directory
,08-30 17:41:36.105  1034  1390 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-30 17:41:36.106  1034  1390 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-30 17:41:36.112  2676  2676 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 17:41:36.112  1034  2718 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-30 17:41:36.113  1034  2718 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 17:41:36.113  1034  2718 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 17:41:36.113  1034  2718 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 17:41:36.113  2676  2676 W wpa_supplicant: USIM:  scard_deinit function
08-30 17:41:36.113  1034  2718 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,08-30 17:41:36.113  1034  2718 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 17:41:36.114  1034  1098 D Tethering: InitialState.processMessage what=4
08-30 17:41:36.115  1034  1390 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=177314
08-30 17:41:36.116  1034  1390 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=177316
08-30 17:41:36.116  1034  1098 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 17:41:36.117  1034  1390 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=177317  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 17:41:36.119  1034  1390 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=177319  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 17:41:36.120  1034  1390 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:41:36.121  1034  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:41:36.147  6878  6878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 17:41:36.153  3883  3883 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 17:41:36.153  3883  3883 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:36.153  3883  3883 V BluetoothPbapReceiver: ***********state = 13
08-30 17:41:36.155  3883  3883 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-30 17:41:36.156  3883  3883 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:36.156  3883  3883 V BluetoothPbapService: state: 13
08-30 17:41:36.156  3883  3883 V BluetoothPbapService: Pbap Service closeService in
08-30 17:41:36.159  3883  3883 V BluetoothPbapService: successfully stopped pbap service
08-30 17:41:36.159  3883  3883 V BluetoothPbapService: Pbap Service closeService out
,08-30 17:41:36.160  3883  3883 V BluetoothPbapService: Pbap Service onDestroy
08-30 17:41:36.160  3883  3883 V BluetoothPbapService: Pbap Service closeService in
08-30 17:41:36.160  3883  3883 V BluetoothPbapService: Pbap Service closeService out
08-30 17:41:36.160  3883  3883 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-30 17:41:36.160  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 17:41:36.161  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 17:41:36.183  6878  6878 D LgDataFeature: LgDataFeature() Constructor: none
08-30 17:41:36.183  6878  6878 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 17:41:36.193  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:36.198  1034  1098 D BluetoothManagerService: Message: 20
08-30 17:41:36.198  1034  1098 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@232be9a:true
,08-30 17:41:36.210  2676  2676 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-30 17:41:36.210  1034  2718 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-30 17:41:36.210  1034  2718 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-30 17:41:36.210  1034  2718 D WifiMonitor: Disconnecting from the supplicant, no more events
08-30 17:41:36.211  1034  1390 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,08-30 17:41:36.230  1034  2006 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6922 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-30 17:41:36.239  1034  1098 D BluetoothManagerService: Message: 30
08-30 17:41:36.245  1034  1098 D BluetoothManagerService: Message: 30
,08-30 17:41:36.257  6878  6878 D LocalBluetoothProfileManager: Adding local MAP profile
08-30 17:41:36.261  6878  6878 D BluetoothMap: Create BluetoothMap proxy object
,08-30 17:41:36.263  1034  1098 D BluetoothManagerService: Message: 30
08-30 17:41:36.272  1034  1098 D BluetoothManagerService: Message: 30
08-30 17:41:36.276  6878  6878 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-30 17:41:36.278  6878  6878 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-30 17:41:36.278  6777  6777 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-30 17:41:36.293  6878  6878 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-30 17:41:36.299  6878  6878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-30 17:41:36.311  6878  6878 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:41:36.313  1940  1940 D WfdsService: Supplicant Connection state is changed : false
08-30 17:41:36.313  1940  2287 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 17:41:36.313  1940  2287 D WfdsService: Set the WFDS Monitor: false
08-30 17:41:36.313  1940  2287 D WfdsMonitor: WFDS Monitor is stopped
08-30 17:41:36.314  1034  1390 D WifiOffDelayIfNotUsed: stopMonitoring
08-30 17:41:36.314  1034  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 17:41:36.314  1034  1390 E WifiStateMachine: useWiFiOffloading() : false
08-30 17:41:36.314  1034  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 17:41:36.315  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 17:41:36.316  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 17:41:36.316  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:36.317  1034  1395 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 17:41:36.317  1034  1395 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 17:41:36.318  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:36.323  2513  2513 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 17:41:36.327  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:36.340  6878  6878 D BluetoothInputDevice: Proxy object connected
,08-30 17:41:36.342  6878  6878 D HidProfile: Bluetooth service connected
08-30 17:41:36.343  6878  6878 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 17:41:36.344  6878  6878 D PanProfile: Bluetooth service connected
08-30 17:41:36.345  6878  6878 D BluetoothMap: Proxy object connected
08-30 17:41:36.346  6878  6878 D MapProfile: Bluetooth service connected
08-30 17:41:36.346  6878  6878 D BluetoothMap: getConnectedDevices()
08-30 17:41:36.347  6878  6878 D BluetoothMap: Bluetooth is Not enabled
08-30 17:41:36.347  6878  6878 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 17:41:36.395  1034  1049 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6946 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-30 17:41:36.397  1034  1049 I ActivityManager: Killing 6358:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-30 17:41:36.425   342   342 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 475us total 29.845ms
,08-30 17:41:36.446   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 419us total 20.946ms
,08-30 17:41:36.466   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 386us total 18.906ms
,08-30 17:41:36.470  1034  1785 W libprocessgroup: failed to open /acct/uid_10004/pid_6358/cgroup.procs: No such file or directory
08-30 17:41:36.484  6922  6922 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-30 17:41:36.484  6922  6922 W LG Account v2.2: No ProfileInfo entries
,08-30 17:41:36.485  6922  6922 I LG Account v2.2: isEnabled: false
,08-30 17:41:36.485  6922  6922 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 17:41:36.485  6922  6922 I Feature : [Lifetracker]Country: EU
,08-30 17:41:36.485  6922  6922 I Feature : [Lifetracker]Operator: OPEN
08-30 17:41:36.485  6922  6922 I Feature : [Lifetracker]Ranking support: false
08-30 17:41:36.485  6922  6922 I Feature : [Lifetracker]Comfort support: false
08-30 17:41:36.485  6922  6922 I Feature : [Lifetracker]Accessory: true
08-30 17:41:36.485  6922  6922 I Feature : [Lifetracker]Health device: true
08-30 17:41:36.485  6922  6922 I Feature : [Lifetracker]Extra Pedometer: false
08-30 17:41:36.485  6922  6922 I Feature : [Lifetracker]Blood glucose device: false
08-30 17:41:36.485  6922  6922 I Feature : [Lifetracker]Device Number: 3
08-30 17:41:36.500  6878  6878 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 17:41:36.506  6946  6946 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 17:41:36.510  6878  6878 D BluetoothPermissionRequest: onReceive
08-30 17:41:36.514  6878  6878 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 17:41:36.531  6878  6878 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 17:41:36.536  1034  1785 I ActivityManager: Killing 6511:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-30 17:41:36.568  1034  1050 W libprocessgroup: failed to open /acct/uid_10008/pid_6511/cgroup.procs: No such file or directory
08-30 17:41:36.569  3883  3883 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-30 17:41:36.569  3883  3883 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-30 17:41:36.570  3883  3883 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-30 17:41:36.573  6946  6946 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-30 17:41:36.579  3883  3883 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:36.579  3883  3883 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 17:41:36.582  3883  3883 V BluetoothFtpService: Ftp Service onStartCommand
08-30 17:41:36.582  3883  3883 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:36.582  3883  3883 V BluetoothFtpService: Ftp Service closeService
08-30 17:41:36.583  3883  3883 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,08-30 17:41:36.590  3883  3883 V BluetoothFtpService: successfully stopped ftp service
08-30 17:41:36.591  3883  3883 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 17:41:36.591  3883  3883 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 17:41:36.591  3883  3883 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 17:41:36.591  3883  3883 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:36.591  3883  3883 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 17:41:36.592  3883  3883 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 17:41:36.595  3883  3883 V BluetoothFtpService: Ftp Service onDestroy
08-30 17:41:36.595  3883  3883 V BluetoothFtpService: Ftp Service closeService
08-30 17:41:36.624  6946  6946 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-30 17:41:36.625  6946  6946 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-30 17:41:36.625  6946  6946 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-30 17:41:36.626  6946  6946 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-30 17:41:36.626  6946  6946 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-30 17:41:36.628  6946  6946 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-30 17:41:36.635  6946  6946 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-30 17:41:36.667  1034  2032 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6965 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 17:41:36.668  3883  3883 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:36.668  3883  3883 V BluetoothSapService: state: 13
08-30 17:41:36.668  3883  3883 V BluetoothSapService: Stopping SAP server process
08-30 17:41:36.671  3883  3883 V BluetoothSapService: Sap Service closeSapService in
08-30 17:41:36.671  3883  3883 V BluetoothSapService: Close listen Socket : 
08-30 17:41:36.671  3883  3883 V BluetoothSapService: Close rfcomm Socket : 
08-30 17:41:36.671  3883  3883 V BluetoothSapService: Close sapd  Socket : 
,08-30 17:41:36.673  3883  3883 V BluetoothSapService: Sap Service closeSapService out
08-30 17:41:36.673  3883  3883 V BluetoothSapService: Sap Service onDestroy
08-30 17:41:36.673  3883  3883 V BluetoothSapService: Sap Service closeSapService in
08-30 17:41:36.673  3883  3883 V BluetoothSapService: Close listen Socket : 
08-30 17:41:36.673  3883  3883 V BluetoothSapService: Close rfcomm Socket : 
08-30 17:41:36.673  3883  3883 V BluetoothSapService: Close sapd  Socket : 
08-30 17:41:36.674  3883  3883 V BluetoothSapService: Sap Service closeSapService out
08-30 17:41:36.684  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 17:41:36.687  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:41:36.706  6946  6946 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 17:41:36.709  6469  6469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:41:36.712  6900  6900 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 17:41:36.713  6900  6900 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 17:41:36.713  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 17:41:36.716  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 17:41:36.716  6946  6946 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-30 17:41:36.719  6946  6946 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-30 17:41:36.724  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:36.734  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:41:36.734  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 17:41:36.737  6946  6946 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 17:41:36.741  6469  6469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:41:36.744  6900  6900 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 17:41:36.744  6900  6900 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 17:41:36.745  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 17:41:36.748  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 17:41:36.749  6965  6965 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 17:41:36.757  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:36.762  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:41:36.763  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 17:41:36.765  6946  6946 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 17:41:36.811  1034  2006 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6988 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-30 17:41:36.814  1034  2006 I ActivityManager: Killing 6008:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-30 17:41:36.899  1034  1974 W libprocessgroup: failed to open /acct/uid_10011/pid_6008/cgroup.procs: No such file or directory
,08-30 17:41:36.983  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 17:41:36.991  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 17:41:36.994  3883  3972 D bt_hci_bdroid: cleanup
08-30 17:41:36.994  3883  4069 W bt-btif : ag scb idx 1 not allocated
08-30 17:41:36.994  3883  4069 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 17:41:36.994  3883  4069 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 17:41:36.994  3883  4069 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:41:36.994  3883  4069 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 17:41:36.994  3883  4069 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:41:36.994  3883  4069 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 17:41:36.994  3883  4069 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:41:36.994  3883  4069 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 17:41:36.994  3883  4069 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:41:36.994  3883  4069 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 17:41:36.994  3883  4069 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:41:36.995  3883  4069 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 17:41:36.995  3883  4069 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:41:36.995  3883  4069 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 17:41:36.995  3883  4069 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:41:36.995  3883  4069 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 17:41:36.995  3883  4069 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:41:36.995  3883  4069 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 17:41:36.995  3883  4069 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:41:36.995  3883  4069 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 17:41:36.995  3883  4072 I bt_lpm  : LPM is already off!!!
08-30 17:41:36.995  3883  4196 I bt_userial_mct: exiting userial_read_thread
08-30 17:41:36.995  3883  4196 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 17:41:36.996  3883  3972 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 17:41:36.996  3883  4072 I bt_vendor: hw_epilog_process
08-30 17:41:36.997  3883  3972 D bt_hci_bdroid: cleanup Finalizing cleanup
,08-30 17:41:36.997  3883  3972 D bt_userial_mct: userial_close
08-30 17:41:36.997  3883  3972 E bt_userial_mct: pthread_join() FAILED result:3
08-30 17:41:36.997  3883  3972 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-30 17:41:37.001  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:37.019  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 17:41:37.020  6878  6878 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 17:41:37.020  6878  6878 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 17:41:37.020  6878  6878 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 17:41:37.021  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-30 17:41:37.024  6988  7008 W FormManager: Network not available. Please check & try again.
08-30 17:41:37.034  6878  6878 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 17:41:37.034  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 17:41:37.034  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 17:41:37.034  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 17:41:37.034  6878  6878 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 17:41:37.035  6878  6878 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-30 17:41:37.042  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 17:41:37.042  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 17:41:37.044  6988  7009 V FormManager: Network unavailable.
08-30 17:41:37.044  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 17:41:37.046  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 17:41:37.052  6988  7009 V FormManager: Network unavailable.
,08-30 17:41:37.056  6900  6900 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-30 17:41:37.056  6900  6900 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 17:41:37.056  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 17:41:37.059  4312  7012 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 17:41:37.062  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:41:37.066  4312  7013 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 17:41:37.066  4312  7013 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 17:41:37.072  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:37.078  3883  3972 D bt_hci_bdroid: set_power 0
08-30 17:41:37.078  3883  3972 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 17:41:37.078  3883  3972 I bt_vendor: bluetooth satus is on
08-30 17:41:37.078  3883  3972 I bt_vendor: bt-vendor : resetting BT status
08-30 17:41:37.078  3883  3972 I bt_vendor: Starting hciattach daemon
08-30 17:41:37.078  3883  3972 I bt_vendor: try to set false
08-30 17:41:37.079  3883  3972 I bt_vendor: Starting hciattach daemon
08-30 17:41:37.079  3883  3972 I bt_vendor: try to set false
08-30 17:41:37.079  3883  3972 I bt_vendor: cleanup
,08-30 17:41:37.081  3883  4069 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 17:41:37.081  3883  3972 I GKI_LINUX: GKI_exit_task 0 done
08-30 17:41:37.081  3883  3972 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 17:41:37.082  3883  3967 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 17:41:37.084  6988  7014 W FormManager: Network not available. Please check & try again.
08-30 17:41:37.086  3883  3883 D HeadsetService: Received stop request...Stopping profile...
08-30 17:41:37.087  3883  3883 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 17:41:37.087  3883  3883 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 17:41:37.087  3883  3883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e33b168
08-30 17:41:37.087  3883  4000 D HeadsetStateMachine: Exit Disconnected: -1
08-30 17:41:37.088  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-30 17:41:37.089  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-30 17:41:37.091  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-30 17:41:37.091  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-30 17:41:37.093  3883  3883 D A2dpService: Received stop request...Stopping profile...
08-30 17:41:37.093  3883  4056 D A2dpStateMachine: Exit Disconnected: -1
08-30 17:41:37.094  3883  3883 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-30 17:41:37.095  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-30 17:41:37.097  6988  7015 V FormManager: Network unavailable.
08-30 17:41:37.097  3883  3967 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 17:41:37.098  3883  3883 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-30 17:41:37.098  3883  3883 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 17:41:37.098  3883  3883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e33b168
08-30 17:41:37.103  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-30 17:41:37.103  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 17:41:37.103  3883  3883 D HidService: Received stop request...Stopping profile...
08-30 17:41:37.103  3883  3883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e33b168
,08-30 17:41:37.104  6946  6946 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 17:41:37.106  3883  3883 D HeadsetStateMachine: Unbinding service...
08-30 17:41:37.106  6988  7015 V FormManager: Network unavailable.
08-30 17:41:37.107  6878  6878 D BluetoothInputDevice: Proxy object disconnected
08-30 17:41:37.107  3883  3883 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 17:41:37.107  3883  3883 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 17:41:37.107  3883  3883 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 17:41:37.107  3883  3883 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 17:41:37.107  3883  3883 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 17:41:37.107  3883  3883 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 17:41:37.107  3883  3883 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 17:41:37.108  3883  3883 D HealthService: Received stop request...Stopping profile...
08-30 17:41:37.108  3883  3883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e33b168
08-30 17:41:37.108  6878  6878 D HidProfile: Bluetooth service disconnected
08-30 17:41:37.109  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 17:41:37.109  6946  6946 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-30 17:41:37.109  3883  3883 D PanService: Received stop request...Stopping profile...
08-30 17:41:37.110  3883  3883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e33b168
08-30 17:41:37.111  3883  3883 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 17:41:37.111  3883  3883 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 17:41:37.111  3883  3883 D BtGatt.GattService: stop()
08-30 17:41:37.111  3883  3883 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 17:41:37.112  6878  6878 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 17:41:37.112  6878  6878 D PanProfile: Bluetooth service disconnected
08-30 17:41:37.112  3883  3883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e33b168
08-30 17:41:37.113  3883  3883 D BluetoothMapService: Received stop request...Stopping profile...
08-30 17:41:37.113  3883  3883 D BluetoothMapService: stop()
08-30 17:41:37.114  3883  3883 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 17:41:37.114  3883  3883 D BluetoothMapEmailAppObserver: removeReceiver()
08-30 17:41:37.114  3883  3883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e33b168
08-30 17:41:37.115  3883  3883 I BluetoothA2dpServiceJni: cleanupNative
08-30 17:41:37.116  3883  4057 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-30 17:41:37.119  3883  3883 I GKI_LINUX: GKI_exit_task 2 done
08-30 17:41:37.119  3883  3883 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 17:41:37.120  3883  3883 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 17:41:37.120  3883  3883 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 17:41:37.120  6878  6878 D BluetoothMap: Proxy object disconnected
08-30 17:41:37.120  6878  6878 D MapProfile: Bluetooth service disconnected
08-30 17:41:37.120  3883  3883 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 17:41:37.120  3883  3883 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 17:41:37.120  3883  3883 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 17:41:37.120  3883  3883 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 17:41:37.120  3883  3883 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 17:41:37.121  3883  3883 V BluetoothMapService: Handler(): got msg=4
08-30 17:41:37.122  3883  3883 D BluetoothMapService: MAP Service closeService in
08-30 17:41:37.122  3883  3883 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 17:41:37.122  3883  3883 V BluetoothMapService: MAP Service closeService out
08-30 17:41:37.122  3883  3883 D BluetoothMapService: cleanup()
08-30 17:41:37.122  3883  3883 D BluetoothMapService: MAP Service closeService in
08-30 17:41:37.122  3883  3883 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 17:41:37.122  3883  3883 V BluetoothMapService: MAP Service closeService out
08-30 17:41:37.122  3883  3967 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 17:41:37.122  3883  3967 D BluetoothAdapterProperties: Setting state to 10
08-30 17:41:37.122  3883  3967 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 17:41:37.123  3883  3967 I BluetoothAdapterState: Entering OffState
08-30 17:41:37.123  1034  1913 I ActivityManager: Killing 6030:com.android.contacts/u0a19 (adj 15): empty #17
08-30 17:41:37.123  1034  1098 D BluetoothManagerService: Message: 60
08-30 17:41:37.123  1034  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 17:41:37.124  1034  1098 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-30 17:41:37.124  6878  6897 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 17:41:37.154  6946  6946 D LgDataFeature: LgDataFeature() Constructor: none
08-30 17:41:37.155  6946  6946 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 17:41:37.167  6946  6946 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-30 17:41:37.169  6946  6946 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-30 17:41:37.169  6946  6946 V SoundPool: create sampleID=1, fd=32, offset=17813 length=10857164
08-30 17:41:37.169  6946  6946 V SoundPool: doLoad: loading sample sampleID=1
08-30 17:41:37.171  6946  7022 V SoundPool: Start decode
08-30 17:41:37.171  6946  7022 V MediaPlayer[Native]: decode(32, 10857164, 17813)
08-30 17:41:37.171  6946  6946 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 17:41:37.173   311  2143 V MediaPlayerService: decode(23, 10857164, 17813)
,08-30 17:41:37.174   311  2143 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-30 17:41:37.174   311  2143 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-30 17:41:37.174   311  2143 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-30 17:41:37.174   311  2143 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-30 17:41:37.174   311  2143 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-30 17:41:37.174   311  2143 V MediaPlayerService: player type = 3
08-30 17:41:37.174   311  2143 V AwesomePlayer: AwesomePlayer create()
08-30 17:41:37.174   311  2143 V AwesomePlayer: reset_l() 
08-30 17:41:37.174   311  2143 V AwesomePlayer: cancelPlayerEvents
08-30 17:41:37.174   311  2143 V AwesomePlayer: setAudioSink() 
08-30 17:41:37.174   311  2143 V AwesomePlayer: reset_l() 
08-30 17:41:37.175   311  2143 V AudioCache: notify(0xb100d300, 8, 0, 0)
08-30 17:41:37.175   311  2143 V AudioCache: ignored
08-30 17:41:37.175   311  2143 V AwesomePlayer: cancelPlayerEvents
08-30 17:41:37.175   311  2143 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-30 17:41:37.175   311  2143 V AwesomePlayer: setDataSource_l dataSource
08-30 17:41:37.175   311  2143 V LGParserOSAL: SniffLGParser start
08-30 17:41:37.175   311  2143 V LGParserOSAL: MainType:5, SubType=0
08-30 17:41:37.175   311  2143 V LGParserOSAL: #### check Mime : application/ogg
08-30 17:41:37.175   311  2143 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-30 17:41:37.175   311  2143 E MediaExtractor: Use LGExtractor :application/ogg 
08-30 17:41:37.224   311  2143 V LGParserOSAL: supported mime: application/ogg
08-30 17:41:37.224   311  2143 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-30 17:41:37.224   311  2143 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-30 17:41:37.224   311  2143 V AwesomePlayer: mBitrate = -1 bits/sec
08-30 17:41:37.224   311  2143 V AwesomePlayer: AudioTrack Setting
08-30 17:41:37.224   311  2143 V AwesomePlayer: AudioTrack Setting channelCount = 2
,08-30 17:41:37.224   311  2143 V AwesomePlayer: setAudioSource() 
08-30 17:41:37.224   311  2143 V MediaPlayerService: prepare
08-30 17:41:37.224   311  2143 V AwesomePlayer: prepareAsync_l() 
08-30 17:41:37.224   311  2143 V MediaPlayerService: wait for prepare
08-30 17:41:37.227   311  7023 V AwesomePlayer: onPrepareAsyncEvent() 
08-30 17:41:37.227   311  7023 V AwesomePlayer: initAudioDecoder() 
08-30 17:41:37.227   311  7023 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 17:41:37.227   311  7023 V AudioSystem: isOffloadSupported()
08-30 17:41:37.227   311  7023 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 17:41:37.227   311  7023 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 17:41:37.227   311  7023 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 17:41:37.227   311  7023 V AwesomePlayer: getUseOffload() = 0 
08-30 17:41:37.227   311  7023 V OMXCodec: OMXCodec::Create
08-30 17:41:37.228   311  7023 V OMXCodec: findMatchingCodecs()
08-30 17:41:37.228   311  7023 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-30 17:41:37.228   311  7023 V OMXCodec: matchingCodecs.size()=1
,08-30 17:41:37.228   311  7023 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-30 17:41:37.232   311  7023 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,08-30 17:41:37.233   311  7023 V LGCodecAdapter: LG Codec Adapter start
08-30 17:41:37.233   311  7023 V OMXCodec: OMXCodec Createtor
08-30 17:41:37.233   311  7023 V OMXCodec: setComponentRole
08-30 17:41:37.233   311  7023 V OMXCodec: configureCodec protected=0
08-30 17:41:37.233   311  7023 V LGCodecAdapter: called getLGCodecSpecificData
08-30 17:41:37.233   311  7023 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-30 17:41:37.233   311  7023 V LGCodecOSAL: Called LGconfigureCodecMETA
,08-30 17:41:37.233   311  7023 V LGCodecOSAL: Called LGconfigureCodecMSG
08-30 17:41:37.233   311  7023 V LGCodecOSAL: Not support LGCodec
08-30 17:41:37.233   311  7023 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 17:41:37.234   311  7023 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-30 17:41:37.234   311  7023 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-30 17:41:37.234   311  7023 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-30 17:41:37.234   311  7023 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 17:41:37.234   311  7023 V AudioSystem: isOffloadSupported()
08-30 17:41:37.234   311  7023 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 17:41:37.234   311  7023 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
,08-30 17:41:37.234   311  7023 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-30 17:41:37.234   311  7023 V OMXCodec: init()
08-30 17:41:37.234   311  7023 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-30 17:41:37.235   311  7023 V OMXCodec: allocateBuffers
08-30 17:41:37.235   311  7023 V OMXCodec: allocateBuffersOnPort portIndex=0
08-30 17:41:37.235   311  7023 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-30 17:41:37.235   311  7023 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
08-30 17:41:37.235   311  7023 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-30 17:41:37.236   311  7023 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-30 17:41:37.236   311  7023 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
,08-30 17:41:37.236   311  7023 V OMXCodec: allocateBuffersOnPort portIndex=1,
08-30 17:41:37.236   311  7023 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 17:41:37.237   311  7023 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-30 17:41:37.237   311  7023 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-30 17:41:37.237   311  7023 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-30 17:41:37.237   311  7023 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bf380 on output port
08-30 17:41:37.237   311  7023 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 17:41:37.237   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
,08-30 17:41:37.238   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 17:41:37.239   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-30 17:41:37.239   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-30 17:41:37.239   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-30 17:41:37.239   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-30 17:41:37.239   311  7023 V OMXCodec: init() mAsyncCompletion wait free! 
08-30 17:41:37.239   311  7023 V AwesomePlayer: finishAsyncPrepare_l() 
08-30 17:41:37.239   311  7023 V AudioCache: notify(0xb100d300, 5, 0, 0)
08-30 17:41:37.239   311  7023 V AudioCache: ignored
,08-30 17:41:37.239   311  7023 V AudioCache: notify(0xb100d300, 1, 0, 0)
08-30 17:41:37.239   311  7023 V AudioCache: prepared
08-30 17:41:37.239   311  2143 V AudioCache: wait - success
08-30 17:41:37.239   311  2143 V MediaPlayerService: start
08-30 17:41:37.239   311  2143 V AwesomePlayer: play_l() 
08-30 17:41:37.240   311  2143 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-30 17:41:37.240   311  2143 V AwesomePlayer: createAudioPlayer_l
08-30 17:41:37.240   311  2143 V AwesomePlayer: seekAudioIfNecessary_l() 
08-30 17:41:37.240   311  2143 V AwesomePlayer: startAudioPlayer_l() 
08-30 17:41:37.240   311  2143 D AudioPlayer: start of Playback, useOffload 0
,08-30 17:41:37.240   311  2143 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 17:41:37.240   311  2143 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 17:41:37.247   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-30 17:41:37.247   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-30 17:41:37.247   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-30 17:41:37.247   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-30 17:41:37.247   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-30 17:41:37.247   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
,08-30 17:41:37.249   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
08-30 17:41:37.249   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 17:41:37.249   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-30 17:41:37.249   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 17:41:37.249   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
08-30 17:41:37.249   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 17:41:37.249   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044799360
08-30 17:41:37.249   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 17:41:37.249   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-30 17:41:37.249   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 17:41:37.250   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-30 17:41:37.250   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-30 17:41:37.250   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-30 17:41:37.250   311  7025 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 17:41:37.250   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 17:41:37.250   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-30 17:41:37.250   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-30 17:41:37.250   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-30 17:41:37.250   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f380 on output port
08-30 17:41:37.250   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-30 17:41:37.250   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-30 17:41:37.254   311  2143 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-30 17:41:37.255   311  2143 V AudioCache: notify(0xb100d300, 6, 0, 0)
08-30 17:41:37.255   311  2143 V AudioCache: ignored
08-30 17:41:37.256   311  2143 V MediaPlayerService: wait for playback complete
08-30 17:41:37.256   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.256   311  7027 V AudioCache: memcpy(0xaf004000, 0xb1788000, 4096)
08-30 17:41:37.260   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.260   311  7027 V AudioCache: memcpy(0xaf005000, 0xb1788000, 4096)
,08-30 17:41:37.261  1034  1590 W libprocessgroup: failed to open /acct/uid_10019/pid_6030/cgroup.procs: No such file or directory
08-30 17:41:37.262   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.262   311  7027 V AudioCache: memcpy(0xaf006000, 0xb1788000, 4096)
08-30 17:41:37.263  6878  6894 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 17:41:37.265   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.265   311  7027 V AudioCache: memcpy(0xaf007000, 0xb1788000, 4096)
08-30 17:41:37.265   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.265   311  7027 V AudioCache: memcpy(0xaf008000, 0xb1788000, 4096)
08-30 17:41:37.267   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.267   311  7027 V AudioCache: memcpy(0xaf009000, 0xb1788000, 4096)
08-30 17:41:37.267   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.267   311  7027 V AudioCache: memcpy(0xaf00a000, 0xb1788000, 4096)
08-30 17:41:37.268   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.268   311  7027 V AudioCache: memcpy(0xaf00b000, 0xb1788000, 4096)
08-30 17:41:37.269   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.269   311  7027 V AudioCache: memcpy(0xaf00c000, 0xb1788000, 4096)
08-30 17:41:37.270   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.270   311  7027 V AudioCache: memcpy(0xaf00d000, 0xb1788000, 4096)
08-30 17:41:37.271   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.271   311  7027 V AudioCache: memcpy(0xaf00e000, 0xb1788000, 4096)
08-30 17:41:37.272   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.272   311  7027 V AudioCache: memcpy(0xaf00f000, 0xb1788000, 4096)
,08-30 17:41:37.273   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.273   311  7027 V AudioCache: memcpy(0xaf010000, 0xb1788000, 4096)
08-30 17:41:37.274  6681  6681 D UEI.SmartControl: QS Service created
08-30 17:41:37.275   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.275   311  7027 V AudioCache: memcpy(0xaf011000, 0xb1788000, 4096)
08-30 17:41:37.277  1034  1098 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:41:37.277   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.277   311  7027 V AudioCache: memcpy(0xaf012000, 0xb1788000, 4096)
08-30 17:41:37.277  1034  1098 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 17:41:37.277  6878  6897 D BluetoothPan: onBluetoothStateChange on: false
08-30 17:41:37.278   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.278   311  7027 V AudioCache: memcpy(0xaf013000, 0xb1788000, 4096)
08-30 17:41:37.278   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.278   311  7027 V AudioCache: memcpy(0xaf014000, 0xb1788000, 4096)
08-30 17:41:37.278   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.278   311  7027 V AudioCache: memcpy(0xaf015000, 0xb1788000, 4096)
08-30 17:41:37.279  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:41:37.279  1851  2455 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:41:37.280   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.280   311  7027 V AudioCache: memcpy(0xaf016000, 0xb1788000, 4096)
08-30 17:41:37.280  1851  1867 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:41:37.280   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.280   311  7027 V AudioCache: memcpy(0xaf017000, 0xb1788000, 4096)
08-30 17:41:37.281  6878  6894 D BluetoothMap: onBluetoothStateChange: up=false
08-30 17:41:37.281   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.281   311  7027 V AudioCache: memcpy(0xaf018000, 0xb1788000, 4096)
08-30 17:41:37.282  6946  6946 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-30 17:41:37.282  1034  1098 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 17:41:37.282   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.282  1034  1098 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 17:41:37.282   311  7027 V AudioCache: memcpy(0xaf019000, 0xb1788000, 4096)
08-30 17:41:37.284   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.284   311  7027 V AudioCache: memcpy(0xaf01a000, 0xb1788000, 4096)
,08-30 17:41:37.285   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.285   311  7027 V AudioCache: memcpy(0xaf01b000, 0xb1788000, 4096)
08-30 17:41:37.286  1034  1098 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 17:41:37.286  6946  6946 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 17:41:37.286  1034  1098 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 17:41:37.286   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.286   311  7027 V AudioCache: memcpy(0xaf01c000, 0xb1788000, 4096)
08-30 17:41:37.286  1034  1098 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@d58d690 mBinding = false
08-30 17:41:37.286  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 17:41:37.287   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.287   311  7027 V AudioCache: memcpy(0xaf01d000, 0xb1788000, 4096)
08-30 17:41:37.287  1034  1098 D BluetoothManagerService: Sending unbind request.
08-30 17:41:37.289   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.289   311  7027 V AudioCache: memcpy(0xaf01e000, 0xb1788000, 4096)
08-30 17:41:37.289   311  7027 V AudioCache: write(0xb1788000, 4096)
,08-30 17:41:37.289   311  7027 V AudioCache: memcpy(0xaf01f000, 0xb1788000, 4096)
08-30 17:41:37.290   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.290   311  7027 V AudioCache: memcpy(0xaf020000, 0xb1788000, 4096)
08-30 17:41:37.291   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.291   311  7027 V AudioCache: memcpy(0xaf021000, 0xb1788000, 4096)
08-30 17:41:37.291   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.291   311  7027 V AudioCache: memcpy(0xaf022000, 0xb1788000, 4096)
08-30 17:41:37.292  1034  1098 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-30 17:41:37.292   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.292   311  7027 V AudioCache: memcpy(0xaf023000, 0xb1788000, 4096)
08-30 17:41:37.293   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.293   311  7027 V AudioCache: memcpy(0xaf024000, 0xb1788000, 4096)
08-30 17:41:37.294   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.294   311  7027 V AudioCache: memcpy(0xaf025000, 0xb1788000, 4096)
08-30 17:41:37.294   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.294   311  7027 V AudioCache: memcpy(0xaf026000, 0xb1788000, 4096)
08-30 17:41:37.295   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.295   311  7027 V AudioCache: memcpy(0xaf027000, 0xb1788000, 4096)
08-30 17:41:37.296  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:37.296   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.296   311  7027 V AudioCache: memcpy(0xaf028000, 0xb1788000, 4096)
08-30 17:41:37.296  1940  2127 D LGBluetoothAPIService: Message: 2
08-30 17:41:37.296  1940  2127 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@55b961b mBinding = false
08-30 17:41:37.296   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.297   311  7027 V AudioCache: memcpy(0xaf029000, 0xb1788000, 4096)
08-30 17:41:37.297  1940  2127 D LGBluetoothAPIService: Sending unbind request.
08-30 17:41:37.297   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.297   311  7027 V AudioCache: memcpy(0xaf02a000, 0xb1788000, 4096)
08-30 17:41:37.298  3883  3972 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-30 17:41:37.298  3883  3883 I GKI_LINUX: GKI_exit_task 1 done
08-30 17:41:37.298  3883  3883 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 17:41:37.299  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 17:41:37.299   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.299   311  7027 V AudioCache: memcpy(0xaf02b000, 0xb1788000, 4096)
08-30 17:41:37.300   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.300   311  7027 V AudioCache: memcpy(0xaf02c000, 0xb1788000, 4096)
08-30 17:41:37.300  3883  3883 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 17:41:37.301   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.301   311  7027 V AudioCache: memcpy(0xaf02d000, 0xb1788000, 4096)
08-30 17:41:37.302   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.302   311  7027 V AudioCache: memcpy(0xaf02e000, 0xb1788000, 4096)
08-30 17:41:37.302   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.302   311  7027 V AudioCache: memcpy(0xaf02f000, 0xb1788000, 4096)
08-30 17:41:37.303   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.303   311  7027 V AudioCache: memcpy(0xaf030000, 0xb1788000, 4096)
08-30 17:41:37.304   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.304   311  7027 V AudioCache: memcpy(0xaf031000, 0xb1788000, 4096)
08-30 17:41:37.304  6946  6946 V LGMDMManager: Create singleton instance
08-30 17:41:37.305   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.305   311  7027 V AudioCache: memcpy(0xaf032000, 0xb1788000, 4096)
08-30 17:41:37.305   311  7027 V AudioCache: write(0xb1788000, 4096),
08-30 17:41:37.305   311  7027 V AudioCache: memcpy(0xaf033000, 0xb1788000, 4096)
08-30 17:41:37.307  3883  3883 I art     : --- WEIRD: removing null entry 246
08-30 17:41:37.307  3883  3883 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-30 17:41:37.307  3883  3883 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-30 17:41:37.307  6878  6878 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 17:41:37.307   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.307   311  7027 V AudioCache: memcpy(0xaf034000, 0xb1788000, 4096)
08-30 17:41:37.308  6878  6878 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 17:41:37.308  6878  6878 D LGBluetoothEventManager: [BTUI] clear device connection state
08-30 17:41:37.308  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:37.308   311  7027 V AudioCache: write(0xb1788000, 4096)
08-30 17:41:37.308   311  7027 V AudioCache: memcpy(0xaf035000, 0xb1788000, 4096)
08-30 17:41:37.309   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-30 17:41:37.309   311  7027 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 17:41:37.309   311  7027 V AwesomePlayer: postAudioEOS() 
08-30 17:41:37.309  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:37.309   311  7027 V AudioCache: write(0xb1788000, 280)
08-30 17:41:37.309   311  7027 V AudioCache: memcpy(0xaf036000, 0xb1788000, 280)
08-30 17:41:37.310  6878  6878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 17:41:37.310   311  7023 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-30 17:41:37.311   311  7023 V AwesomePlayer: onStreamDone
08-30 17:41:37.311   311  7023 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-30 17:41:37.311   311  7023 V AudioCache: notify(0xb100d300, 2, 0, 0)
08-30 17:41:37.311   311  7023 V AudioCache: playback complete
08-30 17:41:37.311   311  7023 V AwesomePlayer: pause_l() 
08-30 17:41:37.311   311  7023 V AudioCache: notify(0xb100d300, 7, 0, 0)
08-30 17:41:37.311   311  7023 V AudioCache: ignored
08-30 17:41:37.311   311  7023 V AwesomePlayer: cancelPlayerEvents
08-30 17:41:37.311   311  2143 V AudioCache: wait - success
08-30 17:41:37.311   311  2143 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-30 17:41:37.311   311  7023 D AudioPlayer: Pause Playback at 1068125
08-30 17:41:37.311   311  2143 V AwesomePlayer: reset_l() 
08-30 17:41:37.311   311  2143 V AudioCache: notify(0xb100d300, 8, 0, 0)
08-30 17:41:37.311   311  2143 V AudioCache: ignored
08-30 17:41:37.311   311  2143 V AwesomePlayer: cancelPlayerEvents
08-30 17:41:37.311   311  2143 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
,08-30 17:41:37.311   311  2143 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-30 17:41:37.311   311  2143 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-30 17:41:37.311   311  2143 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-30 17:41:37.312   311  2143 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 17:41:37.312   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 17:41:37.312   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 17:41:37.312   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-30 17:41:37.312   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-30 17:41:37.312   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-30 17:41:37.312   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-30 17:41:37.312   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-30 17:41:37.312   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-30 17:41:37.312   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-30 17:41:37.312   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
08-30 17:41:37.312   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-30 17:41:37.313   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 17:41:37.313   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f380 on port 1
08-30 17:41:37.313   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-30 17:41:37.313   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
08-30 17:41:37.313   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-30 17:41:37.313   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-30 17:41:37.313   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-30 17:41:37.313   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
08-30 17:41:37.313   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 17:41:37.313   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-30 17:41:37.313   311  2143 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 17:41:37.313   311  2143 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 17:41:37.313   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-30 17:41:37.314   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-30 17:41:37.314   311  7025 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-30 17:41:37.314   311  2143 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 17:41:37.314   311  2143 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-30 17:41:37.314   311  2143 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-30 17:41:37.315  3883  3883 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-30 17:41:37.315   311  2143 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-30 17:41:37.316   311  2143 D AudioPlayer: AudioPlayer releasing audio source
08-30 17:41:37.316   311  2143 D AudioPlayer: AudioPlayer done releasing audio source
08-30 17:41:37.316   311  2143 V AwesomePlayer: reset_l() 
08-30 17:41:37.316   311  2143 V AwesomePlayer: cancelPlayerEvents
08-30 17:41:37.316   311  2143 V AwesomePlayer: ~AwesomePlayer call
08-30 17:41:37.316   311  2143 V AwesomePlayer: reset_l() 
08-30 17:41:37.316   311  2143 V AwesomePlayer: cancelPlayerEvents
08-30 17:41:37.317  6946  7022 V SoundPool: c,lose(32)
08-30 17:41:37.317  6946  7022 V SoundPool: pointer = 0x9fff5000, size = 205080, sampleRate = 48000, numChannels = 2
08-30 17:41:37.317  3883  3883 I art     : System.exit called, status: 0
08-30 17:41:37.317  3883  3883 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 17:41:37.320  1603  1603 D BluetoothAdapter: 330666496: getState() :  mService = null. Returning STATE_OFF
08-30 17:41:37.320  1603  1603 D BluetoothAdapter: 330666496: getState() :  mService = null. Returning STATE_OFF
08-30 17:41:37.323  6878  6878 D DockEventReceiver: finishStartingService: stopping service
08-30 17:41:37.335  6681  6681 I UEI.SmartControl: Service initServices...
08-30 17:41:37.335  6681  6681 D UEI.SmartControl: QS start get config
,08-30 17:41:37.339   311  1403 V AudioFlinger: 3883 died, releasing its sessions
,08-30 17:41:37.339   311  1403 V AudioFlinger:  pid 1851 @ 0
08-30 17:41:37.339   311  1403 V AudioFlinger:  pid 3443 @ 1
08-30 17:41:37.339   311  1403 V AudioFlinger:  pid 3443 @ 2
08-30 17:41:37.340  6878  6878 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-30 17:41:37.395  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 17:41:37.396  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-30 17:41:37.458  1034  2032 I ActivityManager: Process com.android.bluetooth (pid 3883) has died
08-30 17:41:37.459  1034  2032 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-30 17:41:37.471  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1189
08-30 17:41:37.472  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 17:41:37.491  6878  6878 D BluetoothPermissionRequest: onReceive
,08-30 17:41:37.497  6878  6878 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 17:41:37.497  6878  6878 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-30 17:41:37.501  6878  6878 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 17:41:37.561  1034  2397 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7031 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-30 17:41:37.645  7031  7031 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-30 17:41:37.646  7031  7031 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 17:41:37.646  7031  7031 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-30 17:41:37.647  7031  7031 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 17:41:37.667  7031  7031 D BluetoothAdapterApp: Loading JNI Library
,08-30 17:41:37.693  6681  6681 I UEI.SmartControl: Supports setup maps: true
,08-30 17:41:37.700  6681  6681 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 17:41:37.700  6681  6681 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 17:41:37.700  6681  6681 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 17:41:37.700  6681  6681 I UEI.SmartControl: ### init IR Blaster...
08-30 17:41:37.704  6681  6681 D serial_port: Configuring serial port
08-30 17:41:37.704  7031  7031 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@300ba49 Instance Count = 1
08-30 17:41:37.704  6681  6681 E UEI.SmartControl: UEIBLaster setting for 616
08-30 17:41:37.704  6681  6681 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 17:41:37.704  6681  6681 I UEI.SmartControl: configuring settings for MAXQ616
08-30 17:41:37.704  6681  6681 I UEI.SmartControl: Get version...
08-30 17:41:37.710  7031  7031 D BluetoothAdapterApp: onCreate
,08-30 17:41:37.724  6681  7051 D UEI.SmartControl: serial port data available: 21
,08-30 17:41:37.734  7031  7031 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-30 17:41:37.735  7031  7031 D ProfileConfigQcom: Adding HeadsetService
08-30 17:41:37.735  7031  7031 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-30 17:41:37.735  7031  7031 D ProfileConfigQcom: Adding A2dpService
08-30 17:41:37.735  7031  7031 D ProfileConfigQcom: [BTUI] HidService is supported
08-30 17:41:37.735  7031  7031 D ProfileConfigQcom: Adding HidService
08-30 17:41:37.736  7031  7031 D ProfileConfigQcom: [BTUI] HealthService is supported
08-30 17:41:37.736  7031  7031 D ProfileConfigQcom: Adding HealthService
08-30 17:41:37.736  7031  7031 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-30 17:41:37.737  7031  7031 D ProfileConfigQcom: [BTUI] PanService is supported
08-30 17:41:37.737  7031  7031 D ProfileConfigQcom: Adding PanService
08-30 17:41:37.737  7031  7031 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 17:41:37.738  7031  7031 D ProfileConfigQcom: Adding GattService
08-30 17:41:37.738  7031  7031 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
,08-30 17:41:37.738  7031  7031 D ProfileConfigQcom: Adding BluetoothMapService
08-30 17:41:37.738  7031  7031 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 17:41:37.740  7031  7031 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-30 17:41:37.745  6878  6878 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 17:41:37.747  7031  7031 V LGMDMManagerInternal: Create singleton instance
08-30 17:41:37.750  6681  6681 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-30 17:41:37.750  6681  6681 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 17:41:37.750  6681  6681 I UEI.SmartControl: QS saving settings...
08-30 17:41:37.752  6681  6681 D UEI.SmartControl: IR Blaster version: 25672567
08-30 17:41:37.768  6681  7051 D UEI.SmartControl: serial port data available: 4
,08-30 17:41:37.797  6681  7055 I UEI.SmartControl: Device manager: loading config....
08-30 17:41:37.797  6681  6681 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 17:41:37.797  6681  7055 D UEI.SmartControl: ----------- loading internal config...
,08-30 17:41:37.800  6681  6681 E UEI.SmartControl: Services init done
08-30 17:41:37.800  6681  6681 D UEI.SmartControl: QS Service init finished
08-30 17:41:37.801  6681  6681 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 17:41:37.801  6681  6681 D UEI.SmartControl: QS Service version code: 201091
08-30 17:41:37.808  6681  6681 D UEI.SmartControl: Service requested: Control
08-30 17:41:37.815  6681  7055 E UEI.SmartControl: Loading SETTINGS...
,08-30 17:41:37.819  6681  6681 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 17:41:37.823  6681  6681 D UEI.SmartControl: Internal service binding...
08-30 17:41:37.824  6946  6946 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-30 17:41:37.825  6681  7055 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 17:41:37.826  6681  6698 I UEI.SmartControl: ------ IControl API: 11
08-30 17:41:37.826  6681  6698 D UEI.SmartControl: File observer start...
08-30 17:41:37.827  6681  6698 E UEI.SmartControl: IR Port is disabled: false
08-30 17:41:37.827  7031  7031 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:37.828  6681  6698 D UEI.SmartControl: Starting file observer...
08-30 17:41:37.828  6681  6698 I UEI.SmartControl: Registering callback...
08-30 17:41:37.829  6681  6696 I UEI.SmartControl: ------ IControl API: 19
08-30 17:41:37.829  6681  6696 I UEI.SmartControl: Registering Services Ready callback...
08-30 17:41:37.832  7031  7031 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 17:41:37.833  7031  7031 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 17:41:37.833  7031  7031 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 17:41:37.837  7031  7031 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:37.837  7031  7031 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-30 17:41:37.841  6681  7054 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 17:41:37.842  6946  6962 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-30 17:41:37.843  6681  7054 D UEI.SmartControl: -----service ready thread exits
08-30 17:41:37.843  6946  7020 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-30 17:41:37.843  6946  7020 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-30 17:41:37.843  6946  6946 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-30 17:41:37.843  6946  6946 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-30 17:41:37.844  6681  6698 I UEI.SmartControl: ------ IControl API: 8
08-30 17:41:37.845  6946  6946 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-30 17:41:37.845  6946  6946 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-30 17:41:37.845  6965  6965 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-30 17:41:37.845  6946  6946 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-30 17:41:37.846  6946  6946 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-30 17:41:37.846  6946  6946 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-30 17:41:37.847  6946  6946 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-30 17:41:37.850  6946  6946 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-30 17:41:37.852  6946  6946 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 17:41:37.853  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 17:41:37.854  6946  6946 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 17:41:37.854  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 17:41:37.855  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 17:41:37.856  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-30 17:41:37.856  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-30 17:41:37.857  6946  6946 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472571697857]
08-30 17:41:37.858  6946  6946 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-30 17:41:37.859  1034  1868 I ActivityManager: Killing 6066:com.android.gallery3d/u0a27 (adj 15): empty #17
08-30 17:41:37.877  6946  7058 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-30 17:41:37.948  1034  1868 I ActivityManager: Killing 6555:com.lge.email/u0a23 (adj 15): empty #18
,08-30 17:41:38.006  1034  2015 W libprocessgroup: failed to open /acct/uid_10027/pid_6066/cgroup.procs: No such file or directory
,08-30 17:41:38.013  1034  1629 W libprocessgroup: failed to open /acct/uid_10023/pid_6555/cgroup.procs: No such file or directory
08-30 17:41:38.023  6946  6946 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-30 17:41:38.024  6946  6946 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 17:41:38.025  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-30 17:41:38.026  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-30 17:41:38.027  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-30 17:41:38.028  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-30 17:41:38.029  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-30 17:41:38.052  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-30 17:41:38.873  1034  1982 D WifiServiceImplEx: setWifiEnabled: true pid=6777, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 17:41:38.875  1034  1982 D WifiService: setWifiEnabled: true pid=6777, uid=10118
08-30 17:41:38.875  1034  1982 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 17:41:38.899  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 17:41:38.900  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 17:41:38.900  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-30 17:41:38.901  1034  1390 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-30 17:41:38.901  1034  1390 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-30 17:41:38.904  1034  1390 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-30 17:41:38.904  1034  1390 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 17:41:38.904  1034  1390 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-30 17:41:38.904  1034  1390 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 17:41:38.904  1034  1390 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 17:41:38.904  1034  1390 E WifiHW  : unknown target_country: EU , set to default
08-30 17:41:38.904  1034  1390 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-30 17:41:38.904  1034  1390 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 17:41:38.904  1034  1390 I WifiUtil: gEnableBmps=1
08-30 17:41:38.987  1034  1404 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:41:39.005  1034  1098 D Tethering: MasterInitialState.processMessage what=3
08-30 17:41:39.026  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:41:39.029  1034  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:39.031  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:39.032  1034  1404 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:39.034  1034  1098 D Tethering: MasterInitialState.processMessage what=3
08-30 17:41:39.047  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:41:39.051  6469  6469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 17:41:39.054  6469  6898 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 17:41:39.058  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:39.069  5766  5766 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 17:41:39.079  5766  5766 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 17:41:39.102  2208  2208 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:41:39.139  1034  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:41:39.174  1034  1590 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7066 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-30 17:41:39.178  1034  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:39.178  1034  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 17:41:39.265  7066  7066 I AppUp4:AppBoxCP: onCreate
,08-30 17:41:39.266  7066  7066 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-30 17:41:39.276  7066  7066 I AppUp4:DB:  setFingerPrint start
,08-30 17:41:39.277  7066  7066 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-30 17:41:39.286  7066  7066 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-30 17:41:39.286  7066  7066 I AppUp4:DB:  SDK version = 21
,08-30 17:41:39.286  7066  7066 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-30 17:41:39.290  7066  7066 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-30 17:41:39.291  7066  7066 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-30 17:41:39.292  7066  7066 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:39.294  7066  7066 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 17:41:39.295  7066  7066 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 17:41:39.303  7066  7066 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 17:41:39.345  7066  7066 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 17:41:39.345  7066  7066 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 17:41:39.354  7066  7066 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2edf1c8b
,08-30 17:41:39.354  7066  7066 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 17:41:39.354  7066  7066 D AppUp4:CustFacade: isPhone : true
08-30 17:41:39.355  7066  7066 D AppUp4:CustModeStarterReceiver: begin check event
08-30 17:41:39.355  7066  7066 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-30 17:41:39.356  7066  7066 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-30 17:41:39.357  7066  7099 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-30 17:41:39.357  7066  7099 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-30 17:41:39.357  7066  7099 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-30 17:41:39.362  1034  1590 I ActivityManager: Killing 6136:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-30 17:41:39.424  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:39.425  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 17:41:39.425  1034  1785 W libprocessgroup: failed to open /acct/uid_10080/pid_6136/cgroup.procs: No such file or directory
08-30 17:41:39.429  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 17:41:39.438  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 17:41:39.457  4312  7109 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 17:41:39.457  4312  7110 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:39.457  4312  7110 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 17:41:39.514  1034  2015 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7114 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 17:41:39.600  1034  1098 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 17:41:39.602  1034  1098 D Tethering: InitialState.processMessage what=4
,08-30 17:41:39.612   307   893 D SoftapController: Softap fwReload - Ok
,08-30 17:41:39.613  1034  1390 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (704ms)
08-30 17:41:39.616  1034  1098 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 17:41:39.619   307   893 D CommandListener: Setting iface cfg
08-30 17:41:39.619   307   893 D CommandListener: Trying to bring down wlan0
08-30 17:41:39.619   307   893 D CommandListener: Clearing all IP addresses on wlan0
08-30 17:41:39.623  1034  1390 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-30 17:41:39.621  7132  7132 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:41:39.621  7132  7132 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 17:41:39.638  1034  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 17:41:39.638  1034  1390 E WifiStateMachine: useWiFiOffloading() : false
08-30 17:41:39.638  1034  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 17:41:39.639  1034  1390 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 17:41:39.639  1034  1390 D WifiMonitor: connecting to supplicant
08-30 17:41:39.642  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-30 17:41:39.643  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:39.644  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:39.644  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:39.646  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-30 17:41:39.659  7132  7132 I wpa_supplicant: Successfully initialized wpa_supplicant
08-30 17:41:39.662  7114  7114 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:41:39.662  7114  7114 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 17:41:39.667  7114  7114 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-30 17:41:39.667  7114  7114 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 17:41:39.710  7132  7132 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 17:41:39.711  7132  7132 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-30 17:41:39.747  7114  7114 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-30 17:41:39.758  7114  7114 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-30 17:41:39.809  7114  7114 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 17:41:39.825  7132  7132 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 17:41:39.848  7114  7114 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 17:41:39.848  7114  7114 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 17:41:39.871  7132  7132 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-30 17:41:39.876  7132  7132 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 17:41:39.878  1034  1390 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-30 17:41:39.879  1034  1390 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 17:41:39.880  1034  1390 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-30 17:41:39.881  1034  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 17:41:39.881  1034  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,08-30 17:41:39.881  1034  7140 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 17:41:39.881  1034  1390 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-30 17:41:39.881  1034  7140 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-30 17:41:39.882  1034  1390 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:41:39.883  1034  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:41:39.884  1034  1390 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:41:39.885  1034  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:41:39.886  1034  1390 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 17:41:39.886  1034  1390 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-30 17:41:39.888  1034  1390 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 17:41:39.889  1034  1390 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-30 17:41:39.889  1034  1390 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-30 17:41:39.890  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:39.891  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:39.891  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:39.891  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:39.891  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 17:41:39.892  1034  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 17:41:39.892  1034  1390 E WifiStateMachine: useWiFiOffloading() : false
08-30 17:41:39.892  1034  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 17:41:39.894  1034  1390 D WifiNative-wlan0: doBoolean: SET update_config 1
08-30 17:41:39.896  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:39.897  1940  1940 D WfdService: Waiting for WifiP2p enabling
08-30 17:41:39.900  1034  1390 D WifiNative-wlan0: SET update_config 1: returned true
08-30 17:41:39.900  1034  1390 D WifiConfigStore: Loading config and enabling all networks 
08-30 17:41:39.900  1034  1390 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 17:41:39.900  1034  1390 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-30 17:41:39.903  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:41:39.903  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:41:39.903  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:39.903  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:39.903  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:41:39.903  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:41:39.903  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:41:39.903  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:41:39.903  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:41:39.903  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:41:39.903  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:41:39.906  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:41:39.906  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:41:39.906  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:39.906  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:39.906  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:41:39.906  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:41:39.906  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:41:39.906  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:41:39.906  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:41:39.906  1034  1390 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-30 17:41:39.906  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-30 17:41:39.906  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:41:39.906  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:41:39.907  1034  1395 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-30 17:41:39.927  1034  1390 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-30 17:41:39.928  1034  1390 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 17:41:39.931  1034  1390 D WifiStateMachine: enableVerboseLogging : level 2
08-30 17:41:39.931  1034  1390 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 17:41:39.931  1034  1390 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-30 17:41:39.931  1034  1390 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-30 17:41:39.932  1034  1390 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 17:41:39.932  1034  1390 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 17:41:39.932  1034  1390 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 17:41:39.932  1034  1390 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 17:41:39.932  1034  1390 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-30 17:41:39.932  1034  1390 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-30 17:41:39.932  1034  1390 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 17:41:39.932  1034  1390 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 17:41:39.933  1034  1390 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 17:41:39.933  1034  1390 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 17:41:39.933  1034  1390 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,08-30 17:41:39.934  1940  1940 D WfdsService: Supplicant Connection state is changed : true
08-30 17:41:39.934  1034  1390 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 17:41:39.934  1034  1390 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-30 17:41:39.934  1940  2287 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-30 17:41:39.934  1940  2287 D WfdsService: Set the WFDS Monitor: true
08-30 17:41:39.934  1940  2287 D WfdsMonitor: WfdsMonitorThread create
08-30 17:41:39.934  1940  2287 D WfdsMonitor: WFDS Monitor is created and started
08-30 17:41:39.934  1940  2287 D WfdsService: WiFi: Supplicant connection re-established
08-30 17:41:39.935  1034  1390 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 17:41:39.935  1034  1390 D WifiNative-HAL: Setting external_sim to 1
08-30 17:41:39.935  1034  1390 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-30 17:41:39.935  1034  1390 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 17:41:39.935  1034  1390 I WifiNative-HAL: startHal
08-30 17:41:39.935  1034  1390 D wifi    : setting scan oui 0xaf710040
08-30 17:41:39.936  1034  1390 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 17:41:39.936  1034  1390 I WifiNative-HAL: startHal
08-30 17:41:39.936  1034  1390 D wifi    : setting scan oui 0xaf710040
08-30 17:41:39.936  1034  1390 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 17:41:39.936  1940  7144 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
,08-30 17:41:39.936  1034  1390 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 17:41:39.936  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 17:41:39.936  1940  7144 E CtrlSupplicant: Succeed to open control connection
08-30 17:41:39.936  7132  7132 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 17:41:39.936  1034  1390 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 17:41:39.936  1940  7144 E CtrlSupplicant: Succeed to open monitor connection
08-30 17:41:39.937  1940  7144 D WfdsMonitor: Supplicant connection established
08-30 17:41:39.937  1940  2287 D WfdsService: Connected to the supplicant for wfds
08-30 17:41:39.937  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 17:41:39.937  7132  7132 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 17:41:39.937  1034  1390 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 17:41:39.937  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 17:41:39.938  7132  7132 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
,08-30 17:41:39.938  1034  1390 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 17:41:39.938  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 17:41:39.938  7132  7132 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 17:41:39.938  1034  1390 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 17:41:39.938  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 17:41:39.938  7132  7132 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 17:41:39.939  1034  1390 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 17:41:39.939  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 17:41:39.939  7132  7132 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 17:41:39.939  1034  1390 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 17:41:39.939  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 17:41:39.939  7132  7132 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 17:41:39.940  1034  1390 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 17:41:39.940  1034  1390 E WifiNative: : [181,140,045 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 17:41:39.940  1034  1390 D WifiNative-wlan0: doBoolean: RECONNECT
,08-30 17:41:39.941  1034  1390 D WifiNative-wlan0: RECONNECT: returned true
08-30 17:41:39.941  1034  1390 D WifiNative-wlan0: doString: [STATUS]
08-30 17:41:39.941  1034  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 17:41:39.941  1034  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 17:41:39.941  1034  1390 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 17:41:39.941  1034  1390 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 17:41:39.942  1034  1390 D WifiNative-wlan0: SET ps 1: returned true
08-30 17:41:39.942  1034  1389 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:39.943  1034  1390 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 17:41:39.943  1034  1390 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 17:41:39.943  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 17:41:39.943  1034  1390 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-30 17:41:39.944  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-30 17:41:39.944  1034  1390 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 17:41:39.944  1034  1557 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:39.944  1034  1557 I WifiNative-HAL: startHal
,08-30 17:41:39.944  1034  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf710040
08-30 17:41:39.944  1034  1557 D wifi    : failed to get capabilities : -3
08-30 17:41:39.944  1034  1390 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 17:41:39.944  1034  1557 E WifiScanningService: could not get scan capabilities
08-30 17:41:39.944  1034  1390 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 17:41:39.945  1034  1390 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 17:41:39.945  1034  1390 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-30 17:41:39.945  7132  7132 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-30 17:41:39.945  1034  1390 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-30 17:41:39.945  1034  1390 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-30 17:41:39.946  1034  1390 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 17:41:39.946  1034  1390 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-30 17:41:39.946  7132  7132 E wpa_supplicant: disconnect_rssi_lvl: -100
08-30 17:41:39.946  1034  1390 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 17:41:39.946  1034  1390 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
,08-30 17:41:39.946  1034  1558 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:39.947  1034  1390 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 17:41:39.947  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-30 17:41:39.948  7132  7132 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-30 17:41:39.949  7132  7132 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:41:39.949  1034  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 17:41:39.949  1034  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:41:39.949  1034  7140 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:41:39.949  1034  7140 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:41:39.949  7132  7132 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 17:41:39.949  7132  7132 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:41:39.949  1034  7140 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:41:39.950  1034  7140 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 17:41:39.950  7132  7132 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:41:39.950  1940  7144 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:41:39.950  1940  7144 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:41:39.950  1034  1390 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-30 17:41:39.950  1034  7140 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:41:39.950  1034  7140 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 17:41:39.951  1034  1390 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 17:41:39.951   307   893 D CommandListener: Setting iface cfg
08-30 17:41:39.952  1034  1390 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 17:41:39.952   307   893 D CommandListener: Trying to bring up p2p0
08-30 17:41:39.952  1034  1389 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 17:41:39.952  1034  1389 D LGWifiP2pService: P2pEnablingState
08-30 17:41:39.952  1034  1389 D LGWifiP2pService: P2pEnablingState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:39.952  1034  1389 D LGWifiP2pService: DefaultState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:39.952  1034  1390 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-30 17:41:39.952  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-30 17:41:39.953  7132  7132 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 17:41:39.953  7132  7132 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 17:41:39.952  1034  1389 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:39.953  1034  1390 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 17:41:39.953  1034  1390 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 17:41:39.954  1034  1390 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 17:41:39.954  1034  1390 D WifiNative-wlan0: doBoolean: SCAN
08-30 17:41:39.954  1034  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 17:41:39.954  1034  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 17:41:39.954  1034  7140 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 17:41:39.954  1034  7140 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 17:41:39.954  1034  1389 D LGWifiP2pService: P2p socket connection successful
08-30 17:41:39.955  1034  1389 D LGWifiP2pService: P2pEnabledState
08-30 17:41:39.957  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-30 17:41:39.957  1940  1940 D WfdsService: WifiP2pState is changed, : true
08-30 17:41:39.957  1940  2287 D WfdsService: Receive the WFDS_ENABLE Method
08-30 17:41:39.957  1940  2287 D WfdsService: Set the WFDS Monitor: true
08-30 17:41:39.957  1940  2287 D WfdsService: Connected to the supplicant for wfds
08-30 17:41:39.957  1940  2287 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 17:41:39.957  7132  7132 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 17:41:39.958  1940  2287 D WfdsService: selectPreferredScanChannel [36]
08-30 17:41:39.958  1940  2287 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 17:41:39.958  1034  1389 D LGWifiP2pService: sending p2p connection changed broadcast
08-30 17:41:39.958  1034  1390 D WifiNative-wlan0: SCAN: returned false
08-30 17:41:39.958  1034  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=181158  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 17:41:39.959  1034  1389 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
,08-30 17:41:39.961  1940  1940 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 17:41:39.961  1940  1940 D WfdsService: isConnected: false
08-30 17:41:39.962  1034  1389 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 17:41:39.962  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=181162  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 17:41:39.962  1034  1389 D WifiNative-p2p0: doBoolean: SET device_name G3
08-30 17:41:39.963  1034  1389 D WifiNative-p2p0: SET device_name G3: returned true
08-30 17:41:39.963  1034  1389 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 17:41:39.963  1034  1389 D LGWifiP2pService: before postfix = G3
08-30 17:41:39.963  1034  1390 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 17:41:39.963  1034  1389 D WifiServerServiceExt: postfix byte check : 2
08-30 17:41:39.963  1034  1389 D LGWifiP2pService: after postfix = G3
08-30 17:41:39.963  1034  1389 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 17:41:39.964  1034  1390 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 17:41:39.964  1034  1389 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 17:41:39.964  1034  1389 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 17:41:39.964  1034  1390 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 17:41:39.964  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:39.964  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:39.964  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 17:41:39.964  1034  1389 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 17:41:39.964  1034  1389 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-30 17:41:39.965  1034  1390 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 17:41:39.965  1034  1390 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 17:41:39.965  1034  1389 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 17:41:39.965  1034  1389 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 17:41:39.966  1034  1389 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 17:41:39.966  1034  1389 D WifiNative-HAL: p2pGetDeviceAddress
08-30 17:41:39.966  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:39.966  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:41:39.967  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:41:39.967  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-30 17:41:39.967  1034  1389 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-30 17:41:39.968  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:39.969  1034  1389 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-30 17:41:39.969  1034  1389 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-30 17:41:39.970  1034  1389 D WifiNative-p2p0: P2P_FLUSH: returned true
08-30 17:41:39.970  1034  1389 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 17:41:39.970  1034  1389 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
,08-30 17:41:39.970  1034  1389 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 17:41:39.971  1940  1940 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 17:41:39.971  1940  1940 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 17:41:39.971  1940  1940 D WfdsService: Update P2p Interface State: 3
08-30 17:41:39.971  1034  1389 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 17:41:39.971  1034  1389 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-30 17:41:39.977  7114  7114 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 17:41:39.979  1034  1389 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-30 17:41:39.979  1034  1389 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-30 17:41:39.980  1034  1389 D LGWifiP2pService: InactiveState
08-30 17:41:39.980  1034  1389 D LGWifiP2pService: InactiveState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:39.980  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:39.980  1034  1389 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-30 17:41:39.981  7132  7132 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 17:41:39.981  7132  7132 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-30 17:41:39.982  1034  7140 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 17:41:39.982  1034  7140 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:41:39.982  1034  7140 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:41:39.982  1034  7140 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:41:39.982  1940  7144 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 17:41:39.982  7132  7132 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 17:41:39.982  7132  7132 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:41:39.983  1034  1389 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 17:41:39.983  1034  1389 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:39.983  7132  7132 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:41:39.983  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:39.983  1034  1389 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:39.983  1034  1389 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:39.984  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:39.984  1034  7140 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:41:39.984  1034  7140 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:41:39.984  1034  1389 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:39.984  1034  7140 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:41:39.984  1034  7140 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:41:39.984  1940  7144 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:41:39.984  1034  7140 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:41:39.984  1034  7140 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:41:39.984  1940  7144 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:41:39.984  1034  7140 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:41:39.984  1034  7140 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:41:39.984  1034  1389 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:39.984  1940  2287 W WfdsService: DefaultState - msg [9441285] is not handled
08-30 17:41:39.984  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:39.984  1034  1389 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:39.984  1034  1389 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:39.984  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:39.985  1034  1389 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.St,ateMachine$SmHandler }
08-30 17:41:39.985  1034  1034 E WifiServerServiceExt: No p2p device connected
08-30 17:41:40.001  3443  3443 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 17:41:40.001  3443  3443 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:41:40.002  3443  3443 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 17:41:40.011  7114  7114 I HubEmail: JNI_OnLoad()
08-30 17:41:40.011  7114  7114 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 17:41:40.011  7114  7114 I HubEmail: registerNatives()
08-30 17:41:40.011  7114  7114 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 17:41:40.011  7114  7114 I HubEmail: registerNativeMethods()
08-30 17:41:40.011  7114  7114 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 17:41:40.011  7114  7114 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-30 17:41:40.042  1034  1886 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7150 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-30 17:41:40.047  6988  7147 W FormManager: Network not available. Please check & try again.
08-30 17:41:40.053  7114  7149 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:40.055  6988  7148 V FormManager: Network unavailable.
08-30 17:41:40.058  6988  7148 V FormManager: Network unavailable.
,08-30 17:41:40.064  1034  2397 I ActivityManager: Killing 6596:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-30 17:41:40.120  1034  1974 W libprocessgroup: failed to open /acct/uid_10061/pid_6596/cgroup.procs: No such file or directory
,08-30 17:41:40.177  7150  7150 D LgDataFeature: LgDataFeature() Constructor: none
08-30 17:41:40.177  7150  7150 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 17:41:40.180  7150  7150 D PhoneMonitor: Register our PhoneStateListener
,08-30 17:41:40.212  7150  7150 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-30 17:41:40.218  7150  7150 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 17:41:40.252  7150  7150 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-30 17:41:40.254  7150  7150 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-30 17:41:40.255  7150  7150 D TelephonyAutoProfiling: [parse] Load xml
08-30 17:41:40.259  7150  7150 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-30 17:41:40.259  7150  7150 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-30 17:41:40.259  7150  7150 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-30 17:41:40.259  7150  7150 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-30 17:41:40.259  7150  7150 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-30 17:41:40.259  7150  7150 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-30 17:41:40.259  7150  7150 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-30 17:41:40.259  7150  7150 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-30 17:41:40.259  7150  7150 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-30 17:41:40.259  7150  7150 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-30 17:41:40.259  7150  7150 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true,
08-30 17:41:40.259  7150  7150 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-30 17:41:40.259  7150  7150 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-30 17:41:40.260  7150  7150 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-30 17:41:40.260  7150  7150 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-30 17:41:40.260  7150  7150 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-30 17:41:40.260  7150  7150 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-30 17:41:40.271  7150  7150 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-30 17:41:40.301  1034  1974 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7169 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 17:41:40.302  1034  1974 I ActivityManager: Killing 6165:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-30 17:41:40.380  1034  1913 W libprocessgroup: failed to open /acct/uid_10097/pid_6165/cgroup.procs: No such file or directory
,08-30 17:41:40.595  7132  7132 E wpa_supplicant: USIM:  scard_init function
08-30 17:41:40.596  7132  7132 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-30 17:41:40.600  1034  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-30 17:41:40.600  1034  7140 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 17:41:40.600  1034  7140 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-30 17:41:40.600  1034  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: WPS-AP-AVAILABLE 
08-30 17:41:40.600  1034  7140 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-30 17:41:40.600  1034  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-30 17:41:40.600  1034  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-30 17:41:40.601  1034  1390 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 17:41:40.601  1034  1390 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 17:41:40.602  1034  1390 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 17:41:40.602  1034  1390 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 17:41:40.602  1034  1390 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-30 17:41:40.629  1034  1974 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7193 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-30 17:41:40.634  1034  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=181834  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 17:41:40.636  1034  1974 I ActivityManager: Killing 6639:com.lge.eula/1000 (adj 15): empty #17
08-30 17:41:40.690  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=181890  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-30 17:41:40.693  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:40.693  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:41:40.695  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:40.696  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:40.696  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:40.696  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 17:41:40.702  1034  2397 W libprocessgroup: failed to open /acct/uid_1000/pid_6639/cgroup.procs: No such file or directory
08-30 17:41:40.702  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:40.702  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:40.702  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 17:41:40.702  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:41:40.702  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-30 17:41:40.718  7132  7132 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 17:41:40.723  1034  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-30 17:41:40.723  1034  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-30 17:41:40.723  1034  7140 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-30 17:41:40.723  1034  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-30 17:41:40.724  1034  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 17:41:40.724  1034  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 17:41:40.726  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:40.726  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:41:40.727  1034  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=181927  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 17:41:40.728  7132  7132 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 17:41:40.728  7132  7132 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 17:41:40.728  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=181928  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 17:41:40.730  1034  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 17:41:40.730  1034  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 17:41:40.730  1034  7140 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 17:41:40.730  1034  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 17:41:40.730  1034  7140 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 17:41:40.730  1034  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 17:41:40.730  1034  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 17:41:40.730  1034  7140 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 17:41:40.730  1034  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 17:41:40.730  1034  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 17:41:40.732  1034  1098 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 17:41:40.734  1034  1390 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 33 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=181933
08-30 17:41:40.734  1034  1390 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 33 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=181934
08-30 17:41:40.736  1034  1390 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 33 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=181936
08-30 17:41:40.737  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 33 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=181936
08-30 17:41:40.737  1034  1390 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 33 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=181937
08-30 17:41:40.738  1034  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=181938  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 17:41:40.740  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:40.742  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:40.742  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:40.742  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 17:41:40.742  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=181942  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-30 17:41:40.743  1034  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=181943  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 17:41:40.744  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=181943  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 17:41:40.745  1034  1390 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=181945
08-30 17:41:40.746  1034  1390 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=181945
08-30 17:41:40.746  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:40.746  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:40.746  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 17:41:40.746  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:41:40.746  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-30 17:41:40.748  1034  1390 D WifiNative-wlan0: doString: [STATUS]
08-30 17:41:40.748  1034  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 17:41:40.748  1034  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 17:41:40.749  1034  1390 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 17:41:40.750  1034  1390 I WifiServiceExtension: setVHTCapabilityType  : false
08-30 17:41:40.750  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:40.750  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:41:40.751  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:40.752  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:40.752  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:41:40.754  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:40.758  1034  1390 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 17:41:40.758  1034  1390 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-30 17:41:40.762  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:40.762  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:40.762  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 17:41:40.766  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:40.766  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:40.766  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 17:41:40.767  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:40.767  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:41:40.769  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:40.771  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:40.771  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 17:41:40.773  1034  1390 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-30 17:41:40.773  1034  1390 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 17:41:40.773  1034  1390 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 17:41:40.773  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:40.774  1034  1390 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 17:41:40.774  1034  1390 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 17:41:40.776  1034  1404 D ConnectivityService: Got NetworkAgent Messenger
08-30 17:41:40.776  1034  1404 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 17:41:40.776  1034  1404 D ConnectivityService: NetworkAgent connected
08-30 17:41:40.779  1034  1390 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 17:41:40.779  1034  1390 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 17:41:40.779  1034  1390 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 17:41:40.779  1034  1390 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 17:41:40.779  1034  1390 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 17:41:40.783  1034  1390 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-30 17:41:40.786   307   893 D CommandListener: Setting iface cfg
08-30 17:41:40.792  1034  1390 E WifiStateMachine: Start Dhcp Watchdog 2
08-30 17:41:40.792  1034  7211 D DhcpStateMachine: StoppedState
08-30 17:41:40.793  1034  7211 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:40.793  1034  7211 D DhcpStateMachine: WaitBeforeStartState
08-30 17:41:40.793  1034  1390 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=181993  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 17:41:40.793  1034  1390 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=181993  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 17:41:40.794  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=181993  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 17:41:40.794  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:41:40.795  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:41:40.795  1034  1390 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:41:40.796  1034  1390 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:41:40.796  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:41:40.796  1034  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:41:40.797  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:41:40.797  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-30 17:41:40.799  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:41:40.799  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,08-30 17:41:40.800  1034  1390 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=181999  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-30 17:41:40.801  1034  1390 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=182000  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 17:41:40.802  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=182002  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 17:41:40.805  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:136456] from screen [on:0 period:-602081723] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 17:41:40.807  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-602081721] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 17:41:40.807  1034  1390 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 17:41:40.853  1034  1937 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7222 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 17:41:40.854  1034  1937 I ActivityManager: Killing 6656:com.lge.bnr/1000 (adj 15): empty #17
,08-30 17:41:40.932  1034  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:40.932  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:40.932  1034  1389 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 17:41:40.945  1034  1404 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-30 17:41:40.946  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:40.946  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:40.947  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:40.949  1034  1390 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:40.950  1034  1390 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:40.952  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:40.953  1034  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:40.954  1034  1404 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 17:41:40.955  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=94,0,0
08-30 17:41:40.957  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=94,0,0
08-30 17:41:40.957  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-30 17:41:40.959  7132  7132 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,08-30 17:41:40.960  1034  1390 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-30 17:41:40.960  1034  2397 W libprocessgroup: failed to open /acct/uid_1000/pid_6656/cgroup.procs: No such file or directory
08-30 17:41:40.960  1034  1390 D WifiNative-wlan0: doBoolean: SET ps 0
08-30 17:41:40.961  1034  1390 D WifiNative-wlan0: SET ps 0: returned true
08-30 17:41:40.962  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 17:41:40.962  7132  7132 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-30 17:41:40.963  1034  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-30 17:41:40.963  1034  1390 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 17:41:40.963  1034  1390 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 17:41:40.964  1034  1390 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 17:41:40.964  1034  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f45b512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:40.964  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f45b512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:40.964  1034  7211 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:40.965  1034  7211 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 17:41:40.965   307   893 D CommandListener: Setting iface cfg
08-30 17:41:40.966   307   893 D CommandListener: Trying to bring up wlan0
08-30 17:41:40.968  1034  1390 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-30 17:41:40.970  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:41:40.970  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-30 17:41:40.971  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:40.971  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:40.972  1034  1390 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:40.972  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:41:40.972  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 17:41:40.972  1034  1390 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:40.973  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:40.973  1034  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:40.974  1034  1404 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 17:41:40.975  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 17:41:40.975  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 17:41:40.975  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 17:41:40.976  7132  7132 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 17:41:40.976  1034  1389 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:40.976  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:40.978  1034  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 17:41:40.978  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 17:41:40.979  7132  7132 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-30 17:41:40.980  1034  1390 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 17:41:40.980  1034  1390 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 17:41:40.999  7222  7222 I art     : Almond Protected OAT
08-30 17:41:41.000  1034  1390 D WifiNative-wlan0: SET ps 1: returned true
08-30 17:41:41.000  1034  1404 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 17:41:41.001  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 17:41:41.002  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 17:41:41.002  1034  1390 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-30 17:41:41.002  1034  1390 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 17:41:41.003  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 17:41:41.003  1034  1390 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 17:41:41.004  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 17:41:41.004  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,08-30 17:41:41.004  1034  1390 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 17:41:41.005  1034  1404 D ConnectivityService: ignoring duplicate network state non-change
08-30 17:41:41.006  1034  1404 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 17:41:41.007  1034  1404 D ConnectivityService: Adding iface wlan0 to network 101
08-30 17:41:41.009  1034  1390 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 17:41:41.030  1034  1404 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 17:41:41.030  1034  1404 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-30 17:41:41.031  1034  1404 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-30 17:41:41.032   307   893 E Netd    : netlink response contains error (File exists)
08-30 17:41:41.032  1034  1404 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-30 17:41:41.032  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:41.032  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:41:41.033  1034  1404 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 17:41:41.033  1034  1404 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-30 17:41:41.033  1034  1404 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-30 17:41:41.033  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:41.036  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:41.036  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:41.036  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 17:41:41.041  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:41.041  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:41.041  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 17:41:41.042  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-30 17:41:41.046  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-30 17:41:41.048  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:41.048  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:41.048  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 17:41:41.050  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 17:41:41.054  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:41.054  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:41.054  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 17:41:41.054  1034  1404 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 17:41:41.054  1034  1404 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-30 17:41:41.054  1034  1404 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-30 17:41:41.054  1034  1404 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-30 17:41:41.054  1034  1404 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 17:41:41.054  1034  7210 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:41.054  1034  7210 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-30 17:41:41.054  1034  1404 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:41:41.054  1034  1404 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 17:41:41.054  1034  7210 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:41.055  1034  1404 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:41.055  1034  1404 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 17:41:41.055  1034  7210 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 17:41:41.055  1034  1404 D ConnectivityService: currentScore = 0, newScore = 20
08-30 17:41:41.055  1034  1404 D ConnectivityService:    accepting network in place of null
08-30 17:41:41.055  1034  1404 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 17:41:41.055  1851  1851 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:41.056  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-30 17:41:41.056  1034  1390 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:41.056  1034  1390 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 17:41:41.057  1034  1404 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 17:41:41.057  1034  1404 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 17:41:41.057   307  7244 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-30 17:41:41.057  1034  1404 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 17:41:41.058  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:41.058  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 17:41:41.069  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:41.069  1034  1404 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:41.069  1034  1404 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 17:41:41.070  1034  1404 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-30 17:41:41.071  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
,08-30 17:41:41.071  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 17:41:41.071  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 17:41:41.071  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 17:41:41.071  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:41.071  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 17:41:41.072  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:41.072  1034  1404 D ConnectivityService: validation of new default Network = false
08-30 17:41:41.072  1034  1404 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 17:41:41.072  1034  1404 D DSQN    : enableDataServiceNotify 
08-30 17:41:41.072  1034  1404 D DSQN    : start dsqn bin
08-30 17:41:41.075  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:41.075  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 17:41:41.075  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:41.079  1034  1404 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-30 17:41:41.079  1034  1404 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:41.079  1034  1404 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:41:41.079  1034  1404 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:41:41.079  1603  2073 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 17:41:41.071  7245  7245 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:41:41.071  7245  7245 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:41:41.083  7222  7222 D WeatherApplication: removeAccount
,08-30 17:41:41.090  7222  7222 D WeatherApplication: Account.length = 0
08-30 17:41:41.090  7222  7222 E WeatherApplication: OPERATOR:OPEN
08-30 17:41:41.093  7222  7222 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:41:41
08-30 17:41:41.096  1034  1388 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-30 17:41:41.096  7245  7245 E DSQN    : DSQN ssw
,08-30 17:41:41.100  7222  7222 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 17:41:41.100  7222  7222 D Weather.Utils: 2 : All the weather widget is gone.
08-30 17:41:41.101  1816  7247 I CheckinService: active receiver: enabled
08-30 17:41:41.104  7222  7222 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 17:41:41.105  7222  7222 D WeatherAncestor: connectivity changed - connection : true
08-30 17:41:41.106  7222  7222 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-30 17:41:41.110  1816  7247 I CheckinService: Preparing to send checkin request
08-30 17:41:41.110  1816  7247 I EventLogService: Accumulating logs since 1472571576898
08-30 17:41:41.112   307  7244 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-30 17:41:41.114  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 17:41:41.115  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:41.116  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:41.116  7222  7222 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 17:41:41.117  7222  7222 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 17:41:41.117  7222  7222 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-30 17:41:41.141  7222  7222 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-30 17:41:41.141  7222  7222 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:41:41
08-30 17:41:41.144   307  7244 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-30 17:41:41.168  1034  7211 D DhcpStateMachine: DHCPV4 request on wlan0
,08-30 17:41:41.169   307   892 D LGDataListener: argv[0]=dsqncommand
08-30 17:41:41.169   307   892 D LGDataListener: argv[1]=wlan0
08-30 17:41:41.169   307   892 D LGDataListener: argv[2]=1
08-30 17:41:41.169   307   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-30 17:41:41.169  1034  1095 D DSQN    : DSQM DsqnNotification wlan0  1
08-30 17:41:41.169  1034  1095 D DSQN    : start to monitor internet connection
08-30 17:41:41.169  1034  7211 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-30 17:41:41.169  1034  7211 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-30 17:41:41.171  1034  1785 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7252 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 17:41:41.172  1034  1785 I ActivityManager: Killing 2151:com.lge.music/u0a34 (adj 15): empty #17
08-30 17:41:41.161  7264  7264 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:41:41.161  7264  7264 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:41:41.181  7264  7264 I dhcpcd  : version 5.5.6 starting
,08-30 17:41:41.184  7264  7264 E dhcpcd  : get_duid: m
08-30 17:41:41.184  7264  7264 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 17:41:41.184  7264  7264 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-30 17:41:41.193  1034  7210 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 15:41:41 GMT], X-Android-Received-Millis=[1472571701192], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472571701168]}
08-30 17:41:41.193  1034  7210 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 17:41:41.193  1034  7210 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-30 17:41:41.193  1034  1404 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-30 17:41:41.193  1034  1404 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-30 17:41:41.193  1034  1404 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 17:41:41.194  1034  1404 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:41:41.194  1034  1404 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 17:41:41.194  1034  1404 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-30 17:41:41.194  1034  1404 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,08-30 17:41:41.194  1034  1404 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:41.194  1034  1404 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:41:41.195  1034  1404 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:41:41.195   311  2143 V AudioFlinger: 2151 died, releasing its sessions
08-30 17:41:41.195   311  2143 V AudioFlinger:  pid 1851 @ 0
08-30 17:41:41.195   311  2143 V AudioFlinger:  pid 3443 @ 1
08-30 17:41:41.195   311  2143 V AudioFlinger:  pid 3443 @ 2
08-30 17:41:41.196  1603  2073 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 17:41:41.199  1034  1404 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:41.199  1034  1390 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:41.199  1034  1404 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-30 17:41:41.199  1034  1390 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 17:41:41.201  1851  1851 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:41.201  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 17:41:41.219  1816  7247 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-30 17:41:41.220  1034  2397 W libprocessgroup: failed to open /acct/uid_10034/pid_2151/cgroup.procs: No such file or directory
,08-30 17:41:41.239  7264  7264 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 17:41:41.239  7264  7264 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-30 17:41:41.239  7264  7264 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 17:41:41.239  7264  7264 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 17:41:41.239  7264  7264 D dhcpcd  : wlan0: sending REQUEST (xid 0xe41063da), next in 4.09 seconds
,08-30 17:41:41.249  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 17:41:41.250  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:41.251  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:41.328  1034  1886 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7278 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-30 17:41:41.333  7264  7264 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-30 17:41:41.344   342   342 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 321us total 15.275ms
08-30 17:41:41.358  7264  7264 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-30 17:41:41.358  7264  7264 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,08-30 17:41:41.358  7264  7264 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-30 17:41:41.358  7264  7264 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-30 17:41:41.358  7264  7264 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 17:41:41.359  7264  7264 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 17:41:41.359  7264  7264 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 17:41:41.359  7264  7264 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-30 17:41:41.359   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 259us total 13.090ms
08-30 17:41:41.371   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 232us total 11.893ms
08-30 17:41:41.386   278   426 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 17:41:41.386   278   426 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 17:41:41.386   278   426 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:41:41.386  7252  7299 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-30 17:41:41.391   278   426 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 17:41:41.391   278   426 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 17:41:41.391   278   426 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 17:41:41.392  7252  7299 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 17:41:41.396   278   426 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 17:41:41.396   278   426 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 17:41:41.396   278   426 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 17:41:41.399  7252  7303 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-30 17:41:41.405   278   426 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 17:41:41.405   278   426 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 17:41:41.405   278   426 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 17:41:41.405  7252  7303 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 17:41:41.416  7278  7278 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 17:41:41.416  7278  7278 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 17:41:41.445  7278  7278 I MultiDex: VM with version 2.1.0 has multidex support
08-30 17:41:41.445  7278  7278 I MultiDex: install
08-30 17:41:41.445  7278  7278 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 17:41:41.454  7278  7278 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-30 17:41:41.570  7252  7252 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-30 17:41:41.572  1034  7211 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-30 17:41:41.573  1034  7211 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-30 17:41:41.573  1034  7211 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 17:41:41.574  1034  7211 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-30 17:41:41.574  1034  7211 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-30 17:41:41.574  1034  7211 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 17:41:41.574  1034  7211 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-30 17:41:41.574  1034  7211 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-30 17:41:41.574  1034  7211 D DhcpStateMachine: RunningState
08-30 17:41:41.577  7252  7252 I LibraryLoader: Loading: webviewchromium
08-30 17:41:41.579  7252  7252 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2788-2791)
08-30 17:41:41.579  7252  7252 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 17:41:41.583  7252  7252 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {246b7c62}
,08-30 17:41:41.584  7252  7252 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 17:41:41.585  7252  7252 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 17:41:41.592  7252  7252 I BrowserStartupController: Initializing chromium process, renderers=0
08-30 17:41:41.593  7252  7252 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 17:41:41.605  7252  7252 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-30 17:41:41.606  7252  7252 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,08-30 17:41:41.606  7252  7252 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-30 17:41:41.607   311  1403 V AudioPolicyService: registerClient() client 0xb558a260, uid 10093
08-30 17:41:41.608  7252  7343 W AudioManagerAndroid: Requires BLUETOOTH permission
08-30 17:41:41.618  7252  7252 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 17:41:41.618  7252  7252 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 17:41:41.618  7252  7252 I Adreno-EGL: Build Date: 12/12/14 금
08-30 17:41:41.618  7252  7252 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 17:41:41.618  7252  7252 I Adreno-EGL: Remote Branch: 
08-30 17:41:41.618  7252  7252 I Adreno-EGL: Local Patches: 
08-30 17:41:41.618  7252  7252 I Adreno-EGL: Reconstruct Branch: 
,08-30 17:41:41.678  7252  7252 I NSApplication: Starting up...
,08-30 17:41:41.722  1034  1913 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7356 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-30 17:41:41.723  1034  1913 I ActivityManager: Killing 6096:com.android.vending/u0a44 (adj 15): empty #17
,08-30 17:41:41.736  7278  7293 D LgDataFeature: LgDataFeature() Constructor: none
08-30 17:41:41.736  7278  7293 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 17:41:41.823  1034  1974 W libprocessgroup: failed to open /acct/uid_10044/pid_6096/cgroup.procs: No such file or directory
,08-30 17:41:41.882  7356  7356 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 17:41:41.903  1034  1049 D WifiServiceImplEx: setWifiEnabled: false pid=6777, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-30 17:41:41.904  1034  1049 D WifiService: setWifiEnabled: false pid=6777, uid=10118
08-30 17:41:41.904  1034  1049 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 17:41:41.919  1034  1390 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 17:41:41.919  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 17:41:41.919  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 17:41:41.919  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 17:41:41.919  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-30 17:41:41.920  1034  1390 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 17:41:41.920  1034  1390 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 17:41:41.921  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 17:41:41.921  1034  1390 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 17:41:41.921  1034  1390 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 17:41:41.921  1034  1390 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 17:41:41.922  1034  1390 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 17:41:41.922  1034  1390 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 17:41:41.929  1034  1390 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 17:41:41.929  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 17:41:41.929  7132  7132 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 17:41:41.930  1034  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:41.930  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:41.930  1034  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 17:41:41.930  1034  1390 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 17:41:41.930  1034  1390 D WifiNative-wlan0: SET ps 1: returned true
08-30 17:41:41.930  1034  7211 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:41.931   307   893 D CommandListener: Clearing all IP addresses on wlan0
,08-30 17:41:41.956  1034  1404 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 17:41:41.956  1034  1404 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-30 17:41:41.957  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:41.957  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:41:41.958  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-30 17:41:41.959  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:41.961  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-30 17:41:41.961  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:41.961  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:41.961  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 17:41:41.962  1034  1390 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:41.963  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:41.963  1034  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:41.963  1034  1390 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 17:41:41.963  1034  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:41.963  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:41.963  1034  1389 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2bb90821
08-30 17:41:41.963  1034  1389 D LGWifiP2pService: P2pDisablingState
08-30 17:41:41.963  1034  1389 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:41.963  1034  1389 D LGWifiP2pService: p2p socket connection lost
08-30 17:41:41.964  1034  1389 D LGWifiP2pService: P2pDisabledState
08-30 17:41:41.967  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 17:41:41.967  1940  1940 D WfdsService: WifiP2pState is changed : false
08-30 17:41:41.967  1940  2287 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 17:41:41.967  1940  2287 D WfdsService: Set the WFDS Monitor: false
08-30 17:41:41.967  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-30 17:41:41.968  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:41.968  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:41.968  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 17:41:41.968  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 17:41:41.968  1034  1034 D RttService: SCAN_AVAILABLE : 1
,08-30 17:41:41.968  1034  1558 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:41.968  1034  1557 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:41.969  1940  2287 D WfdsMonitor: WFDS Monitor is stopped
08-30 17:41:41.969  1940  2287 D WfdsService: STATE : WfdsDisabledState - enter
08-30 17:41:41.970  1034  1390 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 17:41:41.970  1940  2291 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 17:41:41.971  1034  1389 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:41.971  1034  1389 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:41.971  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 17:41:41.971  7132  7132 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 17:41:41.972  1034  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 17:41:41.972  1034  1390 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 17:41:41.972  1034  1390 D WifiNative-wlan0: SET ps 1: returned true
08-30 17:41:41.980  1940  7144 D CtrlSupplicant: Received on exit socket, terminate
08-30 17:41:41.980  1940  7144 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 17:41:41.980  1940  7144 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 17:41:41.980  1940  7144 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 17:41:41.980  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:41.980  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:41:41.980  1940  2287 W WfdsService: DefaultState - msg [9445378] is not handled
08-30 17:41:41.981  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 17:41:42.019  1034  1404 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 17:41:42.019   307   893 D CommandListener: Clearing all IP addresses on wlan0
08-30 17:41:42.019  1034  1404 D DSQN    : disableDataServiceNotify
08-30 17:41:42.019  1034  1404 D DSQN    : stop dsqn bin
,08-30 17:41:42.020  1034  1390 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 17:41:42.020  1034  1390 D WifiNative-p2p0: TERMINATE: returned true
08-30 17:41:42.020  1034  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 17:41:42.020  1034  1390 E WifiStateMachine: useWiFiOffloading() : false
08-30 17:41:42.020  1034  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 17:41:42.021  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-30 17:41:42.021  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:42.021  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:42.021  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 17:41:42.022  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 17:41:42.022  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:41:42.023  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-30 17:41:42.023  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:42.024  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:42.025  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 17:41:42.025  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:41:42.025  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 17:41:42.025  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:41:42.025  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:41:42.025  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:42.025  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:42.025  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:41:42.025  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:41:42.025  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:41:42.025  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:41:42.025  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:41:42.025  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:41:42.025  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:41:42.025  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:41:42.026  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:41:42.026  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:42.026  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:42.026  6777  6777 V io.jxcore.node.C,onnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:41:42.026  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:41:42.026  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:41:42.026  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:41:42.026  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:41:42.026  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:41:42.026  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:41:42.026  1034  1404 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-30 17:41:42.026  1034  1404 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:42.026  1034  1404 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:41:42.027  1034  1404 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:41:42.027  1034  1404 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-30 17:41:42.027  1034  7210 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:42.027  1034  7210 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:42.027  1034  7210 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 17:41:42.027  1603  2073 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 17:41:42.027  1034  1404 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-30 17:41:42.027  1034  1404 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-30 17:41:42.027  1034  1404 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 17:41:42.028  1034  1404 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:42.028  1034  1404 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 17:41:42.028  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 17:41:42.029  1034  1388 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 17:41:42.030  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 17:41:42.030  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 17:41:42.030  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 17:41:42.030  1034  1404 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:42.031  1034  1404 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:42.031  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 17:41:42.031  1034  1388 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 17:41:42.031  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 17:41:42.031  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 17:41:42.031  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 17:41:42.032  1034  1404 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:42.032  1851  1851 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:42.032  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 17:41:42.033  1034  1390 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:42.033  1034  1390 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 17:41:42.034  1034  1404 D NetworkManagementService: Removing idletimer
08-30 17:41:42.034  1034  1404 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:42.034  1034  1404 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-30 17:41:42.053  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 17:41:42.054  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:42.054  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:42.064  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 17:41:42.065  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:42.065  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 17:41:42.080  1034  1404 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-30 17:41:42.090  7380  7380 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-30 17:41:42.127  1034  2032 I art     : Explicit concurrent mark sweep GC freed 118956(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.950ms total 128.263ms
,08-30 17:41:42.141  7380  7380 I dex2oat : dex2oat took 51.373ms (threads: 4)
,08-30 17:41:42.150  1034  7211 D DhcpStateMachine: StoppedState
08-30 17:41:42.150  1034  7211 D DhcpStateMachine: StoppedState{ when=-178ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:42.151  1034  1390 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-30 17:41:42.151  1034  1390 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-30 17:41:42.158  7278  7293 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 17:41:42.158  7278  7293 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 17:41:42.158  7278  7293 I Adreno-EGL: Build Date: 12/12/14 금
08-30 17:41:42.158  7278  7293 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 17:41:42.158  7278  7293 I Adreno-EGL: Remote Branch: 
08-30 17:41:42.158  7278  7293 I Adreno-EGL: Local Patches: 
08-30 17:41:42.158  7278  7293 I Adreno-EGL: Reconstruct Branch: 
,08-30 17:41:42.169  7132  7132 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 17:41:42.169  7132  7132 I wpa_supplicant: monitor socket send errors count : 1
08-30 17:41:42.169  7132  7132 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1940-4\x00 that cannot receive messages
08-30 17:41:42.170  1034  7140 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 17:41:42.170  1034  7140 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-30 17:41:42.190  7132  7132 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 17:41:42.190  7132  7132 W wpa_supplicant: USIM:  scard_deinit function
,08-30 17:41:42.191  1034  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-30 17:41:42.191  1034  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 17:41:42.191  1034  7140 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 17:41:42.191  1034  7140 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
,08-30 17:41:42.191  1034  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 17:41:42.191  1034  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 17:41:42.191  1034  1098 D Tethering: InitialState.processMessage what=4
08-30 17:41:42.191  1034  1390 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=183391
08-30 17:41:42.192  1034  1390 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=183391
08-30 17:41:42.192  1034  1390 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=183392  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 17:41:42.192  1034  1390 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=183392  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 17:41:42.192  1034  1098 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 17:41:42.193  1034  1390 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:41:42.193  1034  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:41:42.252  6469  6469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 17:41:42.254  6469  6898 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-30 17:41:42.264  2208  2208 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:41:42.269  7066  7066 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 17:41:42.270  7066  7066 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:42.270  7066  7066 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 17:41:42.270  7066  7066 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 17:41:42.271  7066  7066 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 17:41:42.276  7066  7066 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2edf1c8b
08-30 17:41:42.276  7066  7066 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 17:41:42.276  7066  7066 D AppUp4:CustFacade: isPhone : true
08-30 17:41:42.276  7066  7066 D AppUp4:CustModeStarterReceiver: begin check event
08-30 17:41:42.276  7066  7066 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 17:41:42.278  7278  7293 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 17:41:42.278  7278  7293 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 17:41:42.278  7278  7293 I Adreno-EGL: Build Date: 12/12/14 금
08-30 17:41:42.278  7278  7293 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 17:41:42.278  7278  7293 I Adreno-EGL: Remote Branch: 
08-30 17:41:42.278  7278  7293 I Adreno-EGL: Local Patches: 
08-30 17:41:42.278  7278  7293 I Adreno-EGL: Reconstruct Branch: 
08-30 17:41:42.279  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:42.279  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 17:41:42.280  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 17:41:42.282  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 17:41:42.288  4312  7396 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 17:41:42.289  7114  7114 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 17:41:42.292  4312  7397 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:42.292  4312  7397 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 17:41:42.295  7132  7132 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 17:41:42.296  1034  7140 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-30 17:41:42.296  1034  7140 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-TERMINATING 
,08-30 17:41:42.296  1034  7140 D WifiMonitor: Disconnecting from the supplicant, no more events
08-30 17:41:42.296  1034  1390 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 42 0
08-30 17:41:42.308  3443  3443 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 17:41:42.308  3443  3443 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:42.308  3443  3443 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-30 17:41:42.309  7114  7400 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 17:41:42.319  7150  7150 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 17:41:42.319  7150  7150 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 17:41:42.322  6988  7403 W FormManager: Network not available. Please check & try again.
08-30 17:41:42.325  6988  7404 V FormManager: Network unavailable.
,08-30 17:41:42.333  7222  7222 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:41:42
08-30 17:41:42.334  6988  7404 V FormManager: Network unavailable.
08-30 17:41:42.335  7222  7222 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 17:41:42.335  7222  7222 D Weather.Utils: 2 : All the weather widget is gone.
08-30 17:41:42.335  7222  7222 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 17:41:42.335  7222  7222 D WeatherAncestor: connectivity changed - connection : true
08-30 17:41:42.335  7222  7222 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2a806981
08-30 17:41:42.336  7222  7222 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 17:41:42.336  7222  7222 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 17:41:42.336  7222  7222 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 17:41:42.336  7222  7222 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 17:41:42.336  7222  7222 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:41:42
08-30 17:41:42.342  7278  7293 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 17:41:42.342  7278  7293 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 17:41:42.342  7278  7293 I Adreno-EGL: Build Date: 12/12/14 금
08-30 17:41:42.342  7278  7293 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 17:41:42.342  7278  7293 I Adreno-EGL: Remote Branch: 
08-30 17:41:42.342  7278  7293 I Adreno-EGL: Local Patches: 
08-30 17:41:42.342  7278  7293 I Adreno-EGL: Reconstruct Branch: 
,08-30 17:41:42.358  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 17:41:42.359  6878  6878 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 17:41:42.359  6878  6878 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 17:41:42.359  6878  6878 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-30 17:41:42.361  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-30 17:41:42.361  6878  6878 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 17:41:42.361  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 17:41:42.362  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 17:41:42.362  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 17:41:42.362  6878  6878 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 17:41:42.362  6878  6878 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 17:41:42.367  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 17:41:42.370  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:41:42.375  6988  7407 W FormManager: Network not available. Please check & try again.
08-30 17:41:42.376  6988  7408 V FormManager: Network unavailable.
08-30 17:41:42.378  6988  7408 V FormManager: Network unavailable.
08-30 17:41:42.380  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:42.396  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 17:41:42.399  1034  1390 D WifiOffDelayIfNotUsed: stopMonitoring
08-30 17:41:42.399  1034  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 17:41:42.399  1034  1390 E WifiStateMachine: useWiFiOffloading() : false
08-30 17:41:42.399  1034  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 17:41:42.400  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 17:41:42.401  1940  1940 D WfdsService: Supplicant Connection state is changed : false
08-30 17:41:42.402  1940  2287 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 17:41:42.402  1940  2287 D WfdsService: Set the WFDS Monitor: false
08-30 17:41:42.402  1940  2287 D WfdsMonitor: WFDS Monitor is stopped
08-30 17:41:42.402  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 17:41:42.402  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:42.403  2513  2513 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:42.404  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 17:41:42.405  1034  1395 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 17:41:42.405  1034  1395 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 17:41:42.405  6988  7410 W FormManager: Network not available. Please check & try again.
08-30 17:41:42.405  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:41:42.405  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:41:42.405  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:42.405  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:42.405  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:41:42.405  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:41:42.405  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:41:42.405  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:41:42.405  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:41:42.406  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:41:42.406  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:41:42.406  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:42.406  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:42.406  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:41:42.406  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:41:42.406  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:41:42.406  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:41:42.406  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:41:42.410  6988  7411 V FormManager: Network unavailable.
08-30 17:41:42.411  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:42.413  6988  7411 V FormManager: Network unavailable.
,08-30 17:41:42.424  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 17:41:42.424  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 17:41:42.425  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 17:41:42.427  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 17:41:42.431  4312  7412 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 17:41:42.433  4312  7413 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 17:41:42.433  4312  7413 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 17:41:42.454  1034  2032 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7414 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 17:41:42.471  1034  1378 D PowerManagerServiceEx: acquireWakeLockInternal: lock=857639836, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,08-30 17:41:42.501   307  7432 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-30 17:41:42.501  1034  1095 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 17:41:42.502  2594  2594 D [Concierge]Service: onStartCommand(). Type : 9
08-30 17:41:42.505  1816  7247 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-30 17:41:42.513  1816  7247 I CheckinService: active receiver: disabled
,08-30 17:41:42.553  7414  7414 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 17:41:42.553  7414  7414 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-30 17:41:42.560  7414  7414 V [BNRBootReceiver]: Boot Receiver Return
08-30 17:41:42.560  7414  7414 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 17:41:42.567  6469  6469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 17:41:42.587  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:41:42.600  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 17:41:42.624  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 17:41:42.625  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 17:41:42.632  6946  6946 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 17:41:42.643  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-30 17:41:42.655  6878  6878 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-30 17:41:42.664  6469  6469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:41:42.675  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:41:42.687  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:42.697  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 17:41:42.698  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:41:42.704  6946  6946 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 17:41:42.711  6469  6469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 17:41:42.721  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:41:42.730  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:42.741  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:41:42.741  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:41:42.742  6946  6946 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 17:41:42.750  6469  6469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:41:42.764  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:41:42.771  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 17:41:42.779  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:41:42.780  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:41:42.781  6946  6946 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 17:41:42.785  6469  6469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:41:42.794  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:41:42.797  6681  7056 D UEI.SmartControl: Internal timer expired: 2
08-30 17:41:42.797  6681  7056 D UEI.SmartControl: unbind internal service
08-30 17:41:42.801  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:42.809  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 17:41:42.810  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:41:42.811  6946  6946 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 17:41:42.816  6469  6469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:41:42.825  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:41:42.832  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:42.843  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:41:42.843  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:41:42.844  6946  6946 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 17:41:42.850  6469  6469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 17:41:42.863  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:41:42.872  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:42.877  6681  7053 D serial_port: close(fd = 24)
,08-30 17:41:42.881  6681  7053 I UEI.SmartControl: Serial port is closed.
08-30 17:41:42.883  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:41:42.883  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:41:42.884  6946  6946 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 17:41:42.895  6469  6469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 17:41:42.916  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:41:42.925  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:42.938  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:41:42.939  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:41:42.947  6946  6946 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 17:41:42.958  6469  6469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:41:42.969  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:41:42.978  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:42.987  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 17:41:42.988  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:41:42.989  6946  6946 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 17:41:42.994  6469  6469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:41:43.000  6900  6900 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-30 17:41:43.009  1034  1397 D WifiService: New client listening to asynchronous messages
08-30 17:41:43.009  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 17:41:43.015  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 17:41:43.021  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:43.031  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:41:43.031  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:41:43.033  6946  6946 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-30 17:41:43.034  6946  6946 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-30 17:41:43.035  6946  6946 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 17:41:43.042  6469  6469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:41:43.047  6900  6900 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 17:41:43.050  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 17:41:43.054  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 17:41:43.064  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 17:41:43.075  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:41:43.076  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 17:41:43.077  6946  6946 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-30 17:41:43.078  6946  6946 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 17:41:43.079  6946  6946 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-30 17:41:43.082  1034  1785 I ActivityManager: Killing 6922:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-30 17:41:43.143  1034  1951 W libprocessgroup: failed to open /acct/uid_10037/pid_6922/cgroup.procs: No such file or directory
,08-30 17:41:43.152  2208  2208 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-30 17:41:43.166  2208  2208 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-30 17:41:43.168  2208  2208 D c       : Getting all permits...
08-30 17:41:43.168  2208  2208 D a       : Opening database...
08-30 17:41:43.173  2208  2208 D a       : Opening database auth.proximity.permit_store...
08-30 17:41:43.174  2208  2208 D a       : Closing database...
08-30 17:41:43.190  6469  6469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 17:41:43.195  6900  6900 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 17:41:43.196  6900  6900 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 17:41:43.196  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 17:41:43.201  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:41:43.211  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:43.225  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 17:41:43.227  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:41:43.231  6946  6946 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 17:41:43.239  6469  6469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 17:41:43.247  6900  6900 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-30 17:41:43.247  6900  6900 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 17:41:43.248  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 17:41:43.256  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:41:43.271  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 17:41:43.284  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:41:43.285  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 17:41:43.291  6946  6946 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 17:41:43.297  6469  6469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 17:41:43.302  6900  6900 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 17:41:43.302  6900  6900 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 17:41:43.302  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 17:41:43.306  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:41:43.319  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:43.326  6946  6946 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 17:41:43.327  6946  6946 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:41:43.329  6946  6946 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 17:41:43.339  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 17:41:43.346  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:41:43.351  6988  7441 W FormManager: Network not available. Please check & try again.
08-30 17:41:43.354  6988  7442 V FormManager: Network unavailable.
08-30 17:41:43.354  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:43.360  6988  7442 V FormManager: Network unavailable.
08-30 17:41:43.373  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 17:41:43.374  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 17:41:43.377  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 17:41:43.383  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 17:41:43.390  4312  7443 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 17:41:43.392  4312  7444 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 17:41:43.392  4312  7444 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 17:41:43.401  6900  6900 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-30 17:41:43.401  6900  6900 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 17:41:43.401  6900  6900 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 17:41:43.408  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:41:43.420  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:43.421  6988  7446 W FormManager: Network not available. Please check & try again.
08-30 17:41:43.442  6946  6946 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-30 17:41:43.442  6946  6946 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1189
08-30 17:41:43.443  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=857639836 [*alarm*], flags=0x0
,08-30 17:41:43.449  6988  7447 V FormManager: Network unavailable.
,08-30 17:41:43.452  2208  2208 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-30 17:41:43.454  6988  7447 V FormManager: Network unavailable.
08-30 17:41:43.947  1034  1390 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-602078582] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 17:41:43.959  1034  1390 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-602078569] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 17:41:44.071  1034  1404 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:41:44.088  1034  1098 D Tethering: MasterInitialState.processMessage what=3
08-30 17:41:44.102  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:41:44.107  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:44.113  1034  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:44.115  6469  6469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 17:41:44.119  6469  6898 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-30 17:41:44.142  5766  5766 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 17:41:44.163  2208  2208 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:41:44.183  7066  7066 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 17:41:44.183  7066  7066 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:44.183  7066  7066 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 17:41:44.183  7066  7066 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 17:41:44.189  7066  7066 I AppUp4:CustModeStarterReceiver: onReceive
08-30 17:41:44.193  7066  7066 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2edf1c8b
08-30 17:41:44.193  7066  7066 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 17:41:44.193  7066  7066 D AppUp4:CustFacade: isPhone : true
08-30 17:41:44.193  7066  7066 D AppUp4:CustModeStarterReceiver: begin check event
08-30 17:41:44.193  7066  7066 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 17:41:44.198  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:44.198  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 17:41:44.200  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 17:41:44.206  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 17:41:44.214  7114  7114 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 17:41:44.251  7114  7464 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 17:41:44.255  4312  7465 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 17:41:44.273  4312  7468 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:44.273  4312  7468 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 17:41:44.280  1034  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:44.283  6988  7466 W FormManager: Network not available. Please check & try again.
08-30 17:41:44.285  6988  7467 V FormManager: Network unavailable.
08-30 17:41:44.290  3443  3443 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 17:41:44.290  3443  3443 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:44.291  3443  3443 I LgeMiscReceiver: networkInfo.isConnected() = true
08-30 17:41:44.291  3443  3443 D PhoneState: setPdpRejectCasuse : false
08-30 17:41:44.294  7150  7150 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 17:41:44.294  7150  7150 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 17:41:44.295  6988  7467 V FormManager: Network unavailable.
08-30 17:41:44.305  7222  7222 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:41:44
08-30 17:41:44.311  7222  7222 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 17:41:44.311  7222  7222 D Weather.Utils: 2 : All the weather widget is gone.
,08-30 17:41:44.312  7222  7222 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-30 17:41:44.312  7222  7222 D WeatherAncestor: connectivity changed - connection : true
,08-30 17:41:44.312  7222  7222 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2a806981
08-30 17:41:44.313  7222  7222 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 17:41:44.313  7222  7222 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,08-30 17:41:44.313  7222  7222 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 17:41:44.313  7222  7222 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 17:41:44.313  7222  7222 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:41:44
08-30 17:41:44.921  1034  1785 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:44.921  1034  1785 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-30 17:41:44.955  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 17:41:44.955  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 17:41:44.956  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-30 17:41:44.956  1034  1098 D BluetoothManagerService: Message: 1
08-30 17:41:44.956  1034  1098 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-30 17:41:44.984  1034  1098 D BluetoothManagerService: Message: 20
08-30 17:41:44.984  1034  1098 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34bc8ca3:true
,08-30 17:41:44.989  7031  7031 D BluetoothAdapterState: make
08-30 17:41:44.993  7031  7031 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 17:41:44.994  7031  7031 I bluedroid-qcom: init
08-30 17:41:44.995  7031  7497 I BluetoothAdapterState: Entering OffState
08-30 17:41:44.995  7031  7031 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 17:41:44.995  7031  7031 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 17:41:44.996  7031  7031 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 17:41:44.996  7031  7031 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 17:41:44.996  7031  7031 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 17:41:44.997  7031  7031 I bluedroid-qcom: get_profile_interface socket
08-30 17:41:44.998  7031  7031 I bluedroid-qcom: get_profile_interface map_client
,08-30 17:41:45.003  7031  7501 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 17:41:44.991  7500  7500 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:41:45.001  7500  7500 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:41:45.016  7500  7500 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 17:41:45.016  7500  7500 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 17:41:45.016  7500  7500 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-30 17:41:45.022  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-30 17:41:45.023  1034  1098 D BluetoothManagerService: Message: 40
08-30 17:41:45.023  1034  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 17:41:45.024  7031  7047 I bluedroid-qcom: config_hci_snoop_log
08-30 17:41:45.025  1034  1098 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 17:41:45.025  1034  1098 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 17:41:45.028  7500  7500 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-30 17:41:45.029  1034  1404 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:41:45.034  1034  1404 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:45.036  1034  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:45.037  7500  7500 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 17:41:45.037  7500  7500 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-30 17:41:45.048  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:41:45.052  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:45.064  1034  1098 D Tethering: MasterInitialState.processMessage what=3
08-30 17:41:45.064  1034  1098 D Tethering: MasterInitialState.processMessage what=3
,08-30 17:41:45.067  7031  7497 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-30 17:41:45.068  7031  7501 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 17:41:45.074  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:45.075  7031  7501 D BluetoothAdapterProperties: Name is: G3
08-30 17:41:45.075  7031  7497 D BluetoothAdapterProperties: Setting state to 11
,08-30 17:41:45.075  7031  7497 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 17:41:45.076  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 17:41:45.077  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 17:41:45.084  1034  1098 D BluetoothManagerService: Message: 60
08-30 17:41:45.084  1034  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 17:41:45.085  1034  1098 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-30 17:41:45.086  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:45.093  7031  7497 I LGBluetoothServiceJni: classInitNative: succeeds
08-30 17:41:45.094  6469  6469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 17:41:45.094  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:45.095  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 17:41:45.098  6469  6898 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-30 17:41:45.103  6878  6878 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-30 17:41:45.105  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:45.106  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:45.110  5766  5766 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 17:41:45.111  7031  7497 D BluetoothBondStateMachine: make
,08-30 17:41:45.114  7031  7497 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:45.114  7031  7497 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 17:41:45.114  7031  7497 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:45.114  7031  7497 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-30 17:41:45.114  7031  7518 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 17:41:45.115  7031  7497 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-30 17:41:45.118  7031  7031 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 17:41:45.119  7031  7031 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:45.119  7031  7031 V BluetoothPbapReceiver: ***********state = 11
08-30 17:41:45.124  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 17:41:45.126  7031  7497 E BluetoothAdapterService: File transfer profiles supported!!
08-30 17:41:45.173  1034  2397 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7520 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-30 17:41:45.178  5766  5766 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 17:41:45.179  7031  7497 E BluetoothAdapterService: File transfer profiles supported!!
08-30 17:41:45.179  7031  7031 D HeadsetService: Received start request. Starting profile...
08-30 17:41:45.179  7031  7031 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 17:41:45.180  7031  7031 D LGBluetoothHfpAdapter: Version 1.6
08-30 17:41:45.180  1034  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:45.181  1034  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:45.181  1034  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:45.182  7031  7031 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 17:41:45.182  7031  7031 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 17:41:45.183  7031  7031 D HeadsetStateMachine: make
08-30 17:41:45.186  7031  7497 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 17:41:45.191  7031  7497 E BluetoothAdapterService: File transfer profiles supported!!
08-30 17:41:45.198  7031  7497 E BluetoothAdapterService: File transfer profiles supported!!
08-30 17:41:45.199  2208  2208 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:45.203  7031  7497 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 17:41:45.208  7031  7497 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 17:41:45.208  7031  7031 D LgDataFeature: LgDataFeature() Constructor: none
08-30 17:41:45.209  7031  7031 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 17:41:45.213  7066  7066 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 17:41:45.213  7066  7066 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:45.213  7066  7066 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 17:41:45.213  7066  7066 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 17:41:45.216  7031  7031 D HeadsetStateMachine: max_hf_connections = 1
08-30 17:41:45.216  7031  7031 I bluedroid-qcom: get_profile_interface handsfree
08-30 17:41:45.217  7066  7066 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 17:41:45.219  7031  7031 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-30 17:41:45.219   311  1402 V AudioPolicyService: registerClient() client 0xb558a800, uid 1002
08-30 17:41:45.219   311  2143 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 17:41:45.219   311  2143 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 17:41:45.219   311  2143 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 17:41:45.220  7031  7031 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 17:41:45.220   311  1403 V AudioFlinger: registerClient() client 0xb55815e0, pid 7031
08-30 17:41:45.220   311  1396 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 17:41:45.220   311  1396 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 17:41:45.221  7031  7031 V ToneGenerator: Create Track: 0xb4928080
08-30 17:41:45.221  7031  7031 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 17:41:45.221  7031  7031 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 17:41:45.221   311   311 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 17:41:45.221   311   311 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 17:41:45.221   311   311 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 17:41:45.221   311   311 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 17:41:45.221  1034  1590 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 17:41:45.221  7031  7031 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 17:41:45.221  1034  1590 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 17:41:45.221  7031  7502 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 17:41:45.221  7031  7502 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 17:41:45.221  3443  3459 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 17:41:45.221  3443  3459 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 17:41:45.222   311  2143 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 17:41:45.222  1851  2455 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 17:41:45.222  1851  2455 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 17:41:45.222   311  2142 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 17:41:45.223   311  2142 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-30 17:41:45.223   311  2142 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 17:41:45.223   311  2142 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 17:41:45.223  7031  7031 V AudioSystem: getLatency() output 2, latency 50
08-30 17:41:45.223  7031  7031 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 17:41:45.223  7031  7031 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 17:41:45.223  7066  7066 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2edf1c8b
08-30 17:41:45.223  7066  7066 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 17:41:45.223  7066  7066 D AppUp4:CustFacade: isPhone : true
08-30 17:41:45.223   311   311 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 17:41:45.223   311   311 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 17:41:45.223   311   311 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 17:41:45.223   311   311 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curL,vl = 31 
08-30 17:41:45.223   311   311 V AudioFlinger: createTrack() lSessionId: 20
08-30 17:41:45.224  7066  7066 D AppUp4:CustModeStarterReceiver: begin check event
08-30 17:41:45.224  7066  7066 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 17:41:45.224  7031  7497 V LGMDMManager: Create singleton instance
08-30 17:41:45.225  1603  1623 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 17:41:45.225  1603  1623 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 17:41:45.225   311  1398 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 17:41:45.225   311  1398 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 17:41:45.225  1603  1621 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 17:41:45.225  1603  1621 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 17:41:45.225  7031  7502 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 17:41:45.225  7031  7502 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 17:41:45.225  1034  2015 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 17:41:45.225  1034  2015 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 17:41:45.225  1851  1866 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 17:41:45.226  1851  1866 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 17:41:45.226  3443  3458 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 17:41:45.226  3443  3458 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 17:41:45.226  7031  7031 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 17:41:45.226  7031  7497 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 17:41:45.227   311   311 V AudioFlinger: acquiring 20 from 7031, for 7031
08-30 17:41:45.227   311   311 V AudioFlinger:  added new entry for 20
08-30 17:41:45.227  7031  7031 V ToneGenerator: ToneGenerator INIT OK, time: 186439
08-30 17:41:45.227  7031  7031 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:45.228  7031  7531 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 17:41:45.228  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:45.228  7031  7531 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 17:41:45.228  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 17:41:45.228  7031  7531 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 17:41:45.228  7031  7531 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 17:41:45.228   311   311 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7031
08-30 17:41:45.228   311   311 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 17:41:45.228   311   311 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 17:41:45.228   311   311 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 17:41:45.229   311   311 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 17:41:45.229   311   311 V voice   : voice_set_parameters: exit with code(0)
08-30 17:41:45.229   311   311 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 17:41:45.229   311   311 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 17:41:45.229   311   311 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 17:41:45.229   311   311 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 17:41:45.229   311   311 V audio_hw_primary: adev_set,_parameters: exit with code(0)
08-30 17:41:45.229   311   311 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 17:41:45.229  7031  7531 V ToneGenerator: ToneGenerator destructor
08-30 17:41:45.229  7031  7531 V ToneGenerator: stopTone
08-30 17:41:45.229  7031  7531 V ToneGenerator: Delete Track: 0xb4928080
08-30 17:41:45.229  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 17:41:45.229  7031  7531 V AudioTrack: ~AudioTrack, releasing session id from 7031 on behalf of 7031
08-30 17:41:45.230   311  1403 V AudioFlinger: releasing 20 from 7031 for 7031
08-30 17:41:45.230   311  1403 V AudioFlinger:  decremented refcount to 0
08-30 17:41:45.230   311  1403 V AudioFlinger: purging stale effects
08-30 17:41:45.230   311  1403 V AudioPolicyService: AudioCommandThread() adding release output 2
08-30 17:41:45.230   311  1403 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 17:41:45.230   311  1258 V AudioPolicyService: AudioCommandThread() waking up
08-30 17:41:45.230   311  1258 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 17:41:45.230   311  1258 V AudioPolicyManager: releaseOutput() 2
08-30 17:41:45.230   311  1258 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 17:41:45.230   311  1403 V AudioFlinger: PlaybackThread::Track destructor
08-30 17:41:45.230   311  1403 V AudioFlinger: removeClient_l() pid 7031, calling pid 311
08-30 17:41:45.231  1034  2006 W Process : Unable to open /proc/7540/status
08-30 17:41:45.232  7031  7031 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:45.235  7031  7031 D A2dpService: Received start request. Starting profile...
08-30 17:41:45.236  7031  7031 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 17:41:45.236  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 17:41:45.237  7031  7031 V Avrcp   : make
08-30 17:41:45.237  7031  7031 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 17:41:45.237  7031  7031 I bluedroid-qcom: get_profile_interface avrcp
08-30 17:41:45.242  7114  7114 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 17:41:45.249  7031  7031 V AudioManager: registerRemoteController: size of Media player list: 0
08-30 17:41:45.252  7031  7031 E AudioManager: No RCC entry present to update
08-30 17:41:45.252  7031  7031 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 17:41:45.252  4312  7541 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 17:41:45.255  7031  7031 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-30 17:41:45.255  4312  7543 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:45.255  4312  7543 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 17:41:45.256  7031  7031 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 17:41:45.256  7031  7031 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-30 17:41:45.262  7031  7031 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-30 17:41:45.265  3443  3443 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 17:41:45.265  3443  3443 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:45.266  3443  3443 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 17:41:45.303  7150  7150 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-30 17:41:45.304  7150  7150 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 17:41:45.311  6988  7549 V FormManager: Network unavailable.
08-30 17:41:45.311  7114  7547 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:45.312  6988  7548 W FormManager: Network not available. Please check & try again.
08-30 17:41:45.318  7222  7222 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:41:45
,08-30 17:41:45.320  6988  7549 V FormManager: Network unavailable.
08-30 17:41:45.321  7222  7222 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 17:41:45.321  7222  7222 D Weather.Utils: 2 : All the weather widget is gone.
08-30 17:41:45.321  7222  7222 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 17:41:45.322  7222  7222 D WeatherAncestor: connectivity changed - connection : true
08-30 17:41:45.322  7222  7222 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2a806981
08-30 17:41:45.322  7222  7222 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 17:41:45.322  7222  7222 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 17:41:45.322  7222  7222 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 17:41:45.322  7222  7222 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 17:41:45.322  7222  7222 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:41:45
08-30 17:41:45.340  6469  6469 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-30 17:41:45.341  6469  6898 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 17:41:45.346  7520  7520 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-30 17:41:45.346  7520  7520 W LG Account v2.2: No ProfileInfo entries
08-30 17:41:45.346  7520  7520 I LG Account v2.2: isEnabled: false
08-30 17:41:45.346  7520  7520 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 17:41:45.346  7520  7520 I Feature : [Lifetracker]Country: EU
08-30 17:41:45.346  7520  7520 I Feature : [Lifetracker]Operator: OPEN
08-30 17:41:45.346  7520  7520 I Feature : [Lifetracker]Ranking support: false
08-30 17:41:45.347  7520  7520 I Feature : [Lifetracker]Comfort support: false
08-30 17:41:45.347  7520  7520 I Feature : [Lifetracker]Accessory: true
08-30 17:41:45.347  7520  7520 I Feature : [Lifetracker]Health device: true
08-30 17:41:45.347  7520  7520 I Feature : [Lifetracker]Extra Pedometer: false
08-30 17:41:45.347  7520  7520 I Feature : [Lifetracker]Blood glucose device: false
08-30 17:41:45.347  7520  7520 I Feature : [Lifetracker]Device Number: 3
08-30 17:41:45.348  1034  1785 V SIM_STK : Menu title from STK is T-Mobile
08-30 17:41:45.348  1034  1785 V SIM_STK : Menu title from STK is T-Mobile
08-30 17:41:45.357  2208  2208 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:41:45.358  6878  6878 D BluetoothPermissionRequest: onReceive
08-30 17:41:45.361  6878  6878 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 17:41:45.365  7066  7066 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 17:41:45.365  7066  7066 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:45.365  7066  7066 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 17:41:45.365  7066  7066 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 17:41:45.366  7066  7066 I AppUp4:CustModeStarterReceiver: onReceive
08-30 17:41:45.368  7066  7066 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2edf1c8b
08-30 17:41:45.368  7066  7066 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 17:41:45.368  7066  7066 D AppUp4:CustFacade: isPhone : true
08-30 17:41:45.368  7066  7066 D AppUp4:CustModeStarterReceiver: begin check event
08-30 17:41:45.368  7066  7066 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 17:41:45.370  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:45.370  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 17:41:45.371  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 17:41:45.374  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 17:41:45.377  4312  7552 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 17:41:45.378  7114  7114 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 17:41:45.381  4312  7553 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:45.381  4312  7553 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 17:41:45.389  3443  3443 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 17:41:45.389  3443  3443 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:45.389  3443  3443 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-30 17:41:45.392  7150  7150 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 17:41:45.392  7150  7150 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 17:41:45.397  7114  7554 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:45.400  6988  7557 W FormManager: Network not available. Please check & try again.
08-30 17:41:45.402  7222  7222 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:41:45
,08-30 17:41:45.403  6988  7558 V FormManager: Network unavailable.
08-30 17:41:45.404  7222  7222 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 17:41:45.404  7222  7222 D Weather.Utils: 2 : All the weather widget is gone.
08-30 17:41:45.405  6988  7558 V FormManager: Network unavailable.
08-30 17:41:45.407  7222  7222 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 17:41:45.407  7222  7222 D WeatherAncestor: connectivity changed - connection : true
08-30 17:41:45.407  7222  7222 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2a806981
08-30 17:41:45.407  7222  7222 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 17:41:45.407  7222  7222 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 17:41:45.407  7222  7222 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 17:41:45.407  7222  7222 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 17:41:45.408  7222  7222 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:41:45
08-30 17:41:45.410  1034  2015 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-30 17:41:45.415  7031  7031 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-30 17:41:45.418  7031  7031 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 17:41:45.418  7031  7031 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,08-30 17:41:45.418  7031  7031 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 17:41:45.418  7031  7031 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 17:41:45.418  7031  7031 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 17:41:45.418  7031  7031 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 17:41:45.419  7031  7031 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 17:41:45.419  7031  7031 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 17:41:45.419  7031  7031 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 17:41:45.419  7031  7031 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 17:41:45.419  7031  7031 I BluetoothA2dpServiceJni: classInitNative
08-30 17:41:45.419  7031  7031 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 17:41:45.419  7031  7031 D A2dpStateMachine: make
08-30 17:41:45.420  7031  7031 I bluedroid-qcom: get_profile_interface a2dp
08-30 17:41:45.420  7031  7560 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 17:41:45.422  7031  7031 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 17:41:45.422  7031  7031 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-30 17:41:45.422  7031  7031 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:45.423  7031  7559 D A2dpStateMachine: Enter Disconnected: -2
08-30 17:41:45.423  7031  7031 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 17:41:45.424  7031  7031 D HidService: Received start request. Starting profile...
08-30 17:41:45.424  7031  7031 I bluedroid-qcom: get_profile_interface hidhost
08-30 17:41:45.424  7031  7031 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:45.425  7031  7031 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 17:41:45.426  7031  7031 D HealthService: Received start request. Starting profile...
08-30 17:41:45.427  7031  7031 I bluedroid-qcom: get_profile_interface health
08-30 17:41:45.427  7031  7031 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 17:41:45.427  7031  7031 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:45.428  7031  7031 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 17:41:45.429  7031  7031 D PanService: Received start request. Starting profile...
08-30 17:41:45.429  7031  7031 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 17:41:45.429  7031  7031 I bluedroid-qcom: get_profile_interface pan
08-30 17:41:45.433  7031  7031 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-30 17:41:45.433  7031  7031 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:45.434  7031  7031 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-30 17:41:45.438  7031  7031 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 17:41:45.438  7031  7031 D BtGatt.GattService: Received start request. Starting profile...
08-30 17:41:45.438  7031  7031 D BtGatt.GattService: start()
08-30 17:41:45.438  7031  7031 I bluedroid-qcom: get_profile_interface gatt
08-30 17:41:45.439  7031  7031 D BtGatt.AdvertiseManager: advertise manager created
,08-30 17:41:45.442  7031  7031 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:45.443  7031  7031 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:45.443  7031  7031 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-30 17:41:45.444  7031  7031 V BluetoothMapService: BluetoothMapBinder()
08-30 17:41:45.444  7031  7031 D BluetoothMapService: Received start request. Starting profile...
08-30 17:41:45.444  7031  7031 D BluetoothMapService: start()
08-30 17:41:45.446  7031  7031 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-30 17:41:45.446  7031  7031 D BluetoothMapEmailAppObserver: createReceiver()
08-30 17:41:45.447  7031  7031 D BluetoothMapEmailAppObserver: initObservers()
08-30 17:41:45.447  7031  7031 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 17:41:45.451  7031  7031 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
,08-30 17:41:45.451  7031  7031 D HeadsetStateMachine: Proxy object connected
08-30 17:41:45.452  7031  7031 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 17:41:45.452  7031  7031 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-30 17:41:45.455  7031  7031 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 17:41:45.455  7031  7531 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 17:41:45.455  7031  7531 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 17:41:45.455  7031  7531 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-30 17:41:45.457  7031  7031 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 17:41:45.458  7031  7031 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 17:41:45.460  7031  7031 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 17:41:45.460  7031  7031 V PanService: [BTUI] SIM Extra State :ABSENT
08-30 17:41:45.462  7031  7031 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 17:41:45.463  7031  7031 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-30 17:41:45.463  7031  7031 V BluetoothMapService: Handler(): got msg=1
,08-30 17:41:45.464  7031  7497 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 17:41:45.465  7031  7497 I bluedroid-qcom: enable
08-30 17:41:45.465  7031  7497 I bt_hci_bdroid: init
08-30 17:41:45.465  7031  7567 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 17:41:45.465  7031  7567 I bt-btu  : btu_task pending for preload complete event
08-30 17:41:45.465  7031  7031 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:45.466  7031  7497 I bt_vendor: bt-vendor : init
08-30 17:41:45.466  7031  7497 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 17:41:45.466  7031  7497 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 17:41:45.466  7031  7497 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 17:41:45.466  7031  7497 D bt_userial_mct: userial_init
08-30 17:41:45.466  7031  7497 D bt_hci_bdroid: set_power 1
08-30 17:41:45.466  7031  7497 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 17:41:45.466  7031  7497 I bt_vendor: Starting hciattach daemon
08-30 17:41:45.466  7031  7497 I bt_vendor: try to set true
08-30 17:41:45.466  7031  7031 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 17:41:45.466  7031  7031 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 17:41:45.466  7031  7031 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 17:41:45.466  7031  7031 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:45.466  7031  7031 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-30 17:41:45.451  7570  7570 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:41:45.451  7570  7570 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:41:45.478  7571  7571 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 17:41:45.532  7577  7577 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 17:41:45.543  7578  7578 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-30 17:41:45.569  7580  7580 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 17:41:45.580  7581  7581 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-30 17:41:45.593  7582  7582 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 17:41:45.616  7583  7583 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-30 17:41:45.656  7585  7585 I libmdmdetect: ESOC framework not supported
08-30 17:41:45.658  7585  7585 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-30 17:41:45.670  7585  7585 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-30 17:41:45.670  7585  7585 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-30 17:41:45.670  7585  7585 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,08-30 17:41:45.670  7585  7585 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-30 17:41:45.671  7585  7585 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-30 17:41:45.671  7585  7585 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-30 17:41:45.671  7585  7585 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-30 17:41:45.720  7585  7586 E QC-QMI  : qmi_client [7585] 14: failed to locate client data
,08-30 17:41:45.727   493   493 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-30 17:41:45.727   493   493 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-30 17:41:45.796  7593  7593 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 17:41:45.822  7594  7594 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 17:41:45.867  7031  7497 I bt_vendor: bluetooth satus is on
08-30 17:41:45.867  7031  7497 D bt_hci_bdroid: preload
08-30 17:41:45.868  7031  7569 D bt_userial_mct: userial_open(port:0)
08-30 17:41:45.868  7031  7569 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-30 17:41:45.872  7031  7569 I bt_vendor: Done intiailizing UART
08-30 17:41:45.876  7031  7569 I bt_vendor: Done intiailizing UART
,08-30 17:41:45.876  7031  7569 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 17:41:45.876  7031  7569 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-30 17:41:45.876  7031  7596 D bt_userial_mct: Entering userial_read_thread()
08-30 17:41:45.877  7031  7567 I bt-btu  : btu_task received preload complete event
,08-30 17:41:45.877  7031  7567 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-30 17:41:45.877  7031  7567 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-30 17:41:45.880  7031  7567 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-30 17:41:45.884  7031  7567 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 17:41:45.885  7031  7567 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 17:41:45.885  7031  7567 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 17:41:45.885  7031  7567 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 17:41:45.885  7031  7567 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 17:41:45.885  7031  7567 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 17:41:45.885  7031  7567 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 17:41:45.885  7031  7567 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 17:41:45.885  7031  7567 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,08-30 17:41:45.885  7031  7567 I         : BTE_InitTraceLevels -- TRC_GAP
,08-30 17:41:45.885  7031  7567 I         : BTE_InitTraceLevels -- TRC_PAN,
,08-30 17:41:45.885  7031  7567 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 17:41:45.885  7031  7567 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 17:41:45.885  7031  7567 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 17:41:45.885  7031  7567 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 17:41:45.885  7031  7567 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 17:41:45.986  7031  7567 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-30 17:41:45.986  7031  7567 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0203061 
08-30 17:41:45.986  7031  7567 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0203061 
,08-30 17:41:46.026  7031  7501 E bt-btif : Calling BTA_HhEnable
08-30 17:41:46.026  7031  7501 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-30 17:41:46.026  7031  7501 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-30 17:41:46.030  7031  7567 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-30 17:41:46.030  7031  7567 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-30 17:41:46.030  7031  7567 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 17:41:46.030  7031  7567 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 17:41:46.030  7031  7567 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-30 17:41:46.032  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 17:41:46.033  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 17:41:46.033  7031  7501 D BluetoothAdapterProperties: Name is: G3
08-30 17:41:46.035  7031  7501 D BluetoothAdapterProperties: Scan Mode:20
08-30 17:41:46.035  7031  7501 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 17:41:46.035  7031  7501 D bt_hci_bdroid: postload
08-30 17:41:46.035  7031  7569 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 17:41:46.038  7031  7569 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 17:41:46.038  7031  7567 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 17:41:46.039  7031  7501 D bte_conf: Device ID record 1 : primary
08-30 17:41:46.039  7031  7501 D bte_conf:   vendorId            = 00c4
08-30 17:41:46.039  7031  7501 D bte_conf:   vendorIdSource      = 0001
08-30 17:41:46.039  7031  7501 D bte_conf:   product             = 13a1
08-30 17:41:46.039  7031  7501 D bte_conf:   version             = 1000
08-30 17:41:46.039  7031  7501 D bte_conf:   clientExecutableURL = 
08-30 17:41:46.039  7031  7501 D bte_conf:   serviceDescription  = 
08-30 17:41:46.039  7031  7501 D bte_conf:   documentationURL    = 
08-30 17:41:46.039  7031  7501 D bte_conf: bte_load_did_conf no section named DID2.
,08-30 17:41:46.044  7031  7596 E bt_mct  : hci lib postload completed
08-30 17:41:46.047  7031  7497 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 17:41:46.047  7031  7497 D BluetoothAdapterProperties: ScanMode =  20
08-30 17:41:46.047  7031  7497 D BluetoothAdapterProperties: State =  11
08-30 17:41:46.048  7031  7497 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 17:41:46.048  7031  7497 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-30 17:41:46.049  7031  7497 D BluetoothAdapterProperties: Setting state to 12
08-30 17:41:46.049  7031  7497 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 17:41:46.049  7031  7501 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 17:41:46.049  7031  7501 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 17:41:46.041  7601  7601 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 17:41:46.041  7601  7601 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:41:46.059  1034  1098 D BluetoothManagerService: Message: 60
08-30 17:41:46.059  1034  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 17:41:46.059  1034  1098 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-30 17:41:46.060  7031  7497 I BluetoothAdapterState: Entering On State
08-30 17:41:46.069  7031  7567 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 17:41:46.069  7031  7567 W bt-smp  : Plain text(LSB ~ MSB) = 76 54 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 17:41:46.069  7031  7567 W bt-smp  : Encrypted text(LSB ~ MSB) = dc 20 c3 1b af 87 5d c9 d9 6d 7e 35 56 a5 22 7a 
,08-30 17:41:46.071  7031  7567 W bt-btm  : Stopping oneshot timer
08-30 17:41:46.092  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:41:46.092  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:46.092  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:46.092  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:41:46.092  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:41:46.092  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:41:46.092  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:41:46.092  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:41:46.099  7031  7567 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 17:41:46.099  7031  7567 W bt-smp  : Plain text(LSB ~ MSB) = a5 12 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 17:41:46.099  7031  7567 W bt-smp  : Encrypted text(LSB ~ MSB) = bc c5 80 35 cd fb ac 89 57 e9 f6 50 93 57 8f 74 
08-30 17:41:46.100  7031  7567 W bt-btm  : Stopping oneshot timer
08-30 17:41:46.105  7031  7501 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 17:41:46.105  7031  7501 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-30 17:41:46.113  7031  7497 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 17:41:46.113  7031  7497 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 17:41:46.113  7031  7497 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-30 17:41:46.114  7031  7567 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 17:41:46.114  7031  7567 W bt-smp  : Plain text(LSB ~ MSB) = 58 d6 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 17:41:46.114  7031  7567 W bt-smp  : Encrypted text(LSB ~ MSB) = 76 4c 4f 0a b6 5c 6f 15 4b 1d 0e 07 2a b9 55 51 
08-30 17:41:46.114  7031  7567 W bt-btm  : Stopping oneshot timer
08-30 17:41:46.115  7031  7497 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-30 17:41:46.115  7031  7497 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-30 17:41:46.115  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:41:46.126  7031  7567 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 17:41:46.126  7031  7567 W bt-smp  : Plain text(LSB ~ MSB) = 89 85 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 17:41:46.126  7031  7567 W bt-smp  : Encrypted text(LSB ~ MSB) = 83 0a f2 d5 4a 00 e9 ac be 2d 9f 65 75 93 c6 8d 
,08-30 17:41:46.129  7031  7567 W bt-btm  : Stopping oneshot timer
08-30 17:41:46.130  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:41:46.130  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:46.130  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:46.130  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:41:46.130  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:41:46.130  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:41:46.130  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:41:46.130  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:41:46.139  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:41:46.150  7031  7567 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 17:41:46.150  7031  7567 W bt-smp  : Plain text(LSB ~ MSB) = 86 11 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 17:41:46.150  7031  7567 W bt-smp  : Encrypted text(LSB ~ MSB) = 2c f9 17 91 6f 19 e6 e1 bf 6c 10 67 52 8f 9a 8c 
08-30 17:41:46.150  7031  7567 W bt-btm  : Stopping oneshot timer
08-30 17:41:46.156  6878  6897 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 17:41:46.166  6878  6894 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 17:41:46.169  1034  1098 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 17:41:46.171  1034  1034 D BluetoothHeadset: Proxy object connected
08-30 17:41:46.173  1034  1098 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 17:41:46.175  1034  1034 D BluetoothA2dp: Proxy object connected
08-30 17:41:46.175  7619  7619 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-30 17:41:46.177  6878  6897 D BluetoothPan: onBluetoothStateChange on: true
08-30 17:41:46.177  6878  6897 D BluetoothPan: onBluetoothStateChange call bindService
08-30 17:41:46.180  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 17:41:46.182  1851  1851 D BluetoothHeadset: Proxy object connected
08-30 17:41:46.183  1851  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 17:41:46.184  1851  1851 D BluetoothHeadset: Proxy object connected
08-30 17:41:46.185  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 17:41:46.187  1851  1851 D BluetoothHeadset: Proxy object connected
,08-30 17:41:46.187  6878  6894 D BluetoothMap: onBluetoothStateChange: up=true
08-30 17:41:46.192  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-30 17:41:46.192  1034  1091 W ProcessCpuTracker: Skipping unknown process pid 7601
08-30 17:41:46.192  1034  1091 W ProcessCpuTracker: Skipping unknown process pid 7605
08-30 17:41:46.193  1034  1098 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-30 17:41:46.193  1034  1098 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-30 17:41:46.193  1034  1098 D BluetoothManagerService: Message: 40
08-30 17:41:46.193  1034  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 17:41:46.194  6878  6878 D BluetoothInputDevice: Proxy object connected
08-30 17:41:46.194  6878  6878 D HidProfile: Bluetooth service connected
08-30 17:41:46.194  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:46.194  1940  2127 D LGBluetoothAPIService: Message: 1
08-30 17:41:46.194  1940  2127 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,08-30 17:41:46.197  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 17:41:46.204  6777  6777 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 17:41:46.208  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:41:46.210  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:46.211  6878  6878 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 17:41:46.211  6878  6878 D PanProfile: Bluetooth service connected
08-30 17:41:46.211  1940  2127 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-30 17:41:46.213  7031  7031 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:46.213  7031  7031 D BluetoothMapService: STATE_ON
08-30 17:41:46.213  6878  6878 D BluetoothMap: Proxy object connected
08-30 17:41:46.213  6878  6878 D MapProfile: Bluetooth service connected
08-30 17:41:46.213  6878  6878 D BluetoothMap: getConnectedDevices()
08-30 17:41:46.214  7031  7047 V BluetoothMapService: getConnectedDevices()
08-30 17:41:46.214  7031  7031 D LGBluetoothAPIServer: [BTUI] onCreate()
08-30 17:41:46.214  7031  7031 D LGBluetoothAPIServer: [BTUI] onBind()
08-30 17:41:46.216  1940  1940 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-30 17:41:46.216  1940  2127 D LGBluetoothAPIService: Message: 100
08-30 17:41:46.216  1940  2127 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-30 17:41:46.217  6878  6878 D LocalBluetoothProfileManager: Adding local A2DP profile
08-30 17:41:46.219  1034  1098 D BluetoothManagerService: Message: 30
08-30 17:41:46.221  6878  6878 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-30 17:41:46.224  1034  1098 D BluetoothManagerService: Message: 30
08-30 17:41:46.230  6878  6878 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-30 17:41:46.231  6878  6878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 17:41:46.231  7031  7031 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:46.232  7031  7031 V BluetoothPbapService: Pbap Service onCreate
08-30 17:41:46.232  7031  7031 V BluetoothPbapService: Starting PBAP service
08-30 17:41:46.233  7031  7031 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 17:41:46.233  7031  7031 V BluetoothPbapService: Pbap Service onBind
08-30 17:41:46.234  6878  6878 D BluetoothA2dp: Proxy object connected
08-30 17:41:46.234  7031  7031 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:46.234  7031  7031 V BluetoothPbapService: state: 12
08-30 17:41:46.234  7031  7031 V BluetoothMapService: Handler(): got msg=1
08-30 17:41:46.234  6878  6878 D A2dpProfile: Bluetooth service connected
,08-30 17:41:46.236  7031  7031 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 17:41:46.237  7031  7031 V BluetoothPbapService: Handler(): got msg=1
08-30 17:41:46.237  7031  7031 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-30 17:41:46.238  6878  6878 D BluetoothHeadset: Proxy object connected
08-30 17:41:46.238  7031  7031 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 17:41:46.238  7031  7031 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:41:46.238  7031  7031 V BluetoothPbapReceiver: ***********state = 12
08-30 17:41:46.239  6878  6878 D HeadsetProfile: Bluetooth service connected
08-30 17:41:46.239  7031  7624 D BluetoothMapMasInstance: MAS initSocket()
08-30 17:41:46.239  7031  7625 V BluetoothPbapService: Pbap Service initSocket
08-30 17:41:46.240  7031  7624 D BluetoothMapMasInstance:   masId = 00
08-30 17:41:46.240  7031  7624 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 17:41:46.240  7031  7624 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 17:41:46.240  7031  7624 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 17:41:46.242  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 17:41:46.242  1034  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:46.242  2208  2208 D c       : Getting all permits...
08-30 17:41:46.242  2208  2208 D a       : Opening database...
08-30 17:41:46.242  1034  1868 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:46.244  6878  6878 D BluetoothPbap: Proxy object connected
08-30 17:41:46.245  6878  6878 D PbapServerProfile: Bluetooth service connected
08-30 17:41:46.246  2208  2208 D a       : Opening database auth.proximity.permit_store...
08-30 17:41:46.246  6878  6878 D DockEventReceiver: finishStartingService: stopping service
08-30 17:41:46.247  2208  2208 D a       : Closing database...
,08-30 17:41:46.249  7031  7624 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:41:46.250  7031  7625 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:41:46.252  7031  7624 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=0
08-30 17:41:46.252  7031  7625 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-30 17:41:46.253  7031  7624 V BluetoothMapMasInstance: Succeed to create listening socket 
08-30 17:41:46.253  7031  7625 V BluetoothPbapService: Succeed to create listening socket 
08-30 17:41:46.253  7031  7624 D BluetoothMapMasInstance: Accepting socket connection...
08-30 17:41:46.253  7031  7625 V BluetoothPbapService: Accepting socket connection...
08-30 17:41:46.254  7031  7501 D BluetoothAdapterProperties: Scan Mode:21
08-30 17:41:46.254  7031  7501 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-30 17:41:46.256  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:46.257  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:46.263  6878  6878 D BluetoothPermissionRequest: onReceive
,08-30 17:41:46.264  6878  6878 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 17:41:46.266  6878  6878 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 17:41:46.270  7031  7031 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-30 17:41:46.271  7031  7031 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 17:41:46.275  7031  7031 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-30 17:41:46.294  7031  7031 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-30 17:41:46.295  7031  7031 V BtOppService: onCreate
,08-30 17:41:46.299  7031  7031 V BluetoothOppNotification: send message
08-30 17:41:46.302  7031  7031 V BtOppService: Starting RfcommListener
08-30 17:41:46.305  7031  7031 D BluetoothOppPreference: Dumping Names:  
08-30 17:41:46.305  7031  7031 D BluetoothOppPreference: {}
08-30 17:41:46.306  7031  7031 D BluetoothOppPreference: Dumping Channels:  
08-30 17:41:46.306  7031  7031 D BluetoothOppPreference: {}
08-30 17:41:46.306  7031  7031 V BtOppService: onStartCommand
08-30 17:41:46.308  7031  7633 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 17:41:46.310  7031  7031 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:46.310  7031  7031 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-30 17:41:46.314  7031  7031 V BluetoothOppNotification: new notify threadi!
08-30 17:41:46.315  7031  7031 V BluetoothOppNotification: send delay message
08-30 17:41:46.316  7031  7031 V BtOppService: start RfcommListener
08-30 17:41:46.319  7031  7634 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 17:41:46.320  7031  7633 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 17:41:46.320  7031  7031 V BtOppService: RfcommListener started
08-30 17:41:46.320  7031  7630 V BtOppService: Deleted complete outbound shares, number =  0
08-30 17:41:46.321  7031  7635 V BtOppRfcommListener: Starting RFCOMM listener....
08-30 17:41:46.322  1034  1974 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:46.323  7031  7630 V BtOppService: Deleted complete inbound failed shares, number = 0
08-30 17:41:46.323  7031  7635 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:41:46.323  7031  7630 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,08-30 17:41:46.328  7031  7630 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33a8d3c2 on behalf of 
08-30 17:41:46.328  7031  7635 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=73
08-30 17:41:46.329  7031  7635 V BtOppRfcommListener: Started RFCOMM listener....
08-30 17:41:46.329  7031  7634 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@397375d3 on behalf of 
08-30 17:41:46.329  7031  7635 I BtOppRfcommListener: Accept thread started.
08-30 17:41:46.329  7031  7635 V BtOppRfcommListener: Accepting connection...
08-30 17:41:46.329  7031  7633 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1841a510 on behalf of 
08-30 17:41:46.331  7031  7634 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 17:41:46.333  7031  7633 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 17:41:46.333  7031  7633 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 17:41:46.334  7031  7633 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e9e5809 on behalf of 
08-30 17:41:46.335  7031  7633 V BluetoothOppNotification: update too frequent, put in queue
,08-30 17:41:46.336  7031  7634 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 17:41:46.337  7031  7031 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:46.337  7031  7031 V BluetoothFtpService: Ftp Service onCreate
08-30 17:41:46.337  7031  7031 I BluetoothFtpService: Ftp Service onCreate
08-30 17:41:46.337  7031  7031 V BluetoothFtpService: Ftp Service onStartCommand
08-30 17:41:46.338  7031  7031 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:46.338  7031  7031 V BluetoothFtpService: Starting Listening on sockets
08-30 17:41:46.338  7031  7031 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 17:41:46.338  7031  7633 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 17:41:46.338  7031  7031 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 17:41:46.338  7031  7031 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 17:41:46.338  7031  7031 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:46.338  7031  7031 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 17:41:46.338  7031  7031 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 17:41:46.339  7031  7634 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b759c2f on behalf of 
08-30 17:41:46.340  7031  7634 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-30 17:41:46.343  7031  7031 V BtOppService: ContentObserver received notification
08-30 17:41:46.343  7031  7031 V BtOppService: ContentObserver received notification
08-30 17:41:46.343  7031  7031 V BluetoothFtpService: Handler(): got msg=1
08-30 17:41:46.344  7031  7031 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 17:41:46.344  7031  7634 V BluetoothOppNotification: outbound notification was removed.
08-30 17:41:46.344  7031  7031 V BluetoothFtpService: Ftp Service initSocket
08-30 17:41:46.344  7031  7634 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 17:41:46.346  7031  7634 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@204023c on behalf of 
08-30 17:41:46.348  7031  7637 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 17:41:46.348  7031  7637 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 17:41:46.349  1034  1590 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:46.349  7031  7637 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@acb6bc5 on behalf of 
,08-30 17:41:46.350  7031  7634 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 17:41:46.351  7031  7031 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:41:46.350  7031  7637 V BluetoothOppNotification: update too frequent, put in queue
08-30 17:41:46.352  7031  7634 V BluetoothOppNotification: inbound notification was removed.
08-30 17:41:46.352  7031  7634 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 17:41:46.352  7031  7031 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
08-30 17:41:46.352  7031  7031 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-30 17:41:46.354  7031  7638 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-30 17:41:46.356  7031  7637 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 17:41:46.357  7031  7634 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32d1191a on behalf of 
08-30 17:41:46.377  7031  7031 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:46.377  7031  7031 V BluetoothSapService: Sap Service onCreate
,08-30 17:41:46.379  7031  7031 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:46.379  7031  7031 V BluetoothSapService: state: 12
08-30 17:41:46.380  7031  7031 V BluetoothSapService: Starting SAP server process
08-30 17:41:46.381  7031  7031 V BluetoothSapService: SAP Service startRfcommListenerThread
08-30 17:41:46.371  7639  7639 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:41:46.371  7639  7639 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:41:46.383  7031  7640 V BluetoothSapService: Sap Service initRfcommSocket
08-30 17:41:46.383  1034  1886 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:46.384  7031  7640 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:41:46.386  7031  7640 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-30 17:41:46.386  7031  7640 V BluetoothSapService: Succeed to create listening socket 
08-30 17:41:46.386  7031  7640 V BluetoothSapService: Accepting socket connection...
08-30 17:41:46.403  7252  7302 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-30 17:41:46.407  7639  7639 V BT_SAP  : Event pipe created
,08-30 17:41:46.407  7639  7639 V BT_SAP  : create_server_socket qcom.sap.server
08-30 17:41:46.407  7639  7639 V BT_SAP  : created socket fd 6
08-30 17:41:46.965  1034  1389 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:46.965  1034  1389 D LGWifiP2pService: DefaultState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 17:41:47.025  1034  1390 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-30 17:41:47.032  1034  1390 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-30 17:41:47.275  1034  1886 I ActivityManager: Killing 7414:com.lge.bnr/1000 (adj 15): empty #17
,08-30 17:41:47.309  1034  1951 W libprocessgroup: failed to open /acct/uid_1000/pid_7414/cgroup.procs: No such file or directory
,08-30 17:41:47.317  7031  7031 V BluetoothOppNotification: new notify threadi!
08-30 17:41:47.317  7031  7031 V BluetoothOppNotification: send delay message
08-30 17:41:47.319  7031  7652 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 17:41:47.320  7031  7652 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3457ace6 on behalf of 
08-30 17:41:47.321  7031  7652 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 17:41:47.322  7031  7652 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-30 17:41:47.326  7031  7652 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1fe6e227 on behalf of 
08-30 17:41:47.326  7031  7652 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 17:41:47.329  7031  7652 V BluetoothOppNotification: outbound notification was removed.
08-30 17:41:47.329  7031  7652 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 17:41:47.331  7031  7652 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f605cd4 on behalf of 
08-30 17:41:47.332  7031  7652 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-30 17:41:47.338  7031  7652 V BluetoothOppNotification: inbound notification was removed.
,08-30 17:41:47.338  7031  7652 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 17:41:47.339  7031  7652 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38484e7d on behalf of 
08-30 17:41:47.497  1034  2015 I ActivityManager: Killing 6900:com.lge.sync/1000 (adj 15): empty #17
,08-30 17:41:47.533  1034  1397 D WifiService: Client connection lost with reason: 4
,08-30 17:41:47.564  1034  1886 W libprocessgroup: failed to open /acct/uid_1000/pid_6900/cgroup.procs: No such file or directory
,08-30 17:41:47.971  1034  2397 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 17:41:47.971  1034  2397 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@fd8dd9f mBinding = false
,08-30 17:41:48.003  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 17:41:48.003  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 17:41:48.003  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-30 17:41:48.008  1034  1098 D BluetoothManagerService: Message: 2
08-30 17:41:48.009  1034  1098 D BluetoothManagerService: Sending off request.
08-30 17:41:48.009  7031  7047 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 17:41:48.010  7031  7497 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 17:41:48.010  7031  7497 D BluetoothAdapterProperties: Setting state to 13
08-30 17:41:48.010  7031  7497 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 17:41:48.011  7031  7497 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 17:41:48.011  7031  7497 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 17:41:48.013  7031  7501 D BluetoothAdapterProperties: Scan Mode:20
08-30 17:41:48.014  7031  7497 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 17:41:48.016  7031  7625 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 17:41:48.017  7031  7624 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 17:41:48.017  7031  7624 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 17:41:48.017  7031  7624 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 17:41:48.017  7031  7624 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 17:41:48.017  7031  7624 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 17:41:48.017  7031  7624 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 17:41:48.017  7031  7624 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 17:41:48.017  7031  7624 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-30 17:41:48.022  7031  7638 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 17:41:48.022  7031  7640 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 17:41:48.023  7031  7635 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 17:41:48.023  7031  7567 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 17:41:48.024  7031  7567 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-30 17:41:48.025  7031  7497 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 17:41:48.029  7031  7567 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 17:41:48.029  7031  7567 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 17:41:48.029  7031  7567 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 17:41:48.029  7031  7567 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 17:41:48.029  7031  7567 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:41:48.029  7031  7567 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 17:41:48.029  7031  7567 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:41:48.029  7031  7567 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 17:41:48.029  7031  7567 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:41:48.029  7031  7567 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 17:41:48.029  7031  7567 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 17:41:48.029  7031  7567 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 17:41:48.039  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:41:48.039  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:41:48.039  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:48.039  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:48.039  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:41:48.039  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:41:48.039  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:41:48.039  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:41:48.039  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:41:48.044  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:41:48.044  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:41:48.049  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:41:48.050  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:41:48.050  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:48.050  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:48.050  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:41:48.050  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:41:48.050  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:41:48.050  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:41:48.050  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:41:48.050  1034  1098 D BluetoothManagerService: Message: 60
08-30 17:41:48.050  1034  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-30 17:41:48.050  1034  1098 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-30 17:41:48.052  6777  6777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:41:48.052  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:41:48.057  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:48.059  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 17:41:48.064  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:41:48.067  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:48.070  7031  7031 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:48.070  7031  7031 D BluetoothMapService: STATE_TURNING_OFF
08-30 17:41:48.070  7031  7031 V BluetoothMapService: Handler(): got msg=4
08-30 17:41:48.070  7031  7031 D BluetoothMapService: MAP Service closeService in
08-30 17:41:48.070  7031  7031 D BluetoothMapMasInstance: MAP Service shutdown
08-30 17:41:48.071  7031  7031 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 17:41:48.071  7031  7031 V BluetoothMapService: MAP Service closeService out
08-30 17:41:48.072  7031  7031 V BtOppService: Receiver DISABLED_ACTION 
08-30 17:41:48.072  7031  7031 I BtOppRfcommListener: stopping Accept Thread
08-30 17:41:48.072  7031  7031 V BtOppRfcommListener: close mBtServerSocket
08-30 17:41:48.073  7031  7635 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 17:41:48.073  7031  7031 V BtOppRfcommListener: waiting for thread to terminate
08-30 17:41:48.073  7031  7031 V BtOppRfcommListener: done waiting for thread to terminate
08-30 17:41:48.076  6878  6878 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-30 17:41:48.088  6878  6878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 17:41:48.091  7031  7031 V BtOppService: onDestroy
,08-30 17:41:48.093  7031  7031 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 17:41:48.099  7031  7031 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 17:41:48.099  7031  7031 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:48.099  7031  7031 V BluetoothPbapReceiver: ***********state = 13
08-30 17:41:48.100  7031  7031 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-30 17:41:48.103  7031  7031 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:48.103  7031  7031 V BluetoothPbapService: state: 13
08-30 17:41:48.103  7031  7031 V BluetoothPbapService: Pbap Service closeService in
,08-30 17:41:48.108  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 17:41:48.109  7031  7031 V BluetoothPbapService: successfully stopped pbap service
08-30 17:41:48.109  7031  7031 V BluetoothPbapService: Pbap Service closeService out
08-30 17:41:48.110  7031  7031 V BluetoothPbapService: Pbap Service onDestroy
08-30 17:41:48.110  7031  7031 V BluetoothPbapService: Pbap Service closeService in
08-30 17:41:48.110  7031  7031 V BluetoothPbapService: Pbap Service closeService out
,08-30 17:41:48.111  7031  7031 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-30 17:41:48.136  6878  6878 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:41:48.138  6878  6878 D BluetoothPbap: Proxy object disconnected
08-30 17:41:48.138  6878  6878 D PbapServerProfile: Bluetooth service disconnected
,08-30 17:41:48.145  6878  6878 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-30 17:41:48.150  6878  6878 D BluetoothPermissionRequest: onReceive
08-30 17:41:48.150  6878  6878 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 17:41:48.156  6878  6878 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 17:41:48.160  7031  7031 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-30 17:41:48.160  7031  7031 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-30 17:41:48.160  7031  7031 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-30 17:41:48.166  7031  7031 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:48.166  7031  7031 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 17:41:48.167  7031  7031 V BluetoothFtpService: Ftp Service onStartCommand
08-30 17:41:48.167  7031  7031 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:48.168  7031  7031 V BluetoothFtpService: Ftp Service closeService
08-30 17:41:48.168  7031  7031 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-30 17:41:48.169  7031  7031 V BluetoothFtpService: successfully stopped ftp service
08-30 17:41:48.170  7031  7031 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 17:41:48.170  7031  7031 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 17:41:48.170  7031  7031 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 17:41:48.170  7031  7031 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:48.170  7031  7031 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 17:41:48.170  7031  7031 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 17:41:48.171  7031  7031 V BluetoothFtpService: Ftp Service onDestroy
08-30 17:41:48.171  7031  7031 V BluetoothFtpService: Ftp Service closeService
08-30 17:41:48.175  7031  7031 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:48.175  7031  7031 V BluetoothSapService: state: 13
08-30 17:41:48.175  7031  7031 V BluetoothSapService: Stopping SAP server process
08-30 17:41:48.176  7031  7031 V BluetoothSapService: Sap Service closeSapService in
08-30 17:41:48.176  7031  7031 V BluetoothSapService: Close listen Socket : 
08-30 17:41:48.176  7031  7031 V BluetoothSapService: Close rfcomm Socket : 
08-30 17:41:48.176  7031  7031 V BluetoothSapService: Close sapd  Socket : 
,08-30 17:41:48.180  7031  7031 V BluetoothSapService: Sap Service closeSapService out
,08-30 17:41:48.180  7031  7031 V BluetoothSapService: Sap Service onDestroy
08-30 17:41:48.180  7031  7031 V BluetoothSapService: Sap Service closeSapService in
,08-30 17:41:48.180  7031  7031 V BluetoothSapService: Close listen Socket : 
08-30 17:41:48.180  7031  7031 V BluetoothSapService: Close rfcomm Socket : 
08-30 17:41:48.180  7031  7031 V BluetoothSapService: Close sapd  Socket : 
08-30 17:41:48.181  7031  7031 V BluetoothSapService: Sap Service closeSapService out
08-30 17:41:48.930  7031  7501 D bt_hci_bdroid: cleanup
,08-30 17:41:48.940  7031  7569 I bt_lpm  : LPM is already off!!!
08-30 17:41:48.941  7031  7596 I bt_userial_mct: exiting userial_read_thread
08-30 17:41:48.941  7031  7596 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 17:41:48.941  7031  7567 W bt-btif : ag scb idx 1 not allocated
08-30 17:41:48.941  7031  7567 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 17:41:48.941  7031  7567 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 17:41:48.941  7031  7567 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:41:48.941  7031  7567 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 17:41:48.941  7031  7567 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:41:48.941  7031  7567 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 17:41:48.942  7031  7567 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:41:48.942  7031  7567 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 17:41:48.942  7031  7567 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:41:48.942  7031  7567 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 17:41:48.942  7031  7567 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:41:48.942  7031  7567 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 17:41:48.942  7031  7567 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:41:48.942  7031  7567 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 17:41:48.942  7031  7567 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:41:48.942  7031  7567 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 17:41:48.942  7031  7567 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:41:48.942  7031  7567 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 17:41:48.942  7031  7567 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:41:48.942  7031  7567 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 17:41:48.943  7031  7501 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 17:41:48.943  7031  7569 I bt_vendor: hw_epilog_process
08-30 17:41:48.943  7031  7501 D bt_hci_bdroid: cleanup Finalizing cleanup
08-30 17:41:48.943  7031  7501 D bt_userial_mct: userial_close
08-30 17:41:48.943  7031  7501 E bt_userial_mct: pthread_join() FAILED result:3
08-30 17:41:48.943  7031  7501 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-30 17:41:48.948  7031  7501 D bt_hci_bdroid: set_power 0
08-30 17:41:48.948  7031  7501 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 17:41:48.948  7031  7501 I bt_vendor: bluetooth satus is on
08-30 17:41:48.948  7031  7501 I bt_vendor: bt-vendor : resetting BT status
08-30 17:41:48.948  7031  7501 I bt_vendor: Starting hciattach daemon
08-30 17:41:48.948  7031  7501 I bt_vendor: try to set false
08-30 17:41:48.951  7031  7501 I bt_vendor: Starting hciattach daemon
08-30 17:41:48.951  7031  7501 I bt_vendor: try to set false
,08-30 17:41:48.955  7031  7501 I bt_vendor: cleanup
08-30 17:41:48.956  7031  7567 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 17:41:48.956  7031  7501 I GKI_LINUX: GKI_exit_task 0 done
08-30 17:41:48.956  7031  7501 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 17:41:48.958  7031  7497 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 17:41:48.960  7031  7031 D HeadsetService: Received stop request...Stopping profile...
08-30 17:41:48.962  7031  7031 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 17:41:48.962  7031  7031 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 17:41:48.962  7031  7031 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:48.963  7031  7531 D HeadsetStateMachine: Exit Disconnected: -1
,08-30 17:41:48.967  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-30 17:41:48.967  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-30 17:41:48.967  1851  1851 D BluetoothHeadset: Proxy object disconnected
08-30 17:41:48.968  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-30 17:41:48.968  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 17:41:48.970  7031  7031 D HeadsetStateMachine: Unbinding service...
08-30 17:41:48.971  7031  7031 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 17:41:48.971  7031  7031 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 17:41:48.971  7031  7031 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 17:41:48.971  7031  7031 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 17:41:48.971  7031  7031 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 17:41:48.971  7031  7031 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 17:41:48.971  7031  7031 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 17:41:48.978  7031  7031 D A2dpService: Received stop request...Stopping profile...
,08-30 17:41:48.982  7031  7559 D A2dpStateMachine: Exit Disconnected: -1
08-30 17:41:48.984  7031  7497 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 17:41:48.984  7031  7031 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-30 17:41:48.985  7031  7031 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-30 17:41:48.985  7031  7031 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 17:41:48.986  7031  7031 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:48.987  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-30 17:41:48.987  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 17:41:48.988  7031  7031 D HidService: Received stop request...Stopping profile...
08-30 17:41:48.988  7031  7031 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:48.990  7031  7031 D HealthService: Received stop request...Stopping profile...
08-30 17:41:48.991  7031  7031 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:48.994  7031  7031 D PanService: Received stop request...Stopping profile...
,08-30 17:41:48.996  7031  7031 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:48.999  7031  7031 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 17:41:49.000  7031  7031 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 17:41:49.000  7031  7031 D BtGatt.GattService: stop()
08-30 17:41:49.000  7031  7031 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 17:41:49.001  7031  7031 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:49.003  7031  7031 D BluetoothMapService: Received stop request...Stopping profile...
08-30 17:41:49.003  7031  7031 D BluetoothMapService: stop()
08-30 17:41:49.004  7031  7031 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 17:41:49.005  7031  7031 D BluetoothMapEmailAppObserver: removeReceiver()
08-30 17:41:49.005  7031  7031 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
,08-30 17:41:49.009  7031  7031 I BluetoothA2dpServiceJni: cleanupNative
08-30 17:41:49.009  7031  7560 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 17:41:49.009  7031  7031 I GKI_LINUX: GKI_exit_task 2 done
08-30 17:41:49.009  7031  7031 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 17:41:49.010  7031  7031 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 17:41:49.010  7031  7031 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 17:41:49.010  7031  7031 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 17:41:49.010  7031  7031 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 17:41:49.010  7031  7031 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 17:41:49.011  7031  7031 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 17:41:49.011  7031  7031 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 17:41:49.013  7031  7031 V BluetoothMapService: Handler(): got msg=4
08-30 17:41:49.013  7031  7031 D BluetoothMapService: MAP Service closeService in
08-30 17:41:49.013  7031  7031 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 17:41:49.013  7031  7031 V BluetoothMapService: MAP Service closeService out
08-30 17:41:49.014  7031  7497 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 17:41:49.014  7031  7497 D BluetoothAdapterProperties: Setting state to 10
08-30 17:41:49.014  7031  7497 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 17:41:49.016  7031  7031 D BluetoothMapService: cleanup()
08-30 17:41:49.016  7031  7031 D BluetoothMapService: MAP Service closeService in
08-30 17:41:49.016  7031  7031 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 17:41:49.016  7031  7031 V BluetoothMapService: MAP Service closeService out
08-30 17:41:49.017  1034  1098 D BluetoothManagerService: Message: 60
08-30 17:41:49.017  1034  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 17:41:49.017  1034  1098 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
,08-30 17:41:49.021  7031  7497 I BluetoothAdapterState: Entering OffState
08-30 17:41:49.021  6878  6894 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 17:41:49.022  6878  6894 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 17:41:49.022  6878  6894 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 17:41:49.023  6878  6894 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:41:49.024  1034  1098 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:41:49.024  1034  1098 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 17:41:49.024  6878  6894 D BluetoothPan: onBluetoothStateChange on: false
08-30 17:41:49.025  1851  1867 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:41:49.026  1851  2455 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 17:41:49.031  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 17:41:49.034  6878  6897 D BluetoothMap: onBluetoothStateChange: up=false
08-30 17:41:49.035  1034  1098 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 17:41:49.035  1034  1098 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 17:41:49.037  1034  1098 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 17:41:49.037  1034  1098 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 17:41:49.037  1034  1098 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@fd8dd9f mBinding = false
08-30 17:41:49.037  1034  1098 D BluetoothManagerService: Sending unbind request.
08-30 17:41:49.042  7031  7501 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-30 17:41:49.044  7031  7031 I GKI_LINUX: GKI_exit_task 1 done
08-30 17:41:49.044  7031  7031 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 17:41:49.045  7031  7031 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 17:41:49.046  7031  7031 I art     : --- WEIRD: removing null entry 248
08-30 17:41:49.046  7031  7031 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-30 17:41:49.046  7031  7031 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-30 17:41:49.046  7031  7031 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-30 17:41:49.048  1034  1098 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-30 17:41:49.052  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 17:41:49.056  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:41:49.059  1940  2127 D LGBluetoothAPIService: Message: 2
08-30 17:41:49.059  1940  2127 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@239d53b8 mBinding = false
08-30 17:41:49.059  1940  2127 D LGBluetoothAPIService: Sending unbind request.
08-30 17:41:49.063  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:49.064  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:49.064  6878  6878 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 17:41:49.064  6878  6878 D LGBluetoothEventManager: [BTUI] clear device connection state
08-30 17:41:49.068  6878  6878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 17:41:49.075  7031  7031 I art     : System.exit called, status: 0
08-30 17:41:49.075  7031  7031 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 17:41:49.089  6878  6878 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:41:49.095  1603  1603 D BluetoothAdapter: 330666496: getState() :  mService = null. Returning STATE_OFF
08-30 17:41:49.095  1603  1603 D BluetoothAdapter: 330666496: getState() :  mService = null. Returning STATE_OFF
08-30 17:41:49.113   311  1402 V AudioFlinger: 7031 died, releasing its sessions
08-30 17:41:49.113   311  1402 V AudioFlinger:  pid 1851 @ 0
08-30 17:41:49.113   311  1402 V AudioFlinger:  pid 3443 @ 1
08-30 17:41:49.113   311  1402 V AudioFlinger:  pid 3443 @ 2
08-30 17:41:49.114  6878  6878 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-30 17:41:49.168  1034  2006 I ActivityManager: Process com.android.bluetooth (pid 7031) has died
,08-30 17:41:49.168  1034  2006 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-30 17:41:49.173  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 17:41:49.186  6878  6878 D BluetoothPermissionRequest: onReceive
,08-30 17:41:49.189  6878  6878 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 17:41:49.190  6878  6878 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-30 17:41:49.195  6878  6878 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 17:41:49.281  1034  1951 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7700 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-30 17:41:49.365  7700  7700 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-30 17:41:49.365  7700  7700 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 17:41:49.366  7700  7700 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-30 17:41:49.367  7700  7700 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 17:41:49.393  7700  7700 D BluetoothAdapterApp: Loading JNI Library
,08-30 17:41:49.430  7700  7700 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@300ba49 Instance Count = 1
,08-30 17:41:49.520  1034  1091 I art     : Explicit concurrent mark sweep GC freed 76146(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 3.762ms total 183.253ms
,08-30 17:41:49.524  7700  7700 D BluetoothAdapterApp: onCreate
08-30 17:41:49.554  7700  7700 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-30 17:41:49.554  7700  7700 D ProfileConfigQcom: Adding HeadsetService
08-30 17:41:49.554  7700  7700 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-30 17:41:49.554  7700  7700 D ProfileConfigQcom: Adding A2dpService
08-30 17:41:49.555  7700  7700 D ProfileConfigQcom: [BTUI] HidService is supported
08-30 17:41:49.555  7700  7700 D ProfileConfigQcom: Adding HidService
08-30 17:41:49.555  7700  7700 D ProfileConfigQcom: [BTUI] HealthService is supported
08-30 17:41:49.555  7700  7700 D ProfileConfigQcom: Adding HealthService
08-30 17:41:49.556  7700  7700 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-30 17:41:49.556  7700  7700 D ProfileConfigQcom: [BTUI] PanService is supported
08-30 17:41:49.557  7700  7700 D ProfileConfigQcom: Adding PanService
08-30 17:41:49.557  7700  7700 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 17:41:49.557  7700  7700 D ProfileConfigQcom: Adding GattService
08-30 17:41:49.557  7700  7700 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-30 17:41:49.557  7700  7700 D ProfileConfigQcom: Adding BluetoothMapService
08-30 17:41:49.558  7700  7700 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 17:41:49.560  7700  7700 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-30 17:41:49.566  6878  6878 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 17:41:49.567  7700  7700 V LGMDMManagerInternal: Create singleton instance
,08-30 17:41:49.654  7700  7700 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:41:49.661  7700  7700 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 17:41:49.662  7700  7700 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 17:41:49.662  7700  7700 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 17:41:49.666  7700  7700 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:49.666  7700  7700 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-30 17:41:49.671  6965  6965 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-30 17:41:49.676  1034  2015 I ActivityManager: Killing 6681:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-30 17:41:49.706  6946  6946 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-30 17:41:49.709  6946  6946 W System.err: android.os.DeadObjectException
,08-30 17:41:49.712  6946  6946 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 17:41:49.712  6946  6946 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
,08-30 17:41:49.713  6946  6946 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-30 17:41:49.713  6946  6946 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
,08-30 17:41:49.713  6946  6946 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 17:41:49.713  6946  6946 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 17:41:49.713  6946  6946 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 17:41:49.713  6946  6946 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 17:41:49.713  6946  6946 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:41:49.713  6946  6946 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 17:41:49.714  6946  6946 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:41:49.714  6946  6946 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:41:49.714  6946  6946 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 17:41:49.714  6946  6946 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 17:41:49.714  6946  6946 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-30 17:41:49.715  6946  6946 W System.err: android.os.DeadObjectException
08-30 17:41:49.715  6946  6946 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 17:41:49.716  6946  6946 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 17:41:49.716  6946  6946 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-30 17:41:49.716  6946  6946 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-30 17:41:49.716  6946  6946 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 17:41:49.716  6946  6946 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 17:41:49.716  6946  6946 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 17:41:49.716  6946  6946 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 17:41:49.716  6946  6946 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:41:49.716  6946  6946 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 17:41:49.717  6946  6946 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:41:49.717  6946  6946 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:41:49.717  6946  6946 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 17:41:49.717  6946  6946 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 17:41:49.717  6946  6946 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-30 17:41:49.718  6946  6946 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-30 17:41:49.790  1034  2032 W libprocessgroup: failed to open /acct/uid_1000/pid_6681/cgroup.procs: No such file or directory
08-30 17:41:49.791  1034  2032 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-30 17:41:49.806  6946  6946 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-30 17:41:49.807  6946  6946 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-30 17:41:49.870  1034  1785 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7724 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 17:41:49.872  6946  6946 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-30 17:41:49.944  7724  7724 D UEI.SmartControl: Quickset Services start...
,08-30 17:41:49.946  7724  7724 I UEI.SmartControl: Manufacture = LGE
,08-30 17:41:49.946  7724  7724 D UEI.SmartControl: Id = LGNevo
,08-30 17:41:49.951  7724  7724 D UEI.SmartControl: File observer start...
08-30 17:41:49.952  7724  7724 E UEI.SmartControl: IR Port is disabled: false
08-30 17:41:49.953  7724  7724 D UEI.SmartControl: Starting file observer...
08-30 17:41:49.953  7724  7724 D UEI.SmartControl: Extracting JNI libs...
,08-30 17:41:49.954  7724  7724 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-30 17:41:50.062  7724  7724 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-30 17:41:50.062  7724  7724 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-30 17:41:50.062  7724  7724 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-30 17:41:50.122  7724  7724 I UEI.SmartControl: --- Selecting new region: 6
,08-30 17:41:50.125  7724  7724 I UEI.SmartControl: Model = LG-D855
,08-30 17:41:50.127  7724  7724 D UEI.SmartControl: QS Service created
,08-30 17:41:50.147  7724  7724 I UEI.SmartControl: Service initServices...
,08-30 17:41:50.153  7724  7724 D UEI.SmartControl: QS start get config
08-30 17:41:50.229  7724  7724 D UEI.SmartControl: Loading JNI Libs...
,08-30 17:41:50.570  7724  7724 I UEI.SmartControl: Supports setup maps: true
08-30 17:41:50.573  7724  7724 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 17:41:50.573  7724  7724 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 17:41:50.574  7724  7724 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 17:41:50.574  7724  7724 I UEI.SmartControl: ### init IR Blaster...
,08-30 17:41:50.583  7724  7724 D serial_port: Configuring serial port
08-30 17:41:50.586  7724  7724 E UEI.SmartControl: UEIBLaster setting for 616
08-30 17:41:50.586  7724  7724 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 17:41:50.586  7724  7724 I UEI.SmartControl: configuring settings for MAXQ616
08-30 17:41:50.587  7724  7724 I UEI.SmartControl: Get version...
08-30 17:41:50.603  7724  7748 D UEI.SmartControl: serial port data available: 21
,08-30 17:41:50.633  7724  7724 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-30 17:41:50.633  7724  7724 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 17:41:50.634  7724  7724 I UEI.SmartControl: QS saving settings...
,08-30 17:41:50.642  7724  7724 D UEI.SmartControl: IR Blaster version: 25672567
08-30 17:41:50.662  7724  7748 D UEI.SmartControl: serial port data available: 4
,08-30 17:41:50.703  7724  7724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-30 17:41:50.720  7724  7751 I UEI.SmartControl: Device manager: loading config....
08-30 17:41:50.720  7724  7751 D UEI.SmartControl: ----------- loading internal config...
08-30 17:41:50.726  7724  7724 E UEI.SmartControl: Services init done
08-30 17:41:50.726  7724  7724 D UEI.SmartControl: QS Service init finished
,08-30 17:41:50.728  7724  7724 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 17:41:50.729  7724  7724 D UEI.SmartControl: QS Service version code: 201091
08-30 17:41:50.729  7724  7724 D UEI.SmartControl: Service requested: Control
08-30 17:41:50.734  7724  7751 E UEI.SmartControl: Loading SETTINGS...
08-30 17:41:50.735  7724  7724 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 17:41:50.740  1034  2397 I ActivityManager: Killing 6946:com.lge.qremote/u0a112 (adj 15): empty #17
,08-30 17:41:50.752  7724  7751 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-30 17:41:50.759  7724  7750 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-30 17:41:50.759  7724  7750 D UEI.SmartControl: -----service ready thread exits
08-30 17:41:50.802  1034  1937 W libprocessgroup: failed to open /acct/uid_10112/pid_6946/cgroup.procs: No such file or directory
,08-30 17:41:50.817  7724  7724 D UEI.SmartControl: Internal service binding...
,08-30 17:41:51.085  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:51.085  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:41:51.166  1034  1380 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 17:41:51.190  1603  1603 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-30 17:41:51.282  1034  1091 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7753 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-30 17:41:51.293  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-30 17:41:51.294  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-30 17:41:51.314  1034  1034 D administrator: Handling package changes for user 0
,08-30 17:41:51.321  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-30 17:41:51.344  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 17:41:51.369  7753  7753 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 17:41:51.410  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-30 17:41:51.410  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-30 17:41:51.428  7753  7753 D LgDataFeature: LgDataFeature() Constructor: none
08-30 17:41:51.429  7753  7753 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 17:41:51.452  1034  1090 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 17:41:51.457  1034  1090 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-30 17:41:51.463  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-30 17:41:51.464  2513  2513 V GmsNetworkLocationProvi: DISABLE
08-30 17:41:51.490  1034  1090 D LocationProviderProxy: applying state to connected service
,08-30 17:41:51.494  2513  2513 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-30 17:41:51.550  7753  7798 I Babel   : MmsConfig: mnc/mcc: 0/0
08-30 17:41:51.550  7753  7798 I Babel   : MmsConfig.loadMmsSettings
,08-30 17:41:51.556  7753  7798 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-30 17:41:51.556  7753  7798 I Babel   : MmsConfig.loadFromDatabase
,08-30 17:41:51.582  7753  7798 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-30 17:41:51.582  7753  7798 I Babel   : MmsConfig.loadFromResources
08-30 17:41:51.585  7753  7798 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-30 17:41:51.586  7753  7798 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-30 17:41:51.592  7753  7753 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 17:41:51.614  7753  7796 W AudioCapabilities: Unsupported mime audio/evrc
08-30 17:41:51.615  7753  7796 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 17:41:51.617  7753  7796 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-30 17:41:51.624  1816  7800 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-30 17:41:51.624  1816  7800 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-30 17:41:51.629  7066  7066 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 17:41:51.637  7753  7796 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-30 17:41:51.638  7066  7066 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2edf1c8b
08-30 17:41:51.638  7066  7066 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 17:41:51.638  7066  7066 D AppUp4:CustFacade: isPhone : true
08-30 17:41:51.638  7066  7066 D AppUp4:CustModeStarterReceiver: begin check event
08-30 17:41:51.638  7066  7066 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-30 17:41:51.640  1816  4758 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-30 17:41:51.641  7753  7796 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 17:41:51.643  7753  7796 W AudioCapabilities: Unsupported mime audio/evrc
,08-30 17:41:51.659  7753  7796 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-30 17:41:51.664  7753  7796 W VideoCapabilities: Unsupported mime video/divx
08-30 17:41:51.666  7753  7796 W VideoCapabilities: Unsupported mime video/divx311
,08-30 17:41:51.674  7753  7796 W VideoCapabilities: Unsupported mime video/divx4
08-30 17:41:51.680  7753  7796 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-30 17:41:51.685  1034  2032 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7804 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-30 17:41:51.688  1034  2032 I ActivityManager: Killing 7114:com.lge.email/u0a23 (adj 15): empty #17
08-30 17:41:51.711  7753  7796 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-30 17:41:51.718  7753  7796 W AudioCapabilities: Unsupported mime audio/eac3
08-30 17:41:51.719  7753  7796 W AudioCapabilities: Unsupported mime audio/ac3
08-30 17:41:51.720  7753  7796 W AudioCapabilities: Unsupported mime audio/g726
08-30 17:41:51.720  7753  7796 W AudioCapabilities: Unsupported mime audio/wma-voice
08-30 17:41:51.721  7753  7796 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-30 17:41:51.722  7753  7796 W AudioCapabilities: Unsupported mime audio/adpcm
08-30 17:41:51.723  7753  7796 W VideoCapabilities: Unsupported mime video/theora
08-30 17:41:51.725  7753  7796 W VideoCapabilities: Unsupported mime video/mjpg
,08-30 17:41:51.790  1034  1913 W libprocessgroup: failed to open /acct/uid_10023/pid_7114/cgroup.procs: No such file or directory
08-30 17:41:51.820  7804  7804 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:41:51.820  7804  7804 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 17:41:51.821  7804  7804 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 17:41:51.822  7804  7804 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-30 17:41:51.822  7804  7804 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-30 17:41:51.882  7804  7804 I SystemConfig: BUILD Country: EU
08-30 17:41:51.882  7804  7804 I SystemConfig: BUILD Operator: OPEN
,08-30 17:41:51.916  1034  1590 I ActivityManager: Killing 6988:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-30 17:41:52.040  1034  1982 W libprocessgroup: failed to open /acct/uid_10026/pid_6988/cgroup.procs: No such file or directory
,08-30 17:41:52.045  7804  7822 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-30 17:41:52.045  7804  7822 I SystemConfig: existFile = false
08-30 17:41:52.045  7804  7822 I SystemConfig: canReadFile = false
08-30 17:41:52.045  7804  7822 I SystemConfig: systemFeature RCS result false
08-30 17:41:52.045  7804  7822 D SystemConfig: refreshRcsSupport() :false
,08-30 17:41:52.113  1034  2006 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7827 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-30 17:41:52.168  7827  7827 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 17:41:52.169  7827  7827 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 17:41:52.169  7827  7827 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 17:41:52.169  7827  7827 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 17:41:52.248  7827  7827 I AppConfig: Total System Memory = 2995761152
,08-30 17:41:52.255  7827  7827 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-30 17:41:52.331  1034  1785 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7849 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 17:41:52.336  1034  1785 I ActivityManager: Killing 6469:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-30 17:41:52.400  1034  1982 W libprocessgroup: failed to open /acct/uid_1000/pid_6469/cgroup.procs: No such file or directory
,08-30 17:41:52.663  7849  7849 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-30 17:41:52.751  7849  7849 D LgDataFeature: LgDataFeature() Constructor: none
08-30 17:41:52.751  7849  7849 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 17:41:52.807  7849  7849 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-30 17:41:52.829  7849  7849 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 17:41:52.831  7849  7849 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-30 17:41:52.843  1034  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{c3a922f type 2 when 194041 com.google.android.gms} when 194041
,08-30 17:41:52.857  7849  7849 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 17:41:52.857  7849  7849 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-30 17:41:52.878  1034  1590 I ActivityManager: Killing 7150:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-30 17:41:52.933  1034  2015 W libprocessgroup: failed to open /acct/uid_10046/pid_7150/cgroup.procs: No such file or directory
,08-30 17:41:52.939  2850  2962 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-30 17:41:52.941  2850  2962 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2fb2e53f on behalf of 7849
08-30 17:41:52.949  4578  7895 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-30 17:41:53.003  1034  1913 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7896 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-30 17:41:53.052  7849  7849 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-30 17:41:53.102  7849  7849 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-30 17:41:53.111  7896  7896 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-30 17:41:53.132  7896  7896 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-30 17:41:53.132  7896  7896 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,08-30 17:41:53.133  7896  7896 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-30 17:41:53.133  7896  7896 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-30 17:41:53.133  7896  7896 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-30 17:41:53.133  7896  7896 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-30 17:41:53.145   307  7930 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-30 17:41:53.146  1034  1095 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 17:41:53.152  1034  1050 I ActivityManager: Killing 7169:com.android.chrome/u0a57 (adj 15): empty #17
08-30 17:41:53.179  1034  1937 W libprocessgroup: failed to open /acct/uid_10057/pid_7169/cgroup.procs: No such file or directory
,08-30 17:41:53.342  1034  1886 V SIM_STK : Menu title from STK is T-Mobile
,08-30 17:41:53.365  4578  7895 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 416 ms] updated apps [took 416 ms] 
,08-30 17:41:54.101  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:41:54.101  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2a05dae5 added. We now have 6 listener(s)
08-30 17:41:54.101  6777  6843 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:41:54.112  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:41:54.112  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f4e29ba added. We now have 7 listener(s)
08-30 17:41:54.112  6777  6843 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:41:54.113  6777  6843 I System.out: IsBluetoothEnabled
08-30 17:41:54.114  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:54.114  1034  1050 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-30 17:41:54.114  1034  1098 D BluetoothManagerService: Message: 2
08-30 17:41:54.118  6777  6843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:54.119  1034  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:54.119  1034  2015 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-30 17:41:54.136  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 17:41:54.137  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 17:41:54.137  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-30 17:41:54.140  1034  1098 D BluetoothManagerService: Message: 1
08-30 17:41:54.140  1034  1098 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-30 17:41:54.171  1034  1098 D BluetoothManagerService: Message: 20
08-30 17:41:54.171  1034  1098 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3bdd917:true
,08-30 17:41:54.175  7700  7700 D BluetoothAdapterState: make
08-30 17:41:54.179  7700  7700 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 17:41:54.180  7700  7700 I bluedroid-qcom: init
08-30 17:41:54.181  7700  7943 I BluetoothAdapterState: Entering OffState
08-30 17:41:54.181  7700  7700 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 17:41:54.182  7700  7700 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 17:41:54.182  7700  7700 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 17:41:54.182  7700  7700 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 17:41:54.182  7700  7700 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 17:41:54.184  7700  7700 I bluedroid-qcom: get_profile_interface socket
08-30 17:41:54.184  7700  7700 I bluedroid-qcom: get_profile_interface map_client
,08-30 17:41:54.189  7700  7947 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 17:41:54.181  7946  7946 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:41:54.193  7700  7947 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 17:41:54.181  7946  7946 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:41:54.204  7946  7946 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 17:41:54.204  7946  7946 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 17:41:54.204  7946  7946 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-30 17:41:54.208  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-30 17:41:54.208  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 17:41:54.209  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 17:41:54.209  1034  1098 D BluetoothManagerService: Message: 40
08-30 17:41:54.209  1034  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 17:41:54.210  7700  7717 I bluedroid-qcom: config_hci_snoop_log
08-30 17:41:54.211  1034  1098 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 17:41:54.211  1034  1098 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 17:41:54.213  7946  7946 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-30 17:41:54.221  7700  7943 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-30 17:41:54.224  7946  7946 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 17:41:54.224  7946  7946 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-30 17:41:54.226  7700  7947 D BluetoothAdapterProperties: Name is: G3
08-30 17:41:54.226  7700  7943 D BluetoothAdapterProperties: Setting state to 11
08-30 17:41:54.227  7700  7943 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 17:41:54.227  1034  1098 D BluetoothManagerService: Message: 60
08-30 17:41:54.227  1034  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 17:41:54.227  1034  1098 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-30 17:41:54.229  7700  7943 I LGBluetoothServiceJni: classInitNative: succeeds
08-30 17:41:54.236  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:41:54.239  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 17:41:54.241  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:54.244  6878  6878 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-30 17:41:54.264  7700  7700 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 17:41:54.265  7700  7700 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:54.265  7700  7700 V BluetoothPbapReceiver: ***********state = 11
08-30 17:41:54.268  7700  7943 D BluetoothBondStateMachine: make
,08-30 17:41:54.271  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 17:41:54.275  7700  7943 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:54.275  7700  7943 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 17:41:54.275  7700  7943 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:54.275  7700  7943 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-30 17:41:54.276  7700  7943 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-30 17:41:54.277  7700  7961 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 17:41:54.280  7700  7943 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 17:41:54.286  7700  7943 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 17:41:54.287  7700  7700 D HeadsetService: Received start request. Starting profile...
08-30 17:41:54.288  7700  7700 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 17:41:54.288  6878  6878 D BluetoothPermissionRequest: onReceive
08-30 17:41:54.288  7700  7700 D LGBluetoothHfpAdapter: Version 1.6
08-30 17:41:54.290  7700  7700 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 17:41:54.291  7700  7700 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 17:41:54.291  7700  7943 E BluetoothAdapterService: File transfer profiles supported!!
08-30 17:41:54.292  7700  7700 D HeadsetStateMachine: make
08-30 17:41:54.293  6878  6878 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 17:41:54.308  7700  7943 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 17:41:54.312  7700  7943 E BluetoothAdapterService: File transfer profiles supported!!
08-30 17:41:54.317  7700  7943 E BluetoothAdapterService: File transfer profiles supported!!
08-30 17:41:54.320  7700  7700 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 17:41:54.320  7700  7700 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 17:41:54.322  7700  7943 E BluetoothAdapterService: File transfer profiles supported!!
08-30 17:41:54.324  7700  7700 D HeadsetStateMachine: max_hf_connections = 1
08-30 17:41:54.324  7700  7700 I bluedroid-qcom: get_profile_interface handsfree
08-30 17:41:54.326  7700  7700 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-30 17:41:54.326   311  2143 V AudioPolicyService: registerClient() client 0xb0410880, uid 1002
08-30 17:41:54.326   311  2143 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 17:41:54.326   311  2143 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 17:41:54.326   311  2143 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 17:41:54.327  7700  7700 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 17:41:54.327   311  1402 V AudioFlinger: registerClient() client 0xb5581658, pid 7700
08-30 17:41:54.327   311  1396 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 17:41:54.327   311  1396 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 17:41:54.328  1034  1886 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 17:41:54.328  1034  1886 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 17:41:54.328   311  1398 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 17:41:54.328   311  1398 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 17:41:54.328  1603  2094 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 17:41:54.328  1603  2094 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 17:41:54.328  1603  2094 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 17:41:54.328  1603  2094 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 17:41:54.329  1851  2455 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 17:41:54.329  1851  2455 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 17:41:54.329  7700  7716 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 17:41:54.329  1851  2455 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 17:41:54.329  1851  2455 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 17:41:54.329  3443  3459 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 17:41:54.329  3443  3459 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 17:41:54.329  3443  3459 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 17:41:54.329  3443  3459 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 17:41:54.329  7700  7700 V ToneGenerator: Create Track: 0xb4928080
08-30 17:41:54.329  7700  7700 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 17:41:54.329  7700  7700 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 17:41:54.329  7700  7716 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 17:41:54.329  7700  7716 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 17:41:54.329  7700  7716 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 17:41:54.329   311  2142 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 17:41:54.329   311  2142 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 17:41:54.329   311  2142 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 17:41:54.329   311  2142 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 17:41:54.329   311  2143 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 17:,41:54.330   311   311 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 17:41:54.330   311   311 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-30 17:41:54.330   311   311 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 17:41:54.330   311   311 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 17:41:54.330  1034  1937 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 17:41:54.330  1034  1937 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 17:41:54.330  7700  7700 V AudioSystem: getLatency() output 2, latency 50
08-30 17:41:54.330  7700  7700 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 17:41:54.330  7700  7700 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 17:41:54.331   311  1402 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 17:41:54.331   311  1402 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 17:41:54.331   311  1402 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 17:41:54.331   311  1402 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 17:41:54.331   311  1402 V AudioFlinger: createTrack() lSessionId: 21
08-30 17:41:54.332  7700  7700 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 17:41:54.334   311  1402 V AudioFlinger: acquiring 21 from 7700, for 7700
08-30 17:41:54.334   311  1402 V AudioFlinger:  added new entry for 21
08-30 17:41:54.335  7700  7700 V ToneGenerator: ToneGenerator INIT OK, time: 195547
08-30 17:41:54.335  7700  7700 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:54.337  7700  7966 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 17:41:54.337  7700  7966 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 17:41:54.337  7700  7966 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 17:41:54.337  7700  7966 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 17:41:54.338   311  1403 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7700
08-30 17:41:54.338  7700  7700 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:54.338   311  1403 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 17:41:54.338   311  1403 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 17:41:54.338   311  1403 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 17:41:54.338   311  1403 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 17:41:54.338   311  1403 V voice   : voice_set_parameters: exit with code(0)
08-30 17:41:54.339   311  1403 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 17:41:54.339   311  1403 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 17:41:54.339   311  1403 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 17:41:54.339   311  1403 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 17:41:54.339   311  1403 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 17:41:54.339   311  1403 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 17:41:54.339  7700  7966 V ToneGenerator: ToneGenerator destructor
08-30 17:41:54.339  7700  7966 V ToneGenerator: stopTone
08-30 17:41:54.339  7700  7966 V ToneGenerator: Delete Track: 0xb4928080
08-30 17:41:54.339  7700  7966 V AudioTrack: ~AudioTrack, releasing session id from 7700 on behalf of 7700
08-30 17:41:54.339   311  2142 V AudioFlinger: releasing 21 from 7700 for 7700
08-30 17:41:54.339   311  2142 V AudioFlinger:  decremented refcount to 0
08-30 17:41:54.339   311  2142 V AudioFlinger: purging stale effects
08-30 17:41:54.339   311  2142 V AudioPolicyService: AudioCommandThread() adding release output 2
08-30 17:41:54.340   311  2142 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 17:41:54.340   311  1258 V AudioPolicyService: AudioCommandThread() waking up
08-30 17:41:54.340   311  1258 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 17:41:54.340   311  1258 V AudioPolicyManager: releaseOutput() 2
08-30 17:41:54.340   311  1258 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 17:41:54.340   311  2142 V AudioFlinger: PlaybackThread::Track destructor
08-30 17:41:54.340   311  2142 V AudioFlinger: removeClient_l() pid 7700, calling pid 311
08-30 17:41:54.341  7700  7700 D A2dpService: Received start request. Starting profile...
08-30 17:41:54.341  7700  7700 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 17:41:54.342  7700  7700 V Avrcp   : make
08-30 17:41:54.343  7700  7700 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 17:41:54.343  7700  7700 I bluedroid-qcom: get_profile_interface avrcp
08-30 17:41:54.345  7700  7943 V LGMDMManager: Create singleton instance
08-30 17:41:54.346  7700  7943 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 17:41:54.353  7700  7700 V AudioManager: registerRemoteController: size of Media player list: 0
08-30 17:41:54.355  7700  7700 E AudioManager: No RCC entry present to update
08-30 17:41:54.355  7700  7700 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 17:41:54.359  7700  7700 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,08-30 17:41:54.360  7700  7700 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 17:41:54.360  7700  7700 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-30 17:41:54.364  7700  7700 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 17:41:54.455  1034  1974 V SIM_STK : Menu title from STK is T-Mobile
08-30 17:41:54.455  1034  1974 V SIM_STK : Menu title from STK is T-Mobile
,08-30 17:41:54.581  1034  1951 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-30 17:41:54.604  7700  7700 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-30 17:41:54.610  7700  7700 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 17:41:54.611  7700  7700 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 17:41:54.611  7700  7700 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 17:41:54.611  7700  7700 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 17:41:54.612  7700  7700 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 17:41:54.612  7700  7700 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 17:41:54.612  7700  7700 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 17:41:54.612  7700  7700 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 17:41:54.612  7700  7700 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 17:41:54.612  7700  7700 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 17:41:54.613  7700  7700 I BluetoothA2dpServiceJni: classInitNative
08-30 17:41:54.613  7700  7700 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 17:41:54.613  7700  7700 D A2dpStateMachine: make
08-30 17:41:54.616  7700  7700 I bluedroid-qcom: get_profile_interface a2dp
08-30 17:41:54.617  7700  7975 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 17:41:54.620  7700  7700 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 17:41:54.620  7700  7700 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-30 17:41:54.622  7700  7700 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
,08-30 17:41:54.625  7700  7700 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 17:41:54.628  7700  7974 D A2dpStateMachine: Enter Disconnected: -2
08-30 17:41:54.628  7700  7700 D HidService: Received start request. Starting profile...
08-30 17:41:54.628  7700  7700 I bluedroid-qcom: get_profile_interface hidhost
08-30 17:41:54.628  7700  7700 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:54.629  7700  7700 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 17:41:54.631  7700  7700 D HealthService: Received start request. Starting profile...
08-30 17:41:54.635  7700  7700 I bluedroid-qcom: get_profile_interface health
08-30 17:41:54.635  7700  7700 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 17:41:54.635  7700  7700 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:54.636  7700  7700 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 17:41:54.639  7700  7700 D PanService: Received start request. Starting profile...
08-30 17:41:54.639  7700  7700 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 17:41:54.639  7700  7700 I bluedroid-qcom: get_profile_interface pan
08-30 17:41:54.648  7700  7700 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-30 17:41:54.648  7700  7700 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:54.649  7700  7700 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-30 17:41:54.656  7700  7700 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 17:41:54.656  7700  7700 D BtGatt.GattService: Received start request. Starting profile...
08-30 17:41:54.656  7700  7700 D BtGatt.GattService: start()
08-30 17:41:54.656  7700  7700 I bluedroid-qcom: get_profile_interface gatt
08-30 17:41:54.657  7700  7700 D BtGatt.AdvertiseManager: advertise manager created
08-30 17:41:54.666  7700  7700 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:54.667  7700  7700 D HeadsetStateMachine: Proxy object connected
,08-30 17:41:54.668  7700  7700 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 17:41:54.668  7700  7700 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-30 17:41:54.670  7700  7700 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:54.670  7700  7700 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-30 17:41:54.672  7700  7700 V BluetoothMapService: BluetoothMapBinder()
,08-30 17:41:54.673  7700  7700 D BluetoothMapService: Received start request. Starting profile...
08-30 17:41:54.673  7700  7700 D BluetoothMapService: start()
08-30 17:41:54.677  7700  7700 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-30 17:41:54.677  7700  7700 D BluetoothMapEmailAppObserver: createReceiver()
08-30 17:41:54.678  7700  7700 D BluetoothMapEmailAppObserver: initObservers()
08-30 17:41:54.679  7700  7700 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 17:41:54.688  7700  7700 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
,08-30 17:41:54.689  7700  7966 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 17:41:54.690  7700  7966 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 17:41:54.691  7700  7966 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-30 17:41:54.692  7700  7700 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 17:41:54.696  7700  7700 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 17:41:54.698  7700  7700 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:54.702  7700  7700 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 17:41:54.705  7700  7700 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 17:41:54.706  7700  7700 V PanService: [BTUI] SIM Extra State :ABSENT
08-30 17:41:54.709  7700  7700 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 17:41:54.713  7700  7700 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-30 17:41:54.713  7700  7700 V BluetoothMapService: Handler(): got msg=1
08-30 17:41:54.714  7700  7700 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 17:41:54.714  7700  7700 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 17:41:54.714  7700  7700 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 17:41:54.714  7700  7700 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:54.714  7700  7943 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 17:41:54.714  7700  7700 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-30 17:41:54.714  7700  7943 I bluedroid-qcom: enable
08-30 17:41:54.715  7700  7943 I bt_hci_bdroid: init
,08-30 17:41:54.720  7700  7982 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 17:41:54.720  7700  7982 I bt-btu  : btu_task pending for preload complete event
08-30 17:41:54.721  7700  7943 I bt_vendor: bt-vendor : init
08-30 17:41:54.721  7700  7943 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 17:41:54.721  7700  7943 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 17:41:54.721  7700  7943 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 17:41:54.721  7700  7943 D bt_userial_mct: userial_init
08-30 17:41:54.722  7700  7943 D bt_hci_bdroid: set_power 1
08-30 17:41:54.722  7700  7943 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 17:41:54.722  7700  7943 I bt_vendor: Starting hciattach daemon
08-30 17:41:54.722  7700  7943 I bt_vendor: try to set true
08-30 17:41:54.711  7985  7985 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:41:54.711  7985  7985 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 17:41:54.780  7986  7986 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 17:41:54.902  7992  7992 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 17:41:54.919  7993  7993 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 17:41:54.959  7995  7995 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 17:41:54.970  7996  7996 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-30 17:41:54.983  7997  7997 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 17:41:54.995  7998  7998 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-30 17:41:55.018  8000  8000 I libmdmdetect: ESOC framework not supported
08-30 17:41:55.019  8000  8000 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-30 17:41:55.029  8000  8000 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-30 17:41:55.030  8000  8000 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-30 17:41:55.030  8000  8000 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-30 17:41:55.030  8000  8000 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-30 17:41:55.030  8000  8000 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-30 17:41:55.030  8000  8000 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-30 17:41:55.030  8000  8000 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-30 17:41:55.081  8000  8004 E QC-QMI  : qmi_client [8000] 15: failed to locate client data
,08-30 17:41:55.091   493   493 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-30 17:41:55.092   493   493 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-30 17:41:55.126  8008  8008 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 17:41:55.142  8009  8009 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 17:41:55.184  7700  7943 I bt_vendor: bluetooth satus is on
,08-30 17:41:55.185  7700  7943 D bt_hci_bdroid: preload
,08-30 17:41:55.192  7700  7984 D bt_userial_mct: userial_open(port:0)
08-30 17:41:55.192  7700  7984 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-30 17:41:55.197  7700  7984 I bt_vendor: Done intiailizing UART
08-30 17:41:55.202  7700  7984 I bt_vendor: Done intiailizing UART
08-30 17:41:55.202  7700  7984 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 17:41:55.203  7700  7984 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-30 17:41:55.205  7700  7982 I bt-btu  : btu_task received preload complete event
,08-30 17:41:55.205  7700  7982 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-30 17:41:55.206  7700  7982 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-30 17:41:55.208  7700  7982 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-30 17:41:55.210  7700  8011 D bt_userial_mct: Entering userial_read_thread()
08-30 17:41:55.212  7700  7982 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 17:41:55.212  7700  7982 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 17:41:55.212  7700  7982 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 17:41:55.212  7700  7982 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 17:41:55.212  7700  7982 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 17:41:55.212  7700  7982 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 17:41:55.212  7700  7982 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 17:41:55.212  7700  7982 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 17:41:55.212  7700  7982 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-30 17:41:55.212  7700  7982 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 17:41:55.212  7700  7982 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 17:41:55.212  7700  7982 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 17:41:55.212  7700  7982 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 17:41:55.213  7700  7982 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 17:41:55.213  7700  7982 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 17:41:55.213  7700  7982 I         : BTE_InitTraceLevels -- TRC_BTIF
08-30 17:41:55.318  7700  7982 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-30 17:41:55.318  7700  7982 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0203061 
08-30 17:41:55.318  7700  7982 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0203061 
,08-30 17:41:55.363  7700  7947 E bt-btif : Calling BTA_HhEnable
08-30 17:41:55.363  7700  7947 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-30 17:41:55.363  7700  7947 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-30 17:41:55.369  7700  7982 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-30 17:41:55.369  7700  7982 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-30 17:41:55.369  7700  7982 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 17:41:55.370  7700  7982 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 17:41:55.370  7700  7982 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-30 17:41:55.372  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 17:41:55.374  7700  7947 D BluetoothAdapterProperties: Name is: G3
08-30 17:41:55.376  7700  7947 D BluetoothAdapterProperties: Scan Mode:20
08-30 17:41:55.377  7700  7947 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 17:41:55.377  7700  7947 D bt_hci_bdroid: postload
08-30 17:41:55.379  7700  7984 D bt_hci_bdroid: Used up Tx Cmd credits
,08-30 17:41:55.385  7700  7984 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 17:41:55.386  7700  7982 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 17:41:55.387  7700  7947 D bte_conf: Device ID record 1 : primary
08-30 17:41:55.387  7700  7947 D bte_conf:   vendorId            = 00c4
08-30 17:41:55.387  7700  7947 D bte_conf:   vendorIdSource      = 0001
08-30 17:41:55.387  7700  7947 D bte_conf:   product             = 13a1
08-30 17:41:55.387  7700  7947 D bte_conf:   version             = 1000
08-30 17:41:55.387  7700  7947 D bte_conf:   clientExecutableURL = 
08-30 17:41:55.387  7700  7947 D bte_conf:   serviceDescription  = 
08-30 17:41:55.387  7700  7947 D bte_conf:   documentationURL    = 
08-30 17:41:55.387  7700  7947 D bte_conf: bte_load_did_conf no section named DID2.
08-30 17:41:55.390  7700  7984 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 17:41:55.399  7700  7982 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 17:41:55.399  7700  7982 W bt-smp  : Plain text(LSB ~ MSB) = ea 67 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 17:41:55.399  7700  7982 W bt-smp  : Encrypted text(LSB ~ MSB) = 10 b9 4f 61 eb aa c6 76 30 42 27 36 4a 37 49 46 
,08-30 17:41:55.401  7700  7984 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 17:41:55.402  7700  7982 W bt-btm  : Stopping oneshot timer
08-30 17:41:55.402  7700  8011 E bt_mct  : hci lib postload completed
08-30 17:41:55.403  7700  7943 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 17:41:55.403  7700  7943 D BluetoothAdapterProperties: ScanMode =  20
08-30 17:41:55.403  7700  7943 D BluetoothAdapterProperties: State =  11
08-30 17:41:55.403  7700  7943 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 17:41:55.403  7700  7943 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-30 17:41:55.403  7700  7943 D BluetoothAdapterProperties: Setting state to 12
08-30 17:41:55.404  7700  7943 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 17:41:55.405  7700  7947 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 17:41:55.391  8013  8013 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:41:55.401  8013  8013 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:41:55.411  1034  1098 D BluetoothManagerService: Message: 60
08-30 17:41:55.411  1034  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 17:41:55.411  1034  1098 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,08-30 17:41:55.415  7700  7947 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 17:41:55.438  7700  7943 I BluetoothAdapterState: Entering On State
,08-30 17:41:55.450  7700  7982 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 17:41:55.450  7700  7982 W bt-smp  : Plain text(LSB ~ MSB) = 40 e4 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 17:41:55.450  7700  7982 W bt-smp  : Encrypted text(LSB ~ MSB) = 85 4e 37 76 a8 c2 f8 e0 63 3c 75 18 78 57 ca ca 
08-30 17:41:55.450  7700  7982 W bt-btm  : Stopping oneshot timer
08-30 17:41:55.452  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:41:55.452  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:55.452  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:55.452  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:41:55.452  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:41:55.452  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:41:55.452  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:41:55.452  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:41:55.460  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 17:41:55.462  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:41:55.463  7700  7947 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 17:41:55.463  7700  7947 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-30 17:41:55.475  7700  7943 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 17:41:55.475  7700  7943 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 17:41:55.475  7700  7943 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-30 17:41:55.478  7700  7982 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 17:41:55.478  7700  7982 W bt-smp  : Plain text(LSB ~ MSB) = dc e2 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 17:41:55.478  7700  7982 W bt-smp  : Encrypted text(LSB ~ MSB) = e0 a1 12 4a 2f 97 5b e7 15 48 70 e7 22 34 74 c5 
08-30 17:41:55.478  7700  7982 W bt-btm  : Stopping oneshot timer
08-30 17:41:55.479  7700  7943 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-30 17:41:55.480  6878  6894 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 17:41:55.488  7700  7943 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-30 17:41:55.491  6878  6897 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 17:41:55.502  7700  7982 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 17:41:55.502  7700  7982 W bt-smp  : Plain text(LSB ~ MSB) = 0d 8d 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 17:41:55.502  7700  7982 W bt-smp  : Encrypted text(LSB ~ MSB) = 77 e5 cd 54 3c a2 eb 88 be a8 7d fe 51 5d 94 70 
08-30 17:41:55.502  7700  7982 W bt-btm  : Stopping oneshot timer
,08-30 17:41:55.506  6878  6894 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 17:41:55.510  6878  6897 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 17:41:55.523  7700  7982 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 17:41:55.523  7700  7982 W bt-smp  : Plain text(LSB ~ MSB) = b2 71 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 17:41:55.523  7700  7982 W bt-smp  : Encrypted text(LSB ~ MSB) = 24 ed ec d9 b8 af b0 3d de 84 28 c0 fe 51 82 fc 
08-30 17:41:55.523  7700  7982 W bt-btm  : Stopping oneshot timer
,08-30 17:41:55.544  8018  8018 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-30 17:41:55.548  1034  1098 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 17:41:55.549  6878  6878 D BluetoothA2dp: Proxy object connected
08-30 17:41:55.550  6878  6878 D A2dpProfile: Bluetooth service connected
08-30 17:41:55.552  1034  1034 D BluetoothHeadset: Proxy object connected
08-30 17:41:55.553  1034  1098 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 17:41:55.554  6878  6878 D BluetoothInputDevice: Proxy object connected
08-30 17:41:55.554  6878  6897 D BluetoothPan: onBluetoothStateChange on: true
08-30 17:41:55.554  6878  6878 D HidProfile: Bluetooth service connected
08-30 17:41:55.554  6878  6897 D BluetoothPan: onBluetoothStateChange call bindService
08-30 17:41:55.554  1034  1034 D BluetoothA2dp: Proxy object connected
08-30 17:41:55.556  6878  6878 D BluetoothHeadset: Proxy object connected
,08-30 17:41:55.556  6878  6878 D HeadsetProfile: Bluetooth service connected
08-30 17:41:55.558  6878  6878 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 17:41:55.558  6878  6878 D PanProfile: Bluetooth service connected
08-30 17:41:55.558  1851  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 17:41:55.564  1851  1851 D BluetoothHeadset: Proxy object connected
08-30 17:41:55.565  1851  1866 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 17:41:55.566  1851  1851 D BluetoothHeadset: Proxy object connected
08-30 17:41:55.567  1851  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 17:41:55.568  1851  1851 D BluetoothHeadset: Proxy object connected
08-30 17:41:55.568  6878  7386 D BluetoothMap: onBluetoothStateChange: up=true
08-30 17:41:55.570  6878  6878 D BluetoothMap: Proxy object connected
08-30 17:41:55.570  6878  6878 D MapProfile: Bluetooth service connected
08-30 17:41:55.571  6878  6878 D BluetoothMap: getConnectedDevices()
08-30 17:41:55.571  1034  1098 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-30 17:41:55.571  1034  1098 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-30 17:41:55.571  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-30 17:41:55.571  7700  8032 V BluetoothMapService: getConnectedDevices()
,08-30 17:41:55.574  1034  1098 D BluetoothManagerService: Message: 40
08-30 17:41:55.574  1034  1098 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 17:41:55.574  1940  1940 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:55.574  1940  2127 D LGBluetoothAPIService: Message: 1
08-30 17:41:55.574  1940  2127 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-30 17:41:55.574  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 17:41:55.577  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:55.578  1940  2127 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-30 17:41:55.579  7700  7700 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:55.579  7700  7700 D BluetoothMapService: STATE_ON
08-30 17:41:55.580  7700  7700 D LGBluetoothAPIServer: [BTUI] onCreate()
08-30 17:41:55.580  7700  7700 D LGBluetoothAPIServer: [BTUI] onBind()
08-30 17:41:55.582  1940  1940 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-30 17:41:55.582  1940  2127 D LGBluetoothAPIService: Message: 100
08-30 17:41:55.582  1940  2127 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-30 17:41:55.583  6878  6878 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-30 17:41:55.585  6878  6878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 17:41:55.591  6878  6878 D DockEventReceiver: finishStartingService: stopping service
08-30 17:41:55.591  7700  7700 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:55.591  7700  7700 V BluetoothPbapService: Pbap Service onCreate
08-30 17:41:55.591  7700  7700 V BluetoothPbapService: Starting PBAP service
08-30 17:41:55.593  7700  7700 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 17:41:55.593  7700  7700 V BluetoothMapService: Handler(): got msg=1
08-30 17:41:55.594  7700  7700 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 17:41:55.595  7700  7700 V BluetoothPbapService: Pbap Service onBind
,08-30 17:41:55.596  7700  7700 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:55.596  6878  6878 D BluetoothPbap: Proxy object connected
08-30 17:41:55.596  6878  6878 D PbapServerProfile: Bluetooth service connected
08-30 17:41:55.596  7700  7700 V BluetoothPbapService: state: 12
08-30 17:41:55.596  7700  7700 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 17:41:55.596  7700  7700 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:55.596  7700  7700 V BluetoothPbapReceiver: ***********state = 12
08-30 17:41:55.597  7700  8036 D BluetoothMapMasInstance: MAS initSocket()
08-30 17:41:55.597  7700  8036 D BluetoothMapMasInstance:   masId = 00
08-30 17:41:55.597  7700  8036 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 17:41:55.597  7700  8036 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 17:41:55.597  7700  8036 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 17:41:55.598  7700  7700 V BluetoothPbapService: Handler(): got msg=1
08-30 17:41:55.600  7700  7700 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-30 17:41:55.600  1034  1913 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:55.600  2208  2208 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 17:41:55.601  7700  8038 V BluetoothPbapService: Pbap Service initSocket
08-30 17:41:55.601  2208  2208 D c       : Getting all permits...
08-30 17:41:55.601  2208  2208 D a       : Opening database...
08-30 17:41:55.602  1034  1974 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:55.603  7700  8036 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:41:55.603  7700  8038 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:41:55.603  7700  8036 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-30 17:41:55.604  7700  8036 V BluetoothMapMasInstance: Succeed to create listening socket 
08-30 17:41:55.604  7700  8036 D BluetoothMapMasInstance: Accepting socket connection...
08-30 17:41:55.604  7700  7947 D BluetoothAdapterProperties: Scan Mode:21
08-30 17:41:55.604  7700  7947 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-30 17:41:55.605  2208  2208 D a       : Opening database auth.proximity.permit_store...
08-30 17:41:55.606  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:55.606  2208  2208 D a       : Closing database...
08-30 17:41:55.607  7700  8038 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
,08-30 17:41:55.609  7700  8038 V BluetoothPbapService: Succeed to create listening socket 
08-30 17:41:55.609  7700  8038 V BluetoothPbapService: Accepting socket connection...
08-30 17:41:55.616  6878  6878 D BluetoothPermissionRequest: onReceive
08-30 17:41:55.618  6878  6878 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-30 17:41:55.619  6878  6878 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 17:41:55.622  7700  7700 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-30 17:41:55.623  7700  7700 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 17:41:55.628  7700  7700 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-30 17:41:55.643  7700  7700 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-30 17:41:55.643  7700  7700 V BtOppService: onCreate
,08-30 17:41:55.646  7700  7700 V BluetoothOppNotification: send message
08-30 17:41:55.649  7700  7700 V BtOppService: Starting RfcommListener
08-30 17:41:55.652  7700  7700 D BluetoothOppPreference: Dumping Names:  
08-30 17:41:55.652  7700  7700 D BluetoothOppPreference: {}
08-30 17:41:55.652  7700  7700 D BluetoothOppPreference: Dumping Channels:  
08-30 17:41:55.652  7700  7700 D BluetoothOppPreference: {}
08-30 17:41:55.652  7700  7700 V BtOppService: onStartCommand
08-30 17:41:55.654  7700  7700 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:41:55.655  7700  7700 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 17:41:55.658  7700  7700 V BluetoothOppNotification: new notify threadi!
08-30 17:41:55.658  7700  8043 V BtOppService: Deleted complete outbound shares, number =  0
08-30 17:41:55.659  7700  7700 V BluetoothOppNotification: send delay message
08-30 17:41:55.659  7700  8046 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 17:41:55.659  7700  7700 V BtOppService: start RfcommListener
08-30 17:41:55.660  7700  8043 V BtOppService: Deleted complete inbound failed shares, number = 0
08-30 17:41:55.663  7700  8048 V BtOppRfcommListener: Starting RFCOMM listener....
,08-30 17:41:55.663  7700  7700 V BtOppService: RfcommListener started
08-30 17:41:55.664  7700  8047 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 17:41:55.664  7700  8043 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-30 17:41:55.664  1034  1886 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:55.665  7700  8048 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:41:55.665  7700  8046 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 17:41:55.665  7700  8047 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33a8d3c2 on behalf of 
,08-30 17:41:55.665  7700  8043 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@397375d3 on behalf of 
08-30 17:41:55.666  7700  8048 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-30 17:41:55.666  7700  8048 V BtOppRfcommListener: Started RFCOMM listener....
08-30 17:41:55.666  7700  8048 I BtOppRfcommListener: Accept thread started.
08-30 17:41:55.666  7700  8048 V BtOppRfcommListener: Accepting connection...
,08-30 17:41:55.677  7700  7700 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:55.678  7700  7700 V BluetoothFtpService: Ftp Service onCreate
08-30 17:41:55.678  7700  7700 I BluetoothFtpService: Ftp Service onCreate
08-30 17:41:55.678  7700  7700 V BluetoothFtpService: Ftp Service onStartCommand
08-30 17:41:55.678  7700  7700 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:55.678  7700  7700 V BluetoothFtpService: Starting Listening on sockets
08-30 17:41:55.678  7700  8047 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 17:41:55.678  7700  7700 V BtOppService: ContentObserver received notification
08-30 17:41:55.679  7700  7700 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 17:41:55.679  7700  7700 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 17:41:55.679  7700  7700 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 17:41:55.679  7700  7700 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:55.679  7700  7700 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 17:41:55.679  7700  7700 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-30 17:41:55.702  7724  7752 D UEI.SmartControl: Internal timer expired: 1
,08-30 17:41:55.702  7724  7752 D UEI.SmartControl: unbind internal service
,08-30 17:41:55.749  1034  2397 I art     : Explicit concurrent mark sweep GC freed 24938(1228KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.787ms total 80.129ms
08-30 17:41:55.749  7700  8046 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e9e5809 on behalf of 
,08-30 17:41:55.756  7724  7724 D UEI.SmartControl: Service.onUnbind: IControl
08-30 17:41:55.756  7724  7724 D UEI.SmartControl: Service.onDestroy
08-30 17:41:55.756  7724  7724 D UEI.SmartControl: Lock is in USE false
08-30 17:41:55.756  7724  7724 D UEI.SmartControl: unbind internal service
08-30 17:41:55.756  7724  7724 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@7a0f667
08-30 17:41:55.756  7724  7724 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-30 17:41:55.756  7724  7724 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-30 17:41:55.756  7724  7724 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-30 17:41:55.756  7724  7724 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-30 17:41:55.756  7724  7724 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-30 17:41:55.756  7724  7724 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-30 17:41:55.756  7724  7724 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-30 17:41:55.756  7724  7724 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-30 17:41:55.756  7724  7724 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:41:55.757  7724  7724 W System.err: 	at android.os.Looper.loop(Looper.java:135)
,08-30 17:41:55.757  7724  7724 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 17:41:55.757  7724  7724 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:41:55.757  7724  7724 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:41:55.757  7724  7724 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 17:41:55.757  7724  7724 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 17:41:55.757  7724  7724 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@7a0f667
08-30 17:41:55.757  7700  7700 V BtOppService: ContentObserver received notification
08-30 17:41:55.757  7700  7700 V BluetoothFtpService: Handler(): got msg=1
08-30 17:41:55.757  7724  7724 D serial_port: close(fd = 25)
08-30 17:41:55.758  7700  7700 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 17:41:55.758  7700  7700 V BluetoothFtpService: Ftp Service initSocket
08-30 17:41:55.764  1034  1974 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:55.766  7700  7700 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:41:55.767  7700  8046 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 17:41:55.767  7700  8046 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 17:41:55.769  7724  7724 I UEI.SmartControl: Serial port is closed.
08-30 17:41:55.769  7724  7724 I UEI.SmartControl: Serial port is closed.
08-30 17:41:55.769  7724  7724 D UEI.SmartControl: Blaster closed
,08-30 17:41:55.770  7724  7724 D UEI.SmartControl: Shut down QS...
08-30 17:41:55.770  7724  7724 D UEI.SmartControl: Stopping QS lib
08-30 17:41:55.770  7724  7724 D UEI.SmartControl: QS lib stop result = true
08-30 17:41:55.771  7724  7724 D UEI.SmartControl: Stopped QS lib
08-30 17:41:55.772  7724  7724 D UEI.SmartControl: Stopped file observer...
08-30 17:41:55.772  7724  7724 D UEI.SmartControl: QS shutdown complete
08-30 17:41:55.773  7700  8047 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 17:41:55.774  7700  8046 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18346a0e on behalf of 
08-30 17:41:55.775  7700  7700 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=80
08-30 17:41:55.776  7700  7700 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-30 17:41:55.777  7700  8047 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b759c2f on behalf of 
08-30 17:41:55.778  7700  8050 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-30 17:41:55.779  7700  8046 V BluetoothOppNotification: update too frequent, put in queue
08-30 17:41:55.780  7700  8046 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 17:41:55.780  7700  8047 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 17:41:55.782  7700  8047 V BluetoothOppNotification: outbound notification was removed.
08-30 17:41:55.782  7700  8047 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 17:41:55.784  7700  8047 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@204023c on behalf of 
,08-30 17:41:55.785  7700  8047 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 17:41:55.786  7700  8047 V BluetoothOppNotification: inbound notification was removed.
08-30 17:41:55.786  7700  8047 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 17:41:55.787  7700  8047 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@acb6bc5 on behalf of 
08-30 17:41:55.793  7700  7700 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a806981
08-30 17:41:55.793  7700  7700 V BluetoothSapService: Sap Service onCreate
08-30 17:41:55.796  7700  7700 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:41:55.796  7700  7700 V BluetoothSapService: state: 12
08-30 17:41:55.796  7700  7700 V BluetoothSapService: Starting SAP server process
,08-30 17:41:55.791  8051  8051 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 17:41:55.798  7700  7700 V BluetoothSapService: SAP Service startRfcommListenerThread
08-30 17:41:55.791  8051  8051 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:41:55.799  7700  8052 V BluetoothSapService: Sap Service initRfcommSocket
08-30 17:41:55.800  1034  1951 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:55.801  7700  8052 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:41:55.801  7700  8052 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-30 17:41:55.801  7700  8052 V BluetoothSapService: Succeed to create listening socket 
08-30 17:41:55.801  7700  8052 V BluetoothSapService: Accepting socket connection...
08-30 17:41:55.809  8051  8051 V BT_SAP  : Event pipe created
08-30 17:41:55.809  8051  8051 V BT_SAP  : create_server_socket qcom.sap.server
08-30 17:41:55.809  8051  8051 V BT_SAP  : created socket fd 6
,08-30 17:41:56.180  6777  6843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:41:56.180  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:56.180  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:56.180  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:41:56.180  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:41:56.180  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:41:56.180  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:41:56.180  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:41:56.185  6777  6843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:41:56.187  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:41:56.187  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24daa06b added. We now have 8 listener(s)
08-30 17:41:56.187  6777  6843 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:41:56.191  1034  1951 D WifiServiceImplEx: setWifiEnabled: false pid=6777, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 17:41:56.191  1034  1951 D WifiService: setWifiEnabled: false pid=6777, uid=10118
08-30 17:41:56.192  1034  1951 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 17:41:56.196  6777  6843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:41:56.200  1034  1868 D WifiServiceImplEx: setWifiEnabled: true pid=6777, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 17:41:56.201  1034  1868 D WifiService: setWifiEnabled: true pid=6777, uid=10118
08-30 17:41:56.201  1034  1868 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 17:41:56.216  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-30 17:41:56.216  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-30 17:41:56.216  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-30 17:41:56.218  1034  1390 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-30 17:41:56.218  1034  1390 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-30 17:41:56.221  1034  1390 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-30 17:41:56.221  1034  1390 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 17:41:56.221  1034  1390 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
,08-30 17:41:56.221  1034  1390 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010],
08-30 17:41:56.221  1034  1390 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 17:41:56.221  1034  1390 E WifiHW  : unknown target_country: EU , set to default
08-30 17:41:56.221  1034  1390 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-30 17:41:56.221  1034  1390 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 17:41:56.221  1034  1390 I WifiUtil: gEnableBmps=1
08-30 17:41:56.662  7700  7700 V BluetoothOppNotification: new notify threadi!,
08-30 17:41:56.662  7700  7700 V BluetoothOppNotification: send delay message
,08-30 17:41:56.681  7700  8065 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-30 17:41:56.684  7700  8065 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24fbff41 on behalf of 
08-30 17:41:56.684  7700  8065 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 17:41:56.686  7700  8065 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-30 17:41:56.706  7700  8065 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3457ace6 on behalf of 
08-30 17:41:56.706  7700  8065 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-30 17:41:56.726  7700  8065 V BluetoothOppNotification: outbound notification was removed.
08-30 17:41:56.726  7700  8065 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 17:41:56.727  7700  8065 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1fe6e227 on behalf of 
08-30 17:41:56.729  7700  8065 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 17:41:56.730  7700  8065 V BluetoothOppNotification: inbound notification was removed.
08-30 17:41:56.730  7700  8065 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 17:41:56.731  7700  8065 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f605cd4 on behalf of 
08-30 17:41:56.894   307   893 D SoftapController: Softap fwReload - Ok
,08-30 17:41:56.908  1034  1390 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (683ms)
,08-30 17:41:56.929   307   893 D CommandListener: Setting iface cfg
08-30 17:41:56.929   307   893 D CommandListener: Trying to bring down wlan0
,08-30 17:41:56.938   307   893 D CommandListener: Clearing all IP addresses on wlan0
,08-30 17:41:56.983  1034  1098 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 17:41:57.001  1034  1390 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-30 17:41:57.013  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 17:41:57.013  6878  6878 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 17:41:57.013  6878  6878 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 17:41:57.014  6878  6878 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 17:41:57.016  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 17:41:57.020  1034  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 17:41:57.020  1034  1390 E WifiStateMachine: useWiFiOffloading() : false
08-30 17:41:57.020  1034  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-30 17:41:57.025  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-30 17:41:57.011  8085  8085 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:41:57.027  1034  1390 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 17:41:57.027  1034  1390 D WifiMonitor: connecting to supplicant
,08-30 17:41:57.011  8085  8085 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:41:57.027  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 17:41:57.034  6878  6878 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 17:41:57.035  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-30 17:41:57.035  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 17:41:57.035  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 17:41:57.035  6878  6878 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 17:41:57.035  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-30 17:41:57.036  6878  6878 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 17:41:57.037  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-30 17:41:57.039  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:57.056  8085  8085 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-30 17:41:57.080  1034  2015 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8091 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-30 17:41:57.095  8085  8085 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 17:41:57.095  8085  8085 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-30 17:41:57.098  1034  1098 D Tethering: InitialState.processMessage what=4
08-30 17:41:57.098  1034  1098 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 17:41:57.099   342   342 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 362us total 18.746ms
,08-30 17:41:57.115   342   342 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 291us total 15.486ms
08-30 17:41:57.129   342   342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 465us total 13.495ms
,08-30 17:41:57.144  8085  8085 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 17:41:57.173  1034  1886 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8112 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 17:41:57.179  8091  8110 W FormManager: Network not available. Please check & try again.
08-30 17:41:57.180  8091  8111 V FormManager: Network unavailable.
08-30 17:41:57.183  8091  8111 V FormManager: Network unavailable.
08-30 17:41:57.201  8085  8085 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-30 17:41:57.210  1034  1390 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-30 17:41:57.210  1034  1390 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 17:41:57.211  1034  1390 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-30 17:41:57.211  1034  1390 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-30 17:41:57.211  1034  1390 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:41:57.212  1034  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:41:57.212  1034  1390 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:41:57.213  1034  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:41:57.213  1034  1390 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 17:41:57.213  1034  1390 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-30 17:41:57.214  1034  1390 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 17:41:57.214  1034  1390 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
,08-30 17:41:57.215  1034  1390 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-30 17:41:57.215  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:57.215  1034  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 17:41:57.215  1034  1390 E WifiStateMachine: useWiFiOffloading() : false
08-30 17:41:57.215  1034  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 17:41:57.215  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:57.215  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:57.215  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:57.216  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 17:41:57.216  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:57.217  1940  1940 D WfdService: Waiting for WifiP2p enabling
08-30 17:41:57.217  1034  1390 D WifiNative-wlan0: doBoolean: SET update_config 1
08-30 17:41:57.217  1034  1390 D WifiNative-wlan0: SET update_config 1: returned true
08-30 17:41:57.217  1034  1390 D WifiConfigStore: Loading config and enabling all networks 
08-30 17:41:57.217  1034  1390 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 17:41:57.218  1034  1390 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-30 17:41:57.218  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-30 17:41:57.218  1034  1395 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-30 17:41:57.220  8085  8085 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 17:41:57.220  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:41:57.220  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:57.220  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:57.220  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:41:57.220  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:41:57.220  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:41:57.220  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:41:57.220  6777  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:41:57.220  1034  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 17:41:57.220  1034  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 17:41:57.220  1034  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 17:41:57.220  1034  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-30 17:41:57.220  1034  8130 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 17:41:57.220  1034  8130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-30 17:41:57.221  6777  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:41:57.223  1034  1390 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-30 17:41:57.229  1034  1390 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-30 17:41:57.230  1034  1390 E WifiCon,figStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 17:41:57.230  6777  6843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:41:57.230  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:57.230  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:57.230  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:41:57.230  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:41:57.230  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:41:57.230  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:41:57.230  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:41:57.230  1034  1390 D WifiStateMachine: enableVerboseLogging : level 2
08-30 17:41:57.230  1034  1390 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 17:41:57.231  1034  1390 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-30 17:41:57.231  1034  1390 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-30 17:41:57.231  1034  1390 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 17:41:57.231  1034  1390 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 17:41:57.231  1034  1390 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 17:41:57.231  1034  1390 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 17:41:57.232  1034  1390 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-30 17:41:57.232  1034  1390 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-30 17:41:57.232  6777  6843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:41:57.232  1034  1390 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 17:41:57.232  1034  1390 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 17:41:57.232  1034  1390 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 17:41:57.232  1034  1390 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
,08-30 17:41:57.232  1034  1390 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-30 17:41:57.233  7753  7753 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:57.234  1034  1390 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 17:41:57.234  1034  1390 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-30 17:41:57.234  1034  1390 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 17:41:57.234  1034  1390 D WifiNative-HAL: Setting external_sim to 1
08-30 17:41:57.234  1034  1390 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-30 17:41:57.234  1940  1940 D WfdsService: Supplicant Connection state is changed : true
08-30 17:41:57.234  1940  2287 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-30 17:41:57.234  1940  2287 D WfdsService: Set the WFDS Monitor: true
08-30 17:41:57.234  1940  2287 D WfdsMonitor: WfdsMonitorThread create
08-30 17:41:57.235  1940  2287 D WfdsMonitor: WFDS Monitor is created and started
08-30 17:41:57.235  1034  1390 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 17:41:57.235  1034  1390 I WifiNative-HAL: startHal
08-30 17:41:57.235  1940  2287 D WfdsService: WiFi: Supplicant connection re-established
08-30 17:41:57.235  1034  1390 D wifi    : setting scan oui 0xaf710040
08-30 17:41:57.235  1034  1390 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 17:41:57.235  1034  1390 I WifiNative-HAL: startHal
08-30 17:41:57.235  1034  1390 D wifi    : setting scan oui 0xaf710040
08-30 17:41:57.235  1034  1390 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 17:41:57.235  1940  8132 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 17:41:57.236  1034  1390 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 17:41:57.236  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 17:41:57.236  8085  8085 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 17:41:57.236  1940  8132 E CtrlSupplicant: Succeed to open control connection
08-30 17:41:57.236  1034  1390 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 17:41:57.236  1940  8132 E CtrlSupplicant: Succeed to open monitor connection
08-30 17:41:57.236  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 17:41:57.236  8085  8085 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 17:41:57.236  1940  8132 D WfdsMonitor: Supplicant connection established
08-30 17:41:57.237  1034  1390 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 17:41:57.237  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 17:41:57.237  8085  8085 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-30 17:41:57.237  1034  1390 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 17:41:57.237  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 17:41:57.237  6777  6843 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-30 17:41:57.237  8085  8085 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 17:41:57.238  1034  1390 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 17:41:57.238  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 17:41:57.238  1940  2287 D WfdsService: Connected to the supplicant for wfds
08-30 17:41:57.238  8085  8085 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 17:41:57.238  6777  6843 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-30 17:41:57.238  1034  1390 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 17:41:57.238  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 17:41:57.238  8085  8085 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 17:41:57.239  1034  1390 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 17:41:57.239  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER RX,FILTER-START
08-30 17:41:57.239  8085  8085 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 17:41:57.239  1034  1390 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 17:41:57.240  6777  6843 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2cbc2675 Bundle[{}]
08-30 17:41:57.240  1034  1390 E WifiNative: : [198,439,828 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 17:41:57.240  1034  1390 D WifiNative-wlan0: doBoolean: RECONNECT
08-30 17:41:57.241  6777  6843 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 17:41:57.241  1034  1390 D WifiNative-wlan0: RECONNECT: returned true
08-30 17:41:57.241  6777  6843 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-30 17:41:57.241  1034  1390 D WifiNative-wlan0: doString: [STATUS]
,08-30 17:41:57.241  1034  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 17:41:57.241  1034  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 17:41:57.241  1034  1390 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 17:41:57.241  6777  6843 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-30 17:41:57.242  1034  1390 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 17:41:57.242  1034  1390 D WifiNative-wlan0: SET ps 1: returned true
08-30 17:41:57.242  1034  1389 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:57.242  6777  6843 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 17:41:57.243  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 17:41:57.243  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-30 17:41:57.243  1034  1557 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:57.243  1034  1557 I WifiNative-HAL: startHal
08-30 17:41:57.243  1034  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf710040
08-30 17:41:57.243  1034  1557 D wifi    : failed to get capabilities : -3
08-30 17:41:57.243  1034  1558 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:57.243  1034  1557 E WifiScanningService: could not get scan capabilities
08-30 17:41:57.243  6777  6843 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-30 17:41:57.243   307   893 D CommandListener: Setting iface cfg
08-30 17:41:57.243   307   893 D CommandListener: Trying to bring up p2p0
08-30 17:41:57.243  1034  1389 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 17:41:57.243  1034  1389 D LGWifiP2pService: P2pEnablingState
08-30 17:41:57.243  1034  1389 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:57.243  1034  1389 D LGWifiP2pService: P2p socket connection successful
08-30 17:41:57.243  1034  1389 D LGWifiP2pService: P2pEnabledState
08-30 17:41:57.244  1034  1390 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 17:41:57.244  6777  6843 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-30 17:41:57.244  1034  1389 D LGWifiP2pService: sending p2p connection changed broadcast
08-30 17:41:57.244  1034  1390 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 17:41:57.245  1940  1940 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-30 17:41:57.245  1940  1940 D WfdsService: WifiP2pState is changed : true
08-30 17:41:57.245  1940  2287 D WfdsService: Receive the WFDS_ENABLE Method
08-30 17:41:57.245  1940  2287 D WfdsService: Set the WFDS Monitor: true
08-30 17:41:57.245  1940  2287 D WfdsService: Connected to the supplicant for wfds
08-30 17:41:57.245  1940  1940 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 17:41:57.245  1940  2287 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 17:41:57.245  8085  8085 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 17:41:57.246  1034  1389 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 17:41:57.247  1034  1389 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 17:41:57.247  1034  1389 D WifiNative-p2p0: doBoolean: SET device_name G3
08-30 17:41:57.247  1034  1389 D WifiNative-p2p0: SET device_name G3: returned true
08-30 17:41:57.247  1034  1389 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 17:41:57.247  1034  1389 D LGWifiP2pService: before postfix = G3
08-30 17:41:57.247  1034  1389 D WifiServerServiceExt: postfix byte check : 2
08-30 17:41:57.247  1034  1389 D LGWifiP2pService: after postfix = G3
08-30 17,:41:57.247  1034  1389 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 17:41:57.247  1940  2287 D WfdsService: selectPreferredScanChannel [36]
08-30 17:41:57.247  1940  2287 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 17:41:57.247  1034  1389 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 17:41:57.247  1034  1389 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 17:41:57.247  1034  1389 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 17:41:57.247  1034  1389 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-30 17:41:57.247  1034  1389 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 17:41:57.247  1034  1389 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 17:41:57.248  1034  1389 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 17:41:57.248  1034  1389 D WifiNative-HAL: p2pGetDeviceAddress
08-30 17:41:57.248  1034  1389 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-30 17:41:57.249  1034  1389 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-30 17:41:57.249  1034  1389 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-30 17:41:57.249  1034  1389 D WifiNative-p2p0: P2P_FLUSH: returned true
08-30 17:41:57.249  1034  1389 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 17:41:57.250  1034  1389 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-30 17:41:57.250  1034  1389 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 17:41:57.250  1034  1389 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 17:41:57.250  1034  1389 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-30 17:41:57.251  1940  1940 D WfdsService: isConnected: false
08-30 17:41:57.251  1940  1940 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 17:41:57.251  1940  1940 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 17:41:57.251  1940  1940 D WfdsService: Update P2p Interface State: 3
08-30 17:41:57.251  6777  6843 I System.out: Running OutgoingSocketThread
08-30 17:41:57.251  1034  1390 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-30 17:41:57.252  1034  1390 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 17:41:57.252  1034  1390 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 17:41:57.252  6777  8133 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 866)
08-30 17:41:57.253  1034  1390 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 17:41:57.253  1034  1390 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 17:41:57.253  1034  1390 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1,
,08-30 17:41:57.253  6777  8133 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 58365
08-30 17:41:57.254  6777  8133 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-30 17:41:57.258  8085  8085 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-30 17:41:57.258  1034  1389 D WifiNative-p2p0: SAVE_CONFIG: returned true
,08-30 17:41:57.258  1034  1389 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-30 17:41:57.258  1034  1389 D LGWifiP2pService: InactiveState
08-30 17:41:57.258  1034  1389 D LGWifiP2pService: InactiveState{ when=-8ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:57.259  1034  1390 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-30 17:41:57.259  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:57.259  1034  1389 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-30 17:41:57.259  1034  1390 E WifiStateMachine:  ConnectModeState what:132096 -100 0
,08-30 17:41:57.260  8085  8085 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 17:41:57.260  8085  8085 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:41:57.261  8085  8085 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 17:41:57.261  8085  8085 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:41:57.261  8085  8085 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:41:57.261  1940  8132 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 17:41:57.261  1940  8132 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:41:57.261  1940  8132 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:41:57.261  1034  8130 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 17:41:57.261  1034  8130 E WifiMonitor: WifiMonitor:p2p0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:41:57.262  1034  8130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:41:57.262  1034  8130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:41:57.262  1034  8130 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:41:57.262  1034  8130 E WifiMonitor: WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:41:57.262  1034  8130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:41:57.262  1034  8130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:41:57.262  1034  8130 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:41:57.262  1034  8130 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:41:57.262  1034  8130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:41:57.262  1034  8130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:41:57.262  1034  1389 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 17:41:57.262  1034  1389 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:57.262  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:57.262  1034  1389 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:57.262  1034  1389 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:57.262  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:57.262  1034  1389 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:57.262  1034  1389 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:57.262  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:57.262  1034  1389 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:57.262  1034  1389 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:57.262  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:57.26,2  1034  1389 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:57.263  1034  1034 E WifiServerServiceExt: No p2p device connected
08-30 17:41:57.263  1940  2287 W WfdsService: DefaultState - msg [9441285] is not handled
08-30 17:41:57.264  1034  1390 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 17:41:57.264  1034  1390 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-30 17:41:57.264  8085  8085 E wpa_supplicant: disconnect_rssi_lvl: -100
08-30 17:41:57.265  1034  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=198465  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 17:41:57.267  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:57.267  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:41:57.267  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:57.268  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:57.268  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:57.268  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 17:41:57.269  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=198468  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 17:41:57.269  1034  1390 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 17:41:57.269  1034  1390 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 17:41:57.270  1034  1390 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 17:41:57.270  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-30 17:41:57.271  8085  8085 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-30 17:41:57.271  8085  8085 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:41:57.272  8085  8085 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 17:41:57.272  8085  8085 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:41:57.272  1034  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 17:41:57.272  1034  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:41:57.272  1034  8130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:41:57.272  1034  8130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 17:41:57.272  1034  8130 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:41:57.272  1034  8130 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:41:57.272  1034  8130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:41:57.272  1034  8130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:41:57.272  1940  8132 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:41:57.273  8085  8085 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:41:57.273  1940  8132 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:41:57.273  1034  8130 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 17:41:57.273  1034  8130 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:41:57.273  1034  8130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:41:57.273  1034  8130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 17:41:57.274  1034  1390 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-30 17:41:57.274  1034  1389 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:57.274  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:57.274  1034  1390 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 17:41:57.275  1034  1390 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 17:41:57.275  1034  1390 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-30 17:41:57.275  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-30 17:41:57.275  8085  8085 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 17:41:57.275  8085  8085 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 17:41:57.276  1034  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 17:41:57.276  1034  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 17:41:57.276  1034  8130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 17:41:57.276  1034  8130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 17:41:57.276  1034  1390 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 17:41:57.276  1034  1390 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 17:41:57.277  1034  1390 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 17:41:57.277  1034  1390 D WifiNative-wlan0: doBoolean: SCAN
08-30 17:41:57.277  1034  1390 D WifiNative-wlan0: SCAN: returned false
08-30 17:41:57.277  8112  8112 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 17:41:57.278,  1034  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=198478  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 17:41:57.280  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:41:57.282  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=198482  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 17:41:57.283  1034  1390 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 17:41:57.283  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:57.283  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:57.283  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 17:41:57.283  1034  1390 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 17:41:57.284  1034  1390 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 17:41:57.284  1034  1390 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 17:41:57.285  1034  1390 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 17:41:57.286  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:41:57.286  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-30 17:41:57.286  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:41:57.286  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-30 17:41:57.287  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:57.288  1034  1951 I ActivityManager: Killing 7193:com.lge.drmservice/u0a62 (adj 15): empty #17
08-30 17:41:57.288  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:57.288  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:41:57.288  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:57.320  1034  2032 W libprocessgroup: failed to open /acct/uid_10062/pid_7193/cgroup.procs: No such file or directory
,08-30 17:41:57.327  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-30 17:41:57.327  6878  6878 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 17:41:57.327  6878  6878 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 17:41:57.327  6878  6878 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 17:41:57.328  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 17:41:57.328  6878  6878 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 17:41:57.328  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 17:41:57.328  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 17:41:57.328  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
,08-30 17:41:57.328  6878  6878 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 17:41:57.328  6878  6878 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 17:41:57.334  8112  8112 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 17:41:57.336  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:41:57.340  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:57.345  8091  8137 W FormManager: Network not available. Please check & try again.
08-30 17:41:57.351  8091  8138 V FormManager: Network unavailable.
,08-30 17:41:57.354  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 17:41:57.354  4312  4312 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 17:41:57.355  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 17:41:57.360  4312  4312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 17:41:57.363  8091  8138 V FormManager: Network unavailable.
,08-30 17:41:57.368  4312  8139 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 17:41:57.371  4312  8140 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 17:41:57.371  4312  8140 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 17:41:57.415  1034  1937 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8141 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 17:41:57.525  8141  8141 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 17:41:57.526  8141  8141 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-30 17:41:57.534  8141  8141 V [BNRBootReceiver]: Boot Receiver Return
08-30 17:41:57.535  8141  8141 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 17:41:57.596  1034  2015 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8159 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 17:41:57.597  1034  2015 I ActivityManager: Killing 7222:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-30 17:41:57.660  1034  2032 W libprocessgroup: failed to open /acct/uid_10085/pid_7222/cgroup.procs: No such file or directory
,08-30 17:41:57.689  8159  8159 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 17:41:57.723  8159  8159 D PluginManager: init()
,08-30 17:41:57.872  8085  8085 E wpa_supplicant: USIM:  scard_init function
08-30 17:41:57.872  8085  8085 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-30 17:41:57.874  1034  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-30 17:41:57.874  1034  8130 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 17:41:57.874  1034  8130 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-30 17:41:57.874  1034  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: WPS-AP-AVAILABLE 
08-30 17:41:57.874  1034  8130 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-30 17:41:57.874  1034  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-30 17:41:57.874  1034  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-30 17:41:57.875  1034  1390 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 17:41:57.875  1034  1390 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 17:41:57.875  1034  1390 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 17:41:57.876  1034  1390 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 17:41:57.876  1034  1390 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-30 17:41:57.879  1034  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=199078  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 17:41:57.881  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:57.881  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:57.881  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 17:41:57.881  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:57.881  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:41:57.881  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=199081  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 17:41:57.882  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:41:57.882  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-30 17:41:57.887  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 17:41:57.993  1034  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-30 17:41:57.993  8085  8085 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-30 17:41:57.993  1034  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-30 17:41:57.993  1034  8130 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-30 17:41:57.993  1034  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-30 17:41:57.994  1034  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=199193  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 17:41:57.994  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=199194  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 17:41:57.994  1034  1390 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 56 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199194
08-30 17:41:57.994  1034  1390 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 56 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199194
08-30 17:41:57.995  1034  1390 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 56 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199194
08-30 17:41:57.995  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 56 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199195
08-30 17:41:57.995  1034  1390 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 56 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199195
08-30 17:41:57.996  1034  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 17:41:57.996  1034  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 17:41:57.997  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:41:57.997  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-30 17:41:57.998  1034  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=199198  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-30 17:41:58.003  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:58.003  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:58.003  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 17:41:58.003  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:58.003  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:41:58.005  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:58.009  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:58.009  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:58.009  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 17:41:58.010  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=199210  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 17:41:58.011  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:41:58.011  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,08-30 17:41:58.014  8085  8085 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 17:41:58.014  8085  8085 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 17:41:58.018  1034  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 17:41:58.018  1034  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 17:41:58.018  1034  8130 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 17:41:58.018  1034  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 17:41:58.018  1034  8130 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 17:41:58.018  1034  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
,08-30 17:41:58.018  1034  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 17:41:58.018  1034  8130 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 17:41:58.019  1034  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=199218  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 17:41:58.019  1034  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 17:41:58.019  1034  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 17:41:58.019  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=199219  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 17:41:58.019  1034  1390 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=199219
08-30 17:41:58.020  1034  1390 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=199219
08-30 17:41:58.020  1034  1390 D WifiNative-wlan0: doString: [STATUS]
08-30 17:41:58.020  1034  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 17:41:58.020  1034  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 17:41:58.020  1034  1390 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 17:41:58.021  1034  1390 I WifiServiceExtension: setVHTCapabilityType  : false
08-30 17:41:58.023  1034  1098 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 17:41:58.026  1034  1390 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 17:41:58.026  1034  1390 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-30 17:41:58.027  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:58.027  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:41:58.030  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:58.030  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:58.030  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 17:41:58.031  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:58.033  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:58.033  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:41:58.033  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:58.033  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:58.033  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 17:41:58.034  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:58.035  1034  1390 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-30 17:41:58.035  1034  1404 D ConnectivityService: Got NetworkAgent Messenger
08-30 17:41:58.035  1034  1390 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 17:41:58.035  1034  1390 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 17:41:58.035  1034  1404 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 17:41:58.035  1034  1404 D ConnectivityService: NetworkAgent connected
,08-30 17:41:58.035  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:58.035  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:41:58.036  1034  1390 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 17:41:58.036  1034  1390 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 17:41:58.037  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:58.041  1034  1390 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 17:41:58.041  1034  1390 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 17:41:58.041  1034  1390 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 17:41:58.042  1034  1390 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 17:41:58.042  1034  1390 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 17:41:58.045  1034  1390 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 17:41:58.047   307   893 D CommandListener: Setting iface cfg
,08-30 17:41:58.050  1034  1390 E WifiStateMachine: Start Dhcp Watchdog 3
08-30 17:41:58.051  1034  1390 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=199250  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 17:41:58.051  1034  1390 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=199251  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 17:41:58.052  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=199251  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 17:41:58.052  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:41:58.053  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:41:58.053  1034  1390 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:41:58.053  1034  1390 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:41:58.054  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:41:58.054  1034  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 17:41:58.055  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:41:58.055  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-30 17:41:58.055  1034  1390 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=199255  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 17:41:58.056  1034  1390 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=199255  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 17:41:58.056  1034  8180 D DhcpStateMachine: StoppedState
08-30 17:41:58.056  1034  8180 D DhcpStateMachine: StoppedState{ when=-6ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:58.056  1034  8180 D DhcpStateMachine: WaitBeforeStartState
08-30 17:41:58.056  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=199256  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 17:41:58.057  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14097] from screen [on:0 period:-602064471] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 17:41:58.059  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-602064469] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 17:41:58.059  1034  1390 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 17:41:58.064  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 17:41:58.066  1034  1404 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-30 17:41:58.067  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:58.068  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:58.068  1034  1390 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:58.069  1034  1390 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:58.069  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:58.069  1034  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:58.070  1034  1404 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 17:41:58.071  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:41:58.071  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 17:41:58.071  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=103,0,0
08-30 17:41:58.072  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=103,0,0
08-30 17:41:58.072  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-30 17:41:58.072  8085  8085 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-30 17:41:58.074  1034  1390 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-30 17:41:58.074  1034  1390 D WifiNative-wlan0: doBoolean: SET ps 0
08-30 17:41:58.075  1034  1390 D WifiNative-wlan0: SET ps 0: returned true
08-30 17:41:58.075  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 17:41:58.075  8085  8085 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-30 17:41:58.075  1034  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-30 17:41:58.075  1034  1390 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 17:41:58.075  1034  1390 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 17:41:58.075  1034  1390 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 17:41:58.076  1034  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@d73b3bb target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:58.076  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@d73b3bb target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:58.076  1034  8180 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:58.076  1034  8180 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 17:41:58.076   307   893 D CommandListener: Setting iface cfg
08-30 17:41:58.077   307   893 D CommandListener: Trying to bring up wlan0
08-30 17:41:58.077  1034  1390 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
,08-30 17:41:58.079  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 17:41:58.079  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 17:41:58.079  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:58.079  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:58.080  1034  1390 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:58.080  1034  1390 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:58.080  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:58.081  1034  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 17:41:58.082  1034  1404 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 17:41:58.082  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 17:41:58.082  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 17:41:58.082  1034  1389 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:58.082  1034  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:58.082  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 17:41:58.082  8085  8085 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 17:41:58.083  1034  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 17:41:58.083  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 17:41:58.083  8085  8085 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-30 17:41:58.083  1034  1390 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 17:41:58.083  1034  1390 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 17:41:58.102  1034  1390 D WifiNative-wlan0: SET ps 1: returned true
,08-30 17:41:58.102  1034  1404 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,08-30 17:41:58.104  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 17:41:58.105  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 17:41:58.105  1034  1390 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 17:41:58.106  1034  1404 D ConnectivityService: ignoring duplicate network state non-change
08-30 17:41:58.106  8159  8159 W ExternalStrings: load override strings
08-30 17:41:58.106  8159  8159 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-30 17:41:58.106  8159  8159 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-30 17:41:58.106  8159  8159 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-30 17:41:58.106  8159  8159 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-30 17:41:58.106  8159  8159 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-30 17:41:58.106  8159  8159 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-30 17:41:58.106  8159  8159 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-30 17:41:58.106  8159  8159 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-30 17:41:58.106  8159  8159 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-30 17:41:58.106  8159  8159 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-30 17:41:58.106  8159  8159 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-30 17:41:58.106  8159  8159 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:41:58.106  8159  8159 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:41:58.106  8159  8159 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 17:41:58.106  8159  8159 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:41:58.106  8159  8159 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:41:58.106  8159  8159 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 17:41:58.106  8159  8159 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 17:41:58.107  8159  8159 D StatusProvider: onCreate
08-30 17:41:58.108  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:58.108  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:41:58.109  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:58.109  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:58.109  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 17:41:58.110  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:58.110  1034  1404 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 17:41:58.111  1034  1404 D ConnectivityService: Adding iface wlan0 to network 102
08-30 17:41:58.114  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:58.114  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to an,droid.provider.Settings.Global, returning read-only value.
08-30 17:41:58.114  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 17:41:58.115  1034  1390 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 17:41:58.117  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 17:41:58.119  1940  1940 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-30 17:41:58.121  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:58.121  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:58.121  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 17:41:58.122  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 17:41:58.125  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:58.125  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:41:58.125  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 17:41:58.130  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 17:41:58.130  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 17:41:58.131  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:58.134  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:58.134  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 17:41:58.134  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:58.137  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:41:58.137  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 17:41:58.137  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:58.149  1034  1404 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 17:41:58.149  1034  1404 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-30 17:41:58.150  1034  1404 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-30 17:41:58.151   307   893 E Netd    : netlink response contains error (File exists)
08-30 17:41:58.151  1034  1404 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-30 17:41:58.152  1034  1404 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 17:41:58.152  1034  1404 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-30 17:41:58.152  1034  1404 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-30 17:41:58.155  1034  1404 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 17:41:58.156  1034  1404 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 17:41:58.156  1034  1404 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-30 17:41:58.156  1034  1404 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 17:41:58.156  1034  1404 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 17:41:58.156  1034  1404 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:41:58.156  1034  1404 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 17:41:58.156  1034  1404 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:58.156  1034  1404 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 17:41:58.156  1034  1404 D ConnectivityService: currentScore = 0, newScore = 20
08-30 17:41:58.156  1034  1404 D ConnectivityService:    accepting network in place of null
08-30 17:41:58.156  1034  1404 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:58.156  1034  8179 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:58.156  1034  8179 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-30 17:41:58.156  1034  8179 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:41:58.156  1851  1851 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:58.156  1034  8179 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 17:41:58.157  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 17:41:58.157  1034  1390 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:58.157  1034  1390 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 17:41:58.157  1034  1404 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 17:41:58.157  1034  1404 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-30 17:41:58.158  1034  1404 D ConnectivityService: sendStickyBroadcast: ,action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 17:41:58.159   307  8189 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-30 17:41:58.159  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-30 17:41:58.160  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 17:41:58.160  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 17:41:58.160  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 17:41:58.161  1034  1404 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 17:41:58.161  1034  1404 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 17:41:58.161  1034  1404 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-30 17:41:58.167  1034  1404 D ConnectivityService: validation of new default Network = false
08-30 17:41:58.167  1034  1404 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 17:41:58.167  1034  1404 D DSQN    : enableDataServiceNotify 
08-30 17:41:58.167  1034  1404 D DSQN    : start dsqn bin
08-30 17:41:58.170  1034  1388 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-30 17:41:58.176  1034  1404 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 17:41:58.176  1034  1404 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:58.176  1034  1404 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:41:58.176  1034  1404 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:41:58.177  1603  2073 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 17:41:58.161  8190  8190 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:41:58.161  8190  8190 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 17:41:58.187  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 17:41:58.187  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 17:41:58.188  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 17:41:58.196  8159  8159 V Signer  : override build config not found
08-30 17:41:58.196  8190  8190 E DSQN    : DSQN ssw
08-30 17:41:58.196  8159  8159 D Signer  : value of property debug is false
08-30 17:41:58.216   307  8189 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-30 17:41:58.241  8159  8159 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-30 17:41:58.242  8159  8159 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
,08-30 17:41:58.242  8159  8159 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
,08-30 17:41:58.242  8159  8159 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-30 17:41:58.243  8159  8159 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-30 17:41:58.243  8159  8159 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
,08-30 17:41:58.243  8159  8159 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-30 17:41:58.243  8159  8159 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-30 17:41:58.244  8159  8159 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
,08-30 17:41:58.244  8159  8159 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-30 17:41:58.244  8159  8159 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-30 17:41:58.245  8159  8159 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-30 17:41:58.245  8159  8159 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-30 17:41:58.254  6777  6843 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 867)
08-30 17:41:58.254  6777  6843 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 867)
08-30 17:41:58.258  8159  8159 V LGMDMManager: Create singleton instance
,08-30 17:41:58.264  6777  6843 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 872)
08-30 17:41:58.264   307  8189 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-30 17:41:58.266  6777  6843 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-30 17:41:58.266  6777  6843 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 873)
08-30 17:41:58.275  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:41:58.275  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb917c8 added. We now have 2 listener(s)
08-30 17:41:58.276  1034  1590 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 17:41:58.281  1034  8180 D DhcpStateMachine: DHCPV4 request on wlan0
,08-30 17:41:58.282  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 17:41:58.282  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:41:58.282  1034  8180 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-30 17:41:58.282  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:41:58.282  1034  8180 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-30 17:41:58.283  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:41:58.283  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fbe4061 added. We now have 9 listener(s)
08-30 17:41:58.283  6777  6843 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:41:58.284  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 17:41:58.289  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:41:58.281  8195  8195 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:41:58.281  8195  8195 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 17:41:58.292   307   892 D LGDataListener: argv[0]=dsqncommand
08-30 17:41:58.292   307   892 D LGDataListener: argv[1]=wlan0
08-30 17:41:58.292   307   892 D LGDataListener: argv[2]=1
08-30 17:41:58.292   307   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-30 17:41:58.293  1034  1095 D DSQN    : DSQM DsqnNotification wlan0  1
08-30 17:41:58.293  1034  1095 D DSQN    : start to monitor internet connection
,08-30 17:41:58.299  8195  8195 I dhcpcd  : version 5.5.6 starting
08-30 17:41:58.304  8195  8195 E dhcpcd  : get_duid: m
08-30 17:41:58.304  8195  8195 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 17:41:58.305  8195  8195 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-30 17:41:58.307  6777  6843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:41:58.307  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:58.307  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:58.307  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:41:58.307  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:41:58.307  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:58.307  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:41:58.307  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:41:58.310  6777  6843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:58.310  6777  6843 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:41:58.310  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:41:58.311  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b00d847 added. We now have 3 listener(s)
08-30 17:41:58.311  1034  1590 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 17:41:58.312  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:58.313  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:58.314  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 17:41:58.314  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:41:58.314  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:41:58.314  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:41:58.314  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f2be874 added. We now have 10 listener(s)
08-30 17:41:58.314  6777  6843 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:41:58.314  6777  6843 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:58.314  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:58.314  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:58.315  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:58.315  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:58.315  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:41:58.315  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:41:58.315  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb917c8 removed from the list
08-30 17:41:58.315  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:58.315  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fbe4061 removed from the list
08-30 17:41:58.315  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:58.315  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:58.315  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:58.315  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:58.316  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:58.316  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:58.316  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:58.316  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fbe4061 not in the list
08-30 17:41:58.317  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener, does not exist in the list - probably already removed
08-30 17:41:58.317  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:58.317  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:58.317  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:58.317  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:58.317  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f2be874 removed from the list
08-30 17:41:58.317  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:58.317  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:58.317  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:58.317  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:41:58.317  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b00d847 removed from the list
08-30 17:41:58.318  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:41:58.318  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343d819d added. We now have 2 listener(s)
08-30 17:41:58.318  1034  1785 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:58.320  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 17:41:58.320  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:41:58.320  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:41:58.320  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:41:58.320  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@181c3612 added. We now have 9 listener(s)
08-30 17:41:58.320  6777  6843 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:41:58.320  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 17:41:58.321  1034  8179 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 15:41:58 GMT], X-Android-Received-Millis=[1472571718321], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472571718293]}
08-30 17:41:58.322  1034  8179 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 17:41:58.322  1034  8179 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-30 17:41:58.323  1034  1404 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-30 17:41:58.323  1034  1404 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 17:41:58.323  1034  1404 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps Li,nkDnBandwidth>=1048576Kbps]
08-30 17:41:58.323  1034  1404 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:41:58.323  1034  1404 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 17:41:58.323  1034  1404 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-30 17:41:58.323  1034  1404 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 17:41:58.323  1034  1404 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:58.323  1034  1404 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:41:58.323  1034  1404 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:41:58.324  1034  1404 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:58.324  1603  2073 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 17:41:58.324  1034  1404 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-30 17:41:58.324  1034  1390 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:58.325  1034  1390 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 17:41:58.325  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:41:58.325  1851  1851 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:58.325  1851  1851 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 17:41:58.332  6777  6843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:41:58.332  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:58.332  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:58.332  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:41:58.332  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:41:58.332  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:58.332  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:41:58.332  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:41:58.335  6777  6843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:58.335  6777  6843 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:41:58.335  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:41:58.335  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5917e0 added. We now have 3 listener(s)
08-30 17:41:58.336  1034  1913 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:58.337  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:58.338  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:58.343  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 17:41:58.343  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:41:58.343  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:41:58.343  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:41:58.344  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 17:41:58.344  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11759a99 added. We now have 10 listener(s)
08-30 17:41:58.344  6777  6843 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:41:58.344  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:41:58.344  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:41:58.344  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:41:58.344  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:41:58.344  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 17:41:58.346  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:58.347  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 17:41:58.347  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 17:41:58.347  1034  1974 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:58.350  8159  8159 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
08-30 17:41:58.354  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 17:41:58.355  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 17:41:58.357  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:41:58.358  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:41:58.360  6777  6843 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 17:41:58.360  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 17:41:58.361  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:58.362  6777  6843 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:58.362  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:58.362  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:58.362  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:58.362  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:58.362  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:41:58.362  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:41:58.362  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343d819d removed from the list
08-30 17:41:58.362  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:58.362  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@181c3612 removed from the list
08-30 17:41:58.362  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:58.362  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:58.362  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:58.362  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:58.363  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:58.363  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:58.363  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:58.363  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@181c3612 not in the list
08-30 17:41:58.363  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:58.363  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:58.363  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:58.364  6777  6843 D BluetoothLeScanner: could not find callback wrapper
08-30 17:41:58.364  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:41:58.364  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:58.364  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:58.364  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11759a99 removed from the list
08-30 17:41:58.364  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:58.364  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:58.364  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:58.364  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:41:58.364  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5917e0 removed from the list
08-30 17:41:58.364  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:41:58.364  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1967d20c added. We now have 2 listener(s)
08-30 17:41:58.365  1034  1913 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:58.365  8195  8195 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 17:41:58.365  8195  8195 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 17:41:58.365  8195  8195 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 17:41:58.365  8195  8195 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 17:41:58.365  8195  8195 D dhcpcd  : wlan0: sending REQUEST (xid 0xe26053c), next in 4.05 seconds
08-30 17:41:58.366  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 17:41:58.366  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:41:58.366  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:41:58.366  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:41:58.366  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@347c4755 added. We now have 9 listener(s)
08-30 17:41:58.366  6777  6843 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:41:58.366  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 17:41:58.368  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:41:58.371  6777  6843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:41:58.371  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:58.371  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:58.371  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:41:58.371  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:41:58.371  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:58.371  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:41:58.371  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:41:58.372  6777  6843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:58.372  6777  6843 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:41:58.373  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:58.374  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:58.374  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:41:58.374  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b887a5b added. We now have 3 listener(s)
08-30 17:41:58.374  1034  1982 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:58.376  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 17:41:58.376  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:41:58.376  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:41:58.376  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:41:58.376  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bc602f8 added. We now have 10 listener(s)
08-30 17:41:58.376  6777  6843 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:41:58.376  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:41:58.376  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:41:58.376  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:41:58.376  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:41:58.376  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:41:58.376  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 17:41:58.379  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 17:41:58.380  1034  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:58.382  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 17:41:58.382  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 17:41:58.383  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:41:58.383  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:41:58.384  6777  6843 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 17:41:58.384  6777  6843 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:58.384  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:58.384  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:58.384  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:58.385  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:58.385  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:41:58.385  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:41:58.385  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1967d20c removed from the list
08-30 17:41:58.385  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:58.385  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@347c4755 removed from the list
08-30 17:41:58.385  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:58.385  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:58.385  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:58.385  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:58.386  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:58.386  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:58.386  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:58.386  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@347c4755 not in the list
08-30 17:41:58.386  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:58.386  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:58.386  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:58.387  6777  6843 D BluetoothLeScanner: could not find callback wrapper
08-30 17:41:58.387  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:41:58.387  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:58.387  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:58.387  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bc602f8 removed from the list
08-30 17:41:58.387  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:58.387  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:58.387  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:58.387  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:41:58.387  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b887a5b removed from the list
08-30 17:41:58.387  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:41:58.387  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@274a6137 added. We now have 2 listener(s)
08-30 17:41:58.388  1034  1913 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:58.391  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 17:41:58.392  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:41:58.392  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:41:58.392  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:41:58.392  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd456a4 added. We now have 9 listener(s)
08-30 17:41:58.392  6777  6843 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:41:58.392  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 17:41:58.395  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:41:58.397  6777  6843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:41:58.397  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:58.397  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:58.397  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:41:58.397  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:41:58.397  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:58.397  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:41:58.397  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:41:58.398  6777  6843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:58.399  6777  6843 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:41:58.400  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:58.400  8195  8195 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-30 17:41:58.401  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:58.401  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:41:58.401  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da47c2 added. We now have 3 listener(s)
08-30 17:41:58.402  1034  2015 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 17:41:58.403  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 17:41:58.403  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:41:58.403  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:41:58.404  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:41:58.404  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d9d9d3 added. We now have 10 listener(s)
08-30 17:41:58.404  6777  6843 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:41:58.404  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:41:58.404  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:41:58.404  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:41:58.404  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:41:58.404  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 17:41:58.406  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 17:41:58.406  1034  1937 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:58.408  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 17:41:58.409  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 17:41:58.410  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:41:58.410  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:41:58.411  6777  6843 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 17:41:58.412  6777  6843 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:58.412  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:58.412  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:58.412  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:58.412  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:58.412  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:41:58.412  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:41:58.412  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@274a6137 removed from the list
08-30 17:41:58.412  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:58.412  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd456a4 removed from the list
08-30 17:41:58.412  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:58.412  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:58.413  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:58.413  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:58.413  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:58.413  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:58.413  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:58.413  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd456a4 not in the list
08-30 17:41:58.413  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:58.413  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:58.414  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:58.414  6777  6843 D BluetoothLeScanner: could not find callback wrapper
08-30 17:41:58.414  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:41:58.414  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:58.414  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:58.414  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d9d9d3 removed from the list
08-30 17:41:58.414  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:58.414  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:58.415  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:58.415  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:41:58.415  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da47c2 removed from the list
08-30 17:41:58.415  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:41:58.415  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e091e0e added. We now have 2 listener(s)
08-30 17:41:58.415  1034  1785 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:58.417  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 17:41:58.417  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:41:58.417  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:41:58.417  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:41:58.417  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dde402f added. We now have 9 listener(s)
08-30 17:41:58.417  6777  6843 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:41:58.417  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 17:41:58.417  8159  8159 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:41:58.419  8159  8206 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 17:41:58.423  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:41:58.425  6777  6843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:41:58.425  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:41:58.425  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:41:58.425  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:41:58.425  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:41:58.425  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:58.425  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:41:58.425  6777  6843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:41:58.427  6777  6843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:41:58.427  6777  6843 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:41:58.427  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 17:41:58.427  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:41:58.427  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@325eafc5 added. We now have 3 listener(s)
08-30 17:41:58.428  1034  1951 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:41:58.428  8195  8195 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-30 17:41:58.428  8195  8195 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-30 17:41:58.428  8195  8195 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-30 17:41:58.429  8195  8195 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-30 17:41:58.429  8195  8195 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 17:41:58.429  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:58.429  8195  8195 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 17:41:58.429  8195  8195 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 17:41:58.429  8195  8195 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-30 17:41:58.430  6777  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:41:58.430  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 17:41:58.430  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:41:58.430  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:41:58.430  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:41:58.431  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33d0d1a added. We now have 10 listener(s)
08-30 17:41:58.431  6777  6843 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:41:58.431  6777  6843 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:41:58.431  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:41:58.431  6777  6843 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:41:58.431  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:58.431  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:58.431  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:41:58.431  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:41:58.431  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e091e0e removed from the list
08-30 17:41:58.431  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:58.431  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dde402f removed from the list
08-30 17:41:58.431  6777  6843 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:41:58.431  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:58.432  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:58.432  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:58.433  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:58.433  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:58.433  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:58.433  6777  6843 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dde402f not in the list
08-30 17:41:58.433  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener, does not exist in the list - probably already removed
08-30 17:41:58.433  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:58.434  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:41:58.434  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:41:58.434  6777  6843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:41:58.434  6777  6843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33d0d1a removed from the list
08-30 17:41:58.434  6777  6843 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:41:58.434  6777  6843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:41:58.434  6777  6843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:41:58.434  6777  6843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:41:58.434  6777  6843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@325eafc5 removed from the list
08-30 17:41:58.435  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 17:41:58.435  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 17:41:58.435  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 17:41:58.435  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:41:58.435  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 17:41:58.435  6777  6843 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 17:41:58.444  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:58.444  6777  8211 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 880, name: My test thread name)
08-30 17:41:58.445  6777  8211 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 880, thread name: My test thread name)
08-30 17:41:58.445  6777  8211 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 880, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-30 17:41:58.448  6777  8213 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 882, name: My test thread name)
08-30 17:41:58.448  6777  8213 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 882, thread name: My test thread name)
08-30 17:41:58.448  6777  8213 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 882, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-30 17:41:58.450  6777  6843 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-30 17:41:58.450  6777  6843 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-30 17:41:58.450  6777  6843 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-30 17:41:58.450  6777  6843 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-30 17:41:58.450  6777  6843 D com.test.thalitest.ThaliTestRunner: Total duration: 22919 ms
08-30 17:41:58.451  6777  6843 I jxcore-log: *Native tests were executed*
08-30 17:41:58.451  6777  6843 I jxcore-log: 
08-30 17:41:58.451  6777  6843 I jxcore-log: Total number of executed tests:  80
08-30 17:41:58.451  6777  6843 I jxcore-log: 
08-30 17:41:58.451  6777  6843 I jxcore-log: Number of passed tests:  80
08-30 17:41:58.451  6777  6843 I jxcore-log: 
08-30 17:41:58.452  6777  6843 I jxcore-log: Number of failed tests:  0
08-30 17:41:58.452  6777  6843 I jxcore-log: 
08-30 17:41:58.452  6777  6843 I jxcore-log: Number of ignored tests:  0
08-30 17:41:58.452  6777  6843 I jxcore-log: 
08-30 17:41:58.452  6777  6843 I jxcore-log: Total duration:  22919
08-30 17:41:58.452  6777  6843 I jxcore-log: 
08-30 17:41:58.452  6777  6843 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 17:41:58.452  6777  6843 I jxcore-log: 
,08-30 17:41:58.457  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:58.457  6777  6843 I jxcore-log: 
08-30 17:41:58.460  6777  6777 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 17:41:58.468  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:58.468  6777  6843 I jxcore-log: 
08-30 17:41:58.469  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:58.469  6777  6843 I jxcore-log: 
08-30 17:41:58.469  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:58.469  6777  6843 I jxcore-log: 
,08-30 17:41:58.478  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:58.478  6777  6843 I jxcore-log: 
08-30 17:41:58.479  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:58.479  6777  6843 I jxcore-log: 
08-30 17:41:58.480  1034  2032 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8217 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-30 17:41:58.481  1034  2032 I ActivityManager: Killing 7252:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-30 17:41:58.481  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 17:41:58.481  6777  6843 I jxcore-log: 
08-30 17:41:58.483  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 17:41:58.483  6777  6843 I jxcore-log: 
08-30 17:41:58.483  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:41:58.483  6777  6843 I jxcore-log: 
08-30 17:41:58.484  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:41:58.484  6777  6843 I jxcore-log: 
08-30 17:41:58.484  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 17:41:58.484  6777  6843 I jxcore-log: 
08-30 17:41:58.485  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 17:41:58.485  6777  6843 I jxcore-log: 
,08-30 17:41:58.486  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 17:41:58.486  6777  6843 I jxcore-log: 
08-30 17:41:58.486  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:41:58.486  6777  6843 I jxcore-log: 
08-30 17:41:58.487  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:41:58.487  6777  6843 I jxcore-log: 
08-30 17:41:58.487  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:41:58.487  6777  6843 I jxcore-log: 
08-30 17:41:58.489  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:41:58.489  6777  6843 I jxcore-log: 
08-30 17:41:58.489  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:41:58.489  6777  6843 I jxcore-log: 
08-30 17:41:58.490  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:41:58.490  6777  6843 I jxcore-log: 
08-30 17:41:58.490  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:41:58.490  6777  6843 I jxcore-log: 
08-30 17:41:58.491  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:41:58.491  6777  6843 I jxcore-log: 
08-30 17:41:58.492  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:41:58.492  6777  6843 I jxcore-log: 
08-30 17:41:58.492  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:41:58.492  6777  6843 I jxcore-log: 
08-30 17:41:58.493  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:58.493  6777  6843 I jxcore-log: 
08-30 17:41:58.493  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:58.493  6777  6843 I jxcore-log: 
08-30 17:41:58.494  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:58.494  6777  6843 I jxcore-log: 
08-30 17:41:58.495  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:58.495  6777  6843 I jxcore-log: 
08-30 17:41:58.495  6777  6843 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:41:58.495  6777  6843 I jxcore-log: 
08-30 17:41:58.568  8159  8205 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassL,oader());
,08-30 17:41:58.689  1034  8180 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-30 17:41:58.690  1034  8180 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-30 17:41:58.691  1034  8180 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 17:41:58.691  1034  8180 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-30 17:41:58.691  1034  8180 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-30 17:41:58.691  1034  8180 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 17:41:58.691  1034  8180 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-30 17:41:58.691  1034  8180 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-30 17:41:58.691  1034  8180 D DhcpStateMachine: RunningState
08-30 17:41:58.711  8241  8241 D AndroidRuntime: 
08-30 17:41:58.711  8241  8241 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-30 17:41:58.714  8241  8241 D AndroidRuntime: CheckJNI is OFF
08-30 17:41:58.721  1034  1049 W libprocessgroup: failed to open /acct/uid_10093/pid_7252/cgroup.procs: No such file or directory
,08-30 17:41:58.765  8217  8217 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 17:41:58.803  8217  8217 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-30 17:41:58.842  8217  8217 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-30 17:41:58.842  8217  8217 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-30 17:41:58.843  8217  8217 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,08-30 17:41:58.843  8217  8217 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-30 17:41:58.843  8217  8217 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-30 17:41:58.846  8217  8217 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-30 17:41:58.851  8217  8217 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-30 17:41:58.857  8217  8217 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:41:58.860  8159  8205 D LgDataFeature: LgDataFeature() Constructor: none
08-30 17:41:58.860  8159  8205 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 17:41:58.861  8217  8217 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 17:41:58.876  8217  8217 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 17:41:58.878  8159  8159 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:41:58.879  8159  8206 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 17:41:58.879  8217  8217 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-30 17:41:58.883  8217  8217 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-30 17:41:58.888  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 17:41:58.891  8241  8241 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-30 17:41:58.895  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:58.900  1034  1091 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-30 17:41:58.901  8217  8217 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:41:58.901  8217  8217 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:41:58.901  1034  1091 I ActivityManager: Killing 6777:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-30 17:41:58.956  1034  1982 I WindowState: WIN DEATH: Window{38fa64a9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 17:41:58.957  1034  1397 D WifiService: Client connection lost with reason: 4
08-30 17:41:58.964  1034  1982 D InputDispatcher: Window went away: Window{38fa64a9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 17:41:58.973  8159  8205 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-30 17:41:59.121  1034  1091 I ActivityManager:   Force finishing activity ActivityRecord{2424a7da u0 com.test.thalitest/.MainActivity t6}
,08-30 17:41:59.154  1034  1974 W ActivityManager: Spurious death for ProcessRecord{1a216677 6777:com.test.thalitest/u0a118}, curProc for 6777: null
08-30 17:41:59.154   328   338 E GBMv2   : DFP En is all cleared set to be enabled
,08-30 17:41:59.156  1034  1116 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-30 17:41:59.159  8217  8217 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 17:41:59.162  1034  1116 I ActivityManager:   Force finishing activity ActivityRecord{2424a7da u0 com.test.thalitest/.MainActivity t6 f}
08-30 17:41:59.162  1034  1116 W ActivityManager: Duplicate finish request for ActivityRecord{2424a7da u0 com.test.thalitest/.MainActivity t6 f}
,08-30 17:41:59.188  1940  3981 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-30 17:41:59.188  2033  2033 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-30 17:41:59.189  1940  3981 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3f9378f7 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-30 17:41:59.192  1940  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-30 17:41:59.193  1940  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{6aff364 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 17:41:59.193  2033  2033 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-30 17:41:59.196  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-30 17:41:59.205  1034  1380 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 17:41:59.211  2513  2694 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 17:41:59.212  1995  1995 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-30 17:41:59.213  3825  3825 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-30 17:41:59.216  4476  4476 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-30 17:41:59.216  4476  4476 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-30 17:41:59.216  4476  4476 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-30 17:41:59.216  4476  4476 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-30 17:41:59.216  4476  4476 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
,08-30 17:41:59.216  4476  4476 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 17:41:59.216  4476  4476 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:41:59.216  4476  4476 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 17:41:59.216  4476  4476 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:41:59.217  7700  7700 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-30 17:41:59.217  7700  7700 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 17:41:59.216  4476  4476 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:41:59.218  4476  4476 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 17:41:59.218  4476  4476 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-30 17:41:59.229  1034  1390 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 17:41:59.230  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 17:41:59.230  1034  1390 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 17:41:59.231  1034  1390 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 17:41:59.231  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 17:41:59.231  1034  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 17:41:59.232  1034  1404 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-30 17:41:59.232  1034  1404 D ConnectivityService: identical MTU - not setting
08-30 17:41:59.232  1034  1404 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 17:41:59.232  1034  1404 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 17:41:59.232  1034  1404 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 17:41:59.232  1034  1404 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:41:59.233  1034  1404 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 17:41:59.233  1603  2073 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-30 17:41:59.253  1034  1868 V SIM_STK : Menu title from STK is T-Mobile
08-30 17:41:59.254  4578  4578 I art     : Explicit concurrent mark sweep GC freed 8195(469KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 578us total 68.579ms
,08-30 17:41:59.257  1034  1090 W InputMethodInfo: Duplicated subtype definition found: , voice
08-30 17:41:59.299  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-30 17:41:59.302  1034  1034 D administrator: Handling package changes for user 0
08-30 17:41:59.305  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-30 17:41:59.305  2033  2077 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-30 17:41:59.307  8159  8205 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-30 17:41:59.308  6878  6878 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-30 17:41:59.327  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-30 17:41:59.327  1904  1904 D ActionManagerService: notifyUserLog: 1000003
,08-30 17:41:59.336  3825  4468 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-30 17:41:59.338  2033  2033 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-30 17:41:59.339  2033  2033 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-30 17:41:59.340  1603  1665 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 17:41:59.340  1603  1665 D KeyguardModel: createShortcutInfo...
08-30 17:41:59.341  2033  2033 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-30 17:41:59.342  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-30 17:41:59.345  8159  8206 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 17:41:59.346  8159  8159 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:41:59.347  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-30 17:41:59.348  1904  1904 D ActionManagerService: notifyUserLog: 1000004
08-30 17:41:59.348  3825  4468 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-30 17:41:59.349  3825  3840 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 17:41:59.349  1603  1665 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 17:41:59.349  1603  1665 D KeyguardModel: createShortcutInfo...
08-30 17:41:59.351  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-30 17:41:59.351  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262123
08-30 17:41:59.351  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-30 17:41:59.351  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-30 17:41:59.351  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-30 17:41:59.351  2033  2033 I GBoardWebViewUtils: , display: false
08-30 17:41:59.351  2033  2033 I GBoardWebViewUtils: , animation: false }
08-30 17:41:59.351  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-30 17:41:59.351  2033  2033 I GBoardWebViewUtils: , create_time: 1430832262287
08-30 17:41:59.351  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-30 17:41:59.351  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 17:41:59.351  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 17:41:59.351  2033  2033 I GBoardWebViewUtils: , display: false
08-30 17:41:59.351  2033  2033 I GBoardWebViewUtils: , animation: false }
08-30 17:41:59.351  2033  2033 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-30 17:41:59.351  2033  2033 I GBoardWebViewUtils: , create_time: 1472216588858
08-30 17:41:59.351  2033  2033 I GBoardWebViewUtils: , expire_time: 0
08-30 17:41:59.351  2033  2033 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 17:41:59.351  2033  2033 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 17:41:59.351  2033  2033 I GBoardWebViewUtils: , display: false
08-30 17:41:59.351  2033  2033 I GBoardWebViewUtils: , animation: false }
,08-30 17:41:59.355  1603  1665 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 17:41:59.356  1603  1665 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 17:41:59.356  1603  1665 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 17:41:59.359  1603  1665 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 17:41:59.360  8159  8205 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-30 17:41:59.361  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-30 17:41:59.361  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-30 17:41:59.363  1603  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 17:41:59.363  1603  1665 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 17:41:59.364  8159  8205 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-30 17:41:59.365  8159  8205 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-30 17:41:59.366  8159  8205 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-30 17:41:59.366  8159  8205 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
,08-30 17:41:59.374  8159  8205 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-30 17:41:59.380  1603  1665 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 17:41:59.380  1603  1665 D KeyguardModel: createShortcutInfo...
,08-30 17:41:59.383  8159  8205 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-30 17:41:59.385  1603  1665 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 17:41:59.385  1603  1665 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 17:41:59.387  1603  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 17:41:59.387  1603  1665 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 17:41:59.392  1869  1869 D SplitUIManager: split_name #11 / not available #0
08-30 17:41:59.393  1869  1869 D SplitUIService: removed split : 
,08-30 17:41:59.399  1034  2032 V SIM_STK : Menu title from STK is T-Mobile
08-30 17:41:59.399  1034  2032 V SIM_STK : Menu title from STK is T-Mobile
08-30 17:41:59.400  1603  1665 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 17:41:59.400  1603  1665 D KeyguardModel: createShortcutInfo...
08-30 17:41:59.406  1603  1665 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:41:59.406  1603  1665 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 17:41:59.406  1603  1665 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,08-30 17:41:59.406  1603  1665 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 17:41:59.409  1603  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 17:41:59.409  1603  1665 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 17:41:59.415  1603  1665 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 17:41:59.415  1603  1665 D KeyguardModel: createShortcutInfo...
08-30 17:41:59.415  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 17:41:59.418  2033  8285 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-30 17:41:59.421  1034  1937 V SIM_STK : Menu title from STK is T-Mobile
,08-30 17:41:59.424  1869  1869 D SplitUIManager: split_name #11 / not available #0
08-30 17:41:59.424  1869  1869 I SplitUIService: split app #11
08-30 17:41:59.427  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-30 17:41:59.427  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-30 17:41:59.441  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 17:41:59.441  2033  2033 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-30 17:41:59.446  1603  1665 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 17:41:59.446  1603  1665 D KeyguardModel: createShortcutInfo...
,08-30 17:41:59.448  1603  1665 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 17:41:59.448  1603  1665 D KeyguardModel: createShortcutInfo...
,08-30 17:41:59.449  1603  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 17:41:59.449  1603  1665 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 17:41:59.450  1603  1665 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 17:41:59.450  1603  1665 D KeyguardModel: createShortcutInfo...
08-30 17:41:59.452  1603  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 17:41:59.452  1603  1665 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 17:41:59.456  1034  1982 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-30 17:41:59.457  1603  1665 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 17:41:59.457  1603  1665 D KeyguardModel: createShortcutInfo...
08-30 17:41:59.457  7700  7700 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 17:41:59.457  7700  7700 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 17:41:59.457  7700  7700 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 17:41:59.457  7700  7700 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 17:41:59.457  7700  7700 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 17:41:59.457  7700  7700 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 17:41:59.457  7700  7700 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 17:41:59.457  7700  7700 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 17:41:59.457  7700  7700 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 17:41:59.457  7700  7700 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 17:41:59.457  7700  7700 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 17:41:59.458  1603  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 17:41:59.458  1603  1665 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-30 17:41:59.460  1603  1665 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 17:41:59.460  1603  1665 D KeyguardModel: createShortcutInfo...
08-30 17:41:59.467  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:59.470  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-30 17:41:59.470  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 17:41:59.470  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 17:41:59.472  1034  1577 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-30 17:41:59.473  8217  8217 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:41:59.473  8217  8217 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:41:59.473  8217  8217 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 17:41:59.475  8159  8159 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:41:59.475  8159  8206 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 17:41:59.479  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 17:41:59.480  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-30 17:41:59.480  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-30 17:41:59.486  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:59.502  8217  8217 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 17:41:59.506  2033  2033 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-30 17:41:59.510  8217  8217 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:41:59.513  8217  8217 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 17:41:59.515  8159  8159 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:41:59.515  8159  8206 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 17:41:59.519  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:41:59.526  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:59.539  8217  8217 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 17:41:59.539  8217  8217 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:41:59.540  8217  8217 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 17:41:59.541  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 17:41:59.542  6878  6878 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 17:41:59.542  6878  6878 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 17:41:59.542  6878  6878 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 17:41:59.543  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 17:41:59.548  6878  6878 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 17:41:59.548  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-30 17:41:59.548  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 17:41:59.548  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 17:41:59.548  6878  6878 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 17:41:59.548  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-30 17:41:59.549  6878  6878 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 17:41:59.556  8159  8206 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 17:41:59.557  8159  8159 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 17:41:59.561  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 17:41:59.572  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 17:41:59.578  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-30 17:41:59.581  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 17:41:59.582  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-30 17:41:59.583  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-30 17:41:59.584  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-30 17:41:59.585  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-30 17:41:59.586  8217  8217 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:41:59.586  8217  8217 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:41:59.587  8217  8217 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 17:41:59.589  8159  8159 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 17:41:59.600  1034  1099 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{10fd4e8 u0 com.lge.launcher2/.Launcher t5} time:200812
,08-30 17:41:59.604  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-30 17:41:59.604  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 17:41:59.607  2033  2169 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-30 17:41:59.607  2033  2169 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-30 17:41:59.619  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:41:59.622  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:59.622  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-30 17:41:59.623  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 17:41:59.623  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 17:41:59.627  8217  8217 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:41:59.627  8217  8217 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:41:59.627  8217  8217 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 17:41:59.632  8159  8159 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:41:59.632  2033  2033 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-30 17:41:59.636  2594  2594 D [Concierge]Service: onStartCommand(). Type : 8
,08-30 17:41:59.636  2594  2594 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-30 17:41:59.637  2594  2594 D [Concierge]Service: Update widget ID : 11
08-30 17:41:59.639  2033  2033 D [Concierge]WidgetView: change position of spinner
08-30 17:41:59.641  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 17:41:59.641  1034  1116 I art     : Explicit concurrent mark sweep GC freed 83432(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.700ms total 295.143ms
08-30 17:41:59.642  2594  2594 D [Concierge]Service: onStartCommand(). Type : 0
08-30 17:41:59.643  2033  2033 I [Concierge]WidgetView: initWebView(). Time : 1472571719643
,08-30 17:41:59.647  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 17:41:59.652  8217  8217 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:41:59.652  8217  8217 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:41:59.655  8217  8217 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 17:41:59.658  8159  8159 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 17:41:59.668  8241  8241 D AndroidRuntime: Shutting down VM
08-30 17:41:59.696  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:41:59.700  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:59.720  1034  1090 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:41:59.725  1034  1090 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-30 17:41:59.731  1034  1116 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8292 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-30 17:41:59.733  2033  2033 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 258927182
08-30 17:41:59.734  2033  2033 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-30 17:41:59.734  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-30 17:41:59.736  2033  2033 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1316ffce
08-30 17:41:59.736  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-30 17:41:59.737  2033  2033 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 17:41:59.737  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 17:41:59.738  8217  8217 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 17:41:59.740  8217  8217 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:41:59.740  8217  8217 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 17:41:59.743  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-30 17:41:59.743  2033  2033 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-30 17:41:59.743  2033  2033 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 17:41:59.744  2033  2033 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472571546913, New one : 1472571719643
08-30 17:41:59.744  2033  2033 D [Concierge]WidgetView: Unregister all receivers
08-30 17:41:59.744  8159  8159 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:41:59.744  2033  2033 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 17:41:59.746  2033  2033 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-30 17:41:59.748  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 17:41:59.750  8112  8112 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 17:41:59.750  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,08-30 17:41:59.751  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-30 17:41:59.752  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-30 17:41:59.753  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-30 17:41:59.754  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-30 17:41:59.755  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 17:41:59.755  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 17:41:59.763  8112  8112 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 17:41:59.766  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 17:41:59.774  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:59.778  8217  8217 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:41:59.778  8217  8217 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:41:59.779  8217  8217 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 17:41:59.779  8217  8217 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-30 17:41:59.779  8217  8217 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 17:41:59.782  8159  8159 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 17:41:59.785  8112  8112 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 17:41:59.786  8112  8112 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 17:41:59.788  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 17:41:59.791  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 17:41:59.796  2033  2033 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-30 17:41:59.804  2033  2033 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-30 17:41:59.804  2033  2033 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-30 17:41:59.805  2033  2033 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 17:41:59.808  8217  8217 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 17:41:59.808  8217  8217 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 17:41:59.808  8217  8217 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 17:41:59.809  8217  8217 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 17:41:59.809  8217  8217 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 17:41:59.820  8159  8159 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 17:41:59.827  2033  2033 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@150a5e3b time:201039
08-30 17:41:59.829  8217  8217 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 17:41:59.830  8217  8217 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 17:41:59.830  8217  8217 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-30 17:41:59.836  1034  1913 I ActivityManager: Killing 7278:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-30 17:41:59.858  8217  8217 D LgDataFeature: LgDataFeature() Constructor: none
08-30 17:41:59.858  8217  8217 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 17:41:59.863  8217  8217 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-30 17:41:59.863  8217  8217 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-30 17:41:59.863  8217  8217 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-30 17:41:59.863  8217  8217 V SoundPool: doLoad: loading sample sampleID=1
08-30 17:41:59.864  8217  8217 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 17:41:59.865  8217  8312 V SoundPool: Start decode
,08-30 17:41:59.865  8217  8312 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-30 17:41:59.868   311  1402 V MediaPlayerService: decode(23, 10857164, 17813)
08-30 17:41:59.868   311  1402 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-30 17:41:59.868   311  1402 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-30 17:41:59.868   311  1402 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-30 17:41:59.868   311  1402 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-30 17:41:59.868   311  1402 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-30 17:41:59.868   311  1402 V MediaPlayerService: player type = 3
08-30 17:41:59.868   311  1402 V AwesomePlayer: AwesomePlayer create()
08-30 17:41:59.868   311  1402 V AwesomePlayer: reset_l() 
08-30 17:41:59.868   311  1402 V AwesomePlayer: cancelPlayerEvents
08-30 17:41:59.868   311  1402 V AwesomePlayer: setAudioSink() 
08-30 17:41:59.868   311  1402 V AwesomePlayer: reset_l() 
08-30 17:41:59.868   311  1402 V AudioCache: notify(0xb100d200, 8, 0, 0)
08-30 17:41:59.868   311  1402 V AudioCache: ignored
08-30 17:41:59.868   311  1402 V AwesomePlayer: cancelPlayerEvents
08-30 17:41:59.868   311  1402 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-30 17:41:59.869   311  1402 V AwesomePlayer: setDataSource_l dataSource
08-30 17:41:59.869   311  1402 V LGParserOSAL: SniffLGParser start
08-30 17:41:59.869   311  1402 V LGParserOSAL: MainType:5, SubType=0
08-30 17:41:59.869   311  1402 V LGParserOSAL: #### check Mime : application/ogg
08-30 17:41:59.869   311  1402 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-30 17:41:59.869   311  1402 E MediaExtractor: Use LGExtractor :application/ogg 
,08-30 17:41:59.895   311  1402 V LGParserOSAL: supported mime: application/ogg
08-30 17:41:59.895   311  1402 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-30 17:41:59.895   311  1402 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-30 17:41:59.895   311  1402 V AwesomePlayer: mBitrate = -1 bits/sec
08-30 17:41:59.895   311  1402 V AwesomePlayer: AudioTrack Setting
08-30 17:41:59.895   311  1402 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-30 17:41:59.895   311  1402 V AwesomePlayer: setAudioSource() 
08-30 17:41:59.895   311  1402 V MediaPlayerService: prepare
08-30 17:41:59.895   311  1402 V AwesomePlayer: prepareAsync_l() 
08-30 17:41:59.896   311  1402 V MediaPlayerService: wait for prepare
08-30 17:41:59.896   311  8313 V AwesomePlayer: onPrepareAsyncEvent() 
08-30 17:41:59.896   311  8313 V AwesomePlayer: initAudioDecoder() 
08-30 17:41:59.896   311  8313 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 17:41:59.896   311  8313 V AudioSystem: isOffloadSupported()
08-30 17:41:59.896   311  8313 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 17:41:59.896   311  8313 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 17:41:59.896   311  8313 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 17:41:59.896   311  8313 V AwesomePlayer: getUseOffload() = 0 
08-30 17:41:59.896   311  8313 V OMXCodec: OMXCodec::Create
08-30 17:41:59.896   311  8313 V OMXCodec: findMatchingCodecs()
08-30 17:41:59.896   311  8313 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-30 17:41:59.896   311  8313 V OMXCodec: matchingCodecs.size()=1
08-30 17:41:59.896   311  8313 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-30 17:41:59.899   311  8313 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-30 17:41:59.899   311  8313 V LGCodecAdapter: LG Codec Adapter start
,08-30 17:41:59.899   311  8313 V OMXCodec: OMXCodec Createtor
,08-30 17:41:59.899   311  8313 V OMXCodec: setComponentRole
08-30 17:41:59.899   311  8313 V OMXCodec: configureCodec protected=0
08-30 17:41:59.899   311  8313 V LGCodecAdapter: called getLGCodecSpecificData
08-30 17:41:59.899   311  8313 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-30 17:41:59.899   311  8313 V LGCodecOSAL: Called LGconfigureCodecMETA
08-30 17:41:59.899   311  8313 V LGCodecOSAL: Called LGconfigureCodecMSG
08-30 17:41:59.899   311  8313 V LGCodecOSAL: Not support LGCodec
08-30 17:41:59.899   311  8313 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 17:41:59.899   311  8313 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-30 17:41:59.900   311  8313 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-30 17:41:59.900   311  8313 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-30 17:41:59.900   311  8313 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 17:41:59.900   311  8313 V AudioSystem: isOffloadSupported()
08-30 17:41:59.900   311  8313 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 17:41:59.900   311  8313 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 17:41:59.900   311  8313 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-30 17:41:59.900   311  8313 V OMXCodec: init()
08-30 17:41:59.900   311  8313 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-30 17:41:59.900   311  8313 V OMXCodec: allocateBuffers
08-30 17:41:59.900   311  8313 V OMXCodec: allocateBuffersOnPort portIndex=0
08-30 17:41:59.900   311  8313 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-30 17:41:59.900   311  8313 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on input port
08-30 17:41:59.900   311  8313 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7790 on input port
08-30 17:41:59.900   311  8313 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
08-30 17:41:59.900   311  8313 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
08-30 17:41:59.900   311  8313 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 17:41:59.900   311  8313 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 17:41:59.901   311  8313 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on output port
08-30 17:41:59.901   311  8313 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
08-30 17:41:59.901   311  8313 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-30 17:41:59.901   311  8313 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-30 17:41:59.901   311  8313 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 17:41:59.901   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 17:41:59.901   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 17:41:59.901   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-30 17:41:59.901   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-30 17:41:59.901   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-30 17:41:59.901   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-30 17:41:59.901   311  8313 V OMXCodec: init() mAsyncCompletion wait free! 
08-30 17:41:59.901   311  8313 V AwesomePlayer: finishAsyncPrepare_l() 
08-30 17:41:59.901   311  8313 V AudioCache: notify(0xb100d200, 5, 0, 0)
08-30 17:4,1:59.902   311  8313 V AudioCache: ignored
08-30 17:41:59.902   311  8313 V AudioCache: notify(0xb100d200, 1, 0, 0)
08-30 17:41:59.902   311  8313 V AudioCache: prepared
08-30 17:41:59.902   311  1402 V AudioCache: wait - success
08-30 17:41:59.902   311  1402 V MediaPlayerService: start
08-30 17:41:59.902   311  1402 V AwesomePlayer: play_l() 
08-30 17:41:59.902   311  1402 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-30 17:41:59.902   311  1402 V AwesomePlayer: createAudioPlayer_l
08-30 17:41:59.902   311  1402 V AwesomePlayer: seekAudioIfNecessary_l() 
08-30 17:41:59.902   311  1402 V AwesomePlayer: startAudioPlayer_l() 
08-30 17:41:59.902   311  1402 D AudioPlayer: start of Playback, useOffload 0
08-30 17:41:59.902   311  1402 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 17:41:59.902   311  1402 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 17:41:59.903   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-30 17:41:59.903   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-30 17:41:59.903   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-30 17:41:59.903   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-30 17:41:59.903   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-30 17:41:59.903   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 17:41:59.903   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884448
08-30 17:41:59.903   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 17:41:59.903   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884608
08-30 17:41:59.903   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 17:41:59.903   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
08-30 17:41:59.903   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 17:41:59.903   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
08-30 17:41:59.903   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 17:41:59.903   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-30 17:41:59.903   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 17:41:59.903   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-30 17:41:59.903   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-30 17:41:59.903   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-30 17:41:59.903   311  8315 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 17:41:59.903   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 17:41:59.903   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-30 17:41:59.904   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
08-30 17:41:59.904   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on output port
08-30 17:41:59.904   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
08-30 17:41:59.904   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-30 17:41:59.904   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-30 17:41:59.904   311  1402 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-30 17:41:59.904   311  1402 V AudioCache: notify(0xb100d200, 6, 0, 0)
08-30 17:41:59.904   311  1402 V AudioCache: ignored
08-30 17:41:59.905   311  1402 V MediaPlayerService: ,wait for playback complete
08-30 17:41:59.905   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.905   311  8316 V AudioCache: memcpy(0xabf08000, 0xb178a000, 4096)
08-30 17:41:59.906   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.906   311  8316 V AudioCache: memcpy(0xabf09000, 0xb178a000, 4096)
08-30 17:41:59.906   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.906   311  8316 V AudioCache: memcpy(0xabf0a000, 0xb178a000, 4096)
08-30 17:41:59.906   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.906   311  8316 V AudioCache: memcpy(0xabf0b000, 0xb178a000, 4096)
08-30 17:41:59.906   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.906   311  8316 V AudioCache: memcpy(0xabf0c000, 0xb178a000, 4096)
08-30 17:41:59.907   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.907   311  8316 V AudioCache: memcpy(0xabf0d000, 0xb178a000, 4096)
08-30 17:41:59.907   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.907   311  8316 V AudioCache: memcpy(0xabf0e000, 0xb178a000, 4096)
08-30 17:41:59.907   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.907   311  8316 V AudioCache: memcpy(0xabf0f000, 0xb178a000, 4096)
08-30 17:41:59.907   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.907   311  8316 V AudioCache: memcpy(0xabf10000, 0xb178a000, 4096)
08-30 17:41:59.908   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.908   311  8316 V AudioCache: memcpy(0xabf11000, 0xb178a000, 4096)
08-30 17:41:59.908   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.908   311  8316 V AudioCache: memcpy(0xabf12000, 0xb178a000, 4096)
08-30 17:41:59.908  1034  1785 W libprocessgroup: failed to open /acct/uid_10005/pid_7278/cgroup.procs: No such file or directory
08-30 17:41:59.914  7724  7724 D UEI.SmartControl: QS Service created
08-30 17:41:59.916  8217  8217 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-30 17:41:59.908   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.917   311  8316 V AudioCache: memcpy(0xabf13000, 0xb178a000, 4096)
08-30 17:41:59.917   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.917   311  8316 V AudioCache: memcpy(0xabf14000, 0xb178a000, 4096)
08-30 17:41:59.918   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.918   311  8316 V AudioCache: memcpy(0xabf15000, 0xb178a000, 4096)
08-30 17:41:59.918   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.918   311  8316 V AudioCache: memcpy(0xabf16000, 0xb178a000, 4096)
08-30 17:41:59.918   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.918   311  8316 V AudioCache: memcpy(0xabf17000, 0xb178a000, 4096)
08-30 17:41:59.918   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.918   311  8316 V AudioCache: memcpy(0xabf18000, 0xb178a000, 4096)
08-30 17:41:59.918  8217  8217 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 17:41:59.918  8217  8217 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 17:41:59.919   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.919   311  8316 V AudioCache: memcpy(0xabf19000, 0xb178a000, 4096)
08-30 17:41:59.919   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.919   311  8316 V AudioCache: memcpy(0xabf1a000, 0xb178a000, 4096)
08-30 17:41:59.919   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.919   311  8316 V AudioCache: memcpy(0xabf1b000, 0xb178a000, 4096)
08-30 17:41:59.919   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.919   311  8316 V AudioCache: memcpy(0xabf1c000, 0xb178a000, 4096)
08-30 17:41:59.928   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.928   311  8316 V AudioCache: memcpy(0xabf1d000, 0xb178a000, 4096)
08-30 17:41:59.928   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.928   311  8316 V AudioCache: memcpy(0xabf1e000, 0xb178a000, 4096)
08-30 17:41:59.929   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.929   311  8316 V AudioCache: memcpy(0xabf1f000, 0xb178a000, 4096)
08-30 17:41:59.929   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.929   311  8316 V AudioCache: memcpy(0xabf20000, 0xb178a000, 4096)
08-30 17:41:59.929   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.929   311  8316 V AudioCache: memcpy(0xabf21000, 0xb178a000, 4096)
08-30 17:41:59.931   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.931   311  8316 V AudioCache: memcpy(0xabf22000, 0xb178a000, 4096)
08-30 17:41:59.931   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.931   311  8316 V AudioCache: memcpy(0xabf23000, 0xb178a000, 4096)
08-30 17:41:59.931   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.932   311  8316 V AudioCache: memcpy(0xabf24000, 0xb178a000, 4096)
08-30 17:41:59.932   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.932   311  8316 V AudioCache: memcpy(0xabf25000, 0xb178a000, 4096)
08-30 17:41:59.933   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.933   311  8316 V AudioCache: memcpy(0xabf26000, 0xb178a000, 4096)
08-30 17:41:59.934   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.934   311  8316 V AudioCache: memcpy(0xabf27000, 0xb178a000, 4096)
08-30 17:41:59.935   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.935   311  8316 V AudioCache: memcpy(0xabf28000, 0xb178a000, 4096)
08-30 17:41:59.936   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.936   311  8316 V AudioCache: memcpy(0xabf29000, 0xb178a000, 4096)
08-30 17:41:59.936   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.936  8217  8217 V LGMDMManager: Create singleton instance
08-30 17:41:59.936   311  8316 V AudioCache: memcpy(0xabf2a000, 0xb178a000, 4096)
08-30 17:41:59.937   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.937   311  8316 V AudioCache: memcpy(0xabf2b000, 0xb178a000, 4096)
08-30 17:41:59.938  7724  7724 I UEI.SmartControl: Service initServices...
08-30 17:41:59.938  7724  7724 D UEI.SmartControl: QS start get config
08-30 17:41:59.939   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.939   311  8316 V AudioCache: memcpy(0xabf2c000, 0xb178a000, 4096)
08-30 17:41:59.939   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.939   311  8316 V AudioCache: memcpy(0xabf2d000, 0xb178a000, 4096)
08-30 17:41:59.940   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.940   311  8316 V AudioCache: memcpy(0xabf2e000, 0xb178a000, 4096)
08-30 17:41:59.941   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.941   311  8316 V AudioCache: memcpy(0xabf2f000, 0xb178a000, 4096)
08-30 17:41:59.942   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.942   311  8316 V AudioCache: memcpy(0xabf30000, 0xb178a000, 4096)
,08-30 17:41:59.944   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.944   311  8316 V AudioCache: memcpy(0xabf31000, 0xb178a000, 4096)
08-30 17:41:59.945   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.945   311  8316 V AudioCache: memcpy(0xabf32000, 0xb178a000, 4096)
08-30 17:41:59.946   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.946   311  8316 V AudioCache: memcpy(0xabf33000, 0xb178a000, 4096)
08-30 17:41:59.947   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.947   311  8316 V AudioCache: memcpy(0xabf34000, 0xb178a000, 4096)
08-30 17:41:59.947   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.947   311  8316 V AudioCache: memcpy(0xabf35000, 0xb178a000, 4096)
08-30 17:41:59.948   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.948   311  8316 V AudioCache: memcpy(0xabf36000, 0xb178a000, 4096)
08-30 17:41:59.949   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.949   311  8316 V AudioCache: memcpy(0xabf37000, 0xb178a000, 4096)
08-30 17:41:59.949   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.949   311  8316 V AudioCache: memcpy(0xabf38000, 0xb178a000, 4096)
08-30 17:41:59.950   311  8316 V AudioCache: write(0xb178a000, 4096)
08-30 17:41:59.950   311  8316 V AudioCache: memcpy(0xabf39000, 0xb178a000, 4096)
08-30 17:41:59.950   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-30 17:41:59.951   311  8316 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 17:41:59.951   311  8316 V AwesomePlayer: postAudioEOS() 
08-30 17:41:59.951   311  8316 V AudioCache: write(0xb178a000, 280)
08-30 17:41:59.951   311  8316 V AudioCache: memcpy(0xabf3a000, 0xb178a000, 280)
08-30 17:41:59.952   311  8313 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-30 17:41:59.952   311  8313 V AwesomePlayer: onStreamDone
08-30 17:41:59.952   311  8313 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-30 17:41:59.952   311  8313 V AudioCache: notify(0xb100d200, 2, 0, 0)
08-30 17:41:59.952   311  8313 V AudioCache: playback complete
08-30 17:41:59.952   311  8313 V AwesomePlayer: pause_l() 
08-30 17:41:59.952   311  8313 V AudioCache: notify(0xb100d200, 7, 0, 0)
08-30 17:41:59.952   311  8313 V AudioCache: ignored
08-30 17:41:59.952   311  8313 V AwesomePlayer: cancelPlayerEvents
08-30 17:41:59.952   311  8313 D AudioPlayer: Pause Playback at 1068125
08-30 17:41:59.953   311  1402 V AudioCache: wait - success
,08-30 17:41:59.953   311  1402 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-30 17:41:59.953   311  1402 V AwesomePlayer: reset_l() 
08-30 17:41:59.953   311  1402 V AudioCache: notify(0xb100d200, 8, 0, 0)
,08-30 17:41:59.953   311  1402 V AudioCache: ignored
08-30 17:41:59.953   311  1402 V AwesomePlayer: cancelPlayerEvents
08-30 17:41:59.953   311  1402 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-30 17:41:59.953   311  1402 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-30 17:41:59.953   311  1402 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-30 17:41:59.953   311  1402 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-30 17:41:59.953   311  1402 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 17:41:59.953   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
,08-30 17:41:59.953   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 17:41:59.953   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-30 17:41:59.953   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
08-30 17:41:59.954   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-30 17:41:59.954   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
08-30 17:41:59.954   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-30 17:41:59.954   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7790 on port 0
,08-30 17:41:59.954   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-30 17:41:59.954   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 0
08-30 17:41:59.954   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-30 17:41:59.954   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 17:41:59.954   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb00 on port 1
08-30 17:41:59.954   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-30 17:41:59.954   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 1
08-30 17:41:59.954   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-30 17:41:59.954   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 1
08-30 17:41:59.954   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-30 17:41:59.954   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
08-30 17:41:59.954   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 17:41:59.954   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-30 17:41:59.954   311  1402 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 17:41:59.954   311  1402 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
,08-30 17:41:59.957   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-30 17:41:59.957   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-30 17:41:59.957   311  8315 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-30 17:41:59.957   311  1402 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!,
08-30 17:41:59.957   311  1402 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-30 17:41:59.957   311  1402 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-30 17:41:59.958   311  1402 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0,
08-30 17:41:59.958   311  1402 D AudioPlayer: AudioPlayer releasing audio source
08-30 17:41:59.959   311  1402 D AudioPlayer: AudioPlayer done releasing audio source
08-30 17:41:59.959   311  1402 V AwesomePlayer: reset_l() 
08-30 17:41:59.959   311  1402 V AwesomePlayer: cancelPlayerEvents,
08-30 17:41:59.959   311  1402 V AwesomePlayer: ~AwesomePlayer call
08-30 17:41:59.959   311  1402 V AwesomePlayer: reset_l() 
08-30 17:41:59.959   311  1402 V AwesomePlayer: cancelPlayerEvents,
08-30 17:41:59.959  8217  8312 V SoundPool: close(31)
08-30 17:41:59.959  8217  8312 V SoundPool: pointer = 0x9fff5000, size = 205080, sampleRate = 48000, numChannels = 2
08-30 17:41:59.962  2033  2033 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-30 17:42:00.009  8217  8217 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 17:42:00.010  8217  8217 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-30 17:42:00.011  8217  8217 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9983
08-30 17:42:00.013  8159  8159 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 17:42:00.017  8159  8159 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-30 17:42:00.019  1816  1816 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-30 17:42:00.021  7724  7724 E UEI.SmartControl: unzip: java.io.IOException: write failed: EBADF (Bad file number)
08-30 17:42:00.022  7724  7724 I UEI.SmartControl: Specific region DB is not found, use default...
08-30 17:42:00.028  2033  2908 I GBoardtInterface: onReloaded()
,08-30 17:42:00.030  2208  2208 I ConfigService: onCreate
08-30 17:42:00.030  2208  2208 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-30 17:42:00.030  2033  2033 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-30 17:42:00.031  1816  1816 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-30 17:42:00.031  1816  3965 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/data/com.google.android.gms/shared_prefs/config_removals.xml.bak
08-30 17:42:00.032  2208  8319 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/config.db'.
08-30 17:42:00.032  2208  8319 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:42:00.032  2208  8319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:42:00.032  2208  8319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-30 17:42:00.032  2208  8319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-30 17:42:00.032  2208  8319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:42:00.032  2208  8319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:42:00.032  2208  8319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:42:00.032  2208  8319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-30 17:42:00.032  2208  8319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-30 17:42:00.032  2208  8319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-30 17:42:00.032  2208  8319 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-30 17:42:00.032  2208  8319 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-30 17:42:00.032  2208  8319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:42:00.032  2208  8319 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:42:00.032  2208  8319 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:36)
08-30 17:42:00.032  2208  8319 E SQLiteDatabase: 	at com.google.android.gms.config.h.run(SourceFile:121)
08-30 17:42:00.032  2208  8319 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-30 17:42:00.032  2208  8319 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-30 17:42:00.032  2208  8319 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:42:00.032  2208  8319 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:42:00.032  2208  8319 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-30 17:42:00.032  2208  8319 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-30 17:42:00.032  2208  8319 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:42:00.032  2208  8319 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:42:00.032  2208  8319, E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:42:00.032  2208  8319 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-30 17:42:00.032  2208  8319 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-30 17:42:00.032  2208  8319 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-30 17:42:00.032  2208  8319 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-30 17:42:00.032  2208  8319 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-30 17:42:00.032  2208  8319 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:42:00.032  2208  8319 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:42:00.032  2208  8319 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:36)
08-30 17:42:00.032  2208  8319 E SQLiteOpenHelper: 	at com.google.android.gms.config.h.run(SourceFile:121)
08-30 17:42:00.032  2208  8319 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-30 17:42:00.032  3825  3840 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 17:42:00.033  2208  8319 W SQLiteOpenHelper: Opened config.db in read-only mode
08-30 17:42:00.034  2208  2208 I ConfigService: onBind returning update interface
08-30 17:42:00.035  3825  3841 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 17:42:00.036  2208  2208 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-30 17:42:00.036  2208  2208 I ConfigService: onBind returning config service
08-30 17:42:00.039  2208  2208 I ConfigService: onDestroy
08-30 17:42:00.044  1816  8320 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-30 17:42:00.045  1904  1904 D ActionManagerService: notifyUserLog: 1000001
08-30 17:42:00.046  3825  4468 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 17:42:00.046  3825  4468 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-30 17:42:00.047  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-30 17:42:00.047  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
08-30 17:42:00.047  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-30 17:42:00.047  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
08-30 17:42:00.050  1904  1904 D ActionManagerService: notifyUserLog: 1000001
08-30 17:42:00.050  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
08-30 17:42:00.050  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-30 17:42:00.051  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-30 17:42:00.051  3825  3841 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 17:42:00.052  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
08-30 17:42:00.052  7724  7724 E UEI.SmartControl: unzip: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/app_korea/dac1a: open failed: EROFS (Read-only file system)
,08-30 17:42:00.052  7724  7724 I UEI.SmartControl: Supports setup maps: true
08-30 17:42:00.052  7724  7724 W System.err: java.lang.NullPointerException: Attempt to get length of null array
08-30 17:42:00.053  7724  7724 W System.err: 	at com.uei.control.core.ab.b(Unknown Source)
,08-30 17:42:00.053  7724  7724 W System.err: 	at com.uei.control.core.ab.a(Unknown Source)
08-30 17:42:00.053  7724  7724 W System.err: 	at com.uei.control.core.ab.a(Unknown Source)
08-30 17:42:00.053  7724  7724 W System.err: 	at com.uei.control.Service.a(Unknown Source)
08-30 17:42:00.053  7724  7724 W System.err: 	at com.uei.control.Service.onCreate(Unknown Source)
08-30 17:42:00.053  7724  7724 W System.err: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-30 17:42:00.053  7724  7724 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-30 17:42:00.053  7724  7724 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-30 17:42:00.053  7724  7724 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:42:00.053  7724  7724 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:42:00.053  7724  7724 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 17:42:00.053  7724  7724 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:42:00.053  7724  7724 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:42:00.053  7724  7724 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 17:42:00.053  7724  7724 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: java.lang.NullPointerException: Attempt to get length of null array
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at com.uei.control.core.ab.b(Unknown Source)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at com.uei.control.Service.a(Unknown Source)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at com.uei.control.Service.onCreate(Unknown Source)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: java.lang.NullPointerException: Attempt to get length of null array
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at com.uei.control.core.ab.b(Unknown Source)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at com.uei.control.core.ab.a(Unknown Source)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at com.uei.control.Service.a(Unknown Source)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at com.uei.control.Service.onCreate(Unknown Source)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at an,droid.app.ActivityThread.access$1800(ActivityThread.java:148)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 17:42:00.053  7724  7724 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 17:42:00.053  7724  7724 I UEI.SmartControl: ### init IR Blaster...
08-30 17:42:00.054  3825  4468 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 17:42:00.054  3825  4468 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-30 17:42:00.054  3825  4468 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-30 17:42:00.055  3825  4468 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-30 17:42:00.056  2033  2033 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-30 17:42:00.056  2033  2033 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-30 17:42:00.058  7724  7724 D serial_port: Configuring serial port
08-30 17:42:00.058  7724  7724 E UEI.SmartControl: UEIBLaster setting for 616
08-30 17:42:00.058  7724  7724 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 17:42:00.058  7724  7724 I UEI.SmartControl: configuring settings for MAXQ616
08-30 17:42:00.059  7066  7066 E SQLiteLog: (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error
08-30 17:42:00.059  2033  2033 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-30 17:42:00.059  2033  2033 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 17:42:00.061  7066  7066 E SQLiteDatabase: Error inserting package=com.test.thalitest
08-30 17:42:00.061  7066  7066 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 17:42:00.061  7066  7066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-30 17:42:00.061  7066  7066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
08-30 17:42:00.061  7066  7066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
08-30 17:42:00.061  7066  7066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-30 17:42:00.061  7066  7066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
08-30 17:42:00.061  7066  7066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
08-30 17:42:00.061  7066  7066 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
08-30 17:42:00.061  7066  7066 E SQLiteDatabase: 	at android.content.Cont,entProvider$Transport.insert(ContentProvider.java:238)
08-30 17:42:00.061  7066  7066 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
08-30 17:42:00.061  7066  7066 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
08-30 17:42:00.061  7066  7066 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
08-30 17:42:00.061  7066  7066 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
08-30 17:42:00.061  7066  7066 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
08-30 17:42:00.061  7066  7066 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
08-30 17:42:00.061  7066  7066 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
08-30 17:42:00.061  7066  7066 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
08-30 17:42:00.061  7066  7066 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
08-30 17:42:00.061  7066  7066 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:42:00.061  7066  7066 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:42:00.061  7066  7066 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 17:42:00.061  7066  7066 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:42:00.061  7066  7066 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:42:00.061  7066  7066 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 17:42:00.061  7066  7066 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 17:42:00.061  7724  7724 I UEI.SmartControl: Get version...
08-30 17:42:00.062  2033  2033 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-30 17:42:00.062  2033  2033 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 17:42:00.068  2353  2494 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-30 17:42:00.069  2353  2494 D ContactsProvider2ForLG: performBackgroundTask SQLiteDiskIOException during query
08-30 17:42:00.069  2353  2494 D ContactsProvider2ForLG: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 17:42:00.069  2353  2494 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-30 17:42:00.069  2353  2494 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-30 17:42:00.069  2353  2494 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-30 17:42:00.069  2353  2494 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-30 17:42:00.069  2353  2494 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-30 17:42:00.069  2353  2494 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-30 17:42:00.069  2353  2494 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
08-30 17:42:00.069  2353  2494 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
08-30 17:42:00.069  2353  2494 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
08-30 17:42:00.069  2353  2494 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
08-30 17:42:00.069  2353  2494 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
08-30 17:42:00.069  2353  2494 D ContactsProvider2ForLG: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:42:00.069  2353  2494 D ContactsProvider2ForLG: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:42:00.069  2353  2494 D ContactsProvider2ForLG: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:42:00.078  2353  8324 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-30 17:42:00.079  7724  8322 D UEI.SmartControl: serial port data available: 21
08-30 17:42:00.084  2353  8324 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
08-30 17:42:00.085  2353  8324 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-30 17:42:00.085  2353  8324 E AndroidRuntime: Process: android.process.acore, PID: 2353
08-30 17:42:00.085  2353  8324 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 17:42:00.085  2353  8324 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 17:42:00.085  2353  8324 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-30 17:42:00.085  2353  8324 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-30 17:42:00.085  2353  8324 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 17:42:00.085  2353  8324 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-30 17:42:00.085  2353  8324 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
08-30 17:42:00.085  2353  8324 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
08-30 17:42:00.085  2353  8324 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
08-30 17:42:00.085  2353  8324 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-30 17:42:00.085  2353  8324 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-30 17:42:00.085  2353  8324 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 17:42:00.085  2353  8324 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 17:42:00.085  2353  8324 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 17:42:00.085  2353  8324 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:42:00.085  2353  8324 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:42:00.085  2353  8324 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:42:00.098  1034  1886 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8325 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 17:42:00.105  7724  7724 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-30 17:42:00.106  7724  7724 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 17:42:00.106  7724  7724 I UEI.SmartControl: QS saving settings...
08-30 17:42:00.107  7724  7724 W FileUtils: Failed to chmod(/data/data/com.uei.lg.quicksetsdk.maxq616/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
08-30 17:42:00.107  7724  7724 W System.err: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/files/Settings: open failed: EROFS (Read-only file system)
08-30 17:42:00.107  7724  7724 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:42:00.107  7724  7724 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:42:00.107  7724  7724 W System.err: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1047)
08-30 17:42:00.108  7724  7724 W System.err: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
08-30 17:42:00.108  7724  7724 W System.err: 	at com.uei.control.core.QSApp.m(Unknown Source)
08-30 17:42:00.108  7724  7724 W System.err: 	at com.uei.control.core.QSApp.b(Unknown Source)
08-30 17:42:00.108  7724  7724 W System.err: 	at com.uei.control.core.a.a(Unknown Source)
08-30 17:42:00.108  7724  7724 W System.err: 	at com.uei.control.core.a.<init>(Unknown Source)
08-30 17:42:00.108  7724  7724 W System.err: 	at com.uei.control.Service.a(Unknown Source)
08-30 17:42:00.108  7724  7724 W System.err: 	at com.uei.control.Service.onCreate(Unknown Source)
08-30 17:42:00.108  7724  7724 W System.err: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-30 17:42:00.108  7724  7724 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-30 17:42:00.108  7724  7724 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-30 17:42:00.108  7724  7724 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:42:00.108  7724  7724 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:42:00.108  7724  7724 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 17:42:00.108  7724  7724 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:42:00.108  7724  7724 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:42:00.108  7724  7724 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 17:42:00.108  7724  7724 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 17:42:00.108  7724  7724 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:42:00.109  7724  7724 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 17:42:00.109  7724  7724 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:42:00.109  2353  8324 I Process : Sending signal. PID: 2353 SIG: 9
08-30 17:42:00.109  7724  7724 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:42:00.112  7724  7724 W System.err: 	... 19 more
08-30 17:42:00.112  1034  8339 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:42:00.112  1034  8339 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-30 17:42:00.112  1034  8339 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:42:00.112  1034  8339 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:42:00.112  1034  8339 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:42:00.112  1034  8339 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:42:00.112  1034  8339 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-30 17:42:00.112  1034  8339 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-30 17:42:00.112  1034  8339 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:42:00.112  1034  8339 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:42:00.112  1034  8339 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:42:00.112  1034  8339 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:42:00.112  1034  8339 E DropBoxManagerService: 	... 5 more
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/files/Settings: open failed: EROFS (Read-only file system)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1047)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at com.uei.control.core.QSApp.m(Unknown Source)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at com.uei.control.core.QSApp.b(Unknown Source)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at com.uei.control.core.a.a(Unknown Source)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at com.uei.control.core.a.<init>(Unknown Source)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at com.uei.control.Service.a(Unknown Source)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at com.uei.control.Service.onCreate(Unknown Source)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at libcore.io.Posix.open(Native Method)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	... 19 more
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/files/Settings: open failed: EROFS (Read-only file system)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1047)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at com.uei.control.core.QSApp.m(Unknown Source)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at com.uei.control.core.QSApp.b(Unknown Source)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at com.uei.control.core.a.a(Unknown Source)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at com.uei.control.core.a.<init>(Unknown Source)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at com.uei.control.Service.a(Unknown Source)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at com.uei.control.Service.onCreate(Unknown Source)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at libcore.io.Posix.open(Native Method)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:42:00.113  7724  7724 E UEI.SmartControl: 	... 19 more
08-30 17:42:00.113  7724  7724 D UEI.SmartControl: IR Blaster version: 25672567
08-30 17:42:00.115  5940  8345 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-30 17:42:00.118  1816  8343 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
08-30 17:42:00.118  1816  8343 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:42:00.118  1816  8343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:42:00.118  1816  8343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-30 17:42:00.118  1816  8343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-30 17:42:00.118  1816  8343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:42:00.118  1816  8343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:42:00.118  1816  8343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:42:00.118  1816  8343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-30 17:42:00.118  1816  8343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-30 17:42:00.118  1816  8343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-30 17:42:00.118  1816  8343 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-30 17:42:00.118  1816  8343 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-30 17:42:00.118  1816  8343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:42:00.118  1816  8343 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:42:00.118  1816  8343 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.d.e.e(SourceFile:98)
08-30 17:42:00.118  1816  8343 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:212)
08-30 17:42:00.118  1816  8343 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
08-30 17:42:00.118  1816  8343 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 17:42:00.118  1816  8343 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:42:00.118  1816  8343 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:42:00.118  1816  8343 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:42:00.119  1816  8343 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
08-30 17:42:00.119  1816  8343 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:42:00.119  1816  8343 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:42:00.119  1816  8343 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-30 17:42:00.119  1816  8343 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-30 17:42:00.119  1816  8343 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:42:00.119  1816  8343 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:42:00.119  1816  8343 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:42:00.119  1816  8343 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-30 17:42:00.119  1816  8343 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-30 17:42:00.119  1816  8343 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-30 17:42:00.119  1816  8343 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-30 17:42:00.119  1816  8343 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-30 17:42:00.119  1816  8343 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:42:00.119  1816  8343 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 17:42:00.119  1816  8343 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.d.e.e(SourceFile:98)
08-30 17:42:00.119  1816  8343 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:212)
08-30 17:42:00.119  1816  8343 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
08-30 17:42:00.119  1816  8343 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 17:42:00.119  1816  8343 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:42:00.119  1816  8343 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:42:00.119  1816  8343 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 17:42:00.122  1816  8347 I PeopleContactsSync: CP2 sync disabled
08-30 17:42:00.124  1816  4758 I Icing   : doRemovePackageData com.test.thalitest
08-30 17:42:00.132  1816  8344 W GmsApplication: Using Auth Proxy for data requests.
08-30 17:42:00.134  1816  8343 W SQLiteOpenHelper: Opened metrics.db in read-only mode
08-30 17:42:00.135  1816  8343 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
08-30 17:42:00.135  1816  8343 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
08-30 17:42:00.135  1816  8343 E AndroidRuntime: Process: com.google.android.gms, PID: 1816
08-30 17:42:00.135  1816  8343 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-30 17:42:00.135  1816  8343 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 17:42:00.135  1816  8343 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-30 17:42:00.135  1816  8343 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-30 17:42:00.135  1816  8343 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 17:42:00.135  1816  8343 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-30 17:42:00.135  1816  8343 E AndroidRuntime: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:215)
08-30 17:42:00.135  1816  8343 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
08-30 17:42:00.135  1816  8343 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 17:42:00.135  1816  8343 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:42:00.135  1816  8343 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:42:00.135  1816  8343 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 17:42:00.138  1816  8343 I Process : Sending signal. PID: 1816 SIG: 9
08-30 17:42:00.138  7724  8322 D UEI.SmartControl: serial port data available: 4
08-30 17:42:00.141  1034  8350 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:42:00.141  1034  8350 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-30 17:42:00.141  1034  8350 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:42:00.141  1034  8350 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:42:00.141  1034  8350 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:42:00.141  1034  8350 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:42:00.141  1034  8350 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-30 17:42:00.141  1034  8350 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-30 17:42:00.141  1034  8350 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:42:00.141  1034  8350 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:42:00.141  1034  8350 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:42:00.141  1034  8350 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:42:00.141  1034  8350 E DropBoxManagerService: 	... 5 more
08-30 17:42:00.160  8325  8325 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:42:00.160  8325  8325 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 17:42:00.161  8325  8325 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 17:42:00.161  8325  8325 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 17:42:00.165  7724  8353 I UEI.SmartControl: Device manager: loading config....
08-30 17:42:00.166  7724  7724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 17:42:00.167  7724  8353 D UEI.SmartControl: ----------- loading internal config...
08-30 17:42:00.169  7724  8353 E UEI.SmartControl: Loading SETTINGS...
08-30 17:42:00.170  7724  8353 W FileUtils: Failed to chmod(/data/data/com.uei.lg.quicksetsdk.maxq616/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
08-30 17:42:00.170  7724  8353 W System.err: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/files/data: open failed: EROFS (Read-only file system)
08-30 17:42:00.170  7724  8353 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:42:00.170  7724  8353 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:42:00.170  7724  8353 W System.err: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1047)
08-30 17:42:00.170  7724  8353 W System.err: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
08-30 17:42:00.170  7724  8353 W System.err: 	at com.uei.control.core.f.e(Unknown Source)
08-30 17:42:00.170  7724  8353 W System.err: 	at com.uei.control.core.f.l(Unknown Source)
08-30 17:42:00.170  7724  8353 W System.err: 	at com.uei.control.core.f.c(Unknown Source)
08-30 17:42:00.170  7724  8353 W System.err: 	at com.uei.control.i.run(Unknown Source)
08-30 17:42:00.170  7724  8353 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:42:00.170  7724  8353 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 17:42:00.170  7724  8353 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:42:00.170  7724  8353 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:42:00.170  7724  8353 W System.err: 	... 7 more
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/files/data: open failed: EROFS (Read-only file system)
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1047)
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: 	at com.uei.control.core.f.e(Unknown Source)
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: 	at com.uei.control.core.f.l(Unknown Source)
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: 	at com.uei.control.core.f.c(Unknown Source)
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: 	at com.uei.control.i.run(Unknown Source)
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: 	at libcore.io.Posix.open(Native Method)
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: 	... 7 more
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: 
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/files/data: open failed: EROFS (Read-only file system)
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1047)
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: 	at com.uei.control.core.f.e(Unknown Source)
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: 	at com.uei.control.core.f.l(Unknown Source)
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: 	at com.uei.control.core.f.c(Unknown Source)
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: 	at com.uei.control.i.run(Unknown Source)
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: 	at libcore.io.Posix.open(Native Method)
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:42:00.171  7724  8353 E UEI.SmartControl: 	... 7 more
08-30 17:42:00.172  7724  8353 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 17:42:00.172  7724  8353 W System.err: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/app_assets/brands.xml: open failed: EROFS (Read-only file system)
08-30 17:42:00.172  7724  8353 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:42:00.172  7724  8353 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:42:00.172  7724  8353 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:42:00.172  7724  8353 W System.err: 	at com.uei.control.core.f.d(Unknown Source)
08-30 17:42:00.172  7724  8353 W System.err: 	at com.uei.control.core.f.c(Unknown Source)
08-30 17:42:00.173  7724  8353 W System.err: 	at com.uei.control.i.run(Unknown Source)
08-30 17:42:00.173  7724  8353 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:42:00.173  7724  8353 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 17:42:00.173  7724  8353 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:42:00.173  7724  8353 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:42:00.173  7724  8353 W System.err: 	... 5 more
08-30 17:42:00.173  7724  8353 E UEI.SmartControl: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/app_assets/brands.xml: open failed: EROFS (Read-only file system)
08-30 17:42:00.173  7724  8353 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:42:00.173  7724  8353 E UEI.SmartControl: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:42:00.173  7724  8353 E UEI.SmartControl: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:42:00.173  7724  8353 E UEI.SmartControl: 	at com.uei.control.core.f.d(Unknown Source)
08-30 17:42:00.173  7724  8353 E UEI.SmartControl: 	at com.uei.control.core.f.c(Unknown Source)
08-30 17:42:00.173  7724  8353 E UEI.SmartControl: 	at com.uei.control.i.run(Unknown Source)
08-30 17:42:00.173  7724  8353 E UEI.SmartControl: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:42:00.173  7724  8353 E UEI.SmartControl: 	at libcore.io.Posix.open(Native Method)
08-30 17:42:00.173  7724  8353 E UEI.SmartControl: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:42:00.173  7724  8353 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:42:00.173  7724  8353 E UEI.SmartControl: 	... 5 more
08-30 17:42:00.173  7724  8353 E UEI.SmartControl: 
08-30 17:42:00.173  7724  8353 E UEI.SmartControl: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/app_assets/brands.xml: open failed: EROFS (Read-only file system)
08-30 17:42:00.173  7724  8353 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:42:00.173  7724  8353 E UEI.SmartControl: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:42:00.173  7724  8353 E UEI.SmartControl: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:42:00.173  7724  8353 E UEI.SmartControl: 	at com.uei.control.core.f.d(Unknown Source)
08-30 17:42:00.173  7724  8353 E UEI.SmartControl: 	at com.uei.control.core.f.c(Unknown Source)
08-30 17:42:00.173  7724  8353 E UEI.SmartControl: 	at com.uei.control.i.run(Unknown Source)
08-30 17:42:00.173  7724  8353 E UEI.SmartControl: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:42:00.173  7724  8353 E UEI.SmartControl: 	at libcore.io.Posix.open(Native Method)
08-30 17:42:00.173  7724  8353 E UEI.SmartControl: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:42:00.173  7724  8353 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:42:00.173  7724  8353 E UEI.SmartControl: 	... 5 more
,08-30 17:42:00.181  1034  1397 D WifiService: Client connection lost with reason: 4
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/Downloads.db'.
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 17:42:00.200  8325  8325 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 17:42:00.200  8325  8325 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:42:00.200  8325  8325 W System.err: 	at android.database.sqlite.SQLiteCon,nection.nativeOpen(Native Method)
08-30 17:42:00.200  8325  8325 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-30 17:42:00.200  8325  8325 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-30 17:42:00.200  8325  8325 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
,08-30 17:42:00.200  8325  8325 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:42:00.200  8325  8325 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:42:00.200  8325  8325 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-30 17:42:00.200  8325  8325 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-30 17:42:00.200  8325  8325 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-30 17:42:00.201  8325  8325 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-30 17:42:00.201  8325  8325 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-30 17:42:00.201  8325  8325 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:42:00.201  8325  8325 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:42:00.201  8325  8325 W System.err: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
08-30 17:42:00.201  8325  8325 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-30 17:42:00.201  8325  8325 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-30 17:42:00.201  8325  8325 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-30 17:42:00.201  8325  8325 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-30 17:42:00.201  8325  8325 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-30 17:42:00.201  8325  8325 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-30 17:42:00.201  8325  8325 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-30 17:42:00.201  8325  8325 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:42:00.201  8325  8325 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:42:00.201  8325  8325 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 17:42:00.201  8325  8325 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:42:00.201  8325  8325 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:42:00.201  8325  8325 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 17:42:00.201  8325  8325 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-30 17:42:00.205  8325  8325 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/sqt.db'.
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 17:42:00.205  8325  8325 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 17:42:00.205  8325  8325 D AndroidRuntime: Shutting down VM
08-30 17:42:00.206  8325  8325 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:42:00.206  8325  8325 E AndroidRuntime: Process: com.lge.email, PID: 8325
08-30 17:42:00.206  8325  8325 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.email.pr,oviders.sqt.SqtProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-30 17:42:00.206  8325  8325 E AndroidRuntime: 	... 11 more
08-30 17:42:00.208  1034  1629 I ActivityManager: Process android.process.acore (pid 2353) has died
08-30 17:42:00.208  10,34  1629 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.voicemail.VoicemailCleanupService in 1000ms
08-30 17:42:00.208  1034  1629 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/com.lge.providers.contacts.AliveAcoreService in 1000ms
08-30 17:42:00.210  7724  7724 E UEI.SmartControl: Services init done
08-30 17:42:00.210  7724  7724 D UEI.SmartControl: QS Service init finished
08-30 17:42:00.210  7724  7724 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 17:42:00.210  7724  7724 D UEI.SmartControl: QS Service version code: 201091
08-30 17:42:00.210  7724  7724 D UEI.SmartControl: Service requested: Control
08-30 17:42:00.248  1034  1785 I ActivityManager: Process com.google.android.gms (pid 1816) has died
08-30 17:42:00.248  1034  1785 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10960ms
,08-30 17:42:00.248  1034  1785 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10960ms
08-30 17:42:00.248  1034  1785 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10960ms
08-30 17:42:00.248  1034  1785 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20960ms
08-30 17:42:00.248  1034  1785 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 30960ms
08-30 17:42:00.254  1034  8357 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:42:00.254  1034  8357 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-30 17:42:00.254  1034  8357 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:42:00.254  1034  8357 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:42:00.254  1034  8357 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:42:00.254  1034  8357 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:42:00.254  1034  8357 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-30 17:42:00.254  1034  8357 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-30 17:42:00.254  1034  8357 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:42:00.254  1034  8357 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:42:00.254  1034  8357 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:42:00.254  1034  8357 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:42:00.254  1034  8357 E DropBoxManagerService: 	... 5 more
08-30 17:42:00.254  8325  8325 I Process : Sending signal. PID: 8325 SIG: 9
08-30 17:42:00.255  8217  8217 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-30 17:42:00.255  7724  7724 D UEI.SmartControl: Internal service binding...
08-30 17:42:00.255  7724  7740 I UEI.SmartControl: ------ IControl API: 11
08-30 17:42:00.255  7724  7740 D UEI.SmartControl: File observer start...
08-30 17:42:00.256  7724  7740 E UEI.SmartControl: IR Port is disabled: false
08-30 17:42:00.256  7724  7740 D UEI.SmartControl: Starting file observer...
08-30 17:42:00.257  7724  7740 I UEI.SmartControl: Registering callback...
08-30 17:42:00.257  7724  7739 I UEI.SmartControl: ------ IControl API: 19
08-30 17:42:00.257  7724  7739 I UEI.SmartControl: Registering Services Ready callback...
08-30 17:42:00.348  1034  2006 I ActivityManager: Process com.lge.email (pid 8325) has died

```
