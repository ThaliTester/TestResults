#### Test 79751015d1e118e_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
08-05 13:15:38.346  6737  6737 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-05 13:15:43.842  6881  6881 D AndroidRuntime: 
08-05 13:15:43.842  6881  6881 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-05 13:15:43.847  6881  6881 D AndroidRuntime: CheckJNI is OFF
08-05 13:15:43.976  6881  6881 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-05 13:15:43.981  1036  1926 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-05 13:15:43.991  1946  4336 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-05 13:15:43.995  1036  1926 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-05 13:15:43.996  1036  1926 D ActivityManager: setTaskToReturnTo : TaskRecord{1e826688 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-05 13:15:43.996  1036  1926 D ActivityManager: setTaskToReturnTo : TaskRecord{1e826688 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-05 13:15:43.998  1036  1926 D WindowStateEx: AppWindowTokenEx init.. 
08-05 13:15:43.998   350   368 E GBMv2   : DFP En is all cleared set to be enabled
08-05 13:15:44.043  1036  1926 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6900 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-05 13:15:44.045  6881  6881 D AndroidRuntime: Shutting down VM
08-05 13:15:44.101  1946  1962 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-05 13:15:44.101  1946  1962 D SplitWindowPolicy: topRunningActivity=ActivityInfo{35d0dbe3 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-05 13:15:44.102  1946  1961 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-05 13:15:44.102  1946  1961 D SplitWindowPolicy: topRunningActivity=ActivityInfo{17ef9e0 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-05 13:15:44.194  6900  6900 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-05 13:15:44.297  6900  6900 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-05 13:15:44.309  6900  6900 I LibraryLoader: Loading: webviewchromium
08-05 13:15:44.314  6900  6900 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 4674-4679)
08-05 13:15:44.314  6900  6900 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 13:15:44.330  6900  6900 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b619a89}
08-05 13:15:44.333  6900  6900 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 13:15:44.333  6900  6900 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-05 13:15:44.344  6900  6900 I BrowserStartupController: Initializing chromium process, renderers=0
08-05 13:15:44.344  6900  6900 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 13:15:44.357  6900  6900 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-05 13:15:44.359  6900  6900 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-05 13:15:44.359  6900  6900 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-05 13:15:44.363   332  2181 V AudioPolicyService: registerClient() client 0xb0410320, uid 10118
08-05 13:15:44.371  1036  1109 D BluetoothManagerService: Message: 20
08-05 13:15:44.371  1036  1109 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34ad0ed2:true
08-05 13:15:44.382  6900  6900 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 13:15:44.382  6900  6900 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 13:15:44.382  6900  6900 I Adreno-EGL: Build Date: 12/12/14 금
08-05 13:15:44.382  6900  6900 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 13:15:44.382  6900  6900 I Adreno-EGL: Remote Branch: 
08-05 13:15:44.382  6900  6900 I Adreno-EGL: Local Patches: 
08-05 13:15:44.382  6900  6900 I Adreno-EGL: Reconstruct Branch: 
08-05 13:15:44.477  6900  6936 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-05 13:15:44.485  6900  6900 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-05 13:15:44.501  6900  6900 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 13:15:44.508  6900  6900 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-05 13:15:44.511  6900  6900 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-05 13:15:44.514  6900  6900 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-05 13:15:44.514  6900  6900 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-05 13:15:44.530  6900  6900 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-05 13:15:44.537  6900  6900 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 13:15:44.537  6900  6900 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 13:15:44.582  6900  6951 D OpenGLRenderer: Render dirty regions requested: true
08-05 13:15:44.582  6900  6951 I OpenGLRenderer: Initialized EGL, version 1.4
08-05 13:15:44.590  6900  6951 D OpenGLRenderer: Enabling debug mode 0
08-05 13:15:44.601  1036  1093 W ActivityManager: Activity pause timeout for ActivityRecord{df34821 u0 com.test.thalitest/.MainActivity t40}
08-05 13:15:44.603  6900  6900 D Atlas   : Validating map...
08-05 13:15:44.608  1036  2036 D SplitWindow: check instance of lgWin Window{3da018fc u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-05 13:15:44.656  6900  6949 D LgDataFeature: LgDataFeature() Constructor: none
08-05 13:15:44.656  6900  6949 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 13:15:44.733  1036  1110 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +633ms (total +734ms)
08-05 13:15:44.733  1036  1110 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{df34821 u0 com.test.thalitest/.MainActivity t40} time:315100
08-05 13:15:44.736  6900  6900 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@391896ec time:315102
08-05 13:15:44.845  6900  6900 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-05 13:15:44.845  6900  6900 I chromium: 
08-05 13:15:44.890  6900  6900 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-05 13:15:45.092  6900  6961 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435060736
,08-05 13:15:45.108  6900  6961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-05 13:15:45.108  6900  6961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-05 13:15:45.108  6900  6961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-05 13:15:45.108  6900  6961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-05 13:15:45.108  6900  6961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-05 13:15:45.109  6900  6961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24b1e7f0 added. We now have 1 listener(s)
08-05 13:15:45.115  1036  1729 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:15:45.118  6900  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-05 13:15:45.123  6900  6961 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-05 13:15:45.126  6900  6961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 13:15:45.126  6900  6961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 13:15:45.137  6900  6961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-05 13:15:45.137  6900  6961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-05 13:15:45.137  6900  6961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-05 13:15:45.137  6900  6961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-05 13:15:45.137  6900  6961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-05 13:15:45.137  6900  6961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-05 13:15:45.137  6900  6961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-05 13:15:45.137  6900  6961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-05 13:15:45.137  6900  6961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-05 13:15:45.137  6900  6961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-05 13:15:45.137  6900  6961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-05 13:15:45.137  6900  6961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-05 13:15:45.137  6900  6961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-05 13:15:45.137  6900  6961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-05 13:15:45.137  6900  6961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f51648f added. We now have 1 listener(s)
08-05 13:15:45.138  6900  6961 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 13:15:45.143  1036  1545 D WifiService: New client listening to asynchronous messages
08-05 13:15:45.147  6900  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 13:15:45.147  6900  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-05 13:15:45.149  6900  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-05 13:15:45.149  6900  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-05 13:15:45.150  6900  6961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-05 13:15:45.156  6900  6961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 13:15:45.156  1036  1907 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:15:45.157  6900  6961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-05 13:15:45.175  6900  6961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-05 13:15:45.176  6900  6961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 13:15:45.176  6900  6961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:15:45.176  6900  6961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:15:45.176  6900  6961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 13:15:45.176  6900  6961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 13:15:45.176  6900  6961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 13:15:45.176  6900  6961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 13:15:45.176  6900  6961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 13:15:45.177  6900  6961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-05 13:15:45.178  6900  6961 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 13:15:45.181  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:15:45.184  6900  6961 I io.jxcore.node.LifeCycleMonitor: start: OK
08-05 13:15:45.185  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:15:45.219  6900  6949 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-05 13:15:45.219  6900  6949 I chromium: 
,08-05 13:15:45.304  6900  6900 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-05 13:15:45.570   350   370 E GBMv2   : DFP En is all cleared set to be enabled
08-05 13:15:45.570   350   370 E GBMv2   : Set value is all cleared set the max
08-05 13:15:45.570   350   370 I GBMv2   : DFP Enabled. Ignore VFP set
,08-05 13:15:46.158  6900  6964 W jxcore-log: Initializing JXcore engine
08-05 13:15:46.158  6900  6964 W jxcore-log: JXcore engine is ready
,08-05 13:15:46.241  6964  6964 W Thread-812: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8396]" dev="sockfs" ino=8396 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-05 13:15:46.241  6964  6964 W Thread-812: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-05 13:15:46.241  6964  6964 W Thread-812: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8590]" dev="sockfs" ino=8590 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-05 13:15:46.241  6964  6964 W Thread-812: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-05 13:15:46.241  6964  6964 W Thread-812: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31389]" dev="sockfs" ino=31389 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-05 13:15:46.273  6900  6964 W jxcore-log: Starting JXcore engine
,08-05 13:15:46.392  6900  6964 W jxcore-log: Platform android
08-05 13:15:46.392  6900  6964 W jxcore-log: 
08-05 13:15:46.392  6900  6964 W jxcore-log: Process ARCH arm
08-05 13:15:46.392  6900  6964 W jxcore-log: 
,08-05 13:15:46.630  6900  6964 I jxcore-log: JXcore Cordova bridge is ready!
08-05 13:15:46.630  6900  6964 I jxcore-log: 
08-05 13:15:46.631  6900  6964 W jxcore-log: JXcore engine is started
,08-05 13:15:46.641  6900  6961 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-05 13:15:46.647  6900  6900 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-05 13:16:00.063  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-05 13:16:00.064  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 13:16:00.064  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 13:16:00.064  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-05 13:16:00.066  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-05 13:16:00.067  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-05 13:16:00.068  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
,08-05 13:16:00.068  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-05 13:16:02.427  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-05 13:16:02.427  6900  6964 I jxcore-log: 
,08-05 13:16:02.430  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-05 13:16:02.430  6900  6964 I jxcore-log: 
08-05 13:16:02.435  6900  6964 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 13:16:02.435  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:02.435  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:02.435  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 13:16:02.435  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 13:16:02.435  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 13:16:02.435  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 13:16:02.435  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 13:16:02.437  6900  6964 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 13:16:02.440  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-05 13:16:02.440  6900  6964 I jxcore-log: 
,08-05 13:16:02.441  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-05 13:16:02.441  6900  6964 I jxcore-log: 
08-05 13:16:02.775  6900  6964 D ExecuteNativeTests: Running unit tests
,08-05 13:16:02.856  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 13:16:02.856  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8f57b0 added. We now have 2 listener(s)
08-05 13:16:02.857  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:02.858  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 13:16:02.858  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 13:16:02.858  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 13:16:02.858  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 13:16:02.858  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 added. We now have 2 listener(s)
08-05 13:16:02.858  6900  6964 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 13:16:02.861  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 13:16:02.866  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 13:16:02.870  6900  6964 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 13:16:02.870  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:02.870  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:02.870  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 13:16:02.870  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 13:16:02.870  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 13:16:02.870  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 13:16:02.870  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 13:16:02.871  6900  6964 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 13:16:02.871  6900  6964 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 13:16:02.872  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:02.874  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:02.876  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-05 13:16:02.876  6900  6964 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 13:16:02.876  6900  6964 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 13:16:02.878  6900  6964 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-05 13:16:02.879  6900  6964 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-05 13:16:02.879  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 13:16:02.879  6900  6964 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 13:16:02.879  6900  6964 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-05 13:16:02.880  6900  6964 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 13:16:02.881  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 13:16:02.881  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 13:16:02.882  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:02.882  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.882  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 13:16:02.882  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 13:16:02.883  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8f57b0 removed from the list
08-05 13:16:02.883  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:02.883  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 removed from the list
08-05 13:16:02.883  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
08-05 13:16:02.883  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.883  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.883  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 13:16:02.884  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:02.884  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:02.884  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:02.884  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:02.886  6900  6964 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-05 13:16:02.886  6900  6964 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 13:16:02.886  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 13:16:02.886  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 13:16:02.887  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:02.887  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.887  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.887  6900  6964 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8f57b0 not in the list
08-05 13:16:02.887  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:02.887  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:02.887  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
08-05 13:16:02.887  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.887  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.887  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.887  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.888  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:02.888  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:02.888  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:02.888  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:02.891  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-05 13:16:02.891  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-05 13:16:02.891  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-05 13:16:02.891  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-05 13:16:02.892  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-05 13:16:02.892  6900  6964 ,D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-05 13:16:02.892  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-05 13:16:02.892  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-05 13:16:02.892  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-05 13:16:02.892  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-05 13:16:02.892  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-05 13:16:02.892  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-05 13:16:02.892  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-05 13:16:02.892  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-05 13:16:02.892  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-05 13:16:02.892  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-05 13:16:02.892  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-05 13:16:02.892  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-05 13:16:02.892  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-05 13:16:02.892  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-05 13:16:02.892  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-05 13:16:02.892  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-05 13:16:02.892  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-05 13:16:02.892  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-05 13:16:02.892  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-05 13:16:02.892  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-05 13:16:02.892  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-05 13:16:02.892  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-05 13:16:02.892  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-05 13:16:02.892  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-05 13:16:02.892  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-05 13:16:02.892  6900  6964 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 ,13:16:02.892  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 13:16:02.892  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 13:16:02.893  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:02.893  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.893  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.893  6900  6964 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8f57b0 not in the list
08-05 13:16:02.893  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:02.893  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:02.893  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
08-05 13:16:02.893  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.893  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.893  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.893  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.893  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:02.893  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:02.893  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:02.894  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
,08-05 13:16:02.894  6900  6964 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-05 13:16:02.899  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 13:16:02.901  6900  6964 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 13:16:02.901  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:02.901  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:02.901  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 13:16:02.901  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 13:16:02.901  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 13:16:02.901  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 13:16:02.901  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 13:16:02.902  6900  6964 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 13:16:02.902  6900  6964 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 13:16:02.903  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:02.904  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:02.904  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 13:16:02.904  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 13:16:02.905  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 13:16:02.905  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 13:16:02.905  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 13:16:02.908  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-05 13:16:02.909  1036  1729 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:02.912  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 13:16:02.916  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 13:16:02.917  6900  6964 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-05 13:16:02.917  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 13:16:02.918  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 13:16:02.919  6900  6964 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-05 13:16:02.919  6900  6964 I io.jxcore.node.ConnectionHelper: start: OK
08-05 13:16:02.921  6900  6964 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 13:16:02.921  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 13:16:02.921  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 13:16:02.922  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:02.922  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.922  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 13:16:02.922  6900  6964 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8f57b0 not in the list
08-05 13:16:02.922  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:02.922  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:02.922  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
08-05 13:16:02.922  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.922  6900  6964 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-05 13:16:02.923  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 13:16:02.925  6900  6964 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 13:16:02.925  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:02.925  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:02.925  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 13:16:02.925  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 13:16:02.925  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 13:16:02.925  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 13:16:02.925  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 13:16:02.926  6900  6964 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 13:16:02.926  6900  6964 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 13:16:02.926  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 13:16:02.926  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 13:16:02.926  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 13:16:02.926  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 13:16:02.926  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 13:16:02.929  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConne,ctivityInfo: No relevant state changes
08-05 13:16:02.930  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 13:16:02.933  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 13:16:02.933  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 13:16:02.934  6900  6964 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 13:16:02.934  6900  6964 I io.jxcore.node.ConnectionHelper: start: OK
08-05 13:16:02.935  6900  6964 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 13:16:02.935  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 13:16:02.936  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 13:16:02.936  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:02.936  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.936  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 13:16:02.936  6900  6964 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8f57b0 not in the list
08-05 13:16:02.936  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:02.936  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:02.936  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
08-05 13:16:02.936  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.936  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.936  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.937  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:02.937  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:02.938  6900  6964 D BluetoothLeScanner: could not find callback wrapper
08-05 13:16:02.939  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 13:16:02.939  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:02.939  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:02.939  6900  6964 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-05 13:16:02.940  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 13:16:02.944  6900  6964 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 13:16:02.944  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:02.944  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:02.944  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 13:16:02.944  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 13:16:02.944  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 13:16:02.944  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 13:16:02.944  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 13:16:02.945  6900  6964 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 13:16:02.945  6900  6964 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 13:16:02.945  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 13:16:02.945  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 13:16:02.945  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 13:16:02.945  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 13:16:02.945  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 13:16:02.947  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:02.948  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:02.951  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 13:16:02.951  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 13:16:02.953  6900  6964 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-05 13:16:02.953  6900  6964 I io.jxcore.node.ConnectionHelper: start: OK
08-05 13:16:02.953  6900  6964 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 13:16:02.953  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 13:16:02.953  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 13:16:02.955  6900  6964 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 13:16:02.955  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 13:16:02.955  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 13:16:02.956  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:02.956  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.956  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 13:16:02.956  6900  6964 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8f57b0 not in the list
08-05 13:16:02.956  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:02.956  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:02.956  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
08-05 13:16:02.956  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.957  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.957  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.958  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:02.958  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:02.958  6900  6964 D BluetoothLeScanner: could not find callback wrapper
08-05 13:16:02.958  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 13:16:02.959  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:02.959  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:02.959  6900  6964 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-05 13:16:02.960  6900  6964 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-05 13:16:02.960  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 13:16:02.960  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 13:16:02.960  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:02.960  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.960  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.961  6900  6964 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8f57b0 not in the list
08-05 13:16:02.961  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:02.961  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:02.961  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
08-05 13:16:02.961  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.961  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.961  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.961  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.962  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:02.962  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-05 13:16:02.962  6900  6964 D BluetoothLeScanner: could not find callback wrapper
08-05 13:16:02.962  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 13:16:02.962  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:02.962  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:02.963  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-05 13:16:02.964  6900  6964 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 13:16:02.964  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 13:16:02.964  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 13:16:02.964  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:02.964  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.964  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.964  6900  6964 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8f57b0 not in the list
08-05 13:16:02.964  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:02.964  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:02.964  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
08-05 13:16:02.964  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.964  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.964  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.964  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.965  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:02.965  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-05 13:16:02.966  6900  6964 D BluetoothLeScanner: could not find callback wrapper
08-05 13:16:02.966  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 13:16:02.966  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:02.966  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:02.969  6900  6964 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-05 13:16:02.969  6900  6964 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 13:16:02.969  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 13:16:02.969  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 13:16:02.970  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:02.970  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.970  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.970  6900  6964 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8f57b0 not in the list
08-05 13:16:02.970  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:02.970  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:02.970  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
08-05 13:16:02.970  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.970  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.970  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.970  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.971  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:02.971  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:02.974  6900  6964 D BluetoothLeScanner: could not find callback wrapper
08-05 13:16:02.974  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 13:16:02.974  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:02.974  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:02.975  6900  6964 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-05 13:16:02.975  6900  6964 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 13:16:02.975  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 13:16:02.975  6900  6964 V io.jxcore.node.StartStopOperationH,andler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 13:16:02.975  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:02.975  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.975  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.975  6900  6964 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8f57b0 not in the list
08-05 13:16:02.975  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:02.976  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:02.976  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
08-05 13:16:02.976  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.976  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.976  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.976  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.977  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:02.977  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:02.977  6900  6964 D BluetoothLeScanner: could not find callback wrapper
08-05 13:16:02.977  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 13:16:02.977  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:02.977  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:02.978  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-05 13:16:02.978  6900  6964 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 13:16:02.978  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 13:16:02.978  6900  6964 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 13:16:02.978  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-05 13:16:02.979  6900  6964 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 13:16:02.979  6900  6964 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 13:16:02.979  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 13:16:02.979  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 13:16:02.980  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:02.980  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.980  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.980  6900  6964 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8f57b0 not in the list
08-05 13:16:02.980  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:02.980  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:02.980  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
08-05 13:16:02.980  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.980  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.980  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.980  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.981  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:02.981  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:02.982  6900  6964 D BluetoothLeScanner: could not find callback wrapper
08-05 13:16:02.982  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 13:16:02.983  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:02.983  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:02.984  6900  6964 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 13:16:02.984  6900  6964 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-05 13:16:02.984  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-05 13:16:02.988  6900  6964 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 13:16:02.988  6900  6964 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-05 13:16:02.988  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-05 13:16:02.988  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-05 13:16:02.988  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-05 13:16:02.988  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-05 13:16:02.988  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-05 13:16:02.988  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-05 13:16:02.989  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-05 13:16:02.989  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-05 13:16:02.989  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-05 13:16:02.989  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-05 13:16:02.989  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-05 13:16:02.989  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-05 13:16:02.989  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-05 13:16:02.989  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-05 13:16:02.989  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-05 13:16:02.989  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-05 13:16:02.989  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-05 13:16:02.989  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-05 13:16:02.989  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-05 13:16:02.989  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-05 13:16:02.989  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-05 13:16:02.989  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-05 13:16:02.989  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-05 13:16:02.989  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-05 13:16:02.989  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-05 13:16:02.989  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-05 13:16:02.989  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-05 13:16:02.989  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-05 13:16:02.990  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-05 13:16:02.990  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-05 13:16:02.990  6900  6964 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-05 13:16:02.990  6900  6964 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 13:16:02.990  6900  6964 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-05 13:16:02.990  6900  6964 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 13:16:02.990  6900  6964 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 13:16:02.990  6900  6964 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-05 13:16:02.990  6900  6964 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 13:16:02.990  6900  6964 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 13:16:02.991  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-05 13:16:02.994  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-05 13:16:02.995  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-05 13:16:02.995  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-05 13:16:02.996  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-05 13:16:02.996  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-05 13:16:02.996  6900  6964 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-05 13:16:02.996  6900  6964 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 13:16:02.996  6900  6964 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-05 13:16:02.997  6900  6964 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 13:16:02.997  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 13:16:02.997  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 13:16:02.998  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:02.998  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.998  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.998  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-05 13:16:02.999  6900  6964 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8f57b0 not in the list
08-05 13:16:02.999  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:02.999  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:02.999  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
08-05 13:16:02.999  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.999  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:02.999  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:02.999  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.000  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:03.000  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:03.000  6900  6964 D BluetoothLeScanner: could not find callback wrapper
08-05 13:16:03.000  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 13:16:03.001  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:03.001  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:03.002  6900  6964 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-05 13:16:03.002  6900  6964 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 13:16:03.002  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 13:16:03.002  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 13:16:03.003  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:03.003  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.003  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.003  6900  6964 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8f57b0 not in the list
08-05 13:16:03.003  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:03.003  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:03.003  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
08-05 13:16:03.003  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.003  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.003  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.003  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.003  6900  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 876)
08-05 13:16:03.004  6900  6970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 876
08-05 13:16:03.005  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:03.005  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:03.006  6900  6964 D BluetoothLeScanner: could not find callback wrapper
08-05 13:16:03.006  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 13:16:03.006  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:03.006  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:03.007  6900  6964 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-05 13:16:03.007  6900  6964 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 13:16:03.007  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 13:16:03.007  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 13:16:03.008  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:03.008  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 13:16:03.008  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.008  6900  6964 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8f57b0 not in the list
08-05 13:16:03.008  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:03.008  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:03.008  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
08-05 13:16:03.008  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.008  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.008  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.008  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.010  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:03.010  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:03.010  6900  6964 D BluetoothLeScanner: could not find callback wrapper
08-05 13:16:03.011  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 13:16:03.011  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:03.011  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:03.012  6900  6964 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-05 13:16:03.012  6900  6964 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-05 13:16:03.012  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 13:16:03.012  6900  6964 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-05 13:16:03.012  6900  6964 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-05 13:16:03.013  6900  6964 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-05 13:16:03.013  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 13:16:03.013  6900  6964 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-05 13:16:03.013  6900  6964 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-05 13:16:03.013  6900  6964 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-05 13:16:03.013  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 13:16:03.013  6900  6964 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-05 13:16:03.013  6900  6964 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 13:16:03.013  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 13:16:03.013  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 13:16:03.014  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:03.014  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.014  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.014  6900  6964 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8f57b0 not in the list
08-05 13:16:03.014  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:03.014  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:03.014  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
08-05 13:16:03.014  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.014  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.014  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.014  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.016  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:03.016  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:03.017  6900  6964 D BluetoothLeScanner: could not find callback wrapper
08-05 13:16:03.017  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 13:16:03.017  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:03.017  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:03.018  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:03.018  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.018  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.018  6900  6964 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8f57b0 not in the list
08-05 13:16:03.018  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:03.018  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:03.018  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
08-05 13:16:03.018  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.018  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.018  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:03.018  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:03.018  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:03.018  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.018  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.018  6900  6964 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8f57b0 not in the list
08-05 13:16:03.018  6900  6964 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 13:16:03.019  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 13:16:03.019  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 13:16:03.019  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:03.019  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.019  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.019  6900  6964 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8f57b0 not in the list
08-05 13:16:03.019  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:03.019  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:03.019  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
08-05 13:16:03.019  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.019  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.019  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.019  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.020  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:03.020  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:03.021  6900  6964 D BluetoothLeScanner: could not find callback wrapper
08-05 13:16:03.021  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 13:16:03.021  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:03.021  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:03.023  6900  6964 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-05 13:16:03.023  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 13:16:03.024  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-05 13:16:03.024  6900  6964 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-05 13:16:03.025  6900  6964 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-05 13:16:03.029  6900  6900 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-05 13:16:03.030  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-05 13:16:03.030  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-05 13:16:03.032  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:03.032  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-05 13:16:03.033  1036  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:03.033  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-05 13:16:03.033  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-05 13:16:03.033  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.033  6900  6964 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-05 13:16:03.033  6900  6964 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8f57b0 not in the list
08-05 13:16:03.033  6900  6900 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-05 13:16:03.033  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:03.034  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-05 13:16:03.034  6900  6971 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 13:16:03.034  6900  6964 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-05 13:16:03.034  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-05 13:16:03.034  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-05 13:16:03.035  4199  4224 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-05 13:16:03.035  6900  6964 D BluetoothLeScanner: could not find callback wrapper
08-05 13:16:03.035  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 13:16:03.036  6900  6964 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-05 13:16:03.036  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.036  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.036  6900  6971 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-05 13:16:03.036  6900  6971 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-05 13:16:03.036  6900  6971 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-05 13:16:03.037  6900  6964 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 13:16:03.037  6900  6900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 13:16:03.037  6900  6900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 13:16:03.037  6900  6900 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-05 13:16:03.037  6900  6900 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 13:16:03.038  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:03.038  6900  6964 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 13:16:03.038  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 13:16:03.038  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 13:16:03.038  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:03.038  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.038  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.038  6900  6964 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8f57b0 not in the list
08-05 13:16:03.038  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:03.038  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:03.038  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
08-05 13:16:03.038  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.038  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.038  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.038  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.039  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:03.039  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:03.039  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:03.039  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:03.041  6900  6964 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-05 13:16:03.041  6900  6964 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-05 13:16:03.041  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 13:16:03.043  6900  6964 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 13:16:03.043  6900  6964 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 13:16:03.044  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 13:16:03.044  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 13:16:03.044  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:03.044  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.044  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.044  6900  6964 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8f57b0 not in the list
08-05 13:16:03.044  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:03.044  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:03.044  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
08-05 13:16:03.044  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.044  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.044  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.044  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.046  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:03.046  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:03.046  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:03.046  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:03.048  1036  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:03.049  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:03.050  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:03.051  6900  6964 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 13:16:03.051  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 13:16:03.051  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 13:16:03.052  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:03.052  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.052  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.052  6900  6964 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8f57b0 not in the list
08-05 13:16:03.052  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:03.052  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:03.052  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
08-05 13:16:03.052  6900  6964 W ,org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.052  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.052  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.052  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.053  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:03.053  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:03.053  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:03.053  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:03.055  6900  6964 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 13:16:03.055  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-05 13:16:03.055  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 13:16:03.055  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:03.056  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.056  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.056  6900  6964 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8f57b0 not in the list
08-05 13:16:03.056  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:03.056  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:03.056  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
08-05 13:16:03.056  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.056  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.056  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:03.056  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:03.058  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:03.058  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:03.058  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:03.058  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de02629 not in the list
08-05 13:16:03.060  6900  6964 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-05 13:16:03.060  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 13:16:03.061  6900  6964 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-05 13:16:03.061  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 13:16:03.061  6900  6964 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-05 13:16:03.061  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 13:16:03.063  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-05 13:16:03.064  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-05 13:16:03.065  6900  6964 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-05 13:16:03.065  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-05 13:16:03.065  6900  6964 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-05 13:16:03.065  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-05 13:16:03.065  6900  6964 I i,o.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-05 13:16:03.065  6900  6964 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-05 13:16:03.066  6900  6964 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-05 13:16:03.066  6900  6964 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-05 13:16:03.067  6900  6964 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-05 13:16:03.067  6900  6964 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-05 13:16:03.067  6900  6964 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-05 13:16:03.067  6900  6964 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-05 13:16:03.069  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 13:16:03.069  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1030486 added. We now have 2 listener(s)
08-05 13:16:03.069  6900  6964 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 13:16:03.070  6900  6964 D BluetoothAdapter: enable(): BT is already enabled..!
,08-05 13:16:03.071  1036  1926 D WifiServiceImplEx: setWifiEnabled: true pid=6900, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 13:16:03.072  1036  1926 D WifiService: setWifiEnabled: true pid=6900, uid=10118
08-05 13:16:03.072  1036  1926 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-05 13:16:03.074  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 13:16:03.074  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f4df147 added. We now have 3 listener(s)
08-05 13:16:03.074  6900  6964 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 13:16:03.079  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 13:16:03.079  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@379d8d74 added. We now have 4 listener(s)
08-05 13:16:03.079  6900  6964 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 13:16:03.081  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 13:16:03.081  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ae6c29d added. We now have 5 listener(s)
08-05 13:16:03.081  6900  6964 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 13:16:03.083  1036  1944 D WifiServiceImplEx: setWifiEnabled: false pid=6900, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 13:16:03.084  1036  1944 D WifiService: setWifiEnabled: false pid=6900, uid=10118
08-05 13:16:03.084  1036  1944 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 13:16:03.102  1036  1999 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:03.102  1036  1999 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@aebf7cf mBinding = false
08-05 13:16:03.103  1036  1539 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-05 13:16:03.103  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-05 13:16:03.103  1036  1539 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-05 13:16:03.104  1036  1539 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-05 13:16:03.104  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-05 13:16:03.104  1036  1539 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-05 13:16:03.105  1036  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 13:16:03.105  1036  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 13:16:03.106  1036  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 13:16:03.106  1036  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 13:16:03.106  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 13:16:03.107  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 13:16:03.107  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-05 13:16:03.119  6900  6969 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
,08-05 13:16:03.119  6900  6969 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 13:16:03.120  1036  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 13:16:03.120  1036  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:03.120  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:03.120  4199  4224 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 13:16:03.120  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 13:16:03.121  4199  4410 W bt-l2cap: L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 001122334455  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
08-05 13:16:03.121  2596  2596 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 13:16:03.121  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 13:16:03.121  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 13:16:03.122  1036  1539 D WifiNative-wlan0: SET ps 1: returned true
08-05 13:16:03.122  1036  2790 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:03.126   328   895 D CommandListener: Clearing all IP addresses on wlan0
08-05 13:16:03.130  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 13:16:03.130  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 13:16:03.130  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-05 13:16:03.131  1036  1109 D BluetoothManagerService: Message: 2
08-05 13:16:03.135  1036  1109 D BluetoothManagerService: Sending off request.
,08-05 13:16:03.139  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 13:16:03.146  4199  4312 D LGBluetoothServiceAdapter: [BTUI] Precleanup
,08-05 13:16:03.150  4199  4279 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-05 13:16:03.151  4199  4279 D BluetoothAdapterProperties: Setting state to 13
08-05 13:16:03.151  4199  4279 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-05 13:16:03.151  4199  4279 D BluetoothAdapterProperties: onBluetoothDisable()
08-05 13:16:03.152  4199  4279 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-05 13:16:03.152  4199  4283 D BluetoothAdapterProperties: Scan Mode:20
08-05 13:16:03.154  4199  4279 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-05 13:16:03.155  4199  4570 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-05 13:16:03.155  4199  4570 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 13:16:03.155  4199  4570 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-05 13:16:03.155  4199  4570 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-05 13:16:03.155  4199  4570 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-05 13:16:03.155  4199  4570 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-05 13:16:03.155  4199  4570 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-05 13:16:03.155  4199  4570 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-05 13:16:03.156  4199  4572 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 13:16:03.156  4199  4410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-05 13:16:03.156  4199  4623 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 13:16:03.156  4199  4624 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 13:16:03.157  4199  4629 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 13:16:03.157  4199  4410 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-05 13:16:03.159  4199  4410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 13:16:03.159  4199  4410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 13:16:03.159  4199  4410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-05 13:16:03.159  4199  4279 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-05 13:16:03.161  4199  4410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 13:16:03.161  4199  4410 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 13:16:03.161  4199  4410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 13:16:03.161  4199  4410 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 13:16:03.161  4199  4410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 13:16:03.161  4199  4410 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 13:16:03.161  4199  4410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-05 13:16:03.161  4199  4410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-05 13:16:03.161  4199  4410 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-05 13:16:03.163  6900  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 876)
08-05 13:16:03.166  1036  1109 D BluetoothManagerService: Message: 60
08-05 13:16:03.166  1036  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-05 13:16:03.166  1036  1109 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-05 13:16:03.167  6900  6964 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 13:16:03.167  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:03.167  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:03.167  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 13:16:03.167  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 13:16:03.167  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 13:16:03.167  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 13:16:03.167  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 13:16:03.167  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 13:16:03.168  6900  6964 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 13:16:03.168  6900  6964 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 13:16:03.170  1036  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-05 13:16:03.171  1036  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-05 13:16:03.180  6900  6900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 13:16:03.180  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 13:16:03.180  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:03.180  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:03.180  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 13:16:03.180  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 13:16:03.180  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 13:16:03.180  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 13:16:03.180  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 13:16:03.180  6900  6900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 13:16:03.180  6900  6900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 13:16:03.183  6900  6900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 13:16:03.183  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 13:16:03.183  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:03.183  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:03.183  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 13:16:03.183  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 13:16:03.183  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 13:16:03.183  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 13:16:03.183  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 13:16:03.188  6900  6900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 13:16:03.188  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 13:16:03.188  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:03.188  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:03.188  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 13:16:03.188  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 13:16:03.188  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 13:16:03.188  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 13:16:03.188  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 13:16:03.189  6900  6900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 13:16:03.189  6900  6900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetoot,h: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 13:16:03.190  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 13:16:03.197  1036  1981 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-05 13:16:03.203  1036  2787 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-7ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:03.203  1036  2787 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-7ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:03.204  1036  2787 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-05 13:16:03.204  1036  2787 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:03.204  1036  2787 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,08-05 13:16:03.215  1036  1093 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6980 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-05 13:16:03.218  1946  1946 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-05 13:16:03.218  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 13:16:03.229  1036  1546 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-05 13:16:03.229  1036  1546 D DSQN    : disableDataServiceNotify
08-05 13:16:03.230  1036  1546 D DSQN    : stop dsqn bin
08-05 13:16:03.231   328  6998 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-05 13:16:03.231  1036  2787 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-05 13:16:03.232  1036  1106 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-05 13:16:03.233  4199  4199 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:03.233  4199  4199 D BluetoothMapService: STATE_TURNING_OFF
08-05 13:16:03.233  4199  4199 V BluetoothMapService: Handler(): got msg=4
,08-05 13:16:03.233  4199  4199 D BluetoothMapService: MAP Service closeService in
08-05 13:16:03.233  4199  4199 D BluetoothMapMasInstance: MAP Service shutdown
08-05 13:16:03.233  4199  4199 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 13:16:03.233  4199  4199 V BluetoothMapService: MAP Service closeService out
08-05 13:16:03.235  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:03.235  4199  4199 V BtOppService: Receiver DISABLED_ACTION 
08-05 13:16:03.235  4199  4199 I BtOppRfcommListener: stopping Accept Thread
08-05 13:16:03.235  4199  4199 V BtOppRfcommListener: close mBtServerSocket
08-05 13:16:03.236  4199  4199 V BtOppRfcommListener: waiting for thread to terminate
08-05 13:16:03.236  4199  4623 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-05 13:16:03.236  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:03.236  4199  4199 V BtOppRfcommListener: done waiting for thread to terminate
08-05 13:16:03.243  1036  1546 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-05 13:16:03.243  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:03.243  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 13:16:03.244  1036  1546 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 13:16:03.244  1036  1546 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-05 13:16:03.244  1036  2787 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:03.244  1036  2787 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:03.244  1036  2787 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-05 13:16:03.244  1036  1546 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-05 13:16:03.244  1036  1546 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-05 13:16:03.245  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 13:16:03.245  1604  1818 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-05 13:16:03.274  1036  1093 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7004 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-05 13:16:03.275  1036  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:03.276  4199  4199 V BtOppService: onDestroy
08-05 13:16:03.276  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-05 13:16:03.277  1946  1946 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-05 13:16:03.277  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 13:16:03.278  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:03.278  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:03.279  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-05 13:16:03.280  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-05 13:16:03.280  1036  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-05 13:16:03.280  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 13:16:03.281  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 13:16:03.281  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 13:16:03.284  4199  4199 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-05 13:16:03.284  1036  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:03.285  1036  1546 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:03.285  1036  1546 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:03.285  1036  1546 D NetworkManagementService: Removing idletimer
08-05 13:16:03.285  1036  1546 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:03.286  1036  1546 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-05 13:16:03.286  1855  1855 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:03.286  1855  1855 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-05 13:16:03.287  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-05 13:16:03.288  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-05 13:16:03.288  1036  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:03.288  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:03.288  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:03.288  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 13:16:03.288  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 13:16:03.288  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:03.288  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 13:16:03.288  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 13:16:03.288  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:03.289  1036  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:03.289  1036  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-05 13:16:03.289  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-05 13:16:03.289  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-05 13:16:03.289  1036  1557 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:03.290  1036  1538 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:03.290  1036  1558 D RttS,ervice: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:03.290  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:03.290  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:03.291  1036  1539 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-05 13:16:03.291  1036  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:03.291  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:03.292  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:03.292  1036  1539 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:03.292  1036  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 13:16:03.292  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:03.292  1036  1538 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3d3abe4f
08-05 13:16:03.292  1036  1538 D LGWifiP2pService: P2pDisablingState
08-05 13:16:03.293  1036  1538 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:03.293  1036  1538 D LGWifiP2pService: p2p socket connection lost
08-05 13:16:03.293  1036  1538 D LGWifiP2pService: P2pDisabledState
08-05 13:16:03.294  1036  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-05 13:16:03.294  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:03.294  1036  1538 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:03.294  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 13:16:03.294  1036  1538 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:03.295  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 13:16:03.295  1946  1946 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-05 13:16:03.295  1946  1946 D WfdsService: WifiP2pState is changed : false
08-05 13:16:03.295  2596  2596 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 13:16:03.295  1946  2307 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-05 13:16:03.295  1946  2307 D WfdsService: Set the WFDS Monitor: false
08-05 13:16:03.295  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 13:16:03.295  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 13:16:03.296  1946  2307 D WfdsMonitor: WFDS Monitor is stopped
08-05 13:16:03.296  1946  2672 D CtrlSupplicant: Received on exit socket, terminate
08-05 13:16:03.296  1036  1539 D WifiNative-wlan0: SET ps 1: returned true
08-05 13:16:03.296  1946  2672 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-05 13:16:03.296  1946  2307 D WfdsService: STATE : WfdsDisabledState - enter
08-05 13:16:03.296  1946  2672 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-05 13:16:03.296  1946  2672 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-05 13:16:03.296  1946  2307 W WfdsService: DefaultState - msg [9445378] is not handled
08-05 13:16:03.296  1946  2309 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-05 13:16:03.296   328   895 D CommandListener: Clearing all IP a,ddresses on wlan0
08-05 13:16:03.296  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:03.299  1036  1539 D WifiNative-p2p0: doBoolean: TERMINATE
08-05 13:16:03.299  1036  1539 D WifiNative-p2p0: TERMINATE: returned true
08-05 13:16:03.299  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 13:16:03.299  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
08-05 13:16:03.299  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 13:16:03.300  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-05 13:16:03.301  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:03.302  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:03.302  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 13:16:03.305  1946  1946 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-05 13:16:03.306  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-05 13:16:03.306  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 13:16:03.306  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-05 13:16:03.308  6900  6900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 13:16:03.308  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 13:16:03.308  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:03.308  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:03.308  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 13:16:03.308  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 13:16:03.308  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 13:16:03.308  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 13:16:03.308  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 13:16:03.309  6900  6900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 13:16:03.309  6900  6900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 13:16:03.311  6900  6900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 13:16:03.311  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 13:16:03.311  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:03.311  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:03.311  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 13:16:03.311  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 13:16:03.311  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 13:16:03.311  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 13:16:03.311  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 13:16:03.311  6900  6900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 13:16:03.311  6900  6900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 13:16:03.328  1036  2790 D DhcpStateMachine: StoppedState
08-05 13:16:03.329  1036  2790 D DhcpStateMachine: StoppedState{ when=-33ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:03.329  1036  1539 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-05 13:16:03.329  1036  1539 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-05 13:16:03.334  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 13:16:03.336  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:03.336  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:03.352  7004  7004 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 13:16:03.352  7004  7004 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,08-05 13:16:03.352  7004  7004 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 13:16:03.353  7004  7004 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-05 13:16:03.354  7004  7004 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 13:16:03.355  7004  7004 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-05 13:16:03.356  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 13:16:03.356  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:03.357  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:03.357  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:03.357  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 13:16:03.358  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:03.374  6980  6980 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-05 13:16:03.375  6980  6980 W LG Account v2.2: No ProfileInfo entries
08-05 13:16:03.375  6980  6980 I LG Account v2.2: isEnabled: false
08-05 13:16:03.375  6980  6980 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-05 13:16:03.375  6980  6980 I Feature : [Lifetracker]Country: EU
08-05 13:16:03.375  6980  6980 I Feature : [Lifetracker]Operator: OPEN
08-05 13:16:03.375  6980  6980 I Feature : [Lifetracker]Ranking support: false
08-05 13:16:03.375  6980  6980 I Feature : [Lifetracker]Comfort support: false
08-05 13:16:03.375  6980  6980 I Feature : [Lifetracker]Accessory: true
08-05 13:16:03.375  6980  6980 I Feature : [Lifetracker]Health device: true
08-05 13:16:03.375  6980  6980 I Feature : [Lifetracker]Extra Pedometer: false
08-05 13:16:03.375  6980  6980 I Feature : [Lifetracker]Blood glucose device: false
08-05 13:16:03.376  6980  6980 I Feature : [Lifetracker]Device Number: 3
,08-05 13:16:03.384  6377  6377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 13:16:03.394  2596  2596 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-05 13:16:03.394  2596  2596 I wpa_supplicant: monitor socket send errors count : 1
08-05 13:16:03.394  2596  2596 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1946-2\x00 that cannot receive messages
08-05 13:16:03.395  1036  2652 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-05 13:16:03.395  1036  2652 D WifiMonitor: Dropping event because (p2p0) is stopped
08-05 13:16:03.395  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-05 13:16:03.395  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 13:16:03.396  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:03.397  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 13:16:03.427  1036  1052 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7025 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-05 13:16:03.428  1036  1052 I ActivityManager: Killing 2201:com.lge.music/u0a34 (adj 15): empty #17
08-05 13:16:03.441   332  1387 V AudioFlinger: 2201 died, releasing its sessions
08-05 13:16:03.441   332  1387 V AudioFlinger:  pid 1855 @ 0
08-05 13:16:03.441   332  1387 V AudioFlinger:  pid 3386 @ 1
08-05 13:16:03.441   332  1387 V AudioFlinger:  pid 3386 @ 2
,08-05 13:16:03.461  2596  2596 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-05 13:16:03.462  1036  2652 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-05 13:16:03.462  1036  2652 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 13:16:03.462  2596  2596 W wpa_supplicant: USIM:  scard_deinit function
08-05 13:16:03.463  1036  2652 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 13:16:03.463  1036  1109 D Tethering: InitialState.processMessage what=4
08-05 13:16:03.463  1036  2652 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-05 13:16:03.464  1036  2652 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 13:16:03.464  1036  2652 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 13:16:03.464  1036  1539 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=333817
08-05 13:16:03.464  1036  1539 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=333818
08-05 13:16:03.465  1036  1539 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=333818  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 13:16:03.465  1036  1539 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=333818  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 13:16:03.467  1036  2036 W libprocessgroup: failed to open /acct/uid_10034/pid_2201/cgroup.procs: No such file or directory
08-05 13:16:03.469  1036  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-05 13:16:03.478  1036  1539 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-05 13:16:03.479  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-05 13:16:03.522  7004  7004 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-05 13:16:03.526  4199  4199 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 13:16:03.526  4199  4199 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:03.526  4199  4199 V BluetoothPbapReceiver: ***********state = 13
08-05 13:16:03.528  4199  4199 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-05 13:16:03.529  4199  4199 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:03.529  4199  4199 V BluetoothPbapService: state: 13
08-05 13:16:03.529  4199  4199 V BluetoothPbapService: Pbap Service closeService in
08-05 13:16:03.530  4199  4199 V BluetoothPbapService: successfully stopped pbap service
08-05 13:16:03.530  4199  4199 V BluetoothPbapService: Pbap Service closeService out
08-05 13:16:03.530  1036  1109 D BluetoothManagerService: Message: 20
08-05 13:16:03.530  7025  7025 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 13:16:03.530  1036  1109 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@197c5706:true
08-05 13:16:03.530  4199  4199 V BluetoothPbapService: Pbap Service onDestroy
08-05 13:16:03.530  4199  4199 V BluetoothPbapService: Pbap Service closeService in
08-05 13:16:03.530  4199  4199 V BluetoothPbapService: Pbap Service closeService out
08-05 13:16:03.531  4199  4199 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-05 13:16:03.531  2154  2154 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 13:16:03.538  6900  6900 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-05 13:16:03.538  7025  7025 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 13:16:03.539  7025  7025 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 13:16:03.541  1036  2036 I ActivityManager: Killing 6309:com.android.defcontainer/u0a4 (adj 15): empty #17
08-05 13:16:03.546  1036  1109 D BluetoothManagerService: Message: 30
08-05 13:16:03.554  2596  2596 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-05 13:16:03.555  1036  2652 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-05 13:16:03.555  1036  2652 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-05 13:16:03.555  1036  2652 D WifiMonitor: Disconnecting from the supplicant, no more events
08-05 13:16:03.555  1036  1539 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,08-05 13:16:03.565  1036  1890 W libprocessgroup: failed to open /acct/uid_10004/pid_6309/cgroup.procs: No such file or directory
08-05 13:16:03.569  1036  1109 D BluetoothManagerService: Message: 30
,08-05 13:16:03.572  7004  7004 D LocalBluetoothProfileManager: Adding local MAP profile
08-05 13:16:03.574  7004  7004 D BluetoothMap: Create BluetoothMap proxy object
08-05 13:16:03.575  1036  1109 D BluetoothManagerService: Message: 30
08-05 13:16:03.578  1036  1109 D BluetoothManagerService: Message: 30
08-05 13:16:03.579  7004  7004 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-05 13:16:03.580  7004  7004 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-05 13:16:03.591  7004  7004 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-05 13:16:03.594  7004  7004 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-05 13:16:03.607  7004  7004 D DockEventReceiver: finishStartingService: stopping service
,08-05 13:16:03.628  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 13:16:03.657  1036  1539 D WifiOffDelayIfNotUsed: stopMonitoring
08-05 13:16:03.658  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 13:16:03.658  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
08-05 13:16:03.658  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 13:16:03.658  1946  1946 D WfdsService: Supplicant Connection state is changed : false
08-05 13:16:03.658  1946  2307 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-05 13:16:03.658  1946  2307 D WfdsService: Set the WFDS Monitor: false
08-05 13:16:03.658  1946  2307 D WfdsMonitor: WFDS Monitor is stopped
,08-05 13:16:03.663  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
,08-05 13:16:03.664  1946  1946 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-05 13:16:03.664  1036  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-05 13:16:03.664  1036  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-05 13:16:03.665  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:03.665  2508  2508 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:03.665  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:03.669  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:03.685  7004  7004 D LgDataFeature: LgDataFeature() Constructor: none
08-05 13:16:03.686  7004  7004 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 13:16:03.696  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:03.697  7004  7004 D BluetoothInputDevice: Proxy object connected
08-05 13:16:03.698  7004  7004 D HidProfile: Bluetooth service connected
08-05 13:16:03.699  7004  7004 D BluetoothPan: BluetoothPAN Proxy object connected
08-05 13:16:03.700  7004  7004 D PanProfile: Bluetooth service connected
,08-05 13:16:03.701  7004  7004 D BluetoothMap: Proxy object connected
08-05 13:16:03.702  7004  7004 D MapProfile: Bluetooth service connected
08-05 13:16:03.702  7004  7004 D BluetoothMap: getConnectedDevices()
08-05 13:16:03.703  7004  7004 D BluetoothMap: Bluetooth is Not enabled
08-05 13:16:03.703  7004  7004 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-05 13:16:03.705  7004  7004 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-05 13:16:03.709  7004  7004 D BluetoothPermissionRequest: onReceive
08-05 13:16:03.713  7004  7004 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-05 13:16:03.720  1036  1052 I ActivityManager: Killing 6419:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-05 13:16:03.724  7004  7004 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 13:16:03.780  4199  4199 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-05 13:16:03.780  4199  4199 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-05 13:16:03.781  4199  4199 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-05 13:16:03.787  1036  1051 W libprocessgroup: failed to open /acct/uid_10008/pid_6419/cgroup.procs: No such file or directory
08-05 13:16:03.798  4199  4199 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:03.798  4199  4199 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-05 13:16:03.803  4199  4199 V BluetoothFtpService: Ftp Service onStartCommand
08-05 13:16:03.804  4199  4199 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:03.804  4199  4199 V BluetoothFtpService: Ftp Service closeService
08-05 13:16:03.804  4199  4199 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-05 13:16:03.806  4199  4199 V BluetoothFtpService: successfully stopped ftp service
08-05 13:16:03.806  4199  4199 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 13:16:03.807  4199  4199 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 13:16:03.807  4199  4199 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 13:16:03.807  4199  4199 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:03.807  4199  4199 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-05 13:16:03.807  4199  4199 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-05 13:16:03.808  4199  4199 V BluetoothFtpService: Ftp Service onDestroy
08-05 13:16:03.808  4199  4199 V BluetoothFtpService: Ftp Service closeService
08-05 13:16:03.851  1036  2036 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7060 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-05 13:16:03.852  4199  4199 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:03.852  4199  4199 V BluetoothSapService: state: 13
08-05 13:16:03.852  4199  4199 V BluetoothSapService: Stopping SAP server process
08-05 13:16:03.855  4199  4199 V BluetoothSapService: Sap Service closeSapService in
08-05 13:16:03.855  4199  4199 V BluetoothSapService: Close listen Socket : 
08-05 13:16:03.855  4199  4199 V BluetoothSapService: Close rfcomm Socket : 
08-05 13:16:03.855  4199  4199 V BluetoothSapService: Close sapd  Socket : 
08-05 13:16:03.856  4199  4199 V BluetoothSapService: Sap Service closeSapService out
08-05 13:16:03.857  4199  4199 V BluetoothSapService: Sap Service onDestroy
08-05 13:16:03.857  4199  4199 V BluetoothSapService: Sap Service closeSapService in
08-05 13:16:03.857  4199  4199 V BluetoothSapService: Close listen Socket : 
,08-05 13:16:03.857  4199  4199 V BluetoothSapService: Close rfcomm Socket : 
08-05 13:16:03.857  4199  4199 V BluetoothSapService: Close sapd  Socket : 
08-05 13:16:03.857  4199  4199 V BluetoothSapService: Sap Service closeSapService out,
,08-05 13:16:03.913  1036  2036 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7086 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-05 13:16:03.937  7060  7060 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-05 13:16:03.955  1036  2035 I ActivityManager: Killing 6470:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-05 13:16:04.012  1036  2036 W libprocessgroup: failed to open /acct/uid_10011/pid_6470/cgroup.procs: No such file or directory
,08-05 13:16:04.045  7086  7086 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-05 13:16:04.075  7086  7086 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-05 13:16:04.078  1036  3544 I LocationManagerService: remove 2e4ef3f9
08-05 13:16:04.078  1036  3544 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-05 13:16:04.078  1036  3544 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 13:16:04.080  1036  3544 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-05 13:16:04.082  1036  3544 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-05 13:16:04.082  1036  3544 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-05 13:16:04.116  7086  7086 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-05 13:16:04.117  7086  7086 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-05 13:16:04.117  7086  7086 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-05 13:16:04.117  7086  7086 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-05 13:16:04.118  7086  7086 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-05 13:16:04.120  7086  7086 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-05 13:16:04.126  7086  7086 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-05 13:16:04.134  7086  7086 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 13:16:04.139  7086  7086 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 13:16:04.166  4199  4410 W bt-btif : ag scb idx 1 not allocated
08-05 13:16:04.166  4199  4410 E bt-btif : BTA AG is already disabled, ignoring ...
08-05 13:16:04.166  4199  4410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 13:16:04.166  4199  4283 D bt_hci_bdroid: cleanup
08-05 13:16:04.166  4199  4410 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 13:16:04.166  4199  4410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 13:16:04.166  4199  4410 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 13:16:04.166  4199  4410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 13:16:04.166  4199  4410 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 13:16:04.166  4199  4410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 13:16:04.166  4199  4410 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 13:16:04.166  4199  4410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 13:16:04.166  4199  4410 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 13:16:04.166  4199  4410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-05 13:16:04.166  4199  4410 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 13:16:04.166  4199  4410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 13:16:04.166  4199  4410 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 13:16:04.166  4199  4410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 13:16:04.166  4199  4410 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 13:16:04.166  4199  4410 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 13:16:04.166  4199  4410 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 13:16:04.166  4199  4410 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-05 13:16:04.166  4199  4562 I bt_userial_mct: exiting userial_read_thread
08-05 13:16:04.166  4199  4562 D bt_userial_mct: Leaving userial_evt_read_thread()
08-05 13:16:04.166  4199  4413 I bt_lpm  : LPM is already off!!!
08-05 13:16:04.167  4199  4283 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-05 13:16:04.167  7086  7086 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 13:16:04.167  4199  4413 I bt_vendor: hw_epilog_process
08-05 13:16:04.168  4199  4283 D bt_hci_bdroid: cleanup Finalizing cleanup
08-05 13:16:04.168  4199  4283 D bt_userial_mct: userial_close
08-05 13:16:04.168  4199  4283 E bt_userial_mct: pthread_join() FAILED result:3
08-05 13:16:04.168  4199  4283 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-05 13:16:04.171  6377  6377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 13:16:04.174  7086  7086 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-05 13:16:04.175  7025  7025 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 13:16:04.175  7025  7025 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 13:16:04.175  7025  7025 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 13:16:04.178  7086  7086 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-05 13:16:04.179  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 13:16:04.189  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:04.198  7086  7086 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 13:16:04.200  7086  7086 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 13:16:04.207  7086  7086 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 13:16:04.212  6377  6377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 13:16:04.218  7025  7025 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 13:16:04.218  7025  7025 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 13:16:04.218  7025  7025 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 13:16:04.226  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 13:16:04.234  4199  4283 D bt_hci_bdroid: set_power 0
08-05 13:16:04.234  4199  4283 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-05 13:16:04.234  4199  4283 I bt_vendor: bluetooth satus is on
08-05 13:16:04.234  4199  4283 I bt_vendor: bt-vendor : resetting BT status
08-05 13:16:04.234  4199  4283 I bt_vendor: Starting hciattach daemon
08-05 13:16:04.234  4199  4283 I bt_vendor: try to set false
08-05 13:16:04.235  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:04.236  4199  4283 I bt_vendor: Starting hciattach daemon
08-05 13:16:04.236  4199  4283 I bt_vendor: try to set false
08-05 13:16:04.238  4199  4283 I bt_vendor: cleanup
08-05 13:16:04.239  4199  4410 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-05 13:16:04.239  4199  4283 I GKI_LINUX: GKI_exit_task 0 done
08-05 13:16:04.239  4199  4283 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-05 13:16:04.242  4199  4279 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-05 13:16:04.246  4199  4199 D HeadsetService: Received stop request...Stopping profile...
08-05 13:16:04.250  4199  4199 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-05 13:16:04.250  4199  4199 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 13:16:04.250  4199  4313 D HeadsetStateMachine: Exit Disconnected: -1
08-05 13:16:04.250  4199  4199 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@249aba8e
,08-05 13:16:04.254  7086  7086 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 13:16:04.255  7086  7086 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 13:16:04.256  1855  1855 D BluetoothHeadset: Proxy object disconnected
08-05 13:16:04.256  1855  1855 D BluetoothHeadset: Proxy object disconnected
08-05 13:16:04.257  1855  1855 D BluetoothHeadset: Proxy object disconnected
08-05 13:16:04.257  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-05 13:16:04.257  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-05 13:16:04.260  7086  7086 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 13:16:04.262  4199  4199 D A2dpService: Received stop request...Stopping profile...
08-05 13:16:04.263  4199  4367 D A2dpStateMachine: Exit Disconnected: -1
,08-05 13:16:04.264  4199  4199 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-05 13:16:04.317  1036  1944 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7114 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-05 13:16:04.323  4199  4199 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-05 13:16:04.323  4199  4199 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 13:16:04.323  4199  4199 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@249aba8e
08-05 13:16:04.327  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-05 13:16:04.327  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-05 13:16:04.328  4199  4279 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-05 13:16:04.328  4199  4199 D HidService: Received stop request...Stopping profile...
08-05 13:16:04.329  4199  4199 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@249aba8e
08-05 13:16:04.330  4199  4199 D HeadsetStateMachine: Unbinding service...
08-05 13:16:04.330  7004  7004 D BluetoothInputDevice: Proxy object disconnected
08-05 13:16:04.330  7004  7004 D HidProfile: Bluetooth service disconnected
08-05 13:16:04.331  4199  4199 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 13:16:04.331  4199  4199 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 13:16:04.331  4199  4199 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 13:16:04.331  4199  4199 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 13:16:04.331  4199  4199 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-05 13:16:04.331  4199  4199 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 13:16:04.331  4199  4199 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-05 13:16:04.332  4199  4199 D HealthService: Received stop request...Stopping profile...
08-05 13:16:04.332  4199  4199 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@249aba8e
,08-05 13:16:04.336  4199  4199 D PanService: Received stop request...Stopping profile...
08-05 13:16:04.336  4199  4199 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@249aba8e
08-05 13:16:04.337  4199  4199 D BtGatt.DebugUtils: handleDebugAction() action=null
08-05 13:16:04.338  7004  7004 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-05 13:16:04.338  7004  7004 D PanProfile: Bluetooth service disconnected
08-05 13:16:04.338  4199  4199 D BtGatt.GattService: Received stop request...Stopping profile...
08-05 13:16:04.338  4199  4199 D BtGatt.GattService: stop()
08-05 13:16:04.338  4199  4199 D BtGatt.AdvertiseManager: advertise clients cleared
08-05 13:16:04.339  4199  4199 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@249aba8e
08-05 13:16:04.340  4199  4199 I BluetoothA2dpServiceJni: cleanupNative
08-05 13:16:04.340  4199  4368 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-05 13:16:04.340  4199  4199 I GKI_LINUX: GKI_exit_task 2 done
08-05 13:16:04.340  4199  4199 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-05 13:16:04.341  4199  4199 D BluetoothMapService: Received stop request...Stopping profile...
08-05 13:16:04.341  4199  4199 D BluetoothMapService: stop()
08-05 13:16:04.342  4199  4199 D BluetoothMapEmailAppObserver: deinitObservers()
08-05 13:16:04.342  4199  4199 D BluetoothMapEmailAppObserver: removeReceiver()
08-05 13:16:04.342  4199  4199 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@249aba8e
08-05 13:16:04.344  7004  7004 D BluetoothMap: Proxy object disconnected
08-05 13:16:04.344  7004  7004 D MapProfile: Bluetooth service disconnected
08-05 13:16:04.344  4199  4199 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-05 13:16:04.344  4199  4199 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-05 13:16:04.344  4199  4199 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-05 13:16:04.344  4199  4199 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 13:16:04.344  4199  4199 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 13:16:04.345  4199  4199 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-05 13:16:04.345  4199  4199 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-05 13:16:04.347  4199  4199 V BluetoothMapService: Handler(): got msg=4
08-05 13:16:04.347  4199  4199 D BluetoothMapService: MAP Service closeService in
08-05 13:16:04.347  4199  4199 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 13:16:04.347  4199  4199 V BluetoothMapService: MAP Service closeService out
08-05 13:16:04.347  4199  4199 D BluetoothMapService: cleanup()
08-05 13:16:04.347  4199  4199 D BluetoothMapService: MAP Service closeService in
08-05 13:16:04.348  4199  4199 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 13:16:04.348  4199  4199 V BluetoothMapService: MAP Service closeService out
08-05 13:16:04.348  4199  4279 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-05 13:16:04.348  4199  4279 D BluetoothAdapterProperties: Setting state to 10
08-05 13:16:04.348  4199  4279 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-05 13:16:04.349  1036  1109 D BluetoothManagerService: Message: 60
08-05 13:16:04.349  1036  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-05 13:16:04.349  1036  1109 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-05 13:16:04.349  4199  4279 I BluetoothAdapterState: Entering OffState
08-05 13:16:04.349  7004  7020 D BluetoothPbap: onBluetoothStateChange: up=false
08-05 13:16:04.350  1855  2445 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 13:16:04.351  7004  7019 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-05 13:16:04.351  1855  1871 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 13:16:04.352  7004  7020 D BluetoothPan: onBluetoothStateChange on: false
08-05 13:16:04.353  1855  1870 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 13:16:04.353  7004  7019 D BluetoothMap: onBluetoothStateChange: up=false
08-05 13:16:04.355  1036  1109 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 13:16:04.355  1036  1109 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 13:16:04.356  1036  1109 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-05 13:16:04.356  1036  1109 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-05 13:16:04.358  1036  1109 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-05 13:16:04.358  1036  1109 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-05 13:16:04.359  1036  1109 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@aebf7cf mBinding = false
08-05 13:16:04.360  1036  1109 D BluetoothManagerService: Sending unbind request.
08-05 13:16:04.361  1036  1109 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-05 13:16:04.363  1946  1946 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:04.364  1946  2129 D LGBluetoothAPIService: Message: 2
08-05 13:16:04.364  1946  2129 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3672d499 mBinding = false
08-05 13:16:04.364  1946  2129 D LGBluetoothAPIService: Sending unbind request.
,08-05 13:16:04.369  7004  7004 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 13:16:04.370  7004  7004 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-05 13:16:04.370  7004  7004 D LGBluetoothEventManager: [BTUI] clear device connection state
08-05 13:16:04.371  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 13:16:04.374  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:04.377  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:04.377  7004  7004 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-05 13:16:04.380  1604  1604 D BluetoothAdapter: 1066947649: getState() :  mService = null. Returning STATE_OFF
08-05 13:16:04.380  1604  1604 D BluetoothAdapter: 1066947649: getState() :  mService = null. Returning STATE_OFF
,08-05 13:16:04.381  4199  4283 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-05 13:16:04.382  4199  4199 I GKI_LINUX: GKI_exit_task 1 done
08-05 13:16:04.382  4199  4199 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-05 13:16:04.383  4199  4199 I BluetoothServiceJni: cleanupNative: return from cleanup
08-05 13:16:04.383  4199  4199 I art     : --- WEIRD: removing null entry 246
08-05 13:16:04.383  4199  4199 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-05 13:16:04.384  4199  4199 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-05 13:16:04.385  4199  4199 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-05 13:16:04.387  4199  4199 I art     : System.exit called, status: 0
08-05 13:16:04.387  4199  4199 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-05 13:16:04.389  7004  7004 D DockEventReceiver: finishStartingService: stopping service
,08-05 13:16:04.412   332  1387 V AudioFlinger: 4199 died, releasing its sessions
08-05 13:16:04.412   332  1387 V AudioFlinger:  pid 1855 @ 0
08-05 13:16:04.412   332  1387 V AudioFlinger:  pid 3386 @ 1
08-05 13:16:04.412   332  1387 V AudioFlinger:  pid 3386 @ 2
08-05 13:16:04.412  7004  7004 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-05 13:16:04.514  1036  1926 I ActivityManager: Process com.android.bluetooth (pid 4199) has died
,08-05 13:16:04.514  1036  1926 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-05 13:16:04.527  2154  2154 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 13:16:04.562  7025  7025 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 13:16:04.577  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 13:16:04.593  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:04.594  7004  7004 D BluetoothPermissionRequest: onReceive
08-05 13:16:04.601  7004  7004 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-05 13:16:04.602  7004  7004 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-05 13:16:04.606  7114  7141 W FormManager: Network not available. Please check & try again.
,08-05 13:16:04.609  7004  7004 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-05 13:16:04.669  1036  1052 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7143 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-05 13:16:04.693   354   354 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 484us total 25.328ms
,08-05 13:16:04.699  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 13:16:04.700  7004  7004 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 13:16:04.700  7004  7004 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 13:16:04.700  7004  7004 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 13:16:04.701  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 13:16:04.701  7114  7142 V FormManager: Network unavailable.
08-05 13:16:04.704  7114  7142 V FormManager: Network unavailable.
,08-05 13:16:04.712  7004  7004 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 13:16:04.712  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 13:16:04.713  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 13:16:04.713  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 13:16:04.713  7004  7004 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 13:16:04.713  7004  7004 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 13:16:04.715   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 420us total 21.562ms
08-05 13:16:04.719  4691  4691 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 13:16:04.719  4691  4691 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 13:16:04.721  1036  1999 I ActivityManager: Killing 6488:com.android.contacts/u0a19 (adj 15): empty #17
08-05 13:16:04.721  4691  4691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 13:16:04.737   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 440us total 20.691ms
,08-05 13:16:04.822  1036  1576 W libprocessgroup: failed to open /acct/uid_10019/pid_6488/cgroup.procs: No such file or directory
08-05 13:16:04.824  4691  4691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-05 13:16:04.882  7025  7025 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-05 13:16:04.882  7025  7025 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 13:16:04.882  7025  7025 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 13:16:04.892  4691  7163 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 13:16:04.892  7143  7143 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-05 13:16:04.892  4691  7162 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 13:16:04.893  7143  7143 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 13:16:04.894  7143  7143 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-05 13:16:04.894  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 13:16:04.895  7143  7143 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-05 13:16:04.896  4691  7163 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 13:16:04.903  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:04.913  7114  7167 W FormManager: Network not available. Please check & try again.
08-05 13:16:04.915  7114  7168 V FormManager: Network unavailable.
,08-05 13:16:04.917  7143  7143 D BluetoothAdapterApp: Loading JNI Library
08-05 13:16:04.922  7114  7168 V FormManager: Network unavailable.
08-05 13:16:04.927  7086  7086 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-05 13:16:04.932  7086  7086 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-05 13:16:04.934  7086  7086 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-05 13:16:04.957  7143  7143 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@334133b7 Instance Count = 1
,08-05 13:16:04.964  7143  7143 D BluetoothAdapterApp: onCreate
08-05 13:16:04.984  7086  7086 D LgDataFeature: LgDataFeature() Constructor: none
08-05 13:16:04.984  7086  7086 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 13:16:04.987  7143  7143 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-05 13:16:04.988  7143  7143 D ProfileConfigQcom: Adding HeadsetService
08-05 13:16:04.988  7143  7143 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-05 13:16:04.988  7143  7143 D ProfileConfigQcom: Adding A2dpService
08-05 13:16:04.988  7143  7143 D ProfileConfigQcom: [BTUI] HidService is supported
08-05 13:16:04.988  7143  7143 D ProfileConfigQcom: Adding HidService
08-05 13:16:04.989  7143  7143 D ProfileConfigQcom: [BTUI] HealthService is supported
08-05 13:16:04.989  7143  7143 D ProfileConfigQcom: Adding HealthService
08-05 13:16:04.989  7143  7143 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-05 13:16:04.990  7143  7143 D ProfileConfigQcom: [BTUI] PanService is supported
08-05 13:16:04.990  7143  7143 D ProfileConfigQcom: Adding PanService
08-05 13:16:04.990  7143  7143 D ProfileConfigQcom: [BTUI] GattService is supported
08-05 13:16:04.991  7143  7143 D ProfileConfigQcom: Adding GattService
08-05 13:16:04.991  7143  7143 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-05 13:16:04.991  7143  7143 D ProfileConfigQcom: Adding BluetoothMapService
08-05 13:16:04.991  7143  7143 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-05 13:16:04.993  7143  7143 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-05 13:16:04.999  7004  7004 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-05 13:16:05.001  7143  7143 V LGMDMManagerInternal: Create singleton instance
08-05 13:16:05.002  7086  7086 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-05 13:16:05.005  7086  7086 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-05 13:16:05.006  7086  7086 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-05 13:16:05.006  7086  7086 V SoundPool: doLoad: loading sample sampleID=1
08-05 13:16:05.006  7086  7172 V SoundPool: Start decode
08-05 13:16:05.006  7086  7172 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-05 13:16:05.007   332  2181 V MediaPlayerService: decode(23, 10857164, 17813)
08-05 13:16:05.007   332  2181 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-05 13:16:05.008   332  2181 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-05 13:16:05.008   332  2181 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-05 13:16:05.008   332  2181 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-05 13:16:05.008   332  2181 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-05 13:16:05.008   332  2181 V MediaPlayerService: player type = 3
08-05 13:16:05.008   332  2181 V AwesomePlayer: AwesomePlayer create()
08-05 13:16:05.008   332  2181 V AwesomePlayer: reset_l() 
08-05 13:16:05.008   332  2181 V AwesomePlayer: cancelPlayerEvents
08-05 13:16:05.008   332  2181 V AwesomePlayer: setAudioSink() 
08-05 13:16:05.008   332  2181 V AwesomePlayer: reset_l() 
08-05 13:16:05.008   332  2181 V AudioCache: notify(0xb1432500, 8, 0, 0)
08-05 13:16:05.008   332  2181 V AudioCache: ignored
08-05 13:16:05.008   332  2181 V AwesomePlayer: cancelPlayerEvents
08-05 13:16:05.008   332  2181 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-05 13:16:05.008   332  2181 V AwesomePlayer: setDataSource_l dataSource
08-05 13:16:05.008   332  2181 V LGParserOSAL: SniffLGParser start
08-05 13:16:05.008   332  2181 V LGParserOSAL: MainType:5, SubType=0
08-05 13:16:05.008   332  2181 V LGParserOSAL: #### check Mime : application/ogg
08-05 13:16:05.008   332  2181 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-05 13:16:05.008   332  2181 E MediaExtractor: Use LGExtractor :application/ogg 
08-05 13:16:05.009  7086  7086 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-05 13:16:05.022  7086  7086 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-05 13:16:05.026  7086  7086 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 13:16:05.027  7086  7086 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-05 13:16:05.031  6765  6765 D UEI.SmartControl: QS Service created
,08-05 13:16:05.049  6765  6765 I UEI.SmartControl: Service initServices...
08-05 13:16:05.049   332  2181 V LGParserOSAL: supported mime: application/ogg
08-05 13:16:05.049   332  2181 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-05 13:16:05.050   332  2181 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-05 13:16:05.050   332  2181 V AwesomePlayer: mBitrate = -1 bits/sec
08-05 13:16:05.050   332  2181 V AwesomePlayer: AudioTrack Setting
08-05 13:16:05.050   332  2181 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-05 13:16:05.050   332  2181 V AwesomePlayer: setAudioSource() 
08-05 13:16:05.050   332  2181 V MediaPlayerService: prepare
08-05 13:16:05.050  6765  6765 D UEI.SmartControl: QS start get config
08-05 13:16:05.050   332  2181 V AwesomePlayer: prepareAsync_l() 
08-05 13:16:05.050   332  2181 V MediaPlayerService: wait for prepare
08-05 13:16:05.050   332  7173 V AwesomePlayer: onPrepareAsyncEvent() 
08-05 13:16:05.051   332  7173 V AwesomePlayer: initAudioDecoder() 
08-05 13:16:05.051   332  7173 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-05 13:16:05.051   332  7173 V AudioSystem: isOffloadSupported()
08-05 13:16:05.051   332  7173 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-05 13:16:05.051   332  7173 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-05 13:16:05.051   332  7173 I AudioFlinger: isAudioPlaybackHookOn() false
08-05 13:16:05.051   332  7173 V AwesomePlayer: getUseOffload() = 0 
08-05 13:16:05.051   332  7173 V OMXCodec: OMXCodec::Create
08-05 13:16:05.051   332  7173 V OMXCodec: findMatchingCodecs()
08-05 13:16:05.052   332  7173 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-05 13:16:05.052   332  7173 V OMXCodec: matchingCodecs.size()=1
08-05 13:16:05.052   332  7173 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-05 13:16:05.055   332  7173 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-05 13:16:05.055   332  7173 V LGCodecAdapter: LG Codec Adapter start
08-05 13:16:05.055   332  7173 V OMXCodec: OMXCodec Createtor
08-05 13:16:05.055   332  7173 V OMXCodec: setComponentRole
08-05 13:16:05.055   332  7173 V OMXCodec: configureCodec protected=0
08-05 13:16:05.055   332  7173 V LGCodecAdapter: called getLGCodecSpecificData
08-05 13:16:05.055   332  7173 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-05 13:16:05.055   332  7173 V LGCodecOSAL: Called LGconfigureCodecMETA
08-05 13:16:05.055   332  7173 V LGCodecOSAL: Called LGconfigureCodecMSG
08-05 13:16:05.055   332  7173 V LGCodecOSAL: Not support LGCodec
08-05 13:16:05.055   332  7173 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-05 13:16:05.055   332  7173 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-05 13:16:05.055   332  7173 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-05 13:16:05.056   332  7173 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-05 13:16:05.056   332  7173 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-05 13:16:05.056   332  7173 V AudioSystem: isOffloadSupported()
08-05 13:16:05.056   332  7173 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-05 13:16:05.056   332  7173 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-05 13:16:05.056   332  7173 V OMXCodec: [OMX.google.vorbis.de,coder] start mState=1
08-05 13:16:05.056   332  7173 V OMXCodec: init()
08-05 13:16:05.056   332  7173 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-05 13:16:05.056   332  7173 V OMXCodec: allocateBuffers
08-05 13:16:05.056   332  7173 V OMXCodec: allocateBuffersOnPort portIndex=0
08-05 13:16:05.056   332  7173 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-05 13:16:05.056   332  7173 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on input port
08-05 13:16:05.056   332  7173 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
08-05 13:16:05.056   332  7173 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on input port
08-05 13:16:05.056   332  7173 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on input port
08-05 13:16:05.056   332  7173 V OMXCodec: allocateBuffersOnPort portIndex=1
08-05 13:16:05.056   332  7173 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-05 13:16:05.056   332  7173 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-05 13:16:05.057   332  7173 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
08-05 13:16:05.057   332  7173 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
08-05 13:16:05.057   332  7173 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fec0 on output port
08-05 13:16:05.057   332  7173 V OMXCodec: init() mAsyncCompletion wait!!! 
08-05 13:16:05.057   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-05 13:16:05.057   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-05 13:16:05.057   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-05 13:16:05.057   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-05 13:16:05.057   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-05 13:16:05.057   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-05 13:16:05.057   332  7173 V OMXCodec: init() mAsyncCompletion wait free! 
08-05 13:16:05.057   332  7173 V AwesomePlayer: finishAsyncPrepare_l() 
08-05 13:16:05.057   332  7173 V AudioCache: notify(0xb1432500, 5, 0, 0)
08-05 13:16:05.057   332  7173 V AudioCache: ignored
08-05 13:16:05.057   332  7173 V AudioCache: notify(0xb1432500, 1, 0, 0)
08-05 13:16:05.057   332  7173 V AudioCache: prepared
08-05 13:16:05.057   332  2181 V AudioCache: wait - success
08-05 13:16:05.057   332  2181 V MediaPlayerService: start
08-05 13:16:05.057   332  2181 V AwesomePlayer: play_l() 
08-05 13:16:05.057   332  2181 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-05 13:16:05.057   332  2181 V AwesomePlayer: createAudioPlayer_l
08-05 13:16:05.057   332  2181 V AwesomePlayer: seekAudioIfNecessary_l() 
08-05 13:16:05.057   332  2181 V AwesomePlayer: startAudioPlayer_l() 
08-05 13:16:05.057   332  2181 D AudioPlayer: start of Playback, useOffload 0
08-05 13:16:05.057   332  2181 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-05 13:16:05.057   332  2181 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-05 13:16:05.059  7086  7086 V LGMDMManager: Create singleton instance
08-05 13:16:05.064   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-05 13:16:05.064   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
,08-05 13:16:05.064   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-05 13:16:05.064   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-05 13:16:05.064   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-05 13:16:05.064   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-05 13:16:05.064   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048416
08-05 13:16:05.064   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 13:16:05.064   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048576
08-05 13:16:05.064   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 13:16:05.064   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048656
08-05 13:16:05.064   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 13:16:05.064   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957049536
08-05 13:16:05.064   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 13:16:05.064   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-05 13:16:05.064   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-05 13:16:05.064   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-05 13:16:05.064   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-05 13:16:05.064   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-05 13:16:05.064   332  7175 V OMXCodec: allocateBuffersOnPort portIndex=1
08-05 13:16:05.064   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-05 13:16:05.064   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
08-05 13:16:05.064   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
08-05 13:16:05.065   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-05 13:16:05.065   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76a0 on output port
08-05 13:16:05.065   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-05 13:16:05.065   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-05 13:16:05.072   332  2181 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-05 13:16:05.072   332  2181 V AudioCache: notify(0xb1432500, 6, 0, 0)
08-05 13:16:05.072   332  2181 V AudioCache: ignored
08-05 13:16:05.073   332  2181 V MediaPlayerService: wait for playback complete
08-05 13:16:05.073   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.073   332  7176 V AudioCache: memcpy(0xaf006000, 0xb57ce000, 4096)
08-05 13:16:05.075   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.075   332  7176 V AudioCache: memcpy(0xaf007000, 0xb57ce000, 4096)
08-05 13:16:05.076   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.076   332  7176 V AudioCache: memcpy(0xaf008000, 0xb57ce000, 4096)
08-05 13:16:05.076   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.076   332  7176 V AudioCache: memcpy(0xaf009000, 0xb57ce000, 4096)
08-05 13:16:05.077   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.077   332  7176 V AudioCache: memcpy(0xaf00a000, 0xb57ce000, 4096)
,08-05 13:16:05.081   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.081   332  7176 V AudioCache: memcpy(0xaf00b000, 0xb57ce000, 4096)
08-05 13:16:05.082   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.082   332  7176 V AudioCache: memcpy(0xaf00c000, 0xb57ce000, 4096)
08-05 13:16:05.082   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.082   332  7176 V AudioCache: memcpy(0xaf00d000, 0xb57ce000, 4096)
08-05 13:16:05.083   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.083   332  7176 V AudioCache: memcpy(0xaf00e000, 0xb57ce000, 4096)
08-05 13:16:05.083   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.084   332  7176 V AudioCache: memcpy(0xaf00f000, 0xb57ce000, 4096)
08-05 13:16:05.084   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.084   332  7176 V AudioCache: memcpy(0xaf010000, 0xb57ce000, 4096)
,08-05 13:16:05.085   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.085   332  7176 V AudioCache: memcpy(0xaf011000, 0xb57ce000, 4096)
08-05 13:16:05.086   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.086   332  7176 V AudioCache: memcpy(0xaf012000, 0xb57ce000, 4096)
08-05 13:16:05.086   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.086   332  7176 V AudioCache: memcpy(0xaf013000, 0xb57ce000, 4096)
08-05 13:16:05.087   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.087   332  7176 V AudioCache: memcpy(0xaf014000, 0xb57ce000, 4096)
08-05 13:16:05.087   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.087   332  7176 V AudioCache: memcpy(0xaf015000, 0xb57ce000, 4096)
08-05 13:16:05.088   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.088   332  7176 V AudioCache: memcpy(0xaf016000, 0xb57ce000, 4096)
08-05 13:16:05.089   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.089   332  7176 V AudioCache: memcpy(0xaf017000, 0xb57ce000, 4096)
08-05 13:16:05.089   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.089   332  7176 V AudioCache: memcpy(0xaf018000, 0xb57ce000, 4096)
08-05 13:16:05.090   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.090   332  7176 V AudioCache: memcpy(0xaf019000, 0xb57ce000, 4096)
08-05 13:16:05.090  7143  7143 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:05.091   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.091   332  7176 V AudioCache: memcpy(0xaf01a000, 0xb57ce000, 4096)
08-05 13:16:05.092   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.092   332  7176 V AudioCache: memcpy(0xaf01b000, 0xb57ce000, 4096)
08-05 13:16:05.092   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.092   332  7176 V AudioCache: memcpy(0xaf01c000, 0xb57ce000, 4096)
08-05 13:16:05.093   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.093   332  7176 V AudioCache: memcpy(0xaf01d000, 0xb57ce000, 4096)
08-05 13:16:05.094  7143  7143 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 13:16:05.094  7143  7143 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 13:16:05.095  7143  7143 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 13:16:05.096   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.096   332  7176 V AudioCache: memcpy(0xaf01e000, 0xb57ce000, 4096)
08-05 13:16:05.096  7143  7143 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:05.096  7143  7143 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-05 13:16:05.096   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.096   332  7176 V AudioCache: memcpy(0xaf01f000, 0xb57ce000, 4096)
08-05 13:16:05.097   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.097   332  7176 V AudioCache: memcpy(0xaf020000, 0xb57ce000, 4096)
08-05 13:16:05.098   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.098   332  7176 V AudioCache: memcpy(0xaf021000, 0xb57ce000, 4096)
08-05 13:16:05.099   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.099   332  7176 V AudioCache: memcpy(0xaf022000, 0xb57ce000, 4096)
08-05 13:16:05.100   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.100   332  7176 V AudioCache: memcpy(0xaf023000, 0xb57ce000, 4096)
08-05 13:16:05.100   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.100   332  7176 V AudioCache: memcpy(0xaf024000, 0xb57ce000, 4096)
08-05 13:16:05.101   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.101   332  7176 V AudioCache: memcpy(0xaf025000, 0xb57ce000, 4096)
08-05 13:16:05.102   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.102   332  7176 V AudioCache: memcpy(0xaf026000, 0xb57ce000, 4096)
08-05 13:16:05.102  7060  7060 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08,-05 13:16:05.103   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.103   332  7176 V AudioCache: memcpy(0xaf027000, 0xb57ce000, 4096)
08-05 13:16:05.104   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.104   332  7176 V AudioCache: memcpy(0xaf028000, 0xb57ce000, 4096)
08-05 13:16:05.104   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.105   332  7176 V AudioCache: memcpy(0xaf029000, 0xb57ce000, 4096)
,08-05 13:16:05.109   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.109   332  7176 V AudioCache: memcpy(0xaf02a000, 0xb57ce000, 4096)
08-05 13:16:05.110   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.110   332  7176 V AudioCache: memcpy(0xaf02b000, 0xb57ce000, 4096)
08-05 13:16:05.111   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.111   332  7176 V AudioCache: memcpy(0xaf02c000, 0xb57ce000, 4096)
08-05 13:16:05.111   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.111   332  7176 V AudioCache: memcpy(0xaf02d000, 0xb57ce000, 4096)
08-05 13:16:05.112   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.112   332  7176 V AudioCache: memcpy(0xaf02e000, 0xb57ce000, 4096)
08-05 13:16:05.113   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.113   332  7176 V AudioCache: memcpy(0xaf02f000, 0xb57ce000, 4096)
08-05 13:16:05.113   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.114   332  7176 V AudioCache: memcpy(0xaf030000, 0xb57ce000, 4096)
08-05 13:16:05.114   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.114   332  7176 V AudioCache: memcpy(0xaf031000, 0xb57ce000, 4096)
08-05 13:16:05.115   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.115   332  7176 V AudioCache: memcpy(0xaf032000, 0xb57ce000, 4096)
08-05 13:16:05.115   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.115   332  7176 V AudioCache: memcpy(0xaf033000, 0xb57ce000, 4096)
08-05 13:16:05.116   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.116   332  7176 V AudioCache: memcpy(0xaf034000, 0xb57ce000, 4096)
,08-05 13:16:05.118   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.118   332  7176 V AudioCache: memcpy(0xaf035000, 0xb57ce000, 4096)
08-05 13:16:05.119   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.119   332  7176 V AudioCache: memcpy(0xaf036000, 0xb57ce000, 4096)
08-05 13:16:05.120   332  7176 V AudioCache: write(0xb57ce000, 4096)
08-05 13:16:05.120   332  7176 V AudioCache: memcpy(0xaf037000, 0xb57ce000, 4096)
08-05 13:16:05.120   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-05 13:16:05.120   332  7176 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-05 13:16:05.120   332  7176 V AwesomePlayer: postAudioEOS() 
08-05 13:16:05.120   332  7176 V AudioCache: write(0xb57ce000, 280)
08-05 13:16:05.120   332  7176 V AudioCache: memcpy(0xaf038000, 0xb57ce000, 280)
08-05 13:16:05.122   332  7173 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-05 13:16:05.122   332  7173 V AwesomePlayer: onStreamDone
08-05 13:16:05.122   332  7173 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-05 13:16:05.122   332  7173 V AudioCache: notify(0xb1432500, 2, 0, 0)
08-05 13:16:05.122   332  7173 V AudioCache: playback complete
08-05 13:16:05.122   332  7173 V AwesomePlayer: pause_l() 
08-05 13:16:05.122   332  7173 V AudioCache: notify(0xb1432500, 7, 0, 0)
08-05 13:16:05.122   332  7173 V AudioCache: ignored
08-05 13:16:05.122   332  7173 V AwesomePlayer: cancelPlayerEvents
08-05 13:16:05.122   332  2181 V AudioCache: wait - success
08-05 13:16:05.122   332  2181 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-05 13:16:05.122   332  7173 D AudioPlayer: Pause Playback at 1068125
08-05 13:16:05.122   332  2181 V AwesomePlayer: reset_l() 
08-05 13:16:05.122   332  2181 V AudioCache: notify(0xb1432500, 8, 0, 0)
08-05 13:16:05.122   332  2181 V AudioCache: ignored
08-05 13:16:05.122   332  2181 V AwesomePlayer: cancelPlayerEvents
08-05 13:16:05.122   332  2181 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-05 13:16:05.122   332  2181 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-05 13:16:05.122   332  2181 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-05 13:16:05.122   332  2181 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-05 13:16:05.122   332  2181 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-05 13:16:05.123   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-05 13:16:05.123   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-05 13:16:05.123   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-05 13:16:05.123   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 0
08-05 13:16:05.123   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-05 13:16:05.123   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 0
08-05 13:16:05.123   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-05 13:16:05.123   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
08-05 13:16:05.123   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-05 13:16:05.123   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 0
08-05 13:16:05.123   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-05 13:16:05.124   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-05 13:16:05.124   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76a0 on port 1
08-05 13:16:05.124   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-05 13:16:05.124   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 1
08-05 13:16:05.124   33,2  7175 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-05 13:16:05.124   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb00 on port 1
08-05 13:16:05.124   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-05 13:16:05.124   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb50 on port 1
08-05 13:16:05.124   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 13:16:05.124   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-05 13:16:05.124   332  2181 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-05 13:16:05.124   332  2181 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-05 13:16:05.124   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-05 13:16:05.124   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-05 13:16:05.124   332  7175 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-05 13:16:05.124   332  2181 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-05 13:16:05.124   332  2181 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-05 13:16:05.124   332  2181 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-05 13:16:05.126   332  2181 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-05 13:16:05.126   332  2181 D AudioPlayer: AudioPlayer releasing audio source
08-05 13:16:05.126   332  2181 D AudioPlayer: AudioPlayer done releasing audio source
08-05 13:16:05.126   332  2181 V AwesomePlayer: reset_l() 
08-05 13:16:05.126   332  2181 V AwesomePlayer: cancelPlayerEvents
08-05 13:16:05.126   332  2181 V AwesomePlayer: ~AwesomePlayer call
08-05 13:16:05.126   332  2181 V AwesomePlayer: reset_l() 
08-05 13:16:05.126   332  2181 V AwesomePlayer: cancelPlayerEvents
08-05 13:16:05.126  7086  7172 V SoundPool: close(31)
08-05 13:16:05.126  7086  7172 V SoundPool: pointer = 0xa001f000, size = 205080, sampleRate = 48000, numChannels = 2
08-05 13:16:05.134  7086  7086 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-05 13:16:05.134  7086  7086 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-05 13:16:05.144  7086  7086 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3356,
08-05 13:16:05.331  6765  6765 I UEI.SmartControl: Supports setup maps: true
08-05 13:16:05.334  6765  6765 D UEI.SmartControl: QS start statue = true Error code = 0
08-05 13:16:05.334  6765  6765 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-05 13:16:05.334  6765  6765 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-05 13:16:05.334  6765  6765 I UEI.SmartControl: ### init IR Blaster...
,08-05 13:16:05.339  6765  6765 D serial_port: Configuring serial port
,08-05 13:16:05.340  6765  6765 E UEI.SmartControl: UEIBLaster setting for 616
08-05 13:16:05.340  6765  6765 I UEI.SmartControl: Setting serial record hearder size = 2
08-05 13:16:05.340  6765  6765 I UEI.SmartControl: configuring settings for MAXQ616
,08-05 13:16:05.340  6765  6765 I UEI.SmartControl: Get version...
08-05 13:16:05.358  6765  7178 D UEI.SmartControl: serial port data available: 21
,08-05 13:16:05.385  6765  6765 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-05 13:16:05.385  6765  6765 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-05 13:16:05.385  6765  6765 I UEI.SmartControl: QS saving settings...
08-05 13:16:05.387  6765  6765 D UEI.SmartControl: IR Blaster version: 25672567
,08-05 13:16:05.403  6765  7178 D UEI.SmartControl: serial port data available: 4
,08-05 13:16:05.438  6765  7187 I UEI.SmartControl: Device manager: loading config....
,08-05 13:16:05.439  6765  6765 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-05 13:16:05.442  6765  6765 E UEI.SmartControl: Services init done
08-05 13:16:05.442  6765  6765 D UEI.SmartControl: QS Service init finished
08-05 13:16:05.443  6765  6765 D UEI.SmartControl: QS Service version name: 2.1.91
,08-05 13:16:05.443  6765  6765 D UEI.SmartControl: QS Service version code: 201091
08-05 13:16:05.444  6765  6765 D UEI.SmartControl: Service requested: Control
08-05 13:16:05.444  6765  7187 D UEI.SmartControl: ----------- loading internal config...
,08-05 13:16:05.450  6765  7187 E UEI.SmartControl: Loading SETTINGS...
08-05 13:16:05.454  6765  6765 D UEI.SmartControl: Request IControl service: devices are loaded...
08-05 13:16:05.455  6765  7187 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-05 13:16:05.460  7086  7086 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-05 13:16:05.462  6765  6782 I UEI.SmartControl: ------ IControl API: 11
08-05 13:16:05.462  6765  6782 D UEI.SmartControl: File observer start...
08-05 13:16:05.463  6765  6782 E UEI.SmartControl: IR Port is disabled: false
08-05 13:16:05.463  6765  6782 D UEI.SmartControl: Starting file observer...
08-05 13:16:05.464  6765  6782 I UEI.SmartControl: Registering callback...
08-05 13:16:05.464  6765  6765 D UEI.SmartControl: Internal service binding...
08-05 13:16:05.464  6765  6801 I UEI.SmartControl: ------ IControl API: 19
08-05 13:16:05.466  6765  6801 I UEI.SmartControl: Registering Services Ready callback...
08-05 13:16:05.466  6765  6801 I UEI.SmartControl: Notify client services are ready...
08-05 13:16:05.470  7086  7102 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-05 13:16:05.471  7086  7170 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
,08-05 13:16:05.471  7086  7170 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-05 13:16:05.472  7086  7086 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-05 13:16:05.473  7086  7086 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-05 13:16:05.474  6765  6780 I UEI.SmartControl: ------ IControl API: 8
08-05 13:16:05.475  7086  7086 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-05 13:16:05.476  7086  7086 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-05 13:16:05.476  7086  7086 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-05 13:16:05.476  6765  7186 I UEI.SmartControl: Notify AllClients services are ready: 0
08-05 13:16:05.477  6765  7186 D UEI.SmartControl: -----service ready thread exits
08-05 13:16:05.477  7086  7103 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-05 13:16:05.477  7086  7086 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-05 13:16:05.477  7086  7170 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-05 13:16:05.478  7086  7170 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-05 13:16:05.478  7086  7086 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-05 13:16:05.479  7086  7086 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-05 13:16:05.482  7086  7086 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-05 13:16:05.488  7086  7086 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
08-05 13:16:05.489  7086  7086 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-05 13:16:05.490  7086  7086 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-05 13:16:05.491  7086  7086 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 13:16:05.491  7086  7086 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-05 13:16:05.492  7086  7086 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-05 13:16:05.493  7086  7086 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-05 13:16:05.494  7086  7086 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-05 13:16:05.495  7086  7086 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470395765494]
,08-05 13:16:05.499  7086  7086 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-05 13:16:05.500  1036  2035 I ActivityManager: Killing 6539:com.android.gallery3d/u0a27 (adj 15): empty #17
08-05 13:16:05.520  7086  7189 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-05 13:16:05.528  1036  2035 I ActivityManager: Killing 6512:com.lge.email/u0a23 (adj 15): empty #18
,08-05 13:16:05.627  1036  1999 W libprocessgroup: failed to open /acct/uid_10027/pid_6539/cgroup.procs: No such file or directory
,08-05 13:16:05.643  1036  1944 W libprocessgroup: failed to open /acct/uid_10023/pid_6512/cgroup.procs: No such file or directory
08-05 13:16:05.656  7086  7086 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-05 13:16:05.658  7086  7086 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 13:16:05.659  7086  7086 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-05 13:16:05.659  7086  7086 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-05 13:16:05.660  7086  7086 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-05 13:16:05.660  7086  7086 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-05 13:16:05.661  7086  7086 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-05 13:16:05.677  7086  7086 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-05 13:16:06.183  1036  2036 D WifiServiceImplEx: setWifiEnabled: true pid=6900, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 13:16:06.185  1036  2036 D WifiService: setWifiEnabled: true pid=6900, uid=10118
08-05 13:16:06.186  1036  2036 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 13:16:06.209  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 13:16:06.210  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 13:16:06.210  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-05 13:16:06.213  1036  1539 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-05 13:16:06.213  1036  1539 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-05 13:16:06.215  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-05 13:16:06.215  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-05 13:16:06.215  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-05 13:16:06.215  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-05 13:16:06.216  1036  1539 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-05 13:16:06.216  1036  1539 E WifiHW  : unknown target_country: EU , set to default
08-05 13:16:06.216  1036  1539 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-05 13:16:06.216  1036  1539 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-05 13:16:06.216  1036  1539 I WifiUtil: gEnableBmps=1
08-05 13:16:06.280  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 13:16:06.295  1036  1109 D Tethering: MasterInitialState.processMessage what=3
08-05 13:16:06.310  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 13:16:06.316  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:06.317  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:06.319  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:06.321  6377  6377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-05 13:16:06.329  6377  7024 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-05 13:16:06.342  1036  1109 D Tethering: MasterInitialState.processMessage what=3
,08-05 13:16:06.348  5765  5765 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-05 13:16:06.354  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:06.357  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 13:16:06.387  5765  5765 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-05 13:16:06.413  2154  2154 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-05 13:16:06.447  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-05 13:16:06.478  1036  1926 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7217 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-05 13:16:06.485  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:06.486  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 13:16:06.580  7217  7217 I AppUp4:AppBoxCP: onCreate
,08-05 13:16:06.581  7217  7217 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-05 13:16:06.592  7217  7217 I AppUp4:DB:  setFingerPrint start
08-05 13:16:06.592  7217  7217 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-05 13:16:06.601  7217  7217 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,08-05 13:16:06.601  7217  7217 I AppUp4:DB:  SDK version = 21
08-05 13:16:06.601  7217  7217 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-05 13:16:06.603  7217  7217 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-05 13:16:06.605  7217  7217 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-05 13:16:06.605  7217  7217 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:06.607  7217  7217 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 13:16:06.608  7217  7217 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-05 13:16:06.615  7217  7217 I AppUp4:CustModeStarterReceiver: onReceive
08-05 13:16:06.656  7217  7217 D LgDataFeature: LgDataFeature() Constructor: none
08-05 13:16:06.656  7217  7217 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 13:16:06.665  7217  7217 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@b619a89
08-05 13:16:06.665  7217  7217 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 13:16:06.665  7217  7217 D AppUp4:CustFacade: isPhone : true
08-05 13:16:06.666  7217  7217 D AppUp4:CustModeStarterReceiver: begin check event
08-05 13:16:06.666  7217  7217 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-05 13:16:06.666  7217  7217 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-05 13:16:06.667  7217  7236 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-05 13:16:06.668  7217  7236 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-05 13:16:06.668  7217  7236 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-05 13:16:06.671  1036  1890 I ActivityManager: Killing 6601:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-05 13:16:06.759  1036  1907 W libprocessgroup: failed to open /acct/uid_10061/pid_6601/cgroup.procs: No such file or directory
08-05 13:16:06.760  4691  4691 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:06.761  4691  4691 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-05 13:16:06.765  4691  4691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 13:16:06.769  4691  4691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 13:16:06.783  4691  7249 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-05 13:16:06.786  4691  7250 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:06.786  4691  7250 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 13:16:06.832  1036  1926 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7251 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-05 13:16:06.926  1036  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-05 13:16:06.927  1036  1109 D Tethering: InitialState.processMessage what=4
08-05 13:16:06.927  1036  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-05 13:16:06.940   328   895 D SoftapController: Softap fwReload - Ok
08-05 13:16:06.944  1036  1539 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (717ms)
08-05 13:16:06.946   328   895 D CommandListener: Setting iface cfg
08-05 13:16:06.946   328   895 D CommandListener: Trying to bring down wlan0
08-05 13:16:06.947   328   895 D CommandListener: Clearing all IP addresses on wlan0
08-05 13:16:06.949  1036  1539 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-05 13:16:06.951  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 13:16:06.951  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
08-05 13:16:06.951  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 13:16:06.951  7269  7269 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 13:16:06.951  7269  7269 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 13:16:06.957  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:06.959  1946  1946 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-05 13:16:06.960  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:06.961  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-05 13:16:06.962  1036  1539 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-05 13:16:06.962  1036  1539 D WifiMonitor: connecting to supplicant
08-05 13:16:06.964  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 13:16:06.980  7269  7269 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-05 13:16:07.013  7269  7269 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-05 13:16:07.014  7269  7269 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-05 13:16:07.098  1036  1052 I art     : Explicit concurrent mark sweep GC freed 66255(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 1.648ms total 198.763ms
,08-05 13:16:07.119  7251  7251 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 13:16:07.120  7251  7251 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 13:16:07.121  7251  7251 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 13:16:07.121  7251  7251 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-05 13:16:07.147  7269  7269 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-05 13:16:07.174  7251  7251 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-05 13:16:07.183  7251  7251 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-05 13:16:07.200  7269  7269 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-05 13:16:07.210  7251  7251 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 13:16:07.210  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-05 13:16:07.210  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-05 13:16:07.211  7269  7269 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-05 13:16:07.211  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-05 13:16:07.211  1036  1539 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-05 13:16:07.212  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-05 13:16:07.212  1036  7277 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-05 13:16:07.212  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 13:16:07.212  1036  7277 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-05 13:16:07.213  1036  7277 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-05 13:16:07.213  1036  7277 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-05 13:16:07.213  1036  1539 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-05 13:16:07.213  1036  1539 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-05 13:16:07.214  1036  1539 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-05 13:16:07.214  1036  1539 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-05 13:16:07.214  1036  1539 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-05 13:16:07.214  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 13:16:07.214  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
08-05 13:16:07.214  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 13:16:07.215  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:07.215  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:07.215  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:07.215  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:07.215  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 13:16:07.215  1036  1539 D WifiNative-wlan0: doBoolean: SET update_config 1
08-05 13:16:07.217  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:07.217  1036  1539 D WifiNative-wlan0: SET update_config 1: returned true
08-05 13:16:07.217  1036  1539 D WifiConfigStore: Loading config and enabling all networks 
08-05 13:16:07.217  1036  1539 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-05 13:16:07.217  1036  1539 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-05 13:16:07.217  1946  1946 D WfdService: Waiting for WifiP2p enabling
08-05 13:16:07.219  6900  6900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 13:16:07.219  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 13:16:07.219  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:07.219  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:07.219  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 13:16:07.,219  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 13:16:07.219  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 13:16:07.219  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 13:16:07.219  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 13:16:07.219  6900  6900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 13:16:07.219  6900  6900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 13:16:07.219  6900  6900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 13:16:07.219  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 13:16:07.219  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:07.219  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:07.219  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 13:16:07.219  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 13:16:07.219  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 13:16:07.219  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 13:16:07.219  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 13:16:07.219  6900  6900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 13:16:07.219  6900  6900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 13:16:07.220  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-05 13:16:07.220  1036  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-05 13:16:07.224  1036  1539 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-05 13:16:07.233  1036  1539 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,08-05 13:16:07.234  1036  1539 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-05 13:16:07.235  1036  1539 D WifiStateMachine: enableVerboseLogging : level 2
08-05 13:16:07.235  1036  1539 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-05 13:16:07.235  1036  1539 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-05 13:16:07.235  1036  1539 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-05 13:16:07.235  1036  1539 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-05 13:16:07.235  1036  1539 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-05 13:16:07.236  1036  1539 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-05 13:16:07.236  1036  1539 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-05 13:16:07.236  1036  1539 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-05 13:16:07.236  1036  1539 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-05 13:16:07.236  1036  1539 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-05 13:16:07.236  1036  1539 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-05 13:16:07.237  1036  1539 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-05 13:16:07.237  1036  1539 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-05 13:16:07.237  1036  1539 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-05 13:16:07.238  1036  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 13:16:07.238  1036  1539 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-05 13:16:07.238  1946  1946 D WfdsService: Supplicant Connection state is changed : true
08-05 13:16:07.238  1946  2307 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-05 13:16:07.238  1946  2307 D WfdsService: Set the WFDS Monitor: true
08-05 13:16:07.238  1036  1539 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-05 13:16:07.238  1946  2307 D WfdsMonitor: WfdsMonitorThread create
08-05 13:16:07.238  1036  1539 D WifiNative-HAL: Setting external_sim to 1
08-05 13:16:07.238  1036  1539 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-05 13:16:07.238  1946  2307 D WfdsMonitor: WFDS Monitor is created and started
08-05 13:16:07.238  1946  2307 D WfdsService: WiFi: Supplicant connection re-established
08-05 13:16:07.238  1036  1539 D WifiNative-wlan0: SET external_sim 1: returned true
08-05 13:16:07.238  1036  1539 I WifiNative-HAL: startHal
08-05 13:16:07.239  1036  1539 D wifi    : setting scan oui 0xaf6afe60
08-05 13:16:07.239  1036  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 13:16:07.239  1036  1539 I WifiNative-HAL: startHal
08-05 13:16:07.239  1036  1539 D wifi    : setting scan oui 0xaf6afe60
08-05 13:16:07.239  1036  1539 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-05 13:16:07.240  1036  1539 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-05 13:16:07.240  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-05 13:16:07.240  7269  7269 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-05 13:16:07.240  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-05 13:16:07.240  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-05 13:16:07.240  7269  7269 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 13:16:07.240  1946  7278 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-05 13:16:07.240  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 13:16:07.240  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-05 13:16:07.241  7269  7269 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-05 13:16:07.241  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-05 13:16:07.241  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-S,TART
08-05 13:16:07.241  7269  7269 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-05 13:16:07.241  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-05 13:16:07.241  7251  7251 D LgDataFeature: LgDataFeature() Constructor: none
08-05 13:16:07.241  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-05 13:16:07.241  1946  7278 E CtrlSupplicant: Succeed to open control connection
08-05 13:16:07.241  7251  7251 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 13:16:07.241  7269  7269 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 13:16:07.242  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 13:16:07.242  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-05 13:16:07.242  7269  7269 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-05 13:16:07.242  1946  7278 E CtrlSupplicant: Succeed to open monitor connection
08-05 13:16:07.242  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-05 13:16:07.242  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 13:16:07.242  7269  7269 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-05 13:16:07.243  1946  7278 D WfdsMonitor: Supplicant connection established
08-05 13:16:07.243  1946  2307 D WfdsService: Connected to the supplicant for wfds
08-05 13:16:07.243  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-05 13:16:07.246  1036  1539 E WifiNative: : [337,596,979 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-05 13:16:07.246  1036  1539 D WifiNative-wlan0: doBoolean: RECONNECT
08-05 13:16:07.247  1036  1539 D WifiNative-wlan0: RECONNECT: returned true
08-05 13:16:07.247  1036  1539 D WifiNative-wlan0: doString: [STATUS]
08-05 13:16:07.247  1036  1539 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-05 13:16:07.247  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 13:16:07.247  1036  7277 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-05 13:16:07.247  1036  7277 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-05 13:16:07.247  1036  1539 D WifiNative-wlan0: SET ps 1: returned true
08-05 13:16:07.248  1036  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:07.249   328   895 D CommandListener: Setting iface cfg
08-05 13:16:07.249   328   895 D CommandListener: Trying to bring up p2p0
08-05 13:16:07.249  1036  1538 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-05 13:16:07.249  1036  1538 D LGWifiP2pService: P2pEnablingState,
08-05 13:16:07.249  1036  1538 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:07.249  1036  1538 D LGWifiP2pService: P2p socket connection successful
08-05 13:16:07.249  1036  1538 D LGWifiP2pService: P2pEnabledState
,08-05 13:16:07.249  1036  1538 D LGWifiP2pService: sending p2p connection changed broadcast
08-05 13:16:07.249  1036  1538 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-05 13:16:07.250  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-05 13:16:07.250  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-05 13:16:07.250  1946  1946 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-05 13:16:07.251  1036  1557 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:07.251  1036  1557 I WifiNative-HAL: startHal
08-05 13:16:07.251  1036  1558 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:07.252  1036  1538 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-05 13:16:07.252  1036  1538 D WifiNative-p2p0: doBoolean: SET device_name G3
08-05 13:16:07.252  1036  1538 D WifiNative-p2p0: SET device_name G3: returned true
08-05 13:16:07.252  1036  1538 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-05 13:16:07.252  1036  1538 D LGWifiP2pService: before postfix = G3
08-05 13:16:07.252  1946  1946 D WfdsService: WifiP2pState is changed : true
08-05 13:16:07.252  1036  1538 D WifiServerServiceExt: postfix byte check : 2
08-05 13:16:07.252  1036  1538 D LGWifiP2pService: after postfix = G3
08-05 13:16:07.252  1036  1538 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-05 13:16:07.252  1036  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf6afe60
08-05 13:16:07.252  1036  1557 D wifi    : failed to get capabilities : -3
08-05 13:16:07.252  1036  1557 E WifiScanningService: could not get scan capabilities
08-05 13:16:07.252  1036  1538 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-05 13:16:07.252  1036  1538 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-05 13:16:07.253  1036  1538 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-05 13:16:07.253  1036  1538 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-05 13:16:07.253  1946  1946 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-05 13:16:07.253  1036  1538 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-05 13:16:07.253  1036  1538 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-05 13:16:07.253  1036  1538 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-05 13:16:07.253  1036  1538 D WifiNative-HAL: p2pGetDeviceAddress
08-05 13:16:07.253  1036  1538 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-05 13:16:07.254  1946  2307 D WfdsService: Receive the WFDS_ENABLE Method
08-05 13:16:07.254  1946  2307 D WfdsService: Set the WFDS Monitor: true
08-05 13:16:07.254  1946  2307 D WfdsService: Connected to the supplicant for wfds
08-05 13:16:07.254  1946  2307 D WfdsJNI : doCommand: WFDS_SET TRUE
08-05 13:16:07.254  7269  7269 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-05 13:16:07.254  1946  2307 D WfdsService: selectPreferredScanChannel [36]
08-05 13:16:07.254  1946  2307 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-05 13:16:07.255  1946  1946 D WfdsService: isConnected: false
08-05 13:16:07.255  1036  1538 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-05 13:16:07.255  1036  1538 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-05 13:16:07.255  1036  1538 D WifiNative-p2p0: P2P_FLUSH: returned true
08-05 13:16:07.255  1036  1538 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-05 13:16:07.255  1036  1538 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-05 13:16:07.255  1036  1538 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-05 13:16:07.256  1036  1538 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-05 13:16:07.256  1036  1538 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-05 13:16:07.256  1036  1539 E WifiStateMachine:  Dis,connectedState CMD_SET_OPERATIONAL_MODE 1 0
08-05 13:16:07.256  1036  1539 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-05 13:16:07.257  1946  1946 I WfdStateTracker: handleP2pThisDeviceChanged
08-05 13:16:07.257  1946  1946 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-05 13:16:07.257  1946  1946 D WfdsService: Update P2p Interface State: 3
08-05 13:16:07.257  1036  1539 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-05 13:16:07.257  1036  1539 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-05 13:16:07.257  1036  1539 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-05 13:16:07.258  1036  1539 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-05 13:16:07.258  1036  1539 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-05 13:16:07.258  1036  1539 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-05 13:16:07.263  7269  7269 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,08-05 13:16:07.264  1036  1538 D WifiNative-p2p0: SAVE_CONFIG: returned true,
,08-05 13:16:07.264  1036  1538 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-05 13:16:07.264  1036  1538 D LGWifiP2pService: InactiveState
08-05 13:16:07.264  1036  1538 D LGWifiP2pService: InactiveState{ when=-8ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler },
08-05 13:16:07.264  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:07.264  1036  1538 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-05 13:16:07.264  1036  1538 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-05 13:16:07.265  1036  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:07.265  7269  7269 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 13:16:07.265  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:07.265  1036  1538 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:07.265  7269  7269 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ,
08-05 13:16:07.265  1036  7277 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 13:16:07.265  1036  7277 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 13:16:07.265  1036  7277 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 13:16:07.265  1036  7277 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 13:16:07.266  7269  7269 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 13:16:07.266  7269  7269 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:07.266  1036  7277 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD],
08-05 13:16:07.266  1036  7277 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:07.266  1036  7277 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:07.266  1036  7277 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:07.266  7269  7269 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:07.266  1036  7277 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 13:16:07.267  1036  7277 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:07.267  1036  7277 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:07.267  1036  7277 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD,
08-05 13:16:07.267  1036  1538 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:07.267  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:07.267  1036  1538 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:07.267  1036  1538 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:07.267  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:07.267  1036  1538 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:07.268  1036  1036 E WifiServerServiceExt: No p2p device connected
,08-05 13:16:07.268  1036  1538 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:07.268  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:07.268  1036  1538 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:07.268  1946  2307 W WfdsService: DefaultState - msg [9441285] is not handled
08-05 13:16:07.268  1946  7278 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 13:16:07.268  1946  7278 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 13:16:07.269  1946  7278 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-05 13:16:07.269  1036  1539 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-05 13:16:07.269  1036  1539 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-05 13:16:07.270  1036  1539 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-05 13:16:07.270  1036  1539 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-05 13:16:07.270  7269  7269 E wpa_supplicant: disconnect_rssi_lvl: -100
08-05 13:16:07.271  1036  1539 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-05 13:16:07.271  1036  1539 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
,08-05 13:16:07.271  1036  1539 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-05 13:16:07.271  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-05 13:16:07.272  7269  7269 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 13:16:07.272  7269  7269 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 13:16:07.272  1036  7277 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 13:16:07.272  1036  7277 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-05 13:16:07.273  1036  7277 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 13:16:07.273  1036  7277 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 13:16:07.273  7269  7269 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 13:16:07.273  7269  7269 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:07.273  1036  7277 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 13:16:07.273  1036  7277 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:07.273  1036  7277 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD,
08-05 13:16:07.273  1036  7277 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:07.273  1946  7278 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 13:16:07.273  1036  1539 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-05 13:16:07.274  1036  1538 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:07.274  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:07.274  7269  7269 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:07.274  1036  1539 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
,08-05 13:16:07.274  1036  1539 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-05 13:16:07.274  1036  7277 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 13:16:07.274  1036  7277 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:07.275  1036  7277 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:07.275  1036  7277 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:07.275  1036  1539 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-05 13:16:07.275  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
,08-05 13:16:07.275  7269  7269 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-05 13:16:07.275  7269  7269 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 13:16:07.276  1036  7277 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-05 13:16:07.276  1036  7277 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 13:16:07.276  1036  7277 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 13:16:07.276  1036  7277 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 13:16:07.276  1946  7278 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 13:16:07.276  1036  1539 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
,08-05 13:16:07.276  1036  1539 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-05 13:16:07.276  1036  1539 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-05 13:16:07.276  1036  1539 D WifiNative-wlan0: doBoolean: SCAN
,08-05 13:16:07.277  1036  1539 D WifiNative-wlan0: SCAN: returned false,
08-05 13:16:07.277  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=337631  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 13:16:07.278  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=337632  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 13:16:07.279  1036  1539 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 13:16:07.279  1036  1539 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-05 13:16:07.280  1036  1539 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 13:16:07.280  1036  1539 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 13:16:07.280  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:07.280  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 13:16:07.280  1036  1539 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 13:16:07.281  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:07.281  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
08-05 13:16:07.281  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-05 13:16:07.282  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:07.283  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 13:16:07.283  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-05 13:16:07.350  7251  7251 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-05 13:16:07.388  3386  3386 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 13:16:07.388  3386  3386 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:07.388  3386  3386 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-05 13:16:07.393  7251  7251 I HubEmail: JNI_OnLoad()
08-05 13:16:07.393  7251  7251 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 13:16:07.393  7251  7251 I HubEmail: registerNatives()
08-05 13:16:07.393  7251  7251 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 13:16:07.393  7251  7251 I HubEmail: registerNativeMethods()
08-05 13:16:07.393  7251  7251 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 13:16:07.394  7251  7251 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-05 13:16:07.436  1036  1052 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7288 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-05 13:16:07.442  1036  1378 D PowerManagerServiceEx: acquireWakeLockInternal: lock=98461650, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
08-05 13:16:07.444  1036  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2717f5d9 type 2 when 337773 com.google.android.gms} when 337773
08-05 13:16:07.445  7251  7287 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:07.448  7114  7284 W FormManager: Network not available. Please check & try again.
08-05 13:16:07.459  7114  7285 V FormManager: Network unavailable.
,08-05 13:16:07.461  7114  7285 V FormManager: Network unavailable.
08-05 13:16:07.478  1036  1052 I ActivityManager: Killing 6672:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-05 13:16:07.508  2653  2653 D [Concierge]Service: onStartCommand(). Type : 9
,08-05 13:16:07.512  1036  2036 W libprocessgroup: failed to open /acct/uid_10080/pid_6672/cgroup.procs: No such file or directory
08-05 13:16:07.601  7288  7288 D LgDataFeature: LgDataFeature() Constructor: none
08-05 13:16:07.601  7288  7288 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 13:16:07.605  7288  7288 D PhoneMonitor: Register our PhoneStateListener
,08-05 13:16:07.628  7288  7288 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-05 13:16:07.632  7288  7288 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-05 13:16:07.675  7288  7288 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-05 13:16:07.679  7288  7288 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-05 13:16:07.681  7288  7288 D TelephonyAutoProfiling: [parse] Load xml
08-05 13:16:07.688  7288  7288 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-05 13:16:07.688  7288  7288 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-05 13:16:07.688  7288  7288 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-05 13:16:07.689  7288  7288 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-05 13:16:07.689  7288  7288 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-05 13:16:07.689  7288  7288 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-05 13:16:07.689  7288  7288 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-05 13:16:07.689  7288  7288 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-05 13:16:07.689  7288  7288 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-05 13:16:07.689  7288  7288 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-05 13:16:07.689  7288  7288 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-05 13:16:07.689  7288  7288 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-05 13:16:07.689  7288  7288 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-05 13:16:07.690  7288  7288 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-05 13:16:07.690  7288  7288 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
,08-05 13:16:07.690  7288  7288 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-05 13:16:07.690  7288  7288 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-05 13:16:07.708  7288  7288 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-05 13:16:07.713  1036  1051 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7308 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 13:16:07.714  1036  1051 I ActivityManager: Killing 6720:com.lge.eula/1000 (adj 15): empty #17
08-05 13:16:07.765  1036  1729 W libprocessgroup: failed to open /acct/uid_1000/pid_6720/cgroup.procs: No such file or directory
,08-05 13:16:07.810  1036  7277 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-05 13:16:07.810  1036  7277 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-05 13:16:07.810  1036  7277 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-05 13:16:07.811  1036  7277 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-05 13:16:07.811  1036  7277 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-05 13:16:07.811  7269  7269 E wpa_supplicant: USIM:  scard_init function
08-05 13:16:07.812  7269  7269 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-05 13:16:07.813  1036  1539 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-05 13:16:07.815  1036  7277 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-05 13:16:07.815  1036  7277 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-05 13:16:07.817  1036  1539 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-05 13:16:07.818  1036  1539 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-05 13:16:07.819  1036  1539 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-05 13:16:07.819  1036  1539 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-05 13:16:07.833  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=338186  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-05 13:16:07.838  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:07.838  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 13:16:07.841  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:07.844  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:07.844  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:07.844  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-05 13:16:07.846  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=338199  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-05 13:16:07.851  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:07.851  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 13:16:07.851  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-05 13:16:07.853  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 13:16:07.853  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-05 13:16:07.864  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:07.864  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 13:16:07.865  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 13:16:07.928  7269  7269 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-05 13:16:07.930  1036  1109 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-05 13:16:07.932  1036  7277 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-05 13:16:07.932  1036  7277 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-05 13:16:07.932  1036  7277 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-05 13:16:07.932  1036  1539 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-05 13:16:07.933  1036  7277 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-05 13:16:07.933  1036  1539 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-05 13:16:07.933  1036  7277 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,08-05 13:16:07.933  1036  7277 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 13:16:07.933  1036  1539 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-05 13:16:07.934  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-05 13:16:07.935  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 13:16:07.936  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=338289  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-05 13:16:07.936  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=338290  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-05 13:16:07.937  1036  1539 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=338290
08-05 13:16:07.937  1036  1539 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=338291
08-05 13:16:07.938  1036  1539 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=338291
08-05 13:16:07.938  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=338291
08-05 13:16:07.938  1036  1539 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=338292
08-05 13:16:07.939  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=338292  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-05 13:16:07.942  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 13:16:07.943  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-05 13:16:07.946  1036  7277 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 13:16:07.946  1036  7277 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 13:16:07.947  7269  7269 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 13:16:07.947  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=338300  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-05 13:16:07.948  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:07.948  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:07.948  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-05 13:16:07.949  7269  7269 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 13:16:07.949  1036  7277 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-05 13:16:07.949  1036  7277 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 13:16:07.949  1036  7277 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 13:16:07.949  1036  7277 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-05 13:16:07.949  1036  7277 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 13:16:07.949  1036  7277 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 13:16:07.950  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=338303  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-05 13:16:07.951  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:07.951  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:07.951  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-05 13:16:07.951  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 13:16:07.951  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-05 13:16:07.951  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=338304  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-05 13:16:07.952  1036  1539 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=338305
08-05 13:16:07.952  1036  7277 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 13:16:07.952  1036  1539 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=338305
08-05 13:16:07.952  1036  7277 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 13:16:07.953  1036  1539 D WifiNative-wlan0: doString: [STATUS]
08-05 13:16:07.953  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 13:16:07.953  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-05 13:16:07.954  1036  7277 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 13:16:07.954  1036  7277 E Wif,iMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 13:16:07.954  1036  1539 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-05 13:16:07.956  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:07.957  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:07.957  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-05 13:16:07.959  1036  1539 I WifiServiceExtension: setVHTCapabilityType  : false
08-05 13:16:07.959  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:07.965  1036  1539 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-05 13:16:07.965  1036  1539 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-05 13:16:07.968  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:07.968  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:07.968  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-05 13:16:07.970  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:07.970  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:07.970  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-05 13:16:07.977  1036  1539 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-05 13:16:07.977  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:07.977  1036  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 13:16:07.977  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 13:16:07.977  1036  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 13:16:07.977  1036  1546 D ConnectivityService: Got NetworkAgent Messenger
08-05 13:16:07.977  1036  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-05 13:16:07.977  1036  1546 D ConnectivityService: NetworkAgent connected
08-05 13:16:07.977  1036  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 13:16:07.977  1036  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 13:16:07.978  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:07.980  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:07.980  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 13:16:07.981  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:07.981  1036  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 13:16:07.981  1036  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 13:16:07.981  1036  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 13:16:07.981  1036  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 13:16:07.981  1036  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 13:16:07.984  1036  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-05 13:16:07.994   328   895 D CommandListener: Setting iface cfg
,08-05 13:16:08.017  1036  1707 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7328 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-05 13:16:08.018  1036  1707 I ActivityManager: Killing 6737:com.lge.bnr/1000 (adj 15): empty #17
08-05 13:16:08.086  1036  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_6737/cgroup.procs: No such file or directory
,08-05 13:16:08.102  1036  1539 E WifiStateMachine: Start Dhcp Watchdog 2
,08-05 13:16:08.102  1036  7327 D DhcpStateMachine: StoppedState
08-05 13:16:08.102  1036  7327 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:08.102  1036  7327 D DhcpStateMachine: WaitBeforeStartState
08-05 13:16:08.103  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 13:16:08.103  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-05 13:16:08.104  1036  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=338457  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 13:16:08.106  1036  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=338459  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 13:16:08.107  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=338460  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 13:16:08.110  1036  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=338463  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 13:16:08.111  1036  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=338464  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 13:16:08.113  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=338466  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 13:16:08.116  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:292799] from screen [on:0 period:1516952884] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 13:16:08.119  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1516952886] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 13:16:08.119  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 13:16:08.126  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:08.127  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:08.127  1036  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:08.128  1036  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:08.128  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:08.129  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:08.130  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=148,0,0
08-05 13:16:08.130  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=148,0,0
08-05 13:16:08.131  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-05 13:16:08.131  7269  7269 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-05 13:16:08.132  1036  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-05 13:16:08.132  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 0
08-05 13:16:08.132  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:08.132  1036  1539 D WifiNative-wlan0: SET ps 0: returned true
08-05 13:16:08.132  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-05 13:16:08.133  7269  7269 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-05 13:16:08.133  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-05 13:16:08.133  1036  1546 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-05 13:16:08.133  1036  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-05 13:16:08.133  1036  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3db1eaac target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:08.133  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3db1eaac target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:08.134  1036  7327 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:08.134  1036  7327 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-05 13:16:08.136  1036  1539 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-05 13:16:08.136  1036  1539 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-05 13:16:08.136  1036  1539 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,08-05 13:16:08.137   328   895 D CommandListener: Setting iface cfg
08-05 13:16:08.137   328   895 D CommandListener: Trying to bring up wlan0
,08-05 13:16:08.138  1036  1539 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-05 13:16:08.139  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-05 13:16:08.140  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-05 13:16:08.140  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 13:16:08.140  1036  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:08.140  7269  7269 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 13:16:08.140  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:08.141  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 13:16:08.141  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-05 13:16:08.141  7269  7269 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-05 13:16:08.142  1036  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-05 13:16:08.142  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 13:16:08.152  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 13:16:08.152  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-05 13:16:08.159  1036  1539 D WifiNative-wlan0: SET ps 1: returned true
08-05 13:16:08.160  1036  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-05 13:16:08.160  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 13:16:08.160  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 13:16:08.161  1036  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 13:16:08.161  1036  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 13:16:08.162  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 13:16:08.162  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 13:16:08.163  1036  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-05 13:16:08.163  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-05 13:16:08.164  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-05 13:16:08.164  1036  1539 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-05 13:16:08.165  1036  1546 D ConnectivityService: ignoring duplicate network state non-change
08-05 13:16:08.205  1036  1052 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7345 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-05 13:16:08.207  1036  1052 I ActivityManager: Killing 6694:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-05 13:16:08.295  1036  1538 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:08.295  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:08.295  1036  1538 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 13:16:08.337  1036  7327 D DhcpStateMachine: DHCPV4 request on wlan0
,08-05 13:16:08.339  1036  7327 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-05 13:16:08.339  1036  7327 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-05 13:16:08.342  1036  1907 W libprocessgroup: failed to open /acct/uid_10097/pid_6694/cgroup.procs: No such file or directory
08-05 13:16:08.343  1036  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-05 13:16:08.344  1036  1546 D ConnectivityService: Adding iface wlan0 to network 101
08-05 13:16:08.341  7362  7362 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 13:16:08.341  7362  7362 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 13:16:08.357  7362  7362 I dhcpcd  : version 5.5.6 starting
08-05 13:16:08.359  7362  7362 E dhcpcd  : get_duid: m
08-05 13:16:08.359  7362  7362 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-05 13:16:08.359  7362  7362 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-05 13:16:08.376  1036  1546 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-05 13:16:08.376  1036  1546 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-05 13:16:08.378  1036  1546 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-05 13:16:08.378  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:08.378  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 13:16:08.379  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:08.380   328   895 E Netd    : netlink response contains error (File exists)
08-05 13:16:08.380  1036  1546 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-05 13:16:08.382  1036  1539 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-05 13:16:08.382  1036  1546 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-05 13:16:08.383  1036  1546 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-05 13:16:08.383  1036  1546 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-05 13:16:08.385  1036  1539 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 13:16:08.386  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 13:16:08.387  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:08.388  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:08.388  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-05 13:16:08.389  1036  1539 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 13:16:08.390  1036  1539 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 13:16:08.392  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 13:16:08.393  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:08.393  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:08.393  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-05 13:16:08.393  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-05 13:16:08.394  1036  1539 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 13:16:08.396  1946  1946 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-05 13:16:08.397  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:08.397  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:08.398  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-05 13:16:08.398  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-05 13:16:08.402  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:08.402  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:08.402  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-05 13:16:08.402  1036  1546 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-05 13:16:08.402  1036  1546 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-05 13:16:08.402  1036  1546 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-05 13:16:08.402  1036  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-05 13:16:08.403  1036  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 13:16:08.403  1036  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 13:16:08.403  1036  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-05 13:16:08.403  1036  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:08.403  1036  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-05 13:16:08.403  1036  1546 D ConnectivityService: currentScore = 0, newScore = 20
08-05 13:16:08.403  1036  1546 D ConnectivityService:    accepting network in place of null
08-05 13:16:08.403  1036  1546 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:08.404  1036  7326 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:08.404  1036  7326 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-05 13:16:08.404  1036  7326 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:08.404  1036  7326 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-05 13:16:08.406  1036  1539 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:08.406  1036  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 13:16:08.406   328  7369 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-05 13:16:08.406  1855  1855 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:08.406  1855  1855 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-05 13:16:08.406  1036  1546 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 ,wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-05 13:16:08.407  1036  1546 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-05 13:16:08.407  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 13:16:08.411  1036  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:08.411  1036  1546 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-05 13:16:08.412  1036  1546 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-05 13:16:08.413  1036  1546 D ConnectivityService: validation of new default Network = false
08-05 13:16:08.413  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:08.413  1036  1546 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-05 13:16:08.413  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 13:16:08.413  1036  1546 D DSQN    : enableDataServiceNotify 
08-05 13:16:08.413  1036  1546 D DSQN    : start dsqn bin
,08-05 13:16:08.416  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:08.417  7345  7345 I art     : Almond Protected OAT
08-05 13:16:08.418  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-05 13:16:08.418  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 13:16:08.418  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 13:16:08.418  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 13:16:08.420  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:08.420  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-05 13:16:08.420  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:08.424  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:08.424  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-05 13:16:08.425  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:08.427  1036  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-05 13:16:08.421  7372  7372 W dsqn    : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 13:16:08.427  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:08.429  1036  1537 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-05 13:16:08.427  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 13:16:08.429  1036  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 13:16:08.421  7372  7372 W dsqn    : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 13:16:08.435  1604  1818 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-05 13:16:08.439  7362  7362 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-05 13:16:08.439  7362  7362 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-05 13:16:08.439  7362  7362 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-05 13:16:08.439  7362  7362 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-05 13:16:08.439  7362  7362 D dhcpcd  : wlan0: sending REQUEST (xid 0xd752e55), next in 3.77 seconds
08-05 13:16:08.442  7372  7372 E DSQN    : DSQN ssw
,08-05 13:16:08.451  1819  7377 I CheckinService: active receiver: enabled
,08-05 13:16:08.463  1819  7377 I CheckinService: Preparing to send checkin request
08-05 13:16:08.463  1819  7377 I EventLogService: Accumulating logs since 1470395570596
08-05 13:16:08.465  7362  7362 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-05 13:16:08.465   328  7369 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-05 13:16:08.475  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 13:16:08.475  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:08.476  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 13:16:08.485  7345  7345 D WeatherApplication: removeAccount
08-05 13:16:08.486  7345  7345 D WeatherApplication: Account.length = 0
08-05 13:16:08.486  7345  7345 E WeatherApplication: OPERATOR:OPEN
08-05 13:16:08.488  7362  7362 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-05 13:16:08.488  7362  7362 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-05 13:16:08.488  7362  7362 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-05 13:16:08.488  7362  7362 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-05 13:16:08.488  7362  7362 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-05 13:16:08.488  7362  7362 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-05 13:16:08.488  7362  7362 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-05 13:16:08.488  7362  7362 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-05 13:16:08.489  7345  7345 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:16:8
08-05 13:16:08.491  7345  7345 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 13:16:08.491  7345  7345 D Weather.Utils: 2 : All the weather widget is gone.
08-05 13:16:08.493  7345  7345 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 13:16:08.495  7345  7345 D WeatherAncestor: connectivity changed - connection : true
08-05 13:16:08.496  7345  7345 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-05 13:16:08.499  1819  7377 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-05 13:16:08.501   328  7369 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-05 13:16:08.507  7345  7345 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 13:16:08.507  7345  7345 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 13:16:08.507  7345  7345 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-05 13:16:08.527  7345  7345 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 13:16:08.527  7345  7345 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:16:8
,08-05 13:16:08.551   328   894 D LGDataListener: argv[0]=dsqncommand
08-05 13:16:08.551   328   894 D LGDataListener: argv[1]=wlan0
08-05 13:16:08.551   328   894 D LGDataListener: argv[2]=1
08-05 13:16:08.551   328   894 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-05 13:16:08.551  1036  1106 D DSQN    : DSQM DsqnNotification wlan0  1
08-05 13:16:08.551  1036  1106 D DSQN    : start to monitor internet connection
,08-05 13:16:08.572  1036  1926 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7394 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 13:16:08.573  1036  1926 I ActivityManager: Killing 6559:com.android.vending/u0a44 (adj 15): empty #17
,08-05 13:16:08.597  1036  7326 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Aug 2016 11:16:08 GMT], X-Android-Received-Millis=[1470395768597], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470395768551]}
08-05 13:16:08.597  1036  7326 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,08-05 13:16:08.597  1036  7326 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-05 13:16:08.597  1036  1546 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-05 13:16:08.597  1036  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-05 13:16:08.598  1036  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 13:16:08.598  1036  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 13:16:08.598  1036  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-05 13:16:08.598  1036  1546 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-05 13:16:08.598  1036  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-05 13:16:08.598  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:08.598  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 13:16:08.598  1036  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 13:16:08.599  1036  1546 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:08.599  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-05 13:16:08.599  1036  1539 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:08.599  1855  1855 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:08.599  1604  1818 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-05 13:16:08.599  1036  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 13:16:08.599  1855  1855 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-05 13:16:08.670  1036  1944 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7419 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-05 13:16:08.670  1036  1052 W libprocessgroup: failed to open /acct/uid_10044/pid_6559/cgroup.procs: No such file or directory
,08-05 13:16:08.708  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 13:16:08.709  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:08.710  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:08.739  7419  7419 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-05 13:16:08.740  7419  7419 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-05 13:16:08.744  1036  7327 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-05 13:16:08.745  1036  7327 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-05 13:16:08.745  1036  7327 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,08-05 13:16:08.745  1036  7327 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-05 13:16:08.745  1036  7327 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-05 13:16:08.745  1036  7327 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-05 13:16:08.745  1036  7327 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-05 13:16:08.745  1036  7327 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-05 13:16:08.746  1036  7327 D DhcpStateMachine: RunningState
08-05 13:16:08.767  7419  7419 I MultiDex: VM with version 2.1.0 has multidex support
08-05 13:16:08.768  7419  7419 I MultiDex: install
08-05 13:16:08.768  7419  7419 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-05 13:16:08.778  7419  7419 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-05 13:16:08.796   278   323 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 13:16:08.796   278   323 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-05 13:16:08.796   278   323 W Vold    : Returning OperationFailed - no handler for errno 0
,08-05 13:16:08.801  7394  7438 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-05 13:16:08.804   278   323 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 13:16:08.804   278   323 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-05 13:16:08.804   278   323 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 13:16:08.805  7394  7438 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-05 13:16:08.816   278   323 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 13:16:08.816   278   323 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-05 13:16:08.816   278   323 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 13:16:08.816  7394  7442 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-05 13:16:08.818   278   323 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 13:16:08.818   278   323 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-05 13:16:08.818   278   323 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 13:16:08.818  7394  7442 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-05 13:16:09.051  7394  7394 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-05 13:16:09.068  7394  7394 I LibraryLoader: Loading: webviewchromium
08-05 13:16:09.071  7394  7394 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9434-9437)
08-05 13:16:09.071  7394  7394 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-05 13:16:09.075  7394  7394 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {56e35d8}
08-05 13:16:09.077  7394  7394 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 13:16:09.077  7394  7394 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-05 13:16:09.085  7394  7394 I BrowserStartupController: Initializing chromium process, renderers=0
,08-05 13:16:09.086  7394  7394 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 13:16:09.096  7394  7394 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-05 13:16:09.096  7394  7394 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-05 13:16:09.097  7394  7394 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-05 13:16:09.098   332   332 V AudioPolicyService: registerClient() client 0xb04108e0, uid 10093
08-05 13:16:09.099  7394  7465 W AudioManagerAndroid: Requires BLUETOOTH permission
08-05 13:16:09.111  7394  7394 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 13:16:09.111  7394  7394 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 13:16:09.111  7394  7394 I Adreno-EGL: Build Date: 12/12/14 금
08-05 13:16:09.111  7394  7394 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 13:16:09.111  7394  7394 I Adreno-EGL: Remote Branch: 
08-05 13:16:09.111  7394  7394 I Adreno-EGL: Local Patches: 
08-05 13:16:09.111  7394  7394 I Adreno-EGL: Reconstruct Branch: 
,08-05 13:16:09.190  7394  7394 I NSApplication: Starting up...
,08-05 13:16:09.247  1036  1051 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7479 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-05 13:16:09.248  1036  1051 I ActivityManager: Killing 6834:com.lge.clock/u0a10 (adj 15): empty #17
,08-05 13:16:09.260  7419  7435 D LgDataFeature: LgDataFeature() Constructor: none
08-05 13:16:09.260  7419  7435 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 13:16:09.305  1036  1539 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-05 13:16:09.305  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 13:16:09.305  1036  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 13:16:09.305  1036  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 13:16:09.305  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 13:16:09.306  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 13:16:09.307  1036  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-05 13:16:09.307  1036  1546 D ConnectivityService: identical MTU - not setting
08-05 13:16:09.307  1036  1546 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-05 13:16:09.307  1036  1546 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-05 13:16:09.307  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:09.308  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 13:16:09.308  1036  1546 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 13:16:09.309  1604  1818 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-05 13:16:09.314  1036  1052 D WifiServiceImplEx: setWifiEnabled: false pid=6900, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 13:16:09.315  1036  1052 D WifiService: setWifiEnabled: false pid=6900, uid=10118
08-05 13:16:09.315  1036  1052 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-05 13:16:09.316  1036  1944 W libprocessgroup: failed to open /acct/uid_10010/pid_6834/cgroup.procs: No such file or directory
,08-05 13:16:09.331  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 13:16:09.331  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 13:16:09.331  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-05 13:16:09.332  1036  1539 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-05 13:16:09.332  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-05 13:16:09.332  1036  1539 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-05 13:16:09.332  1036  1539 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-05 13:16:09.332  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-05 13:16:09.332  1036  1539 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-05 13:16:09.333  1036  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 13:16:09.333  1036  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 13:16:09.333  1036  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 13:16:09.333  1036  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-05 13:16:09.341  1036  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 13:16:09.341  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 13:16:09.341  7269  7269 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 13:16:09.341  1036  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:09.341  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:09.341  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 13:16:09.341  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 13:16:09.341  1036  1539 D WifiNative-wlan0: SET ps 1: returned true
08-05 13:16:09.341   328   895 D CommandListener: Clearing all IP addresses on wlan0
08-05 13:16:09.353  1036  7327 D DhcpStateMachine: RunningState{ when=-12ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 13:16:09.360  7479  7479 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 13:16:09.381  1036  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-05 13:16:09.381  1036  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-05 13:16:09.381  1036  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:09.381  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:09.381  1036  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:09.381  1036  1538 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3d3abe4f
08-05 13:16:09.381  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:09.382  1036  1538 D LGWifiP2pService: P2pDisablingState
08-05 13:16:09.382  1036  1538 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:09.382  1036  1538 D LGWifiP2pService: p2p socket connection lost
08-05 13:16:09.382  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:09.382  1036  1538 D LGWifiP2pService: P2pDisabledState
08-05 13:16:09.382  1036  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:09.382  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:09.382  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-05 13:16:09.394  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-05 13:16:09.395  1946  1946 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-05 13:16:09.395  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:09.395  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 13:16:09.396  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 13:16:09.399  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:09.399  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:09.399  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 13:16:09.399  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-05 13:16:09.399  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:09.399  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:09.399  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 13:16:09.399  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-05 13:16:09.399  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-05 13:16:09.400  1036  1557 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:09.400  1036  1558 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:09.401  1036  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:09.402  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:09.402  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:09.402  1036  1539 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-05 13:16:09.402  1036  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-05 13:16:09.402  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 13:16:09.402  7269  7269 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 13:16:09.403  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 13:16:09.403  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 13:16:09.403  1036  1539 D WifiNative-wlan0: SET ps 1: returned true
08-05 13:16:09.403  1036  1538 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:09.403  1036  1538 D LGWifiP2pService: DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:09.404  1946  1946 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-05 13:16:09.404  1946  1946 D WfdsService: WifiP2pState is changed : false
08-05 13:16:09.404  1946  2307 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-05 13:16:09.404  1946  2307 D WfdsService: Set the WFDS Monitor: false
08-05 13:16:09.405  1946  2307 D WfdsMonitor: WFDS Monitor is stopped
08-05 13:16:09.405  1946  2307 D WfdsService: STATE : WfdsDisabledState - enter
08-05 13:16:09.405  1946  2309 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-05 13:16:09.405  1946  7278 D CtrlSupplicant: Received on exit socket, terminate
08-05 13:16:09.405  1946  7278 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-05 13:16:09.405  1946  7278 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-05 13:16:09.405  1946  7278 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-05 13:16:09.406  1946  2307 W WfdsService: DefaultState - msg [9445378] is not handled
08-05 13:16:09.417  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:09.418  1604  1604 I StatusBar.NetworkContr,oller: mWifiConnected = false, mWifiLevel = 0
08-05 13:16:09.420  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 13:16:09.424   328   895 D CommandListener: Clearing all IP addresses on wlan0
08-05 13:16:09.425  1036  1546 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-05 13:16:09.425  1036  1546 D DSQN    : disableDataServiceNotify
08-05 13:16:09.425  1036  1546 D DSQN    : stop dsqn bin
08-05 13:16:09.426  1036  1539 D WifiNative-p2p0: doBoolean: TERMINATE
08-05 13:16:09.427  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-05 13:16:09.427  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:09.427  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:09.428  1036  1539 D WifiNative-p2p0: TERMINATE: returned true
08-05 13:16:09.428  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 13:16:09.428  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
08-05 13:16:09.428  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 13:16:09.428  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 13:16:09.429  1946  1946 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-05 13:16:09.429  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-05 13:16:09.430  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 13:16:09.430  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-05 13:16:09.432  6900  6900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 13:16:09.432  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 13:16:09.432  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:09.432  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:09.432  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 13:16:09.432  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 13:16:09.432  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 13:16:09.432  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 13:16:09.432  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 13:16:09.432  6900  6900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 13:16:09.432  6900  6900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-05 13:16:09.433  6900  6900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 13:16:09.433  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 13:16:09.433  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:09.433  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:09.433  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 13:16:09.433  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 13:16:09.433  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 13:16:09.433  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 13:16:09.433  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 13:16:09.433  6900  6900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 13:16:09.433  6900  6900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 13:16:09.435  1036  1546 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-05 13:16:09.435  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:09.435  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 13:16:09.436  1036  1546 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 13:16:09.436  1036  1546 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-05 13:16:09.436  1036  7326 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:09.436  1604  1818 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-05 13:16:09.436  1036  7326 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:09.436  1036  7326 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-05 13:16:09.436  1036  1546 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-05 13:16:09.436  1036  1546 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-05 13:16:09.437  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 13:16:09.437  1036  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:09.437  1036  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConn,ected  type  :1
08-05 13:16:09.437  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 13:16:09.438  1036  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:09.438  1036  1546 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:09.438  1036  1546 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:09.438  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-05 13:16:09.438  1036  1539 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:09.439  1036  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 13:16:09.439  1036  1546 D NetworkManagementService: Removing idletimer
08-05 13:16:09.439  1036  1546 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:09.439  1036  1546 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-05 13:16:09.439  1855  1855 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:09.439  1855  1855 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-05 13:16:09.439  1036  1546 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-05 13:16:09.439  1036  1537 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-05 13:16:09.440  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-05 13:16:09.440  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 13:16:09.441  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:09.442  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 13:16:09.442  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 13:16:09.442  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 13:16:09.442  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-05 13:16:09.442  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 13:16:09.442  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 13:16:09.442  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 13:16:09.442  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 13:16:09.462  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-05 13:16:09.464  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:09.464  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:09.479  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 13:16:09.480  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:09.480  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 13:16:09.536  7269  7269 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-05 13:16:09.536  7269  7269 I wpa_supplicant: monitor socket send errors count : 1
08-05 13:16:09.537  7269  7269 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1946-4\x00 that cannot receive messages
08-05 13:16:09.539  1036  7277 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-05 13:16:09.539  1036  7277 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-05 13:16:09.554  7508  7508 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-05 13:16:09.560  1036  7327 D DhcpStateMachine: StoppedState
08-05 13:16:09.560  1036  7327 D DhcpStateMachine: StoppedState{ when=-158ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:09.562  1036  1539 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-05 13:16:09.563  1036  1539 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-05 13:16:09.577  7269  7269 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 13:16:09.577  1036  7277 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-05 13:16:09.578  7269  7269 W wpa_supplicant: USIM:  scard_deinit function
08-05 13:16:09.578  1036  7277 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 13:16:09.578  1036  7277 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 13:16:09.578  1036  7277 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-05 13:16:09.578  1036  7277 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 13:16:09.578  1036  7277 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 13:16:09.578  1036  1109 D Tethering: InitialState.processMessage what=4
08-05 13:16:09.579  1036  1539 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=339932
08-05 13:16:09.579  1036  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-05 13:16:09.580  1036  1539 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=339933
,08-05 13:16:09.580  1036  1539 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=339933  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 13:16:09.580  1036  1539 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=339934  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 13:16:09.581  1036  1539 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-05 13:16:09.581  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 13:16:09.624  7508  7508 I dex2oat : dex2oat took 69.498ms (threads: 4)
,08-05 13:16:09.636  7419  7435 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 13:16:09.636  7419  7435 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 13:16:09.636  7419  7435 I Adreno-EGL: Build Date: 12/12/14 금
08-05 13:16:09.636  7419  7435 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 13:16:09.636  7419  7435 I Adreno-EGL: Remote Branch: 
08-05 13:16:09.636  7419  7435 I Adreno-EGL: Local Patches: 
08-05 13:16:09.636  7419  7435 I Adreno-EGL: Reconstruct Branch: 
08-05 13:16:09.657  6377  6377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-05 13:16:09.658  6377  7024 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-05 13:16:09.680  2154  2154 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-05 13:16:09.685  7269  7269 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-05 13:16:09.690  1036  7277 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-05 13:16:09.690  1036  7277 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-05 13:16:09.690  1036  7277 D WifiMonitor: Disconnecting from the supplicant, no more events
08-05 13:16:09.690  1036  1539 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-05 13:16:09.700  7217  7217 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-05 13:16:09.700  7217  7217 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:09.700  7217  7217 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 13:16:09.702  7217  7217 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-05 13:16:09.704  7217  7217 I AppUp4:CustModeStarterReceiver: onReceive
08-05 13:16:09.708  7217  7217 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@b619a89
08-05 13:16:09.708  7217  7217 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 13:16:09.708  7217  7217 D AppUp4:CustFacade: isPhone : true
08-05 13:16:09.709  7217  7217 D AppUp4:CustModeStarterReceiver: begin check event
08-05 13:16:09.710  7217  7217 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-05 13:16:09.712  4691  4691 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:09.713  4691  4691 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 13:16:09.715  4691  4691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-05 13:16:09.719  4691  4691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 13:16:09.725  7251  7251 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-05 13:16:09.726  4691  7527 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-05 13:16:09.731  4691  7528 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-05 13:16:09.731  4691  7528 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 13:16:09.738  7251  7529 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 13:16:09.741  7419  7435 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 13:16:09.741  7419  7435 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 13:16:09.741  7419  7435 I Adreno-EGL: Build Date: 12/12/14 금
08-05 13:16:09.741  7419  7435 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 13:16:09.741  7419  7435 I Adreno-EGL: Remote Branch: 
08-05 13:16:09.741  7419  7435 I Adreno-EGL: Local Patches: 
08-05 13:16:09.741  7419  7435 I Adreno-EGL: Reconstruct Branch: 
,08-05 13:16:09.747  7114  7531 W FormManager: Network not available. Please check & try again.
08-05 13:16:09.752  3386  3386 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 13:16:09.752  3386  3386 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:09.753  3386  3386 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-05 13:16:09.757  7288  7288 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-05 13:16:09.757  7288  7288 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-05 13:16:09.761  7114  7532 V FormManager: Network unavailable.
08-05 13:16:09.767  7345  7345 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:16:9
08-05 13:16:09.768  7345  7345 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 13:16:09.768  7345  7345 D Weather.Utils: 2 : All the weather widget is gone.
,08-05 13:16:09.769  7345  7345 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 13:16:09.769  7345  7345 D WeatherAncestor: connectivity changed - connection : true
08-05 13:16:09.769  7345  7345 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@128ce2af
,08-05 13:16:09.770  7114  7532 V FormManager: Network unavailable.
08-05 13:16:09.771  7345  7345 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 13:16:09.771  7345  7345 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 13:16:09.771  7345  7345 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-05 13:16:09.771  7345  7345 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 13:16:09.771  7345  7345 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:16:9
08-05 13:16:09.789  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 13:16:09.789  7004  7004 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 13:16:09.789  7004  7004 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 13:16:09.789  7004  7004 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 13:16:09.790  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 13:16:09.791  7004  7004 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 13:16:09.791  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 13:16:09.791  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 13:16:09.791  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 13:16:09.791  7004  7004 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 13:16:09.791  7004  7004 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 13:16:09.791  7419  7435 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 13:16:09.791  7419  7435 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 13:16:09.791  7419  7435 I Adreno-EGL: Build Date: 12/12/14 금
08-05 13:16:09.791  7419  7435 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 13:16:09.791  7419  7435 I Adreno-EGL: Remote Branch: 
08-05 13:16:09.791  7419  7435 I Adreno-EGL: Local Patches: 
08-05 13:16:09.791  7419  7435 I Adreno-EGL: Reconstruct Branch: 
08-05 13:16:09.792  1946  1946 D WfdsService: Supplicant Connection state is changed : false
,08-05 13:16:09.792  1946  2307 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,08-05 13:16:09.792  1946  2307 D WfdsService: Set the WFDS Monitor: false
08-05 13:16:09.792  1946  2307 D WfdsMonitor: WFDS Monitor is stopped
08-05 13:16:09.792  1036  1539 D WifiOffDelayIfNotUsed: stopMonitoring
08-05 13:16:09.792  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 13:16:09.792  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
08-05 13:16:09.792  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 13:16:09.794  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-05 13:16:09.794  1036  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-05 13:16:09.794  1036  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-05 13:16:09.794  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:09.795  2508  2508 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:09.796  6900  6900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 13:16:09.796  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 13:16:09.796  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:09.796  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:09.796  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 13:16:09.796  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 13:16:09.796  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 13:16:09.796  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 13:16:09.796  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 13:16:09.796  1946  1946 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-05 13:16:09.796  6900  6900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 13:16:09.796  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 13:16:09.796  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:09.796  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:09.796  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 13:16:09.796  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 13:16:09.796  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 13:16:09.796  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 13:16:09.796  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 13:16:09.801  7025  7025 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 13:16:09.804  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 13:16:09.809  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:09.813  7114  7535 W FormManager: Network not available. Please check & try again.
08-05 13:16:09.818  7114  7536 V FormManager: Network unavailable.
,08-05 13:16:09.822  7114  7536 V FormManager: Network unavailable.
08-05 13:16:09.824  7025  7025 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 13:16:09.826  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 13:16:09.827  7114  7537 W FormManager: Network not available. Please check & try again.
08-05 13:16:09.830  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 13:16:09.831  7114  7538 V FormManager: Network unavailable.
,08-05 13:16:09.835  7114  7538 V FormManager: Network unavailable.
08-05 13:16:09.845  4691  4691 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 13:16:09.845  4691  4691 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-05 13:16:09.846  4691  4691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-05 13:16:09.847  4691  4691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 13:16:09.852  4691  7539 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 13:16:09.853  4691  7540 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 13:16:09.853  4691  7540 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 13:16:09.855   328  7542 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-05 13:16:09.856  1036  1106 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-05 13:16:09.856  1819  7377 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,08-05 13:16:09.881  1036  1926 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7543 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-05 13:16:09.888  1819  7377 I CheckinService: active receiver: disabled
,08-05 13:16:09.948  7543  7543 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-05 13:16:09.948  7543  7543 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-05 13:16:09.956  7543  7543 V [BNRBootReceiver]: Boot Receiver Return
08-05 13:16:09.957  7543  7543 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-05 13:16:09.958  6377  6377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 13:16:09.963  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 13:16:09.966  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 13:16:09.974  7086  7086 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 13:16:09.975  7086  7086 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 13:16:09.976  7086  7086 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 13:16:09.977  1036  1908 I ActivityManager: Killing 6980:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-05 13:16:09.981   328  7562 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-05 13:16:09.982  1036  1106 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-05 13:16:10.015  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=98461650 [*alarm*], flags=0x0
,08-05 13:16:10.020  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-05 13:16:10.024  7004  7004 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-05 13:16:10.034  6377  6377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 13:16:10.039  1036  1963 W libprocessgroup: failed to open /acct/uid_10037/pid_6980/cgroup.procs: No such file or directory
08-05 13:16:10.053  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 13:16:10.064  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:10.074  7086  7086 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 13:16:10.075  7086  7086 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 13:16:10.077  7086  7086 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 13:16:10.084  6377  6377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 13:16:10.094  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 13:16:10.104  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 13:16:10.121  7086  7086 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 13:16:10.122  7086  7086 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 13:16:10.124  7086  7086 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 13:16:10.130  6377  6377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 13:16:10.144  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 13:16:10.159  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 13:16:10.175  7086  7086 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 13:16:10.175  7086  7086 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 13:16:10.176  7086  7086 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 13:16:10.182  6377  6377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 13:16:10.196  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 13:16:10.205  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null,
08-05 13:16:10.215  7086  7086 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 13:16:10.215  7086  7086 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 13:16:10.216  7086  7086 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 13:16:10.222  6377  6377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 13:16:10.232  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 13:16:10.239  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:10.248  7086  7086 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 13:16:10.248  7086  7086 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 13:16:10.249  7086  7086 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 13:16:10.254  6377  6377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 13:16:10.267  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 13:16:10.276  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 13:16:10.288  7086  7086 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 13:16:10.289  7086  7086 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 13:16:10.290  7086  7086 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 13:16:10.305  6377  6377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 13:16:10.331  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 13:16:10.346  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:10.364  7086  7086 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 13:16:10.365  7086  7086 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 13:16:10.373  7086  7086 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 13:16:10.381  6377  6377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 13:16:10.393  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 13:16:10.402  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 13:16:10.412  7086  7086 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 13:16:10.412  7086  7086 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 13:16:10.414  7086  7086 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 13:16:10.421  6377  6377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 13:16:10.428  7025  7025 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-05 13:16:10.438  6765  7188 D UEI.SmartControl: Internal timer expired: 2
08-05 13:16:10.438  6765  7188 D UEI.SmartControl: unbind internal service
08-05 13:16:10.445  1036  1545 D WifiService: New client listening to asynchronous messages
08-05 13:16:10.446  7025  7025 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 13:16:10.453  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 13:16:10.468  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:10.485  7086  7086 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 13:16:10.486  7086  7086 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 13:16:10.488  7086  7086 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-05 13:16:10.490  7086  7086 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-05 13:16:10.491  7086  7086 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-05 13:16:10.506  6377  6377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 13:16:10.515  7025  7025 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-05 13:16:10.519  6765  7182 D serial_port: close(fd = 24)
08-05 13:16:10.521  7025  7025 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 13:16:10.525  6765  7182 I UEI.SmartControl: Serial port is closed.
,08-05 13:16:10.533  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 13:16:10.546  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:10.558  7086  7086 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 13:16:10.558  7086  7086 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 13:16:10.560  7086  7086 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-05 13:16:10.562  7086  7086 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-05 13:16:10.563  7086  7086 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-05 13:16:10.569  2154  2154 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-05 13:16:10.583  2154  2154 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-05 13:16:10.584  2154  2154 D c       : Getting all permits...
08-05 13:16:10.584  2154  2154 D a       : Opening database...
,08-05 13:16:10.589  2154  2154 D a       : Opening database auth.proximity.permit_store...
08-05 13:16:10.590  2154  2154 D a       : Closing database...
08-05 13:16:10.604  6377  6377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 13:16:10.611  7025  7025 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 13:16:10.611  7025  7025 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 13:16:10.611  7025  7025 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 13:16:10.616  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 13:16:10.626  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:10.637  7086  7086 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 13:16:10.637  7086  7086 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 13:16:10.639  7086  7086 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 13:16:10.644  6377  6377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 13:16:10.650  7025  7025 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 13:16:10.651  7025  7025 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 13:16:10.651  7025  7025 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 13:16:10.659  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 13:16:10.671  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:10.681  7086  7086 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 13:16:10.682  7086  7086 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 13:16:10.685  7086  7086 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-05 13:16:10.691  6377  6377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 13:16:10.699  7025  7025 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 13:16:10.699  7025  7025 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 13:16:10.699  7025  7025 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 13:16:10.711  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 13:16:10.719  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:10.730  7086  7086 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 13:16:10.731  7086  7086 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 13:16:10.734  7086  7086 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 13:16:10.744  7025  7025 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 13:16:10.749  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 13:16:10.757  7114  7570 W FormManager: Network not available. Please check & try again.
08-05 13:16:10.758  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:10.769  7114  7571 V FormManager: Network unavailable.
,08-05 13:16:10.777  7114  7571 V FormManager: Network unavailable.
08-05 13:16:10.782  4691  4691 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 13:16:10.782  4691  4691 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 13:16:10.784  4691  4691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-05 13:16:10.788  4691  4691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 13:16:10.798  4691  7572 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 13:16:10.798  7025  7025 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-05 13:16:10.798  7025  7025 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 13:16:10.799  7025  7025 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 13:16:10.804  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 13:16:10.804  4691  7574 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 13:16:10.805  4691  7574 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 13:16:10.812  7114  7575 W FormManager: Network not available. Please check & try again.
,08-05 13:16:10.814  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:10.815  7114  7576 V FormManager: Network unavailable.
08-05 13:16:10.821  7114  7576 V FormManager: Network unavailable.
08-05 13:16:10.832  2154  2154 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-05 13:16:11.129  1036  1539 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1516955896] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 13:16:11.131  1036  1539 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1516955899] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 13:16:11.413  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 13:16:11.427  1036  1109 D Tethering: MasterInitialState.processMessage what=3
08-05 13:16:11.433  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 13:16:11.437  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:11.440  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:11.445  6377  6377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-05 13:16:11.449  6377  7024 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-05 13:16:11.462  5765  5765 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-05 13:16:11.486  2154  2154 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-05 13:16:11.516  7217  7217 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-05 13:16:11.516  7217  7217 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:11.516  7217  7217 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 13:16:11.516  7217  7217 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-05 13:16:11.523  7217  7217 I AppUp4:CustModeStarterReceiver: onReceive
08-05 13:16:11.526  7217  7217 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@b619a89
08-05 13:16:11.526  7217  7217 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 13:16:11.526  7217  7217 D AppUp4:CustFacade: isPhone : true
08-05 13:16:11.527  7217  7217 D AppUp4:CustModeStarterReceiver: begin check event
08-05 13:16:11.527  7217  7217 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-05 13:16:11.532  4691  4691 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:11.533  4691  4691 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-05 13:16:11.537  4691  4691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 13:16:11.547  4691  4691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-05 13:16:11.562  7251  7251 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-05 13:16:11.583  4691  7595 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 13:16:11.584  4691  7596 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-05 13:16:11.587  4691  7596 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 13:16:11.590  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:11.608  3386  3386 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-05 13:16:11.608  3386  3386 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:11.608  3386  3386 I LgeMiscReceiver: networkInfo.isConnected() = true
08-05 13:16:11.608  3386  3386 D PhoneState: setPdpRejectCasuse : false
08-05 13:16:11.614  7288  7288 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-05 13:16:11.614  7288  7288 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-05 13:16:11.618  7251  7600 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:11.619  7114  7604 V FormManager: Network unavailable.
08-05 13:16:11.620  7114  7603 W FormManager: Network not available. Please check & try again.
,08-05 13:16:11.632  7345  7345 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:16:11
08-05 13:16:11.632  7114  7604 V FormManager: Network unavailable.
,08-05 13:16:11.633  7345  7345 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 13:16:11.633  7345  7345 D Weather.Utils: 2 : All the weather widget is gone.
08-05 13:16:11.633  7345  7345 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 13:16:11.634  7345  7345 D WeatherAncestor: connectivity changed - connection : true
08-05 13:16:11.634  7345  7345 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@128ce2af
08-05 13:16:11.634  7345  7345 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 13:16:11.634  7345  7345 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 13:16:11.634  7345  7345 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-05 13:16:11.635  7345  7345 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 13:16:11.635  7345  7345 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:16:11
08-05 13:16:12.333  1036  1729 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:12.335  1036  1729 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-05 13:16:12.364  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 13:16:12.364  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 13:16:12.364  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-05 13:16:12.365  1036  1109 D BluetoothManagerService: Message: 1
08-05 13:16:12.365  1036  1109 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-05 13:16:12.390  1036  1109 D BluetoothManagerService: Message: 20
08-05 13:16:12.390  1036  1109 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1828236c:true
,08-05 13:16:12.395  7143  7143 D BluetoothAdapterState: make
08-05 13:16:12.400  7143  7143 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-05 13:16:12.400  7143  7143 I bluedroid-qcom: init
08-05 13:16:12.402  7143  7616 I BluetoothAdapterState: Entering OffState
08-05 13:16:12.402  7143  7143 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-05 13:16:12.402  7143  7143 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-05 13:16:12.402  7143  7143 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-05 13:16:12.402  7143  7143 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-05 13:16:12.402  7143  7143 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-05 13:16:12.404  7143  7143 I bluedroid-qcom: get_profile_interface socket
08-05 13:16:12.404  7143  7143 I bluedroid-qcom: get_profile_interface map_client
,08-05 13:16:12.409  7143  7620 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-05 13:16:12.401  7619  7619 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 13:16:12.411  7619  7619 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 13:16:12.425  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-05 13:16:12.428  1036  1109 D BluetoothManagerService: Message: 40
08-05 13:16:12.428  1036  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-05 13:16:12.429  7143  7160 I bluedroid-qcom: config_hci_snoop_log
08-05 13:16:12.430  1036  1109 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-05 13:16:12.430  1036  1109 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-05 13:16:12.433  7619  7619 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-05 13:16:12.433  7619  7619 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-05 13:16:12.434  7619  7619 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-05 13:16:12.437  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 13:16:12.442  7619  7619 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-05 13:16:12.446  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:12.449  7619  7619 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-05 13:16:12.450  7619  7619 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-05 13:16:12.455  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 13:16:12.460  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:12.462  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:12.464  1036  1109 D Tethering: MasterInitialState.processMessage what=3
08-05 13:16:12.465  7143  7616 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-05 13:16:12.466  7143  7620 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-05 13:16:12.468  7143  7620 D BluetoothAdapterProperties: Name is: G3
,08-05 13:16:12.471  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-05 13:16:12.471  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-05 13:16:12.477  1036  1109 D Tethering: MasterInitialState.processMessage what=3
08-05 13:16:12.477  7143  7616 D BluetoothAdapterProperties: Setting state to 11
08-05 13:16:12.477  7143  7616 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-05 13:16:12.479  7143  7616 I LGBluetoothServiceJni: classInitNative: succeeds
08-05 13:16:12.481  1036  1109 D BluetoothManagerService: Message: 60
08-05 13:16:12.481  1036  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-05 13:16:12.481  1036  1109 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-05 13:16:12.491  6377  6377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-05 13:16:12.496  6377  7024 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-05 13:16:12.500  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:12.501  1946  1946 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-05 13:16:12.504  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:12.507  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:12.507  7004  7004 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-05 13:16:12.508  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 13:16:12.509  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:12.515  7143  7616 D BluetoothBondStateMachine: make
,08-05 13:16:12.519  7143  7616 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128ce2af
08-05 13:16:12.519  7143  7616 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-05 13:16:12.519  7143  7616 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128ce2af
08-05 13:16:12.519  7143  7616 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-05 13:16:12.520  7143  7616 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-05 13:16:12.520  7143  7637 I BluetoothBondStateMachine: StableState(): Entering Off State
08-05 13:16:12.523  7143  7616 E BluetoothAdapterService: File transfer profiles supported!!
08-05 13:16:12.524  5765  5765 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-05 13:16:12.525  7143  7143 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 13:16:12.526  7143  7143 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:12.526  7143  7143 V BluetoothPbapReceiver: ***********state = 11
08-05 13:16:12.530  2154  2154 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 13:16:12.575  1036  1908 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7640 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-05 13:16:12.582  7143  7143 D HeadsetService: Received start request. Starting profile...
08-05 13:16:12.582  7143  7616 E BluetoothAdapterService: File transfer profiles supported!!
08-05 13:16:12.582  7143  7143 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 13:16:12.582  7143  7143 D LGBluetoothHfpAdapter: Version 1.6
08-05 13:16:12.585  7143  7143 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 13:16:12.586  7143  7143 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 13:16:12.586  7143  7143 D HeadsetStateMachine: make
08-05 13:16:12.587  5765  5765 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-05 13:16:12.589  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:12.589  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:12.589  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 13:16:12.592  7143  7616 E BluetoothAdapterService: File transfer profiles supported!!
08-05 13:16:12.595   354   354 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 300us total 18.123ms
08-05 13:16:12.601  2154  2154 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-05 13:16:12.608   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 244us total 12.551ms
08-05 13:16:12.616  7143  7143 D LgDataFeature: LgDataFeature() Constructor: none
08-05 13:16:12.616  7143  7143 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 13:16:12.620   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 252us total 11.758ms
,08-05 13:16:12.730  1036  1944 I art     : Explicit concurrent mark sweep GC freed 129744(6MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 1.518ms total 119.720ms
,08-05 13:16:12.741  7143  7616 E BluetoothAdapterService: File transfer profiles supported!!
08-05 13:16:12.748  7143  7143 D HeadsetStateMachine: max_hf_connections = 1
,08-05 13:16:12.748  7143  7143 I bluedroid-qcom: get_profile_interface handsfree
08-05 13:16:12.754  7143  7143 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-05 13:16:12.755   332  2181 V AudioPolicyService: registerClient() client 0xb0410220, uid 1002
08-05 13:16:12.755   332   332 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-05 13:16:12.755   332   332 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 13:16:12.755   332   332 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 13:16:12.756  7143  7143 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-05 13:16:12.758   332  1386 V AudioFlinger: registerClient() client 0xb55815c8, pid 7143
08-05 13:16:12.759   332  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 13:16:12.759   332  1381 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 13:16:12.759  1036  1908 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 13:16:12.759  1036  1908 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 13:16:12.760  3386  3402 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 13:16:12.760  3386  3402 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 13:16:12.760  1604  2119 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 13:16:12.760  1604  2119 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 13:16:12.760  7143  7621 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 13:16:12.760  7143  7616 E BluetoothAdapterService: File transfer profiles supported!!
08-05 13:16:12.760  1855  1871 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 13:16:12.760  1855  1871 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 13:16:12.761   332  1382 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 13:16:12.761   332  1382 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 13:16:12.762  1036  1052 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 13:16:12.762  1036  1052 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 13:16:12.762  1604  1625 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 13:16:12.762  1604  1625 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-05 13:16:12.762  1855  1870 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
,08-05 13:16:12.762  1855  1870 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-05 13:16:12.763  3386  3403 V AudioSystem: ioConfigChanged() event 0, ioHandle 4,
08-05 13:16:12.763  3386  3403 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-05 13:16:12.763  7143  7621 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
,08-05 13:16:12.763  7143  7621 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 13:16:12.764  7143  7621 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-05 13:16:12.764  7143  7143 V ToneGenerator: Create Track: 0xb4928a80
08-05 13:16:12.764  7143  7143 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-05 13:16:12.764  7143  7143 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
,08-05 13:16:12.764   332  2181 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 13:16:12.764   332  2181 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-05 13:16:12.764   332  2181 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 13:16:12.764   332  2181 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 13:16:12.764   332   332 I AudioFlinger: isAudioPlaybackHookOn() false
08-05 13:16:12.764   332  1387 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 13:16:12.764   332  1387 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-05 13:16:12.764   332  1387 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 13:16:12.764   332  1387 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 13:16:12.764  7143  7143 V AudioSystem: getLatency() output 2, latency 50
08-05 13:16:12.764  7143  7143 V AudioSystem: getFrameCount() output 2, frameCount 960
08-05 13:16:12.764  7143  7143 V AudioTrack: createTrack_l() output 2 afLatency 50
08-05 13:16:12.764   332  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 13:16:12.764   332  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 13:16:12.764   332  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 13:16:12.764   332  1386 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 13:16:12.764   332  1386 V AudioFlinger: createTrack() lSessionId: 22
08-05 13:16:12.766  7217  7217 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-05 13:16:12.766  7217  7217 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:12.766  7217  7217 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 13:16:12.766  7217  7217 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-05 13:16:12.766  7143  7143 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-05 13:16:12.767   332  2181 V AudioFlinger: acquiring 22 from 7143, for 7143
08-05 13:16:12.767   332  2181 V AudioFlinger:  added new entry for 22
08-05 13:16:12.767  7143  7143 V ToneGenerator: ToneGenerator INIT OK, time: 343133
,08-05 13:16:12.767  7143  7143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128ce2af
08-05 13:16:12.769  7143  7656 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-05 13:16:12.769  7143  7656 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 13:16:12.769  7143  7656 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 13:16:12.769  7143  7656 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-05 13:16:12.769   332   332 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7143
08-05 13:16:12.769   332   332 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-05 13:16:12.769   332   332 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-05 13:16:12.769   332   332 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
,08-05 13:16:12.769   332   332 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-05 13:16:12.769   332   332 V voice   : voice_set_parameters: exit with code(0)
08-05 13:16:12.769   332   332 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-05 13:16:12.769   332   332 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-05 13:16:12.770   332   332 V msm8974_platform: platform_set_parameters: exit with code(0)
08-05 13:16:12.770   332   332 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-05 13:16:12.770   332   332 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-05 13:16:12.770   332   332 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
,08-05 13:16:12.770  7143  7656 V ToneGenerator: ToneGenerator destructor
08-05 13:16:12.770  7143  7656 V ToneGenerator: stopTone
08-05 13:16:12.770  7143  7656 V ToneGenerator: Delete Track: 0xb4928a80
08-05 13:16:12.770  7143  7656 V AudioTrack: ~AudioTrack, releasing session id from 7143 on behalf of 7143
08-05 13:16:12.770   332  1387 V AudioFlinger: releasing 22 from 7143 for 7143
08-05 13:16:12.770   332  1387 V AudioFlinger:  decremented refcount to 0
08-05 13:16:12.770   332  1387 V AudioFlinger: purging stale effects
08-05 13:16:12.770   332  1387 V AudioPolicyService: AudioCommandThread() adding release output 2
,08-05 13:16:12.770   332  1387 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-05 13:16:12.770   332  1120 V AudioPolicyService: AudioCommandThread() waking up
08-05 13:16:12.770   332  1120 V AudioPolicyService: AudioCommandThread() processing release output 2
08-05 13:16:12.770   332  1120 V AudioPolicyManager: releaseOutput() 2
08-05 13:16:12.770   332  1120 V AudioPolicyService: AudioCommandThread() going to sleep
,08-05 13:16:12.770   332  1387 V AudioFlinger: PlaybackThread::Track destructor
08-05 13:16:12.770   332  1387 V AudioFlinger: removeClient_l() pid 7143, calling pid 332
08-05 13:16:12.771  1036  1729 W Process : Unable to open /proc/7659/status
08-05 13:16:12.774  7143  7143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128ce2af
,08-05 13:16:12.779  7143  7143 D A2dpService: Received start request. Starting profile...
08-05 13:16:12.781  7143  7143 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-05 13:16:12.782  7143  7143 V Avrcp   : make
08-05 13:16:12.784  7143  7143 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-05 13:16:12.784  7143  7143 I bluedroid-qcom: get_profile_interface avrcp
08-05 13:16:12.785  7143  7616 E BluetoothAdapterService: File transfer profiles supported!!
08-05 13:16:12.793  7143  7143 V AudioManager: registerRemoteController: size of Media player list: 0
,08-05 13:16:12.794  7217  7217 I AppUp4:CustModeStarterReceiver: onReceive
08-05 13:16:12.795  7143  7143 E AudioManager: No RCC entry present to update
08-05 13:16:12.795  7143  7143 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-05 13:16:12.796  7143  7616 E BluetoothAdapterService: File transfer profiles supported!!
08-05 13:16:12.798  7143  7143 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-05 13:16:12.799  7143  7143 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-05 13:16:12.799  7143  7143 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-05 13:16:12.805  7143  7143 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-05 13:16:12.811  7143  7616 V LGMDMManager: Create singleton instance
,08-05 13:16:12.813  7143  7616 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-05 13:16:12.819  7217  7217 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@b619a89
08-05 13:16:12.819  7217  7217 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 13:16:12.819  7217  7217 D AppUp4:CustFacade: isPhone : true
08-05 13:16:12.847  7217  7217 D AppUp4:CustModeStarterReceiver: begin check event
,08-05 13:16:12.848  7217  7217 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-05 13:16:12.850  4691  4691 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:12.850  7640  7640 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-05 13:16:12.851  7640  7640 W LG Account v2.2: No ProfileInfo entries
08-05 13:16:12.851  4691  4691 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 13:16:12.851  7640  7640 I LG Account v2.2: isEnabled: false
08-05 13:16:12.851  7640  7640 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-05 13:16:12.851  7640  7640 I Feature : [Lifetracker]Country: EU
08-05 13:16:12.851  7640  7640 I Feature : [Lifetracker]Operator: OPEN
08-05 13:16:12.851  7640  7640 I Feature : [Lifetracker]Ranking support: false
08-05 13:16:12.851  7640  7640 I Feature : [Lifetracker]Comfort support: false
08-05 13:16:12.851  7640  7640 I Feature : [Lifetracker]Accessory: true
08-05 13:16:12.851  7640  7640 I Feature : [Lifetracker]Health device: true
08-05 13:16:12.851  7640  7640 I Feature : [Lifetracker]Extra Pedometer: false
08-05 13:16:12.851  7640  7640 I Feature : [Lifetracker]Blood glucose device: false
08-05 13:16:12.851  7640  7640 I Feature : [Lifetracker]Device Number: 3
08-05 13:16:12.852  4691  4691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 13:16:12.859  4691  4691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-05 13:16:12.859  7004  7004 D BluetoothPermissionRequest: onReceive
08-05 13:16:12.864  7004  7004 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 13:16:12.866  4691  7664 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 13:16:12.868  4691  7665 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:12.868  4691  7665 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 13:16:12.871  7251  7251 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-05 13:16:12.889  7251  7666 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 13:16:12.893  3386  3386 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 13:16:12.893  3386  3386 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:12.893  3386  3386 I LgeMiscReceiver: networkInfo.isConnected() = false
08-05 13:16:12.894  7114  7668 W FormManager: Network not available. Please check & try again.
08-05 13:16:12.896  7288  7288 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-05 13:16:12.897  7288  7288 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-05 13:16:12.897  7114  7669 V FormManager: Network unavailable.
08-05 13:16:12.906  1036  1999 V SIM_STK : Menu title from STK is T-Mobile
08-05 13:16:12.906  1036  1999 V SIM_STK : Menu title from STK is T-Mobile
,08-05 13:16:12.907  7114  7669 V FormManager: Network unavailable.
08-05 13:16:12.907  7345  7345 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:16:12
08-05 13:16:12.908  7345  7345 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 13:16:12.908  7345  7345 D Weather.Utils: 2 : All the weather widget is gone.
08-05 13:16:12.908  7345  7345 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 13:16:12.909  7345  7345 D WeatherAncestor: connectivity changed - connection : true
08-05 13:16:12.909  7345  7345 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@128ce2af
08-05 13:16:12.910  7345  7345 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 13:16:12.910  7345  7345 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 13:16:12.910  7345  7345 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-05 13:16:12.910  7345  7345 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 13:16:12.911  7345  7345 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:16:12
08-05 13:16:12.927  6377  6377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-05 13:16:12.928  6377  7024 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-05 13:16:12.939  2154  2154 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-05 13:16:12.948  7217  7217 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-05 13:16:12.948  7217  7217 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:12.948  7217  7217 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 13:16:12.949  7217  7217 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-05 13:16:12.950  7217  7217 I AppUp4:CustModeStarterReceiver: onReceive
,08-05 13:16:12.953  7217  7217 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@b619a89
08-05 13:16:12.954  7217  7217 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 13:16:12.954  7217  7217 D AppUp4:CustFacade: isPhone : true
08-05 13:16:12.954  7217  7217 D AppUp4:CustModeStarterReceiver: begin check event
08-05 13:16:12.954  7217  7217 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-05 13:16:12.957  1036  1908 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-05 13:16:12.957  4691  4691 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:12.957  4691  4691 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 13:16:12.958  4691  4691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 13:16:12.959  4691  4691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 13:16:12.962  7143  7143 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-05 13:16:12.963  4691  7671 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-05 13:16:12.964  7143  7143 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-05 13:16:12.965  7143  7143 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-05 13:16:12.965  7143  7143 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-05 13:16:12.965  7143  7143 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-05 13:16:12.965  7143  7143 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 13:16:12.965  7143  7143 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-05 13:16:12.965  7143  7143 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-05 13:16:12.965  7143  7143 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-05 13:16:12.965  7143  7143 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 13:16:12.965  7143  7143 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-05 13:16:12.965  7143  7143 I BluetoothA2dpServiceJni: classInitNative
08-05 13:16:12.965  7143  7143 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-05 13:16:12.965  7143  7143 D A2dpStateMachine: make
08-05 13:16:12.966  7251  7251 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-05 13:16:12.966  7143  7143 I bluedroid-qcom: get_profile_interface a2dp
08-05 13:16:12.966  7143  7674 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-05 13:16:12.968  7143  7143 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-05 13:16:12.968  4691  7672 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:12.968  7143  7143 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-05 13:16:12.968  4691  7672 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 13:16:12.969  7143  7143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128ce2af
08-05 13:16:12.969  7143  7673 D A2dpStateMachine: Enter Disconnected: -2
08-05 13:16:12.969  7143  7143 I BluetoothHidServiceJni: classInitNative: succeeds
08-05 13:16:12.970  7143  7143 D HidService: Received start request. Starting profile...
08-05 13:16:12.970  7143  7143 I bluedroid-qcom: get_profile_interface hidhost
08-05 13:16:12.970  7143  7143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128ce2af
08-05 13:16:12.970  7143  7143 D HeadsetStateMachine: Proxy object connected
08-05 13:16:12.971  7143  7143 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-05 13:16:12.971  7143  7143 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-05 13:16:12.971  7143  7143 I BluetoothHealthServiceJni: classInitNative: succeeds
08-05 13:16:12.972  7143  7143 D HealthService: Received start request. Starting profile...
08-05 13:16:12.974  7143  7143 I bluedroid-qcom: get_profile_interface health
08-05 13:16:12.974  7143  7143 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-05 13:16:12.974  7143  7143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128ce2af
08-05 13:16:12.980  7143  7143 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-05 13:16:12.980  7143  7143 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-05 13:16:12.980  7143  7656 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-05 13:16:12.981  7143  7656 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-05 13:16:12.981  7143  7656 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-05 13:16:12.982  7143  7143 D PanService: Received start request. Starting profile...
08-05 13:16:12.982  7143  7143 D BluetoothPanServiceJni: initializeNative(L110): pan
08-05 13:16:12.982  7143  7143 I bluedroid-qcom: get_profile_interface pan
08-05 13:16:12.984  7251  7678 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:12.988  3386  3386 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 13:16:12.988  3386  3386 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:12.988  7143  7143 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-05 13:16:12.988  3386  3386 I LgeMiscReceiver: networkInfo.isConnected() = false
08-05 13:16:12.988  7143  7143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128ce2af
08-05 13:16:12.989  7143  7143 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-05 13:16:12.990  7288  7288 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-05 13:16:12.990  7288  7288 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-05 13:16:12.993  7114  7680 W FormManager: Network not available. Please check & try again.
,08-05 13:16:12.997  7143  7143 D BtGatt.DebugUtils: handleDebugAction() action=null
08-05 13:16:12.997  7143  7143 D BtGatt.GattService: Received start request. Starting profile...
08-05 13:16:12.997  7143  7143 D BtGatt.GattService: start()
08-05 13:16:12.997  7143  7143 I bluedroid-qcom: get_profile_interface gatt
08-05 13:16:12.997  7143  7143 D BtGatt.AdvertiseManager: advertise manager created
08-05 13:16:13.000  7345  7345 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:16:13
08-05 13:16:13.001  7345  7345 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 13:16:13.001  7345  7345 D Weather.Utils: 2 : All the weather widget is gone.
08-05 13:16:13.002  7345  7345 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 13:16:13.002  7345  7345 D WeatherAncestor: connectivity changed - connection : true
08-05 13:16:13.002  7345  7345 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@128ce2af
08-05 13:16:13.002  7114  7683 V FormManager: Network unavailable.
08-05 13:16:13.002  7143  7143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128ce2af
08-05 13:16:13.003  7143  7143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128ce2af
08-05 13:16:13.003  7345  7345 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 13:16:13.003  7345  7345 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 13:16:13.003  7345  7345 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-05 13:16:13.003  7345  7345 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 13:16:13.003  7143  7143 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-05 13:16:13.003  7345  7345 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:16:13
08-05 13:16:13.004  7114  7683 V FormManager: Network unavailable.
08-05 13:16:13.005  7143  7143 V BluetoothMapService: BluetoothMapBinder()
08-05 13:16:13.005  7143  7143 D BluetoothMapService: Received start request. Starting profile...
08-05 13:16:13.005  7143  7143 D BluetoothMapService: start()
,08-05 13:16:13.007  7143  7143 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-05 13:16:13.007  7143  7143 D BluetoothMapEmailAppObserver: createReceiver()
08-05 13:16:13.009  7143  7143 D BluetoothMapEmailAppObserver: initObservers()
08-05 13:16:13.009  7143  7143 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-05 13:16:13.015  7143  7143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128ce2af
08-05 13:16:13.021  7143  7143 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-05 13:16:13.024  7143  7143 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 13:16:13.026  7143  7143 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 13:16:13.026  7143  7143 V PanService: [BTUI] SIM Extra State :ABSENT
08-05 13:16:13.028  7143  7143 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 13:16:13.030  7143  7143 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-05 13:16:13.031  7143  7143 V BluetoothMapService: Handler(): got msg=1
08-05 13:16:13.031  7143  7616 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-05 13:16:13.031  7143  7616 I bluedroid-qcom: enable
08-05 13:16:13.031  7143  7686 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-05 13:16:13.031  7143  7686 I bt-btu  : btu_task pending for preload complete event
08-05 13:16:13.032  7143  7616 I bt_hci_bdroid: init
08-05 13:16:13.032  7143  7616 I bt_vendor: bt-vendor : init
08-05 13:16:13.032  7143  7616 I bt_vendor: bt-vendor : get_bt_soc_type
08-05 13:16:13.032  7143  7616 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-05 13:16:13.032  7143  7616 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-05 13:16:13.032  7143  7616 D bt_userial_mct: userial_init
08-05 13:16:13.033  7143  7616 D bt_hci_bdroid: set_power 1
08-05 13:16:13.033  7143  7616 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-05 13:16:13.033  7143  7616 I bt_vendor: Starting hciattach daemon
08-05 13:16:13.033  7143  7616 I bt_vendor: try to set true
08-05 13:16:13.033  7143  7143 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-05 13:16:13.031  7689  7689 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 13:16:13.031  7689  7689 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 13:16:13.036  7143  7143 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 13:16:13.036  7143  7143 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 13:16:13.036  7143  7143 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 13:16:13.036  7143  7143 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:13.036  7143  7143 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-05 13:16:13.048  7690  7690 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-05 13:16:13.096  7696  7696 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-05 13:16:13.104  7697  7697 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-05 13:16:13.135  7699  7699 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 13:16:13.141  7700  7700 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-05 13:16:13.150  7701  7701 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 13:16:13.159  7702  7702 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-05 13:16:13.172  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 7700
,08-05 13:16:13.179  7704  7704 I libmdmdetect: ESOC framework not supported
08-05 13:16:13.181  7704  7704 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-05 13:16:13.190  7704  7704 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-05 13:16:13.190  7704  7704 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-05 13:16:13.190  7704  7704 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-05 13:16:13.190  7704  7704 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-05 13:16:13.190  7704  7704 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-05 13:16:13.191  7704  7704 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-05 13:16:13.191  7704  7704 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-05 13:16:13.236  7704  7705 E QC-QMI  : qmi_client [7704] 14: failed to locate client data
,08-05 13:16:13.237   485   485 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-05 13:16:13.237   485   485 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-05 13:16:13.285  7706  7706 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-05 13:16:13.318  7710  7710 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-05 13:16:13.385  7143  7616 I bt_vendor: bluetooth satus is on
,08-05 13:16:13.385  7143  7616 D bt_hci_bdroid: preload
,08-05 13:16:13.386  7143  7688 D bt_userial_mct: userial_open(port:0)
,08-05 13:16:13.386  7143  7688 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-05 13:16:13.390  7143  7688 I bt_vendor: Done intiailizing UART
,08-05 13:16:13.394  7143  7688 I bt_vendor: Done intiailizing UART
08-05 13:16:13.394  7143  7688 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-05 13:16:13.394  7143  7688 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-05 13:16:13.395  7143  7686 I bt-btu  : btu_task received preload complete event
08-05 13:16:13.396  7143  7686 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001,
08-05 13:16:13.396  7143  7686 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f,
,08-05 13:16:13.404  7143  7715 D bt_userial_mct: Entering userial_read_thread()
08-05 13:16:13.405  7143  7686 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-05 13:16:13.417  7143  7686 I         : BTE_InitTraceLevels -- TRC_HCI
08-05 13:16:13.417  7143  7686 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-05 13:16:13.417  7143  7686 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-05 13:16:13.417  7143  7686 I         : BTE_InitTraceLevels -- TRC_AVDT
08-05 13:16:13.417  7143  7686 I         : BTE_InitTraceLevels -- TRC_AVRC
08-05 13:16:13.417  7143  7686 I         : BTE_InitTraceLevels -- TRC_A2D
08-05 13:16:13.417  7143  7686 I         : BTE_InitTraceLevels -- TRC_BNEP
08-05 13:16:13.417  7143  7686 I         : BTE_InitTraceLevels -- TRC_BTM
08-05 13:16:13.417  7143  7686 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-05 13:16:13.417  7143  7686 I         : BTE_InitTraceLevels -- TRC_GAP
08-05 13:16:13.417  7143  7686 I         : BTE_InitTraceLevels -- TRC_PAN
08-05 13:16:13.417  7143  7686 I         : BTE_InitTraceLevels -- TRC_SDP
08-05 13:16:13.417  7143  7686 I         : BTE_InitTraceLevels -- TRC_GATT
08-05 13:16:13.417  7143  7686 I         : BTE_InitTraceLevels -- TRC_SMP
08-05 13:16:13.417  7143  7686 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-05 13:16:13.417  7143  7686 I         : BTE_InitTraceLevels -- TRC_BTIF
08-05 13:16:13.473  7143  7686 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-05 13:16:13.473  7143  7686 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa022d061 
08-05 13:16:13.473  7143  7686 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa022d061 
,08-05 13:16:13.499  7143  7620 E bt-btif : Calling BTA_HhEnable
08-05 13:16:13.500  7143  7620 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-05 13:16:13.500  7143  7620 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-05 13:16:13.506  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-05 13:16:13.506  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-05 13:16:13.507  7143  7686 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-05 13:16:13.507  7143  7686 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-05 13:16:13.507  7143  7686 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-05 13:16:13.507  7143  7686 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-05 13:16:13.507  7143  7686 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-05 13:16:13.508  7143  7620 D BluetoothAdapterProperties: Name is: G3
08-05 13:16:13.510  7143  7620 D BluetoothAdapterProperties: Scan Mode:20
08-05 13:16:13.510  7143  7620 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 13:16:13.511  7143  7620 D bt_hci_bdroid: postload
08-05 13:16:13.511  7143  7688 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 13:16:13.512  7143  7688 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 13:16:13.515  7143  7688 D bt_hci_bdroid: Used up Tx Cmd credits
,08-05 13:16:13.519  7143  7686 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-05 13:16:13.520  7143  7620 D bte_conf: Device ID record 1 : primary
08-05 13:16:13.520  7143  7620 D bte_conf:   vendorId            = 00c4
08-05 13:16:13.520  7143  7620 D bte_conf:   vendorIdSource      = 0001
08-05 13:16:13.520  7143  7620 D bte_conf:   product             = 13a1
08-05 13:16:13.520  7143  7620 D bte_conf:   version             = 1000
08-05 13:16:13.520  7143  7620 D bte_conf:   clientExecutableURL = 
08-05 13:16:13.520  7143  7620 D bte_conf:   serviceDescription  = 
08-05 13:16:13.520  7143  7620 D bte_conf:   documentationURL    = 
08-05 13:16:13.520  7143  7620 D bte_conf: bte_load_did_conf no section named DID2.
08-05 13:16:13.522  7143  7688 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 13:16:13.525  7143  7715 E bt_mct  : hci lib postload completed
08-05 13:16:13.521  7720  7720 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 13:16:13.531  7143  7686 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 13:16:13.531  7143  7686 W bt-smp  : Plain text(LSB ~ MSB) = 39 52 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 13:16:13.531  7143  7686 W bt-smp  : Encrypted text(LSB ~ MSB) = 70 47 95 d3 fd e9 0d b8 b2 4b 1b 2c 9e 71 f8 49 
08-05 13:16:13.532  7143  7686 W bt-btm  : Stopping oneshot timer
08-05 13:16:13.532  7143  7616 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-05 13:16:13.532  7143  7616 D BluetoothAdapterProperties: ScanMode =  20
08-05 13:16:13.532  7143  7616 D BluetoothAdapterProperties: State =  11
08-05 13:16:13.533  7143  7616 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-05 13:16:13.533  7143  7616 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-05 13:16:13.533  7143  7616 D BluetoothAdapterProperties: Setting state to 12
08-05 13:16:13.531  7720  7720 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 13:16:13.535  7143  7616 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-05 13:16:13.535  7143  7620 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-05 13:16:13.535  7143  7620 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-05 13:16:13.543  1036  1109 D BluetoothManagerService: Message: 60
08-05 13:16:13.543  1036  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-05 13:16:13.543  1036  1109 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
,08-05 13:16:13.571  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 13:16:13.571  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:13.571  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:13.571  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 13:16:13.571  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 13:16:13.571  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 13:16:13.571  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 13:16:13.571  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 13:16:13.581  7143  7686 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 13:16:13.581  7143  7686 W bt-smp  : Plain text(LSB ~ MSB) = 52 d8 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 13:16:13.581  7143  7686 W bt-smp  : Encrypted text(LSB ~ MSB) = 6d 55 ff c5 7f 2e e1 1e ba 9a 98 88 a9 fe 22 38 
08-05 13:16:13.581  7143  7686 W bt-btm  : Stopping oneshot timer
08-05 13:16:13.583  7143  7620 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 13:16:13.584  7143  7620 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-05 13:16:13.591  6900  6900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 13:16:13.597  7143  7616 I BluetoothAdapterState: Entering On State
,08-05 13:16:13.600  7143  7686 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 13:16:13.600  7143  7686 W bt-smp  : Plain text(LSB ~ MSB) = ab 11 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 13:16:13.600  7143  7686 W bt-smp  : Encrypted text(LSB ~ MSB) = 70 29 9f bb d6 a7 65 55 a5 30 f7 c6 51 36 66 67 
08-05 13:16:13.600  7143  7686 W bt-btm  : Stopping oneshot timer
08-05 13:16:13.613  7143  7686 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 13:16:13.613  7143  7686 W bt-smp  : Plain text(LSB ~ MSB) = 67 06 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 13:16:13.613  7143  7686 W bt-smp  : Encrypted text(LSB ~ MSB) = 3d 01 d9 d7 39 2f 7c ee 02 2e e1 9e e5 2f 06 b3 
,08-05 13:16:13.615  7143  7686 W bt-btm  : Stopping oneshot timer
08-05 13:16:13.616  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 13:16:13.616  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:13.616  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:13.616  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 13:16:13.616  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 13:16:13.616  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 13:16:13.616  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 13:16:13.616  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 13:16:13.627  6900  6900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-05 13:16:13.630  7143  7686 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 13:16:13.630  7143  7686 W bt-smp  : Plain text(LSB ~ MSB) = d5 6c 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 13:16:13.630  7143  7686 W bt-smp  : Encrypted text(LSB ~ MSB) = 76 bc ae 80 d5 7b f0 d4 f9 72 53 72 b6 72 9d 94 
08-05 13:16:13.630  7143  7686 W bt-btm  : Stopping oneshot timer
08-05 13:16:13.640  7143  7616 D LGBluetoothServiceAdapter: [BTUI] OnState
08-05 13:16:13.640  7143  7616 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-05 13:16:13.640  7143  7616 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-05 13:16:13.643  7143  7616 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-05 13:16:13.644  7004  7019 D BluetoothPbap: onBluetoothStateChange: up=true
08-05 13:16:13.652  7725  7725 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-05 13:16:13.659  7143  7616 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-05 13:16:13.669  1855  2445 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-05 13:16:13.674  7004  7275 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-05 13:16:13.674  1855  1855 D BluetoothHeadset: Proxy object connected
08-05 13:16:13.678  1855  1870 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 13:16:13.679  7004  7004 D BluetoothInputDevice: Proxy object connected
08-05 13:16:13.679  7004  7004 D HidProfile: Bluetooth service connected
08-05 13:16:13.681  1855  1855 D BluetoothHeadset: Proxy object connected
,08-05 13:16:13.682  7004  7019 D BluetoothPan: onBluetoothStateChange on: true
08-05 13:16:13.682  7004  7019 D BluetoothPan: onBluetoothStateChange call bindService
08-05 13:16:13.688  1855  1871 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 13:16:13.688  7004  7004 D BluetoothPan: BluetoothPAN Proxy object connected
08-05 13:16:13.688  7004  7004 D PanProfile: Bluetooth service connected
08-05 13:16:13.691  1855  1855 D BluetoothHeadset: Proxy object connected
08-05 13:16:13.692  7004  7020 D BluetoothMap: onBluetoothStateChange: up=true
08-05 13:16:13.695  1036  1109 D BluetoothA2dp: onBluetoothStateChange: up=true
08-05 13:16:13.696  7004  7004 D BluetoothMap: Proxy object connected
08-05 13:16:13.696  7004  7004 D MapProfile: Bluetooth service connected
08-05 13:16:13.696  7004  7004 D BluetoothMap: getConnectedDevices()
08-05 13:16:13.696  1036  1109 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 13:16:13.696  1036  1036 D BluetoothHeadset: Proxy object connected
08-05 13:16:13.696  1036  1109 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-05 13:16:13.697  1036  1109 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-05 13:16:13.697  7143  7160 V BluetoothMapService: getConnectedDevices()
,08-05 13:16:13.702  1946  1946 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:13.702  1946  2129 D LGBluetoothAPIService: Message: 1
08-05 13:16:13.702  1946  2129 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,08-05 13:16:13.703  1036  1036 D BluetoothA2dp: Proxy object connected
08-05 13:16:13.703  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 13:16:13.706  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-05 13:16:13.707  1946  2129 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-05 13:16:13.708  1036  1109 D BluetoothManagerService: Message: 40
08-05 13:16:13.708  1036  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-05 13:16:13.708  6900  6900 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-05 13:16:13.709  7143  7143 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:13.709  7143  7143 D BluetoothMapService: STATE_ON
08-05 13:16:13.711  7143  7143 D LGBluetoothAPIServer: [BTUI] onCreate()
08-05 13:16:13.711  7143  7143 D LGBluetoothAPIServer: [BTUI] onBind()
,08-05 13:16:13.712  7004  7004 D LocalBluetoothProfileManager: Adding local A2DP profile
08-05 13:16:13.713  1946  1946 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-05 13:16:13.714  1946  2129 D LGBluetoothAPIService: Message: 100
08-05 13:16:13.714  1946  2129 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-05 13:16:13.714  7143  7143 V BluetoothMapService: Handler(): got msg=1
08-05 13:16:13.715  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:13.715  7143  7143 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-05 13:16:13.715  1036  1109 D BluetoothManagerService: Message: 30
08-05 13:16:13.717  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:13.717  7143  7741 D BluetoothMapMasInstance: MAS initSocket()
08-05 13:16:13.717  7143  7741 D BluetoothMapMasInstance:   masId = 00
08-05 13:16:13.717  7143  7741 D BluetoothMapMasInstance:   msgTypes = 0e
08-05 13:16:13.717  7143  7741 D BluetoothMapMasInstance:   masName = SMS/MMS
08-05 13:16:13.717  7143  7741 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-05 13:16:13.719  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:13.719  7004  7004 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-05 13:16:13.720  7143  7741 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 13:16:13.721  7143  7741 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-05 13:16:13.721  7143  7741 V BluetoothMapMasInstance: Succeed to create listening socket 
08-05 13:16:13.721  7143  7741 D BluetoothMapMasInstance: Accepting socket connection...
08-05 13:16:13.722  7143  7620 D BluetoothAdapterProperties: Scan Mode:21
08-05 13:16:13.722  7143  7620 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-05 13:16:13.724  1036  1109 D BluetoothManagerService: Message: 30
,08-05 13:16:13.726  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:13.730  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:13.733  7143  7143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128ce2af
08-05 13:16:13.734  7143  7143 V BluetoothPbapService: Pbap Service onCreate
08-05 13:16:13.734  7143  7143 V BluetoothPbapService: Starting PBAP service
08-05 13:16:13.734  7004  7004 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-05 13:16:13.736  7004  7004 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-05 13:16:13.736  7143  7143 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-05 13:16:13.736  7143  7143 V BluetoothPbapService: Pbap Service onBind
08-05 13:16:13.738  7004  7004 D BluetoothA2dp: Proxy object connected
08-05 13:16:13.738  7004  7004 D A2dpProfile: Bluetooth service connected
,08-05 13:16:13.739  7143  7143 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:13.739  7143  7143 V BluetoothPbapService: state: 12
08-05 13:16:13.740  7004  7004 D BluetoothHeadset: Proxy object connected
08-05 13:16:13.740  7143  7143 V BluetoothPbapService: Handler(): got msg=1
08-05 13:16:13.740  7143  7143 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-05 13:16:13.740  7004  7004 D HeadsetProfile: Bluetooth service connected
08-05 13:16:13.741  7143  7143 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 13:16:13.741  7143  7143 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:13.741  7143  7143 V BluetoothPbapReceiver: ***********state = 12
08-05 13:16:13.741  7143  7744 V BluetoothPbapService: Pbap Service initSocket
08-05 13:16:13.742  1036  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:13.742  7143  7744 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 13:16:13.743  2154  2154 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 13:16:13.743  7143  7744 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-05 13:16:13.743  7004  7004 D BluetoothPbap: Proxy object connected
08-05 13:16:13.744  7143  7744 V BluetoothPbapService: Succeed to create listening socket 
08-05 13:16:13.744  7143  7744 V BluetoothPbapService: Accepting socket connection...
08-05 13:16:13.744  7004  7004 D PbapServerProfile: Bluetooth service connected
08-05 13:16:13.745  2154  2154 D c       : Getting all permits...
08-05 13:16:13.745  2154  2154 D a       : Opening database...
08-05 13:16:13.746  7004  7004 D DockEventReceiver: finishStartingService: stopping service
08-05 13:16:13.748  1036  1729 E Process : Error getting pid for '0'
08-05 13:16:13.748  2154  2154 D a       : Opening database auth.proximity.permit_store...
08-05 13:16:13.749  2154  2154 D a       : Closing database...
,08-05 13:16:13.758  7004  7004 D BluetoothPermissionRequest: onReceive
08-05 13:16:13.760  7004  7004 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-05 13:16:13.761  7004  7004 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-05 13:16:13.764  7143  7143 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-05 13:16:13.765  7143  7143 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-05 13:16:13.770  7143  7143 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-05 13:16:13.785  7143  7143 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-05 13:16:13.785  7143  7143 V BtOppService: onCreate
08-05 13:16:13.789  7143  7143 V BluetoothOppNotification: send message
08-05 13:16:13.791  7143  7143 V BtOppService: Starting RfcommListener
08-05 13:16:13.795  7143  7143 D BluetoothOppPreference: Dumping Names:  
08-05 13:16:13.796  7143  7143 D BluetoothOppPreference: {}
08-05 13:16:13.796  7143  7143 D BluetoothOppPreference: Dumping Channels:  
08-05 13:16:13.796  7143  7143 D BluetoothOppPreference: {}
08-05 13:16:13.796  7143  7143 V BtOppService: onStartCommand
08-05 13:16:13.798  7143  7753 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 13:16:13.798  7143  7753 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-05 13:16:13.800  7143  7753 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31b98038 on behalf of 
08-05 13:16:13.801  7143  7143 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:13.801  7143  7753 V BluetoothOppNotification: update too frequent, put in queue
08-05 13:16:13.801  7143  7143 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-05 13:16:13.801  7143  7753 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-05 13:16:13.802  7143  7750 V BtOppService: Deleted complete outbound shares, number =  0
08-05 13:16:13.803  7143  7143 V BluetoothOppNotification: new notify threadi!
08-05 13:16:13.804  7143  7143 V BluetoothOppNotification: send delay message
08-05 13:16:13.805  7143  7750 V BtOppService: Deleted complete inbound failed shares, number = 0
08-05 13:16:13.805  7143  7143 V BtOppService: start RfcommListener
08-05 13:16:13.806  7143  7750 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-05 13:16:13.806  7143  7754 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-05 13:16:13.807  7143  7143 V BtOppService: RfcommListener started
08-05 13:16:13.808  7143  7750 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@145cd811 on behalf of 
08-05 13:16:13.810  7143  7143 V BtOppService: ContentObserver received notification
08-05 13:16:13.814  7143  7755 V BtOppRfcommListener: Starting RFCOMM listener....
08-05 13:16:13.814  7143  7754 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23835d76 on behalf of 
08-05 13:16:13.815  7394  7440 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-05 13:16:13.817  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:13.819  7143  7755 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 13:16:13.820  7143  7757 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 13:16:13.820  7143  7757 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 13:16:13.820  7143  7755 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-05 13:16:13.820  7143  7755 V BtOppRfcommListener: Started RFCOMM listener....
08-05 13:16:13.820  7143  7755 I BtOppRfcommListener: Accept thread started.
08-05 13:16:13.820  7143  7755 V BtOppRfcommListener: Accepting connection...
08-05 13:16:13.822  7143  7754 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-05 13:16:13.822  7143  7757 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24acef77 on behalf of 
08-05 13:16:13.823  7143  7754 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-05 13:16:13.824  7143  7757 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-05 13:16:13.825  7143  7754 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ba267e4 on behalf of 
08-05 13:16:13.826  7143  7754 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-05 13:16:13.827  7143  7754 V BluetoothOppNotification: outbound notification was removed.
08-05 13:16:13.827  7143  7754 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-05 13:16:13.829  7143  7754 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e25e44d on behalf of 
,08-05 13:16:13.831  7143  7754 V BluetoothOppNotification: inbound: succ-0  fail-0
08-05 13:16:13.832  7143  7754 V BluetoothOppNotification: inbound notification was removed.
08-05 13:16:13.832  7143  7754 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 13:16:13.834  7143  7754 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23fdb02 on behalf of 
08-05 13:16:13.841  7143  7143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128ce2af
08-05 13:16:13.841  7143  7143 V BluetoothFtpService: Ftp Service onCreate
08-05 13:16:13.841  7143  7143 I BluetoothFtpService: Ftp Service onCreate
08-05 13:16:13.841  7143  7143 V BluetoothFtpService: Ftp Service onStartCommand
08-05 13:16:13.841  7143  7143 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:13.841  7143  7143 V BluetoothFtpService: Starting Listening on sockets
,08-05 13:16:13.842  7143  7143 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-05 13:16:13.842  7143  7143 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 13:16:13.842  7143  7143 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 13:16:13.842  7143  7143 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:13.842  7143  7143 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-05 13:16:13.842  7143  7143 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-05 13:16:13.844  7143  7143 V BtOppService: ContentObserver received notification
08-05 13:16:13.844  7143  7143 V BluetoothFtpService: Handler(): got msg=1
08-05 13:16:13.845  7143  7143 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-05 13:16:13.845  7143  7143 V BluetoothFtpService: Ftp Service initSocket
08-05 13:16:13.848  7143  7759 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 13:16:13.848  1036  2035 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:13.848  7143  7759 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 13:16:13.849  7143  7143 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 13:16:13.850  7143  7143 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-05 13:16:13.850  7143  7143 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-05 13:16:13.852  7143  7759 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5101e50 on behalf of 
08-05 13:16:13.852  7143  7760 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-05 13:16:13.853  7143  7759 V BluetoothOppNotification: update too frequent, put in queue
,08-05 13:16:13.853  7143  7759 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-05 13:16:13.870  7143  7143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128ce2af
08-05 13:16:13.870  7143  7143 V BluetoothSapService: Sap Service onCreate
,08-05 13:16:13.872  7143  7143 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:13.873  7143  7143 V BluetoothSapService: state: 12
08-05 13:16:13.873  7143  7143 V BluetoothSapService: Starting SAP server process
08-05 13:16:13.874  7143  7143 V BluetoothSapService: SAP Service startRfcommListenerThread
08-05 13:16:13.871  7761  7761 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 13:16:13.871  7761  7761 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 13:16:13.878  7143  7762 V BluetoothSapService: Sap Service initRfcommSocket
08-05 13:16:13.878  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:13.879  7143  7762 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 13:16:13.883  7143  7762 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-05 13:16:13.883  7143  7762 V BluetoothSapService: Succeed to create listening socket 
08-05 13:16:13.883  7143  7762 V BluetoothSapService: Accepting socket connection...
,08-05 13:16:13.899  7761  7761 V BT_SAP  : Event pipe created
08-05 13:16:13.899  7761  7761 V BT_SAP  : create_server_socket qcom.sap.server
08-05 13:16:13.899  7761  7761 V BT_SAP  : created socket fd 6
,08-05 13:16:14.383  1036  1538 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:14.383  1036  1538 D LGWifiP2pService: DefaultState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 13:16:14.432  1036  1539 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-05 13:16:14.433  1036  1539 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-05 13:16:14.660  1036  1890 I ActivityManager: Killing 7543:com.lge.bnr/1000 (adj 15): empty #17
,08-05 13:16:14.692  1036  1576 W libprocessgroup: failed to open /acct/uid_1000/pid_7543/cgroup.procs: No such file or directory
,08-05 13:16:14.806  7143  7143 V BluetoothOppNotification: new notify threadi!
08-05 13:16:14.806  7143  7143 V BluetoothOppNotification: send delay message
,08-05 13:16:14.813  7143  7772 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-05 13:16:14.815  7143  7772 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@160cf7c on behalf of 
08-05 13:16:14.815  7143  7772 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-05 13:16:14.817  7143  7772 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-05 13:16:14.818  7143  7772 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b585005 on behalf of 
08-05 13:16:14.818  7143  7772 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-05 13:16:14.826  7143  7772 V BluetoothOppNotification: outbound notification was removed.
08-05 13:16:14.826  7143  7772 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-05 13:16:14.828  7143  7772 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25d9c85a on behalf of 
08-05 13:16:14.828  7143  7772 V BluetoothOppNotification: inbound: succ-0  fail-0
08-05 13:16:14.830  7143  7772 V BluetoothOppNotification: inbound notification was removed.
08-05 13:16:14.830  7143  7772 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 13:16:14.832  7143  7772 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@861ea8b on behalf of 
08-05 13:16:14.846  1036  1890 I ActivityManager: Killing 6765:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-05 13:16:14.866  7086  7086 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-05 13:16:14.866  7086  7086 W System.err: android.os.DeadObjectException
08-05 13:16:14.866  7086  7086 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 13:16:14.866  7086  7086 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-05 13:16:14.866  7086  7086 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-05 13:16:14.866  7086  7086 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-05 13:16:14.866  7086  7086 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-05 13:16:14.866  7086  7086 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-05 13:16:14.866  7086  7086 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 13:16:14.866  7086  7086 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 13:16:14.866  7086  7086 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 13:16:14.866  7086  7086 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 13:16:14.866  7086  7086 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 13:16:14.867  7086  7086 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 13:16:14.867  7086  7086 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 13:16:14.867  7086  7086 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 13:16:14.867  7086  7086 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-05 13:16:14.867  7086  7086 W System.err: android.os.DeadObjectException
08-05 13:16:14.867  7086  7086 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 13:16:14.867  7086  7086 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-05 13:16:14.867  7086  7086 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-05 13:16:14.867  7086  7086 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-05 13:16:14.867  7086  7086 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-05 13:16:14.867  7086  7086 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-05 13:16:14.867  7086  7086 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 13:16:14.867  7086  7086 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 13:16:14.867  7086  7086 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 13:16:14.867  7086  7086 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 13:16:14.867  7086  7086 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 13:16:14.867  7086  7086 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 13:16:14.868  7086  7086 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 13:16:14.868  7086  7086 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 13:16:14.868  7086  7086 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-05 13:16:14.868  7086  7086 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-05 13:16:14.884  1036  1576 W libprocessgroup: failed to open /acct/uid_1000/pid_6765/cgroup.procs: No such file or directory
08-05 13:16:14.884  1036  1576 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-05 13:16:14.889  7086  7086 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-05 13:16:14.889  7086  7086 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-05 13:16:14.917  1036  1926 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7773 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-05 13:16:14.958  7086  7086 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-05 13:16:14.989  7773  7773 D UEI.SmartControl: Quickset Services start...
,08-05 13:16:14.993  7773  7773 I UEI.SmartControl: Manufacture = LGE
08-05 13:16:14.994  7773  7773 D UEI.SmartControl: Id = LGNevo
08-05 13:16:14.995  7773  7773 D UEI.SmartControl: File observer start...
08-05 13:16:14.996  7773  7773 E UEI.SmartControl: IR Port is disabled: false
08-05 13:16:14.996  7773  7773 D UEI.SmartControl: Starting file observer...
08-05 13:16:14.996  7773  7773 D UEI.SmartControl: Extracting JNI libs...
08-05 13:16:14.997  7773  7773 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-05 13:16:15.086  7773  7773 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-05 13:16:15.087  7773  7773 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-05 13:16:15.087  7773  7773 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-05 13:16:15.115  7773  7773 I UEI.SmartControl: --- Selecting new region: 6
,08-05 13:16:15.117  7773  7773 I UEI.SmartControl: Model = LG-D855
,08-05 13:16:15.119  7773  7773 D UEI.SmartControl: QS Service created
,08-05 13:16:15.130  7773  7773 I UEI.SmartControl: Service initServices...
,08-05 13:16:15.135  7773  7773 D UEI.SmartControl: QS start get config
08-05 13:16:15.181  7773  7773 D UEI.SmartControl: Loading JNI Libs...
,08-05 13:16:15.375  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 13:16:15.375  1036  1052 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3bd969b7 mBinding = false
08-05 13:16:15.391  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 13:16:15.391  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-05 13:16:15.392  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-05 13:16:15.394  1036  1109 D BluetoothManagerService: Message: 2
08-05 13:16:15.395  1036  1109 D BluetoothManagerService: Sending off request.
08-05 13:16:15.396  7143  7739 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-05 13:16:15.396  7143  7616 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-05 13:16:15.396  7143  7616 D BluetoothAdapterProperties: Setting state to 13
08-05 13:16:15.396  7143  7616 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-05 13:16:15.398  1036  1109 D BluetoothManagerService: Message: 60
08-05 13:16:15.398  1036  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-05 13:16:15.398  1036  1109 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-05 13:16:15.399  7143  7616 D BluetoothAdapterProperties: onBluetoothDisable()
08-05 13:16:15.399  7143  7616 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-05 13:16:15.404  7143  7143 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:15.404  7143  7143 D BluetoothMapService: STATE_TURNING_OFF
08-05 13:16:15.405  7143  7143 V BluetoothMapService: Handler(): got msg=4
08-05 13:16:15.405  7143  7143 D BluetoothMapService: MAP Service closeService in
08-05 13:16:15.405  7143  7143 D BluetoothMapMasInstance: MAP Service shutdown
08-05 13:16:15.405  1946  1946 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:15.406  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 13:16:15.408  7143  7741 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-05 13:16:15.408  7143  7741 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 13:16:15.408  7143  7741 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-05 13:16:15.408  7143  7741 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-05 13:16:15.408  7143  7741 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-05 13:16:15.408  7143  7741 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-05 13:16:15.408  7143  7741 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-05 13:16:15.408  7143  7741 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-05 13:16:15.409  7143  7143 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 13:16:15.409  7143  7143 V BluetoothMapService: MAP Service closeService out
08-05 13:16:15.409  7143  7143 V BtOppService: Receiver DISABLED_ACTION 
08-05 13:16:15.409  7143  7143 I BtOppRfcommListener: stopping Accept Thread
08-05 13:16:15.409  7143  7143 V BtOppRfcommListener: close mBtServerSocket
08-05 13:16:15.410  7143  7755 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 13:16:15.411  7143  7755 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-05 13:16:15.411  7143  7143 V BtOppRfcommListener: waiting for thread to terminate
08-05 13:16:15.412  7143  7143 V BtOppRfcommListener: done waiting for thread to terminate
08-05 13:16:15.415  7004  7004 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-05 13:16:15.415  6900  6900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 13:16:15.416  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 13:16:15.416  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:15.416  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:15.416  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 13:16:15.416  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 13:16:15.416  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 13:16:15.416  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 13:16:15.416  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 13:16:15.416  6900  6900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 13:16:15.416  6900  6900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 13:16:15.419  7143  7620 D BluetoothAdapterProperties: Scan Mode:20
,08-05 13:16:15.424  7143  7616 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-05 13:16:15.425  7143  7616 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-05 13:16:15.427  6900  6900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 13:16:15.427  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 13:16:15.427  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:15.427  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:15.427  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 13:16:15.427  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 13:16:15.427  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 13:16:15.427  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 13:16:15.427  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 13:16:15.428  7143  7744 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-05 13:16:15.428  6900  6900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 13:16:15.428  6900  6900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 13:16:15.428  7143  7686 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-05 13:16:15.429  7143  7686 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-05 13:16:15.430  7143  7686 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 13:16:15.430  7143  7686 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 13:16:15.430  7143  7686 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 13:16:15.430  7143  7686 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 13:16:15.430  7143  7686 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 13:16:15.430  7143  7686 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 13:16:15.430  7143  7686 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 13:16:15.430  7143  7686 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 13:16:15.430  7143  7686 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 13:16:15.430  7143  7686 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-05 13:16:15.430  7143  7686 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-05 13:16:15.430  7143  7686 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-05 13:16:15.430  7143  7760 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 13:16:15.431  7143  7762 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 13:16:15.432  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:15.434  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:15.434  7004  7004 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-05 13:16:15.439  7143  7143 V BtOppService: onDestroy
08-05 13:16:15.448  7143  7143 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,08-05 13:16:15.453  7143  7143 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 13:16:15.453  7143  7143 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:15.453  7143  7143 V BluetoothPbapReceiver: ***********state = 13
08-05 13:16:15.456  7143  7143 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-05 13:16:15.459  7143  7143 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:15.459  7143  7143 V BluetoothPbapService: state: 13
08-05 13:16:15.459  7143  7143 V BluetoothPbapService: Pbap Service closeService in
08-05 13:16:15.460  7004  7004 D DockEventReceiver: finishStartingService: stopping service
,08-05 13:16:15.464  2154  2154 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 13:16:15.465  7143  7143 V BluetoothPbapService: successfully stopped pbap service
08-05 13:16:15.465  7143  7143 V BluetoothPbapService: Pbap Service closeService out
08-05 13:16:15.465  7143  7143 V BluetoothPbapService: Pbap Service onDestroy
08-05 13:16:15.466  7143  7143 V BluetoothPbapService: Pbap Service closeService in
08-05 13:16:15.466  7143  7143 V BluetoothPbapService: Pbap Service closeService out
08-05 13:16:15.466  7143  7143 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-05 13:16:15.463  7004  7004 D BluetoothPbap: Proxy object disconnected
08-05 13:16:15.473  7004  7004 D PbapServerProfile: Bluetooth service disconnected
,08-05 13:16:15.480  7004  7004 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-05 13:16:15.483  7004  7004 D BluetoothPermissionRequest: onReceive
08-05 13:16:15.483  7004  7004 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-05 13:16:15.489  7004  7004 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 13:16:15.493  7143  7143 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF,
08-05 13:16:15.493  7143  7143 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-05 13:16:15.495  7143  7143 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-05 13:16:15.503  7143  7143 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:15.503  7143  7143 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-05 13:16:15.504  7143  7143 V BluetoothFtpService: Ftp Service onStartCommand
08-05 13:16:15.504  7143  7143 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:15.504  7143  7143 V BluetoothFtpService: Ftp Service closeService
08-05 13:16:15.504  7143  7143 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-05 13:16:15.505  7143  7143 V BluetoothFtpService: successfully stopped ftp service
08-05 13:16:15.505  7143  7143 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 13:16:15.505  7143  7143 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 13:16:15.505  7143  7143 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 13:16:15.506  7143  7143 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:15.506  7143  7143 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-05 13:16:15.506  7143  7143 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-05 13:16:15.506  7143  7143 V BluetoothFtpService: Ftp Service onDestroy
,08-05 13:16:15.506  7143  7143 V BluetoothFtpService: Ftp Service closeService
08-05 13:16:15.509  7143  7143 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:15.509  7143  7143 V BluetoothSapService: state: 13
08-05 13:16:15.509  7143  7143 V BluetoothSapService: Stopping SAP server process
08-05 13:16:15.510  7143  7143 V BluetoothSapService: Sap Service closeSapService in
08-05 13:16:15.510  7143  7143 V BluetoothSapService: Close listen Socket : 
08-05 13:16:15.510  7143  7143 V BluetoothSapService: Close rfcomm Socket : 
08-05 13:16:15.510  7143  7143 V BluetoothSapService: Close sapd  Socket : 
08-05 13:16:15.511  7143  7143 V BluetoothSapService: Sap Service closeSapService out
08-05 13:16:15.512  7143  7143 V BluetoothSapService: Sap Service onDestroy
08-05 13:16:15.512  7143  7143 V BluetoothSapService: Sap Service closeSapService in
08-05 13:16:15.512  7143  7143 V BluetoothSapService: Close listen Socket : 
08-05 13:16:15.512  7143  7143 V BluetoothSapService: Close rfcomm Socket : 
08-05 13:16:15.512  7143  7143 V BluetoothSapService: Close sapd  Socket : 
08-05 13:16:15.513  7143  7143 V BluetoothSapService: Sap Service closeSapService out
08-05 13:16:15.647  7773  7773 I UEI.SmartControl: Supports setup maps: true
,08-05 13:16:15.652  7773  7773 D UEI.SmartControl: QS start statue = true Error code = 0
08-05 13:16:15.652  7773  7773 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-05 13:16:15.652  7773  7773 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-05 13:16:15.653  7773  7773 I UEI.SmartControl: ### init IR Blaster...
08-05 13:16:15.661  7773  7773 D serial_port: Configuring serial port
08-05 13:16:15.665  7773  7773 E UEI.SmartControl: UEIBLaster setting for 616
08-05 13:16:15.665  7773  7773 I UEI.SmartControl: Setting serial record hearder size = 2
08-05 13:16:15.665  7773  7773 I UEI.SmartControl: configuring settings for MAXQ616
08-05 13:16:15.665  7773  7773 I UEI.SmartControl: Get version...
,08-05 13:16:15.679  7773  7824 D UEI.SmartControl: serial port data available: 21
,08-05 13:16:15.708  7773  7773 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-05 13:16:15.708  7773  7773 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-05 13:16:15.709  7773  7773 I UEI.SmartControl: QS saving settings...
,08-05 13:16:15.713  7773  7773 D UEI.SmartControl: IR Blaster version: 25672567
08-05 13:16:15.730  7773  7824 D UEI.SmartControl: serial port data available: 4
,08-05 13:16:15.774  7773  7831 I UEI.SmartControl: Device manager: loading config....
,08-05 13:16:15.776  7773  7831 D UEI.SmartControl: ----------- loading internal config...
08-05 13:16:15.779  7773  7773 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-05 13:16:15.783  7773  7773 E UEI.SmartControl: Services init done
08-05 13:16:15.783  7773  7773 D UEI.SmartControl: QS Service init finished
08-05 13:16:15.785  7773  7773 D UEI.SmartControl: QS Service version name: 2.1.91
08-05 13:16:15.785  7773  7773 D UEI.SmartControl: QS Service version code: 201091
08-05 13:16:15.787  7773  7773 D UEI.SmartControl: Service requested: Control
08-05 13:16:15.803  7773  7773 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-05 13:16:15.804  7773  7831 E UEI.SmartControl: Loading SETTINGS...
08-05 13:16:15.811  7086  7086 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-05 13:16:15.812  7773  7788 I UEI.SmartControl: ------ IControl API: 11
08-05 13:16:15.815  7773  7788 I UEI.SmartControl: Registering callback...
08-05 13:16:15.817  7773  7789 I UEI.SmartControl: ------ IControl API: 19
08-05 13:16:15.819  7773  7789 I UEI.SmartControl: Registering Services Ready callback...
08-05 13:16:15.819  7773  7831 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-05 13:16:15.821  1036  1890 I ActivityManager: Killing 7086:com.lge.qremote/u0a112 (adj 15): empty #17
,08-05 13:16:15.830  7773  7830 I UEI.SmartControl: Notify AllClients services are ready: 0
08-05 13:16:15.830  7773  7830 D UEI.SmartControl: -----service ready thread exits
08-05 13:16:15.920  1036  2036 W libprocessgroup: failed to open /acct/uid_10112/pid_7086/cgroup.procs: No such file or directory
,08-05 13:16:15.926  7773  7773 D UEI.SmartControl: Internal service binding...
,08-05 13:16:16.427  7143  7620 D bt_hci_bdroid: cleanup
,08-05 13:16:16.434  7143  7688 I bt_lpm  : LPM is already off!!!
08-05 13:16:16.437  7143  7715 I bt_userial_mct: exiting userial_read_thread
08-05 13:16:16.437  7143  7715 D bt_userial_mct: Leaving userial_evt_read_thread()
08-05 13:16:16.438  7143  7686 W bt-btif : ag scb idx 1 not allocated
08-05 13:16:16.438  7143  7686 E bt-btif : BTA AG is already disabled, ignoring ...
08-05 13:16:16.438  7143  7686 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 13:16:16.438  7143  7686 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 13:16:16.438  7143  7686 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 13:16:16.438  7143  7686 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 13:16:16.438  7143  7686 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 13:16:16.438  7143  7686 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 13:16:16.438  7143  7686 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 13:16:16.439  7143  7686 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 13:16:16.439  7143  7686 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 13:16:16.439  7143  7686 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 13:16:16.439  7143  7686 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 13:16:16.439  7143  7686 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 13:16:16.439  7143  7686 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 13:16:16.439  7143  7686 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 13:16:16.439  7143  7686 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 13:16:16.439  7143  7686 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 13:16:16.439  7143  7686 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 13:16:16.439  7143  7686 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 13:16:16.439  7143  7686 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-05 13:16:16.442  7143  7620 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-05 13:16:16.442  7143  7688 I bt_vendor: hw_epilog_process
08-05 13:16:16.445  7143  7620 D bt_hci_bdroid: cleanup Finalizing cleanup
08-05 13:16:16.445  7143  7620 D bt_userial_mct: userial_close
08-05 13:16:16.445  7143  7620 E bt_userial_mct: pthread_join() FAILED result:3
08-05 13:16:16.445  7143  7620 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-05 13:16:16.454  7143  7620 D bt_hci_bdroid: set_power 0
08-05 13:16:16.454  7143  7620 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-05 13:16:16.454  7143  7620 I bt_vendor: bluetooth satus is on
08-05 13:16:16.454  7143  7620 I bt_vendor: bt-vendor : resetting BT status
08-05 13:16:16.454  7143  7620 I bt_vendor: Starting hciattach daemon
08-05 13:16:16.454  7143  7620 I bt_vendor: try to set false
08-05 13:16:16.456  7143  7620 I bt_vendor: Starting hciattach daemon
08-05 13:16:16.457  7143  7620 I bt_vendor: try to set false
,08-05 13:16:16.460  7143  7620 I bt_vendor: cleanup
08-05 13:16:16.461  7143  7686 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-05 13:16:16.461  7143  7620 I GKI_LINUX: GKI_exit_task 0 done
08-05 13:16:16.461  7143  7620 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-05 13:16:16.463  7143  7616 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-05 13:16:16.469  7143  7143 D HeadsetService: Received stop request...Stopping profile...
,08-05 13:16:16.475  7143  7616 D BluetoothAdapterState: Stopping profile services that were post enabled
08-05 13:16:16.476  7143  7143 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-05 13:16:16.476  7143  7143 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 13:16:16.476  7143  7143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128ce2af
08-05 13:16:16.476  7143  7656 D HeadsetStateMachine: Exit Disconnected: -1
08-05 13:16:16.480  1855  1855 D BluetoothHeadset: Proxy object disconnected
08-05 13:16:16.480  1855  1855 D BluetoothHeadset: Proxy object disconnected
08-05 13:16:16.480  1855  1855 D BluetoothHeadset: Proxy object disconnected
08-05 13:16:16.482  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-05 13:16:16.482  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-05 13:16:16.485  7143  7143 D A2dpService: Received stop request...Stopping profile...
08-05 13:16:16.486  7143  7673 D A2dpStateMachine: Exit Disconnected: -1
08-05 13:16:16.487  7143  7143 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-05 13:16:16.489  7143  7143 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-05 13:16:16.489  7143  7143 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 13:16:16.489  7143  7143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128ce2af
08-05 13:16:16.491  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-05 13:16:16.491  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-05 13:16:16.492  7143  7143 D HidService: Received stop request...Stopping profile...
08-05 13:16:16.492  7143  7143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128ce2af
08-05 13:16:16.494  7143  7143 D HealthService: Received stop request...Stopping profile...
08-05 13:16:16.494  7143  7143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128ce2af
,08-05 13:16:16.500  7143  7143 D PanService: Received stop request...Stopping profile...
08-05 13:16:16.501  7143  7143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128ce2af
08-05 13:16:16.502  7143  7143 D BtGatt.DebugUtils: handleDebugAction() action=null
08-05 13:16:16.503  7143  7143 D BtGatt.GattService: Received stop request...Stopping profile...
08-05 13:16:16.503  7143  7143 D BtGatt.GattService: stop()
08-05 13:16:16.503  7143  7143 D BtGatt.AdvertiseManager: advertise clients cleared
08-05 13:16:16.505  7143  7143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128ce2af
08-05 13:16:16.506  7143  7143 D BluetoothMapService: Received stop request...Stopping profile...
08-05 13:16:16.506  7143  7143 D BluetoothMapService: stop()
,08-05 13:16:16.510  7143  7143 D BluetoothMapEmailAppObserver: deinitObservers()
08-05 13:16:16.510  7143  7143 D BluetoothMapEmailAppObserver: removeReceiver()
08-05 13:16:16.511  7143  7143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128ce2af
08-05 13:16:16.512  7143  7143 D HeadsetStateMachine: Unbinding service...
08-05 13:16:16.514  7143  7143 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 13:16:16.514  7143  7143 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 13:16:16.514  7143  7143 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 13:16:16.514  7143  7143 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 13:16:16.514  7143  7143 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-05 13:16:16.514  7143  7143 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 13:16:16.514  7143  7143 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-05 13:16:16.514  7143  7143 I BluetoothA2dpServiceJni: cleanupNative
08-05 13:16:16.515  7143  7674 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-05 13:16:16.515  7143  7143 I GKI_LINUX: GKI_exit_task 2 done
08-05 13:16:16.515  7143  7143 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-05 13:16:16.516  7143  7143 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-05 13:16:16.516  7143  7143 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-05 13:16:16.516  7143  7143 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-05 13:16:16.516  7143  7143 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 13:16:16.516  7143  7143 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 13:16:16.517  7143  7143 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-05 13:16:16.517  7143  7143 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-05 13:16:16.519  7143  7143 V BluetoothMapService: Handler(): got msg=4
,08-05 13:16:16.519  7143  7143 D BluetoothMapService: MAP Service closeService in
08-05 13:16:16.525  7143  7143 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 13:16:16.525  7143  7143 V BluetoothMapService: MAP Service closeService out
08-05 13:16:16.526  7143  7616 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-05 13:16:16.526  7143  7616 D BluetoothAdapterProperties: Setting state to 10
08-05 13:16:16.526  7143  7616 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-05 13:16:16.526  7143  7143 D BluetoothMapService: cleanup()
08-05 13:16:16.527  7143  7143 D BluetoothMapService: MAP Service closeService in
08-05 13:16:16.527  7143  7143 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 13:16:16.527  7143  7143 V BluetoothMapService: MAP Service closeService out
08-05 13:16:16.529  1036  1109 D BluetoothManagerService: Message: 60
08-05 13:16:16.529  1036  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-05 13:16:16.529  1036  1109 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-05 13:16:16.530  7143  7616 I BluetoothAdapterState: Entering OffState
08-05 13:16:16.530  7004  7020 D BluetoothPbap: onBluetoothStateChange: up=false
08-05 13:16:16.530  7004  7020 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 13:16:16.531  1855  1870 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 13:16:16.533  7004  7020 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-05 13:16:16.536  1855  2445 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 13:16:16.536  7004  7020 D BluetoothPan: onBluetoothStateChange on: false
08-05 13:16:16.537  1855  1871 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 13:16:16.538  7004  7020 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 13:16:16.538  7004  7020 D BluetoothMap: onBluetoothStateChange: up=false
08-05 13:16:16.539  1036  1109 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 13:16:16.539  1036  1109 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 13:16:16.540  1036  1109 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-05 13:16:16.540  1036  1109 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-05 13:16:16.541  1036  1109 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-05 13:16:16.541  1036  1109 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-05 13:16:16.541  1036  1109 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3bd969b7 mBinding = false
08-05 13:16:16.542  1036  1109 D BluetoothManagerService: Sending unbind request.
08-05 13:16:16.547  7143  7620 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-05 13:16:16.550  7143  7143 I GKI_LINUX: GKI_exit_task 1 done
08-05 13:16:16.550  7143  7143 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-05 13:16:16.550  7143  7143 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-05 13:16:16.550  7143  7143 I art     : --- WEIRD: removing null entry 248
08-05 13:16:16.550  7143  7143 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-05 13:16:16.551  7143  7143 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-05 13:16:16.552  7143  7143 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-05 13:16:16.553  1036  1109 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-05 13:16:16.555  7143  7143 I art     : System.exit called, status: 0
08-05 13:16:16.555  7143  7143 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-05 13:16:16.578   332  1387 V AudioFlinger: 7143 died, releasing its sessions
08-05 13:16:16.581  1946  1946 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-05 13:16:16.581  1946  2129 D LGBluetoothAPIService: Message: 101
08-05 13:16:16.581  1946  2129 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-05 13:16:16.582  1946  2129 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-05 13:16:16.582  1946  2129 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-05 13:16:16.583   332  1387 V AudioFlinger:  pid 1855 @ 0
08-05 13:16:16.583   332  1387 V AudioFlinger:  pid 3386 @ 1
08-05 13:16:16.583   332  1387 V AudioFlinger:  pid 3386 @ 2
08-05 13:16:16.583  7004  7004 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-05 13:16:16.634  1036  1729 I ActivityManager: Process com.android.bluetooth (pid 7143) has died
,08-05 13:16:16.635  1036  1729 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-05 13:16:16.635  1036  1729 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
08-05 13:16:16.649  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-05 13:16:16.649  7004  7004 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-05 13:16:16.649  7004  7004 D LGBluetoothEventManager: [BTUI] clear device connection state
08-05 13:16:16.652  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 13:16:16.654  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:16.656  1946  1946 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:16.657  1946  2129 D LGBluetoothAPIService: Message: 2
08-05 13:16:16.657  1946  2129 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-05 13:16:16.662  1604  1604 D BluetoothAdapter: 1066947649: getState() :  mService = null. Returning STATE_OFF
08-05 13:16:16.662  1604  1604 D BluetoothAdapter: 1066947649: getState() :  mService = null. Returning STATE_OFF
08-05 13:16:16.665  7004  7004 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-05 13:16:16.717  1036  1707 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7858 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-05 13:16:16.719  7004  7004 D DockEventReceiver: finishStartingService: stopping service
,08-05 13:16:16.798  7858  7858 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-05 13:16:16.798  7858  7858 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-05 13:16:16.799  7858  7858 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-05 13:16:16.799  7858  7858 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-05 13:16:16.820  7858  7858 D BluetoothAdapterApp: Loading JNI Library
,08-05 13:16:16.858  7858  7858 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@334133b7 Instance Count = 1
,08-05 13:16:16.865  7858  7858 D BluetoothAdapterApp: onCreate
08-05 13:16:16.891  7858  7858 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-05 13:16:16.891  7858  7858 D ProfileConfigQcom: Adding HeadsetService
08-05 13:16:16.892  7858  7858 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-05 13:16:16.892  7858  7858 D ProfileConfigQcom: Adding A2dpService
08-05 13:16:16.892  7858  7858 D ProfileConfigQcom: [BTUI] HidService is supported
08-05 13:16:16.892  7858  7858 D ProfileConfigQcom: Adding HidService
,08-05 13:16:16.892  7858  7858 D ProfileConfigQcom: [BTUI] HealthService is supported
08-05 13:16:16.893  7858  7858 D ProfileConfigQcom: Adding HealthService
08-05 13:16:16.893  7858  7858 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-05 13:16:16.894  7858  7858 D ProfileConfigQcom: [BTUI] PanService is supported
08-05 13:16:16.894  7858  7858 D ProfileConfigQcom: Adding PanService
08-05 13:16:16.895  7858  7858 D ProfileConfigQcom: [BTUI] GattService is supported
08-05 13:16:16.895  7858  7858 D ProfileConfigQcom: Adding GattService
08-05 13:16:16.895  7858  7858 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-05 13:16:16.895  7858  7858 D ProfileConfigQcom: Adding BluetoothMapService
08-05 13:16:16.896  7858  7858 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
,08-05 13:16:16.897  7858  7858 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 13:16:16.898  7858  7858 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:16.898  7858  7858 V BluetoothPbapReceiver: ***********state = 10
08-05 13:16:16.900  7858  7858 V LGMDMManagerInternal: Create singleton instance
08-05 13:16:17.000  2154  2154 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 13:16:17.002  7858  7858 D LGBluetoothAPIServer: [BTUI] onCreate()
08-05 13:16:17.003  7858  7858 D LGBluetoothAPIServer: [BTUI] onBind()
,08-05 13:16:17.009  1946  1946 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-05 13:16:17.009  1946  2129 D LGBluetoothAPIService: Message: 100
08-05 13:16:17.009  1946  2129 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-05 13:16:17.024  7004  7004 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-05 13:16:17.029  7004  7004 D BluetoothPermissionRequest: onReceive
08-05 13:16:17.031  7004  7004 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-05 13:16:17.031  7004  7004 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-05 13:16:17.034  7004  7004 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 13:16:17.039  7858  7858 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-05 13:16:17.045  7858  7858 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-05 13:16:17.048  7858  7858 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 13:16:17.048  7858  7858 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 13:16:17.049  7858  7858 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 13:16:17.050  7858  7858 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:17.050  7858  7858 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-05 13:16:17.053  7060  7060 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-05 13:16:18.401  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
,08-05 13:16:18.401  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 13:16:18.506  1604  1604 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-05 13:16:18.535  1036  1390 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-05 13:16:18.600  1036  1093 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7887 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-05 13:16:18.605  2037  2037 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-05 13:16:18.629  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-05 13:16:18.630  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-05 13:16:18.646  1036  1036 D administrator: Handling package changes for user 0
,08-05 13:16:18.659  2037  2037 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 13:16:18.673  7887  7887 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-05 13:16:18.735  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-05 13:16:18.735  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-05 13:16:18.738  7887  7887 D LgDataFeature: LgDataFeature() Constructor: none
08-05 13:16:18.738  7887  7887 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 13:16:18.779  1036  1092 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 13:16:18.783  1036  1092 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-05 13:16:18.788  2037  2037 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-05 13:16:18.789  2508  2508 V GmsNetworkLocationProvi: DISABLE
08-05 13:16:18.808  1036  1092 D LocationProviderProxy: applying state to connected service
,08-05 13:16:18.811  2508  2508 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-05 13:16:18.838  7887  7932 I Babel   : MmsConfig: mnc/mcc: 0/0
08-05 13:16:18.838  7887  7932 I Babel   : MmsConfig.loadMmsSettings
,08-05 13:16:18.841  7887  7932 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-05 13:16:18.841  7887  7932 I Babel   : MmsConfig.loadFromDatabase
,08-05 13:16:18.864  7887  7932 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-05 13:16:18.864  7887  7932 I Babel   : MmsConfig.loadFromResources
08-05 13:16:18.866  7887  7932 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-05 13:16:18.867  7887  7932 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-05 13:16:18.880  7887  7887 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 13:16:18.892  7887  7930 W AudioCapabilities: Unsupported mime audio/evrc
08-05 13:16:18.895  7887  7930 W AudioCapabilities: Unsupported mime audio/qcelp
08-05 13:16:18.898  7887  7930 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-05 13:16:18.900  1819  7933 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-05 13:16:18.900  1819  7933 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-05 13:16:18.903  7217  7217 I AppUp4:CustModeStarterReceiver: onReceive
,08-05 13:16:18.908  7217  7217 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@b619a89
08-05 13:16:18.908  7217  7217 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 13:16:18.908  7217  7217 D AppUp4:CustFacade: isPhone : true
08-05 13:16:18.908  7217  7217 D AppUp4:CustModeStarterReceiver: begin check event
,08-05 13:16:18.908  7217  7217 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-05 13:16:18.910  1819  5143 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-05 13:16:18.918  7887  7930 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-05 13:16:18.927  7887  7930 W AudioCapabilities: Unsupported mime audio/qcelp
,08-05 13:16:18.932  7887  7930 W AudioCapabilities: Unsupported mime audio/evrc
08-05 13:16:18.944  7887  7930 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-05 13:16:18.946  7887  7930 W VideoCapabilities: Unsupported mime video/divx
08-05 13:16:18.947  7887  7930 W VideoCapabilities: Unsupported mime video/divx311
08-05 13:16:18.949  7887  7930 W VideoCapabilities: Unsupported mime video/divx4
08-05 13:16:18.953  1036  1999 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7937 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-05 13:16:18.954  7887  7930 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-05 13:16:18.957  1036  1999 I ActivityManager: Killing 7025:com.lge.sync/1000 (adj 15): empty #17
,08-05 13:16:18.971  1036  1545 D WifiService: Client connection lost with reason: 4
,08-05 13:16:18.983  7887  7930 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-05 13:16:18.986  7887  7930 W AudioCapabilities: Unsupported mime audio/eac3
,08-05 13:16:18.986  7887  7930 W AudioCapabilities: Unsupported mime audio/ac3
08-05 13:16:18.987  7887  7930 W AudioCapabilities: Unsupported mime audio/g726
08-05 13:16:18.988  7887  7930 W AudioCapabilities: Unsupported mime audio/wma-voice
08-05 13:16:18.989  7887  7930 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-05 13:16:18.989  7887  7930 W AudioCapabilities: Unsupported mime audio/adpcm
08-05 13:16:18.991  7887  7930 W VideoCapabilities: Unsupported mime video/theora
08-05 13:16:18.993  7887  7930 W VideoCapabilities: Unsupported mime video/mjpg
,08-05 13:16:19.035  1036  1981 W libprocessgroup: failed to open /acct/uid_1000/pid_7025/cgroup.procs: No such file or directory
08-05 13:16:19.067  7937  7937 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 13:16:19.067  7937  7937 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-05 13:16:19.067  7937  7937 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-05 13:16:19.069  7937  7937 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-05 13:16:19.069  7937  7937 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 13:16:19.145  7937  7937 I SystemConfig: BUILD Country: EU
08-05 13:16:19.145  7937  7937 I SystemConfig: BUILD Operator: OPEN
,08-05 13:16:19.192  1036  1981 I ActivityManager: Killing 7251:com.lge.email/u0a23 (adj 15): empty #17
,08-05 13:16:19.329  1036  1963 W libprocessgroup: failed to open /acct/uid_10023/pid_7251/cgroup.procs: No such file or directory
,08-05 13:16:19.338  7937  7956 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-05 13:16:19.338  7937  7956 I SystemConfig: existFile = false
08-05 13:16:19.338  7937  7956 I SystemConfig: canReadFile = false
08-05 13:16:19.339  7937  7956 I SystemConfig: systemFeature RCS result false
08-05 13:16:19.339  7937  7956 D SystemConfig: refreshRcsSupport() :false
08-05 13:16:19.415  1036  1981 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7958 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-05 13:16:19.493  7958  7958 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 13:16:19.494  7958  7958 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-05 13:16:19.494  7958  7958 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-05 13:16:19.495  7958  7958 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-05 13:16:19.601  7958  7958 I AppConfig: Total System Memory = 2995761152
,08-05 13:16:19.614  7958  7958 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-05 13:16:19.691  1036  1051 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7983 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 13:16:19.694  1036  1051 I ActivityManager: Killing 7114:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-05 13:16:19.762  1036  2036 W libprocessgroup: failed to open /acct/uid_10026/pid_7114/cgroup.procs: No such file or directory
,08-05 13:16:19.973  7983  7983 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-05 13:16:20.048  7983  7983 D LgDataFeature: LgDataFeature() Constructor: none
08-05 13:16:20.049  7983  7983 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 13:16:20.124  7983  7983 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-05 13:16:20.158  7983  7983 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-05 13:16:20.160  7983  7983 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-05 13:16:20.189  7983  7983 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-05 13:16:20.190  7983  7983 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-05 13:16:20.222  3486  4073 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-05 13:16:20.224  3486  4073 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@31ca7952 on behalf of 7983
08-05 13:16:20.225  1036  1890 I ActivityManager: Killing 6377:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-05 13:16:20.290  1036  1944 W libprocessgroup: failed to open /acct/uid_1000/pid_6377/cgroup.procs: No such file or directory
,08-05 13:16:20.440  1036  1908 I art     : Explicit concurrent mark sweep GC freed 43689(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.552ms total 143.642ms
08-05 13:16:20.443  4947  8037 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-05 13:16:20.483  1036  1926 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8038 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-05 13:16:20.538  7983  7983 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-05 13:16:20.557  8038  8038 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-05 13:16:20.562  7983  7983 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-05 13:16:20.574  8038  8038 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-05 13:16:20.574  8038  8038 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-05 13:16:20.574  8038  8038 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-05 13:16:20.574  8038  8038 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-05 13:16:20.574  8038  8038 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-05 13:16:20.574  8038  8038 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-05 13:16:20.591  1036  1052 I ActivityManager: Killing 7288:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-05 13:16:20.614  1036  1963 W libprocessgroup: failed to open /acct/uid_10046/pid_7288/cgroup.procs: No such file or directory
,08-05 13:16:20.774  7773  7832 D UEI.SmartControl: Internal timer expired: 1
08-05 13:16:20.775  7773  7832 D UEI.SmartControl: unbind internal service
,08-05 13:16:20.782  7773  7773 D UEI.SmartControl: Service.onUnbind: IControl
08-05 13:16:20.782  7773  7773 D UEI.SmartControl: Service.onDestroy
08-05 13:16:20.783  7773  7773 D UEI.SmartControl: Lock is in USE false
08-05 13:16:20.783  7773  7773 D UEI.SmartControl: unbind internal service
08-05 13:16:20.784  7773  7773 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@c05645
08-05 13:16:20.786  7773  7773 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-05 13:16:20.786  7773  7773 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-05 13:16:20.786  7773  7773 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-05 13:16:20.786  7773  7773 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-05 13:16:20.786  7773  7773 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-05 13:16:20.786  7773  7773 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-05 13:16:20.786  7773  7773 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-05 13:16:20.787  7773  7773 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-05 13:16:20.787  7773  7773 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 13:16:20.787  7773  7773 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 13:16:20.787  7773  7773 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 13:16:20.787  7773  7773 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 13:16:20.787  7773  7773 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 13:16:20.787  7773  7773 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 13:16:20.787  7773  7773 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 13:16:20.787  7773  7773 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@c05645
08-05 13:16:20.789  7773  7773 D serial_port: close(fd = 25)
08-05 13:16:20.792  7773  7773 I UEI.SmartControl: Serial port is closed.
08-05 13:16:20.793  7773  7773 I UEI.SmartControl: Serial port is closed.
08-05 13:16:20.793  7773  7773 D UEI.SmartControl: Blaster closed
08-05 13:16:20.794  7773  7773 D UEI.SmartControl: Shut down QS...
08-05 13:16:20.794  7773  7773 D UEI.SmartControl: Stopping QS lib
08-05 13:16:20.794  7773  7773 D UEI.SmartControl: QS lib stop result = true
08-05 13:16:20.794  7773  7773 D UEI.SmartControl: Stopped QS lib
08-05 13:16:20.794  7773  7773 D UEI.SmartControl: Stopped file observer...
08-05 13:16:20.794  7773  7773 D UEI.SmartControl: QS shutdown complete
,08-05 13:16:20.810  1036  1981 V SIM_STK : Menu title from STK is T-Mobile
,08-05 13:16:20.832  4947  8037 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 390 ms] updated apps [took 390 ms] 
,08-05 13:16:21.416  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-05 13:16:21.416  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3eee5ae3 added. We now have 6 listener(s)
08-05 13:16:21.416  6900  6964 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 13:16:21.427  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 13:16:21.427  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@19c00ce0 added. We now have 7 listener(s)
08-05 13:16:21.427  6900  6964 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 13:16:21.428  6900  6964 I System.out: IsBluetoothEnabled
08-05 13:16:21.429  1036  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:21.429  1036  1908 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-05 13:16:21.430  1036  1109 D BluetoothManagerService: Message: 2
08-05 13:16:21.433  6900  6964 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:21.435  1036  1707 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:21.435  1036  1707 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-05 13:16:21.453  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 13:16:21.454  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 13:16:21.454  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-05 13:16:21.455  1036  1109 D BluetoothManagerService: Message: 1
08-05 13:16:21.455  1036  1109 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-05 13:16:21.479  1036  1109 D BluetoothManagerService: Message: 20
08-05 13:16:21.480  1036  1109 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c154c0d:true
,08-05 13:16:21.484  7858  7858 D BluetoothAdapterState: make
08-05 13:16:21.489  7858  7858 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-05 13:16:21.489  7858  7858 I bluedroid-qcom: init
08-05 13:16:21.490  7858  8083 I BluetoothAdapterState: Entering OffState
08-05 13:16:21.490  7858  7858 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-05 13:16:21.491  7858  7858 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-05 13:16:21.491  7858  7858 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-05 13:16:21.491  7858  7858 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-05 13:16:21.491  7858  7858 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-05 13:16:21.493  7858  7858 I bluedroid-qcom: get_profile_interface socket
08-05 13:16:21.493  7858  7858 I bluedroid-qcom: get_profile_interface map_client
,08-05 13:16:21.497  7858  8087 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-05 13:16:21.500  7858  8087 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-05 13:16:21.491  8086  8086 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 13:16:21.491  8086  8086 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 13:16:21.510  8086  8086 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-05 13:16:21.510  8086  8086 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-05 13:16:21.510  8086  8086 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-05 13:16:21.515  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-05 13:16:21.515  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-05 13:16:21.517  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-05 13:16:21.518  1036  1109 D BluetoothManagerService: Message: 40
08-05 13:16:21.518  1036  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-05 13:16:21.519  7858  7873 I bluedroid-qcom: config_hci_snoop_log
08-05 13:16:21.520  1036  1109 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-05 13:16:21.520  1036  1109 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-05 13:16:21.521  8086  8086 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-05 13:16:21.527  8086  8086 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-05 13:16:21.527  8086  8086 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-05 13:16:21.534  7858  8083 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-05 13:16:21.534  7858  8087 D BluetoothAdapterProperties: Name is: G3
08-05 13:16:21.534  7858  8083 D BluetoothAdapterProperties: Setting state to 11
08-05 13:16:21.535  7858  8083 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-05 13:16:21.535  1036  1109 D BluetoothManagerService: Message: 60
08-05 13:16:21.535  1036  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-05 13:16:21.535  1036  1109 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-05 13:16:21.537  7858  8083 I LGBluetoothServiceJni: classInitNative: succeeds
08-05 13:16:21.543  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-05 13:16:21.543  1946  1946 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:21.549  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:21.552  7004  7004 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-05 13:16:21.558  7858  7858 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 13:16:21.559  7858  7858 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:21.559  7858  7858 V BluetoothPbapReceiver: ***********state = 11
,08-05 13:16:21.573  7858  8083 D BluetoothBondStateMachine: make
,08-05 13:16:21.579  7858  8100 I BluetoothBondStateMachine: StableState(): Entering Off State
08-05 13:16:21.579  2154  2154 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 13:16:21.579  7858  8083 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@156806bc
08-05 13:16:21.579  7858  8083 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-05 13:16:21.580  7858  8083 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@156806bc
08-05 13:16:21.580  7858  8083 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-05 13:16:21.581  7858  8083 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-05 13:16:21.587  7858  8083 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 13:16:21.600  7858  7858 D HeadsetService: Received start request. Starting profile...
,08-05 13:16:21.600  7004  7004 D BluetoothPermissionRequest: onReceive
08-05 13:16:21.600  7858  7858 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 13:16:21.601  7858  7858 D LGBluetoothHfpAdapter: Version 1.6
08-05 13:16:21.601  7858  8083 E BluetoothAdapterService: File transfer profiles supported!!
08-05 13:16:21.605  7858  7858 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 13:16:21.606  7858  7858 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 13:16:21.606  7858  7858 D HeadsetStateMachine: make
08-05 13:16:21.607  7858  8083 E BluetoothAdapterService: File transfer profiles supported!!
08-05 13:16:21.610  7004  7004 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 13:16:21.615  7858  8083 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 13:16:21.621  7858  8083 E BluetoothAdapterService: File transfer profiles supported!!
08-05 13:16:21.627  7858  8083 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 13:16:21.632  7858  8083 E BluetoothAdapterService: File transfer profiles supported!!
08-05 13:16:21.641  7858  7858 D LgDataFeature: LgDataFeature() Constructor: none
,08-05 13:16:21.641  7858  7858 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 13:16:21.645  7858  7858 D HeadsetStateMachine: max_hf_connections = 1
08-05 13:16:21.645  7858  7858 I bluedroid-qcom: get_profile_interface handsfree
08-05 13:16:21.647  7858  7858 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-05 13:16:21.647   332   332 V AudioPolicyService: registerClient() client 0xb04105c0, uid 1002
08-05 13:16:21.647   332  2181 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-05 13:16:21.647   332  2181 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 13:16:21.647   332  2181 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 13:16:21.647  7858  7858 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-05 13:16:21.648   332  1387 V AudioFlinger: registerClient() client 0xb5581628, pid 7858
08-05 13:16:21.648   332  1382 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 13:16:21.648   332  1382 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 13:16:21.648  1036  1576 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 13:16:21.648  1036  1576 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 13:16:21.648  1604  1622 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 13:16:21.648  1604  1622 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 13:16:21.648  3386  3402 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 13:16:21.648  3386  3402 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 13:16:21.648  7858  7874 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 13:16:21.648  1855  2445 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 13:16:21.648  1855  2445 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 13:16:21.649   332  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 13:16:21.649   332  1381 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 13:16:21.649  7858  7874 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-05 13:16:21.649  1036  1981 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 13:16:21.649  1036  1981 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 13:16:21.649  3386  3403 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 13:16:21.649  3386  3403 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 13:16:21.649  7858  7858 V ToneGenerator: Create Track: 0xb4928a80
08-05 13:16:21.649  7858  7858 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-05 13:16:21.649  1604  1754 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 13:16:21.649  1604  1754 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 13:16:21.649  7858  7858 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-05 13:16:21.649   332   332 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 13:16:21.649   332   332 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-05 13:16:21.649   332   332 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 13:16:21.649   332   332 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 13:16:21.649  1855  1871 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 13:16:21.649  7858  7874 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 13:16:21.649  1855  1871 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 13:16:21.649  7858  7874 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-05 13:16:21.650   332  2181 I AudioFlinger: isAudioPlaybackHookOn() false
08-05 ,13:16:21.650   332  1386 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 13:16:21.650   332  1386 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-05 13:16:21.650   332  1386 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 13:16:21.650   332  1386 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 13:16:21.650  7858  7858 V AudioSystem: getLatency() output 2, latency 50
08-05 13:16:21.650  7858  7858 V AudioSystem: getFrameCount() output 2, frameCount 960
08-05 13:16:21.650  7858  7858 V AudioTrack: createTrack_l() output 2 afLatency 50
08-05 13:16:21.650   332   332 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 13:16:21.650   332   332 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 13:16:21.650   332   332 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 13:16:21.650   332   332 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 13:16:21.650   332   332 V AudioFlinger: createTrack() lSessionId: 23
08-05 13:16:21.651  7858  7858 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-05 13:16:21.651   332  1387 V AudioFlinger: acquiring 23 from 7858, for 7858
08-05 13:16:21.651   332  1387 V AudioFlinger:  added new entry for 23
08-05 13:16:21.651  7858  7858 V ToneGenerator: ToneGenerator INIT OK, time: 352018
08-05 13:16:21.652  7858  7858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@156806bc
08-05 13:16:21.653  7858  7858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@156806bc
08-05 13:16:21.654  7858  8106 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-05 13:16:21.655  7858  7858 D A2dpService: Received start request. Starting profile...
08-05 13:16:21.656  7858  8106 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 13:16:21.656  7858  8106 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 13:16:21.656  7858  8106 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-05 13:16:21.656  7858  7858 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-05 13:16:21.657   332  2181 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7858
08-05 13:16:21.657   332  2181 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-05 13:16:21.657   332  2181 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-05 13:16:21.657   332  2181 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-05 13:16:21.657   332  2181 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-05 13:16:21.657   332  2181 V voice   : voice_set_parameters: exit with code(0)
08-05 13:16:21.657   332  2181 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-05 13:16:21.657   332  2181 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-05 13:16:21.657   332  2181 V msm8974_platform: platform_set_parameters: exit with code(0)
08-05 13:16:21.657   332  2181 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-05 13:16:21.657   332  2181 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-05 13:16:21.657   332  2181 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-05 13:16:21.658  7858  7858 V Avrcp   : make
08-05 13:16:21.658  7858  8106 V ToneGenerator: ToneGenerator destructor
08-05 13:16:21.658  7858  8106 V ToneGenerator: stopTone
08-05 13:16:21.658  7858  8106 V ToneGenerator: Delete Track: 0xb4928a80
08-05 13:16:21.658  7858  7858 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-05 13:16:21.658  7858  7858 I bluedroid-qcom: get_profile_interface avrcp
08-05 13:16:21.659  7858  8106 V, AudioTrack: ~AudioTrack, releasing session id from 7858 on behalf of 7858
08-05 13:16:21.659   332  1387 V AudioPolicyService: AudioCommandThread() adding release output 2
08-05 13:16:21.659   332  1387 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-05 13:16:21.659   332  1120 V AudioPolicyService: AudioCommandThread() waking up
08-05 13:16:21.659   332  1120 V AudioPolicyService: AudioCommandThread() processing release output 2
08-05 13:16:21.659   332  1120 V AudioPolicyManager: releaseOutput() 2
08-05 13:16:21.659   332  1120 V AudioPolicyService: AudioCommandThread() going to sleep
08-05 13:16:21.659   332  1387 V AudioFlinger: PlaybackThread::Track destructor
08-05 13:16:21.659   332  1387 V AudioFlinger: removeClient_l() pid 7858, calling pid 332
08-05 13:16:21.659   332  1387 V AudioFlinger: releasing 23 from 7858 for 7858
08-05 13:16:21.659   332  1387 V AudioFlinger:  decremented refcount to 0
08-05 13:16:21.659   332  1387 V AudioFlinger: purging stale effects
08-05 13:16:21.659  1036  1051 W Process : Unable to open /proc/8107/status
08-05 13:16:21.660  7858  8083 V LGMDMManager: Create singleton instance
08-05 13:16:21.664  7858  8083 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-05 13:16:21.670  7858  7858 V AudioManager: registerRemoteController: size of Media player list: 0
08-05 13:16:21.671  7858  7858 E AudioManager: No RCC entry present to update
08-05 13:16:21.671  7858  7858 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-05 13:16:21.675  7858  7858 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,08-05 13:16:21.676  7858  7858 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-05 13:16:21.676  7858  7858 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-05 13:16:21.680  7858  7858 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-05 13:16:21.827  1036  1907 V SIM_STK : Menu title from STK is T-Mobile
08-05 13:16:21.827  1036  1907 V SIM_STK : Menu title from STK is T-Mobile
,08-05 13:16:21.950  1036  2036 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-05 13:16:21.961  7858  7858 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-05 13:16:21.966  7858  7858 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-05 13:16:21.967  7858  7858 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-05 13:16:21.967  7858  7858 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-05 13:16:21.967  7858  7858 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-05 13:16:21.967  7858  7858 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 13:16:21.967  7858  7858 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-05 13:16:21.967  7858  7858 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-05 13:16:21.967  7858  7858 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-05 13:16:21.967  7858  7858 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 13:16:21.967  7858  7858 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-05 13:16:21.968  7858  7858 I BluetoothA2dpServiceJni: classInitNative
08-05 13:16:21.968  7858  7858 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-05 13:16:21.968  7858  7858 D A2dpStateMachine: make
,08-05 13:16:21.976  7858  7858 I bluedroid-qcom: get_profile_interface a2dp
08-05 13:16:21.976  7858  8115 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-05 13:16:21.979  7858  7858 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-05 13:16:21.979  7858  7858 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-05 13:16:21.980  7858  7858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@156806bc
08-05 13:16:21.981  7858  7858 I BluetoothHidServiceJni: classInitNative: succeeds
08-05 13:16:21.981  7858  8114 D A2dpStateMachine: Enter Disconnected: -2
08-05 13:16:21.982  7858  7858 D HidService: Received start request. Starting profile...
08-05 13:16:21.982  7858  7858 I bluedroid-qcom: get_profile_interface hidhost
08-05 13:16:21.983  7858  7858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@156806bc
08-05 13:16:21.983  7858  7858 I BluetoothHealthServiceJni: classInitNative: succeeds
08-05 13:16:21.985  7858  7858 D HealthService: Received start request. Starting profile...
08-05 13:16:21.989  7858  7858 I bluedroid-qcom: get_profile_interface health
08-05 13:16:21.989  7858  7858 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-05 13:16:21.990  7858  7858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@156806bc
08-05 13:16:21.990  7858  7858 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-05 13:16:21.993  7858  7858 D PanService: Received start request. Starting profile...
,08-05 13:16:21.994  7858  7858 D BluetoothPanServiceJni: initializeNative(L110): pan
08-05 13:16:21.995  7858  7858 I bluedroid-qcom: get_profile_interface pan
08-05 13:16:22.012  7858  7858 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-05 13:16:22.012  7858  7858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@156806bc
,08-05 13:16:22.016  7858  7858 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-05 13:16:22.032  7858  7858 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-05 13:16:22.034  7858  7858 D BtGatt.GattService: Received start request. Starting profile...
08-05 13:16:22.034  7858  7858 D BtGatt.GattService: start()
08-05 13:16:22.035  7858  7858 I bluedroid-qcom: get_profile_interface gatt
08-05 13:16:22.036  7858  7858 D BtGatt.AdvertiseManager: advertise manager created
08-05 13:16:22.046  7858  7858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@156806bc
08-05 13:16:22.049  7858  7858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@156806bc
08-05 13:16:22.049  7858  7858 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-05 13:16:22.050  7858  7858 V BluetoothMapService: BluetoothMapBinder()
08-05 13:16:22.051  7858  7858 D BluetoothMapService: Received start request. Starting profile...
08-05 13:16:22.051  7858  7858 D BluetoothMapService: start()
,08-05 13:16:22.059  7858  7858 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-05 13:16:22.059  7858  7858 D BluetoothMapEmailAppObserver: createReceiver()
08-05 13:16:22.061  7858  7858 D BluetoothMapEmailAppObserver: initObservers()
08-05 13:16:22.062  7858  7858 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-05 13:16:22.085  7858  7858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@156806bc
,08-05 13:16:22.085  7858  7858 D HeadsetStateMachine: Proxy object connected
08-05 13:16:22.086  7858  7858 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-05 13:16:22.086  7858  7858 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-05 13:16:22.089  7858  8106 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-05 13:16:22.091  7858  8106 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-05 13:16:22.091  7858  8106 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-05 13:16:22.093  7858  7858 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 13:16:22.097  7858  7858 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-05 13:16:22.104  7858  7858 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 13:16:22.106  7858  7858 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:22.112  7858  7858 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-05 13:16:22.113  7858  7858 V PanService: [BTUI] SIM Extra State :ABSENT
08-05 13:16:22.117  7858  7858 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 13:16:22.122  7858  7858 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-05 13:16:22.122  7858  7858 V BluetoothMapService: Handler(): got msg=1
08-05 13:16:22.124  7858  8083 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-05 13:16:22.124  7858  8083 I bluedroid-qcom: enable
08-05 13:16:22.124  7858  7858 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 13:16:22.125  7858  7858 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 13:16:22.125  7858  7858 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 13:16:22.125  7858  8083 I bt_hci_bdroid: init
08-05 13:16:22.125  7858  7858 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:22.125  7858  7858 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-05 13:16:22.126  7858  8083 I bt_vendor: bt-vendor : init
08-05 13:16:22.126  7858  8083 I bt_vendor: bt-vendor : get_bt_soc_type
08-05 13:16:22.127  7858  8083 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-05 13:16:22.127  7858  8083 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-05 13:16:22.127  7858  8083 D bt_userial_mct: userial_init
08-05 13:16:22.127  7858  8122 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-05 13:16:22.127  7858  8122 I bt-btu  : btu_task pending for preload complete event
,08-05 13:16:22.129  7858  8083 D bt_hci_bdroid: set_power 1
08-05 13:16:22.129  7858  8083 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-05 13:16:22.129  7858  8083 I bt_vendor: Starting hciattach daemon
08-05 13:16:22.129  7858  8083 I bt_vendor: try to set true
08-05 13:16:22.121  8125  8125 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 13:16:22.131  8125  8125 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 13:16:22.171  8126  8126 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-05 13:16:22.306  8132  8132 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-05 13:16:22.320  8133  8133 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-05 13:16:22.362  8135  8135 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 13:16:22.377  8136  8136 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-05 13:16:22.390  8137  8137 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 13:16:22.402  8138  8138 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-05 13:16:22.426  8140  8140 I libmdmdetect: ESOC framework not supported
,08-05 13:16:22.429  8140  8140 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-05 13:16:22.446  8140  8140 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-05 13:16:22.446  8140  8140 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-05 13:16:22.446  8140  8140 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-05 13:16:22.446  8140  8140 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-05 13:16:22.447  8140  8140 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-05 13:16:22.447  8140  8140 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-05 13:16:22.447  8140  8140 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-05 13:16:22.503  8140  8144 E QC-QMI  : qmi_client [8140] 15: failed to locate client data,
,08-05 13:16:22.508   485   485 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-05 13:16:22.508   485   485 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-05 13:16:22.526  8148  8148 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-05 13:16:22.541  8149  8149 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-05 13:16:22.584  7858  8083 I bt_vendor: bluetooth satus is on
08-05 13:16:22.584  7858  8083 D bt_hci_bdroid: preload
08-05 13:16:22.584  7858  8124 D bt_userial_mct: userial_open(port:0)
08-05 13:16:22.584  7858  8124 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-05 13:16:22.587  7858  8124 I bt_vendor: Done intiailizing UART
08-05 13:16:22.588  7858  8124 I bt_vendor: Done intiailizing UART
08-05 13:16:22.588  7858  8124 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-05 13:16:22.588  7858  8124 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-05 13:16:22.589  7858  8122 I bt-btu  : btu_task received preload complete event
08-05 13:16:22.589  7858  8122 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-05 13:16:22.589  7858  8122 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-05 13:16:22.591  7858  8122 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-05 13:16:22.593  7858  8151 D bt_userial_mct: Entering userial_read_thread()
08-05 13:16:22.595  7858  8122 I         : BTE_InitTraceLevels -- TRC_HCI
08-05 13:16:22.595  7858  8122 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-05 13:16:22.595  7858  8122 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-05 13:16:22.595  7858  8122 I         : BTE_InitTraceLevels -- TRC_AVDT
08-05 13:16:22.595  7858  8122 I         : BTE_InitTraceLevels -- TRC_AVRC
08-05 13:16:22.595  7858  8122 I         : BTE_InitTraceLevels -- TRC_A2D
08-05 13:16:22.595  7858  8122 I         : BTE_InitTraceLevels -- TRC_BNEP
08-05 13:16:22.595  7858  8122 I         : BTE_InitTraceLevels -- TRC_BTM
08-05 13:16:22.595  7858  8122 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-05 13:16:22.595  7858  8122 I         : BTE_InitTraceLevels -- TRC_GAP
08-05 13:16:22.595  7858  8122 I         : BTE_InitTraceLevels -- TRC_PAN
08-05 13:16:22.595  7858  8122 I         : BTE_InitTraceLevels -- TRC_SDP
08-05 13:16:22.595  7858  8122 I         : BTE_InitTraceLevels -- TRC_GATT
08-05 13:16:22.595  7858  8122 I         : BTE_InitTraceLevels -- TRC_SMP
08-05 13:16:22.595  7858  8122 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-05 13:16:22.595  7858  8122 I         : BTE_InitTraceLevels -- TRC_BTIF
08-05 13:16:22.656  7858  8122 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-05 13:16:22.656  7858  8122 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa022d061 
08-05 13:16:22.656  7858  8122 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa022d061 
,08-05 13:16:22.683  7858  8087 E bt-btif : Calling BTA_HhEnable
08-05 13:16:22.683  7858  8087 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-05 13:16:22.684  7858  8087 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-05 13:16:22.688  7858  8122 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-05 13:16:22.688  7858  8122 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-05 13:16:22.688  7858  8122 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-05 13:16:22.689  7858  8122 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-05 13:16:22.689  7858  8122 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-05 13:16:22.690  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-05 13:16:22.690  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-05 13:16:22.691  7858  8087 D BluetoothAdapterProperties: Name is: G3
08-05 13:16:22.693  7858  8087 D BluetoothAdapterProperties: Scan Mode:20
08-05 13:16:22.693  7858  8087 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 13:16:22.693  7858  8087 D bt_hci_bdroid: postload
08-05 13:16:22.694  7858  8124 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 13:16:22.695  7858  8122 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-05 13:16:22.695  7858  8087 D bte_conf: Device ID record 1 : primary
08-05 13:16:22.695  7858  8087 D bte_conf:   vendorId            = 00c4
08-05 13:16:22.695  7858  8087 D bte_conf:   vendorIdSource      = 0001
08-05 13:16:22.695  7858  8087 D bte_conf:   product             = 13a1
08-05 13:16:22.695  7858  8087 D bte_conf:   version             = 1000
08-05 13:16:22.695  7858  8087 D bte_conf:   clientExecutableURL = 
08-05 13:16:22.695  7858  8087 D bte_conf:   serviceDescription  = 
08-05 13:16:22.695  7858  8087 D bte_conf:   documentationURL    = 
08-05 13:16:22.696  7858  8087 D bte_conf: bte_load_did_conf no section named DID2.
08-05 13:16:22.697  7858  8124 D bt_hci_bdroid: Used up Tx Cmd credits
,08-05 13:16:22.704  7858  8124 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 13:16:22.707  7858  8124 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 13:16:22.708  7858  8083 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-05 13:16:22.708  7858  8083 D BluetoothAdapterProperties: ScanMode =  20
08-05 13:16:22.708  7858  8083 D BluetoothAdapterProperties: State =  11
08-05 13:16:22.708  7858  8083 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-05 13:16:22.709  7858  8083 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-05 13:16:22.709  7858  8083 D BluetoothAdapterProperties: Setting state to 12
08-05 13:16:22.709  7858  8083 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-05 13:16:22.709  7858  8087 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-05 13:16:22.710  7858  8087 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-05 13:16:22.711  8153  8153 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 13:16:22.711  8153  8153 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 13:16:22.724  1036  1109 D BluetoothManagerService: Message: 60
08-05 13:16:22.724  1036  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-05 13:16:22.724  1036  1109 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-05 13:16:22.726  7858  8151 E bt_mct  : hci lib postload completed
08-05 13:16:22.734  7858  8122 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 13:16:22.734  7858  8122 W bt-smp  : Plain text(LSB ~ MSB) = 13 60 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 13:16:22.734  7858  8122 W bt-smp  : Encrypted text(LSB ~ MSB) = 97 bd 79 08 42 fb 41 49 85 9e b1 f9 96 dd ad 78 
,08-05 13:16:22.737  7858  8122 W bt-btm  : Stopping oneshot timer
08-05 13:16:22.748  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 13:16:22.748  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:22.748  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:22.748  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 13:16:22.748  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 13:16:22.748  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 13:16:22.748  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 13:16:22.748  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 13:16:22.755  7858  8083 I BluetoothAdapterState: Entering On State
08-05 13:16:22.761  7858  8087 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 13:16:22.761  7858  8087 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-05 13:16:22.764  7858  8122 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 13:16:22.764  7858  8122 W bt-smp  : Plain text(LSB ~ MSB) = 8f 18 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 13:16:22.765  7858  8122 W bt-smp  : Encrypted text(LSB ~ MSB) = 65 2b d3 cd 8b f2 82 a6 c3 18 81 9d bd 39 64 a9 
08-05 13:16:22.765  7858  8122 W bt-btm  : Stopping oneshot timer
08-05 13:16:22.767  6900  6900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 13:16:22.776  7858  8083 D LGBluetoothServiceAdapter: [BTUI] OnState
08-05 13:16:22.776  7858  8083 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-05 13:16:22.776  7858  8083 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-05 13:16:22.782  7858  8083 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-05 13:16:22.785  7004  7019 D BluetoothPbap: onBluetoothStateChange: up=true
08-05 13:16:22.788  7858  8122 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 13:16:22.788  7858  8122 W bt-smp  : Plain text(LSB ~ MSB) = e3 9a 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 13:16:22.788  7858  8122 W bt-smp  : Encrypted text(LSB ~ MSB) = 7e 1e bf 22 2c a6 22 3e db 00 71 75 95 6b 4f a0 
08-05 13:16:22.789  7858  8122 W bt-btm  : Stopping oneshot timer
,08-05 13:16:22.799  7004  7020 D BluetoothA2dp: onBluetoothStateChange: up=true
08-05 13:16:22.805  7858  8083 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-05 13:16:22.808  7858  8122 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 13:16:22.808  7858  8122 W bt-smp  : Plain text(LSB ~ MSB) = 6a 11 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 13:16:22.808  7858  8122 W bt-smp  : Encrypted text(LSB ~ MSB) = cf 88 cb 8d 74 ab c3 57 1b a3 bf 58 76 08 fe 7e 
08-05 13:16:22.808  7858  8122 W bt-btm  : Stopping oneshot timer
08-05 13:16:22.819  1855  2445 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-05 13:16:22.834  7858  8122 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 13:16:22.834  7858  8122 W bt-smp  : Plain text(LSB ~ MSB) = cf df 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 13:16:22.834  7858  8122 W bt-smp  : Encrypted text(LSB ~ MSB) = 5c 0b 37 12 39 56 8d 14 56 e0 a3 0d 2c 1a dc 88 
08-05 13:16:22.834  7858  8122 W bt-btm  : Stopping oneshot timer
,08-05 13:16:22.854  8158  8158 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-05 13:16:22.868  1855  1855 D BluetoothHeadset: Proxy object connected
,08-05 13:16:22.872  7004  7019 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-05 13:16:22.879  1855  1870 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 13:16:22.881  7004  7004 D BluetoothA2dp: Proxy object connected
08-05 13:16:22.882  7004  7004 D A2dpProfile: Bluetooth service connected
08-05 13:16:22.885  1855  1855 D BluetoothHeadset: Proxy object connected
08-05 13:16:22.885  7004  7020 D BluetoothPan: onBluetoothStateChange on: true
,08-05 13:16:22.885  7004  7020 D BluetoothPan: onBluetoothStateChange call bindService
08-05 13:16:22.888  7004  7004 D BluetoothInputDevice: Proxy object connected
08-05 13:16:22.888  7004  7004 D HidProfile: Bluetooth service connected
08-05 13:16:22.889  1855  2445 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 13:16:22.894  7004  7004 D BluetoothPan: BluetoothPAN Proxy object connected
08-05 13:16:22.894  7004  7004 D PanProfile: Bluetooth service connected
08-05 13:16:22.894  1855  1855 D BluetoothHeadset: Proxy object connected
08-05 13:16:22.895  7004  7275 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 13:16:22.897  7004  7019 D BluetoothMap: onBluetoothStateChange: up=true
08-05 13:16:22.900  7004  7004 D BluetoothHeadset: Proxy object connected
08-05 13:16:22.900  1036  1109 D BluetoothA2dp: onBluetoothStateChange: up=true
08-05 13:16:22.900  7004  7004 D HeadsetProfile: Bluetooth service connected
08-05 13:16:22.900  1036  1036 D BluetoothA2dp: Proxy object connected
08-05 13:16:22.901  1036  1109 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 13:16:22.902  1036  1036 D BluetoothHeadset: Proxy object connected
,08-05 13:16:22.903  1036  1109 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-05 13:16:22.903  1036  1109 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-05 13:16:22.904  1946  1946 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:22.905  1946  2129 D LGBluetoothAPIService: Message: 1
08-05 13:16:22.905  1946  2129 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-05 13:16:22.905  1946  2129 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-05 13:16:22.905  1946  2129 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-05 13:16:22.905  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 13:16:22.910  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:22.912  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-05 13:16:22.912  7004  7004 D BluetoothMap: Proxy object connected
08-05 13:16:22.912  7004  7004 D MapProfile: Bluetooth service connected
08-05 13:16:22.912  7004  7004 D BluetoothMap: getConnectedDevices()
08-05 13:16:22.913  7858  7858 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:22.913  7858  7858 D BluetoothMapService: STATE_ON
08-05 13:16:22.913  7858  7858 V BluetoothMapService: Handler(): got msg=1
08-05 13:16:22.913  1036  1109 D BluetoothManagerService: Message: 40
08-05 13:16:22.913  1036  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-05 13:16:22.914  7858  7858 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-05 13:16:22.915  7858  7874 V BluetoothMapService: getConnectedDevices()
08-05 13:16:22.919  7004  7004 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-05 13:16:22.919  7858  8178 D BluetoothMapMasInstance: MAS initSocket()
08-05 13:16:22.920  7858  8178 D BluetoothMapMasInstance:   masId = 00
08-05 13:16:22.920  7858  8178 D BluetoothMapMasInstance:   msgTypes = 0e
08-05 13:16:22.920  7858  8178 D BluetoothMapMasInstance:   masName = SMS/MMS
08-05 13:16:22.920  7858  8178 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-05 13:16:22.921  7004  7004 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-05 13:16:22.922  1036  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:22.924  7858  8178 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 13:16:22.925  7858  8178 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-05 13:16:22.926  7858  8178 V BluetoothMapMasInstance: Succeed to create listening socket 
08-05 13:16:22.926  7858  8178 D BluetoothMapMasInstance: Accepting socket connection...
08-05 13:16:22.927  7858  8087 D BluetoothAdapterProperties: Scan Mode:21
08-05 13:16:22.927  7858  8087 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-05 13:16:22.930  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:22.933  7858  7858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@156806bc
08-05 13:16:22.933  7858  7858 V BluetoothPbapService: Pbap Service onCreate
08-05 13:16:22.933  7004  7004 D DockEventReceiver: finishStartingService: stopping service
08-05 13:16:22.934  7858  7858 V BluetoothPbapService: Starting PBAP service
,08-05 13:16:22.935  7858  7858 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-05 13:16:22.935  7858  7858 V BluetoothPbapService: Pbap Service onBind
08-05 13:16:22.937  7004  7004 D BluetoothPbap: Proxy object connected
08-05 13:16:22.937  7004  7004 D PbapServerProfile: Bluetooth service connected
08-05 13:16:22.937  7858  7858 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-05 13:16:22.937  7858  7858 V BluetoothPbapService: state: 12
08-05 13:16:22.938  7858  7858 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 13:16:22.938  7858  7858 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:22.938  7858  7858 V BluetoothPbapReceiver: ***********state = 12
08-05 13:16:22.939  7858  7858 V BluetoothPbapService: Handler(): got msg=1
08-05 13:16:22.939  7858  7858 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-05 13:16:22.940  2154  2154 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 13:16:22.941  7858  8180 V BluetoothPbapService: Pbap Service initSocket
08-05 13:16:22.941  2154  2154 D c       : Getting all permits...
08-05 13:16:22.941  2154  2154 D a       : Opening database...
08-05 13:16:22.941  1036  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:22.942  7858  8180 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 13:16:22.943  7858  8180 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-05 13:16:22.943  7858  8180 V BluetoothPbapService: Succeed to create listening socket 
08-05 13:16:22.943  7858  8180 V BluetoothPbapService: Accepting socket connection...
08-05 13:16:22.944  2154  2154 D a       : Opening database auth.proximity.permit_store...
08-05 13:16:22.944  2154  2154 D a       : Closing database...
08-05 13:16:22.953  7004  7004 D BluetoothPermissionRequest: onReceive
08-05 13:16:22.955  7004  7004 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-05 13:16:22.957  7004  7004 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 13:16:22.959  7858  7858 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-05 13:16:22.961  7858  7858 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-05 13:16:22.966  7858  7858 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-05 13:16:22.989  7858  7858 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 13:16:22.989  7858  7858 V BtOppService: onCreate
,08-05 13:16:22.994  7858  7858 V BluetoothOppNotification: send message
08-05 13:16:22.996  7858  7858 V BtOppService: Starting RfcommListener
08-05 13:16:23.002  7858  7858 D BluetoothOppPreference: Dumping Names:  
08-05 13:16:23.002  7858  7858 D BluetoothOppPreference: {}
08-05 13:16:23.002  7858  7858 D BluetoothOppPreference: Dumping Channels:  
08-05 13:16:23.002  7858  7858 D BluetoothOppPreference: {}
08-05 13:16:23.003  7858  7858 V BtOppService: onStartCommand
08-05 13:16:23.005  7858  8186 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-05 13:16:23.009  7858  7858 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:23.009  7858  7858 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-05 13:16:23.012  7858  8186 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 13:16:23.015  7858  8183 V BtOppService: Deleted complete outbound shares, number =  0
08-05 13:16:23.016  7858  8186 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31b98038 on behalf of 
,08-05 13:16:23.018  7858  8183 V BtOppService: Deleted complete inbound failed shares, number = 0
08-05 13:16:23.018  7858  8183 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-05 13:16:23.019  7858  7858 V BluetoothOppNotification: new notify threadi!
08-05 13:16:23.020  7858  7858 V BluetoothOppNotification: send delay message
08-05 13:16:23.020  7858  8183 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@145cd811 on behalf of 
08-05 13:16:23.020  7858  7858 V BtOppService: start RfcommListener
08-05 13:16:23.021  7858  8186 V BluetoothOppNotification: update too frequent, put in queue
08-05 13:16:23.024  7858  7858 V BtOppService: RfcommListener started
08-05 13:16:23.027  7858  8186 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 13:16:23.028  7858  8187 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-05 13:16:23.028  7858  8188 V BtOppRfcommListener: Starting RFCOMM listener....
08-05 13:16:23.029  1036  1907 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:23.031  7858  8188 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 13:16:23.031  7858  8186 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 13:16:23.032  7858  8188 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-05 13:16:23.032  7858  8188 V BtOppRfcommListener: Started RFCOMM listener....
08-05 13:16:23.032  7858  8188 I BtOppRfcommListener: Accept thread started.
08-05 13:16:23.033  7858  8188 V BtOppRfcommListener: Accepting connection...
08-05 13:16:23.035  7858  8187 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23835d76 on behalf of 
08-05 13:16:23.035  7858  8186 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24acef77 on behalf of 
08-05 13:16:23.036  7858  8187 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-05 13:16:23.038  7858  8187 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-05 13:16:23.038  7858  8186 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-05 13:16:23.040  7858  8187 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ba267e4 on behalf of 
08-05 13:16:23.042  7858  8187 V BluetoothOppNotification: outbound: succ-0  fail-0
08-05 13:16:23.045  7858  8187 V BluetoothOppNotification: outbound notification was removed.
08-05 13:16:23.045  7858  7858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@156806bc
08-05 13:16:23.045  7858  7858 V BluetoothFtpService: Ftp Service onCreate
08-05 13:16:23.045  7858  7858 I BluetoothFtpService: Ftp Service onCreate
08-05 13:16:23.045  7858  8187 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-05 13:16:23.046  7858  7858 V BluetoothFtpService: Ftp Service onStartCommand
08-05 13:16:23.046  7858  7858 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:23.046  7858  7858 V BluetoothFtpService: Starting Listening on sockets
08-05 13:16:23.046  7858  7858 V BtOppService: ContentObserver received notification
08-05 13:16:23.046  7858  7858 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 13:16:23.047  7858  7858 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 13:16:23.047  7858  7858 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 13:16:23.047  7858  7858 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:23.047  7858  7858 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-05 13:16:23.047  7858  7858 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-05 13:16:23.048  7858  8187 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23fdb02 on behalf of 
08-05 13:16:23.049  7858  7858 V BtOppService: ContentObserver received notification
08-05 13:16:23.049  7858  7858 V BluetoothFtpService: Handler(): got msg=1
08-05 13:16:23.052  7858  7858 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-05 13:16:23.052  7858  7858 V BluetoothFtpService: Ftp Service initSocket
08-05 13:16:23.052  7858  8189 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 13:16:23.052  7858  8189 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-05 13:16:23.054  7858  8189 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f770c13 on behalf of 
08-05 13:16:23.055  7858  8189 V BluetoothOppNotification: update too frequent, put in queue
08-05 13:16:23.056  7858  8187 V BluetoothOppNotification: inbound: succ-0  fail-0
08-05 13:16:23.058  7858  8189 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-05 13:16:23.059  1036  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:23.060  7858  8187 V BluetoothOppNotification: inbound notification was removed.
08-05 13:16:23.060  7858  8187 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 13:16:23.061  7858  7858 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 13:16:23.062  7858  7858 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-05 13:16:23.062  7858  7858 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-05 13:16:23.063  7858  8187 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5101e50 on behalf of 
08-05 13:16:23.066  7858  8190 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-05 13:16:23.079  7858  7858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@156806bc
,08-05 13:16:23.079  7858  7858 V BluetoothSapService: Sap Service onCreate
,08-05 13:16:23.081  7858  7858 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 13:16:23.081  7858  7858 V BluetoothSapService: state: 12
08-05 13:16:23.081  7858  7858 V BluetoothSapService: Starting SAP server process
,08-05 13:16:23.083  7858  7858 V BluetoothSapService: SAP Service startRfcommListenerThread
08-05 13:16:23.081  8191  8191 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 13:16:23.081  8191  8191 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 13:16:23.087  7858  8192 V BluetoothSapService: Sap Service initRfcommSocket
08-05 13:16:23.088  1036  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:23.089  7858  8192 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 13:16:23.092  7858  8192 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-05 13:16:23.092  7858  8192 V BluetoothSapService: Succeed to create listening socket 
08-05 13:16:23.092  7858  8192 V BluetoothSapService: Accepting socket connection...
,08-05 13:16:23.097  8191  8191 V BT_SAP  : Event pipe created
,08-05 13:16:23.097  8191  8191 V BT_SAP  : create_server_socket qcom.sap.server
08-05 13:16:23.097  8191  8191 V BT_SAP  : created socket fd 6
08-05 13:16:23.484  6900  6964 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 13:16:23.484  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:23.484  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:23.484  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 13:16:23.484  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 13:16:23.484  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 13:16:23.484  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 13:16:23.484  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 13:16:23.498  6900  6964 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 13:16:23.500  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 13:16:23.501  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ff1eb99 added. We now have 8 listener(s)
08-05 13:16:23.501  6900  6964 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 13:16:23.507  1036  1908 D WifiServiceImplEx: setWifiEnabled: false pid=6900, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 13:16:23.508  1036  1908 D WifiService: setWifiEnabled: false pid=6900, uid=10118
08-05 13:16:23.508  1036  1908 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-05 13:16:23.513  6900  6964 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 13:16:23.518  1036  1052 D WifiServiceImplEx: setWifiEnabled: true pid=6900, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 13:16:23.518  1036  1052 D WifiService: setWifiEnabled: true pid=6900, uid=10118
08-05 13:16:23.518  1036  1052 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 13:16:23.536  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-05 13:16:23.536  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-05 13:16:23.536  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-05 13:16:23.537  1036  1539 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-05 13:16:23.537  1036  1539 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-05 13:16:23.540  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-05 13:16:23.540  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-05 13:16:23.540  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-05 13:16:23.540  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-05 13:16:23.540  1036  1539 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-05 13:16:23.540  1036  1539 E WifiHW  : unknown target_country: EU , set to default
08-05 13:16:23.540  1036  1539 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-05 13:16:23.540  1036  1539 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-05 13:16:23.540  1036  1539 I WifiUtil: gEnableBmps=1
08-05 13:16:24.023  7858  7858 V BluetoothOppNotification: new notify threadi!
,08-05 13:16:24.045  7858  7858 V BluetoothOppNotification: send delay message
08-05 13:16:24.077  7858  8206 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-05 13:16:24.096  7858  8206 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@160cf7c on behalf of 
08-05 13:16:24.097  7858  8206 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-05 13:16:24.106  7858  8206 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-05 13:16:24.107  7858  8206 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b585005 on behalf of 
08-05 13:16:24.108  7858  8206 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-05 13:16:24.111  7858  8206 V BluetoothOppNotification: outbound notification was removed.
08-05 13:16:24.112  7858  8206 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-05 13:16:24.113  7858  8206 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25d9c85a on behalf of 
08-05 13:16:24.114  7858  8206 V BluetoothOppNotification: inbound: succ-0  fail-0
08-05 13:16:24.115  7858  8206 V BluetoothOppNotification: inbound notification was removed.
08-05 13:16:24.116  7858  8206 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 13:16:24.116  7858  8206 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@861ea8b on behalf of 
08-05 13:16:24.252   328   895 D SoftapController: Softap fwReload - Ok
,08-05 13:16:24.262  1036  1109 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-05 13:16:24.277  1036  1539 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (734ms)
08-05 13:16:24.281   328   895 D CommandListener: Setting iface cfg
08-05 13:16:24.281   328   895 D CommandListener: Trying to bring down wlan0
08-05 13:16:24.288   328   895 D CommandListener: Clearing all IP addresses on wlan0
,08-05 13:16:24.304  1036  1539 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-05 13:16:24.301  8213  8213 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 13:16:24.321  8213  8213 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 13:16:24.335  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 13:16:24.335  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
08-05 13:16:24.335  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 13:16:24.356  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-05 13:16:24.374  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 13:16:24.375  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:24.378  1036  1539 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-05 13:16:24.378  1036  1539 D WifiMonitor: connecting to supplicant
08-05 13:16:24.381  1946  1946 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-05 13:16:24.383  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 13:16:24.383  7004  7004 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 13:16:24.383  7004  7004 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 13:16:24.383  7004  7004 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 13:16:24.385  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 13:16:24.385  7004  7004 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 13:16:24.385  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-05 13:16:24.385  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 13:16:24.385  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 13:16:24.385  7004  7004 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 13:16:24.386  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-05 13:16:24.386  7004  7004 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-05 13:16:24.388  8213  8213 I wpa_supplicant: Successfully initialized wpa_supplicant
08-05 13:16:24.425  8213  8213 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-05 13:16:24.426  8213  8213 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-05 13:16:24.427  1036  1907 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8229 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-05 13:16:24.431  1036  1109 D Tethering: InitialState.processMessage what=4
08-05 13:16:24.431  1036  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-05 13:16:24.497  8213  8213 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-05 13:16:24.535  1036  1729 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8252 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-05 13:16:24.540  8229  8250 W FormManager: Network not available. Please check & try again.
08-05 13:16:24.543  8213  8213 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-05 13:16:24.543  8229  8251 V FormManager: Network unavailable.
08-05 13:16:24.545  8229  8251 V FormManager: Network unavailable.
08-05 13:16:24.546  8213  8213 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-05 13:16:24.547  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-05 13:16:24.547  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-05 13:16:24.547  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-05 13:16:24.548  1036  1539 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-05 13:16:24.548  1036  8267 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-05 13:16:24.548  1036  8267 D WifiMonitor: Dropping event because (p2p0) is stopped
08-05 13:16:24.548  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,08-05 13:16:24.548  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 13:16:24.548  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-05 13:16:24.549  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 13:16:24.549  1036  1539 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-05 13:16:24.549  1036  1539 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-05 13:16:24.549  1036  1539 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-05 13:16:24.549  1036  1539 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-05 13:16:24.550  1036  1539 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-05 13:16:24.550  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 13:16:24.550  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
08-05 13:16:24.550  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 13:16:24.550  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:24.550  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:24.550  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:24.550  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:24.551  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 13:16:24.553  1946  1946 D WfdService: Waiting for WifiP2p enabling
08-05 13:16:24.554  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:24.554  1036  8267 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-05 13:16:24.554  1036  8267 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-05 13:16:24.554  8213  8213 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-05 13:16:24.555  1036  8267 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-05 13:16:24.555  1036  8267 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-05 13:16:24.555  1036  8267 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-05 13:16:24.555  1036  8267 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-05 13:16:24.555  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-05 13:16:24.555  1036  1544 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-05 13:16:24.557  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 13:16:24.557  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:24.557  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:24.557  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 13:16:24.557  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 13:16:24.557  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 13:16:24.557  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 13:16:24.557  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 13:16:24.558  6900  6900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 13:16:24.560  1036  1539 D WifiNative-wlan0: doBoolean: SET update_config 1
08-05 13:16:24.561  1036  1539 D WifiNative-wlan0: SET update_config 1: returned true
08-05 13:16:24.561  1036  1539 D WifiConfigStore: Loading config and enabling all networks 
08-05 13:16:24.561  1036  1539 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-05 13:16:24.561  1036  1539 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,08-05 13:16:24.568  1036  1539 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-05 13:16:24.571  1036  1926 I ActivityManager: Killing 7308:com.android.chrome/u0a57 (adj 15): empty #17
08-05 13:16:24.580  1036  1539 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-05 13:16:24.580  1036  1539 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-05 13:16:24.588  8252  8252 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 13:16:24.614  1036  1539 D WifiStateMachine: enableVerboseLogging : level 2
08-05 13:16:24.614  1036  1539 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-05 13:16:24.614  1036  2035 W libprocessgroup: failed to open /acct/uid_10057/pid_7308/cgroup.procs: No such file or directory
08-05 13:16:24.615  1036  1539 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-05 13:16:24.615  1036  1539 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-05 13:16:24.615  1036  1539 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-05 13:16:24.615  1036  1539 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-05 13:16:24.615  1036  1539 D WifiNative-wlan0: SET model_name LG-D855: returned true
,08-05 13:16:24.615  1036  1539 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-05 13:16:24.616  1036  1539 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-05 13:16:24.616  1036  1539 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-05 13:16:24.616  1036  1539 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-05 13:16:24.616  1036  1539 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-05 13:16:24.616  1036  1539 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-05 13:16:24.616  1036  1539 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-05 13:16:24.617  1036  1539 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-05 13:16:24.622  1036  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 13:16:24.622  1036  1539 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-05 13:16:24.623  1946  1946 D WfdsService: Supplicant Connection state is changed : true
08-05 13:16:24.623  1946  2307 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-05 13:16:24.623  1946  2307 D WfdsService: Set the WFDS Monitor: true
08-05 13:16:24.623  1946  2307 D WfdsMonitor: WfdsMonitorThread create
08-05 13:16:24.623  1946  2307 D WfdsMonitor: WFDS Monitor is created and started
08-05 13:16:24.623  1946  2307 D WfdsService: WiFi: Supplicant connection re-established
08-05 13:16:24.623  1036  1539 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-05 13:16:24.623  1036  1539 D WifiNative-HAL: Setting external_sim to 1
08-05 13:16:24.623  1036  1539 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-05 13:16:24.624  1036  1539 D WifiNative-wlan0: SET external_sim 1: returned true
08-05 13:16:24.624  1036  1539 I WifiNative-HAL: startHal
08-05 13:16:24.624  1036  1539 D wifi    : setting scan oui 0xaf6afe60
08-05 13:16:24.624  1036  1539 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 13:16:24.624  1036  1539 I WifiNative-HAL: startHal
08-05 13:16:24.624  1036  1539 D wifi    : setting scan oui 0xaf6afe60
08-05 13:16:24.624  1036  1539 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-05 13:16:24.624  1036  1539 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-05 13:16:24.624  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-05 13:16:24.625  8213  8213 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-05 13:16:24.625  1946  8274 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-05 13:16:24.625  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-05 13:16:24.625  7887  7887 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:24.625  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-05 13:16:24.625  8213  8213 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 13:16:24.625  1946  8274 E CtrlSupplicant: Succeed to open control connection
08-05 13:16:24.625  1946  8274 E CtrlSupplicant: Succeed to open monitor connection
08-05 13:16:24.625  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 13:16:24.625  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-05 13:16:24.625  8213  8213 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-05 13:16:24.626  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-05 13:16:24.626  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 13:16:24.626  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 13:16:24.626  8213  8213 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-05 13:16:24.626  1946  8274 D WfdsMonitor: Supplicant connection established
08-05 13:16:24.626  1946  2307 D WfdsService: Connected to the supplicant for wfds
08-05 13:16:24.626  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: r,eturned true
08-05 13:16:24.627  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-05 13:16:24.627  8213  8213 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 13:16:24.627  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 13:16:24.627  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-05 13:16:24.627  8213  8213 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-05 13:16:24.627  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-05 13:16:24.627  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 13:16:24.627  8213  8213 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-05 13:16:24.627  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-05 13:16:24.629  1036  1539 E WifiNative: : [354,982,372 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-05 13:16:24.629  1036  1539 D WifiNative-wlan0: doBoolean: RECONNECT
08-05 13:16:24.630  1036  1539 D WifiNative-wlan0: RECONNECT: returned true
08-05 13:16:24.630  1036  1539 D WifiNative-wlan0: doString: [STATUS]
08-05 13:16:24.630  1036  8267 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-05 13:16:24.630  1036  8267 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-05 13:16:24.630  1036  1539 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-05 13:16:24.630  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 13:16:24.631  1036  1539 D WifiNative-wlan0: SET ps 1: returned true
08-05 13:16:24.631  1036  1538 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:24.632  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-05 13:16:24.632  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-05 13:16:24.632  1036  1557 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:24.632  1036  1557 I WifiNative-HAL: startHal
08-05 13:16:24.632  1036  1539 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-05 13:16:24.632  1036  1557 D wifi    : getting scan capabilities on interface[1] = 0xaf6afe60
08-05 13:16:24.632  1036  1557 D wifi    : failed to get capabilities : -3
08-05 13:16:24.632  1036  1557 E WifiScanningService: could not get scan capabilities
08-05 13:16:24.633  1036  1539 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-05 13:16:24.633  1036  1558 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:24.633  1036  1539 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-05 13:16:24.633  1036  1539 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-05 13:16:24.633  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=354987  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 13:16:24.635   328   895 D CommandListener: Setting iface cfg
08-05 13:16:24.635   328   895 D CommandListener: Trying to bring up p2p0
08-05 13:16:24.636  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:24.636  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 13:16:24.636  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:24.636  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:24.636  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-05 13:16:24.636  1036  1538 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-05 13:16:24.637  1036  1538 D LGWifiP2pService: P2pEnablingState
08-05 13:16:24.637  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=354990  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 13:16:24.637  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:24.637  1036  1538 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:24.637  1036  1538 D LGWifiP2pService: P2p socket connection successful
08-05 13:16:24.637  1036  1538 D LGWifiP2pService: P2pEnabledState
08-05 13:16:24.637  1036  1539 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-05 13:16:24.637  1036  1538 D LGWifiP2pService: sending p2p connection changed broadcast
08-05 13:16:24.638  1036  1539 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-05 13:16:24.638  1946  1946 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-05 13:16:24.638  1036  1539 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-05 13:16:24.638  1036  1539 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-05 13:16:24.638  1946  1946 D WfdsService: WifiP2pState is changed : true
08-05 13:16:24.639  8213  8213 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-05 13:16:24.639  1036  1539 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-05 13:16:24.639  1036  1539 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-05 13:16:24.639  1946  2307 D WfdsService: Receive the WFDS_ENABLE Method
08-05 13:16:24.639  1946  2307 D WfdsService: Set the WFDS Monitor: true
,08-05 13:16:24.639  1946  2307 D WfdsService: Connected to the supplicant for wfds
08-05 13:16:24.639  1946  2307 D WfdsJNI : doCommand: WFDS_SET TRUE
08-05 13:16:24.639  1036  1539 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-05 13:16:24.640  8213  8213 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-05 13:16:24.640  1946  2307 D WfdsService: selectPreferredScanChannel [36]
08-05 13:16:24.640  1946  2307 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-05 13:16:24.640  1036  1539 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-05 13:16:24.640  1036  1538 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-05 13:16:24.640  8213  8213 E wpa_supplicant: disconnect_rssi_lvl: -100
08-05 13:16:24.640  1036  1539 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-05 13:16:24.640  1036  1538 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-05 13:16:24.641  1036  1538 D WifiNative-p2p0: doBoolean: SET device_name G3
08-05 13:16:24.642  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:24.643  1946  1946 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-05 13:16:24.643  1036  1538 D WifiNative-p2p0: SET device_name G3: returned true
08-05 13:16:24.643  1036  1538 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-05 13:16:24.643  1036  1538 D LGWifiP2pService: before postfix = G3
08-05 13:16:24.643  1036  1538 D WifiServerServiceExt: postfix byte check : 2
08-05 13:16:24.643  1036  1538 D LGWifiP2pService: after postfix = G3
08-05 13:16:24.643  1036  1538 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-05 13:16:24.643  1036  1538 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-05 13:16:24.643  1036  1538 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-05 13:16:24.644  1036  1052 I ActivityManager: Killing 7328:com.lge.drmservice/u0a62 (adj 15): empty #17
08-05 13:16:24.644  1036  1538 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-05 13:16:24.644  1036  1538 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-05 13:16:24.644  1036  1539 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-05 13:16:24.644  1036  1538 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-05 13:16:24.644  1036  1538 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-05 13:16:24.644  1036  1539 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-05 13:16:24.644  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-05 13:16:24.644  1036  1538 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-05 13:16:24.644  1036  1538 D WifiNative-HAL: p2pGetDeviceAddress
08-05 13:16:24.644  1946  1946 D WfdsService: isConnected: false
08-05 13:16:24.645  1036  1538 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-05 13:16:24.645  8213  8213 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 13:16:24.646  8213  8213 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 13:16:24.646  1036  8267 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 13:16:24.646  8213  8213 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 13:16:24.646  1036  8267 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 13:16:24.647  8213  8213 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:24.647  1036  8267 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 13:16:24.647  1946  8274 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 13:16:24.647  1036  8267 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 13:16:24.647  1036  8267 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 13:16:24.647  1036  8267 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:24.647  1036  8267 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:24.647  1036  8267 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:24.647  1036  1539 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-05 13:16:24.647  8213  8213 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:24.647  1036  1539 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-05 13:16:24.647  1036  8267 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 13:16:24.648  1036  8267 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:24.648  1036  8267 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:24.648  1036  8267 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:24.648  1946  8274 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 13:16:24.648  1036  1539 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-05 13:16:24.648  1036  1539 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-05 13:16:24.648  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-05 13:16:24.648  8213  8213 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-05 13:16:24.649  8213  8213 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 13:16:24.649  1036  8267 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-05 13:16:24.649  1036  8267 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 13:16:24.649  1036  8267 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 13:16:24.649  1036  8267 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 13:16:24.649  1036  1539 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-05 13:16:24.649  1036  1539 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-05 13:16:24.649  1036  1539 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-05 13:16:24.649  1036  1539 D WifiNative-wlan0: doBoolean: SCAN
08-05 13:16:24.650  1036  1539 D WifiNative-wlan0: SCAN: returned false
08-05 13:16:24.650  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=355003  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 13:16:24.676  1036  2035 W libprocessgroup: failed to open /acct/uid_10062/pid_7328/cgroup.procs: No such file or directory
08-05 13:16:24.676  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=355029  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 13:16:24.681  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:24.681  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 13:16:24.682  1036  1538 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-05 13:16:24.682  1036  1538 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-05 13:16:24.682  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:24.682  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:24.682  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-05 13:16:24.682  1036  1538 D WifiNative-p2p0: P2P_FLUSH: returned true
08-05 13:16:24.682  1036  1538 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-05 13:16:24.682  1036  1538 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-05 13:16:24.683  1036  1538 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-05 13:16:24.683  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:24.684  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 13:16:24.684  1036  1539 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 13:16:24.684  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-05 13:16:24.684  1036  1539 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 13:16:24.685  1036  1539 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 13:16:24.685  1036  1539 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 13:16:24.685  1946  1946 I WfdStateTracker: handleP2pThisDeviceChanged
08-05 13:16:24.686  1946  1946 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-05 13:16:24.686  1036  1538 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-05 13:16:24.686  1036  1538 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-05 13:16:24.686  1946  1946 D WfdsService: Update P2p Interface State: 3
08-05 13:16:24.687  1036  1539 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 13:16:24.687  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 13:16:24.687  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-05 13:16:24.689  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 13:16:24.689  7004  7004 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 13:16:24.689  7004  7004 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 13:16:24.689  7004  7004 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 13:16:24.690  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 13:16:24.691  7004  7004 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 13:16:24.691  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 13:16:24.691  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 13:16:24.691  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 13:16:24.691  7004  7004 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 13:16:24.691  7004  7004 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 13:16:24.696  1036  1538 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-05 13:16:24.696  1036  1538 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-05 13:16:24.696  1036  1538 D LGWifiP2pService: InactiveState
08-05 13:16:24.696  1036  1538 D LGWifiP2pService: InactiveState{ when=-49ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:24.696  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-49ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:24.696  1036  1538 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-05 13:16:24.697  8252  8252 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 13:16:24.697  8213  8213 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 13:16:24.698  8213  8213 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 13:16:24.699  1036  8267 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 13:16:24.699  1036  8267 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 13:16:24.699  1036  8267 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 13:16:24.699  1036  8267 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 13:16:24.699  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 13:16:24.699  8213  8213 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 13:16:24.700  8213  8213 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:24.700  1036  8267 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 13:16:24.700  1036  8267 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:24.700  1036  8267 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:24.700  1036  8267 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:24.700  1946  8274 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 13:16:24.700  1946  8274 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 13:16:24.700  8213  8213 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:24.701  1036  1538 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-05 13:16:24.701  1036  1538 D LGWifiP2pService: InactiveState{ when=-18ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:24.701  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-18ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:24.701  1036  1538 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 13:16:24.701  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:24.701  1036  1538 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:24.701  1036  1538 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:24.701  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:24.701  1036  1538 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:24.701  1036  1538 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:24.701  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:24.701  1036  1538 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:24.701  1946  8274 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 13:16:24.702  1946  2307 W WfdsService: DefaultState - msg [9441285] is not handled
08-05 13:16:24.703  1036  1538 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:24.703  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:24.703  1036  1538 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:24.703  1036  1036 E WifiServerServiceExt: No p2p device connected
08-05 13:16:24.703  1036  8267 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 13:16:24.703  1036  8267 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:24.703  1036  8267 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:24.703  1036  8267 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 13:16:24.705  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:24.709  8229  8276 W FormManager: Network not available. Please check & try again.
08-05 13:16:24.717  4691  4691 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 13:16:24.718  4691  4691 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 13:16:24.719  8229  8277 V FormManager: Network unavailable.
08-05 13:16:24.720  4691  4691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 13:16:24.722  8229  8277 V FormManager: Network unavailable.
08-05 13:16:24.723  4691  4691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 13:16:24.728  4691  8278 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 13:16:24.730  4691  8279 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-05 13:16:24.730  4691  8279 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 13:16:24.786  1036  1890 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8280 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-05 13:16:24.869  8280  8280 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-05 13:16:24.892  8280  8280 D PluginManager: init()
,08-05 13:16:25.251  8213  8213 E wpa_supplicant: USIM:  scard_init function
08-05 13:16:25.252  8213  8213 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-05 13:16:25.252  1036  8267 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-05 13:16:25.252  1036  8267 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-05 13:16:25.252  1036  8267 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-05 13:16:25.252  1036  8267 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-05 13:16:25.252  1036  8267 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-05 13:16:25.253  1036  8267 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-05 13:16:25.253  1036  8267 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-05 13:16:25.258  1036  1539 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-05 13:16:25.259  1036  1539 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-05 13:16:25.261  1036  1539 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-05 13:16:25.262  1036  1539 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-05 13:16:25.262  1036  1539 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,08-05 13:16:25.276  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=355630  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-05 13:16:25.281  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 13:16:25.281  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:25.281  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-05 13:16:25.282  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:25.282  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 13:16:25.284  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=355637  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-05 13:16:25.286  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 13:16:25.286  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-05 13:16:25.287  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:25.291  8280  8280 W ExternalStrings: load override strings
08-05 13:16:25.291  8280  8280 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-05 13:16:25.291  8280  8280 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-05 13:16:25.291  8280  8280 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-05 13:16:25.291  8280  8280 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-05 13:16:25.291  8280  8280 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-05 13:16:25.291  8280  8280 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-05 13:16:25.291  8280  8280 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-05 13:16:25.291  8280  8280 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-05 13:16:25.291  8280  8280 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-05 13:16:25.291  8280  8280 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-05 13:16:25.291  8280  8280 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-05 13:16:25.291  8280  8280 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 13:16:25.291  8280  8280 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-05 13:16:25.291  8280  8280 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 13:16:25.291  8280  8280 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 13:16:25.291  8280  8280 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 13:16:25.291  8280  8280 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 13:16:25.291  8280  8280 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-05 13:16:25.294  8280  8280 D StatusProvider: onCreate
08-05 13:16:25.363  8280  8280 V Signer  : override build config not found
,08-05 13:16:25.363  8280  8280 D Signer  : value of property debug is false
08-05 13:16:25.377  8213  8213 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-05 13:16:25.380  1036  1109 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-05 13:16:25.380  1036  8267 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-05 13:16:25.380  1036  8267 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-05 13:16:25.381  1036  8267 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-05 13:16:25.381  1036  8267 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-05 13:16:25.381  1036  8267 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 13:16:25.381  1036  8267 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 13:16:25.382  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=355735  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-05 13:16:25.382  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=355735  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-05 13:16:25.383  1036  1539 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-05 13:16:25.383  1036  1539 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-05 13:16:25.384  1036  1539 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-05 13:16:25.384  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-05 13:16:25.384  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 13:16:25.385  1036  1539 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=355738
08-05 13:16:25.386  1036  1539 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=355739
08-05 13:16:25.386  1036  1539 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=355739
08-05 13:16:25.387  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=355740
08-05 13:16:25.387  1036  1539 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=355741
08-05 13:16:25.388  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=355741  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-05 13:16:25.390  8213  8213 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 13:16:25.391  8213  8213 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 13:16:25.393  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:25.393  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:25.394  1036  8267 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 13:16:25.394  1036  8267 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 13:16:25.394  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-05 13:16:25.394  1036  8267 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-05 13:16:25.394  1036  8267 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 13:16:25.394  1036  8267 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 13:16:25.394  1036  8267 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-05 13:16:25.394  1036  8267 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 13:16:25.394  1036  8267 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 13:16:25.394  1036  8267 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 13:16:25.394  1036  8267 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 13:16:25.397  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:25.397  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 13:16:25.397  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=355750  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-05 13:16:25.399  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 13:16:25.401  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=355755  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-05 13:16:25.402  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=355755  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-05 13:16:25.403  1036  1539 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=355756
,08-05 13:16:25.404  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:25.404  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 13:16:25.405  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:25.405  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:25.405  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-05 13:16:25.405  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 13:16:25.405  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-05 13:16:25.406  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:25.408  1036  1539 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=355761
08-05 13:16:25.408  8280  8280 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-05 13:16:25.408  8280  8280 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-05 13:16:25.408  1036  1539 D WifiNative-wlan0: doString: [STATUS]
08-05 13:16:25.408  8280  8280 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-05 13:16:25.409  8280  8280 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-05 13:16:25.409  1036  8267 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 13:16:25.409  1036  8267 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 13:16:25.409  8280  8280 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-05 13:16:25.409  8280  8280 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-05 13:16:25.409  1036  1539 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-05 13:16:25.410  8280  8280 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-05 13:16:25.410  8280  8280 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-05 13:16:25.410  8280  8280 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-05 13:16:25.410  8280  8280 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-05 13:16:25.411  8280  8280 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-05 13:16:25.411  8280  8280 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-05 13:16:25.411  1036  1539 I WifiServiceExtension: setVHTCapabilityType  : false
08-05 13:16:25.411  8280  8280 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-05 13:16:25.416  1036  1539 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-05 13:16:25.416  1036  1539 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-05 13:16:25.422  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:25.422  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:25.422  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-05 13:16:25.423  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:25.424  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:25.424  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-05 13:16:25.425  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:25.425  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 13:16:25.426  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:25.427  8280  8280 V LGMDMManager: Create singleton instance
08-05 13:16:25.428  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:25.428  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-05 13:16:25.428  1036  1378 V AlarmManager: RTC_WAKEUP set : Alarm{11b8b6ad type 0 when 1470395779856 com.google.android.gms} when 1470395779856
08-05 13:16:25.429  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:25.435  1036  1539 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-05 13:16:25.435  1036  1546 D ConnectivityService: Got NetworkAgent Messenger
08-05 13:16:25.435  1036  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 13:16:25.435  1036  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 13:16:25.435  1036  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-05 13:16:25.435  1036  1546 D ConnectivityService: NetworkAgent connected
08-05 13:16:25.435  1036  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 13:16:25.435  1036  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 13:16:25.443  1036  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 13:16:25.443  1036  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 13:16:25.443  1036  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-05 13:16:25.445  1036  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 13:16:25.445  1036  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 13:16:25.448  1036  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 13:16:25.449   328   895 D CommandListener: Setting iface cfg
08-05 13:16:25.451  1036  1539 E WifiStateMachine: Start Dhcp Watchdog 3
08-05 13:16:25.451  1036  8315 D DhcpStateMachine: StoppedState
08-05 13:16:25.451  1036  8315 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:25.451  1036  8315 D DhcpStateMachine: WaitBeforeStartState
08-05 13:16:25.451  1036  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=355804  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 13:16:25.452  1036  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=355805  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 13:16:25.452  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=355805  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 13:16:25.453  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 13:16:25.453  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-05 13:16:25.454  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 13:16:25.454  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,08-05 13:16:25.454  1036  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=355808  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 13:16:25.455  1036  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=355808  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 13:16:25.455  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=355808  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 13:16:25.457  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14324] from screen [on:0 period:1516970224] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 13:16:25.457  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1516970225] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 13:16:25.457  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 13:16:25.460  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:25.461  1036  1546 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-05 13:16:25.462  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:25.462  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:25.462  1036  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:25.463  1036  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:25.463  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:25.463  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:25.464  1036  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-05 13:16:25.464  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=158,0,0
08-05 13:16:25.464  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=158,0,0
08-05 13:16:25.464  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-05 13:16:25.465  8213  8213 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-05 13:16:25.465  1036  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-05 13:16:25.465  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 0
08-05 13:16:25.465  1036  1539 D WifiNative-wlan0: SET ps 0: returned true
08-05 13:16:25.465  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-05 13:16:25.465  8213  8213 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-05 13:16:25.466  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-05 13:16:25.466  1036  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3cdf038c target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:25.466  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3cdf038c target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:25.466  1036  8315 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:25.466  1036  8315 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-05 13:16:25.466  1036  1539 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-05 13:16:25.466  1036  1539 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-05 13:16:25.466  1036  1539 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,08-05 13:16:25.474   328   895 D CommandListener: Setting iface cfg
08-05 13:16:25.474   328   895 D CommandListener: Trying to bring up wlan0
08-05 13:16:25.475  1036  1539 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-05 13:16:25.476  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 13:16:25.476  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-05 13:16:25.477  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 13:16:25.477  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-05 13:16:25.477  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:25.478  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:25.478  1036  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:25.479  1036  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:25.479  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:25.480  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 13:16:25.480  1036  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-05 13:16:25.481  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-05 13:16:25.481  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-05 13:16:25.481  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 13:16:25.481  1036  1538 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:25.482  1036  1538 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:25.482  8213  8213 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-05 13:16:25.482  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 13:16:25.484  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-05 13:16:25.484  8213  8213 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-05 13:16:25.484  1036  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-05 13:16:25.484  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 13:16:25.486  8280  8280 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
08-05 13:16:25.500  1036  1539 D WifiNative-wlan0: SET ps 1: returned true
08-05 13:16:25.500  1036  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,08-05 13:16:25.501  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,08-05 13:16:25.501  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-05 13:16:25.502  1036  1539 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-05 13:16:25.503  1036  1546 D ConnectivityService: ignoring duplicate network state non-change
08-05 13:16:25.507  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:25.507  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 13:16:25.509  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:25.510  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:25.510  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:25.510  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-05 13:16:25.512  1036  1546 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-05 13:16:25.515  1036  1546 D ConnectivityService: Adding iface wlan0 to network 102
08-05 13:16:25.516  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:25.516  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:25.516  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-05 13:16:25.519  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-05 13:16:25.523  1946  1946 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-05 13:16:25.529  8280  8280 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 13:16:25.530  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:25.530  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-05 13:16:25.531  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:25.533  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:25.533  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:25.534  1036  1539 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-05 13:16:25.536  8280  8319 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-05 13:16:25.538  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-05 13:16:25.538  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-05 13:16:25.538  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:25.538  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-05 13:16:25.539  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:25.540  1036  1546 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-05 13:16:25.540  1036  1546 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-05 13:16:25.541  1036  1546 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-05 13:16:25.541   328   895 E Netd    : netlink response contains error (File exists)
08-05 13:16:25.541  1036  1546 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-05 13:16:25.542  1036  1546 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-05 13:16:25.542  1036  1546 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-05 13:16:25.542  1036  1546 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-05 13:16:25.544  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:25.544  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:25.544  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-05 13:16:25.546  1036  1546 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-05 13:16:25.546  1036  1546 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-05 13:16:25.546  1036  1546 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-05 13:16:25.546  1036  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-05 13:16:25.546  1036  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 13:16:25.546  1036  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 13:16:25.547  1036  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-05 13:16:25.547  1036  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:25.547  1036  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-05 13:16:25.547  1036  1546 D ConnectivityService: currentScore = 0, newScore = 20
08-05 13:16:25.547  1036  1546 D ConnectivityService:    accepting network in place of null
08-05 13:16:25.547  1036  1546 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:25.548  1036  1546 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-05 13:16:25.548  1036  1546 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-05 13:16:25.548  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 13:16:25.548  1036  8314 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:25.548  1036  8314 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-05 13:16:25.548  1036  8314 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:25.548  1036  1539 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:25.548  1036  8314 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-05 13:16:25.548  1036  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 13:16:25.549  1036  1546 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:25.549  1036  1546 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-05 13:16:25.549  1036  1546 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED,, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-05 13:16:25.550   328  8323 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-05 13:16:25.550  1036  1546 D ConnectivityService: validation of new default Network = false
08-05 13:16:25.550  1036  1546 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-05 13:16:25.550  1036  1546 D DSQN    : enableDataServiceNotify 
08-05 13:16:25.550  1036  1546 D DSQN    : start dsqn bin
08-05 13:16:25.553  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-05 13:16:25.553  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 13:16:25.553  1855  1855 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:25.553  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 13:16:25.553  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 13:16:25.554  1855  1855 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-05 13:16:25.558  6900  6964 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 13:16:25.558  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:25.558  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:25.558  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 13:16:25.558  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 13:16:25.558  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 13:16:25.558  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 13:16:25.558  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 13:16:25.559  1036  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-05 13:16:25.551  8325  8325 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 13:16:25.559  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:25.559  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 13:16:25.551  8325  8325 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 13:16:25.559  1036  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 13:16:25.562  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 13:16:25.563  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:25.564  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-05 13:16:25.564  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:25.568  1036  1537 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-05 13:16:25.569  6900  6964 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 13:16:25.571  8325  8325 E DSQN    : DSQN ssw
08-05 13:16:25.572  1604  1818 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-05 13:16:25.575  6900  6964 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-05 13:16:25.576  6900  6964 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-05 13:16:25.577  6900  6964 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@201f843 Bundle[{}]
08-05 13:16:25.578  6900  6964 I io.jxcore.node.LifeCycleMonitor: start: OK
08-05 13:16:25.579  6900  6964 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-05 13:16:25.580  6900  6964 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-05 13:16:25.580  6900  6964 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-05 13:16:25.580  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:25.581  6900  6964 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-05 13:16:25.582  6900  6964 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-05 13:16:25.589  6900  6964 I System.out: Running OutgoingSocketThread
,08-05 13:16:25.591  6900  8330 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 906)
08-05 13:16:25.592  6900  8330 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 46031
08-05 13:16:25.592  6900  8330 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-05 13:16:25.615   328  8323 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-05 13:16:25.625  1036  1707 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8331 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-05 13:16:25.627  1036  1707 I ActivityManager: Killing 7345:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-05 13:16:25.648   328  8323 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-05 13:16:25.656   354   354 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 452us total 27.667ms
08-05 13:16:25.668  1036  8315 D DhcpStateMachine: DHCPV4 request on wlan0
,08-05 13:16:25.669  1036  8315 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-05 13:16:25.669  1036  8315 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-05 13:16:25.661  8348  8348 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 13:16:25.661  8348  8348 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 13:16:25.676   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 286us total 19.876ms
08-05 13:16:25.681  8348  8348 I dhcpcd  : version 5.5.6 starting
,08-05 13:16:25.684  8348  8348 E dhcpcd  : get_duid: m
08-05 13:16:25.684  8348  8348 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-05 13:16:25.684  8348  8348 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-05 13:16:25.690   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 306us total 13.897ms
08-05 13:16:25.693   328   894 D LGDataListener: argv[0]=dsqncommand
08-05 13:16:25.693   328   894 D LGDataListener: argv[1]=wlan0
08-05 13:16:25.693   328   894 D LGDataListener: argv[2]=1
08-05 13:16:25.693   328   894 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-05 13:16:25.694  1036  1106 D DSQN    : DSQM DsqnNotification wlan0  1
08-05 13:16:25.694  1036  1106 D DSQN    : start to monitor internet connection
08-05 13:16:25.701  8280  8318 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-05 13:16:25.705  1036  1576 W libprocessgroup: failed to open /acct/uid_10085/pid_7345/cgroup.procs: No such file or directory
08-05 13:16:25.727  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-05 13:16:25.728  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 13:16:25.730  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:25.738  8348  8348 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-05 13:16:25.738  8348  8348 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-05 13:16:25.738  8348  8348 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-05 13:16:25.738  8348  8348 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-05 13:16:25.738  8348  8348 D dhcpcd  : wlan0: sending REQUEST (xid 0xcb2201b9), next in 4.62 seconds
08-05 13:16:25.741  1036  8314 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Aug 2016 11:16:25 GMT], X-Android-Received-Millis=[1470395785741], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470395785692]}
08-05 13:16:25.742  1036  8314 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-05 13:16:25.742  1036  8314 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-05 13:16:25.742  8331  8331 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 13:16:25.742  1036  1546 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-05 13:16:25.742  1036  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-05 13:16:25.742  1036  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 13:16:25.742  1036  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 13:16:25.742  1036  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-05 13:16:25.743  1036  1546 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
,08-05 13:16:25.743  1036  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-05 13:16:25.743  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:25.743  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 13:16:25.744  1036  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 13:16:25.744  1036  1546 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:25.745  1604  1818 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-05 13:16:25.745  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-05 13:16:25.745  1036  1539 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:25.745  1036  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 13:16:25.746  1855  1855 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:25.746  1855  1855 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-05 13:16:25.758  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 13:16:25.759  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:25.760  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:25.769  8331  8331 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-05 13:16:25.792  8331  8331 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-05 13:16:25.792  8331  8331 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-05 13:16:25.793  8331  8331 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-05 13:16:25.793  8331  8331 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-05 13:16:25.793  8331  8331 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-05 13:16:25.794  8348  8348 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-05 13:16:25.795  8331  8331 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-05 13:16:25.799  8331  8331 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-05 13:16:25.804  8331  8331 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 13:16:25.808  8331  8331 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 13:16:25.823  8348  8348 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-05 13:16:25.824  8348  8348 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-05 13:16:25.824  8331  8331 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 13:16:25.824  8348  8348 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-05 13:16:25.825  8348  8348 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-05 13:16:25.825  8348  8348 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-05 13:16:25.826  8348  8348 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-05 13:16:25.826  8348  8348 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-05 13:16:25.826  8348  8348 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-05 13:16:25.829  8331  8331 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-05 13:16:25.835  8331  8331 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-05 13:16:25.868  1036  1999 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8371 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-05 13:16:25.887  8280  8318 D LgDataFeature: LgDataFeature() Constructor: none
08-05 13:16:25.887  8280  8318 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 13:16:25.950  8371  8371 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-05 13:16:25.950  8371  8371 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-05 13:16:25.956  8371  8371 V [BNRBootReceiver]: Boot Receiver Return
08-05 13:16:25.956  8371  8371 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-05 13:16:25.958  8280  8280 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 13:16:25.958  8280  8319 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-05 13:16:25.964  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 13:16:25.968  8280  8318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-05 13:16:25.974  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:25.979  1036  1944 I ActivityManager: Killing 7394:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-05 13:16:25.997  8280  8318 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-05 13:16:26.003  8280  8318 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-05 13:16:26.003  8280  8318 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-05 13:16:26.004  8280  8318 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-05 13:16:26.005  8280  8318 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-05 13:16:26.006  8280  8318 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-05 13:16:26.012  8280  8318 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,08-05 13:16:26.013  8280  8318 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,08-05 13:16:26.073  1036  8315 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-05 13:16:26.075  1036  8315 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-05 13:16:26.076  1036  8315 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-05 13:16:26.076  1036  8315 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-05 13:16:26.076  1036  8315 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-05 13:16:26.077  1036  8315 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-05 13:16:26.077  1036  8315 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-05 13:16:26.077  1036  8315 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-05 13:16:26.078  1036  8315 D DhcpStateMachine: RunningState
08-05 13:16:26.193  8331  8331 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 13:16:26.194  8331  8331 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 13:16:26.194  1036  2035 W libprocessgroup: failed to open /acct/uid_10093/pid_7394/cgroup.procs: No such file or directory
08-05 13:16:26.205  8331  8331 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-05 13:16:26.214  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-05 13:16:26.217  7004  7004 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-05 13:16:26.222  8280  8280 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 13:16:26.222  8280  8319 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-05 13:16:26.236  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 13:16:26.248  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:26.261  8331  8331 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 13:16:26.261  8331  8331 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 13:16:26.262  8331  8331 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 13:16:26.268  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 13:16:26.268  7004  7004 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 13:16:26.268  7004  7004 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 13:16:26.268  7004  7004 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 13:16:26.269  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 13:16:26.270  7004  7004 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 13:16:26.270  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-05 13:16:26.270  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 13:16:26.271  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 13:16:26.271  7004  7004 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 13:16:26.271  7004  7004 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-05 13:16:26.271  7004  7004 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 13:16:26.275  8280  8280 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 13:16:26.275  8280  8319 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-05 13:16:26.285  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 13:16:26.297  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:26.307  8331  8331 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 13:16:26.308  8331  8331 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 13:16:26.309  8331  8331 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 13:16:26.315  8280  8280 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 13:16:26.316  8280  8319 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-05 13:16:26.332  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 13:16:26.341  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:26.348  8331  8331 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 13:16:26.349  8331  8331 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 13:16:26.349  8331  8331 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 13:16:26.352  8280  8280 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 13:16:26.386  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 13:16:26.397  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 13:16:26.405  8331  8331 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 13:16:26.405  8331  8331 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 13:16:26.407  8331  8331 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 13:16:26.410  8280  8280 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 13:16:26.420  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 13:16:26.430  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:26.442  8331  8331 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 13:16:26.443  8331  8331 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 13:16:26.444  8331  8331 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 13:16:26.465  8331  8331 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-05 13:16:26.466  8331  8331 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:3356
,08-05 13:16:26.486  1819  8415 I CheckinService: active receiver: enabled
,08-05 13:16:26.491  8280  8280 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 13:16:26.591  6900  6964 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 907)
08-05 13:16:26.591  6900  6964 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 907)
08-05 13:16:26.597  6900  6964 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 912)
,08-05 13:16:26.599  6900  6964 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-05 13:16:26.599  6900  6964 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 913)
08-05 13:16:26.602  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 13:16:26.602  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11201e5e added. We now have 2 listener(s)
08-05 13:16:26.626  1036  1539 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 13:16:26.626  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 13:16:26.627  1036  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 13:16:26.627  1036  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 13:16:26.628  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 13:16:26.628  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 13:16:26.629  1036  1546 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-05 13:16:26.629  1036  1546 D ConnectivityService: identical MTU - not setting
08-05 13:16:26.629  1036  1546 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-05 13:16:26.629  1036  1546 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-05 13:16:26.629  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:26.629  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 13:16:26.630  1036  1546 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-05 13:16:26.631  1604  1818 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-05 13:16:26.736  1819  8415 I CheckinService: Preparing to send checkin request
,08-05 13:16:26.736  1819  8415 I EventLogService: Accumulating logs since 1470395768464
,08-05 13:16:26.740  1036  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:26.744  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 13:16:26.744  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 13:16:26.744  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 13:16:26.744  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 13:16:26.744  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea1c23f added. We now have 9 listener(s)
08-05 13:16:26.744  6900  6964 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 13:16:26.744  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 13:16:26.749  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 13:16:26.753  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 13:16:26.756  6900  6964 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 13:16:26.756  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:26.756  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:26.756  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 13:16:26.756  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 13:16:26.756  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 13:16:26.756  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 13:16:26.756  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 13:16:26.757  6900  6964 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 13:16:26.758  6900  6964 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 13:16:26.760  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:26.761  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 13:16:26.761  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ceca855 added. We now have 3 listener(s)
08-05 13:16:26.762  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:26.763  1036  1707 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:26.765  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-05 13:16:26.765  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 13:16:26.765  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 13:16:26.765  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 13:16:26.765  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cbc26a added. We now have 10 listener(s)
08-05 13:16:26.765  6900  6964 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 13:16:26.766  6900  6964 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 13:16:26.766  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 13:16:26.766  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 13:16:26.766  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:26.767  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:26.767  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 13:16:26.767  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 13:16:26.767  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11201e5e removed from the list
08-05 13:16:26.767  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:26.767  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea1c23f removed from the list
08-05 13:16:26.767  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
08-05 13:16:26.767  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:26.768  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:26.768  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:26.768  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:26.769  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:26.769  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:26.769  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:26.769  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea1c23f not in the list
08-05 13:16:26.769  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:26.769  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 13:16:26.771  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:26.771  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:26.771  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:26.771  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cbc26a removed from the list
08-05 13:16:26.771  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:26.771  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:26.771  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:26.771  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 13:16:26.771  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ceca855 removed from the list
08-05 13:16:26.772  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 13:16:26.772  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfa435b added. We now have 2 listener(s)
08-05 13:16:26.774  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:26.776  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 13:16:26.776  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 13:16:26.776  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 13:16:26.776  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 13:16:26.776  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277697f8 added. We now have 9 listener(s)
08-05 13:16:26.776  6900  6964 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 13:16:26.777  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 13:16:26.779  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 13:16:26.780  8331  8331 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 13:16:26.780  8331  8331 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 13:16:26.781  1819  8415 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-05 13:16:26.784  6900  6964 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 13:16:26.784  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:26.784  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:26.784  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 13:16:26.784  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 13:16:26.784  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 13:16:26.784  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 13:16:26.784  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 13:16:26.785  6900  6964 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 13:16:26.785  6900  6964 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 13:16:26.786  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 13:16:26.786  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35db9b36 added. We now have 3 listener(s)
08-05 13:16:26.786  1036  1944 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:26.787  8331  8331 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 13:16:26.790  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:26.791  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:26.791  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 13:16:26.791  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 13:16:26.791  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 13:16:26.792  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 13:16:26.792  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198fba37 added. We now have 10 listener(s)
08-05 13:16:26.792  6900  6964 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 13:16:26.792  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 13:16:26.792  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 13:16:26.792  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 13:16:26.792  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 13:16:26.792  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 13:16:26.794  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoo,thMacAddress: Constructing...
,08-05 13:16:26.794  8280  8280 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 13:16:26.795  1036  1907 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:26.799  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 13:16:26.799  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 13:16:26.800  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 13:16:26.801  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 13:16:26.804  6900  6964 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 13:16:26.804  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 13:16:26.804  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 13:16:26.805  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 13:16:26.807  6900  6964 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 13:16:26.807  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 13:16:26.807  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 13:16:26.807  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:26.807  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:26.807  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 13:16:26.807  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 13:16:26.807  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfa435b removed from the list
08-05 13:16:26.807  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:26.807  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277697f8 removed from the list
08-05 13:16:26.807  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
08-05 13:16:26.807  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:26.808  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:26.808  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:26.809  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:26.809  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:26.809  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:26.809  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277697f8 not in the list
08-05 13:16:26.809  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:26.809  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:26.810  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:26.810  6900  6964 D BluetoothLeScanner: could not find callback wrapper
08-05 13:16:26.810  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 13:16:26.811  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:26.811  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:26.811  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198fba37 removed from the list
08-05 13:16:26.811  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:26.811  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:26.811  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 1,3:16:26.811  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 13:16:26.811  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35db9b36 removed from the list
08-05 13:16:26.811  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 13:16:26.811  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@333e34c2 added. We now have 2 listener(s)
08-05 13:16:26.812  1036  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:26.813  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 13:16:26.813  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 13:16:26.813  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 13:16:26.813  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 13:16:26.813  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@159bc2d3 added. We now have 9 listener(s)
08-05 13:16:26.813  6900  6964 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 13:16:26.816  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 13:16:26.821  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:26.890  1036  1051 I art     : Explicit concurrent mark sweep GC freed 73463(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.461ms total 75.913ms
08-05 13:16:26.892  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 13:16:26.902  6900  6964 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 13:16:26.902  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:26.902  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:26.902  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 13:16:26.902  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 13:16:26.902  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 13:16:26.902  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 13:16:26.902  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 13:16:26.904  6900  6964 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 13:16:26.904  6900  6964 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 13:16:26.904  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 13:16:26.904  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1377ed09 added. We now have 3 listener(s)
08-05 13:16:26.905  1036  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:26.908  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:26.909  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 13:16:26.909  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 13:16:26.909  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 13:16:26.909  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 13:16:26.909  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323edb0e added. We now have 10 listener(s)
08-05 13:16:26.909  6900  6964 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 13:16:26.909  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 13:16:26.910  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 13:16:26.910  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 13:16:26.910  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 13:16:26.910  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 13:16:26.910  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 13:16:26.914  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 13:16:26.914  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:26.916  8331  8331 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 13:16:26.917  8331  8331 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 13:16:26.917  1036  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:26.917  8331  8331 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 13:16:26.922  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 13:16:26.923  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 13:16:26.924  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 13:16:26.924  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-05 13:16:26.926  6900  6964 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 13:16:26.926  6900  6964 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 13:16:26.926  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 13:16:26.926  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 13:16:26.926  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:26.926  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:26.926  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 13:16:26.926  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 13:16:26.926  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@333e34c2 removed from the list
08-05 13:16:26.926  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:26.926  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@159bc2d3 removed from the list
08-05 13:16:26.926  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
08-05 13:16:26.926  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:26.927  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:26.927  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:26.927  8280  8280 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 13:16:26.927  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:26.927  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:26.927  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:26.928  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@159bc2d3 not in the list
08-05 13:16:26.928  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:26.928  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:26.928  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:26.929  6900  6964 D BluetoothLeScanner: could not find callback wrapper
08-05 13:16:26.929  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 13:16:26.929  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:26.929  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:26.929  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@323edb0e removed from the list
08-05 13:16:26.929  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:26.929  6900  6964 W org.t,haliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:26.929  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:26.929  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 13:16:26.929  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1377ed09 removed from the list
,08-05 13:16:26.930  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 13:16:26.930  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2950c5 added. We now have 2 listener(s)
08-05 13:16:26.930  1036  1944 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:26.930  8252  8252 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-05 13:16:26.933  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 13:16:26.933  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 13:16:26.933  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 13:16:26.933  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 13:16:26.933  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1919a1a added. We now have 9 listener(s)
08-05 13:16:26.933  6900  6964 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 13:16:26.933  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 13:16:26.935  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 13:16:26.936  8252  8252 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-05 13:16:26.938  6900  6964 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 13:16:26.938  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:26.938  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:26.938  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 13:16:26.938  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 13:16:26.938  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 13:16:26.938  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 13:16:26.938  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 13:16:26.939  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 13:16:26.939  6900  6964 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 13:16:26.940  6900  6964 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 13:16:26.940  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 13:16:26.940  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7bbef28 added. We now have 3 listener(s)
08-05 13:16:26.940  1036  1890 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:26.942  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:26.943  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 13:16:26.945  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 13:16:26.945  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 13:16:26.945  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 13:16:26.945  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 13:16:26.945  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ed33441 added. We now have 10 listener(s)
08-05 13:16:26.945  6900  6964 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 13:16:26.946  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 13:16:26.946  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 13:16:26.946  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 13:16:26.946  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 13:16:26.946  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 13:16:26.948  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 13:16:26.948  1036  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:26.948  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:26.952  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 13:16:26.953  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 13:16:26.954  8331  8331 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 13:16:26.954  8331  8331 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 13:16:26.954  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 13:16:26.955  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 13:16:26.955  8331  8331 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-05 13:16:26.956  6900  6964 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-05 13:16:26.957  8331  8331 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-05 13:16:26.957  8331  8331 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-05 13:16:26.958  6900  6964 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 13:16:26.958  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 13:16:26.958  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 13:16:26.958  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:26.958  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:26.958  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 13:16:26.958  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 13:16:26.958  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2950c5 removed from the list
08-05 13:16:26.958  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:26.958  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1919a1a removed from the list
08-05 13:16:26.958  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
08-05 13:16:26.958  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:26.961  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:26.961  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:26.962  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:26.962  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:26.962  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:26.962  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1919a1a not in the list
08-05 13:16:26.962  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:26.962  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:26.963  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:26.964  6900  6964 D BluetoothLeScanner: could not find callback wrapper
08-05 13:16:26.964  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 13:16:26.964  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:26.964  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:26.964  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ed33441 removed from the list
08-05 13:16:26.964  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:26.964  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.b,luetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:26.964  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:26.964  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 13:16:26.964  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7bbef28 removed from the list
08-05 13:16:26.964  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 13:16:26.964  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2074d5d4 added. We now have 2 listener(s)
08-05 13:16:26.965  8280  8280 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 13:16:26.968  1036  1907 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:26.968  8252  8252 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-05 13:16:26.970  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 13:16:26.971  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 13:16:26.971  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 13:16:26.971  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 13:16:26.971  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20ddd37d added. We now have 9 listener(s)
08-05 13:16:26.971  6900  6964 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 13:16:26.971  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 13:16:26.971  8252  8252 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-05 13:16:26.974  7004  7004 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 13:16:26.975  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 13:16:26.978  6900  6964 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 13:16:26.978  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:26.978  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:26.978  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 13:16:26.978  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 13:16:26.978  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 13:16:26.978  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 13:16:26.978  6900  6964 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 13:16:26.979  6900  6964 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 13:16:26.979  6900  6964 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 13:16:26.979  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 13:16:26.979  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2b06c3 added. We now have 3 listener(s)
08-05 13:16:26.980  1036  1890 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 13:16:26.981  7004  7004 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 13:16:26.982  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 13:16:26.982  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 13:16:26.982  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 13:16:26.982  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 13:16:26.982  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f337b40 added. We now have 10 listener(s)
,08-05 13:16:26.982  6900  6964 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 13:16:26.982  6900  6964 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 13:16:26.982  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-05 13:16:26.982  6900  6964 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 13:16:26.982  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:26.982  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:26.983  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 13:16:26.983  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 13:16:26.983  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2074d5d4 removed from the list
08-05 13:16:26.983  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:26.983  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20ddd37d removed from the list
08-05 13:16:26.983  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:26.983  6900  6964 D io.jxcore.node.ConnectivityMonitor: stop
08-05 13:16:26.983  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:26.987  8331  8331 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 13:16:26.987  8331  8331 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 13:16:26.988  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:26.988  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:26.988  8331  8331 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-05 13:16:26.988  8331  8331 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-05 13:16:26.989  8331  8331 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-05 13:16:26.990  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:26.990  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:26.990  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:26.990  6900  6964 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20ddd37d not in the list
08-05 13:16:26.990  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:26.990  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:26.990  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 13:16:26.991  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 13:16:26.991  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 13:16:26.991  6900  6964 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 13:16:26.991  6900  6964 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f337b40 removed from the list
08-05 13:16:26.991  6900  6964 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 13:16:26.,991  6900  6964 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 13:16:26.991  6900  6964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 13:16:26.991  6900  6964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 13:16:26.991  6900  6964 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2b06c3 removed from the list
08-05 13:16:26.992  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-05 13:16:26.992  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-05 13:16:26.992  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-05 13:16:26.992  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 13:16:26.992  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-05 13:16:26.992  6900  6964 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-05 13:16:26.997  8280  8280 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 13:16:26.999  8331  8331 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-05 13:16:27.001  6900  8430 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 921, name: My test thread name)
08-05 13:16:27.001  6900  8430 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 921, thread name: My test thread name)
08-05 13:16:27.002  6900  8430 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 921, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-05 13:16:27.003  8331  8331 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-05 13:16:27.004  6900  8431 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 923, name: My test thread name)
08-05 13:16:27.004  6900  8431 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 923, thread name: My test thread name)
08-05 13:16:27.005  6900  8431 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 923, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-05 13:16:27.007  6900  6964 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-05 13:16:27.007  6900  6964 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-05 13:16:27.007  6900  6964 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-05 13:16:27.007  6900  6964 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-05 13:16:27.007  6900  6964 D com.test.thalitest.ThaliTestRunner: Total duration: 24153 ms
08-05 13:16:27.007  8331  8331 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-05 13:16:27.008  6900  6964 I jxcore-log: Total number of executed tests:  80
08-05 13:16:27.008  6900  6964 I jxcore-log: 
08-05 13:16:27.009  6900  6964 I jxcore-log: Number of passed tests:  80
08-05 13:16:27.009  6900  6964 I jxcore-log: 
08-05 13:16:27.009  6900  6964 I jxcore-log: Number of failed tests:  0
08-05 13:16:27.009  6900  6964 I jxcore-log: 
08-05 13:16:27.009  6900  6964 I jxcore-log: Number of ignored tests:  0
08-05 13:16:27.009  6900  6964 I jxcore-log: 
08-05 13:16:27.009  6900  6964 I jxcore-log: Total duration:  24153
08-05 13:16:27.009  6900  6964 I jxcore-log: 
,08-05 13:16:27.012  6900  6964 I jxcore-log: Unit Test app is loaded
08-05 13:16:27.012  6900  6964 I jxcore-log: 
08-05 13:16:27.020  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 13:16:27.020  6900  6964 I jxcore-log: 
08-05 13:16:27.024  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 13:16:27.024  6900  6964 I jxcore-log: 
08-05 13:16:27.025  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 13:16:27.025  6900  6964 I jxcore-log: 
08-05 13:16:27.028  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 13:16:27.028  6900  6964 I jxcore-log: 
08-05 13:16:27.028  8331  8331 D LgDataFeature: LgDataFeature() Constructor: none
08-05 13:16:27.028  8331  8331 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 13:16:27.029  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 13:16:27.029  6900  6964 I jxcore-log: 
,08-05 13:16:27.030  6900  6900 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-05 13:16:27.030  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 13:16:27.030  6900  6964 I jxcore-log: 
08-05 13:16:27.033  8331  8331 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-05 13:16:27.033  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 13:16:27.033  6900  6964 I jxcore-log: 
08-05 13:16:27.034  8331  8331 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-05 13:16:27.034  8331  8331 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-05 13:16:27.034  8331  8331 V SoundPool: doLoad: loading sample sampleID=1
08-05 13:16:27.034  8331  8434 V SoundPool: Start decode
08-05 13:16:27.034  8331  8434 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-05 13:16:27.035   332  2181 V MediaPlayerService: decode(23, 10857164, 17813)
08-05 13:16:27.035   332  2181 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-05 13:16:27.035   332  2181 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-05 13:16:27.035   332  2181 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-05 13:16:27.035   332  2181 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-05 13:16:27.035   332  2181 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-05 13:16:27.035   332  2181 V MediaPlayerService: player type = 3
08-05 13:16:27.035   332  2181 V AwesomePlayer: AwesomePlayer create()
08-05 13:16:27.035   332  2181 V AwesomePlayer: reset_l() 
08-05 13:16:27.035   332  2181 V AwesomePlayer: cancelPlayerEvents
08-05 13:16:27.035   332  2181 V AwesomePlayer: setAudioSink() 
08-05 13:16:27.035   332  2181 V AwesomePlayer: reset_l() 
08-05 13:16:27.035   332  2181 V AudioCache: notify(0xb1432500, 8, 0, 0)
08-05 13:16:27.035   332  2181 V AudioCache: ignored
08-05 13:16:27.035   332  2181 V AwesomePlayer: cancelPlayerEvents
08-05 13:16:27.035   332  2181 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-05 13:16:27.035   332  2181 V AwesomePlayer: setDataSource_l dataSource
08-05 13:16:27.035   332  2181 V LGParserOSAL: SniffLGParser start
08-05 13:16:27.035   332  2181 V LGParserOSAL: MainType:5, SubType=0
08-05 13:16:27.035   332  2181 V LGParserOSAL: #### check Mime : application/ogg
08-05 13:16:27.035   332  2181 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-05 13:16:27.035   332  2181 E MediaExtractor: Use LGExtractor :application/ogg 
08-05 13:16:27.035  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 13:16:27.035  6900  6964 I jxcore-log: 
08-05 13:16:27.036  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 13:16:27.036  6900  6964 I jxcore-log: 
08-05 13:16:27.037  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 13:16:27.037  6900  6964 I jxcore-log: 
08-05 13:16:27.038  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-05 13:16:27.038  6900  6964 I jxcore-log: 
08-05 13:16:27.039  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 13:16:27.039  6900  6964 I jxcore-log: 
08-05 13:16:27.041  6900  6964 I jxcore-log: DEBUG thaliMobil,eNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 13:16:27.041  6900  6964 I jxcore-log: 
08-05 13:16:27.041  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 13:16:27.041  6900  6964 I jxcore-log: 
08-05 13:16:27.042  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 13:16:27.042  6900  6964 I jxcore-log: 
08-05 13:16:27.043  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 13:16:27.043  6900  6964 I jxcore-log: 
08-05 13:16:27.044  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 13:16:27.044  6900  6964 I jxcore-log: 
,08-05 13:16:27.045  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 13:16:27.045  6900  6964 I jxcore-log: 
08-05 13:16:27.046  8331  8331 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-05 13:16:27.046  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 13:16:27.046  6900  6964 I jxcore-log: 
08-05 13:16:27.046  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 13:16:27.046  6900  6964 I jxcore-log: 
08-05 13:16:27.047  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 13:16:27.047  6900  6964 I jxcore-log: 
08-05 13:16:27.048  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 13:16:27.048  6900  6964 I jxcore-log: 
08-05 13:16:27.049  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 13:16:27.049  6900  6964 I jxcore-log: 
08-05 13:16:27.049  8331  8331 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-05 13:16:27.050  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 13:16:27.050  6900  6964 I jxcore-log: 
08-05 13:16:27.050  8331  8331 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 13:16:27.050  8331  8331 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-05 13:16:27.050  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 13:16:27.050  6900  6964 I jxcore-log: 
08-05 13:16:27.051  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 13:16:27.051  6900  6964 I jxcore-log: 
08-05 13:16:27.052  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 13:16:27.052  6900  6964 I jxcore-log: 
08-05 13:16:27.053  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 13:16:27.053  6900  6964 I jxcore-log: 
08-05 13:16:27.056  6900  6964 I jxcore-log: My device name is: LGE-LG-D855
08-05 13:16:27.056  6900  6964 I jxcore-log: 
08-05 13:16:27.057   332  2181 V LGParserOSAL: supported mime: application/ogg
08-05 13:16:27.057   332  2181 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-05 13:16:27.057   332  2181 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-05 13:16:27.057  6900  6964 I jxcore-log: WARN testUtils: myNameCallback not set!
08-05 13:16:27.057  6900  6964 I jxcore-log: 
08-05 13:16:27.057   332  2181 V AwesomePlayer: mBitrate = -1 bits/sec
08-05 13:16:27.057   332  2181 V AwesomePlayer: AudioTrack Setting
08-05 13:16:27.057   332  2181 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-05 13:16:27.057   332  2181 V AwesomePlayer: setAudioSource() 
08-05 13:16:27.057   332  2181 V MediaPlayerService: prepare
08-05 13:16:27.057   332  2181 V AwesomePlayer: prepare,Async_l() 
08-05 13:16:27.057   332  2181 V MediaPlayerService: wait for prepare
08-05 13:16:27.057   332  8435 V AwesomePlayer: onPrepareAsyncEvent() 
08-05 13:16:27.057   332  8435 V AwesomePlayer: initAudioDecoder() 
08-05 13:16:27.057   332  8435 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-05 13:16:27.057   332  8435 V AudioSystem: isOffloadSupported()
08-05 13:16:27.057   332  8435 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-05 13:16:27.057   332  8435 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-05 13:16:27.057   332  8435 I AudioFlinger: isAudioPlaybackHookOn() false
08-05 13:16:27.057   332  8435 V AwesomePlayer: getUseOffload() = 0 
08-05 13:16:27.057   332  8435 V OMXCodec: OMXCodec::Create
08-05 13:16:27.057   332  8435 V OMXCodec: findMatchingCodecs()
08-05 13:16:27.057   332  8435 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-05 13:16:27.057   332  8435 V OMXCodec: matchingCodecs.size()=1
08-05 13:16:27.057   332  8435 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-05 13:16:27.058  8331  8331 V LGMDMManager: Create singleton instance
08-05 13:16:27.059  7773  7773 D UEI.SmartControl: QS Service created
,08-05 13:16:27.060   332  8435 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-05 13:16:27.060   332  8435 V LGCodecAdapter: LG Codec Adapter start
08-05 13:16:27.060   332  8435 V OMXCodec: OMXCodec Createtor
08-05 13:16:27.060   332  8435 V OMXCodec: setComponentRole
08-05 13:16:27.060   332  8435 V OMXCodec: configureCodec protected=0
08-05 13:16:27.060   332  8435 V LGCodecAdapter: called getLGCodecSpecificData
08-05 13:16:27.060   332  8435 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-05 13:16:27.060   332  8435 V LGCodecOSAL: Called LGconfigureCodecMETA
08-05 13:16:27.060   332  8435 V LGCodecOSAL: Called LGconfigureCodecMSG
08-05 13:16:27.060   332  8435 V LGCodecOSAL: Not support LGCodec
08-05 13:16:27.060   332  8435 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-05 13:16:27.060   332  8435 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-05 13:16:27.060   332  8435 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-05 13:16:27.060   332  8435 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-05 13:16:27.060   332  8435 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-05 13:16:27.060   332  8435 V AudioSystem: isOffloadSupported()
08-05 13:16:27.060   332  8435 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-05 13:16:27.060   332  8435 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-05 13:16:27.060   332  8435 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-05 13:16:27.060   332  8435 V OMXCodec: init()
08-05 13:16:27.061   332  8435 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-05 13:16:27.061   332  8435 V OMXCodec: allocateBuffers
08-05 13:16:27.061   332  8435 V OMXCodec: allocateBuffersOnPort portIndex=0
08-05 13:16:27.061   332  8435 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-05 13:16:27.061   332  8435 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on input port
08-05 13:16:27.061   332  8435 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
08-05 13:16:27.061   332  8435 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on input port
08-05 13:16:27.061   332  8435 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on input port
08-05 13:16:27.061   332  8435 V OMXCodec: allocateBuffersOnPort portIndex=1
08-05 13:16:27.061   332  8435 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-05 13:16:27.061   332  8435 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-05 13:16:27.061   332  8435 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
08-05 13:16:27.061   332  8435 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
08-05 13:16:27.061   332  8435 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fd80 on output port
08-05 13:16:27.061   332  8435 V OMXCodec: init() mAsyncCompletion wait!!! 
08-05 13:16:27.061   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-05 13:16:27.061   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-05 13:16:27.061   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-05 13:16:27.061   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-05 13:16:27.061   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-05 13:16:27.061   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=,4
08-05 13:16:27.063   332  8435 V OMXCodec: init() mAsyncCompletion wait free! 
08-05 13:16:27.063   332  8435 V AwesomePlayer: finishAsyncPrepare_l() 
08-05 13:16:27.063   332  8435 V AudioCache: notify(0xb1432500, 5, 0, 0)
08-05 13:16:27.063   332  8435 V AudioCache: ignored
08-05 13:16:27.063   332  8435 V AudioCache: notify(0xb1432500, 1, 0, 0)
08-05 13:16:27.063   332  8435 V AudioCache: prepared
08-05 13:16:27.063   332  2181 V AudioCache: wait - success
08-05 13:16:27.063   332  2181 V MediaPlayerService: start
08-05 13:16:27.063   332  2181 V AwesomePlayer: play_l() 
08-05 13:16:27.063   332  2181 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-05 13:16:27.063   332  2181 V AwesomePlayer: createAudioPlayer_l
08-05 13:16:27.063   332  2181 V AwesomePlayer: seekAudioIfNecessary_l() 
08-05 13:16:27.063   332  2181 V AwesomePlayer: startAudioPlayer_l() 
08-05 13:16:27.063   332  2181 D AudioPlayer: start of Playback, useOffload 0
08-05 13:16:27.063   332  2181 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-05 13:16:27.063   332  2181 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-05 13:16:27.065   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-05 13:16:27.065   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-05 13:16:27.065   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-05 13:16:27.065   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-05 13:16:27.065   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-05 13:16:27.065   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-05 13:16:27.065   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048416
08-05 13:16:27.065   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 13:16:27.065   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048576
08-05 13:16:27.065  7773  7773 I UEI.SmartControl: Service initServices...
08-05 13:16:27.065   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 13:16:27.065   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048656
08-05 13:16:27.065   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 13:16:27.065   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957049216
08-05 13:16:27.065   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 13:16:27.065  7773  7773 D UEI.SmartControl: QS start get config
08-05 13:16:27.065   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-05 13:16:27.065   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-05 13:16:27.065   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-05 13:16:27.065   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-05 13:16:27.065   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-05 13:16:27.065   332  8437 V OMXCodec: allocateBuffersOnPort portIndex=1
08-05 13:16:27.065   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-05 13:16:27.066   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
08-05 13:16:27.067   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
08-05 13:16:27.067   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-05 13:16:27.067   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-05 13:16:27.068   332  8437 V OMXCodec: [OMX.google.v,orbis.decoder] PORT_ENABLED(1)
08-05 13:16:27.068   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-05 13:16:27.070   332  2181 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-05 13:16:27.070   332  2181 V AudioCache: notify(0xb1432500, 6, 0, 0)
08-05 13:16:27.070   332  2181 V AudioCache: ignored
08-05 13:16:27.070   332  2181 V MediaPlayerService: wait for playback complete
08-05 13:16:27.075   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.075   332  8438 V AudioCache: memcpy(0xaf006000, 0xb57c1000, 4096)
08-05 13:16:27.077   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.077   332  8438 V AudioCache: memcpy(0xaf007000, 0xb57c1000, 4096)
08-05 13:16:27.077   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.077   332  8438 V AudioCache: memcpy(0xaf008000, 0xb57c1000, 4096)
08-05 13:16:27.078   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.078   332  8438 V AudioCache: memcpy(0xaf009000, 0xb57c1000, 4096)
08-05 13:16:27.080   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.080   332  8438 V AudioCache: memcpy(0xaf00a000, 0xb57c1000, 4096)
08-05 13:16:27.080   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.080   332  8438 V AudioCache: memcpy(0xaf00b000, 0xb57c1000, 4096)
08-05 13:16:27.080   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.080   332  8438 V AudioCache: memcpy(0xaf00c000, 0xb57c1000, 4096)
08-05 13:16:27.080   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.080   332  8438 V AudioCache: memcpy(0xaf00d000, 0xb57c1000, 4096)
08-05 13:16:27.081   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.081   332  8438 V AudioCache: memcpy(0xaf00e000, 0xb57c1000, 4096)
08-05 13:16:27.081   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.081   332  8438 V AudioCache: memcpy(0xaf00f000, 0xb57c1000, 4096)
08-05 13:16:27.081   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.081   332  8438 V AudioCache: memcpy(0xaf010000, 0xb57c1000, 4096)
08-05 13:16:27.081   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.081   332  8438 V AudioCache: memcpy(0xaf011000, 0xb57c1000, 4096)
08-05 13:16:27.082   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.082   332  8438 V AudioCache: memcpy(0xaf012000, 0xb57c1000, 4096)
08-05 13:16:27.082   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.082   332  8438 V AudioCache: memcpy(0xaf013000, 0xb57c1000, 4096)
08-05 13:16:27.082   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.082   332  8438 V AudioCache: memcpy(0xaf014000, 0xb57c1000, 4096)
08-05 13:16:27.083   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.083   332  8438 V AudioCache: memcpy(0xaf015000, 0xb57c1000, 4096)
08-05 13:16:27.083   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.083   332  8438 V AudioCache: memcpy(0xaf016000, 0xb57c1000, 4096)
08-05 13:16:27.083   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.083   332  8438 V AudioCache: memcpy(0xaf017000, 0xb57c1000, 4096)
08-05 13:16:27.084   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.084   332  8438 V AudioCache: memcpy(0xaf018000, 0xb57c1000, 4096)
08-05 13:16:27.084   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.084   332  8438 V AudioCache: memcpy(0xaf019000, 0xb57c1000, 4096)
08-05 13:16:27.085   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.085   332  8438 V AudioCache: memcpy(0xaf01a000, 0xb57c1000, 4096)
08-05 13:16:27.085   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.085   332  8438 V AudioCache: memcpy(0xaf01b000, 0xb57c1000, 4096)
08-05 13:16:27.085   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.085   332  8438 V AudioCache: memcpy(0xaf01c000, 0xb57c1000, 4096)
08-05 13:16:27.086   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.086   332  8438 V AudioCache: memcpy(0xaf01d000, 0xb57c1000, 4096)
08-05 13:16:27.086   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.086   332  8438 V AudioCache: memcpy(0xaf01e000, 0xb57c1000, 4096)
08-05 13:16:27.086   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.086   332  8438 V AudioCache: memcpy(0xaf01f000, 0xb57c1000, 4096)
08-05 13:16:27.087   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.087   332  8438 V AudioCache: memcpy(0xaf020000, 0xb57c1000, 4096)
08-05 13:16:27.087   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.087   332  8438 V AudioCache: memcpy(0xaf021000, 0xb57c1000, 4096)
08-05 13:16:27.088   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.088   332  8438 V AudioCache: memcpy(0xaf022000, 0xb57c1000, 4096)
08-05 13:16:27.088   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.088   332  8438 V AudioCache: memcpy(0xaf023000, 0xb57c1000, 4096)
08-05 13:16:27.088   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.088   332  8438 V AudioCache: memcpy(0xaf024000, 0xb57c1000, 4096)
08-05 13:16:27.089   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.089   332  8438 V AudioCache: memcpy(0xaf025000, 0xb57c1000, 4096)
08-05 13:16:27.089   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.089   332  8438 V AudioCache: memcpy(0xaf026000, 0xb57c1000, 4096)
08-05 13:16:27.089   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.089   332  8438 V AudioCache: memcpy(0xaf027000, 0xb57c1000, 4096)
08-05 13:16:27.090   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.090   332  8438 V AudioCache: memcpy(0xaf028000, 0xb57c1000, 4096)
08-05 13:16:27.093   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.093   332  8438 V AudioCache: memcpy(0xaf029000, 0xb57c1000, 4096)
08-05 13:16:27.094   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.094   332  8438 V AudioCache: memcpy(0xaf02a000, 0xb57c1000, 4096)
08-05 13:16:27.094   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.094   332  8438 V AudioCache: memcpy(0xaf02b000, 0xb57c1000, 4096)
08-05 13:16:27.095   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.095   332  8438 V AudioCache: memcpy(0xaf02c000, 0xb57c1000, 4096)
08-05 13:16:27.095   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.095   332  8438 V AudioCache: memcpy(0xaf02d000, 0xb57c1000, 4096)
08-05 13:16:27.095   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.095   332  8438 V AudioCache: memcpy(0xaf02e000, 0xb57c1000, 4096)
08-05 13:16:27.095   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.095   332  8438 V AudioCache: memcpy(0xaf02f000, 0xb57c1000, 4096)
08-05 13:16:27.096   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.096   332  8438 V AudioCache: memcpy(0xaf030000, 0xb57c1000, 4096)
08-05 13:16:27.096   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.096   332  8438 V AudioCache: memcpy(0xaf031000, 0xb57c1000, 4096)
08-05 13:16:27.097   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.097   332  8438 V AudioCache: memcpy(0xaf032000, 0xb57c1000, 4096)
08-05 13:16:27.097   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.097   332  8438 V AudioCache: memcpy(0xaf033000, 0xb57c1000, 4096)
08-05 13:16:27.097   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.097   332  8438 V AudioCache: memcpy(0xaf034000, 0xb57c1000, 4096)
08-05 13:16:27.098   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.098   332  8438 V AudioCache: memcpy(0xaf035000, 0xb57c1000, 4096)
08-05 13:16:27.098   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.098   332  8438 V AudioCache: memcpy(0xaf036000, 0xb57c1000, 4096)
08-05 13:16:27.099   332  8438 V AudioCache: write(0xb57c1000, 4096)
08-05 13:16:27.099   332  8438 V AudioCache: memcpy(0xaf037000, 0xb57c1000, 4096)
08-05 13:16:27.099   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-05 13:16:27.099   332  8438 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-05 13:16:27.099   332  8438 V AwesomePlayer: postAudioEOS() 
08-05 13:16:27.099   332  8438 V AudioCache: write(0xb57c1000, 280)
08-05 13:16:27.099   332  8438 V AudioCache: memcpy(0xaf038000, 0xb57c1000, 280)
08-05 13:16:27.100   332  8435 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-05 13:16:27.100   332  8435 V AwesomePlayer: onStreamDone
08-05 13:16:27.100   332  8435 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-05 13:16:27.100   332  8435 V AudioCache: notify(0xb1432500, 2, 0, 0)
08-05 13:16:27.100   332  8435 V AudioCache: playback complete
08-05 13:16:27.100   332  8435 V AwesomePlayer: pause_l() 
08-05 13:16:27.100   332  8435 V AudioCache: notify(0xb1432500, 7, 0, 0)
08-05 13:16:27.100   332  8435 V AudioCache: ignored
08-05 13:16:27.100   332  8435 V AwesomePlayer: cancelPlayerEvents
08-05 13:16:27.100   332  2181 V AudioCache: wait - success
08-05 13:16:27.100   332  2181 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-05 13:16:27.100   332  8435 D AudioPlayer: Pause Playback at 1068125
08-05 13:16:27.102   332  2181 V AwesomePlayer: reset_l() 
08-05 13:16:27.102   332  2181 V AudioCache: notify(0xb1432500, 8, 0, 0)
08-05 13:16:27.103   332  2181 V AudioCache: ignored
08-05 13:16:27.103   332  2181 V AwesomePlayer: cancelPlayerEvents
08-05 13:16:27.103   332  2181 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-05 13:16:27.103   332  2181 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-05 13:16:27.103   332  2181 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-05 13:16:27.103   332  2181 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-05 13:16:27.103   332  2181 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-05 13:16:27.103   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-05 13:16:27.103   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-05 13:16:27.103   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-05 13:16:27.103   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 0
08-05 13:16:27.103   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-05 13:16:27.103   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 0
08-05 13:16:27.103   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-05 13:16:27.103   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
08-05 13:16:27.103   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-05 13:16:27.103   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 0
08-05 13:16:27.103   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-05 13:16:27.103   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-05 13:16:27.103   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
08-05 13:16:27.103   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-05 13:16:27.103   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 1
08-05 13:16:27.103   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-05 13:16:27.103   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb00 on port 1
08-05 13:16:27.103   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-05 13:16:27.103   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb50 on port 1
08-05 13:16:27.103   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 13:16:27.103   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-05 13:16:27.103   332  2181 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-05 13:16:27.103   332  2181 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-05 13:16:27.103   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-05 13:16:27.103   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-05 13:16:27.103   332  8437 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-05 13:16:27.103   332  2181 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-05 13:16:27.103   332  2181 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-05 13:16:27.103   332  2181 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-05 13:16:27.104   332  2181 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-05 13:16:27.104   332  2181 D AudioPlayer: AudioPlayer releasing audio source
08-05 13:16:27.104   332  2181 D AudioPlayer: AudioPlayer done releasing audio source
08-05 13:16:27.104   332  2181 V AwesomePlayer: reset_l() 
08-05 13:16:27.104   332  2181 V AwesomePlayer: cancelPlayerEvents
08-05 13:16:27.104   332  2181 V AwesomePlayer: ~AwesomePlayer call
08-05 13:16:27.104   332  2181 V AwesomePlayer: reset_l() 
08-05 13:16:27.104   332  2181 V AwesomePlayer: cancelPlayerEvents
08-05 13:16:27.105  8331  8434 V SoundPool: close(31)
08-05 13:16:27.105  8331  8434 V SoundPool: pointer = 0xa001f000, size = 205080, sampleRate = 48000, numChannels = 2
08-05 13:16:27.119  8331  8331 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-05 13:16:27.119  8331  8331 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-05 13:16:27.120  8331  8331 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6238
08-05 13:16:27.122  8280  8280 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 13:16:27.124  8280  8280 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 13:16:27.126  8280  8280 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 13:16:27.129  8280  8280 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 13:16:27.281  7773  7773 I UEI.SmartControl: Supports setup maps: true
,08-05 13:16:27.283  7773  7773 D UEI.SmartControl: QS start statue = true Error code = 0
08-05 13:16:27.283  7773  7773 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-05 13:16:27.283  7773  7773 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-05 13:16:27.283  7773  7773 I UEI.SmartControl: ### init IR Blaster...
08-05 13:16:27.287  7773  7773 D serial_port: Configuring serial port
08-05 13:16:27.287  7773  7773 E UEI.SmartControl: UEIBLaster setting for 616
08-05 13:16:27.287  7773  7773 I UEI.SmartControl: Setting serial record hearder size = 2
08-05 13:16:27.287  7773  7773 I UEI.SmartControl: configuring settings for MAXQ616
,08-05 13:16:27.287  7773  7773 I UEI.SmartControl: Get version...
08-05 13:16:27.306  7773  8439 D UEI.SmartControl: serial port data available: 21
,08-05 13:16:27.339  7773  7773 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-05 13:16:27.340  7773  7773 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-05 13:16:27.340  7773  7773 I UEI.SmartControl: QS saving settings...
08-05 13:16:27.341  7773  7773 D UEI.SmartControl: IR Blaster version: 25672567
,08-05 13:16:27.358  7773  8439 D UEI.SmartControl: serial port data available: 4
,08-05 13:16:27.392  7773  8442 I UEI.SmartControl: Device manager: loading config....
08-05 13:16:27.393  7773  7773 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-05 13:16:27.395  7773  8442 D UEI.SmartControl: ----------- loading internal config...
08-05 13:16:27.399  7773  7773 E UEI.SmartControl: Services init done
08-05 13:16:27.399  7773  7773 D UEI.SmartControl: QS Service init finished
08-05 13:16:27.400  7773  7773 D UEI.SmartControl: QS Service version name: 2.1.91
08-05 13:16:27.400  7773  7773 D UEI.SmartControl: QS Service version code: 201091
08-05 13:16:27.402  7773  7773 D UEI.SmartControl: Service requested: Control
08-05 13:16:27.406  7773  8442 E UEI.SmartControl: Loading SETTINGS...
08-05 13:16:27.407  7773  7773 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-05 13:16:27.409  7419  7435 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 13:16:27.409  7419  7435 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 13:16:27.409  7419  7435 I Adreno-EGL: Build Date: 12/12/14 금
08-05 13:16:27.409  7419  7435 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 13:16:27.409  7419  7435 I Adreno-EGL: Remote Branch: 
08-05 13:16:27.409  7419  7435 I Adreno-EGL: Local Patches: 
08-05 13:16:27.409  7419  7435 I Adreno-EGL: Reconstruct Branch: 
,08-05 13:16:27.411  8331  8331 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-05 13:16:27.419  7773  7773 D UEI.SmartControl: Internal service binding...
08-05 13:16:27.421  7773  7789 I UEI.SmartControl: ------ IControl API: 11
08-05 13:16:27.421  7773  7789 D UEI.SmartControl: File observer start...
08-05 13:16:27.423  7773  7789 E UEI.SmartControl: IR Port is disabled: false
08-05 13:16:27.423  7773  7789 D UEI.SmartControl: Starting file observer...
08-05 13:16:27.424  7773  7789 I UEI.SmartControl: Registering callback...
08-05 13:16:27.424  7773  7788 I UEI.SmartControl: ------ IControl API: 19
08-05 13:16:27.424  7773  7788 I UEI.SmartControl: Registering Services Ready callback...
08-05 13:16:27.427  7773  8442 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-05 13:16:27.430  7773  8441 I UEI.SmartControl: Notify AllClients services are ready: 0
08-05 13:16:27.431  8331  8346 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-05 13:16:27.431  8331  8432 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-05 13:16:27.432  8331  8432 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-05 13:16:27.432  7773  8441 D UEI.SmartControl: -----service ready thread exits
,08-05 13:16:27.444  8331  8331 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-05 13:16:27.444  8331  8331 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-05 13:16:27.445  7773  7789 I UEI.SmartControl: ------ IControl API: 8
08-05 13:16:27.447  8331  8331 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-05 13:16:27.447  8331  8331 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-05 13:16:27.447  8331  8331 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-05 13:16:27.448  8331  8331 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-05 13:16:27.449  8331  8331 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-05 13:16:27.449  8331  8331 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-05 13:16:27.450  8331  8331 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-05 13:16:27.452  8331  8331 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-05 13:16:27.452  8331  8331 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-05 13:16:27.453  8331  8331 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 13:16:27.453  8331  8331 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-05 13:16:27.454  7419  7435 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 13:16:27.454  7419  7435 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 13:16:27.454  7419  7435 I Adreno-EGL: Build Date: 12/12/14 금
08-05 13:16:27.454  7419  7435 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 13:16:27.454  7419  7435 I Adreno-EGL: Remote Branch: 
08-05 13:16:27.454  7419  7435 I Adreno-EGL: Local Patches: 
08-05 13:16:27.454  7419  7435 I Adreno-EGL: Reconstruct Branch: 
08-05 13:16:27.454  8331  8331 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-05 13:16:27.455  8331  8331 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-05 13:16:27.456  8331  8331 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-05 13:16:27.457  8331  8331 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470395787456]
08-05 13:16:27.459  8331  8331 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-05 13:16:27.479  8331  8447 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
08-05 13:16:27.483  8331  8331 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-05 13:16:27.483  8331  8331 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 13:16:27.484  8331  8331 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-05 13:16:27.484  8331  8331 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-05 13:16:27.484  8331  8331 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-05 13:16:27.484  8331  8331 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-05 13:16:27.485  8331  8331 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-05 13:16:27.496  8331  8331 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
08-05 13:16:27.497  7419  7435 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 13:16:27.497  7419  7435 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 13:16:27.497  7419  7435 I Adreno-EGL: Build Date: 12/12/14 금
08-05 13:16:27.497  7419  7435 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 13:16:27.497  7419  7435 I Adreno-EGL: Remote Branch: 
08-05 13:16:27.497  7419  7435 I Adreno-EGL: Local Patches: 
08-05 13:16:27.497  7419  7435 I Adreno-EGL: Reconstruct Branch: 
08-05 13:16:27.542   328  8453 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 13:16:27.542   328  8453 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-05 13:16:27.581   328  8453 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-05 13:16:27.753  1819  8415 I CheckinTask: Sending checkin request (7857 bytes)
,08-05 13:16:28.000  1819  8415 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-05 13:16:28.018  1819  8415 I CheckinService: active receiver: disabled
,08-05 13:16:28.039  2154  2154 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-05 13:16:28.055  2154  2154 I GCM     : GCM config loaded
,08-05 13:16:28.092   328  8464 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-05 13:16:28.095   328  8464 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-05 13:16:28.098  1036  1576 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8473 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-05 13:16:28.145   328  8464 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-05 13:16:28.163  8473  8473 D LgDataFeature: LgDataFeature() Constructor: none
08-05 13:16:28.163  8473  8473 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 13:16:28.165  8473  8473 D PhoneMonitor: Register our PhoneStateListener
08-05 13:16:28.180  8473  8473 V SetupWizard: Connected to Gservices successfully
,08-05 13:16:28.182  1036  1707 I ActivityManager: Killing 7887:com.google.android.talk/u0a72 (adj 15): empty #17
08-05 13:16:28.194  8473  8473 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-05 13:16:28.197  8473  8473 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-05 13:16:28.197  8473  8473 D TelephonyAutoProfiling: [parse] Load xml
08-05 13:16:28.200  8473  8473 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-05 13:16:28.201  8473  8473 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-05 13:16:28.201  8473  8473 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-05 13:16:28.201  8473  8473 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-05 13:16:28.201  8473  8473 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-05 13:16:28.201  8473  8473 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-05 13:16:28.201  8473  8473 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-05 13:16:28.201  8473  8473 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-05 13:16:28.201  8473  8473 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-05 13:16:28.201  8473  8473 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-05 13:16:28.201  8473  8473 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-05 13:16:28.201  8473  8473 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-05 13:16:28.201  8473  8473 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-05 13:16:28.201  8473  8473 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-05 13:16:28.201  8473  8473 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-05 13:16:28.201  8473  8473 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-05 13:16:28.201  8473  8473 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-05 13:16:28.209  8473  8473 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-05 13:16:28.298  1036  1051 W libprocessgroup: failed to open /acct/uid_10072/pid_7887/cgroup.procs: No such file or directory
,08-05 13:16:28.454  2154  8498 D GCM     : Connected
,08-05 13:16:28.465  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=79.0, 0.0, 0.0  rx=82.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1516973233] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 13:16:28.468  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=79.0, 0.0, 0.0  rx=82.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1516973236] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 13:16:28.468  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 13:16:28.477  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 13:16:28.489  2154  8498 D GCM     : Message class com.google.e.a.a.q
,08-05 13:16:28.519  1036  1540 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-05 13:16:28.550  1036  1546 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 13:16:28.554  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:28.560  8280  8280 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-05 13:16:28.563  1036  1109 D Tethering: MasterInitialState.processMessage what=3
08-05 13:16:28.566  5765  5765 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-05 13:16:28.572  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 13:16:28.572  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 13:16:28.572  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 13:16:28.572  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 13:16:28.572  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 13:16:28.572  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 13:16:28.572  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 13:16:28.572  6900  6900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 13:16:28.581  8280  8318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-05 13:16:28.584  6900  6900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 13:16:28.585  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 13:16:28.602  2154  2154 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-05 13:16:28.623  7217  7217 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-05 13:16:28.623  7217  7217 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-05 13:16:28.624  7217  7217 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 13:16:28.624  7217  7217 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-05 13:16:28.625  1036  1926 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
08-05 13:16:28.626  1036  8314 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:28.626  1036  8314 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:28.626  1036  8314 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-05 13:16:28.626  1036  8314 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-05 13:16:28.626  1036  8314 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-05 13:16:28.628  7217  7217 I AppUp4:CustModeStarterReceiver: onReceive
08-05 13:16:28.632  7217  7217 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@b619a89
08-05 13:16:28.632  7217  7217 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 13:16:28.632  7217  7217 D AppUp4:CustFacade: isPhone : true
08-05 13:16:28.632  7217  7217 D AppUp4:CustModeStarterReceiver: begin check event
08-05 13:16:28.632  7217  7217 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-05 13:16:28.637  4691  4691 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:28.638  4691  4691 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 13:16:28.639  4691  4691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-05 13:16:28.642  4691  4691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 13:16:28.646  3486  3486 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:28.648  3486  3486 V DownloadManager: DownloadService onCreate
08-05 13:16:28.653  3486  8504 I DownloadManager: in removeSpuriousFiles
,08-05 13:16:28.655  3486  8504 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-05 13:16:28.656  3486  8504 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@b98d423 on behalf of 3486
08-05 13:16:28.656  3486  8504 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-05 13:16:28.656  3486  8504 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-05 13:16:28.657  3486  8504 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-05 13:16:28.657  3486  8504 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-05 13:16:28.657  3486  8504 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-05 13:16:28.657  3486  8504 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-05 13:16:28.657  3486  8504 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-05 13:16:28.657  3486  8504 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-05 13:16:28.657  3486  8504 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-05 13:16:28.657  3486  8504 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-05 13:16:28.658  4691  8507 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:28.658  4691  8503 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 13:16:28.658  4691  8507 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 13:16:28.658  3486  8504 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-05 13:16:28.659  3486  8504 I DownloadManager: in trimDatabase
08-05 13:16:28.659  3486  8504 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-05 13:16:28.660  3486  8504 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@36c72d20 on behalf of 3486
08-05 13:16:28.661  4691  8503 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-05 13:16:28.669  1036  8314 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Aug 2016 11:16:28 GMT], X-Android-Received-Millis=[1470395788668], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470395788627]}
08-05 13:16:28.669  1036  8314 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-05 13:16:28.669  1036  8314 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-05 13:16:28.670  1036  1546 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-05 13:16:28.670  1036  1546 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-05 13:16:28.670  1036  1546 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkU,pBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 13:16:28.670  1036  1546 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 13:16:28.670  1036  1546 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-05 13:16:28.670  1036  1546 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-05 13:16:28.670  1036  1546 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-05 13:16:28.670  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 13:16:28.670  1036  1546 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 13:16:28.670  1036  1546 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-05 13:16:28.673  1604  1818 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-05 13:16:28.694  1036  1908 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8514 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-05 13:16:28.696  3486  3486 V DownloadManager: DownloadService onStartCommand
08-05 13:16:28.698  4691  8503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-05 13:16:28.698  3486  8505 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-05 13:16:28.700  3486  8505 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2f9a8f7f on behalf of 3486
08-05 13:16:28.700  4691  4691 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-05 13:16:28.701  4691  4691 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-05 13:16:28.701  4691  4691 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-05 13:16:28.702  4691  4691 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-05 13:16:28.703  3486  8505 V DownloadManager: processing inserted download 1
08-05 13:16:28.704  4691  4691 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-05 13:16:28.707  3486  8505 V DownloadManager: processing inserted download 4
08-05 13:16:28.708  3486  8505 V DownloadManager: processing inserted download 7
,08-05 13:16:28.709  3486  8505 V DownloadManager: processing inserted download 8
08-05 13:16:28.710  3486  8505 V DownloadManager: processing inserted download 9
08-05 13:16:28.711  3486  8505 V DownloadManager: processing inserted download 10
08-05 13:16:28.712  3486  8505 V DownloadManager: processing inserted download 11
08-05 13:16:28.713  3486  8505 V DownloadManager: processing inserted download 12
08-05 13:16:28.715  3486  8505 V DownloadManager: processing inserted download 13
08-05 13:16:28.716  3486  8505 V DownloadManager: processing inserted download 14
08-05 13:16:28.717  3486  8505 V DownloadManager: processing inserted download 16
08-05 13:16:28.719  3486  3486 V DownloadManager: DownloadService onDestroy
,08-05 13:16:28.741  8514  8514 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 13:16:28.741  8514  8514 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 13:16:28.742  8514  8514 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 13:16:28.743  8514  8514 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 13:16:28.801  8514  8514 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-05 13:16:28.810  8514  8514 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-05 13:16:28.860  8514  8514 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-05 13:16:28.892  8514  8514 D LgDataFeature: LgDataFeature() Constructor: none
08-05 13:16:28.893  8514  8514 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 13:16:29.014  8514  8514 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-05 13:16:29.058  8514  8514 I HubEmail: JNI_OnLoad()
08-05 13:16:29.058  8514  8514 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 13:16:29.058  8514  8514 I HubEmail: registerNatives()
08-05 13:16:29.058  8514  8514 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 13:16:29.058  8514  8514 I HubEmail: registerNativeMethods()
08-05 13:16:29.058  8514  8514 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 13:16:29.058  8514  8514 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-05 13:16:29.066  3386  3386 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 13:16:29.066  3386  3386 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-05 13:16:29.066  3386  3386 I LgeMiscReceiver: networkInfo.isConnected() = true
08-05 13:16:29.066  3386  3386 D PhoneState: setPdpRejectCasuse : false
08-05 13:16:29.071  8473  8473 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-05 13:16:29.072  8473  8473 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-05 13:16:29.079  8514  8543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 13:16:29.094   328  8545 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 13:16:29.094   328  8545 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
08-05 13:16:29.121  1036  1052 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8546 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-05 13:16:29.132   328  8545 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-05 13:16:29.252  8229  8541 V FormManager: There are no updated forms. The schedule will be deleted.
,08-05 13:16:29.259  8229  8541 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-05 13:16:29.287  1036  1052 I ActivityManager: Killing 7937:com.android.contacts/u0a19 (adj 15): empty #17
,08-05 13:16:29.416  1036  1926 W libprocessgroup: failed to open /acct/uid_10019/pid_7937/cgroup.procs: No such file or directory
,08-05 13:16:29.503  1036  1999 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8570 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-05 13:16:29.504  1036  1999 I ActivityManager: Killing 7958:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-05 13:16:29.635  1036  1707 W libprocessgroup: failed to open /acct/uid_10027/pid_7958/cgroup.procs: No such file or directory
,08-05 13:16:29.736  1036  1729 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8587 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 13:16:29.740  1036  1729 I ActivityManager: Killing 8038:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-05 13:16:29.743   328  8596 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 13:16:29.743   328  8596 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
08-05 13:16:29.775   328  8596 D libc-netbsd: res_queryN name = www.google.com succeed
,08-05 13:16:29.780   328  8609 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 13:16:29.781   328  8609 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-05 13:16:29.781   328  8609 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-05 13:16:29.825  1036  1999 W libprocessgroup: failed to open /acct/uid_10080/pid_8038/cgroup.procs: No such file or directory
,08-05 13:16:29.864  1036  1541 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-05 13:16:29.879  8587  8587 I art     : Almond Protected OAT
,08-05 13:16:29.937  8587  8587 D WeatherApplication: removeAccount
08-05 13:16:29.938  8587  8587 D WeatherApplication: Account.length = 0
08-05 13:16:29.938  8587  8587 E WeatherApplication: OPERATOR:OPEN
,08-05 13:16:29.943  8587  8587 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:16:29
08-05 13:16:29.946  8587  8587 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 13:16:29.946  8587  8587 D Weather.Utils: 2 : All the weather widget is gone.
08-05 13:16:29.948  8587  8587 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 13:16:29.950  8587  8587 D WeatherAncestor: connectivity changed - connection : true
08-05 13:16:29.951  8587  8587 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-05 13:16:29.959  8587  8587 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 13:16:29.959  8587  8587 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 13:16:29.959  8587  8587 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-05 13:16:29.978  8587  8587 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 13:16:29.978  8587  8587 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:16:29
,08-05 13:16:30.021  1036  2035 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8611 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 13:16:30.022  1036  2035 I ActivityManager: Killing 7983:com.android.vending/u0a44 (adj 15): empty #17
,08-05 13:16:30.110  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-05 13:16:30.110  6900  6964 I jxcore-log: 
,08-05 13:16:30.125  1036  1981 W libprocessgroup: failed to open /acct/uid_10044/pid_7983/cgroup.procs: No such file or directory
,08-05 13:16:30.231   278   323 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-05 13:16:30.232   278   323 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-05 13:16:30.232   278   323 W Vold    : Returning OperationFailed - no handler for errno 0
,08-05 13:16:30.233  8611  8629 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-05 13:16:30.235  1036  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1934c80 type 2 when 360588 com.google.android.gms} when 360588
08-05 13:16:30.235   278   323 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 13:16:30.235   278   323 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-05 13:16:30.235   278   323 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 13:16:30.236  8611  8629 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-05 13:16:30.254   278   323 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 13:16:30.255   278   323 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-05 13:16:30.255   278   323 W Vold    : Returning OperationFailed - no handler for errno 0
,08-05 13:16:30.256  8611  8631 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-05 13:16:30.266   278   323 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 13:16:30.266   278   323 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-05 13:16:30.266   278   323 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 13:16:30.266  8611  8631 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-05 13:16:30.461  8611  8611 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-05 13:16:30.474  8611  8611 I LibraryLoader: Loading: webviewchromium
,08-05 13:16:30.477  8611  8611 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 839-843)
08-05 13:16:30.477  8611  8611 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 13:16:30.485  8611  8611 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {56e35d8}
,08-05 13:16:30.491  8611  8611 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 13:16:30.492  8611  8611 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-05 13:16:30.511  8611  8611 I BrowserStartupController: Initializing chromium process, renderers=0
,08-05 13:16:30.512  8611  8611 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 13:16:30.523  8611  8611 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-05 13:16:30.526  8611  8611 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-05 13:16:30.526  8611  8611 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-05 13:16:30.528   332  1387 V AudioPolicyService: registerClient() client 0xb0410020, uid 10093
08-05 13:16:30.529  8611  8653 W AudioManagerAndroid: Requires BLUETOOTH permission
08-05 13:16:30.546  8611  8611 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 13:16:30.546  8611  8611 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 13:16:30.546  8611  8611 I Adreno-EGL: Build Date: 12/12/14 금
08-05 13:16:30.546  8611  8611 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 13:16:30.546  8611  8611 I Adreno-EGL: Remote Branch: 
08-05 13:16:30.546  8611  8611 I Adreno-EGL: Local Patches: 
08-05 13:16:30.546  8611  8611 I Adreno-EGL: Reconstruct Branch: 
,08-05 13:16:30.636  8611  8611 I NSApplication: Starting up...
,08-05 13:16:30.670  1036  1052 I ActivityManager: Killing 7640:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-05 13:16:30.754  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-05 13:16:30.754  6900  6964 I jxcore-log: 
,08-05 13:16:30.760  1036  1907 W libprocessgroup: failed to open /acct/uid_10037/pid_7640/cgroup.procs: No such file or directory
08-05 13:16:30.777   328  8668 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 13:16:30.777   328  8668 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-05 13:16:30.778   328  8668 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-05 13:16:30.779  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-05 13:16:30.779  6900  6964 I jxcore-log: 
,08-05 13:16:31.103  2154  8669 D GCM     : Connected
,08-05 13:16:31.141  2154  8669 D GCM     : Message class com.google.e.a.a.q
,08-05 13:16:31.409  7858  8106 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-05 13:16:31.411  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 13:16:31.412  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:31.412  1036  1545 D WifiController: battery changed pluggedType: 2
08-05 13:16:31.412  1946  2101 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-05 13:16:31.412  1946  2101 D LEDHandler: Battery Level Remaining: 100%
08-05 13:16:31.412  1946  2101 D LEDHandler: Battery Temp: 290, mChargingStatus=5, mChargingStop=false
08-05 13:16:31.424  1604  1604 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-05 13:16:31.424  1604  1604 I [SystemUI]LGPowerUI: On Skip Timer : true
08-05 13:16:31.424  1604  1604 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
08-05 13:16:31.424  1604  1604 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-05 13:16:31.430  1604  1604 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-05 13:16:31.431  8371  8371 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-05 13:16:31.482  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=55.0, 0.0, 0.0  rx=53.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1516976250] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 13:16:31.483  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=55.0, 0.0, 0.0  rx=53.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1516976251] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 13:16:31.483  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 13:16:32.265  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-05 13:16:32.265  6900  6964 I jxcore-log: 
,08-05 13:16:32.392  7773  8443 D UEI.SmartControl: Internal timer expired: 2
08-05 13:16:32.392  7773  8443 D UEI.SmartControl: unbind internal service
,08-05 13:16:32.443  7773  8440 D serial_port: close(fd = 24)
,08-05 13:16:32.453  7773  8440 I UEI.SmartControl: Serial port is closed.
,08-05 13:16:32.491  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-05 13:16:32.491  6900  6964 I jxcore-log: 
,08-05 13:16:32.496  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-05 13:16:32.496  6900  6964 I jxcore-log: 
,08-05 13:16:32.512  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-05 13:16:32.512  6900  6964 I jxcore-log: 
,08-05 13:16:32.516  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-05 13:16:32.516  6900  6964 I jxcore-log: 
08-05 13:16:32.542  1036  1576 I ActivityManager: Killing 7060:com.lge.settings.easy/1000 (adj 15): empty #17
,08-05 13:16:32.625  1036  2036 W libprocessgroup: failed to open /acct/uid_1000/pid_7060/cgroup.procs: No such file or directory
,08-05 13:16:33.179  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-05 13:16:33.179  6900  6964 I jxcore-log: 
,08-05 13:16:33.190  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-05 13:16:33.190  6900  6964 I jxcore-log: 
08-05 13:16:33.198  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-05 13:16:33.198  6900  6964 I jxcore-log: 
,08-05 13:16:33.204  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-05 13:16:33.204  6900  6964 I jxcore-log: 
08-05 13:16:33.251  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-05 13:16:33.251  6900  6964 I jxcore-log: 
,08-05 13:16:33.304  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-05 13:16:33.304  6900  6964 I jxcore-log: 
,08-05 13:16:33.313  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-05 13:16:33.313  6900  6964 I jxcore-log: 
,08-05 13:16:33.476  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-05 13:16:33.476  6900  6964 I jxcore-log: 
,08-05 13:16:33.502  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-05 13:16:33.502  6900  6964 I jxcore-log: 
,08-05 13:16:33.507  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-05 13:16:33.507  6900  6964 I jxcore-log: 
,08-05 13:16:33.512  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-05 13:16:33.512  6900  6964 I jxcore-log: 
,08-05 13:16:33.530  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-05 13:16:33.530  6900  6964 I jxcore-log: 
,08-05 13:16:33.612  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-05 13:16:33.612  6900  6964 I jxcore-log: 
,08-05 13:16:33.624  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-05 13:16:33.624  6900  6964 I jxcore-log: 
,08-05 13:16:33.653  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-05 13:16:33.653  6900  6964 I jxcore-log: 
,08-05 13:16:33.667  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-05 13:16:33.667  6900  6964 I jxcore-log: 
,08-05 13:16:33.685  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-05 13:16:33.685  6900  6964 I jxcore-log: 
,08-05 13:16:33.719  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-05 13:16:33.719  6900  6964 I jxcore-log: 
,08-05 13:16:33.725  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-05 13:16:33.725  6900  6964 I jxcore-log: 
08-05 13:16:33.927  6900  6964 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-05 13:16:33.927  6900  6964 I jxcore-log: 
,08-05 13:16:33.936  6900  6964 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
08-05 13:16:33.937  6900  6964 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-05 13:16:33.937  6900  6964 I jxcore-log: 
08-05 13:16:33.998  6900  6964 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 13:16:33.998  6900  6964 I jxcore-log: 
,08-05 13:16:34.500  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=40.0, 0.0, 0.0  rx=36.2 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1516979268] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 13:16:34.503  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=40.0, 0.0, 0.0  rx=36.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1516979271] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 13:16:34.503  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 13:16:35.292  8611  8632 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-05 13:16:36.817  1604  1604 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-05 13:16:36.908  1036  1093 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8686 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-05 13:16:36.914  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-05 13:16:36.915  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-05 13:16:36.945  2037  2037 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-05 13:16:36.956  1036  1036 D administrator: Handling package changes for user 0
08-05 13:16:36.968  1036  1390 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-05 13:16:36.974  2037  2037 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 13:16:36.992  8686  8686 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-05 13:16:37.083  8686  8686 D LgDataFeature: LgDataFeature() Constructor: none
08-05 13:16:37.083  8686  8686 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 13:16:37.086  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-05 13:16:37.086  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-05 13:16:37.156  1036  1092 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 13:16:37.177  1036  1092 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-05 13:16:37.190  2037  2037 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-05 13:16:37.191  2508  2508 V GmsNetworkLocationProvi: DISABLE
08-05 13:16:37.192  8686  8729 I Babel   : MmsConfig: mnc/mcc: 0/0
08-05 13:16:37.192  8686  8729 I Babel   : MmsConfig.loadMmsSettings
08-05 13:16:37.196  8686  8729 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-05 13:16:37.196  8686  8729 I Babel   : MmsConfig.loadFromDatabase
,08-05 13:16:37.212  8686  8729 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-05 13:16:37.212  8686  8729 I Babel   : MmsConfig.loadFromResources
08-05 13:16:37.216  8686  8729 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-05 13:16:37.216  8686  8729 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-05 13:16:37.231  2154  2170 I art     : Explicit concurrent mark sweep GC freed 7462(467KB) AllocSpace objects, 4(64KB) LOS objects, 52% free, 29MB/61MB, paused 1.081ms total 27.569ms
08-05 13:16:37.238  8686  8727 W AudioCapabilities: Unsupported mime audio/evrc
08-05 13:16:37.238  8686  8686 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 13:16:37.241  8686  8727 W AudioCapabilities: Unsupported mime audio/qcelp
08-05 13:16:37.245  2508  2508 E GCoreFlp: Bound FusedProviderService with LocationManager
08-05 13:16:37.246  8686  8727 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-05 13:16:37.265  8686  8727 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-05 13:16:37.266  8686  8727 W AudioCapabilities: Unsupported mime audio/qcelp
08-05 13:16:37.267  1819  8733 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-05 13:16:37.267  1819  8733 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-05 13:16:37.267  8686  8727 W AudioCapabilities: Unsupported mime audio/evrc
,08-05 13:16:37.269  7217  7217 I AppUp4:CustModeStarterReceiver: onReceive
08-05 13:16:37.277  7217  7217 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@b619a89
08-05 13:16:37.277  7217  7217 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 13:16:37.277  7217  7217 D AppUp4:CustFacade: isPhone : true
08-05 13:16:37.277  7217  7217 D AppUp4:CustModeStarterReceiver: begin check event
08-05 13:16:37.277  7217  7217 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-05 13:16:37.282  1819  5143 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-05 13:16:37.290  8686  8727 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-05 13:16:37.294  8686  8727 W VideoCapabilities: Unsupported mime video/divx
,08-05 13:16:37.296  8686  8727 W VideoCapabilities: Unsupported mime video/divx311
08-05 13:16:37.298  8686  8727 W VideoCapabilities: Unsupported mime video/divx4
08-05 13:16:37.302  8686  8727 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-05 13:16:37.305  1036  1926 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8736 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-05 13:16:37.307  1036  1092 D LocationProviderProxy: applying state to connected service
08-05 13:16:37.309  1036  1576 I ActivityManager: Killing 8371:com.lge.bnr/1000 (adj 15): empty #17
,08-05 13:16:37.327  8686  8727 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-05 13:16:37.330  8686  8727 W AudioCapabilities: Unsupported mime audio/eac3
08-05 13:16:37.331  8686  8727 W AudioCapabilities: Unsupported mime audio/ac3
08-05 13:16:37.331  8686  8727 W AudioCapabilities: Unsupported mime audio/g726
08-05 13:16:37.332  8686  8727 W AudioCapabilities: Unsupported mime audio/wma-voice
08-05 13:16:37.333  8686  8727 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-05 13:16:37.333  8686  8727 W AudioCapabilities: Unsupported mime audio/adpcm
08-05 13:16:37.335  8686  8727 W VideoCapabilities: Unsupported mime video/theora
08-05 13:16:37.336  8686  8727 W VideoCapabilities: Unsupported mime video/mjpg
08-05 13:16:37.364  1036  1707 W libprocessgroup: failed to open /acct/uid_1000/pid_8371/cgroup.procs: No such file or directory
,08-05 13:16:37.380  8736  8736 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 13:16:37.380  8736  8736 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 13:16:37.380  8736  8736 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-05 13:16:37.381  8736  8736 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-05 13:16:37.381  8736  8736 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-05 13:16:37.430  8736  8736 I SystemConfig: BUILD Country: EU
,08-05 13:16:37.431  8736  8736 I SystemConfig: BUILD Operator: OPEN
,08-05 13:16:37.527  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=25.0, 0.0, 0.0  rx=21.6 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1516982295] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 13:16:37.529  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=25.0, 0.0, 0.0  rx=21.6 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1516982297] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 13:16:37.530  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 13:16:37.560  1036  2036 I art     : Explicit concurrent mark sweep GC freed 32810(1702KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.350ms total 96.624ms
,08-05 13:16:37.579  1036  1890 I ActivityManager: Killing 8252:com.lge.sync/1000 (adj 15): empty #17
,08-05 13:16:37.647  1036  2035 W libprocessgroup: failed to open /acct/uid_1000/pid_8252/cgroup.procs: No such file or directory
,08-05 13:16:37.651  8736  8755 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
,08-05 13:16:37.651  8736  8755 I SystemConfig: existFile = false
08-05 13:16:37.651  8736  8755 I SystemConfig: canReadFile = false
08-05 13:16:37.651  8736  8755 I SystemConfig: systemFeature RCS result false
08-05 13:16:37.651  8736  8755 D SystemConfig: refreshRcsSupport() :false
08-05 13:16:37.692  1036  1890 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8757 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-05 13:16:37.737  8757  8757 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 13:16:37.737  8757  8757 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-05 13:16:37.738  8757  8757 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-05 13:16:37.739  8757  8757 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 13:16:37.812  8757  8757 I AppConfig: Total System Memory = 2995761152
,08-05 13:16:37.828  8757  8757 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-05 13:16:37.932  1036  1999 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8776 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 13:16:37.933  1036  1999 I ActivityManager: Killing 7004:com.android.settings/1000 (adj 15): empty #17
,08-05 13:16:37.956   354   354 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 515us total 21.811ms
,08-05 13:16:37.978   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 412us total 20.982ms
,08-05 13:16:37.997   354   354 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 365us total 19.070ms
,08-05 13:16:38.005  1036  1926 W libprocessgroup: failed to open /acct/uid_1000/pid_7004/cgroup.procs: No such file or directory
,08-05 13:16:38.213  8776  8776 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-05 13:16:38.315  8776  8776 D LgDataFeature: LgDataFeature() Constructor: none
,08-05 13:16:38.315  8776  8776 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 13:16:38.377  8776  8776 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-05 13:16:38.401  8776  8776 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-05 13:16:38.402  8776  8776 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-05 13:16:38.421  8776  8776 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-05 13:16:38.422  8776  8776 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-05 13:16:38.451  1036  1052 I ActivityManager: Killing 7773:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-05 13:16:38.477  8331  8331 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-05 13:16:38.477  8331  8331 W System.err: android.os.DeadObjectException
08-05 13:16:38.478  8331  8331 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 13:16:38.478  8331  8331 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-05 13:16:38.478  8331  8331 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-05 13:16:38.478  8331  8331 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-05 13:16:38.478  8331  8331 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-05 13:16:38.478  8331  8331 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-05 13:16:38.478  8331  8331 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 13:16:38.478  8331  8331 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 13:16:38.478  8331  8331 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 13:16:38.478  8331  8331 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 13:16:38.478  8331  8331 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 13:16:38.478  8331  8331 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 13:16:38.478  8331  8331 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 13:16:38.478  8331  8331 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 13:16:38.479  8331  8331 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-05 13:16:38.479  8331  8331 W System.err: android.os.DeadObjectException
08-05 13:16:38.479  8331  8331 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 13:16:38.479  8331  8331 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-05 13:16:38.479  8331  8331 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-05 13:16:38.479  8331  8331 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-05 13:16:38.479  8331  8331 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-05 13:16:38.479  8331  8331 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-05 13:16:38.479  8331  8331 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 13:16:38.480  8331  8331 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 13:16:38.480  8331  8331 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 13:16:38.480  8331  8331 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 13:16:38.480  8331  8331 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 13:16:38.480  8331  8331 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 13:16:38.480  8331  8331 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 13:16:38.480  8331  8331 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 13:16:38.480  8331  8331 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-05 13:16:38.480  8331  8331 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-05 13:16:38.696  1036  1729 W libprocessgroup: failed to open /acct/uid_1000/pid_7773/cgroup.procs: No such file or directory
,08-05 13:16:38.697  1036  1729 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-05 13:16:38.722  1604  1604 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-05 13:16:38.722  1604  1604 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-05 13:16:38.727  8331  8331 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-05 13:16:38.727  8331  8331 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-05 13:16:38.754  4947  8822 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-05 13:16:38.788  1036  1926 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8823 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-05 13:16:38.829  8331  8331 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-05 13:16:38.851  3486  3502 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-05 13:16:38.857  3486  3502 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@20f15795 on behalf of 8776
08-05 13:16:38.887  1036  1981 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8851 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-05 13:16:38.929  8776  8776 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-05 13:16:38.943  8776  8776 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-05 13:16:38.966  8823  8823 D UEI.SmartControl: Quickset Services start...
,08-05 13:16:38.969  8823  8823 I UEI.SmartControl: Manufacture = LGE
08-05 13:16:38.969  8823  8823 D UEI.SmartControl: Id = LGNevo
08-05 13:16:38.971  8823  8823 D UEI.SmartControl: File observer start...
08-05 13:16:38.972  8823  8823 E UEI.SmartControl: IR Port is disabled: false
08-05 13:16:38.972  8823  8823 D UEI.SmartControl: Starting file observer...
08-05 13:16:38.972  8823  8823 D UEI.SmartControl: Extracting JNI libs...
08-05 13:16:38.973  8823  8823 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-05 13:16:38.974  8851  8851 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-05 13:16:38.994  8851  8851 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-05 13:16:38.994  8851  8851 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-05 13:16:38.994  8851  8851 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-05 13:16:38.994  8851  8851 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-05 13:16:38.994  8851  8851 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-05 13:16:38.994  8851  8851 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-05 13:16:39.006  1036  2036 I ActivityManager: Killing 8331:com.lge.qremote/u0a112 (adj 15): empty #17
08-05 13:16:39.051  8823  8823 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-05 13:16:39.051  8823  8823 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-05 13:16:39.051  8823  8823 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-05 13:16:39.064  1036  1051 W libprocessgroup: failed to open /acct/uid_10112/pid_8331/cgroup.procs: No such file or directory
,08-05 13:16:39.110  8823  8823 I UEI.SmartControl: --- Selecting new region: 6
,08-05 13:16:39.113  8823  8823 I UEI.SmartControl: Model = LG-D855
08-05 13:16:39.116  8823  8823 D UEI.SmartControl: QS Service created
08-05 13:16:39.135  8823  8823 I UEI.SmartControl: Service initServices...
,08-05 13:16:39.140  8823  8823 D UEI.SmartControl: QS start get config
08-05 13:16:39.192  8823  8823 D UEI.SmartControl: Loading JNI Libs...
,08-05 13:16:39.197  1036  2035 V SIM_STK : Menu title from STK is T-Mobile
08-05 13:16:39.209  4947  8822 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 455 ms] updated apps [took 455 ms] 
,08-05 13:16:39.572  8823  8823 I UEI.SmartControl: Supports setup maps: true
,08-05 13:16:39.579  8823  8823 D UEI.SmartControl: QS start statue = true Error code = 0
,08-05 13:16:39.579  8823  8823 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-05 13:16:39.579  8823  8823 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-05 13:16:39.579  8823  8823 I UEI.SmartControl: ### init IR Blaster...
,08-05 13:16:39.585  8823  8823 D serial_port: Configuring serial port
08-05 13:16:39.591  8823  8823 E UEI.SmartControl: UEIBLaster setting for 616
08-05 13:16:39.591  8823  8823 I UEI.SmartControl: Setting serial record hearder size = 2
08-05 13:16:39.591  8823  8823 I UEI.SmartControl: configuring settings for MAXQ616
08-05 13:16:39.592  8823  8823 I UEI.SmartControl: Get version...,
,08-05 13:16:39.610  8823  8885 D UEI.SmartControl: serial port data available: 21
,08-05 13:16:39.650  8823  8823 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-05 13:16:39.669  8823  8823 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-05 13:16:39.669  8823  8823 I UEI.SmartControl: QS saving settings...
,08-05 13:16:39.675  8823  8823 D UEI.SmartControl: IR Blaster version: 25672567
08-05 13:16:39.692  8823  8885 D UEI.SmartControl: serial port data available: 4
,08-05 13:16:39.725  8823  8823 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-05 13:16:39.733  8823  8823 E UEI.SmartControl: Services init done
08-05 13:16:39.733  8823  8823 D UEI.SmartControl: QS Service init finished
08-05 13:16:39.735  8823  8891 I UEI.SmartControl: Device manager: loading config....
08-05 13:16:39.739  8823  8891 D UEI.SmartControl: ----------- loading internal config...
,08-05 13:16:39.744  8823  8823 D UEI.SmartControl: QS Service version name: 2.1.91
08-05 13:16:39.744  8823  8823 D UEI.SmartControl: QS Service version code: 201091
08-05 13:16:39.746  8823  8823 D UEI.SmartControl: Service requested: Control
08-05 13:16:39.754  8823  8891 E UEI.SmartControl: Loading SETTINGS...
,08-05 13:16:39.758  8823  8823 D UEI.SmartControl: Request IControl service: devices are loaded...
08-05 13:16:39.759  8823  8823 D UEI.SmartControl: Service.onUnbind: IControl
08-05 13:16:39.760  8823  8823 D UEI.SmartControl: Service.onDestroy
08-05 13:16:39.761  8823  8823 D UEI.SmartControl: Lock is in USE false
08-05 13:16:39.761  8823  8823 D UEI.SmartControl: unbind internal service
08-05 13:16:39.763  8823  8823 D serial_port: close(fd = 25)
08-05 13:16:39.766  8823  8823 I UEI.SmartControl: Serial port is closed.
08-05 13:16:39.766  8823  8823 I UEI.SmartControl: Serial port is closed.
08-05 13:16:39.766  8823  8823 D UEI.SmartControl: Blaster closed
08-05 13:16:39.767  8823  8823 D UEI.SmartControl: Shut down QS...
08-05 13:16:39.767  8823  8823 D UEI.SmartControl: Stopping QS lib
08-05 13:16:39.769  8823  8823 D UEI.SmartControl: QS lib stop result = true
08-05 13:16:39.769  8823  8823 D UEI.SmartControl: Stopped QS lib
,08-05 13:16:39.771  8823  8823 D UEI.SmartControl: Stopped file observer...
08-05 13:16:39.771  8823  8823 D UEI.SmartControl: QS shutdown complete
08-05 13:16:39.774  8823  8823 D UEI.SmartControl: QS Service created
08-05 13:16:39.780  8823  8890 I UEI.SmartControl: Notify AllClients services are ready: 11
08-05 13:16:39.781  8823  8890 D UEI.SmartControl: -----service ready thread exits
,08-05 13:16:39.785  8823  8891 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-05 13:16:39.802  8823  8823 I UEI.SmartControl: Service initServices...
08-05 13:16:39.802  8823  8823 D UEI.SmartControl: QS start get config
,08-05 13:16:40.097  8823  8823 I UEI.SmartControl: Supports setup maps: true
,08-05 13:16:40.106  8823  8823 D UEI.SmartControl: QS start statue = true Error code = 0
,08-05 13:16:40.106  8823  8823 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-05 13:16:40.106  8823  8823 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-05 13:16:40.106  8823  8823 I UEI.SmartControl: ### init IR Blaster...
08-05 13:16:40.111  8823  8823 D serial_port: Configuring serial port
08-05 13:16:40.112  8823  8823 E UEI.SmartControl: UEIBLaster setting for 616
08-05 13:16:40.112  8823  8823 I UEI.SmartControl: Setting serial record hearder size = 2
08-05 13:16:40.112  8823  8823 I UEI.SmartControl: configuring settings for MAXQ616
08-05 13:16:40.112  8823  8823 I UEI.SmartControl: Get version...
08-05 13:16:40.128  8823  8899 D UEI.SmartControl: serial port data available: 21
,08-05 13:16:40.154  8823  8823 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-05 13:16:40.155  8823  8823 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-05 13:16:40.157  8823  8823 I UEI.SmartControl: QS saving settings...
,08-05 13:16:40.160  8823  8823 D UEI.SmartControl: IR Blaster version: 25672567
08-05 13:16:40.177  8823  8899 D UEI.SmartControl: serial port data available: 4
,08-05 13:16:40.208  8823  8823 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-05 13:16:40.214  8823  8823 E UEI.SmartControl: Services init done
,08-05 13:16:40.214  8823  8823 D UEI.SmartControl: QS Service init finished
08-05 13:16:40.216  8823  8903 I UEI.SmartControl: Device manager: loading config....
08-05 13:16:40.217  8823  8823 D UEI.SmartControl: QS Service version name: 2.1.91
08-05 13:16:40.217  8823  8823 D UEI.SmartControl: QS Service version code: 201091
08-05 13:16:40.218  8823  8823 D UEI.SmartControl: Service requested: Control
08-05 13:16:40.219  8823  8903 D UEI.SmartControl: ----------- loading internal config...
08-05 13:16:40.228  8823  8903 E UEI.SmartControl: Loading SETTINGS...
08-05 13:16:40.229  8823  8823 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-05 13:16:40.241  1036  1729 I ActivityManager: Killing 8514:com.lge.email/u0a23 (adj 15): empty #17
08-05 13:16:40.242  8823  8903 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-05 13:16:40.248  8823  8902 I UEI.SmartControl: Notify AllClients services are ready: 0
08-05 13:16:40.248  8823  8902 D UEI.SmartControl: -----service ready thread exits
,08-05 13:16:40.304  1036  1052 W libprocessgroup: failed to open /acct/uid_10023/pid_8514/cgroup.procs: No such file or directory
,08-05 13:16:40.308  8823  8823 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@c05645 that was originally bound here
08-05 13:16:40.308  8823  8823 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@c05645 that was originally bound here
08-05 13:16:40.308  8823  8823 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-05 13:16:40.308  8823  8823 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-05 13:16:40.308  8823  8823 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-05 13:16:40.308  8823  8823 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-05 13:16:40.308  8823  8823 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-05 13:16:40.308  8823  8823 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-05 13:16:40.308  8823  8823 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-05 13:16:40.308  8823  8823 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-05 13:16:40.308  8823  8823 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-05 13:16:40.308  8823  8823 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-05 13:16:40.308  8823  8823 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-05 13:16:40.308  8823  8823 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 13:16:40.308  8823  8823 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-05 13:16:40.308  8823  8823 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 13:16:40.308  8823  8823 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 13:16:40.308  8823  8823 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 13:16:40.308  8823  8823 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 13:16:40.308  8823  8823 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-05 13:16:40.309  8823  8823 D UEI.SmartControl: Internal service binding...
08-05 13:16:40.548  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=13.0, 0.0, 0.0  rx=10.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1516985315] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 13:16:40.551  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=13.0, 0.0, 0.0  rx=10.8 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1516985319] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
08-05 13:16:40.551  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 13:16:40.759  8823  8893 D UEI.SmartControl: Internal timer expired: 2
,08-05 13:16:43.574  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=6.5, 0.0, 0.0  rx=5.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1516988342] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 13:16:43.586  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=6.5, 0.0, 0.0  rx=5.4 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:1516988354] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 13:16:43.587  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 13:16:43.975  8823  8834 E UEI.SmartControl: file observer is disposed!
,08-05 13:16:45.208  8823  8904 D UEI.SmartControl: Internal timer expired: 3
,08-05 13:16:45.214  8823  8904 D UEI.SmartControl: unbind internal service
08-05 13:16:45.232  8823  8823 D UEI.SmartControl: Service.onUnbind: IControl
,08-05 13:16:45.237  8823  8823 D UEI.SmartControl: Service.onDestroy
,08-05 13:16:45.237  8823  8823 D UEI.SmartControl: Lock is in USE false
08-05 13:16:45.237  8823  8823 D UEI.SmartControl: unbind internal service
,08-05 13:16:45.238  8823  8823 D serial_port: close(fd = 24)
08-05 13:16:45.242  8823  8823 I UEI.SmartControl: Serial port is closed.
08-05 13:16:45.242  8823  8823 I UEI.SmartControl: Serial port is closed.
08-05 13:16:45.242  8823  8823 D UEI.SmartControl: Blaster closed
08-05 13:16:45.242  8823  8823 D UEI.SmartControl: Shut down QS...
08-05 13:16:45.242  8823  8823 D UEI.SmartControl: Stopping QS lib
08-05 13:16:45.243  8823  8823 D UEI.SmartControl: QS lib stop result = true
08-05 13:16:45.243  8823  8823 D UEI.SmartControl: Stopped QS lib
08-05 13:16:45.243  8823  8823 D UEI.SmartControl: QS shutdown complete
08-05 13:16:46.607  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=3.2, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1516991375] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 13:16:46.610  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=3.2, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1516991378] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 13:16:46.610  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 13:16:48.103  1036  1539 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-05 13:16:48.103  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-05 13:16:48.104  1036  1539 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-05 13:16:48.104  1036  1539 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-05 13:16:48.105  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-05 13:16:48.105  1036  1539 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-05 13:16:49.568  6900  6964 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-05 13:16:49.568  6900  6964 I jxcore-log: 
,08-05 13:16:49.643  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:1516994410] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 13:16:49.677  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:35] from screen [on:0 period:1516994445] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 13:16:49.677  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 13:16:49.890  8917  8917 D AndroidRuntime: 
08-05 13:16:49.890  8917  8917 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-05 13:16:49.896  8917  8917 D AndroidRuntime: CheckJNI is OFF
08-05 13:16:50.049  8917  8917 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-05 13:16:50.066  1036  1093 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-05 13:16:50.067  1036  1093 I ActivityManager: Killing 6900:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-05 13:16:50.148  1036  1981 I WindowState: WIN DEATH: Window{3da018fc u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-05 13:16:50.154  1036  1545 D WifiService: Client connection lost with reason: 4
,08-05 13:16:50.164  1036  1981 D InputDispatcher: Window went away: Window{3da018fc u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-05 13:16:50.286  1036  1093 I ActivityManager:   Force finishing activity ActivityRecord{df34821 u0 com.test.thalitest/.MainActivity t40}
,08-05 13:16:50.306   350   368 E GBMv2   : DFP En is all cleared set to be enabled
,08-05 13:16:50.310  1036  1052 W ActivityManager: Spurious death for ProcessRecord{1747ecf4 6900:com.test.thalitest/u0a118}, curProc for 6900: null
08-05 13:16:50.310  1036  1128 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-05 13:16:50.311  1036  1128 I ActivityManager:   Force finishing activity ActivityRecord{df34821 u0 com.test.thalitest/.MainActivity t40 f}
08-05 13:16:50.311  1036  1128 W ActivityManager: Duplicate finish request for ActivityRecord{df34821 u0 com.test.thalitest/.MainActivity t40 f}
08-05 13:16:50.344  2037  2037 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-05 13:16:50.345  2037  2037 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-05 13:16:50.349  1946  1962 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-05 13:16:50.350  1946  1962 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3a0b476a co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
08-05 13:16:50.352  2037  2037 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-05 13:16:50.353  1946  1961 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-05 13:16:50.353  1946  1961 D SplitWindowPolicy: topRunningActivity=ActivityInfo{c8be45b co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
08-05 13:16:50.354  2037  2124 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,08-05 13:16:50.362  1909  1909 D ActionManagerService: notifyUserLog: 1000003
08-05 13:16:50.363  2037  2037 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-05 13:16:50.371  1036  1390 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-05 13:16:50.371  3859  4857 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
,08-05 13:16:50.375  1604  1604 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-05 13:16:50.388  2508  2625 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-05 13:16:50.391  2000  2000 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-05 13:16:50.392  3859  3859 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-05 13:16:50.395  7858  7858 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-05 13:16:50.395  7858  7858 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-05 13:16:50.451  2037  2037 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-05 13:16:50.456  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-05 13:16:50.461  1604  1649 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-05 13:16:50.461  1604  1649 D KeyguardModel: createShortcutInfo...
08-05 13:16:50.465  2037  2037 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-05 13:16:50.467  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-05 13:16:50.467  1604  1604 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-05 13:16:50.468  2037  2037 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,08-05 13:16:50.471  1604  1649 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-05 13:16:50.471  1604  1649 D KeyguardModel: createShortcutInfo...
08-05 13:16:50.472  1909  1909 D ActionManagerService: notifyUserLog: 1000004
08-05 13:16:50.472  3859  4857 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-05 13:16:50.472  2037  2037 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-05 13:16:50.474  3859  3874 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 13:16:50.476  2037  2037 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-05 13:16:50.476  2037  2037 I GBoardWebViewUtils: , create_time: 1430832262123
08-05 13:16:50.476  2037  2037 I GBoardWebViewUtils: , expire_time: 0
08-05 13:16:50.476  2037  2037 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-05 13:16:50.476  2037  2037 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-05 13:16:50.476  2037  2037 I GBoardWebViewUtils: , display: false
08-05 13:16:50.476  2037  2037 I GBoardWebViewUtils: , animation: false }
08-05 13:16:50.476  2037  2037 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-05 13:16:50.476  2037  2037 I GBoardWebViewUtils: , create_time: 1430832262287
08-05 13:16:50.476  2037  2037 I GBoardWebViewUtils: , expire_time: 0
08-05 13:16:50.476  2037  2037 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-05 13:16:50.476  2037  2037 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-05 13:16:50.476  2037  2037 I GBoardWebViewUtils: , display: false
08-05 13:16:50.476  2037  2037 I GBoardWebViewUtils: , animation: false }
08-05 13:16:50.476  2037  2037 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1470393742816
08-05 13:16:50.476  2037  2037 I GBoardWebViewUtils: , create_time: 1470393743569
08-05 13:16:50.476  2037  2037 I GBoardWebViewUtils: , expire_time: 0
08-05 13:16:50.476  2037  2037 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-05 13:16:50.476  2037  2037 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-05 13:16:50.476  2037  2037 I GBoardWebViewUtils: , display: false
08-05 13:16:50.476  2037  2037 I GBoardWebViewUtils: , animation: false }
08-05 13:16:50.479  1604  1649 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-05 13:16:50.480  1604  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 13:16:50.486  1872  1872 D SplitUIManager: split_name #11 / not available #0
08-05 13:16:50.487  1872  1872 D SplitUIService: removed split : 
08-05 13:16:50.491  1604  1649 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-05 13:16:50.493  1604  1649 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 13:16:50.496  2037  8948 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-05 13:16:50.497  1604  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-05 13:16:50.497  1604  1649 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-05 13:16:50.501  2037  2037 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-05 13:16:50.502  1604  1649 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-05 13:16:50.502  1604  1649 D KeyguardModel: createShortcutInfo...
08-05 13:16:50.509  1604  1649 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-05 13:16:50.509  1604  1649 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 13:16:50.514  4947  4947 I art     : Explicit concurrent mark sweep GC freed 15471(887KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 2.717ms total 162.180ms
,08-05 13:16:50.515  1604  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 13:16:50.516  1604  1649 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-05 13:16:50.517  8280  8280 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-05 13:16:50.525  1819  1819 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-05 13:16:50.525  1604  1649 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-05 13:16:50.525  1604  1649 D KeyguardModel: createShortcutInfo...
08-05 13:16:50.534  4830  4830 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-05 13:16:50.534  4830  4830 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-05 13:16:50.535  4830  4830 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-05 13:16:50.535  4830  4830 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-05 13:16:50.535  4830  4830 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 13:16:50.535  4830  4830 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 13:16:50.535  4830  4830 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 13:16:50.535  4830  4830 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 13:16:50.535  4830  4830 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 13:16:50.535  4830  4830 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 13:16:50.535  4830  4830 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 13:16:50.535  4830  4830 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 13:16:50.536  1604  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 13:16:50.536  1604  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-05 13:16:50.536  1604  1649 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-05 13:16:50.536  1604  1649 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-05 13:16:50.542  1604  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 13:16:50.543  1604  1649 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-05 13:16:50.544  1604  1649 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-05 13:16:50.544  1604  1649 D KeyguardModel: createShortcutInfo...
08-05 13:16:50.556  1036  1036 I art     : Explicit concurrent mark sweep GC freed 29119(1868KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 7.142ms total 214.339ms
,08-05 13:16:50.557  1036  1128 I art     : WaitForGcToComplete blocked for 201.348ms for cause Explicit
08-05 13:16:50.558  2154  2154 I ConfigService: onCreate
08-05 13:16:50.563  2037  2037 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-05 13:16:50.566  1036  1092 W InputMethodInfo: Duplicated subtype definition found: , voice
08-05 13:16:50.572  1036  1944 V SIM_STK : Menu title from STK is T-Mobile
08-05 13:16:50.572  1036  1944 V SIM_STK : Menu title from STK is T-Mobile
,08-05 13:16:50.578  1036  1926 V SIM_STK : Menu title from STK is T-Mobile
08-05 13:16:50.583  2154  2154 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-05 13:16:50.583  2154  2154 I ConfigService: onBind returning update interface
08-05 13:16:50.591  2037  2037 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-05 13:16:50.594  1819  1819 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-05 13:16:50.596  2154  2154 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-05 13:16:50.596  2154  2154 I ConfigService: onBind returning config service
08-05 13:16:50.597  1604  1604 D KeyguardModel: handleShortcutListChanged...
08-05 13:16:50.597  1604  1604 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-05 13:16:50.598  1872  1872 D SplitUIManager: split_name #11 / not available #0
08-05 13:16:50.598  1872  1872 I SplitUIService: split app #11
08-05 13:16:50.600  1604  1649 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-05 13:16:50.600  1604  1649 D KeyguardModel: createShortcutInfo...
08-05 13:16:50.601  1819  1819 I ConfigFetchService: service connected
08-05 13:16:50.602  1604  1649 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-05 13:16:50.602  1604  1649 D KeyguardModel: createShortcutInfo...
08-05 13:16:50.603  1604  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 13:16:50.603  1604  1649 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-05 13:16:50.604  1604  1649 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-05 13:16:50.604  1604  1649 D KeyguardModel: createShortcutInfo...
08-05 13:16:50.606  1819  8952 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-05 13:16:50.607  1604  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 13:16:50.607  1604  1649 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-05 13:16:50.607  2154  2154 I ConfigService: onDestroy
08-05 13:16:50.609  1604  1649 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-05 13:16:50.609  1604  1649 D KeyguardModel: createShortcutInfo...
08-05 13:16:50.610  1604  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 13:16:50.610  1604  1649 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-05 13:16:50.611  1604  1649 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-05 13:16:50.611  1604  1649 D KeyguardModel: createShortcutInfo...
08-05 13:16:50.628  1036  1890 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-05 13:16:50.630  7858  7858 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-05 13:16:50.630  7858  7858 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-05 13:16:50.630  7858  7858 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-05 13:16:50.630  7858  7858 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-05 13:16:50.630  7858  7858 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-05 13:16:50.630  7858  7858 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 13:16:50.630  7858  7858 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-05 13:16:50.630  7858  7858 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-05 13:16:50.630  7858  7858 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-05 13:16:50.630  7858  7858 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 13:16:50.630  7858  7858 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-05 13:16:50.634  7217  7217 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-05 13:16:50.635  5801  8958 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-05 13:16:50.646  1604  1604 D KeyguardModel: handleShortcutListChanged...
08-05 13:16:50.646  1604  1604 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-05 13:16:50.653  1036  2035 V SIM_STK : Menu title from STK is T-Mobile
,08-05 13:16:50.653   344   429 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-05 13:16:50.654  3251  8961 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-05 13:16:50.667  1036  1729 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8962 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-05 13:16:50.670  2379  8960 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-05 13:16:50.680  1819  8972 I PeopleContactsSync: CP2 sync disabled
,08-05 13:16:50.686  1036  1036 D administrator: Handling package changes for user 0
08-05 13:16:50.688  1819  5143 I Icing   : doRemovePackageData com.test.thalitest
,08-05 13:16:50.706  1819  8959 W GmsApplication: Using Auth Proxy for data requests.
08-05 13:16:50.711  1819  8959 W GmsApplication: Using Auth Proxy for data requests.
,08-05 13:16:50.724  8962  8962 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 13:16:50.726  8962  8962 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 13:16:50.727  8962  8962 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 13:16:50.727  8962  8962 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 13:16:50.757  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-05 13:16:50.757  2037  2037 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-05 13:16:50.757  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-05 13:16:50.757  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-05 13:16:50.759  1036  1578 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
08-05 13:16:50.761  2037  2037 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 13:16:50.763  2037  2037 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-05 13:16:50.764  2037  2037 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-05 13:16:50.765  2037  2037 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-05 13:16:50.766  2037  2037 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-05 13:16:50.780  1036  1110 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{38c64b22 u0 com.lge.launcher2/.Launcher t39} time:381146
08-05 13:16:50.784  2037  2037 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-05 13:16:50.785  2037  2037 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 13:16:50.787  2037  2262 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-05 13:16:50.787  2037  2262 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-05 13:16:50.799  2037  2037 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-05 13:16:50.800  2037  2037 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-05 13:16:50.800  2037  2037 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-05 13:16:50.808  2037  2037 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-05 13:16:50.809  2653  2653 D [Concierge]Service: onStartCommand(). Type : 8
08-05 13:16:50.809  2653  2653 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-05 13:16:50.810  2653  2653 D [Concierge]Service: Update widget ID : 11
08-05 13:16:50.811  2037  2037 D [Concierge]WidgetView: change position of spinner
08-05 13:16:50.812  2037  2037 I [Concierge]WidgetView: initWebView(). Time : 1470395810812
08-05 13:16:50.812  2653  2653 D [Concierge]Service: onStartCommand(). Type : 0
,08-05 13:16:50.820  1819  8983 I art     : Explicit concurrent mark sweep GC freed 34589(2MB) AllocSpace objects, 28(448KB) LOS objects, 51% free, 30MB/62MB, paused 838us total 25.539ms
08-05 13:16:50.820  1819  1831 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-05 13:16:50.820  1819  1831 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-05 13:16:50.821  1819  1831 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-05 13:16:50.825  2037  2037 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 64305700
08-05 13:16:50.825  2037  2037 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-05 13:16:50.825  2037  2037 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-05 13:16:50.828  2037  2037 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1aa23b36
08-05 13:16:50.828  2037  2037 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-05 13:16:50.830  2037  2037 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-05 13:16:50.830  2037  2037 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-05 13:16:50.835  2037  2037 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-05 13:16:50.836  2037  2037 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-05 13:16:50.836  2037  2037 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-05 13:16:50.836  2037  2037 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470395457568, New one : 1470395810812
08-05 13:16:50.836  2037  2037 D [Concierge]WidgetView: Unregister all receivers
08-05 13:16:50.837  2037  2037 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-05 13:16:50.840  2037  2037 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 13:16:50.840  8962  8962 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-05 13:16:50.841  2037  2037 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-05 13:16:50.842  2037  2037 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-05 13:16:50.843  2037  2037 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-05 13:16:50.844  2037  2037 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-05 13:16:50.846  2037  2037 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-05 13:16:50.846  2037  2037 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 13:16:50.847  2037  2037 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-05 13:16:50.855  1036  1128 I art     : Explicit concurrent mark sweep GC freed 9503(480KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.728ms total 296.704ms
08-05 13:16:50.855  8962  8962 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-05 13:16:50.880  8962  8962 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-05 13:16:50.899  2037  2037 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-05 13:16:50.907  2037  2037 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-05 13:16:50.907  2037  2037 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-05 13:16:50.908  2037  2037 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 13:16:50.912  8962  8962 D LgDataFeature: LgDataFeature() Constructor: none
08-05 13:16:50.913  8962  8962 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 13:16:50.928  2037  2037 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3d9405b9 time:381294
08-05 13:16:50.933  8917  8917 D AndroidRuntime: Shutting down VM
,08-05 13:16:50.953  1036  1128 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8989 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-05 13:16:50.972  1036  1092 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 13:16:50.979  1036  1092 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-05 13:16:50.982  2037  2037 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-05 13:16:50.991  8962  8962 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-05 13:16:51.001  1036  1890 I ActivityManager: Killing 8229:com.lge.formmanager/u0a26 (adj 15): empty #17
08-05 13:16:51.056  2037  2037 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-05 13:16:51.074  2000  2000 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-05 13:16:51.074  2000  2000 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-05 13:16:51.075  1036  1052 W libprocessgroup: failed to open /acct/uid_10026/pid_8229/cgroup.procs: No such file or directory
08-05 13:16:51.075  2000  2000 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-05 13:16:51.081  8280  8280 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-05 13:16:51.091  2037  2922 I GBoardtInterface: onReloaded()
,08-05 13:16:51.092  2037  2037 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-05 13:16:51.110  1036  2036 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=9008 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-05 13:16:51.110  1036  2036 I ActivityManager: Killing 8473:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-05 13:16:51.111  3859  3874 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 13:16:51.144  1036  1576 W libprocessgroup: failed to open /acct/uid_10046/pid_8473/cgroup.procs: No such file or directory
,08-05 13:16:51.148  3859  4850 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 13:16:51.153  1909  1909 D ActionManagerService: notifyUserLog: 1000001
08-05 13:16:51.154  3859  4857 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-05 13:16:51.154  3859  4857 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-05 13:16:51.157  1909  1909 D ActionManagerService: notifyUserLog: 1000001
08-05 13:16:51.158  3859  4857 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-05 13:16:51.158  3859  4857 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-05 13:16:51.158  3859  4857 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-05 13:16:51.158  3859  4857 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-05 13:16:51.158  3859  3874 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-05 13:16:51.161  2037  2037 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-05 13:16:51.161  2037  2037 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-05 13:16:51.162  2037  2037 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-05 13:16:51.162  2037  2037 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-05 13:16:51.164  2037  2037 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-05 13:16:51.164  2037  2037 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-05 13:16:51.185  9008  9008 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-05 13:16:51.185  9008  9008 W LG Account v2.2: No ProfileInfo entries
08-05 13:16:51.185  9008  9008 I LG Account v2.2: isEnabled: false
08-05 13:16:51.186  9008  9008 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-05 13:16:51.186  9008  9008 I Feature : [Lifetracker]Country: EU
08-05 13:16:51.186  9008  9008 I Feature : [Lifetracker]Operator: OPEN
08-05 13:16:51.186  9008  9008 I Feature : [Lifetracker]Ranking support: false
08-05 13:16:51.186  9008  9008 I Feature : [Lifetracker]Comfort support: false
08-05 13:16:51.186  9008  9008 I Feature : [Lifetracker]Accessory: true
08-05 13:16:51.186  9008  9008 I Feature : [Lifetracker]Health device: true
08-05 13:16:51.186  9008  9008 I Feature : [Lifetracker]Extra Pedometer: false
08-05 13:16:51.186  9008  9008 I Feature : [Lifetracker]Blood glucose device: false
08-05 13:16:51.186  9008  9008 I Feature : [Lifetracker]Device Number: 3
08-05 13:16:51.186  9008  9008 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED

```
