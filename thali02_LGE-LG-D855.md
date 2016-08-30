#### Test 8326112021d0a60_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-30 14:57:00.082  1587  1587 I [SystemUI]Clock: called onTimeUpdated()
08-30 14:57:00.090  1587  1587 I LgeClockWidgetControlView: called onTimeUpdated()
08-30 14:57:00.091  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
08-30 14:57:00.094  1587  1587 I [SystemUI]DateView: called onTimeUpdated()
08-30 14:57:00.095  1587  1587 D KeyguardUpdateMonitor: handleTimeUpdate
,08-30 14:57:20.680  6631  6631 D AndroidRuntime: 
08-30 14:57:20.680  6631  6631 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 14:57:20.686  6631  6631 D AndroidRuntime: CheckJNI is OFF
08-30 14:57:20.807  6631  6631 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 14:57:20.812  1035  2016 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 14:57:20.821  1925  2921 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-30 14:57:20.825  1035  2016 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-30 14:57:20.826  1035  2016 D ActivityManager: setTaskToReturnTo : TaskRecord{7fd98cd #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 14:57:20.826  1035  2016 D ActivityManager: setTaskToReturnTo : TaskRecord{7fd98cd #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 14:57:20.828  1035  2016 D WindowStateEx: AppWindowTokenEx init.. 
08-30 14:57:20.828   337   348 E GBMv2   : DFP En is all cleared set to be enabled
08-30 14:57:20.868  1035  2016 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6646 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 14:57:20.870  6631  6631 D AndroidRuntime: Shutting down VM
08-30 14:57:20.909  1925  2921 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-30 14:57:20.909  1925  2921 D SplitWindowPolicy: topRunningActivity=ActivityInfo{36843b2b co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 14:57:20.910  1925  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-30 14:57:20.910  1925  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2e967b88 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 14:57:20.955  6646  6646 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-30 14:57:21.017  6646  6646 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-30 14:57:21.024  6646  6646 I LibraryLoader: Loading: webviewchromium
08-30 14:57:21.026  6646  6646 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3911-3913)
08-30 14:57:21.026  6646  6646 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 14:57:21.063  6646  6646 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1af7a111}
08-30 14:57:21.065  6646  6646 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 14:57:21.065  6646  6646 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 14:57:21.078  6646  6646 I BrowserStartupController: Initializing chromium process, renderers=0
08-30 14:57:21.080  6646  6646 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 14:57:21.096  6646  6646 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-30 14:57:21.096  6646  6646 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-30 14:57:21.097  6646  6646 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-30 14:57:21.103   311  1368 V AudioPolicyService: registerClient() client 0xb558a600, uid 10118
,08-30 14:57:21.113  1035  1117 D BluetoothManagerService: Message: 20
08-30 14:57:21.113  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3de266ef:true
,08-30 14:57:21.115  6646  6646 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 14:57:21.115  6646  6646 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 14:57:21.115  6646  6646 I Adreno-EGL: Build Date: 12/12/14 금
08-30 14:57:21.115  6646  6646 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 14:57:21.115  6646  6646 I Adreno-EGL: Remote Branch: 
08-30 14:57:21.115  6646  6646 I Adreno-EGL: Local Patches: 
08-30 14:57:21.115  6646  6646 I Adreno-EGL: Reconstruct Branch: 
,08-30 14:57:21.192  6646  6692 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-30 14:57:21.194  6646  6646 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-30 14:57:21.226  6646  6646 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 14:57:21.231  6646  6646 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 14:57:21.235  6646  6646 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-30 14:57:21.239  6646  6646 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-30 14:57:21.239  6646  6646 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-30 14:57:21.256  6646  6646 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-30 14:57:21.264  6646  6646 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 14:57:21.264  6646  6646 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 14:57:21.308  6646  6708 D OpenGLRenderer: Render dirty regions requested: true
08-30 14:57:21.308  6646  6708 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 14:57:21.325  6646  6708 D OpenGLRenderer: Enabling debug mode 0
,08-30 14:57:21.338  6646  6646 D Atlas   : Validating map...
08-30 14:57:21.344  1035  1998 D SplitWindow: check instance of lgWin Window{3b415f71 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 14:57:21.370  6646  6706 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 14:57:21.370  6646  6706 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 14:57:21.489  1035  1118 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +581ms (total +660ms)
,08-30 14:57:21.490  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2716b582 u0 com.test.thalitest/.MainActivity t6} time:164377
08-30 14:57:21.495  6646  6646 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3b2eef14 time:164382
08-30 14:57:21.600  6646  6646 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-30 14:57:21.600  6646  6646 I chromium: 
,08-30 14:57:21.649  6646  6646 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 14:57:21.736  6646  6706 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-30 14:57:21.736  6646  6706 I chromium: 
,08-30 14:57:21.863  6646  6722 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435165696
,08-30 14:57:21.877  6646  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 14:57:21.877  6646  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 14:57:21.877  6646  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 14:57:21.877  6646  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 14:57:21.877  6646  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 14:57:21.877  6646  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b784798 added. We now have 1 listener(s)
,08-30 14:57:21.882  1035  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 14:57:21.885  6646  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,08-30 14:57:21.887  6646  6722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-30 14:57:21.888  6646  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:57:21.889  6646  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 14:57:21.895  6646  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 14:57:21.895  6646  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 14:57:21.895  6646  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 14:57:21.895  6646  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-30 14:57:21.895  6646  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 14:57:21.895  6646  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 14:57:21.895  6646  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 14:57:21.895  6646  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 14:57:21.895  6646  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 14:57:21.895  6646  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 14:57:21.895  6646  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 14:57:21.895  6646  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 14:57:21.895  6646  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 14:57:21.895  6646  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 14:57:21.895  6646  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cda6657 added. We now have 1 listener(s)
08-30 14:57:21.896  6646  6722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:57:21.901  1035  1528 D WifiService: New client listening to asynchronous messages
08-30 14:57:21.904  6646  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 14:57:21.904  6646  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 14:57:21.906  6646  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 14:57:21.907  6646  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 14:57:21.907  6646  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 14:57:21.915  6646  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:57:21.916  1035  1936 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:21.916  6646  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-30 14:57:21.926  6646  6722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-30 14:57:21.928  6646  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:57:21.928  6646  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:21.928  6646  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:21.928  6646  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:57:21.928  6646  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:57:21.928  6646  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:57:21.928  6646  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:57:21.928  6646  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:57:21.928  6646  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 14:57:21.928  6646  6722 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:57:21.929  6646  6722 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 14:57:21.932  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:21.933  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:21.954  6646  6646 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 14:57:22.003   337   350 E GBMv2   : DFP En is all cleared set to be enabled
08-30 14:57:22.003   337   350 E GBMv2   : Set value is all cleared set the max
08-30 14:57:22.003   337   350 I GBMv2   : DFP Enabled. Ignore VFP set
,08-30 14:57:22.622  6646  6725 W jxcore-log: Initializing JXcore engine
08-30 14:57:22.622  6646  6725 W jxcore-log: JXcore engine is ready
,08-30 14:57:22.704  6725  6725 W Thread-762: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7501]" dev="sockfs" ino=7501 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-30 14:57:22.704  6725  6725 W Thread-762: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-30 14:57:22.704  6725  6725 W Thread-762: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10404]" dev="sockfs" ino=10404 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-30 14:57:22.704  6725  6725 W Thread-762: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-30 14:57:22.704  6725  6725 W Thread-762: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[25305]" dev="sockfs" ino=25305 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-30 14:57:22.738  6646  6725 W jxcore-log: Starting JXcore engine
,08-30 14:57:22.886  6646  6725 W jxcore-log: Platform android
08-30 14:57:22.886  6646  6725 W jxcore-log: 
08-30 14:57:22.886  6646  6725 W jxcore-log: Process ARCH arm
08-30 14:57:22.886  6646  6725 W jxcore-log: 
,08-30 14:57:23.134  6646  6725 I jxcore-log: JXcore Cordova bridge is ready!
08-30 14:57:23.134  6646  6725 I jxcore-log: 
08-30 14:57:23.134  6646  6725 W jxcore-log: JXcore engine is started
,08-30 14:57:23.141  6646  6722 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-30 14:57:23.144  6646  6646 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 14:57:32.816  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 14:57:32.816  6646  6725 I jxcore-log: 
08-30 14:57:32.818  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 14:57:32.818  6646  6725 I jxcore-log: 
,08-30 14:57:32.825  6646  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:57:32.825  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:32.825  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:32.825  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:57:32.825  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:57:32.825  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:57:32.825  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:57:32.825  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:57:32.828  6646  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:57:32.830  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 14:57:32.830  6646  6725 I jxcore-log: 
08-30 14:57:32.832  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 14:57:32.832  6646  6725 I jxcore-log: 
,08-30 14:57:33.335  6646  6725 D executeNativeTests: Running unit tests
,08-30 14:57:33.419  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 14:57:33.419  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c160868 added. We now have 2 listener(s)
,08-30 14:57:33.420  1035  1969 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 14:57:33.422  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 14:57:33.422  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 14:57:33.422  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 14:57:33.422  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 14:57:33.422  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 added. We now have 2 listener(s),
08-30 14:57:33.422  6646  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:57:33.423  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 14:57:33.425  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-30 14:57:33.427  6646  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-30 14:57:33.427  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-30 14:57:33.427  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:33.427  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:57:33.427  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:57:33.427  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:57:33.427  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,08-30 14:57:33.427  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:57:33.428  6646  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 14:57:33.428  6646  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 14:57:33.429  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:33.430  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-30 14:57:33.433  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 14:57:33.433  6646  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
08-30 14:57:33.433  6646  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 14:57:33.435  6646  6725 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-30 14:57:33.435  6646  6725 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 14:57:33.435  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-30 14:57:33.435  6646  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 14:57:33.435  6646  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 14:57:33.436  6646  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:57:33.436  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:33.437  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 14:57:33.437  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:33.437  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.437  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:57:33.437  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:57:33.438  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c160868 removed from the list
08-30 14:57:33.438  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.438  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 removed from the list
08-30 14:57:33.438  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:57:33.438  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.438  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.438  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.439  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:33.439  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:33.439  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.439  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.440  6646  6725 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 14:57:33.441  6646  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:57:33.441  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:33.441  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:57:33.441  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:33.441  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.441  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.441  6646  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c160868 not in the list
08-30 14:57:33.441  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.441  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.441  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:57:33.441  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 14:57:33.441  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.441  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.441  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.442  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:33.442  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:33.442  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.442  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 14:57:33.446  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 14:57:33.446  6646  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:57:33.446  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:33.446  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:57:33.447  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:33.447  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.447  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.447  6646  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c160868 not in the list
08-30 14:57:33.447  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.447  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.447  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:57:33.447  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.447  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.447  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.447  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.451  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:33.451  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:33.451  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.451  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.453  6646  6725 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 14:57:33.455  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:57:33.457  6646  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:57:33.457  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:33.457  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:33.457  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:57:33.457  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:57:33.457  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:57:33.457  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:57:33.457  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:57:33.458  6646  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:57:33.458  6646  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:57:33.459  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:33.459  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:57:33.459  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 14:57:33.459  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 14:57:33.459  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:57:33.459  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 14:57:33.462  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:33.464  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 14:57:33.464  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:33.467  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 14:57:33.471  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 14:57:33.473  6646  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 14:57:33.473  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 14:57:33.473  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:57:33.474  6646  6725 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-30 14:57:33.474  6646  6725 I io.jxcore.node.ConnectionHelper: start: OK
08-30 14:57:33.476  6646  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:57:33.476  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:33.476  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:57:33.477  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:33.477  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.477  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:57:33.477  6646  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c160868 not in the list
08-30 14:57:33.477  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.477  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.477  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:57:33.477  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.477  6646  6725 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 14:57:33.478  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:57:33.480  6646  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:57:33.480  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:33.480  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:33.480  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:57:33.480  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:57:33.480  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:57:33.480  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:57:33.480  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:57:33.481  6646  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:57:33.481  6646  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:57:33.482  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:57:33.482  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 14:57:33.482  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 14:57:33.482  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:57:33.482  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 14:57:33.482  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:33.484  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:33.486  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 14:57:33.486  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:57:33.487  6646  6725 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 14:57:33.487  6646  6725 I io.jxcore.node.ConnectionHelper: start: OK
08-30 14:57:33.488  6646  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:57:33.488  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:33.488  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:57:33.488  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:33.488  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.488  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:57:33.488  6646  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c160868 not in the list
08-30 14:57:33.488  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.488  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.488  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:57:33.488  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.489  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.489  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.489  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:33.489  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:33.490  6646  6725 D BluetoothLeScanner: could not find callback wrapper
08-30 14:57:33.490  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:57:33.491  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.491  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.491  6646  6725 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 14:57:33.492  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:57:33.494  6646  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:57:33.494  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:33.494  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:33.494  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:57:33.494  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:57:33.494  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:57:33.494  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:57:33.494  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:57:33.495  6646  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:57:33.495  6646  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:57:33.496  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:33.496  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:57:33.497  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 14:57:33.497  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 14:57:33.497  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:57:33.497  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 14:57:33.500  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:33.569  1035  1630 I art     : Explicit concurrent mark sweep GC freed 33101(1599KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 1.541ms total 71.141ms
08-30 14:57:33.571  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 14:57:33.571  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:57:33.572  6646  6725 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 14:57:33.572  6646  6725 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 14:57:33.572  6646  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:57:33.575  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:33.575  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:57:33.575  6646  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:57:33.575  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:33.575  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:57:33.576  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:33.576  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.576  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:57:33.576  6646  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c160868 not in the list
08-30 14:57:33.576  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.576  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.576  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:57:33.576  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.577  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.577  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.578  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:33.578  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:33.578  6646  6725 D BluetoothLeScanner: could not find callback wrapper
08-30 14:57:33.578  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:57:33.578  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.578  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.579  6646  6725 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-30 14:57:33.579  6646  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:57:33.579  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:33.579  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:57:33.579  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:33.579  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: rele,ase: The given listener does not exist in the list - probably already removed
08-30 14:57:33.579  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.580  6646  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c160868 not in the list
08-30 14:57:33.580  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.580  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.580  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:57:33.580  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.580  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.580  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.580  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.580  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:33.580  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:33.581  6646  6725 D BluetoothLeScanner: could not find callback wrapper
08-30 14:57:33.581  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:57:33.581  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.581  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.581  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 14:57:33.581  6646  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:57:33.581  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:33.582  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:57:33.582  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:33.582  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.582  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.582  6646  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c160868 not in the list
08-30 14:57:33.582  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.582  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.582  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:57:33.582  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.582  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: releas,e: 1 listener(s) left
08-30 14:57:33.582  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.582  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.583  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:33.583  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:33.583  6646  6725 D BluetoothLeScanner: could not find callback wrapper
08-30 14:57:33.583  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:57:33.583  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.583  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.584  6646  6725 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 14:57:33.584  6646  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:57:33.584  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:33.584  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:57:33.584  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:33.584  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.584  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.584  6646  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c160868 not in the list
08-30 14:57:33.584  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.584  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.584  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:57:33.584  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.584  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.584  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.584  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.585  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:33.585  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:33.585  6646  6725 D BluetoothLeScanner: could not find callback wrapper
08-30 14:57:33.585  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:57:33.585  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.585  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.586  6646  6725 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 14:57:33.586  6646  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:57:33.586  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:33.586  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:57:33.586  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:33.586  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.586  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.586  6646  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c160868 not in the list
08-30 14:57:33.586  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.586  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.586  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:57:33.586  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.586  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.586  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.587  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.587  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:33.587  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:33.588  6646  6725 D BluetoothLeScanner: could not find callback wrapper
08-30 14:57:33.588  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:57:33.588  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.588  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.588  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 14:57:33.589  6646  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 14:57:33.589  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 14:57:33.589  6646  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 14:57:33.589  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 14:57:33.589  6646  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 14:57:33.589  6646  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:57:33.589  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:33.589  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:57:33.590  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:33.590  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.590  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.590  6646  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c160868 not in the list
08-30 14:57:33.590  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.590  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.590  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:57:33.590  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.590  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.590  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.590  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.591  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:33.591  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:33.591  6646  6725 D BluetoothLeScanner: could not find callback wrapper
08-30 14:57:33.591  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:57:33.591  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.591  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.592  6646  6725 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 14:57:33.592  6646  6725 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 14:57:33.592  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 14:57:33.597  6646  6725 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 14:57:33.597  6646  6725 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 14:57:33.597  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 14:57:33.597  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 14:57:33.597  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 14:57:33.597  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 14:57:33.597  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 14:57:33.597  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 14:57:33.597  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 14:57:33.597  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 14:57:33.597  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 14:57:33.597  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 14:57:33.597  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 14:57:33.597  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 14:57:33.597  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 14:57:33.597  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 14:57:33.597  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 14:57:33.597  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 14:57:33.597  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 14:57:33.597  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 14:57:33.597  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 14:57:33.597  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 14:57:33.597  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 14:57:33.597  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 14:57:33.597  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 14:57:33.597  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 14:57:33.597  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 14:57:33.598  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 14:57:33.598  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 14:57:33.598  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 14:57:33.599  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 14:57:33.599  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 14:57:33.599  6646  6725 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 14:57:33.599  6646  6725 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 14:57:33.599  6646  6725 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 14:57:33.599  6646  6725 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 14:57:33.599  6646  6725 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 14:57:33.599  6646  6725 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 14:57:33.599  6646  6725 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 14:57:33.599  6646  6725 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 14:57:33.599  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 14:57:33.601  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-30 14:57:33.601  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 14:57:33.601  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 14:57:33.602  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 14:57:33.602  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 14:57:33.602  6646  6725 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 14:57:33.602  6646  6725 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 14:57:33.602  6646  6725 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 14:57:33.602  6646  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:57:33.602  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:33.602  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:57:33.604  6646  6726 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 826)
08-30 14:57:33.612  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:33.612  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.612  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.612  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 14:57:33.613  6646  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c160868 not in the list
08-30 14:57:33.613  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.613  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.613  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:57:33.613  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.613  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.613  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.613  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.615  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:33.616  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:33.616  6646  6727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 826
08-30 14:57:33.616  6646  6727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 826)
08-30 14:57:33.616  6646  6727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 826)
08-30 14:57:33.617  6646  6725 D BluetoothLeScanner: could not find callback wrapper
08-30 14:57:33.617  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:57:33.617  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.617  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.618  6646  6725 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 14:57:33.619  6646  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:57:33.619  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:33.619  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:57:33.619  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:33.619  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.619  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.619  6646  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c160868 not in the list
08-30 14:57:33.619  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.619  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.619  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:57:33.619  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.619  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.619  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.619  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.623  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:33.623  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:33.623  6646  6725 D BluetoothLeScanner: could not find callback wrapper
08-30 14:57:33.623  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:57:33.623  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.624  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.630  6646  6725 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 14:57:33.631  6646  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:57:33.631  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:33.631  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 14:57:33.631  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:33.631  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.631  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.631  6646  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c160868 not in the list
08-30 14:57:33.631  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.631  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.631  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:57:33.631  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.631  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.631  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.631  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.632  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:33.632  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:33.632  6646  6725 D BluetoothLeScanner: could not find callback wrapper
08-30 14:57:33.632  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:57:33.632  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.632  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.633  6646  6725 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 14:57:33.633  6646  6725 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 14:57:33.633  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 14:57:33.633  6646  6725 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 14:57:33.633  6646  6725 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 14:57:33.633  6646  6725 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 14:57:33.633  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 14:57:33.633  6646  6725 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 14:57:33.634  6646  6725 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 14:57:33.634  6646  6725 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 14:57:33.634  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 14:57:33.634  6646  6725 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 14:57:33.634  6646  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:57:33.634  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:33.634  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:57:33.634  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:33.634  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.634  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.634  6646  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c160868 not in the list
08-30 14:57:33.634  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.634  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.634  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:57:33.634  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.634  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.634  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.634  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.635  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:33.635  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:33.642  6646  6725 D BluetoothLeScanner: could not find callback wrapper
08-30 14:57:33.642  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:57:33.642  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.642  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.643  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:33.643  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.643  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.643  6646  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c160868 not in the list
08-30 14:57:33.643  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.643  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.643  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:57:33.643  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.643  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.643  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.643  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.643  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:33.643  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.643  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.643  6646  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c160868 not in the list
08-30 14:57:33.643  6646  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:57:33.643  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:33.643  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:57:33.645  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:33.645  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.645  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.645  6646  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c160868 not in the list
08-30 14:57:33.645  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.645  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.645  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:57:33.645  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.645  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.645  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.645  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.646  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:33.646  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:33.646  6646  6725 D BluetoothLeScanner: could not find callback wrapper
08-30 14:57:33.646  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:57:33.646  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.646  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.647  6646  6725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 14:57:33.648  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:57:33.648  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 14:57:33.648  6646  6725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 14:57:33.649  6646  6725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 14:57:33.649  6646  6646 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 14:57:33.649  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 14:57:33.649  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 14:57:33.650  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:33.650  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 14:57:33.650  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 14:57:33.650  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 14:57:33.650  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.650  6646  6725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 14:57:33.651  6646  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 14:57:33.651  6646  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 14:57:33.651  6646  6646 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 14:57:33.651  6646  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c160868 not in the list
08-30 14:57:33.651  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.651  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 14:57:33.652  6646  6725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 14:57:33.652  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 14:57:33.662  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 14:57:33.663  6646  6725 D BluetoothLeScanner: could not find callback wrapper
08-30 14:57:33.663  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:57:33.663  6646  6725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 14:57:33.663  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.663  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.664  6646  6725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 14:57:33.664  6646  6646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:57:33.665  6646  6646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 14:57:33.665  6646  6646 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 14:57:33.665  6646  6646 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 14:57:33.665  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.665  6646  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:57:33.665  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:33.665  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:57:33.665  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:33.665  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.665  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.665  6646  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c160868 not in the list
08-30 14:57:33.665  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 14:57:33.665  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.666  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:57:33.666  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.666  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.666  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.666  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.666  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:33.666  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:33.666  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.666  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.667  6646  6725 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 14:57:33.673  6646  6725 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 14:57:33.673  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 14:57:33.675  6646  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 14:57:33.675  6646  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:57:33.675  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:33.675  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:57:33.676  6646  6726 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-30 14:57:33.676  6646  6726 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 826)
,08-30 14:57:33.677  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:33.677  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.677  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 14:57:33.677  6646  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c160868 not in the list
08-30 14:57:33.677  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.677  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.677  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:57:33.677  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.678  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.678  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.678  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.678  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:33.678  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:33.678  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.678  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.679  1035  2034 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:33.681  1035  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:33.681  1035  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 14:57:33.682  6646  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-30 14:57:33.682  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:33.682  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:57:33.682  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:33.682  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-30 14:57:33.682  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.682  6646  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c160868 not in the list
08-30 14:57:33.682  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.682  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.682  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 14:57:33.682  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.682  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.682  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.682  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.683  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:33.683  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:33.683  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-30 14:57:33.683  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.685  6646  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:57:33.685  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:33.685  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:57:33.685  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 14:57:33.685  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.685  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.685  6646  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c160868 not in the list
08-30 14:57:33.685  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.685  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.685  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop,
08-30 14:57:33.685  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.685  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 14:57:33.698  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:33.699  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:33.700  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:33.700  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:33.700  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:33.700  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4617481 not in the list
08-30 14:57:33.702  6646  6725 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 14:57:33.702  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 14:57:33.703  6646  6725 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 14:57:33.703  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 14:57:33.703  6646  6725 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 14:57:33.703  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 14:57:33.705  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 14:57:33.705  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-30 14:57:33.706  6646  6725 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 14:57:33.706  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 14:57:33.708  6646  6725 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 14:57:33.708  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 14:57:33.708  6646  6725 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 14:57:33.708  6646  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 14:57:33.709  6646  6725 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 14:57:33.709  6646  6725 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 14:57:33.710  6646  6725 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 14:57:33.710  6646  6725 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 14:57:33.710  6646  6725 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 14:57:33.710  6646  6725 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 14:57:33.712  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:57:33.712  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@331b26fe added. We now have 2 listener(s)
08-30 14:57:33.712  6646  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:57:33.713  6646  6725 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 14:57:33.714  1035  1936 D WifiServiceImplEx: setWifiEnabled: true pid=6646, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 14:57:33.714  1035  1936 D WifiService: setWifiEnabled: true pid=6646, uid=10118
08-30 14:57:33.714  1035  1936 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 14:57:33.716  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:57:33.716  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ee52e5f added. We now have 3 listener(s)
08-30 14:57:33.716  6646  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 14:57:33.720  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:57:33.720  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@82fe0ac added. We now have 4 listener(s)
08-30 14:57:33.720  6646  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:57:33.722  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:57:33.722  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3df4175 added. We now have 5 listener(s)
08-30 14:57:33.722  6646  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:57:33.724  1035  1936 D WifiServiceImplEx: setWifiEnabled: false pid=6646, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 14:57:33.724  1035  1936 D WifiService: setWifiEnabled: false pid=6646, uid=10118
08-30 14:57:33.724  1035  1936 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 14:57:33.735  1035  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:33.735  1035  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 14:57:33.735  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 14:57:33.735  1035  1908 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@19bdf378 mBinding = false
08-30 14:57:33.736  1035  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 14:57:33.736  1035  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 14:57:33.736  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 14:57:33.736  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 14:57:33.736  1035  1523 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 14:57:33.736  1035  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 14:57:33.736  1035  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 14:57:33.736  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 14:57:33.737  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-30 14:57:33.737  1035  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 14:57:33.737  1035  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 14:57:33.744  1035  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 14:57:33.744  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 14:57:33.744  2724  2724 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 14:57:33.744  1035  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:33.744  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:33.744  1035  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 14:57:33.744  1035  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 14:57:33.745  1035  1523 D WifiNative-wlan0: SET ps 1: returned true
08-30 14:57:33.745  1035  2850 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:33.746  1035  1117 D BluetoothManagerService: Message: 2
08-30 14:57:33.747  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 14:57:33.747  1035  1117 D BluetoothManagerService: Sending off request.
08-30 14:57:33.747  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 14:57:33.747  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-30 14:57:33.748  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:57:33.749   305   893 D CommandListener: Clearing all IP addresses on wlan0
,08-30 14:57:33.749  3881  3899 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 14:57:33.752  3881  3964 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 14:57:33.752  3881  3964 D BluetoothAdapterProperties: Setting state to 13
08-30 14:57:33.752  3881  3964 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 14:57:33.753  3881  3964 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 14:57:33.753  3881  3964 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 14:57:33.753  1035  1117 D BluetoothManagerService: Message: 60
08-30 14:57:33.754  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-30 14:57:33.754  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-30 14:57:33.755  3881  3970 D BluetoothAdapterProperties: Scan Mode:20
08-30 14:57:33.756  3881  3964 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 14:57:33.756  3881  3964 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 14:57:33.756  3881  4268 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 14:57:33.757  3881  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 14:57:33.757  3881  4082 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-30 14:57:33.759  3881  4270 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 14:57:33.760  3881  4195 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 14:57:33.760  3881  4267 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-30 14:57:33.764  3881  4194 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 14:57:33.764  3881  4194 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 14:57:33.764  3881  4194 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 14:57:33.764  3881  4194 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 14:57:33.764  3881  4194 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 14:57:33.764  3881  4194 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 14:57:33.764  3881  4194 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 14:57:33.764  3881  4194 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-30 14:57:33.765  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 14:57:33.766  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:33.766  3881  3881 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:33.766  3881  3881 D BluetoothMapService: STATE_TURNING_OFF
08-30 14:57:33.766  3881  3881 V BluetoothMapService: Handler(): got msg=4
08-30 14:57:33.766  3881  3881 D BluetoothMapService: MAP Service closeService in
08-30 14:57:33.767  3881  3881 D BluetoothMapMasInstance: MAP Service shutdown
08-30 14:57:33.768  3881  3881 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 14:57:33.768  3881  3881 V BluetoothMapService: MAP Service closeService out
08-30 14:57:33.768  3881  3881 V BtOppService: Receiver DISABLED_ACTION 
08-30 14:57:33.769  3881  3881 I BtOppRfcommListener: stopping Accept Thread
08-30 14:57:33.769  3881  3881 V BtOppRfcommListener: close mBtServerSocket
08-30 14:57:33.770  3881  4267 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 14:57:33.770  3881  3881 V BtOppRfcommListener: waiting for thread to terminate
08-30 14:57:33.770  3881  3881 V BtOppRfcommListener: done waiting for thread to terminate
08-30 14:57:33.772  3881  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 14:57:33.772  3881  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 14:57:33.772  3881  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 14:57:33.772  3881  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 14:57:33.772  3881  4082 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 14:57:33.772  3881  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 14:57:33.772  3881  4082 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 14:57:33.772  3881  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 14:57:33.772  3881  4082 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 14:57:33.772  3881  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 14:57:33.772  3881  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
,08-30 14:57:33.773  3881  4082 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 14:57:33.779  1035  1908 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-30 14:57:33.779  1035  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:33.779  1035  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:33.779  1035  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-30 14:57:33.779  1035  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:33.779  1035  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 14:57:33.786   305  6744 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-30 14:57:33.786  1035  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-30 14:57:33.788  1035  1115 D DSQN    : Dns fail occured do internet check.
08-30 14:57:33.788  1035  1035 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-30 14:57:33.789  1035  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 14:57:33.789  1035  1035 D DSQN    : try Internet connection check
08-30 14:57:33.790  1035  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-30 14:57:33.800  1035  1098 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6747 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 14:57:33.801  1035  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:33.801  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:33.801  1035  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:33.802  1035  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:33.802  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:33.804  3881  3881 V BtOppService: onDestroy
,08-30 14:57:33.804  1035  1521 D LGWifiP2pService: InactiveState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:33.804  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:33.804  1035  1521 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@381a0817
08-30 14:57:33.805  1035  1521 D LGWifiP2pService: P2pDisablingState
08-30 14:57:33.805  1035  1521 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:33.805  1035  1521 D LGWifiP2pService: p2p socket connection lost
08-30 14:57:33.805  1035  1521 D LGWifiP2pService: P2pDisabledState
08-30 14:57:33.806  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-30 14:57:33.808  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-30 14:57:33.808  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:33.808  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:33.808  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 14:57:33.808  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-30 14:57:33.808  1035  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:33.809  1035  1523 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 14:57:33.810  1035  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 14:57:33.810  1035  1521 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:33.810  1035  1521 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:33.810  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 14:57:33.810  2724  2724 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 14:57:33.810  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:33.811  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:33.811  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 14:57:33.811  1035  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 14:57:33.811  1035  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 14:57:33.811  1035  1523 D WifiNative-wlan0: SET ps 1: returned true
08-30 14:57:33.812  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:57:33.812  6646  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:57:33.812  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:33.812  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:33.812  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:57:33.812  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:57:33.812  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:57:33.812  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:57:33.812  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - active netwo,rk type is Wi-Fi: true
08-30 14:57:33.815  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 14:57:33.815  1925  1925 D WfdsService: WifiP2pState is changed : false
08-30 14:57:33.815  1925  2320 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 14:57:33.815  1925  2320 D WfdsService: Set the WFDS Monitor: false
08-30 14:57:33.815  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 14:57:33.815  1035  1035 D RttService: SCAN_AVAILABLE : 1
08-30 14:57:33.815  1035  1540 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:33.816  1035  1541 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:33.816  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:57:33.816  1925  2320 D WfdsMonitor: WFDS Monitor is stopped
08-30 14:57:33.817  1925  2320 D WfdsService: STATE : WfdsDisabledState - enter
08-30 14:57:33.817  6646  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:57:33.817  1925  2757 D CtrlSupplicant: Received on exit socket, terminate
08-30 14:57:33.817  6646  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:57:33.817  1925  2757 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 14:57:33.817  1925  2757 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 14:57:33.817  1925  2757 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 14:57:33.817  1925  2322 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 14:57:33.817  1925  2320 W WfdsService: DefaultState - msg [9445378] is not handled
08-30 14:57:33.819  6646  6646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:57:33.819  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:57:33.819  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:33.819  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:33.819  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:57:33.819  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:57:33.819  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:57:33.819  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:57:33.819  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:57:33.820  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:33.821  6646  6646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:57:33.821  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:57:33.821  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:33.821  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:33.821  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:57:33.821  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:57:33.821  6646  6646, V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:57:33.821  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:57:33.821  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:57:33.825  6646  6646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:57:33.825  6646  6646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:57:33.826  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:33.827  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:33.829  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:33.831  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:33.831  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:57:33.832  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:33.835  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:33.835  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:57:33.836  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:33.841   305   893 D CommandListener: Clearing all IP addresses on wlan0
08-30 14:57:33.841  1035  1529 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 14:57:33.842  1035  1529 D DSQN    : disableDataServiceNotify
08-30 14:57:33.842  1035  1529 D DSQN    : stop dsqn bin
08-30 14:57:33.844  1035  1098 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6769 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-30 14:57:33.844  3881  3881 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 14:57:33.844   305  6768 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 14:57:33.845  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 14:57:33.845  1035  1523 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 14:57:33.846  1035  6754 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
08-30 14:57:33.846  1035  1523 D WifiNative-p2p0: TERMINATE: returned true
08-30 14:57:33.846  1035  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 14:57:33.846  1035  1523 E WifiStateMachine: useWiFiOffloading() : false
08-30 14:57:33.846  1035  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 14:57:33.847  1035  6746 D DSQN    : ThreadInternetCheck internet check NOK 
08-30 14:57:33.847  1035  6746 D DSQN    : InternetcheckProgress is not set don't send DS quality intent
08-30 14:57:33.847  1035  1529 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 14:57:33.847  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:57:33.847  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:57:33.847  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-30 14:57:33.847  1035  1529 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:57:33.848  1035  1529 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-30 14:57:33.848  1035  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:33.848  1035  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:33.848  1035  2849 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 14:57:33.848  1587  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 14:57:33.848  1035  1529 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-30 14:57:33.848  1035  1529 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 14:57:33.848  1035  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 14:57:33.849  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:33.849  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:33.849  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 14:57:33.851  1035  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 14:57:33.851  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 14:57:33.852  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 14:57:33.852  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 14:57:33.852  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 14:57:33.853  1035  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:33.853  1035  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 14:57:33.854  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
,08-30 14:57:33.856  1035  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:33.856  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 14:57:33.856  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:57:33.856  1035  1529 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:57:33.856  1035  1529 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:57:33.856  1035  1529 D NetworkManagementService: Removing idletimer
08-30 14:57:33.856  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 14:57:33.856  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:57:33.857  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 14:57:33.857  1035  1529 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:33.857  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 14:57:33.857  1035  1523 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:57:33.857  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 14:57:33.857  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 14:57:33.857  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 14:57:33.857  1035  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 14:57:33.857  1035  1529 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 14:57:33.857  1035  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 14:57:33.857  1835  1835 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:57:33.857  1835  1835 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 14:57:33.859  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:33.859  6646  6646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:57:33.859  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:57:33.859  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:33.859  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:33.859  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:57:33.859  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:57:33.859  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:57:33.859  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:57:33.859  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:57:33.860  6646  6646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:57:33.860  6646  6646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:57:33.863  6646  6646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:57:33.863  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:57:33.863  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:33.863  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:33.863  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:57:33.863  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:57:33.863  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:57:33.863  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:57:33.863  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:57:33.863  6646  6646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:57:33.863  6646  6646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:57:33.886  6747  6747 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 14:57:33.886  6747  6747 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-30 14:57:33.886  6747  6747 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 14:57:33.886  6747  6747 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-30 14:57:33.887  6747  6747 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 14:57:33.888  6747  6747 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 14:57:33.897  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 14:57:33.898  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:33.899  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:33.902  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 14:57:33.915  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 14:57:33.916  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:33.916  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:33.939  6769  6769 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-30 14:57:33.939  6769  6769 W LG Account v2.2: No ProfileInfo entries
08-30 14:57:33.939  6769  6769 I LG Account v2.2: isEnabled: false
08-30 14:57:33.939  6769  6769 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 14:57:33.939  6769  6769 I Feature : [Lifetracker]Country: EU
,08-30 14:57:33.939  6769  6769 I Feature : [Lifetracker]Operator: OPEN
08-30 14:57:33.940  6769  6769 I Feature : [Lifetracker]Ranking support: false
08-30 14:57:33.940  6769  6769 I Feature : [Lifetracker]Comfort support: false
08-30 14:57:33.940  6769  6769 I Feature : [Lifetracker]Accessory: true
08-30 14:57:33.940  6769  6769 I Feature : [Lifetracker]Health device: true
08-30 14:57:33.940  6769  6769 I Feature : [Lifetracker]Extra Pedometer: false
08-30 14:57:33.940  6769  6769 I Feature : [Lifetracker]Blood glucose device: false
08-30 14:57:33.940  6769  6769 I Feature : [Lifetracker]Device Number: 3
,08-30 14:57:33.946  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:33.949  1035  2850 D DhcpStateMachine: StoppedState
08-30 14:57:33.949  1035  2850 D DhcpStateMachine: StoppedState{ when=-138ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:33.963  2724  2724 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 14:57:33.963  2724  2724 I wpa_supplicant: monitor socket send errors count : 1
08-30 14:57:33.963  2724  2724 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1925-2\x00 that cannot receive messages
,08-30 14:57:33.964  1035  2755 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 14:57:33.964  1035  2755 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 14:57:33.973  1035  1979 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6789 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 14:57:33.974  1035  1979 I ActivityManager: Killing 5914:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-30 14:57:33.977  6747  6747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 14:57:34.003  2724  2724 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 14:57:34.004  2724  2724 W wpa_supplicant: USIM:  scard_deinit function
08-30 14:57:34.004  1035  2755 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-30 14:57:34.004  1035  2755 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 14:57:34.004  1035  2755 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 14:57:34.004  1035  2755 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 14:57:34.005  1035  2755 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 14:57:34.005  1035  2755 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-30 14:57:34.005  1035  1117 D Tethering: InitialState.processMessage what=4
08-30 14:57:34.006  1035  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=176880
08-30 14:57:34.006  1035  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=176880
08-30 14:57:34.006  1035  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=176880  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 14:57:34.006  1035  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=176881  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 14:57:34.023  2724  2724 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-30 14:57:34.023  1035  2755 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-30 14:57:34.023  1035  2755 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-30 14:57:34.023  1035  2755 D WifiMonitor: Disconnecting from the supplicant, no more events
08-30 14:57:34.024  1035  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-30 14:57:34.025  1035  1908 W libprocessgroup: failed to open /acct/uid_10014/pid_5914/cgroup.procs: No such file or directory
08-30 14:57:34.032  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 14:57:34.035  3881  3881 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 14:57:34.036  3881  3881 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:34.036  3881  3881 V BluetoothPbapReceiver: ***********state = 13
,08-30 14:57:34.038  3881  3881 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-30 14:57:34.040  3881  3881 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:34.040  3881  3881 V BluetoothPbapService: state: 13
08-30 14:57:34.040  3881  3881 V BluetoothPbapService: Pbap Service closeService in
08-30 14:57:34.042  2169  2169 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 14:57:34.043  3881  3881 V BluetoothPbapService: successfully stopped pbap service
08-30 14:57:34.043  3881  3881 V BluetoothPbapService: Pbap Service closeService out
08-30 14:57:34.043  3881  3881 V BluetoothPbapService: Pbap Service onDestroy
08-30 14:57:34.043  3881  3881 V BluetoothPbapService: Pbap Service closeService in
08-30 14:57:34.043  3881  3881 V BluetoothPbapService: Pbap Service closeService out
08-30 14:57:34.043  3881  3881 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-30 14:57:34.048  1035  1117 D BluetoothManagerService: Message: 20
,08-30 14:57:34.049  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@252b0c53:true
08-30 14:57:34.070  1035  1117 D BluetoothManagerService: Message: 30
,08-30 14:57:34.075  1035  1117 D BluetoothManagerService: Message: 30
08-30 14:57:34.077  6747  6747 D LocalBluetoothProfileManager: Adding local MAP profile
08-30 14:57:34.079  6789  6789 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 14:57:34.079  6747  6747 D BluetoothMap: Create BluetoothMap proxy object
08-30 14:57:34.079  1035  1117 D BluetoothManagerService: Message: 30
08-30 14:57:34.081  6789  6789 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 14:57:34.081  6789  6789 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:57:34.083  1035  1943 I ActivityManager: Killing 6254:com.android.defcontainer/u0a4 (adj 15): empty #17
08-30 14:57:34.084  1035  1117 D BluetoothManagerService: Message: 30
08-30 14:57:34.105  6747  6747 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-30 14:57:34.106  1035  2034 W libprocessgroup: failed to open /acct/uid_10004/pid_6254/cgroup.procs: No such file or directory
,08-30 14:57:34.107  6747  6747 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-30 14:57:34.126  1035  1523 D WifiOffDelayIfNotUsed: stopMonitoring
08-30 14:57:34.126  1035  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 14:57:34.126  1035  1523 E WifiStateMachine: useWiFiOffloading() : false
08-30 14:57:34.126  1035  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 14:57:34.127  6747  6747 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-30 14:57:34.127  1925  1925 D WfdsService: Supplicant Connection state is changed : false
08-30 14:57:34.127  1925  2320 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 14:57:34.127  1925  2320 D WfdsService: Set the WFDS Monitor: false
08-30 14:57:34.127  1925  2320 D WfdsMonitor: WFDS Monitor is stopped
,08-30 14:57:34.129  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 14:57:34.129  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:34.129  1035  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 14:57:34.129  1035  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 14:57:34.130  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 14:57:34.132  2489  2489 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:34.132  6747  6747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-30 14:57:34.133  6646  6646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:57:34.134  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:57:34.134  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:34.134  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:34.134  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:57:34.134  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:57:34.134  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:57:34.134  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:57:34.134  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:57:34.135  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:34.142  6747  6747 D DockEventReceiver: finishStartingService: stopping service
,08-30 14:57:34.155  6747  6747 D BluetoothInputDevice: Proxy object connected
,08-30 14:57:34.156  6747  6747 D HidProfile: Bluetooth service connected
,08-30 14:57:34.157  6747  6747 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 14:57:34.158  6747  6747 D PanProfile: Bluetooth service connected
08-30 14:57:34.159  6747  6747 D BluetoothMap: Proxy object connected
08-30 14:57:34.160  6747  6747 D MapProfile: Bluetooth service connected
08-30 14:57:34.160  6747  6747 D BluetoothMap: getConnectedDevices()
08-30 14:57:34.161  6747  6747 D BluetoothMap: Bluetooth is Not enabled
08-30 14:57:34.165  6646  6646 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-30 14:57:34.175  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:57:34.211  6747  6747 D LgDataFeature: LgDataFeature() Constructor: none
08-30 14:57:34.211  6747  6747 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 14:57:34.223  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:57:34.223  6747  6747 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 14:57:34.226  6747  6747 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 14:57:34.233  6747  6747 D BluetoothPermissionRequest: onReceive
08-30 14:57:34.238  6747  6747 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 14:57:34.246  1035  1908 I ActivityManager: Killing 6394:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-30 14:57:34.251  6747  6747 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 14:57:34.295  1035  1559 W libprocessgroup: failed to open /acct/uid_10008/pid_6394/cgroup.procs: No such file or directory
,08-30 14:57:34.296  3881  3881 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-30 14:57:34.296  3881  3881 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-30 14:57:34.297  3881  3881 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-30 14:57:34.330  1035  1523 E WifiStateMachine:  InitialState CMD_ON_QUIT 0 0
08-30 14:57:34.331  1035  1523 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-30 14:57:34.333  1035  1523 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:57:34.334  1035  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-30 14:57:34.400  1035  1770 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6820 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-30 14:57:34.408  3881  3881 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:34.409  3881  3881 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 14:57:34.415  3881  3881 V BluetoothFtpService: Ftp Service onStartCommand
08-30 14:57:34.415  3881  3881 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:34.415  3881  3881 V BluetoothFtpService: Ftp Service closeService
08-30 14:57:34.416  3881  3881 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,08-30 14:57:34.418  3881  3881 V BluetoothFtpService: successfully stopped ftp service
08-30 14:57:34.421  3881  3881 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 14:57:34.421  3881  3881 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 14:57:34.421  3881  3881 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 14:57:34.422  3881  3881 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:34.422  3881  3881 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 14:57:34.422  3881  3881 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 14:57:34.424  3881  3881 V BluetoothFtpService: Ftp Service onDestroy
08-30 14:57:34.424  3881  3881 V BluetoothFtpService: Ftp Service closeService
,08-30 14:57:34.462  1035  2016 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6840 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 14:57:34.465  3881  3881 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:34.465  3881  3881 V BluetoothSapService: state: 13
08-30 14:57:34.465  3881  3881 V BluetoothSapService: Stopping SAP server process
08-30 14:57:34.467  3881  3881 V BluetoothSapService: Sap Service closeSapService in
08-30 14:57:34.467  3881  3881 V BluetoothSapService: Close listen Socket : 
08-30 14:57:34.468  3881  3881 V BluetoothSapService: Close rfcomm Socket : 
08-30 14:57:34.468  3881  3881 V BluetoothSapService: Close sapd  Socket : 
08-30 14:57:34.470  3881  3881 V BluetoothSapService: Sap Service closeSapService out
08-30 14:57:34.470  3881  3881 V BluetoothSapService: Sap Service onDestroy
08-30 14:57:34.470  3881  3881 V BluetoothSapService: Sap Service closeSapService in
08-30 14:57:34.470  3881  3881 V BluetoothSapService: Close listen Socket : 
08-30 14:57:34.470  3881  3881 V BluetoothSapService: Close rfcomm Socket : 
08-30 14:57:34.470  3881  3881 V BluetoothSapService: Close sapd  Socket : 
08-30 14:57:34.471  3881  3881 V BluetoothSapService: Sap Service closeSapService out
08-30 14:57:34.510  6820  6820 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 14:57:34.548  6840  6840 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 14:57:34.580  1035  2016 I ActivityManager: Killing 6010:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-30 14:57:34.627  1035  1889 W libprocessgroup: failed to open /acct/uid_10011/pid_6010/cgroup.procs: No such file or directory
,08-30 14:57:34.633  6820  6820 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-30 14:57:34.675  6820  6820 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-30 14:57:34.675  6820  6820 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-30 14:57:34.676  6820  6820 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-30 14:57:34.676  6820  6820 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-30 14:57:34.676  6820  6820 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-30 14:57:34.678  6820  6820 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-30 14:57:34.687  6820  6820 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-30 14:57:34.700  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 14:57:34.705  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 14:57:34.744  6820  6820 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 14:57:34.753  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:34.756  6820  6820 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-30 14:57:34.764  6789  6789 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 14:57:34.764  6789  6789 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 14:57:34.765  6820  6820 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-30 14:57:34.765  6789  6789 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:57:34.769  3881  4082 W bt-btif : ag scb idx 1 not allocated
08-30 14:57:34.769  3881  3970 D bt_hci_bdroid: cleanup
08-30 14:57:34.769  3881  4082 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 14:57:34.769  3881  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 14:57:34.769  3881  4082 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 14:57:34.769  3881  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 14:57:34.770  3881  4084 I bt_lpm  : LPM is already off!!!
08-30 14:57:34.769  3881  4082 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 14:57:34.770  3881  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-30 14:57:34.770  3881  4183 I bt_userial_mct: exiting userial_read_thread
08-30 14:57:34.770  3881  4082 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 14:57:34.770  3881  4183 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 14:57:34.770  3881  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 14:57:34.770  3881  4082 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 14:57:34.770  3881  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 14:57:34.770  3881  4082 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 14:57:34.770  3881  3970 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 14:57:34.771  3881  4084 I bt_vendor: hw_epilog_process
08-30 14:57:34.771  3881  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 14:57:34.771  3881  4082 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 14:57:34.771  3881  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 14:57:34.771  3881  4082 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 14:57:34.771  3881  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 14:57:34.771  3881  4082 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 14:57:34.771  3881  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 14:57:34.771  3881  4082 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 14:57:34.771  3881  3970 D bt_hci_bdroid: cleanup Finalizing cleanup
08-30 14:57:34.771  3881  3970 D bt_userial_mct: userial_close
08-30 14:57:34.771  3881  4082 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 14:57:34.771  3881  3970 E bt_userial_mct: pthread_join() FAILED result:3
08-30 14:57:34.772  3881  3970 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-30 14:57:34.776  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:57:34.788  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:57:34.799  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:57:34.800  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 14:57:34.804  6820  6820 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 14:57:34.809  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:34.813  6789  6789 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 14:57:34.813  6789  6789 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 14:57:34.813  6789  6789 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 14:57:34.818  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 14:57:34.823  3881  3970 D bt_hci_bdroid: set_power 0
08-30 14:57:34.823  3881  3970 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 14:57:34.823  3881  3970 I bt_vendor: bluetooth satus is on
08-30 14:57:34.823  3881  3970 I bt_vendor: bt-vendor : resetting BT status
08-30 14:57:34.823  3881  3970 I bt_vendor: Starting hciattach daemon
08-30 14:57:34.823  3881  3970 I bt_vendor: try to set false
08-30 14:57:34.824  3881  3970 I bt_vendor: Starting hciattach daemon
08-30 14:57:34.824  3881  3970 I bt_vendor: try to set false
08-30 14:57:34.825  3881  3970 I bt_vendor: cleanup
,08-30 14:57:34.826  3881  4082 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 14:57:34.827  3881  3970 I GKI_LINUX: GKI_exit_task 0 done
08-30 14:57:34.827  3881  3970 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 14:57:34.829  3881  3964 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 14:57:34.833  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:57:34.833  3881  3881 D HeadsetService: Received stop request...Stopping profile...
08-30 14:57:34.843  3881  3881 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 14:57:34.843  3881  3881 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 14:57:34.843  3881  4015 D HeadsetStateMachine: Exit Disconnected: -1
,08-30 14:57:34.843  3881  3881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12a8f276
08-30 14:57:34.848  1035  1035 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
,08-30 14:57:34.855  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:57:34.855  1035  1035 D BluetoothHeadset: Proxy object disconnected
08-30 14:57:34.856  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 14:57:34.856  1835  1835 D BluetoothHeadset: Proxy object disconnected
,08-30 14:57:34.857  1835  1835 D BluetoothHeadset: Proxy object disconnected
08-30 14:57:34.857  1835  1835 D BluetoothHeadset: Proxy object disconnected
08-30 14:57:34.857  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:57:34.858  3881  3881 D A2dpService: Received stop request...Stopping profile...
08-30 14:57:34.859  3881  4064 D A2dpStateMachine: Exit Disconnected: -1
08-30 14:57:34.861  3881  3881 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-30 14:57:34.863  6820  6820 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 14:57:34.864  3881  3964 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-30 14:57:34.933  1035  1998 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6873 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-30 14:57:34.937  3881  3881 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
,08-30 14:57:34.937  3881  3881 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 14:57:34.938  3881  3881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12a8f276
08-30 14:57:34.939  1035  1035 D BluetoothA2dp: Proxy object disconnected
08-30 14:57:34.939  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 14:57:34.941  3881  3881 D HidService: Received stop request...Stopping profile...
08-30 14:57:34.941  3881  3881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12a8f276
08-30 14:57:34.944  3881  3881 D HealthService: Received stop request...Stopping profile...
08-30 14:57:34.944  3881  3881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12a8f276
08-30 14:57:34.946  6747  6747 D BluetoothInputDevice: Proxy object disconnected
08-30 14:57:34.946  6747  6747 D HidProfile: Bluetooth service disconnected
08-30 14:57:34.948  3881  3881 D PanService: Received stop request...Stopping profile...
08-30 14:57:34.951  3881  3881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12a8f276
,08-30 14:57:34.955  3881  3881 D HeadsetStateMachine: Unbinding service...
08-30 14:57:34.956  6747  6747 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 14:57:34.956  6747  6747 D PanProfile: Bluetooth service disconnected
08-30 14:57:34.956  3881  3881 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 14:57:34.956  3881  3881 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 14:57:34.956  3881  3881 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 14:57:34.956  3881  3881 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 14:57:34.957  3881  3881 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 14:57:34.957  3881  3881 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 14:57:34.957  3881  3881 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 14:57:34.957  3881  3881 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 14:57:34.957  3881  3881 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 14:57:34.957  3881  3881 D BtGatt.GattService: stop()
08-30 14:57:34.958  3881  3881 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 14:57:34.958   341   341 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 908us total 22.263ms
08-30 14:57:34.959  3881  3881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12a8f276
08-30 14:57:34.960  3881  3881 D BluetoothMapService: Received stop request...Stopping profile...
08-30 14:57:34.960  3881  3881 D BluetoothMapService: stop()
08-30 14:57:34.961  3881  3881 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 14:57:34.961  3881  3881 D BluetoothMapEmailAppObserver: removeReceiver()
08-30 14:57:34.961  3881  3881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12a8f276
08-30 14:57:34.962  6747  6747 D BluetoothMap: Proxy object disconnected
08-30 14:57:34.962  6747  6747 D MapProfile: Bluetooth service disconnected
08-30 14:57:34.964  3881  3881 I BluetoothA2dpServiceJni: cleanupNative
08-30 14:57:34.964  3881  4065 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 14:57:34.965  3881  3881 I GKI_LINUX: GKI_exit_task 2 done
,08-30 14:57:34.965  3881  3881 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 14:57:34.966  3881  3881 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 14:57:34.966  3881  3881 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 14:57:34.966  3881  3881 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 14:57:34.966  3881  3881 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 14:57:34.966  3881  3881 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 14:57:34.966  3881  3881 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 14:57:34.966  3881  3881 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 14:57:34.968  3881  3881 V BluetoothMapService: Handler(): got msg=4
08-30 14:57:34.968  3881  3881 D BluetoothMapService: MAP Service closeService in
08-30 14:57:34.968  3881  3881 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 14:57:34.968  3881  3881 V BluetoothMapService: MAP Service closeService out
08-30 14:57:34.968  3881  3881 D BluetoothMapService: cleanup()
08-30 14:57:34.968  3881  3881 D BluetoothMapService: MAP Service closeService in
08-30 14:57:34.968  3881  3881 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 14:57:34.968  3881  3964 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 14:57:34.968  3881  3881 V BluetoothMapService: MAP Service closeService out
08-30 14:57:34.968  3881  3964 D BluetoothAdapterProperties: Setting state to 10
08-30 14:57:34.968  3881  3964 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 14:57:34.969  1035  1117 D BluetoothManagerService: Message: 60
08-30 14:57:34.969  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 14:57:34.969  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-30 14:57:34.969  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:57:34.970  3881  3964 I BluetoothAdapterState: Entering OffState
,08-30 14:57:34.970  6747  6767 D BluetoothMap: onBluetoothStateChange: up=false
08-30 14:57:34.970  1835  1851 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:57:34.971  6747  6765 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 14:57:34.972  6747  6767 D BluetoothPan: onBluetoothStateChange on: false
08-30 14:57:34.973  6747  6765 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 14:57:34.973  1835  4014 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:57:34.974  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 14:57:34.974  1835  4020 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 14:57:34.975  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 14:57:34.975  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 14:57:34.978  1035  1117 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
,08-30 14:57:34.978  1035  1117 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 14:57:34.978   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 376us total 19.168ms
08-30 14:57:34.978  1035  1117 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@19bdf378 mBinding = false
08-30 14:57:34.980  1035  1117 D BluetoothManagerService: Sending unbind request.
08-30 14:57:34.981  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-30 14:57:34.987  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:34.987  1925  2129 D LGBluetoothAPIService: Message: 2
,08-30 14:57:34.987  1925  2129 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2e63921 mBinding = false
,08-30 14:57:34.988  1925  2129 D LGBluetoothAPIService: Sending unbind request.
08-30 14:57:34.989  3881  3970 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-30 14:57:34.989  3881  3881 I GKI_LINUX: GKI_exit_task 1 done
08-30 14:57:34.989  3881  3881 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 14:57:34.992  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 14:57:34.995   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 287us total 17.103ms
08-30 14:57:34.996  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:34.997  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:34.997  3881  3881 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 14:57:34.997  6747  6747 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 14:57:34.997  3881  3881 I art     : --- WEIRD: removing null entry 246
08-30 14:57:34.998  3881  3881 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-30 14:57:34.998  3881  3881 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-30 14:57:34.998  6747  6747 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 14:57:34.998  6747  6747 D LGBluetoothEventManager: [BTUI] clear device connection state
08-30 14:57:34.998  3881  3881 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-30 14:57:35.000  6747  6747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 14:57:35.000  3881  3881 I art     : System.exit called, status: 0
08-30 14:57:35.000  3881  3881 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 14:57:35.003  1587  1587 D BluetoothAdapter: 385424078: getState() :  mService = null. Returning STATE_OFF
08-30 14:57:35.003  1587  1587 D BluetoothAdapter: 385424078: getState() :  mService = null. Returning STATE_OFF
,08-30 14:57:35.009  6747  6747 D DockEventReceiver: finishStartingService: stopping service
08-30 14:57:35.018   311  1368 V AudioFlinger: 3881 died, releasing its sessions
08-30 14:57:35.018   311  1368 V AudioFlinger:  pid 1835 @ 0
,08-30 14:57:35.018   311  1368 V AudioFlinger:  pid 3482 @ 1
08-30 14:57:35.018   311  1368 V AudioFlinger:  pid 3482 @ 2
08-30 14:57:35.018  6747  6747 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-30 14:57:35.083  1035  2016 I ActivityManager: Process com.android.bluetooth (pid 3881) has died
08-30 14:57:35.084  1035  2016 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-30 14:57:35.101  2169  2169 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 14:57:35.119  6789  6789 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 14:57:35.128  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 14:57:35.139  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:57:35.142  6747  6747 D BluetoothPermissionRequest: onReceive
,08-30 14:57:35.146  6747  6747 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 14:57:35.148  6747  6747 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-30 14:57:35.151  6747  6747 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 14:57:35.232  1035  1630 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6896 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-30 14:57:35.257  6873  6894 W FormManager: Network not available. Please check & try again.
,08-30 14:57:35.265  6873  6895 V FormManager: Network unavailable.
08-30 14:57:35.266  6747  6747 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 14:57:35.266  6747  6747 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-30 14:57:35.267  6747  6747 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-30 14:57:35.267  6747  6747 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 14:57:35.268  6747  6747 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 14:57:35.269  6873  6895 V FormManager: Network unavailable.
08-30 14:57:35.285  6747  6747 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 14:57:35.285  6747  6747 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 14:57:35.285  6747  6747 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
,08-30 14:57:35.285  6747  6747 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 14:57:35.285  6747  6747 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 14:57:35.286  6747  6747 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 14:57:35.290  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 14:57:35.291  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 14:57:35.294  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 14:57:35.294  1035  1936 I ActivityManager: Killing 6032:com.android.contacts/u0a19 (adj 15): empty #17
08-30 14:57:35.383  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 14:57:35.395  1035  1889 W libprocessgroup: failed to open /acct/uid_10019/pid_6032/cgroup.procs: No such file or directory
,08-30 14:57:35.415  6896  6896 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-30 14:57:35.415  6896  6896 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 14:57:35.416  6896  6896 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-30 14:57:35.416  6896  6896 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 14:57:35.423  4296  6915 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 14:57:35.426  4296  6916 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 14:57:35.432  4296  6916 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 14:57:35.433  6789  6789 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-30 14:57:35.433  6789  6789 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 14:57:35.433  6789  6789 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:57:35.439  6896  6896 D BluetoothAdapterApp: Loading JNI Library
08-30 14:57:35.443  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 14:57:35.448  6873  6918 W FormManager: Network not available. Please check & try again.
08-30 14:57:35.451  6873  6919 V FormManager: Network unavailable.
08-30 14:57:35.454  6873  6919 V FormManager: Network unavailable.
,08-30 14:57:35.459  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 14:57:35.471  6896  6896 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@7c7e07f Instance Count = 1
,08-30 14:57:35.474  6820  6820 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 14:57:35.475  6896  6896 D BluetoothAdapterApp: onCreate
08-30 14:57:35.475  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 14:57:35.475  6820  6820 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-30 14:57:35.490  6896  6896 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-30 14:57:35.490  6896  6896 D ProfileConfigQcom: Adding HeadsetService
08-30 14:57:35.491  6896  6896 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-30 14:57:35.491  6896  6896 D ProfileConfigQcom: Adding A2dpService
08-30 14:57:35.491  6896  6896 D ProfileConfigQcom: [BTUI] HidService is supported
08-30 14:57:35.491  6896  6896 D ProfileConfigQcom: Adding HidService
08-30 14:57:35.491  6896  6896 D ProfileConfigQcom: [BTUI] HealthService is supported
,08-30 14:57:35.492  6896  6896 D ProfileConfigQcom: Adding HealthService
08-30 14:57:35.492  6896  6896 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-30 14:57:35.492  6896  6896 D ProfileConfigQcom: [BTUI] PanService is supported
08-30 14:57:35.493  6896  6896 D ProfileConfigQcom: Adding PanService
,08-30 14:57:35.493  6896  6896 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 14:57:35.493  6896  6896 D ProfileConfigQcom: Adding GattService
08-30 14:57:35.494  6896  6896 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-30 14:57:35.494  6896  6896 D ProfileConfigQcom: Adding BluetoothMapService
08-30 14:57:35.494  6896  6896 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 14:57:35.496  6896  6896 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-30 14:57:35.501  6747  6747 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 14:57:35.503  6896  6896 V LGMDMManagerInternal: Create singleton instance
08-30 14:57:35.509  6820  6820 D LgDataFeature: LgDataFeature() Constructor: none
08-30 14:57:35.509  6820  6820 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 14:57:35.516  6820  6820 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-30 14:57:35.517  6820  6820 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-30 14:57:35.517  6820  6820 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-30 14:57:35.517  6820  6820 V SoundPool: doLoad: loading sample sampleID=1
08-30 14:57:35.518  6820  6923 V SoundPool: Start decode
08-30 14:57:35.518  6820  6923 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-30 14:57:35.519   311  1369 V MediaPlayerService: decode(23, 10857164, 17813)
08-30 14:57:35.519   311  1369 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-30 14:57:35.519   311  1369 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-30 14:57:35.519   311  1369 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-30 14:57:35.519   311  1369 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-30 14:57:35.519   311  1369 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-30 14:57:35.519   311  1369 V MediaPlayerService: player type = 3
08-30 14:57:35.519   311  1369 V AwesomePlayer: AwesomePlayer create()
08-30 14:57:35.519   311  1369 V AwesomePlayer: reset_l() 
08-30 14:57:35.519  6820  6820 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 14:57:35.519   311  1369 V AwesomePlayer: cancelPlayerEvents
08-30 14:57:35.519   311  1369 V AwesomePlayer: setAudioSink() 
08-30 14:57:35.520   311  1369 V AwesomePlayer: reset_l() 
08-30 14:57:35.520   311  1369 V AudioCache: notify(0xb5474a40, 8, 0, 0)
08-30 14:57:35.520   311  1369 V AudioCache: ignored
08-30 14:57:35.520   311  1369 V AwesomePlayer: cancelPlayerEvents
08-30 14:57:35.520   311  1369 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-30 14:57:35.520   311  1369 V AwesomePlayer: setDataSource_l dataSource
08-30 14:57:35.520   311  1369 V LGParserOSAL: SniffLGParser start
08-30 14:57:35.520   311  1369 V LGParserOSAL: MainType:5, SubType=0
08-30 14:57:35.520   311  1369 V LGParserOSAL: #### check Mime : application/ogg
08-30 14:57:35.520   311  1369 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-30 14:57:35.520   311  1369 E MediaExtractor: Use LGExtractor :application/ogg 
08-30 14:57:35.523  6552  6552 D UEI.SmartControl: QS Service created
08-30 14:57:35.524  6820  6820 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-30 14:57:35.525  6820  6820 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-30 14:57:35.525  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 14:57:35.538  6820  6820 V LGMDMManager: Create singleton instance
08-30 14:57:35.543  6552  6552 I UEI.SmartControl: Service initServices...
08-30 14:57:35.544  6552  6552 D UEI.SmartControl: QS start get config
08-30 14:57:35.549   311  1369 V LGParserOSAL: supported mime: application/ogg
08-30 14:57:35.549   311  1369 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-30 14:57:35.549   311  1369 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-30 14:57:35.549   311  1369 V AwesomePlayer: mBitrate = -1 bits/sec
08-30 14:57:35.549   311  1369 V AwesomePlayer: AudioTrack Setting
08-30 14:57:35.549   311  1369 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-30 14:57:35.549   311  1369 V AwesomePlayer: setAudioSource() 
08-30 14:57:35.549   311  1369 V MediaPlayerService: prepare
08-30 14:57:35.549   311  1369 V AwesomePlayer: prepareAsync_l() 
08-30 14:57:35.550   311  1369 V MediaPlayerService: wait for prepare
08-30 14:57:35.550   311  6924 V AwesomePlayer: onPrepareAsyncEvent() 
08-30 14:57:35.550   311  6924 V AwesomePlayer: initAudioDecoder() 
08-30 14:57:35.550   311  6924 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 14:57:35.550   311  6924 V AudioSystem: isOffloadSupported()
08-30 14:57:35.550   311  6924 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 14:57:35.550   311  6924 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 14:57:35.550   311  6924 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 14:57:35.550   311  6924 V AwesomePlayer: getUseOffload() = 0 
08-30 14:57:35.550   311  6924 V OMXCodec: OMXCodec::Create
08-30 14:57:35.550   311  6924 V OMXCodec: findMatchingCodecs()
08-30 14:57:35.550   311  6924 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-30 14:57:35.550   311  6924 V OMXCodec: matchingCodecs.size()=1
08-30 14:57:35.550   311  6924 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-30 14:57:35.552   311  6924 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-30 14:57:35.552   311  6924 V LGCodecAdapter: LG Codec Adapter start
08-30 14:57:35.552   311  6924 V OMXCodec: OMXCodec Createtor
08-30 14:57:35.552   311  6924 V OMXCodec: setComponentRole
08-30 14:57:35.552   311  6924 V OMXCodec: configureCodec protected=0
08-30 14:57:35.552   311  6924 V LGCodecAdapter: called getLGCodecSpecificData
08-30 14:57:35.552   311  6924 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-30 14:57:35.552   311  6924 V LGCodecOSAL: Called LGconfigureCodecMETA
08-30 14:57:35.553   311  6924 V LGCodecOSAL: Called LGconfigureCodecMSG
08-30 14:57:35.553   311  6924 V LGCodecOSAL: Not support LGCodec
08-30 14:57:35.554   311  6924 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 14:57:35.554   311  6924 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-30 14:57:35.554   311  6924 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-30 14:57:35.554   311  6924 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-30 14:57:35.554   311  6924 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 14:57:35.554   311  6924 V AudioSystem: isOffloadSupported()
08-30 14:57:35.555   311  6924 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 14:57:35.555   311  6924 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 14:57:35.555   311  6924 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-30 14:57:35.555   311  6924 V OMXCodec: init()
08-30 14:57:35.555   311  6924 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-30 14:57:35.555   311  6924 V OMXCodec: allocateBuffers
08-30 14:57:35.555   311  6924 V OMXCodec: allocateBuffersOnPort portIndex=0
08-30 14:57:35.555   311  6924 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-30 14:57:35.555   311  6924 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-30 14:57:35.555   311  6924 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-30 14:57:35.555   311  6924 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-30 14:57:35.555   311  6924 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
08-30 14:57:35.555   311  6924 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 14:57:35.555   311  6924 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 14:57:35.555   311  6924 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-30 14:57:35.555   311  6924 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f9380 on output port
08-30 14:57:35.555   311  6924 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f94c0 on output port
08-30 14:57:35.555   311  6924 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f96f0 on output port
08-30 14:57:35.555   311  6924 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 14:57:35.555   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 14:57:35.555   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 14:57:35.555   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
,08-30 14:57:35.556   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-30 14:57:35.556   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-30 14:57:35.556   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-30 14:57:35.561   311  6924 V OMXCodec: init() mAsyncCompletion wait free! 
08-30 14:57:35.561   311  6924 V AwesomePlayer: finishAsyncPrepare_l() 
08-30 14:57:35.561   311  6924 V AudioCache: notify(0xb5474a40, 5, 0, 0)
08-30 14:57:35.561   311  6924 V AudioCache: ignored
08-30 14:57:35.561   311  6924 V AudioCache: notify(0xb5474a40, 1, 0, 0)
08-30 14:57:35.561   311  6924 V AudioCache: prepared
,08-30 14:57:35.561   311  1369 V AudioCache: wait - success
08-30 14:57:35.561   311  1369 V MediaPlayerService: start
08-30 14:57:35.561   311  1369 V AwesomePlayer: play_l() 
,08-30 14:57:35.561   311  1369 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-30 14:57:35.561   311  1369 V AwesomePlayer: createAudioPlayer_l
08-30 14:57:35.561   311  1369 V AwesomePlayer: seekAudioIfNecessary_l() 
08-30 14:57:35.561   311  1369 V AwesomePlayer: startAudioPlayer_l() 
08-30 14:57:35.561   311  1369 D AudioPlayer: start of Playback, useOffload 0
08-30 14:57:35.561   311  1369 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 14:57:35.561   311  1369 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 14:57:35.563   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-30 14:57:35.563   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-30 14:57:35.563   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-30 14:57:35.563   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-30 14:57:35.563   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-30 14:57:35.563   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 14:57:35.563   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-30 14:57:35.563   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 14:57:35.563   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045036928
08-30 14:57:35.563   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 14:57:35.563   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045037248
08-30 14:57:35.563   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 14:57:35.564   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045037808
08-30 14:57:35.564   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 14:57:35.564   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,08-30 14:57:35.564   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 14:57:35.564   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-30 14:57:35.564   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-30 14:57:35.564   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-30 14:57:35.564   311  6926 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 14:57:35.564   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 14:57:35.564   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f94c0 on output port
08-30 14:57:35.564   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f9380 on output port
08-30 14:57:35.564   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-30 14:57:35.564   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on output port
08-30 14:57:35.564   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-30 14:57:35.564   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-30 14:57:35.565   311  1369 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-30 14:57:35.565   311  1369 V AudioCache: notify(0xb5474a40, 6, 0, 0)
08-30 14:57:35.565   311  1369 V AudioCache: ignored
08-30 14:57:35.565   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.565   311  6927 V AudioCache: memcpy(0xac300000, 0xb16ab000, 4096)
08-30 14:57:35.565   311  1369 V MediaPlayerService: wait for playback complete
08-30 14:57:35.567   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.567   311  6927 V AudioCache: memcpy(0xac301000, 0xb16ab000, 4096)
08-30 14:57:35.567   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.567   311  6927 V AudioCache: memcpy(0xac302000, 0xb16ab000, 4096)
08-30 14:57:35.568   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.568   311  6927 V AudioCache: memcpy(0xac303000, 0xb16ab000, 4096)
08-30 14:57:35.568   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.568   311  6927 V AudioCache: memcpy(0xac304000, 0xb16ab000, 4096)
08-30 14:57:35.568   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.568   311  6927 V AudioCache: memcpy(0xac305000, 0xb16ab000, 4096)
08-30 14:57:35.568   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.568   311  6927 V AudioCache: memcpy(0xac306000, 0xb16ab000, 4096)
08-30 14:57:35.569   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.569   311  6927 V AudioCache: memcpy(0xac307000, 0xb16ab000, 4096)
08-30 14:57:35.570   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.570   311  6927 V AudioCache: memcpy(0xac308000, 0xb16ab000, 4096)
08-30 14:57:35.570   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.570   311  6927 V AudioCache: memcpy(0xac309000, 0xb16ab000, 4096)
08-30 14:57:35.571   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.571   311  6927 V AudioCache: memcpy(0xac30a000, 0xb16ab000, 4096)
08-30 14:57:35.571   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.571   311  6927 V AudioCache: memcpy(0xac30b000, 0xb16ab000, 4096)
08-30 14:57:35.572   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.572   311  6927 V AudioCache: memcpy(0xac30c000, 0xb16ab000, 4096)
08-30 14:57:35.573   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.573   311  6927 V AudioCache: memcpy(0xac30d000, 0xb16ab000, 4096)
08-30 14:57:35.573   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.573   311  6927 V AudioCache: memcpy(0xac30e000, 0xb16ab000, 4096)
08-30 14:57:35.574   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.574   311  6927 V AudioCache: memcpy(0xac30f000, 0xb16ab000, 4096)
08-30 14:57:35.574   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.574   311  6927 V Au,dioCache: memcpy(0xac310000, 0xb16ab000, 4096)
08-30 14:57:35.574   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.574   311  6927 V AudioCache: memcpy(0xac311000, 0xb16ab000, 4096)
08-30 14:57:35.574   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.574   311  6927 V AudioCache: memcpy(0xac312000, 0xb16ab000, 4096)
08-30 14:57:35.575   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.575   311  6927 V AudioCache: memcpy(0xac313000, 0xb16ab000, 4096)
08-30 14:57:35.576   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.576   311  6927 V AudioCache: memcpy(0xac314000, 0xb16ab000, 4096)
08-30 14:57:35.576   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.576   311  6927 V AudioCache: memcpy(0xac315000, 0xb16ab000, 4096)
08-30 14:57:35.576   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.576   311  6927 V AudioCache: memcpy(0xac316000, 0xb16ab000, 4096)
08-30 14:57:35.577   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.577   311  6927 V AudioCache: memcpy(0xac317000, 0xb16ab000, 4096)
08-30 14:57:35.578   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.578   311  6927 V AudioCache: memcpy(0xac318000, 0xb16ab000, 4096)
08-30 14:57:35.578   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.578   311  6927 V AudioCache: memcpy(0xac319000, 0xb16ab000, 4096)
08-30 14:57:35.578   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.578   311  6927 V AudioCache: memcpy(0xac31a000, 0xb16ab000, 4096)
08-30 14:57:35.579   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.579   311  6927 V AudioCache: memcpy(0xac31b000, 0xb16ab000, 4096)
08-30 14:57:35.579   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.579   311  6927 V AudioCache: memcpy(0xac31c000, 0xb16ab000, 4096)
08-30 14:57:35.579   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.580   311  6927 V AudioCache: memcpy(0xac31d000, 0xb16ab000, 4096)
08-30 14:57:35.580   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.580   311  6927 V AudioCache: memcpy(0xac31e000, 0xb16ab000, 4096)
08-30 14:57:35.581   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.581   311  6927 V AudioCache: memcpy(0xac31f000, 0xb16ab000, 4096)
08-30 14:57:35.581   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.581   311  6927 V AudioCache: memcpy(0xac320000, 0xb16ab000, 4096)
08-30 14:57:35.581   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.581   311  6927 V AudioCache: memcpy(0xac321000, 0xb16ab000, 4096)
08-30 14:57:35.582   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.582   311  6927 V AudioCache: memcpy(0xac322000, 0xb16ab000, 4096)
08-30 14:57:35.582   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.582   311  6927 V AudioCache: memcpy(0xac323000, 0xb16ab000, 4096)
08-30 14:57:35.582  6896  6896 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:35.583   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.583   311  6927 V AudioCache: memcpy(0xac324000, 0xb16ab000, 4096)
08-30 14:57:35.583   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.583   311  6927 V AudioCache: memcpy(0xac325000, 0xb16ab000, 4096)
08-30 14:57:35.584   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.584   311  6927 V AudioCache: memcpy(0xac326000, 0xb16ab000, 4096)
08-30 14:57:35.584   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.584   311  6927 V AudioCache: memcpy(0xac327000, 0xb16ab000, 4096)
,08-30 14:57:35.585  6896  6896 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 14:57:35.585   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.585   311  6927 V AudioCache: memcpy(0xac328000, 0xb16ab000, 4096)
08-30 14:57:35.585  6896  6896 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 14:57:35.585   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.585   311  6927 V AudioCache: memcpy(0xac329000, 0xb16ab000, 4096)
08-30 14:57:35.585  6896  6896 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 14:57:35.585   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.585   311  6927 V AudioCache: memcpy(0xac32a000, 0xb16ab000, 4096)
,08-30 14:57:35.586  6896  6896 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:35.586   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.586   311  6927 V AudioCache: memcpy(0xac32b000, 0xb16ab000, 4096)
08-30 14:57:35.586  6896  6896 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-30 14:57:35.586   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.586   311  6927 V AudioCache: memcpy(0xac32c000, 0xb16ab000, 4096)
08-30 14:57:35.587   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.587   311  6927 V AudioCache: memcpy(0xac32d000, 0xb16ab000, 4096)
,08-30 14:57:35.587   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.587   311  6927 V AudioCache: memcpy(0xac32e000, 0xb16ab000, 4096)
08-30 14:57:35.588   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.588   311  6927 V AudioCache: memcpy(0xac32f000, 0xb16ab000, 4096)
08-30 14:57:35.589   311  6927 V AudioCache: write(0xb16ab000, 4096)
08-30 14:57:35.589   311  6927 V AudioCache: memcpy(0xac330000, 0xb16ab000, 4096)
08-30 14:57:35.589   311  6927 V AudioCache: write(0xb16ab000, 4096)
,08-30 14:57:35.589   311  6927 V AudioCache: memcpy(0xac331000, 0xb16ab000, 4096)
08-30 14:57:35.589   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-30 14:57:35.589   311  6927 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 14:57:35.590   311  6927 V AwesomePlayer: postAudioEOS() 
08-30 14:57:35.590   311  6927 V AudioCache: write(0xb16ab000, 280)
08-30 14:57:35.590   311  6927 V AudioCache: memcpy(0xac332000, 0xb16ab000, 280)
08-30 14:57:35.591   311  6924 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-30 14:57:35.591   311  6924 V AwesomePlayer: onStreamDone
,08-30 14:57:35.591   311  6924 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-30 14:57:35.591   311  6924 V AudioCache: notify(0xb5474a40, 2, 0, 0)
08-30 14:57:35.591   311  6924 V AudioCache: playback complete
08-30 14:57:35.591   311  6924 V AwesomePlayer: pause_l() 
,08-30 14:57:35.591   311  6924 V AudioCache: notify(0xb5474a40, 7, 0, 0),
08-30 14:57:35.591   311  6924 V AudioCache: ignored
08-30 14:57:35.591   311  6924 V AwesomePlayer: cancelPlayerEvents
08-30 14:57:35.592   311  1369 V AudioCache: wait - success
08-30 14:57:35.592   311  1369 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-30 14:57:35.592   311  6924 D AudioPlayer: Pause Playback at 1068125
08-30 14:57:35.592   311  1369 V AwesomePlayer: reset_l() 
08-30 14:57:35.592   311  1369 V AudioCache: notify(0xb5474a40, 8, 0, 0)
08-30 14:57:35.592   311  1369 V AudioCache: ignored
08-30 14:57:35.592   311  1369 V AwesomePlayer: cancelPlayerEvents
08-30 14:57:35.592   311  1369 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-30 14:57:35.592   311  1369 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-30 14:57:35.592   311  1369 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
,08-30 14:57:35.592   311  1369 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-30 14:57:35.592   311  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 14:57:35.592  6840  6840 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-30 14:57:35.594   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 14:57:35.594   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 14:57:35.594   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-30 14:57:35.594   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
08-30 14:57:35.594   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-30 14:57:35.594   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-30 14:57:35.594   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-30 14:57:35.594   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-30 14:57:35.594   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-30 14:57:35.594   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-30 14:57:35.594   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-30 14:57:35.594   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
,08-30 14:57:35.594   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 1
08-30 14:57:35.594   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-30 14:57:35.594   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-30 14:57:35.594   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-30 14:57:35.594   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57f9380 on port 1
08-30 14:57:35.594   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-30 14:57:35.594   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57f94c0 on port 1
08-30 14:57:35.594   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 14:57:35.594   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-30 14:57:35.595   311  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 14:57:35.595   311  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 14:57:35.595   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-30 14:57:35.595   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-30 14:57:35.595   311  6926 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
,08-30 14:57:35.595   311  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 14:57:35.595   311  1369 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-30 14:57:35.595   311  1369 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-30 14:57:35.596   311  1369 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-30 14:57:35.596   311  1369 D AudioPlayer: AudioPlayer releasing audio source
08-30 14:57:35.596   311  1369 D AudioPlayer: AudioPlayer done releasing audio source
08-30 14:57:35.596   311  1369 V AwesomePlayer: reset_l() 
08-30 14:57:35.596   311  1369 V AwesomePlayer: cancelPlayerEvents
08-30 14:57:35.596   311  1369 V AwesomePlayer: ~AwesomePlayer call
08-30 14:57:35.596   311  1369 V AwesomePlayer: reset_l() 
08-30 14:57:35.596   311  1369 V AwesomePlayer: cancelPlayerEvents
08-30 14:57:35.596  6820  6923 V SoundPool: close(31)
08-30 14:57:35.596  6820  6923 V SoundPool: pointer = 0x9fffb000, size = 205080, sampleRate = 48000, numChannels = 2
08-30 14:57:35.607  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-30 14:57:35.608  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-30 14:57:35.610  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1218
,08-30 14:57:35.807  6552  6552 I UEI.SmartControl: Supports setup maps: true
,08-30 14:57:35.810  6552  6552 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 14:57:35.810  6552  6552 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-30 14:57:35.810  6552  6552 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 14:57:35.810  6552  6552 I UEI.SmartControl: ### init IR Blaster...
08-30 14:57:35.814  6552  6552 D serial_port: Configuring serial port
08-30 14:57:35.814  6552  6552 E UEI.SmartControl: UEIBLaster setting for 616
08-30 14:57:35.814  6552  6552 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 14:57:35.814  6552  6552 I UEI.SmartControl: configuring settings for MAXQ616
08-30 14:57:35.814  6552  6552 I UEI.SmartControl: Get version...
08-30 14:57:35.833  6552  6929 D UEI.SmartControl: serial port data available: 21
,08-30 14:57:35.859  6552  6552 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-30 14:57:35.859  6552  6552 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 14:57:35.859  6552  6552 I UEI.SmartControl: QS saving settings...
08-30 14:57:35.861  6552  6552 D UEI.SmartControl: IR Blaster version: 25672567
08-30 14:57:35.880  6552  6929 D UEI.SmartControl: serial port data available: 4
,08-30 14:57:35.913  6552  6935 I UEI.SmartControl: Device manager: loading config....
,08-30 14:57:35.915  6552  6552 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-30 14:57:35.916  6552  6935 D UEI.SmartControl: ----------- loading internal config...
,08-30 14:57:35.920  6552  6552 E UEI.SmartControl: Services init done
,08-30 14:57:35.920  6552  6552 D UEI.SmartControl: QS Service init finished
08-30 14:57:35.922  6552  6552 D UEI.SmartControl: QS Service version name: 2.1.91
,08-30 14:57:35.923  6552  6552 D UEI.SmartControl: QS Service version code: 201091
08-30 14:57:35.923  6552  6552 D UEI.SmartControl: Service requested: Control
08-30 14:57:35.931  6552  6935 E UEI.SmartControl: Loading SETTINGS...
08-30 14:57:35.934  6552  6552 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-30 14:57:35.949  6552  6552 D UEI.SmartControl: Internal service binding...
08-30 14:57:35.950  6820  6820 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-30 14:57:35.955  6552  6568 I UEI.SmartControl: ------ IControl API: 11
08-30 14:57:35.955  6552  6568 D UEI.SmartControl: File observer start...
08-30 14:57:35.956  6552  6568 E UEI.SmartControl: IR Port is disabled: false
08-30 14:57:35.956  6552  6568 D UEI.SmartControl: Starting file observer...
08-30 14:57:35.957  6552  6568 I UEI.SmartControl: Registering callback...
08-30 14:57:35.958  6552  6566 I UEI.SmartControl: ------ IControl API: 19
,08-30 14:57:35.961  6552  6566 I UEI.SmartControl: Registering Services Ready callback...
08-30 14:57:35.965  6552  6935 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 14:57:35.973  6552  6934 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 14:57:35.973  6552  6934 D UEI.SmartControl: -----service ready thread exits
08-30 14:57:35.974  6820  6838 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-30 14:57:35.974  6820  6921 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-30 14:57:35.975  6820  6921 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-30 14:57:35.975  6820  6820 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-30 14:57:35.977  6820  6820 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-30 14:57:35.977  6552  6568 I UEI.SmartControl: ------ IControl API: 8
08-30 14:57:35.980  6820  6820 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-30 14:57:35.981  6820  6820 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-30 14:57:35.982  6820  6820 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-30 14:57:35.983  6820  6820 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-30 14:57:35.985  6820  6820 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
,08-30 14:57:35.986  6820  6820 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-30 14:57:35.988  6820  6820 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-30 14:57:35.993  6820  6820 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 14:57:35.994  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 14:57:35.995  6820  6820 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 14:57:35.995  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 14:57:35.996  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-30 14:57:35.997  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-30 14:57:35.998  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-30 14:57:35.999  6820  6820 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472561855999]
08-30 14:57:36.000  6820  6820 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-30 14:57:36.004  1035  1051 I ActivityManager: Killing 6055:com.android.gallery3d/u0a27 (adj 15): empty #17
08-30 14:57:36.025  6820  6940 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-30 14:57:36.042  1035  1051 I ActivityManager: Killing 6443:com.lge.email/u0a23 (adj 15): empty #18
,08-30 14:57:36.075  1035  1943 W libprocessgroup: failed to open /acct/uid_10027/pid_6055/cgroup.procs: No such file or directory
,08-30 14:57:36.094  1035  1630 W libprocessgroup: failed to open /acct/uid_10023/pid_6443/cgroup.procs: No such file or directory
,08-30 14:57:36.101  6820  6820 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-30 14:57:36.102  6820  6820 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-30 14:57:36.103  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-30 14:57:36.103  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-30 14:57:36.104  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-30 14:57:36.104  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-30 14:57:36.105  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-30 14:57:36.119  6820  6820 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-30 14:57:36.823  1035  1050 D WifiServiceImplEx: setWifiEnabled: true pid=6646, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 14:57:36.824  1035  1050 D WifiService: setWifiEnabled: true pid=6646, uid=10118
08-30 14:57:36.825  1035  1050 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 14:57:36.855  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 14:57:36.855  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 14:57:36.855  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-30 14:57:36.856  1035  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:36.864  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:57:36.869  1035  1117 D Tethering: MasterInitialState.processMessage what=3
08-30 14:57:36.869  1035  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:36.871  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:36.880  1035  1117 D Tethering: MasterInitialState.processMessage what=3
,08-30 14:57:36.888  1035  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-30 14:57:36.888  1035  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-30 14:57:36.889  1035  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-30 14:57:36.889  1035  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 14:57:36.889  1035  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-30 14:57:36.889  1035  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 14:57:36.889  1035  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 14:57:36.889  1035  1523 E WifiHW  : unknown target_country: EU , set to default
08-30 14:57:36.889  1035  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-30 14:57:36.889  1035  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 14:57:36.889  1035  1523 I WifiUtil: gEnableBmps=1
08-30 14:57:36.900  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:57:36.909  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:36.910  1035  1371 D PowerManagerServiceEx: acquireWakeLockInternal: lock=263854985, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
08-30 14:57:36.911  1035  1371 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2e8472ab type 2 when 179761 com.google.android.gms} when 179761
08-30 14:57:36.917  1035  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:57:36.921  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 14:57:36.925  6359  6788 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 14:57:36.947  2563  2563 D [Concierge]Service: onStartCommand(). Type : 9
,08-30 14:57:36.977  5773  5773 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 14:57:36.986  5773  5773 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 14:57:37.004  2169  2169 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:57:37.038  1035  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:57:37.078  1035  1559 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6959 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-30 14:57:37.085  1035  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:37.085  1035  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 14:57:37.147  6959  6959 I AppUp4:AppBoxCP: onCreate
,08-30 14:57:37.148  6959  6959 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-30 14:57:37.158  6959  6959 I AppUp4:DB:  setFingerPrint start
08-30 14:57:37.159  6959  6959 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-30 14:57:37.168  6959  6959 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-30 14:57:37.168  6959  6959 I AppUp4:DB:  SDK version = 21
,08-30 14:57:37.168  6959  6959 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-30 14:57:37.171  6959  6959 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-30 14:57:37.173  6959  6959 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 14:57:37.173  6959  6959 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:37.175  6959  6959 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 14:57:37.176  6959  6959 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 14:57:37.186  6959  6959 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 14:57:37.252  6959  6959 D LgDataFeature: LgDataFeature() Constructor: none
08-30 14:57:37.253  6959  6959 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 14:57:37.261  6959  6959 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1af7a111
08-30 14:57:37.261  6959  6959 D AppUp4:CustFacade: isCustomizationCompleted : false
,08-30 14:57:37.261  6959  6959 D AppUp4:CustFacade: isPhone : true
08-30 14:57:37.262  6959  6959 D AppUp4:CustModeStarterReceiver: begin check event
08-30 14:57:37.262  6959  6959 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
,08-30 14:57:37.263  6959  6959 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-30 14:57:37.264  6959  6977 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-30 14:57:37.264  6959  6977 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-30 14:57:37.264  6959  6977 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,08-30 14:57:37.270  1035  2034 I ActivityManager: Killing 6119:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-30 14:57:37.323  1035  1943 W libprocessgroup: failed to open /acct/uid_10080/pid_6119/cgroup.procs: No such file or directory
,08-30 14:57:37.327  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:37.327  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 14:57:37.329  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 14:57:37.333  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 14:57:37.348  4296  6983 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 14:57:37.352  4296  6984 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:37.352  4296  6984 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 14:57:37.402  1035  1051 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6985 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 14:57:37.514  6985  6985 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 14:57:37.515  6985  6985 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 14:57:37.516  6985  6985 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 14:57:37.517  6985  6985 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 14:57:37.614  6985  6985 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-30 14:57:37.652   305   893 D SoftapController: Softap fwReload - Ok
,08-30 14:57:37.656  1035  1523 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (761ms)
08-30 14:57:37.657  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 14:57:37.657  1035  1117 D Tethering: InitialState.processMessage what=4
08-30 14:57:37.660  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 14:57:37.661   305   893 D CommandListener: Setting iface cfg
08-30 14:57:37.662   305   893 D CommandListener: Trying to bring down wlan0
08-30 14:57:37.663   305   893 D CommandListener: Clearing all IP addresses on wlan0
08-30 14:57:37.663  6985  6985 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-30 14:57:37.672  1035  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-30 14:57:37.675  1035  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 14:57:37.675  1035  1523 E WifiStateMachine: useWiFiOffloading() : false
08-30 14:57:37.675  1035  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 14:57:37.679  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-30 14:57:37.681  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:37.681  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-30 14:57:37.682  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:37.683  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:37.674  7011  7011 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:57:37.686  1035  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 14:57:37.686  1035  1523 D WifiMonitor: connecting to supplicant
,08-30 14:57:37.674  7011  7011 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:57:37.716  6985  6985 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 14:57:37.720  7011  7011 I wpa_supplicant: Successfully initialized wpa_supplicant
08-30 14:57:37.754  6985  6985 D LgDataFeature: LgDataFeature() Constructor: none
08-30 14:57:37.754  6985  6985 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 14:57:37.755  7011  7011 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 14:57:37.755  7011  7011 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-30 14:57:37.812  7011  7011 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 14:57:37.828  1035  1371 V AlarmManager: ELAPSED_WAKEUP set : Alarm{39e37302 type 2 when 180702 com.google.android.gms} when 180702
,08-30 14:57:37.867  7011  7011 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-30 14:57:37.879  7011  7011 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-30 14:57:37.879  1035  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-30 14:57:37.879  1035  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 14:57:37.880  1035  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
,08-30 14:57:37.882  1035  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-30 14:57:37.883  1035  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:57:37.884  1035  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:57:37.885  1035  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:57:37.885  1035  7021 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-30 14:57:37.886  1035  7021 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 14:57:37.886  7011  7011 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 14:57:37.886  1035  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 14:57:37.886  1035  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 14:57:37.886  1035  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 14:57:37.886  1035  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-30 14:57:37.886  1035  7021 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 14:57:37.886  1035  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:57:37.886  1035  7021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-30 14:57:37.887  1035  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 14:57:37.888  1035  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-30 14:57:37.889  1035  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 14:57:37.889  1035  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-30 14:57:37.889  1035  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-30 14:57:37.890  1035  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 14:57:37.890  1035  1523 E WifiStateMachine: useWiFiOffloading() : false
08-30 14:57:37.890  1035  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 14:57:37.891  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:37.891  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:37.891  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:37.891  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:37.891  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 14:57:37.893  1035  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
,08-30 14:57:37.897  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:37.899  1925  1925 D WfdService: Waiting for WifiP2p enabling
08-30 14:57:37.900  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-30 14:57:37.900  1035  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-30 14:57:37.902  1035  1523 D WifiNative-wlan0: SET update_config 1: returned true
08-30 14:57:37.902  1035  1523 D WifiConfigStore: Loading config and enabling all networks 
08-30 14:57:37.902  1035  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 14:57:37.902  6646  6646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:57:37.902  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:57:37.902  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:37.902  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:37.902  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:57:37.902  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:57:37.902  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:57:37.902  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:57:37.902  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:57:37.902  6646  6646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:57:37.902  6646  6646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:57:37.902  1035  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-30 14:57:37.904  6646  6646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:57:37.904  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:57:37.904  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:37.904  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:37.904  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:57:37.904  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:57:37.904  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:57:37.904  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:57:37.904  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:57:37.904  6646  6646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:57:37.904  6646  6646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:57:37.909  1035  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-30 14:57:37.919  1035  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-30 14:57:37.919  6985  6985 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 14:57:37.919  1035  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 14:57:37.922  1035  1523 D WifiStateMachine: enableVerboseLogging : level 2
08-30 14:57:37.922  1035  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 14:57:37.923  1035  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-30 14:57:37.923  1035  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-30 14:57:37.923  1035  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 14:57:37.923  1035  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 14:57:37.924  1035  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 14:57:37.924  1035  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 14:57:37.924  1035  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-30 14:57:37.924  1035  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-30 14:57:37.924  1035  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 14:57:37.924  1035  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
,08-30 14:57:37.925  1035  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 14:57:37.925  1035  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 14:57:37.925  1035  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,08-30 14:57:37.927  1925  1925 D WfdsService: Supplicant Connection state is changed : true
08-30 14:57:37.927  1925  2320 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-30 14:57:37.927  1035  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 14:57:37.927  1035  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-30 14:57:37.928  1035  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 14:57:37.928  1035  1523 D WifiNative-HAL: Setting external_sim to 1
08-30 14:57:37.928  1035  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-30 14:57:37.928  1035  1523 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 14:57:37.928  1035  1523 I WifiNative-HAL: startHal
08-30 14:57:37.928  1925  2320 D WfdsService: Set the WFDS Monitor: true
08-30 14:57:37.928  1925  2320 D WfdsMonitor: WfdsMonitorThread create
08-30 14:57:37.928  1035  1523 D wifi    : setting scan oui 0x957ba0e0
08-30 14:57:37.928  1925  2320 D WfdsMonitor: WFDS Monitor is created and started
08-30 14:57:37.929  1925  2320 D WfdsService: WiFi: Supplicant connection re-established
08-30 14:57:37.929  1035  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 14:57:37.929  1035  1523 I WifiNative-HAL: startHal
08-30 14:57:37.929  1035  1523 D wifi    : setting scan oui 0x957ba0e0
08-30 14:57:37.929  1035  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 14:57:37.929  1035  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 14:57:37.929  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 14:57:37.929  7011  7011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 14:57:37.930  1925  7022 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 14:57:37.930  1035  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 14:57:37.930  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 14:57:37.930  1925  7022 E CtrlSupplicant: Succeed to open control connection
08-30 14:57:37.930  7011  7011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 14:57:37.930  1925  7022 E CtrlSupplicant: Succeed to open monitor connection
08-30 14:57:37.930  1035  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 14:57:37.930  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 14:57:37.931  7011  7011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-30 14:57:37.931  1925  7022 D WfdsMonitor: Supplicant connection established
08-30 14:57:37.931  1035  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 14:57:37.931  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 14:57:37.931  1925  2320 D WfdsService: Connected to the supplicant for wfds
08-30 14:57:37.931  7011  7011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 14:57:37.931  1035  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 14:57:37.931  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 14:57:37.931  7011  7011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 14:57:37.932  1035  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 14:57:37.932  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 14:57:37.932  7011  7011 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 14:57:37.932  1035  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 14:57:37.932  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 14:57:37.932  7011  7011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 14:57:37.933  1035  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 14:57:37.934  1035  1523 E WifiNative: : [180,807,602 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 14:57:37.934  1035  1523 D WifiNative-wlan0: doBoolean: RECONNECT
08-30 14:57:37.934  1035  1523 D W,ifiNative-wlan0: RECONNECT: returned true
08-30 14:57:37.934  1035  1523 D WifiNative-wlan0: doString: [STATUS]
08-30 14:57:37.934  1035  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 14:57:37.934  1035  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 14:57:37.934  1035  1523 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 14:57:37.935  1035  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 14:57:37.935  1035  1523 D WifiNative-wlan0: SET ps 1: returned true
08-30 14:57:37.936  1035  1521 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:37.936  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 14:57:37.937  1035  1035 D RttService: SCAN_AVAILABLE : 3
,08-30 14:57:37.937  1035  1540 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:37.937  1035  1540 I WifiNative-HAL: startHal
08-30 14:57:37.937  1035  1540 D wifi    : getting scan capabilities on interface[1] = 0x957ba0e0
08-30 14:57:37.937  1035  1540 D wifi    : failed to get capabilities : -3
08-30 14:57:37.937  1035  1540 E WifiScanningService: could not get scan capabilities
08-30 14:57:37.937  1035  1541 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:37.937   305   893 D CommandListener: Setting iface cfg
08-30 14:57:37.938   305   893 D CommandListener: Trying to bring up p2p0
08-30 14:57:37.938  1035  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 14:57:37.938  1035  1521 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 14:57:37.938  1035  1521 D LGWifiP2pService: P2pEnablingState
08-30 14:57:37.938  1035  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 14:57:37.938  1035  1521 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:37.938  1035  1521 D LGWifiP2pService: P2p socket connection successful
08-30 14:57:37.938  1035  1521 D LGWifiP2pService: P2pEnabledState
08-30 14:57:37.938  1035  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-30 14:57:37.939  1035  1521 D LGWifiP2pService: sending p2p connection changed broadcast
,08-30 14:57:37.939  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-30 14:57:37.941  1925  1925 D WfdsService: WifiP2pState is changed : true
08-30 14:57:37.941  1925  2320 D WfdsService: Receive the WFDS_ENABLE Method
08-30 14:57:37.941  1925  2320 D WfdsService: Set the WFDS Monitor: true
08-30 14:57:37.941  1925  2320 D WfdsService: Connected to the supplicant for wfds
08-30 14:57:37.941  1925  2320 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 14:57:37.941  7011  7011 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 14:57:37.941  1925  2320 D WfdsService: selectPreferredScanChannel [36]
08-30 14:57:37.941  1925  2320 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 14:57:37.943  1925  1925 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 14:57:37.943  1925  1925 D WfdsService: isConnected: false
08-30 14:57:37.944  1035  1521 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 14:57:37.944  1035  1521 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 14:57:37.945  1035  1521 D WifiNative-p2p0: doBoolean: SET device_name G3
08-30 14:57:37.945  1035  1521 D WifiNative-p2p0: SET device_name G3: returned true
08-30 14:57:37.945  1035  1521 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 14:57:37.945  1035  1521 D LGWifiP2pService: before postfix = G3
08-30 14:57:37.945  1035  1521 D WifiServerServiceExt: postfix byte check : 2
08-30 14:57:37.945  1035  1521 D LGWifiP2pService: after postfix = G3
08-30 14:57:37.945  1035  1521 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 14:57:37.946  1035  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 14:57:37.946  1035  1521 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 14:57:37.946  1035  1521 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 14:57:37.946  1035  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=180820  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 14:57:37.946  1035  1521 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 14:57:37.946  1035  1521 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-30 14:57:37.947  1035  1521 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 14:57:37.947  1035  1521 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 14:57:37.947  1035  1521 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 14:57:37.947  1035  1521 D WifiNative-HAL: p2pGetDeviceAddress
08-30 14:57:37.947  1035  1521 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-30 14:57:37.947  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=180822  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 14:57:37.948  1035  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 14:57:37.948  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:37.948  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:57:37.948  1035  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 14:57:37.948  1035  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 14:57:37.949  1035  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-30 14:57:37.949  7011  7011 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-30 14:57:37.949  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:37.949  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to and,roid.provider.Settings.Global, returning read-only value.
08-30 14:57:37.949  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 14:57:37.949  1035  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-30 14:57:37.950  1035  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-30 14:57:37.950  1035  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 14:57:37.950  1035  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-30 14:57:37.950  7011  7011 E wpa_supplicant: disconnect_rssi_lvl: -100
08-30 14:57:37.951  1035  1523 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
,08-30 14:57:37.953  1035  1521 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
,08-30 14:57:37.953  1035  1521 D WifiNative-p2p0: doBoolean: P2P_FLUSH
,08-30 14:57:37.953  1035  1521 D WifiNative-p2p0: P2P_FLUSH: returned true
08-30 14:57:37.953  1035  1521 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 14:57:37.954  1035  1521 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-30 14:57:37.954  1035  1521 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 14:57:37.954  1035  1521 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 14:57:37.954  1035  1521 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-30 14:57:37.955  1035  1523 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 14:57:37.955  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:37.955  1925  1925 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 14:57:37.956  1035  1523 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 14:57:37.956  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-30 14:57:37.957  1925  1925 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 14:57:37.957  1925  1925 D WfdsService: Update P2p Interface State: 3
08-30 14:57:37.962  6985  6985 I HubEmail: JNI_OnLoad()
08-30 14:57:37.962  6985  6985 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 14:57:37.962  6985  6985 I HubEmail: registerNatives()
08-30 14:57:37.962  6985  6985 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 14:57:37.962  6985  6985 I HubEmail: registerNativeMethods()
08-30 14:57:37.962  6985  6985 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 14:57:37.962  6985  6985 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-30 14:57:37.963  1035  1521 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-30 14:57:37.963  1035  1521 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-30 14:57:37.964  7011  7011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 14:57:37.965  7011  7011 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:57:37.965  1035  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 14:57:37.965  1035  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:57:37.965  1035  7021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:57:37.965  1035  7021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:57:37.965  7011  7011 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 14:57:37.966  7011  7011 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:37.966  1035  7021 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:57:37.966  1035  7021 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:37.966  1035  7021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:37.966  1035  7021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:37.966  7011  7011 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:37.966  1035  7021 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:57:37.966  1035  7021 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:37.967  1035  7021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:37.967  1035  7021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:37.967  1925  7022 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER t,ype=WORLD]
08-30 14:57:37.967  1925  7022 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:57:37.968  1035  1523 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-30 14:57:37.968  1035  1523 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 14:57:37.968  1035  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 14:57:37.969  1035  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-30 14:57:37.969  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-30 14:57:37.969  7011  7011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 14:57:37.969  7011  7011 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 14:57:37.969  1035  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 14:57:37.969  1035  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 14:57:37.969  1035  7021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 14:57:37.969  1035  7021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-30 14:57:37.970  3482  3482 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 14:57:37.970  3482  3482 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:37.971  3482  3482 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 14:57:37.971  1035  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 14:57:37.971  1035  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 14:57:37.971  1035  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 14:57:37.971  1035  1523 D WifiNative-wlan0: doBoolean: SCAN
08-30 14:57:37.972  1035  1523 D WifiNative-wlan0: SCAN: returned false
08-30 14:57:37.973  1035  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=180847  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 14:57:37.973  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=180848  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 14:57:37.974  1035  1523 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 14:57:37.974  1035  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 14:57:37.975  1035  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 14:57:37.975  1035  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 14:57:37.975  1035  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 14:57:37.976  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:37.976  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:37.976  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 14:57:37.983  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:37.983  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 14:57:37.984  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:38.012  1035  1943 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7028 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-30 14:57:38.020  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:57:38.020  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
08-30 14:57:38.020  1035  1521 D LGWifiP2pService: InactiveState
08-30 14:57:38.021  1035  1521 D LGWifiP2pService: InactiveState{ when=-67ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:38.021  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-67ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:38.021  1035  1521 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-30 14:57:38.022  7011  7011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 14:57:38.022  7011  7011 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:57:38.023  1035  7021 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 14:57:38.023  1035  7021 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:57:38.023  1035  7021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:57:38.023  1035  7021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:57:38.023  1925  7022 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 14:57:38.024  7011  7011 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 14:57:38.025  7011  7011 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:38.026  1035  1521 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 14:57:38.026  1035  1521 D LGWifiP2pService: InactiveState{ when=-58ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:38.026  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-59ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
,08-30 14:57:38.026  1035  1521 D LGWifiP2pService: InactiveState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 14:57:38.027  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:38.027  1035  1521 D LGWifiP2pService: DefaultState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:38.027  7011  7011 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:38.027  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:57:38.027  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
08-30 14:57:38.029  1035  7021 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:57:38.029  1035  7021 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:38.029  1035  7021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:38.029  1035  7021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:38.029  1035  7021 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:57:38.029  1035  7021 E WifiMonitor: WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:38.029  1035  7021 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:38.029  1035  7021 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:38.029  1925  7022 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:57:38.029  1925  7022 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-30 14:57:38.031  1035  1521 D LGWifiP2pService: InactiveState{ when=-10ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:38.031  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:38.031  1035  1521 D LGWifiP2pService: DefaultState{ when=-10ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:38.031  1035  1521 D LGWifiP2pService: InactiveState{ when=-10ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:38.031  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:38.031  1035  1521 D LGWifiP2pService: DefaultState{ when=-10ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:38.031  1035  1521 D LGWifiP2pService: InactiveState{ when=-11ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:38.031  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:38.032  1035  1521 D LGWifiP2pService: DefaultState{ when=-11ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:38.032  1035  1035 E WifiServerServiceExt: No p2p device connected
08-30 14:57:38.033  6873  7024 W FormManager: Network not available. Please check & try again.
08-30 14:57:38.033  1925  2320 W WfdsService: DefaultState - msg [9441285] is not handled,
08-30 14:57:38.034  6985  7027 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:38.036  6873  7026 V FormManager: Network unavailable.
,08-30 14:57:38.038  6873  7026 V FormManager: Network unavailable.
,08-30 14:57:38.045  1035  1979 I ActivityManager: Killing 6476:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-30 14:57:38.111  1035  2016 W libprocessgroup: failed to open /acct/uid_10061/pid_6476/cgroup.procs: No such file or directory
08-30 14:57:38.192  7028  7028 D LgDataFeature: LgDataFeature() Constructor: none
08-30 14:57:38.193  7028  7028 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 14:57:38.196  7028  7028 D PhoneMonitor: Register our PhoneStateListener
08-30 14:57:38.220  7028  7028 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-30 14:57:38.224  7028  7028 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 14:57:38.246  7028  7028 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-30 14:57:38.247  7028  7028 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-30 14:57:38.248  7028  7028 D TelephonyAutoProfiling: [parse] Load xml
08-30 14:57:38.254  7028  7028 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-30 14:57:38.255  7028  7028 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-30 14:57:38.255  7028  7028 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-30 14:57:38.255  7028  7028 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-30 14:57:38.255  7028  7028 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-30 14:57:38.255  7028  7028 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-30 14:57:38.255  7028  7028 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-30 14:57:38.255  7028  7028 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-30 14:57:38.255  7028  7028 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-30 14:57:38.255  7028  7028 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-30 14:57:38.255  7028  7028 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-30 14:57:38.255  7028  7028 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-30 14:57:38.256  7028  7028 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-30 14:57:38.256  7028  7028 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-30 14:57:38.256  7028  7028 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-30 14:57:38.256  7028  7028 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-30 14:57:38.256  7028  7028 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-30 14:57:38.264  7028  7028 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-30 14:57:38.300  1035  1908 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7047 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 14:57:38.303  1035  1908 I ActivityManager: Killing 6137:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-30 14:57:38.384  1035  1050 W libprocessgroup: failed to open /acct/uid_10097/pid_6137/cgroup.procs: No such file or directory
,08-30 14:57:38.426  1035  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-30 14:57:38.426  1035  7021 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 14:57:38.426  1035  7021 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-30 14:57:38.426  1035  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-30 14:57:38.426  1035  7021 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
,08-30 14:57:38.427  7011  7011 E wpa_supplicant: USIM:  scard_init function
,08-30 14:57:38.428  7011  7011 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-30 14:57:38.430  1035  1523 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-30 14:57:38.431  1035  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-30 14:57:38.431  1035  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-30 14:57:38.432  1035  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-30 14:57:38.432  1035  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-30 14:57:38.432  1035  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-30 14:57:38.432  1035  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-30 14:57:38.445  1035  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=181319  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 14:57:38.449  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=181323  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 14:57:38.450  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:38.450  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:38.450  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-30 14:57:38.453  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:38.453  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:57:38.455  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:38.457  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:57:38.457  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-30 14:57:38.556  7011  7011 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-30 14:57:38.557  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 14:57:38.560  1035  1523 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:57:38.560  1035  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:57:38.561  1035  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:57:38.561  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:57:38.561  1035  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-30 14:57:38.574  1035  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-30 14:57:38.574  1035  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,08-30 14:57:38.577  1035  7021 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-30 14:57:38.577  1035  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-30 14:57:38.577  1035  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 14:57:38.577  1035  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 14:57:38.579  1035  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=181453  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 14:57:38.579  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=181454  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 14:57:38.580  1035  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=181454
08-30 14:57:38.580  1035  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=181454
08-30 14:57:38.580  1035  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=181455
08-30 14:57:38.581  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=181455
08-30 14:57:38.581  1035  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=181455
08-30 14:57:38.581  1035  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=181456  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 14:57:38.583  7011  7011 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 14:57:38.583  7011  7011 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 14:57:38.584  1035  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 14:57:38.584  1035  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 14:57:38.585  1035  7021 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 14:57:38.585  1035  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 14:57:38.585  1035  7021 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 14:57:38.585  1035  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 14:57:38.585  1035  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 14:57:38.585  1035  7021 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 14:57:38.585  1035  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 14:57:38.585  1035  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 14:57:38.586  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:38.586  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:57:38.587  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-,only value.
08-30 14:57:38.587  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:38.587  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-30 14:57:38.589  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:38.594  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:38.594  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:38.595  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 14:57:38.596  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=181470  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 14:57:38.597  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:57:38.597  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-30 14:57:38.598  1035  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=181472  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 14:57:38.599  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=181473  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 14:57:38.599  1035  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=181474
08-30 14:57:38.600  1035  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=181474
08-30 14:57:38.600  1035  1523 D WifiNative-wlan0: doString: [STATUS]
08-30 14:57:38.601  1035  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 14:57:38.601  1035  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 14:57:38.601  1035  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 14:57:38.602  1035  1523 I WifiServiceExtension: setVHTCapabilityType  : false
,08-30 14:57:38.609  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:38.609  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:57:38.609  1035  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 14:57:38.609  1035  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-30 14:57:38.611  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:38.615  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:38.615  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:38.615  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 14:57:38.618  1035  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-30 14:57:38.618  1035  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 14:57:38.618  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:38.618  1035  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 14:57:38.618  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:38.618  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 14:57:38.618  1035  1529 D ConnectivityService: Got NetworkAgent Messenger
08-30 14:57:38.618  1035  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 14:57:38.618  1035  1529 D ConnectivityService: NetworkAgent connected
08-30 14:57:38.618  1035  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 14:57:38.618  1035  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 14:57:38.628  1035  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 14:57:38.631  1035  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 14:57:38.631  1035  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-30 14:57:38.634  1035  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 14:57:38.634  1035  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 14:57:38.636  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:38.636  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:57:38.637  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:38.639  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:38.639  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:57:38.640  1035  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 14:57:38.643  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:38.645   305   893 D CommandListener: Setting iface cfg
,08-30 14:57:38.652  1035  2034 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7081 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-30 14:57:38.653  1035  1523 E WifiStateMachine: Start Dhcp Watchdog 2
08-30 14:57:38.653  1035  7080 D DhcpStateMachine: StoppedState
08-30 14:57:38.653  1035  7080 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:38.653  1035  7080 D DhcpStateMachine: WaitBeforeStartState
08-30 14:57:38.653  1035  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=181528  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 14:57:38.654  1035  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=181528  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 14:57:38.654  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=181528  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 14:57:38.655  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:57:38.655  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-30 14:57:38.657  1035  2034 I ActivityManager: Killing 6509:com.lge.eula/1000 (adj 15): empty #17
,08-30 14:57:38.705  1035  1969 W libprocessgroup: failed to open /acct/uid_1000/pid_6509/cgroup.procs: No such file or directory
,08-30 14:57:38.706  1035  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=181580  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 14:57:38.706  1035  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=181580  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 14:57:38.707  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=181581  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 14:57:38.708  1035  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:136219] from screen [on:0 period:-611923820] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 14:57:38.709  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-611923819] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 14:57:38.709  1035  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 14:57:38.719  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:57:38.719  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,08-30 14:57:38.723  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:38.724  1035  1529 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-30 14:57:38.724  1035  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:38.725  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:38.725  1035  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:38.726  1035  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:38.726  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:38.727  1035  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:38.727  1035  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 14:57:38.727  1035  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=129,0,0
08-30 14:57:38.728  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=129,0,0
08-30 14:57:38.728  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-30 14:57:38.729  7011  7011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-30 14:57:38.729  1035  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-30 14:57:38.730  1035  1523 D WifiNative-wlan0: doBoolean: SET ps 0
08-30 14:57:38.730  1035  1523 D WifiNative-wlan0: SET ps 0: returned true
08-30 14:57:38.730  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 14:57:38.730  7011  7011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-30 14:57:38.731  1035  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-30 14:57:38.731  1035  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 14:57:38.731  1035  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 14:57:38.731  1035  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 14:57:38.731  1035  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2362b186 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:38.731  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2362b186 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:38.732  1035  7080 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:38.732  1035  7080 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 14:57:38.732   305   893 D CommandListener: Setting iface cfg
08-30 14:57:38.732   305   893 D CommandListener: Trying to bring up wlan0
08-30 14:57:38.734  1035  1523 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-30 14:57:38.735  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:57:38.735  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 14:57:38.736  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-30 14:57:38.736  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-30 14:57:38.737  1035  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,08-30 14:57:38.738  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:38.738  1035  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:38.738  1035  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:38.739  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:38.739  1035  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:38.740  1035  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 14:57:38.740  1035  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 14:57:38.740  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,08-30 14:57:38.741  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 14:57:38.741  1035  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:38.741  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:38.741  7011  7011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 14:57:38.742  1035  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 14:57:38.742  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 14:57:38.742  7011  7011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-30 14:57:38.742  1035  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 14:57:38.742  1035  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 14:57:38.763  1035  1523 D WifiNative-wlan0: SET ps 1: returned true
08-30 14:57:38.764  1035  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-30 14:57:38.766  1035  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0,
08-30 14:57:38.768  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 14:57:38.768  1035  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 14:57:38.770  1035  1529 D ConnectivityService: ignoring duplicate network state non-change,
08-30 14:57:38.805  1035  1521 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:38.805  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:38.805  1035  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler },
,08-30 14:57:38.812  1035  1943 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7102 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 14:57:38.813  1035  1943 I ActivityManager: Killing 6526:com.lge.bnr/1000 (adj 15): empty #17
08-30 14:57:38.896  1035  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 14:57:38.897  1035  1529 D ConnectivityService: Adding iface wlan0 to network 101
,08-30 14:57:38.906  1035  2034 W libprocessgroup: failed to open /acct/uid_1000/pid_6526/cgroup.procs: No such file or directory
,08-30 14:57:38.915  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 14:57:38.915  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:38.915  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 14:57:38.915  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:38.915  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 14:57:38.920  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:38.928  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:38.928  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 14:57:38.928  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 14:57:38.932  1035  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 14:57:38.935  1035  7080 D DhcpStateMachine: DHCPV4 request on wlan0
08-30 14:57:38.935  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 14:57:38.935  1035  7080 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-30 14:57:38.935  1035  7080 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-30 14:57:38.939  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-30 14:57:38.934  7121  7121 W dhcpcd  : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:57:38.943  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 14:57:38.943  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:57:38.934  7121  7121 W dhcpcd  : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:57:38.945  1035  1529 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 14:57:38.945  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:38.945  1035  1529 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-30 14:57:38.947  1035  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 14:57:38.948  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 14:57:38.948  1035  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 14:57:38.949  1035  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 14:57:38.949  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 14:57:38.950  1035  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 14:57:38.952  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:38.953  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:38.953  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:38.953  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 14:57:38.953  1035  1529 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-30 14:57:38.954   305   893 E Netd    : netlink response contains error (File exists)
08-30 14:57:38.954  1035  1529 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-30 14:57:38.954  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 14:57:38.955  1035  1529 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 14:57:38.955  1035  1529 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
,08-30 14:57:38.955  1035  1529 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-30 14:57:38.956  7121  7121 I dhcpcd  : version 5.5.6 starting
,08-30 14:57:38.958  7121  7121 E dhcpcd  : get_duid: m
08-30 14:57:38.958  7121  7121 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 14:57:38.958  7121  7121 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-30 14:57:38.959  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 14:57:38.959  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:38.963  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:38.963  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:38.963  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 14:57:38.964  1035  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 14:57:38.964  1035  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-30 14:57:38.964  1035  1529 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-30 14:57:38.964  1035  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-30 14:57:38.964  1035  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 14:57:38.964  1035  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:57:38.964  1035  7071 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:38.964  1035  7071 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-30 14:57:38.964  1035  7071 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:38.964  1035  7071 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 14:57:38.964  1035  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 14:57:38.966  1035  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:57:38.966  1035  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 14:57:38.966  1035  1529 D ConnectivityService: currentScore = 0, newScore = 20
08-30 14:57:38.966  1035  1529 D ConnectivityService:    accepting network in place of null
08-30 14:57:38.966  1035  1529 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:57:38.967  1035  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:57:38.967  1035  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 14:57:38.967   305  7124 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-30 14:57:38.967  1835  1835 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:57:38.967  1835  1835 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&T,ETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 14:57:38.968  1035  1529 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 14:57:38.968  1035  1529 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 14:57:38.968  1035  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 14:57:38.968  1035  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:38.969  1035  1529 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 14:57:38.969  1035  1529 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-30 14:57:38.970  1035  1529 D ConnectivityService: validation of new default Network = false
08-30 14:57:38.970  1035  1529 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 14:57:38.970  1035  1529 D DSQN    : enableDataServiceNotify 
08-30 14:57:38.970  1035  1529 D DSQN    : start dsqn bin
08-30 14:57:38.976  1035  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-30 14:57:38.976  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:57:38.976  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:57:38.976  1035  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:57:38.976  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-30 14:57:38.977  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 14:57:38.977  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 14:57:38.977  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-30 14:57:38.964  7126  7126 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:57:38.964  7126  7126 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:57:38.984  1587  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 14:57:38.985  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:38.985  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 14:57:38.988  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 14:57:38.993  7126  7126 E DSQN    : DSQN ssw
08-30 14:57:38.996  1035  1520 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-30 14:57:39.011  7121  7121 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 14:57:39.011  7121  7121 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 14:57:39.011  7121  7121 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 14:57:39.011  7121  7121 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 14:57:39.012  7121  7121 D dhcpcd  : wlan0: sending REQUEST (xid 0x7ea847a3), next in 4.98 seconds
08-30 14:57:39.015  1800  7134 I CheckinService: active receiver: enabled
08-30 14:57:39.016  7102  7102 I art     : Almond Protected OAT
,08-30 14:57:39.023  1800  7134 I CheckinService: Preparing to send checkin request
08-30 14:57:39.023  1800  7134 I EventLogService: Accumulating logs since 1472561734674
08-30 14:57:39.028  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-30 14:57:39.028  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:39.029  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:39.035  7121  7121 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-30 14:57:39.053  7121  7121 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-30 14:57:39.053  7121  7121 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-30 14:57:39.053  7102  7102 D WeatherApplication: removeAccount
08-30 14:57:39.053  7121  7121 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-30 14:57:39.053  7121  7121 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-30 14:57:39.053  7121  7121 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 14:57:39.053  7121  7121 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 14:57:39.053  7121  7121 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 14:57:39.053  7121  7121 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-30 14:57:39.054  1800  7134 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-30 14:57:39.054  7102  7102 D WeatherApplication: Account.length = 0
08-30 14:57:39.054  7102  7102 E WeatherApplication: OPERATOR:OPEN
,08-30 14:57:39.057  7102  7102 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:57:39
08-30 14:57:39.059  7102  7102 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 14:57:39.059  7102  7102 D Weather.Utils: 2 : All the weather widget is gone.
08-30 14:57:39.060  7102  7102 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 14:57:39.062  7102  7102 D WeatherAncestor: connectivity changed - connection : true
08-30 14:57:39.063  7102  7102 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-30 14:57:39.070  7102  7102 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 14:57:39.070  7102  7102 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 14:57:39.070  7102  7102 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-30 14:57:39.085  7102  7102 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 14:57:39.086  7102  7102 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:57:39
08-30 14:57:39.122  1035  1051 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7147 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 14:57:39.123  1035  1051 I ActivityManager: Killing 2110:com.lge.music/u0a34 (adj 15): empty #17
,08-30 14:57:39.148   311   311 V AudioFlinger: 2110 died, releasing its sessions
,08-30 14:57:39.148   311   311 V AudioFlinger:  pid 1835 @ 0
08-30 14:57:39.148   311   311 V AudioFlinger:  pid 3482 @ 1
08-30 14:57:39.148   311   311 V AudioFlinger:  pid 3482 @ 2
08-30 14:57:39.173  1035  1908 W libprocessgroup: failed to open /acct/uid_10034/pid_2110/cgroup.procs: No such file or directory
,08-30 14:57:39.240   278   413 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 14:57:39.240   278   413 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,08-30 14:57:39.240   278   413 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 14:57:39.241  7147  7176 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-30 14:57:39.243   278   413 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 14:57:39.243   278   413 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 14:57:39.243   278   413 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 14:57:39.243  7147  7176 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 14:57:39.243  1035  1908 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7177 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-30 14:57:39.264   278   413 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 14:57:39.264   278   413 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 14:57:39.264   278   413 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 14:57:39.264  7147  7188 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-30 14:57:39.266   278   413 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 14:57:39.266   278   413 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 14:57:39.266   278   413 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 14:57:39.267  7147  7188 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 14:57:39.283  7177  7177 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 14:57:39.283  7177  7177 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 14:57:39.299  7177  7177 I MultiDex: VM with version 2.1.0 has multidex support
08-30 14:57:39.299  7177  7177 I MultiDex: install
08-30 14:57:39.299  7177  7177 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 14:57:39.312  7177  7177 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-30 14:57:39.337  1035  7080 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-30 14:57:39.338  1035  7080 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-30 14:57:39.338  1035  7080 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 14:57:39.338  1035  7080 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
,08-30 14:57:39.338  1035  7080 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-30 14:57:39.338  1035  7080 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 14:57:39.338  1035  7080 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-30 14:57:39.338  1035  7080 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-30 14:57:39.339  1035  7080 D DhcpStateMachine: RunningState
08-30 14:57:39.472  7147  7147 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-30 14:57:39.487  7147  7147 I LibraryLoader: Loading: webviewchromium
08-30 14:57:39.490  7147  7147 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2374-2377)
08-30 14:57:39.490  7147  7147 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 14:57:39.495  7147  7147 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3f95e880}
08-30 14:57:39.497  7147  7147 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 14:57:39.497  7147  7147 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 14:57:39.509  7147  7147 I BrowserStartupController: Initializing chromium process, renderers=0
,08-30 14:57:39.510  7147  7147 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 14:57:39.519  7147  7147 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-30 14:57:39.520  7147  7147 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-30 14:57:39.520  7147  7147 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-30 14:57:39.528   311  2117 V AudioPolicyService: registerClient() client 0xb558ada0, uid 10093
,08-30 14:57:39.530  7147  7222 W AudioManagerAndroid: Requires BLUETOOTH permission
08-30 14:57:39.537  7147  7147 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 14:57:39.537  7147  7147 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 14:57:39.537  7147  7147 I Adreno-EGL: Build Date: 12/12/14 금
08-30 14:57:39.537  7147  7147 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 14:57:39.537  7147  7147 I Adreno-EGL: Remote Branch: 
08-30 14:57:39.537  7147  7147 I Adreno-EGL: Local Patches: 
08-30 14:57:39.537  7147  7147 I Adreno-EGL: Reconstruct Branch: 
08-30 14:57:39.565  7177  7196 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 14:57:39.565  7177  7196 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 14:57:39.735  7235  7235 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-30 14:57:39.746  1035  1943 I art     : Explicit concurrent mark sweep GC freed 99705(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.122ms total 137.154ms
08-30 14:57:39.749  7147  7147 I NSApplication: Starting up...
08-30 14:57:39.813  1035  1908 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7243 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-30 14:57:39.815  1035  1908 I ActivityManager: Killing 6079:com.android.vending/u0a44 (adj 15): empty #17
,08-30 14:57:39.817  7235  7235 I dex2oat : dex2oat took 81.485ms (threads: 4)
08-30 14:57:39.831  7177  7196 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 14:57:39.831  7177  7196 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 14:57:39.831  7177  7196 I Adreno-EGL: Build Date: 12/12/14 금
08-30 14:57:39.831  7177  7196 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 14:57:39.831  7177  7196 I Adreno-EGL: Remote Branch: 
08-30 14:57:39.831  7177  7196 I Adreno-EGL: Local Patches: 
08-30 14:57:39.831  7177  7196 I Adreno-EGL: Reconstruct Branch: 
,08-30 14:57:39.893  1035  1888 W libprocessgroup: failed to open /acct/uid_10044/pid_6079/cgroup.procs: No such file or directory
,08-30 14:57:39.903  1035  1051 D WifiServiceImplEx: setWifiEnabled: false pid=6646, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 14:57:39.903  1035  1051 D WifiService: setWifiEnabled: false pid=6646, uid=10118
08-30 14:57:39.903  1035  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 14:57:39.921  1035  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 14:57:39.921  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 14:57:39.922  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-30 14:57:39.922  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 14:57:39.922  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-30 14:57:39.922  1035  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 14:57:39.922  1035  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 14:57:39.923  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 14:57:39.923  1035  1523 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 14:57:39.924  1035  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 14:57:39.924  1035  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 14:57:39.924  1035  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 14:57:39.924  1035  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 14:57:39.931  1035  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 14:57:39.931  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 14:57:39.932  1035  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:39.932  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:39.932  7011  7011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 14:57:39.933  1035  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 14:57:39.933  1035  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 14:57:39.933  7243  7243 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 14:57:39.934  1035  1523 D WifiNative-wlan0: SET ps 1: returned true
,08-30 14:57:39.934  1035  7080 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:39.938   305   893 D CommandListener: Clearing all IP addresses on wlan0
08-30 14:57:39.972  1035  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 14:57:39.972  1035  1529 D ConnectivityService: ignoring duplicate network state non-change
08-30 14:57:39.972  1035  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-30 14:57:39.973  1035  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,08-30 14:57:39.974  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:39.974  1035  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:39.975  1035  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:39.975  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:39.976  1035  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:39.976  1035  1523 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 14:57:39.976  1035  1521 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:39.976  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:39.976  1035  1521 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@381a0817
08-30 14:57:39.976  1035  1521 D LGWifiP2pService: P2pDisablingState
08-30 14:57:39.977  1035  1521 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:39.977  1035  1521 D LGWifiP2pService: p2p socket connection lost
08-30 14:57:39.977  1035  1521 D LGWifiP2pService: P2pDisabledState
08-30 14:57:39.977  1035  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 14:57:39.978  1035  1521 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:39.978  1035  1521 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 14:57:39.979  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 14:57:39.979  7011  7011 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 14:57:39.980  1035  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 14:57:39.980  1035  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 14:57:39.980  1035  1523 D WifiNative-wlan0: SET ps 1: returned true
08-30 14:57:39.983  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-30 14:57:39.984  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:39.984  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:57:39.986  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-30 14:57:39.986  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:39.986  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:39.986  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 14:57:39.986  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-30 14:57:39.987  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:39.990  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:39.990  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:57:39.991  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:39.991  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:39.991  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 14:57:39.991  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 14:57:39.996  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 14:57:39.996  1035  1540 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 14:57:39.997  1035  1035 D RttService: SCAN_AVAILABLE : 1
08-30 14:57:39.997  1035  1541 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:39.998  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 14:57:39.999  1925  1925 D WfdsService: WifiP2pState is changed : false
08-30 14:57:39.999  1925  2320 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 14:57:39.999  1925  2320 D WfdsService: Set the WFDS Monitor: false
08-30 14:57:40.000  1925  2320 D WfdsMonitor: WFDS Monitor is stopped
08-30 14:57:40.000  1925  2320 D WfdsService: STATE : WfdsDisabledState - enter
08-30 14:57:40.000  1925  7022 D CtrlSupplicant: Received on exit socket, terminate
08-30 14:57:40.000  1925  7022 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 14:57:40.000  1925  7022 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 14:57:40.000  1925  7022 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 14:57:40.001  1925  2322 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 14:57:40.001  1925  2320 W WfdsService: DefaultState - msg [9445378] is not handled
08-30 14:57:40.022  7177  7196 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 14:57:40.022  7177  7196 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 14:57:40.022  7177  7196 I Adreno-EGL: Build Date: 12/12/14 금
08-30 14:57:40.022  7177  7196 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 14:57:40.022  7177  7196 I Adreno-EGL: Remote Branch: 
08-30 14:57:40.022  7177  7196 I Adreno-EGL: Local Patches: 
08-30 14:57:40.022  7177  7196 I Adreno-EGL: Reconstruct Branch: 
,08-30 14:57:40.036   305   893 D CommandListener: Clearing all IP addresses on wlan0
08-30 14:57:40.036  1035  1529 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 14:57:40.036  1035  1529 D DSQN    : disableDataServiceNotify
08-30 14:57:40.036  1035  1529 D DSQN    : stop dsqn bin
,08-30 14:57:40.039  1035  1523 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 14:57:40.040  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-30 14:57:40.040  1035  1523 D WifiNative-p2p0: TERMINATE: returned true
08-30 14:57:40.040  1035  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 14:57:40.040  1035  1523 E WifiStateMachine: useWiFiOffloading() : false
08-30 14:57:40.040  1035  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 14:57:40.041  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 14:57:40.041  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:57:40.041  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:40.041  1035  1529 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-30 14:57:40.042  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:57:40.042  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:57:40.042  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:40.042  1035  1529 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:57:40.042  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:40.042  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 14:57:40.042  1035  1529 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-30 14:57:40.043  1035  1529 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-30 14:57:40.043  1035  1529 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 14:57:40.043  1587  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 14:57:40.043  1035  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 14:57:40.043  1035  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:40.043  1035  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 14:57:40.043  1035  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:40.043  1035  1529 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:57:40.043  1035  1529 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_REST,RICTED&TRUSTED&NOT_VPN] ]
08-30 14:57:40.044  1035  1529 D NetworkManagementService: Removing idletimer
08-30 14:57:40.044  1035  1529 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:40.044  1035  1529 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-30 14:57:40.044  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-30 14:57:40.044  1835  1835 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:57:40.044  1035  1523 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:57:40.044  1035  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 14:57:40.044  1835  1835 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 14:57:40.046  1035  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 14:57:40.047  6646  6646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:57:40.047  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:57:40.047  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:40.047  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:40.047  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:57:40.047  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:57:40.047  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:57:40.047  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:57:40.047  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:57:40.047  6646  6646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:57:40.047  6646  6646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:57:40.047  6646  6646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:57:40.047  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:57:40.047  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:40.047  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:40.047  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:57:40.047  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:57:40.047  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:57:40.047  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:57:40.047  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
0,8-30 14:57:40.048  6646  6646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:57:40.048  6646  6646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:57:40.048  1035  1520 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 14:57:40.049  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 14:57:40.050  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:57:40.050  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 14:57:40.050  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 14:57:40.050  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 14:57:40.050  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 14:57:40.050  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 14:57:40.050  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 14:57:40.050  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 14:57:40.050  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 14:57:40.050  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 14:57:40.060  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:40.078  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 14:57:40.079  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:40.079  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 14:57:40.091  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-30 14:57:40.091  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 14:57:40.092  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:40.111  7177  7196 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 14:57:40.111  7177  7196 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 14:57:40.111  7177  7196 I Adreno-EGL: Build Date: 12/12/14 금
08-30 14:57:40.111  7177  7196 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 14:57:40.111  7177  7196 I Adreno-EGL: Remote Branch: 
08-30 14:57:40.111  7177  7196 I Adreno-EGL: Local Patches: 
08-30 14:57:40.111  7177  7196 I Adreno-EGL: Reconstruct Branch: 
,08-30 14:57:40.135  7011  7011 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-30 14:57:40.135  7011  7011 I wpa_supplicant: monitor socket send errors count : 1
08-30 14:57:40.135  7011  7011 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1925-4\x00 that cannot receive messages
08-30 14:57:40.137  1035  7021 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 14:57:40.137  1035  7021 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 14:57:40.144  1035  7080 D DhcpStateMachine: StoppedState
08-30 14:57:40.144  1035  7080 D DhcpStateMachine: StoppedState{ when=-163ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:40.144  1035  1523 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-30 14:57:40.144  1035  1523 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-30 14:57:40.180  7011  7011 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 14:57:40.181  1035  1117 D Tethering: InitialState.processMessage what=4
08-30 14:57:40.182  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 14:57:40.183  1035  1523 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:57:40.183  1035  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:57:40.186  7011  7011 W wpa_supplicant: USIM:  scard_deinit function
,08-30 14:57:40.189  1035  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-30 14:57:40.190  1035  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 14:57:40.190  1035  7021 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 14:57:40.190  1035  7021 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 14:57:40.190  1035  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 14:57:40.191  1035  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=183065
08-30 14:57:40.191  1035  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 14:57:40.191  1035  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=183065
08-30 14:57:40.191  1035  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=183065  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 14:57:40.191  1035  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=183066  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 14:57:40.218  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-30 14:57:40.228  2169  2169 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:57:40.230  6359  6788 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 14:57:40.239  6959  6959 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 14:57:40.239  6959  6959 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:40.239  6959  6959 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 14:57:40.240  6959  6959 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 14:57:40.241  6959  6959 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 14:57:40.245  6959  6959 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1af7a111
08-30 14:57:40.245  6959  6959 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 14:57:40.245  6959  6959 D AppUp4:CustFacade: isPhone : true
08-30 14:57:40.245  6959  6959 D AppUp4:CustModeStarterReceiver: begin check event
08-30 14:57:40.246  6959  6959 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 14:57:40.249  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:40.249  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 14:57:40.252  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 14:57:40.254  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 14:57:40.257  4296  7279 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 14:57:40.259  4296  7280 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:40.259  4296  7280 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 14:57:40.262  6985  6985 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 14:57:40.280  3482  3482 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 14:57:40.280  3482  3482 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:40.280  3482  3482 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 14:57:40.281  6873  7286 W FormManager: Network not available. Please check & try again.
,08-30 14:57:40.283  6985  7284 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:40.287   305  7291 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 14:57:40.287  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 14:57:40.287  7028  7028 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 14:57:40.287  7028  7028 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 14:57:40.289  1800  7134 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-30 14:57:40.292  6873  7287 V FormManager: Network unavailable.
08-30 14:57:40.295  7011  7011 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 14:57:40.297  7102  7102 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:57:40
08-30 14:57:40.298  7102  7102 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 14:57:40.298  7102  7102 D Weather.Utils: 2 : All the weather widget is gone.
,08-30 14:57:40.299  7102  7102 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 14:57:40.299  7102  7102 D WeatherAncestor: connectivity changed - connection : true
08-30 14:57:40.299  7102  7102 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@29136077
08-30 14:57:40.299  7102  7102 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 14:57:40.299  7102  7102 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 14:57:40.299  7102  7102 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 14:57:40.300  7102  7102 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 14:57:40.300  7102  7102 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:57:40
08-30 14:57:40.300  1035  7021 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-30 14:57:40.301  1035  7021 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-30 14:57:40.301  1035  7021 D WifiMonitor: Disconnecting from the supplicant, no more events
08-30 14:57:40.301  6873  7287 V FormManager: Network unavailable.
08-30 14:57:40.301  1035  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
08-30 14:57:40.305  1925  1925 D WfdsService: Supplicant Connection state is changed : false
08-30 14:57:40.305  1925  2320 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 14:57:40.305  1925  2320 D WfdsService: Set the WFDS Monitor: false
08-30 14:57:40.305  1925  2320 D WfdsMonitor: WFDS Monitor is stopped
08-30 14:57:40.305  1035  1523 D WifiOffDelayIfNotUsed: stopMonitoring
08-30 14:57:40.305  1035  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 14:57:40.305  1035  1523 E WifiStateMachine: useWiFiOffloading() : false
08-30 14:57:40.305  1035  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 14:57:40.306  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 14:57:40.307  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:40.308  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:40.309  2489  2489 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:40.309  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:40.311  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 14:57:40.311  1035  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 14:57:40.311  1035  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 14:57:40.312  1800  7134 I CheckinService: active receiver: disabled
,08-30 14:57:40.339   305  7294 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 14:57:40.340  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-30 14:57:40.341  6747  6747 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 14:57:40.341  6747  6747 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 14:57:40.341  6747  6747 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 14:57:40.341  6747  6747 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 14:57:40.342  6747  6747 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 14:57:40.342  6747  6747 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 14:57:40.342  6747  6747 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 14:57:40.342  6747  6747 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
,08-30 14:57:40.342  6747  6747 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 14:57:40.342  6747  6747 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 14:57:40.342  6747  6747 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 14:57:40.350  6789  6789 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:57:40.354  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 14:57:40.355  6873  7296 W FormManager: Network not available. Please check & try again.
08-30 14:57:40.357  6873  7297 V FormManager: Network unavailable.
08-30 14:57:40.358  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:57:40.361  6873  7297 V FormManager: Network unavailable.
08-30 14:57:40.369  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=263854985 [*alarm*], flags=0x0
,08-30 14:57:40.374  6789  6789 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:57:40.376  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 14:57:40.381  6873  7300 W FormManager: Network not available. Please check & try again.
08-30 14:57:40.383  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:57:40.386  6873  7301 V FormManager: Network unavailable.
08-30 14:57:40.388  6873  7301 V FormManager: Network unavailable.
08-30 14:57:40.392  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-30 14:57:40.392  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 14:57:40.395  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 14:57:40.397  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 14:57:40.401  4296  7302 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 14:57:40.405  4296  7303 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 14:57:40.405  4296  7303 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 14:57:40.437  1035  1998 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7304 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 14:57:40.450   341   341 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 229us total 11.699ms
08-30 14:57:40.462   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 231us total 10.694ms
,08-30 14:57:40.474   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 206us total 11.241ms
,08-30 14:57:40.564  7304  7304 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 14:57:40.564  7304  7304 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-30 14:57:40.575  7304  7304 V [BNRBootReceiver]: Boot Receiver Return
,08-30 14:57:40.576  7304  7304 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 14:57:40.582  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 14:57:40.596  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:57:40.605  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 14:57:40.621  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:57:40.621  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 14:57:40.624  6820  6820 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 14:57:40.628  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 14:57:40.639  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:57:40.645  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 14:57:40.654  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 14:57:40.655  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:57:40.657  6820  6820 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 14:57:40.664  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-30 14:57:40.669  6747  6747 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-30 14:57:40.677  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:40.687  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:57:40.694  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:57:40.701  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:57:40.702  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 14:57:40.702  6820  6820 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 14:57:40.706  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:40.714  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:57:40.720  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:57:40.727  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:57:40.727  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:57:40.728  6820  6820 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 14:57:40.732  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 14:57:40.743  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 14:57:40.749  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 14:57:40.759  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:57:40.760  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:57:40.760  6820  6820 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 14:57:40.765  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 14:57:40.775  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 14:57:40.781  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 14:57:40.789  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:57:40.790  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:57:40.791  6820  6820 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 14:57:40.798  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 14:57:40.806  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:57:40.813  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:57:40.822  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 14:57:40.823  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:57:40.824  6820  6820 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 14:57:40.834  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 14:57:40.852  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:57:40.862  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 14:57:40.872  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:57:40.872  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 14:57:40.878  6820  6820 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 14:57:40.885  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:40.898  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:57:40.905  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:57:40.914  6552  6936 D UEI.SmartControl: Internal timer expired: 2
,08-30 14:57:40.914  6552  6936 D UEI.SmartControl: unbind internal service
08-30 14:57:40.916  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:57:40.917  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:57:40.918  6820  6820 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 14:57:40.925  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:40.933  6789  6789 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-30 14:57:40.944  1035  1528 D WifiService: New client listening to asynchronous messages
08-30 14:57:40.945  6789  6789 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:57:40.951  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:57:40.958  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:57:40.970  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 14:57:40.971  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:57:40.973  6820  6820 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-30 14:57:40.974  6820  6820 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-30 14:57:40.975  6820  6820 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 14:57:40.983  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:40.989  6789  6789 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-30 14:57:40.991  6789  6789 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:57:41.000  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:57:41.007  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 14:57:41.018  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 14:57:41.019  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 14:57:41.021  6552  6930 D serial_port: close(fd = 24)
,08-30 14:57:41.021  6820  6820 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-30 14:57:41.023  6820  6820 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-30 14:57:41.024  6552  6930 I UEI.SmartControl: Serial port is closed.
08-30 14:57:41.024  6820  6820 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 14:57:41.029  1035  1979 I ActivityManager: Killing 6769:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-30 14:57:41.130  1035  1630 W libprocessgroup: failed to open /acct/uid_10037/pid_6769/cgroup.procs: No such file or directory
,08-30 14:57:41.156  2169  2169 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-30 14:57:41.185  2169  2169 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-30 14:57:41.186  2169  2169 D c       : Getting all permits...
08-30 14:57:41.186  2169  2169 D a       : Opening database...
,08-30 14:57:41.191  2169  2169 D a       : Opening database auth.proximity.permit_store...
08-30 14:57:41.192  2169  2169 D a       : Closing database...
08-30 14:57:41.204  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 14:57:41.208  6789  6789 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 14:57:41.208  6789  6789 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 14:57:41.208  6789  6789 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:57:41.211  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:57:41.217  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:57:41.224  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:57:41.224  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:57:41.226  6820  6820 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 14:57:41.232  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:41.235  6789  6789 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 14:57:41.235  6789  6789 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 14:57:41.235  6789  6789 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:57:41.238  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:57:41.245  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 14:57:41.250  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:57:41.251  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 14:57:41.254  6820  6820 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 14:57:41.258  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:41.260  6789  6789 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 14:57:41.260  6789  6789 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 14:57:41.261  6789  6789 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:57:41.264  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:57:41.272  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:57:41.279  6820  6820 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:57:41.279  6820  6820 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 14:57:41.282  6820  6820 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 14:57:41.291  6789  6789 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 14:57:41.299  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 14:57:41.304  6873  7332 W FormManager: Network not available. Please check & try again.
,08-30 14:57:41.307  6873  7333 V FormManager: Network unavailable.
08-30 14:57:41.310  6873  7333 V FormManager: Network unavailable.
08-30 14:57:41.311  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:57:41.329  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 14:57:41.329  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 14:57:41.331  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 14:57:41.335  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 14:57:41.343  4296  7334 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 14:57:41.344  6789  6789 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-30 14:57:41.344  6789  6789 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 14:57:41.344  6789  6789 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 14:57:41.352  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 14:57:41.355  4296  7335 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 14:57:41.355  4296  7335 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 14:57:41.364  6873  7345 W FormManager: Network not available. Please check & try again.
08-30 14:57:41.365  6873  7346 V FormManager: Network unavailable.
08-30 14:57:41.366  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:57:41.372  6873  7346 V FormManager: Network unavailable.
,08-30 14:57:41.385  2169  2169 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-30 14:57:41.735  1035  1523 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3011] from screen [on:0 period:-611920793] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 14:57:41.738  1035  1523 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-611920790] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 14:57:41.971  1035  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:57:41.990  1035  1117 D Tethering: MasterInitialState.processMessage what=3
08-30 14:57:41.996  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:57:41.998  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:42.004  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 14:57:42.008  6359  6788 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-30 14:57:42.010  1035  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:42.022  5773  5773 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 14:57:42.041  2169  2169 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:57:42.059  6959  6959 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 14:57:42.059  6959  6959 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:42.059  6959  6959 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 14:57:42.059  6959  6959 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 14:57:42.067  6959  6959 I AppUp4:CustModeStarterReceiver: onReceive
08-30 14:57:42.071  6959  6959 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1af7a111
08-30 14:57:42.071  6959  6959 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 14:57:42.071  6959  6959 D AppUp4:CustFacade: isPhone : true
08-30 14:57:42.072  6959  6959 D AppUp4:CustModeStarterReceiver: begin check event
08-30 14:57:42.073  6959  6959 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-30 14:57:42.081  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:42.081  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 14:57:42.083  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 14:57:42.088  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 14:57:42.099  6985  6985 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 14:57:42.136  1035  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 14:57:42.146  3482  3482 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 14:57:42.146  3482  3482 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:42.146  3482  3482 I LgeMiscReceiver: networkInfo.isConnected() = true
08-30 14:57:42.147  3482  3482 D PhoneState: setPdpRejectCasuse : false
08-30 14:57:42.150  7028  7028 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 14:57:42.150  7028  7028 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 14:57:42.164  7102  7102 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:57:42
08-30 14:57:42.165  7102  7102 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 14:57:42.165  7102  7102 D Weather.Utils: 2 : All the weather widget is gone.
08-30 14:57:42.166  7102  7102 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 14:57:42.166  7102  7102 D WeatherAncestor: connectivity changed - connection : true
08-30 14:57:42.166  7102  7102 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@29136077
,08-30 14:57:42.168  7102  7102 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-30 14:57:42.168  7102  7102 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 14:57:42.168  7102  7102 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 14:57:42.168  7102  7102 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 14:57:42.168  7102  7102 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:57:42
08-30 14:57:42.169  4296  7370 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 14:57:42.170  6873  7374 W FormManager: Network not available. Please check & try again.
08-30 14:57:42.175  4296  7376 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:42.175  4296  7376 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 14:57:42.183  6985  7372 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 14:57:42.190  6873  7375 V FormManager: Network unavailable.
08-30 14:57:42.198  6873  7375 V FormManager: Network unavailable.
,08-30 14:57:42.925  1035  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:42.926  1035  1888 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-30 14:57:42.951  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 14:57:42.951  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 14:57:42.951  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-30 14:57:42.952  1035  1117 D BluetoothManagerService: Message: 1
08-30 14:57:42.952  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-30 14:57:42.979  1035  1117 D BluetoothManagerService: Message: 20
08-30 14:57:42.979  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@93d6607:true
,08-30 14:57:42.985  6896  6896 D BluetoothAdapterState: make
08-30 14:57:42.990  6896  6896 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 14:57:42.990  6896  6896 I bluedroid-qcom: init
08-30 14:57:42.991  6896  7393 I BluetoothAdapterState: Entering OffState
08-30 14:57:42.992  6896  6896 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 14:57:42.992  6896  6896 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 14:57:42.992  6896  6896 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 14:57:42.992  6896  6896 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 14:57:42.992  6896  6896 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 14:57:42.994  6896  6896 I bluedroid-qcom: get_profile_interface socket
08-30 14:57:42.994  6896  6896 I bluedroid-qcom: get_profile_interface map_client
,08-30 14:57:42.999  6896  7397 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 14:57:42.984  7396  7396 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:57:43.004  6896  7397 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 14:57:42.994  7396  7396 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:57:43.015  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-30 14:57:43.018  1035  1117 D BluetoothManagerService: Message: 40
08-30 14:57:43.018  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 14:57:43.019  6896  6912 I bluedroid-qcom: config_hci_snoop_log
08-30 14:57:43.021  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 14:57:43.021  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 14:57:43.023  7396  7396 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 14:57:43.023  7396  7396 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 14:57:43.023  7396  7396 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-30 14:57:43.026  7396  7396 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-30 14:57:43.029  7396  7396 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 14:57:43.029  7396  7396 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-30 14:57:43.036  6896  7393 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-30 14:57:43.038  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 14:57:43.038  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 14:57:43.038  6896  7397 D BluetoothAdapterProperties: Name is: G3
08-30 14:57:43.038  6896  7393 D BluetoothAdapterProperties: Setting state to 11
08-30 14:57:43.039  6896  7393 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 14:57:43.039  1035  1117 D BluetoothManagerService: Message: 60
08-30 14:57:43.039  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 14:57:43.039  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-30 14:57:43.044  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 14:57:43.048  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 14:57:43.048  1035  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:43.051  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:43.055  6747  6747 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-30 14:57:43.056  1035  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:57:43.061  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:43.075  1035  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:57:43.088  6896  7393 I LGBluetoothServiceJni: classInitNative: succeeds
08-30 14:57:43.089  1035  1117 D Tethering: MasterInitialState.processMessage what=3
08-30 14:57:43.094  1035  1117 D Tethering: MasterInitialState.processMessage what=3
,08-30 14:57:43.095  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:43.099  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:43.101  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:43.103  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:43.104  6896  7393 D BluetoothBondStateMachine: make
08-30 14:57:43.105  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 14:57:43.105  6896  6896 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 14:57:43.106  6896  6896 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:43.106  6896  6896 V BluetoothPbapReceiver: ***********state = 11
08-30 14:57:43.107  6896  7393 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29136077
08-30 14:57:43.108  6896  7393 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 14:57:43.108  6359  6788 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 14:57:43.108  6896  7393 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29136077
08-30 14:57:43.108  6896  7393 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-30 14:57:43.108  6896  7393 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-30 14:57:43.110  6896  7414 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 14:57:43.117  2169  2169 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 14:57:43.120  6896  7393 E BluetoothAdapterService: File transfer profiles supported!!
08-30 14:57:43.123  5773  5773 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 14:57:43.162  1035  1936 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7416 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-30 14:57:43.169  1035  1097 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:43.170  1035  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:43.170  6896  6896 D HeadsetService: Received start request. Starting profile...
08-30 14:57:43.171  6896  6896 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 14:57:43.172  6896  6896 D LGBluetoothHfpAdapter: Version 1.6
08-30 14:57:43.172  6896  7393 E BluetoothAdapterService: File transfer profiles supported!!
08-30 14:57:43.170  1035  1097 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 14:57:43.176  6896  6896 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 14:57:43.178  6896  6896 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 14:57:43.178  6896  6896 D HeadsetStateMachine: make
08-30 14:57:43.179  5773  5773 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 14:57:43.181  6896  7393 E BluetoothAdapterService: File transfer profiles supported!!
08-30 14:57:43.188  6896  7393 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 14:57:43.196  2169  2169 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:57:43.203  6896  7393 E BluetoothAdapterService: File transfer profiles supported!!
08-30 14:57:43.207  6896  6896 D LgDataFeature: LgDataFeature() Constructor: none
08-30 14:57:43.207  6896  6896 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 14:57:43.211  6896  7393 E BluetoothAdapterService: File transfer profiles supported!!
08-30 14:57:43.211  6959  6959 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 14:57:43.211  6959  6959 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:43.211  6959  6959 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 14:57:43.211  6959  6959 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 14:57:43.212  6896  6896 D HeadsetStateMachine: max_hf_connections = 1
08-30 14:57:43.212  6896  6896 I bluedroid-qcom: get_profile_interface handsfree
08-30 14:57:43.213  6959  6959 I AppUp4:CustModeStarterReceiver: onReceive
08-30 14:57:43.213  6896  6896 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,08-30 14:57:43.214   311  1369 V AudioPolicyService: registerClient() client 0xb558afe0, uid 1002
08-30 14:57:43.215   311  1369 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 14:57:43.215   311  1369 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 14:57:43.215   311  1369 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 14:57:43.215  6896  6896 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 14:57:43.215   311  2117 V AudioFlinger: registerClient() client 0xb55815b0, pid 6896
08-30 14:57:43.217   311  1362 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 14:57:43.217   311  1362 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 14:57:43.217  1035  1979 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 14:57:43.217  1035  1979 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 14:57:43.217  1835  2412 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 14:57:43.217  1835  2412 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 14:57:43.217  3482  3498 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 14:57:43.217  3482  3498 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 14:57:43.217   311  1364 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 14:57:43.217   311  1364 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 14:57:43.217  1835  4014 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 14:57:43.217  1035  1770 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 14:57:43.217  1835  4014 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 14:57:43.217  1035  1770 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 14:57:43.217  3482  3497 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 14:57:43.217  3482  3497 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 14:57:43.217  6896  6896 V ToneGenerator: Create Track: 0xb4928080
08-30 14:57:43.218  6896  6896 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 14:57:43.218  6896  6896 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 14:57:43.218   311  1368 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 14:57:43.218   311  1368 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 14:57:43.218   311  1368 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 14:57:43.218   311  1368 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 14:57:43.218  1587  2518 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 14:57:43.218  6896  6912 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 14:57:43.218  1587  2518 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 14:57:43.218  6896  6912 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 14:57:43.218  1587  2518 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 14:57:43.218  6896  6912 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 14:57:43.218  1587  2518 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 14:57:43.218  6896  6912 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 14:57:43.218   311   311 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 14:57:43.218   311  1369 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 14:57:43.218   311  1369 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-30 14:57:43.218   31,1  1369 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 14:57:43.218   311  1369 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 14:57:43.218  6896  6896 V AudioSystem: getLatency() output 2, latency 50
08-30 14:57:43.218  6896  6896 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 14:57:43.218  6896  6896 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 14:57:43.219   311  2117 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 14:57:43.219   311  2117 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 14:57:43.219   311  2117 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 14:57:43.219   311  2117 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 14:57:43.219   311  2117 V AudioFlinger: createTrack() lSessionId: 22
08-30 14:57:43.223  6896  6896 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 14:57:43.223   311  2117 V AudioFlinger: acquiring 22 from 6896, for 6896
08-30 14:57:43.223   311  2117 V AudioFlinger:  added new entry for 22
08-30 14:57:43.223  6896  7393 E BluetoothAdapterService: File transfer profiles supported!!
08-30 14:57:43.223  6896  6896 V ToneGenerator: ToneGenerator INIT OK, time: 186111
08-30 14:57:43.223  6896  6896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29136077
08-30 14:57:43.224  6896  7433 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 14:57:43.224  6896  7433 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 14:57:43.224  6896  6896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29136077
08-30 14:57:43.226  6896  6896 D A2dpService: Received start request. Starting profile...
,08-30 14:57:43.226  6959  6959 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1af7a111
08-30 14:57:43.226  6896  6896 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 14:57:43.226  6959  6959 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 14:57:43.226  6959  6959 D AppUp4:CustFacade: isPhone : true
08-30 14:57:43.227  6896  6896 V Avrcp   : make
08-30 14:57:43.227  6896  6896 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 14:57:43.227  6896  6896 I bluedroid-qcom: get_profile_interface avrcp
08-30 14:57:43.228  6896  7433 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 14:57:43.228  6896  7433 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 14:57:43.228  6959  6959 D AppUp4:CustModeStarterReceiver: begin check event
08-30 14:57:43.228   311  1368 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6896
08-30 14:57:43.229   311  1368 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 14:57:43.229   311  1368 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 14:57:43.229   311  1368 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 14:57:43.229   311  1368 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 14:57:43.229   311  1368 V voice   : voice_set_parameters: exit with code(0)
08-30 14:57:43.229   311  1368 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 14:57:43.229   311  1368 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 14:57:43.229   311  1368 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 14:57:43.229   311  1368 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 14:57:43.229   311  1368 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 14:57:43.229   311  1368 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 14:57:43.229  6896  7433 V ToneGenerator: ToneGenerator destructor
08-30 14:57:43.229  6896  7433 V ToneGenerator: stopTone
08-30 14:57:43.229  6896  7433 V ToneGenerator: Delete Track: 0xb4928080
08-30 14:57:43.230  6896  7433 V AudioTrack: ~AudioTrack, releasing session id from 6896 on behalf of 6896
08-30 14:57:43.230   311   311 V AudioPolicyService: AudioCommandThread() adding release output 2
08-30 14:57:43.230   311   311 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 14:57:43.230   311   311 V AudioFlinger: PlaybackThread::Track destructor
08-30 14:57:43.230   311  1369 V AudioFlinger: releasing 22 from 6896 for 6896
08-30 14:57:43.230   311   311 V AudioFlinger: removeClient_l() pid 6896, calling pid 311
08-30 14:57:43.230   311  1369 V AudioFlinger:  decremented refcount to 0
08-30 14:57:43.230   311  1369 V AudioFlinger: purging stale effects
08-30 14:57:43.230   311  1272 V AudioPolicyService: AudioCommandThread() waking up
08-30 14:57:43.230   311  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 14:57:43.230   311  1272 V AudioPolicyManager: releaseOutput() 2
08-30 14:57:43.230   311  1272 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 14:57:43.230  6959  6959 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 14:57:43.234  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:43.234  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 14:57:43.235  6896  6896 V AudioManager: registerRemoteController: size of Media player list: 0
08-30 14:57:43.235  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclien,t.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 14:57:43.236  6896  6896 E AudioManager: No RCC entry present to update
08-30 14:57:43.236  6896  6896 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 14:57:43.239  6896  6896 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-30 14:57:43.240  6896  6896 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 14:57:43.240  6896  6896 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-30 14:57:43.242  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 14:57:43.243  6896  7393 V LGMDMManager: Create singleton instance
08-30 14:57:43.246  6896  7393 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 14:57:43.246  6896  6896 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 14:57:43.247  4296  7438 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 14:57:43.249  4296  7439 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:43.249  4296  7439 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 14:57:43.284  6985  6985 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 14:57:43.287  7416  7416 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-30 14:57:43.287  7416  7416 W LG Account v2.2: No ProfileInfo entries
08-30 14:57:43.287  7416  7416 I LG Account v2.2: isEnabled: false
08-30 14:57:43.287  7416  7416 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 14:57:43.287  7416  7416 I Feature : [Lifetracker]Country: EU
08-30 14:57:43.287  7416  7416 I Feature : [Lifetracker]Operator: OPEN
08-30 14:57:43.287  7416  7416 I Feature : [Lifetracker]Ranking support: false
08-30 14:57:43.287  7416  7416 I Feature : [Lifetracker]Comfort support: false
08-30 14:57:43.287  7416  7416 I Feature : [Lifetracker]Accessory: true
08-30 14:57:43.287  7416  7416 I Feature : [Lifetracker]Health device: true
08-30 14:57:43.287  7416  7416 I Feature : [Lifetracker]Extra Pedometer: false
08-30 14:57:43.288  7416  7416 I Feature : [Lifetracker]Blood glucose device: false
08-30 14:57:43.288  7416  7416 I Feature : [Lifetracker]Device Number: 3
08-30 14:57:43.297  6747  6747 D BluetoothPermissionRequest: onReceive
08-30 14:57:43.308  6747  6747 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 14:57:43.315  6985  7442 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:43.320  3482  3482 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 14:57:43.320  3482  3482 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:43.320  3482  3482 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-30 14:57:43.322  6873  7444 W FormManager: Network not available. Please check & try again.
08-30 14:57:43.325  7028  7028 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 14:57:43.325  6873  7445 V FormManager: Network unavailable.
08-30 14:57:43.326  7028  7028 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 14:57:43.332  6873  7445 V FormManager: Network unavailable.
,08-30 14:57:43.333  1035  1908 V SIM_STK : Menu title from STK is T-Mobile
,08-30 14:57:43.333  1035  1908 V SIM_STK : Menu title from STK is T-Mobile
08-30 14:57:43.334  7102  7102 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:57:43
08-30 14:57:43.335  7102  7102 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 14:57:43.335  7102  7102 D Weather.Utils: 2 : All the weather widget is gone.
08-30 14:57:43.335  7102  7102 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 14:57:43.335  7102  7102 D WeatherAncestor: connectivity changed - connection : true
08-30 14:57:43.335  7102  7102 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@29136077
08-30 14:57:43.337  7102  7102 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 14:57:43.337  7102  7102 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 14:57:43.337  7102  7102 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 14:57:43.337  7102  7102 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 14:57:43.337  7102  7102 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:57:43
08-30 14:57:43.354  6359  6359 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-30 14:57:43.354  6359  6788 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 14:57:43.366  2169  2169 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 14:57:43.374  6959  6959 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 14:57:43.374  6959  6959 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:43.374  6959  6959 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 14:57:43.374  6959  6959 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 14:57:43.375  6959  6959 I AppUp4:CustModeStarterReceiver: onReceive
08-30 14:57:43.378  6959  6959 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1af7a111
,08-30 14:57:43.378  6959  6959 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 14:57:43.378  6959  6959 D AppUp4:CustFacade: isPhone : true
08-30 14:57:43.378  6959  6959 D AppUp4:CustModeStarterReceiver: begin check event
08-30 14:57:43.378  6959  6959 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 14:57:43.381  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:43.381  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 14:57:43.382  1035  1874 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-30 14:57:43.383  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 14:57:43.384  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 14:57:43.387  6896  6896 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 14:57:43.389  6896  6896 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 14:57:43.390  6896  6896 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 14:57:43.390  6896  6896 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 14:57:43.390  6896  6896 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 14:57:43.390  6896  6896 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 14:57:43.390  4296  7447 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 14:57:43.390  6896  6896 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 14:57:43.390  6896  6896 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 14:57:43.390  6896  6896 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 14:57:43.390  6896  6896 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 14:57:43.390  6896  6896 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 14:57:43.391  6896  6896 I BluetoothA2dpServiceJni: classInitNative
,08-30 14:57:43.391  6896  6896 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 14:57:43.391  6896  6896 D A2dpStateMachine: make
08-30 14:57:43.392  6985  6985 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 14:57:43.392  6896  6896 I bluedroid-qcom: get_profile_interface a2dp
08-30 14:57:43.392  6896  7449 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 14:57:43.394  6896  6896 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 14:57:43.394  6896  6896 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-30 14:57:43.395  6896  6896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29136077
08-30 14:57:43.395  6896  7448 D A2dpStateMachine: Enter Disconnected: -2
08-30 14:57:43.396  6896  6896 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 14:57:43.396  4296  7451 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:43.396  4296  7451 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 14:57:43.397  6896  6896 D HidService: Received start request. Starting profile...
08-30 14:57:43.397  6896  6896 I bluedroid-qcom: get_profile_interface hidhost
08-30 14:57:43.397  6896  6896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29136077
08-30 14:57:43.398  6896  6896 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 14:57:43.399  6896  6896 D HealthService: Received start request. Starting profile...
08-30 14:57:43.400  6896  6896 I bluedroid-qcom: get_profile_interface health
08-30 14:57:43.400  6896  6896 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 14:57:43.400  6896  6896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29136077
08-30 14:57:43.401  6896  6896 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 14:57:43.403  6896  6896 D PanService: Received start request. Starting profile...
08-30 14:57:43.403  6896  6896 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 14:57:43.403  6896  6896 I bluedroid-qcom: get_profile_interface pan
,08-30 14:57:43.408  6896  6896 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-30 14:57:43.409  6896  6896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29136077
08-30 14:57:43.409  6896  6896 D HeadsetStateMachine: Proxy object connected
08-30 14:57:43.409  6896  6896 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 14:57:43.409  6896  6896 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-30 14:57:43.411  6896  6896 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-30 14:57:43.412  6873  7457 W FormManager: Network not available. Please check & try again.
08-30 14:57:43.415  6896  6896 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 14:57:43.415  6896  6896 D BtGatt.GattService: Received start request. Starting profile...
08-30 14:57:43.415  6896  6896 D BtGatt.GattService: start()
08-30 14:57:43.415  6896  6896 I bluedroid-qcom: get_profile_interface gatt
08-30 14:57:43.416  6896  6896 D BtGatt.AdvertiseManager: advertise manager created
,08-30 14:57:43.419  3482  3482 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 14:57:43.419  3482  3482 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:43.419  3482  3482 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 14:57:43.421  6896  6896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29136077
08-30 14:57:43.425  6896  6896 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 14:57:43.425  7028  7028 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 14:57:43.425  7028  7028 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 14:57:43.425  6985  7455 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:43.425  6873  7458 V FormManager: Network unavailable.
08-30 14:57:43.425  6896  7433 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 14:57:43.426  6896  7433 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 14:57:43.426  6896  7433 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-30 14:57:43.426  6896  6896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29136077
08-30 14:57:43.427  6896  6896 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-30 14:57:43.427  6896  6896 V BluetoothMapService: BluetoothMapBinder()
08-30 14:57:43.428  6896  6896 D BluetoothMapService: Received start request. Starting profile...
08-30 14:57:43.428  6896  6896 D BluetoothMapService: start()
,08-30 14:57:43.431  6873  7458 V FormManager: Network unavailable.
08-30 14:57:43.432  6896  6896 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-30 14:57:43.432  6896  6896 D BluetoothMapEmailAppObserver: createReceiver()
08-30 14:57:43.435  7102  7102 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:57:43
08-30 14:57:43.436  6896  6896 D BluetoothMapEmailAppObserver: initObservers()
08-30 14:57:43.436  6896  6896 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 14:57:43.438  7102  7102 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 14:57:43.438  7102  7102 D Weather.Utils: 2 : All the weather widget is gone.
,08-30 14:57:43.438  7102  7102 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-30 14:57:43.438  7102  7102 D WeatherAncestor: connectivity changed - connection : true
08-30 14:57:43.438  7102  7102 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@29136077
08-30 14:57:43.439  7102  7102 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 14:57:43.439  7102  7102 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 14:57:43.439  7102  7102 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 14:57:43.439  7102  7102 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 14:57:43.439  7102  7102 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:57:43
08-30 14:57:43.442  6896  6896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29136077
08-30 14:57:43.448  6896  6896 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 14:57:43.450  6896  6896 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 14:57:43.452  6896  6896 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 14:57:43.452  6896  6896 V PanService: [BTUI] SIM Extra State :ABSENT
08-30 14:57:43.455  6896  6896 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 14:57:43.457  6896  6896 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-30 14:57:43.457  6896  6896 V BluetoothMapService: Handler(): got msg=1
08-30 14:57:43.457  6896  7393 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 14:57:43.457  6896  7393 I bluedroid-qcom: enable
08-30 14:57:43.458  6896  7462 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 14:57:43.458  6896  7393 I bt_hci_bdroid: init
08-30 14:57:43.458  6896  7462 I bt-btu  : btu_task pending for preload complete event
08-30 14:57:43.458  6896  7393 I bt_vendor: bt-vendor : init
08-30 14:57:43.458  6896  7393 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 14:57:43.459  6896  7393 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 14:57:43.459  6896  7393 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 14:57:43.459  6896  7393 D bt_userial_mct: userial_init
08-30 14:57:43.459  6896  6896 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:43.459  6896  7393 D bt_hci_bdroid: set_power 1
08-30 14:57:43.459  6896  7393 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 14:57:43.459  6896  7393 I bt_vendor: Starting hciattach daemon
08-30 14:57:43.459  6896  7393 I bt_vendor: try to set true
08-30 14:57:43.460  6896  6896 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 14:57:43.444  7465  7465 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:57:43.444  7465  7465 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:57:43.460  6896  6896 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 14:57:43.460  6896  6896 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 14:57:43.460  6896  6896 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:43.460  6896  6896 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-30 14:57:43.478  7466  7466 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 14:57:43.555  7472  7472 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 14:57:43.580  7473  7473 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 14:57:43.632  7475  7475 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 14:57:43.648  7476  7476 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-30 14:57:43.676  7477  7477 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 14:57:43.690  7478  7478 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-30 14:57:43.741  7480  7480 I libmdmdetect: ESOC framework not supported
08-30 14:57:43.743  7480  7480 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-30 14:57:43.753  7480  7480 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-30 14:57:43.753  7480  7480 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-30 14:57:43.753  7480  7480 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-30 14:57:43.753  7480  7480 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-30 14:57:43.753  7480  7480 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-30 14:57:43.753  7480  7480 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-30 14:57:43.753  7480  7480 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-30 14:57:43.796  7480  7484 E QC-QMI  : qmi_client [7480] 14: failed to locate client data
,08-30 14:57:43.798   478   478 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-30 14:57:43.798   478   478 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-30 14:57:43.850  7488  7488 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 14:57:43.864  7489  7489 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 14:57:43.911  6896  7393 I bt_vendor: bluetooth satus is on
08-30 14:57:43.911  6896  7393 D bt_hci_bdroid: preload
08-30 14:57:43.911  6896  7464 D bt_userial_mct: userial_open(port:0)
08-30 14:57:43.911  6896  7464 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-30 14:57:43.915  6896  7464 I bt_vendor: Done intiailizing UART
,08-30 14:57:43.918  6896  7464 I bt_vendor: Done intiailizing UART
08-30 14:57:43.918  6896  7464 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 14:57:43.918  6896  7464 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-30 14:57:43.919  6896  7462 I bt-btu  : btu_task received preload complete event
08-30 14:57:43.920  6896  7462 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-30 14:57:43.920  6896  7462 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-30 14:57:43.923  6896  7491 D bt_userial_mct: Entering userial_read_thread()
08-30 14:57:43.926  6896  7462 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-30 14:57:43.934  6896  7462 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 14:57:43.934  6896  7462 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 14:57:43.934  6896  7462 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 14:57:43.934  6896  7462 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 14:57:43.934  6896  7462 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 14:57:43.934  6896  7462 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 14:57:43.934  6896  7462 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 14:57:43.934  6896  7462 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 14:57:43.934  6896  7462 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-30 14:57:43.934  6896  7462 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 14:57:43.934  6896  7462 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 14:57:43.934  6896  7462 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 14:57:43.934  6896  7462 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 14:57:43.934  6896  7462 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 14:57:43.934  6896  7462 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 14:57:43.934  6896  7462 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 14:57:43.972   305  7124 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-30 14:57:43.973   305  7124 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 28
08-30 14:57:43.973   305  7124 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 1
,08-30 14:57:43.976  1035  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 14:57:43.978  1035  7071 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-30 14:57:43.978  1035  7071 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-3s935ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:43.978  1035  7071 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3s935ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:43.978  1035  7071 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 14:57:43.999  6896  7462 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-30 14:57:43.999  6896  7462 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0209061 
08-30 14:57:43.999  6896  7462 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0209061 
,08-30 14:57:44.020  6896  7397 E bt-btif : Calling BTA_HhEnable
08-30 14:57:44.020  6896  7397 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-30 14:57:44.020  6896  7397 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-30 14:57:44.024  6896  7397 D BluetoothAdapterProperties: Name is: G3
08-30 14:57:44.024  6896  7462 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-30 14:57:44.024  6896  7462 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-30 14:57:44.024  6896  7462 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 14:57:44.024  6896  7462 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 14:57:44.024  6896  7462 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-30 14:57:44.025  6896  7397 D BluetoothAdapterProperties: Scan Mode:20
08-30 14:57:44.025  6896  7397 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 14:57:44.025  6896  7397 D bt_hci_bdroid: postload
08-30 14:57:44.025  6896  7464 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 14:57:44.026  6896  7462 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 14:57:44.026  6896  7397 D bte_conf: Device ID record 1 : primary
08-30 14:57:44.026  6896  7397 D bte_conf:   vendorId            = 00c4
08-30 14:57:44.026  6896  7397 D bte_conf:   vendorIdSource      = 0001
08-30 14:57:44.026  6896  7397 D bte_conf:   product             = 13a1
08-30 14:57:44.026  6896  7397 D bte_conf:   version             = 1000
08-30 14:57:44.026  6896  7397 D bte_conf:   clientExecutableURL = 
08-30 14:57:44.026  6896  7397 D bte_conf:   serviceDescription  = 
08-30 14:57:44.026  6896  7397 D bte_conf:   documentationURL    = 
08-30 14:57:44.026  6896  7397 D bte_conf: bte_load_did_conf no section named DID2.
08-30 14:57:44.027  6896  7464 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 14:57:44.028  6896  7464 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 14:57:44.029  6896  7393 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 14:57:44.029  6896  7393 D BluetoothAdapterProperties: ScanMode =  20
08-30 14:57:44.029  6896  7393 D BluetoothAdapterProperties: State =  11
08-30 14:57:44.029  6896  7393 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 14:57:44.030  6896  7464 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 14:57:44.030  6896  7393 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-30 14:57:44.030  6896  7393 D BluetoothAdapterProperties: Setting state to 12
08-30 14:57:44.030  6896  7393 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 14:57:44.030  6896  7491 E bt_mct  : hci lib postload completed
08-30 14:57:44.030  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 14:57:44.031  1035  1117 D BluetoothManagerService: Message: 60
08-30 14:57:44.031  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 14:57:44.031  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 14:57:44.031  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-30 14:57:44.031  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:57:44.032  6896  7393 I BluetoothAdapterState: Entering On State
08-30 14:57:44.032  6896  7397 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 14:57:44.033  6896  7397 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-30 14:57:44.024  7493  7493 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:57:44.024  7493  7493 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:57:44.039  6896  7462 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 14:57:44.039  6896  7462 W bt-smp  : Plain text(LSB ~ MSB) = e7 83 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 14:57:44.039  6896  7462 W bt-smp  : Encrypted text(LSB ~ MSB) = f9 0a f0 3b 5f 9d b5 85 b0 d8 71 9e 1a d3 5c d0 
08-30 14:57:44.039  6896  7462 W bt-btm  : Stopping oneshot timer
08-30 14:57:44.046  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:57:44.046  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:44.046  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:44.046  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:57:44.046  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:57:44.046  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:57:44.046  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:57:44.046  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 14:57:44.050  6646  6646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 14:57:44.058  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:57:44.058  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:44.058  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:44.058  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:57:44.058  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:57:44.058  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:57:44.058  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:57:44.058  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:57:44.060  6896  7397 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 14:57:44.060  6896  7397 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-30 14:57:44.061  6646  6646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:57:44.068  6896  7393 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 14:57:44.068  6896  7393 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 14:57:44.068  6896  7393 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-30 14:57:44.068  1035  1035 D BluetoothHeadset: Proxy object connected
,08-30 14:57:44.071  6896  7462 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 14:57:44.071  6896  7462 W bt-smp  : Plain text(LSB ~ MSB) = 38 a3 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 14:57:44.071  6896  7462 W bt-smp  : Encrypted text(LSB ~ MSB) = db 97 3d 48 f5 e1 12 7f 67 aa 9e 22 72 f6 10 30 
08-30 14:57:44.071  6896  7462 W bt-btm  : Stopping oneshot timer
08-30 14:57:44.073  6747  6765 D BluetoothMap: onBluetoothStateChange: up=true
08-30 14:57:44.077  1835  1850 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:57:44.082  6896  7393 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-30 14:57:44.083  1835  1835 D BluetoothHeadset: Proxy object connected
08-30 14:57:44.083  6896  7393 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-30 14:57:44.084  6747  6747 D BluetoothMap: Proxy object connected
08-30 14:57:44.085  6747  6747 D MapProfile: Bluetooth service connected
08-30 14:57:44.085  6747  6747 D BluetoothMap: getConnectedDevices()
08-30 14:57:44.086  6896  6912 V BluetoothMapService: getConnectedDevices()
08-30 14:57:44.088  6747  6765 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 14:57:44.089  6896  7462 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 14:57:44.089  6896  7462 W bt-smp  : Plain text(LSB ~ MSB) = 57 1d 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 14:57:44.089  6896  7462 W bt-smp  : Encrypted text(LSB ~ MSB) = 09 6b 40 d8 dc 8a c9 bf 2b e6 f0 cc 47 a3 f1 5f 
08-30 14:57:44.089  6896  7462 W bt-btm  : Stopping oneshot timer
08-30 14:57:44.091  6747  6767 D BluetoothPan: onBluetoothStateChange on: true
08-30 14:57:44.091  6747  6767 D BluetoothPan: onBluetoothStateChange call bindService
08-30 14:57:44.098  6896  7462 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 14:57:44.098  6896  7462 W bt-smp  : Plain text(LSB ~ MSB) = 59 b9 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 14:57:44.098  6896  7462 W bt-smp  : Encrypted text(LSB ~ MSB) = 46 01 6d 2b 4d ee 68 36 7b b8 02 4b d6 ec 58 2f 
08-30 14:57:44.098  6896  7462 W bt-btm  : Stopping oneshot timer
,08-30 14:57:44.103  6747  6765 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 14:57:44.107  6747  6747 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 14:57:44.107  6747  6747 D PanProfile: Bluetooth service connected
08-30 14:57:44.111  1835  4014 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 14:57:44.115  6747  6747 D BluetoothInputDevice: Proxy object connected
08-30 14:57:44.115  6747  6747 D HidProfile: Bluetooth service connected
08-30 14:57:44.115  1835  1835 D BluetoothHeadset: Proxy object connected
08-30 14:57:44.116  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 14:57:44.117  6896  7462 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 14:57:44.117  6896  7462 W bt-smp  : Plain text(LSB ~ MSB) = f8 46 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 14:57:44.117  6896  7462 W bt-smp  : Encrypted text(LSB ~ MSB) = 1c 28 a9 10 2c da a7 2e 5b 95 5e d6 b0 ab 52 f9 
08-30 14:57:44.117  6896  7462 W bt-btm  : Stopping oneshot timer
08-30 14:57:44.118  1835  4017 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:57:44.119  1035  1035 D BluetoothA2dp: Proxy object connected
08-30 14:57:44.123  1835  1835 D BluetoothHeadset: Proxy object connected
08-30 14:57:44.125  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-30 14:57:44.125  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-30 14:57:44.130  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-30 14:57:44.131  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:44.131  1925  2129 D LGBluetoothAPIService: Message: 1
08-30 14:57:44.131  1925  2129 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-30 14:57:44.132  7508  7508 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-30 14:57:44.132  1035  1117 D BluetoothManagerService: Message: 40
08-30 14:57:44.132  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 14:57:44.134  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 14:57:44.138  6896  6896 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:44.138  6896  6896 D BluetoothMapService: STATE_ON
,08-30 14:57:44.146  1925  2129 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-30 14:57:44.147  6646  6646 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 14:57:44.151  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:44.151  6747  6747 D LocalBluetoothProfileManager: Adding local A2DP profile
08-30 14:57:44.152  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:44.154  1035  1117 D BluetoothManagerService: Message: 30
08-30 14:57:44.155  6896  6896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29136077
08-30 14:57:44.155  6896  6896 V BluetoothPbapService: Pbap Service onCreate
08-30 14:57:44.155  6896  6896 V BluetoothPbapService: Starting PBAP service
,08-30 14:57:44.157  6896  6896 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 14:57:44.157  6896  6896 V BluetoothPbapService: Pbap Service onBind
08-30 14:57:44.158  6747  6747 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-30 14:57:44.158  6896  6896 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:44.158  6896  6896 V BluetoothPbapService: state: 12
08-30 14:57:44.158  6896  6896 V BluetoothMapService: Handler(): got msg=1
08-30 14:57:44.159  6896  6896 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 14:57:44.160  1035  1117 D BluetoothManagerService: Message: 30
08-30 14:57:44.160  6896  7513 D BluetoothMapMasInstance: MAS initSocket()
08-30 14:57:44.160  6896  7513 D BluetoothMapMasInstance:   masId = 00
08-30 14:57:44.160  6896  7513 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 14:57:44.160  6896  7513 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 14:57:44.160  6896  7513 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 14:57:44.160  6896  6896 D LGBluetoothAPIServer: [BTUI] onCreate()
08-30 14:57:44.161  6896  6896 D LGBluetoothAPIServer: [BTUI] onBind()
08-30 14:57:44.162  1035  1630 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:44.162  6896  6896 V BluetoothPbapService: Handler(): got msg=1
08-30 14:57:44.162  1925  1925 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-30 14:57:44.162  1925  2129 D LGBluetoothAPIService: Message: 100
08-30 14:57:44.162  1925  2129 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-30 14:57:44.163  6896  6896 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-30 14:57:44.164  6896  7514 V BluetoothPbapService: Pbap Service initSocket
08-30 14:57:44.164  6896  7513 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 14:57:44.165  1035  1969 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:44.166  6747  6747 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-30 14:57:44.166  6896  7513 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-30 14:57:44.166  6896  7397 D BluetoothAdapterProperties: Scan Mode:21
08-30 14:57:44.166  6896  7513 V BluetoothMapMasInstance: Succeed to create listening socket 
08-30 14:57:44.166  6896  7397 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-30 14:57:44.166  6896  7513 D BluetoothMapMasInstance: Accepting socket connection...
08-30 14:57:44.169  6896  7514 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 14:57:44.169  6747  6747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 14:57:44.169  6896  7514 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-30 14:57:44.169  6896  7514 V BluetoothPbapService: Succeed to create listening socket 
08-30 14:57:44.169  6896  7514 V BluetoothPbapService: Accepting socket connection...
,08-30 14:57:44.172  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:44.173  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:44.174  6747  6747 D BluetoothA2dp: Proxy object connected
08-30 14:57:44.175  6747  6747 D A2dpProfile: Bluetooth service connected
08-30 14:57:44.175  6896  6896 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 14:57:44.176  6896  6896 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:44.176  6896  6896 V BluetoothPbapReceiver: ***********state = 12
08-30 14:57:44.176  6747  6747 D BluetoothPbap: Proxy object connected
08-30 14:57:44.177  6747  6747 D PbapServerProfile: Bluetooth service connected
08-30 14:57:44.177  6747  6747 D BluetoothHeadset: Proxy object connected
08-30 14:57:44.178  6747  6747 D HeadsetProfile: Bluetooth service connected
08-30 14:57:44.179  2169  2169 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 14:57:44.179  2169  2169 D c       : Getting all permits...
,08-30 14:57:44.179  2169  2169 D a       : Opening database...
08-30 14:57:44.186  2169  2169 D a       : Opening database auth.proximity.permit_store...
08-30 14:57:44.186  2169  2169 D a       : Closing database...
08-30 14:57:44.190  6747  6747 D DockEventReceiver: finishStartingService: stopping service
08-30 14:57:44.197  6747  6747 D BluetoothPermissionRequest: onReceive
,08-30 14:57:44.199  6747  6747 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 14:57:44.200  6747  6747 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 14:57:44.204  6896  6896 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-30 14:57:44.205  6896  6896 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 14:57:44.211  6896  6896 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-30 14:57:44.238  6896  6896 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 14:57:44.239  6896  6896 V BtOppService: onCreate
,08-30 14:57:44.243  6896  6896 V BluetoothOppNotification: send message
08-30 14:57:44.246  6896  6896 V BtOppService: Starting RfcommListener
08-30 14:57:44.253  6896  6896 D BluetoothOppPreference: Dumping Names:  
08-30 14:57:44.253  6896  6896 D BluetoothOppPreference: {}
08-30 14:57:44.253  6896  6896 D BluetoothOppPreference: Dumping Channels:  
08-30 14:57:44.253  6896  6896 D BluetoothOppPreference: {}
,08-30 14:57:44.254  6896  6896 V BtOppService: onStartCommand
08-30 14:57:44.259  6896  7521 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 14:57:44.259  6896  7521 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 14:57:44.259  6896  6896 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:44.260  6896  6896 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 14:57:44.260  6896  7518 V BtOppService: Deleted complete outbound shares, number =  0
08-30 14:57:44.262  6896  7521 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2bdfa6e0 on behalf of 
08-30 14:57:44.262  6896  6896 V BluetoothOppNotification: new notify threadi!
08-30 14:57:44.263  6896  7518 V BtOppService: Deleted complete inbound failed shares, number = 0
08-30 14:57:44.263  6896  6896 V BluetoothOppNotification: send delay message
08-30 14:57:44.265  6896  7518 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-30 14:57:44.265  6896  6896 V BtOppService: start RfcommListener
08-30 14:57:44.267  6896  6896 V BtOppService: RfcommListener started
08-30 14:57:44.268  6896  7518 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4527d99 on behalf of 
,08-30 14:57:44.270  6896  6896 V BtOppService: ContentObserver received notification
08-30 14:57:44.271  6896  7523 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 14:57:44.273  6896  7523 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@36ba485e on behalf of 
08-30 14:57:44.273  7147  7191 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-30 14:57:44.273  6896  7523 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 14:57:44.274  6896  7524 V BtOppRfcommListener: Starting RFCOMM listener....
08-30 14:57:44.274  6896  7521 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 14:57:44.274  6896  7521 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 14:57:44.275  1035  1936 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:44.276  6896  7523 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 14:57:44.276  6896  7524 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 14:57:44.278  6896  7524 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-30 14:57:44.278  6896  7523 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2611a43f on behalf of 
08-30 14:57:44.278  6896  7521 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d48510c on behalf of 
08-30 14:57:44.278  6896  7524 V BtOppRfcommListener: Started RFCOMM listener....
08-30 14:57:44.278  6896  7524 I BtOppRfcommListener: Accept thread started.
08-30 14:57:44.278  6896  7524 V BtOppRfcommListener: Accepting connection...
08-30 14:57:44.279  6896  7523 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 14:57:44.279  6896  7521 V BluetoothOppNotification: update too frequent, put in queue
08-30 14:57:44.280  6896  7521 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 14:57:44.281  6896  7523 V BluetoothOppNotification: outbound notification was removed.
08-30 14:57:44.281  6896  7523 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-30 14:57:44.282  6896  7523 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3bc45a55 on behalf of 
08-30 14:57:44.283  6896  7523 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 14:57:44.285  6896  6896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29136077
,08-30 14:57:44.285  6896  6896 V BluetoothFtpService: Ftp Service onCreate
08-30 14:57:44.285  6896  6896 I BluetoothFtpService: Ftp Service onCreate
08-30 14:57:44.285  6896  6896 V BtOppService: ContentObserver received notification
08-30 14:57:44.285  6896  7523 V BluetoothOppNotification: inbound notification was removed.
08-30 14:57:44.285  6896  7523 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 14:57:44.286  6896  6896 V BluetoothFtpService: Ftp Service onStartCommand
08-30 14:57:44.286  6896  6896 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:44.286  6896  6896 V BluetoothFtpService: Starting Listening on sockets
08-30 14:57:44.286  6896  6896 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 14:57:44.286  6896  6896 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 14:57:44.286  6896  6896 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 14:57:44.286  6896  6896 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:44.286  6896  6896 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 14:57:44.286  6896  6896 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 14:57:44.287  6896  7526 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 14:57:44.287  6896  7526 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 14:57:44.288  6896  7526 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@986455b on behalf of 
08-30 14:57:44.288  6896  7526 V BluetoothOppNotification: update too frequent, put in queue
08-30 14:57:44.289  6896  7526 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 14:57:44.289  6896  6896 V BluetoothFtpService: Handler(): got msg=1
08-30 14:57:44.290  6896  6896 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 14:57:44.290  6896  6896 V BluetoothFtpService: Ftp Service initSocket
08-30 14:57:44.290  6896  7523 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@36af71f8 on behalf of 
08-30 14:57:44.294  1035  1874 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:44.295  6896  6896 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 14:57:44.296  6896  6896 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-30 14:57:44.296  6896  6896 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-30 14:57:44.298  6896  7527 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-30 14:57:44.311  6896  6896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29136077
,08-30 14:57:44.312  6896  6896 V BluetoothSapService: Sap Service onCreate
,08-30 14:57:44.314  6896  6896 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 14:57:44.314  6896  6896 V BluetoothSapService: state: 12
08-30 14:57:44.314  6896  6896 V BluetoothSapService: Starting SAP server process
08-30 14:57:44.315  6896  6896 V BluetoothSapService: SAP Service startRfcommListenerThread
08-30 14:57:44.317  6896  7529 V BluetoothSapService: Sap Service initRfcommSocket
08-30 14:57:44.317  1035  1936 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:44.304  7528  7528 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:57:44.304  7528  7528 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:57:44.318  6896  7529 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 14:57:44.318  6896  7529 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-30 14:57:44.318  6896  7529 V BluetoothSapService: Succeed to create listening socket 
08-30 14:57:44.318  6896  7529 V BluetoothSapService: Accepting socket connection...
08-30 14:57:44.344  7528  7528 V BT_SAP  : Event pipe created
08-30 14:57:44.344  7528  7528 V BT_SAP  : create_server_socket qcom.sap.server
08-30 14:57:44.344  7528  7528 V BT_SAP  : created socket fd 6
,08-30 14:57:44.982  1035  1521 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:44.982  1035  1521 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 14:57:45.045  1035  1523 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-30 14:57:45.046  1035  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-30 14:57:45.237  1035  1630 I ActivityManager: Killing 7304:com.lge.bnr/1000 (adj 15): empty #17
,08-30 14:57:45.265  6896  6896 V BluetoothOppNotification: new notify threadi!
08-30 14:57:45.265  6896  6896 V BluetoothOppNotification: send delay message
,08-30 14:57:45.270  6896  7539 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 14:57:45.283  1035  1908 W libprocessgroup: failed to open /acct/uid_1000/pid_7304/cgroup.procs: No such file or directory
,08-30 14:57:45.304  1035  1050 I ActivityManager: Killing 6552:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-30 14:57:45.390  6820  6820 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-30 14:57:45.390  6820  6820 W System.err: android.os.DeadObjectException
08-30 14:57:45.390  6820  6820 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 14:57:45.391  6820  6820 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 14:57:45.391  6820  6820 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-30 14:57:45.391  6820  6820 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-30 14:57:45.391  6820  6820 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 14:57:45.391  6820  6820 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 14:57:45.391  6820  6820 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 14:57:45.391  6820  6820 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 14:57:45.391  6820  6820 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 14:57:45.391  6820  6820 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 14:57:45.391  6820  6820 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:57:45.391  6820  6820 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 14:57:45.391  6820  6820 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 14:57:45.391  6820  6820 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 14:57:45.391  6820  6820 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-30 14:57:45.391  6820  6820 W System.err: android.os.DeadObjectException
08-30 14:57:45.392  6820  6820 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 14:57:45.392  6820  6820 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 14:57:45.392  6820  6820 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-30 14:57:45.392  6820  6820 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-30 14:57:45.395  6820  6820 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 14:57:45.395  6820  6820 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 14:57:45.395  6820  6820 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 14:57:45.395  6820  6820 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 14:57:45.395  6820  6820 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 14:57:45.395  6820  6820 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 14:57:45.395  6820  6820 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:57:45.395  6820  6820 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 14:57:45.395  6820  6820 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 14:57:45.395  6820  6820 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 14:57:45.395  6820  6820 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-30 14:57:45.396  6820  6820 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-30 14:57:45.471  1035  2016 I art     : Explicit concurrent mark sweep GC freed 94324(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 3.851ms total 200.272ms
,08-30 14:57:45.473  6896  7539 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d65b5a4 on behalf of 
08-30 14:57:45.474  6896  7539 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 14:57:45.475  6896  7539 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 14:57:45.477  6896  7539 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27e7f0d on behalf of 
08-30 14:57:45.477  6896  7539 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 14:57:45.479  6896  7539 V BluetoothOppNotification: outbound notification was removed.
08-30 14:57:45.479  6896  7539 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 14:57:45.480  6896  7539 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ba03ec2 on behalf of 
08-30 14:57:45.480  6896  7539 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 14:57:45.482  6896  7539 V BluetoothOppNotification: inbound notification was removed.
08-30 14:57:45.482  6896  7539 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 14:57:45.483  6896  7539 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@326604d3 on behalf of 
08-30 14:57:45.524  1035  1998 W libprocessgroup: failed to open /acct/uid_1000/pid_6552/cgroup.procs: No such file or directory
08-30 14:57:45.525  1035  1998 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-30 14:57:45.531  6820  6820 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-30 14:57:45.532  6820  6820 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 14:57:45.601  1035  1943 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7557 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 14:57:45.603  6820  6820 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-30 14:57:45.715  7557  7557 D UEI.SmartControl: Quickset Services start...
,08-30 14:57:45.718  7557  7557 I UEI.SmartControl: Manufacture = LGE
08-30 14:57:45.718  7557  7557 D UEI.SmartControl: Id = LGNevo
08-30 14:57:45.719  7557  7557 D UEI.SmartControl: File observer start...
08-30 14:57:45.720  7557  7557 E UEI.SmartControl: IR Port is disabled: false
08-30 14:57:45.721  7557  7557 D UEI.SmartControl: Starting file observer...
08-30 14:57:45.721  7557  7557 D UEI.SmartControl: Extracting JNI libs...
08-30 14:57:45.721  7557  7557 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-30 14:57:45.821  7557  7557 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-30 14:57:45.822  7557  7557 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-30 14:57:45.822  7557  7557 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-30 14:57:45.858  7557  7557 I UEI.SmartControl: --- Selecting new region: 6
,08-30 14:57:45.861  7557  7557 I UEI.SmartControl: Model = LG-D855
,08-30 14:57:45.862  7557  7557 D UEI.SmartControl: QS Service created
08-30 14:57:45.880  7557  7557 I UEI.SmartControl: Service initServices...
,08-30 14:57:45.885  7557  7557 D UEI.SmartControl: QS start get config
08-30 14:57:45.931  7557  7557 D UEI.SmartControl: Loading JNI Libs...
,08-30 14:57:45.964  1035  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:45.965  1035  1889 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1030e63e mBinding = false
,08-30 14:57:45.982  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 14:57:45.983  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 14:57:45.983  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-30 14:57:45.983  1035  1117 D BluetoothManagerService: Message: 2
,08-30 14:57:45.988  1035  1117 D BluetoothManagerService: Sending off request.
08-30 14:57:45.989  6896  6912 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 14:57:45.991  6896  7393 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 14:57:45.991  6896  7393 D BluetoothAdapterProperties: Setting state to 13
08-30 14:57:45.991  6896  7393 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 14:57:45.992  6896  7393 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 14:57:45.993  6896  7393 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 14:57:45.994  6896  7397 D BluetoothAdapterProperties: Scan Mode:20
08-30 14:57:45.994  6896  7393 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 14:57:45.998  6896  7393 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 14:57:46.001  6896  7527 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-30 14:57:46.001  6896  7529 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 14:57:46.002  6896  7462 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 14:57:46.002  6896  7462 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-30 14:57:46.000  6896  7524 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 14:57:46.003  6896  7514 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 14:57:46.004  1035  1117 D BluetoothManagerService: Message: 60
08-30 14:57:46.004  6896  7513 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 14:57:46.004  6896  7513 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 14:57:46.004  6896  7513 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 14:57:46.004  6896  7513 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 14:57:46.004  6896  7513 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 14:57:46.004  6896  7513 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 14:57:46.004  6896  7513 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 14:57:46.004  6896  7513 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-30 14:57:46.005  6896  7462 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 14:57:46.005  6896  7462 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 14:57:46.005  6896  7462 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 14:57:46.005  6896  7462 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 14:57:46.005  6896  7462 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 14:57:46.005  6896  7462 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 14:57:46.005  6896  7462 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 14:57:46.005  6896  7462 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 14:57:46.005  6896  7462 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 14:57:46.005  6896  7462 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 14:57:46.005  6896  7462 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 14:57:46.005  6896  7462 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 14:57:46.005  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-30 14:57:46.005  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-30 14:57:46.006  6646  6646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:57:46.006  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:57:46.006  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:46.006  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:46.006  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:57:46.006  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:57:46.006  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:57:46.006  6646  6646 V io.jxcore.node.C,onnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:57:46.006  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:57:46.006  6646  6646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:57:46.006  6646  6646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:57:46.007  6646  6646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:57:46.008  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:57:46.008  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:46.008  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:46.008  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:57:46.008  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 14:57:46.008  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:57:46.008  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:57:46.008  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 14:57:46.008  6646  6646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 14:57:46.008  6646  6646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:57:46.012  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:46.015  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 14:57:46.016  6896  6896 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:46.016  6896  6896 D BluetoothMapService: STATE_TURNING_OFF
08-30 14:57:46.017  6896  6896 V BtOppService: Receiver DISABLED_ACTION 
08-30 14:57:46.018  6896  6896 V BluetoothMapService: Handler(): got msg=4
08-30 14:57:46.018  6896  6896 D BluetoothMapService: MAP Service closeService in
08-30 14:57:46.018  6896  6896 D BluetoothMapMasInstance: MAP Service shutdown
08-30 14:57:46.018  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:46.018  6896  6896 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 14:57:46.018  6896  6896 V BluetoothMapService: MAP Service closeService out
08-30 14:57:46.018  6896  6896 I BtOppRfcommListener: stopping Accept Thread
08-30 14:57:46.018  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:46.019  6896  6896 V BtOppRfcommListener: close mBtServerSocket
08-30 14:57:46.019  6896  6896 V BtOppRfcommListener: waiting for thread to terminate
08-30 14:57:46.019  6896  7524 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 14:57:46.020  6896  6896 V BtOppRfcommListener: done waiting for thread to terminate
08-30 14:57:46.020  6747  6747 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-30 14:57:46.021  6896  6896 V BtOppService: onDestroy
08-30 14:57:46.023  6896  6896 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 14:57:46.029  6747  6747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 14:57:46.040  6896  6896 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 14:57:46.040  6896  6896 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:46.040  6896  6896 V BluetoothPbapReceiver: ***********state = 13
08-30 14:57:46.041  6896  6896 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-30 14:57:46.043  6896  6896 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:46.043  6896  6896 V BluetoothPbapService: state: 13
08-30 14:57:46.043  6896  6896 V BluetoothPbapService: Pbap Service closeService in
08-30 14:57:46.047  2169  2169 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 14:57:46.053  6896  6896 V BluetoothPbapService: successfully stopped pbap service
08-30 14:57:46.053  6896  6896 V BluetoothPbapService: Pbap Service closeService out
08-30 14:57:46.054  6896  6896 V BluetoothPbapService: Pbap Service onDestroy
08-30 14:57:46.054  6896  6896 V BluetoothPbapService: Pbap Service closeService in
08-30 14:57:46.054  6896  6896 V BluetoothPbapService: Pbap Service closeService out
08-30 14:57:46.054  6896  6896 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-30 14:57:46.058  6747  6747 D DockEventReceiver: finishStartingService: stopping service
08-30 14:57:46.058  6747  6747 D BluetoothPbap: Proxy object disconnected
08-30 14:57:46.058  6747  6747 D PbapServerProfile: Bluetooth service disconnected
08-30 14:57:46.067  6747  6747 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-30 14:57:46.072  6747  6747 D BluetoothPermissionRequest: onReceive
08-30 14:57:46.072  6747  6747 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-30 14:57:46.079  6747  6747 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 14:57:46.082  6896  6896 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-30 14:57:46.082  6896  6896 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-30 14:57:46.083  6896  6896 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-30 14:57:46.086  6896  6896 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:46.086  6896  6896 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 14:57:46.087  6896  6896 V BluetoothFtpService: Ftp Service onStartCommand
08-30 14:57:46.087  6896  6896 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:46.087  6896  6896 V BluetoothFtpService: Ftp Service closeService
08-30 14:57:46.087  6896  6896 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-30 14:57:46.089  6896  6896 V BluetoothFtpService: successfully stopped ftp service
08-30 14:57:46.089  6896  6896 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 14:57:46.089  6896  6896 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 14:57:46.089  6896  6896 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 14:57:46.089  6896  6896 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:46.089  6896  6896 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 14:57:46.089  6896  6896 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 14:57:46.091  6896  6896 V BluetoothFtpService: Ftp Service onDestroy
08-30 14:57:46.091  6896  6896 V BluetoothFtpService: Ftp Service closeService
08-30 14:57:46.094  6896  6896 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:46.094  6896  6896 V BluetoothSapService: state: 13
08-30 14:57:46.094  6896  6896 V BluetoothSapService: Stopping SAP server process
08-30 14:57:46.095  6896  6896 V BluetoothSapService: Sap Service closeSapService in
08-30 14:57:46.095  6896  6896 V BluetoothSapService: Close listen Socket : 
08-30 14:57:46.095  6896  6896 V BluetoothSapService: Close rfcomm Socket : 
08-30 14:57:46.095  6896  6896 V BluetoothSapService: Close sapd  Socket : 
08-30 14:57:46.097  6896  6896 V BluetoothSapService: Sap Service closeSapService out
08-30 14:57:46.097  6896  6896 V BluetoothSapService: Sap Service onDestroy
08-30 14:57:46.097  6896  6896 V BluetoothSapService: Sap Service closeSapService in
08-30 14:57:46.098  6896  6896 V BluetoothSapService: Close listen Socket : 
08-30 14:57:46.098  6896  6896 V BluetoothSapService: Close rfcomm Socket : 
08-30 14:57:46.098  6896  6896 V BluetoothSapService: Close sapd  Socket : 
08-30 14:57:46.098  6896  6896 V BluetoothSapService: Sap Service closeSapService out
,08-30 14:57:46.270  7557  7557 I UEI.SmartControl: Supports setup maps: true
,08-30 14:57:46.274  7557  7557 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 14:57:46.274  7557  7557 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 14:57:46.274  7557  7557 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 14:57:46.274  7557  7557 I UEI.SmartControl: ### init IR Blaster...
08-30 14:57:46.280  7557  7557 D serial_port: Configuring serial port
08-30 14:57:46.284  7557  7557 E UEI.SmartControl: UEIBLaster setting for 616
08-30 14:57:46.284  7557  7557 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 14:57:46.284  7557  7557 I UEI.SmartControl: configuring settings for MAXQ616
08-30 14:57:46.284  7557  7557 I UEI.SmartControl: Get version...
08-30 14:57:46.301  7557  7596 D UEI.SmartControl: serial port data available: 21
,08-30 14:57:46.329  7557  7557 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-30 14:57:46.329  7557  7557 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 14:57:46.329  7557  7557 I UEI.SmartControl: QS saving settings...
08-30 14:57:46.330  7557  7557 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 14:57:46.346  7557  7596 D UEI.SmartControl: serial port data available: 4
,08-30 14:57:46.386  7557  7602 I UEI.SmartControl: Device manager: loading config....
08-30 14:57:46.387  7557  7602 D UEI.SmartControl: ----------- loading internal config...
,08-30 14:57:46.391  7557  7557 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 14:57:46.394  7557  7557 E UEI.SmartControl: Services init done
08-30 14:57:46.395  7557  7557 D UEI.SmartControl: QS Service init finished
08-30 14:57:46.397  7557  7557 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 14:57:46.397  7557  7557 D UEI.SmartControl: QS Service version code: 201091
08-30 14:57:46.398  7557  7557 D UEI.SmartControl: Service requested: Control
08-30 14:57:46.406  7557  7602 E UEI.SmartControl: Loading SETTINGS...
08-30 14:57:46.411  7557  7557 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-30 14:57:46.425  6820  6820 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-30 14:57:46.425  1035  2016 I ActivityManager: Killing 6820:com.lge.qremote/u0a112 (adj 15): empty #17
08-30 14:57:46.426  7557  7572 I UEI.SmartControl: ------ IControl API: 11
08-30 14:57:46.428  7557  7572 I UEI.SmartControl: Registering callback...
08-30 14:57:46.440  7557  7602 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-30 14:57:46.467  7557  7601 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 14:57:46.467  7557  7601 D UEI.SmartControl: -----service ready thread exits
,08-30 14:57:46.486  1035  1943 W libprocessgroup: failed to open /acct/uid_10112/pid_6820/cgroup.procs: No such file or directory
,08-30 14:57:46.489  7557  7557 D UEI.SmartControl: Internal service binding...
,08-30 14:57:46.939  6896  7397 D bt_hci_bdroid: cleanup
,08-30 14:57:46.949  6896  7464 I bt_lpm  : LPM is already off!!!
08-30 14:57:46.950  6896  7491 I bt_userial_mct: exiting userial_read_thread
08-30 14:57:46.950  6896  7491 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 14:57:46.951  6896  7462 W bt-btif : ag scb idx 1 not allocated
08-30 14:57:46.951  6896  7462 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 14:57:46.951  6896  7462 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 14:57:46.951  6896  7462 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 14:57:46.951  6896  7462 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 14:57:46.951  6896  7462 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 14:57:46.951  6896  7462 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 14:57:46.951  6896  7462 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 14:57:46.951  6896  7462 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 14:57:46.951  6896  7462 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 14:57:46.951  6896  7462 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 14:57:46.951  6896  7462 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 14:57:46.951  6896  7462 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 14:57:46.952  6896  7462 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 14:57:46.952  6896  7462 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 14:57:46.952  6896  7462 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 14:57:46.952  6896  7462 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 14:57:46.952  6896  7462 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 14:57:46.952  6896  7462 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 14:57:46.952  6896  7462 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 14:57:46.952  6896  7462 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 14:57:46.954  6896  7397 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 14:57:46.954  6896  7464 I bt_vendor: hw_epilog_process
08-30 14:57:46.955  6896  7397 D bt_hci_bdroid: cleanup Finalizing cleanup
08-30 14:57:46.955  6896  7397 D bt_userial_mct: userial_close
08-30 14:57:46.955  6896  7397 E bt_userial_mct: pthread_join() FAILED result:3
08-30 14:57:46.955  6896  7397 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-30 14:57:46.963  6896  7397 D bt_hci_bdroid: set_power 0
08-30 14:57:46.963  6896  7397 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 14:57:46.963  6896  7397 I bt_vendor: bluetooth satus is on
08-30 14:57:46.963  6896  7397 I bt_vendor: bt-vendor : resetting BT status
08-30 14:57:46.963  6896  7397 I bt_vendor: Starting hciattach daemon
08-30 14:57:46.963  6896  7397 I bt_vendor: try to set false
,08-30 14:57:46.970  6896  7397 I bt_vendor: Starting hciattach daemon
08-30 14:57:46.970  6896  7397 I bt_vendor: try to set false
08-30 14:57:46.972  6896  7397 I bt_vendor: cleanup
08-30 14:57:46.972  6896  7462 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 14:57:46.973  6896  7397 I GKI_LINUX: GKI_exit_task 0 done
08-30 14:57:46.973  6896  7397 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 14:57:46.974  6896  7393 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 14:57:46.979  6896  6896 D HeadsetService: Received stop request...Stopping profile...
,08-30 14:57:46.983  6896  6896 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 14:57:46.984  6896  6896 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 14:57:46.984  6896  6896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29136077
08-30 14:57:46.987  6896  7433 D HeadsetStateMachine: Exit Disconnected: -1
08-30 14:57:46.988  1035  1035 D BluetoothHeadset: Proxy object disconnected
08-30 14:57:46.988  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 14:57:46.989  1835  1835 D BluetoothHeadset: Proxy object disconnected
08-30 14:57:46.989  1835  1835 D BluetoothHeadset: Proxy object disconnected
08-30 14:57:46.989  1835  1835 D BluetoothHeadset: Proxy object disconnected
08-30 14:57:46.990  6896  6896 D A2dpService: Received stop request...Stopping profile...
08-30 14:57:46.991  6896  7448 D A2dpStateMachine: Exit Disconnected: -1
,08-30 14:57:46.995  6896  6896 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-30 14:57:46.998  6896  6896 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-30 14:57:46.998  6896  6896 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 14:57:46.998  6896  6896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29136077
08-30 14:57:47.001  1035  1035 D BluetoothA2dp: Proxy object disconnected
08-30 14:57:47.001  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 14:57:47.002  6896  7393 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-30 14:57:47.005  6896  6896 D HidService: Received stop request...Stopping profile...
08-30 14:57:47.005  6896  6896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29136077
08-30 14:57:47.008  6896  6896 D HealthService: Received stop request...Stopping profile...
08-30 14:57:47.009  6896  6896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29136077
08-30 14:57:47.010  6896  6896 D HeadsetStateMachine: Unbinding service...
08-30 14:57:47.014  6896  6896 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 14:57:47.014  6896  6896 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 14:57:47.014  6896  6896 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 14:57:47.014  6896  6896 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 14:57:47.014  6896  6896 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 14:57:47.014  6896  6896 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 14:57:47.014  6896  6896 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,08-30 14:57:47.018  6896  6896 D PanService: Received stop request...Stopping profile...
08-30 14:57:47.018  6896  6896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29136077
08-30 14:57:47.019  6896  6896 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 14:57:47.020  6896  6896 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 14:57:47.020  6896  6896 D BtGatt.GattService: stop()
08-30 14:57:47.020  6896  6896 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 14:57:47.022  6896  6896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29136077
08-30 14:57:47.024  6896  6896 I BluetoothA2dpServiceJni: cleanupNative
08-30 14:57:47.024  6896  7449 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 14:57:47.025  6896  6896 I GKI_LINUX: GKI_exit_task 2 done
08-30 14:57:47.025  6896  6896 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 14:57:47.026  6896  6896 D BluetoothMapService: Received stop request...Stopping profile...
08-30 14:57:47.026  6896  6896 D BluetoothMapService: stop()
,08-30 14:57:47.029  6896  6896 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 14:57:47.030  6896  6896 D BluetoothMapEmailAppObserver: removeReceiver()
08-30 14:57:47.030  6896  6896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29136077
08-30 14:57:47.032  6896  6896 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 14:57:47.032  6896  6896 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 14:57:47.032  6896  6896 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 14:57:47.033  6896  6896 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 14:57:47.033  6896  6896 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 14:57:47.033  6896  6896 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 14:57:47.033  6896  6896 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 14:57:47.036  6896  6896 V BluetoothMapService: Handler(): got msg=4
08-30 14:57:47.036  6896  6896 D BluetoothMapService: MAP Service closeService in
08-30 14:57:47.036  6896  6896 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 14:57:47.038  6896  6896 V BluetoothMapService: MAP Service closeService out
,08-30 14:57:47.040  6896  7393 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 14:57:47.041  6896  7393 D BluetoothAdapterProperties: Setting state to 10
08-30 14:57:47.041  6896  7393 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 14:57:47.041  6896  6896 D BluetoothMapService: cleanup()
08-30 14:57:47.041  6896  6896 D BluetoothMapService: MAP Service closeService in
08-30 14:57:47.041  6896  6896 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 14:57:47.041  6896  6896 V BluetoothMapService: MAP Service closeService out
08-30 14:57:47.044  1035  1117 D BluetoothManagerService: Message: 60
08-30 14:57:47.044  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 14:57:47.044  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-30 14:57:47.044  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:57:47.044  6896  7393 I BluetoothAdapterState: Entering OffState
08-30 14:57:47.045  6747  6767 D BluetoothMap: onBluetoothStateChange: up=false
08-30 14:57:47.046  1835  4020 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:57:47.046  6747  6767 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 14:57:47.047  6747  6767 D BluetoothPan: onBluetoothStateChange on: false
08-30 14:57:47.049  6747  6767 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 14:57:47.049  1835  1851 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 14:57:47.052  6747  6767 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:57:47.053  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 14:57:47.053  6747  6767 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 14:57:47.054  1835  2412 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 14:57:47.055  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 14:57:47.055  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 14:57:47.056  1035  1117 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 14:57:47.057  1035  1117 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 14:57:47.057  1035  1117 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1030e63e mBinding = false
08-30 14:57:47.057  1035  1117 D BluetoothManagerService: Sending unbind request.
08-30 14:57:47.062  6896  7397 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-30 14:57:47.065  6896  6896 I GKI_LINUX: GKI_exit_task 1 done
08-30 14:57:47.065  6896  6896 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 14:57:47.065  6896  6896 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 14:57:47.066  6896  6896 I art     : --- WEIRD: removing null entry 248
08-30 14:57:47.066  6896  6896 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-30 14:57:47.066  6896  6896 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-30 14:57:47.067  6896  6896 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-30 14:57:47.068  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-30 14:57:47.070  6896  6896 I art     : System.exit called, status: 0
08-30 14:57:47.070  6896  6896 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 14:57:47.089   311  1369 V AudioFlinger: 6896 died, releasing its sessions
08-30 14:57:47.089   311  1369 V AudioFlinger:  pid 1835 @ 0
08-30 14:57:47.089   311  1369 V AudioFlinger:  pid 3482 @ 1
08-30 14:57:47.089   311  1369 V AudioFlinger:  pid 3482 @ 2
,08-30 14:57:47.099  1925  1925 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
,08-30 14:57:47.099  1925  2129 D LGBluetoothAPIService: Message: 101
,08-30 14:57:47.099  1925  2129 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-30 14:57:47.100  1925  2129 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-30 14:57:47.100  1925  2129 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-30 14:57:47.100  6747  6747 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-30 14:57:47.173  1035  1908 I ActivityManager: Process com.android.bluetooth (pid 6896) has died
08-30 14:57:47.174  1035  1908 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-30 14:57:47.174  1035  1908 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 10999ms
,08-30 14:57:47.184  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:47.185  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 14:57:47.186  1925  2129 D LGBluetoothAPIService: Message: 2
08-30 14:57:47.186  1925  2129 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-30 14:57:47.191  6747  6747 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 14:57:47.191  6747  6747 D LGBluetoothEventManager: [BTUI] clear device connection state
08-30 14:57:47.192  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:47.194  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:57:47.195  1587  1587 D BluetoothAdapter: 385424078: getState() :  mService = null. Returning STATE_OFF
08-30 14:57:47.195  1587  1587 D BluetoothAdapter: 385424078: getState() :  mService = null. Returning STATE_OFF
,08-30 14:57:47.197  6747  6747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 14:57:47.255  1035  1874 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7631 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-30 14:57:47.259  6747  6747 D DockEventReceiver: finishStartingService: stopping service
,08-30 14:57:47.345  7631  7631 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-30 14:57:47.346  7631  7631 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 14:57:47.346  7631  7631 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-30 14:57:47.347  7631  7631 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 14:57:47.367  7631  7631 D BluetoothAdapterApp: Loading JNI Library
,08-30 14:57:47.402  7631  7631 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@7c7e07f Instance Count = 1
,08-30 14:57:47.409  7631  7631 D BluetoothAdapterApp: onCreate
,08-30 14:57:47.435  7631  7631 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-30 14:57:47.435  7631  7631 D ProfileConfigQcom: Adding HeadsetService
,08-30 14:57:47.436  7631  7631 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-30 14:57:47.436  7631  7631 D ProfileConfigQcom: Adding A2dpService
08-30 14:57:47.437  7631  7631 D ProfileConfigQcom: [BTUI] HidService is supported
08-30 14:57:47.437  7631  7631 D ProfileConfigQcom: Adding HidService
08-30 14:57:47.438  7631  7631 D ProfileConfigQcom: [BTUI] HealthService is supported
08-30 14:57:47.438  7631  7631 D ProfileConfigQcom: Adding HealthService
08-30 14:57:47.439  7631  7631 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-30 14:57:47.441  7631  7631 D ProfileConfigQcom: [BTUI] PanService is supported
08-30 14:57:47.441  7631  7631 D ProfileConfigQcom: Adding PanService
08-30 14:57:47.442  7631  7631 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 14:57:47.443  7631  7631 D ProfileConfigQcom: Adding GattService
08-30 14:57:47.443  7631  7631 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-30 14:57:47.444  7631  7631 D ProfileConfigQcom: Adding BluetoothMapService
08-30 14:57:47.445  7631  7631 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 14:57:47.449  7631  7631 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-30 14:57:47.452  7631  7631 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-30 14:57:47.452  7631  7631 V BluetoothPbapReceiver: ***********state = 10
08-30 14:57:47.457  7631  7631 V LGMDMManagerInternal: Create singleton instance
08-30 14:57:47.557  7631  7631 D LGBluetoothAPIServer: [BTUI] onCreate()
08-30 14:57:47.557  7631  7631 D LGBluetoothAPIServer: [BTUI] onBind()
,08-30 14:57:47.565  2169  2169 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 14:57:47.566  6747  6747 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 14:57:47.566  1925  1925 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-30 14:57:47.566  1925  2129 D LGBluetoothAPIService: Message: 100
08-30 14:57:47.567  1925  2129 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-30 14:57:47.586  6747  6747 D BluetoothPermissionRequest: onReceive
,08-30 14:57:47.588  6747  6747 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 14:57:47.588  6747  6747 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-30 14:57:47.591  6747  6747 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 14:57:47.596  7631  7631 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-30 14:57:47.599  7631  7631 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-30 14:57:47.603  7631  7631 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-30 14:57:47.603  7631  7631 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 14:57:47.603  7631  7631 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 14:57:47.604  7631  7631 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:47.605  7631  7631 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-30 14:57:47.607  6840  6840 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-30 14:57:48.987  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:57:48.987  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 14:57:49.080  1587  1587 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-30 14:57:49.098  1035  1439 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 14:57:49.123  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-30 14:57:49.140  1035  1035 D administrator: Handling package changes for user 0
,08-30 14:57:49.242  1035  1098 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7658 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-30 14:57:49.249  1587  1587 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-30 14:57:49.250  1587  1587 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-30 14:57:49.260  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 14:57:49.311  7658  7658 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 14:57:49.319  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-30 14:57:49.319  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-30 14:57:49.373  1035  1097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 14:57:49.378  1035  1097 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-30 14:57:49.384  2489  2489 V GmsNetworkLocationProvi: DISABLE
08-30 14:57:49.387  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-30 14:57:49.390  7658  7658 D LgDataFeature: LgDataFeature() Constructor: none
08-30 14:57:49.391  7658  7658 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 14:57:49.408  1035  1097 D LocationProviderProxy: applying state to connected service
,08-30 14:57:49.409  2489  2489 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-30 14:57:49.502  7658  7703 I Babel   : MmsConfig: mnc/mcc: 0/0
08-30 14:57:49.502  7658  7703 I Babel   : MmsConfig.loadMmsSettings
08-30 14:57:49.507  7658  7703 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-30 14:57:49.507  7658  7703 I Babel   : MmsConfig.loadFromDatabase
08-30 14:57:49.529  7658  7703 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-30 14:57:49.529  7658  7703 I Babel   : MmsConfig.loadFromResources
08-30 14:57:49.532  7658  7703 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-30 14:57:49.533  7658  7703 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-30 14:57:49.537  7658  7658 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 14:57:49.565  1800  7705 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-30 14:57:49.565  1800  7705 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-30 14:57:49.570  6959  6959 I AppUp4:CustModeStarterReceiver: onReceive
08-30 14:57:49.573  1800  4670 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-30 14:57:49.575  6959  6959 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1af7a111
08-30 14:57:49.575  6959  6959 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 14:57:49.575  6959  6959 D AppUp4:CustFacade: isPhone : true
08-30 14:57:49.575  6959  6959 D AppUp4:CustModeStarterReceiver: begin check event
08-30 14:57:49.576  6959  6959 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-30 14:57:49.581  7658  7701 W AudioCapabilities: Unsupported mime audio/evrc
08-30 14:57:49.582  7658  7701 W AudioCapabilities: Unsupported mime audio/qcelp
,08-30 14:57:49.585  7658  7701 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 14:57:49.606  7658  7701 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-30 14:57:49.606  7658  7701 W AudioCapabilities: Unsupported mime audio/qcelp
,08-30 14:57:49.607  7658  7701 W AudioCapabilities: Unsupported mime audio/evrc
08-30 14:57:49.615  7658  7701 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-30 14:57:49.618  1035  1630 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7708 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-30 14:57:49.618  7658  7701 W VideoCapabilities: Unsupported mime video/divx
,08-30 14:57:49.621  1035  1050 I ActivityManager: Killing 6789:com.lge.sync/1000 (adj 15): empty #17
08-30 14:57:49.621  7658  7701 W VideoCapabilities: Unsupported mime video/divx311
08-30 14:57:49.623  7658  7701 W VideoCapabilities: Unsupported mime video/divx4
08-30 14:57:49.627  7658  7701 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-30 14:57:49.634  1035  1528 D WifiService: Client connection lost with reason: 4
,08-30 14:57:49.639  7658  7701 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-30 14:57:49.642  7658  7701 W AudioCapabilities: Unsupported mime audio/eac3
08-30 14:57:49.643  7658  7701 W AudioCapabilities: Unsupported mime audio/ac3
08-30 14:57:49.644  7658  7701 W AudioCapabilities: Unsupported mime audio/g726
08-30 14:57:49.645  7658  7701 W AudioCapabilities: Unsupported mime audio/wma-voice
08-30 14:57:49.645  7658  7701 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-30 14:57:49.646  7658  7701 W AudioCapabilities: Unsupported mime audio/adpcm
08-30 14:57:49.647  7658  7701 W VideoCapabilities: Unsupported mime video/theora
08-30 14:57:49.649  7658  7701 W VideoCapabilities: Unsupported mime video/mjpg
,08-30 14:57:49.726  1035  1998 W libprocessgroup: failed to open /acct/uid_1000/pid_6789/cgroup.procs: No such file or directory
08-30 14:57:49.760  7708  7708 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 14:57:49.760  7708  7708 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 14:57:49.761  7708  7708 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 14:57:49.762  7708  7708 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-30 14:57:49.762  7708  7708 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-30 14:57:49.813  7708  7708 I SystemConfig: BUILD Country: EU
08-30 14:57:49.813  7708  7708 I SystemConfig: BUILD Operator: OPEN
,08-30 14:57:49.852  1035  2034 I ActivityManager: Killing 6985:com.lge.email/u0a23 (adj 15): empty #17
,08-30 14:57:49.988  1035  1969 W libprocessgroup: failed to open /acct/uid_10023/pid_6985/cgroup.procs: No such file or directory
,08-30 14:57:50.046  1035  2034 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7732 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-30 14:57:50.052  7708  7727 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-30 14:57:50.053  7708  7727 I SystemConfig: existFile = false
08-30 14:57:50.053  7708  7727 I SystemConfig: canReadFile = false
08-30 14:57:50.053  7708  7727 I SystemConfig: systemFeature RCS result false
08-30 14:57:50.053  7708  7727 D SystemConfig: refreshRcsSupport() :false
,08-30 14:57:50.113  7732  7732 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 14:57:50.113  7732  7732 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 14:57:50.114  7732  7732 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 14:57:50.115  7732  7732 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-30 14:57:50.225  7732  7732 I AppConfig: Total System Memory = 2995761152
,08-30 14:57:50.236  7732  7732 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-30 14:57:50.356  1035  1998 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7754 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 14:57:50.356  1035  1998 I ActivityManager: Killing 6873:com.lge.formmanager/u0a26 (adj 15): empty #17
08-30 14:57:50.424  1035  2016 W libprocessgroup: failed to open /acct/uid_10026/pid_6873/cgroup.procs: No such file or directory
,08-30 14:57:50.603  7754  7754 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-30 14:57:50.693  7754  7754 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 14:57:50.700  7754  7754 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 14:57:50.751  7754  7754 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-30 14:57:50.770  7754  7754 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 14:57:50.771  7754  7754 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-30 14:57:50.788  7754  7754 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 14:57:50.788  7754  7754 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-30 14:57:50.808  1035  1770 I ActivityManager: Killing 6359:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-30 14:57:50.847  1035  1969 W libprocessgroup: failed to open /acct/uid_1000/pid_6359/cgroup.procs: No such file or directory
,08-30 14:57:50.855  4583  7791 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-30 14:57:50.861  2831  2944 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-30 14:57:50.862  2831  2944 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1dd32de5 on behalf of 7754
08-30 14:57:50.907  1035  1559 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7792 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-30 14:57:50.959  7754  7754 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-30 14:57:50.996  7754  7754 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-30 14:57:51.020  7792  7792 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-30 14:57:51.048  7792  7792 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-30 14:57:51.048  7792  7792 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-30 14:57:51.048  7792  7792 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-30 14:57:51.049  7792  7792 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-30 14:57:51.049  7792  7792 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-30 14:57:51.049  7792  7792 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-30 14:57:51.066  1035  1051 I ActivityManager: Killing 7028:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-30 14:57:51.178  1035  1050 W libprocessgroup: failed to open /acct/uid_10046/pid_7028/cgroup.procs: No such file or directory
,08-30 14:57:51.387  7557  7603 D UEI.SmartControl: Internal timer expired: 1
08-30 14:57:51.387  7557  7603 D UEI.SmartControl: unbind internal service
,08-30 14:57:51.392  7557  7557 D UEI.SmartControl: Service.onUnbind: IControl
08-30 14:57:51.393  7557  7557 D UEI.SmartControl: Service.onDestroy
08-30 14:57:51.393  7557  7557 D UEI.SmartControl: Lock is in USE false
08-30 14:57:51.393  7557  7557 D UEI.SmartControl: unbind internal service
08-30 14:57:51.394  7557  7557 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@e243d4d
08-30 14:57:51.394  7557  7557 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-30 14:57:51.395  7557  7557 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-30 14:57:51.395  7557  7557 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-30 14:57:51.395  7557  7557 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-30 14:57:51.395  7557  7557 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-30 14:57:51.395  7557  7557 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-30 14:57:51.395  7557  7557 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-30 14:57:51.395  7557  7557 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-30 14:57:51.395  7557  7557 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:57:51.395  7557  7557 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 14:57:51.396  7557  7557 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 14:57:51.396  7557  7557 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:57:51.396  7557  7557 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 14:57:51.396  7557  7557 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 14:57:51.396  7557  7557 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 14:57:51.396  7557  7557 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@e243d4d
08-30 14:57:51.397  7557  7557 D serial_port: close(fd = 25)
08-30 14:57:51.400  7557  7557 I UEI.SmartControl: Serial port is closed.
08-30 14:57:51.402  7557  7557 I UEI.SmartControl: Serial port is closed.
,08-30 14:57:51.403  7557  7557 D UEI.SmartControl: Blaster closed
08-30 14:57:51.403  7557  7557 D UEI.SmartControl: Shut down QS...
08-30 14:57:51.403  7557  7557 D UEI.SmartControl: Stopping QS lib
08-30 14:57:51.404  7557  7557 D UEI.SmartControl: QS lib stop result = true
08-30 14:57:51.404  7557  7557 D UEI.SmartControl: Stopped QS lib
08-30 14:57:51.404  7557  7557 D UEI.SmartControl: Stopped file observer...
08-30 14:57:51.405  7557  7557 D UEI.SmartControl: QS shutdown complete
08-30 14:57:51.414  1035  1979 V SIM_STK : Menu title from STK is T-Mobile
08-30 14:57:51.436  4583  7791 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 582 ms] updated apps [took 582 ms] 
,08-30 14:57:52.004  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 14:57:52.005  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dd8517b added. We now have 6 listener(s)
08-30 14:57:52.005  6646  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 14:57:52.016  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:57:52.016  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e105b98 added. We now have 7 listener(s)
08-30 14:57:52.016  6646  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:57:52.017  6646  6725 I System.out: IsBluetoothEnabled
08-30 14:57:52.019  1035  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:52.020  1035  1908 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-30 14:57:52.021  1035  1117 D BluetoothManagerService: Message: 2
08-30 14:57:52.024  6646  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:57:52.027  1035  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:52.027  1035  1998 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-30 14:57:52.046  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 14:57:52.047  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 14:57:52.047  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-30 14:57:52.048  1035  1117 D BluetoothManagerService: Message: 1
08-30 14:57:52.048  1035  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-30 14:57:52.073  1035  1117 D BluetoothManagerService: Message: 20
08-30 14:57:52.073  1035  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16cd836c:true
,08-30 14:57:52.077  7631  7631 D BluetoothAdapterState: make
08-30 14:57:52.082  7631  7631 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 14:57:52.082  7631  7631 I bluedroid-qcom: init
08-30 14:57:52.084  7631  7837 I BluetoothAdapterState: Entering OffState
08-30 14:57:52.084  7631  7631 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 14:57:52.084  7631  7631 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 14:57:52.084  7631  7631 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 14:57:52.084  7631  7631 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 14:57:52.084  7631  7631 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 14:57:52.086  7631  7631 I bluedroid-qcom: get_profile_interface socket
08-30 14:57:52.086  7631  7631 I bluedroid-qcom: get_profile_interface map_client
,08-30 14:57:52.091  7631  7841 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 14:57:52.074  7840  7840 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:57:52.095  7631  7841 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 14:57:52.084  7840  7840 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:57:52.105  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 14:57:52.106  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
,08-30 14:57:52.110  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-30 14:57:52.110  1035  1117 D BluetoothManagerService: Message: 40
08-30 14:57:52.110  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 14:57:52.111  7631  7647 I bluedroid-qcom: config_hci_snoop_log
08-30 14:57:52.113  7840  7840 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 14:57:52.113  7840  7840 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 14:57:52.113  7840  7840 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-30 14:57:52.114  1035  1117 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 14:57:52.114  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 14:57:52.116  7840  7840 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-30 14:57:52.118  7631  7841 D BluetoothAdapterProperties: Name is: G3
,08-30 14:57:52.123  7840  7840 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 14:57:52.123  7840  7840 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-30 14:57:52.127  7631  7837 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-30 14:57:52.128  7631  7837 D BluetoothAdapterProperties: Setting state to 11
08-30 14:57:52.128  7631  7837 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 14:57:52.129  7631  7837 I LGBluetoothServiceJni: classInitNative: succeeds
08-30 14:57:52.133  1035  1117 D BluetoothManagerService: Message: 60
08-30 14:57:52.133  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 14:57:52.133  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-30 14:57:52.137  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:52.140  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 14:57:52.143  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:52.147  6747  6747 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-30 14:57:52.168  7631  7631 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 14:57:52.168  7631  7631 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:52.168  7631  7631 V BluetoothPbapReceiver: ***********state = 11
08-30 14:57:52.169  7631  7837 D BluetoothBondStateMachine: make
,08-30 14:57:52.176  2169  2169 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 14:57:52.178  7631  7837 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ae84e4
08-30 14:57:52.179  7631  7837 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 14:57:52.179  7631  7837 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ae84e4
08-30 14:57:52.179  7631  7837 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-30 14:57:52.180  7631  7837 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-30 14:57:52.182  7631  7855 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 14:57:52.185  7631  7837 E BluetoothAdapterService: File transfer profiles supported!!
08-30 14:57:52.190  6747  6747 D BluetoothPermissionRequest: onReceive
08-30 14:57:52.194  7631  7837 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 14:57:52.197  7631  7631 D HeadsetService: Received start request. Starting profile...
08-30 14:57:52.197  7631  7631 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 14:57:52.198  7631  7631 D LGBluetoothHfpAdapter: Version 1.6
08-30 14:57:52.201  7631  7631 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 14:57:52.202  7631  7631 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 14:57:52.203  7631  7631 D HeadsetStateMachine: make
08-30 14:57:52.209  7631  7837 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 14:57:52.211  6747  6747 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 14:57:52.216  7631  7837 E BluetoothAdapterService: File transfer profiles supported!!
08-30 14:57:52.226  7631  7837 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 14:57:52.230  7631  7837 E BluetoothAdapterService: File transfer profiles supported!!
08-30 14:57:52.235  7631  7837 E BluetoothAdapterService: File transfer profiles supported!!
08-30 14:57:52.238  7631  7631 D LgDataFeature: LgDataFeature() Constructor: none
08-30 14:57:52.238  7631  7631 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 14:57:52.243  7631  7631 D HeadsetStateMachine: max_hf_connections = 1
08-30 14:57:52.243  7631  7631 I bluedroid-qcom: get_profile_interface handsfree
08-30 14:57:52.245  7631  7631 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-30 14:57:52.245   311  1368 V AudioPolicyService: registerClient() client 0xb558a620, uid 1002
08-30 14:57:52.246   311   311 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 14:57:52.246   311   311 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 14:57:52.246   311   311 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 14:57:52.246  7631  7631 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 14:57:52.246   311  2117 V AudioFlinger: registerClient() client 0xb1433190, pid 7631
08-30 14:57:52.246   311  1362 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 14:57:52.246   311  1362 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 14:57:52.247  7631  7631 V ToneGenerator: Create Track: 0xb4928080
08-30 14:57:52.247  7631  7631 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 14:57:52.247  7631  7631 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 14:57:52.247   311   311 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 14:57:52.247  1587  2518 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 14:57:52.247   311   311 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 14:57:52.247   311   311 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 14:57:52.247  1587  2518 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 14:57:52.247   311   311 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 14:57:52.247  7631  7631 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 14:57:52.247  1835  1851 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 14:57:52.247  1835  1851 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 14:57:52.247  3482  3498 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 14:57:52.247  3482  3498 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 14:57:52.247   311  1364 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 14:57:52.247   311  1364 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 14:57:52.247  7631  7647 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 14:57:52.247  7631  7647 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 14:57:52.247  1835  1850 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 14:57:52.247  1835  1850 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 14:57:52.247  7631  7647 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 14:57:52.247  3482  3497 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 14:57:52.247  3482  3497 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 14:57:52.247  7631  7647 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 14:57:52.248  1587  2518 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 14:57:52.248  1587  2518 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 14:57:52.248  1035  1050 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 14:57:52.248  1035  1050 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 14:57:52.248  1035  1050 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 14:57:52.248  1035  1050 V AudioSystem: ioConfigChanged() ope,ning already existing output! 4
08-30 14:57:52.248   311   311 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 14:57:52.248   311  1369 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 14:57:52.248   311  1369 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-30 14:57:52.248   311  1369 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 14:57:52.248   311  1369 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 14:57:52.248  7631  7631 V AudioSystem: getLatency() output 2, latency 50
08-30 14:57:52.249  7631  7631 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 14:57:52.249  7631  7631 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 14:57:52.249   311  2116 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 14:57:52.249   311  2116 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 14:57:52.249   311  2116 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 14:57:52.249   311  2116 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 14:57:52.249   311  2116 V AudioFlinger: createTrack() lSessionId: 23
08-30 14:57:52.250  7631  7631 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 14:57:52.250   311  2116 V AudioFlinger: acquiring 23 from 7631, for 7631
08-30 14:57:52.250   311  2116 V AudioFlinger:  added new entry for 23
08-30 14:57:52.250  7631  7631 V ToneGenerator: ToneGenerator INIT OK, time: 195138
08-30 14:57:52.250  7631  7631 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ae84e4
08-30 14:57:52.251  7631  7859 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 14:57:52.251  7631  7859 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 14:57:52.251  7631  7859 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 14:57:52.251  7631  7859 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 14:57:52.251   311  2117 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7631
08-30 14:57:52.252   311  2117 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 14:57:52.252   311  2117 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 14:57:52.252   311  2117 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 14:57:52.252   311  2117 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 14:57:52.252   311  2117 V voice   : voice_set_parameters: exit with code(0)
08-30 14:57:52.252   311  2117 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 14:57:52.252   311  2117 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 14:57:52.252   311  2117 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 14:57:52.252   311  2117 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 14:57:52.252   311  2117 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 14:57:52.252   311  2117 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 14:57:52.253  7631  7631 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ae84e4
08-30 14:57:52.255  7631  7837 V LGMDMManager: Create singleton instance
,08-30 14:57:52.256  7631  7631 D A2dpService: Received start request. Starting profile...
,08-30 14:57:52.257  7631  7631 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 14:57:52.257  7631  7859 V ToneGenerator: ToneGenerator destructor
08-30 14:57:52.257  7631  7859 V ToneGenerator: stopTone
08-30 14:57:52.257  7631  7859 V ToneGenerator: Delete Track: 0xb4928080
08-30 14:57:52.258  1035  1888 W Process : Unable to open /proc/7861/status
08-30 14:57:52.258  7631  7631 V Avrcp   : make
08-30 14:57:52.259  7631  7631 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 14:57:52.259  7631  7631 I bluedroid-qcom: get_profile_interface avrcp
08-30 14:57:52.261  7631  7837 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 14:57:52.262   311   311 V AudioPolicyService: AudioCommandThread() adding release output 2
08-30 14:57:52.262   311   311 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 14:57:52.262   311  1272 V AudioPolicyService: AudioCommandThread() waking up
08-30 14:57:52.262  7631  7859 V AudioTrack: ~AudioTrack, releasing session id from 7631 on behalf of 7631
08-30 14:57:52.262   311  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 14:57:52.262   311  1272 V AudioPolicyManager: releaseOutput() 2
08-30 14:57:52.262   311  1272 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 14:57:52.262   311  2116 V AudioFlinger: releasing 23 from 7631 for 7631
08-30 14:57:52.262   311  2116 V AudioFlinger:  decremented refcount to 0
08-30 14:57:52.262   311   311 V AudioFlinger: PlaybackThread::Track destructor
08-30 14:57:52.262   311  2116 V AudioFlinger: purging stale effects
08-30 14:57:52.262   311   311 V AudioFlinger: removeClient_l() pid 7631, calling pid 311
08-30 14:57:52.269  7631  7631 V AudioManager: registerRemoteController: size of Media player list: 0
,08-30 14:57:52.271  7631  7631 E AudioManager: No RCC entry present to update
,08-30 14:57:52.271  7631  7631 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 14:57:52.275  7631  7631 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-30 14:57:52.277  7631  7631 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 14:57:52.277  7631  7631 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-30 14:57:52.281  7631  7631 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 14:57:52.420  1035  1050 V SIM_STK : Menu title from STK is T-Mobile
,08-30 14:57:52.420  1035  1050 V SIM_STK : Menu title from STK is T-Mobile
,08-30 14:57:52.490  1035  1888 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-30 14:57:52.497  7631  7631 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 14:57:52.501  7631  7631 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 14:57:52.501  7631  7631 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 14:57:52.501  7631  7631 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 14:57:52.501  7631  7631 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 14:57:52.502  7631  7631 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 14:57:52.502  7631  7631 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 14:57:52.502  7631  7631 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 14:57:52.502  7631  7631 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 14:57:52.502  7631  7631 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 14:57:52.502  7631  7631 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 14:57:52.502  7631  7631 I BluetoothA2dpServiceJni: classInitNative
08-30 14:57:52.502  7631  7631 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 14:57:52.502  7631  7631 D A2dpStateMachine: make
08-30 14:57:52.506  7631  7631 I bluedroid-qcom: get_profile_interface a2dp
,08-30 14:57:52.508  7631  7869 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 14:57:52.514  7631  7631 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 14:57:52.515  7631  7631 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-30 14:57:52.517  7631  7631 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ae84e4
08-30 14:57:52.518  7631  7865 D A2dpStateMachine: Enter Disconnected: -2
08-30 14:57:52.520  7631  7631 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 14:57:52.524  7631  7631 D HidService: Received start request. Starting profile...
,08-30 14:57:52.524  7631  7631 I bluedroid-qcom: get_profile_interface hidhost
08-30 14:57:52.524  7631  7631 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ae84e4
08-30 14:57:52.525  7631  7631 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 14:57:52.527  7631  7631 D HealthService: Received start request. Starting profile...
08-30 14:57:52.528  7631  7631 I bluedroid-qcom: get_profile_interface health
08-30 14:57:52.528  7631  7631 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 14:57:52.528  7631  7631 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ae84e4
08-30 14:57:52.529  7631  7631 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 14:57:52.530  7631  7631 D PanService: Received start request. Starting profile...
08-30 14:57:52.530  7631  7631 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 14:57:52.531  7631  7631 I bluedroid-qcom: get_profile_interface pan
08-30 14:57:52.538  7631  7631 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-30 14:57:52.538  7631  7631 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ae84e4
,08-30 14:57:52.539  7631  7631 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-30 14:57:52.543  7631  7631 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 14:57:52.543  7631  7631 D BtGatt.GattService: Received start request. Starting profile...
08-30 14:57:52.543  7631  7631 D BtGatt.GattService: start()
08-30 14:57:52.543  7631  7631 I bluedroid-qcom: get_profile_interface gatt
08-30 14:57:52.544  7631  7631 D BtGatt.AdvertiseManager: advertise manager created
08-30 14:57:52.552  7631  7631 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ae84e4
,08-30 14:57:52.555  7631  7631 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ae84e4
08-30 14:57:52.555  7631  7631 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-30 14:57:52.556  7631  7631 V BluetoothMapService: BluetoothMapBinder()
08-30 14:57:52.557  7631  7631 D BluetoothMapService: Received start request. Starting profile...
08-30 14:57:52.557  7631  7631 D BluetoothMapService: start()
08-30 14:57:52.560  7631  7631 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-30 14:57:52.560  7631  7631 D BluetoothMapEmailAppObserver: createReceiver()
08-30 14:57:52.561  7631  7631 D BluetoothMapEmailAppObserver: initObservers()
08-30 14:57:52.561  7631  7631 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 14:57:52.570  7631  7631 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ae84e4
08-30 14:57:52.571  7631  7631 D HeadsetStateMachine: Proxy object connected
08-30 14:57:52.571  7631  7631 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 14:57:52.571  7631  7631 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-30 14:57:52.577  7631  7631 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 14:57:52.578  7631  7859 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 14:57:52.578  7631  7859 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 14:57:52.579  7631  7859 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-30 14:57:52.583  7631  7631 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 14:57:52.587  7631  7631 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 14:57:52.589  7631  7631 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:52.598  7631  7631 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 14:57:52.599  7631  7631 V PanService: [BTUI] SIM Extra State :ABSENT
,08-30 14:57:52.603  7631  7631 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 14:57:52.607  7631  7631 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-30 14:57:52.607  7631  7631 V BluetoothMapService: Handler(): got msg=1
08-30 14:57:52.609  7631  7631 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 14:57:52.609  7631  7631 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 14:57:52.609  7631  7631 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 14:57:52.609  7631  7631 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:52.609  7631  7837 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 14:57:52.609  7631  7631 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-30 14:57:52.609  7631  7837 I bluedroid-qcom: enable
08-30 14:57:52.610  7631  7876 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 14:57:52.610  7631  7876 I bt-btu  : btu_task pending for preload complete event
08-30 14:57:52.610  7631  7837 I bt_hci_bdroid: init
08-30 14:57:52.613  7631  7837 I bt_vendor: bt-vendor : init
08-30 14:57:52.613  7631  7837 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 14:57:52.613  7631  7837 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 14:57:52.613  7631  7837 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 14:57:52.613  7631  7837 D bt_userial_mct: userial_init
08-30 14:57:52.614  7631  7837 D bt_hci_bdroid: set_power 1
08-30 14:57:52.614  7631  7837 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 14:57:52.614  7631  7837 I bt_vendor: Starting hciattach daemon
08-30 14:57:52.614  7631  7837 I bt_vendor: try to set true
,08-30 14:57:52.604  7879  7879 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:57:52.604  7879  7879 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:57:52.652  7880  7880 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 14:57:52.795  7886  7886 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 14:57:52.810  7887  7887 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 14:57:52.847  7889  7889 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 14:57:52.863  7890  7890 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-30 14:57:52.888  7891  7891 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 14:57:52.912  7892  7892 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-30 14:57:52.940  7897  7897 I libmdmdetect: ESOC framework not supported
08-30 14:57:52.942  7897  7897 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-30 14:57:52.952  7897  7897 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-30 14:57:52.952  7897  7897 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-30 14:57:52.952  7897  7897 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-30 14:57:52.952  7897  7897 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-30 14:57:52.952  7897  7897 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-30 14:57:52.952  7897  7897 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-30 14:57:52.952  7897  7897 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-30 14:57:52.988  7897  7898 E QC-QMI  : qmi_client [7897] 15: failed to locate client data
08-30 14:57:52.988   478   478 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-30 14:57:52.988   478   478 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-30 14:57:53.044  7902  7902 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 14:57:53.059  7903  7903 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 14:57:53.124  7631  7837 I bt_vendor: bluetooth satus is on
08-30 14:57:53.124  7631  7837 D bt_hci_bdroid: preload
,08-30 14:57:53.129  7631  7878 D bt_userial_mct: userial_open(port:0)
08-30 14:57:53.129  7631  7878 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-30 14:57:53.134  7631  7878 I bt_vendor: Done intiailizing UART
08-30 14:57:53.137  7631  7878 I bt_vendor: Done intiailizing UART
08-30 14:57:53.137  7631  7878 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 14:57:53.137  7631  7878 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-30 14:57:53.138  7631  7876 I bt-btu  : btu_task received preload complete event
08-30 14:57:53.139  7631  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-30 14:57:53.139  7631  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-30 14:57:53.149  7631  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-30 14:57:53.153  7631  7905 D bt_userial_mct: Entering userial_read_thread()
08-30 14:57:53.160  7631  7876 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 14:57:53.160  7631  7876 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 14:57:53.160  7631  7876 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 14:57:53.160  7631  7876 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 14:57:53.160  7631  7876 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 14:57:53.160  7631  7876 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 14:57:53.160  7631  7876 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 14:57:53.160  7631  7876 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 14:57:53.160  7631  7876 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-30 14:57:53.160  7631  7876 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 14:57:53.160  7631  7876 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 14:57:53.160  7631  7876 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 14:57:53.160  7631  7876 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 14:57:53.160  7631  7876 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 14:57:53.160  7631  7876 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 14:57:53.160  7631  7876 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 14:57:53.228  7631  7876 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-30 14:57:53.228  7631  7876 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0209061 
08-30 14:57:53.228  7631  7876 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0209061 
,08-30 14:57:53.256  7631  7841 E bt-btif : Calling BTA_HhEnable
08-30 14:57:53.256  7631  7841 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-30 14:57:53.256  7631  7841 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-30 14:57:53.261  7631  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-30 14:57:53.261  7631  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-30 14:57:53.261  7631  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 14:57:53.262  7631  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 14:57:53.262  7631  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-30 14:57:53.263  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 14:57:53.264  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 14:57:53.264  7631  7841 D BluetoothAdapterProperties: Name is: G3
08-30 14:57:53.266  7631  7841 D BluetoothAdapterProperties: Scan Mode:20
08-30 14:57:53.266  7631  7841 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 14:57:53.267  7631  7841 D bt_hci_bdroid: postload
08-30 14:57:53.267  7631  7878 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 14:57:53.268  7631  7876 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 14:57:53.269  7631  7841 D bte_conf: Device ID record 1 : primary
08-30 14:57:53.269  7631  7841 D bte_conf:   vendorId            = 00c4
08-30 14:57:53.269  7631  7841 D bte_conf:   vendorIdSource      = 0001
08-30 14:57:53.269  7631  7841 D bte_conf:   product             = 13a1
08-30 14:57:53.269  7631  7841 D bte_conf:   version             = 1000
08-30 14:57:53.269  7631  7841 D bte_conf:   clientExecutableURL = 
08-30 14:57:53.269  7631  7841 D bte_conf:   serviceDescription  = 
08-30 14:57:53.269  7631  7841 D bte_conf:   documentationURL    = 
08-30 14:57:53.269  7631  7841 D bte_conf: bte_load_did_conf no section named DID2.
08-30 14:57:53.273  7631  7878 D bt_hci_bdroid: Used up Tx Cmd credits
,08-30 14:57:53.277  7631  7878 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 14:57:53.279  7631  7878 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 14:57:53.282  7631  7905 E bt_mct  : hci lib postload completed
08-30 14:57:53.283  7631  7837 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 14:57:53.283  7631  7837 D BluetoothAdapterProperties: ScanMode =  20
08-30 14:57:53.283  7631  7837 D BluetoothAdapterProperties: State =  11
08-30 14:57:53.283  7631  7837 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 14:57:53.284  7631  7837 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-30 14:57:53.284  7631  7837 D BluetoothAdapterProperties: Setting state to 12
08-30 14:57:53.284  7631  7837 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 14:57:53.274  7907  7907 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 14:57:53.293  7631  7876 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 14:57:53.293  7631  7876 W bt-smp  : Plain text(LSB ~ MSB) = 13 3f 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 14:57:53.293  7631  7876 W bt-smp  : Encrypted text(LSB ~ MSB) = a6 52 20 29 14 a1 d1 94 a7 a0 7b 8e 6f b9 e1 bd 
08-30 14:57:53.293  7631  7876 W bt-btm  : Stopping oneshot timer
08-30 14:57:53.294  7631  7841 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 14:57:53.294  7631  7841 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 14:57:53.284  7907  7907 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:57:53.314  1035  1117 D BluetoothManagerService: Message: 60
08-30 14:57:53.314  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 14:57:53.314  1035  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-30 14:57:53.314  1035  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 14:57:53.321  7631  7837 I BluetoothAdapterState: Entering On State
08-30 14:57:53.335  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:57:53.335  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:53.335  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:53.335  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:57:53.335  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:57:53.335  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:57:53.335  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:57:53.335  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 14:57:53.338  7631  7841 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 14:57:53.339  7631  7841 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-30 14:57:53.343  7631  7876 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 14:57:53.343  7631  7876 W bt-smp  : Plain text(LSB ~ MSB) = c6 34 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 14:57:53.343  7631  7876 W bt-smp  : Encrypted text(LSB ~ MSB) = b6 29 57 08 d4 c3 b4 6c ea 4f f1 fb 34 c3 08 2b 
08-30 14:57:53.344  7631  7876 W bt-btm  : Stopping oneshot timer
08-30 14:57:53.344  6646  6646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:57:53.359  1035  1035 D BluetoothHeadset: Proxy object connected
,08-30 14:57:53.365  7631  7876 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 14:57:53.365  7631  7876 W bt-smp  : Plain text(LSB ~ MSB) = 76 e4 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 14:57:53.365  7631  7876 W bt-smp  : Encrypted text(LSB ~ MSB) = 08 87 7b b8 ed 7a 9d a2 e0 bc 23 93 62 36 77 31 
08-30 14:57:53.365  7631  7876 W bt-btm  : Stopping oneshot timer
08-30 14:57:53.369  7631  7837 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 14:57:53.369  7631  7837 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 14:57:53.369  7631  7837 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-30 14:57:53.371  7631  7837 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-30 14:57:53.371  7631  7837 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-30 14:57:53.392  7631  7876 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 14:57:53.392  7631  7876 W bt-smp  : Plain text(LSB ~ MSB) = 13 ec 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 14:57:53.392  7631  7876 W bt-smp  : Encrypted text(LSB ~ MSB) = 74 08 d7 8f 6d 15 2b 93 85 53 6b 51 61 0a 07 0b 
08-30 14:57:53.392  7631  7876 W bt-btm  : Stopping oneshot timer
,08-30 14:57:53.401  6747  6765 D BluetoothMap: onBluetoothStateChange: up=true
08-30 14:57:53.405  7912  7912 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-30 14:57:53.414  1835  4017 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:57:53.416  1835  1835 D BluetoothHeadset: Proxy object connected
08-30 14:57:53.416  6747  6765 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 14:57:53.418  6747  7498 D BluetoothPan: onBluetoothStateChange on: true
08-30 14:57:53.418  6747  7498 D BluetoothPan: onBluetoothStateChange call bindService
08-30 14:57:53.419  7631  7876 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 14:57:53.419  7631  7876 W bt-smp  : Plain text(LSB ~ MSB) = f2 05 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 14:57:53.419  7631  7876 W bt-smp  : Encrypted text(LSB ~ MSB) = e9 22 cb c1 8a 67 48 d6 14 7f ba aa 72 39 e4 92 
08-30 14:57:53.419  7631  7876 W bt-btm  : Stopping oneshot timer
,08-30 14:57:53.428  6747  6747 D BluetoothMap: Proxy object connected
08-30 14:57:53.429  6747  6747 D MapProfile: Bluetooth service connected
08-30 14:57:53.429  6747  6747 D BluetoothMap: getConnectedDevices()
,08-30 14:57:53.431  6747  6765 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 14:57:53.434  7631  7646 V BluetoothMapService: getConnectedDevices()
08-30 14:57:53.437  1835  2412 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:57:53.443  1835  1835 D BluetoothHeadset: Proxy object connected
08-30 14:57:53.443  6747  6747 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 14:57:53.443  6747  6747 D PanProfile: Bluetooth service connected
08-30 14:57:53.443  6747  6767 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 14:57:53.446  6747  6747 D BluetoothInputDevice: Proxy object connected
08-30 14:57:53.446  6747  6747 D HidProfile: Bluetooth service connected
08-30 14:57:53.446  1035  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 14:57:53.448  6747  6765 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 14:57:53.448  1035  1035 D BluetoothA2dp: Proxy object connected
08-30 14:57:53.450  6747  6747 D BluetoothHeadset: Proxy object connected
08-30 14:57:53.450  6747  6747 D HeadsetProfile: Bluetooth service connected
08-30 14:57:53.453  6747  6747 D BluetoothA2dp: Proxy object connected
08-30 14:57:53.453  6747  6747 D A2dpProfile: Bluetooth service connected
08-30 14:57:53.453  1835  1850 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 14:57:53.456  1835  1835 D BluetoothHeadset: Proxy object connected
,08-30 14:57:53.457  1035  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-30 14:57:53.457  1035  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-30 14:57:53.459  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:53.459  1925  2129 D LGBluetoothAPIService: Message: 1
08-30 14:57:53.459  1925  2129 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-30 14:57:53.460  1925  2129 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-30 14:57:53.460  1925  2129 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-30 14:57:53.461  1587  1587 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 14:57:53.463  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:53.465  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-30 14:57:53.467  1035  1117 D BluetoothManagerService: Message: 40
08-30 14:57:53.467  1035  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 14:57:53.468  6747  6747 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-30 14:57:53.469  7631  7631 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:53.469  7631  7631 D BluetoothMapService: STATE_ON
08-30 14:57:53.470  6747  6747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 14:57:53.480  6747  6747 D DockEventReceiver: finishStartingService: stopping service
08-30 14:57:53.488  7631  7631 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ae84e4
08-30 14:57:53.488  7631  7631 V BluetoothPbapService: Pbap Service onCreate
08-30 14:57:53.488  7631  7631 V BluetoothPbapService: Starting PBAP service
08-30 14:57:53.489  7631  7631 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 14:57:53.490  7631  7631 V BluetoothMapService: Handler(): got msg=1
08-30 14:57:53.490  7631  7631 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 14:57:53.490  7631  7631 V BluetoothPbapService: Pbap Service onBind
08-30 14:57:53.491  7631  7932 D BluetoothMapMasInstance: MAS initSocket()
08-30 14:57:53.492  7631  7932 D BluetoothMapMasInstance:   masId = 00
08-30 14:57:53.492  7631  7932 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 14:57:53.492  7631  7932 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 14:57:53.492  7631  7932 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 14:57:53.493  7631  7631 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:53.493  7631  7631 V BluetoothPbapService: state: 12
08-30 14:57:53.493  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 14:57:53.494  7631  7631 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 14:57:53.494  7631  7631 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:53.494  7631  7631 V BluetoothPbapReceiver: ***********state = 12
08-30 14:57:53.495  7631  7631 V BluetoothPbapService: Handler(): got msg=1
08-30 14:57:53.497  6747  6747 D BluetoothPbap: Proxy object connected
08-30 14:57:53.497  6747  6747 D PbapServerProfile: Bluetooth service connected
08-30 14:57:53.497  7631  7932 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 14:57:53.497  7631  7631 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-30 14:57:53.499  7631  7933 V BluetoothPbapService: Pbap Service initSocket
08-30 14:57:53.499  2169  2169 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 14:57:53.500  2169  2169 D c       : Getting all permits...
08-30 14:57:53.500  2169  2169 D a       : Opening database...
08-30 14:57:53.500  1035  1979 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:53.501  7631  7932 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-30 14:57:53.502  7631  7932 V BluetoothMapMasInstance: Succeed to create listening socket 
08-30 14:57:53.502  7631  7932 D BluetoothMapMasInstance: Accepting socket connection...
08-30 14:57:53.502  7631  7841 D BluetoothAdapterProperties: Scan Mode:21
08-30 14:57:53.502  7631  7841 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-30 14:57:53.503  7631  7933 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 14:57:53.504  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:53.505  2169  2169 D a       : Opening database auth.proximity.permit_store...
08-30 14:57:53.506  2169  2169 D a       : Closing database...
,08-30 14:57:53.510  7631  7933 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-30 14:57:53.510  7631  7933 V BluetoothPbapService: Succeed to create listening socket 
08-30 14:57:53.510  7631  7933 V BluetoothPbapService: Accepting socket connection...
08-30 14:57:53.516  6747  6747 D BluetoothPermissionRequest: onReceive
08-30 14:57:53.518  6747  6747 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-30 14:57:53.520  6747  6747 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 14:57:53.524  7631  7631 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-30 14:57:53.525  7631  7631 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 14:57:53.530  7631  7631 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-30 14:57:53.550  7631  7631 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 14:57:53.550  7631  7631 V BtOppService: onCreate
,08-30 14:57:53.558  7631  7631 V BluetoothOppNotification: send message
08-30 14:57:53.577  7631  7936 V BtOppService: Deleted complete outbound shares, number =  0
,08-30 14:57:53.581  7631  7936 V BtOppService: Deleted complete inbound failed shares, number = 0
,08-30 14:57:53.581  7631  7936 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-30 14:57:53.675  1035  1888 I art     : Explicit concurrent mark sweep GC freed 27934(1369KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.341ms total 114.612ms
08-30 14:57:53.676  7631  7936 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31c41ce3 on behalf of 
08-30 14:57:53.678  7631  7631 V BtOppService: Starting RfcommListener
,08-30 14:57:53.688  7631  7631 D BluetoothOppPreference: Dumping Names:  
08-30 14:57:53.688  7631  7631 D BluetoothOppPreference: {}
08-30 14:57:53.688  7631  7631 D BluetoothOppPreference: Dumping Channels:  
08-30 14:57:53.688  7631  7631 D BluetoothOppPreference: {}
08-30 14:57:53.689  7631  7631 V BtOppService: onStartCommand
08-30 14:57:53.689  7631  7940 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 14:57:53.690  7631  7940 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-30 14:57:53.695  7631  7940 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4527d99 on behalf of 
08-30 14:57:53.696  7631  7940 V BluetoothOppNotification: update too frequent, put in queue
08-30 14:57:53.696  7631  7940 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 14:57:53.696  7631  7940 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 14:57:53.696  7631  7631 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:53.697  7631  7940 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@36ba485e on behalf of 
08-30 14:57:53.697  7631  7631 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 14:57:53.697  7631  7940 V BluetoothOppNotification: update too frequent, put in queue
08-30 14:57:53.700  7631  7940 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 14:57:53.700  7631  7631 V BluetoothOppNotification: new notify threadi!
08-30 14:57:53.701  7631  7631 V BluetoothOppNotification: send delay message
08-30 14:57:53.702  7631  7631 V BtOppService: ContentObserver received notification
08-30 14:57:53.704  7631  7631 V BtOppService: ContentObserver received notification
,08-30 14:57:53.704  7631  7631 V BtOppService: start RfcommListener
08-30 14:57:53.704  7631  7941 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 14:57:53.707  7631  7941 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2611a43f on behalf of 
08-30 14:57:53.707  7631  7631 V BtOppService: RfcommListener started
08-30 14:57:53.711  7631  7941 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 14:57:53.713  7631  7941 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 14:57:53.716  7631  7942 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 14:57:53.716  7631  7942 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 14:57:53.716  7631  7943 V BtOppRfcommListener: Starting RFCOMM listener....
,08-30 14:57:53.717  1035  1969 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:53.721  7631  7943 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 14:57:53.723  7631  7941 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d48510c on behalf of 
08-30 14:57:53.724  7631  7943 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-30 14:57:53.724  7631  7943 V BtOppRfcommListener: Started RFCOMM listener....
08-30 14:57:53.724  7631  7943 I BtOppRfcommListener: Accept thread started.
08-30 14:57:53.724  7631  7943 V BtOppRfcommListener: Accepting connection...
08-30 14:57:53.724  7631  7941 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-30 14:57:53.724  7631  7942 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3bc45a55 on behalf of 
08-30 14:57:53.725  7631  7942 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 14:57:53.726  7631  7941 V BluetoothOppNotification: outbound notification was removed.
08-30 14:57:53.726  7631  7941 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 14:57:53.726  7631  7941 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38de8c6a on behalf of 
08-30 14:57:53.727  7631  7941 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 14:57:53.728  7631  7941 V BluetoothOppNotification: inbound notification was removed.
08-30 14:57:53.728  7631  7941 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 14:57:53.729  7631  7941 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@986455b on behalf of 
,08-30 14:57:53.739  7631  7631 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ae84e4
08-30 14:57:53.739  7631  7631 V BluetoothFtpService: Ftp Service onCreate
08-30 14:57:53.739  7631  7631 I BluetoothFtpService: Ftp Service onCreate
08-30 14:57:53.739  7631  7631 V BluetoothFtpService: Ftp Service onStartCommand
08-30 14:57:53.739  7631  7631 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:53.739  7631  7631 V BluetoothFtpService: Starting Listening on sockets
08-30 14:57:53.740  7631  7631 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-30 14:57:53.740  7631  7631 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 14:57:53.740  7631  7631 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 14:57:53.740  7631  7631 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 14:57:53.741  7631  7631 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 14:57:53.741  7631  7631 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 14:57:53.743  7631  7631 V BluetoothFtpService: Handler(): got msg=1
08-30 14:57:53.743  7631  7631 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 14:57:53.743  7631  7631 V BluetoothFtpService: Ftp Service initSocket
08-30 14:57:53.745  1035  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:53.746  7631  7631 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 14:57:53.747  7631  7631 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-30 14:57:53.747  7631  7631 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-30 14:57:53.749  7631  7944 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-30 14:57:53.756  7631  7631 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37ae84e4
08-30 14:57:53.756  7631  7631 V BluetoothSapService: Sap Service onCreate
,08-30 14:57:53.757  7631  7631 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 14:57:53.757  7631  7631 V BluetoothSapService: state: 12
08-30 14:57:53.757  7631  7631 V BluetoothSapService: Starting SAP server process
08-30 14:57:53.759  7631  7631 V BluetoothSapService: SAP Service startRfcommListenerThread
08-30 14:57:53.744  7945  7945 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:57:53.760  7631  7946 V BluetoothSapService: Sap Service initRfcommSocket
08-30 14:57:53.744  7945  7945 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 14:57:53.760  1035  2034 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:53.761  7631  7946 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 14:57:53.762  7631  7946 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-30 14:57:53.762  7631  7946 V BluetoothSapService: Succeed to create listening socket 
08-30 14:57:53.762  7631  7946 V BluetoothSapService: Accepting socket connection...
08-30 14:57:53.780  7945  7945 V BT_SAP  : Event pipe created
08-30 14:57:53.780  7945  7945 V BT_SAP  : create_server_socket qcom.sap.server
08-30 14:57:53.780  7945  7945 V BT_SAP  : created socket fd 6
,08-30 14:57:54.086  6646  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:57:54.086  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:54.086  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:54.086  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 14:57:54.086  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:57:54.086  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:57:54.086  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:57:54.086  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 14:57:54.092  6646  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 14:57:54.096  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:57:54.096  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@286f7ff1 added. We now have 8 listener(s)
08-30 14:57:54.096  6646  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:57:54.104  1035  2034 D WifiServiceImplEx: setWifiEnabled: false pid=6646, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 14:57:54.104  1035  2034 D WifiService: setWifiEnabled: false pid=6646, uid=10118
08-30 14:57:54.104  1035  2034 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 14:57:54.110  6646  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:57:54.113  1035  1969 D WifiServiceImplEx: setWifiEnabled: true pid=6646, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 14:57:54.114  1035  1969 D WifiService: setWifiEnabled: true pid=6646, uid=10118
08-30 14:57:54.114  1035  1969 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 14:57:54.129  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 14:57:54.130  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 14:57:54.130  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-30 14:57:54.131  1035  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-30 14:57:54.131  1035  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-30 14:57:54.134  1035  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-30 14:57:54.134  1035  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 14:57:54.134  1035  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-30 14:57:54.134  1035  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 14:57:54.134  1035  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 14:57:54.134  1035  1523 E WifiHW  : unknown target_country: EU , set to default
08-30 14:57:54.134  1035  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-30 14:57:54.134  1035  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 14:57:54.134  1035  1523 I WifiUtil: gEnableBmps=1
08-30 14:57:54.704  7631  7631 V BluetoothOppNotification: new notify threadi!
08-30 14:57:54.704  7631  7631 V BluetoothOppNotification: send delay message
,08-30 14:57:54.722   305   893 D SoftapController: Softap fwReload - Ok
,08-30 14:57:54.728  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 14:57:54.743  1035  1523 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (604ms)
08-30 14:57:54.753  1035  1117 D Tethering: InitialState.processMessage what=4
08-30 14:57:54.754  1035  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 14:57:54.760   305   893 D CommandListener: Setting iface cfg
08-30 14:57:54.760   305   893 D CommandListener: Trying to bring down wlan0
08-30 14:57:54.763   305   893 D CommandListener: Clearing all IP addresses on wlan0
08-30 14:57:54.765  1035  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-30 14:57:54.764  7967  7967 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:57:54.784  1035  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 14:57:54.784  1035  1523 E WifiStateMachine: useWiFiOffloading() : false
08-30 14:57:54.784  1035  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 14:57:54.784  7967  7967 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 14:57:54.804  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:54.808  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-30 14:57:54.823  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 14:57:54.835  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-30 14:57:54.839  1035  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 14:57:54.840  1035  1523 D WifiMonitor: connecting to supplicant
08-30 14:57:54.840  7631  7965 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 14:57:54.844  7631  7965 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d65b5a4 on behalf of 
08-30 14:57:54.845  6747  6747 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 14:57:54.845  6747  6747 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 14:57:54.845  6747  6747 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 14:57:54.846  6747  6747 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 14:57:54.846  7631  7965 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 14:57:54.848  6747  6747 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 14:57:54.850  6747  6747 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 14:57:54.850  6747  6747 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 14:57:54.851  6747  6747 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 14:57:54.851  6747  6747 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 14:57:54.851  6747  6747 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 14:57:54.851  6747  6747 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-30 14:57:54.853  7967  7967 I wpa_supplicant: Successfully initialized wpa_supplicant
08-30 14:57:54.857  6747  6747 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 14:57:54.857  6747  6747 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 14:57:54.857  6747  6747 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 14:57:54.857  6747  6747 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 14:57:54.858  7631  7965 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 14:57:54.861  6747  6747 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 14:57:54.863  7631  7965 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27e7f0d on behalf of 
08-30 14:57:54.865  7631  7965 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 14:57:54.867  6747  6747 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 14:57:54.868  6747  6747 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 14:57:54.868  6747  6747 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 14:57:54.868  6747  6747 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 14:57:54.868  6747  6747 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 14:57:54.868  6747  6747 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-30 14:57:54.875  7631  7965 V BluetoothOppNotification: outbound notification was removed.
08-30 14:57:54.875  7631  7965 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 14:57:54.877  7631  7965 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ba03ec2 on behalf of 
08-30 14:57:54.878  7631  7965 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 14:57:54.880  7631  7965 V BluetoothOppNotification: inbound notification was removed.
08-30 14:57:54.880  7631  7965 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 14:57:54.881  7631  7965 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@326604d3 on behalf of 
08-30 14:57:54.883  7967  7967 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 14:57:54.883  7967  7967 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-30 14:57:54.928  1035  1998 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7985 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-30 14:57:54.962  7967  7967 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 14:57:55.025  7967  7967 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-30 14:57:55.029  7967  7967 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-30 14:57:55.032  1035  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-30 14:57:55.033  1035  8006 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 14:57:55.033  1035  8006 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-30 14:57:55.033  1035  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 14:57:55.033  1035  8006 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 14:57:55.033  1035  8006 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-30 14:57:55.034  1035  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-30 14:57:55.034  1035  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-30 14:57:55.035  1035  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:57:55.035  1035  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:57:55.036  1035  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:57:55.037  1035  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:57:55.037  1035  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 14:57:55.037  1035  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-30 14:57:55.038  1035  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 14:57:55.039  1035  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-30 14:57:55.039  1035  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-30 14:57:55.046  1035  1051 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8007 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 14:57:55.052  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:55.052  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:55.052  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:55.053  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:55.053  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 14:57:55.053  1035  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 14:57:55.053  1035  1523 E WifiStateMachine: useWiFiOffloading() : false
08-30 14:57:55.053  1035  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 14:57:55.054  1035  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
08-30 14:57:55.055  1035  1523 D WifiNative-wlan0: SET update_config 1: returned true
08-30 14:57:55.055  1035  1523 D WifiConfigStore: Loading config and enabling all networks 
08-30 14:57:55.055  1035  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 14:57:55.055  1035  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-30 14:57:55.056  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:55.057  1925  1925 D WfdService: Waiting for WifiP2p enabling
08-30 14:57:55.058  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-30 14:57:55.058  1035  1527 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-30 14:57:55.061  7985  8004 W FormManager: Network not available. Please check & try again.
08-30 14:57:55.063  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:57:55.063  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:55.063  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:55.063  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:57:55.063  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:57:55.063  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:57:55.063  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:57:55.063  6646  6646 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 14:57:55.064  1035  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-30 14:57:55.067  6646  6646 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:57:55.075  1035  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-30 14:57:55.075  1035  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 14:57:55.076  1035  1523 D WifiStateMachine: enableVerboseLogging : level 2
08-30 14:57:55.076  1035  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 14:57:55.078  7985  8005 V FormManager: Network unavailable.
08-30 14:57:55.080  1035  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
,08-30 14:57:55.080  1035  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-30 14:57:55.080  1035  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 14:57:55.080  1035  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 14:57:55.080  1035  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 14:57:55.080  1035  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 14:57:55.081  1035  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-30 14:57:55.081  1035  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-30 14:57:55.081  1035  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 14:57:55.081  1035  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 14:57:55.082  1035  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 14:57:55.082  7985  8005 V FormManager: Network unavailable.
08-30 14:57:55.082  1035  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 14:57:55.082  1035  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-30 14:57:55.083  1035  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 14:57:55.083  1035  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-30 14:57:55.083  1925  1925 D WfdsService: Supplicant Connection state is changed : true
08-30 14:57:55.083  1035  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 14:57:55.084  1035  1523 D WifiNative-HAL: Setting external_sim to 1
08-30 14:57:55.084  1035  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-30 14:57:55.084  1925  2320 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-30 14:57:55.084  1925  2320 D WfdsService: Set the WFDS Monitor: true
08-30 14:57:55.084  1925  2320 D WfdsMonitor: WfdsMonitorThread create
08-30 14:57:55.084  1925  2320 D WfdsMonitor: WFDS Monitor is created and started
08-30 14:57:55.084  1925  2320 D WfdsService: WiFi: Supplicant connection re-established
08-30 14:57:55.084  7658  7658 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:55.084  1035  1523 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 14:57:55.084  1035  1523 I WifiNative-HAL: startHal
08-30 14:57:55.084  1035  1523 D wifi    : setting scan oui 0x957ba0e0
08-30 14:57:55.085  1035  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 14:57:55.085  1035  1523 I WifiNative-HAL: startHal
08-30 14:57:55.085  1035  1523 D wifi    : setting scan oui 0x957ba0e0
08-30 14:57:55.085  1035  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 14:57:55.085  1925  8024 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 14:57:55.086  1925  8024 E CtrlSupplicant: Succeed to open control connection
08-30 14:57:55.086  1035  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 14:57:55.086  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 14:57:55.086  1925  8024 E CtrlSupplicant: Succeed to open monitor connection
08-30 14:57:55.086  7967  7967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 14:57:55.087  1035  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 14:57:55.087  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 14:57:55.087  7967  7967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 14:57:55.087  1925  8024 D WfdsMonitor: Supplicant connection established
08-30 14:57:55.087  1925  2320 D WfdsService: Connected to the supplicant for wfds
08-30 14:57:55.088  1035  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 14:57:55.088  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 14:57:55.088  7967  7967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-30 14:57:55.088  1035  1523 D WifiNative-wlan0,: DRIVER RXFILTER-REMOVE 3: returned true
08-30 14:57:55.088  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 14:57:55.088  7967  7967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 14:57:55.089  1035  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 14:57:55.089  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 14:57:55.089  7967  7967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 14:57:55.089  1035  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 14:57:55.089  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 14:57:55.089  7967  7967 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 14:57:55.090  1035  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 14:57:55.090  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 14:57:55.090  7967  7967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,08-30 14:57:55.092  1035  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 14:57:55.094  1035  1523 E WifiNative: : [197,966,488 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 14:57:55.094  1035  1523 D WifiNative-wlan0: doBoolean: RECONNECT
08-30 14:57:55.094  1035  1523 D WifiNative-wlan0: RECONNECT: returned true
08-30 14:57:55.094  1035  1523 D WifiNative-wlan0: doString: [STATUS]
08-30 14:57:55.095  1035  8006 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 14:57:55.095  1035  8006 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 14:57:55.095  1035  1523 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 14:57:55.095  1035  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 14:57:55.096  1035  1523 D WifiNative-wlan0: SET ps 1: returned true
08-30 14:57:55.096  1035  1521 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.098  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 14:57:55.098  1035  1035 D RttService: SCAN_AVAILABLE : 3
08-30 14:57:55.098   305   893 D CommandListener: Setting iface cfg
08-30 14:57:55.098   305   893 D CommandListener: Trying to bring up p2p0
08-30 14:57:55.098  1035  1540 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.098  1035  1540 I WifiNative-HAL: startHal
08-30 14:57:55.098  1035  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 14:57:55.098  1035  1540 D wifi    : getting scan capabilities on interface[1] = 0x957ba0e0
08-30 14:57:55.098  1035  1540 D wifi    : failed to get capabilities : -3
08-30 14:57:55.098  1035  1540 E WifiScanningService: could not get scan capabilities
08-30 14:57:55.099  1035  1541 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.099  1035  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 14:57:55.099  1035  1521 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 14:57:55.099  1035  1521 D LGWifiP2pService: P2pEnablingState
08-30 14:57:55.099  1035  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-30 14:57:55.099  1035  1521 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.099  1035  1521 D LGWifiP2pService: P2p socket connection successful
08-30 14:57:55.099  1035  1521 D LGWifiP2pService: P2pEnabledState
08-30 14:57:55.100  1035  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 14:57:55.100  1035  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 14:57:55.100  1035  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 14:57:55.101  1035  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 14:57:55.101  1035  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-30 14:57:55.101  7967  7967 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-30 14:57:55.101  1035  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-30 14:57:55.102  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
,08-30 14:57:55.102  1925  1925 D WfdsService: WifiP2pState is changed : true
08-30 14:57:55.102  1925  2320 D WfdsService: Receive the WFDS_ENABLE Method
08-30 14:57:55.102  1035  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-30 14:57:55.102  1925  2320 D WfdsService: Set the WFDS Monitor: true
08-30 14:57:55.102  1925  2320 D WfdsService: Connected to the supplicant for wfds
08-30 14:57:55.102  1925  2320 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 14:57:55.102  7967  7967 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 14:57:55.102  1035  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 14:57:55.102  1035  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-30 14:57:55.102  1925  2320 D WfdsService: selectPreferredScanChannel [36]
08-30 14:57:55.102  1925  2320 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 14:57:55.102  7967  7967 E wpa_supplicant: disconnect_rssi_lvl: -100
08-30 14:57:55.103  1035  1523 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 14:57:55.103  1035  1523 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 14:57:55.104  1035  1523 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 14:57:55.104  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-30 14:57:55.104  7967  7967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 14:57:55.105  1035  1521 D LGWifiP2pService: sending p2p connection changed broadcast
08-30 14:57:55.105  7967  7967 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:57:55.105  1035  1521 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 14:57:55.105  7967  7967 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 14:57:55.106  7967  7967 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:55.106  7967  7967 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:55.107  1035  1523 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-30 14:57:55.107  1925  8024 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:57:55.107  1035  1521 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 14:57:55.107  1925  8024 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:57:55.107  1035  8006 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 14:57:55.107  1035  8006 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:57:55.107  1035  1521 D WifiNative-p2p0: doBoolean: SET device_name G3
08-30 14:57:55.107  1035  8006 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:57:55.107  1035  8006 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:57:55.107  1035  8006 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:57:55.107  1035  8006 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:55.108  1035  8006 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:55.108  1035  8006 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:55.108  1035  8006 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:57:55.108  1035  8006 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:55.108  1035  1521 D WifiNative-p2p0: SET device_name G3: returned true
08-30 14:57:55.108  1035  1521 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 14:57:55.108  1035  8006 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD,
08-30 14:57:55.108  1035  1521 D LGWifiP2pService: before postfix = G3
08-30 14:57:55.108  1035  8006 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:55.108  1035  1521 D WifiServerServiceExt: postfix byte check : 2
08-30 14:57:55.108  1035  1521 D LGWifiP2pService: after postfix = G3
08-30 14:57:55.108  1035  1521 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 14:57:55.108  1925  1925 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 14:57:55.108  1035  1521 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 14:57:55.108  1035  1521 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 14:57:55.109  1925  1925 D WfdsService: isConnected: false
08-30 14:57:55.109  1035  1521 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 14:57:55.109  1035  1521 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-30 14:57:55.109  1035  1521 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 14:57:55.109  1035  1521 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 14:57:55.109  1035  1521 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 14:57:55.110  1035  1521 D WifiNative-HAL: p2pGetDeviceAddress
08-30 14:57:55.110  1035  1521 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-30 14:57:55.111  1035  1521 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-30 14:57:55.111  1925  1925 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 14:57:55.111  1035  1521 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-30 14:57:55.112  1925  1925 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 14:57:55.112  1925  1925 D WfdsService: Update P2p Interface State: 3
08-30 14:57:55.112  1035  1521 D WifiNative-p2p0: P2P_FLUSH: returned true
08-30 14:57:55.112  1035  1521 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 14:57:55.112  1035  1521 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-30 14:57:55.113  1035  1521 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 14:57:55.113  1035  1521 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 14:57:55.113  1035  1521 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-30 14:57:55.115  1035  1523 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 14:57:55.115  1035  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 14:57:55.115  1035  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-30 14:57:55.115  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
,08-30 14:57:55.123  1035  1521 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-30 14:57:55.123  1035  1521 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-30 14:57:55.123  1035  1521 D LGWifiP2pService: InactiveState
08-30 14:57:55.123  1035  1521 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.123  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.123  1035  1521 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-30 14:57:55.124  7967  7967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 14:57:55.124  7967  7967 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:57:55.125  1035  8006 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 14:57:55.125  1035  8006 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:57:55.125  1035  8006 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:57:55.125  1035  8006 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 14:57:55.125  1925  8024 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 14:57:55.125  7967  7967 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 14:57:55.125  7967  7967 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:55.126  1035  1521 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 14:57:55.126  1035  1521 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.126  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.126  1035  1521 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.126  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.126  1035  1521 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.126  7967  7967 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:55.126  1035  1521 D LGWifiP2pService: InactiveState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.126  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.126  1035  1521 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.126  1035  1521 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.126  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.126  1035  1521 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.127  1035  1521 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.127  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.127  1035  1521 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.127  1925  8024 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANG,E init=DRIVER type=WORLD]
08-30 14:57:55.127  1925  8024 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:57:55.127  1035  8006 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:57:55.127  1035  8006 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:55.127  1035  8006 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:55.127  1035  8006 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:55.127  1035  8006 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 14:57:55.127  1035  8006 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:55.127  1035  8006 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:55.127  1035  8006 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 14:57:55.127  1035  1035 E WifiServerServiceExt: No p2p device connected
08-30 14:57:55.127  7967  7967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 14:57:55.127  7967  7967 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 14:57:55.128  1035  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 14:57:55.128  1035  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 14:57:55.129  1035  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 14:57:55.129  1035  1523 D WifiNative-wlan0: doBoolean: SCAN
08-30 14:57:55.129  1035  1523 D WifiNative-wlan0: SCAN: returned false
08-30 14:57:55.129  1925  2320 W WfdsService: DefaultState - msg [9441285] is not handled
08-30 14:57:55.130  1035  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=198004  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-30 14:57:55.130  1035  8006 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
,08-30 14:57:55.130  1035  8006 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 14:57:55.130  1035  8006 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 14:57:55.131  1035  8006 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 14:57:55.131  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=198005  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 14:57:55.131  1035  1523 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 14:57:55.132  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:55.132  1035  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 14:57:55.132  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:57:55.133  1035  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 14:57:55.133  1035  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 14:57:55.133  1035  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 14:57:55.134  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:55.134  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:55.134  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:55.134  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 14:57:55.134  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:57:55.134  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
08-30 14:57:55.137  1035  1969 I ActivityManager: Killing 7047:com.android.chrome/u0a57 (adj 15): empty #17
08-30 14:57:55.145  6646  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 14:57:55.145  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:55.145  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:55.145  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:57:55.145  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:57:55.145  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 14:57:55.145  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 14:57:55.145  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 14:57:55.148  6646  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 14:57:55.153  6646  6725 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-30 14:57:55.154  6646  6725 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 14:57:55.155  6646  6725 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@182d8b8b Bundle[{}]
08-30 14:57:55.156  6646  6725 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 14:57:55.156  6646  6725 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 14:57:55.157  6646  6725 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-30 14:57:55.157  8007  8007 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:57:55.157  6646  6725 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 14:57:55.158  6646  6725 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-30 14:57:55.159  6646  6725 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-30 14:57:55.165  6646  6725 I System.out: Running OutgoingSocketThread
08-30 14:57:55.166  6646  8029 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 857)
08-30 14:57:55.167  6646  8029 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 60662
08-30 14:57:55.167  6646  8029 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-30 14:57:55.185  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 14:57:55.185  1035  1936 W libprocessgroup: failed to open /acct/uid_10057/pid_7047/cgroup.procs: No such file or directory
,08-30 14:57:55.189  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 14:57:55.190  1035  2034 I ActivityManager: Killing 7081:com.lge.drmservice/u0a62 (adj 15): empty #17
08-30 14:57:55.218  1035  1050 W libprocessgroup: failed to open /acct/uid_10062/pid_7081/cgroup.procs: No such file or directory
,08-30 14:57:55.253  8007  8007 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 14:57:55.256  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 14:57:55.262  7985  8031 W FormManager: Network not available. Please check & try again.
08-30 14:57:55.265  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:57:55.273  7985  8032 V FormManager: Network unavailable.
,08-30 14:57:55.279  7985  8032 V FormManager: Network unavailable.
08-30 14:57:55.284  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 14:57:55.284  4296  4296 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 14:57:55.286  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 14:57:55.293  4296  4296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 14:57:55.307  4296  8033 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 14:57:55.313  4296  8034 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 14:57:55.313  4296  8034 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 14:57:55.367  1035  1936 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8035 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 14:57:55.389   341   341 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 644us total 21.149ms
,08-30 14:57:55.413   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 452us total 21.114ms
,08-30 14:57:55.434   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 417us total 19.260ms
08-30 14:57:55.483  8035  8035 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 14:57:55.483  8035  8035 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-30 14:57:55.489  8035  8035 V [BNRBootReceiver]: Boot Receiver Return
08-30 14:57:55.492  8035  8035 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 14:57:55.536  7967  7967 E wpa_supplicant: USIM:  scard_init function
,08-30 14:57:55.536  7967  7967 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-30 14:57:55.537  1035  8006 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-30 14:57:55.538  1035  8006 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,08-30 14:57:55.538  1035  8006 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-30 14:57:55.538  1035  8006 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-30 14:57:55.538  1035  8006 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-30 14:57:55.538  1035  8006 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-30 14:57:55.538  1035  8006 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-30 14:57:55.543  1035  1523 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
,08-30 14:57:55.544  1035  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-30 14:57:55.545  1035  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-30 14:57:55.545  1035  1908 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8056 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 14:57:55.546  1035  1908 I ActivityManager: Killing 7102:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-30 14:57:55.548  1035  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-30 14:57:55.550  1035  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,08-30 14:57:55.590  1035  1979 W libprocessgroup: failed to open /acct/uid_10085/pid_7102/cgroup.procs: No such file or directory
08-30 14:57:55.590  1035  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=198465  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-30 14:57:55.595  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=198470  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 14:57:55.596  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:55.596  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:57:55.597  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:55.597  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:55.597  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 14:57:55.597  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:55.599  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:55.599  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:55.599  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 14:57:55.605  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:57:55.605  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-30 14:57:55.620  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:55.620  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 14:57:55.622  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:55.624  8056  8056 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 14:57:55.649  7967  7967 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-30 14:57:55.651  8056  8056 D PluginManager: init()
,08-30 14:57:55.653  1035  8006 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-30 14:57:55.653  1035  8006 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-30 14:57:55.653  1035  8006 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-30 14:57:55.653  1035  8006 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-30 14:57:55.653  1035  8006 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 14:57:55.653  1035  8006 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 14:57:55.654  1035  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=198529  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 14:57:55.655  1035  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 14:57:55.655  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=198529  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 14:57:55.656  1035  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=198530
08-30 14:57:55.656  1035  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=198530
08-30 14:57:55.657  1035  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=198531
08-30 14:57:55.657  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=198531
08-30 14:57:55.657  1035  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=198532
08-30 14:57:55.660  7967  7967 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 14:57:55.660  7967  7967 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 14:57:55.661  1035  8006 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 14:57:55.661  1035  8006 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 14:57:55.661  1035  8006 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 14:57:55.661  1035  8006 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 14:57:55.661  1035  8006 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 14:57:55.661  1035  8006 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 14:57:55.661  1035  8006 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 14:57:55.661  1035  8006 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 14:57:55.662  1035  8006 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 14:57:55.662  1035  8006 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 14:57:55.658  1035  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=198532  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-30 14:57:55.668  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:55.668  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:57:55.668  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:55.668  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:55.668  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 14:57:55.670  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:55.674  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=198548  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 14:57:55.676  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:55.676  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:55.676  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,08-30 14:57:55.678  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:57:55.678  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-30 14:57:55.679  1035  1523 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:57:55.679  1035  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:57:55.680  1035  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:57:55.680  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:57:55.681  1035  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 14:57:55.681  1035  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=198556  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 14:57:55.682  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=198556  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 14:57:55.683  1035  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=198557
08-30 14:57:55.683  1035  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=198558
08-30 14:57:55.684  1035  1523 D WifiNative-wlan0: doString: [STATUS]
08-30 14:57:55.684  1035  8006 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 14:57:55.684  1035  8006 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 14:57:55.685  1035  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 14:57:55.686  1035  1523 I WifiServiceExtension: setVHTCapabilityType  : false
08-30 14:57:55.691  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:55.692  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:57:55.692  1035  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 14:57:55.692  1035  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-30 14:57:55.693  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:55.697  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 14:57:55.697  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:55.697  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 14:57:55.704  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:55.704  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:55.704  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 14:57:55.710  1035  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-30 14:57:55.710  1035  1529 D ConnectivityService: Got NetworkAgent Messenger
,08-30 14:57:55.710  1035  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 14:57:55.710  1035  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 14:57:55.711  1035  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 14:57:55.711  1035  1529 D ConnectivityService: NetworkAgent connected
08-30 14:57:55.711  1035  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 14:57:55.711  1035  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 14:57:55.714  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:55.714  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:57:55.715  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:55.717  1035  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 14:57:55.717  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:55.717  1035  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 14:57:55.717  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:57:55.717  1035  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 14:57:55.718  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:55.718  1035  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 14:57:55.719  1035  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 14:57:55.724  1035  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-30 14:57:55.725   305   893 D CommandListener: Setting iface cfg
08-30 14:57:55.728  1035  8080 D DhcpStateMachine: StoppedState
08-30 14:57:55.728  1035  1523 E WifiStateMachine: Start Dhcp Watchdog 3
08-30 14:57:55.728  1035  8080 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.728  1035  8080 D DhcpStateMachine: WaitBeforeStartState
08-30 14:57:55.729  1035  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=198603  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 14:57:55.729  1035  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=198604  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 14:57:55.730  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=198604  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 14:57:55.731  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:57:55.731  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-30 14:57:55.731  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:57:55.731  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-30 14:57:55.732  1035  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=198606  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 14:57:55.733  1035  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=198607  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 14:57:55.733  1035  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=198608  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 14:57:55.735  1035  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13996] from screen [on:0 period:-611906793] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 14:57:55.736  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-611906792] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 14:57:55.736  1035  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 14:57:55.740  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:55.741  1035  1529 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-30 14:57:55.742  1035  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:55.742  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-30 14:57:55.743  1035  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:55.744  1035  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:55.744  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:55.745  1035  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:55.745  1035  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 14:57:55.746  1035  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=132,0,0
08-30 14:57:55.746  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=132,0,0
08-30 14:57:55.747  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-30 14:57:55.747  7967  7967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-30 14:57:55.747  1035  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-30 14:57:55.747  1035  1523 D WifiNative-wlan0: doBoolean: SET ps 0
08-30 14:57:55.748  1035  1523 D WifiNative-wlan0: SET ps 0: returned true
08-30 14:57:55.748  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 14:57:55.748  7967  7967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
,08-30 14:57:55.749  1035  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-30 14:57:55.749  1035  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@33ed8efd target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.749  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@33ed8efd target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.749  1035  8080 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.750  1035  8080 D DhcpStateMachine: DHCP Start wake lock is acquired.
,08-30 14:57:55.750  1035  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 14:57:55.750  1035  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 14:57:55.750  1035  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 14:57:55.751   305   893 D CommandListener: Setting iface cfg
08-30 14:57:55.751   305   893 D CommandListener: Trying to bring up wlan0
08-30 14:57:55.752  1035  1523 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-30 14:57:55.753  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:57:55.753  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 14:57:55.754  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 14:57:55.754  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 14:57:55.756  1035  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:55.756  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:55.757  1035  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:55.757  1035  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:55.758  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:55.758  1035  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 14:57:55.759  1035  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 14:57:55.759  1035  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 14:57:55.760  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 14:57:55.760  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 14:57:55.760  1035  1521 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.760  1035  1521 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.760  7967  7967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-30 14:57:55.761  1035  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 14:57:55.762  1035  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 14:57:55.762  7967  7967 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-30 14:57:55.762  1035  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 14:57:55.762  1035  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 14:57:55.779  1035  1523 D WifiNative-wlan0: SET ps 1: returned true
08-30 14:57:55.779  1035  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 14:57:55.780  1035  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,08-30 14:57:55.780  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,08-30 14:57:55.780  1035  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 14:57:55.781  1035  1529 D ConnectivityService: ignoring duplicate network state non-change
08-30 14:57:55.784  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:55.784  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:57:55.786  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:55.788  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:55.788  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:55.788  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 14:57:55.790  1035  1529 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 14:57:55.791  1035  1529 D ConnectivityService: Adding iface wlan0 to network 102
,08-30 14:57:55.797  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:55.797  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:55.797  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 14:57:55.799  1035  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 14:57:55.801  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 14:57:55.804  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-30 14:57:55.809  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:55.809  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:55.809  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 14:57:55.810  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 14:57:55.815  1035  1529 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 14:57:55.815  1035  1529 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-30 14:57:55.816  1035  1529 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-30 14:57:55.817  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:55.817  1587  1587 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 14:57:55.817  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:55.817  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 14:57:55.817   305   893 E Netd    : netlink response contains error (File exists)
08-30 14:57:55.817  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 14:57:55.818  1035  1529 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-30 14:57:55.819  1035  1529 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 14:57:55.819  1035  1529 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-30 14:57:55.819  1035  1529 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-30 14:57:55.822  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:55.825  1035  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 14:57:55.825  1035  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 14:57:55.825  1035  1529 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-30 14:57:55.825  1035  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 14:57:55.825  1035  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 14:57:55.825  1035  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:57:55.825  1035  8079 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.825  1035  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 14:57:55.825  1035  8079 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-30 14:57:55.825  1035  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:57:55.826  1035  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 14:57:55.826  1035  8079 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 14:57:55.826  1035  1529 D ConnectivityService: currentScore = 0, newScore = 20
08-30 14:57:55.826  1035  1529 D ConnectivityService:    accepting network in place of null
08-30 14:57:55.826  1035  1529 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:57:55.826  1035  8079 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 14:57:55.826  1035  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:57:55.826  1035  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 14:57:55.827  1835  1835 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:57:55.827  1835  1835 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-30 14:57:55.829  1035  1529 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 14:57:55.829  1035  1529 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-30 14:57:55.830  1035  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 14:57:55.830  1035  1529 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 14:57:55.830  1035  1529 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 14:57:55.830  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:55.831  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 14:57:55.831  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:55.832  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-30 14:57:55.833  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 14:57:55.833  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 14:57:55.833  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-30 14:57:55.835  1035  1529 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-30 14:57:55.836  1035  1529 D ConnectivityService: validation of new default Network = false
08-30 14:57:55.836  1035  1529 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 14:57:55.836  1035  1529 D DSQN    : enableDataServiceNotify 
08-30 14:57:55.836  1035  1529 D DSQN    : start dsqn bin
08-30 14:57:55.837  1587  1587 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 14:57:55.837  1587  1587 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 14:57:55.837  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:55.839   305  8084 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 14:57:55.839   305  8084 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-30 14:57:55.844  1035  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 14:57:55.844  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:57:55.844  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-30 14:57:55.845  1035  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:57:55.834  8085  8085 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:57:55.834  8085  8085 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:57:55.848  1035  1520 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-30 14:57:55.848  1587  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 14:57:55.853  8085  8085 E DSQN    : DSQN ssw
,08-30 14:57:55.865  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 14:57:55.866  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:55.867  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:55.886   305  8084 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-30 14:57:55.911   305   892 D LGDataListener: argv[0]=dsqncommand
08-30 14:57:55.911   305   892 D LGDataListener: argv[1]=wlan0
08-30 14:57:55.911   305   892 D LGDataListener: argv[2]=1
08-30 14:57:55.911   305   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,08-30 14:57:55.912  1035  1115 D DSQN    : DSQM DsqnNotification wlan0  1
,08-30 14:57:55.912  1035  1115 D DSQN    : start to monitor internet connection
08-30 14:57:55.940  1035  8079 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 12:57:55 GMT], X-Android-Received-Millis=[1472561875940], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472561875911]}
08-30 14:57:55.940  1035  8079 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,08-30 14:57:55.940  1035  8079 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-30 14:57:55.941  1035  1529 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-30 14:57:55.941  1035  1529 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 14:57:55.941  1035  1529 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 14:57:55.941  1035  1529 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:57:55.942  1035  1529 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 14:57:55.942  1035  1529 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-30 14:57:55.942  1035  1529 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 14:57:55.942  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:57:55.942  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-30 14:57:55.944  1035  1529 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:57:55.946  1587  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 14:57:55.946  1035  1529 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:57:55.946  1035  1523 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:57:55.947  1035  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 14:57:55.948  1035  1529 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-30 14:57:55.948  1835  1835 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:57:55.949  1835  1835 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 14:57:55.953  1035  8080 D DhcpStateMachine: DHCPV4 request on wlan0
08-30 14:57:55.954  1035  8080 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-30 14:57:55.954  1035  8080 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-30 14:57:55.944  8091  8091 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 14:57:55.944  8091  8091 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 14:57:55.977  8091  8091 I dhcpcd  : version 5.5.6 starting
,08-30 14:57:55.980  8091  8091 E dhcpcd  : get_duid: m
08-30 14:57:55.980  8091  8091 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 14:57:55.980  8091  8091 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-30 14:57:55.987  1587  1587 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 14:57:55.990  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 14:57:55.993  1587  1587 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 14:57:56.046  8091  8091 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 14:57:56.046  8091  8091 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-30 14:57:56.046  8091  8091 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-30 14:57:56.047  8091  8091 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 14:57:56.047  8091  8091 D dhcpcd  : wlan0: sending REQUEST (xid 0xad051141), next in 3.76 seconds
08-30 14:57:56.104  8091  8091 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-30 14:57:56.105  8056  8056 W ExternalStrings: load override strings
08-30 14:57:56.105  8056  8056 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-30 14:57:56.105  8056  8056 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-30 14:57:56.105  8056  8056 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-30 14:57:56.105  8056  8056 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-30 14:57:56.105  8056  8056 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-30 14:57:56.105  8056  8056 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-30 14:57:56.105  8056  8056 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-30 14:57:56.105  8056  8056 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-30 14:57:56.105  8056  8056 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-30 14:57:56.105  8056  8056 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-30 14:57:56.105  8056  8056 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-30 14:57:56.105  8056  8056 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 14:57:56.105  8056  8056 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-30 14:57:56.105  8056  8056 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 14:57:56.105  8056  8056 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:57:56.105  8056  8056 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 14:57:56.105  8056  8056 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 14:57:56.105  8056  8056 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 14:57:56.107  8056  8056 D StatusProvider: onCreate
,08-30 14:57:56.113  8091  8091 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-30 14:57:56.113  8091  8091 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-30 14:57:56.114  8091  8091 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-30 14:57:56.114  8091  8091 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-30 14:57:56.115  8091  8091 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 14:57:56.115  8091  8091 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 14:57:56.116  8091  8091 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 14:57:56.116  8091  8091 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-30 14:57:56.145  8056  8056 V Signer  : override build config not found
08-30 14:57:56.145  8056  8056 D Signer  : value of property debug is false
,08-30 14:57:56.169  6646  6725 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 858)
08-30 14:57:56.169  6646  6725 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 858)
08-30 14:57:56.170  8056  8056 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-30 14:57:56.170  8056  8056 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-30 14:57:56.170  8056  8056 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-30 14:57:56.170  8056  8056 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-30 14:57:56.170  8056  8056 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-30 14:57:56.170  8056  8056 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
,08-30 14:57:56.171  8056  8056 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-30 14:57:56.171  8056  8056 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-30 14:57:56.171  8056  8056 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-30 14:57:56.171  8056  8056 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-30 14:57:56.171  8056  8056 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-30 14:57:56.171  8056  8056 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-30 14:57:56.171  8056  8056 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-30 14:57:56.178  8056  8056 V LGMDMManager: Create singleton instance
08-30 14:57:56.181  6646  6725 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 863)
08-30 14:57:56.183  6646  6725 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-30 14:57:56.183  6646  6725 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 864)
08-30 14:57:56.189  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:57:56.189  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15db17d6 added. We now have 2 listener(s)
08-30 14:57:56.190  1035  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 14:57:56.195  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 14:57:56.195  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:57:56.195  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:57:56.195  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:57:56.195  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15108a57 added. We now have 9 listener(s)
08-30 14:57:56.196  6646  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:57:56.196  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 14:57:56.198  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:57:56.212  6646  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:57:56.212  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:56.212  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:56.212  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:57:56.212  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:57:56.212  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:57:56.212  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:57:56.212  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 14:57:56.214  6646  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:57:56.215  6646  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:57:56.215  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:57:56.215  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23eb2a2d added. We now have 3 listener(s)
08-30 14:57:56.216  1035  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:56.217  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:56.219  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:56.221  8056  8056 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
08-30 14:57:56.224  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 14:57:56.224  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:57:56.224  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:57:56.225  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:57:56.225  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8db62 added. We now have 10 listener(s)
08-30 14:57:56.225  6646  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 14:57:56.225  6646  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:57:56.226  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:56.226  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:57:56.226  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:56.226  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:56.226  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:57:56.226  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:57:56.226  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15db17d6 removed from the list
08-30 14:57:56.226  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:56.226  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15108a57 removed from the list
08-30 14:57:56.227  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:57:56.227  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:56.228  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:56.228  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:56.230  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:56.230  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:56.230  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:56.230  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15108a57 not in the list
,08-30 14:57:56.230  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:56.230  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:56.230  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:56.230  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:56.230  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:56.230  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dc8db62 removed from the list
08-30 14:57:56.230  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:56.230  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:56.230  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:56.230  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:57:56.230  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23eb2a2d removed from the list
08-30 14:57:56.231  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:57:56.231  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@112974f3 added. We now have 2 listener(s)
08-30 14:57:56.231  1035  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:56.232  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 14:57:56.232  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:57:56.232  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:57:56.232  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:57:56.233  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@173b05b0 added. We now have 9 listener(s)
08-30 14:57:56.233  6646  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:57:56.239  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 14:57:56.244  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:57:56.248  6646  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:57:56.248  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:56.248  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:56.248  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:57:56.248  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:57:56.248  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:57:56.248  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:57:56.248  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:57:56.249  6646  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:57:56.249  6646  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:57:56.249  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:57:56.249  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15dd4bae added. We now have 3 listener(s)
08-30 14:57:56.250  1035  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:56.252  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 14:57:56.252  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:57:56.252  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:57:56.252  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:57:56.252  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32dc6d4f added. We now have 10 listener(s)
08-30 14:57:56.252  6646  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 14:57:56.252  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:57:56.252  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 14:57:56.252  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 14:57:56.252  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 14:57:56.252  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 14:57:56.255  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:56.257  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:56.258  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 14:57:56.258  1035  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:56.262  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 14:57:56.263  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 14:57:56.265  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 14:57:56.265  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 14:57:56.268  6646  6725 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 14:57:56.269  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:56.269  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:57:56.271  6646  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:57:56.271  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:56.271  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:57:56.271  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:56.272  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:56.272  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:57:56.272  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:57:56.272  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@112974f3 removed from the list
08-30 14:57:56.272  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:56.272  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@173b05b0 removed from the list
08-30 14:57:56.272  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:57:56.272  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:56.272  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:56.272  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:56.273  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:56.273  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:56.273  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:56.273  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@173b05b0 not in the list
08-30 14:57:56.273  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:56.273  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:56.274  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:56.274  6646  6725 D BluetoothLeScanner: could not find callback wrapper
08-30 14:57:56.274  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:57:56.274  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:56.274  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:56.274  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryMa,nagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32dc6d4f removed from the list
08-30 14:57:56.274  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:56.274  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:56.274  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:56.274  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:57:56.274  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15dd4bae removed from the list
08-30 14:57:56.275  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:57:56.275  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cb674ba added. We now have 2 listener(s)
08-30 14:57:56.275  1035  1969 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:56.278  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 14:57:56.278  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:57:56.278  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:57:56.278  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:57:56.278  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@131c8f6b added. We now have 9 listener(s)
08-30 14:57:56.278  6646  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:57:56.278  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 14:57:56.281  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:57:56.284  6646  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:57:56.284  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:56.284  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:56.284  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:57:56.284  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:57:56.284  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:57:56.284  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:57:56.284  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:57:56.287  6646  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:57:56.287  6646  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:57:56.289  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:57:56.289  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@308f4761 added. We now have 3 listener(s)
08-30 14:57:56.290  1035  1559 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:56.290  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:56.292  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 14:57:56.292  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:57:56.292  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:57:56.293  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:57:56.293  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ac72286 added. We now have 10 listener(s)
08-30 14:57:56.293  6646  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:57:56.293  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:57:56.293  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:56.294  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 14:57:56.294  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 14:57:56.294  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 14:57:56.294  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:57:56.294  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 14:57:56.297  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 14:57:56.299  1035  1979 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:56.299  8056  8113 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 14:57:56.300  8056  8056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:56.304  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 14:57:56.305  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 14:57:56.307  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 14:57:56.307  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:57:56.309  6646  6725 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 14:57:56.309  6646  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:57:56.309  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:56.309  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:57:56.309  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:56.309  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:56.309  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:57:56.309  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:57:56.309  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cb674ba removed from the list
08-30 14:57:56.309  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:56.309  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@131c8f6b removed from the list
08-30 14:57:56.309  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:57:56.309  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:56.310  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:56.310  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:56.311  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:56.311  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:56.311  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:56.311  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@131c8f6b not in the list
08-30 14:57:56.312  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:56.312  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:56.312  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:56.313  6646  6725 D BluetoothLeScanner: could not find callback wrapper
08-30 14:57:56.313  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:57:56.314  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:56.314  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:56.314  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ac72286 removed from the list
08-,30 14:57:56.314  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:56.314  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:56.314  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:56.314  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:57:56.314  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@308f4761 removed from the list
08-30 14:57:56.315  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:57:56.315  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e97f89d added. We now have 2 listener(s)
08-30 14:57:56.316  1035  1630 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 14:57:56.316  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 14:57:56.318  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 14:57:56.318  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:57:56.318  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:57:56.318  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:57:56.319  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ae2e112 added. We now have 9 listener(s)
08-30 14:57:56.319  6646  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:57:56.319  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 14:57:56.322  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:57:56.325  6646  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:57:56.325  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:56.325  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:56.325  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:57:56.325  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:57:56.325  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:57:56.325  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:57:56.325  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:57:56.328  6646  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:57:56.328  6646  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:57:56.328  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:57:56.328  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27b33ae0 added. We now have 3 listener(s)
08-30 14:57:56.329  1035  1630 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 14:57:56.330  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:56.332  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:56.334  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 14:57:56.334  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:57:56.334  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:57:56.335  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:57:56.335  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c808199 added. We now have 10 listener(s)
08-30 14:57:56.335  6646  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:57:56.335  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:57:56.335  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 14:57:56.335  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 14:57:56.335  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 14:57:56.335  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 14:57:56.338  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:57:56.338  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 14:57:56.341  1035  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:56.345  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 14:57:56.346  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 14:57:56.347  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 14:57:56.390  1035  1559 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8123 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-30 14:57:56.390  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:57:56.391  1035  1559 I ActivityManager: Killing 7147:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-30 14:57:56.393  6646  6725 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 14:57:56.395  6646  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:57:56.395  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:56.395  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:57:56.395  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:56.395  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:56.395  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:57:56.395  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:57:56.395  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e97f89d removed from the list
08-30 14:57:56.395  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:56.395  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ae2e112 removed from the list
08-30 14:57:56.395  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:57:56.395  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:56.460  8056  8111 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-30 14:57:56.559  1035  8080 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-30 14:57:56.562  1035  8080 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-30 14:57:56.565  1035  8080 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 14:57:56.566  1035  8080 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-30 14:57:56.566  1035  8080 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-30 14:57:56.566  1035  8080 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 14:57:56.566  1035  8080 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-30 14:57:56.566  1035  8080 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,08-30 14:57:56.567  1035  8080 D DhcpStateMachine: RunningState
,08-30 14:57:56.602  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:56.602  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 14:57:56.611  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 14:57:56.611  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:56.612  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:56.612  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ae2e112 not in the list
08-30 14:57:56.612  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:56.612  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:56.614  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:56.615  1035  1979 W libprocessgroup: failed to open /acct/uid_10093/pid_7147/cgroup.procs: No such file or directory
08-30 14:57:56.617  6646  6725 D BluetoothLeScanner: could not find callback wrapper
08-30 14:57:56.617  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 14:57:56.617  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:56.617  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:56.617  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c808199 removed from the list
08-30 14:57:56.617  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:56.617  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:56.617  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:56.618  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:57:56.618  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27b33ae0 removed from the list
08-30 14:57:56.620  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:57:56.621  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c1250c added. We now have 2 listener(s)
08-30 14:57:56.622  1035  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 14:57:56.631  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 14:57:56.632  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:57:56.632  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:57:56.633  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:57:56.633  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12ce9e55 added. We now have 9 listener(s)
08-30 14:57:56.633  6646  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:57:56.634  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 14:57:56.637  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 14:57:56.642  6646  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 14:57:56.642  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 14:57:56.642  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 14:57:56.642  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 14:57:56.642  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 14:57:56.642  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 14:57:56.642  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 14:57:56.642  6646  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 14:57:56.645  6646  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 14:57:56.645  6646  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 14:57:56.645  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 14:57:56.645  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31a4295b added. We now have 3 listener(s)
08-30 14:57:56.646  1035  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 14:57:56.649  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:56.652  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-30 14:57:56.652  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 14:57:56.652  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 14:57:56.653  6646  6646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 14:57:56.653  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 14:57:56.653  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ee185f8 added. We now have 10 listener(s)
08-30 14:57:56.653  6646  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 14:57:56.654  6646  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 14:57:56.654  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:56.654  6646  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 14:57:56.655  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:56.655  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:56.655  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 14:57:56.655  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:57:56.655  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c1250c removed from the list
08-30 14:57:56.655  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:56.655  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12ce9e55 removed from the list
08-30 14:57:56.655  6646  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-30 14:57:56.655  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:56.658  8123  8123 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 14:57:56.659  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:56.659  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:56.662  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:56.662  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:56.662  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:56.662  6646  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12ce9e55 not in the list
08-30 14:57:56.662  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:56.662  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:56.664  6646  6725 I org.thalipro,ject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 14:57:56.664  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 14:57:56.664  6646  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 14:57:56.664  6646  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ee185f8 removed from the list
08-30 14:57:56.664  6646  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 14:57:56.664  6646  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 14:57:56.664  6646  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 14:57:56.664  6646  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 14:57:56.665  6646  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31a4295b removed from the list
,08-30 14:57:56.667  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 14:57:56.667  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 14:57:56.668  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 14:57:56.668  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 14:57:56.669  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 14:57:56.669  6646  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 14:57:56.687  8123  8123 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-30 14:57:56.688  6646  8145 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 871, name: My test thread name)
08-30 14:57:56.688  6646  8145 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 871, thread name: My test thread name)
08-30 14:57:56.689  6646  8145 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 871, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-30 14:57:56.691  6646  8146 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 873, name: My test thread name)
08-30 14:57:56.691  6646  8146 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 873, thread name: My test thread name)
08-30 14:57:56.691  6646  8146 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 873, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-30 14:57:56.694  6646  6725 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-30 14:57:56.694  6646  6725 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-30 14:57:56.694  6646  6725 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-30 14:57:56.694  6646  6725 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-30 14:57:56.694  6646  6725 D com.test.thalitest.ThaliTestRunner: Total duration: 23277 ms
08-30 14:57:56.695  6646  6725 I jxcore-log: *Native tests were executed*
08-30 14:57:56.695  6646  6725 I jxcore-log: 
08-30 14:57:56.696  6646  6725 I jxcore-log: Total number of executed tests:  80
08-30 14:57:56.696  6646  6725 I jxcore-log: 
08-30 14:57:56.696  6646  6725 I jxcore-log: Number of passed tests:  80
08-30 14:57:56.696  6646  6725 I jxcore-log: 
08-30 14:57:56.696  6646  6725 I jxcore-log: Number of failed tests:  0
08-30 14:57:56.696  6646  6725 I jxcore-log: 
08-30 14:57:56.696  6646  6725 I jxcore-log: Number of ignored tests:  0
08-30 14:57:56.696  6646  6725 I jxcore-log: 
08-30 14:57:56.697  6646  6725 I jxcore-log: Total duration:  23277
08-30 14:57:56.697  6646  6725 I jxcore-log: 
08-30 14:57:56.697  6646  6725 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 14:57:56.697  6646  6725 I jxcore-log: 
08-30 14:57:56.700  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:57:56.700  6646  6725 I jxcore-log: 
08-30 14:57:56.703  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:57:56.703  6646  6725 I jxcore-log: 
,08-30 14:57:56.705  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:57:56.705  6646  6725 I jxcore-log: 
08-30 14:57:56.706  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:57:56.706  6646  6725 I jxcore-log: 
08-30 14:57:56.707  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:57:56.707  6646  6725 I jxcore-log: 
08-30 14:57:56.709  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 14:57:56.709  6646  6725 I jxcore-log: 
08-30 14:57:56.712  6646  6646 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 14:57:56.712  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 14:57:56.712  6646  6725 I jxcore-log: 
08-30 14:57:56.715  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 14:57:56.715  6646  6725 I jxcore-log: 
08-30 14:57:56.716  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 14:57:56.716  6646  6725 I jxcore-log: 
08-30 14:57:56.717  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 14:57:56.717  6646  6725 I jxcore-log: 
08-30 14:57:56.718  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 14:57:56.718  6646  6725 I jxcore-log: 
08-30 14:57:56.719  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 14:57:56.719  6646  6725 I jxcore-log: 
08-30 14:57:56.721  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 14:57:56.721  6646  6725 I jxcore-log: 
08-30 14:57:56.722  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 14:57:56.722  6646  6725 I jxcore-log: 
,08-30 14:57:56.723  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 14:57:56.723  6646  6725 I jxcore-log: 
08-30 14:57:56.724  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 14:57:56.724  6646  6725 I jxcore-log: 
08-30 14:57:56.724  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 14:57:56.724  6646  6725 I jxcore-log: 
08-30 14:57:56.725  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 14:57:56.725  6646  6725 I jxcore-log: 
08-30 14:57:56.726  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 14:57:56.726  6646  6725 I jxcore-log: 
08-30 14:57:56.727  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 14:57:56.727  6646  6725 I jxcore-log: 
08-30 14:57:56.728  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 14:57:56.728  6646  6725 I jxcore-log: 
08-30 14:57:56.729  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 14:57:56.729  6646  6725 I jxcore-log: 
08-30 14:57:56.730  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:57:56.730  6646  6725 I jxcore-log: 
08-30 14:57:56.730  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:57:56.730  6646  6725 I jxcore-log: 
08-30 14:57:56.731  8123  8123 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-30 14:57:56.731  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:57:56.731  6646  6725 I jxcore-log: 
08-30 14:57:56.731  8123  8123 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-30 14:57:56.732  8123  8123 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-30 14:57:56.732  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:57:56.732  6646  6725 I jxcore-log: 
08-30 14:57:56.732  8123  8123 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-30 14:57:56.733  8123  8123 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-30 14:57:56.733  6646  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 14:57:56.733  6646  6725 I jxcore-log: 
08-30 14:57:56.734  8123  8123 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-30 14:57:56.738  8123  8123 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-30 14:57:56.742  8123  8123 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:57:56.744  8123  8123 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:57:56.752  8123  8123 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 14:57:56.754  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-30 14:57:56.756  6747  6747 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-30 14:57:56.758  8123  8123 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-30 14:57:56.759  8056  8056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:56.759  8056  8113 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 14:57:56.759  8056  8111 D LgDataFeature: LgDataFeature() Constructor: none
08-30 14:57:56.760  8056  8111 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 14:57:56.762  8123  8123 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-30 14:57:56.764  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:57:56.769  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:57:56.776  8123  8123 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:57:56.776  8123  8123 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 14:57:56.778  8123  8123 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 14:57:56.780  8056  8056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:56.781  8056  8113 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 14:57:56.788  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:57:56.793  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null,
08-30 14:57:56.798  8123  8123 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:57:56.799  8123  8123 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:57:56.799  8123  8123 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 14:57:56.801  6747  6747 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 14:57:56.801  6747  6747 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 14:57:56.801  6747  6747 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 14:57:56.801  6747  6747 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-30 14:57:56.802  6747  6747 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 14:57:56.803  6747  6747 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 14:57:56.803  6747  6747 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-30 14:57:56.803  6747  6747 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 14:57:56.803  6747  6747 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 14:57:56.803  6747  6747 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 14:57:56.803  6747  6747 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-30 14:57:56.803  6747  6747 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 14:57:56.805  8056  8056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:56.806  8056  8113 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 14:57:56.811  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:57:56.814  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:57:56.819  8123  8123 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:57:56.819  8123  8123 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:57:56.820  8123  8123 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 14:57:56.822  8056  8056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:56.822  8056  8113 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 14:57:56.829  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:57:56.833  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:57:56.837  8123  8123 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:57:56.837  8123  8123 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:57:56.837  8123  8123 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 14:57:56.840  8056  8056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:56.840  8056  8113 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 14:57:56.845  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 14:57:56.849  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:57:56.855  8123  8123 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 14:57:56.855  8123  8123 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:57:56.856  8123  8123 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 14:57:56.858  8056  8056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:56.858  8056  8113 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 14:57:56.864  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:57:56.868  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:57:56.873  8123  8123 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:57:56.874  8123  8123 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:57:56.874  8123  8123 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 14:57:56.880  8056  8113 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 14:57:56.881  8056  8056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:56.891  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:57:56.896  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:57:56.901  8123  8123 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:57:56.901  8123  8123 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:57:56.902  8056  8111 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-30 14:57:56.907  8123  8123 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 14:57:56.910  8056  8056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:56.911  8056  8113 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 14:57:56.915  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 14:57:56.919  8056  8111 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-30 14:57:56.921  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:57:56.927  8123  8123 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:57:56.927  8123  8123 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:57:56.928  8123  8123 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 14:57:56.930  8056  8056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:56.931  8056  8113 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 14:57:56.933  8056  8111 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-30 14:57:56.933  8007  8007 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 14:57:56.933  8056  8111 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-30 14:57:56.934  8056  8111 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-30 14:57:56.935  8056  8111 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-30 14:57:56.935  8056  8111 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-30 14:57:56.937  8007  8007 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:57:56.939  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 14:57:56.940  8056  8111 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,08-30 14:57:56.942  8056  8111 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-30 14:57:56.944  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:57:56.949  8123  8123 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:57:56.950  8123  8123 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 14:57:56.951  8123  8123 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 14:57:56.951  8123  8123 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 14:57:56.952  8123  8123 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 14:57:56.955  8056  8056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:56.956  8056  8113 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 14:57:56.959  8007  8007 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 14:57:56.959  8007  8007 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 14:57:56.963  6747  6747 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 14:57:56.964  8152  8152 D AndroidRuntime: 
08-30 14:57:56.964  8152  8152 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 14:57:56.967  8152  8152 D AndroidRuntime: CheckJNI is OFF
,08-30 14:57:56.967  6747  6747 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 14:57:56.974  8123  8123 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 14:57:56.974  8123  8123 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 14:57:56.975  8123  8123 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 14:57:56.975  8123  8123 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 14:57:56.976  8123  8123 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 14:57:56.978  8056  8056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 14:57:56.982  8123  8123 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-30 14:57:56.983  8123  8123 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 14:57:56.983  8123  8123 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-30 14:57:57.018  8123  8123 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 14:57:57.019  8123  8123 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 14:57:57.025  8123  8123 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-30 14:57:57.026  8123  8123 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-30 14:57:57.026  8123  8123 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-30 14:57:57.026  8123  8123 V SoundPool: doLoad: loading sample sampleID=1
08-30 14:57:57.026  8123  8123 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 14:57:57.027  8123  8171 V SoundPool: Start decode
08-30 14:57:57.027  8123  8171 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-30 14:57:57.029  7557  7557 D UEI.SmartControl: QS Service created
08-30 14:57:57.030  8123  8123 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-30 14:57:57.031   311  2116 V MediaPlayerService: decode(23, 10857164, 17813)
08-30 14:57:57.031   311  2116 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-30 14:57:57.031   311  2116 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-30 14:57:57.031   311  2116 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-30 14:57:57.031   311  2116 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-30 14:57:57.031   311  2116 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-30 14:57:57.031   311  2116 V MediaPlayerService: player type = 3
08-30 14:57:57.031   311  2116 V AwesomePlayer: AwesomePlayer create()
08-30 14:57:57.031   311  2116 V AwesomePlayer: reset_l() 
08-30 14:57:57.031   311  2116 V AwesomePlayer: cancelPlayerEvents
08-30 14:57:57.031   311  2116 V AwesomePlayer: setAudioSink() 
08-30 14:57:57.031   311  2116 V AwesomePlayer: reset_l() 
08-30 14:57:57.031   311  2116 V AudioCache: notify(0xb14324c0, 8, 0, 0)
08-30 14:57:57.031   311  2116 V AudioCache: ignored
08-30 14:57:57.031   311  2116 V AwesomePlayer: cancelPlayerEvents
,08-30 14:57:57.031   311  2116 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-30 14:57:57.032   311  2116 V AwesomePlayer: setDataSource_l dataSource
08-30 14:57:57.032   311  2116 V LGParserOSAL: SniffLGParser start
08-30 14:57:57.032   311  2116 V LGParserOSAL: MainType:5, SubType=0
08-30 14:57:57.032   311  2116 V LGParserOSAL: #### check Mime : application/ogg
08-30 14:57:57.032   311  2116 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-30 14:57:57.032   311  2116 E MediaExtractor: Use LGExtractor :application/ogg 
08-30 14:57:57.036  8123  8123 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 14:57:57.036  8123  8123 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 14:57:57.039  7557  7557 I UEI.SmartControl: Service initServices...
08-30 14:57:57.040  7557  7557 D UEI.SmartControl: QS start get config
08-30 14:57:57.046  8123  8123 V LGMDMManager: Create singleton instance
,08-30 14:57:57.087   311  2116 V LGParserOSAL: supported mime: application/ogg
08-30 14:57:57.087   311  2116 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-30 14:57:57.087   311  2116 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-30 14:57:57.087   311  2116 V AwesomePlayer: mBitrate = -1 bits/sec
08-30 14:57:57.087   311  2116 V AwesomePlayer: AudioTrack Setting
08-30 14:57:57.087   311  2116 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-30 14:57:57.087   311  2116 V AwesomePlayer: setAudioSource() 
08-30 14:57:57.087   311  2116 V MediaPlayerService: prepare
08-30 14:57:57.087   311  2116 V AwesomePlayer: prepareAsync_l() 
08-30 14:57:57.087   311  2116 V MediaPlayerService: wait for prepare
08-30 14:57:57.087   311  8172 V AwesomePlayer: onPrepareAsyncEvent() 
08-30 14:57:57.087   311  8172 V AwesomePlayer: initAudioDecoder() 
08-30 14:57:57.087   311  8172 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 14:57:57.087   311  8172 V AudioSystem: isOffloadSupported()
08-30 14:57:57.087   311  8172 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 14:57:57.087   311  8172 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 14:57:57.087   311  8172 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 14:57:57.087   311  8172 V AwesomePlayer: getUseOffload() = 0 
08-30 14:57:57.087   311  8172 V OMXCodec: OMXCodec::Create
08-30 14:57:57.087   311  8172 V OMXCodec: findMatchingCodecs()
08-30 14:57:57.087   311  8172 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-30 14:57:57.087   311  8172 V OMXCodec: matchingCodecs.size()=1
08-30 14:57:57.087   311  8172 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-30 14:57:57.088   311  8172 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-30 14:57:57.088   311  8172 V LGCodecAdapter: LG Codec Adapter start
08-30 14:57:57.089   311  8172 V OMXCodec: OMXCodec Createtor
08-30 14:57:57.089   311  8172 V OMXCodec: setComponentRole
08-30 14:57:57.089   311  8172 V OMXCodec: configureCodec protected=0
08-30 14:57:57.089   311  8172 V LGCodecAdapter: called getLGCodecSpecificData
08-30 14:57:57.089   311  8172 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-30 14:57:57.089   311  8172 V LGCodecOSAL: Called LGconfigureCodecMETA
08-30 14:57:57.089   311  8172 V LGCodecOSAL: Called LGconfigureCodecMSG
08-30 14:57:57.089   311  8172 V LGCodecOSAL: Not support LGCodec
08-30 14:57:57.089   311  8172 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 14:57:57.089   311  8172 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-30 14:57:57.089   311  8172 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-30 14:57:57.089   311  8172 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-30 14:57:57.089   311  8172 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 14:57:57.089   311  8172 V AudioSystem: isOffloadSupported()
08-30 14:57:57.089   311  8172 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 14:57:57.089   311  8172 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 14:57:57.089   311  8172 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-30 14:57:57.089   311  8172 V OMXCodec: init()
08-30 14:57:57.089   311  8172 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-30 14:57:57.089   311  8172 V OMXCodec: allocateBuffers
08-30 14:57:57.089   311  8172 V OMXCodec: allocateBuffersOnPort portIndex=0
08-30 14:57:57.089   311  8172 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-30 14:57:57.089   311  8172 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7790 on input port
08-30 14:57:57.089   311  8172 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f77e0 on input port
08-30 14:57:57.089   311  8172 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7830 on input port
08-30 14:57:57.089   311  8172 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-30 14:57:57.089   311  8172 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 14:57:57.089   311  8172 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 14:57:57.089   311  8172 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-30 14:57:57.089   311  8172 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-30 14:57:57.089   311  8172 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-30 14:57:57.089   311  8172 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-30 14:57:57.089   311  8172 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 14:57:57.090   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 14:57:57.090   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 14:57:57.090   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-30 14:57:57.090   311  8172 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 14:57:57.090   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-30 14:57:57.090   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-30 14:57:57.090   31,1  8174 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-30 14:57:57.090   311  8172 V OMXCodec: init() mAsyncCompletion wait free! 
08-30 14:57:57.090   311  8172 V AwesomePlayer: finishAsyncPrepare_l() 
08-30 14:57:57.090   311  8172 V AudioCache: notify(0xb14324c0, 5, 0, 0)
08-30 14:57:57.090   311  8172 V AudioCache: ignored
08-30 14:57:57.090   311  8172 V AudioCache: notify(0xb14324c0, 1, 0, 0)
08-30 14:57:57.091   311  8172 V AudioCache: prepared
08-30 14:57:57.091   311  2116 V AudioCache: wait - success
08-30 14:57:57.091   311  2116 V MediaPlayerService: start
08-30 14:57:57.091   311  2116 V AwesomePlayer: play_l() 
08-30 14:57:57.091   311  2116 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-30 14:57:57.091   311  2116 V AwesomePlayer: createAudioPlayer_l
08-30 14:57:57.091   311  2116 V AwesomePlayer: seekAudioIfNecessary_l() 
08-30 14:57:57.091   311  2116 V AwesomePlayer: startAudioPlayer_l() 
08-30 14:57:57.091   311  2116 D AudioPlayer: start of Playback, useOffload 0
08-30 14:57:57.091   311  2116 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 14:57:57.091   311  2116 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 14:57:57.092  8152  8152 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-30 14:57:57.094   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-30 14:57:57.094   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-30 14:57:57.094   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-30 14:57:57.094   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-30 14:57:57.094   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-30 14:57:57.094   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 14:57:57.094   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
08-30 14:57:57.094   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 14:57:57.094   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
08-30 14:57:57.094   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 14:57:57.094   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
08-30 14:57:57.094   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 14:57:57.094   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
,08-30 14:57:57.094   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 14:57:57.095   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-30 14:57:57.095   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 14:57:57.095   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-30 14:57:57.095   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-30 14:57:57.095   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
,08-30 14:57:57.095   311  8174 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 14:57:57.095   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 14:57:57.095   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-30 14:57:57.095   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-30 14:57:57.095   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port,
08-30 14:57:57.095   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f91a0 on output port
08-30 14:57:57.096   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-30 14:57:57.096   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-30 14:57:57.097   311  2116 V AudioCache: open(48000, 2, 0x0, 1, 4)
,08-30 14:57:57.097   311  2116 V AudioCache: notify(0xb14324c0, 6, 0, 0)
08-30 14:57:57.097   311  2116 V AudioCache: ignored
08-30 14:57:57.097   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.097   311  2116 V MediaPlayerService: wait for playback complete
,08-30 14:57:57.097   311  8176 V AudioCache: memcpy(0xac300000, 0xb17fe000, 4096)
08-30 14:57:57.098   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.098   311  8176 V AudioCache: memcpy(0xac301000, 0xb17fe000, 4096)
08-30 14:57:57.098   311  8176 V AudioCache: write(0xb17fe000, 4096)
,08-30 14:57:57.098   311  8176 V AudioCache: memcpy(0xac302000, 0xb17fe000, 4096)
08-30 14:57:57.099  8123  8123 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 14:57:57.099  8123  8123 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-30 14:57:57.101   311  8176 V AudioCache: write(0xb17fe000, 4096)
,08-30 14:57:57.101   311  8176 V AudioCache: memcpy(0xac303000, 0xb17fe000, 4096)
08-30 14:57:57.101   311  8176 V AudioCache: write(0xb17fe000, 4096),
08-30 14:57:57.101   311  8176 V AudioCache: memcpy(0xac304000, 0xb17fe000, 4096)
08-30 14:57:57.101   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.101   311  8176 V AudioCache: memcpy(0xac305000, 0xb17fe000, 4096)
08-30 14:57:57.101   311  8176 V AudioCache: write(0xb17fe000, 4096)
,08-30 14:57:57.101   311  8176 V AudioCache: memcpy(0xac306000, 0xb17fe000, 4096)
,08-30 14:57:57.102   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.102   311  8176 V AudioCache: memcpy(0xac307000, 0xb17fe000, 4096)
08-30 14:57:57.102   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.102   311  8176 V AudioCache: memcpy(0xac308000, 0xb17fe000, 4096)
08-30 14:57:57.102   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.102   311  8176 V AudioCache: memcpy(0xac309000, 0xb17fe000, 4096)
08-30 14:57:57.102   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.102   311  8176 V AudioCache: memcpy(0xac30a000, 0xb17fe000, 4096)
08-30 14:57:57.103   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.103   311  8176 V AudioCache: memcpy(0xac30b000, 0xb17fe000, 4096)
08-30 14:57:57.103   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.103   311  8176 V AudioCache: memcpy(0xac30c000, 0xb17fe000, 4096)
08-30 14:57:57.103  8123  8123 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9098
08-30 14:57:57.103   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.103   311  8176 V AudioCache: memcpy(0xac30d000, 0xb17fe000, 4096)
,08-30 14:57:57.104   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.104   311  8176 V AudioCache: memcpy(0xac30e000, 0xb17fe000, 4096)
08-30 14:57:57.104   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.104   311  8176 V AudioCache: memcpy(0xac30f000, 0xb17fe000, 4096)
08-30 14:57:57.105   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.105   311  8176 V AudioCache: memcpy(0xac310000, 0xb17fe000, 4096)
08-30 14:57:57.105   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.105   311  8176 V AudioCache: memcpy(0xac311000, 0xb17fe000, 4096)
08-30 14:57:57.105   311  8176 V AudioCache: write(0xb17fe000, 4096)
,08-30 14:57:57.105   311  8176 V AudioCache: memcpy(0xac312000, 0xb17fe000, 4096)
08-30 14:57:57.106   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.106   311  8176 V AudioCache: memcpy(0xac313000, 0xb17fe000, 4096)
08-30 14:57:57.106   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.106   311  8176 V AudioCache: memcpy(0xac314000, 0xb17fe000, 4096)
08-30 14:57:57.106   311  8176 V AudioCache: write(0xb17fe000, 4096)
,08-30 14:57:57.106   311  8176 V AudioCache: memcpy(0xac315000, 0xb17fe000, 4096)
08-30 14:57:57.107   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.107   311  8176 V AudioCache: memcpy(0xac316000, 0xb17fe000, 4096)
08-30 14:57:57.107   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.107   311  8176 V AudioCache: memcpy(0xac317000, 0xb17fe000, 4096)
08-30 14:57:57.107   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.107   311  8176 V AudioCache: memcpy(0xac318000, 0xb17fe000, 4096)
08-30 14:57:57.107  1035  1098 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-30 14:57:57.108   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.108   311  8176 V AudioCache: memcpy(0xac319000, 0xb17fe000, 4096)
08-30 14:57:57.108  1035  1098 I ActivityManager: Killing 6646:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-30 14:57:57.109   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.109   311  8176 V AudioCache: memcpy(0xac31a000, 0xb17fe000, 4096)
08-30 14:57:57.109   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.109   311  8176 V AudioCache: memcpy(0xac31b000, 0xb17fe000, 4096)
08-30 14:57:57.109   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.109   311  8176 V AudioCache: memcpy(0xac31c000, 0xb17fe000, 4096)
08-30 14:57:57.110   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.110   311  8176 V AudioCache: memcpy(0xac31d000, 0xb17fe000, 4096)
08-30 14:57:57.110   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.110   311  8176 V AudioCache: memcpy(0xac31e000, 0xb17fe000, 4096)
08-30 14:57:57.110  8056  8056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:57.110   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.110   311  8176 V AudioCache: memcpy(0xac31f000, 0xb17fe000, 4096)
08-30 14:57:57.111   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.111   311  8176 V AudioCache: memcpy(0xac320000, 0xb17fe000, 4096)
08-30 14:57:57.111   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.111   311  8176 V AudioCache: memcpy(0xac321000, 0xb17fe000, 4096)
08-30 14:57:57.112   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.112   311  8176 V AudioCache: memcpy(0xac322000, 0xb17fe000, 4096)
08-30 14:57:57.112   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.112   311  8176 V AudioCache: memcpy(0xac323000, 0xb17fe000, 4096)
08-30 14:57:57.112   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.112   311  8176 V AudioCache: memcpy(0xac324000, 0xb17fe000, 4096)
08-30 14:57:57.113   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.113   311  8176 V AudioCache: memcpy(0xac325000, 0xb17fe000, 4096)
08-30 14:57:57.113   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.113   311  8176 V AudioCache: memcpy(0xac326000, 0xb17fe000, 4096)
08-30 14:57:57.113   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.113   311  8176 V AudioCache: memcpy(0xac327000, 0xb17fe000, 4096)
08-30 14:57:57.114   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.114   311  8176 V AudioCache: memcpy(0xac328000, 0xb17fe000, 4096)
08-30 14:57:57.114   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.114   311  8176 V AudioCache: memcpy(0xac329000, 0xb17fe000, 4096)
08-30 14:57:57.114   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.114   311  8176 V AudioCache: memcpy(0xac32a000, 0xb17fe000, 4096)
08-30 14:57:57.115   311  8176 V AudioCache: write(0xb17fe000, 4096)
,08-30 14:57:57.115   311  8176 V AudioCache: memcpy(0xac32b000, 0xb17fe000, 4096),
08-30 14:57:57.115   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.115   311  8176 V AudioCache: memcpy(0xac32c000, 0xb17fe000, 4096)
08-30 14:57:57.117   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.117   311  8176 V AudioCache: memcpy(0xac32d000, 0xb17fe000, 4096)
,08-30 14:57:57.117   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.117   311  8176 V AudioCache: memcpy(0xac32e000, 0xb17fe000, 4096)
08-30 14:57:57.118   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.118   311  8176 V AudioCache: memcpy(0xac32f000, 0xb17fe000, 4096)
08-30 14:57:57.118   311  8176 V AudioCache: write(0xb17fe000, 4096),
08-30 14:57:57.118   311  8176 V AudioCache: memcpy(0xac330000, 0xb17fe000, 4096)
08-30 14:57:57.118   311  8176 V AudioCache: write(0xb17fe000, 4096)
08-30 14:57:57.118   311  8176 V AudioCache: memcpy(0xac331000, 0xb17fe000, 4096)
08-30 14:57:57.118   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
,08-30 14:57:57.119   311  8176 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 14:57:57.119   311  8176 V AwesomePlayer: postAudioEOS() 
08-30 14:57:57.119   311  8176 V AudioCache: write(0xb17fe000, 280)
08-30 14:57:57.119   311  8176 V AudioCache: memcpy(0xac332000, 0xb17fe000, 280)
,08-30 14:57:57.120   311  8172 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-30 14:57:57.120   311  8172 V AwesomePlayer: onStreamDone
08-30 14:57:57.120   311  8172 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-30 14:57:57.120   311  8172 V AudioCache: notify(0xb14324c0, 2, 0, 0)
08-30 14:57:57.120   311  8172 V AudioCache: playback complete,
08-30 14:57:57.120   311  8172 V AwesomePlayer: pause_l() 
08-30 14:57:57.120   311  8172 V AudioCache: notify(0xb14324c0, 7, 0, 0)
08-30 14:57:57.120   311  8172 V AudioCache: ignored
08-30 14:57:57.120   311  8172 V AwesomePlayer: cancelPlayerEvents,
08-30 14:57:57.120   311  2116 V AudioCache: wait - success
08-30 14:57:57.120   311  2116 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-30 14:57:57.120   311  8172 D AudioPlayer: Pause Playback at 1068125
08-30 14:57:57.121   311  2116 V AwesomePlayer: reset_l() ,
08-30 14:57:57.121   311  2116 V AudioCache: notify(0xb14324c0, 8, 0, 0)
08-30 14:57:57.121   311  2116 V AudioCache: ignored
08-30 14:57:57.121   311  2116 V AwesomePlayer: cancelPlayerEvents
08-30 14:57:57.121   311  2116 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
,08-30 14:57:57.121   311  2116 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-30 14:57:57.121   311  2116 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-30 14:57:57.121   311  2116 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-30 14:57:57.121   311  2116 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
,08-30 14:57:57.121   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 14:57:57.121   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 14:57:57.121   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-30 14:57:57.121   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
,08-30 14:57:57.121   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-30 14:57:57.121   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7830 on port 0
08-30 14:57:57.121   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-30 14:57:57.121   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f77e0 on port 0,
08-30 14:57:57.121   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-30 14:57:57.121   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7790 on port 0
08-30 14:57:57.121   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
,08-30 14:57:57.121   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 14:57:57.121   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57f91a0 on port 1
08-30 14:57:57.121   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-30 14:57:57.121   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
,08-30 14:57:57.121   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-30 14:57:57.121   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
08-30 14:57:57.121   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
,08-30 14:57:57.121   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
08-30 14:57:57.121   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-30 14:57:57.121   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-30 14:57:57.121   311  2116 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
,08-30 14:57:57.121   311  2116 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!,
08-30 14:57:57.121   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-30 14:57:57.121   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
,08-30 14:57:57.121   311  8174 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-30 14:57:57.121   311  2116 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 14:57:57.121   311  2116 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-30 14:57:57.122   311  2116 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1,
08-30 14:57:57.122   311  2116 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-30 14:57:57.122   311  2116 D AudioPlayer: AudioPlayer releasing audio source
08-30 14:57:57.122   311  2116 D AudioPlayer: AudioPlayer done releasing audio source
,08-30 14:57:57.122   311  2116 V AwesomePlayer: reset_l() 
08-30 14:57:57.122   311  2116 V AwesomePlayer: cancelPlayerEvents
08-30 14:57:57.122   311  2116 V AwesomePlayer: ~AwesomePlayer call
08-30 14:57:57.122   311  2116 V AwesomePlayer: reset_l() 
,08-30 14:57:57.122   311  2116 V AwesomePlayer: cancelPlayerEvents
08-30 14:57:57.123  8123  8171 V SoundPool: close(31)
08-30 14:57:57.123  8123  8171 V SoundPool: pointer = 0x9fffb000, size = 205080, sampleRate = 48000, numChannels = 2
08-30 14:57:57.144  1035  1559 I WindowState: WIN DEATH: Window{3b415f71 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 14:57:57.144  1035  1528 D WifiService: Client connection lost with reason: 4
08-30 14:57:57.150  1035  1559 D InputDispatcher: Window went away: Window{3b415f71 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 14:57:57.288  7557  7557 I UEI.SmartControl: Supports setup maps: true
,08-30 14:57:57.290  7557  7557 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 14:57:57.290  7557  7557 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 14:57:57.290  7557  7557 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-30 14:57:57.290  7557  7557 I UEI.SmartControl: ### init IR Blaster...
,08-30 14:57:57.294  7557  7557 D serial_port: Configuring serial port
08-30 14:57:57.296  7557  7557 E UEI.SmartControl: UEIBLaster setting for 616
08-30 14:57:57.296  7557  7557 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 14:57:57.296  7557  7557 I UEI.SmartControl: configuring settings for MAXQ616
08-30 14:57:57.296  7557  7557 I UEI.SmartControl: Get version...
08-30 14:57:57.311  7557  8179 D UEI.SmartControl: serial port data available: 21
,08-30 14:57:57.320  1035  1098 I ActivityManager:   Force finishing activity ActivityRecord{2716b582 u0 com.test.thalitest/.MainActivity t6}
,08-30 14:57:57.338  7557  7557 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-30 14:57:57.338  7557  7557 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 14:57:57.338  7557  7557 I UEI.SmartControl: QS saving settings...
08-30 14:57:57.340   337   348 E GBMv2   : DFP En is all cleared set to be enabled
08-30 14:57:57.341  7557  7557 D UEI.SmartControl: IR Blaster version: 25672567
08-30 14:57:57.343  1035  2034 W ActivityManager: Spurious death for ProcessRecord{25760577 6646:com.test.thalitest/u0a118}, curProc for 6646: null
08-30 14:57:57.344  8056  8056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:57.345  1925  2921 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-30 14:57:57.345  1925  2921 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2adbc834 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 14:57:57.345  1035  1123 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-30 14:57:57.348  1925  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-30 14:57:57.348  1035  1123 I ActivityManager:   Force finishing activity ActivityRecord{2716b582 u0 com.test.thalitest/.MainActivity t6 f}
08-30 14:57:57.349  1925  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2cc465d co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 14:57:57.350  1035  1123 W ActivityManager: Duplicate finish request for ActivityRecord{2716b582 u0 com.test.thalitest/.MainActivity t6 f}
,08-30 14:57:57.358  7557  8179 D UEI.SmartControl: serial port data available: 4
,08-30 14:57:57.381  2017  2017 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-30 14:57:57.383  2017  2017 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-30 14:57:57.395  7631  7631 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-30 14:57:57.395  7631  7631 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 14:57:57.396  1587  1587 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-30 14:57:57.400  3725  3725 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-30 14:57:57.400  1980  1980 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-30 14:57:57.409  7557  7557 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 14:57:57.409  7557  8182 I UEI.SmartControl: Device manager: loading config....
08-30 14:57:57.410  7557  8182 D UEI.SmartControl: ----------- loading internal config...
,08-30 14:57:57.415  7557  8182 E UEI.SmartControl: Loading SETTINGS...
08-30 14:57:57.418  1035  1439 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-30 14:57:57.420  7557  8182 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-30 14:57:57.425  1035  1523 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 14:57:57.425  1035  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 14:57:57.426  1035  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 14:57:57.426  1035  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 14:57:57.426  4583  4583 I art     : Explicit concurrent mark sweep GC freed 8191(470KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 742us total 57.633ms
08-30 14:57:57.426  1035  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 14:57:57.427  1035  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 14:57:57.428  1035  1529 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-30 14:57:57.428  1035  1529 D ConnectivityService: identical MTU - not setting
08-30 14:57:57.428  1035  1529 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 14:57:57.428  1035  1529 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 14:57:57.428  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 14:57:57.428  1035  1529 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:57:57.429  1035  1529 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 14:57:57.433  1587  2055 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-30 14:57:57.434  7557  8181 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 14:57:57.434  7557  8181 D UEI.SmartControl: -----service ready thread exits
,08-30 14:57:57.461  1035  1874 V SIM_STK : Menu title from STK is T-Mobile
,08-30 14:57:57.484  4474  4474 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-30 14:57:57.484  4474  4474 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-30 14:57:57.485  4474  4474 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-30 14:57:57.485  4474  4474 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-30 14:57:57.485  4474  4474 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
,08-30 14:57:57.486  4474  4474 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 14:57:57.486  4474  4474 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 14:57:57.486  4474  4474 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 14:57:57.486  4474  4474 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 14:57:57.486  4474  4474 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 14:57:57.486  4474  4474 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 14:57:57.486  4474  4474 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 14:57:57.494  8056  8056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:57.498  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,08-30 14:57:57.502  2017  2109 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-30 14:57:57.504  1035  1035 D administrator: Handling package changes for user 0
08-30 14:57:57.505  2489  2668 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 14:57:57.507  7557  7557 E UEI.SmartControl: Services init done
08-30 14:57:57.507  7557  7557 D UEI.SmartControl: QS Service init finished
08-30 14:57:57.532  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-30 14:57:57.533  1890  1890 D ActionManagerService: notifyUserLog: 1000003
,08-30 14:57:57.533  3725  4472 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-30 14:57:57.537  2017  2017 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-30 14:57:57.539  2017  2017 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-30 14:57:57.540  2017  2017 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,08-30 14:57:57.542  1587  1587 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-30 14:57:57.544  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-30 14:57:57.544  1890  1890 D ActionManagerService: notifyUserLog: 1000004
08-30 14:57:57.544  3725  4472 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-30 14:57:57.545  3725  4470 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 14:57:57.547  7557  7557 D UEI.SmartControl: QS Service version name: 2.1.91
,08-30 14:57:57.547  7557  7557 D UEI.SmartControl: QS Service version code: 201091
08-30 14:57:57.547  7557  7557 D UEI.SmartControl: Service requested: Control
08-30 14:57:57.548  8056  8056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 14:57:57.561  1587  1587 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-30 14:57:57.561  1587  1587 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-30 14:57:57.582  8056  8056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 14:57:57.584  8123  8123 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-30 14:57:57.584  7557  7557 D UEI.SmartControl: Internal service binding...
08-30 14:57:57.585  7557  7572 I UEI.SmartControl: ------ IControl API: 11
08-30 14:57:57.585  7557  7572 D UEI.SmartControl: File observer start...
08-30 14:57:57.585  7557  7572 E UEI.SmartControl: IR Port is disabled: false
08-30 14:57:57.585  7557  7572 D UEI.SmartControl: Starting file observer...
08-30 14:57:57.585  7557  7572 I UEI.SmartControl: Registering callback...
08-30 14:57:57.586  7557  7573 I UEI.SmartControl: ------ IControl API: 19
08-30 14:57:57.587  7557  7573 I UEI.SmartControl: Registering Services Ready callback...
08-30 14:57:57.587  7557  7573 I UEI.SmartControl: Notify client services are ready...
08-30 14:57:57.587  8123  8139 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-30 14:57:57.588  8123  8168 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-30 14:57:57.588  8123  8168 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-30 14:57:57.588  8123  8123 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-30 14:57:57.588  8123  8123 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-30 14:57:57.589  7557  7572 I UEI.SmartControl: ------ IControl API: 8
08-30 14:57:57.590  8123  8123 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-30 14:57:57.590  8123  8123 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-30 14:57:57.590  8123  8123 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-30 14:57:57.591  8123  8123 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-30 14:57:57.591  8123  8123 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-30 14:57:57.592  8123  8123 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-30 14:57:57.598  1035  2016 V SIM_STK : Menu title from STK is T-Mobile
,08-30 14:57:57.598  1035  2016 V SIM_STK : Menu title from STK is T-Mobile
08-30 14:57:57.603  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-30 14:57:57.603  2017  2017 I GBoardWebViewUtils: , create_time: 1430832262123
08-30 14:57:57.603  2017  2017 I GBoardWebViewUtils: , expire_time: 0
08-30 14:57:57.603  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-30 14:57:57.603  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-30 14:57:57.603  2017  2017 I GBoardWebViewUtils: , display: false
08-30 14:57:57.603  2017  2017 I GBoardWebViewUtils: , animation: false }
08-30 14:57:57.603  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-30 14:57:57.603  2017  2017 I GBoardWebViewUtils: , create_time: 1430832262287
08-30 14:57:57.603  2017  2017 I GBoardWebViewUtils: , expire_time: 0
08-30 14:57:57.603  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 14:57:57.603  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 14:57:57.603  2017  2017 I GBoardWebViewUtils: , display: false
08-30 14:57:57.603  2017  2017 I GBoardWebViewUtils: , animation: false }
08-30 14:57:57.603  2017  2017 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-30 14:57:57.603  2017  2017 I GBoardWebViewUtils: , create_time: 1472216588858
08-30 14:57:57.603  2017  2017 I GBoardWebViewUtils: , expire_time: 0
08-30 14:57:57.603  2017  2017 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 14:57:57.603  2017  2017 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 14:57:57.603  2017  2017 I GBoardWebViewUtils: , display: false
08-30 14:57:57.603  2017  2017 I GBoardWebViewUtils: , animation: false }
08-30 14:57:57.607  1852  1852 D SplitUIManager: split_name #11 / not available #0
08-30 14:57:57.607  1852  1852 D SplitUIService: removed split : 
08-30 14:57:57.613  8056  8056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 14:57:57.613  1035  1097 W InputMethodInfo: Duplicated subtype definition found: , voice
08-30 14:57:57.619  8123  8123 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-30 14:57:57.637  1587  1646 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 14:57:57.637  1587  1646 D KeyguardModel: createShortcutInfo...
08-30 14:57:57.637  8123  8123 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-30 14:57:57.649  1587  1646 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 14:57:57.650  1587  1646 D KeyguardModel: createShortcutInfo...
08-30 14:57:57.653  8056  8056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:57.654  2017  8185 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-30 14:57:57.655  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-30 14:57:57.655  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 14:57:57.656  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 14:57:57.656  1852  1852 D SplitUIManager: split_name #11 / not available #0
08-30 14:57:57.656  1852  1852 I SplitUIService: split app #11
08-30 14:57:57.657  8056  8056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:57.658  1587  1646 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 14:57:57.658  1587  1646 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 14:57:57.658  1587  1646 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 14:57:57.659  1587  1646 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 14:57:57.660  8056  8056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:57.661  1035  1562 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-30 14:57:57.663  1587  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 14:57:57.663  1587  1646 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 14:57:57.664  1035  1908 V SIM_STK : Menu title from STK is T-Mobile
08-30 14:57:57.664  8056  8056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 14:57:57.665  1587  1646 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 14:57:57.665  1587  1646 D KeyguardModel: createShortcutInfo...
08-30 14:57:57.667  8056  8056 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-30 14:57:57.669  1587  1646 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 14:57:57.669  1587  1646 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 14:57:57.670  1587  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 14:57:57.670  1587  1646 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 14:57:57.672  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 14:57:57.672  1800  1800 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-30 14:57:57.673  2017  2017 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-30 14:57:57.682  1035  1936 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-30 14:57:57.684  2169  2169 I ConfigService: onCreate
08-30 14:57:57.685  7631  7631 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 14:57:57.685  2169  2169 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-30 14:57:57.685  7631  7631 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 14:57:57.685  7631  7631 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 14:57:57.685  7631  7631 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 14:57:57.685  7631  7631 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 14:57:57.685  7631  7631 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 14:57:57.685  7631  7631 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 14:57:57.685  7631  7631 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 14:57:57.685  7631  7631 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 14:57:57.685  7631  7631 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 14:57:57.685  7631  7631 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 14:57:57.686  1800  1800 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-30 14:57:57.686  1587  1646 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 14:57:57.686  1587  1646 D KeyguardModel: createShortcutInfo...
08-30 14:57:57.691  2169  2169 I ConfigService: onBind returning update interface
08-30 14:57:57.691  1587  1646 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 14:57:57.691  1587  1646 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 14:57:57.691  1587  1646 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 14:57:57.692  1587  1646 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 14:57:57.692  2169  2169 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-30 14:57:57.692  2169  2169 I ConfigService: onBind returning config service
08-30 14:57:57.694  1587  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 14:57:57.694  1587  1646 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-30 14:57:57.698  1587  1646 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 14:57:57.698  1587  1646 D KeyguardModel: createShortcutInfo...
08-30 14:57:57.701  2169  2169 I ConfigService: onDestroy
08-30 14:57:57.701  1587  1587 D KeyguardModel: handleShortcutListChanged...
08-30 14:57:57.701  1587  1587 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-30 14:57:57.705  1587  1646 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 14:57:57.705  1587  1646 D KeyguardModel: createShortcutInfo...
08-30 14:57:57.708  1587  1646 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 14:57:57.708  1587  1646 D KeyguardModel: createShortcutInfo...
,08-30 14:57:57.709  1587  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 14:57:57.709  1587  1646 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 14:57:57.711  1587  1646 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 14:57:57.711  1587  1646 D KeyguardModel: createShortcutInfo...
08-30 14:57:57.715  1800  8188 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-30 14:57:57.715  1587  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 14:57:57.716  1587  1646 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 14:57:57.717  1587  1646 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 14:57:57.717  1587  1646 D KeyguardModel: createShortcutInfo...
08-30 14:57:57.718  1587  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 14:57:57.718  1587  1646 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 14:57:57.720  1587  1646 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 14:57:57.720  1587  1646 D KeyguardModel: createShortcutInfo...
,08-30 14:57:57.735  2017  2017 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-30 14:57:57.742  1587  1587 D KeyguardModel: handleShortcutListChanged...
08-30 14:57:57.742  1587  1587 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-30 14:57:57.768  5944  8194 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-30 14:57:57.775  1800  8195 I PeopleContactsSync: CP2 sync disabled
08-30 14:57:57.778  2017  2031 I art     : Background partial concurrent mark sweep GC freed 7079(323KB) AllocSpace objects, 6(19MB) LOS objects, 34% free, 60MB/92MB, paused 5.405ms total 52.128ms
08-30 14:57:57.779  1800  4670 I Icing   : doRemovePackageData com.test.thalitest
,08-30 14:57:57.797  1800  8193 W GmsApplication: Using Auth Proxy for data requests.
,08-30 14:57:57.802  1800  8193 W GmsApplication: Using Auth Proxy for data requests.
,08-30 14:57:57.829  6959  6959 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-30 14:57:57.840  1035  1874 I ActivityManager: Killing 7177:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-30 14:57:57.841  2169  2349 I art     : Explicit concurrent mark sweep GC freed 7924(460KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 409us total 17.331ms
08-30 14:57:57.855   322   409 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-30 14:57:57.855  3188  8198 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-30 14:57:57.857  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-30 14:57:57.859  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 14:57:57.861  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-30 14:57:57.863  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-30 14:57:57.863  1035  1123 I art     : Explicit concurrent mark sweep GC freed 85663(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 2.751ms total 295.205ms
08-30 14:57:57.864  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-30 14:57:57.865  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-30 14:57:57.883  2017  2164 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-30 14:57:57.883  2017  2164 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-30 14:57:57.884  8152  8152 D AndroidRuntime: Shutting down VM
08-30 14:57:57.885  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-30 14:57:57.885  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 14:57:57.899  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-30 14:57:57.899  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 14:57:57.900  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 14:57:57.906  2017  2017 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-30 14:57:57.923  1035  1969 W libprocessgroup: failed to open /acct/uid_10005/pid_7177/cgroup.procs: No such file or directory
08-30 14:57:57.923  2563  2563 D [Concierge]Service: onStartCommand(). Type : 8
08-30 14:57:57.923  2563  2563 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,08-30 14:57:57.925  2563  2563 D [Concierge]Service: Update widget ID : 11
08-30 14:57:57.926  2017  2017 D [Concierge]WidgetView: change position of spinner
08-30 14:57:57.927  2563  2563 D [Concierge]Service: onStartCommand(). Type : 0
08-30 14:57:57.927  1035  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1a7f271b u0 com.lge.launcher2/.Launcher t5} time:200815
08-30 14:57:57.929  2017  2017 I [Concierge]WidgetView: initWebView(). Time : 1472561877929
08-30 14:57:57.932  2331  8201 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-30 14:57:57.957  1035  2034 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8202 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 14:57:57.983  2017  2017 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 509041484
08-30 14:57:57.984  2017  2017 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-30 14:57:57.984  2017  2017 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-30 14:57:57.987  2017  2017 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@39972259
08-30 14:57:57.987  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-30 14:57:57.988  1035  1097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 14:57:57.989  2017  2017 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 14:57:57.989  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 14:57:57.994  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,08-30 14:57:57.995  2017  2017 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-30 14:57:57.995  2017  2017 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 14:57:57.995  2017  2017 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472561705334, New one : 1472561877929
08-30 14:57:57.995  2017  2017 D [Concierge]WidgetView: Unregister all receivers
08-30 14:57:57.995  2017  2017 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 14:57:57.996  8202  8202 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 14:57:57.996  8202  8202 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 14:57:57.996  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 14:57:57.997  8202  8202 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 14:57:57.997  8202  8202 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 14:57:57.998  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-30 14:57:57.999  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-30 14:57:58.000  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-30 14:57:58.001  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-30 14:57:58.002  1035  1097 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-30 14:57:58.002  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-30 14:57:58.006  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 14:57:58.006  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 14:57:58.037  2017  2017 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-30 14:57:58.045  2017  2017 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,08-30 14:57:58.045  2017  2017 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-30 14:57:58.046  2017  2017 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-30 14:57:58.048  2017  2017 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 14:57:58.067  2017  2017 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@134c8641 time:200954
,08-30 14:57:58.074  8202  8202 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-30 14:57:58.086  8202  8202 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-30 14:57:58.108  8202  8202 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 14:57:58.123  1035  1123 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8221 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-30 14:57:58.144  8202  8202 D LgDataFeature: LgDataFeature() Constructor: none
08-30 14:57:58.144  8202  8202 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 14:57:58.166  1035  1050 I ActivityManager: Killing 7658:com.google.android.talk/u0a72 (adj 15): empty #17
,08-30 14:57:58.208  2017  2017 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-30 14:57:58.243  1035  1770 W libprocessgroup: failed to open /acct/uid_10072/pid_7658/cgroup.procs: No such file or directory
08-30 14:57:58.243  2017  2854 I GBoardtInterface: onReloaded()
,08-30 14:57:58.245  2017  2017 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-30 14:57:58.246  3725  4470 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 14:57:58.250  3725  3741 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 14:57:58.256  1890  1890 D ActionManagerService: notifyUserLog: 1000001
08-30 14:57:58.257  3725  4472 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 14:57:58.257  3725  4472 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,08-30 14:57:58.260  1890  1890 D ActionManagerService: notifyUserLog: 1000001
08-30 14:57:58.261  3725  4472 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 14:57:58.261  3725  4472 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-30 14:57:58.261  3725  4472 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-30 14:57:58.261  3725  4472 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-30 14:57:58.262  3725  4470 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 14:57:58.264  2017  2017 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-30 14:57:58.264  2017  2017 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-30 14:57:58.265  2017  2017 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-30 14:57:58.265  2017  2017 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 14:57:58.267  2017  2017 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-30 14:57:58.267  2017  2017 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 14:57:58.279  8202  8202 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)

```
