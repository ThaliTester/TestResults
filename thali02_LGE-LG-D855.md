#### Test 832729920321fb3_thali02_LGE-LG-D855 Logs


```
--------- beginning of system
08-30 17:27:36.493  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=868934919 [*alarm*], flags=0x0
,--------- beginning of main
08-30 17:27:38.352  6748  6748 D AndroidRuntime: 
08-30 17:27:38.352  6748  6748 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 17:27:38.356  6748  6748 D AndroidRuntime: CheckJNI is OFF
08-30 17:27:38.563  6748  6748 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 17:27:38.573  1034  1925 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 17:27:38.589  1941  1958 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-30 17:27:38.594  1034  1925 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-30 17:27:38.596  1034  1925 D ActivityManager: setTaskToReturnTo : TaskRecord{25ab906b #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 17:27:38.596  1034  1925 D ActivityManager: setTaskToReturnTo : TaskRecord{25ab906b #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 17:27:38.597  1034  1925 D WindowStateEx: AppWindowTokenEx init.. 
08-30 17:27:38.598   337   355 E GBMv2   : DFP En is all cleared set to be enabled
08-30 17:27:38.627  1034  1925 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6763 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 17:27:38.629  6748  6748 D AndroidRuntime: Shutting down VM
08-30 17:27:38.683  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-30 17:27:38.684  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{29020e03 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 17:27:38.684  1941  2563 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-30 17:27:38.685  1941  2563 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2f771180 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 17:27:38.757  6763  6763 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-30 17:27:38.855  6763  6763 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-30 17:27:38.864  6763  6763 I LibraryLoader: Loading: webviewchromium
08-30 17:27:38.867  6763  6763 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4233-4236)
08-30 17:27:38.867  6763  6763 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 17:27:38.886  6763  6763 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ac031a9}
,08-30 17:27:38.887  6763  6763 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 17:27:38.888  6763  6763 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 17:27:38.900  6763  6763 I BrowserStartupController: Initializing chromium process, renderers=0
,08-30 17:27:38.901  6763  6763 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 17:27:38.913   313  1384 V AudioPolicyService: registerClient() client 0xb04109c0, uid 10118
,08-30 17:27:38.914  6763  6763 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-30 17:27:38.915  6763  6763 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-30 17:27:38.915  6763  6763 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-30 17:27:38.919  1034  1096 D BluetoothManagerService: Message: 20
08-30 17:27:38.919  1034  1096 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@106f19d:true
08-30 17:27:38.934  6763  6763 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 17:27:38.934  6763  6763 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 17:27:38.934  6763  6763 I Adreno-EGL: Build Date: 12/12/14 금
08-30 17:27:38.934  6763  6763 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 17:27:38.934  6763  6763 I Adreno-EGL: Remote Branch: 
08-30 17:27:38.934  6763  6763 I Adreno-EGL: Local Patches: 
08-30 17:27:38.934  6763  6763 I Adreno-EGL: Reconstruct Branch: 
,08-30 17:27:39.019  6763  6797 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-30 17:27:39.022  6763  6763 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-30 17:27:39.041  6763  6763 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 17:27:39.047  6763  6763 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 17:27:39.051  6763  6763 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,08-30 17:27:39.054  6763  6763 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-30 17:27:39.054  6763  6763 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-30 17:27:39.071  6763  6763 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-30 17:27:39.078  6763  6763 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 17:27:39.078  6763  6763 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 17:27:39.119  6763  6810 D OpenGLRenderer: Render dirty regions requested: true
08-30 17:27:39.119  6763  6810 I OpenGLRenderer: Initialized EGL, version 1.4
08-30 17:27:39.126  6763  6810 D OpenGLRenderer: Enabling debug mode 0
,08-30 17:27:39.139  6763  6763 D Atlas   : Validating map...
,08-30 17:27:39.144  1034  1905 D SplitWindow: check instance of lgWin Window{2638302f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 17:27:39.181  6763  6808 D LgDataFeature: LgDataFeature() Constructor: none
08-30 17:27:39.181  6763  6808 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 17:27:39.267  1034  1097 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +585ms (total +668ms)
,08-30 17:27:39.270  6763  6763 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@9ae988c time:294639
,08-30 17:27:39.270  1034  1097 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2dcf47c8 u0 com.test.thalitest/.MainActivity t6} time:294640
08-30 17:27:39.378  6763  6763 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-30 17:27:39.378  6763  6763 I chromium: 
,08-30 17:27:39.386  6763  6763 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-30 17:27:39.525  6763  6820 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435160064
,08-30 17:27:39.539  6763  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 17:27:39.539  6763  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 17:27:39.539  6763  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 17:27:39.539  6763  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 17:27:39.539  6763  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 17:27:39.540  6763  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4963790 added. We now have 1 listener(s)
,08-30 17:27:39.545  1034  1738 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:27:39.548  6763  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-30 17:27:39.551  6763  6820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 17:27:39.552  6763  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:27:39.552  6763  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:27:39.560  6763  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 17:27:39.560  6763  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 17:27:39.560  6763  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 17:27:39.560  6763  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-30 17:27:39.560  6763  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 17:27:39.560  6763  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 17:27:39.560  6763  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 17:27:39.560  6763  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 17:27:39.560  6763  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 17:27:39.560  6763  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 17:27:39.560  6763  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 17:27:39.560  6763  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 17:27:39.560  6763  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 17:27:39.560  6763  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 17:27:39.560  6763  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175730af added. We now have 1 listener(s)
08-30 17:27:39.560  6763  6820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:27:39.564  1034  1546 D WifiService: New client listening to asynchronous messages
08-30 17:27:39.569  6763  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 17:27:39.570  6763  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 17:27:39.571  6763  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 17:27:39.571  6763  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 17:27:39.572  6763  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 17:27:39.579  6763  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:27:39.580  1034  1812 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:27:39.581  6763  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,08-30 17:27:39.594  6763  6820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 17:27:39.594  6763  6820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:27:39.594  6763  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:27:39.594  6763  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:27:39.594  6763  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:27:39.594  6763  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:27:39.594  6763  6820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:27:39.594  6763  6820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:27:39.594  6763  6820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:27:39.594  6763  6820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 17:27:39.594  6763  6820 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:27:39.597  6763  6763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:27:39.598  6763  6763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:27:39.600  6763  6820 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 17:27:39.631  6763  6808 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-30 17:27:39.631  6763  6808 I chromium: 
,08-30 17:27:39.709  6763  6763 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 17:27:40.539   337   364 E GBMv2   : DFP En is all cleared set to be enabled
,08-30 17:27:40.539   337   364 E GBMv2   : Set value is all cleared set the max
08-30 17:27:40.539   337   364 I GBMv2   : DFP Enabled. Ignore VFP set
08-30 17:27:40.887  6763  6823 W jxcore-log: Initializing JXcore engine
08-30 17:27:40.887  6763  6823 W jxcore-log: JXcore engine is ready
,08-30 17:27:40.955  6823  6823 W Thread-771: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7785]" dev="sockfs" ino=7785 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-30 17:27:40.955  6823  6823 W Thread-771: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-30 17:27:40.955  6823  6823 W Thread-771: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10542]" dev="sockfs" ino=10542 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-30 17:27:40.955  6823  6823 W Thread-771: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,08-30 17:27:40.955  6823  6823 W Thread-771: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31712]" dev="sockfs" ino=31712 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-30 17:27:40.990  6763  6823 W jxcore-log: Starting JXcore engine
,08-30 17:27:41.139  6763  6823 W jxcore-log: Platform android
08-30 17:27:41.139  6763  6823 W jxcore-log: 
08-30 17:27:41.139  6763  6823 W jxcore-log: Process ARCH arm
08-30 17:27:41.139  6763  6823 W jxcore-log: 
,08-30 17:27:41.557  6763  6823 I jxcore-log: JXcore Cordova bridge is ready!
08-30 17:27:41.557  6763  6823 I jxcore-log: 
08-30 17:27:41.558  6763  6823 W jxcore-log: JXcore engine is started
,08-30 17:27:41.572  6763  6820 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 17:27:41.577  6763  6763 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 17:28:00.069  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-30 17:28:00.070  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-30 17:28:00.070  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-30 17:28:00.078  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
08-30 17:28:00.082  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-30 17:28:00.082  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-30 17:28:00.084  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-30 17:28:00.085  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
,08-30 17:28:01.787  6763  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 17:28:01.787  6763  6823 I jxcore-log: 
,08-30 17:28:01.790  6763  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 17:28:01.790  6763  6823 I jxcore-log: 
,08-30 17:28:01.793  6763  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:28:01.793  6763  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:28:01.793  6763  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:28:01.793  6763  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:28:01.793  6763  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:28:01.793  6763  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:28:01.793  6763  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:28:01.793  6763  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:28:01.795  6763  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:28:01.797  6763  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 17:28:01.797  6763  6823 I jxcore-log: 
08-30 17:28:01.798  6763  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 17:28:01.798  6763  6823 I jxcore-log: 
08-30 17:28:02.144  6763  6823 I jxcore-log: Running unit tests
08-30 17:28:02.144  6763  6823 I jxcore-log: 
,08-30 17:28:02.144  6763  6823 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-30 17:28:02.145  6763  6823 I jxcore-log: Failed to execute UT.
08-30 17:28:02.145  6763  6823 I jxcore-log: 
08-30 17:28:02.146  6763  6823 I jxcore-log: Unit Test app is loaded
08-30 17:28:02.146  6763  6823 I jxcore-log: 
08-30 17:28:02.154  6763  6763 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 17:28:02.163  6763  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:28:02.163  6763  6823 I jxcore-log: 
,08-30 17:28:02.173  6763  6823 I jxcore-log: My device name is: LGE-LG-D855
08-30 17:28:02.173  6763  6823 I jxcore-log: 
08-30 17:28:07.028  6763  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 17:28:07.028  6763  6823 I jxcore-log: 
,08-30 17:28:07.904  6763  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 17:28:07.904  6763  6823 I jxcore-log: 
,08-30 17:28:07.952  6763  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 17:28:07.952  6763  6823 I jxcore-log: 
,08-30 17:28:10.639  6763  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 17:28:10.639  6763  6823 I jxcore-log: 
,08-30 17:28:11.090  6763  6823 I jxcore-log: ERROR runTests: 
08-30 17:28:11.090  6763  6823 I jxcore-log: 
08-30 17:28:11.094  6763  6823 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 17:28:11.094  6763  6823 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-30 17:28:11.130  6763  6823 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 17:28:11.130  6763  6823 I jxcore-log:     _functionName: 'loadFile',
08-30 17:28:11.130  6763  6823 I jxcore-log:     _lineNumber: '26',
08-30 17:28:11.130  6763  6823 I jxcore-log:     _columnNumber: '11',
08-30 17:28:11.130  6763  6823 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 17:28:11.130  6763  6823 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 17:28:11.130  6763  6823 I jxcore-log:     _functionName: '',
08-30 17:28:11.130  6763  6823 I jxcore-log:     _lineNumber: '38',
08-30 17:28:11.130  6763  6823 I jxcore-log:     _columnNumber: '7',
08-30 17:28:11.130  6763  6823 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 17:28:11.130  6763  6823 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 17:28:11.130  6763  6823 I jxcore-log:     _functionName: '',
08-30 17:28:11.130  6763  6823 I jxcore-log:     _lineNumber: '35',
08-30 17:28:11.130  6763  6823 I jxcore-log:     _columnNumber: '3',
08-30 17:28:11.130  6763  6823 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 17:28:11.130  6763  6823 I jxcore-log:   { _fileName: 'module.js',
08-30 17:28:11.130  6763  6823 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 17:28:11.130  6763  6823 I jxcore-log:     _lineNumber: '621',
08-30 17:28:11.130  6763  6823 I jxcore-log:     _columnNumber: '8',
08-30 17:28:11.130  6763  6823 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 17:28:11.130  6763  6823 I jxcore-log:   { _fileName: 'module.js',
08-30 17:28:11.130  6763  6823 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 17:28:11.130  6763  6823 I jxcore-log:     _lineNumber: '651',
08-30 17:28:11.130  6763  6823 I jxcore-log:     _columnNumber: '1',
08-30 17:28:11.130  6763  6823 I jxcore-log:    
08-30 17:28:11.130  6763  6823 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 17:28:11.130  6763  6823 I jxcore-log: 
,08-30 17:28:11.133  6763  6823 E jxcore-log: Error: 
08-30 17:28:11.133  6763  6823 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 17:28:11.133  6763  6823 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 17:28:11.133  6763  6823 E jxcore-log: 
08-30 17:28:11.476  6844  6844 D AndroidRuntime: 
08-30 17:28:11.476  6844  6844 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-30 17:28:11.483  6844  6844 D AndroidRuntime: CheckJNI is OFF
08-30 17:28:11.701  6844  6844 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 17:28:11.719  1034  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-30 17:28:11.720  1034  1092 I ActivityManager: Killing 6763:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-30 17:28:11.796  1034  1904 I WindowState: WIN DEATH: Window{2638302f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 17:28:11.811  1034  1546 D WifiService: Client connection lost with reason: 4
,08-30 17:28:11.824  1034  1904 D InputDispatcher: Window went away: Window{2638302f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 17:28:11.964  1034  1092 I ActivityManager:   Force finishing activity ActivityRecord{2dcf47c8 u0 com.test.thalitest/.MainActivity t6}
,08-30 17:28:11.994   337   355 E GBMv2   : DFP En is all cleared set to be enabled
,08-30 17:28:11.998  1034  1654 W ActivityManager: Spurious death for ProcessRecord{1cc1827d 6763:com.test.thalitest/u0a118}, curProc for 6763: null
08-30 17:28:11.999  1034  1108 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-30 17:28:12.002  1034  1108 I ActivityManager:   Force finishing activity ActivityRecord{2dcf47c8 u0 com.test.thalitest/.MainActivity t6 f}
08-30 17:28:12.003  1034  1108 W ActivityManager: Duplicate finish request for ActivityRecord{2dcf47c8 u0 com.test.thalitest/.MainActivity t6 f}
,08-30 17:28:12.040  2034  2034 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-30 17:28:12.042  1941  2563 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-30 17:28:12.044  1941  2563 D SplitWindowPolicy: topRunningActivity=ActivityInfo{607a3b9 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 17:28:12.045  2034  2034 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-30 17:28:12.046  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-30 17:28:12.047  1941  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-30 17:28:12.047  2034  2142 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-30 17:28:12.048  1941  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3f3943fe co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 17:28:12.054  1906  1906 D ActionManagerService: notifyUserLog: 1000003
08-30 17:28:12.055  3756  4460 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
,08-30 17:28:12.056  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-30 17:28:12.060  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-30 17:28:12.063  1034  1483 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-30 17:28:12.064  3756  3756 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-30 17:28:12.064  2445  2594 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 17:28:12.065  1997  1997 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-30 17:28:12.066  4582  4582 I art     : Explicit concurrent mark sweep GC freed 461(31KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 628us total 46.673ms
08-30 17:28:12.069  3813  3813 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-30 17:28:12.069  3813  3813 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-30 17:28:12.073  2034  2034 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-30 17:28:12.074  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-30 17:28:12.133  2034  2034 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-30 17:28:12.143  1818  1818 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-30 17:28:12.145  2034  2034 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-30 17:28:12.146  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-30 17:28:12.155  4466  4466 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-30 17:28:12.158  1034  1091 W InputMethodInfo: Duplicated subtype definition found: , voice
08-30 17:28:12.160  4466  4466 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-30 17:28:12.160  4466  4466 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-30 17:28:12.160  4466  4466 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-30 17:28:12.160  4466  4466 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 17:28:12.160  4466  4466 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 17:28:12.160  4466  4466 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:28:12.160  4466  4466 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 17:28:12.160  4466  4466 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:28:12.160  4466  4466 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:28:12.160  4466  4466 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 17:28:12.160  4466  4466 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 17:28:12.163  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-30 17:28:12.163  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-30 17:28:12.166  1870  1870 D SplitUIManager: split_name #11 / not available #0
08-30 17:28:12.166  1870  1870 D SplitUIService: removed split : 
08-30 17:28:12.185  1034  1983 V SIM_STK : Menu title from STK is T-Mobile
,08-30 17:28:12.201  1870  1870 D SplitUIManager: split_name #11 / not available #0
08-30 17:28:12.201  1870  1870 I SplitUIService: split app #11
,08-30 17:28:12.205  1034  1034 I art     : Explicit concurrent mark sweep GC freed 42265(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 2.650ms total 172.747ms
08-30 17:28:12.205  1034  1959 I art     : WaitForGcToComplete blocked for 68.249ms for cause Explicit
08-30 17:28:12.291  1034  1034 D administrator: Handling package changes for user 0
,08-30 17:28:12.327  1034  1951 V SIM_STK : Menu title from STK is T-Mobile
08-30 17:28:12.327  1034  1951 V SIM_STK : Menu title from STK is T-Mobile
,08-30 17:28:12.337  1034  1959 I art     : Explicit concurrent mark sweep GC freed 6448(414KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.616ms total 131.168ms
08-30 17:28:12.337  1034  1108 I art     : WaitForGcToComplete blocked for 264.852ms for cause Explicit
08-30 17:28:12.348  1605  1653 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 17:28:12.348  1605  1653 D KeyguardModel: createShortcutInfo...
,08-30 17:28:12.349  1605  1653 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 17:28:12.349  1605  1653 D KeyguardModel: createShortcutInfo...
08-30 17:28:12.353  1605  1653 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 17:28:12.353  1605  1653 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:28:12.354  1605  1653 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 17:28:12.355  1605  1653 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 17:28:12.355  1605  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 17:28:12.355  1605  1653 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 17:28:12.356  1605  1653 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 17:28:12.356  1605  1653 D KeyguardModel: createShortcutInfo...
08-30 17:28:12.362  1605  1653 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 17:28:12.362  1605  1653 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 17:28:12.364  1605  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 17:28:12.364  1605  1653 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 17:28:12.366  2205  2205 I ConfigService: onCreate
08-30 17:28:12.368  2205  2205 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-30 17:28:12.369  1605  1653 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 17:28:12.369  1605  1653 D KeyguardModel: createShortcutInfo...
08-30 17:28:12.371  1906  1906 D ActionManagerService: notifyUserLog: 1000004
08-30 17:28:12.371  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-30 17:28:12.372  3756  4460 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-30 17:28:12.373  3756  4264 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 17:28:12.375  2205  2205 I ConfigService: onBind returning update interface
,08-30 17:28:12.379  1818  1818 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-30 17:28:12.380  2205  2205 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-30 17:28:12.380  2205  2205 I ConfigService: onBind returning config service
08-30 17:28:12.381  1605  1653 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:28:12.381  1605  1653 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 17:28:12.381  1605  1653 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 17:28:12.381  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-30 17:28:12.381  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262123
08-30 17:28:12.381  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-30 17:28:12.381  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-30 17:28:12.381  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-30 17:28:12.381  2034  2034 I GBoardWebViewUtils: , display: false
08-30 17:28:12.381  2034  2034 I GBoardWebViewUtils: , animation: false }
08-30 17:28:12.381  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-30 17:28:12.381  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262287
08-30 17:28:12.381  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-30 17:28:12.381  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 17:28:12.381  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 17:28:12.381  2034  2034 I GBoardWebViewUtils: , display: false
08-30 17:28:12.381  2034  2034 I GBoardWebViewUtils: , animation: false }
08-30 17:28:12.381  1605  1653 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 17:28:12.381  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-30 17:28:12.381  2034  2034 I GBoardWebViewUtils: , create_time: 1472216588858
08-30 17:28:12.381  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-30 17:28:12.381  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 17:28:12.381  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 17:28:12.381  2034  2034 I GBoardWebViewUtils: , display: false
08-30 17:28:12.381  2034  2034 I GBoardWebViewUtils: , animation: false }
08-30 17:28:12.382  1605  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 17:28:12.382  1605  1653 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 17:28:12.384  1605  1653 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 17:28:12.384  1605  1653 D KeyguardModel: createShortcutInfo...
08-30 17:28:12.385  2034  6880 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-30 17:28:12.386  1818  1818 I ConfigFetchService: service connected
,08-30 17:28:12.394  2205  2205 I ConfigService: onDestroy
08-30 17:28:12.395  1034  1050 V SIM_STK : Menu title from STK is T-Mobile
08-30 17:28:12.397  1818  6881 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-30 17:28:12.400  1605  1605 D KeyguardModel: handleShortcutListChanged...
08-30 17:28:12.400  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-30 17:28:12.406  1605  1653 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 17:28:12.406  1605  1653 D KeyguardModel: createShortcutInfo...
08-30 17:28:12.408  1605  1653 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 17:28:12.408  1605  1653 D KeyguardModel: createShortcutInfo...
08-30 17:28:12.408  1605  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 17:28:12.409  1605  1653 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 17:28:12.409  1605  1653 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 17:28:12.409  1605  1653 D KeyguardModel: createShortcutInfo...
,08-30 17:28:12.415  1605  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 17:28:12.416  1605  1653 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 17:28:12.422  6003  6003 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-30 17:28:12.426  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-30 17:28:12.433  1605  1653 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 17:28:12.433  1605  1653 D KeyguardModel: createShortcutInfo...
08-30 17:28:12.437  1605  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 17:28:12.437  1605  1653 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 17:28:12.437  1034  2033 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-30 17:28:12.438  3813  3813 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 17:28:12.438  3813  3813 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 17:28:12.438  3813  3813 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 17:28:12.438  3813  3813 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 17:28:12.438  3813  3813 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 17:28:12.438  3813  3813 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 17:28:12.438  3813  3813 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 17:28:12.438  3813  3813 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 17:28:12.438  3813  3813 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 17:28:12.438  3813  3813 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 17:28:12.438  3813  3813 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 17:28:12.445  1605  1653 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 17:28:12.445  1605  1653 D KeyguardModel: createShortcutInfo...
,08-30 17:28:12.455  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-30 17:28:12.455  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 17:28:12.457  2370  6888 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 17:28:12.461  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 17:28:12.465  6534  6534 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-30 17:28:12.477  5935  6889 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-30 17:28:12.479  1605  1605 D KeyguardModel: handleShortcutListChanged...
08-30 17:28:12.479  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-30 17:28:12.481  1034  1579 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-30 17:28:12.485  1818  6891 I PeopleContactsSync: CP2 sync disabled
08-30 17:28:12.501  1818  4716 I Icing   : doRemovePackageData com.test.thalitest
08-30 17:28:12.502  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-30 17:28:12.506  1818  6887 W GmsApplication: Using Auth Proxy for data requests.
08-30 17:28:12.508  2034  2034 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-30 17:28:12.522  1997  1997 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-30 17:28:12.522  1997  1997 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-30 17:28:12.523  1997  1997 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,08-30 17:28:12.527  1818  6887 W GmsApplication: Using Auth Proxy for data requests.
08-30 17:28:12.530  6433  6433 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-30 17:28:12.569  1034  1577 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6894 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-30 17:28:12.571  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-30 17:28:12.573  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 17:28:12.575  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-30 17:28:12.576  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-30 17:28:12.578  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-30 17:28:12.579  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-30 17:28:12.594  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-30 17:28:12.594  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 17:28:12.600  1034  1097 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{5dd9812 u0 com.lge.launcher2/.Launcher t5} time:327970
,08-30 17:28:12.601  2034  2172 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-30 17:28:12.601  2034  2172 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-30 17:28:12.610  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-30 17:28:12.611  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 17:28:12.611  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 17:28:12.618  2034  2034 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-30 17:28:12.621  2613  2613 D [Concierge]Service: onStartCommand(). Type : 8
08-30 17:28:12.621  2613  2613 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-30 17:28:12.623  2613  2613 D [Concierge]Service: Update widget ID : 11
08-30 17:28:12.623  2034  2034 D [Concierge]WidgetView: change position of spinner
08-30 17:28:12.624  2034  2034 I [Concierge]WidgetView: initWebView(). Time : 1472570892624
08-30 17:28:12.624  2613  2613 D [Concierge]Service: onStartCommand(). Type : 0
08-30 17:28:12.630  1034  1108 I art     : Explicit concurrent mark sweep GC freed 7821(402KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.527ms total 291.520ms
,08-30 17:28:12.642  2034  2034 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 719126468
08-30 17:28:12.643  2034  2034 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-30 17:28:12.643  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-30 17:28:12.646  2034  2034 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2bf62398
08-30 17:28:12.646  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-30 17:28:12.647  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 17:28:12.647  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 17:28:12.652  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-30 17:28:12.652  2034  2034 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-30 17:28:12.653  2034  2034 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 17:28:12.653  2034  2034 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472570593461, New one : 1472570892624
08-30 17:28:12.653  2034  2034 D [Concierge]WidgetView: Unregister all receivers
08-30 17:28:12.653  2034  2034 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 17:28:12.654  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 17:28:12.655  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-30 17:28:12.657  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-30 17:28:12.658  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-30 17:28:12.659  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-30 17:28:12.659  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,08-30 17:28:12.664  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 17:28:12.664  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 17:28:12.672  6894  6894 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-30 17:28:12.672  6894  6894 W LG Account v2.2: No ProfileInfo entries
08-30 17:28:12.672  6894  6894 I LG Account v2.2: isEnabled: false
08-30 17:28:12.673  6894  6894 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 17:28:12.673  6894  6894 I Feature : [Lifetracker]Country: EU
08-30 17:28:12.673  6894  6894 I Feature : [Lifetracker]Operator: OPEN
08-30 17:28:12.673  6894  6894 I Feature : [Lifetracker]Ranking support: false
08-30 17:28:12.673  6894  6894 I Feature : [Lifetracker]Comfort support: false
08-30 17:28:12.673  6894  6894 I Feature : [Lifetracker]Accessory: true
08-30 17:28:12.673  6894  6894 I Feature : [Lifetracker]Health device: true
08-30 17:28:12.673  6894  6894 I Feature : [Lifetracker]Extra Pedometer: false
08-30 17:28:12.673  6894  6894 I Feature : [Lifetracker]Blood glucose device: false
08-30 17:28:12.673  6894  6894 I Feature : [Lifetracker]Device Number: 3
08-30 17:28:12.673  6894  6894 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
,08-30 17:28:12.703  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-30 17:28:12.711  1034  1996 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6916 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 17:28:12.713  1034  1996 I ActivityManager: Killing 6198:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-30 17:28:12.732  6844  6844 D AndroidRuntime: Shutting down VM
,08-30 17:28:12.734  2034  2034 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-30 17:28:12.734  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-30 17:28:12.736  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 17:28:12.739  1034  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:28:12.745  1034  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-30 17:28:12.756  2034  2034 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@b1ac4d9 time:328126
,08-30 17:28:12.842  1034  2033 W libprocessgroup: failed to open /acct/uid_10014/pid_6198/cgroup.procs: No such file or directory
,08-30 17:28:12.862  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-30 17:28:12.883  6916  6916 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 17:28:12.883  6916  6916 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-30 17:28:12.884  6916  6916 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 17:28:12.884  6916  6916 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-30 17:28:12.885  6916  6916 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 17:28:12.886  6916  6916 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 17:28:12.949  2034  2034 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-30 17:28:13.011  2034  2870 I GBoardtInterface: onReloaded()
,08-30 17:28:13.014  2034  2034 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-30 17:28:13.017  3756  4264 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 17:28:13.020  3756  3772 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 17:28:13.027  1906  1906 D ActionManagerService: notifyUserLog: 1000001
08-30 17:28:13.028  3756  4460 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 17:28:13.028  3756  4460 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,08-30 17:28:13.033  1906  1906 D ActionManagerService: notifyUserLog: 1000001
08-30 17:28:13.034  3756  4460 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 17:28:13.034  3756  4460 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-30 17:28:13.034  3756  4460 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-30 17:28:13.034  3756  4460 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-30 17:28:13.035  3756  4264 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 17:28:13.037  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-30 17:28:13.037  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-30 17:28:13.039  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-30 17:28:13.039  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 17:28:13.041  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-30 17:28:13.041  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-30 17:28:13.071  6916  6916 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-30 17:28:13.081  6916  6916 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-30 17:28:13.081  6916  6916 D HideNavigationAppsReceiver: replacing : false
08-30 17:28:13.085  6916  6916 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
,08-30 17:28:13.088  6916  6916 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
,08-30 17:28:13.088  6916  6916 D ButtonCombinationReceiver: replacing : false
08-30 17:28:13.100  1034  1904 I ActivityManager: Killing 6483:com.google.android.partnersetup/u0a8 (adj 15): empty #17

```
