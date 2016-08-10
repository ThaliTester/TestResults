#### Test 797638305e9d4c1_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-10 15:48:00.103  1586  1586 I [SystemUI]Clock: called onTimeUpdated()
08-10 15:48:00.113  1586  1586 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 15:48:00.113  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
08-10 15:48:00.115  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
08-10 15:48:00.117  1586  1586 D KeyguardUpdateMonitor: handleTimeUpdate
,08-10 15:48:05.840  6760  6760 D AndroidRuntime: 
08-10 15:48:05.840  6760  6760 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-10 15:48:05.846  6760  6760 D AndroidRuntime: CheckJNI is OFF
08-10 15:48:06.047  6760  6760 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-10 15:48:06.058  1036  2017 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-10 15:48:06.073  1927  1942 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-10 15:48:06.078  1036  2017 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-10 15:48:06.080  1036  2017 D ActivityManager: setTaskToReturnTo : TaskRecord{b16d918 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-10 15:48:06.080  1036  2017 D ActivityManager: setTaskToReturnTo : TaskRecord{b16d918 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-10 15:48:06.081  1036  2017 D WindowStateEx: AppWindowTokenEx init.. 
08-10 15:48:06.082   344   385 E GBMv2   : DFP En is all cleared set to be enabled
08-10 15:48:06.111  1036  2017 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6775 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-10 15:48:06.113  6760  6760 D AndroidRuntime: Shutting down VM
08-10 15:48:06.165  1927  3961 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-10 15:48:06.165  1927  3961 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3ed5b9cc co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-10 15:48:06.166  1927  1943 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-10 15:48:06.166  1927  1943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1f647415 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-10 15:48:06.223  6775  6775 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-10 15:48:06.333  6775  6775 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-10 15:48:06.342  6775  6775 I LibraryLoader: Loading: webviewchromium
08-10 15:48:06.345  6775  6775 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 149-154)
08-10 15:48:06.345  6775  6775 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-10 15:48:06.362  6775  6775 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4459d5a}
,08-10 15:48:06.363  6775  6775 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 15:48:06.364  6775  6775 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-10 15:48:06.374  6775  6775 I BrowserStartupController: Initializing chromium process, renderers=0
08-10 15:48:06.375  6775  6775 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-10 15:48:06.386  6775  6775 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-10 15:48:06.387  6775  6775 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-10 15:48:06.387  6775  6775 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-10 15:48:06.388   317  2153 V AudioPolicyService: registerClient() client 0xb558ad60, uid 10118
08-10 15:48:06.392  1036  1118 D BluetoothManagerService: Message: 20
08-10 15:48:06.392  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27bf6ce2:true
,08-10 15:48:06.407  6775  6775 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 15:48:06.407  6775  6775 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 15:48:06.407  6775  6775 I Adreno-EGL: Build Date: 12/12/14 금
08-10 15:48:06.407  6775  6775 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 15:48:06.407  6775  6775 I Adreno-EGL: Remote Branch: 
08-10 15:48:06.407  6775  6775 I Adreno-EGL: Local Patches: 
08-10 15:48:06.407  6775  6775 I Adreno-EGL: Reconstruct Branch: 
,08-10 15:48:06.480  6775  6809 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-10 15:48:06.485  6775  6775 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-10 15:48:06.502  6775  6775 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-10 15:48:06.507  6775  6775 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-10 15:48:06.510  6775  6775 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-10 15:48:06.513  6775  6775 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-10 15:48:06.513  6775  6775 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-10 15:48:06.527  6775  6775 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-10 15:48:06.534  6775  6775 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-10 15:48:06.534  6775  6775 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-10 15:48:06.610  6775  6819 D LgDataFeature: LgDataFeature() Constructor: none
08-10 15:48:06.611  6775  6819 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 15:48:06.660  1036  1051 I art     : Explicit concurrent mark sweep GC freed 27711(1296KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.887ms total 98.082ms
,08-10 15:48:06.664  1036  1099 W ActivityManager: Activity pause timeout for ActivityRecord{2f6fef71 u0 com.test.thalitest/.MainActivity t6}
08-10 15:48:06.670  6775  6826 D OpenGLRenderer: Render dirty regions requested: true
08-10 15:48:06.670  6775  6826 I OpenGLRenderer: Initialized EGL, version 1.4
08-10 15:48:06.676  6775  6826 D OpenGLRenderer: Enabling debug mode 0
,08-10 15:48:06.685  6775  6775 D Atlas   : Validating map...
08-10 15:48:06.689  1036  2018 D SplitWindow: check instance of lgWin Window{9538a8c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-10 15:48:06.782  1036  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +618ms (total +698ms)
,08-10 15:48:06.784  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2f6fef71 u0 com.test.thalitest/.MainActivity t6} time:180593
08-10 15:48:06.785  6775  6775 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@7a58bf1 time:180593
08-10 15:48:06.885  6775  6775 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-10 15:48:06.885  6775  6775 I chromium: 
,08-10 15:48:06.895  6775  6775 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-10 15:48:07.036  6775  6831 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435177984
,08-10 15:48:07.057  6775  6831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-10 15:48:07.057  6775  6831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-10 15:48:07.057  6775  6831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-10 15:48:07.057  6775  6831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-10 15:48:07.057  6775  6831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-10 15:48:07.058  6775  6831 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@139cbde5 added. We now have 1 listener(s)
08-10 15:48:07.071  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-10 15:48:07.074  6775  6831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-10 15:48:07.075  6775  6831 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 15:48:07.077  6775  6831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 15:48:07.077  6775  6831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 15:48:07.085  6775  6831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-10 15:48:07.085  6775  6831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-10 15:48:07.085  6775  6831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-10 15:48:07.085  6775  6831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-10 15:48:07.085  6775  6831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-10 15:48:07.085  6775  6831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-10 15:48:07.085  6775  6831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-10 15:48:07.085  6775  6831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-10 15:48:07.085  6775  6831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-10 15:48:07.085  6775  6831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-10 15:48:07.085  6775  6831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-10 15:48:07.085  6775  6831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-10 15:48:07.085  6775  6831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-10 15:48:07.085  6775  6831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-10 15:48:07.085  6775  6831 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@191b96c8 added. We now have 1 listener(s)
,08-10 15:48:07.086  6775  6831 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 15:48:07.090  1036  1528 D WifiService: New client listening to asynchronous messages
08-10 15:48:07.094  6775  6831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 15:48:07.095  6775  6831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-10 15:48:07.095  6775  6831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-10 15:48:07.095  6775  6831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-10 15:48:07.096  6775  6831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-10 15:48:07.099  6775  6831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 15:48:07.100  1036  1712 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-10 15:48:07.102  6775  6831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-10 15:48:07.111  6775  6831 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-10 15:48:07.112  6775  6831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 15:48:07.112  6775  6831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:48:07.112  6775  6831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 15:48:07.112  6775  6831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 15:48:07.112  6775  6831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 15:48:07.112  6775  6831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 15:48:07.112  6775  6831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 15:48:07.112  6775  6831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 15:48:07.112  6775  6831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-10 15:48:07.112  6775  6831 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 15:48:07.115  6775  6775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 15:48:07.117  6775  6775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 15:48:07.118  6775  6831 I io.jxcore.node.LifeCycleMonitor: start: OK
08-10 15:48:07.172  6775  6819 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-10 15:48:07.172  6775  6819 I chromium: 
,08-10 15:48:07.237  6775  6775 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-10 15:48:08.039   344   387 E GBMv2   : DFP En is all cleared set to be enabled
08-10 15:48:08.039   344   387 E GBMv2   : Set value is all cleared set the max
08-10 15:48:08.039   344   387 I GBMv2   : DFP Enabled. Ignore VFP set
,08-10 15:48:08.088  6775  6834 W jxcore-log: Initializing JXcore engine
08-10 15:48:08.088  6775  6834 W jxcore-log: JXcore engine is ready
,08-10 15:48:08.152  6834  6834 W Thread-771: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7561]" dev="sockfs" ino=7561 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-10 15:48:08.152  6834  6834 W Thread-771: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-10 15:48:08.152  6834  6834 W Thread-771: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9964]" dev="sockfs" ino=9964 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-10 15:48:08.152  6834  6834 W Thread-771: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-10 15:48:08.152  6834  6834 W Thread-771: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[32570]" dev="sockfs" ino=32570 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-10 15:48:08.191  6775  6834 W jxcore-log: Starting JXcore engine
,08-10 15:48:08.346  6775  6834 W jxcore-log: Platform android
08-10 15:48:08.346  6775  6834 W jxcore-log: 
08-10 15:48:08.346  6775  6834 W jxcore-log: Process ARCH arm
08-10 15:48:08.346  6775  6834 W jxcore-log: 
,08-10 15:48:08.693  6775  6834 I jxcore-log: JXcore Cordova bridge is ready!
08-10 15:48:08.693  6775  6834 I jxcore-log: 
08-10 15:48:08.693  6775  6834 W jxcore-log: JXcore engine is started
,08-10 15:48:08.704  6775  6831 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-10 15:48:08.708  6775  6775 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-10 15:48:18.636  6775  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-10 15:48:18.636  6775  6834 I jxcore-log: 
,08-10 15:48:18.638  6775  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-10 15:48:18.638  6775  6834 I jxcore-log: 
,08-10 15:48:18.643  6775  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 15:48:18.643  6775  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:48:18.643  6775  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 15:48:18.643  6775  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 15:48:18.643  6775  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 15:48:18.643  6775  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 15:48:18.643  6775  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 15:48:18.643  6775  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 15:48:18.645  6775  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 15:48:18.647  6775  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-10 15:48:18.647  6775  6834 I jxcore-log: 
08-10 15:48:18.649  6775  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-10 15:48:18.649  6775  6834 I jxcore-log: 
,08-10 15:48:18.970  6775  6834 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-10 15:48:18.970  6775  6834 I jxcore-log: Failed to execute UT.
08-10 15:48:18.970  6775  6834 I jxcore-log: 
08-10 15:48:18.970  6775  6834 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-10 15:48:18.970  6775  6834 I jxcore-log: 
,08-10 15:48:18.975  6775  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 15:48:18.975  6775  6834 I jxcore-log: 
08-10 15:48:18.992  6775  6775 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-10 15:48:19.337  6835  6835 D AndroidRuntime: 
08-10 15:48:19.337  6835  6835 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-10 15:48:19.344  6835  6835 D AndroidRuntime: CheckJNI is OFF
08-10 15:48:19.552  6835  6835 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-10 15:48:19.569  1036  1099 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-10 15:48:19.573  1036  1099 I ActivityManager: Killing 6775:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-10 15:48:19.636  1036  1052 I WindowState: WIN DEATH: Window{9538a8c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-10 15:48:19.642  1036  1528 D WifiService: Client connection lost with reason: 4
08-10 15:48:19.646  1036  1052 D InputDispatcher: Window went away: Window{9538a8c u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-10 15:48:19.704  1036  1099 I ActivityManager:   Force finishing activity ActivityRecord{2f6fef71 u0 com.test.thalitest/.MainActivity t6}
,08-10 15:48:19.778   344   385 E GBMv2   : DFP En is all cleared set to be enabled
,08-10 15:48:19.782  1036  1908 W ActivityManager: Spurious death for ProcessRecord{26bf0442 6775:com.test.thalitest/u0a118}, curProc for 6775: null
08-10 15:48:19.783  1036  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-10 15:48:19.784  1036  1124 I ActivityManager:   Force finishing activity ActivityRecord{2f6fef71 u0 com.test.thalitest/.MainActivity t6 f}
08-10 15:48:19.784  1036  1124 W ActivityManager: Duplicate finish request for ActivityRecord{2f6fef71 u0 com.test.thalitest/.MainActivity t6 f}
,08-10 15:48:19.817  2019  2019 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-10 15:48:19.818  2019  2019 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-10 15:48:19.820  1927  3961 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-10 15:48:19.821  1927  3961 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1662032a co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-10 15:48:19.822  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-10 15:48:19.822  2019  2112 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-10 15:48:19.823  1927  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-10 15:48:19.824  1927  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{12e551b co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-10 15:48:19.836  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-10 15:48:19.836  1891  1891 D ActionManagerService: notifyUserLog: 1000003
08-10 15:48:19.836  3831  4514 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-10 15:48:19.838  1586  1586 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-10 15:48:19.853  1981  1981 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-10 15:48:19.853  3893  3893 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-10 15:48:19.853  3893  3893 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-10 15:48:19.864  4629  4629 I art     : Explicit concurrent mark sweep GC freed 453(29KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 556us total 59.535ms
08-10 15:48:19.864  3831  3831 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-10 15:48:19.866  2461  2614 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-10 15:48:19.895  1036  1367 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-10 15:48:19.916  4526  4526 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-10 15:48:19.917  4526  4526 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-10 15:48:19.917  4526  4526 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-10 15:48:19.917  4526  4526 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-10 15:48:19.917  4526  4526 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 15:48:19.917  4526  4526 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 15:48:19.917  4526  4526 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-10 15:48:19.917  4526  4526 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-10 15:48:19.917  4526  4526 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 15:48:19.917  4526  4526 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 15:48:19.917  4526  4526 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-10 15:48:19.917  4526  4526 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-10 15:48:19.920  2019  2019 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-10 15:48:19.921  2019  2019 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-10 15:48:19.922  6456  6456 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-10 15:48:19.934  1036  1098 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-10 15:48:19.946  1586  1644 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-10 15:48:19.946  1586  1644 D KeyguardModel: createShortcutInfo...
08-10 15:48:19.946  2019  2019 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-10 15:48:19.946  1586  1586 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-10 15:48:19.949  1586  1644 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-10 15:48:19.949  1586  1644 D KeyguardModel: createShortcutInfo...
08-10 15:48:19.950  1891  1891 D ActionManagerService: notifyUserLog: 1000004
08-10 15:48:19.951  1803  1803 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-10 15:48:19.951  3831  4514 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-10 15:48:19.957  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-10 15:48:19.958  3831  4500 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-10 15:48:19.959  1586  1644 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-10 15:48:19.959  1586  1644 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 15:48:19.959  1586  1644 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-10 15:48:19.963  1586  1644 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-10 15:48:19.963  1586  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 15:48:19.963  1586  1644 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-10 15:48:19.972  1586  1586 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-10 15:48:19.972  1586  1586 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-10 15:48:19.974  2176  2176 I ConfigService: onCreate
08-10 15:48:19.974  2176  2176 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-10 15:48:19.975  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-10 15:48:19.975  2019  2019 I GBoardWebViewUtils: , create_time: 1430832262123
08-10 15:48:19.975  2019  2019 I GBoardWebViewUtils: , expire_time: 0
08-10 15:48:19.975  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-10 15:48:19.975  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-10 15:48:19.975  2019  2019 I GBoardWebViewUtils: , display: false
08-10 15:48:19.975  2019  2019 I GBoardWebViewUtils: , animation: false }
08-10 15:48:19.975  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-10 15:48:19.975  2019  2019 I GBoardWebViewUtils: , create_time: 1430832262287
08-10 15:48:19.975  2019  2019 I GBoardWebViewUtils: , expire_time: 0
08-10 15:48:19.975  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-10 15:48:19.975  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-10 15:48:19.975  2019  2019 I GBoardWebViewUtils: , display: false
08-10 15:48:19.975  2019  2019 I GBoardWebViewUtils: , animation: false }
08-10 15:48:19.975  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1470393742816
08-10 15:48:19.975  2019  2019 I GBoardWebViewUtils: , create_time: 1470393743569
08-10 15:48:19.975  2019  2019 I GBoardWebViewUtils: , expire_time: 0
08-10 15:48:19.975  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-10 15:48:19.975  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-10 15:48:19.975  2019  2019 I GBoardWebViewUtils: , display: false
08-10 15:48:19.975  2019  2019 I GBoardWebViewUtils: , animation: false }
08-10 15:48:19.968  1586  1644 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-10 15:48:19.980  1586  1644 D KeyguardModel: createShortcutInfo...
08-10 15:48:19.981  1855  1855 D SplitUIManager: split_name #11 / not available #0
08-10 15:48:19.982  1855  1855 D SplitUIService: removed split : 
08-10 15:48:19.984  1803  1803 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-10 15:48:19.985  2176  2176 I ConfigService: onBind returning update interface
,08-10 15:48:19.985  2019  6870 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-10 15:48:19.986  2176  2176 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-10 15:48:19.986  2176  2176 I ConfigService: onBind returning config service
08-10 15:48:19.991  1586  1644 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-10 15:48:19.991  1586  1644 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 15:48:19.993  1036  1712 V SIM_STK : Menu title from STK is T-Mobile
08-10 15:48:19.994  1586  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 15:48:19.994  1586  1644 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-10 15:48:20.000  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-10 15:48:20.012  1586  1644 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-10 15:48:20.012  1586  1644 D KeyguardModel: createShortcutInfo...
08-10 15:48:20.016  2176  2176 I ConfigService: onDestroy
08-10 15:48:20.019  1803  6874 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-10 15:48:20.028  1586  1644 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 15:48:20.028  1586  1644 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-10 15:48:20.029  1586  1644 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-10 15:48:20.029  1586  1644 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-10 15:48:20.029  1586  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 15:48:20.030  1586  1644 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-10 15:48:20.033  1586  1644 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-10 15:48:20.033  1586  1644 D KeyguardModel: createShortcutInfo...
,08-10 15:48:20.038  1036  1036 I art     : Explicit concurrent mark sweep GC freed 15611(1306KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.816ms total 238.991ms
,08-10 15:48:20.038  1036  1124 I art     : WaitForGcToComplete blocked for 197.790ms for cause Explicit
08-10 15:48:20.052  1036  1770 V SIM_STK : Menu title from STK is T-Mobile
08-10 15:48:20.052  1036  1770 V SIM_STK : Menu title from STK is T-Mobile
,08-10 15:48:20.056  1855  1855 D SplitUIManager: split_name #11 / not available #0
08-10 15:48:20.056  1855  1855 I SplitUIService: split app #11
08-10 15:48:20.072  6024  6024 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-10 15:48:20.082  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-10 15:48:20.082  1586  1586 D KeyguardModel: handleShortcutListChanged...
08-10 15:48:20.082  1586  1586 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-10 15:48:20.084  2019  2019 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-10 15:48:20.094  1586  1644 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-10 15:48:20.094  1586  1644 D KeyguardModel: createShortcutInfo...
08-10 15:48:20.098  1586  1644 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-10 15:48:20.098  1586  1644 D KeyguardModel: createShortcutInfo...
08-10 15:48:20.098  1036  1036 D administrator: Handling package changes for user 0
08-10 15:48:20.102  1586  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 15:48:20.102  1586  1644 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-10 15:48:20.103  1586  1644 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-10 15:48:20.103  1586  1644 D KeyguardModel: createShortcutInfo...
08-10 15:48:20.104  1586  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 15:48:20.104  1586  1644 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-10 15:48:20.105  1586  1644 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-10 15:48:20.105  1586  1644 D KeyguardModel: createShortcutInfo...
08-10 15:48:20.106  1586  1644 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 15:48:20.106  1586  1644 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-10 15:48:20.107  1586  1644 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-10 15:48:20.107  1586  1644 D KeyguardModel: createShortcutInfo...
08-10 15:48:20.114  1036  1962 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-10 15:48:20.115  3893  3893 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-10 15:48:20.115  3893  3893 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-10 15:48:20.115  3893  3893 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-10 15:48:20.115  3893  3893 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-10 15:48:20.115  3893  3893 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-10 15:48:20.115  3893  3893 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-10 15:48:20.115  3893  3893 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-10 15:48:20.115  3893  3893 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-10 15:48:20.115  3893  3893 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-10 15:48:20.115  3893  3893 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-10 15:48:20.115  3893  3893 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-10 15:48:20.120  1036  1980 V SIM_STK : Menu title from STK is T-Mobile
08-10 15:48:20.125  5949  6879 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-10 15:48:20.129  2342  6882 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-10 15:48:20.134  6556  6556 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-10 15:48:20.135  1586  1586 D KeyguardModel: handleShortcutListChanged...
08-10 15:48:20.135  1586  1586 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-10 15:48:20.138  1803  6883 I PeopleContactsSync: CP2 sync disabled
08-10 15:48:20.144  1803  4763 I Icing   : doRemovePackageData com.test.thalitest
,08-10 15:48:20.146   329   421 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-10 15:48:20.147  1803  6880 W GmsApplication: Using Auth Proxy for data requests.
08-10 15:48:20.148  3159  6885 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-10 15:48:20.157  1803  6880 W GmsApplication: Using Auth Proxy for data requests.
,08-10 15:48:20.187  1981  1981 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-10 15:48:20.187  1981  1981 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-10 15:48:20.191  1981  1981 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-10 15:48:20.196  2019  2034 I art     : Background partial concurrent mark sweep GC freed 7051(323KB) AllocSpace objects, 5(19MB) LOS objects, 34% free, 60MB/92MB, paused 1.973ms total 116.786ms
08-10 15:48:20.200  6456  6456 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-10 15:48:20.218  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-10 15:48:20.221  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 15:48:20.223  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-10 15:48:20.224  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-10 15:48:20.225  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-10 15:48:20.226  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-10 15:48:20.231  1036  1908 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6888 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-10 15:48:20.242  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{18ed63df u0 com.lge.launcher2/.Launcher t5} time:194050
08-10 15:48:20.255  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-10 15:48:20.255  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-10 15:48:20.259  2019  2165 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-10 15:48:20.259  2019  2165 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-10 15:48:20.271  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-10 15:48:20.272  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-10 15:48:20.272  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 15:48:20.279  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-10 15:48:20.279  2019  2019 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-10 15:48:20.280  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-10 15:48:20.281  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-10 15:48:20.282  2593  2593 D [Concierge]Service: onStartCommand(). Type : 8
08-10 15:48:20.282  2593  2593 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-10 15:48:20.283  1036  1561 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-10 15:48:20.283  2019  2019 D [Concierge]WidgetView: change position of spinner
08-10 15:48:20.283  2593  2593 D [Concierge]Service: Update widget ID : 11
08-10 15:48:20.284  2593  2593 D [Concierge]Service: onStartCommand(). Type : 0
08-10 15:48:20.284  2019  2019 I [Concierge]WidgetView: initWebView(). Time : 1470836900284
08-10 15:48:20.303  2019  2019 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 213248073
08-10 15:48:20.303  2019  2019 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-10 15:48:20.303  2019  2019 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-10 15:48:20.307  2019  2019 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@10c07d0
08-10 15:48:20.307  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-10 15:48:20.309  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-10 15:48:20.309  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 15:48:20.315  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-10 15:48:20.315  2019  2019 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-10 15:48:20.315  2019  2019 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-10 15:48:20.316  2019  2019 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470836734088, New one : 1470836900284
08-10 15:48:20.316  2019  2019 D [Concierge]WidgetView: Unregister all receivers
08-10 15:48:20.316  2019  2019 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-10 15:48:20.316  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-10 15:48:20.320  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-10 15:48:20.321  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-10 15:48:20.322  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-10 15:48:20.323  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-10 15:48:20.324  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-10 15:48:20.328  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 15:48:20.328  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-10 15:48:20.344  1036  1124 I art     : Explicit concurrent mark sweep GC freed 8405(456KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 4.415ms total 304.799ms
,08-10 15:48:20.346  6888  6888 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-10 15:48:20.347  6888  6888 W LG Account v2.2: No ProfileInfo entries
08-10 15:48:20.347  6888  6888 I LG Account v2.2: isEnabled: false
08-10 15:48:20.347  6888  6888 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-10 15:48:20.347  6888  6888 I Feature : [Lifetracker]Country: EU
08-10 15:48:20.347  6888  6888 I Feature : [Lifetracker]Operator: OPEN
08-10 15:48:20.347  6888  6888 I Feature : [Lifetracker]Ranking support: false
08-10 15:48:20.347  6888  6888 I Feature : [Lifetracker]Comfort support: false
08-10 15:48:20.347  6888  6888 I Feature : [Lifetracker]Accessory: true
08-10 15:48:20.347  6888  6888 I Feature : [Lifetracker]Health device: true
08-10 15:48:20.347  6888  6888 I Feature : [Lifetracker]Extra Pedometer: false
08-10 15:48:20.347  6888  6888 I Feature : [Lifetracker]Blood glucose device: false
08-10 15:48:20.347  6888  6888 I Feature : [Lifetracker]Device Number: 3
08-10 15:48:20.348  6888  6888 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-10 15:48:20.372  2019  2019 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-10 15:48:20.380  2019  2019 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-10 15:48:20.380  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-10 15:48:20.381  1036  1051 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6910 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-10 15:48:20.381  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 15:48:20.382  1036  1051 I ActivityManager: Killing 6235:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-10 15:48:20.401  2019  2019 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@33a2d7ca time:194210
,08-10 15:48:20.429  6835  6835 D AndroidRuntime: Shutting down VM
,08-10 15:48:20.436  1036  1098 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 15:48:20.440  1036  1098 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-10 15:48:20.462  1036  1908 W libprocessgroup: failed to open /acct/uid_10014/pid_6235/cgroup.procs: No such file or directory
08-10 15:48:20.464  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-10 15:48:20.474  6910  6910 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 15:48:20.474  6910  6910 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-10 15:48:20.474  6910  6910 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 15:48:20.474  6910  6910 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-10 15:48:20.475  6910  6910 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-10 15:48:20.475  6910  6910 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-10 15:48:20.522  2019  2019 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-10 15:48:20.546  6910  6910 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-10 15:48:20.553  6910  6910 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-10 15:48:20.553  6910  6910 D HideNavigationAppsReceiver: replacing : false
08-10 15:48:20.555  6910  6910 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-10 15:48:20.556  6910  6910 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-10 15:48:20.556  6910  6910 D ButtonCombinationReceiver: replacing : false
,08-10 15:48:20.561  2019  2867 I GBoardtInterface: onReloaded()
08-10 15:48:20.563  2019  2019 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-10 15:48:20.564  1036  2017 I ActivityManager: Killing 6338:com.android.defcontainer/u0a4 (adj 15): empty #17
08-10 15:48:20.584  1036  1872 W libprocessgroup: failed to open /acct/uid_10004/pid_6338/cgroup.procs: No such file or directory
,08-10 15:48:20.584  3831  4500 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-10 15:48:20.586  4629  6927 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-10 15:48:20.587  3831  3846 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-10 15:48:20.617  1036  1980 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6928 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-10 15:48:20.619  1036  1994 V SIM_STK : Menu title from STK is T-Mobile
08-10 15:48:20.622  1891  1891 D ActionManagerService: notifyUserLog: 1000001
08-10 15:48:20.623  3831  4514 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-10 15:48:20.623  3831  4514 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-10 15:48:20.626  1891  1891 D ActionManagerService: notifyUserLog: 1000001
08-10 15:48:20.627  3831  4514 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-10 15:48:20.627  3831  4514 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-10 15:48:20.627  3831  4514 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-10 15:48:20.627  3831  4514 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-10 15:48:20.628  3831  4500 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-10 15:48:20.630  2019  2019 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
,08-10 15:48:20.630  2019  2019 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-10 15:48:20.632  2019  2019 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-10 15:48:20.632  2019  2019 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-10 15:48:20.634  2019  2019 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-10 15:48:20.634  2019  2019 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-10 15:48:20.671  1036  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6945 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-10 15:48:20.681   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 204us total 9.574ms
08-10 15:48:20.690   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 194us total 9.150ms
,08-10 15:48:20.700   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 190us total 9.160ms
08-10 15:48:20.702  6928  6928 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2586 
,08-10 15:48:20.718  6138  6138 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-10 15:48:20.718  6138  6138 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-10 15:48:20.718  6138  6138 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-10 15:48:20.718  6138  6138 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-10 15:48:20.718  6138  6138 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-10 15:48:20.718  6138  6138 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-10 15:48:20.733  6650  6650 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_REMOVED : com.test.thalitest
,08-10 15:48:20.735  4629  6927 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 148 ms] updated apps [took 148 ms] 
08-10 15:48:20.739  6910  6910 D PackageIntentReceiver: Not supported Hotkey customization function 
08-10 15:48:20.771  1036  1962 I ActivityManager: Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=6968 uid=10060 gids={50060, 9997, 1028, 4002} abi=armeabi-v7a
,08-10 15:48:20.773  1036  1962 I ActivityManager: Killing 6513:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-10 15:48:20.842  1036  1872 W libprocessgroup: failed to open /acct/uid_10008/pid_6513/cgroup.procs: No such file or directory

```
