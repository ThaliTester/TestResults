#### Test 7976383092ab77f_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-12 17:41:00.101  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 17:41:00.101  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 17:41:00.101  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-12 17:41:00.102  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-12 17:41:00.116  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 17:41:00.116  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 17:41:00.121  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-12 17:41:00.122  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 17:41:00.424  6828  6828 D AndroidRuntime: 
08-12 17:41:00.424  6828  6828 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-12 17:41:00.431  6828  6828 D AndroidRuntime: CheckJNI is OFF
08-12 17:41:00.632  6828  6828 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-12 17:41:00.643  1035  1051 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 17:41:00.658  1972  1989 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-12 17:41:00.664  1035  1051 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-12 17:41:00.666  1035  1051 D ActivityManager: setTaskToReturnTo : TaskRecord{f7477a1 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 17:41:00.666  1035  1051 D ActivityManager: setTaskToReturnTo : TaskRecord{f7477a1 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 17:41:00.668  1035  1051 D WindowStateEx: AppWindowTokenEx init.. 
08-12 17:41:00.669   342   351 E GBMv2   : DFP En is all cleared set to be enabled
08-12 17:41:00.707  1035  1051 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6843 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-12 17:41:00.711  6828  6828 D AndroidRuntime: Shutting down VM
08-12 17:41:00.787  1972  1989 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-12 17:41:00.787  1972  1989 D SplitWindowPolicy: topRunningActivity=ActivityInfo{28192d8d co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 17:41:00.788  1972  1992 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-12 17:41:00.789  1972  1992 D SplitWindowPolicy: topRunningActivity=ActivityInfo{6a78b42 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 17:41:00.841  6843  6843 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-12 17:41:00.924  6843  6843 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-12 17:41:00.932  6843  6843 I LibraryLoader: Loading: webviewchromium
08-12 17:41:00.935  6843  6843 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 2184-2188)
08-12 17:41:00.936  6843  6843 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-12 17:41:00.949  6843  6843 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3cdeebc3}
,08-12 17:41:00.950  6843  6843 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 17:41:00.951  6843  6843 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 17:41:00.960  6843  6843 I BrowserStartupController: Initializing chromium process, renderers=0
08-12 17:41:00.961  6843  6843 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 17:41:00.972  6843  6843 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-12 17:41:00.972  6843  6843 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-12 17:41:00.973  6843  6843 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-12 17:41:00.977   314   314 V AudioPolicyService: registerClient() client 0xb0410480, uid 10118
08-12 17:41:00.985  1035  1110 D BluetoothManagerService: Message: 20
08-12 17:41:00.985  1035  1110 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@206b2f23:true
08-12 17:41:01.004  6843  6843 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-12 17:41:01.004  6843  6843 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-12 17:41:01.004  6843  6843 I Adreno-EGL: Build Date: 12/12/14 금
08-12 17:41:01.004  6843  6843 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-12 17:41:01.004  6843  6843 I Adreno-EGL: Remote Branch: 
08-12 17:41:01.004  6843  6843 I Adreno-EGL: Local Patches: 
08-12 17:41:01.004  6843  6843 I Adreno-EGL: Reconstruct Branch: 
,08-12 17:41:01.086  6843  6878 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-12 17:41:01.094  6843  6843 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-12 17:41:01.123  6843  6843 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 17:41:01.129  6843  6843 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-12 17:41:01.132  6843  6843 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-12 17:41:01.136  6843  6843 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-12 17:41:01.136  6843  6843 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-12 17:41:01.152  6843  6843 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-12 17:41:01.159  6843  6843 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 17:41:01.159  6843  6843 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 17:41:01.191  6843  6890 D OpenGLRenderer: Render dirty regions requested: true
08-12 17:41:01.191  6843  6890 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 17:41:01.197  6843  6890 D OpenGLRenderer: Enabling debug mode 0
,08-12 17:41:01.208  6843  6843 D Atlas   : Validating map...
08-12 17:41:01.213  1035  1575 D SplitWindow: check instance of lgWin Window{b469305 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 17:41:01.250  6843  6888 D LgDataFeature: LgDataFeature() Constructor: none
,08-12 17:41:01.250  6843  6888 D LgDataFeature: LgDataFeature() Constructor Done, null
08-12 17:41:01.359  1035  1111 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +574ms (total +689ms)
08-12 17:41:01.360  1035  1111 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{38902dc6 u0 com.test.thalitest/.MainActivity t6} time:182613
08-12 17:41:01.365  6843  6843 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2c62216e time:182617
,08-12 17:41:01.512  6843  6843 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 17:41:01.603  6843  6888 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-12 17:41:01.603  6843  6888 I chromium: 
,08-12 17:41:01.732  6843  6901 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435044352
,08-12 17:41:01.750  6843  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 17:41:01.750  6843  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 17:41:01.750  6843  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 17:41:01.750  6843  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 17:41:01.750  6843  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-12 17:41:01.751  6843  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27a3cad2 added. We now have 1 listener(s)
,08-12 17:41:01.763  1035  2323 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 17:41:01.768  6843  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-12 17:41:01.769  6843  6901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-12 17:41:01.771  6843  6843 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-12 17:41:01.771  6843  6843 I chromium: 
,08-12 17:41:01.772  6843  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 17:41:01.773  6843  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 17:41:01.784  6843  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 17:41:01.784  6843  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 17:41:01.784  6843  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 17:41:01.784  6843  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-12 17:41:01.784  6843  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 17:41:01.784  6843  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 17:41:01.784  6843  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 17:41:01.784  6843  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 17:41:01.784  6843  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 17:41:01.784  6843  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 17:41:01.784  6843  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 17:41:01.784  6843  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 17:41:01.784  6843  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 17:41:01.784  6843  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 17:41:01.784  6843  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f4ec659 added. We now have 1 listener(s)
,08-12 17:41:01.785  6843  6901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 17:41:01.790  1035  1543 D WifiService: New client listening to asynchronous messages
08-12 17:41:01.796  6843  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-12 17:41:01.796  6843  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 17:41:01.799  6843  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 17:41:01.799  6843  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 17:41:01.799  6843  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-12 17:41:01.803  6843  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 17:41:01.805  1035  2324 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 17:41:01.806  6843  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-12 17:41:01.816  6843  6901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-12 17:41:01.818  6843  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 17:41:01.818  6843  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 17:41:01.818  6843  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 17:41:01.818  6843  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 17:41:01.818  6843  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 17:41:01.818  6843  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 17:41:01.818  6843  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 17:41:01.818  6843  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 17:41:01.819  6843  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 17:41:01.819  6843  6901 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 17:41:01.822  6843  6843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 17:41:01.824  6843  6901 I io.jxcore.node.LifeCycleMonitor: start: OK
08-12 17:41:01.824  6843  6843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 17:41:01.865  6843  6843 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 17:41:02.589   342   353 E GBMv2   : DFP En is all cleared set to be enabled
08-12 17:41:02.589   342   353 E GBMv2   : Set value is all cleared set the max
08-12 17:41:02.589   342   353 I GBMv2   : DFP Enabled. Ignore VFP set
,08-12 17:41:02.799  6843  6904 W jxcore-log: Initializing JXcore engine
08-12 17:41:02.799  6843  6904 W jxcore-log: JXcore engine is ready
,08-12 17:41:02.874  6904  6904 W Thread-797: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9856]" dev="sockfs" ino=9856 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-12 17:41:02.874  6904  6904 W Thread-797: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-12 17:41:02.874  6904  6904 W Thread-797: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10034]" dev="sockfs" ino=10034 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-12 17:41:02.874  6904  6904 W Thread-797: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-12 17:41:02.874  6904  6904 W Thread-797: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32182]" dev="sockfs" ino=32182 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-12 17:41:02.899  6843  6904 W jxcore-log: Starting JXcore engine
,08-12 17:41:03.069  6843  6904 W jxcore-log: Platform android
08-12 17:41:03.069  6843  6904 W jxcore-log: 
08-12 17:41:03.069  6843  6904 W jxcore-log: Process ARCH arm
08-12 17:41:03.069  6843  6904 W jxcore-log: 
,08-12 17:41:03.466  6843  6904 I jxcore-log: JXcore Cordova bridge is ready!
08-12 17:41:03.466  6843  6904 I jxcore-log: 
,08-12 17:41:03.466  6843  6904 W jxcore-log: JXcore engine is started
,08-12 17:41:03.478  6843  6901 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-12 17:41:03.486  6843  6843 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 17:41:22.735  6843  6904 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 17:41:22.735  6843  6904 I jxcore-log: 
,08-12 17:41:22.741  6843  6904 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 17:41:22.741  6843  6904 I jxcore-log: 
08-12 17:41:22.746  6843  6904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 17:41:22.746  6843  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 17:41:22.746  6843  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 17:41:22.746  6843  6904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 17:41:22.746  6843  6904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 17:41:22.746  6843  6904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 17:41:22.746  6843  6904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 17:41:22.746  6843  6904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 17:41:22.749  6843  6904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 17:41:22.755  6843  6904 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 17:41:22.755  6843  6904 I jxcore-log: 
08-12 17:41:22.758  6843  6904 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 17:41:22.758  6843  6904 I jxcore-log: 
08-12 17:41:23.404  6843  6904 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-12 17:41:23.404  6843  6904 I jxcore-log: Failed to execute UT.
08-12 17:41:23.404  6843  6904 I jxcore-log: 
08-12 17:41:23.404  6843  6904 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-12 17:41:23.404  6843  6904 I jxcore-log: 
,08-12 17:41:23.418  6843  6904 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 17:41:23.418  6843  6904 I jxcore-log: 
08-12 17:41:23.425  6843  6843 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 17:41:23.731  6926  6926 D AndroidRuntime: 
08-12 17:41:23.731  6926  6926 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-12 17:41:23.739  6926  6926 D AndroidRuntime: CheckJNI is OFF
08-12 17:41:23.947  6926  6926 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 17:41:23.965  1035  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-12 17:41:23.966  1035  1092 I ActivityManager: Killing 6843:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-12 17:41:24.035  1035  2069 I WindowState: WIN DEATH: Window{b469305 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 17:41:24.040  1035  1543 D WifiService: Client connection lost with reason: 4
08-12 17:41:24.046  1035  2069 D InputDispatcher: Window went away: Window{b469305 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 17:41:24.129  1035  1092 I ActivityManager:   Force finishing activity ActivityRecord{38902dc6 u0 com.test.thalitest/.MainActivity t6}
,08-12 17:41:24.177   342   351 E GBMv2   : DFP En is all cleared set to be enabled
08-12 17:41:24.178  1035  2095 W ActivityManager: Spurious death for ProcessRecord{1326fb03 6843:com.test.thalitest/u0a118}, curProc for 6843: null
,08-12 17:41:24.179  1035  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-12 17:41:24.180  1035  1124 I ActivityManager:   Force finishing activity ActivityRecord{38902dc6 u0 com.test.thalitest/.MainActivity t6 f}
08-12 17:41:24.180  1035  1124 W ActivityManager: Duplicate finish request for ActivityRecord{38902dc6 u0 com.test.thalitest/.MainActivity t6 f}
,08-12 17:41:24.210  2096  2096 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-12 17:41:24.211  1972  1992 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,08-12 17:41:24.211  1972  1992 D SplitWindowPolicy: topRunningActivity=ActivityInfo{18d09753 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-12 17:41:24.212  2096  2096 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-12 17:41:24.214  2096  2096 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-12 17:41:24.215  2096  2193 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-12 17:41:24.217  1972  2792 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-12 17:41:24.218  1972  2792 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3c1de890 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-12 17:41:24.228  1930  1930 D ActionManagerService: notifyUserLog: 1000003
08-12 17:41:24.228  3766  4808 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-12 17:41:24.228  2096  2096 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-12 17:41:24.230  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-12 17:41:24.239  2460  2620 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-12 17:41:24.239  4168  4168 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-12 17:41:24.239  4168  4168 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-12 17:41:24.243  2046  2046 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-12 17:41:24.243  3766  3766 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-12 17:41:24.247  1035  1425 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-12 17:41:24.263  4889  4889 I art     : Explicit concurrent mark sweep GC freed 496(33KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 783us total 72.298ms
,08-12 17:41:24.278  1035  1091 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-12 17:41:24.293  2096  2096 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-12 17:41:24.295  4784  4784 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-12 17:41:24.299  2096  2096 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-12 17:41:24.301  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-12 17:41:24.302  2096  2096 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-12 17:41:24.307  1930  1930 D ActionManagerService: notifyUserLog: 1000004
08-12 17:41:24.308  3766  4808 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-12 17:41:24.309  1602  1647 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 17:41:24.309  1602  1647 D KeyguardModel: createShortcutInfo...
08-12 17:41:24.314  1602  1647 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 17:41:24.314  1602  1647 D KeyguardModel: createShortcutInfo...,
08-12 17:41:24.322  1035  1709 V SIM_STK : Menu title from STK is T-Mobile
,08-12 17:41:24.327  2096  2096 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-12 17:41:24.327  6410  6410 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-12 17:41:24.331  1843  1843 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-12 17:41:24.334  1602  1647 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-12 17:41:24.334  1602  1647 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 17:41:24.334  1602  1647 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-12 17:41:24.335  1602  1647 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-12 17:41:24.296  4784  4784 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-12 17:41:24.336  4784  4784 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-12 17:41:24.336  4784  4784 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-12 17:41:24.337  3766  4802 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 17:41:24.339  4784  4784 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 17:41:24.339  4784  4784 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 17:41:24.339  4784  4784 W System.err: 	at android.os.Looper.loop(Looper.java:135)
,08-12 17:41:24.339  4784  4784 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-12 17:41:24.339  4784  4784 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 17:41:24.339  4784  4784 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 17:41:24.339  4784  4784 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-12 17:41:24.339  4784  4784 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-12 17:41:24.340  1602  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 17:41:24.340  1602  1647 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 17:41:24.347  2096  2096 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-12 17:41:24.347  2096  2096 I GBoardWebViewUtils: , create_time: 1430832262123
08-12 17:41:24.347  2096  2096 I GBoardWebViewUtils: , expire_time: 0
08-12 17:41:24.347  2096  2096 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-12 17:41:24.347  2096  2096 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-12 17:41:24.347  2096  2096 I GBoardWebViewUtils: , display: false
08-12 17:41:24.347  2096  2096 I GBoardWebViewUtils: , animation: false }
08-12 17:41:24.347  2096  2096 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-12 17:41:24.347  2096  2096 I GBoardWebViewUtils: , create_time: 1430832262287
08-12 17:41:24.347  2096  2096 I GBoardWebViewUtils: , expire_time: 0
08-12 17:41:24.347  2096  2096 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-12 17:41:24.347  2096  2096 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-12 17:41:24.347  2096  2096 I GBoardWebViewUtils: , display: false
08-12 17:41:24.347  2096  2096 I GBoardWebViewUtils: , animation: false }
08-12 17:41:24.347  2096  2096 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-12 17:41:24.347  2096  2096 I GBoardWebViewUtils: , create_time: 1471007226523
08-12 17:41:24.347  2096  2096 I GBoardWebViewUtils: , expire_time: 0
08-12 17:41:24.347  2096  2096 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-12 17:41:24.347  2096  2096 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-12 17:41:24.347  2096  2096 I GBoardWebViewUtils: , display: false
08-12 17:41:24.347  2096  2096 I GBoardWebViewUtils: , animation: false }
08-12 17:41:24.348  1896  1896 D SplitUIManager: split_name #11 / not available #0
08-12 17:41:24.350  1896  1896 D SplitUIService: removed split : 
,08-12 17:41:24.358  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-12 17:41:24.358  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-12 17:41:24.360  2096  6959 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-12 17:41:24.361  1602  1647 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
,08-12 17:41:24.361  1602  1647 D KeyguardModel: createShortcutInfo...
08-12 17:41:24.370  2268  2268 I ConfigService: onCreate
08-12 17:41:24.370  1602  1647 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-12 17:41:24.370  1602  1647 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 17:41:24.371  2268  2268 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-12 17:41:24.375  1602  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 17:41:24.375  1602  1647 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-12 17:41:24.379  2268  2268 I ConfigService: onBind returning update interface
08-12 17:41:24.380  2096  2096 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-12 17:41:24.381  1602  1647 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
,08-12 17:41:24.381  1602  1647 D KeyguardModel: createShortcutInfo...
08-12 17:41:24.384  1843  1843 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-12 17:41:24.385  2268  2268 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-12 17:41:24.385  2268  2268 I ConfigService: onBind returning config service
08-12 17:41:24.389  1602  1647 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 17:41:24.389  1602  1647 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-12 17:41:24.389  1602  1647 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-12 17:41:24.389  1602  1647 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-12 17:41:24.395  1843  1843 I ConfigFetchService: service connected
08-12 17:41:24.398  1602  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 17:41:24.398  1602  1647 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 17:41:24.400  1602  1647 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 17:41:24.400  1602  1647 D KeyguardModel: createShortcutInfo...
08-12 17:41:24.403  2268  2268 I ConfigService: onDestroy
08-12 17:41:24.418  1843  6962 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-12 17:41:24.418  1602  1647 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 17:41:24.418  1602  1647 D KeyguardModel: createShortcutInfo...
08-12 17:41:24.419  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-12 17:41:24.419  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-12 17:41:24.422  1602  1647 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 17:41:24.422  1602  1647 D KeyguardModel: createShortcutInfo...
,08-12 17:41:24.423  1602  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 17:41:24.423  1602  1647 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 17:41:24.424  1896  1896 D SplitUIManager: split_name #11 / not available #0
08-12 17:41:24.424  1896  1896 I SplitUIService: split app #11
08-12 17:41:24.425  1602  1647 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 17:41:24.425  1602  1647 D KeyguardModel: createShortcutInfo...
08-12 17:41:24.426  1602  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 17:41:24.426  1602  1647 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 17:41:24.428  1602  1647 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 17:41:24.428  1602  1647 D KeyguardModel: createShortcutInfo...
08-12 17:41:24.432  1035  1035 I art     : Explicit concurrent mark sweep GC freed 20308(1538KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 4.610ms total 227.514ms
,08-12 17:41:24.434  1035  2069 V SIM_STK : Menu title from STK is T-Mobile
08-12 17:41:24.434  1035  2069 V SIM_STK : Menu title from STK is T-Mobile
,08-12 17:41:24.437  1602  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 17:41:24.438  1602  1647 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 17:41:24.441  1602  1647 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 17:41:24.441  1602  1647 D KeyguardModel: createShortcutInfo...
08-12 17:41:24.460  2096  2096 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-12 17:41:24.465  2096  2096 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-12 17:41:24.475  5816  6968 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-12 17:41:24.484  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-12 17:41:24.484  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-12 17:41:24.492  1035  2324 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-12 17:41:24.492  4168  4168 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-12 17:41:24.492  4168  4168 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-12 17:41:24.493  4168  4168 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-12 17:41:24.493  4168  4168 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-12 17:41:24.493  4168  4168 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-12 17:41:24.493  4168  4168 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-12 17:41:24.493  4168  4168 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-12 17:41:24.493  4168  4168 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-12 17:41:24.493  4168  4168 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-12 17:41:24.493  4168  4168 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-12 17:41:24.493  4168  4168 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-12 17:41:24.497  1035  1124 I art     : WaitForGcToComplete blocked for 286.803ms for cause Explicit
08-12 17:41:24.505  1843  6967 W GmsApplication: Using Auth Proxy for data requests.
,08-12 17:41:24.510  1843  6967 W GmsApplication: Using Auth Proxy for data requests.
08-12 17:41:24.517  1843  6969 I PeopleContactsSync: CP2 sync disabled
08-12 17:41:24.517  1843  5071 I Icing   : doRemovePackageData com.test.thalitest
,08-12 17:41:24.524  6497  6497 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-12 17:41:24.525  1035  1720 V SIM_STK : Menu title from STK is T-Mobile
08-12 17:41:24.533   328   423 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-12 17:41:24.534  3260  6972 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-12 17:41:24.542  6548  6548 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-12 17:41:24.542  2151  6973 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-12 17:41:24.555  1035  1035 D administrator: Handling package changes for user 0
,08-12 17:41:24.564  2046  2046 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-12 17:41:24.564  2046  2046 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-12 17:41:24.566  2046  2046 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-12 17:41:24.569  6410  6410 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-12 17:41:24.594  1035  2324 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6976 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-12 17:41:24.616  2096  2096 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-12 17:41:24.619  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 17:41:24.620  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-12 17:41:24.621  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-12 17:41:24.622  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-12 17:41:24.623  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-12 17:41:24.644  2096  2096 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-12 17:41:24.644  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 17:41:24.645  1035  1111 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1e2d019e u0 com.lge.launcher2/.Launcher t5} time:205898
08-12 17:41:24.659  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-12 17:41:24.659  2096  2096 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-12 17:41:24.659  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 17:41:24.659  1035  1124 I art     : Explicit concurrent mark sweep GC freed 5771(336KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.957ms total 144.598ms
08-12 17:41:24.660  2096  2288 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-12 17:41:24.660  2096  2288 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-12 17:41:24.668  2096  2096 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-12 17:41:24.669  2669  2669 D [Concierge]Service: onStartCommand(). Type : 8
08-12 17:41:24.669  2669  2669 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-12 17:41:24.670  2669  2669 D [Concierge]Service: Update widget ID : 11
,08-12 17:41:24.671  2096  2096 D [Concierge]WidgetView: change position of spinner
08-12 17:41:24.672  2096  2096 I [Concierge]WidgetView: initWebView(). Time : 1471016484672
08-12 17:41:24.672  2669  2669 D [Concierge]Service: onStartCommand(). Type : 0
08-12 17:41:24.682  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-12 17:41:24.682  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 17:41:24.682  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-12 17:41:24.683  1035  1577 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-12 17:41:24.693  2096  2096 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 45650406
08-12 17:41:24.693  2096  2096 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-12 17:41:24.694  2096  2096 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-12 17:41:24.696  2096  2096 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3af35766
08-12 17:41:24.696  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-12 17:41:24.698  2096  2096 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-12 17:41:24.698  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 17:41:24.704  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-12 17:41:24.705  2096  2096 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-12 17:41:24.706  2096  2096 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471016307022, New one : 1471016484672
08-12 17:41:24.706  2096  2096 D [Concierge]WidgetView: Unregister all receivers
08-12 17:41:24.707  2096  2096 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-12 17:41:24.707  2096  2096 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-12 17:41:24.707  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 17:41:24.709  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-12 17:41:24.710  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-12 17:41:24.710  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-12 17:41:24.711  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
,08-12 17:41:24.712  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-12 17:41:24.714  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 17:41:24.715  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 17:41:24.727  6976  6976 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-12 17:41:24.727  6976  6976 W LG Account v2.2: No ProfileInfo entries
08-12 17:41:24.727  6976  6976 I LG Account v2.2: isEnabled: false
08-12 17:41:24.727  6976  6976 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-12 17:41:24.727  6976  6976 I Feature : [Lifetracker]Country: EU
08-12 17:41:24.727  6976  6976 I Feature : [Lifetracker]Operator: OPEN
08-12 17:41:24.728  6976  6976 I Feature : [Lifetracker]Ranking support: false
08-12 17:41:24.728  6976  6976 I Feature : [Lifetracker]Comfort support: false
08-12 17:41:24.728  6976  6976 I Feature : [Lifetracker]Accessory: true
08-12 17:41:24.728  6976  6976 I Feature : [Lifetracker]Health device: true
08-12 17:41:24.728  6976  6976 I Feature : [Lifetracker]Extra Pedometer: false
08-12 17:41:24.728  6976  6976 I Feature : [Lifetracker]Blood glucose device: false
08-12 17:41:24.728  6976  6976 I Feature : [Lifetracker]Device Number: 3
08-12 17:41:24.728  6976  6976 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
,08-12 17:41:24.736  6926  6926 D AndroidRuntime: Shutting down VM
,08-12 17:41:24.744  2096  2096 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-12 17:41:24.752  2096  2096 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-12 17:41:24.753  2096  2096 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-12 17:41:24.754  2096  2096 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 17:41:24.758  1035  1709 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7000 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-12 17:41:24.759  1035  1709 I ActivityManager: Killing 6183:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-12 17:41:24.774  2096  2096 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@b046373 time:206026
,08-12 17:41:24.798  1035  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-12 17:41:24.802  1035  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-12 17:41:24.841  1035  1965 W libprocessgroup: failed to open /acct/uid_10014/pid_6183/cgroup.procs: No such file or directory
08-12 17:41:24.843  2096  2096 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-12 17:41:24.853  7000  7000 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 17:41:24.854  7000  7000 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-12 17:41:24.854  7000  7000 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-12 17:41:24.854  7000  7000 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-12 17:41:24.855  7000  7000 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-12 17:41:24.856  7000  7000 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-12 17:41:24.910  2096  2096 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-12 17:41:24.934  7000  7000 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-12 17:41:24.943  7000  7000 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-12 17:41:24.943  7000  7000 D HideNavigationAppsReceiver: replacing : false
08-12 17:41:24.946  2096  2931 I GBoardtInterface: onReloaded()
,08-12 17:41:24.957  7000  7000 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-12 17:41:24.957  2096  2096 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
,08-12 17:41:24.959  7000  7000 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-12 17:41:24.959  7000  7000 D ButtonCombinationReceiver: replacing : false
08-12 17:41:24.959  3766  4802 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 17:41:24.962  3766  3781 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 17:41:24.967  1035  1984 I ActivityManager: Killing 6446:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-12 17:41:24.982  1930  1930 D ActionManagerService: notifyUserLog: 1000001
,08-12 17:41:24.983  1035  2069 W libprocessgroup: failed to open /acct/uid_10008/pid_6446/cgroup.procs: No such file or directory
08-12 17:41:24.985  4889  7018 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-12 17:41:24.987  3766  4808 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-12 17:41:24.987  3766  4808 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-12 17:41:24.987  1930  1930 D ActionManagerService: notifyUserLog: 1000001
08-12 17:41:24.989  3766  4808 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-12 17:41:24.989  3766  4808 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-12 17:41:24.989  3766  4808 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-12 17:41:24.989  3766  4802 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 17:41:24.989  3766  4808 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-12 17:41:25.005  1035  2323 V SIM_STK : Menu title from STK is T-Mobile
,08-12 17:41:25.018  1035  1052 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7020 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-12 17:41:25.020  2096  2096 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-12 17:41:25.020  2096  2096 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-12 17:41:25.022  2096  2096 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-12 17:41:25.022  2096  2096 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-12 17:41:25.023  2096  2096 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-12 17:41:25.023  2096  2096 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-12 17:41:25.051  4889  7018 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-12 17:41:25.053  2268  2285 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
08-12 17:41:25.054  2268  2285 W ServiceConnection: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/service.connections: open failed: EROFS (Read-only file system)
08-12 17:41:25.054  2268  2285 W ServiceConnection: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-12 17:41:25.054  2268  2285 W ServiceConnection: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 17:41:25.054  2268  2285 W ServiceConnection: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1047)
08-12 17:41:25.054  2268  2285 W ServiceConnection: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
08-12 17:41:25.054  2268  2285 W ServiceConnection: 	at com.google.android.gms.common.internal.bf.b(SourceFile:56)
08-12 17:41:25.054  2268  2285 W ServiceConnection: 	at com.google.android.gms.common.internal.bf.a(SourceFile:48)
08-12 17:41:25.054  2268  2285 W ServiceConnection: 	at com.google.android.gms.common.internal.be.a(SourceFile:45)
08-12 17:41:25.054  2268  2285 W ServiceConnection: 	at com.google.android.gms.icing.service.n.b(SourceFile:118)
08-12 17:41:25.054  2268  2285 W ServiceConnection: 	at com.google.android.gms.common.internal.bd.b(SourceFile:218)
08-12 17:41:25.054  2268  2285 W ServiceConnection: 	at com.google.android.gms.common.internal.ao.onTransact(SourceFile:460)
08-12 17:41:25.054  2268  2285 W ServiceConnection: 	at android.os.Binder.execTransact(Binder.java:446)
08-12 17:41:25.054  2268  2285 W ServiceConnection: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 17:41:25.054  2268  2285 W ServiceConnection: 	at libcore.io.Posix.open(Native Method)
08-12 17:41:25.054  2268  2285 W ServiceConnection: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 17:41:25.054  2268  2285 W ServiceConnection: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-12 17:41:25.054  2268  2285 W ServiceConnection: 	... 10 more
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: Exception thrown from notifyTableChanged
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	at beg.a(PG:301)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	at beg.c(PG:222)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	at cun.b(PG:660)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	at cun.a(PG:651)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	at cun.g(PG:597)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	at android.content.ContentResolver.update(ContentResolver.java:1349)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	at cuw.Tg(PG:368)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	at cuy.ub(PG:301)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	at android.os.Looper.loop(Looper.java:135)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 17:41:25.054,  4889  7018 E IcingCorporaProvider: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	at bea.a(PG:382)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	at beg.i(PG:325)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	at beh.call(PG:215)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	at beg.a(PG:299)
08-12 17:41:25.054  4889  7018 E IcingCorporaProvider: 	... 15 more
08-12 17:41:25.054  4889  7018 W IcingCorporaProvider: notifyTableChanged failed.
08-12 17:41:25.054  4889  7018 W IcingCorporaProvider: Table change notification failed for TableStorageSpec[applications]
08-12 17:41:25.055  4889  7018 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 70 ms] updated apps [took 70 ms] 
08-12 17:41:25.064  7020  7020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2586 
08-12 17:41:25.072  1843  5071 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
08-12 17:41:25.072  1843  5071 E Icing   : Could not init tag ds.tag.corpusid-1
08-12 17:41:25.072  1843  5071 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-13 for write failed: Read-only file system
08-12 17:41:25.072  1843  5071 E Icing   : Could not init tag ds.tag.corpusid-13
08-12 17:41:25.072  1843  5071 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-7 for write failed: Read-only file system
08-12 17:41:25.072  1843  5071 E Icing   : Could not init tag ds.tag.corpusid-7
08-12 17:41:25.072  1843  5071 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-8 for write failed: Read-only file system
08-12 17:41:25.072  1843  5071 E Icing   : Could not init tag ds.tag.corpusid-8
08-12 17:41:25.072  1843  5071 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-9 for write failed: Read-only file system
08-12 17:41:25.072  1843  5071 E Icing   : Could not init tag ds.tag.corpusid-9
08-12 17:41:25.072  1843  5071 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
08-12 17:41:25.072  1843  5071 E Icing   : Could not init tag ds.tag.deleted
08-12 17:41:25.073  1843  5071 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
08-12 17:41:25.073  1843  5071 E Icing   : Writing status failed
08-12 17:41:25.074  6695  6695 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-12 17:41:25.074  6695  6695 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-12 17:41:25.074  6695  6695 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-12 17:41:25.074  6695  6695 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-12 17:41:25.075  6695  6695 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-12 17:41:25.075  6695  6695 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-12 17:41:25.082  5491  5491 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_REMOVED : com.test.thalitest
08-12 17:41:25.087  7020  7038 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
08-12 17:41:25.087  7020  7038 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 17:41:25.087  7020  7038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 17:41:25.087  7020  7038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-12 17:41:25.087  7020  7038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-12 17:41:25.087  7020  7038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 17:41:25.087  7020  7038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 17:41:25.087  7020  7038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 17:41:25.087  7020  7038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-12 17:41:25.087  7020  7038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-12 17:41:25.087  7020  7038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-12 17:41:25.087  7020  7038 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-12 17:41:25.087  7020  7038 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-12 17:41:25.087  7020  7038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 17:41:25.087  7020  7038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 17:41:25.087  7020  7038 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-12 17:41:25.087  7020  7038 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-12 17:41:25.087  7020  7038 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-12 17:41:25.087  7020  7038 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 17:41:25.087  7020  7038 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-12 17:41:25.087  7020  7038 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
--------- beginning of crash
08-12 17:41:25.088  7020  7038 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-12 17:41:25.088  7020  7038 E AndroidRuntime: Process: com.android.keychain, PID: 7020
08-12 17:41:25.088  7020  7038 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 17:41:25.088  7020  7038 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 17:41:25.088  7020  7038 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-12 17:41:25.088  7020  7038 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-12 17:41:25.088  7020  7038 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 17:41:25.088  7020  7038 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 17:41:25.088  7020  7038 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 17:41:25.088  7020  7038 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-12 17:41:25.088  7020  7038 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-12 17:41:25.088  7020  7038 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-12 17:41:25.088  7020  7038 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-12 17:41:25.088  7020  7038 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-12 17:41:25.088  7020  7038 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 17:41:25.088  7020  7038 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 17:41:25.088  7020  7038 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-12 17:41:25.088  7020  7038 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-12 17:41:25.088  7020  7038 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-12 17:41:25.088  7020  7038 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 17:41:25.088  7020  7038 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-12 17:41:25.088  7020  7038 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 17:41:25.089  7000  7000 D PackageIntentReceiver: Not supported Hotkey customization function 
08-12 17:41:25.095  1035  7041 E DropBoxManagerService: Can't write: system_app_crash
08-12 17:41:25.095  1035  7041 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-12 17:41:25.095  1035  7041 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-12 17:41:25.095  1035  7041 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 17:41:25.095  1035  7041 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 17:41:25.095  1035  7041 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 17:41:25.095  1035  7041 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-12 17:41:25.095  1035  7041 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-12 17:41:25.095  1035  7041 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 17:41:25.095  1035  7041 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 17:41:25.095  1035  7041 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 17:41:25.095  1035  7041 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-12 17:41:25.095  1035  7041 E DropBoxManagerService: 	... 5 more

```
