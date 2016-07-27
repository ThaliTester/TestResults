#### Test 77622416ad9274d_thali05_LGE-LG-D855 Logs


```
--------- beginning of system
07-27 11:50:48.243  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=375115087 [*alarm*], flags=0x0
,--------- beginning of main
07-27 11:50:58.049  6715  6715 D AndroidRuntime: 
07-27 11:50:58.049  6715  6715 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-27 11:50:58.055  6715  6715 D AndroidRuntime: CheckJNI is OFF
07-27 11:50:58.169  6715  6715 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-27 11:50:58.174  1037  1998 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-27 11:50:58.195  1927  1942 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
07-27 11:50:58.200  1037  1998 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
07-27 11:50:58.201  1037  1998 D ActivityManager: setTaskToReturnTo : TaskRecord{37239c43 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-27 11:50:58.201  1037  1998 D ActivityManager: setTaskToReturnTo : TaskRecord{37239c43 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-27 11:50:58.202  1037  1998 D WindowStateEx: AppWindowTokenEx init.. 
07-27 11:50:58.202   351   361 E GBMv2   : DFP En is all cleared set to be enabled
07-27 11:50:58.224  1037  1998 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6735 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-27 11:50:58.227  6715  6715 D AndroidRuntime: Shutting down VM
07-27 11:50:58.263  1927  1943 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
07-27 11:50:58.263  1927  1943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1f485006 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
07-27 11:50:58.264  1927  2922 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
07-27 11:50:58.265  1927  2922 D SplitWindowPolicy: topRunningActivity=ActivityInfo{4d016c7 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
07-27 11:50:58.300  6735  6735 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-27 11:50:58.363  6735  6735 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
07-27 11:50:58.369  6735  6735 I LibraryLoader: Loading: webviewchromium
07-27 11:50:58.371  6735  6735 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6211-6213)
07-27 11:50:58.371  6735  6735 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 11:50:58.384  6735  6735 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {215a71a4}
07-27 11:50:58.385  6735  6735 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 11:50:58.385  6735  6735 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-27 11:50:58.391  6735  6735 I BrowserStartupController: Initializing chromium process, renderers=0
07-27 11:50:58.392  6735  6735 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 11:50:58.402  6735  6735 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-27 11:50:58.403  6735  6735 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
07-27 11:50:58.403  6735  6735 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
07-27 11:50:58.404   336   336 V AudioPolicyService: registerClient() client 0xb558abe0, uid 10118
07-27 11:50:58.408  1037  1120 D BluetoothManagerService: Message: 20
07-27 11:50:58.408  1037  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@70deb5:true
07-27 11:50:58.419  6735  6735 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 11:50:58.419  6735  6735 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 11:50:58.419  6735  6735 I Adreno-EGL: Build Date: 12/12/14 금
07-27 11:50:58.419  6735  6735 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-27 11:50:58.419  6735  6735 I Adreno-EGL: Remote Branch: 
07-27 11:50:58.419  6735  6735 I Adreno-EGL: Local Patches: 
07-27 11:50:58.419  6735  6735 I Adreno-EGL: Reconstruct Branch: 
07-27 11:50:58.475  6735  6766 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-27 11:50:58.483  6735  6735 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-27 11:50:58.504  6735  6735 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 11:50:58.510  6735  6735 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-27 11:50:58.514  6735  6735 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-27 11:50:58.518  6735  6735 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-27 11:50:58.518  6735  6735 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-27 11:50:58.535  6735  6735 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
07-27 11:50:58.546  6735  6735 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 11:50:58.546  6735  6735 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 11:50:58.596  6735  6782 D OpenGLRenderer: Render dirty regions requested: true
07-27 11:50:58.596  6735  6782 I OpenGLRenderer: Initialized EGL, version 1.4
07-27 11:50:58.607  6735  6782 D OpenGLRenderer: Enabling debug mode 0
07-27 11:50:58.617  6735  6735 D Atlas   : Validating map...
07-27 11:50:58.623  1037  1871 D SplitWindow: check instance of lgWin Window{22b8ba87 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-27 11:50:58.664  6735  6776 D LgDataFeature: LgDataFeature() Constructor: none
07-27 11:50:58.664  6735  6776 D LgDataFeature: LgDataFeature() Constructor Done, null
07-27 11:50:58.761  1037  1121 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +498ms (total +558ms)
07-27 11:50:58.762  1037  1121 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{329822c0 u0 com.test.thalitest/.MainActivity t40} time:286604
07-27 11:50:58.765  6735  6735 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@c35b4c3 time:286608
07-27 11:50:58.877  6735  6735 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-27 11:50:58.877  6735  6735 I chromium: 
07-27 11:50:58.946  6735  6735 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-27 11:50:59.118  6735  6789 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435196928
07-27 11:50:59.135  6735  6789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-27 11:50:59.135  6735  6789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-27 11:50:59.135  6735  6789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-27 11:50:59.135  6735  6789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-27 11:50:59.135  6735  6789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-27 11:50:59.135  6735  6789 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cb1ee17 added. We now have 1 listener(s)
07-27 11:50:59.143  1037  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:50:59.147  6735  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
07-27 11:50:59.148  6735  6789 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 11:50:59.152  6735  6789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:50:59.153  6735  6789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:50:59.171  6735  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-27 11:50:59.171  6735  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-27 11:50:59.171  6735  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-27 11:50:59.171  6735  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
07-27 11:50:59.171  6735  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-27 11:50:59.171  6735  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-27 11:50:59.171  6735  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-27 11:50:59.171  6735  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-27 11:50:59.171  6735  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-27 11:50:59.171  6735  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-27 11:50:59.171  6735  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-27 11:50:59.171  6735  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-27 11:50:59.171  6735  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-27 11:50:59.171  6735  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-27 11:50:59.172  6735  6789 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ce56222 added. We now have 1 listener(s)
07-27 11:50:59.173  6735  6789 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:50:59.181  1037  1528 D WifiService: New client listening to asynchronous messages
07-27 11:50:59.186  6735  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 11:50:59.187  6735  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-27 11:50:59.187  6735  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-27 11:50:59.187  6735  6789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-27 11:50:59.192  6735  6789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:50:59.193  1037  1766 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:50:59.194  6735  6789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
07-27 11:50:59.203  6735  6789 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,07-27 11:50:59.204  6735  6789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:50:59.204  6735  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:50:59.204  6735  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:50:59.204  6735  6789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:50:59.204  6735  6789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:50:59.204  6735  6789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:50:59.204  6735  6789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:50:59.204  6735  6789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:50:59.204  6735  6789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-27 11:50:59.204  6735  6789 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:50:59.205  6735  6789 I io.jxcore.node.LifeCycleMonitor: start: OK
07-27 11:50:59.210  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:50:59.213  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:50:59.251  6735  6776 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
07-27 11:50:59.251  6735  6776 I chromium: 
,07-27 11:50:59.299   351   363 E GBMv2   : DFP En is all cleared set to be enabled
07-27 11:50:59.299   351   363 E GBMv2   : Set value is all cleared set the max
07-27 11:50:59.300   351   363 I GBMv2   : DFP Enabled. Ignore VFP set
,07-27 11:50:59.309  6735  6735 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
07-27 11:51:00.054  1587  1587 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 11:51:00.054  1587  1587 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 11:51:00.054  1587  1587 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-27 11:51:00.054  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
,07-27 11:51:00.062  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 11:51:00.062  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
,07-27 11:51:00.064  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
07-27 11:51:00.065  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 11:51:00.301  6735  6792 W jxcore-log: Initializing JXcore engine
07-27 11:51:00.301  6735  6792 W jxcore-log: JXcore engine is ready
,07-27 11:51:00.364  6792  6792 W Thread-778: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7389]" dev="sockfs" ino=7389 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
07-27 11:51:00.364  6792  6792 W Thread-778: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
07-27 11:51:00.364  6792  6792 W Thread-778: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7591]" dev="sockfs" ino=7591 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,07-27 11:51:00.364  6792  6792 W Thread-778: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
07-27 11:51:00.364  6792  6792 W Thread-778: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[31518]" dev="sockfs" ino=31518 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
07-27 11:51:00.391  6735  6792 W jxcore-log: Starting JXcore engine
,07-27 11:51:00.556  6735  6792 W jxcore-log: Platform android
07-27 11:51:00.556  6735  6792 W jxcore-log: 
07-27 11:51:00.556  6735  6792 W jxcore-log: Process ARCH arm
07-27 11:51:00.556  6735  6792 W jxcore-log: 
,07-27 11:51:00.767  6735  6792 I jxcore-log: JXcore Cordova bridge is ready!
07-27 11:51:00.767  6735  6792 I jxcore-log: 
07-27 11:51:00.767  6735  6792 W jxcore-log: JXcore engine is started
,07-27 11:51:00.779  6735  6789 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-27 11:51:00.787  6735  6735 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-27 11:51:10.712  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-27 11:51:10.712  6735  6792 I jxcore-log: 
,07-27 11:51:10.715  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-27 11:51:10.715  6735  6792 I jxcore-log: 
07-27 11:51:10.722  6735  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:51:10.722  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:10.722  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:10.722  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:10.722  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:10.722  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:10.722  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:51:10.722  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:51:10.727  6735  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 11:51:10.730  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-27 11:51:10.730  6735  6792 I jxcore-log: 
07-27 11:51:10.732  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-27 11:51:10.732  6735  6792 I jxcore-log: 
07-27 11:51:11.059  6735  6792 D ExecuteNativeTests: Running unit tests
,07-27 11:51:11.127  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-27 11:51:11.127  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151a08d0 added. We now have 2 listener(s)
07-27 11:51:11.128  1037  2028 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-27 11:51:11.130  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 11:51:11.130  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:51:11.130  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:51:11.130  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:11.130  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 added. We now have 2 listener(s)
07-27 11:51:11.130  6735  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:51:11.131  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 11:51:11.135  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:51:11.140  6735  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:51:11.140  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:11.140  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:11.140  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:11.140  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:11.140  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:11.140  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:51:11.140  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 11:51:11.142  6735  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 11:51:11.142  6735  6792 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:51:11.143  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:11.144  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:11.147  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-27 11:51:11.148  6735  6792 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
07-27 11:51:11.148  6735  6792 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-27 11:51:11.149  6735  6792 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,07-27 11:51:11.150  6735  6792 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-27 11:51:11.150  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,07-27 11:51:11.150  6735  6792 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-27 11:51:11.150  6735  6792 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-27 11:51:11.151  6735  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-27 11:51:11.151  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.151  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-27 11:51:11.153  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.153  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.153  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-27 11:51:11.153  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-27 11:51:11.153  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151a08d0 removed from the list
07-27 11:51:11.153  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 11:51:11.153  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 removed from the list
07-27 11:51:11.153  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
,07-27 11:51:11.153  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.154  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.154  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 11:51:11.155  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
,07-27 11:51:11.155  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.155  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.155  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
,07-27 11:51:11.157  6735  6792 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-27 11:51:11.157  6735  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.157  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.157  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
07-27 11:51:11.158  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.158  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.158  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 11:51:11.158  6735  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151a08d0 not in the list
07-27 11:51:11.158  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.158  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list,
07-27 11:51:11.158  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.158  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.158  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 11:51:11.158  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.158  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.159  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.159  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.159  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.159  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
,07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910],
07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910],
07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,07-27 11:51:11.167  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-27 11:51:11.168  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-27 11:51:11.168  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,07-27 11:51:11.168  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-27 11:51:11.168  6735  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.168  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-27 11:51:11.168  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.168  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.168  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 11:51:11.168  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.168  6735  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151a08d0 not in the list
07-27 11:51:11.168  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 11:51:11.168  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.168  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.168  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.168  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.168  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.168  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.170  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-27 11:51:11.170  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.170  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.170  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.171  6735  6792 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-27 11:51:11.173  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:51:11.176  6735  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:51:11.176  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:11.176  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:11.176  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:11.176  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:11.176  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:11.176  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:51:11.176  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 11:51:11.177  6735  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:11.177  6735  6792 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:51:11.178  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:11.180  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:11.181  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:51:11.181  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 11:51:11.181  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:51:11.181  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-27 11:51:11.184  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-27 11:51:11.185  1037  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:11.189  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-27 11:51:11.193  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-27 11:51:11.195  6735  6792 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
,07-27 11:51:11.196  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 11:51:11.196  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:51:11.197  6735  6792 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 11:51:11.197  6735  6792 I io.jxcore.node.ConnectionHelper: start: OK
07-27 11:51:11.199  6735  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.200  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.200  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-27 11:51:11.200  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.200  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.200  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:51:11.200  6735  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151a08d0 not in the list
07-27 11:51:11.200  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.200  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.200  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.200  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 11:51:11.200  6735  6792 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-27 11:51:11.202  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:51:11.204  6735  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:51:11.204  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:11.204  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:11.204  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:11.204  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:11.204  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:11.204  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:51:11.204  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:51:11.204  6735  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:11.204  6735  6792 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-27 11:51:11.206  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
07-27 11:51:11.207  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:11.207  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:51:11.207  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 11:51:11.207  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:51:11.208  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 11:51:11.211  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-27 11:51:11.211  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:51:11.212  6735  6792 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 11:51:11.212  6735  6792 I io.jxcore.node.ConnectionHelper: start: OK
07-27 11:51:11.213  6735  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.213  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.213  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.213  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-27 11:51:11.213  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.213  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:51:11.213  6735  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151a08d0 not in the list
07-27 11:51:11.213  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.213  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.213  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.213  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 11:51:11.214  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.214  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.214  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.214  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.215  6735  6792 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:11.215  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:11.215  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 11:51:11.216  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
,07-27 11:51:11.216  6735  6792 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-27 11:51:11.217  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:51:11.219  6735  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:51:11.219  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:11.219  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:11.219  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:11.219  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:11.219  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:11.219  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:51:11.219  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:51:11.220  6735  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:11.220  6735  6792 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:51:11.221  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:51:11.221  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 11:51:11.221  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:51:11.221  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 11:51:11.221  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:11.222  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:11.227  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 11:51:11.227  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-27 11:51:11.228  6735  6792 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 11:51:11.228  6735  6792 I io.jxcore.node.ConnectionHelper: start: OK
07-27 11:51:11.228  6735  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.228  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.228  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.229  6735  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.229  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.229  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.229  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.229  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.229  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:51:11.229  6735  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151a08d0 not in the list
07-27 11:51:11.229  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.229  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.229  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.229  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.230  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.230  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.231  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.231  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.231  6735  6792 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:11.231  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:11.231  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.231  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.232  6735  6792 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-27 11:51:11.232  6735  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.232  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.232  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.232  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.232  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.232  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.232  6735  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151a08d0 not in the list
07-27 11:51:11.232  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.232  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.232  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.232  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.232  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.232  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.232  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.234  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.234  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.234  6735  6792 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:11.234  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:11.234  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.234  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.235  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-27 11:51:11.235  6735  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.235  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.235  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.235  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.235  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.235  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.235  6735  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151a08d0 not in the list
07-27 11:51:11.235  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.235  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.235  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.235  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.235  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.235  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.235  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.236  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.236  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.236  6735  6792 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:11.236  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:11.236  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.236  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.237  6735  6792 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-27 11:51:11.237  6735  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.237  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.237  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.237  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.237  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.237  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.237  6735  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151a08d0 not in the list
07-27 11:51:11.237  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.237  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.237  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.237  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.237  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.237  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.237  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.238  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.238  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.238  6735  6792 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:11.238  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:11.238  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.238  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.239  6735  6792 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-27 11:51:11.239  6735  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.239  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.239  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.239  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.239  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.239  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.239  6735  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151a08d0 not in the list
07-27 11:51:11.239  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.239  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.239  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.239  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.239  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.239  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.239  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.240  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.240  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.240  6735  6792 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:11.240  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:11.240  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.240  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.241  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-27 11:51:11.242  6735  6792 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-27 11:51:11.242  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-27 11:51:11.242  6735  6792 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-27 11:51:11.242  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-27 11:51:11.242  6735  6792 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-27 11:51:11.242  6735  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.242  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.242  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.243  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.243  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.243  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.243  6735  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151a08d0 not in the list
07-27 11:51:11.243  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.243  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.243  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.243  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.243  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.243  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.243  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.244  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.244  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.245  6735  6792 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:11.245  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:11.245  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.245  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.245  6735  6792 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 11:51:11.246  6735  6792 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-27 11:51:11.247  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-27 11:51:11.252  6735  6792 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 11:51:11.252  6735  6792 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-27 11:51:11.252  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-27 11:51:11.253  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,07-27 11:51:11.253  6735  6792 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-27 11:51:11.253  6735  6792 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-27 11:51:11.253  6735  6792 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-27 11:51:11.253  6735  6792 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 11:51:11.253  6735  6792 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-27 11:51:11.253  6735  6792 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-27 11:51:11.253  6735  6792 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 11:51:11.253  6735  6792 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-27 11:51:11.253  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
07-27 11:51:11.255  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
07-27 11:51:11.256  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
07-27 11:51:11.257  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
07-27 11:51:11.258  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
07-27 11:51:11.258  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-27 11:51:11.258  6735  6792 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-27 11:51:11.258  6735  6792 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 11:51:11.258  6735  6792 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-27 11:51:11.259  6735  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.259  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.259  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.259  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.259  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.259  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.259  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-27 11:51:11.260  6735  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151a08d0 not in the list
07-27 11:51:11.260  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.260  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.260  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.260  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.260  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.260  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.260  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.261  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.261  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.261  6735  6792 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:11.261  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:11.261  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.262  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.262  6735  6792 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-27 11:51:11.263  6735  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.263  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.263  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.263  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.263  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.263  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.263  6735  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151a08d0 not in the list
07-27 11:51:11.263  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.263  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.263  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.263  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.263  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.263  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.263  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.264  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.264  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.265  6735  6792 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:11.265  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:11.265  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.265  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.266  6735  6792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-27 11:51:11.267  6735  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.267  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.267  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.267  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.267  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.268  6735  6795 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 842
07-27 11:51:11.268  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.268  6735  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151a08d0 not in the list
07-27 11:51:11.268  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.268  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.268  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.268  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.268  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.268  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.268  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.269  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.269  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.269  6735  6792 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:11.269  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:11.270  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.272  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.273  6735  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 842)
07-27 11:51:11.273  6735  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 842)
07-27 11:51:11.274  6735  6792 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-27 11:51:11.274  6735  6792 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-27 11:51:11.274  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-27 11:51:11.275  6735  6792 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-27 11:51:11.275  6735  6792 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-27 11:51:11.275  6735  6792 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-27 11:51:11.275  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-27 11:51:11.275  6735  6792 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-27 11:51:11.275  6735  6792 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-27 11:51:11.275  6735  6792 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-27 11:51:11.275  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-27 11:51:11.275  6735  6792 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-27 11:51:11.275  6735  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.275  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.275  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.276  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.276  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.276  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.276  6735  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151a08d0 not in the list
07-27 11:51:11.276  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.276  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.276  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.276  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.276  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.276  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.276  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.276  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.276  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.277  6735  6792 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:11.277  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:11.277  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.277  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.278  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.278  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.278  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.278  6735  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151a08d0 not in the list
07-27 11:51:11.278  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.278  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.278  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.278  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.278  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.279  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.279  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.279  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.279  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.279  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.279  6735  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151a08d0 not in the list
07-27 11:51:11.279  6735  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.279  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.279  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.280  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.280  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.280  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.280  6735  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151a08d0 not in the list
07-27 11:51:11.280  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.280  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.280  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.280  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.280  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.280  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.280  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.281  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.281  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.281  6735  6792 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:11.281  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:11.281  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.281  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.282  6735  6792 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-27 11:51:11.283  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:51:11.283  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-27 11:51:11.284  6735  6792 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-27 11:51:11.284  6735  6792 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-27 11:51:11.284  6735  6735 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-27 11:51:11.284  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-27 11:51:11.284  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-27 11:51:11.285  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.285  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-27 11:51:11.285  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-27 11:51:11.285  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-27 11:51:11.285  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.285  6735  6792 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-27 11:51:11.286  6735  6735 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-27 11:51:11.286  6735  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151a08d0 not in the list
07-27 11:51:11.286  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.286  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-27 11:51:11.286  6735  6792 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-27 11:51:11.286  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-27 11:51:11.288  6735  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-27 11:51:11.288  6735  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-27 11:51:11.288  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-27 11:51:11.289  6735  6792 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:11.289  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:11.289  6735  6792 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-27 11:51:11.289  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.289  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.290  6735  6792 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 11:51:11.290  6735  6735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 11:51:11.291  6735  6735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 11:51:11.291  6735  6735 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-27 11:51:11.291  6735  6735 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 11:51:11.291  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.291  6735  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.291  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.291  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.291  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.291  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.291  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.291  6735  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151a08d0 not in the list
07-27 11:51:11.291  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.291  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.291  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.291  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.291  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.291  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.291  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.292  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.292  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.292  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.292  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.293  6735  6792 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-27 11:51:11.293  6735  6792 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-27 11:51:11.293  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,07-27 11:51:11.294  6735  6792 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-27 11:51:11.294  6735  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.295  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.295  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.295  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.295  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.295  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.295  6735  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151a08d0 not in the list
07-27 11:51:11.295  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.295  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.295  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.295  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.295  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.295  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.295  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.296  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.296  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.296  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.296  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.299  1037  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:11.300  1037  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:11.301  1037  1871 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:11.301  6735  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.301  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.301  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.302  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.302  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.302  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.302  6735  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151a08d0 not in the list
07-27 11:51:11.302  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.302  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.302  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.302  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.302  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.302  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.302  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.302  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.302  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.303  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.303  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.303  6735  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.303  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.303  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.304  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.304  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.304  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.304  6735  6792 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151a08d0 not in the list
07-27 11:51:11.304  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.304  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.304  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.304  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.304  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.304  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.304  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.304  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.304  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.304  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.305  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba550c9 not in the list
07-27 11:51:11.305  6735  6792 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-27 11:51:11.305  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-27 11:51:11.306  6735  6792 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-27 11:51:11.306  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-27 11:51:11.306  6735  6792 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-27 11:51:11.306  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-27 11:51:11.307  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-27 11:51:11.307  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-27 11:51:11.308  6735  6792 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-27 11:51:11.308  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-27 11:51:11.308  6735  6792 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-27 11:51:11.308  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-27 11:51:11.308  6735  6792 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-27 11:51:11.308  6735  6792 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-27 11:51:11.309  6735  6792 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-27 11:51:11.309  6735  6792 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-27 11:51:11.310  6735  6792 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-27 11:51:11.310  6735  6792 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-27 11:51:11.310  6735  6792 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-27 11:51:11.310  6735  6792 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-27 11:51:11.311  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:11.312  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@21c58ea6 added. We now have 2 listener(s)
07-27 11:51:11.312  6735  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:51:11.313  6735  6792 D BluetoothAdapter: enable(): BT is already enabled..!
07-27 11:51:11.314  1037  2028 D WifiServiceImplEx: setWifiEnabled: true pid=6735, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-27 11:51:11.314  1037  2028 D WifiService: setWifiEnabled: true pid=6735, uid=10118
07-27 11:51:11.314  1037  2028 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-27 11:51:11.315  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:11.315  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cf880e7 added. We now have 3 listener(s)
07-27 11:51:11.315  6735  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:51:11.318  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:11.318  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@16bf7494 added. We now have 4 listener(s)
07-27 11:51:11.318  6735  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:51:11.319  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:11.319  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@381eb3d added. We now have 5 listener(s)
07-27 11:51:11.319  6735  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:51:11.321  1037  1766 D WifiServiceImplEx: setWifiEnabled: false pid=6735, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-27 11:51:11.321  1037  1766 D WifiService: setWifiEnabled: false pid=6735, uid=10118
07-27 11:51:11.321  1037  1766 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-27 11:51:11.330  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 11:51:11.330  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-27 11:51:11.330  1037  1037 D Ulp_jni : JNI:system_update. Event-4
07-27 11:51:11.331  1037  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
07-27 11:51:11.331  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
,07-27 11:51:11.331  1037  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
07-27 11:51:11.331  1037  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
07-27 11:51:11.332  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
07-27 11:51:11.332  1037  1523 E WifiStateMachine: WifiStateMachine: Leaving Connected state
07-27 11:51:11.332  1037  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 11:51:11.332  1037  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-27 11:51:11.332  1037  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-27 11:51:11.332  1037  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-27 11:51:11.333  1037  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:11.334  1037  1998 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@224e8426 mBinding = false
07-27 11:51:11.336  1037  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-27 11:51:11.336  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-27 11:51:11.336  1037  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:11.337  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:11.337  2730  2730 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-27 11:51:11.337  1037  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-27 11:51:11.337  1037  1523 D WifiNative-wlan0: doBoolean: SET ps 1
07-27 11:51:11.338  1037  1523 D WifiNative-wlan0: SET ps 1: returned true
07-27 11:51:11.338  1037  2846 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:11.338   332   895 D CommandListener: Clearing all IP addresses on wlan0
07-27 11:51:11.348  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 11:51:11.348  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-27 11:51:11.349  1037  1037 D Ulp_jni : JNI:system_update. Event-4
07-27 11:51:11.357  1037  1120 D BluetoothManagerService: Message: 2
07-27 11:51:11.358  1037  1120 D BluetoothManagerService: Sending off request.
07-27 11:51:11.358  3858  3885 D LGBluetoothServiceAdapter: [BTUI] Precleanup
07-27 11:51:11.359  3858  3973 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
07-27 11:51:11.359  3858  3973 D BluetoothAdapterProperties: Setting state to 13
07-27 11:51:11.359  3858  3973 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-27 11:51:11.363  3858  3973 D BluetoothAdapterProperties: onBluetoothDisable()
07-27 11:51:11.363  3858  3973 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-27 11:51:11.364  1037  1120 D BluetoothManagerService: Message: 60
07-27 11:51:11.364  1037  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
07-27 11:51:11.364  1037  1120 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,07-27 11:51:11.392  1037  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-27 11:51:11.393  1037  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
07-27 11:51:11.393  1037  1111 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6803 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-27 11:51:11.399  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:11.400  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-27 11:51:11.402  3858  3858 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:11.402  3858  3858 D BluetoothMapService: STATE_TURNING_OFF
07-27 11:51:11.402  3858  3858 V BluetoothMapService: Handler(): got msg=4
07-27 11:51:11.402  3858  3858 D BluetoothMapService: MAP Service closeService in
07-27 11:51:11.402  3858  3858 D BluetoothMapMasInstance: MAP Service shutdown
07-27 11:51:11.404  3858  4182 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
07-27 11:51:11.404  3858  4182 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 11:51:11.404  3858  4182 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
07-27 11:51:11.404  3858  4182 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
07-27 11:51:11.404  3858  4182 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
07-27 11:51:11.404  3858  4182 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
07-27 11:51:11.404  3858  4182 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
07-27 11:51:11.404  3858  4182 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
07-27 11:51:11.404  3858  3858 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-27 11:51:11.404  3858  3858 V BluetoothMapService: MAP Service closeService out
07-27 11:51:11.404  3858  3858 V BtOppService: Receiver DISABLED_ACTION 
07-27 11:51:11.404  3858  3858 I BtOppRfcommListener: stopping Accept Thread
07-27 11:51:11.404  3858  3858 V BtOppRfcommListener: close mBtServerSocket
07-27 11:51:11.405  3858  3858 V BtOppRfcommListener: waiting for thread to terminate
07-27 11:51:11.405  3858  4219 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 11:51:11.405  3858  4219 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-27 11:51:11.405  3858  3858 V BtOppRfcommListener: done waiting for thread to terminate
07-27 11:51:11.407  6735  6735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:11.407  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:11.407  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:11.407  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:11.407  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:11.407  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:51:11.407  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:11.407  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:11.407  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 11:51:11.414  3858  3858 V BtOppService: onDestroy
07-27 11:51:11.417  6735  6735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:11.417  6735  6735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:51:11.420  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 0
07-27 11:51:11.421  1037  1037 D WifiHS20: hidePasspointNotification off =false
07-27 11:51:11.421  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:11.421  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:11.421  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-27 11:51:11.421  1037  1037 D WifiHS20: hidePasspointNotification off =false
07-27 11:51:11.421  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:11.421  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:11.421  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-27 11:51:11.428  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 1
07-27 11:51:11.428  1037  1037 D RttService: SCAN_AVAILABLE : 1
07-27 11:51:11.428  1037  1542 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:11.428  1037  1541 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:11.429  1037  1522 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:11.429  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:11.429  1037  1522 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1f527ee2
07-27 11:51:11.429  1037  1522 D LGWifiP2pService: P2pDisablingState
07-27 11:51:11.430  1037  1522 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:11.430  1037  1522 D LGWifiP2pService: p2p socket connection lost
07-27 11:51:11.430  1037  1522 D LGWifiP2pService: P2pDisabledState
07-27 11:51:11.430  1037  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:11.430  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:11.430  1037  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:11.431  1037  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:11.431  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:11.431  1037  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:11.432  1037  1523 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-27 11:51:11.432  1037  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
,07-27 11:51:11.440  1037  1522 D LGWifiP2pService: P2pDisabledState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:11.440  1037  1522 D LGWifiP2pService: DefaultState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:11.440  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,07-27 11:51:11.440  2730  2730 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-27 11:51:11.441  1037  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-27 11:51:11.441  1037  1523 D WifiNative-wlan0: doBoolean: SET ps 1
07-27 11:51:11.441  1037  1523 D WifiNative-wlan0: SET ps 1: returned true
07-27 11:51:11.446  6426  6426 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:51:11.446  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-27 11:51:11.446  1927  1927 D WfdsService: WifiP2pState is changed : false
07-27 11:51:11.447  1927  2323 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
07-27 11:51:11.447  1927  2323 D WfdsService: Set the WFDS Monitor: false
,07-27 11:51:11.448  1927  2323 D WfdsMonitor: WFDS Monitor is stopped
07-27 11:51:11.448  1927  2323 D WfdsService: STATE : WfdsDisabledState - enter
07-27 11:51:11.448  1927  2765 D CtrlSupplicant: Received on exit socket, terminate
07-27 11:51:11.448  1927  2765 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
07-27 11:51:11.448  1927  2765 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
07-27 11:51:11.448  1927  2765 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
07-27 11:51:11.448  1927  2323 W WfdsService: DefaultState - msg [9445378] is not handled
07-27 11:51:11.449  1927  2326 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
07-27 11:51:11.451  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:11.451  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:51:11.452  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:11.453  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:11.453  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:51:11.454  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:11.454   332   895 D CommandListener: Clearing all IP addresses on wlan0
07-27 11:51:11.455  1037  1530 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
07-27 11:51:11.456  1037  1530 D DSQN    : disableDataServiceNotify
07-27 11:51:11.456  1037  1530 D DSQN    : stop dsqn bin
07-27 11:51:11.457  1037  1523 D WifiNative-p2p0: doBoolean: TERMINATE
07-27 11:51:11.457  1037  1523 D WifiNative-p2p0: TERMINATE: returned true
07-27 11:51:11.458  1037  1037 D WifiHS20: hidePasspointNotification off =false
,07-27 11:51:11.458  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:11.458  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:11.458  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-27 11:51:11.458  1037  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-27 11:51:11.458  1037  1523 E WifiStateMachine: useWiFiOffloading() : false
07-27 11:51:11.458  1037  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-27 11:51:11.461  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
07-27 11:51:11.462  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
07-27 11:51:11.462  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:51:11.462  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
07-27 11:51:11.463  6735  6735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:11.463  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:11.463  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:11.463  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:11.463  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:51:11.463  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:51:11.463  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:11.463  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:11.463  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:51:11.463  6735  6735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:11.464  6735  6735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:51:11.468  1037  1530 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-27 11:51:11.468  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:11.468  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:51:11.468  1037  1530 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:51:11.469  1037  1530 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
07-27 11:51:11.469  1037  1530 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  w,asFirstNetwork :true
07-27 11:51:11.469  1037  1530 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-27 11:51:11.469  1037  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-27 11:51:11.470  1037  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:11.470  1037  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-27 11:51:11.470  1037  2845 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:11.470  1037  2845 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:11.471  1037  2845 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-27 11:51:11.471  1037  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:11.471  1037  1530 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:11.471  1037  1530 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:11.471  1037  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-27 11:51:11.471  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-27 11:51:11.471  1037  1530 D NetworkManagementService: Removing idletimer
07-27 11:51:11.471  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-27 11:51:11.471  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-27 11:51:11.471  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-27 11:51:11.472  1037  1530 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:11.472  1587  2056 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
07-27 11:51:11.472  1037  1530 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
07-27 11:51:11.472  1037  1523 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:11.472  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-27 11:51:11.472  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:51:11.472  1037  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:51:11.473  1837  1837 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:11.473  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-27 11:51:11.473  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:11.473  1037  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1,
07-27 11:51:11.473  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-27 11:51:11.473  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-27 11:51:11.473  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-27 11:51:11.473  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-27 11:51:11.498  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 11:51:11.521  1037  1641 I art     : Explicit concurrent mark sweep GC freed 37794(1967KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 5.719ms total 161.758ms
07-27 11:51:11.522  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 11:51:11.526  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:11.526  6735  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:51:11.526  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:11.526  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:11.526  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:51:11.526  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:51:11.526  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:11.526  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:11.526  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:51:11.526  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:11.526  6735  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:51:11.526  6735  6792 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:51:11.528  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:11.532  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:11.539  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-27 11:51:11.539  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:11.540  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:11.543  1037  2846 D DhcpStateMachine: StoppedState
07-27 11:51:11.544  1037  2846 D DhcpStateMachine: StoppedState{ when=-102ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:11.546  6803  6803 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 11:51:11.547  6803  6803 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
07-27 11:51:11.547  6803  6803 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 11:51:11.548  6803  6803 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
07-27 11:51:11.549  6803  6803 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,07-27 11:51:11.549  6803  6803 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-27 11:51:11.557  1037  1997 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6833 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-27 11:51:11.558  3858  3976 D BluetoothAdapterProperties: Scan Mode:20
07-27 11:51:11.558  3858  3973 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-27 11:51:11.559  3858  3973 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-27 11:51:11.560  1037  1523 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
,07-27 11:51:11.561  1037  1523 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
07-27 11:51:11.561  6735  6735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:11.561  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:11.561  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:11.561  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:11.561  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:51:11.561  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:51:11.561  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:11.561  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:11.561  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:51:11.561  3858  4183 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 11:51:11.561  3858  4043 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
07-27 11:51:11.561  3858  4043 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
07-27 11:51:11.562  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:11.562  3858  4043 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 11:51:11.562  3858  4043 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 11:51:11.562  3858  4043 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 11:51:11.562  3858  4043 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 11:51:11.562  3858  4043 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:51:11.562  3858  4043 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 11:51:11.562  3858  4043 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:51:11.562  3858  4043 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 11:51:11.562  3858  4043 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 11:51:11.562  3858  4043 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
07-27 11:51:11.562  3858  4043 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
07-27 11:51:11.562  3858  4043 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-27 11:51:11.562  3858  4221 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 11:51:11.563  3858  4223 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 11:51:11.563  3858  3858 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
07-27 11:51:11.582  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-27 11:51:11.583  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:11.583  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 11:51:11.588  2730  2730 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-27 11:51:11.588  2730  2730 I wpa_supplicant: monitor socket send errors count : 1
07-27 11:51:11.588  2730  2730 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1927-2\x00 that cannot receive messages
07-27 11:51:11.590  1037  2763 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
07-27 11:51:11.590  1037  2763 D WifiMonitor: Dropping event because (p2p0) is stopped
07-27 11:51:11.618  6833  6833 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-27 11:51:11.620  6833  6833 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-27 11:51:11.620  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-27 11:51:11.624  1037  1944 I ActivityManager: Killing 6197:com.android.providers.calendar/u0a14 (adj 15): empty #17
07-27 11:51:11.628  2730  2730 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-27 11:51:11.628  1037  2763 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
07-27 11:51:11.628  1037  2763 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-27 11:51:11.628  1037  2763 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-27 11:51:11.629  1037  2763 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
07-27 11:51:11.629  1037  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=299457
07-27 11:51:11.629  1037  1120 D Tethering: InitialState.processMessage what=4
07-27 11:51:11.629  2730  2730 W wpa_supplicant: USIM:  scard_deinit function
07-27 11:51:11.629  1037  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=299457
07-27 11:51:11.630  1037  2763 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 11:51:11.630  1037  2763 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 11:51:11.632  1037  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=299460  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-27 11:51:11.632  1037  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=299460  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,07-27 11:51:11.656  6803  6803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,07-27 11:51:11.816  1037  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-27 11:51:11.816  1037  1766 W libprocessgroup: failed to open /acct/uid_10014/pid_6197/cgroup.procs: No such file or directory
,07-27 11:51:11.832  2730  2730 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-27 11:51:11.832  1037  2763 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
07-27 11:51:11.833  1037  2763 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
07-27 11:51:11.833  1037  2763 D WifiMonitor: Disconnecting from the supplicant, no more events
07-27 11:51:11.836  1037  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,07-27 11:51:11.849  3858  3858 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-27 11:51:11.849  3858  3858 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:11.849  3858  3858 V BluetoothPbapReceiver: ***********state = 13
07-27 11:51:11.852  3858  3858 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
07-27 11:51:11.855  3858  3858 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:11.855  3858  3858 V BluetoothPbapService: state: 13
07-27 11:51:11.855  3858  3858 V BluetoothPbapService: Pbap Service closeService in
,07-27 11:51:11.861  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-27 11:51:11.864  3858  3858 V BluetoothPbapService: successfully stopped pbap service
07-27 11:51:11.864  3858  3858 V BluetoothPbapService: Pbap Service closeService out
07-27 11:51:11.864  3858  3858 V BluetoothPbapService: Pbap Service onDestroy
07-27 11:51:11.864  3858  3858 V BluetoothPbapService: Pbap Service closeService in
,07-27 11:51:11.864  3858  3858 V BluetoothPbapService: Pbap Service closeService out
,07-27 11:51:11.865  3858  3858 D LGBluetoothPbapAdapter: [BTUI] cleanup
07-27 11:51:11.872  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 11:51:11.907  6803  6803 D LgDataFeature: LgDataFeature() Constructor: none
07-27 11:51:11.908  6803  6803 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 11:51:11.920  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-27 11:51:11.930  1037  1120 D BluetoothManagerService: Message: 20
07-27 11:51:11.930  1037  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@320e8f80:true
07-27 11:51:11.940  1037  2028 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6854 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,07-27 11:51:11.944  1927  1927 D WfdsService: Supplicant Connection state is changed : false
07-27 11:51:11.944  1927  2323 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
07-27 11:51:11.944  1927  2323 D WfdsService: Set the WFDS Monitor: false
07-27 11:51:11.944  1927  2323 D WfdsMonitor: WFDS Monitor is stopped
07-27 11:51:11.946  1037  1523 D WifiOffDelayIfNotUsed: stopMonitoring
07-27 11:51:11.946  1037  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-27 11:51:11.946  1037  1523 E WifiStateMachine: useWiFiOffloading() : false
07-27 11:51:11.946  1037  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-27 11:51:11.948  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
07-27 11:51:11.949  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:11.949  1037  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
07-27 11:51:11.949  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-27 11:51:11.949  1037  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
07-27 11:51:11.950  2455  2455 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:11.953  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:11.955  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:11.957  1037  1120 D BluetoothManagerService: Message: 30
07-27 11:51:11.961   355   355 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 436us total 19.460ms
,07-27 11:51:11.964  1037  1120 D BluetoothManagerService: Message: 30
07-27 11:51:11.968  6803  6803 D LocalBluetoothProfileManager: Adding local MAP profile
07-27 11:51:11.971  6803  6803 D BluetoothMap: Create BluetoothMap proxy object
07-27 11:51:11.972  1037  1120 D BluetoothManagerService: Message: 30
07-27 11:51:11.979   355   355 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 409us total 16.968ms
,07-27 11:51:11.980  1037  1120 D BluetoothManagerService: Message: 30
07-27 11:51:11.982  6803  6803 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-27 11:51:11.983  6803  6803 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
07-27 11:51:11.997  6803  6803 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,07-27 11:51:12.000   355   355 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 403us total 20.475ms
07-27 11:51:12.001  6803  6803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
07-27 11:51:12.009  6803  6803 D DockEventReceiver: finishStartingService: stopping service
07-27 11:51:12.018  6803  6803 D BluetoothInputDevice: Proxy object connected
07-27 11:51:12.019  6803  6803 D HidProfile: Bluetooth service connected
,07-27 11:51:12.020  6803  6803 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 11:51:12.020  6803  6803 D PanProfile: Bluetooth service connected
07-27 11:51:12.021  6803  6803 D BluetoothMap: Proxy object connected
07-27 11:51:12.022  6803  6803 D MapProfile: Bluetooth service connected
07-27 11:51:12.022  6803  6803 D BluetoothMap: getConnectedDevices()
07-27 11:51:12.022  6803  6803 D BluetoothMap: Bluetooth is Not enabled
07-27 11:51:12.023  6803  6803 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-27 11:51:12.074  1037  1766 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6878 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,07-27 11:51:12.079  1037  1766 I ActivityManager: Killing 2112:com.lge.music/u0a34 (adj 15): empty #17
07-27 11:51:12.104   336  1371 V AudioFlinger: 2112 died, releasing its sessions
07-27 11:51:12.104   336  1371 V AudioFlinger:  pid 1837 @ 0
07-27 11:51:12.105   336  1371 V AudioFlinger:  pid 3414 @ 1
07-27 11:51:12.105   336  1371 V AudioFlinger:  pid 3414 @ 2
,07-27 11:51:12.120  6854  6854 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
07-27 11:51:12.121  6854  6854 W LG Account v2.2: No ProfileInfo entries
07-27 11:51:12.121  6854  6854 I LG Account v2.2: isEnabled: false
07-27 11:51:12.121  6854  6854 I Feature : [Lifetracker]ver: 4.21.112(40211120)
,07-27 11:51:12.122  6854  6854 I Feature : [Lifetracker]Country: EU
07-27 11:51:12.122  6854  6854 I Feature : [Lifetracker]Operator: OPEN
07-27 11:51:12.122  6854  6854 I Feature : [Lifetracker]Ranking support: false
07-27 11:51:12.122  6854  6854 I Feature : [Lifetracker]Comfort support: false
07-27 11:51:12.122  6854  6854 I Feature : [Lifetracker]Accessory: true
07-27 11:51:12.122  6854  6854 I Feature : [Lifetracker]Health device: true
07-27 11:51:12.123  6854  6854 I Feature : [Lifetracker]Extra Pedometer: false
07-27 11:51:12.123  6854  6854 I Feature : [Lifetracker]Blood glucose device: false
07-27 11:51:12.123  6854  6854 I Feature : [Lifetracker]Device Number: 3
07-27 11:51:12.128  1037  2028 W libprocessgroup: failed to open /acct/uid_10034/pid_2112/cgroup.procs: No such file or directory
07-27 11:51:12.143  6803  6803 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,07-27 11:51:12.148  1037  1523 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:51:12.149  1037  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:51:12.151  6803  6803 D BluetoothPermissionRequest: onReceive
07-27 11:51:12.153  6803  6803 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,07-27 11:51:12.167  6803  6803 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,07-27 11:51:12.171  6878  6878 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 11:51:12.171  1037  1998 I ActivityManager: Killing 6487:com.google.android.partnersetup/u0a8 (adj 15): empty #17
07-27 11:51:12.231  3858  3858 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,07-27 11:51:12.232  3858  3858 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
07-27 11:51:12.232  1037  1871 W libprocessgroup: failed to open /acct/uid_10008/pid_6487/cgroup.procs: No such file or directory
07-27 11:51:12.233  3858  3858 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
07-27 11:51:12.249  6878  6878 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,07-27 11:51:12.253  3858  3858 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:12.253  3858  3858 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-27 11:51:12.257  3858  3858 V BluetoothFtpService: Ftp Service onStartCommand
07-27 11:51:12.257  3858  3858 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:12.258  3858  3858 V BluetoothFtpService: Ftp Service closeService
07-27 11:51:12.258  3858  3858 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
07-27 11:51:12.264  3858  3858 V BluetoothFtpService: successfully stopped ftp service
07-27 11:51:12.265  3858  3858 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 11:51:12.265  3858  3858 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-27 11:51:12.265  3858  3858 V BluetoothSapReceiver: SapReceiver onReceive 
07-27 11:51:12.266  3858  3858 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:12.266  3858  3858 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
07-27 11:51:12.266  3858  3858 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-27 11:51:12.269  3858  3858 V BluetoothFtpService: Ftp Service onDestroy
07-27 11:51:12.269  3858  3858 V BluetoothFtpService: Ftp Service closeService
,07-27 11:51:12.297  6878  6878 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,07-27 11:51:12.298  6878  6878 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
07-27 11:51:12.298  6878  6878 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
07-27 11:51:12.299  6878  6878 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
07-27 11:51:12.299  6878  6878 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
07-27 11:51:12.301  6878  6878 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
07-27 11:51:12.307  6878  6878 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
07-27 11:51:12.345  1037  1641 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6900 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-27 11:51:12.349  3858  3858 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:12.349  3858  3858 V BluetoothSapService: state: 13
07-27 11:51:12.350  3858  3858 V BluetoothSapService: Stopping SAP server process
07-27 11:51:12.351  3858  3858 V BluetoothSapService: Sap Service closeSapService in
07-27 11:51:12.351  3858  3858 V BluetoothSapService: Close listen Socket : 
07-27 11:51:12.351  3858  3858 V BluetoothSapService: Close rfcomm Socket : 
07-27 11:51:12.352  3858  3858 V BluetoothSapService: Close sapd  Socket : 
07-27 11:51:12.353  3858  3858 V BluetoothSapService: Sap Service closeSapService out
07-27 11:51:12.353  3858  3858 V BluetoothSapService: Sap Service onDestroy
07-27 11:51:12.353  3858  3858 V BluetoothSapService: Sap Service closeSapService in
07-27 11:51:12.353  3858  3858 V BluetoothSapService: Close listen Socket : 
07-27 11:51:12.353  3858  3858 V BluetoothSapService: Close rfcomm Socket : 
07-27 11:51:12.353  3858  3858 V BluetoothSapService: Close sapd  Socket : 
07-27 11:51:12.354  3858  3858 V BluetoothSapService: Sap Service closeSapService out
07-27 11:51:12.379  6878  6878 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-27 11:51:12.381  6878  6878 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:51:12.397  6878  6878 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-27 11:51:12.401  6878  6878 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
07-27 11:51:12.406  6426  6426 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:51:12.408  6878  6878 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
07-27 11:51:12.411  6833  6833 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,07-27 11:51:12.412  6833  6833 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-27 11:51:12.412  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 11:51:12.417  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:51:12.423  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:12.425  6900  6900 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 11:51:12.430  6878  6878 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:51:12.430  6878  6878 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:51:12.432  6878  6878 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-27 11:51:12.435  6426  6426 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 11:51:12.440  6833  6833 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-27 11:51:12.440  6833  6833 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-27 11:51:12.440  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 11:51:12.443  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:51:12.451  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-27 11:51:12.456  1037  1997 I ActivityManager: Killing 6055:com.lge.appbox.client/u0a11 (adj 15): empty #17
07-27 11:51:12.492  6878  6878 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:51:12.492  6878  6878 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-27 11:51:12.493  1037  1998 W libprocessgroup: failed to open /acct/uid_10011/pid_6055/cgroup.procs: No such file or directory
07-27 11:51:12.499  6878  6878 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-27 11:51:12.566  3858  3976 D bt_hci_bdroid: cleanup
07-27 11:51:12.566  3858  4045 I bt_lpm  : LPM is already off!!!
07-27 11:51:12.566  3858  4043 W bt-btif : ag scb idx 1 not allocated
07-27 11:51:12.566  3858  4043 E bt-btif : BTA AG is already disabled, ignoring ...
07-27 11:51:12.566  3858  4043 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 11:51:12.566  3858  4043 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:51:12.566  3858  4043 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 11:51:12.566  3858  4043 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:51:12.566  3858  4043 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 11:51:12.566  3858  4043 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 11:51:12.566  3858  4043 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 11:51:12.566  3858  4043 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:51:12.566  3858  4043 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 11:51:12.566  3858  4043 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:51:12.566  3858  4043 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 11:51:12.566  3858  4043 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 11:51:12.566  3858  4043 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 11:51:12.566  3858  4043 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:51:12.566  3858  4043 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 11:51:12.566  3858  4043 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:51:12.566  3858  4043 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 11:51:12.566  3858  4043 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 11:51:12.566  3858  4043 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,07-27 11:51:12.568  3858  4171 I bt_userial_mct: exiting userial_read_thread
07-27 11:51:12.568  3858  4171 D bt_userial_mct: Leaving userial_evt_read_thread()
07-27 11:51:12.569  3858  3976 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
07-27 11:51:12.569  3858  4045 I bt_vendor: hw_epilog_process
07-27 11:51:12.570  3858  3976 D bt_hci_bdroid: cleanup Finalizing cleanup
07-27 11:51:12.570  3858  3976 D bt_userial_mct: userial_close
07-27 11:51:12.570  3858  3976 E bt_userial_mct: pthread_join() FAILED result:3
07-27 11:51:12.570  3858  3976 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
07-27 11:51:12.577  1037  1908 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6921 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,07-27 11:51:12.638  3858  3976 D bt_hci_bdroid: set_power 0
07-27 11:51:12.638  3858  3976 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
07-27 11:51:12.638  3858  3976 I bt_vendor: bluetooth satus is on
07-27 11:51:12.638  3858  3976 I bt_vendor: bt-vendor : resetting BT status
07-27 11:51:12.638  3858  3976 I bt_vendor: Starting hciattach daemon
07-27 11:51:12.638  3858  3976 I bt_vendor: try to set false
07-27 11:51:12.640  3858  3976 I bt_vendor: Starting hciattach daemon
07-27 11:51:12.640  3858  3976 I bt_vendor: try to set false
,07-27 11:51:12.642  3858  3976 I bt_vendor: cleanup
07-27 11:51:12.643  3858  4043 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-27 11:51:12.644  3858  3976 I GKI_LINUX: GKI_exit_task 0 done
07-27 11:51:12.644  3858  3976 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
07-27 11:51:12.648  3858  3973 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-27 11:51:12.651  3858  3858 D HeadsetService: Received stop request...Stopping profile...
07-27 11:51:12.654  3858  3858 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,07-27 11:51:12.654  3858  3858 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-27 11:51:12.654  3858  3858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@afa8b0d
07-27 11:51:12.654  3858  3992 D HeadsetStateMachine: Exit Disconnected: -1
07-27 11:51:12.658  1037  1037 D BluetoothHeadset: Proxy object disconnected
07-27 11:51:12.658  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-27 11:51:12.659  1837  1837 D BluetoothHeadset: Proxy object disconnected
07-27 11:51:12.659  1837  1837 D BluetoothHeadset: Proxy object disconnected
07-27 11:51:12.661  1837  1837 D BluetoothHeadset: Proxy object disconnected
07-27 11:51:12.661  3858  3858 D A2dpService: Received stop request...Stopping profile...
07-27 11:51:12.662  3858  4027 D A2dpStateMachine: Exit Disconnected: -1
07-27 11:51:12.662  3858  3858 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
07-27 11:51:12.665  3858  3858 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
07-27 11:51:12.665  3858  3858 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
07-27 11:51:12.665  3858  3858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@afa8b0d
07-27 11:51:12.667  1037  1037 D BluetoothA2dp: Proxy object disconnected
07-27 11:51:12.667  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,07-27 11:51:12.669  3858  3858 D HidService: Received stop request...Stopping profile...,
07-27 11:51:12.669  3858  3858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@afa8b0d
07-27 11:51:12.671  3858  3973 D BluetoothAdapterState: Stopping profile services that were post enabled
07-27 11:51:12.671  3858  3858 D HeadsetStateMachine: Unbinding service...
07-27 11:51:12.672  6803  6803 D BluetoothInputDevice: Proxy object disconnected
07-27 11:51:12.672  6803  6803 D HidProfile: Bluetooth service disconnected
07-27 11:51:12.672  3858  3858 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-27 11:51:12.672  3858  3858 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-27 11:51:12.673  3858  3858 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-27 11:51:12.673  3858  3858 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-27 11:51:12.673  3858  3858 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-27 11:51:12.673  3858  3858 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-27 11:51:12.673  3858  3858 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-27 11:51:12.673  3858  3858 D HealthService: Received stop request...Stopping profile...
07-27 11:51:12.674  3858  3858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@afa8b0d
07-27 11:51:12.676  3858  3858 D PanService: Received stop request...Stopping profile...
07-27 11:51:12.676  3858  3858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@afa8b0d
07-27 11:51:12.677  3858  3858 D BtGatt.DebugUtils: handleDebugAction() action=null
07-27 11:51:12.678  3858  3858 D BtGatt.GattService: Received stop request...Stopping profile...
07-27 11:51:12.678  6803  6803 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-27 11:51:12.678  6803  6803 D PanProfile: Bluetooth service disconnected
07-27 11:51:12.678  3858  3858 D BtGatt.GattService: stop()
07-27 11:51:12.678  3858  3858 D BtGatt.AdvertiseManager: advertise clients cleared
07-27 11:51:12.679  3858  3858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@afa8b0d
07-27 11:51:12.680  3858  3858 I BluetoothA2dpServiceJni: cleanupNative
07-27 11:51:12.680  3858  4028 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-27 11:51:12.680  3858  3858 I GKI_LINUX: GKI_exit_task 2 done
07-27 11:51:12.680  3858  3858 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-27 11:51:12.682  3858  3858 D BluetoothMapService: Received stop request...Stopping profile...
07-27 11:51:12.683  3858  3858 D BluetoothMapService: stop()
07-27 11:51:12.683  3858  3858 D BluetoothMapEmailAppObserver: deinitObservers()
07-27 11:51:12.683  3858  3858 D BluetoothMapEmailAppObserver: removeReceiver()
07-27 11:51:12.684  3858  3858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@afa8b0d
07-27 11:51:12.686  3858  3858 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-27 11:51:12.686  3858  3858 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-27 11:51:12.686  6803  6803 D BluetoothMap: Proxy object disconnected
07-27 11:51:12.686  6803  6803 D MapProfile: Bluetooth service disconnected
07-27 11:51:12.686  3858  3858 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-27 11:51:12.686  3858  3858 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-27 11:51:12.686  3858  3858 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-27 11:51:12.686  3858  3858 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-27 11:51:12.686  3858  3858 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,07-27 11:51:12.689  3858  3858 V BluetoothMapService: Handler(): got msg=4
,07-27 11:51:12.689  3858  3858 D BluetoothMapService: MAP Service closeService in
07-27 11:51:12.689  3858  3858 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-27 11:51:12.689  3858  3858 V BluetoothMapService: MAP Service closeService out
07-27 11:51:12.689  3858  3973 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
07-27 11:51:12.690  3858  3973 D BluetoothAdapterProperties: Setting state to 10
07-27 11:51:12.690  3858  3973 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-27 11:51:12.690  3858  3858 D BluetoothMapService: cleanup()
07-27 11:51:12.690  3858  3858 D BluetoothMapService: MAP Service closeService in
07-27 11:51:12.690  3858  3858 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-27 11:51:12.690  3858  3858 V BluetoothMapService: MAP Service closeService out
07-27 11:51:12.691  1037  1120 D BluetoothManagerService: Message: 60
07-27 11:51:12.691  1037  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
07-27 11:51:12.691  1037  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
07-27 11:51:12.692  6803  6819 D BluetoothMap: onBluetoothStateChange: up=false
07-27 11:51:12.692  3858  3973 I BluetoothAdapterState: Entering OffState
07-27 11:51:12.692  1837  3991 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 11:51:12.694  6803  6821 D BluetoothPan: onBluetoothStateChange on: false
07-27 11:51:12.695  1837  2507 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 11:51:12.696  1037  1120 D BluetoothA2dp: onBluetoothStateChange: up=false
07-27 11:51:12.696  6803  6819 D BluetoothPbap: onBluetoothStateChange: up=false
07-27 11:51:12.697  1037  1120 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 11:51:12.697  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 11:51:12.698  6803  6821 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-27 11:51:12.699  1037  1120 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
07-27 11:51:12.699  1037  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
07-27 11:51:12.702  1037  1120 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
07-27 11:51:12.702  1037  1120 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
07-27 11:51:12.702  1037  1120 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@224e8426 mBinding = false
07-27 11:51:12.703  1037  1120 D BluetoothManagerService: Sending unbind request.
07-27 11:51:12.704  1037  1120 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
07-27 11:51:12.706  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:12.707  1927  2132 D LGBluetoothAPIService: Message: 2
07-27 11:51:12.707  1927  2132 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@187484f4 mBinding = false
07-27 11:51:12.707  1927  2132 D LGBluetoothAPIService: Sending unbind request.
07-27 11:51:12.708  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-27 11:51:12.708  6803  6803 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-27 11:51:12.709  6803  6803 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
07-27 11:51:12.709  6803  6803 D LGBluetoothEventManager: [BTUI] clear device connection state
07-27 11:51:12.710  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:12.711  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:12.715  1587  1587 D BluetoothAdapter: 829040965: getState() :  mService = null. Returning STATE_OFF
07-27 11:51:12.715  1587  1587 D BluetoothAdapter: 829040965: getState() :  mService = null. Returning STATE_OFF
07-27 11:51:12.718  6803  6803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-27 11:51:12.730  3858  3976 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,07-27 11:51:12.732  3858  3858 I GKI_LINUX: GKI_exit_task 1 done
07-27 11:51:12.732  3858  3858 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
07-27 11:51:12.733  3858  3858 I BluetoothServiceJni: cleanupNative: return from cleanup
07-27 11:51:12.733  3858  3858 I art     : --- WEIRD: removing null entry 246
07-27 11:51:12.733  3858  3858 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
07-27 11:51:12.733  3858  3858 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
07-27 11:51:12.735  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 11:51:12.735  3858  3858 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
07-27 11:51:12.736  6803  6803 D DockEventReceiver: finishStartingService: stopping service
07-27 11:51:12.739  3858  3858 I art     : System.exit called, status: 0
07-27 11:51:12.739  3858  3858 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-27 11:51:12.745  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:51:12.759   336  1372 V AudioFlinger: 3858 died, releasing its sessions
07-27 11:51:12.759   336  1372 V AudioFlinger:  pid 1837 @ 0
07-27 11:51:12.759   336  1372 V AudioFlinger:  pid 3414 @ 1
07-27 11:51:12.759   336  1372 V AudioFlinger:  pid 3414 @ 2
07-27 11:51:12.764  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:12.765  6803  6803 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
07-27 11:51:12.858  1037  1944 I ActivityManager: Process com.android.bluetooth (pid 3858) has died
07-27 11:51:12.858  1037  1944 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,07-27 11:51:12.878  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-27 11:51:12.893  6921  6943 W FormManager: Network not available. Please check & try again.
,07-27 11:51:12.925  6921  6948 V FormManager: Network unavailable.
,07-27 11:51:12.935  6803  6803 D BluetoothPermissionRequest: onReceive
07-27 11:51:12.937  6921  6948 V FormManager: Network unavailable.
07-27 11:51:12.940  6803  6803 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-27 11:51:12.941  6803  6803 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,07-27 11:51:12.948  6803  6803 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,07-27 11:51:12.955  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,07-27 11:51:12.955  6803  6803 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,07-27 11:51:12.955  6803  6803 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,07-27 11:51:12.955  6803  6803 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-27 11:51:12.957  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,07-27 11:51:13.025  1037  1998 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6952 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,07-27 11:51:13.031  1037  1574 I ActivityManager: Killing 6078:com.android.contacts/u0a19 (adj 15): empty #17
07-27 11:51:13.090  1037  1872 W libprocessgroup: failed to open /acct/uid_10019/pid_6078/cgroup.procs: No such file or directory
,07-27 11:51:13.108  6803  6803 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-27 11:51:13.108  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
,07-27 11:51:13.109  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-27 11:51:13.109  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-27 11:51:13.109  6803  6803 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-27 11:51:13.110  6803  6803 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-27 11:51:13.118  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-27 11:51:13.119  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 11:51:13.122  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 11:51:13.126  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-27 11:51:13.128  6952  6952 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
07-27 11:51:13.128  6952  6952 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 11:51:13.129  6952  6952 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
07-27 11:51:13.129  6952  6952 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-27 11:51:13.136  4297  6970 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-27 11:51:13.141  4297  6972 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-27 11:51:13.141  4297  6972 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-27 11:51:13.143  6833  6833 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
07-27 11:51:13.146  6833  6833 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-27 11:51:13.146  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-27 11:51:13.151  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-27 11:51:13.153  6921  6973 W FormManager: Network not available. Please check & try again.
07-27 11:51:13.157  6921  6974 V FormManager: Network unavailable.
07-27 11:51:13.157  6952  6952 D BluetoothAdapterApp: Loading JNI Library
,07-27 11:51:13.161  6921  6974 V FormManager: Network unavailable.
07-27 11:51:13.164  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:13.183  6878  6878 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-27 11:51:13.184  6878  6878 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,07-27 11:51:13.185  6878  6878 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
07-27 11:51:13.202  6952  6952 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@a40286a Instance Count = 1
,07-27 11:51:13.208  6952  6952 D BluetoothAdapterApp: onCreate
,07-27 11:51:13.222  6878  6878 D LgDataFeature: LgDataFeature() Constructor: none
07-27 11:51:13.223  6878  6878 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 11:51:13.230  6878  6878 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
07-27 11:51:13.231  6878  6878 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
07-27 11:51:13.231  6878  6878 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
07-27 11:51:13.231  6878  6878 V SoundPool: doLoad: loading sample sampleID=1
07-27 11:51:13.232  6952  6952 D ProfileConfigQcom: [BTUI] HeadsetService is supported
07-27 11:51:13.232  6878  6878 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-27 11:51:13.232  6952  6952 D ProfileConfigQcom: Adding HeadsetService
07-27 11:51:13.233  6952  6952 D ProfileConfigQcom: [BTUI] A2dpService is supported
07-27 11:51:13.233  6952  6952 D ProfileConfigQcom: Adding A2dpService
07-27 11:51:13.233  6952  6952 D ProfileConfigQcom: [BTUI] HidService is supported
07-27 11:51:13.234  6952  6952 D ProfileConfigQcom: Adding HidService
07-27 11:51:13.234  6878  6978 V SoundPool: Start decode
07-27 11:51:13.235  6878  6978 V MediaPlayer[Native]: decode(31, 10857164, 17813)
07-27 11:51:13.234  6952  6952 D ProfileConfigQcom: [BTUI] HealthService is supported
07-27 11:51:13.235  6952  6952 D ProfileConfigQcom: Adding HealthService
07-27 11:51:13.235   336  1371 V MediaPlayerService: decode(23, 10857164, 17813)
07-27 11:51:13.235   336  1371 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
07-27 11:51:13.235   336  1371 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
07-27 11:51:13.235   336  1371 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
07-27 11:51:13.236   336  1371 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
07-27 11:51:13.236   336  1371 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
07-27 11:51:13.236   336  1371 V MediaPlayerService: player type = 3
07-27 11:51:13.236   336  1371 V AwesomePlayer: AwesomePlayer create()
07-27 11:51:13.236   336  1371 V AwesomePlayer: reset_l() 
07-27 11:51:13.236   336  1371 V AwesomePlayer: cancelPlayerEvents
07-27 11:51:13.236   336  1371 V AwesomePlayer: setAudioSink() 
07-27 11:51:13.236   336  1371 V AwesomePlayer: reset_l() 
07-27 11:51:13.237   336  1371 V AudioCache: notify(0xb1432cc0, 8, 0, 0)
07-27 11:51:13.237   336  1371 V AudioCache: ignored
07-27 11:51:13.237   336  1371 V AwesomePlayer: cancelPlayerEvents
07-27 11:51:13.237  6952  6952 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
07-27 11:51:13.237   336  1371 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
07-27 11:51:13.237   336  1371 V AwesomePlayer: setDataSource_l dataSource
07-27 11:51:13.237   336  1371 V LGParserOSAL: SniffLGParser start
07-27 11:51:13.237   336  1371 V LGParserOSAL: MainType:5, SubType=0
07-27 11:51:13.238   336  1371 V LGParserOSAL: #### check Mime : application/ogg
07-27 11:51:13.238   336  1371 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
07-27 11:51:13.238  6952  6952 D ProfileConfigQcom: [BTUI] PanService is supported
07-27 11:51:13.238   336  1371 E MediaExtractor: Use LGExtractor :application/ogg 
,07-27 11:51:13.238  6952  6952 D ProfileConfigQcom: Adding PanService
07-27 11:51:13.238  6952  6952 D ProfileConfigQcom: [BTUI] GattService is supported
07-27 11:51:13.239  6952  6952 D ProfileConfigQcom: Adding GattService
07-27 11:51:13.239  6952  6952 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
07-27 11:51:13.239  6952  6952 D ProfileConfigQcom: Adding BluetoothMapService
07-27 11:51:13.239  6639  6639 D UEI.SmartControl: QS Service created
07-27 11:51:13.239  6952  6952 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
07-27 11:51:13.241  6952  6952 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
07-27 11:51:13.253  6878  6878 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
07-27 11:51:13.256  6803  6803 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-27 11:51:13.257  6952  6952 V LGMDMManagerInternal: Create singleton instance
07-27 11:51:13.258  6878  6878 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-27 11:51:13.258  6878  6878 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,07-27 11:51:13.269  6639  6639 I UEI.SmartControl: Service initServices...
07-27 11:51:13.269  6639  6639 D UEI.SmartControl: QS start get config
07-27 11:51:13.272  6878  6878 V LGMDMManager: Create singleton instance
07-27 11:51:13.292   336  1371 V LGParserOSAL: supported mime: application/ogg
07-27 11:51:13.292   336  1371 V AwesomePlayer: setDataSource_l() extractor countTracks=1
07-27 11:51:13.292   336  1371 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
07-27 11:51:13.292   336  1371 V AwesomePlayer: mBitrate = -1 bits/sec
07-27 11:51:13.292   336  1371 V AwesomePlayer: AudioTrack Setting
07-27 11:51:13.292   336  1371 V AwesomePlayer: AudioTrack Setting channelCount = 2
07-27 11:51:13.292   336  1371 V AwesomePlayer: setAudioSource() 
07-27 11:51:13.292   336  1371 V MediaPlayerService: prepare
07-27 11:51:13.292   336  1371 V AwesomePlayer: prepareAsync_l() 
07-27 11:51:13.292   336  1371 V MediaPlayerService: wait for prepare
07-27 11:51:13.292   336  6979 V AwesomePlayer: onPrepareAsyncEvent() 
07-27 11:51:13.292   336  6979 V AwesomePlayer: initAudioDecoder() 
07-27 11:51:13.292   336  6979 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-27 11:51:13.293   336  6979 V AudioSystem: isOffloadSupported()
07-27 11:51:13.293   336  6979 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-27 11:51:13.293   336  6979 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-27 11:51:13.293   336  6979 I AudioFlinger: isAudioPlaybackHookOn() false
07-27 11:51:13.293   336  6979 V AwesomePlayer: getUseOffload() = 0 
07-27 11:51:13.293   336  6979 V OMXCodec: OMXCodec::Create
07-27 11:51:13.293   336  6979 V OMXCodec: findMatchingCodecs()
07-27 11:51:13.293   336  6979 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
07-27 11:51:13.293   336  6979 V OMXCodec: matchingCodecs.size()=1
07-27 11:51:13.293   336  6979 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,07-27 11:51:13.295   336  6979 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
07-27 11:51:13.295   336  6979 V LGCodecAdapter: LG Codec Adapter start
07-27 11:51:13.295   336  6979 V OMXCodec: OMXCodec Createtor
07-27 11:51:13.295   336  6979 V OMXCodec: setComponentRole
07-27 11:51:13.295   336  6979 V OMXCodec: configureCodec protected=0
07-27 11:51:13.295   336  6979 V LGCodecAdapter: called getLGCodecSpecificData
07-27 11:51:13.295   336  6979 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
07-27 11:51:13.295   336  6979 V LGCodecOSAL: Called LGconfigureCodecMETA
07-27 11:51:13.295   336  6979 V LGCodecOSAL: Called LGconfigureCodecMSG
07-27 11:51:13.295   336  6979 V LGCodecOSAL: Not support LGCodec
07-27 11:51:13.295   336  6979 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-27 11:51:13.295   336  6979 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
07-27 11:51:13.295   336  6979 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
07-27 11:51:13.295   336  6979 I AwesomePlayer: Could not offload audio decode, try pcm offload
07-27 11:51:13.295   336  6979 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-27 11:51:13.295   336  6979 V AudioSystem: isOffloadSupported()
07-27 11:51:13.295   336  6979 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-27 11:51:13.295   336  6979 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-27 11:51:13.295   336  6979 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
07-27 11:51:13.295   336  6979 V OMXCodec: init()
07-27 11:51:13.295   336  6979 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
07-27 11:51:13.295   336  6979 V OMXCodec: allocateBuffers
07-27 11:51:13.296   336  6979 V OMXCodec: allocateBuffersOnPort portIndex=0
07-27 11:51:13.296   336  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
07-27 11:51:13.296   336  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7790 on input port
07-27 11:51:13.296   336  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
07-27 11:51:13.296   336  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
07-27 11:51:13.296   336  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
07-27 11:51:13.296   336  6979 V OMXCodec: allocateBuffersOnPort portIndex=1
07-27 11:51:13.296   336  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-27 11:51:13.296   336  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on output port
07-27 11:51:13.296   336  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
07-27 11:51:13.296   336  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
07-27 11:51:13.296   336  6979 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
07-27 11:51:13.296   336  6979 V OMXCodec: init() mAsyncCompletion wait!!! 
07-27 11:51:13.297   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-27 11:51:13.297   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-27 11:51:13.297   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
07-27 11:51:13.297   336  6979 V OMXCodec: init() mAsyncCompletion wait!!! 
07-27 11:51:13.307   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
07-27 11:51:13.307   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
07-27 11:51:13.307   33,6  6981 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
07-27 11:51:13.307   336  6979 V OMXCodec: init() mAsyncCompletion wait free! 
07-27 11:51:13.307   336  6979 V AwesomePlayer: finishAsyncPrepare_l() 
07-27 11:51:13.307   336  6979 V AudioCache: notify(0xb1432cc0, 5, 0, 0)
07-27 11:51:13.307   336  6979 V AudioCache: ignored
07-27 11:51:13.307   336  6979 V AudioCache: notify(0xb1432cc0, 1, 0, 0)
07-27 11:51:13.307   336  6979 V AudioCache: prepared
07-27 11:51:13.314   336  1371 V AudioCache: wait - success
07-27 11:51:13.314   336  1371 V MediaPlayerService: start
07-27 11:51:13.314   336  1371 V AwesomePlayer: play_l() 
07-27 11:51:13.314   336  1371 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
07-27 11:51:13.314   336  1371 V AwesomePlayer: createAudioPlayer_l
07-27 11:51:13.314   336  1371 V AwesomePlayer: seekAudioIfNecessary_l() 
07-27 11:51:13.314   336  1371 V AwesomePlayer: startAudioPlayer_l() 
07-27 11:51:13.314   336  1371 D AudioPlayer: start of Playback, useOffload 0
07-27 11:51:13.314   336  1371 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-27 11:51:13.314   336  1371 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-27 11:51:13.317   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
07-27 11:51:13.317   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
07-27 11:51:13.317   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
07-27 11:51:13.317   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
07-27 11:51:13.317   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
07-27 11:51:13.317   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-27 11:51:13.317   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884448
07-27 11:51:13.317   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 11:51:13.317   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884608
07-27 11:51:13.317   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 11:51:13.317   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
07-27 11:51:13.318   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 11:51:13.318   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
07-27 11:51:13.318   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 11:51:13.318   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
07-27 11:51:13.318   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-27 11:51:13.318   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
07-27 11:51:13.318   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
07-27 11:51:13.318   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
07-27 11:51:13.318   336  6981 V OMXCodec: allocateBuffersOnPort portIndex=1
07-27 11:51:13.318   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-27 11:51:13.318   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
07-27 11:51:13.318   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
07-27 11:51:13.318   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on output port
07-27 11:51:13.318   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c01a0 on output port
07-27 11:51:13.319   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
07-27 11:51:13.319   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
07-27 11:51:13.320   336  1371 V AudioCache: open(48000, 2, 0x0, 1, 4)
07-27 11:51:13.320   336  1371 V AudioCache: notify(0xb1432cc0, 6, 0, 0)
07-27 11:51:13.320   336  1371 V AudioCache: ignored
07-27 11:51:13.321   336  1371 V MediaPlayerService: wait for playback complete
07-27 11:51:13.322   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.322   336  6982 V AudioCache: memcpy(0xac300000, 0xb16e8000, 4096)
07-27 11:51:13.324   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.324   336  6982 V AudioCache: memcpy(0xac301000, 0xb16e8000, 4096)
07-27 11:51:13.326   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.326   336  6982 V AudioCache: memcpy(0xac302000, 0xb16e8000, 4096)
07-27 11:51:13.328   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.328   336  6982 V AudioCache: memcpy(0xac303000, 0xb16e8000, 4096)
07-27 11:51:13.329   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.329   336  6982 V AudioCache: memcpy(0xac304000, 0xb16e8000, 4096)
07-27 11:51:13.330   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.330   336  6982 V AudioCache: memcpy(0xac305000, 0xb16e8000, 4096)
07-27 11:51:13.331   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.331   336  6982 V AudioCache: memcpy(0xac306000, 0xb16e8000, 4096)
07-27 11:51:13.331   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.331   336  6982 V AudioCache: memcpy(0xac307000, 0xb16e8000, 4096)
07-27 11:51:13.331   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.331   336  6982 V AudioCache: memcpy(0xac308000, 0xb16e8000, 4096)
07-27 11:51:13.331   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.331   336  6982 V AudioCache: memcpy(0xac309000, 0xb16e8000, 4096)
07-27 11:51:13.334   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.334   336  6982 V AudioCache: memcpy(0xac30a000, 0xb16e8000, 4096)
07-27 11:51:13.334   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.334   336  6982 V AudioCache: memcpy(0xac30b000, 0xb16e8000, 4096)
07-27 11:51:13.334   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.334   336  6982 V AudioCache: memcpy(0xac30c000, 0xb16e8000, 4096)
07-27 11:51:13.334   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.334   336  6982 V AudioCache: memcpy(0xac30d000, 0xb16e8000, 4096)
07-27 11:51:13.335   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.335   336  6982 V AudioCache: memcpy(0xac30e000, 0xb16e8000, 4096)
,07-27 11:51:13.336   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.336   336  6982 V AudioCache: memcpy(0xac30f000, 0xb16e8000, 4096)
07-27 11:51:13.336   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.336   336  6982 V AudioCache: memcpy(0xac310000, 0xb16e8000, 4096)
07-27 11:51:13.338   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.338   336  6982 V AudioCache: memcpy(0xac311000, 0xb16e8000, 4096)
07-27 11:51:13.338   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.338   336  6982 V AudioCache: memcpy(0xac312000, 0xb16e8000, 4096)
07-27 11:51:13.340   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.340   336  6982 V AudioCache: memcpy(0xac313000, 0xb16e8000, 4096)
07-27 11:51:13.341   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.341   336  6982 V AudioCache: memcpy(0xac314000, 0xb16e8000, 4096)
07-27 11:51:13.341   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.341   336  6982 V AudioCache: memcpy(0xac315000, 0xb16e8000, 4096)
07-27 11:51:13.342   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.342   336  6982 V AudioCache: memcpy(0xac316000, 0xb16e8000, 4096)
07-27 11:51:13.343   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.343   336  6982 V AudioCache: memcpy(0xac317000, 0xb16e8000, 4096)
07-27 11:51:13.343   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.343   336  6982 V AudioCache: memcpy(0xac318000, 0xb16e8000, 4096)
07-27 11:51:13.344   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.344   336  6982 V AudioCache: memcpy(0xac319000, 0xb16e8000, 4096)
07-27 11:51:13.344   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.344   336  6982 V AudioCache: memcpy(0xac31a000, 0xb16e8000, 4096)
07-27 11:51:13.345   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.345   336  6982 V AudioCache: memcpy(0xac31b000, 0xb16e8000, 4096)
07-27 11:51:13.346   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.346   336  6982 V AudioCache: memcpy(0xac31c000, 0xb16e8000, 4096)
07-27 11:51:13.346   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.346   336  6982 V AudioCache: memcpy(0xac31d000, 0xb16e8000, 4096)
07-27 11:51:13.347   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.347   336  6982 V AudioCache: memcpy(0xac31e000, 0xb16e8000, 4096)
07-27 11:51:13.348   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.348   336  6982 V AudioCache: memcpy(0xac31f000, 0xb16e8000, 4096)
07-27 11:51:13.348  6952  6952 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:13.349   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.349   336  6982 V AudioCache: memcpy(0xac320000, 0xb16e8000, 4096)
07-27 11:51:13.350   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.350   336  6982 V AudioCache: memcpy(0xac321000, 0xb16e8000, 4096)
07-27 11:51:13.352  6952  6952 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 11:51:13.352   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.352  6952  6952 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-27 11:51:13.352   336  6982 V AudioCache: memcpy(0xac322000, 0xb16e8000, 4096)
07-27 11:51:13.352  6952  6952 V BluetoothSapReceiver: SapReceiver onReceive 
07-27 11:51:13.353   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.353   336  6982 V AudioCache: memcpy(0xac323000, 0xb16e8000, 4096)
07-27 11:51:13.354   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.354   336  6982 V AudioCache: memcpy(0xac324000, 0xb16e8000, 4096)
07-27 11:51:13.354  6952  6952 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:13.354  6952  6952 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
07-27 11:51:13.354   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.354   336  6982 V AudioCache: memcpy(0xac325000, 0xb16e8000, 4096)
07-27 11:51:13.355   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.355   336  6982 V AudioCache: memcpy(0xac326000, 0xb16e8000, 4096)
07-27 11:51:13.356   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.356   336  6982 V AudioCache: memcpy(0xac327000, 0xb16e8000, 4096)
07-27 11:51:13.357   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.357   336  6982 V AudioCache: memcpy(0xac328000, 0xb16e8000, 4096)
07-27 11:51:13.358   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.358   336  6982 V AudioCache: memcpy(0xac329000, 0xb16e8000, 4096)
07-27 11:51:13.358   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.358   336  6982 V AudioCache: memcpy(0xac32a000, 0xb16e8000, 4096)
07-27 11:51:13.359   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.359   336  6982 V AudioCache: memcpy(0xac32b000, 0xb16e8000, 4096)
07-27 11:51:13.359   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.359   336  6982 V AudioCache: memcpy(0xac32c000, 0xb16e8000, 4096)
07-27 11:51:13.360   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.360   336  6982 V AudioCache: memcpy(0xac32d000, 0xb16e8000, 4096)
07-27 11:51:13.360   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.360   336  6982 V AudioCache: memcpy(0xac32e000, 0xb16e8000, 4096)
07-27 11:51:13.361   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.361   336  6982 V AudioCache: memcpy(0xac32f000, 0xb16e8000, 4096)
07-27 11:51:13.361   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.361   336  6982 V AudioCache: memcpy(0xac330000, 0xb16e8000, 4096)
07-27 11:51:13.362   336  6982 V AudioCache: write(0xb16e8000, 4096)
07-27 11:51:13.362   336  6982 V AudioCache: memcpy(0xac331000, 0xb16e8000, 4096)
07-27 11:51:13.362  6900  6900 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
07-27 11:51:13.362   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
07-27 11:51:13.363   336  6982 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-27 11:51:13.363   336  6982 V AwesomePlayer: postAudioEOS() 
07-27 11:51:13.363   336  6982 V AudioCache: write(0xb16e8000, 280)
07-27 11:51:13.363   336  6982 V AudioCache: memcpy(0xac332000, 0xb16e8000, 280)
07-27 11:51:13.364   336  6979 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
07-27 11:51:13.364   336  6979 V AwesomePlayer: onStreamDone
07-27 11:51:13.364   336  6979 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
07-27 11:51:13.364   336  6979 V AudioCache: notify(0xb1432cc0, 2, 0, 0)
07-27 11:51:13.364   336  6979 V AudioCache: playback complete
07-27 11:51:13.364   336  6979 V AwesomePlayer: pause_l() 
07-27 11:51:13.364   336  1371 V AudioCache: wait - success
07-27 11:51:13.364   336  6979 V AudioCache: notify(0xb1432cc0, 7, 0, 0)
07-27 11:51:13.364   336  6979 V AudioCache: ignored
07-27 11:51:13.364   336  1371 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
07-27 11:51:13.364   336  6979 V AwesomePlayer: cancelPlayerEvents
07-27 11:51:13.364   336  6979 D AudioPlayer: Pause Playback at 1068125
07-27 11:51:13.365   336  1371 V AwesomePlayer: reset_l() 
07-27 11:51:13.365   336  1371 V AudioCache: notify(0xb1432cc0, 8, 0, 0)
07-27 11:51:13.365   336  1371 V AudioCache: ignored
07-27 11:51:13.365   336  1371 V AwesomePlayer: cancelPlayerEvents
07-27 11:51:13.365   336  1371 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
07-27 11:51:13.365   336  1371 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
07-27 11:51:13.365   336  1371 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
07-27 11:51:13.365   336  1371 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
07-27 11:51:13.365   336  1371 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-27 11:51:13.365   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-27 11:51:13.365   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-27 11:51:13.365   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
07-27 11:51:13.365   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
07-27 11:51:13.365   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
07-27 11:51:13.365   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
07-27 11:51:13.365   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
07-27 11:51:13.365   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
07-27 11:51:13.365   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
07-27 11:51:13.365   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7790 on port 0
07-27 11:51:13.365   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
07-27 11:51:13.365   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-27 11:51:13.365   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c01a0 on port 1
07-27 11:51:13.365   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
07-27 11:51:13.365   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 1
07-27 11:51:13.365   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
07-27 11:51:13.366   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 1
07-27 11:51:13.366   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
07-27 11:51:13.366   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
07-27 11:51:13.366   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-27 11:51:13.366   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
07-27 11:51:13.366   336  1371 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-27 11:51:13.366   336  1371 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-27 11:51:13.366   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
07-27 11:51:13.366   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
07-27 11:51:13.366   336  6981 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
07-27 11:51:13.366   336  1371 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-27 11:51:13.366   336  1371 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
07-27 11:51:13.366   336  1371 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
07-27 11:51:13.367   336  1371 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
07-27 11:51:13.367   336  1371 D AudioPlayer: AudioPlayer releasing audio source
07-27 11:51:13.367   336  1371 D AudioPlayer: AudioPlayer done releasing audio source
07-27 11:51:13.367   336  1371 V AwesomePlayer: reset_l() 
07-27 11:51:13.367   336  1371 V AwesomePlayer: cancelPlayerEvents
07-27 11:51:13.367   336  1371 V AwesomePlayer: ~AwesomePlayer call
07-27 11:51:13.367   336  1371 V AwesomePlayer: reset_l() 
07-27 11:51:13.367   336  1371 V AwesomePlayer: cancelPlayerEvents
07-27 11:51:13.368  6878  6978 V SoundPool: close(31)
07-27 11:51:13.368  6878  6978 V SoundPool: pointer = 0x9ffd2000, size = 205080, sampleRate = 48000, numChannels = 2
07-27 11:51:13.373  6878  6878 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-27 11:51:13.374  6878  6878 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,07-27 11:51:13.376  6878  6878 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8872
07-27 11:51:13.541  6639  6639 I UEI.SmartControl: Supports setup maps: true
,07-27 11:51:13.544  6639  6639 D UEI.SmartControl: QS start statue = true Error code = 0
07-27 11:51:13.544  6639  6639 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-27 11:51:13.544  6639  6639 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-27 11:51:13.544  6639  6639 I UEI.SmartControl: ### init IR Blaster...
,07-27 11:51:13.551  6639  6639 D serial_port: Configuring serial port
07-27 11:51:13.551  6639  6639 E UEI.SmartControl: UEIBLaster setting for 616
,07-27 11:51:13.552  6639  6639 I UEI.SmartControl: Setting serial record hearder size = 2
07-27 11:51:13.552  6639  6639 I UEI.SmartControl: configuring settings for MAXQ616
07-27 11:51:13.552  6639  6639 I UEI.SmartControl: Get version...
07-27 11:51:13.569  6639  6984 D UEI.SmartControl: serial port data available: 21
,07-27 11:51:13.595  6639  6639 D UEI.SmartControl: MAXQ616 A2-X4 software.
,07-27 11:51:13.595  6639  6639 I UEI.SmartControl: IR Blaster version: 256702256704300002
,07-27 11:51:13.595  6639  6639 I UEI.SmartControl: QS saving settings...
07-27 11:51:13.598  6639  6639 D UEI.SmartControl: IR Blaster version: 25672567
07-27 11:51:13.619  6639  6984 D UEI.SmartControl: serial port data available: 4
,07-27 11:51:13.652  6639  6990 I UEI.SmartControl: Device manager: loading config....
,07-27 11:51:13.657  6639  6639 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,07-27 11:51:13.660  6639  6990 D UEI.SmartControl: ----------- loading internal config...
07-27 11:51:13.660  6639  6639 E UEI.SmartControl: Services init done
07-27 11:51:13.661  6639  6639 D UEI.SmartControl: QS Service init finished
07-27 11:51:13.663  6639  6639 D UEI.SmartControl: QS Service version name: 2.1.91
07-27 11:51:13.663  6639  6639 D UEI.SmartControl: QS Service version code: 201091
07-27 11:51:13.663  6639  6639 D UEI.SmartControl: Service requested: Control
07-27 11:51:13.679  6639  6990 E UEI.SmartControl: Loading SETTINGS...
,07-27 11:51:13.684  6639  6639 D UEI.SmartControl: Request IControl service: devices are loaded...
07-27 11:51:13.685  6639  6990 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
07-27 11:51:13.690  6639  6639 D UEI.SmartControl: Internal service binding...
07-27 11:51:13.691  6878  6878 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-27 11:51:13.692  6639  6654 I UEI.SmartControl: ------ IControl API: 11
07-27 11:51:13.693  6639  6654 D UEI.SmartControl: File observer start...
07-27 11:51:13.693  6639  6654 E UEI.SmartControl: IR Port is disabled: false
07-27 11:51:13.694  6639  6654 D UEI.SmartControl: Starting file observer...
07-27 11:51:13.695  6639  6654 I UEI.SmartControl: Registering callback...
,07-27 11:51:13.698  6639  6989 I UEI.SmartControl: Notify AllClients services are ready: 0
07-27 11:51:13.698  6639  6989 D UEI.SmartControl: -----service ready thread exits
07-27 11:51:13.698  6639  6655 I UEI.SmartControl: ------ IControl API: 19
07-27 11:51:13.699  6639  6655 I UEI.SmartControl: Registering Services Ready callback...
07-27 11:51:13.699  6639  6655 I UEI.SmartControl: Notify client services are ready...
07-27 11:51:13.700  6878  6893 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
07-27 11:51:13.701  6878  6975 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
07-27 11:51:13.701  6878  6975 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
07-27 11:51:13.701  6878  6878 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
07-27 11:51:13.702  6878  6878 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
07-27 11:51:13.702  6639  6654 I UEI.SmartControl: ------ IControl API: 8
07-27 11:51:13.704  6878  6878 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
07-27 11:51:13.705  6878  6878 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
07-27 11:51:13.705  6878  6878 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
07-27 11:51:13.705  6878  6878 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
07-27 11:51:13.706  6878  6878 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
07-27 11:51:13.706  6878  6878 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
07-27 11:51:13.708  6878  6878 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,07-27 11:51:13.711  6878  6878 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-27 11:51:13.712  6878  6878 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-27 11:51:13.712  6878  6878 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-27 11:51:13.713  6878  6878 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-27 11:51:13.713  6878  6878 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-27 11:51:13.715  6878  6878 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
07-27 11:51:13.715  6878  6878 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
07-27 11:51:13.716  6878  6878 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1469613073716]
07-27 11:51:13.720  6878  6878 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,07-27 11:51:13.721  1037  1641 I ActivityManager: Killing 6100:com.android.gallery3d/u0a27 (adj 15): empty #17
07-27 11:51:13.745  6878  6995 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,07-27 11:51:13.793  1037  1641 I ActivityManager: Killing 6530:com.lge.email/u0a23 (adj 15): empty #18
,07-27 11:51:13.839  1037  1997 W libprocessgroup: failed to open /acct/uid_10027/pid_6100/cgroup.procs: No such file or directory
07-27 11:51:13.843  1037  1871 W libprocessgroup: failed to open /acct/uid_10023/pid_6530/cgroup.procs: No such file or directory
,07-27 11:51:13.851  6878  6878 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
07-27 11:51:13.852  6878  6878 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-27 11:51:13.853  6878  6878 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
07-27 11:51:13.854  6878  6878 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
07-27 11:51:13.855  6878  6878 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
07-27 11:51:13.856  6878  6878 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
07-27 11:51:13.857  6878  6878 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,07-27 11:51:13.870  6878  6878 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,07-27 11:51:14.473  1037  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:51:14.489  1037  1120 D Tethering: MasterInitialState.processMessage what=3
07-27 11:51:14.502  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:14.508  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:14.509  1037  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:14.512  1037  1120 D Tethering: MasterInitialState.processMessage what=3
07-27 11:51:14.521  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:14.526  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:14.528  6426  6426 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-27 11:51:14.531  6426  6831 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-27 11:51:14.531  1037  1109 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:14.534  1037  1872 D WifiServiceImplEx: setWifiEnabled: true pid=6735, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-27 11:51:14.535  1037  1872 D WifiService: setWifiEnabled: true pid=6735, uid=10118
07-27 11:51:14.535  1037  1872 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-27 11:51:14.541  5768  5768 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-27 11:51:14.545  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 11:51:14.545  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-27 11:51:14.545  1037  1037 D Ulp_jni : JNI:system_update. Event-4
07-27 11:51:14.546  1037  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
07-27 11:51:14.546  1037  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-27 11:51:14.547  1037  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
07-27 11:51:14.547  1037  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-27 11:51:14.547  1037  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
07-27 11:51:14.547  1037  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-27 11:51:14.547  1037  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D
07-27 11:51:14.547  1037  1523 E WifiHW  : unknown target_country: EU , set to default
07-27 11:51:14.547  1037  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
07-27 11:51:14.547  1037  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
07-27 11:51:14.547  1037  1523 I WifiUtil: gEnableBmps=1
,07-27 11:51:14.574  5768  5768 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-27 11:51:14.590  2194  2194 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:51:14.645  1037  1109 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:51:14.664  1037  1997 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7016 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,07-27 11:51:14.669  1037  1109 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:14.669  1037  1109 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:14.748  7016  7016 I AppUp4:AppBoxCP: onCreate
07-27 11:51:14.749  7016  7016 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,07-27 11:51:14.758  7016  7016 I AppUp4:DB:  setFingerPrint start
07-27 11:51:14.759  7016  7016 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
07-27 11:51:14.767  7016  7016 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
07-27 11:51:14.767  7016  7016 I AppUp4:DB:  SDK version = 21
07-27 11:51:14.767  7016  7016 I AppUp4:DB:  beforefinger == newfinger no write in DB
07-27 11:51:14.769  7016  7016 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,07-27 11:51:14.771  7016  7016 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-27 11:51:14.771  7016  7016 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:14.773  7016  7016 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-27 11:51:14.774  7016  7016 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-27 11:51:14.781  7016  7016 I AppUp4:CustModeStarterReceiver: onReceive
,07-27 11:51:14.838  7016  7016 D LgDataFeature: LgDataFeature() Constructor: none
,07-27 11:51:14.838  7016  7016 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 11:51:14.853  7016  7016 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@215a71a4
07-27 11:51:14.853  7016  7016 D AppUp4:CustFacade: isCustomizationCompleted : false
07-27 11:51:14.853  7016  7016 D AppUp4:CustFacade: isPhone : true
07-27 11:51:14.854  7016  7016 D AppUp4:CustModeStarterReceiver: begin check event
07-27 11:51:14.855  7016  7016 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
07-27 11:51:14.855  7016  7016 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
07-27 11:51:14.856  7016  7034 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
07-27 11:51:14.856  7016  7034 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
,07-27 11:51:14.857  7016  7034 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
07-27 11:51:14.864  1037  1908 I ActivityManager: Killing 6366:com.android.defcontainer/u0a4 (adj 15): empty #17
07-27 11:51:14.900  1037  1871 W libprocessgroup: failed to open /acct/uid_10004/pid_6366/cgroup.procs: No such file or directory
,07-27 11:51:14.901  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:14.902  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 11:51:14.906  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 11:51:14.912  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 11:51:14.922  4297  7037 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-27 11:51:14.935  4297  7038 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:14.936  4297  7038 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,07-27 11:51:14.978  1037  1574 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7042 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,07-27 11:51:15.067  7042  7042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 11:51:15.069  7042  7042 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 11:51:15.072  7042  7042 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-27 11:51:15.073  7042  7042 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-27 11:51:15.173  7042  7042 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,07-27 11:51:15.206  7042  7042 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,07-27 11:51:15.265  7042  7042 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-27 11:51:15.315  7042  7042 D LgDataFeature: LgDataFeature() Constructor: none
07-27 11:51:15.315  7042  7042 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 11:51:15.343  1037  1120 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-27 11:51:15.348   332   895 D SoftapController: Softap fwReload - Ok
07-27 11:51:15.353  1037  1523 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (798ms)
07-27 11:51:15.355  1037  1120 D Tethering: InitialState.processMessage what=4
,07-27 11:51:15.362  1037  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-27 11:51:15.368   332   895 D CommandListener: Setting iface cfg
07-27 11:51:15.368   332   895 D CommandListener: Trying to bring down wlan0
,07-27 11:51:15.370   332   895 D CommandListener: Clearing all IP addresses on wlan0
07-27 11:51:15.372  1037  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
07-27 11:51:15.374  1037  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-27 11:51:15.374  1037  1523 E WifiStateMachine: useWiFiOffloading() : false
07-27 11:51:15.374  1037  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-27 11:51:15.364  7068  7068 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:51:15.364  7068  7068 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:51:15.378  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:15.378  1037  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-27 11:51:15.378  1037  1523 D WifiMonitor: connecting to supplicant
07-27 11:51:15.388  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,07-27 11:51:15.393  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:15.393  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
07-27 11:51:15.398  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:15.405  7068  7068 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-27 11:51:15.446  7068  7068 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-27 11:51:15.446  7068  7068 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,07-27 11:51:15.475  7042  7042 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-27 11:51:15.505  3414  3414 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-27 11:51:15.505  3414  3414 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:51:15.506  3414  3414 I LgeMiscReceiver: networkInfo.isConnected() = false
,07-27 11:51:15.515  7042  7042 I HubEmail: JNI_OnLoad()
07-27 11:51:15.515  7042  7042 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-27 11:51:15.515  7042  7042 I HubEmail: registerNatives()
07-27 11:51:15.515  7042  7042 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-27 11:51:15.515  7042  7042 I HubEmail: registerNativeMethods()
07-27 11:51:15.515  7042  7042 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-27 11:51:15.516  7042  7042 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
07-27 11:51:15.521  7068  7068 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 11:51:15.554  1037  1997 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7082 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,07-27 11:51:15.563  6921  7078 W FormManager: Network not available. Please check & try again.
07-27 11:51:15.565  7042  7080 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:15.569  7068  7068 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
07-27 11:51:15.573  7068  7068 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
07-27 11:51:15.573  7068  7068 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-27 11:51:15.573  6921  7079 V FormManager: Network unavailable.
,07-27 11:51:15.574  1037  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
07-27 11:51:15.574  1037  7092 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
07-27 11:51:15.574  1037  7092 D WifiMonitor: Dropping event because (p2p0) is stopped
07-27 11:51:15.574  1037  7092 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-27 11:51:15.574  1037  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
07-27 11:51:15.574  1037  7092 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-27 11:51:15.574  1037  7092 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-27 11:51:15.574  1037  7092 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-27 11:51:15.575  1037  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
07-27 11:51:15.575  1037  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
07-27 11:51:15.576  1037  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:51:15.576  6921  7079 V FormManager: Network unavailable.
07-27 11:51:15.576  1037  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:51:15.576  1037  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:51:15.577  1037  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:51:15.577  1037  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
07-27 11:51:15.577  1037  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
07-27 11:51:15.578  1037  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
07-27 11:51:15.578  1037  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
07-27 11:51:15.578  1037  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
07-27 11:51:15.578  1037  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-27 11:51:15.578  1037  1523 E WifiStateMachine: useWiFiOffloading() : false
07-27 11:51:15.578  1037  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-27 11:51:15.579  1037  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
07-27 11:51:15.579  1037  1523 D WifiNative-wlan0: SET update_config 1: returned true
07-27 11:51:15.579  1037  1523 D WifiConfigStore: Loading config and enabling all networks 
07-27 11:51:15.579  1037  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
07-27 11:51:15.580  1037  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
07-27 11:51:15.582  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:15.582  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:15.583  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:15.583  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:15.583  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-27 11:51:15.585  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:15.586  1037  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,07-27 11:51:15.587  1927  1927 D WfdService: Waiting for WifiP2p enabling
07-27 11:51:15.592  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
07-27 11:51:15.593  1037  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-27 11:51:15.593  6735  6735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:15.593  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:15.593  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:15.593  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:15.593  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:15.593  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:51:15.593  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:15.593  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:15.593  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:51:15.593  6735  6735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:15.593  6735  6735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:51:15.594  6735  6735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:15.594  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:15.594  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:15.594  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:15.594  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:15.594  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:51:15.594  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:15.594  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:15.594  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:51:15.594  6735  6735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:15.594  6735  6735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:51:15.598  1037  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,07-27 11:51:15.599  1037  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-27 11:51:15.601  1037  1574 I ActivityManager: Killing 6126:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
07-27 11:51:15.601  1037  1523 D WifiStateMachine: enableVerboseLogging : level 2
07-27 11:51:15.601  1037  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
07-27 11:51:15.602  1037  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
07-27 11:51:15.602  1037  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
07-27 11:51:15.603  1037  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
07-27 11:51:15.603  1037  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
07-27 11:51:15.603  1037  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
07-27 11:51:15.603  1037  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
07-27 11:51:15.604  1037  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
07-27 11:51:15.604  1037  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
07-27 11:51:15.604  1037  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
07-27 11:51:15.604  1037  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
07-27 11:51:15.605  1037  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
07-27 11:51:15.605  1037  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
07-27 11:51:15.605  1037  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
07-27 11:51:15.629  1037  1060 W libprocessgroup: failed to open /acct/uid_10080/pid_6126/cgroup.procs: No such file or directory
07-27 11:51:15.629  1037  1523 D WifiStateMachine: Setting OUI to DA-A1-19
07-27 11:51:15.630  1037  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
07-27 11:51:15.630  1037  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
07-27 11:51:15.630  1037  1523 D WifiNative-HAL: Setting external_sim to 1
07-27 11:51:15.630  1037  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
,07-27 11:51:15.630  1037  1523 D WifiNative-wlan0: SET external_sim 1: returned true
07-27 11:51:15.630  1037  1523 I WifiNative-HAL: startHal
07-27 11:51:15.630  1037  1523 D wifi    : setting scan oui 0x9576af80
07-27 11:51:15.631  1037  1523 D WifiStateMachine: Setting OUI to DA-A1-19
07-27 11:51:15.631  1037  1523 I WifiNative-HAL: startHal
07-27 11:51:15.631  1037  1523 D wifi    : setting scan oui 0x9576af80
07-27 11:51:15.631  1037  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
07-27 11:51:15.632  1037  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
07-27 11:51:15.632  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
07-27 11:51:15.632  7068  7068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
07-27 11:51:15.633  1037  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
07-27 11:51:15.633  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-27 11:51:15.633  7068  7068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-27 11:51:15.634  1037  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-27 11:51:15.634  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
07-27 11:51:15.634  7068  7068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
07-27 11:51:15.634  1037  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
07-27 11:51:15.635  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-27 11:51:15.635  7068  7068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-27 11:51:15.635  1037  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-27 11:51:15.635  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-27 11:51:15.635  1927  1927 D WfdsService: Supplicant Connection state is changed : true
07-27 11:51:15.635  1927  2323 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-27 11:51:15.635  1927  2323 D WfdsService: Set the WFDS Monitor: true
07-27 11:51:15.635  7068  7068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-27 11:51:15.635  1927  2323 D WfdsMonitor: WfdsMonitorThread create
07-27 11:51:15.636  1927  2323 D WfdsMonitor: WFDS Monitor is created and started
07-27 11:51:15.636  1927  2323 D WfdsService: WiFi: Supplicant connection re-established
07-27 11:51:15.636  1037  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-27 11:51:15.636  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
07-27 11:51:15.636  7068  7068 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
07-27 11:51:15.636  1927  7100 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-27 11:51:15.637  1037  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
07-27 11:51:15.637  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-27 11:51:15.637  7068  7068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-27 11:51:15.637  1927  7100 E CtrlSupplicant: Succeed to open control connection
07-27 11:51:15.637  1927  7100 E CtrlSupplicant: Succeed to open monitor connection
07-27 11:51:15.637  1037  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-27 11:51:15.637  1927  7100 D WfdsMonitor: Supplicant connection established
07-27 11:51:15.637  1927  2323 D WfdsService: Connected to the supplicant for wfds
07-27 11:51:15.638  1037  1523 E WifiNative: : [303,465,723 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
07-27 11:51:15.638  1037  1523 D WifiNative-wlan0: doBoolean: RECONNECT
07-27 11:51:15.639  1037  1523 D WifiNative-wlan0: RECONNECT: returned true
07-27 11:51:15.639  1037  1523 D WifiNative-wlan0: doString: [STATUS]
07-27 11:51:15.639  1037  7092 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-27 11:51:15.639  1037  7092 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SS,ID=
07-27 11:51:15.639  1037  1523 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-27 11:51:15.639  1037  1523 D WifiNative-wlan0: doBoolean: SET ps 1
07-27 11:51:15.640  1037  1523 D WifiNative-wlan0: SET ps 1: returned true
07-27 11:51:15.640  1037  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:15.640  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 3
07-27 11:51:15.640  1037  1037 D RttService: SCAN_AVAILABLE : 3
07-27 11:51:15.640  1037  1542 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:15.641  1037  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
07-27 11:51:15.641  1037  1541 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:15.641  1037  1541 I WifiNative-HAL: startHal
07-27 11:51:15.641  1037  1541 D wifi    : getting scan capabilities on interface[1] = 0x9576af80
07-27 11:51:15.641  1037  1541 D wifi    : failed to get capabilities : -3
07-27 11:51:15.641  1037  1541 E WifiScanningService: could not get scan capabilities
07-27 11:51:15.641  1037  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
07-27 11:51:15.641  1037  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
07-27 11:51:15.641   332   895 D CommandListener: Setting iface cfg
07-27 11:51:15.641  1037  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
07-27 11:51:15.641   332   895 D CommandListener: Trying to bring up p2p0
07-27 11:51:15.642  1037  1522 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-27 11:51:15.642  1037  1522 D LGWifiP2pService: P2pEnablingState
07-27 11:51:15.642  1037  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
07-27 11:51:15.642  1037  1522 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:15.642  1037  1522 D LGWifiP2pService: P2p socket connection successful
07-27 11:51:15.642  1037  1522 D LGWifiP2pService: P2pEnabledState
07-27 11:51:15.642  1037  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
07-27 11:51:15.642  1037  1522 D LGWifiP2pService: sending p2p connection changed broadcast
07-27 11:51:15.642  1037  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
07-27 11:51:15.642  1037  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
07-27 11:51:15.642  7068  7068 E wpa_supplicant: nWIFIDualbandAPConnection: 1
07-27 11:51:15.643  1037  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
07-27 11:51:15.643  1037  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
07-27 11:51:15.643  1037  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
07-27 11:51:15.643  1037  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
,07-27 11:51:15.643  7068  7068 E wpa_supplicant: disconnect_rssi_lvl: -100
07-27 11:51:15.644  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
07-27 11:51:15.644  1927  1927 D WfdsService: WifiP2pState is changed : true
07-27 11:51:15.644  1927  2323 D WfdsService: Receive the WFDS_ENABLE Method
07-27 11:51:15.644  1927  2323 D WfdsService: Set the WFDS Monitor: true
07-27 11:51:15.644  1927  2323 D WfdsService: Connected to the supplicant for wfds
07-27 11:51:15.644  1927  2323 D WfdsJNI : doCommand: WFDS_SET TRUE
07-27 11:51:15.644  7068  7068 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
,07-27 11:51:15.645  1927  2323 D WfdsService: selectPreferredScanChannel [36]
07-27 11:51:15.645  1927  2323 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
07-27 11:51:15.645  1037  1523 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
07-27 11:51:15.646  1037  1523 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
07-27 11:51:15.646  1037  1523 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
07-27 11:51:15.646  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
07-27 11:51:15.646  1037  1522 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
07-27 11:51:15.648  7068  7068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-27 11:51:15.648  1927  1927 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-27 11:51:15.648  7068  7068 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:51:15.648  1927  1927 D WfdsService: isConnected: false
07-27 11:51:15.648  1037  7092 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-27 11:51:15.649  1037  7092 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:51:15.649  1037  7092 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,07-27 11:51:15.649  1037  7092 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:51:15.649  7068  7068 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-27 11:51:15.649  7068  7068 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:15.649  1037  7092 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:51:15.649  1037  7092 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:15.649  1037  7092 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:15.649  1037  1523 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
07-27 11:51:15.649  1037  7092 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:15.650  1927  7100 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:51:15.650  1037  1523 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
07-27 11:51:15.650  1037  1522 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
07-27 11:51:15.650  7068  7068 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:15.650  1037  1522 D WifiNative-p2p0: doBoolean: SET device_name G3
07-27 11:51:15.650  1037  7092 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:51:15.650  1037  7092 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:15.650  1037  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
07-27 11:51:15.650  1037  7092 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:15.650  1037  7092 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:15.651  1037  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
07-27 11:51:15.651  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
07-27 11:51:15.651  1927  7100 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:51:15.651  1037  1522 D WifiNative-p2p0: SET device_name G3: returned true
07-27 11:51:15.651  1037  1522 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-27 11:51:15.651  1037  1522 D LGWifiP2pService: before postfix = G3
07-27 11:51:15.651  1037  1522 D WifiServerServiceExt: postfix byte check : 2
07-27 11:51:15.651  1037  1522 D LGWifiP2pService: after postfix = G3
07-27 11:51:15.651  1037  1522 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
07-27 11:51:15.652  1037  1522 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
07-27 11:51:15.652  1037  1522 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
07-27 11:51:15.652  1037  1522 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
07-27 11:51:15.652  1037  1522 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
07-27 11:51:15.652  7068  7068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
07-27 11:51:15.652  7068  7068 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 11:51:15.653  1037  7092 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
07-27 11:51:15.653  1037  7092 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 11:51:15.653  1037  7092 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 11:51:15.653  1037  7092 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 11:51:15.653  1037  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
07-27 11:51:15.653  1037  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
07-27 11:51:15.654  1037  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
07-27 11:51:15.654  1037  1523 D ,WifiNative-wlan0: doBoolean: SCAN
07-27 11:51:15.654  1037  1523 D WifiNative-wlan0: SCAN: returned false
07-27 11:51:15.655  1037  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=303483  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-27 11:51:15.656  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=303484  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-27 11:51:15.656  1037  1523 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 11:51:15.657  1037  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 11:51:15.657  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:15.657  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-27 11:51:15.658  1037  1522 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
07-27 11:51:15.658  1037  1522 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
07-27 11:51:15.658  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:15.658  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:15.658  1037  1522 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
,07-27 11:51:15.658  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-27 11:51:15.658  1037  1522 D WifiNative-HAL: p2pGetDeviceAddress
07-27 11:51:15.658  1037  1522 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
07-27 11:51:15.658  1037  1522 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
07-27 11:51:15.659  1037  1522 D WifiNative-p2p0: doBoolean: P2P_FLUSH
07-27 11:51:15.660  1927  1927 I WfdStateTracker: handleP2pThisDeviceChanged
07-27 11:51:15.660  1927  1927 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
07-27 11:51:15.660  1927  1927 D WfdsService: Update P2p Interface State: 3
07-27 11:51:15.660  1037  1522 D WifiNative-p2p0: P2P_FLUSH: returned true
07-27 11:51:15.660  1037  1522 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
07-27 11:51:15.661  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:15.661  1037  1522 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
07-27 11:51:15.661  1037  1522 D WifiNative-p2p0: doString: [LIST_NETWORKS]
07-27 11:51:15.661  1037  1522 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
07-27 11:51:15.661  1037  1522 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
07-27 11:51:15.662  1037  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 11:51:15.663  1037  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 11:51:15.663  1037  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 11:51:15.664  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:51:15.664  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
07-27 11:51:15.691  1037  1522 D WifiNative-p2p0: SAVE_CONFIG: returned true
07-27 11:51:15.691  1037  1522 D LGWifiP2pService: sending p2p persistent groups changed broadcast
07-27 11:51:15.691  1037  1522 D LGWifiP2pService: InactiveState
07-27 11:51:15.691  1037  1522 D LGWifiP2pService: InactiveState{ when=-42ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:15.691  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-42ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:15.691  1037  1522 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,07-27 11:51:15.692  7068  7068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-27 11:51:15.693  7068  7068 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:51:15.693  1037  7092 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-27 11:51:15.693  1037  7092 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:51:15.693  1037  7092 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:51:15.693  1037  7092 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:51:15.693  7068  7068 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-27 11:51:15.693  7068  7068 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:15.694  1037  7092 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:51:15.694  1037  7092 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:15.694  1037  7092 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:15.694  1037  7092 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:15.694  7068  7068 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,07-27 11:51:15.694  1037  7092 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:51:15.694  1037  7092 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:15.694  1037  7092 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:15.694  1037  7092 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:15.696  1927  7100 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-27 11:51:15.696  1927  7100 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:51:15.696  1927  7100 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:51:15.696  1037  1522 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
07-27 11:51:15.696  1037  1522 D LGWifiP2pService: InactiveState{ when=-35ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:15.696  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-35ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:15.696  1037  1522 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:15.697  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:15.697  1037  1522 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:15.697  1037  1522 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:15.697  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:15.697  1037  1522 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:15.697  1927  2323 W WfdsService: DefaultState - msg [9441285] is not handled
07-27 11:51:15.698  1037  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:15.698  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:15.698  1037  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:15.698  1037  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:15.698  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:15.698  1037  1522 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:15.698  1037  1037 E WifiServerServiceExt: No p2p device connected
07-27 11:51:15.712  7082  7082 D LgDataFeature: LgDataFeature() Constructor: none
07-27 11:51:15.712  7082  7082 D LgDataFeature: LgDataFeature() Constructor Done, null
07-27 11:51:15.714  7082  7082 D PhoneMonitor: Register our PhoneStateListener
,07-27 11:51:15.735  7082  7082 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,07-27 11:51:15.739  7082  7082 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,07-27 11:51:15.771  7082  7082 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,07-27 11:51:15.772  7082  7082 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
07-27 11:51:15.774  7082  7082 D TelephonyAutoProfiling: [parse] Load xml
07-27 11:51:15.781  7082  7082 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
07-27 11:51:15.781  7082  7082 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
07-27 11:51:15.781  7082  7082 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
07-27 11:51:15.781  7082  7082 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
07-27 11:51:15.781  7082  7082 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
07-27 11:51:15.781  7082  7082 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
07-27 11:51:15.781  7082  7082 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
,07-27 11:51:15.781  7082  7082 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
07-27 11:51:15.781  7082  7082 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
07-27 11:51:15.782  7082  7082 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
07-27 11:51:15.782  7082  7082 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
07-27 11:51:15.782  7082  7082 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
07-27 11:51:15.782  7082  7082 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
07-27 11:51:15.782  7082  7082 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
,07-27 11:51:15.782  7082  7082 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
07-27 11:51:15.782  7082  7082 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
07-27 11:51:15.782  7082  7082 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
07-27 11:51:15.793  7082  7082 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
07-27 11:51:15.800  1037  1766 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7103 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-27 11:51:15.801  1037  1766 I ActivityManager: Killing 6567:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,07-27 11:51:15.864  1037  1908 W libprocessgroup: failed to open /acct/uid_10061/pid_6567/cgroup.procs: No such file or directory
,07-27 11:51:16.090  1037  1998 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7127 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,07-27 11:51:16.092  1037  1998 I ActivityManager: Killing 6154:com.google.android.apps.plus/u0a97 (adj 15): empty #17
07-27 11:51:16.159  1037  1908 W libprocessgroup: failed to open /acct/uid_10097/pid_6154/cgroup.procs: No such file or directory
,07-27 11:51:16.160  7068  7068 E wpa_supplicant: USIM:  scard_init function
07-27 11:51:16.160  7068  7068 I wpa_supplicant: Trying to associate with SSID 'NG700'
07-27 11:51:16.160  1037  7092 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
07-27 11:51:16.160  1037  7092 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
07-27 11:51:16.161  1037  7092 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
07-27 11:51:16.162  1037  7092 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
07-27 11:51:16.162  1037  7092 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
07-27 11:51:16.162  1037  7092 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
07-27 11:51:16.162  1037  7092 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
07-27 11:51:16.165  1037  1523 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
07-27 11:51:16.166  1037  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
07-27 11:51:16.166  1037  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
07-27 11:51:16.167  1037  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
07-27 11:51:16.167  1037  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
07-27 11:51:16.174  1037  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=304002  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,07-27 11:51:16.178  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=304006  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
07-27 11:51:16.182  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:16.182  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:51:16.182  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:16.182  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:16.182  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-27 11:51:16.183  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 11:51:16.188  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:16.188  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:16.188  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-27 11:51:16.195  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:51:16.195  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATING
07-27 11:51:16.204  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:16.204  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-27 11:51:16.208  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 11:51:16.274  7068  7068 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-27 11:51:16.287  1037  7092 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,07-27 11:51:16.287  1037  7092 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
07-27 11:51:16.288  1037  7092 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
07-27 11:51:16.288  1037  7092 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
07-27 11:51:16.288  1037  7092 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 11:51:16.288  1037  7092 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 11:51:16.289  1037  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=304117  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-27 11:51:16.290  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=304118  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-27 11:51:16.290  1037  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=304118
07-27 11:51:16.291  1037  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=304119
07-27 11:51:16.291  1037  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=304119
07-27 11:51:16.292  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=304120
07-27 11:51:16.292  1037  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=304120
07-27 11:51:16.293  1037  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=304121  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-27 11:51:16.305  7068  7068 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 11:51:16.305  7068  7068 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-27 11:51:16.308  1037  1871 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7144 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-27 11:51:16.309  1037  1871 I ActivityManager: Killing 6601:com.lge.eula/1000 (adj 15): empty #17
,07-27 11:51:16.311  1037  7092 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 11:51:16.311  1037  7092 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 11:51:16.311  1037  7092 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
07-27 11:51:16.311  1037  7092 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 11:51:16.311  1037  7092 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 11:51:16.311  1037  7092 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
07-27 11:51:16.311  1037  7092 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-27 11:51:16.312  1037  7092 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-27 11:51:16.312  1037  7092 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 11:51:16.312  1037  7092 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 11:51:16.359  1037  1120 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-27 11:51:16.368  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=304196  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-27 11:51:16.369  1037  1998 W libprocessgroup: failed to open /acct/uid_1000/pid_6601/cgroup.procs: No such file or directory
07-27 11:51:16.375  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:16.375  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-27 11:51:16.377  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:16.379  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:16.379  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:16.379  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-27 11:51:16.384  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:16.384  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:16.384  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
07-27 11:51:16.385  1037  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=304213  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-27 11:51:16.386  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=304214  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-27 11:51:16.387  1037  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=304215
07-27 11:51:16.388  1037  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=304216
07-27 11:51:16.388  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:16.388  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:51:16.389  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 11:51:16.390  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:51:16.391  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATED
07-27 11:51:16.392  1037  1523 D WifiNative-wlan0: doString: [STATUS]
07-27 11:51:16.392  1037  7092 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 11:51:16.392  1037  7092 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 11:51:16.393  1037  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-27 11:51:16.396  1037  1523 I WifiServiceExtension: setVHTCapabilityType  : false
07-27 11:51:16.410  1037  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
07-27 11:51:16.410  1037  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,07-27 11:51:16.417  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:16.418  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:16.418  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-27 11:51:16.425  7144  7144 I art     : Almond Protected OAT
,07-27 11:51:16.429  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:16.429  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:16.429  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-27 11:51:16.430  1037  1522 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:16.430  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:16.430  1037  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:16.434  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:16.435  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:51:16.436  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 11:51:16.439  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:16.439  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:51:16.440  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:16.441  1037  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
07-27 11:51:16.441  1037  1530 D ConnectivityService: Got NetworkAgent Messenger
07-27 11:51:16.442  1037  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-27 11:51:16.442  1037  1530 D ConnectivityService: NetworkAgent connected
07-27 11:51:16.442  1037  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 11:51:16.442  1037  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-27 11:51:16.442  1037  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-27 11:51:16.442  1037  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-27 11:51:16.452  1037  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
,07-27 11:51:16.454  1037  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 11:51:16.454  1037  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-27 11:51:16.455  1037  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-27 11:51:16.455  1037  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-27 11:51:16.463  1037  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-27 11:51:16.466   332   895 D CommandListener: Setting iface cfg
07-27 11:51:16.470  1037  1523 E WifiStateMachine: Start Dhcp Watchdog 2
,07-27 11:51:16.472  1037  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=304300  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 11:51:16.472  1037  7167 D DhcpStateMachine: StoppedState
07-27 11:51:16.472  1037  7167 D DhcpStateMachine: StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:16.473  1037  7167 D DhcpStateMachine: WaitBeforeStartState
07-27 11:51:16.473  1037  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=304301  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 11:51:16.475  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=304302  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 11:51:16.476  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:51:16.478  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:51:16.478  1037  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:51:16.478  1037  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
,07-27 11:51:16.479  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:51:16.479  1037  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:51:16.480  1037  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=304308  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 11:51:16.481  1037  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=304309  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 11:51:16.481  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=304309  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 11:51:16.483  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:258186] from screen [on:0 period:734261250] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 11:51:16.484  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:734261251] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-27 11:51:16.484  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 11:51:16.488  1037  1530 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
07-27 11:51:16.488  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
07-27 11:51:16.488  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-27 11:51:16.489  1037  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
07-27 11:51:16.489  1037  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-27 11:51:16.490  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
07-27 11:51:16.490  1037  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
07-27 11:51:16.490  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,07-27 11:51:16.491  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:16.491  1037  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:16.492  1037  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:16.492  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:16.492  1037  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:16.493  1037  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-27 11:51:16.493  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=136,0,0
07-27 11:51:16.494  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=136,0,0
07-27 11:51:16.494  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
07-27 11:51:16.494  7068  7068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
07-27 11:51:16.494  1037  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
07-27 11:51:16.494  1037  1523 D WifiNative-wlan0: doBoolean: SET ps 0
07-27 11:51:16.495  1037  1523 D WifiNative-wlan0: SET ps 0: returned true
07-27 11:51:16.495  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
07-27 11:51:16.495  7068  7068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
07-27 11:51:16.495  1037  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
07-27 11:51:16.496  1037  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@29b4a791 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:16.496  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@29b4a791 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:16.496  1037  7167 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:16.496  1037  7167 D DhcpStateMachine: DHCP Start wake lock is acquired.
07-27 11:51:16.497  1037  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
07-27 11:51:16.497  1037  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
,07-27 11:51:16.497  1037  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-27 11:51:16.504   332   895 D CommandListener: Setting iface cfg
07-27 11:51:16.504   332   895 D CommandListener: Trying to bring up wlan0
07-27 11:51:16.505  1037  1523 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
07-27 11:51:16.507  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:16.507  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:16.508  1037  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:16.508  1037  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:16.508  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:16.509  1037  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:16.510  1037  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-27 11:51:16.510  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-27 11:51:16.511  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-27 11:51:16.511  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,07-27 11:51:16.511  7144  7144 D WeatherApplication: removeAccount
07-27 11:51:16.511  1037  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:16.511  7068  7068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-27 11:51:16.511  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:16.512  1037  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-27 11:51:16.512  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-27 11:51:16.512  7068  7068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
07-27 11:51:16.512  1037  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
07-27 11:51:16.512  1037  1523 D WifiNative-wlan0: doBoolean: SET ps 1
07-27 11:51:16.512  7144  7144 D WeatherApplication: Account.length = 0
07-27 11:51:16.513  7144  7144 E WeatherApplication: OPERATOR:OPEN
07-27 11:51:16.515  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:51:16.515  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-27 11:51:16.517  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:16.518  7144  7144 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:51:16
07-27 11:51:16.520  7144  7144 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-27 11:51:16.520  7144  7144 D Weather.Utils: 2 : All the weather widget is gone.
07-27 11:51:16.522  7144  7144 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-27 11:51:16.525  7144  7144 D WeatherAncestor: connectivity changed - connection : true
07-27 11:51:16.526  7144  7144 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,07-27 11:51:16.529  1037  1523 D WifiNative-wlan0: SET ps 1: returned true
07-27 11:51:16.530  1037  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-27 11:51:16.530  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-27 11:51:16.531  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-27 11:51:16.531  1037  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-27 11:51:16.532  1037  1530 D ConnectivityService: ignoring duplicate network state non-change
,07-27 11:51:16.533  1037  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-27 11:51:16.534  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:16.534  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:51:16.535  1037  1530 D ConnectivityService: Adding iface wlan0 to network 101
07-27 11:51:16.535  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:16.535  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:16.535  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:16.535  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,07-27 11:51:16.542  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:16.542  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:16.542  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-27 11:51:16.544  1037  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-27 11:51:16.545  7144  7144 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-27 11:51:16.545  7144  7144 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-27 11:51:16.545  7144  7144 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
07-27 11:51:16.546  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-27 11:51:16.548  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 1
07-27 11:51:16.556  1037  1530 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-27 11:51:16.556  1037  1530 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,07-27 11:51:16.557  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:16.557  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:51:16.557  1037  1530 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
07-27 11:51:16.558   332   895 E Netd    : netlink response contains error (File exists)
07-27 11:51:16.558  1037  1530 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
07-27 11:51:16.559  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:16.559  1037  1530 D ConnectivityService: addLocalRoutetoDefaultNetwork
07-27 11:51:16.559  1037  1530 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
07-27 11:51:16.559  1037  1530 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
07-27 11:51:16.561  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:16.561  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-27 11:51:16.561  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:16.566  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:16.566  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:16.566  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-27 11:51:16.566  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,07-27 11:51:16.570  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:16.570  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:16.570  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-27 11:51:16.570  1037  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-27 11:51:16.570  1037  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
07-27 11:51:16.570  1037  1530 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
07-27 11:51:16.571  1037  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
07-27 11:51:16.571  1037  7161 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:16.571  1037  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:51:16.571  1037  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:51:16.571  1037  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-27 11:51:16.571  1037  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:16.571  1037  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
07-27 11:51:16.571  1037  1530 D ConnectivityService: currentScore = 0, newScore = 20
07-27 11:51:16.571  1037  1530 D ConnectivityService:    accepting network in place of null
07-27 11:51:16.571  1037  1530 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:16.571  1037  7161 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
07-27 11:51:16.571  1037  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:16.571  1037  7161 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:16.571  1037  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:51:16.571  1037  7161 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-27 11:51:16.573  1837  1837 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:16.574  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-27 11:51:16.575  1037  1530 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-27 11:51:16.575  1037  1530 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-27 11:51:16.575   332  7179 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
07-27 11:51:16.575  1037  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-27 11:51:16.576  1037  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:16.576  1037  1530 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
07-27 11:51:16.576  1037  1530 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
07-27 11:51:16.577  1037  1037 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
07-27 11:51:16.578  7144  7144 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-27 11:51:16.578  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-27 11:51:16.578  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-27 11:51:16.578  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-27 11:51:16.578  7144  7144 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:51:16
07-27 11:51:16.580  1037  1530 D ConnectivityService: validation of new default Network = false
07-27 11:51:16.580  1037  1530 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
07-27 11:51:16.580  1037  1530 D DSQN    : enableDataServiceNotify 
07-27 11:51:16.580  1037  1530 D DSQN    : start dsqn bin
,07-27 11:51:16.582  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:16.582  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-27 11:51:16.583  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:16.617  1037  1872 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7180 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-27 11:51:16.618  1037  1872 I ActivityManager: Killing 6618:com.lge.bnr/1000 (adj 15): empty #17
,07-27 11:51:16.629   355   355 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 432us total 10.983ms
07-27 11:51:16.631   332  7179 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,07-27 11:51:16.639   355   355 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 190us total 10.543ms
07-27 11:51:16.657   355   355 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 186us total 16.768ms
,07-27 11:51:16.670   332  7179 D libc-netbsd: res_queryN name = clients3.google.com succeed
,07-27 11:51:16.677  1037  1962 W libprocessgroup: failed to open /acct/uid_1000/pid_6618/cgroup.procs: No such file or directory
,07-27 11:51:16.683  1037  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
07-27 11:51:16.683  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:16.683  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:51:16.683  1037  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:51:16.683  1587  2056 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,07-27 11:51:16.674  7197  7197 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:51:16.684  7197  7197 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-27 11:51:16.700  7197  7197 E DSQN    : DSQN ssw
07-27 11:51:16.702  1037  7167 D DhcpStateMachine: DHCPV4 request on wlan0
,07-27 11:51:16.702  1037  7167 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
07-27 11:51:16.702  1037  7167 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
07-27 11:51:16.703   332   894 D LGDataListener: argv[0]=dsqncommand
07-27 11:51:16.703   332   894 D LGDataListener: argv[1]=wlan0
07-27 11:51:16.703   332   894 D LGDataListener: argv[2]=1
07-27 11:51:16.703   332   894 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
07-27 11:51:16.704  1037  1118 D DSQN    : DSQM DsqnNotification wlan0  1
07-27 11:51:16.704  1037  1118 D DSQN    : start to monitor internet connection
07-27 11:51:16.694  7203  7203 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:51:16.694  7203  7203 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:51:16.708  1037  1521 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
07-27 11:51:16.714  7203  7203 I dhcpcd  : version 5.5.6 starting
07-27 11:51:16.716  7203  7203 E dhcpcd  : get_duid: m
,07-27 11:51:16.716  7203  7203 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
07-27 11:51:16.716  7203  7203 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
07-27 11:51:16.719  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-27 11:51:16.720  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:16.721  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 11:51:16.729  1802  7204 I CheckinService: active receiver: enabled
07-27 11:51:16.736  1802  7204 I CheckinService: Preparing to send checkin request
07-27 11:51:16.736  1802  7204 I EventLogService: Accumulating logs since 1469612829716
07-27 11:51:16.746  1037  7161 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jul 2016 09:51:16 GMT], X-Android-Received-Millis=[1469613076746], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1469613076703]}
07-27 11:51:16.747  1037  7161 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-27 11:51:16.747  1037  7161 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
07-27 11:51:16.747  1037  1530 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
07-27 11:51:16.747  1037  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
07-27 11:51:16.747  1037  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:51:16.747  1037  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:51:16.747  1037  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-27 11:51:16.747  1037  1530 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
07-27 11:51:16.747  1037  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
07-27 11:51:16.747  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:16.747  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:51:16.747  1037  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-27 11:51:16.748  1037  1530 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:16.748  1037  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-27 11:51:16.748  1037  1523 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 11:51:16.748  1037  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:51:16.749  1587  2056 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-27 11:51:16.750  1837  1837 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:16.750  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-27 11:51:16.750  7203  7203 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-27 11:51:16.750  7203  7203 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-27 11:51:16.750  7203  7203 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-27 11:51:16.751  7203  7203 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
07-27 11:51:16.751  7203  7203 D dhcpcd  : wlan0: sending REQUEST (xid 0x74f2d6f0), next in 3.24 seconds
,07-27 11:51:16.765  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-27 11:51:16.766  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:16.766  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:16.769  1802  7204 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
07-27 11:51:16.771   281   358 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-27 11:51:16.771   281   358 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-27 11:51:16.771   281   358 W Vold    : Returning OperationFailed - no handler for errno 0
07-27 11:51:16.772  7180  7213 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
07-27 11:51:16.773   281   358 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-27 11:51:16.773   281   358 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-27 11:51:16.773   281   358 W Vold    : Returning OperationFailed - no handler for errno 0
07-27 11:51:16.773  7180  7213 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-27 11:51:16.776  7203  7203 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,07-27 11:51:16.787  7203  7203 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
07-27 11:51:16.787  7203  7203 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
07-27 11:51:16.787  7203  7203 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
07-27 11:51:16.787  7203  7203 D dhcpcd  : wlan0: adding default route via 192.168.1.1
07-27 11:51:16.787   281   358 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-27 11:51:16.788   281   358 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-27 11:51:16.788   281   358 W Vold    : Returning OperationFailed - no handler for errno 0
07-27 11:51:16.788  7203  7203 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-27 11:51:16.788  7203  7203 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-27 11:51:16.788  7203  7203 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-27 11:51:16.788  7203  7203 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
07-27 11:51:16.788  7180  7215 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
07-27 11:51:16.789  1037  1366 D PowerManagerServiceEx: acquireWakeLockInternal: lock=375115087, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
07-27 11:51:16.789  1037  1366 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3b645f93 type 2 when 304617 com.google.android.gms} when 304617
,07-27 11:51:16.791   281   358 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-27 11:51:16.791   281   358 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-27 11:51:16.791   281   358 W Vold    : Returning OperationFailed - no handler for errno 0
07-27 11:51:16.792  7180  7215 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-27 11:51:16.816  2592  2592 D [Concierge]Service: onStartCommand(). Type : 9
,07-27 11:51:16.865  1037  2028 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7228 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,07-27 11:51:16.911  7228  7228 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-27 11:51:16.911  7228  7228 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-27 11:51:16.931  7228  7228 I MultiDex: VM with version 2.1.0 has multidex support
07-27 11:51:16.931  7228  7228 I MultiDex: install
07-27 11:51:16.931  7228  7228 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-27 11:51:16.940  7228  7228 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
07-27 11:51:17.010  7180  7180 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,07-27 11:51:17.018  7180  7180 I LibraryLoader: Loading: webviewchromium
07-27 11:51:17.020  7180  7180 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4860-4863)
07-27 11:51:17.020  7180  7180 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 11:51:17.024  7180  7180 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1134da1f}
,07-27 11:51:17.025  7180  7180 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 11:51:17.026  7180  7180 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-27 11:51:17.033  7180  7180 I BrowserStartupController: Initializing chromium process, renderers=0
07-27 11:51:17.034  7180  7180 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 11:51:17.046   336  1372 V AudioPolicyService: registerClient() client 0xb558a9e0, uid 10093
07-27 11:51:17.046  7180  7277 W AudioManagerAndroid: Requires BLUETOOTH permission
07-27 11:51:17.047  7180  7180 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-27 11:51:17.048  7180  7180 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
07-27 11:51:17.049  7180  7180 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,07-27 11:51:17.065  7180  7180 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 11:51:17.065  7180  7180 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 11:51:17.065  7180  7180 I Adreno-EGL: Build Date: 12/12/14 금
07-27 11:51:17.065  7180  7180 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-27 11:51:17.065  7180  7180 I Adreno-EGL: Remote Branch: 
07-27 11:51:17.065  7180  7180 I Adreno-EGL: Local Patches: 
07-27 11:51:17.065  7180  7180 I Adreno-EGL: Reconstruct Branch: 
,07-27 11:51:17.106  1037  7167 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,07-27 11:51:17.108  1037  7167 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
07-27 11:51:17.108  1037  7167 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-27 11:51:17.109  1037  7167 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
07-27 11:51:17.109  1037  7167 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
07-27 11:51:17.109  1037  7167 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-27 11:51:17.109  1037  7167 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
07-27 11:51:17.109  1037  7167 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
07-27 11:51:17.109  1037  7167 D DhcpStateMachine: RunningState
07-27 11:51:17.124  7180  7180 I NSApplication: Starting up...
,07-27 11:51:17.179  1037  1574 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7290 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
07-27 11:51:17.180  1037  1574 I ActivityManager: Killing 5843:com.android.vending/u0a44 (adj 15): empty #17
,07-27 11:51:17.239  1037  1926 W libprocessgroup: failed to open /acct/uid_10044/pid_5843/cgroup.procs: No such file or directory
,07-27 11:51:17.271  7307  7307 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,07-27 11:51:17.275  7290  7290 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 11:51:17.339  7307  7307 I dex2oat : dex2oat took 68.317ms (threads: 4)
,07-27 11:51:17.366  7228  7244 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 11:51:17.366  7228  7244 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 11:51:17.366  7228  7244 I Adreno-EGL: Build Date: 12/12/14 금
07-27 11:51:17.366  7228  7244 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-27 11:51:17.366  7228  7244 I Adreno-EGL: Remote Branch: 
07-27 11:51:17.366  7228  7244 I Adreno-EGL: Local Patches: 
07-27 11:51:17.366  7228  7244 I Adreno-EGL: Reconstruct Branch: 
07-27 11:51:17.507  1037  1890 I art     : Explicit concurrent mark sweep GC freed 87635(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.465ms total 140.651ms
,07-27 11:51:17.559  1037  1871 D WifiServiceImplEx: setWifiEnabled: false pid=6735, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-27 11:51:17.559  1037  1871 D WifiService: setWifiEnabled: false pid=6735, uid=10118
07-27 11:51:17.559  1037  1871 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-27 11:51:17.569  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 11:51:17.570  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-27 11:51:17.570  1037  1037 D Ulp_jni : JNI:system_update. Event-4
07-27 11:51:17.571  1037  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
07-27 11:51:17.571  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
07-27 11:51:17.572  1037  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
07-27 11:51:17.572  1037  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
07-27 11:51:17.572  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
07-27 11:51:17.572  1037  1523 E WifiStateMachine: WifiStateMachine: Leaving Connected state
07-27 11:51:17.573  1037  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 11:51:17.573  1037  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-27 11:51:17.573  1037  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-27 11:51:17.573  1037  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-27 11:51:17.580  1037  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
,07-27 11:51:17.580  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-27 11:51:17.580  7068  7068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-27 11:51:17.580  1037  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:17.581  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:17.581  1037  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-27 11:51:17.581  1037  1523 D WifiNative-wlan0: doBoolean: SET ps 1
07-27 11:51:17.581  1037  1523 D WifiNative-wlan0: SET ps 1: returned true
07-27 11:51:17.582   332   895 D CommandListener: Clearing all IP addresses on wlan0
07-27 11:51:17.582  1037  7167 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:17.619  1037  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:17.619  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:17.619  1037  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:17.621  1037  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-27 11:51:17.621  1037  1530 D ConnectivityService: ignoring duplicate network state non-change
07-27 11:51:17.621  1037  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
07-27 11:51:17.623  1037  1522 D LGWifiP2pService: InactiveState{ when=-5ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:17.623  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:17.623  1037  1522 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1f527ee2
07-27 11:51:17.624  1037  1037 D WifiHS20: hidePasspointNotification off =false
,07-27 11:51:17.625  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 0
07-27 11:51:17.627  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:17.627  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:17.627  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:51:17.628  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:17.628  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-27 11:51:17.629  1037  1037 D WifiHS20: hidePasspointNotification off =false
07-27 11:51:17.633  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:17.633  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:17.633  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-27 11:51:17.633  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:17.635  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 1
07-27 11:51:17.635  1037  1541 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:17.635  1037  1037 D RttService: SCAN_AVAILABLE : 1
07-27 11:51:17.636  1037  1542 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:17.636  1037  1522 D LGWifiP2pService: P2pDisablingState
07-27 11:51:17.636  1037  1522 D LGWifiP2pService: P2pDisablingState{ when=-13ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:17.636  1037  1522 D LGWifiP2pService: p2p socket connection lost
07-27 11:51:17.636  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:17.636  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:51:17.636  1037  1522 D LGWifiP2pService: P2pDisabledState
07-27 11:51:17.648  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:17.649  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-27 11:51:17.650  1927  1927 D WfdsService: WifiP2pState is changed : false
07-27 11:51:17.650  1927  2323 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
07-27 11:51:17.650  1927  2323 D WfdsService: Set the WFDS Monitor: false
,07-27 11:51:17.651  1927  2323 D WfdsMonitor: WFDS Monitor is stopped
07-27 11:51:17.651  1927  2323 D WfdsService: STATE : WfdsDisabledState - enter
07-27 11:51:17.651  1927  7100 D CtrlSupplicant: Received on exit socket, terminate
07-27 11:51:17.651  1927  7100 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
07-27 11:51:17.651  1927  7100 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
07-27 11:51:17.652  1927  7100 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
07-27 11:51:17.652  1927  2326 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
07-27 11:51:17.654  1927  2323 W WfdsService: DefaultState - msg [9445378] is not handled
07-27 11:51:17.659  1037  1523 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-27 11:51:17.659  1037  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
07-27 11:51:17.659  1037  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:17.659  1037  1522 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:17.660  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-27 11:51:17.660  7068  7068 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-27 11:51:17.660  1037  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-27 11:51:17.660  1037  1523 D WifiNative-wlan0: doBoolean: SET ps 1
07-27 11:51:17.660  1037  1523 D WifiNative-wlan0: SET ps 1: returned true
07-27 11:51:17.680   332   895 D CommandListener: Clearing all IP addresses on wlan0
,07-27 11:51:17.680  1037  1530 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
07-27 11:51:17.680  1037  1530 D DSQN    : disableDataServiceNotify
07-27 11:51:17.680  1037  1530 D DSQN    : stop dsqn bin
07-27 11:51:17.681  7228  7244 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 11:51:17.681  7228  7244 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 11:51:17.681  7228  7244 I Adreno-EGL: Build Date: 12/12/14 금
07-27 11:51:17.681  7228  7244 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-27 11:51:17.681  7228  7244 I Adreno-EGL: Remote Branch: 
07-27 11:51:17.681  7228  7244 I Adreno-EGL: Local Patches: 
07-27 11:51:17.681  7228  7244 I Adreno-EGL: Reconstruct Branch: 
07-27 11:51:17.684  1037  1530 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
07-27 11:51:17.684  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:17.684  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:51:17.684  1037  1530 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:51:17.685  1037  1530 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
07-27 11:51:17.685  1037  1530 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
07-27 11:51:17.685  1037  1530 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-27 11:51:17.685  1037  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-27 11:51:17.685  1037  7161 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:17.685  1037  7161 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:17.685  1037  7161 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-27 11:51:17.686  1587  2056 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
07-27 11:51:17.687  1037  1523 D WifiNative-p2p0: doBoolean: TERMINATE
07-27 11:51:17.687  1037  1523 D WifiNative-p2p0: TERMINATE: returned true
07-27 11:51:17.688  1037  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-27 11:51:17.688  1037  1523 E WifiStateMachine: useWiFiOffloading() : false
07-27 11:51:17.688  1037  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-27 11:51:17.688  1037  1037 D WifiHS20: hidePasspointNotification off =false
07-27 11:51:17.688  1037  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:17.689  1037  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-27 11:51:17.689  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:17.,689  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:17.689  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-27 11:51:17.689  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-27 11:51:17.689  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-27 11:51:17.689  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-27 11:51:17.689  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-27 11:51:17.689  1037  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-27 11:51:17.690  1037  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:17.690  1037  1530 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:17.691  1037  1530 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:17.691  1837  1837 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:17.691  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-27 11:51:17.691  1037  1530 D NetworkManagementService: Removing idletimer
07-27 11:51:17.691  1037  1530 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:17.691  1037  1523 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:17.691  1037  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:51:17.692  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-27 11:51:17.692  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:51:17.692  1037  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-27 11:51:17.692  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:17.694  6735  6735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:17.695  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:17.695  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:17.695  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:17.695  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:51:17.695  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:51:17.695  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:17.695  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to ,active network: false
07-27 11:51:17.695  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:51:17.695  6735  6735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:17.695  6735  6735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:51:17.695  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
07-27 11:51:17.695  6735  6735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:17.695  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:17.695  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:17.695  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:17.695  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:51:17.695  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:51:17.695  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:17.695  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:17.695  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:51:17.695  6735  6735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:17.695  6735  6735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:51:17.696  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-27 11:51:17.698  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
07-27 11:51:17.698  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:51:17.698  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
07-27 11:51:17.698  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-27 11:51:17.698  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-27 11:51:17.698  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-27 11:51:17.698  1037  1530 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
07-27 11:51:17.719  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-27 11:51:17.720  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:17.721  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 11:51:17.733  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-27 11:51:17.734  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:17.734  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:17.737  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:17.748  7228  7244 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 11:51:17.748  7228  7244 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 11:51:17.748  7228  7244 I Adreno-EGL: Build Date: 12/12/14 금
07-27 11:51:17.748  7228  7244 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-27 11:51:17.748  7228  7244 I Adreno-EGL: Remote Branch: 
07-27 11:51:17.748  7228  7244 I Adreno-EGL: Local Patches: 
07-27 11:51:17.748  7228  7244 I Adreno-EGL: Reconstruct Branch: 
,07-27 11:51:17.774  6426  6426 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,07-27 11:51:17.775  6426  6831 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,07-27 11:51:17.778  7068  7068 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-27 11:51:17.778  7068  7068 I wpa_supplicant: monitor socket send errors count : 1
07-27 11:51:17.778  7068  7068 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1927-4\x00 that cannot receive messages
07-27 11:51:17.780  1037  7092 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
07-27 11:51:17.780  1037  7092 D WifiMonitor: Dropping event because (p2p0) is stopped
07-27 11:51:17.789  1037  7167 D DhcpStateMachine: StoppedState
07-27 11:51:17.789  1037  7167 D DhcpStateMachine: StoppedState{ when=-129ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:17.789  2194  2194 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:17.789  1037  1523 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
07-27 11:51:17.790  1037  1523 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,07-27 11:51:17.797  7016  7016 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-27 11:51:17.797  7016  7016 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:17.798  7016  7016 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-27 11:51:17.798  7016  7016 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-27 11:51:17.799  7016  7016 I AppUp4:CustModeStarterReceiver: onReceive
,07-27 11:51:17.803  7016  7016 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@215a71a4
07-27 11:51:17.803  7016  7016 D AppUp4:CustFacade: isCustomizationCompleted : false
07-27 11:51:17.803  7016  7016 D AppUp4:CustFacade: isPhone : true
07-27 11:51:17.805  7016  7016 D AppUp4:CustModeStarterReceiver: begin check event
07-27 11:51:17.805  7016  7016 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-27 11:51:17.809  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:17.809  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 11:51:17.811  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 11:51:17.812  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 11:51:17.817  4297  7337 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-27 11:51:17.818  7042  7042 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
07-27 11:51:17.821  7228  7244 D LgDataFeature: LgDataFeature() Constructor: none
07-27 11:51:17.821  7228  7244 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 11:51:17.824  7068  7068 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-27 11:51:17.824  4297  7338 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:17.824  4297  7338 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-27 11:51:17.825  7068  7068 W wpa_supplicant: USIM:  scard_deinit function
07-27 11:51:17.825  1037  7092 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
07-27 11:51:17.825  1037  7092 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-27 11:51:17.826  1037  7092 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-27 11:51:17.826  1037  7092 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
07-27 11:51:17.826  1037  7092 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 11:51:17.826  1037  7092 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 11:51:17.826  1037  1120 D Tethering: InitialState.processMessage what=4
07-27 11:51:17.826  1037  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=305654
,07-27 11:51:17.826  1037  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=305654
07-27 11:51:17.827  1037  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=305655  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-27 11:51:17.827  1037  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=305655  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-27 11:51:17.828  1037  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-27 11:51:17.829  1037  1523 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:51:17.829  1037  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:51:17.838  7042  7339 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:17.841  6921  7341 W FormManager: Network not available. Please check & try again.
,07-27 11:51:17.843  3414  3414 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-27 11:51:17.843  3414  3414 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:17.843  3414  3414 I LgeMiscReceiver: networkInfo.isConnected() = false
07-27 11:51:17.845  7082  7082 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-27 11:51:17.845  7082  7082 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-27 11:51:17.855  6921  7342 V FormManager: Network unavailable.
,07-27 11:51:17.861  7144  7144 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:51:17
07-27 11:51:17.862  6921  7342 V FormManager: Network unavailable.
07-27 11:51:17.863  7144  7144 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-27 11:51:17.863  7144  7144 D Weather.Utils: 2 : All the weather widget is gone.
07-27 11:51:17.863  7144  7144 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-27 11:51:17.863  7144  7144 D WeatherAncestor: connectivity changed - connection : true
07-27 11:51:17.863  7144  7144 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1c195ac2
07-27 11:51:17.864  7144  7144 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-27 11:51:17.864  7144  7144 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-27 11:51:17.864  7144  7144 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-27 11:51:17.864  7144  7144 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-27 11:51:17.864  7144  7144 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:51:17
07-27 11:51:17.884  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-27 11:51:17.884  6803  6803 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,07-27 11:51:17.886  6803  6803 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-27 11:51:17.886  6803  6803 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-27 11:51:17.887  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-27 11:51:17.889  6803  6803 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-27 11:51:17.889  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-27 11:51:17.889  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-27 11:51:17.889  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-27 11:51:17.889  6803  6803 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-27 11:51:17.889  6803  6803 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-27 11:51:17.895  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-27 11:51:17.898  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-27 11:51:17.904  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:17.909  6921  7348 W FormManager: Network not available. Please check & try again.
,07-27 11:51:17.911  6921  7349 V FormManager: Network unavailable.
07-27 11:51:17.917  6921  7349 V FormManager: Network unavailable.
07-27 11:51:17.928  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-27 11:51:17.930  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-27 11:51:17.932  6921  7350 W FormManager: Network not available. Please check & try again.
07-27 11:51:17.938  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:17.940  6921  7351 V FormManager: Network unavailable.
,07-27 11:51:17.949  6921  7351 V FormManager: Network unavailable.
07-27 11:51:17.949  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-27 11:51:17.950  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 11:51:17.951  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-27 11:51:17.954  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 11:51:17.958  7068  7068 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-27 11:51:17.958  1037  7092 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
07-27 11:51:17.958  1037  7092 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
07-27 11:51:17.958  1037  7092 D WifiMonitor: Disconnecting from the supplicant, no more events
07-27 11:51:17.960  1037  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
07-27 11:51:17.963  4297  7352 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-27 11:51:17.968  4297  7353 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-27 11:51:17.968  4297  7353 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-27 11:51:17.987  1037  1997 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7354 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,07-27 11:51:18.050  7354  7354 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-27 11:51:18.050  7354  7354 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,07-27 11:51:18.058  7354  7354 V [BNRBootReceiver]: Boot Receiver Return
07-27 11:51:18.060  7354  7354 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-27 11:51:18.061  1037  1523 D WifiOffDelayIfNotUsed: stopMonitoring
07-27 11:51:18.061  1037  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-27 11:51:18.061  1037  1523 E WifiStateMachine: useWiFiOffloading() : false
07-27 11:51:18.061  1037  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-27 11:51:18.062  1927  1927 D WfdsService: Supplicant Connection state is changed : false
07-27 11:51:18.062  1927  2323 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
07-27 11:51:18.062  1927  2323 D WfdsService: Set the WFDS Monitor: false
07-27 11:51:18.062  1927  2323 D WfdsMonitor: WFDS Monitor is stopped
07-27 11:51:18.062  6426  6426 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 11:51:18.066  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:18.068  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-27 11:51:18.069  2455  2455 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:18.069  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
07-27 11:51:18.069  1037  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
07-27 11:51:18.069  1037  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
07-27 11:51:18.070  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:18.071  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:18.071  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:51:18.078  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:18.091  6878  6878 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-27 11:51:18.092  6878  6878 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:51:18.095  6878  6878 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-27 11:51:18.098  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
07-27 11:51:18.102  6803  6803 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
07-27 11:51:18.105  6426  6426 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 11:51:18.108   332  7373 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-27 11:51:18.108  1037  1118 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-27 11:51:18.109  1802  7204 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
07-27 11:51:18.110  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 11:51:18.115  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:18.117  1802  7204 I CheckinService: active receiver: disabled
,07-27 11:51:18.128  6878  6878 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:51:18.128  6878  6878 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:51:18.129  6878  6878 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-27 11:51:18.132  6426  6426 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:51:18.137  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:51:18.143  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:18.151  6878  6878 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:51:18.151  6878  6878 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:51:18.152  6878  6878 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-27 11:51:18.154  6426  6426 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:51:18.163  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:51:18.167  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:18.174  6878  6878 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-27 11:51:18.175  6878  6878 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:51:18.175  6878  6878 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 11:51:18.180  6426  6426 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:51:18.190  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:51:18.206  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:18.220  6878  6878 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:51:18.221  6878  6878 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:51:18.222  6878  6878 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-27 11:51:18.229  6426  6426 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:51:18.242  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:51:18.251  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:18.263  6878  6878 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:51:18.264  6878  6878 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:51:18.264  6878  6878 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-27 11:51:18.273  6426  6426 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:51:18.289  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:51:18.301  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:18.314  6878  6878 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:51:18.315  6878  6878 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:51:18.316  6878  6878 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-27 11:51:18.331  6426  6426 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 11:51:18.354  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:51:18.367  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-27 11:51:18.378  6878  6878 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:51:18.379  6878  6878 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-27 11:51:18.387  6878  6878 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-27 11:51:18.401  6426  6426 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:51:18.418  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:51:18.428  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:18.444  6878  6878 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:51:18.445  6878  6878 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-27 11:51:18.447  6878  6878 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 11:51:18.452  6426  6426 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:51:18.456  6833  6833 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-27 11:51:18.472  1037  1528 D WifiService: New client listening to asynchronous messages
,07-27 11:51:18.478  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 11:51:18.486  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:51:18.511  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:18.533  6878  6878 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-27 11:51:18.534  6878  6878 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:51:18.537  6878  6878 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-27 11:51:18.539  6878  6878 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-27 11:51:18.541  6878  6878 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-27 11:51:18.551  6426  6426 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 11:51:18.559  6833  6833 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-27 11:51:18.562  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 11:51:18.570  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:51:18.584  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-27 11:51:18.596  6878  6878 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:51:18.596  6878  6878 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:51:18.598  6878  6878 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-27 11:51:18.600  6878  6878 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-27 11:51:18.601  6878  6878 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,07-27 11:51:18.607  1037  1060 I ActivityManager: Killing 6854:com.lge.lifetracker/u0a37 (adj 15): empty #17
07-27 11:51:18.613   332  7380 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-27 11:51:18.613  1037  1118 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,07-27 11:51:18.654  6639  6991 D UEI.SmartControl: Internal timer expired: 2
07-27 11:51:18.654  6639  6991 D UEI.SmartControl: unbind internal service
,07-27 11:51:18.700  1037  1962 W libprocessgroup: failed to open /acct/uid_10037/pid_6854/cgroup.procs: No such file or directory,
,07-27 11:51:18.709  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=375115087 [*alarm*], flags=0x0
07-27 11:51:18.717  2194  2194 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
07-27 11:51:18.741  2194  2194 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-27 11:51:18.745  2194  2194 D c       : Getting all permits...
07-27 11:51:18.745  2194  2194 D a       : Opening database...
07-27 11:51:18.751  6639  6985 D serial_port: close(fd = 24)
07-27 11:51:18.752  2194  2194 D a       : Opening database auth.proximity.permit_store...
07-27 11:51:18.753  2194  2194 D a       : Closing database...
07-27 11:51:18.755  6639  6985 I UEI.SmartControl: Serial port is closed.
07-27 11:51:18.772  6426  6426 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 11:51:18.779  6833  6833 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-27 11:51:18.779  6833  6833 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-27 11:51:18.779  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 11:51:18.783  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:51:18.795  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:18.809  6878  6878 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-27 11:51:18.810  6878  6878 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:51:18.815  6878  6878 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-27 11:51:18.828  6426  6426 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-27 11:51:18.840  6833  6833 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-27 11:51:18.840  6833  6833 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-27 11:51:18.840  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 11:51:18.847  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:51:18.863  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:18.875  6878  6878 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:51:18.876  6878  6878 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:51:18.878  6878  6878 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-27 11:51:18.883  6426  6426 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:51:18.889  6833  6833 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-27 11:51:18.889  6833  6833 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-27 11:51:18.889  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 11:51:18.896  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:51:18.912  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:18.926  6878  6878 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:51:18.926  6878  6878 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-27 11:51:18.931  6878  6878 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-27 11:51:18.947  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-27 11:51:18.955  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-27 11:51:18.963  6921  7384 W FormManager: Network not available. Please check & try again.
,07-27 11:51:18.972  6921  7385 V FormManager: Network unavailable.
07-27 11:51:18.978  6921  7385 V FormManager: Network unavailable.
07-27 11:51:18.979  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:19.013  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-27 11:51:19.013  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 11:51:19.016  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-27 11:51:19.023  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 11:51:19.035  4297  7386 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-27 11:51:19.043  4297  7387 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-27 11:51:19.043  4297  7387 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-27 11:51:19.047  6833  6833 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
07-27 11:51:19.047  6833  6833 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-27 11:51:19.047  6833  6833 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 11:51:19.053  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:51:19.061  6921  7389 W FormManager: Network not available. Please check & try again.
07-27 11:51:19.068  6921  7390 V FormManager: Network unavailable.
07-27 11:51:19.069  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-27 11:51:19.082  6921  7390 V FormManager: Network unavailable.
,07-27 11:51:19.088  2194  2194 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-27 11:51:19.491  1037  1523 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:734264258] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-27 11:51:19.493  1037  1523 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:734264261] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-27 11:51:19.579  1037  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:51:19.598  1037  1109 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:19.599  1037  1120 D Tethering: MasterInitialState.processMessage what=3
07-27 11:51:19.606  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:19.611  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:19.617  6426  6426 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-27 11:51:19.619  6426  6831 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-27 11:51:19.629  5768  5768 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,07-27 11:51:19.653  2194  2194 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:51:19.674  7016  7016 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-27 11:51:19.675  7016  7016 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:19.675  7016  7016 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-27 11:51:19.675  7016  7016 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,07-27 11:51:19.680  7016  7016 I AppUp4:CustModeStarterReceiver: onReceive
07-27 11:51:19.684  7016  7016 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@215a71a4
07-27 11:51:19.684  7016  7016 D AppUp4:CustFacade: isCustomizationCompleted : false
07-27 11:51:19.684  7016  7016 D AppUp4:CustFacade: isPhone : true
07-27 11:51:19.684  7016  7016 D AppUp4:CustModeStarterReceiver: begin check event
07-27 11:51:19.685  7016  7016 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-27 11:51:19.689  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:19.690  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 11:51:19.691  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-27 11:51:19.698  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 11:51:19.705  7042  7042 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-27 11:51:19.746  4297  7399 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-27 11:51:19.758  1037  1109 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:19.767  4297  7405 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:19.767  4297  7405 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,07-27 11:51:19.769  7042  7398 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:19.776  3414  3414 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-27 11:51:19.776  3414  3414 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:19.777  3414  3414 I LgeMiscReceiver: networkInfo.isConnected() = true
07-27 11:51:19.777  3414  3414 D PhoneState: setPdpRejectCasuse : false
07-27 11:51:19.778  6921  7414 W FormManager: Network not available. Please check & try again.
07-27 11:51:19.783  7082  7082 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-27 11:51:19.783  7082  7082 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,07-27 11:51:19.785  6921  7415 V FormManager: Network unavailable.
07-27 11:51:19.795  6921  7415 V FormManager: Network unavailable.
,07-27 11:51:19.798  7144  7144 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:51:19
,07-27 11:51:19.800  7144  7144 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-27 11:51:19.800  7144  7144 D Weather.Utils: 2 : All the weather widget is gone.
07-27 11:51:19.800  7144  7144 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-27 11:51:19.801  7144  7144 D WeatherAncestor: connectivity changed - connection : true
07-27 11:51:19.801  7144  7144 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1c195ac2
07-27 11:51:19.802  7144  7144 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-27 11:51:19.802  7144  7144 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-27 11:51:19.802  7144  7144 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-27 11:51:19.802  7144  7144 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-27 11:51:19.802  7144  7144 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:51:19
07-27 11:51:20.574  1037  1997 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:20.575  1037  1997 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,07-27 11:51:20.603  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 11:51:20.603  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-27 11:51:20.603  1037  1037 D Ulp_jni : JNI:system_update. Event-4
07-27 11:51:20.604  1037  1120 D BluetoothManagerService: Message: 1
07-27 11:51:20.604  1037  1120 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
07-27 11:51:20.629  1037  1120 D BluetoothManagerService: Message: 20
07-27 11:51:20.629  1037  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@376049b6:true
,07-27 11:51:20.634  6952  6952 D BluetoothAdapterState: make
07-27 11:51:20.641  6952  6952 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
07-27 11:51:20.641  6952  6952 I bluedroid-qcom: init
07-27 11:51:20.643  6952  7431 I BluetoothAdapterState: Entering OffState
,07-27 11:51:20.646  6952  6952 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-27 11:51:20.646  6952  6952 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-27 11:51:20.647  6952  6952 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-27 11:51:20.647  6952  6952 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-27 11:51:20.647  6952  6952 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
07-27 11:51:20.649  6952  6952 I bluedroid-qcom: get_profile_interface socket
07-27 11:51:20.649  6952  6952 I bluedroid-qcom: get_profile_interface map_client
07-27 11:51:20.650  6952  7435 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
07-27 11:51:20.653  6952  7435 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-27 11:51:20.644  7434  7434 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:51:20.644  7434  7434 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:51:20.661  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-27 11:51:20.661  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
,07-27 11:51:20.671  7434  7434 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
07-27 11:51:20.671  7434  7434 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
07-27 11:51:20.671  7434  7434 I LGFTMITEM: [GET_FTM][id=8], offset=16384
07-27 11:51:20.672  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
07-27 11:51:20.673  1037  1120 D BluetoothManagerService: Message: 40
07-27 11:51:20.673  1037  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
07-27 11:51:20.674  6952  6967 I bluedroid-qcom: config_hci_snoop_log
07-27 11:51:20.677  1037  1120 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
07-27 11:51:20.677  1037  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,07-27 11:51:20.680  7434  7434 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
07-27 11:51:20.686  7434  7434 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
07-27 11:51:20.686  7434  7434 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
07-27 11:51:20.690  1037  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:51:20.694  1037  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:20.703  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:20.707  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:20.717  6952  7431 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,07-27 11:51:20.720  1037  1120 D Tethering: MasterInitialState.processMessage what=3
07-27 11:51:20.720  1037  1120 D Tethering: MasterInitialState.processMessage what=3
07-27 11:51:20.720  6952  7435 D BluetoothAdapterProperties: Name is: G3
07-27 11:51:20.721  6952  7431 D BluetoothAdapterProperties: Setting state to 11
07-27 11:51:20.721  6952  7431 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-27 11:51:20.722  6952  7431 I LGBluetoothServiceJni: classInitNative: succeeds
07-27 11:51:20.724  1037  1120 D BluetoothManagerService: Message: 60
07-27 11:51:20.724  1037  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-27 11:51:20.725  1037  1120 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
07-27 11:51:20.736  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:20.747  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:20.748  6426  6426 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,07-27 11:51:20.748  1037  1109 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:20.752  6426  6831 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-27 11:51:20.753  6952  7431 D BluetoothBondStateMachine: make
07-27 11:51:20.755  6952  7431 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c195ac2
07-27 11:51:20.755  6952  7431 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
07-27 11:51:20.755  6952  7431 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c195ac2
07-27 11:51:20.755  6952  7431 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
07-27 11:51:20.755  6952  7431 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
07-27 11:51:20.756  6952  7450 I BluetoothBondStateMachine: StableState(): Entering Off State
07-27 11:51:20.759  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:20.761  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:20.762  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:20.767  6803  6803 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
07-27 11:51:20.767  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,07-27 11:51:20.772  6952  6952 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-27 11:51:20.773  6952  6952 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:20.773  6952  6952 V BluetoothPbapReceiver: ***********state = 11
07-27 11:51:20.776  5768  5768 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-27 11:51:20.777  6952  7431 E BluetoothAdapterService: File transfer profiles supported!!
07-27 11:51:20.781  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-27 11:51:20.783  5768  5768 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,07-27 11:51:20.788  6952  7431 E BluetoothAdapterService: File transfer profiles supported!!
07-27 11:51:20.789  6952  6952 D HeadsetService: Received start request. Starting profile...
07-27 11:51:20.789  6952  6952 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
07-27 11:51:20.789  6952  6952 D LGBluetoothHfpAdapter: Version 1.6
07-27 11:51:20.791  6952  6952 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-27 11:51:20.792  6952  6952 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-27 11:51:20.792  1037  1109 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:20.792  6952  6952 D HeadsetStateMachine: make
07-27 11:51:20.795  6952  7431 E BluetoothAdapterService: File transfer profiles supported!!
07-27 11:51:20.819  6952  6952 D LgDataFeature: LgDataFeature() Constructor: none
07-27 11:51:20.819  6952  6952 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 11:51:20.830  1037  1998 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7455 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
07-27 11:51:20.835  6952  6952 D HeadsetStateMachine: max_hf_connections = 1
07-27 11:51:20.835  6952  6952 I bluedroid-qcom: get_profile_interface handsfree
07-27 11:51:20.836  6952  7431 E BluetoothAdapterService: File transfer profiles supported!!
,07-27 11:51:20.837  6952  6952 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
07-27 11:51:20.838   336  2146 V AudioPolicyService: registerClient() client 0xb558ade0, uid 1002
07-27 11:51:20.838   336  1371 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
07-27 11:51:20.838   336  1371 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 11:51:20.838   336  1371 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 11:51:20.838  6952  6952 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-27 11:51:20.839   336  1372 V AudioFlinger: registerClient() client 0xb14330a0, pid 6952
07-27 11:51:20.839   336  1365 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 11:51:20.839   336  1365 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 11:51:20.839  6952  6952 V ToneGenerator: Create Track: 0xb4928a80
07-27 11:51:20.839  6952  6952 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-27 11:51:20.839  6952  6952 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
07-27 11:51:20.839   336  2149 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-27 11:51:20.840   336  2149 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
07-27 11:51:20.840   336  2149 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 11:51:20.840   336  2149 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 11:51:20.840  6952  6952 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-27 11:51:20.840  1037  1574 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 11:51:20.840  1037  1574 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 11:51:20.840   336  1371 I AudioFlinger: isAudioPlaybackHookOn() false
07-27 11:51:20.840   336  1372 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-27 11:51:20.841   336  1372 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-27 11:51:20.841   336  1372 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 11:51:20.841   336  1372 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 11:51:20.842  1837  1853 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 11:51:20.842  1837  1853 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 11:51:20.842  3414  3430 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 11:51:20.842  3414  3430 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 11:51:20.842   336  1367 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 11:51:20.842   336  1367 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 11:51:20.842  1037  1871 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 11:51:20.842  1037  1871 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 11:51:20.842  6952  7436 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 11:51:20.842  6952  7436 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-27 11:51:20.842  1837  2507 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 11:51:20.842  1837  2507 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 11:51:20.842  6952  7436 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 11:51:20.842  6952  7436 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-27 11:51:20.842  3414  3429 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 11:51:20.842  3414  3429 V AudioSystem: ioConfigChanged() opening already existing, output! 4
07-27 11:51:20.842  1587  2106 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 11:51:20.842  1587  2106 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 11:51:20.842  1587  2106 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 11:51:20.842  1587  2106 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 11:51:20.843  6952  6952 V AudioSystem: getLatency() output 2, latency 50
07-27 11:51:20.843  6952  6952 V AudioSystem: getFrameCount() output 2, frameCount 960
07-27 11:51:20.843  6952  6952 V AudioTrack: createTrack_l() output 2 afLatency 50
07-27 11:51:20.843  1037  1109 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:20.843  1037  1109 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:20.844   336  2149 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-27 11:51:20.844   336  2149 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-27 11:51:20.844   336  2149 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-27 11:51:20.844   336  2149 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-27 11:51:20.844   336  2149 V AudioFlinger: createTrack() lSessionId: 22
07-27 11:51:20.844  6952  7431 E BluetoothAdapterService: File transfer profiles supported!!
07-27 11:51:20.845  6952  6952 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-27 11:51:20.846   336  2149 V AudioFlinger: acquiring 22 from 6952, for 6952
07-27 11:51:20.846   336  2149 V AudioFlinger:  added new entry for 22
07-27 11:51:20.846  6952  6952 V ToneGenerator: ToneGenerator INIT OK, time: 308689
07-27 11:51:20.846  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c195ac2
07-27 11:51:20.846  2194  2194 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:20.847  6952  7454 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
07-27 11:51:20.847  6952  7454 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-27 11:51:20.848  6952  7454 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-27 11:51:20.848  6952  7454 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
07-27 11:51:20.848  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c195ac2
07-27 11:51:20.849   336  2146 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6952
07-27 11:51:20.850   336  2146 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
07-27 11:51:20.850   336  2146 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-27 11:51:20.850   336  2146 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-27 11:51:20.850   336  2146 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-27 11:51:20.850   336  2146 V voice   : voice_set_parameters: exit with code(0)
07-27 11:51:20.850   336  2146 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
07-27 11:51:20.850   336  2146 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-27 11:51:20.850   336  2146 V msm8974_platform: platform_set_parameters: exit with code(0)
07-27 11:51:20.850   336  2146 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-27 11:51:20.850   336,  2146 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-27 11:51:20.850   336  2146 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-27 11:51:20.851  6952  6952 D A2dpService: Received start request. Starting profile...
07-27 11:51:20.852  6952  7454 V ToneGenerator: ToneGenerator destructor
07-27 11:51:20.852  6952  7454 V ToneGenerator: stopTone
07-27 11:51:20.852  6952  7454 V ToneGenerator: Delete Track: 0xb4928a80
07-27 11:51:20.852  6952  6952 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-27 11:51:20.853  6952  7454 V AudioTrack: ~AudioTrack, releasing session id from 6952 on behalf of 6952
07-27 11:51:20.853   336   336 V AudioFlinger: releasing 22 from 6952 for 6952
07-27 11:51:20.853   336   336 V AudioFlinger:  decremented refcount to 0
07-27 11:51:20.853   336   336 V AudioFlinger: purging stale effects
07-27 11:51:20.853   336   336 V AudioPolicyService: AudioCommandThread() adding release output 2
07-27 11:51:20.853   336   336 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-27 11:51:20.853   336  1275 V AudioPolicyService: AudioCommandThread() waking up
07-27 11:51:20.853   336  1275 V AudioPolicyService: AudioCommandThread() processing release output 2
07-27 11:51:20.853   336  1275 V AudioPolicyManager: releaseOutput() 2
07-27 11:51:20.853   336  1275 V AudioPolicyService: AudioCommandThread() going to sleep
07-27 11:51:20.853   336   336 V AudioFlinger: PlaybackThread::Track destructor
07-27 11:51:20.853   336   336 V AudioFlinger: removeClient_l() pid 6952, calling pid 336
07-27 11:51:20.853  6952  7431 E BluetoothAdapterService: File transfer profiles supported!!
07-27 11:51:20.854  6952  6952 V Avrcp   : make
07-27 11:51:20.854  6952  6952 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-27 11:51:20.854  6952  6952 I bluedroid-qcom: get_profile_interface avrcp
07-27 11:51:20.865  6952  7431 E BluetoothAdapterService: File transfer profiles supported!!
07-27 11:51:20.871  7016  7016 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-27 11:51:20.871  7016  7016 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:20.873  6952  6952 V AudioManager: registerRemoteController: size of Media player list: 0
07-27 11:51:20.874  7016  7016 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-27 11:51:20.874  7016  7016 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-27 11:51:20.874  6952  6952 E AudioManager: No RCC entry present to update
07-27 11:51:20.875  6952  6952 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-27 11:51:20.879  6952  6952 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
07-27 11:51:20.880  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
07-27 11:51:20.880  6952  6952 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
07-27 11:51:20.884  7016  7016 I AppUp4:CustModeStarterReceiver: onReceive
07-27 11:51:20.898  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,07-27 11:51:20.900  6952  7431 V LGMDMManager: Create singleton instance
,07-27 11:51:20.904  6952  7431 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
07-27 11:51:20.905  7016  7016 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@215a71a4
07-27 11:51:20.905  7016  7016 D AppUp4:CustFacade: isCustomizationCompleted : false
07-27 11:51:20.905  7016  7016 D AppUp4:CustFacade: isPhone : true
07-27 11:51:20.960  7016  7016 D AppUp4:CustModeStarterReceiver: begin check event
07-27 11:51:20.960  7016  7016 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,07-27 11:51:20.973  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:20.974  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 11:51:20.979  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-27 11:51:20.987  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 11:51:20.992  4297  7477 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-27 11:51:21.000  4297  7478 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:21.000  4297  7478 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-27 11:51:21.005  7042  7042 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
07-27 11:51:21.025  1037  1908 V SIM_STK : Menu title from STK is T-Mobile
07-27 11:51:21.025  1037  1908 V SIM_STK : Menu title from STK is T-Mobile
07-27 11:51:21.025  7042  7479 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:21.027  3414  3414 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-27 11:51:21.027  3414  3414 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:21.028  3414  3414 I LgeMiscReceiver: networkInfo.isConnected() = false
,07-27 11:51:21.035  7082  7082 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-27 11:51:21.035  7082  7082 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-27 11:51:21.043  7455  7455 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
07-27 11:51:21.043  7455  7455 W LG Account v2.2: No ProfileInfo entries
07-27 11:51:21.044  7455  7455 I LG Account v2.2: isEnabled: false
,07-27 11:51:21.044  7455  7455 I Feature : [Lifetracker]ver: 4.21.112(40211120)
07-27 11:51:21.044  7455  7455 I Feature : [Lifetracker]Country: EU
07-27 11:51:21.044  7455  7455 I Feature : [Lifetracker]Operator: OPEN
07-27 11:51:21.044  7455  7455 I Feature : [Lifetracker]Ranking support: false
07-27 11:51:21.044  7455  7455 I Feature : [Lifetracker]Comfort support: false
07-27 11:51:21.044  7455  7455 I Feature : [Lifetracker]Accessory: true
07-27 11:51:21.044  7455  7455 I Feature : [Lifetracker]Health device: true
07-27 11:51:21.044  7455  7455 I Feature : [Lifetracker]Extra Pedometer: false
07-27 11:51:21.044  7455  7455 I Feature : [Lifetracker]Blood glucose device: false
07-27 11:51:21.044  7455  7455 I Feature : [Lifetracker]Device Number: 3
07-27 11:51:21.048  7144  7144 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:51:21
07-27 11:51:21.052  7144  7144 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-27 11:51:21.052  7144  7144 D Weather.Utils: 2 : All the weather widget is gone.
07-27 11:51:21.052  6921  7482 W FormManager: Network not available. Please check & try again.
07-27 11:51:21.053  7144  7144 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-27 11:51:21.053  7144  7144 D WeatherAncestor: connectivity changed - connection : true
07-27 11:51:21.053  7144  7144 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1c195ac2
07-27 11:51:21.053  7144  7144 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-27 11:51:21.053  7144  7144 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-27 11:51:21.053  7144  7144 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-27 11:51:21.054  7144  7144 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-27 11:51:21.054  7144  7144 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:51:21
07-27 11:51:21.064  6803  6803 D BluetoothPermissionRequest: onReceive
,07-27 11:51:21.067  6921  7485 V FormManager: Network unavailable.
07-27 11:51:21.070  6803  6803 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-27 11:51:21.075  1037  1574 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
07-27 11:51:21.077  6921  7485 V FormManager: Network unavailable.
07-27 11:51:21.079  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,07-27 11:51:21.082  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-27 11:51:21.083  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-27 11:51:21.083  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-27 11:51:21.083  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-27 11:51:21.083  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-27 11:51:21.083  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-27 11:51:21.083  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-27 11:51:21.083  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-27 11:51:21.083  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-27 11:51:21.083  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-27 11:51:21.083  6952  6952 I BluetoothA2dpServiceJni: classInitNative
07-27 11:51:21.083  6952  6952 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-27 11:51:21.083  6952  6952 D A2dpStateMachine: make
07-27 11:51:21.085  6952  6952 I bluedroid-qcom: get_profile_interface a2dp
07-27 11:51:21.085  6952  7487 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-27 11:51:21.086  6426  6426 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-27 11:51:21.087  6426  6831 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-27 11:51:21.088  6952  6952 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
07-27 11:51:21.088  6952  6952 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-27 11:51:21.089  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c195ac2
07-27 11:51:21.090  6952  7486 D A2dpStateMachine: Enter Disconnected: -2
,07-27 11:51:21.090  6952  6952 D HeadsetStateMachine: Proxy object connected
07-27 11:51:21.091  6952  6952 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
07-27 11:51:21.091  6952  6952 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
07-27 11:51:21.092  6952  6952 I BluetoothHidServiceJni: classInitNative: succeeds
07-27 11:51:21.094  6952  6952 D HidService: Received start request. Starting profile...
07-27 11:51:21.094  6952  6952 I bluedroid-qcom: get_profile_interface hidhost
07-27 11:51:21.095  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c195ac2
07-27 11:51:21.095  6952  6952 I BluetoothHealthServiceJni: classInitNative: succeeds
07-27 11:51:21.097  6952  6952 D HealthService: Received start request. Starting profile...
,07-27 11:51:21.098  2194  2194 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE,
07-27 11:51:21.100  6952  6952 I bluedroid-qcom: get_profile_interface health
07-27 11:51:21.100  6952  6952 I LGBluetoothHealthServiceJni: classInitNative: succeeds
07-27 11:51:21.100  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c195ac2
07-27 11:51:21.102  6952  6952 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 11:51:21.103  6952  6952 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-27 11:51:21.104  6952  6952 D PanService: Received start request. Starting profile...
07-27 11:51:21.104  6952  6952 D BluetoothPanServiceJni: initializeNative(L110): pan
07-27 11:51:21.104  6952  6952 I bluedroid-qcom: get_profile_interface pan
07-27 11:51:21.108  6952  6952 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
07-27 11:51:21.108  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c195ac2
07-27 11:51:21.108  6952  7454 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 11:51:21.109  6952  7454 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-27 11:51:21.109  6952  7454 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-27 11:51:21.109  6952  6952 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
07-27 11:51:21.110  7016  7016 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-27 11:51:21.110  7016  7016 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:21.110  7016  7016 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-27 11:51:21.110  7016  7016 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-27 11:51:21.112  7016  7016 I AppUp4:CustModeStarterReceiver: onReceive
,07-27 11:51:21.112  6952  6952 D BtGatt.DebugUtils: handleDebugAction() action=null
07-27 11:51:21.112  6952  6952 D BtGatt.GattService: Received start request. Starting profile...
07-27 11:51:21.113  6952  6952 D BtGatt.GattService: start()
07-27 11:51:21.113  6952  6952 I bluedroid-qcom: get_profile_interface gatt
07-27 11:51:21.113  6952  6952 D BtGatt.AdvertiseManager: advertise manager created
,07-27 11:51:21.114  7016  7016 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@215a71a4
07-27 11:51:21.114  7016  7016 D AppUp4:CustFacade: isCustomizationCompleted : false
07-27 11:51:21.114  7016  7016 D AppUp4:CustFacade: isPhone : true
07-27 11:51:21.114  7016  7016 D AppUp4:CustModeStarterReceiver: begin check event
07-27 11:51:21.114  7016  7016 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-27 11:51:21.118  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:21.118  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 11:51:21.119  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 11:51:21.121  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c195ac2
07-27 11:51:21.121  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 11:51:21.122  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c195ac2
07-27 11:51:21.122  6952  6952 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
07-27 11:51:21.123  6952  6952 V BluetoothMapService: BluetoothMapBinder()
07-27 11:51:21.123  6952  6952 D BluetoothMapService: Received start request. Starting profile...
07-27 11:51:21.123  6952  6952 D BluetoothMapService: start()
07-27 11:51:21.125  4297  7494 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-27 11:51:21.126  4297  7495 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:21.126  4297  7495 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-27 11:51:21.127  7042  7042 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
07-27 11:51:21.127  6952  6952 D BluetoothMapEmailSettingsLoader: Found 0 applications
07-27 11:51:21.128  6952  6952 D BluetoothMapEmailAppObserver: createReceiver()
,07-27 11:51:21.133  6952  6952 D BluetoothMapEmailAppObserver: initObservers()
07-27 11:51:21.133  6952  6952 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
07-27 11:51:21.142  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c195ac2
,07-27 11:51:21.145  6952  6952 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 11:51:21.145  6921  7498 W FormManager: Network not available. Please check & try again.
07-27 11:51:21.146  6921  7499 V FormManager: Network unavailable.
07-27 11:51:21.146  7042  7497 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:21.147  6952  6952 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 11:51:21.148  3414  3414 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-27 11:51:21.148  3414  3414 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:21.148  3414  3414 I LgeMiscReceiver: networkInfo.isConnected() = false
07-27 11:51:21.149  6952  6952 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 11:51:21.150  7082  7082 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-27 11:51:21.150  7082  7082 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-27 11:51:21.150  6921  7499 V FormManager: Network unavailable.
07-27 11:51:21.152  6952  6952 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 11:51:21.152  6952  6952 V PanService: [BTUI] SIM Extra State :ABSENT
07-27 11:51:21.155  6952  6952 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,07-27 11:51:21.157  6952  6952 V BluetoothMapService: Handler(): got msg=1
07-27 11:51:21.157  7144  7144 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:51:21
07-27 11:51:21.157  6952  7431 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
07-27 11:51:21.157  6952  7431 I bluedroid-qcom: enable
07-27 11:51:21.157  6952  7431 I bt_hci_bdroid: init
07-27 11:51:21.158  6952  7501 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-27 11:51:21.159  6952  7501 I bt-btu  : btu_task pending for preload complete event
07-27 11:51:21.159  6952  7431 I bt_vendor: bt-vendor : init
07-27 11:51:21.159  7144  7144 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-27 11:51:21.159  6952  7431 I bt_vendor: bt-vendor : get_bt_soc_type
07-27 11:51:21.159  6952  7431 E bt_vendor: get_bt_soc_type: Failed to get soc type
07-27 11:51:21.159  7144  7144 D Weather.Utils: 2 : All the weather widget is gone.
07-27 11:51:21.159  6952  7431 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
07-27 11:51:21.159  6952  7431 D bt_userial_mct: userial_init
07-27 11:51:21.160  6952  7431 D bt_hci_bdroid: set_power 1
07-27 11:51:21.160  6952  7431 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
07-27 11:51:21.160  6952  7431 I bt_vendor: Starting hciattach daemon
07-27 11:51:21.160  6952  7431 I bt_vendor: try to set true
07-27 11:51:21.160  6952  6952 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:21.154  7504  7504 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:51:21.161  7144  7144 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-27 11:51:21.161  7144  7144 D WeatherAncestor: connectivity changed - connection : true
07-27 11:51:21.161  7144  7144 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1c195ac2
07-27 11:51:21.154  7504  7504 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:51:21.162  7144  7144 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-27 11:51:21.162  6952  6952 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 11:51:21.162  7144  7144 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-27 11:51:21.162  7144  7144 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-27 11:51:21.162  7144  7144 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-27 11:51:21.162  6952  6952 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-27 11:51:21.162  6952  6952 V BluetoothSapReceiver: SapReceiver onReceive 
07-27 11:51:21.162  7144  7144 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:51:21
07-27 11:51:21.162  6952  6952 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:21.162  6952  6952 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
07-27 11:51:21.179  7505  7505 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,07-27 11:51:21.227  7511  7511 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,07-27 11:51:21.237  7512  7512 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
07-27 11:51:21.262  7514  7514 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-27 11:51:21.272  7515  7515 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
07-27 11:51:21.285  7516  7516 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-27 11:51:21.293  7517  7517 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,07-27 11:51:21.310  7519  7519 I libmdmdetect: ESOC framework not supported
07-27 11:51:21.310  7519  7519 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,07-27 11:51:21.318  7519  7519 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,07-27 11:51:21.318  7519  7519 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
07-27 11:51:21.318  7519  7519 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
07-27 11:51:21.318  7519  7519 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
07-27 11:51:21.318  7519  7519 D bthci_qcomm_common: [BTUI]     LE: Class 2
07-27 11:51:21.318  7519  7519 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
07-27 11:51:21.318  7519  7519 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
07-27 11:51:21.350  7519  7520 E QC-QMI  : qmi_client [7519] 14: failed to locate client data
07-27 11:51:21.351   487   487 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
07-27 11:51:21.351   487   487 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,07-27 11:51:21.439  7521  7521 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,07-27 11:51:21.453  7525  7525 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-27 11:51:21.512  6952  7431 I bt_vendor: bluetooth satus is on
07-27 11:51:21.512  6952  7431 D bt_hci_bdroid: preload
,07-27 11:51:21.512  6952  7503 D bt_userial_mct: userial_open(port:0)
07-27 11:51:21.512  6952  7503 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
07-27 11:51:21.520  6952  7503 I bt_vendor: Done intiailizing UART
07-27 11:51:21.523  6952  7503 I bt_vendor: Done intiailizing UART
07-27 11:51:21.523  6952  7503 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
07-27 11:51:21.524  6952  7503 I bt_vendor: Bluetooth Firmware and transport layer are initialized
07-27 11:51:21.524  6952  7501 I bt-btu  : btu_task received preload complete event
07-27 11:51:21.525  6952  7527 D bt_userial_mct: Entering userial_read_thread()
07-27 11:51:21.525  6952  7501 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
07-27 11:51:21.526  6952  7501 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,07-27 11:51:21.534  6952  7501 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
07-27 11:51:21.534  1037  1111 W ProcessCpuTracker: Skipping unknown process pid 7446
07-27 11:51:21.535  1037  1111 W ProcessCpuTracker: Skipping unknown process pid 7447
07-27 11:51:21.536  1037  1111 W ProcessCpuTracker: Skipping unknown process pid 7451
07-27 11:51:21.536  1037  1111 W ProcessCpuTracker: Skipping unknown process pid 7453
07-27 11:51:21.538  1037  1111 W ProcessCpuTracker: Skipping unknown process pid 7522
07-27 11:51:21.540  6952  7501 I         : BTE_InitTraceLevels -- TRC_HCI
07-27 11:51:21.540  6952  7501 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-27 11:51:21.540  6952  7501 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,07-27 11:51:21.540  6952  7501 I         : BTE_InitTraceLevels -- TRC_AVDT
07-27 11:51:21.541  6952  7501 I         : BTE_InitTraceLevels -- TRC_AVRC
07-27 11:51:21.541  6952  7501 I         : BTE_InitTraceLevels -- TRC_A2D
07-27 11:51:21.541  6952  7501 I         : BTE_InitTraceLevels -- TRC_BNEP
07-27 11:51:21.541  6952  7501 I         : BTE_InitTraceLevels -- TRC_BTM
07-27 11:51:21.541  6952  7501 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,07-27 11:51:21.541  6952  7501 I         : BTE_InitTraceLevels -- TRC_GAP
07-27 11:51:21.541  6952  7501 I         : BTE_InitTraceLevels -- TRC_PAN
07-27 11:51:21.541  6952  7501 I         : BTE_InitTraceLevels -- TRC_SDP
07-27 11:51:21.541  6952  7501 I         : BTE_InitTraceLevels -- TRC_GATT
07-27 11:51:21.541  6952  7501 I         : BTE_InitTraceLevels -- TRC_SMP
07-27 11:51:21.541  6952  7501 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-27 11:51:21.541  6952  7501 I         : BTE_InitTraceLevels -- TRC_BTIF
07-27 11:51:21.639  6952  7501 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
07-27 11:51:21.639  6952  7501 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01e0061 
07-27 11:51:21.639  6952  7501 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01e0061 
,07-27 11:51:21.698  6952  7435 E bt-btif : Calling BTA_HhEnable
,07-27 11:51:21.698  6952  7435 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
07-27 11:51:21.699  6952  7435 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,07-27 11:51:21.704  6952  7501 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
07-27 11:51:21.704  6952  7501 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
07-27 11:51:21.704  6952  7501 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
07-27 11:51:21.704  6952  7501 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
07-27 11:51:21.704  6952  7501 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
07-27 11:51:21.712  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-27 11:51:21.713  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
07-27 11:51:21.713  6952  7435 D BluetoothAdapterProperties: Name is: G3
,07-27 11:51:21.719  6952  7435 D BluetoothAdapterProperties: Scan Mode:20
07-27 11:51:21.719  6952  7435 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 11:51:21.720  6952  7435 D bt_hci_bdroid: postload
07-27 11:51:21.720  6952  7503 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 11:51:21.721  6952  7501 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
07-27 11:51:21.723  6952  7501 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 11:51:21.723  6952  7501 W bt-smp  : Plain text(LSB ~ MSB) = 57 c5 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 11:51:21.723  6952  7501 W bt-smp  : Encrypted text(LSB ~ MSB) = 0b 96 65 58 94 34 c2 ff 64 ba ea 67 3d e7 ff 37 
07-27 11:51:21.723  6952  7501 W bt-btm  : Stopping oneshot timer
07-27 11:51:21.723  6952  7503 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 11:51:21.723  6952  7435 D bte_conf: Device ID record 1 : primary
07-27 11:51:21.723  6952  7435 D bte_conf:   vendorId            = 00c4
07-27 11:51:21.723  6952  7435 D bte_conf:   vendorIdSource      = 0001
07-27 11:51:21.723  6952  7435 D bte_conf:   product             = 13a1
07-27 11:51:21.723  6952  7435 D bte_conf:   version             = 1000
07-27 11:51:21.723  6952  7435 D bte_conf:   clientExecutableURL = 
07-27 11:51:21.723  6952  7435 D bte_conf:   serviceDescription  = 
07-27 11:51:21.723  6952  7435 D bte_conf:   documentationURL    = 
07-27 11:51:21.723  6952  7435 D bte_conf: bte_load_did_conf no section named DID2.
07-27 11:51:21.724  6952  7503 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 11:51:21.724  6952  7503 D bt_hci_bdroid: Used up Tx Cmd credits
,07-27 11:51:21.725  6952  7503 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 11:51:21.727  6952  7527 E bt_mct  : hci lib postload completed
07-27 11:51:21.724  7532  7532 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:51:21.727  6952  7431 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-27 11:51:21.728  6952  7431 D BluetoothAdapterProperties: ScanMode =  20
07-27 11:51:21.728  6952  7431 D BluetoothAdapterProperties: State =  11
07-27 11:51:21.728  6952  7431 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
07-27 11:51:21.728  6952  7431 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
07-27 11:51:21.724  7532  7532 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:51:21.728  6952  7431 D BluetoothAdapterProperties: Setting state to 12
07-27 11:51:21.728  6952  7431 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-27 11:51:21.729  1037  1120 D BluetoothManagerService: Message: 60
07-27 11:51:21.729  1037  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
07-27 11:51:21.729  1037  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
07-27 11:51:21.730  6952  7431 I BluetoothAdapterState: Entering On State
07-27 11:51:21.731  6952  7435 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-27 11:51:21.732  6952  7435 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-27 11:51:21.750  6952  7431 D LGBluetoothServiceAdapter: [BTUI] OnState
07-27 11:51:21.750  6952  7431 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
07-27 11:51:21.750  6952  7431 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,07-27 11:51:21.753  6952  7431 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-27 11:51:21.754  6803  6821 D BluetoothMap: onBluetoothStateChange: up=true
07-27 11:51:21.755  6952  7435 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 11:51:21.755  6952  7435 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
07-27 11:51:21.757  6952  7501 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 11:51:21.757  6952  7501 W bt-smp  : Plain text(LSB ~ MSB) = a7 72 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 11:51:21.757  6952  7501 W bt-smp  : Encrypted text(LSB ~ MSB) = b7 fc 16 95 71 7c bb 29 cb 32 7a 09 ef ee 7d 78 
07-27 11:51:21.757  6952  7501 W bt-btm  : Stopping oneshot timer
07-27 11:51:21.763  1837  3991 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 11:51:21.765  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:21.765  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:21.765  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:21.765  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:51:21.765  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:21.765  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:21.765  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:21.765  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:51:21.769  6735  6735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:51:21.772  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:21.772  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:21.772  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:21.772  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:51:21.772  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:21.772  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:21.772  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:21.772  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:51:21.773  6952  7501 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 11:51:21.773  6952  7501 W bt-smp  : Plain text(LSB ~ MSB) = e7 9f 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 11:51:21.773  6952  7501 W bt-smp  : Encrypted text(LSB ~ MSB) = 5b 33 1e a3 14 81 f8 ba 8c 1c db ac fe 22 ee 65 
07-27 11:51:21.773  6952  7501 W bt-btm  : Stopping oneshot timer
07-27 11:51:21.777  6735  6735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:51:21.779  6952  7431 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
07-27 11:51:21.781  1837  1837 D BluetoothHeadset: Proxy object connected
07-27 11:51:21.782  6952  7501 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 11:51:21.782  6952  7501 W bt-smp  : Plain text(LSB ~ MSB) = e7 4e 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 11:51:21.782  6952  7501 W bt-smp  : Encrypted text(LSB ~ MSB) = f0 19 a0 ae 63 cd ff 37 87 10 ed 78 17 e2 46 04 
07-27 11:51:21.782  6952  7501 W bt-btm  : Stopping oneshot timer
07-27 11:51:21.782  6803  6821 D BluetoothPan: onBluetoothStateChange on: true
07-27 11:51:21.783  6803  6821 D BluetoothPan: onBluetoothStateChange call bindService
07-27 11:51:21.797  6952  7501 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 11:51:21.797  6952  7501 W bt-smp  : Plain text(LSB ~ MSB) = d3 a6 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 11:51:21.797  6952  7501 W bt-smp  : Encrypted text(LSB ~ MSB) = 87 5b 90 d6 c7 67 4f fc 75 e8 98 fe 8b 9e 1a 28 
07-27 11:51:21.797  6952  7501 W bt-btm  : Stopping oneshot timer
,07-27 11:51:21.801  1837  2507 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 11:51:21.803  1037  1120 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 11:51:21.803  1837  1837 D BluetoothHeadset: Proxy object connected
07-27 11:51:21.806  6803  7539 D BluetoothPbap: onBluetoothStateChange: up=true
07-27 11:51:21.810  6803  6803 D BluetoothMap: Proxy object connected
07-27 11:51:21.810  6803  6803 D MapProfile: Bluetooth service connected
07-27 11:51:21.811  6803  6803 D BluetoothMap: getConnectedDevices()
,07-27 11:51:21.812  6952  6967 V BluetoothMapService: getConnectedDevices()
07-27 11:51:21.813  1037  1037 D BluetoothA2dp: Proxy object connected
07-27 11:51:21.815  1037  1120 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 11:51:21.816  1037  1037 D BluetoothHeadset: Proxy object connected
07-27 11:51:21.816  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 11:51:21.819  6803  6821 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-27 11:51:21.820  1837  1837 D BluetoothHeadset: Proxy object connected
07-27 11:51:21.821  7538  7538 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
07-27 11:51:21.823  1037  1120 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
,07-27 11:51:21.824  1037  1120 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
07-27 11:51:21.825  6803  6803 D BluetoothPan: BluetoothPAN Proxy object connected
,07-27 11:51:21.825  6803  6803 D PanProfile: Bluetooth service connected
07-27 11:51:21.827  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-27 11:51:21.827  1037  1120 D BluetoothManagerService: Message: 40
07-27 11:51:21.827  1037  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
07-27 11:51:21.828  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:21.828  6803  6803 D BluetoothInputDevice: Proxy object connected
07-27 11:51:21.828  6803  6803 D HidProfile: Bluetooth service connected
07-27 11:51:21.828  1927  2132 D LGBluetoothAPIService: Message: 1
07-27 11:51:21.828  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-27 11:51:21.828  1927  2132 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
07-27 11:51:21.839  6735  6735 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,07-27 11:51:21.842  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:21.843  1927  2132 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
07-27 11:51:21.843  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:21.844  6952  6952 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:21.844  6952  6952 D BluetoothMapService: STATE_ON
07-27 11:51:21.845  6803  6803 D LocalBluetoothProfileManager: Adding local A2DP profile
07-27 11:51:21.846  6952  6952 D LGBluetoothAPIServer: [BTUI] onCreate()
07-27 11:51:21.847  6952  6952 D LGBluetoothAPIServer: [BTUI] onBind()
07-27 11:51:21.848  1037  1120 D BluetoothManagerService: Message: 30
07-27 11:51:21.848  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
07-27 11:51:21.848  1927  2132 D LGBluetoothAPIService: Message: 100
07-27 11:51:21.848  1927  2132 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
07-27 11:51:21.850  6803  6803 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-27 11:51:21.852  1037  1120 D BluetoothManagerService: Message: 30
,07-27 11:51:21.857  6803  6803 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
07-27 11:51:21.859  6803  6803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-27 11:51:21.861  6803  6803 D BluetoothA2dp: Proxy object connected
07-27 11:51:21.861  6803  6803 D A2dpProfile: Bluetooth service connected
07-27 11:51:21.864  6803  6803 D BluetoothHeadset: Proxy object connected
07-27 11:51:21.865  6803  6803 D HeadsetProfile: Bluetooth service connected
07-27 11:51:21.867  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c195ac2
07-27 11:51:21.868  6952  6952 V BluetoothPbapService: Pbap Service onCreate
07-27 11:51:21.868  6952  6952 V BluetoothPbapService: Starting PBAP service
,07-27 11:51:21.870  6952  6952 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
07-27 11:51:21.870  6952  6952 V BluetoothPbapService: Pbap Service onBind
07-27 11:51:21.871  6803  6803 D DockEventReceiver: finishStartingService: stopping service
07-27 11:51:21.871  6952  6952 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:21.871  6952  6952 V BluetoothPbapService: state: 12
07-27 11:51:21.871  6952  6952 V BluetoothMapService: Handler(): got msg=1
07-27 11:51:21.872  7180  7216 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
07-27 11:51:21.872  6952  6952 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
07-27 11:51:21.872  6952  6952 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-27 11:51:21.872  6803  6803 D BluetoothPbap: Proxy object connected
07-27 11:51:21.873  6952  6952 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:21.873  6952  6952 V BluetoothPbapReceiver: ***********state = 12
07-27 11:51:21.873  6803  6803 D PbapServerProfile: Bluetooth service connected
07-27 11:51:21.874  6952  7552 D BluetoothMapMasInstance: MAS initSocket()
07-27 11:51:21.874  6952  7552 D BluetoothMapMasInstance:   masId = 00
07-27 11:51:21.874  6952  7552 D BluetoothMapMasInstance:   msgTypes = 0e
07-27 11:51:21.874  6952  7552 D BluetoothMapMasInstance:   masName = SMS/MMS
07-27 11:51:21.874  6952  7552 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
07-27 11:51:21.874  6952  6952 V BluetoothPbapService: Handler(): got msg=1
07-27 11:51:21.875  6952  6952 V BluetoothPbapService: Pbap Service startRfcommSocketListener
07-27 11:51:21.875  1037  1641 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:21.877  6952  7553 V BluetoothPbapService: Pbap Service initSocket
07-27 11:51:21.877  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-27 11:51:21.877  1037  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:21.877  2194  2194 D c       : Getting all permits...
07-27 11:51:21.877  2194  2194 D a       : Opening database...
07-27 11:51:21.878  6952  7552 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 11:51:21.879  6952  7553 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 11:51:21.881  2194  2194 D a       : Opening database auth.proximity.permit_store...
07-27 11:51:21.882  6952  7435 D BluetoothAdapterProperties: Scan Mode:21
07-27 11:51:21.882  6952  7553 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
07-27 11:51:21.882  2194  2194 D a       : Closing database...
07-27 11:51:21.882  6952  7553 V BluetoothPbapService: Succeed to create listening socket 
07-27 11:51:21.882  6952  7553 V BluetoothPbapService: Accepting socket connection...
07-27 11:51:21.882  6952  7435 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
07-27 11:51:21.883  6952  7552 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
07-27 11:51:21.883  6952  7552 V BluetoothMapMasInstance: Succeed to create listening socket 
07-27 11:51:21.883  6952  7552 D BluetoothMapMasInstance: Accepting socket connection...
07-27 11:51:21.883  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:21.885  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:21.885  6952  7435 D BluetoothAdapterProperties: Scan Mode:21
07-27 11:51:21.885  6952  7435 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
07-27 11:51:21.892  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:21.893  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:21.899  6803  6803 D BluetoothPermissionRequest: onReceive
07-27 11:51:21.900  6803  6803 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-27 11:51:21.902  6803  6803 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-27 11:51:21.905  6952  6952 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
07-27 11:51:21.906  6952  6952 I LGBluetoothOppAdapter: [BTUI] startOppService()
,07-27 11:51:21.911  6952  6952 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
07-27 11:51:21.925  6952  6952 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-27 11:51:21.925  6952  6952 V BtOppService: onCreate
,07-27 11:51:21.929  6952  6952 V BluetoothOppNotification: send message
07-27 11:51:21.932  6952  6952 V BtOppService: Starting RfcommListener
07-27 11:51:21.940  6952  6952 D BluetoothOppPreference: Dumping Names:  
07-27 11:51:21.940  6952  6952 D BluetoothOppPreference: {}
07-27 11:51:21.940  6952  6952 D BluetoothOppPreference: Dumping Channels:  
07-27 11:51:21.940  6952  6952 D BluetoothOppPreference: {}
,07-27 11:51:21.941  6952  6952 V BtOppService: onStartCommand
07-27 11:51:21.944  6952  6952 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:21.944  6952  6952 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-27 11:51:21.944  6952  7561 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-27 11:51:21.945  6952  6952 V BluetoothOppNotification: new notify threadi!
07-27 11:51:21.946  6952  7561 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-27 11:51:21.946  6952  6952 V BluetoothOppNotification: send delay message
07-27 11:51:21.946  6952  7558 V BtOppService: Deleted complete outbound shares, number =  0
07-27 11:51:21.947  6952  6952 V BtOppService: start RfcommListener
07-27 11:51:21.949  6952  6952 V BtOppService: RfcommListener started
07-27 11:51:21.949  6952  6952 V BtOppService: ContentObserver received notification
07-27 11:51:21.950  6952  7562 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-27 11:51:21.951  6952  7561 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3769d3ff on behalf of 
07-27 11:51:21.951  6952  7563 V BtOppRfcommListener: Starting RFCOMM listener....
07-27 11:51:21.953  6952  7558 V BtOppService: Deleted complete inbound failed shares, number = 0
07-27 11:51:21.954  6952  7558 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
07-27 11:51:21.956  1037  1872 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-27 11:51:21.956  6952  7558 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ce125cc on behalf of 
07-27 11:51:21.958  6952  7563 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 11:51:21.959  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c195ac2
07-27 11:51:21.959  6952  6952 V BluetoothFtpService: Ftp Service onCreate
07-27 11:51:21.959  6952  6952 I BluetoothFtpService: Ftp Service onCreate
07-27 11:51:21.959  6952  6952 V BluetoothFtpService: Ftp Service onStartCommand
07-27 11:51:21.960  6952  6952 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:21.960  6952  6952 V BluetoothFtpService: Starting Listening on sockets
07-27 11:51:21.960  6952  6952 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 11:51:21.960  6952  6952 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-27 11:51:21.960  6952  6952 V BluetoothSapReceiver: SapReceiver onReceive 
07-27 11:51:21.960  6952  6952 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:21.960  6952  6952 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
07-27 11:51:21.960  6952  6952 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-27 11:51:21.960  6952  7563 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
07-27 11:51:21.961  6952  7563 V BtOppRfcommListener: Started RFCOMM listener....
07-27 11:51:21.961  6952  7563 I BtOppRfcommListener: Accept thread started.
07-27 11:51:21.961  6952  7563 V BtOppRfcommListener: Accepting connection...
07-27 11:51:21.962  6952  6952 V BtOppService: ContentObserver received notification
07-27 11:51:21.962  6952  6952 V BluetoothFtpService: Handler(): got msg=1
07-27 11:51:21.963  6952  6952 V BluetoothFtpService: Ftp Service startRfcommSocketListener
07-27 11:51:21.963  6952  6952 V BluetoothFtpService: Ftp Service initSocket
07-27 11:51:21.965  6952  7561 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-27 11:51:21.965  6952  7561 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-27 11:51:21.966  1037  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:21.967  6952  6952 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 11:51:21.967  6952  7561 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10094f2a on behalf of 
07-27 11:51:21.967  6952  7562 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e91b11b on behalf of 
07-27 11:51:21.968  6952  6952 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
07-27 11:51:21.968  6952  6952 V BluetoothFtpService: Succeed to create listening socket on channel 20
07-27 11:51:21.969  6952  7561 V BluetoothOppNotification: update too frequent, put in queue
07-27 11:51:21.969  6952  7564 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
07-27 11:51:21.970  6952  7562 V BluetoothOppNotification: mUpdateCompleteNotification = true
,07-27 11:51:21.977  6952  7561 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-27 11:51:21.979  6952  7562 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-27 11:51:21.979  6952  7562 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2de0d2b8 on behalf of 
07-27 11:51:21.980  6952  7562 V BluetoothOppNotification: outbound: succ-0  fail-0
07-27 11:51:21.981  6952  7562 V BluetoothOppNotification: outbound notification was removed.
07-27 11:51:21.981  6952  7562 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-27 11:51:21.982  6952  7562 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b3df891 on behalf of 
07-27 11:51:21.982  6952  7562 V BluetoothOppNotification: inbound: succ-0  fail-0
07-27 11:51:21.984  6952  7562 V BluetoothOppNotification: inbound notification was removed.
,07-27 11:51:21.984  6952  7562 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-27 11:51:21.986  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c195ac2
07-27 11:51:21.986  6952  6952 V BluetoothSapService: Sap Service onCreate
07-27 11:51:21.989  6952  6952 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:21.989  6952  6952 V BluetoothSapService: state: 12
07-27 11:51:21.989  6952  6952 V BluetoothSapService: Starting SAP server process
07-27 11:51:21.989  6952  7562 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25388ccd on behalf of 
07-27 11:51:21.991  6952  6952 V BluetoothSapService: SAP Service startRfcommListenerThread
07-27 11:51:21.984  7565  7565 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:51:21.984  7565  7565 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:51:21.995  6952  7566 V BluetoothSapService: Sap Service initRfcommSocket
07-27 11:51:21.995  1037  2028 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:21.998  6952  7566 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 11:51:22.000  6952  7566 V BluetoothSapService: Succeed to create listening socket 
07-27 11:51:22.000  6952  7566 V BluetoothSapService: Accepting socket connection...
,07-27 11:51:22.003  7565  7565 V BT_SAP  : Event pipe created
,07-27 11:51:22.004  7565  7565 V BT_SAP  : create_server_socket qcom.sap.server
,07-27 11:51:22.004  7565  7565 V BT_SAP  : created socket fd 6
,07-27 11:51:22.638  1037  1522 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:22.639  1037  1522 D LGWifiP2pService: DefaultState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,07-27 11:51:22.692  1037  1523 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,07-27 11:51:22.693  1037  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,07-27 11:51:22.789  1037  1766 I ActivityManager: Killing 7354:com.lge.bnr/1000 (adj 15): empty #17
,07-27 11:51:22.828  1037  1944 W libprocessgroup: failed to open /acct/uid_1000/pid_7354/cgroup.procs: No such file or directory
,07-27 11:51:22.949  6952  6952 V BluetoothOppNotification: new notify threadi!
,07-27 11:51:22.949  6952  6952 V BluetoothOppNotification: send delay message
,07-27 11:51:22.962  6952  7576 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,07-27 11:51:22.970  6952  7576 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7889982 on behalf of 
,07-27 11:51:22.972  6952  7576 V BluetoothOppNotification: mUpdateCompleteNotification = true
,07-27 11:51:22.980  6952  7576 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-27 11:51:22.982  6952  7576 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@107b2893 on behalf of 
07-27 11:51:22.983  6952  7576 V BluetoothOppNotification: outbound: succ-0  fail-0
07-27 11:51:22.985  6952  7576 V BluetoothOppNotification: outbound notification was removed.
07-27 11:51:22.985  6952  7576 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-27 11:51:22.986  6952  7576 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f7f40d0 on behalf of 
07-27 11:51:22.987  6952  7576 V BluetoothOppNotification: inbound: succ-0  fail-0
07-27 11:51:22.988  6952  7576 V BluetoothOppNotification: inbound notification was removed.
07-27 11:51:22.988  6952  7576 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-27 11:51:22.989  6952  7576 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3fce28c9 on behalf of 
,07-27 11:51:23.109  1037  1766 I ActivityManager: Killing 6639:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,07-27 11:51:23.138  6878  6878 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
07-27 11:51:23.139  6878  6878 W System.err: android.os.DeadObjectException
07-27 11:51:23.139  6878  6878 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-27 11:51:23.139  6878  6878 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-27 11:51:23.139  6878  6878 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
07-27 11:51:23.139  6878  6878 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
07-27 11:51:23.139  6878  6878 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-27 11:51:23.139  6878  6878 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-27 11:51:23.139  6878  6878 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 11:51:23.139  6878  6878 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 11:51:23.139  6878  6878 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 11:51:23.139  6878  6878 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 11:51:23.139  6878  6878 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:51:23.139  6878  6878 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 11:51:23.139  6878  6878 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 11:51:23.139  6878  6878 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 11:51:23.140  6878  6878 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
07-27 11:51:23.140  6878  6878 W System.err: android.os.DeadObjectException
07-27 11:51:23.140  6878  6878 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-27 11:51:23.140  6878  6878 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-27 11:51:23.140  6878  6878 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
07-27 11:51:23.140  6878  6878 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
07-27 11:51:23.140  6878  6878 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
07-27 11:51:23.140  6878  6878 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
07-27 11:51:23.140  6878  6878 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 11:51:23.140  6878  6878 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 11:51:23.141  6878  6878 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 11:51:23.141  6878  6878 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 11:51:23.141  6878  6878 W System.err: ,	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:51:23.141  6878  6878 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 11:51:23.141  6878  6878 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 11:51:23.141  6878  6878 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 11:51:23.141  6878  6878 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,07-27 11:51:23.141  6878  6878 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,07-27 11:51:23.176  1037  1944 W libprocessgroup: failed to open /acct/uid_1000/pid_6639/cgroup.procs: No such file or directory
07-27 11:51:23.176  1037  1944 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,07-27 11:51:23.184  6878  6878 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
07-27 11:51:23.184  6878  6878 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-27 11:51:23.226  1037  1926 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7577 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-27 11:51:23.286  6878  6878 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
07-27 11:51:23.313  7577  7577 D UEI.SmartControl: Quickset Services start...
07-27 11:51:23.315  7577  7577 I UEI.SmartControl: Manufacture = LGE
07-27 11:51:23.316  7577  7577 D UEI.SmartControl: Id = LGNevo
07-27 11:51:23.317  7577  7577 D UEI.SmartControl: File observer start...
,07-27 11:51:23.321  7577  7577 E UEI.SmartControl: IR Port is disabled: false
07-27 11:51:23.321  7577  7577 D UEI.SmartControl: Starting file observer...
07-27 11:51:23.321  7577  7577 D UEI.SmartControl: Extracting JNI libs...
07-27 11:51:23.322  7577  7577 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-27 11:51:23.409  7577  7577 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-27 11:51:23.409  7577  7577 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-27 11:51:23.409  7577  7577 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,07-27 11:51:23.447  7577  7577 I UEI.SmartControl: --- Selecting new region: 6
,07-27 11:51:23.450  7577  7577 I UEI.SmartControl: Model = LG-D855
07-27 11:51:23.452  7577  7577 D UEI.SmartControl: QS Service created
07-27 11:51:23.469  7577  7577 I UEI.SmartControl: Service initServices...
,07-27 11:51:23.474  7577  7577 D UEI.SmartControl: QS start get config
07-27 11:51:23.514  7577  7577 D UEI.SmartControl: Loading JNI Libs...
,07-27 11:51:23.620  1037  2028 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:23.620  1037  2028 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@10128a29 mBinding = false
,07-27 11:51:23.643  1037  1120 D BluetoothManagerService: Message: 2
07-27 11:51:23.643  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 11:51:23.643  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-27 11:51:23.643  1037  1037 D Ulp_jni : JNI:system_update. Event-4
07-27 11:51:23.644  1037  1120 D BluetoothManagerService: Sending off request.
07-27 11:51:23.645  6952  6967 D LGBluetoothServiceAdapter: [BTUI] Precleanup
07-27 11:51:23.645  6952  7431 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
07-27 11:51:23.645  6952  7431 D BluetoothAdapterProperties: Setting state to 13
07-27 11:51:23.645  6952  7431 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-27 11:51:23.646  6952  7431 D BluetoothAdapterProperties: onBluetoothDisable()
07-27 11:51:23.646  6952  7431 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-27 11:51:23.647  6952  7435 D BluetoothAdapterProperties: Scan Mode:20
07-27 11:51:23.647  1037  1120 D BluetoothManagerService: Message: 60
07-27 11:51:23.647  1037  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
07-27 11:51:23.647  6952  7431 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-27 11:51:23.647  1037  1120 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
07-27 11:51:23.648  6952  7564 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 11:51:23.648  6952  7431 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-27 11:51:23.649  6952  7553 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 11:51:23.650  6952  7563 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 11:51:23.650  6952  7566 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 11:51:23.650  6952  7501 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
07-27 11:51:23.651  6952  7501 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
,07-27 11:51:23.657  6952  7552 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
07-27 11:51:23.657  6952  7552 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-27 11:51:23.657  6952  7552 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
07-27 11:51:23.657  6952  7552 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
07-27 11:51:23.657  6952  7552 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
07-27 11:51:23.657  6952  7552 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
07-27 11:51:23.657  6952  7552 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
07-27 11:51:23.657  6952  7552 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
07-27 11:51:23.659  6952  7501 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 11:51:23.659  6952  7501 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 11:51:23.659  6952  7501 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 11:51:23.659  6952  7501 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 11:51:23.659  6952  7501 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:51:23.659  6952  7501 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 11:51:23.659  6952  7501 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:51:23.659  6952  7501 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 11:51:23.659  6952  7501 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 11:51:23.659  6952  7501 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
07-27 11:51:23.659  6952  7501 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
07-27 11:51:23.659  6952  7501 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-27 11:51:23.660  6735  6735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:23.660  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:23.660  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:23.660  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:23.660  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:51:23.660  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:51:23.660  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:23.660  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:23.660  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:51:23.661  6735  6735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:23.661  6735  6735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:51:23.662  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:23.663  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-27 11:51:23.664  6952  6952 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07,-27 11:51:23.664  6952  6952 D BluetoothMapService: STATE_TURNING_OFF
07-27 11:51:23.664  6952  6952 V BtOppService: Receiver DISABLED_ACTION 
07-27 11:51:23.664  6952  6952 V BluetoothMapService: Handler(): got msg=4
07-27 11:51:23.664  6952  6952 D BluetoothMapService: MAP Service closeService in
07-27 11:51:23.665  6952  6952 D BluetoothMapMasInstance: MAP Service shutdown
07-27 11:51:23.665  6952  6952 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-27 11:51:23.665  6952  6952 V BluetoothMapService: MAP Service closeService out
07-27 11:51:23.665  6735  6735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:23.665  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:23.665  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:23.665  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:23.665  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:51:23.665  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:51:23.665  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:23.665  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:23.665  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:51:23.665  6952  6952 I BtOppRfcommListener: stopping Accept Thread
07-27 11:51:23.665  6952  6952 V BtOppRfcommListener: close mBtServerSocket
07-27 11:51:23.665  6735  6735 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:23.665  6952  6952 V BtOppRfcommListener: waiting for thread to terminate
07-27 11:51:23.665  6735  6735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:51:23.667  6952  7563 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-27 11:51:23.669  6952  6952 V BtOppRfcommListener: done waiting for thread to terminate
07-27 11:51:23.670  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:23.671  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:23.673  6803  6803 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
07-27 11:51:23.675  6952  6952 V BtOppService: onDestroy
07-27 11:51:23.676  6952  6952 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
07-27 11:51:23.676  6803  6803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-27 11:51:23.681  6952  6952 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-27 11:51:23.681  6952  6952 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:23.681  6952  6952 V BluetoothPbapReceiver: ***********state = 13
,07-27 11:51:23.684  6952  6952 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
07-27 11:51:23.685  6952  6952 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:23.685  6952  6952 V BluetoothPbapService: state: 13
07-27 11:51:23.685  6952  6952 V BluetoothPbapService: Pbap Service closeService in
07-27 11:51:23.688  6952  6952 V BluetoothPbapService: successfully stopped pbap service
07-27 11:51:23.688  6803  6803 D DockEventReceiver: finishStartingService: stopping service
07-27 11:51:23.688  6952  6952 V BluetoothPbapService: Pbap Service closeService out
07-27 11:51:23.688  6952  6952 V BluetoothPbapService: Pbap Service onDestroy
07-27 11:51:23.688  6952  6952 V BluetoothPbapService: Pbap Service closeService in
07-27 11:51:23.688  6952  6952 V BluetoothPbapService: Pbap Service closeService out
07-27 11:51:23.688  6952  6952 D LGBluetoothPbapAdapter: [BTUI] cleanup
07-27 11:51:23.688  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-27 11:51:23.689  6803  6803 D BluetoothPbap: Proxy object disconnected
07-27 11:51:23.689  6803  6803 D PbapServerProfile: Bluetooth service disconnected
07-27 11:51:23.702  6803  6803 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,07-27 11:51:23.709  6803  6803 D BluetoothPermissionRequest: onReceive
07-27 11:51:23.709  6803  6803 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-27 11:51:23.713  6803  6803 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,07-27 11:51:23.717  6952  6952 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
07-27 11:51:23.717  6952  6952 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
07-27 11:51:23.717  6952  6952 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
07-27 11:51:23.720  6952  6952 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:23.721  6952  6952 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-27 11:51:23.721  6952  6952 V BluetoothFtpService: Ftp Service onStartCommand
07-27 11:51:23.721  6952  6952 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:23.722  6952  6952 V BluetoothFtpService: Ftp Service closeService
07-27 11:51:23.722  6952  6952 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
07-27 11:51:23.722  6952  6952 V BluetoothFtpService: successfully stopped ftp service
07-27 11:51:23.723  6952  6952 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 11:51:23.723  6952  6952 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-27 11:51:23.723  6952  6952 V BluetoothSapReceiver: SapReceiver onReceive 
07-27 11:51:23.723  6952  6952 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:23.723  6952  6952 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
07-27 11:51:23.723  6952  6952 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-27 11:51:23.724  6952  6952 V BluetoothFtpService: Ftp Service onDestroy
07-27 11:51:23.724  6952  6952 V BluetoothFtpService: Ftp Service closeService
07-27 11:51:23.725  6952  6952 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:23.725  6952  6952 V BluetoothSapService: state: 13
07-27 11:51:23.725  6952  6952 V BluetoothSapService: Stopping SAP server process
07-27 11:51:23.727  6952  6952 V BluetoothSapService: Sap Service closeSapService in
07-27 11:51:23.727  6952  6952 V BluetoothSapService: Close listen Socket : 
07-27 11:51:23.727  6952  6952 V BluetoothSapService: Close rfcomm Socket : 
07-27 11:51:23.727  6952  6952 V BluetoothSapService: Close sapd  Socket : 
,07-27 11:51:23.729  6952  6952 V BluetoothSapService: Sap Service closeSapService out
07-27 11:51:23.729  6952  6952 V BluetoothSapService: Sap Service onDestroy
07-27 11:51:23.729  6952  6952 V BluetoothSapService: Sap Service closeSapService in
07-27 11:51:23.729  6952  6952 V BluetoothSapService: Close listen Socket : 
07-27 11:51:23.729  6952  6952 V BluetoothSapService: Close rfcomm Socket : 
07-27 11:51:23.729  6952  6952 V BluetoothSapService: Close sapd  Socket : 
07-27 11:51:23.732  6952  6952 V BluetoothSapService: Sap Service closeSapService out
07-27 11:51:23.888  7577  7577 I UEI.SmartControl: Supports setup maps: true
,07-27 11:51:23.894  7577  7577 D UEI.SmartControl: QS start statue = true Error code = 0
,07-27 11:51:23.894  7577  7577 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-27 11:51:23.894  7577  7577 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-27 11:51:23.894  7577  7577 I UEI.SmartControl: ### init IR Blaster...
07-27 11:51:23.900  7577  7577 D serial_port: Configuring serial port
07-27 11:51:23.906  7577  7577 E UEI.SmartControl: UEIBLaster setting for 616
07-27 11:51:23.906  7577  7577 I UEI.SmartControl: Setting serial record hearder size = 2
07-27 11:51:23.907  7577  7577 I UEI.SmartControl: configuring settings for MAXQ616
,07-27 11:51:23.907  7577  7577 I UEI.SmartControl: Get version...
,07-27 11:51:23.924  7577  7613 D UEI.SmartControl: serial port data available: 21
,07-27 11:51:23.957  7577  7577 D UEI.SmartControl: MAXQ616 A2-X4 software.
07-27 11:51:23.958  7577  7577 I UEI.SmartControl: IR Blaster version: 256702256704300002
07-27 11:51:23.958  7577  7577 I UEI.SmartControl: QS saving settings...
07-27 11:51:23.962  7577  7577 D UEI.SmartControl: IR Blaster version: 25672567
,07-27 11:51:23.980  7577  7613 D UEI.SmartControl: serial port data available: 4
,07-27 11:51:24.022  7577  7619 I UEI.SmartControl: Device manager: loading config....
07-27 11:51:24.023  7577  7619 D UEI.SmartControl: ----------- loading internal config...
,07-27 11:51:24.026  7577  7577 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,07-27 11:51:24.046  7577  7619 E UEI.SmartControl: Loading SETTINGS...
,07-27 11:51:24.060  7577  7619 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
07-27 11:51:24.079  7577  7618 I UEI.SmartControl: Notify AllClients services are ready: 0
,07-27 11:51:24.080  7577  7618 D UEI.SmartControl: -----service ready thread exits
07-27 11:51:24.196  1037  1061 I art     : Explicit concurrent mark sweep GC freed 95042(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.177ms total 163.790ms
07-27 11:51:24.197  7577  7577 E UEI.SmartControl: Services init done
07-27 11:51:24.197  7577  7577 D UEI.SmartControl: QS Service init finished
,07-27 11:51:24.203  7577  7577 D UEI.SmartControl: QS Service version name: 2.1.91
,07-27 11:51:24.203  7577  7577 D UEI.SmartControl: QS Service version code: 201091
07-27 11:51:24.205  7577  7577 D UEI.SmartControl: Service requested: Control
07-27 11:51:24.207  1037  1944 I ActivityManager: Killing 6878:com.lge.qremote/u0a112 (adj 15): empty #17
07-27 11:51:24.269  1037  1871 W libprocessgroup: failed to open /acct/uid_10112/pid_6878/cgroup.procs: No such file or directory
,07-27 11:51:24.269  7577  7577 D UEI.SmartControl: Internal service binding...
,07-27 11:51:24.564  6952  7435 D bt_hci_bdroid: cleanup
,07-27 11:51:24.572  6952  7503 I bt_lpm  : LPM is already off!!!
07-27 11:51:24.573  6952  7527 I bt_userial_mct: exiting userial_read_thread
07-27 11:51:24.573  6952  7527 D bt_userial_mct: Leaving userial_evt_read_thread()
07-27 11:51:24.574  6952  7501 W bt-btif : ag scb idx 1 not allocated
07-27 11:51:24.574  6952  7501 E bt-btif : BTA AG is already disabled, ignoring ...
07-27 11:51:24.575  6952  7501 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 11:51:24.575  6952  7501 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:51:24.575  6952  7501 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 11:51:24.575  6952  7501 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:51:24.575  6952  7501 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 11:51:24.575  6952  7501 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 11:51:24.575  6952  7501 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 11:51:24.575  6952  7501 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:51:24.575  6952  7501 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 11:51:24.575  6952  7501 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:51:24.575  6952  7501 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 11:51:24.575  6952  7501 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 11:51:24.575  6952  7501 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-27 11:51:24.575  6952  7501 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:51:24.575  6952  7501 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-27 11:51:24.575  6952  7501 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:51:24.576  6952  7501 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-27 11:51:24.576  6952  7501 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 11:51:24.576  6952  7501 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-27 11:51:24.580  6952  7435 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
07-27 11:51:24.580  6952  7503 I bt_vendor: hw_epilog_process
07-27 11:51:24.581  6952  7435 D bt_hci_bdroid: cleanup Finalizing cleanup
07-27 11:51:24.581  6952  7435 D bt_userial_mct: userial_close
07-27 11:51:24.581  6952  7435 E bt_userial_mct: pthread_join() FAILED result:3
07-27 11:51:24.581  6952  7435 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
07-27 11:51:24.588  6952  7435 D bt_hci_bdroid: set_power 0
07-27 11:51:24.588  6952  7435 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
07-27 11:51:24.588  6952  7435 I bt_vendor: bluetooth satus is on
07-27 11:51:24.588  6952  7435 I bt_vendor: bt-vendor : resetting BT status
07-27 11:51:24.588  6952  7435 I bt_vendor: Starting hciattach daemon
07-27 11:51:24.588  6952  7435 I bt_vendor: try to set false
,07-27 11:51:24.594  6952  7435 I bt_vendor: Starting hciattach daemon
07-27 11:51:24.594  6952  7435 I bt_vendor: try to set false
07-27 11:51:24.596  6952  7435 I bt_vendor: cleanup
07-27 11:51:24.598  6952  7501 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-27 11:51:24.598  6952  7435 I GKI_LINUX: GKI_exit_task 0 done
07-27 11:51:24.598  6952  7435 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
07-27 11:51:24.600  6952  7431 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-27 11:51:24.605  6952  6952 D HeadsetService: Received stop request...Stopping profile...
,07-27 11:51:24.608  6952  6952 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-27 11:51:24.608  6952  6952 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-27 11:51:24.608  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c195ac2
07-27 11:51:24.610  6952  7454 D HeadsetStateMachine: Exit Disconnected: -1
07-27 11:51:24.614  1837  1837 D BluetoothHeadset: Proxy object disconnected
07-27 11:51:24.614  1837  1837 D BluetoothHeadset: Proxy object disconnected
07-27 11:51:24.614  1837  1837 D BluetoothHeadset: Proxy object disconnected
07-27 11:51:24.615  1037  1037 D BluetoothHeadset: Proxy object disconnected
07-27 11:51:24.615  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-27 11:51:24.616  6952  6952 D A2dpService: Received stop request...Stopping profile...
,07-27 11:51:24.620  6952  7486 D A2dpStateMachine: Exit Disconnected: -1
07-27 11:51:24.624  6952  7431 D BluetoothAdapterState: Stopping profile services that were post enabled
07-27 11:51:24.625  6952  6952 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
07-27 11:51:24.627  6952  6952 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
07-27 11:51:24.627  6952  6952 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
07-27 11:51:24.627  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c195ac2
07-27 11:51:24.629  6952  6952 D HidService: Received stop request...Stopping profile...
07-27 11:51:24.629  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c195ac2
,07-27 11:51:24.632  6952  6952 D HeadsetStateMachine: Unbinding service...
07-27 11:51:24.634  1037  1037 D BluetoothA2dp: Proxy object disconnected
07-27 11:51:24.634  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-27 11:51:24.635  6952  6952 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-27 11:51:24.635  6952  6952 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-27 11:51:24.635  6952  6952 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-27 11:51:24.636  6952  6952 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-27 11:51:24.636  6952  6952 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-27 11:51:24.636  6952  6952 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-27 11:51:24.636  6952  6952 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-27 11:51:24.637  6952  6952 D HealthService: Received stop request...Stopping profile...
07-27 11:51:24.637  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c195ac2
07-27 11:51:24.639  6952  6952 D PanService: Received stop request...Stopping profile...
07-27 11:51:24.639  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c195ac2
07-27 11:51:24.641  6952  6952 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-27 11:51:24.644  6952  6952 D BtGatt.GattService: Received stop request...Stopping profile...
07-27 11:51:24.644  6952  6952 D BtGatt.GattService: stop()
07-27 11:51:24.644  6952  6952 D BtGatt.AdvertiseManager: advertise clients cleared
07-27 11:51:24.646  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c195ac2
07-27 11:51:24.649  6952  6952 D BluetoothMapService: Received stop request...Stopping profile...
07-27 11:51:24.649  6952  6952 D BluetoothMapService: stop()
07-27 11:51:24.649  6952  6952 D BluetoothMapEmailAppObserver: deinitObservers()
07-27 11:51:24.650  6952  6952 D BluetoothMapEmailAppObserver: removeReceiver()
07-27 11:51:24.650  6952  6952 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c195ac2
07-27 11:51:24.652  6952  6952 I BluetoothA2dpServiceJni: cleanupNative
07-27 11:51:24.652  6952  7487 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-27 11:51:24.652  6952  6952 I GKI_LINUX: GKI_exit_task 2 done
07-27 11:51:24.652  6952  6952 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-27 11:51:24.653  6952  6952 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-27 11:51:24.653  6952  6952 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-27 11:51:24.653  6952  6952 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,07-27 11:51:24.655  6952  6952 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-27 11:51:24.656  6952  6952 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-27 11:51:24.656  6952  6952 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-27 11:51:24.656  6952  6952 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-27 11:51:24.661  6952  6952 V BluetoothMapService: Handler(): got msg=4
07-27 11:51:24.661  6952  6952 D BluetoothMapService: MAP Service closeService in
07-27 11:51:24.661  6952  6952 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-27 11:51:24.661  6952  6952 V BluetoothMapService: MAP Service closeService out
07-27 11:51:24.662  6952  7431 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
07-27 11:51:24.662  6952  7431 D BluetoothAdapterProperties: Setting state to 10
07-27 11:51:24.662  6952  7431 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-27 11:51:24.662  6952  6952 D BluetoothMapService: cleanup()
07-27 11:51:24.662  6952  6952 D BluetoothMapService: MAP Service closeService in
07-27 11:51:24.663  6952  6952 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-27 11:51:24.663  6952  6952 V BluetoothMapService: MAP Service closeService out
07-27 11:51:24.664  1037  1120 D BluetoothManagerService: Message: 60
07-27 11:51:24.664  1037  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
07-27 11:51:24.664  1037  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
,07-27 11:51:24.668  6952  7431 I BluetoothAdapterState: Entering OffState
07-27 11:51:24.669  6803  7539 D BluetoothA2dp: onBluetoothStateChange: up=false
07-27 11:51:24.670  6803  6821 D BluetoothMap: onBluetoothStateChange: up=false
07-27 11:51:24.671  1837  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 11:51:24.671  6803  7539 D BluetoothPan: onBluetoothStateChange on: false
07-27 11:51:24.672  6803  6821 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 11:51:24.672  1837  1853 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 11:51:24.673  1037  1120 D BluetoothA2dp: onBluetoothStateChange: up=false
07-27 11:51:24.673  6803  7539 D BluetoothPbap: onBluetoothStateChange: up=false
07-27 11:51:24.674  1037  1120 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 11:51:24.674  1837  2507 D BluetoothHeadset: onBluetoothStateChange: up=false
07-27 11:51:24.674  6803  6821 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-27 11:51:24.675  1037  1120 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
07-27 11:51:24.675  1037  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
07-27 11:51:24.677  1037  1120 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
07-27 11:51:24.678  1037  1120 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
07-27 11:51:24.678  1037  1120 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@10128a29 mBinding = false
,07-27 11:51:24.680  1037  1120 D BluetoothManagerService: Sending unbind request.
07-27 11:51:24.686  6952  7435 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
07-27 11:51:24.686  6952  6952 I GKI_LINUX: GKI_exit_task 1 done
07-27 11:51:24.686  6952  6952 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
07-27 11:51:24.687  6952  6952 I BluetoothServiceJni: cleanupNative: return from cleanup
07-27 11:51:24.687  6952  6952 I art     : --- WEIRD: removing null entry 248
07-27 11:51:24.687  6952  6952 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
07-27 11:51:24.687  6952  6952 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
07-27 11:51:24.688  6952  6952 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
07-27 11:51:24.689  1037  1120 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,07-27 11:51:24.693  6952  6952 I art     : System.exit called, status: 0
07-27 11:51:24.693  6952  6952 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-27 11:51:24.713   336  1371 V AudioFlinger: 6952 died, releasing its sessions
07-27 11:51:24.713   336  1371 V AudioFlinger:  pid 1837 @ 0
07-27 11:51:24.713   336  1371 V AudioFlinger:  pid 3414 @ 1
07-27 11:51:24.713   336  1371 V AudioFlinger:  pid 3414 @ 2
,07-27 11:51:24.716  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
07-27 11:51:24.716  1927  2132 D LGBluetoothAPIService: Message: 101
07-27 11:51:24.716  1927  2132 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
07-27 11:51:24.717  1927  2132 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
07-27 11:51:24.717  1927  2132 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
07-27 11:51:24.719  6803  6803 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
07-27 11:51:24.767  1037  1061 I ActivityManager: Process com.android.bluetooth (pid 6952) has died
07-27 11:51:24.768  1037  1061 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
07-27 11:51:24.768  1037  1061 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
,07-27 11:51:24.777  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-27 11:51:24.781  6803  6803 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
07-27 11:51:24.781  6803  6803 D LGBluetoothEventManager: [BTUI] clear device connection state
07-27 11:51:24.783  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:24.784  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:24.784  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:24.785  1927  2132 D LGBluetoothAPIService: Message: 2
07-27 11:51:24.785  1927  2132 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
07-27 11:51:24.786  6803  6803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-27 11:51:24.787  1587  1587 D BluetoothAdapter: 829040965: getState() :  mService = null. Returning STATE_OFF
07-27 11:51:24.787  1587  1587 D BluetoothAdapter: 829040965: getState() :  mService = null. Returning STATE_OFF
07-27 11:51:24.850  1037  1997 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7646 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
07-27 11:51:24.853  6803  6803 D DockEventReceiver: finishStartingService: stopping service
,07-27 11:51:24.947  7646  7646 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,07-27 11:51:24.947  7646  7646 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 11:51:24.948  7646  7646 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
07-27 11:51:24.949  7646  7646 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-27 11:51:24.975  7646  7646 D BluetoothAdapterApp: Loading JNI Library
,07-27 11:51:25.010  7646  7646 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@a40286a Instance Count = 1
,07-27 11:51:25.016  7646  7646 D BluetoothAdapterApp: onCreate
,07-27 11:51:25.040  7646  7646 D ProfileConfigQcom: [BTUI] HeadsetService is supported
07-27 11:51:25.040  7646  7646 D ProfileConfigQcom: Adding HeadsetService
07-27 11:51:25.041  7646  7646 D ProfileConfigQcom: [BTUI] A2dpService is supported
07-27 11:51:25.041  7646  7646 D ProfileConfigQcom: Adding A2dpService
07-27 11:51:25.041  7646  7646 D ProfileConfigQcom: [BTUI] HidService is supported
07-27 11:51:25.041  7646  7646 D ProfileConfigQcom: Adding HidService
07-27 11:51:25.041  7646  7646 D ProfileConfigQcom: [BTUI] HealthService is supported
07-27 11:51:25.041  7646  7646 D ProfileConfigQcom: Adding HealthService
07-27 11:51:25.042  7646  7646 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
07-27 11:51:25.043  7646  7646 D ProfileConfigQcom: [BTUI] PanService is supported
07-27 11:51:25.043  7646  7646 D ProfileConfigQcom: Adding PanService
07-27 11:51:25.044  7646  7646 D ProfileConfigQcom: [BTUI] GattService is supported
07-27 11:51:25.044  7646  7646 D ProfileConfigQcom: Adding GattService
07-27 11:51:25.044  7646  7646 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
07-27 11:51:25.044  7646  7646 D ProfileConfigQcom: Adding BluetoothMapService
,07-27 11:51:25.045  7646  7646 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
,07-27 11:51:25.046  7646  7646 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-27 11:51:25.047  7646  7646 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:51:25.047  7646  7646 V BluetoothPbapReceiver: ***********state = 10
07-27 11:51:25.049  7646  7646 V LGMDMManagerInternal: Create singleton instance
07-27 11:51:25.148  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-27 11:51:25.156  7646  7646 D LGBluetoothAPIServer: [BTUI] onCreate()
,07-27 11:51:25.161  7646  7646 D LGBluetoothAPIServer: [BTUI] onBind()
07-27 11:51:25.165  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
07-27 11:51:25.165  1927  2132 D LGBluetoothAPIService: Message: 100
07-27 11:51:25.165  1927  2132 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
07-27 11:51:25.173  6803  6803 D BluetoothPermissionRequest: onReceive
,07-27 11:51:25.176  6803  6803 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-27 11:51:25.179  6803  6803 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-27 11:51:25.179  6803  6803 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
07-27 11:51:25.182  6803  6803 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-27 11:51:25.190  7646  7646 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,07-27 11:51:25.199  7646  7646 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:25.202  7646  7646 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 11:51:25.203  7646  7646 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-27 11:51:25.203  7646  7646 V BluetoothSapReceiver: SapReceiver onReceive 
07-27 11:51:25.204  7646  7646 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:25.204  7646  7646 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,07-27 11:51:25.210  6900  6900 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,07-27 11:51:26.645  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:26.646  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 11:51:26.805  1587  1587 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,07-27 11:51:26.828  1037  1424 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-27 11:51:26.899  1037  1111 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7674 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-27 11:51:26.908  1587  1587 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
07-27 11:51:26.909  1587  1587 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
07-27 11:51:26.926  1037  1037 D administrator: Handling package changes for user 0
,07-27 11:51:26.942  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,07-27 11:51:26.972  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-27 11:51:26.994  7674  7674 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-27 11:51:27.057  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
07-27 11:51:27.057  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,07-27 11:51:27.075  7674  7674 D LgDataFeature: LgDataFeature() Constructor: none
07-27 11:51:27.075  7674  7674 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 11:51:27.120  1037  1109 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 11:51:27.127  1037  1109 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
07-27 11:51:27.152  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,07-27 11:51:27.154  2455  2455 V GmsNetworkLocationProvi: DISABLE
07-27 11:51:27.189  1037  1109 D LocationProviderProxy: applying state to connected service
,07-27 11:51:27.191  2455  2455 E GCoreFlp: Bound FusedProviderService with LocationManager
07-27 11:51:27.211  7674  7719 I Babel   : MmsConfig: mnc/mcc: 0/0
07-27 11:51:27.212  7674  7719 I Babel   : MmsConfig.loadMmsSettings
,07-27 11:51:27.218  7674  7719 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
07-27 11:51:27.218  7674  7719 I Babel   : MmsConfig.loadFromDatabase
,07-27 11:51:27.234  7674  7719 E Babel   : canonicalizeMccMnc: invalid mccmnc 
07-27 11:51:27.235  7674  7719 I Babel   : MmsConfig.loadFromResources
07-27 11:51:27.237  7674  7719 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
07-27 11:51:27.237  7674  7719 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,07-27 11:51:27.252  7674  7674 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:27.265  7674  7717 W AudioCapabilities: Unsupported mime audio/evrc
,07-27 11:51:27.268  7674  7717 W AudioCapabilities: Unsupported mime audio/qcelp
,07-27 11:51:27.274  7674  7717 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-27 11:51:27.280  1802  7722 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
07-27 11:51:27.280  1802  7722 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,07-27 11:51:27.284  7016  7016 I AppUp4:CustModeStarterReceiver: onReceive
07-27 11:51:27.289  7016  7016 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@215a71a4
07-27 11:51:27.289  7016  7016 D AppUp4:CustFacade: isCustomizationCompleted : false
07-27 11:51:27.289  7016  7016 D AppUp4:CustFacade: isPhone : true
07-27 11:51:27.290  7016  7016 D AppUp4:CustModeStarterReceiver: begin check event
07-27 11:51:27.290  7016  7016 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
07-27 11:51:27.292  1802  4754 I Icing   : updateResources: need to parse e{com.google.android.gms}
,07-27 11:51:27.308  7674  7717 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,07-27 11:51:27.310  7674  7717 W AudioCapabilities: Unsupported mime audio/qcelp
07-27 11:51:27.324  7674  7717 W AudioCapabilities: Unsupported mime audio/evrc
,07-27 11:51:27.335  1037  1574 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7725 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
07-27 11:51:27.341  1037  1574 I ActivityManager: Killing 6833:com.lge.sync/1000 (adj 15): empty #17
,07-27 11:51:27.355  7674  7717 W VideoCapabilities: Unsupported mime video/x-ms-wmv
07-27 11:51:27.357  7674  7717 W VideoCapabilities: Unsupported mime video/divx
,07-27 11:51:27.359  7674  7717 W VideoCapabilities: Unsupported mime video/divx311
07-27 11:51:27.362  1037  1528 D WifiService: Client connection lost with reason: 4
07-27 11:51:27.362  7674  7717 W VideoCapabilities: Unsupported mime video/divx4
07-27 11:51:27.368  7674  7717 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,07-27 11:51:27.383  7674  7717 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-27 11:51:27.386  7674  7717 W AudioCapabilities: Unsupported mime audio/eac3
07-27 11:51:27.387  7674  7717 W AudioCapabilities: Unsupported mime audio/ac3
07-27 11:51:27.388  7674  7717 W AudioCapabilities: Unsupported mime audio/g726
07-27 11:51:27.389  7674  7717 W AudioCapabilities: Unsupported mime audio/wma-voice
07-27 11:51:27.390  7674  7717 W AudioCapabilities: Unsupported mime audio/x-ms-wma
07-27 11:51:27.390  7674  7717 W AudioCapabilities: Unsupported mime audio/adpcm
07-27 11:51:27.392  7674  7717 W VideoCapabilities: Unsupported mime video/theora
07-27 11:51:27.393  7674  7717 W VideoCapabilities: Unsupported mime video/mjpg
07-27 11:51:27.430  1037  1060 W libprocessgroup: failed to open /acct/uid_1000/pid_6833/cgroup.procs: No such file or directory
,07-27 11:51:27.472  7725  7725 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 11:51:27.473  7725  7725 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 11:51:27.473  7725  7725 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
07-27 11:51:27.475  7725  7725 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
07-27 11:51:27.475  7725  7725 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-27 11:51:27.545  7725  7725 I SystemConfig: BUILD Country: EU
07-27 11:51:27.545  7725  7725 I SystemConfig: BUILD Operator: OPEN
,07-27 11:51:27.592  1037  2028 I ActivityManager: Killing 7042:com.lge.email/u0a23 (adj 15): empty #17
,07-27 11:51:27.644  1037  1908 W libprocessgroup: failed to open /acct/uid_10023/pid_7042/cgroup.procs: No such file or directory
,07-27 11:51:27.648  7725  7743 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
07-27 11:51:27.649  7725  7743 I SystemConfig: existFile = false
07-27 11:51:27.649  7725  7743 I SystemConfig: canReadFile = false
07-27 11:51:27.649  7725  7743 I SystemConfig: systemFeature RCS result false
07-27 11:51:27.649  7725  7743 D SystemConfig: refreshRcsSupport() :false
07-27 11:51:27.689  1037  2028 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7748 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,07-27 11:51:27.741  7748  7748 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 11:51:27.742  7748  7748 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-27 11:51:27.742  7748  7748 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-27 11:51:27.743  7748  7748 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-27 11:51:27.837  7748  7748 I AppConfig: Total System Memory = 2995761152
,07-27 11:51:27.846  7748  7748 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
07-27 11:51:27.945  1037  1766 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7767 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 11:51:27.955  1037  1766 I ActivityManager: Killing 6921:com.lge.formmanager/u0a26 (adj 15): empty #17
07-27 11:51:27.989  1037  1641 W libprocessgroup: failed to open /acct/uid_10026/pid_6921/cgroup.procs: No such file or directory
,07-27 11:51:28.185  7767  7767 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,07-27 11:51:28.249  7767  7767 D LgDataFeature: LgDataFeature() Constructor: none
07-27 11:51:28.249  7767  7767 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 11:51:28.289  7767  7767 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,07-27 11:51:28.305  7767  7767 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-27 11:51:28.305  7767  7767 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-27 11:51:28.317  7767  7767 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
07-27 11:51:28.318  7767  7767 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,07-27 11:51:28.329  1037  1871 I ActivityManager: Killing 6426:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,07-27 11:51:28.471  1037  1060 W libprocessgroup: failed to open /acct/uid_1000/pid_6426/cgroup.procs: No such file or directory
,07-27 11:51:28.491  4585  7813 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-27 11:51:28.548  1037  1766 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7814 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,07-27 11:51:28.577   355   355 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 556us total 25.046ms
,07-27 11:51:28.599   355   355 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 444us total 20.156ms
,07-27 11:51:28.620   355   355 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 556us total 20.368ms
,07-27 11:51:28.624  3499  4473 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
07-27 11:51:28.625  3499  4473 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1b5c7788 on behalf of 7767
07-27 11:51:28.632  7767  7767 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
07-27 11:51:28.644  7767  7767 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,07-27 11:51:28.661  7814  7814 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,07-27 11:51:28.688  7814  7814 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,07-27 11:51:28.689  7814  7814 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
07-27 11:51:28.690  7814  7814 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
07-27 11:51:28.690  7814  7814 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
07-27 11:51:28.690  7814  7814 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
07-27 11:51:28.690  7814  7814 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
07-27 11:51:28.712  1037  1060 I ActivityManager: Killing 7082:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,07-27 11:51:28.730  1037  1574 W libprocessgroup: failed to open /acct/uid_10046/pid_7082/cgroup.procs: No such file or directory
,07-27 11:51:28.941  1037  1962 V SIM_STK : Menu title from STK is T-Mobile
,07-27 11:51:28.985  4585  7813 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 494 ms] updated apps [took 494 ms] 
,07-27 11:51:29.024  7577  7620 D UEI.SmartControl: Internal timer expired: 1
,07-27 11:51:29.024  7577  7620 D UEI.SmartControl: unbind internal service
,07-27 11:51:29.032  7577  7577 D UEI.SmartControl: Service.onUnbind: IControl
07-27 11:51:29.034  7577  7577 D UEI.SmartControl: Service.onDestroy
07-27 11:51:29.034  7577  7577 D UEI.SmartControl: Lock is in USE false
07-27 11:51:29.035  7577  7577 D UEI.SmartControl: unbind internal service
07-27 11:51:29.041  7577  7577 D serial_port: close(fd = 25)
,07-27 11:51:29.046  7577  7577 I UEI.SmartControl: Serial port is closed.
07-27 11:51:29.046  7577  7577 I UEI.SmartControl: Serial port is closed.
07-27 11:51:29.046  7577  7577 D UEI.SmartControl: Blaster closed
07-27 11:51:29.047  7577  7577 D UEI.SmartControl: Shut down QS...
07-27 11:51:29.047  7577  7577 D UEI.SmartControl: Stopping QS lib
07-27 11:51:29.048  7577  7577 D UEI.SmartControl: QS lib stop result = true
07-27 11:51:29.048  7577  7577 D UEI.SmartControl: Stopped QS lib
07-27 11:51:29.048  7577  7577 D UEI.SmartControl: Stopped file observer...
07-27 11:51:29.048  7577  7577 D UEI.SmartControl: QS shutdown complete
07-27 11:51:29.659  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:29.659  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2424483 added. We now have 6 listener(s)
07-27 11:51:29.659  6735  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 11:51:29.665  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:29.665  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27694600 added. We now have 7 listener(s)
07-27 11:51:29.665  6735  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:51:29.666  6735  6792 I System.out: IsBluetoothEnabled
07-27 11:51:29.667  1037  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:29.667  1037  1908 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
07-27 11:51:29.668  1037  1120 D BluetoothManagerService: Message: 2
07-27 11:51:29.680  6735  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:29.683  1037  2028 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:29.683  1037  2028 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,07-27 11:51:29.700  1037  1120 D BluetoothManagerService: Message: 1
07-27 11:51:29.700  1037  1120 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
07-27 11:51:29.703  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 11:51:29.703  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-27 11:51:29.703  1037  1037 D Ulp_jni : JNI:system_update. Event-4
07-27 11:51:29.740  1037  1120 D BluetoothManagerService: Message: 20
07-27 11:51:29.740  1037  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@341152cf:true
,07-27 11:51:29.744  7646  7646 D BluetoothAdapterState: make
07-27 11:51:29.748  7646  7646 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
07-27 11:51:29.749  7646  7646 I bluedroid-qcom: init
07-27 11:51:29.750  7646  7853 I BluetoothAdapterState: Entering OffState
07-27 11:51:29.750  7646  7646 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-27 11:51:29.750  7646  7646 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-27 11:51:29.750  7646  7646 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-27 11:51:29.750  7646  7646 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-27 11:51:29.751  7646  7646 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
07-27 11:51:29.752  7646  7646 I bluedroid-qcom: get_profile_interface socket
07-27 11:51:29.752  7646  7646 I bluedroid-qcom: get_profile_interface map_client
,07-27 11:51:29.757  7646  7857 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
07-27 11:51:29.754  7856  7856 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:51:29.761  7646  7857 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-27 11:51:29.754  7856  7856 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:51:29.770  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,07-27 11:51:29.774  1037  1120 D BluetoothManagerService: Message: 40
07-27 11:51:29.774  1037  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
07-27 11:51:29.782  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-27 11:51:29.783  7646  7662 I bluedroid-qcom: config_hci_snoop_log
07-27 11:51:29.783  7646  7857 D BluetoothAdapterProperties: Name is: G3
07-27 11:51:29.783  7856  7856 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
07-27 11:51:29.783  7856  7856 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
07-27 11:51:29.784  7856  7856 I LGFTMITEM: [GET_FTM][id=8], offset=16384
07-27 11:51:29.784  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
07-27 11:51:29.785  1037  1120 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
07-27 11:51:29.785  1037  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,07-27 11:51:29.786  7856  7856 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
07-27 11:51:29.790  7856  7856 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
07-27 11:51:29.790  7856  7856 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
07-27 11:51:29.798  7646  7853 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
07-27 11:51:29.798  7646  7853 D BluetoothAdapterProperties: Setting state to 11
07-27 11:51:29.799  7646  7853 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-27 11:51:29.799  1037  1120 D BluetoothManagerService: Message: 60
07-27 11:51:29.799  1037  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-27 11:51:29.800  1037  1120 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
07-27 11:51:29.800  7646  7853 I LGBluetoothServiceJni: classInitNative: succeeds
,07-27 11:51:29.804  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:29.806  6803  6803 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
07-27 11:51:29.806  7646  7853 D BluetoothBondStateMachine: make
07-27 11:51:29.807  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-27 11:51:29.810  7646  7646 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-27 11:51:29.810  7646  7646 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:29.810  7646  7646 V BluetoothPbapReceiver: ***********state = 11
07-27 11:51:29.811  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:29.815  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-27 11:51:29.815  7646  7874 I BluetoothBondStateMachine: StableState(): Entering Off State
07-27 11:51:29.816  7646  7853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247ef0d3
07-27 11:51:29.816  7646  7853 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
07-27 11:51:29.816  7646  7853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247ef0d3
07-27 11:51:29.816  7646  7853 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
,07-27 11:51:29.818  7646  7853 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
07-27 11:51:29.831  7646  7853 E BluetoothAdapterService: File transfer profiles supported!!
,07-27 11:51:29.833  6803  6803 D BluetoothPermissionRequest: onReceive
07-27 11:51:29.838  6803  6803 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-27 11:51:29.846  7646  7853 E BluetoothAdapterService: File transfer profiles supported!!
,07-27 11:51:29.850  7646  7646 D HeadsetService: Received start request. Starting profile...
07-27 11:51:29.850  7646  7646 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
07-27 11:51:29.851  7646  7646 D LGBluetoothHfpAdapter: Version 1.6
07-27 11:51:29.854  7646  7646 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-27 11:51:29.855  7646  7646 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-27 11:51:29.855  7646  7646 D HeadsetStateMachine: make
07-27 11:51:29.856  7646  7853 E BluetoothAdapterService: File transfer profiles supported!!
07-27 11:51:29.863  7646  7853 E BluetoothAdapterService: File transfer profiles supported!!
,07-27 11:51:29.869  7646  7853 E BluetoothAdapterService: File transfer profiles supported!!
07-27 11:51:29.875  7646  7853 E BluetoothAdapterService: File transfer profiles supported!!
07-27 11:51:29.881  7646  7853 E BluetoothAdapterService: File transfer profiles supported!!
,07-27 11:51:29.898  7646  7853 V LGMDMManager: Create singleton instance
,07-27 11:51:29.900  7646  7646 D LgDataFeature: LgDataFeature() Constructor: none
07-27 11:51:29.900  7646  7646 D LgDataFeature: LgDataFeature() Constructor Done, null
07-27 11:51:29.903  7646  7853 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,07-27 11:51:29.906  7646  7646 D HeadsetStateMachine: max_hf_connections = 1
07-27 11:51:29.906  7646  7646 I bluedroid-qcom: get_profile_interface handsfree
07-27 11:51:29.909  7646  7646 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
07-27 11:51:29.909   336  1371 V AudioPolicyService: registerClient() client 0xb558a260, uid 1002
07-27 11:51:29.910   336  1372 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
07-27 11:51:29.910   336  1372 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 11:51:29.910   336  1372 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 11:51:29.910  7646  7646 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-27 11:51:29.911   336  2146 V AudioFlinger: registerClient() client 0xb55814f0, pid 7646
07-27 11:51:29.911   336  1367 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 11:51:29.911   336  1367 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 11:51:29.912  7646  7646 V ToneGenerator: Create Track: 0xb4928080
07-27 11:51:29.912  7646  7646 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-27 11:51:29.912  7646  7646 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
07-27 11:51:29.912   336  1365 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 11:51:29.912  1587  2106 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 11:51:29.912  1587  2106 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 11:51:29.912   336  1365 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 11:51:29.912  7646  7663 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 11:51:29.912  7646  7663 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-27 11:51:29.912   336  2146 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-27 11:51:29.912  1037  1871 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 11:51:29.912  1037  1871 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 11:51:29.912   336  2146 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
07-27 11:51:29.912   336  2146 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 11:51:29.912  1837  3991 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 11:51:29.912   336  2146 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 11:51:29.912  1037  1871 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 11:51:29.912  1837  3991 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 11:51:29.912  1037  1871 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 11:51:29.912  7646  7646 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-27 11:51:29.912  3414  3430 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 11:51:29.912  3414  3430 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 11:51:29.913   336  1371 I AudioFlinger: isAudioPlaybackHookOn() false
07-27 11:51:29.913  7646  7663 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 11:51:29.913  1587  1607 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 11:51:29.913  7646  7663 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-27 11:51:29.913   336  2149 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-27 11:51:29.913  1587  1607 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 11:51:29.913   336  2149 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-27 11:5,1:29.913   336  2149 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 11:51:29.913   336  2149 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 11:51:29.913  1837  1852 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 11:51:29.913  7646  7646 V AudioSystem: getLatency() output 2, latency 50
07-27 11:51:29.913  1837  1852 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 11:51:29.913  7646  7646 V AudioSystem: getFrameCount() output 2, frameCount 960
07-27 11:51:29.913  7646  7646 V AudioTrack: createTrack_l() output 2 afLatency 50
07-27 11:51:29.913  3414  3429 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 11:51:29.913  3414  3429 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 11:51:29.914   336   336 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-27 11:51:29.914   336   336 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-27 11:51:29.914   336   336 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-27 11:51:29.914   336   336 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-27 11:51:29.914   336   336 V AudioFlinger: createTrack() lSessionId: 23
07-27 11:51:29.915  7646  7646 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-27 11:51:29.915   336   336 V AudioFlinger: acquiring 23 from 7646, for 7646
07-27 11:51:29.915   336   336 V AudioFlinger:  added new entry for 23
07-27 11:51:29.915  7646  7646 V ToneGenerator: ToneGenerator INIT OK, time: 317758
07-27 11:51:29.915  7646  7646 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247ef0d3
,07-27 11:51:29.917  7646  7646 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247ef0d3
07-27 11:51:29.919  7646  7876 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
07-27 11:51:29.919  7646  7876 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-27 11:51:29.919  7646  7876 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-27 11:51:29.919  7646  7876 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
07-27 11:51:29.920  7646  7646 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:29.922   336  1371 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7646
07-27 11:51:29.923   336  1371 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
07-27 11:51:29.923   336  1371 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-27 11:51:29.923   336  1371 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-27 11:51:29.923   336  1371 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-27 11:51:29.923   336  1371 V voice   : voice_set_parameters: exit with code(0)
,07-27 11:51:29.923   336  1371 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
07-27 11:51:29.923   336  1371 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-27 11:51:29.923   336  1371 V msm8974_platform: platform_set_parameters: exit with code(0)
07-27 11:51:29.923   336  1371 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-27 11:51:29.923   336  1371 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-27 11:51:29.923   336  1371 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-27 11:51:29.923  7646  7876 V ToneGenerator: ToneGenerator destructor
07-27 11:51:29.923  7646  7876 V ToneGenerator: stopTone
07-27 11:51:29.923  7646  7876 V ToneGenerator: Delete Track: 0xb4928080
07-27 11:51:29.924  7646  7646 D A2dpService: Received start request. Starting profile...
07-27 11:51:29.924   336  1372 V AudioPolicyService: AudioCommandThread() adding release output 2
07-27 11:51:29.924   336  1372 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-27 11:51:29.924   336  1372 V AudioFlinger: PlaybackThread::Track destructor
07-27 11:51:29.924   336  1372 V AudioFlinger: removeClient_l() pid 7646, calling pid 336
07-27 11:51:29.924   336  1275 V AudioPolicyService: AudioCommandThread() waking up
07-27 11:51:29.925   336  1275 V AudioPolicyService: AudioCommandThread() processing release output 2
07-27 11:51:29.925   336  1275 V AudioPolicyManager: releaseOutput() 2
07-27 11:51:29.925   336  1275 V AudioPolicyService: AudioCommandThread() going to sleep
07-27 11:51:29.925  7646  7646 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-27 11:51:29.925  7646  7876 V AudioTrack: ~AudioTrack, releasing session id from 7646 on behalf of 7646
07-27 11:51:29.925   336   336 V AudioFlinger: releasing 23 from 7646 for 7646
07-27 11:51:29.925   336   336 V AudioFlinger:  decremented refcount to 0
07-27 11:51:29.925   336   336 V AudioFlinger: purging stale effects
07-27 11:51:29.926  7646  7646 V Avrcp   : make
07-27 11:51:29.926  7646  7646 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-27 11:51:29.926  7646  7646 I bluedroid-qcom: get_profile_interface avrcp
07-27 11:51:29.938  7646  7646 V AudioManager: registerRemoteController: size of Media player list: 0
,07-27 11:51:29.941  7646  7646 E AudioManager: No RCC entry present to update
07-27 11:51:29.941  7646  7646 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-27 11:51:29.945  7646  7646 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
07-27 11:51:29.946  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
07-27 11:51:29.946  7646  7646 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
07-27 11:51:29.953  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,07-27 11:51:30.056  1037  1890 V SIM_STK : Menu title from STK is T-Mobile
,07-27 11:51:30.056  1037  1890 V SIM_STK : Menu title from STK is T-Mobile
,07-27 11:51:30.169  1037  1908 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,07-27 11:51:30.180  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
07-27 11:51:30.188  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,07-27 11:51:30.189  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-27 11:51:30.189  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-27 11:51:30.189  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-27 11:51:30.189  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-27 11:51:30.189  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-27 11:51:30.189  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-27 11:51:30.189  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-27 11:51:30.190  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-27 11:51:30.190  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-27 11:51:30.190  7646  7646 I BluetoothA2dpServiceJni: classInitNative
07-27 11:51:30.190  7646  7646 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-27 11:51:30.190  7646  7646 D A2dpStateMachine: make
07-27 11:51:30.193  7646  7646 I bluedroid-qcom: get_profile_interface a2dp
07-27 11:51:30.194  7646  7885 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-27 11:51:30.197  7646  7646 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
07-27 11:51:30.197  7646  7646 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-27 11:51:30.198  7646  7646 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247ef0d3
07-27 11:51:30.199  7646  7646 I BluetoothHidServiceJni: classInitNative: succeeds
07-27 11:51:30.200  7646  7884 D A2dpStateMachine: Enter Disconnected: -2
07-27 11:51:30.201  7646  7646 D HidService: Received start request. Starting profile...
07-27 11:51:30.201  7646  7646 I bluedroid-qcom: get_profile_interface hidhost
07-27 11:51:30.201  7646  7646 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247ef0d3
07-27 11:51:30.202  7646  7646 I BluetoothHealthServiceJni: classInitNative: succeeds
07-27 11:51:30.203  7646  7646 D HealthService: Received start request. Starting profile...
,07-27 11:51:30.207  7646  7646 I bluedroid-qcom: get_profile_interface health,
07-27 11:51:30.207  7646  7646 I LGBluetoothHealthServiceJni: classInitNative: succeeds
07-27 11:51:30.207  7646  7646 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247ef0d3,
07-27 11:51:30.208  7646  7646 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-27 11:51:30.213  7646  7646 D PanService: Received start request. Starting profile...
,07-27 11:51:30.213  7646  7646 D BluetoothPanServiceJni: initializeNative(L110): pan
07-27 11:51:30.213  7646  7646 I bluedroid-qcom: get_profile_interface pan
,07-27 11:51:30.227  7646  7646 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
07-27 11:51:30.227  7646  7646 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247ef0d3
07-27 11:51:30.233  7646  7646 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,07-27 11:51:30.243  7646  7646 D BtGatt.DebugUtils: handleDebugAction() action=null
07-27 11:51:30.244  7646  7646 D BtGatt.GattService: Received start request. Starting profile...
07-27 11:51:30.244  7646  7646 D BtGatt.GattService: start()
07-27 11:51:30.244  7646  7646 I bluedroid-qcom: get_profile_interface gatt
,07-27 11:51:30.245  7646  7646 D BtGatt.AdvertiseManager: advertise manager created
07-27 11:51:30.259  7646  7646 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247ef0d3
,07-27 11:51:30.263  7646  7646 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247ef0d3
07-27 11:51:30.264  7646  7646 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
07-27 11:51:30.267  7646  7646 V BluetoothMapService: BluetoothMapBinder()
07-27 11:51:30.269  7646  7646 D BluetoothMapService: Received start request. Starting profile...
07-27 11:51:30.269  7646  7646 D BluetoothMapService: start()
07-27 11:51:30.277  7646  7646 D BluetoothMapEmailSettingsLoader: Found 0 applications
07-27 11:51:30.277  7646  7646 D BluetoothMapEmailAppObserver: createReceiver()
,07-27 11:51:30.281  7646  7646 D BluetoothMapEmailAppObserver: initObservers()
07-27 11:51:30.282  7646  7646 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
07-27 11:51:30.303  7646  7646 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247ef0d3
,07-27 11:51:30.303  7646  7646 D HeadsetStateMachine: Proxy object connected
07-27 11:51:30.304  7646  7646 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
07-27 11:51:30.304  7646  7646 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
07-27 11:51:30.306  7646  7876 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 11:51:30.306  7646  7876 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-27 11:51:30.307  7646  7876 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-27 11:51:30.311  7646  7646 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,07-27 11:51:30.312  7646  7646 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 11:51:30.312  7646  7646 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-27 11:51:30.312  7646  7646 V BluetoothSapReceiver: SapReceiver onReceive 
,07-27 11:51:30.312  7646  7646 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:30.312  7646  7646 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
07-27 11:51:30.320  7646  7646 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,07-27 11:51:30.323  7646  7646 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 11:51:30.330  7646  7646 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 11:51:30.330  7646  7646 V PanService: [BTUI] SIM Extra State :ABSENT
,07-27 11:51:30.335  7646  7646 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-27 11:51:30.338  7646  7646 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
07-27 11:51:30.338  7646  7646 V BluetoothMapService: Handler(): got msg=1
,07-27 11:51:30.340  7646  7853 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
07-27 11:51:30.340  7646  7853 I bluedroid-qcom: enable
07-27 11:51:30.340  7646  7853 I bt_hci_bdroid: init
,07-27 11:51:30.341  7646  7892 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-27 11:51:30.344  7646  7853 I bt_vendor: bt-vendor : init
07-27 11:51:30.344  7646  7853 I bt_vendor: bt-vendor : get_bt_soc_type
07-27 11:51:30.344  7646  7853 E bt_vendor: get_bt_soc_type: Failed to get soc type
07-27 11:51:30.344  7646  7853 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
07-27 11:51:30.344  7646  7853 D bt_userial_mct: userial_init
07-27 11:51:30.344  7646  7892 I bt-btu  : btu_task pending for preload complete event
07-27 11:51:30.345  7646  7853 D bt_hci_bdroid: set_power 1
07-27 11:51:30.345  7646  7853 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
07-27 11:51:30.345  7646  7853 I bt_vendor: Starting hciattach daemon
07-27 11:51:30.345  7646  7853 I bt_vendor: try to set true
07-27 11:51:30.344  7895  7895 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:51:30.344  7895  7895 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-27 11:51:30.387  7896  7896 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,07-27 11:51:30.522  7902  7902 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,07-27 11:51:30.543  7903  7903 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-27 11:51:30.577  7905  7905 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-27 11:51:30.589  7906  7906 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,07-27 11:51:30.619  7910  7910 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-27 11:51:30.630  7911  7911 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
07-27 11:51:30.666  7913  7913 I libmdmdetect: ESOC framework not supported
07-27 11:51:30.667  7913  7913 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,07-27 11:51:30.680  7913  7913 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
07-27 11:51:30.680  7913  7913 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,07-27 11:51:30.680  7913  7913 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,07-27 11:51:30.681  7913  7913 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
07-27 11:51:30.681  7913  7913 D bthci_qcomm_common: [BTUI]     LE: Class 2
07-27 11:51:30.681  7913  7913 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
07-27 11:51:30.681  7913  7913 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
07-27 11:51:30.724  7913  7914 E QC-QMI  : qmi_client [7913] 15: failed to locate client data
07-27 11:51:30.725   487   487 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
07-27 11:51:30.725   487   487 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,07-27 11:51:30.782  7918  7918 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,07-27 11:51:30.797  7919  7919 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-27 11:51:30.851  7646  7853 I bt_vendor: bluetooth satus is on
07-27 11:51:30.851  7646  7853 D bt_hci_bdroid: preload
07-27 11:51:30.851  7646  7894 D bt_userial_mct: userial_open(port:0)
07-27 11:51:30.851  7646  7894 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,07-27 11:51:30.855  7646  7894 I bt_vendor: Done intiailizing UART
,07-27 11:51:30.856  7646  7894 I bt_vendor: Done intiailizing UART
07-27 11:51:30.856  7646  7894 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
07-27 11:51:30.856  7646  7894 I bt_vendor: Bluetooth Firmware and transport layer are initialized
07-27 11:51:30.857  7646  7892 I bt-btu  : btu_task received preload complete event
07-27 11:51:30.857  7646  7892 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
07-27 11:51:30.857  7646  7892 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
07-27 11:51:30.859  7646  7892 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
07-27 11:51:30.862  7646  7921 D bt_userial_mct: Entering userial_read_thread()
,07-27 11:51:30.864  7646  7892 I         : BTE_InitTraceLevels -- TRC_HCI,
07-27 11:51:30.864  7646  7892 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-27 11:51:30.864  7646  7892 I         : BTE_InitTraceLevels -- TRC_RFCOMM,
07-27 11:51:30.864  7646  7892 I         : BTE_InitTraceLevels -- TRC_AVDT,
07-27 11:51:30.864  7646  7892 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-27 11:51:30.864  7646  7892 I         : BTE_InitTraceLevels -- TRC_A2D
,07-27 11:51:30.864  7646  7892 I         : BTE_InitTraceLevels -- TRC_BNEP
07-27 11:51:30.864  7646  7892 I         : BTE_InitTraceLevels -- TRC_BTM
,07-27 11:51:30.864  7646  7892 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,07-27 11:51:30.864  7646  7892 I         : BTE_InitTraceLevels -- TRC_GAP,
07-27 11:51:30.864  7646  7892 I         : BTE_InitTraceLevels -- TRC_PAN,
,07-27 11:51:30.864  7646  7892 I         : BTE_InitTraceLevels -- TRC_SDP
,07-27 11:51:30.864  7646  7892 I         : BTE_InitTraceLevels -- TRC_GATT,
,07-27 11:51:30.864  7646  7892 I         : BTE_InitTraceLevels -- TRC_SMP
,07-27 11:51:30.864  7646  7892 I         : BTE_InitTraceLevels -- TRC_BTAPP,
07-27 11:51:30.864  7646  7892 I         : BTE_InitTraceLevels -- TRC_BTIF
07-27 11:51:30.968  7646  7892 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
07-27 11:51:30.969  7646  7892 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01e0061 
07-27 11:51:30.969  7646  7892 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01e0061 
,07-27 11:51:31.021  7646  7857 E bt-btif : Calling BTA_HhEnable
07-27 11:51:31.021  7646  7857 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,07-27 11:51:31.024  7646  7857 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-27 11:51:31.025  7646  7892 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
07-27 11:51:31.025  7646  7892 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
07-27 11:51:31.025  7646  7892 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
07-27 11:51:31.025  7646  7892 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
07-27 11:51:31.025  7646  7892 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
07-27 11:51:31.026  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-27 11:51:31.027  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
07-27 11:51:31.027  7646  7857 D BluetoothAdapterProperties: Name is: G3
07-27 11:51:31.028  7646  7857 D BluetoothAdapterProperties: Scan Mode:20
07-27 11:51:31.028  7646  7857 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 11:51:31.029  7646  7857 D bt_hci_bdroid: postload
07-27 11:51:31.029  7646  7894 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 11:51:31.029  7646  7894 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 11:51:31.030  7646  7892 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
07-27 11:51:31.031  7646  7894 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 11:51:31.031  7646  7857 D bte_conf: Device ID record 1 : primary
07-27 11:51:31.031  7646  7857 D bte_conf:   vendorId            = 00c4
07-27 11:51:31.031  7646  7857 D bte_conf:   vendorIdSource      = 0001
07-27 11:51:31.031  7646  7857 D bte_conf:   product             = 13a1
07-27 11:51:31.031  7646  7857 D bte_conf:   version             = 1000
07-27 11:51:31.031  7646  7857 D bte_conf:   clientExecutableURL = 
07-27 11:51:31.031  7646  7857 D bte_conf:   serviceDescription  = 
07-27 11:51:31.031  7646  7857 D bte_conf:   documentationURL    = 
07-27 11:51:31.031  7646  7857 D bte_conf: bte_load_did_conf no section named DID2.
07-27 11:51:31.024  7924  7924 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-27 11:51:31.041  7646  7894 D bt_hci_bdroid: Used up Tx Cmd credits
07-27 11:51:31.042  7646  7853 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-27 11:51:31.042  7646  7853 D BluetoothAdapterProperties: ScanMode =  20
07-27 11:51:31.042  7646  7853 D BluetoothAdapterProperties: State =  11
07-27 11:51:31.042  7646  7853 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
07-27 11:51:31.043  7646  7853 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
07-27 11:51:31.043  7646  7853 D BluetoothAdapterProperties: Setting state to 12
07-27 11:51:31.034  7924  7924 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:51:31.048  7646  7853 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-27 11:51:31.048  7646  7857 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-27 11:51:31.048  7646  7857 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-27 11:51:31.051  1037  1120 D BluetoothManagerService: Message: 60
07-27 11:51:31.052  1037  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
07-27 11:51:31.052  1037  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,07-27 11:51:31.057  7646  7921 E bt_mct  : hci lib postload completed
07-27 11:51:31.066  7646  7892 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 11:51:31.066  7646  7892 W bt-smp  : Plain text(LSB ~ MSB) = 05 97 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 11:51:31.066  7646  7892 W bt-smp  : Encrypted text(LSB ~ MSB) = 1b 06 f9 f6 d2 91 63 1f 61 4f e0 58 45 7b 4a 02 
07-27 11:51:31.066  7646  7892 W bt-btm  : Stopping oneshot timer
,07-27 11:51:31.088  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:31.088  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:31.088  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:31.088  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:51:31.088  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:31.088  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:31.088  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:31.088  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:51:31.092  7646  7853 I BluetoothAdapterState: Entering On State
07-27 11:51:31.096  7646  7857 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 11:51:31.096  7646  7857 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
07-27 11:51:31.100  6735  6735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:51:31.117  7646  7892 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 11:51:31.117  7646  7892 W bt-smp  : Plain text(LSB ~ MSB) = 2c 56 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 11:51:31.117  7646  7892 W bt-smp  : Encrypted text(LSB ~ MSB) = 11 51 06 98 0d 0c fa f9 22 89 31 a4 c7 2c 72 1a 
,07-27 11:51:31.122  7646  7892 W bt-btm  : Stopping oneshot timer
07-27 11:51:31.137  7646  7853 D LGBluetoothServiceAdapter: [BTUI] OnState
07-27 11:51:31.138  7646  7853 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
07-27 11:51:31.138  7646  7853 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,07-27 11:51:31.142  7646  7853 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-27 11:51:31.142  7646  7853 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
07-27 11:51:31.149  7646  7892 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 11:51:31.150  7646  7892 W bt-smp  : Plain text(LSB ~ MSB) = b6 bf 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 11:51:31.150  7646  7892 W bt-smp  : Encrypted text(LSB ~ MSB) = 38 a3 87 c6 c4 ce 3a 9e c4 31 05 af b9 25 8b 90 
07-27 11:51:31.150  7646  7892 W bt-btm  : Stopping oneshot timer
07-27 11:51:31.160  6803  6821 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-27 11:51:31.167  6803  7539 D BluetoothMap: onBluetoothStateChange: up=true
07-27 11:51:31.168  6803  6803 D BluetoothA2dp: Proxy object connected
07-27 11:51:31.168  6803  6803 D A2dpProfile: Bluetooth service connected
07-27 11:51:31.170  1837  2507 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 11:51:31.173  6803  6819 D BluetoothPan: onBluetoothStateChange on: true
07-27 11:51:31.173  6803  6819 D BluetoothPan: onBluetoothStateChange call bindService
07-27 11:51:31.175  1837  1837 D BluetoothHeadset: Proxy object connected
,07-27 11:51:31.175  7941  7941 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
07-27 11:51:31.176  6803  7539 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 11:51:31.178  6803  6803 D BluetoothMap: Proxy object connected
07-27 11:51:31.178  6803  6803 D MapProfile: Bluetooth service connected
07-27 11:51:31.178  6803  6803 D BluetoothMap: getConnectedDevices()
07-27 11:51:31.179  7646  7892 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 11:51:31.179  7646  7892 W bt-smp  : Plain text(LSB ~ MSB) = 8b b6 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 11:51:31.179  7646  7892 W bt-smp  : Encrypted text(LSB ~ MSB) = be 23 46 6f 70 6a 87 40 38 de f3 05 51 9e 05 85 
07-27 11:51:31.179  7646  7892 W bt-btm  : Stopping oneshot timer
07-27 11:51:31.180  1837  1852 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 11:51:31.181  1037  1120 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 11:51:31.181  1837  1837 D BluetoothHeadset: Proxy object connected
07-27 11:51:31.182  1037  1037 D BluetoothA2dp: Proxy object connected
07-27 11:51:31.182  7646  7944 V BluetoothMapService: getConnectedDevices()
07-27 11:51:31.182  6803  7539 D BluetoothPbap: onBluetoothStateChange: up=true
07-27 11:51:31.183  6803  6803 D BluetoothHeadset: Proxy object connected
07-27 11:51:31.183  6803  6803 D HeadsetProfile: Bluetooth service connected
07-27 11:51:31.184  1037  1120 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 11:51:31.185  1037  1037 D BluetoothHeadset: Proxy object connected
07-27 11:51:31.185  1837  1852 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 11:51:31.185  6803  6803 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 11:51:31.185  6803  6803 D PanProfile: Bluetooth service connected
07-27 11:51:31.187  1837  1837 D BluetoothHeadset: Proxy object connected
07-27 11:51:31.187  6803  6819 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-27 11:51:31.189  7646  7892 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-27 11:51:31.189  7646  7892 W bt-smp  : Plain text(LSB ~ MSB) = ab 02 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 11:51:31.189  7646  7892 W bt-smp  : Encrypted text(LSB ~ MSB) = bf ea d9 f7 a1 ef 25 25 95 40 ba 49 0e 7a a5 d4 
07-27 11:51:31.189  7646  7892 W bt-btm  : Stopping oneshot timer
07-27 11:51:31.192  1037  1120 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
07-27 11:51:31.192  1037  1120 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
07-27 11:51:31.193  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-27 11:51:31.193  6803  6803 D BluetoothInputDevice: Proxy object connected
07-27 11:51:31.193  6803  6803 D HidProfile: Bluetooth service connected
07-27 11:51:31.194  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-27 11:51:31.195  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:31.196  1927  2132 D LGBluetoothAPIService: Message: 1
07-27 11:51:31.196  1927  2132 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
07-27 11:51:31.196  1927  2132 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
07-27 11:51:31.196  1927  2132 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
07-27 11:51:31.197  1037  1120 D BluetoothManagerService: Message: 40
07-27 11:51:31.197  1037  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
07-27 11:51:31.199  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:31.201  7646  7646 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:31.201  7646  7646 D BluetoothMapService: STATE_ON
07-27 11:51:31.201  7646  7646 V BluetoothMapService: Handler(): got msg=1
07-27 11:51:31.203  7646  7646 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
07-27 11:51:31.204  6803  6803 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
07-27 11:51:31.206  6803  6803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-27 11:51:31.209  7646  7948 D BluetoothMapMasInstance: MAS initSocket()
07-27 11:51:31.209  7646  7948 D BluetoothMapMasInstance:   masId = 00
07-27 11:51:31.209  7646  7948 D BluetoothMapMasInstance:   msgTypes = 0e
07-27 11:51:31.209  7646  7948 D BluetoothMapMasInstance:   masName = SMS/MMS
07-27 11:51:31.209  7646  7948 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
07-27 11:51:31.210  1037  1641 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:31.211  7646  7948 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 11:51:31.212  6803  6803 D DockEventReceiver: finishStartingService: stopping service
07-27 11:51:31.216  7646  7857 D BluetoothAdapterProperties: Scan Mode:21
07-27 11:51:31.216  7646  7857 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
07-27 11:51:31.217  7646  7948 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
07-27 11:51:31.218  7646  7948 V BluetoothMapMasInstance: Succeed to create listening socket 
07-27 11:51:31.218  7646  7948 D BluetoothMapMasInstance: Accepting socket connection...
07-27 11:51:31.219  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:31.221  7646  7646 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247ef0d3
07-27 11:51:31.221  7646  7646 V BluetoothPbapService: Pbap Service onCreate
07-27 11:51:31.221  7646  7646 V BluetoothPbapService: Starting PBAP service
07-27 11:51:31.223  7646  7646 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
07-27 11:51:31.223  7646  7646 V BluetoothPbapService: Pbap Service onBind
,07-27 11:51:31.224  7646  7646 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:31.224  7646  7646 V BluetoothPbapService: state: 12
07-27 11:51:31.224  6803  6803 D BluetoothPbap: Proxy object connected
07-27 11:51:31.224  6803  6803 D PbapServerProfile: Bluetooth service connected
07-27 11:51:31.224  7646  7646 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-27 11:51:31.224  7646  7646 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:31.224  7646  7646 V BluetoothPbapReceiver: ***********state = 12
07-27 11:51:31.226  7646  7646 V BluetoothPbapService: Handler(): got msg=1
07-27 11:51:31.226  7646  7646 V BluetoothPbapService: Pbap Service startRfcommSocketListener
07-27 11:51:31.227  7646  7950 V BluetoothPbapService: Pbap Service initSocket
07-27 11:51:31.228  1037  1890 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:31.228  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-27 11:51:31.228  2194  2194 D c       : Getting all permits...
07-27 11:51:31.228  2194  2194 D a       : Opening database...
07-27 11:51:31.229  7646  7950 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 11:51:31.230  7646  7950 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
07-27 11:51:31.230  7646  7950 V BluetoothPbapService: Succeed to create listening socket 
07-27 11:51:31.230  7646  7950 V BluetoothPbapService: Accepting socket connection...
07-27 11:51:31.232  2194  2194 D a       : Opening database auth.proximity.permit_store...
07-27 11:51:31.232  2194  2194 D a       : Closing database...
07-27 11:51:31.241  6803  6803 D BluetoothPermissionRequest: onReceive
,07-27 11:51:31.243  6803  6803 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-27 11:51:31.244  6803  6803 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-27 11:51:31.246  7646  7646 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
07-27 11:51:31.247  7646  7646 I LGBluetoothOppAdapter: [BTUI] startOppService()
07-27 11:51:31.252  7646  7646 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,07-27 11:51:31.265  7646  7646 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-27 11:51:31.265  7646  7646 V BtOppService: onCreate
07-27 11:51:31.268  7646  7646 V BluetoothOppNotification: send message
,07-27 11:51:31.271  7646  7646 V BtOppService: Starting RfcommListener
07-27 11:51:31.279  7646  7646 D BluetoothOppPreference: Dumping Names:  
07-27 11:51:31.279  7646  7646 D BluetoothOppPreference: {}
,07-27 11:51:31.279  7646  7646 D BluetoothOppPreference: Dumping Channels:  
07-27 11:51:31.279  7646  7646 D BluetoothOppPreference: {}
07-27 11:51:31.281  7646  7646 V BtOppService: onStartCommand
07-27 11:51:31.284  7646  7954 V BtOppService: Deleted complete outbound shares, number =  0
07-27 11:51:31.285  7646  7957 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-27 11:51:31.286  7646  7957 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-27 11:51:31.287  7646  7957 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3769d3ff on behalf of 
07-27 11:51:31.287  7646  7954 V BtOppService: Deleted complete inbound failed shares, number = 0
07-27 11:51:31.288  7646  7646 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:31.288  7646  7957 V BluetoothOppNotification: update too frequent, put in queue
07-27 11:51:31.289  7646  7954 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
07-27 11:51:31.289  7646  7646 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-27 11:51:31.289  7646  7957 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-27 11:51:31.291  7646  7954 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ce125cc on behalf of 
07-27 11:51:31.293  7646  7646 V BluetoothOppNotification: new notify threadi!
,07-27 11:51:31.294  7646  7646 V BluetoothOppNotification: send delay message
07-27 11:51:31.295  7646  7958 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-27 11:51:31.296  7646  7646 V BtOppService: start RfcommListener
07-27 11:51:31.296  7646  7958 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d297015 on behalf of 
07-27 11:51:31.297  7646  7958 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-27 11:51:31.298  7646  7958 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-27 11:51:31.299  7646  7958 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10094f2a on behalf of 
07-27 11:51:31.300  7646  7958 V BluetoothOppNotification: outbound: succ-0  fail-0
07-27 11:51:31.301  7646  7958 V BluetoothOppNotification: outbound notification was removed.
07-27 11:51:31.301  7646  7958 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-27 11:51:31.303  7646  7646 V BtOppService: RfcommListener started
07-27 11:51:31.304  7646  7646 V BtOppService: ContentObserver received notification
07-27 11:51:31.307  7646  7646 V BtOppService: ContentObserver received notification
,07-27 11:51:31.310  7646  7961 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-27 11:51:31.310  7646  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-27 11:51:31.318  7646  7960 V BtOppRfcommListener: Starting RFCOMM listener....
07-27 11:51:31.319  1037  1766 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-27 11:51:31.320  7646  7960 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 11:51:31.326  7646  7960 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
07-27 11:51:31.326  7646  7960 V BtOppRfcommListener: Started RFCOMM listener....
07-27 11:51:31.326  7646  7960 I BtOppRfcommListener: Accept thread started.
07-27 11:51:31.326  7646  7960 V BtOppRfcommListener: Accepting connection...
07-27 11:51:31.335  7646  7646 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247ef0d3
07-27 11:51:31.335  7646  7646 V BluetoothFtpService: Ftp Service onCreate
07-27 11:51:31.335  7646  7646 I BluetoothFtpService: Ftp Service onCreate
07-27 11:51:31.336  7646  7646 V BluetoothFtpService: Ftp Service onStartCommand
,07-27 11:51:31.336  7646  7646 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:31.336  7646  7646 V BluetoothFtpService: Starting Listening on sockets
07-27 11:51:31.336  7646  7646 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 11:51:31.336  7646  7646 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-27 11:51:31.336  7646  7646 V BluetoothSapReceiver: SapReceiver onReceive 
07-27 11:51:31.336  7646  7646 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:31.336  7646  7646 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
07-27 11:51:31.336  7646  7646 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-27 11:51:31.424  1037  1926 I art     : Explicit concurrent mark sweep GC freed 25961(1275KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.324ms total 122.194ms
,07-27 11:51:31.426  7646  7646 V BluetoothFtpService: Handler(): got msg=1
07-27 11:51:31.427  7646  7646 V BluetoothFtpService: Ftp Service startRfcommSocketListener
07-27 11:51:31.428  7646  7646 V BluetoothFtpService: Ftp Service initSocket
07-27 11:51:31.429  7646  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b3df891 on behalf of 
07-27 11:51:31.431  1037  1997 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:31.431  7646  7958 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2de0d2b8 on behalf of 
07-27 11:51:31.432  7646  7646 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 11:51:31.433  7646  7958 V BluetoothOppNotification: inbound: succ-0  fail-0
07-27 11:51:31.434  7646  7646 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=78
07-27 11:51:31.435  7646  7646 V BluetoothFtpService: Succeed to create listening socket on channel 20
07-27 11:51:31.438  7646  7962 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
07-27 11:51:31.439  7646  7961 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,07-27 11:51:31.441  7646  7958 V BluetoothOppNotification: inbound notification was removed.
07-27 11:51:31.441  7646  7958 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-27 11:51:31.442  7646  7958 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2c4533f6 on behalf of 
07-27 11:51:31.459  7646  7646 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247ef0d3
07-27 11:51:31.459  7646  7646 V BluetoothSapService: Sap Service onCreate
,07-27 11:51:31.461  7646  7646 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:31.461  7646  7646 V BluetoothSapService: state: 12
07-27 11:51:31.461  7646  7646 V BluetoothSapService: Starting SAP server process
07-27 11:51:31.464  7646  7646 V BluetoothSapService: SAP Service startRfcommListenerThread
07-27 11:51:31.454  7963  7963 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:51:31.454  7963  7963 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:51:31.467  7646  7964 V BluetoothSapService: Sap Service initRfcommSocket
07-27 11:51:31.468  1037  1872 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:31.470  7646  7964 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 11:51:31.473  7646  7964 V BluetoothSapService: Succeed to create listening socket 
,07-27 11:51:31.474  7646  7964 V BluetoothSapService: Accepting socket connection...
,07-27 11:51:31.476  7963  7963 V BT_SAP  : Event pipe created
07-27 11:51:31.476  7963  7963 V BT_SAP  : create_server_socket qcom.sap.server
07-27 11:51:31.476  7963  7963 V BT_SAP  : created socket fd 6
,07-27 11:51:31.751  6735  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:31.751  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:31.751  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:31.751  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:51:31.751  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:31.751  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:31.751  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:31.751  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:51:31.756  6735  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:51:31.761  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-27 11:51:31.761  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f26fe39 added. We now have 8 listener(s)
,07-27 11:51:31.761  6735  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 11:51:31.772  1037  1641 D WifiServiceImplEx: setWifiEnabled: false pid=6735, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,07-27 11:51:31.773  1037  1641 D WifiService: setWifiEnabled: false pid=6735, uid=10118
07-27 11:51:31.773  1037  1641 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-27 11:51:31.782  6735  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:31.783  1037  1998 D WifiServiceImplEx: setWifiEnabled: true pid=6735, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-27 11:51:31.784  1037  1998 D WifiService: setWifiEnabled: true pid=6735, uid=10118
07-27 11:51:31.784  1037  1998 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-27 11:51:31.794  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 11:51:31.795  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-27 11:51:31.795  1037  1037 D Ulp_jni : JNI:system_update. Event-4
,07-27 11:51:31.797  1037  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,07-27 11:51:31.797  1037  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-27 11:51:31.800  1037  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
07-27 11:51:31.800  1037  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-27 11:51:31.800  1037  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
07-27 11:51:31.800  1037  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-27 11:51:31.800  1037  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D
07-27 11:51:31.801  1037  1523 E WifiHW  : unknown target_country: EU , set to default
07-27 11:51:31.801  1037  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
07-27 11:51:31.801  1037  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
07-27 11:51:31.801  1037  1523 I WifiUtil: gEnableBmps=1
07-27 11:51:32.299  7646  7646 V BluetoothOppNotification: new notify threadi!
07-27 11:51:32.300  7646  7646 V BluetoothOppNotification: send delay message
,07-27 11:51:32.311  7646  7983 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-27 11:51:32.313  7646  7983 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7889982 on behalf of 
07-27 11:51:32.313  7646  7983 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-27 11:51:32.315  7646  7983 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-27 11:51:32.317  7646  7983 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@107b2893 on behalf of 
07-27 11:51:32.317  7646  7983 V BluetoothOppNotification: outbound: succ-0  fail-0
,07-27 11:51:32.321  7646  7983 V BluetoothOppNotification: outbound notification was removed.
07-27 11:51:32.321  7646  7983 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-27 11:51:32.322  7646  7983 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f7f40d0 on behalf of 
07-27 11:51:32.323  7646  7983 V BluetoothOppNotification: inbound: succ-0  fail-0
07-27 11:51:32.325  7646  7983 V BluetoothOppNotification: inbound notification was removed.
07-27 11:51:32.325  7646  7983 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-27 11:51:32.326  7646  7983 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3fce28c9 on behalf of 
07-27 11:51:32.383   332   895 D SoftapController: Softap fwReload - Ok
,07-27 11:51:32.402  1037  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-27 11:51:32.403  1037  1120 D Tethering: InitialState.processMessage what=4
,07-27 11:51:32.408  1037  1523 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (604ms)
07-27 11:51:32.420   332   895 D CommandListener: Setting iface cfg
07-27 11:51:32.420   332   895 D CommandListener: Trying to bring down wlan0
,07-27 11:51:32.438   332   895 D CommandListener: Clearing all IP addresses on wlan0
,07-27 11:51:32.448  1037  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-27 11:51:32.457  1037  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,07-27 11:51:32.454  7985  7985 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:51:32.464  7985  7985 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-27 11:51:32.502  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-27 11:51:32.503  6803  6803 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-27 11:51:32.503  6803  6803 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-27 11:51:32.503  6803  6803 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,07-27 11:51:32.507  1037  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-27 11:51:32.507  1037  1523 E WifiStateMachine: useWiFiOffloading() : false
07-27 11:51:32.507  1037  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-27 11:51:32.512  1037  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-27 11:51:32.512  1037  1523 D WifiMonitor: connecting to supplicant
07-27 11:51:32.518  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:32.519  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-27 11:51:32.524  7985  7985 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-27 11:51:32.531  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
07-27 11:51:32.532  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
07-27 11:51:32.539  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:32.540  6803  6803 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-27 11:51:32.540  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-27 11:51:32.540  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-27 11:51:32.540  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-27 11:51:32.540  6803  6803 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,07-27 11:51:32.540  6803  6803 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-27 11:51:32.545  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-27 11:51:32.545  6803  6803 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-27 11:51:32.545  6803  6803 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-27 11:51:32.545  6803  6803 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-27 11:51:32.545  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-27 11:51:32.546  6803  6803 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-27 11:51:32.546  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-27 11:51:32.546  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-27 11:51:32.546  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-27 11:51:32.546  6803  6803 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-27 11:51:32.546  6803  6803 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-27 11:51:32.561  7985  7985 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-27 11:51:32.561  7985  7985 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,07-27 11:51:32.586  1037  1908 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8004 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,07-27 11:51:32.619  7985  7985 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-27 11:51:32.696  7985  7985 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,07-27 11:51:32.703  7985  7985 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
07-27 11:51:32.704  7985  7985 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-27 11:51:32.705  1037  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
07-27 11:51:32.705  1037  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
07-27 11:51:32.706  1037  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
07-27 11:51:32.706  1037  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
07-27 11:51:32.706  1037  8027 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
07-27 11:51:32.707  1037  8027 D WifiMonitor: Dropping event because (p2p0) is stopped
07-27 11:51:32.707  1037  8027 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-27 11:51:32.707  1037  8027 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-27 11:51:32.707  1037  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:51:32.707  1037  8027 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-27 11:51:32.707  1037  8027 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-27 11:51:32.707  1037  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:51:32.708  1037  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:51:32.708  1037  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:51:32.709  1037  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
07-27 11:51:32.709  1037  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
07-27 11:51:32.710  1037  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
07-27 11:51:32.710  1037  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
07-27 11:51:32.710  1037  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
07-27 11:51:32.710  1037  1926 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8025 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-27 11:51:32.715  1037  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-27 11:51:32.715  1037  1523 E WifiStateMachine: useWiFiOffloading() : false
07-27 11:51:32.715  1037  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,07-27 11:51:32.717  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:32.717  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:32.718  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:32.718  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:32.718  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-27 11:51:32.718  8004  8023 W FormManager: Network not available. Please check & try again.
07-27 11:51:32.719  1037  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
07-27 11:51:32.720  1037  1523 D WifiNative-wlan0: SET update_config 1: returned true
07-27 11:51:32.720  1037  1523 D WifiConfigStore: Loading config and enabling all networks 
07-27 11:51:32.720  1037  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
07-27 11:51:32.720  1927  1927 D WfdService: Waiting for WifiP2p enabling
07-27 11:51:32.720  1037  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
07-27 11:51:32.721  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:32.723  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
07-27 11:51:32.723  1037  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-27 11:51:32.727  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:32.727  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:32.727  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:32.727  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:32.727  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:32.727  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:32.727  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:32.727  6735  6735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:51:32.729  1037  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
07-27 11:51:32.730  8004  8024 V FormManager: Network unavailable.
07-27 11:51:32.731  6735  6735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:51:32.733  8004  8024 V FormManager: Network unavailable.
07-27 11:51:32.740  1037  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
07-27 11:51:32.741  1037  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-27 11:51:32.741  1037  1523 D WifiStateMachine: enableVerboseLogging : level 2
07-27 11:51:32.742  1037  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,07-27 11:51:32.742  1037  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
07-27 11:51:32.742  1037  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
07-27 11:51:32.742  1037  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
07-27 11:51:32.742  1037  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
07-27 11:51:32.743  1037  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
07-27 11:51:32.743  1037  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
07-27 11:51:32.743  1037  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
07-27 11:51:32.744  1037  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
07-27 11:51:32.744  1037  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
07-27 11:51:32.744  1037  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
07-27 11:51:32.745  1037  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
07-27 11:51:32.745  1037  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
07-27 11:51:32.745  1037  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
07-27 11:51:32.746  1037  1523 D WifiStateMachine: Setting OUI to DA-A1-19
07-27 11:51:32.746  1037  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
07-27 11:51:32.746  1037  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
07-27 11:51:32.746  1037  1523 D WifiNative-HAL: Setting external_sim to 1
07-27 11:51:32.746  1037  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
07-27 11:51:32.746  1927  1927 D WfdsService: Supplicant Connection state is changed : true
07-27 11:51:32.747  1927  2323 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-27 11:51:32.747  1927  2323 D WfdsService: Set the WFDS Monitor: true
07-27 11:51:32.747  1927  2323 D WfdsMonitor: WfdsMonitorThread create
07-27 11:51:32.747  7674  7674 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:32.747  1927  2323 D WfdsMonitor: WFDS Monitor is created and started
07-27 11:51:32.747  1927  2323 D WfdsService: WiFi: Supplicant connection re-established
07-27 11:51:32.748  1037  1523 D WifiNative-wlan0: SET external_sim 1: returned true
07-27 11:51:32.748  1037  1523 I WifiNative-HAL: startHal
07-27 11:51:32.748  1037  1523 D wifi    : setting scan oui 0x9576af80
07-27 11:51:32.749  1927  8044 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-27 11:51:32.749  1927  8044 E CtrlSupplicant: Succeed to open control connection
07-27 11:51:32.749  1927  8044 E CtrlSupplicant: Succeed to open monitor connection
07-27 11:51:32.749  1037  1523 D WifiStateMachine: Setting OUI to DA-A1-19
07-27 11:51:32.749  1037  1523 I WifiNative-HAL: startHal
07-27 11:51:32.749  1037  1523 D wifi    : setting scan oui 0x9576af80
07-27 11:51:32.750  1927  8044 D WfdsMonitor: Supplicant connection established
07-27 11:51:32.750  1037  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
07-27 11:51:32.750  1927  2323 D WfdsService: Connected to the supplicant for wfds
07-27 11:51:32.750  1037  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
07-27 11:51:32.750  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
07-27 11:51:32.750  7985  7985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
07-27 11:51:32.751  1037  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
07-27 11:51:32.751  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-27 11:51:32.751  7985  7985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-27 11:51:32.751  1037  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-27 11:51:32.751  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
07-27 11:51:32.751  7985  7985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
07-27 11:51:32.751  ,1037  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
07-27 11:51:32.751  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-27 11:51:32.752  7985  7985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-27 11:51:32.752  1037  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-27 11:51:32.752  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-27 11:51:32.752  7985  7985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-27 11:51:32.752  1037  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-27 11:51:32.752  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
07-27 11:51:32.752  7985  7985 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
07-27 11:51:32.753  1037  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
07-27 11:51:32.753  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-27 11:51:32.753  7985  7985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-27 11:51:32.753  1037  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-27 11:51:32.754  1037  1523 E WifiNative: : [320,581,649 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
07-27 11:51:32.754  1037  1523 D WifiNative-wlan0: doBoolean: RECONNECT
07-27 11:51:32.754  1037  1523 D WifiNative-wlan0: RECONNECT: returned true
07-27 11:51:32.754  1037  1523 D WifiNative-wlan0: doString: [STATUS]
07-27 11:51:32.755  1037  8027 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-27 11:51:32.755  1037  8027 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
07-27 11:51:32.755  1037  1523 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-27 11:51:32.755  1037  1523 D WifiNative-wlan0: doBoolean: SET ps 1
07-27 11:51:32.756  1037  1523 D WifiNative-wlan0: SET ps 1: returned true
07-27 11:51:32.756  1037  1522 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:32.757  1037  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
07-27 11:51:32.758  1037  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
07-27 11:51:32.758  1037  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
07-27 11:51:32.758  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 3
07-27 11:51:32.758  1037  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
07-27 11:51:32.758  1037  1541 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:32.759  1037  1541 I WifiNative-HAL: startHal
07-27 11:51:32.759  1037  1541 D wifi    : getting scan capabilities on interface[1] = 0x9576af80
07-27 11:51:32.759  1037  1541 D wifi    : failed to get capabilities : -3
07-27 11:51:32.759  1037  1541 E WifiScanningService: could not get scan capabilities
07-27 11:51:32.759  1037  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
07-27 11:51:32.759  1037  1037 D RttService: SCAN_AVAILABLE : 3
07-27 11:51:32.759  1037  1542 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:32.759  1037  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
07-27 11:51:32.759  1037  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
07-27 11:51:32.759  1037  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
07-27 11:51:32.759  7985  7985 E wpa_supplicant: nWIFIDualbandAPConnection: 1
07-27 11:51:32.760  1037  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
07-27 11:51:32.760   332   895 D CommandListener: Setting iface cfg
07-27 11:51:32.760   332   895 D CommandListener: Trying to bring up p2p0
07-27 11:51:32.760  1037  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
07-27 11:51:32.760  1037  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
07-27 11:51:32.760  1037  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
07-27 11:51:32.760  7985  7985 E wpa_supplicant: disconnect_rssi_lvl: -100
07-27 11:51:32.761  1037  1522 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-27 11:51:32.761  1037  1523 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
07-27 11:51:32.761  1037  1523 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
07-27 11:51:32.761  1037  1522 D LGWifiP2pService: P2pEnablingState
07-27 11:51:32.762  1037  1522 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:32.762  1037  1523 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
07-27 11:51:32.762  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
07-27 11:51:32.762  1037  1926 I ActivityManager: Killing 7103:com.android.chrome/u0a57 (adj 15): empty #17
07-27 11:51:32.762  1037  1522 D LGWifiP2pService: P2p socket connection successful
07-27 11:51:32.762  1037  1522 D LGWifiP2pService: P2pEnabledState
07-27 11:51:32.762  7985  7985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-27 11:51:32.762  7985  7985 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:51:32.763  7985  7985 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-27 11:51:32.763  7985  7985 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:32.764  7985  7985 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:32.765  1927  8044 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:51:32.765  1927  8044 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:51:32.765  1037  8027 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-27 11:51:32.765  1037  8027 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:51:32.765  1037  8027 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:51:32.765  1037  8027 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:51:32.765  1037  8027 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:51:32.765  1037  8027 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:32.765  1037  8027 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:32.765  1037  8027 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:32.765  1037  8027 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:51:32.765  1037  8027 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:32.765  1037  8027 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:32.765  1037  8027 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:32.766  1037  1523 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
07-27 11:51:32.766  1037  1523 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
07-27 11:51:32.766  1037  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
07-27 11:51:32.767  1037  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
07-27 11:51:32.767  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
07-27 11:51:32.767  7985  7985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
07-27 11:51:32.767  7985  7985 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 11:51:32.768  1037  8027 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
07-27 11:51:32.768  1037  8027 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 11:51:32.768  1037  8027 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 11:51:32.768  1037  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
07-27 11:51:32.768  1037  8027 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 11:51:32.768  1037  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
07-27 11:51:32.768  1037  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
07-27 11:51:32.768  1037  1523 D WifiNative-wlan0: doBoolean: SCAN
07-27 11:51:32.769  1037  1523 D WifiNative-wlan0: SCAN: returned false
07-27 11:51:32.769  1037  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=320597  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,07-27 11:51:32.806  6735  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:32.806  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:32.806  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:32.806  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:32.806  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:32.806  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:32.806  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:32.806  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:51:32.810  6735  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:51:32.814  6735  6792 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
07-27 11:51:32.815  6735  6792 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-27 11:51:32.816  6735  6792 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@303183e6 Bundle[{}]
07-27 11:51:32.817  6735  6792 I io.jxcore.node.LifeCycleMonitor: start: OK
07-27 11:51:32.817  6735  6792 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-27 11:51:32.818  6735  6792 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-27 11:51:32.819  6735  6792 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-27 11:51:32.820  6735  6792 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-27 11:51:32.821  6735  6792 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-27 11:51:32.831  6735  6792 I System.out: Running OutgoingSocketThread
07-27 11:51:32.832  6735  8045 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 872)
07-27 11:51:32.833  6735  8045 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 53022
07-27 11:51:32.833  6735  8045 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-27 11:51:32.843  1037  1522 D LGWifiP2pService: sending p2p connection changed broadcast
07-27 11:51:32.844  1037  1522 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
07-27 11:51:32.845  1037  1522 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
07-27 11:51:32.845  1037  1522 D WifiNative-p2p0: doBoolean: SET device_name G3
,07-27 11:51:32.845  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
07-27 11:51:32.845  1927  1927 D WfdsService: WifiP2pState is changed : true
07-27 11:51:32.845  1927  1927 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-27 11:51:32.846  1927  1927 D WfdsService: isConnected: false
07-27 11:51:32.846  1927  2323 D WfdsService: Receive the WFDS_ENABLE Method
07-27 11:51:32.846  1927  2323 D WfdsService: Set the WFDS Monitor: true
07-27 11:51:32.846  1927  2323 D WfdsService: Connected to the supplicant for wfds
07-27 11:51:32.846  1927  2323 D WfdsJNI : doCommand: WFDS_SET TRUE
07-27 11:51:32.846  7985  7985 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
07-27 11:51:32.847  1037  1060 W libprocessgroup: failed to open /acct/uid_10057/pid_7103/cgroup.procs: No such file or directory
07-27 11:51:32.848  1037  1522 D WifiNative-p2p0: SET device_name G3: returned true
,07-27 11:51:32.848  1037  1522 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-27 11:51:32.848  1037  1522 D LGWifiP2pService: before postfix = G3
07-27 11:51:32.848  1037  1522 D WifiServerServiceExt: postfix byte check : 2
07-27 11:51:32.848  1037  1522 D LGWifiP2pService: after postfix = G3
07-27 11:51:32.848  1927  2323 D WfdsService: selectPreferredScanChannel [36]
07-27 11:51:32.848  1927  2323 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
07-27 11:51:32.848  1037  1522 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
07-27 11:51:32.848  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=320676  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-27 11:51:32.849  1037  1523 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 11:51:32.850  1037  1522 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
07-27 11:51:32.850  1037  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 11:51:32.850  1037  1522 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
07-27 11:51:32.850  1037  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 11:51:32.851  1037  1522 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
07-27 11:51:32.851  1037  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 11:51:32.851  1037  1522 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
07-27 11:51:32.851  1037  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-27 11:51:32.852  1037  1522 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
07-27 11:51:32.852  1037  1522 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
07-27 11:51:32.853  1037  1522 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
07-27 11:51:32.853  1037  1522 D WifiNative-HAL: p2pGetDeviceAddress
07-27 11:51:32.856  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:32.856  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:32.856  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-27 11:51:32.857  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:32.857  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:51:32.857  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:51:32.858  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
07-27 11:51:32.858  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:32.859  1037  1522 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
07-27 11:51:32.860  1037  1522 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
,07-27 11:51:32.860  1037  1522 D WifiNative-p2p0: doBoolean: P2P_FLUSH
,07-27 11:51:32.861  1037  1522 D WifiNative-p2p0: P2P_FLUSH: returned true
,07-27 11:51:32.861  1037  1522 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
07-27 11:51:32.862  1927  1927 I WfdStateTracker: handleP2pThisDeviceChanged
07-27 11:51:32.862  1927  1927 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
07-27 11:51:32.862  1927  1927 D WfdsService: Update P2p Interface State: 3
07-27 11:51:32.862  1037  1522 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
07-27 11:51:32.862  1037  1522 D WifiNative-p2p0: doString: [LIST_NETWORKS]
07-27 11:51:32.863  1037  1522 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
07-27 11:51:32.863  1037  1522 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
07-27 11:51:32.872  1037  1522 D WifiNative-p2p0: SAVE_CONFIG: returned true
07-27 11:51:32.873  1037  1522 D LGWifiP2pService: sending p2p persistent groups changed broadcast
07-27 11:51:32.873  1037  1522 D LGWifiP2pService: InactiveState
07-27 11:51:32.873  1037  1522 D LGWifiP2pService: InactiveState{ when=-107ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:32.873  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-107ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:32.873  1037  1522 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
07-27 11:51:32.874  7985  7985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-27 11:51:32.875  7985  7985 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:51:32.876  7985  7985 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-27 11:51:32.876  1037  8027 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-27 11:51:32.876  7985  7985 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:32.876  1037  8027 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:51:32.877  1037  8027 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:51:32.877  1037  8027 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-27 11:51:32.877  1037  8027 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:51:32.877  1037  1522 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
07-27 11:51:32.877  1037  8027 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:32.877  1037  1522 D LGWifiP2pService: InactiveState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:32.877  1037  8027 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:32.877  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:32.878  1037  8027 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:32.878  1037  1522 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:32.878  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:32.878  1037  1522 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:32.878  1037  1522 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:32.878  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:32.878  1037  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:32.878  1927  8044 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTR,Y alpha2=CZ]
07-27 11:51:32.878  7985  7985 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:32.878  1927  8044 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:51:32.879  1037  8027 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:51:32.879  1037  8027 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:32.879  1037  8027 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:32.879  1037  8027 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-27 11:51:32.879  1927  8044 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-27 11:51:32.881  1927  2323 W WfdsService: DefaultState - msg [9441285] is not handled
07-27 11:51:32.881  1037  1522 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:32.881  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:32.881  1037  1522 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:32.881  1037  1522 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:32.881  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:32.881  1037  1522 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:32.881  1037  1037 E WifiServerServiceExt: No p2p device connected
,07-27 11:51:32.904  8025  8025 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-27 11:51:32.908  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:51:32.918  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:32.920  1037  1890 I ActivityManager: Killing 7127:com.lge.drmservice/u0a62 (adj 15): empty #17
07-27 11:51:32.974  1037  1766 W libprocessgroup: failed to open /acct/uid_10062/pid_7127/cgroup.procs: No such file or directory
,07-27 11:51:33.024  8025  8025 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-27 11:51:33.034  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:51:33.044  8004  8049 W FormManager: Network not available. Please check & try again.
07-27 11:51:33.047  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:33.059  8004  8050 V FormManager: Network unavailable.
,07-27 11:51:33.066  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-27 11:51:33.067  4297  4297 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 11:51:33.067  8004  8050 V FormManager: Network unavailable.
07-27 11:51:33.069  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-27 11:51:33.072  4297  4297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-27 11:51:33.084  4297  8051 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-27 11:51:33.087  4297  8052 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,07-27 11:51:33.087  4297  8052 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,07-27 11:51:33.134  1037  1872 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8053 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,07-27 11:51:33.268  8053  8053 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-27 11:51:33.268  8053  8053 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,07-27 11:51:33.279  8053  8053 V [BNRBootReceiver]: Boot Receiver Return
,07-27 11:51:33.285  8053  8053 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,07-27 11:51:33.323  1037  8027 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,07-27 11:51:33.324  1037  8027 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,07-27 11:51:33.324  7985  7985 E wpa_supplicant: USIM:  scard_init function
07-27 11:51:33.324  1037  8027 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
07-27 11:51:33.324  1037  8027 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
,07-27 11:51:33.324  1037  8027 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
07-27 11:51:33.325  7985  7985 I wpa_supplicant: Trying to associate with SSID 'NG700'
07-27 11:51:33.326  1037  1523 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-27 11:51:33.333  1037  8027 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
07-27 11:51:33.333  1037  8027 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,07-27 11:51:33.337  1037  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-27 11:51:33.338  1037  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-27 11:51:33.340  1037  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
07-27 11:51:33.340  1037  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
07-27 11:51:33.342  1037  1641 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8071 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-27 11:51:33.344  1037  1641 I ActivityManager: Killing 7144:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
07-27 11:51:33.383  1037  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=321211  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,07-27 11:51:33.387  1037  1060 W libprocessgroup: failed to open /acct/uid_10085/pid_7144/cgroup.procs: No such file or directory
07-27 11:51:33.390  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=321218  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
07-27 11:51:33.391  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:33.391  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:51:33.392  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:33.392  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:33.392  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-27 11:51:33.393  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:33.395  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:33.395  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:51:33.397  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:33.397  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:33.397  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-27 11:51:33.397  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:33.398  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:51:33.398  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATING
07-27 11:51:33.409  8071  8071 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-27 11:51:33.431  8071  8071 D PluginManager: init()
,07-27 11:51:33.440  7985  7985 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
07-27 11:51:33.441  1037  8027 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
07-27 11:51:33.441  1037  8027 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
07-27 11:51:33.442  1037  8027 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
07-27 11:51:33.442  1037  8027 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
07-27 11:51:33.442  1037  8027 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 11:51:33.442  1037  8027 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 11:51:33.447  1037  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=321275  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,07-27 11:51:33.449  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=321276  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-27 11:51:33.450  1037  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=321278
07-27 11:51:33.452  1037  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=321280
07-27 11:51:33.452  7985  7985 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 11:51:33.452  7985  7985 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-27 11:51:33.453  1037  8027 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 11:51:33.453  1037  8027 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 11:51:33.454  1037  8027 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
07-27 11:51:33.454  1037  8027 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 11:51:33.454  1037  8027 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 11:51:33.454  1037  8027 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
07-27 11:51:33.454  1037  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=321282
07-27 11:51:33.454  1037  8027 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-27 11:51:33.454  1037  8027 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-27 11:51:33.455  1037  8027 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 11:51:33.455  1037  8027 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 11:51:33.455  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=321283
07-27 11:51:33.455  1037  1120 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-27 11:51:33.456  1037  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=321284
07-27 11:51:33.458  1037  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=321286  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,07-27 11:51:33.463  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:33.463  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:51:33.464  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:33.464  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:33.464  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-27 11:51:33.464  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:33.468  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:33.468  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:33.468  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
07-27 11:51:33.468  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=321296  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-27 11:51:33.468  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:51:33.469  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATED
07-27 11:51:33.469  1037  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=321297  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-27 11:51:33.470  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=321298  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-27 11:51:33.470  1037  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=321299
07-27 11:51:33.471  1037  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=321299
07-27 11:51:33.471  1037  1523 D WifiNative-wlan0: doString: [STATUS]
,07-27 11:51:33.472  1037  8027 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-27 11:51:33.472  1037  8027 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-27 11:51:33.473  1037  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-27 11:51:33.475  1037  1523 I WifiServiceExtension: setVHTCapabilityType  : false
07-27 11:51:33.479  1037  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
07-27 11:51:33.479  1037  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
07-27 11:51:33.485  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:33.485  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:51:33.486  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:33.486  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:33.486  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-27 11:51:33.487  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:33.487  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:33.487  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:33.487  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,07-27 11:51:33.489  1037  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
07-27 11:51:33.490  1037  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 11:51:33.490  1037  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-27 11:51:33.490  1037  1530 D ConnectivityService: Got NetworkAgent Messenger
07-27 11:51:33.490  1037  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-27 11:51:33.490  1037  1530 D ConnectivityService: NetworkAgent connected
07-27 11:51:33.490  1037  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-27 11:51:33.490  1037  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-27 11:51:33.492  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:33.492  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:51:33.492  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:33.494  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:33.494  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:51:33.494  1037  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-27 11:51:33.494  1037  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 11:51:33.494  1037  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-27 11:51:33.494  1037  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-27 11:51:33.495  1037  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-27 11:51:33.495  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:33.498  1037  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-27 11:51:33.499   332   895 D CommandListener: Setting iface cfg
07-27 11:51:33.502  1037  1523 E WifiStateMachine: Start Dhcp Watchdog 3
,07-27 11:51:33.502  1037  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=321330  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 11:51:33.504  1037  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=321332  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 11:51:33.505  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=321333  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 11:51:33.505  1037  8089 D DhcpStateMachine: StoppedState
07-27 11:51:33.505  1037  8089 D DhcpStateMachine: StoppedState{ when=-4ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:33.505  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:51:33.505  1037  8089 D DhcpStateMachine: WaitBeforeStartState
07-27 11:51:33.506  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:51:33.506  1037  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:51:33.506  1037  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:51:33.507  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:51:33.510  1037  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-27 11:51:33.511  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:51:33.511  1037  1037 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
07-27 11:51:33.512  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:51:33.512  1037  1037 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
07-27 11:51:33.512  1037  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=321340  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 11:51:33.513  1037  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=321341  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-27 11:51:33.514  1037  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=321341  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,07-27 11:51:33.515  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14021] from screen [on:0 period:734278283] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-27 11:51:33.516  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:734278284] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-27 11:51:33.516  1037  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-27 11:51:33.519  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:33.520  1037  1530 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
07-27 11:51:33.520  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:33.520  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:33.521  1037  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:33.521  1037  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,07-27 11:51:33.522  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:33.522  1037  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:33.522  1037  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
07-27 11:51:33.523  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:51:33.523  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-27 11:51:33.523  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=146,0,0
07-27 11:51:33.524  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=146,0,0
07-27 11:51:33.524  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
07-27 11:51:33.524  7985  7985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
07-27 11:51:33.525  1037  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
07-27 11:51:33.525  1037  1523 D WifiNative-wlan0: doBoolean: SET ps 0
07-27 11:51:33.525  1037  1523 D WifiNative-wlan0: SET ps 0: returned true
07-27 11:51:33.525  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
07-27 11:51:33.525  7985  7985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
07-27 11:51:33.526  1037  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
07-27 11:51:33.526  1037  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@23a7c244 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:33.526  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@23a7c244 target=com.android.internal.util.StateMachine$SmHandler }
,07-27 11:51:33.527  1037  8089 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:33.528  1037  8089 D DhcpStateMachine: DHCP Start wake lock is acquired.
,07-27 11:51:33.529  1037  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
07-27 11:51:33.529  1037  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-27 11:51:33.529  1037  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-27 11:51:33.530   332   895 D CommandListener: Setting iface cfg
07-27 11:51:33.530   332   895 D CommandListener: Trying to bring up wlan0
07-27 11:51:33.531  1037  1523 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
07-27 11:51:33.532  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 11:51:33.532  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-27 11:51:33.532  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:33.532  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:33.533  1037  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:33.533  1037  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:33.533  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:33.534  1037  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-27 11:51:33.534  1037  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
07-27 11:51:33.535  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-27 11:51:33.535  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-27 11:51:33.535  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-27 11:51:33.535  1037  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:33.535  1037  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:33.535  7985  7985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-27 11:51:33.536  1037  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-27 11:51:33.536  1037  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-27 11:51:33.536  7985  7985 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
07-27 11:51:33.536  1037  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
07-27 11:51:33.536  1037  1523 D WifiNative-wlan0: doBoolean: SET ps 1
07-27 11:51:33.553  1037  1523 D WifiNative-wlan0: SET ps 1: returned true
07-27 11:51:33.553  1037  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
07-27 11:51:33.554  1037  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,07-27 11:51:33.554  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-27 11:51:33.554  1037  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-27 11:51:33.555  1037  1530 D ConnectivityService: ignoring duplicate network state non-change
07-27 11:51:33.558  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:33.558  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 11:51:33.559  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:33.560  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 11:51:33.560  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:33.560  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-27 11:51:33.562  1037  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-27 11:51:33.563  1037  1530 D ConnectivityService: Adding iface wlan0 to network 102
07-27 11:51:33.563  1037  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-27 11:51:33.573  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:33.573  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:33.573  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-27 11:51:33.574  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-27 11:51:33.575  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 1
07-27 11:51:33.580  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:33.581  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-27 11:51:33.582  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:33.590  1037  1530 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-27 11:51:33.590  1037  1530 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
07-27 11:51:33.590  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:33.590  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-27 11:51:33.590  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:33.591  1037  1530 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
07-27 11:51:33.592   332   895 E Netd    : netlink response contains error (File exists)
07-27 11:51:33.592  1037  1530 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
07-27 11:51:33.592  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:33.592  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:33.593  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-27 11:51:33.593  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-27 11:51:33.593  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:33.593  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:33.593  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,07-27 11:51:33.595  1037  1530 D ConnectivityService: addLocalRoutetoDefaultNetwork
07-27 11:51:33.595  1037  1530 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
07-27 11:51:33.595  1037  1530 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
07-27 11:51:33.596  1037  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-27 11:51:33.596  1037  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
07-27 11:51:33.596  1037  1530 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
07-27 11:51:33.596  1037  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
07-27 11:51:33.596  1037  8088 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:33.596  1037  8088 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
07-27 11:51:33.596  1037  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:51:33.596  1037  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,07-27 11:51:33.596  1037  8088 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:33.596  1037  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-27 11:51:33.596  1037  8088 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-27 11:51:33.597  1037  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:33.597  1037  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
07-27 11:51:33.597  1037  1530 D ConnectivityService: currentScore = 0, newScore = 20
07-27 11:51:33.597  1037  1530 D ConnectivityService:    accepting network in place of null
07-27 11:51:33.597  1037  1530 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:33.598  1037  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:33.598  1037  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:51:33.599  1837  1837 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:33.599   332  8093 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
07-27 11:51:33.599  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-27 11:51:33.600  1037  1530 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-27 11:51:33.600  1037  1530 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
07-27 11:51:33.601  1037  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-27 11:51:33.603  1037  1037 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
07-27 11:51:33.603  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-27 11:51:33.603  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-27 11:51:33.603  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-27 11:51:33.604  1037  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:33.604  1037  1530 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
07-27 11:51:33.604  1037  1530 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[,], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
07-27 11:51:33.605  1037  1530 D ConnectivityService: validation of new default Network = false
07-27 11:51:33.605  1037  1530 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
07-27 11:51:33.605  1037  1530 D DSQN    : enableDataServiceNotify 
07-27 11:51:33.605  1037  1530 D DSQN    : start dsqn bin
,07-27 11:51:33.613  1037  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
07-27 11:51:33.613  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:33.613  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:51:33.614  1037  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:51:33.604  8094  8094 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:51:33.604  8094  8094 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:51:33.614  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:33.614  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-27 11:51:33.615  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:33.616  1587  2056 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-27 11:51:33.626  8094  8094 E DSQN    : DSQN ssw
07-27 11:51:33.626  1037  1521 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,07-27 11:51:33.636  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-27 11:51:33.637  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-27 11:51:33.638  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:33.650   332  8093 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,07-27 11:51:33.683   332  8093 D libc-netbsd: res_queryN name = clients3.google.com succeed
,07-27 11:51:33.721   332   894 D LGDataListener: argv[0]=dsqncommand
07-27 11:51:33.721   332   894 D LGDataListener: argv[1]=wlan0
,07-27 11:51:33.721   332   894 D LGDataListener: argv[2]=1
,07-27 11:51:33.721   332   894 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
07-27 11:51:33.723  1037  1118 D DSQN    : DSQM DsqnNotification wlan0  1
07-27 11:51:33.723  1037  1118 D DSQN    : start to monitor internet connection
07-27 11:51:33.732  1037  8089 D DhcpStateMachine: DHCPV4 request on wlan0
07-27 11:51:33.733  1037  8089 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
07-27 11:51:33.733  1037  8089 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,07-27 11:51:33.734  8100  8100 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:51:33.734  8100  8100 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6839 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-27 11:51:33.745  8100  8100 I dhcpcd  : version 5.5.6 starting
07-27 11:51:33.747  8100  8100 E dhcpcd  : get_duid: m
07-27 11:51:33.747  8100  8100 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
07-27 11:51:33.747  8100  8100 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
07-27 11:51:33.760  1037  8088 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jul 2016 09:51:33 GMT], X-Android-Received-Millis=[1469613093760], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1469613093720]}
07-27 11:51:33.760  1037  8088 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-27 11:51:33.760  1037  8088 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
07-27 11:51:33.761  1037  1530 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
07-27 11:51:33.761  1037  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
07-27 11:51:33.761  1037  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:51:33.761  1037  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:51:33.761  1037  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-27 11:51:33.761  1037  1530 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
07-27 11:51:33.761  1037  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
07-27 11:51:33.761  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:33.761  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:51:33.761  1037  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:51:33.762  1037  1530 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:33.762  1037  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-27 11:51:33.764  1037  1523 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:33.765  1037  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:51:33.765  1587  2056 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-27 11:51:33.765  1837  1837 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:33.765  1837  1837 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,07-27 11:51:33.785  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-27 11:51:33.786  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:33.787  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-27 11:51:33.835  6735  6792 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 873)
07-27 11:51:33.835  6735  6792 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 873)
07-27 11:51:33.836  6735  6792 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 873)
,07-27 11:51:33.836  6735  6792 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 873)
07-27 11:51:33.839  8100  8100 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-27 11:51:33.839  8100  8100 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-27 11:51:33.839  8100  8100 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-27 11:51:33.840  8100  8100 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
07-27 11:51:33.841  8100  8100 D dhcpcd  : wlan0: sending REQUEST (xid 0x4daf575), next in 4.46 seconds
07-27 11:51:33.846  6735  6792 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 878)
07-27 11:51:33.846  6735  6792 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 878)
07-27 11:51:33.846  6735  6792 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 878)
07-27 11:51:33.849  6735  6792 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 879)
,07-27 11:51:33.853  6735  6792 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 881)
07-27 11:51:33.860  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:51:33.860  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e25cc7e added. We now have 2 listener(s)
07-27 11:51:33.860  1037  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-27 11:51:33.864  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 11:51:33.864  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:51:33.864  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:51:33.864  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:33.864  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1daa5df added. We now have 9 listener(s)
07-27 11:51:33.864  6735  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 11:51:33.865  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 11:51:33.867  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:51:33.871  8071  8071 W ExternalStrings: load override strings
07-27 11:51:33.871  8071  8071 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
07-27 11:51:33.871  8071  8071 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
07-27 11:51:33.871  8071  8071 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
07-27 11:51:33.871  8071  8071 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
07-27 11:51:33.871  8071  8071 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
07-27 11:51:33.871  8071  8071 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
07-27 11:51:33.871  8071  8071 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
07-27 11:51:33.871  8071  8071 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
07-27 11:51:33.871  8071  8071 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
07-27 11:51:33.871  8071  8071 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
07-27 11:51:33.871  8071  8071 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
07-27 11:51:33.871  8071  8071 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:51:33.871  8071  8071 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
07-27 11:51:33.871  8071  8071 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 11:51:33.871  8071  8071 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:51:33.871  8071  8071 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 11:51:33.871  8071  8071 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 11:51:33.871  8071  8071 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 11:51:33.873  6735  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:51:33.873  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:33.873  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:33.873  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:33.873  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:33.873  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:33.873  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:51:33.873  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:51:33.874  8071  8071 D StatusProvider: onCreate
,07-27 11:51:33.875  6735  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:33.875  6735  6792 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:51:33.876  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:51:33.876  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@137044f5 added. We now have 3 listener(s)
07-27 11:51:33.876  1037  1890 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:33.878  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:33.879  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:33.879  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 11:51:33.879  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:51:33.879  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:51:33.879  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:33.880  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64e328a added. We now have 10 listener(s)
07-27 11:51:33.880  6735  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:51:33.880  6735  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:33.880  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:33.880  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:33.880  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:33.880  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:33.880  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:51:33.880  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:51:33.880  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e25cc7e removed from the list
07-27 11:51:33.880  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:33.880  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1daa5df removed from the list
07-27 11:51:33.880  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:33.880  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:33.881  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:33.881  6735  6792 D org.,thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:33.883  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:33.883  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:33.883  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:33.883  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1daa5df not in the list
07-27 11:51:33.883  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:33.883  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:33.884  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:33.884  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:33.884  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:33.884  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64e328a removed from the list
07-27 11:51:33.884  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:33.884  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:33.884  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:33.884  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:51:33.884  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@137044f5 removed from the list
07-27 11:51:33.885  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:51:33.885  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@236dc0fb added. We now have 2 listener(s)
07-27 11:51:33.885  1037  1872 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-27 11:51:33.888  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 11:51:33.888  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:51:33.888  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:51:33.888  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:33.888  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a9d518 added. We now have 9 listener(s)
07-27 11:51:33.888  6735  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:51:33.889  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 11:51:33.891  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:51:33.895  6735  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:51:33.895  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:33.895  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:33.895  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:33.895  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:33.895  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:33.895  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:51:33.895  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:51:33.897  6735  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:33.897  6735  6792 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:51:33.897  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:51:33.897  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e4ed56 added. We now have 3 listener(s)
07-27 11:51:33.897  1037  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:33.898  8100  8100 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,07-27 11:51:33.900  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:33.901  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 11:51:33.901  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:51:33.901  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:51:33.901  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:33.901  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34d71d7 added. We now have 10 listener(s)
07-27 11:51:33.901  6735  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:51:33.901  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:51:33.901  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 11:51:33.901  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:51:33.901  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 11:51:33.901  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:33.904  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-27 11:51:33.906  1037  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:33.912  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-27 11:51:33.913  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-27 11:51:33.914  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 11:51:33.915  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:51:33.917  6735  6792 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 11:51:33.917  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:33.917  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:33.919  6735  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:33.919  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:33.919  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:33.920  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:33.920  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:33.920  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:51:33.920  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:51:33.920  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@236dc0fb removed from the list
07-27 11:51:33.920  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:33.920  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a9d518 removed from the list
07-27 11:51:33.920  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:33.920  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:33.920  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:33.920  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:33.921  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:33.921  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:33.921  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:33.921  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a9d518 not in the list
07-27 11:51:33.921  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:33.922  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:33.922  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-27 11:51:33.922  6735  6792 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:33.922  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:33.922  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:33.922  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:33.922  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34d71d7 removed from the list
07-27 11:51:33.922  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:33.922  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:33.923  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:33.923  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:51:33.923  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e4ed56 removed from the list
07-27 11:51:33.923  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:51:33.923  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@325a88e2 added. We now have 2 listener(s)
07-27 11:51:33.923  1037  1061 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-27 11:51:33.926  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 11:51:33.926  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:51:33.926  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:51:33.926  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:33.926  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70d5473 added. We now have 9 listener(s)
07-27 11:51:33.926  6735  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:51:33.926  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 11:51:33.927  8100  8100 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
07-27 11:51:33.927  8100  8100 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
07-27 11:51:33.928  8100  8100 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
07-27 11:51:33.928  8100  8100 D dhcpcd  : wlan0: adding default route via 192.168.1.1
07-27 11:51:33.928  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 11:51:33.929  8100  8100 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-27 11:51:33.929  8100  8100 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-27 11:51:33.929  8100  8100 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-27 11:51:33.929  8100  8100 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
07-27 11:51:33.930  6735  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:51:33.930  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:33.930  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:33.930  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:33.930  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:33.930  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:33.930  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:51:33.930  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:51:33.933  6735  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:33.933  6735  6792 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:51:33.933  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:51:33.933  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e6e7a9 added. We now have 3 listener(s)
07-27 11:51:33.933  1037  1061 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:33.935  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:33.936  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:33.940  8071  8071 V Signer  : override build config not found
07-27 11:51:33.940  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,07-27 11:51:33.940  8071  8071 D Signer  : value of property debug is false
07-27 11:51:33.941  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:51:33.941  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:51:33.941  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:33.941  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@299c512e added. We now have 10 listener(s)
07-27 11:51:33.941  6735  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:51:33.941  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:51:33.943  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:51:33.944  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 11:51:33.944  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:51:33.944  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 11:51:33.949  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-27 11:51:33.949  1037  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:33.959  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-27 11:51:33.959  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-27 11:51:33.961  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 11:51:33.961  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:51:33.962  6735  6792 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 11:51:33.963  6735  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:33.963  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:33.963  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:33.963  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:33.963  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:33.963  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:51:33.963  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:51:33.963  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@325a88e2 removed from the list
07-27 11:51:33.963  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:33.963  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70d5473 removed from the list
07-27 11:51:33.963  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:33.963  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:33.964  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:33.964  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:33.965  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:33.965  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:33.965  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:33.965  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70d5473 not in the list
07-27 11:51:33.965  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:33.965  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:33.966  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:33.966  6735  6792 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:33.966  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:33.966  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:33.966  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:33.966  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@299c512e removed from the list
0,7-27 11:51:33.966  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:33.966  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:33.966  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:33.966  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:51:33.966  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e6e7a9 removed from the list
07-27 11:51:33.967  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:51:33.967  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19d5565 added. We now have 2 listener(s)
07-27 11:51:33.967  1037  1766 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:33.969  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 11:51:33.969  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:51:33.969  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:51:33.969  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:33.969  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1120523a added. We now have 9 listener(s)
07-27 11:51:33.969  6735  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 11:51:33.970  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 11:51:33.972  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 11:51:33.974  6735  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:51:33.974  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:33.974  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:33.974  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:33.974  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:33.974  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:33.974  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:51:33.974  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:51:33.978  6735  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:33.978  6735  6792 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:51:33.978  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:51:33.978  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@848b448 added. We now have 3 listener(s)
07-27 11:51:33.978  1037  1766 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:33.980  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:33.981  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:33.982  8071  8071 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
07-27 11:51:33.982  8071  8071 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
07-27 11:51:33.983  8071  8071 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
07-27 11:51:33.983  8071  8071 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
07-27 11:51:33.983  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 11:51:33.983  8071  8071 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
07-27 11:51:33.983  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:51:33.983  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:51:33.984  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:33.984  8071  8071 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
07-27 11:51:33.984  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2592e2e1 added. We now have 10 listener(s)
07-27 11:51:33.984  6735  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:51:33.984  8071  8071 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
07-27 11:51:33.984  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:51:33.984  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, ,start advertiser: false
07-27 11:51:33.984  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:51:33.984  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 11:51:33.984  8071  8071 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
07-27 11:51:33.984  8071  8071 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
07-27 11:51:33.985  8071  8071 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
07-27 11:51:33.985  8071  8071 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
07-27 11:51:33.985  8071  8071 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
07-27 11:51:33.985  8071  8071 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
07-27 11:51:33.987  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-27 11:51:33.988  1037  1061 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:33.991  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-27 11:51:33.991  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-27 11:51:33.992  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 11:51:33.993  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:51:33.994  6735  6792 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 11:51:33.996  6735  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:33.996  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:33.996  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:33.996  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:33.996  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:33.996  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:51:33.996  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:51:33.996  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19d5565 removed from the list
07-27 11:51:33.996  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:33.996  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1120523a removed from the list
07-27 11:51:33.996  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:33.996  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:33.997  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:33.997  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:33.998  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:33.998  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:33.998  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:33.998  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1120523a not in the list
07-27 11:51:33.998  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:33.998  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:33.999  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:33.999  6735  6792 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:33.,999  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:33.999  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:33.999  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:33.999  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2592e2e1 removed from the list
07-27 11:51:33.999  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:33.999  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:33.999  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:33.999  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:51:33.999  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@848b448 removed from the list
07-27 11:51:34.000  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:51:34.000  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e58ccf4 added. We now have 2 listener(s)
07-27 11:51:34.000  1037  1944 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:34.001  8071  8071 V LGMDMManager: Create singleton instance
07-27 11:51:34.002  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 11:51:34.002  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:51:34.002  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:51:34.002  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:34.002  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32f9cc1d added. We now have 9 listener(s)
07-27 11:51:34.002  6735  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:51:34.003  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 11:51:34.005  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:51:34.008  6735  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:51:34.008  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:34.008  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:34.008  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:34.008  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:34.008  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:34.008  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:51:34.008  6735  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:51:34.009  6735  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:34.009  6735  6792 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:51:34.011  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:34.011  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:51:34.011  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25744063 added. We now have 3 listener(s)
07-27 11:51:34.012  1037  1871 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 11:51:34.012  6735  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:34.014  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-27 11:51:34.014  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-27 11:51:34.014  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:51:34.014  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:34.014  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dafc460 added. We now have 10 listener(s)
07-27 11:51:34.014  6735  6792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:51:34.015  6735  6792 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:34.015  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:34.015  6735  6792 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:34.015  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:34.015  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:34.015  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:51:34.015  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:51:34.015  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e58ccf4 removed from the list
07-27 11:51:34.015  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:34.015  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32f9cc1d removed from the list
07-27 11:51:34.015  6735  6792 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:34.015  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:34.015  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:34.015  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:34.016  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:34.016  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:34.016  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:34.016  6735  6792 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32f9cc1d not in the list
07-27 11:51:34.016  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:34.016  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 11:51:34.018  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:34.018  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:34.018  6735  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:34.018  6735  6792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dafc460 removed from the list
07-27 11:51:34.018  6735  6792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:34.018  6735  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:34.018  6735  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:34.018  6735  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:51:34.018  6735  6792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25744063 removed from the list
07-27 11:51:34.018  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-27 11:51:34.019  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-27 11:51:34.019  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-27 11:51:34.019  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-27 11:51:34.019  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-27 11:51:34.019  6735  6792 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:34.025  6735  8116 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 887, name: My test thread name)
07-27 11:51:34.025  6735  8116 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 887, thread name: My test thread name)
07-27 11:51:34.026  6735  8116 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 887, name: My test thread name)
07-27 11:51:34.028  6735  8117 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 889, name: My test thread name)
07-27 11:51:34.028  6735  8117 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 889, thread name: My test thread name)
07-27 11:51:34.028  6735  8117 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 889, name: My test thread name)
,07-27 11:51:34.030  6735  6792 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 84
07-27 11:51:34.030  6735  6792 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 84
07-27 11:51:34.030  6735  6792 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-27 11:51:34.030  6735  6792 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-27 11:51:34.030  6735  6792 D com.test.thalitest.ThaliTestRunner: Total duration: 22905 ms
07-27 11:51:34.031  6735  6792 I jxcore-log: Total number of executed tests:  84
07-27 11:51:34.031  6735  6792 I jxcore-log: 
07-27 11:51:34.032  6735  6792 I jxcore-log: Number of passed tests:  84
07-27 11:51:34.032  6735  6792 I jxcore-log: 
07-27 11:51:34.032  6735  6792 I jxcore-log: Number of failed tests:  0
07-27 11:51:34.032  6735  6792 I jxcore-log: 
07-27 11:51:34.033  6735  6792 I jxcore-log: Number of ignored tests:  0
07-27 11:51:34.033  6735  6792 I jxcore-log: 
07-27 11:51:34.033  6735  6792 I jxcore-log: Total duration:  22905
07-27 11:51:34.033  6735  6792 I jxcore-log: 
07-27 11:51:34.033  6735  6792 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
07-27 11:51:34.033  6735  6792 I jxcore-log: 
07-27 11:51:34.035  6735  6792 I jxcore-log: Unit Test app is loaded
07-27 11:51:34.035  6735  6792 I jxcore-log: 
07-27 11:51:34.042  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:51:34.042  6735  6792 I jxcore-log: 
07-27 11:51:34.045  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:51:34.045  6735  6792 I jxcore-log: 
,07-27 11:51:34.046  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:51:34.046  6735  6792 I jxcore-log: 
07-27 11:51:34.047  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:51:34.047  6735  6792 I jxcore-log: 
07-27 11:51:34.048  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:51:34.048  6735  6792 I jxcore-log: 
07-27 11:51:34.048  6735  6735 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
07-27 11:51:34.049  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-27 11:51:34.049  6735  6792 I jxcore-log: 
07-27 11:51:34.051  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-27 11:51:34.051  6735  6792 I jxcore-log: 
07-27 11:51:34.052  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 11:51:34.052  6735  6792 I jxcore-log: 
07-27 11:51:34.053  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 11:51:34.053  6735  6792 I jxcore-log: 
07-27 11:51:34.053  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 11:51:34.053  6735  6792 I jxcore-log: 
07-27 11:51:34.054  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 11:51:34.054  6735  6792 I jxcore-log: 
07-27 11:51:34.055  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 11:51:34.055  6735  6792 I jxcore-log: 
07-27 11:51:34.056  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 11:51:34.056  6735  6792 I jxcore-log: 
07-27 11:51:34.057  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 11:51:34.057  6735  6792 I jxcore-log: 
07-27 11:51:34.057  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 11:51:34.057  6735  6792 I jxcore-log: 
07-27 11:51:34.058  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 11:51:34.058  6735  6792 I jxcore-log: 
07-27 11:51:34.058  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 11:51:34.058  6735  6792 I jxcore-log: 
07-27 11:51:34.059  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 11:51:34.059  6735  6792 I jxcore-log: 
07-27 11:51:34.059  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 11:51:34.059  6735  6792 I jxcore-log: 
07-27 11:51:34.060  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 11:51:34.060  6735  6792 I jxcore-log: 
07-27 11:51:34.060  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 11:51:34.060  6735  6792 I jxcore-log: 
07-27 11:51:34.061  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 11:51:34.061  6735  6792 I jxcore-log: 
07-27 11:51:34.062  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:51:34.062  6735  6792 I jxcore-log: 
07-27 11:51:34.062  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:51:34.062  6735  6792 I jxcore-log: 
07-27 11:51:34.063  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:51:34.063  6735  6792 I jxcore-log: 
07-27 11:51:34.064  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:51:34.064  6735  6792 I jxcore-log: 
07-27 11:51:34.064  6735  6792 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:51:34.064  6735  6792 I jxcore-log: 
,07-27 11:51:34.067  6735  6792 I jxcore-log: My device name is: LGE-LG-D855
07-27 11:51:34.067  6735  6792 I jxcore-log: 
07-27 11:51:34.087  8071  8071 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,07-27 11:51:34.139  1037  8089 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,07-27 11:51:34.140  1037  8089 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
07-27 11:51:34.140  1037  8089 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-27 11:51:34.140  1037  8089 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
07-27 11:51:34.140  1037  8089 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
07-27 11:51:34.140  1037  8089 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-27 11:51:34.140  1037  8089 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
07-27 11:51:34.140  1037  8089 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
07-27 11:51:34.140  1037  8089 D DhcpStateMachine: RunningState
07-27 11:51:34.149  8071  8133 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,07-27 11:51:34.151  8071  8071 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:51:34.175  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:51:34.208  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-27 11:51:34.237  1037  1890 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8136 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
07-27 11:51:34.237  1037  1890 I ActivityManager: Killing 7180:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
07-27 11:51:34.253  8131  8131 D AndroidRuntime: 
07-27 11:51:34.253  8131  8131 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-27 11:51:34.255  8131  8131 D AndroidRuntime: CheckJNI is OFF
,07-27 11:51:34.259  8071  8130 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
07-27 11:51:34.356  8131  8131 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-27 11:51:34.531  1037  1962 W libprocessgroup: failed to open /acct/uid_10093/pid_7180/cgroup.procs: No such file or directory
,07-27 11:51:34.540  1037  1126 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
07-27 11:51:34.541  1037  1523 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-27 11:51:34.541  1037  1126 I ActivityManager: Killing 6735:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
07-27 11:51:34.542  1037  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-27 11:51:34.543  1037  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-27 11:51:34.544  1037  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-27 11:51:34.545  1037  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-27 11:51:34.547  1037  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,07-27 11:51:34.549  1037  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
07-27 11:51:34.550  1037  1530 D ConnectivityService: identical MTU - not setting
07-27 11:51:34.550  1037  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-27 11:51:34.550  1037  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
07-27 11:51:34.551  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:34.551  1037  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:51:34.552  1037  1530 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-27 11:51:34.557  1587  2056 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295,
07-27 11:51:34.563  8136  8136 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 11:51:34.577  1037  1871 I WindowState: WIN DEATH: Window{22b8ba87 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,07-27 11:51:34.578  1037  1528 D WifiService: Client connection lost with reason: 4
,07-27 11:51:34.586  1037  1871 D InputDispatcher: Window went away: Window{22b8ba87 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-27 11:51:34.764  1037  1126 I ActivityManager:   Force finishing activity ActivityRecord{329822c0 u0 com.test.thalitest/.MainActivity t40}
,07-27 11:51:34.830   351   361 E GBMv2   : DFP En is all cleared set to be enabled
,07-27 11:51:34.860  1037  1111 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,07-27 11:51:34.868  1037  1111 I ActivityManager:   Force finishing activity ActivityRecord{329822c0 u0 com.test.thalitest/.MainActivity t40 f}
07-27 11:51:34.868  1037  1111 W ActivityManager: Duplicate finish request for ActivityRecord{329822c0 u0 com.test.thalitest/.MainActivity t40 f}
07-27 11:51:34.871  1927  2922 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
07-27 11:51:34.871  1037  1944 W ActivityManager: Spurious death for ProcessRecord{b19b2a4 6735:com.test.thalitest/u0a118}, curProc for 6735: null
07-27 11:51:34.871  1927  2922 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2e2d5863 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
07-27 11:51:34.872  2017  2017 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,07-27 11:51:34.874  2017  2017 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
07-27 11:51:34.875  1927  1943 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
07-27 11:51:34.876  1927  1943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{39cefc60 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
07-27 11:51:34.877  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
07-27 11:51:34.878  2017  2110 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
07-27 11:51:34.882  1587  1587 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
07-27 11:51:34.889  2455  2583 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-27 11:51:34.894  3806  3806 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
07-27 11:51:34.894  1980  1980 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
07-27 11:51:34.899  7646  7646 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
07-27 11:51:34.899  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
07-27 11:51:34.904  1037  1424 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-27 11:51:34.916  8136  8136 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
07-27 11:51:34.954  4585  4585 I art     : Explicit concurrent mark sweep GC freed 8198(469KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 584us total 106.068ms
07-27 11:51:34.954  1037  1061 V SIM_STK : Menu title from STK is T-Mobile
,07-27 11:51:34.959  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
07-27 11:51:34.961  2017  2017 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
07-27 11:51:34.963  2017  2017 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
07-27 11:51:34.964  2017  2017 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
07-27 11:51:34.970  1891  1891 D ActionManagerService: notifyUserLog: 1000003
,07-27 11:51:34.973  4483  4483 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-27 11:51:34.973  4483  4483 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
07-27 11:51:34.973  4483  4483 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
07-27 11:51:34.973  3806  4477 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
07-27 11:51:34.973  4483  4483 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
07-27 11:51:34.973  4483  4483 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 11:51:34.973  4483  4483 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 11:51:34.973  4483  4483 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 11:51:34.973  4483  4483 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 11:51:34.973  4483  4483 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:51:34.973  4483  4483 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 11:51:34.973  4483  4483 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 11:51:34.973  4483  4483 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 11:51:35.001  1037  1037 D administrator: Handling package changes for user 0
07-27 11:51:35.002  1891  1891 D ActionManagerService: notifyUserLog: 1000004
07-27 11:51:35.002  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,07-27 11:51:35.004  3806  4477 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
07-27 11:51:35.004  3806  4474 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-27 11:51:35.008  1587  1650 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-27 11:51:35.008  1587  1650 D KeyguardModel: createShortcutInfo...
07-27 11:51:35.018  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
07-27 11:51:35.018  2017  2017 I GBoardWebViewUtils: , create_time: 1430832262123
07-27 11:51:35.018  2017  2017 I GBoardWebViewUtils: , expire_time: 0
07-27 11:51:35.018  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
07-27 11:51:35.018  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
07-27 11:51:35.018  2017  2017 I GBoardWebViewUtils: , display: false
07-27 11:51:35.018  2017  2017 I GBoardWebViewUtils: , animation: false }
07-27 11:51:35.018  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
07-27 11:51:35.018  2017  2017 I GBoardWebViewUtils: , create_time: 1430832262287
07-27 11:51:35.018  2017  2017 I GBoardWebViewUtils: , expire_time: 0
07-27 11:51:35.018  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
07-27 11:51:35.018  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
07-27 11:51:35.018  2017  2017 I GBoardWebViewUtils: , display: false
07-27 11:51:35.018  2017  2017 I GBoardWebViewUtils: , animation: false }
07-27 11:51:35.018  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1469186101390
07-27 11:51:35.018  2017  2017 I GBoardWebViewUtils: , create_time: 1469186101943
07-27 11:51:35.018  2017  2017 I GBoardWebViewUtils: , expire_time: 0
07-27 11:51:35.018  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1469186101390&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
07-27 11:51:35.018  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
07-27 11:51:35.018  2017  2017 I GBoardWebViewUtils: , display: false
07-27 11:51:35.018  2017  2017 I GBoardWebViewUtils: , animation: false }
07-27 11:51:35.019  1587  1587 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,07-27 11:51:35.022  1587  1650 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-27 11:51:35.022  1587  1650 D KeyguardModel: createShortcutInfo...
07-27 11:51:35.026  2017  8178 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,07-27 11:51:35.042  1587  1650 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
07-27 11:51:35.043  1587  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 11:51:35.043  1587  1650 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
07-27 11:51:35.044  1587  1650 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,07-27 11:51:35.052  8136  8136 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
07-27 11:51:35.053  1587  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 11:51:35.053  1587  1650 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-27 11:51:35.053  8136  8136 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
07-27 11:51:35.054  8136  8136 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
07-27 11:51:35.054  8136  8136 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
07-27 11:51:35.054  8136  8136 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
07-27 11:51:35.056  8136  8136 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
07-27 11:51:35.068  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-27 11:51:35.069  1587  1587 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
07-27 11:51:35.069  1587  1587 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
07-27 11:51:35.069  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
07-27 11:51:35.070  1587  1650 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-27 11:51:35.070  1587  1650 D KeyguardModel: createShortcutInfo...
07-27 11:51:35.073  8136  8136 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
07-27 11:51:35.079  1587  1650 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
07-27 11:51:35.079  1587  1650 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 11:51:35.081  1587  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 11:51:35.083  1587  1650 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-27 11:51:35.090  1854  1854 D SplitUIManager: split_name #11 / not available #0
07-27 11:51:35.090  1854  1854 D SplitUIService: removed split : 
07-27 11:51:35.091  1587  1650 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-27 11:51:35.091  1587  1650 D KeyguardModel: createShortcutInfo...
07-27 11:51:35.094  1037  1890 V SIM_STK : Menu title from STK is T-Mobile
07-27 11:51:35.094  1037  1890 V SIM_STK : Menu title from STK is T-Mobile
07-27 11:51:35.096  1587  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 11:51:35.096  1587  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-27 11:51:35.096  1587  1650 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-27 11:51:35.096  1587  1650 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,07-27 11:51:35.099  1037  1109 W InputMethodInfo: Duplicated subtype definition found: , voice
07-27 11:51:35.100  1587  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 11:51:35.100  1587  1650 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-27 11:51:35.103  1587  1650 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-27 11:51:35.103  1587  1650 D KeyguardModel: createShortcutInfo...
07-27 11:51:35.149  2017  2017 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
07-27 11:51:35.150  2017  2032 I art     : Background sticky concurrent mark sweep GC freed 2772(151KB) AllocSpace objects, 3(176KB) LOS objects, 0% free, 80MB/80MB, paused 12.486ms total 17.874ms
07-27 11:51:35.151  1037  1944 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
07-27 11:51:35.151  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
07-27 11:51:35.151  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-27 11:51:35.151  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-27 11:51:35.151  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-27 11:51:35.151  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-27 11:51:35.151  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-27 11:51:35.151  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-27 11:51:35.151  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-27 11:51:35.151  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-27 11:51:35.151  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-27 11:51:35.151  7646  7646 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-27 11:51:35.155  1037  1061 V SIM_STK : Menu title from STK is T-Mobile
07-27 11:51:35.155  1587  1587 D KeyguardModel: handleShortcutListChanged...
07-27 11:51:35.155  1587  1587 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,07-27 11:51:35.158  1587  1650 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-27 11:51:35.158  1587  1650 D KeyguardModel: createShortcutInfo...
07-27 11:51:35.160  1587  1650 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-27 11:51:35.160  1587  1650 D KeyguardModel: createShortcutInfo...
07-27 11:51:35.161  1587  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 11:51:35.161  1587  1650 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-27 11:51:35.167  8136  8136 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:51:35.169  8136  8136 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:51:35.170  1587  1650 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-27 11:51:35.170  1587  1650 D KeyguardModel: createShortcutInfo...
07-27 11:51:35.171  1587  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 11:51:35.171  1587  1650 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-27 11:51:35.171  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
07-27 11:51:35.171  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-27 11:51:35.172  1587  1650 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-27 11:51:35.172  1587  1650 D KeyguardModel: createShortcutInfo...
07-27 11:51:35.173  1587  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-27 11:51:35.173  1587  1650 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-27 11:51:35.174  1037  1037 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-27 11:51:35.175  1037  1561 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
07-27 11:51:35.176  1587  1650 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-27 11:51:35.176  1587  1650 D KeyguardModel: createShortcutInfo...
07-27 11:51:35.177  1037  1528 D WifiController: battery changed pluggedType: 2
07-27 11:51:35.177  1927  2081 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 11:51:35.177  1927  2081 D LEDHandler: Battery Level Remaining: 100%
07-27 11:51:35.177  1927  2081 D LEDHandler: Battery Temp: 291, mChargingStatus=5, mChargingStop=false
07-27 11:51:35.179  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:35.179  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:35.179  8136  8136 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-27 11:51:35.179  7646  7876 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 11:51:35.180  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
07-27 11:51:35.182  8136  8136 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
07-27 11:51:35.183  8053  8053 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-27 11:51:35.185  6803  6803 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
07-27 11:51:35.185  8136  8136 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
07-27 11:51:35.186  1854  1854 D SplitUIManager: split_name #11 / not available #0
07-27 11:51:35.186  1854  1854 I SplitUIService: split app #11
07-27 11:51:35.188  8071  8071 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:51:35.189  8071  8133 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-27 11:51:35.193  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:51:35.197  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:35.198  1587  1587 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 11:51:35.198  1587  1587 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 11:51:35.198  1587  1587 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
07-27 11:51:35.198  1587  1587 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 11:51:35.198  1587  1587 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 11:51:35.200  1587  1587 D KeyguardModel: handleShortcutListChanged...
07-27 11:51:35.201  1587  1587 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
07-27 11:51:35.203  8136  8136 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:51:35.203  8136  8136 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:51:35.204  8136  8136 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-27 11:51:35.207  8071  8071 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:51:35.208  8071  8133 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,07-27 11:51:35.217  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 11:51:35.221  8071  8130 D LgDataFeature: LgDataFeature() Constructor: none
07-27 11:51:35.221  8071  8130 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-27 11:51:35.233  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:35.241  8136  8136 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-27 11:51:35.243  8136  8136 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:51:35.243  8136  8136 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 11:51:35.246  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-27 11:51:35.246  6803  6803 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-27 11:51:35.246  6803  6803 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-27 11:51:35.246  6803  6803 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-27 11:51:35.247  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-27 11:51:35.249  6803  6803 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-27 11:51:35.249  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
07-27 11:51:35.249  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-27 11:51:35.249  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-27 11:51:35.249  6803  6803 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-27 11:51:35.249  6803  6803 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
07-27 11:51:35.250  6803  6803 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-27 11:51:35.252  8071  8071 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:51:35.252  8071  8133 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,07-27 11:51:35.258  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
07-27 11:51:35.258  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 11:51:35.260  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 11:51:35.262  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
07-27 11:51:35.263  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
07-27 11:51:35.264  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
07-27 11:51:35.265  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
07-27 11:51:35.265  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:35.273   345   456 I ThermalEngine: Thermal-Server: Thermal received msg from  override
07-27 11:51:35.274  3206  8188 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,07-27 11:51:35.282  1037  1121 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{370e52db u0 com.lge.launcher2/.Launcher t39} time:323124
07-27 11:51:35.283  8136  8136 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:51:35.283  8136  8136 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:51:35.283  8136  8136 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 11:51:35.284  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
07-27 11:51:35.284  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-27 11:51:35.288  2017  2167 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
07-27 11:51:35.289  2017  2167 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
07-27 11:51:35.290  8071  8071 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:51:35.290  8071  8133 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-27 11:51:35.297  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 11:51:35.300  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:35.301  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
07-27 11:51:35.302  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
07-27 11:51:35.302  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,07-27 11:51:35.310  2017  2017 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
07-27 11:51:35.310  2592  2592 D [Concierge]Service: onStartCommand(). Type : 8
07-27 11:51:35.311  2592  2592 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
07-27 11:51:35.313  2017  2017 D [Concierge]WidgetView: change position of spinner
07-27 11:51:35.315  2592  2592 D [Concierge]Service: Update widget ID : 11
07-27 11:51:35.315  8136  8136 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:51:35.316  2017  2017 I [Concierge]WidgetView: initWebView(). Time : 1469613095316
,07-27 11:51:35.316  8136  8136 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:51:35.316  8136  8136 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 11:51:35.317  2592  2592 D [Concierge]Service: onStartCommand(). Type : 0
07-27 11:51:35.318  8071  8071 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:51:35.318  8071  8133 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-27 11:51:35.322  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 11:51:35.325  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:35.340  8136  8136 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:51:35.340  8136  8136 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:51:35.340  8136  8136 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-27 11:51:35.341  2017  2017 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 533737563
07-27 11:51:35.341  2017  2017 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
07-27 11:51:35.342  2017  2017 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
07-27 11:51:35.342  8071  8071 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:51:35.343  8071  8133 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-27 11:51:35.344  2017  2017 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@cbefdb
07-27 11:51:35.344  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
07-27 11:51:35.345  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
07-27 11:51:35.345  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 11:51:35.346  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 11:51:35.350  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:35.351  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
07-27 11:51:35.351  2017  2017 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
07-27 11:51:35.351  2017  2017 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
07-27 11:51:35.352  2017  2017 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1469612799703, New one : 1469613095316
07-27 11:51:35.352  2017  2017 D [Concierge]WidgetView: Unregister all receivers
07-27 11:51:35.353  2017  2017 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,07-27 11:51:35.354  8136  8136 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:51:35.354  8136  8136 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:51:35.355  8136  8136 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 11:51:35.356  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 11:51:35.356  8071  8130 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
07-27 11:51:35.358  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
07-27 11:51:35.359  1037  1126 I art     : Explicit concurrent mark sweep GC freed 84332(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.012ms total 333.526ms
07-27 11:51:35.359  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
07-27 11:51:35.360  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
07-27 11:51:35.361  8071  8071 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:51:35.361  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
07-27 11:51:35.361  8071  8133 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-27 11:51:35.362  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
07-27 11:51:35.363  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 11:51:35.363  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 11:51:35.374  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:51:35.380  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:35.384  8136  8136 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:51:35.384  8136  8136 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,07-27 11:51:35.387  8136  8136 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 11:51:35.402  2017  2017 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,07-27 11:51:35.403  8131  8131 D AndroidRuntime: Shutting down VM
07-27 11:51:35.406  8071  8071 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:51:35.406  8071  8133 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-27 11:51:35.411  2017  2017 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
07-27 11:51:35.417  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,07-27 11:51:35.419  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-27 11:51:35.435  8071  8130 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,07-27 11:51:35.439  2017  2017 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@169f2c94 time:323282
07-27 11:51:35.442  8071  8130 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
07-27 11:51:35.442  8071  8130 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
07-27 11:51:35.443  8071  8130 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
07-27 11:51:35.443  8071  8130 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
07-27 11:51:35.443  8071  8130 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
07-27 11:51:35.445  8071  8130 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
07-27 11:51:35.446  8071  8130 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
07-27 11:51:35.447  1037  1109 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 11:51:35.447  1037  1126 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8192 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,07-27 11:51:35.452  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 11:51:35.458  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:35.462  8136  8136 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:51:35.462  8136  8136 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:51:35.462  8136  8136 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-27 11:51:35.465  8071  8071 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:51:35.466  8071  8133 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-27 11:51:35.466  1037  1109 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,07-27 11:51:35.468  8025  8025 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-27 11:51:35.471  8025  8025 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-27 11:51:35.473  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 11:51:35.476  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
07-27 11:51:35.476  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:35.481  8136  8136 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-27 11:51:35.481  8136  8136 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:51:35.482  8136  8136 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,07-27 11:51:35.483  8136  8136 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-27 11:51:35.483  8136  8136 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-27 11:51:35.485  1037  1908 I ActivityManager: Killing 7228:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
07-27 11:51:35.576  2017  2017 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
07-27 11:51:35.576  8071  8071 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-27 11:51:35.576  1037  1890 W libprocessgroup: failed to open /acct/uid_10005/pid_7228/cgroup.procs: No such file or directory
07-27 11:51:35.577  8071  8133 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,07-27 11:51:35.581  8025  8025 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-27 11:51:35.582  8025  8025 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-27 11:51:35.584  6803  6803 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 11:51:35.589  6803  6803 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 11:51:35.594  8136  8136 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-27 11:51:35.594  8136  8136 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-27 11:51:35.595  8136  8136 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-27 11:51:35.595  8136  8136 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-27 11:51:35.595  8136  8136 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-27 11:51:35.597  8071  8071 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
07-27 11:51:35.598  8071  8071 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
07-27 11:51:35.599  8071  8133 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-27 11:51:35.600  1802  1802 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,07-27 11:51:35.607  2194  2194 I ConfigService: onCreate
07-27 11:51:35.607  2194  2194 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-27 11:51:35.607  1802  1802 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
07-27 11:51:35.614  2194  2194 I ConfigService: onBind returning update interface
,07-27 11:51:35.615  2194  2194 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-27 11:51:35.615  2194  2194 I ConfigService: onBind returning config service
07-27 11:51:35.617  2194  2194 I ConfigService: onDestroy
07-27 11:51:35.620  1802  8214 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
07-27 11:51:35.630  2017  2850 I GBoardtInterface: onReloaded()
,07-27 11:51:35.632  2017  2017 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
07-27 11:51:35.633  3806  4474 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-27 11:51:35.639  3806  3823 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-27 11:51:35.640  5980  8222 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
07-27 11:51:35.647  1891  1891 D ActionManagerService: notifyUserLog: 1000001
,07-27 11:51:35.651  3806  4477 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
07-27 11:51:35.651  3806  4477 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
07-27 11:51:35.651  1802  8223 I PeopleContactsSync: CP2 sync disabled
07-27 11:51:35.654  1891  1891 D ActionManagerService: notifyUserLog: 1000001
07-27 11:51:35.655  7016  7016 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
07-27 11:51:35.655  3806  4477 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
07-27 11:51:35.655  3806  4477 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
07-27 11:51:35.655  3806  4477 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
07-27 11:51:35.655  3806  4477 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
07-27 11:51:35.656  3806  4474 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-27 11:51:35.660  1802  4754 I Icing   : doRemovePackageData com.test.thalitest
07-27 11:51:35.660  2017  2017 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
,07-27 11:51:35.660  2017  2017 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
07-27 11:51:35.662  2017  2017 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
07-27 11:51:35.662  2017  2017 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
07-27 11:51:35.664  2017  2017 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1469186101390&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
07-27 11:51:35.664  2017  2017 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1469186101390&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
07-27 11:51:35.669  2332  8225 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
07-27 11:51:35.692  1037  1962 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8227 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,07-27 11:51:35.700  1802  8221 W GmsApplication: Using Auth Proxy for data requests.
07-27 11:51:35.705  1802  8221 W GmsApplication: Using Auth Proxy for data requests.
,07-27 11:51:35.732  8227  8227 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 11:51:35.732  8227  8227 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-27 11:51:35.733  8227  8227 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-27 11:51:35.733  8227  8227 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-27 11:51:35.743  1802  8218 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-27 11:51:35.744  1802  8218 E DriveAsyncService: disk I/O error (code 3850)
07-27 11:51:35.744  1802  8218 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-27 11:51:35.744  1802  8218 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-27 11:51:35.744  1802  8218 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
07-27 11:51:35.744  1802  8218 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-27 11:51:35.744  1802  8218 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-27 11:51:35.744  1802  8218 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
07-27 11:51:35.744  1802  8218 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
07-27 11:51:35.744  1802  8218 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.c(SourceFile:438)
07-27 11:51:35.744  1802  8218 E DriveAsyncService: 	at com.google.android.gms.drive.database.d.g(SourceFile:1384)
07-27 11:51:35.744  1802  8218 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.al.a(SourceFile:15)
07-27 11:51:35.744  1802  8218 E DriveAsyncService: 	at com.google.android.gms.common.service.c.onHandleIntent(SourceFile:60)
07-27 11:51:35.744  1802  8218 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-27 11:51:35.744  1802  8218 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:51:35.744  1802  8218 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:135)
07-27 11:51:35.744  1802  8218 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/Downloads.db'.
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-27 11:51:35.770  8227  8227 E S,QLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-27 11:51:35.770  8227  8227 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-27 11:51:35.771  8227  8227 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.

```
